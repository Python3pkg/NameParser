##Name Parser:

Name Parser, basit bir isim ayrıştırıcıdır. Yani örneğin;

Ali Opcode GOREN adını girdiğiniz zaman size hangisinin isim hangisinin soyisim olduğunu gösterir.

Örneğin;

~~~~{.python}
from name import NameParser

np = NameParser()

print(np.getName('Benjamin Franklin C-Note'))
~~~~

şeklinde kullanırsak şöyle bir çıktı alırız:

~~~~{.shell}
Name: Benjamin
Name: Franklin
Surname: C-Note
~~~~

##Kurulum:

~~~~{.shell}
python setup.py install
~~~~

komutunu girmeniz yeterlidir. Bir hata görmeniz durumunda söylerseniz iyi olurdu valla.
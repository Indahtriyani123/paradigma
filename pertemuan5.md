# paradigma
praktikum paradigma bahasa pemrograman
# paradigma
praktikum paradigma bahasa pemrograman

>>> class Complex:
	def __init__(self, realpart, imagpart):
		self.r = realpart
		self.i = imagpart		
>>> x = Complex(3.0, -4.5)
>>> x.r, x.i
(3.0, -4.5)

program diatas adalah salah satu contoh pemrograman berorientasi objek dimana didalamnya mempunyai  class dan objek. class pada program diatas bernama complex, def adalah salah satu function yang ada pada pemrograman python, init  merupakan method yang pertama kali di jalankan atau di proses sebelum method-method yang lainnya dan method init berguna untuk melakukan inisialisasi pembuatan object dari class. self adalah variabel yang menyatakan kelas tersebut. sedangkan realpart dan imagpart adalah nama objek dari kelas tersebut, self.r = realpart adalah objek yang akan dipanggil merupakan objek realpart begitupun pada self.i = imagpart maka objek yang dipanggil adalah objek imagpart. kemudian x adalah variabel lokal yang isinya (3.0 , -4.5) lalu dipanggil dengan kode x.r yang artinya variabel x berisi objek r dan x.i yang artinya variabel x berisi objek i.


>>> class Dog:
	 kind = 'canine'
	 def __init__(self, name):
		 self.name = name

		 
>>> d = Dog('Fido')
>>> e = Dog('Buddy')
>>> d.kind
'canine'
>>> e.kind
'canine'
>>> d.name
'Fido'
>>> e.name
'Buddy'

program diatas memiliki nama kelas dog
kind adalah objek yang isinya string yaitu 'canine'
def adalah salah satu function pada pemrograman python
init adalah method yang pertama kali di jalankan atau di proses sebelum method-method yang lainnya dan method init berguna untuk melakukan inisialisasi pembuatan object dari class
self adalah variabel yang menyatakan kelas tersebut
name adalah nama objek pada kelas tersebut
self.name=name maksudnya adalah dari variabel self memanggil objek name
d adalah variabel lokal yang berisi 'fido'
e adalah variabel lokal yang berisi 'buddy'
d.kind maksudnya adalah memanggil variabel d berisi objek kind
e.kind maksudnya adalah memanggil variabel e berisi objek kind
d.name maksudnya adalah memanggil variabel d dari objek name dimana objek name isinya adalah kosong
e.name maksudnya adalah memanggil variabel e dari objek name dimana objek name isinya adalah kosong

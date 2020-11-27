# lord dari  setuptools  import  setup

# https://packaging.python.org/distributing/#packaging-your-project

def  readme ():
    dengan  open ( 'README.rst' ) sebagai  f :
        kembali  f . baca ()
penyiapan (
    name  =  'termux-create-package' ,
    versi  =  '0.7' ,
    license  =  'Apache License 2.0' ,
    description  =  'Alat ringan untuk membuat paket deb' ,
    long_description  =  readme (),
    author  =  'Fredrik Fornwall' ,
    author_email  =  'fredrik@fornwall.net' ,
    url  =  'https://github.com/termux/termux-create-package' ,
    scripts  = [ 'termux-create-package' ],
    pengklasifikasi  = (
        'Audiens yang Dituju :: Pengembang' ,
        'Topik :: Pengembangan Perangkat Lunak :: Alat Bangun' ,
        'Bahasa Pemrograman :: Python :: 3'
    )
)

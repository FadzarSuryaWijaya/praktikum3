# Praktikum 3
> sebagai Mata Kuliah Bahasa Pemrograman | Universitas Pelita Bangsa

## Laporan Praktikum
### Latihan 1

    # penggunaan end
    print('A', end='')
    print('B', end='')
    print('C', end='')
    print()
    print('X', end='')
    print('Y', end='')
    print('Z', end='')

    # Penggunaan separator
    w, x, y, z = 10, 15, 20, 25
    print(w, x, y, z)
    print(w, x, y, z, sep=',')
    print(w, x, y, z, sep='')
    print(w, x, y, z, sep=':')
    print(w, x, y, z, sep='-----') 

    # string format
    print(0, 10**0)
    print(1, 10**1)
    print(2, 10**2)
    print(3, 10**3)
    print(4, 10**4)
    print(5, 10**5)
    print(6, 10**6)
    print(7, 10**7)
    print(8, 10**8)
    print(9, 10**9)
    print(10, 10**10) 
 
    # string format
    print('{0:>3} {1:>16}'.format(0, 10**0))
    print('{0:>3} {1:>16}'.format(1, 10**1))
    print('{0:>3} {1:>16}'.format(2, 10**2))
    print('{0:>3} {1:>16}'.format(3, 10**3))
    print('{0:>3} {1:>16}'.format(5, 10**5))
    print('{0:>3} {1:>16}'.format(6, 10**6))
    print('{0:>3} {1:>16}'.format(7, 10**7))
    print('{0:>3} {1:>16}'.format(8, 10**8))
    print('{0:>3} {1:>16}'.format(9, 10**9))
    print('{0:>3} {1:>16}'.format(10, 10**10))

### Latihan2

    a=input("masukkan nilai a:")
    b=input("masukkan nilai b:")
    print("Variable a=",a)
    print("Variable b=",b)
    print("Hasil penggabungan {0}&{1}={2}".format(a, b, a+b))

    # konversi nilai variable
    a=int(a)
    b=int(b)
    print("Hasil penjumlahan {0}+{1}={2}".format(a, b, a+b))
    print("Hasil pembagian {0}/{1}={2:.2f}".format(a, b, a/b))

### Latihan3

    print('##  Program Python Belah Ketupat Bintang  ##')
    print('Hello ini script python')
    print('============================================')
    print()
 
    lebar_belah_ketupat = int(input('Input lebar belah ketupat: '))
    print()
 
    for i in range(lebar_belah_ketupat):
      for j in range(lebar_belah_ketupat-i):
        print(' ',end='')
     
      for k in range(i+1):
        print('* ',end='')
      print()

    for i in range(1,lebar_belah_ketupat):
      for j in range(i+1):
        print(' ',end='')
     
      for k in range(lebar_belah_ketupat-i):
        print('* ',end='')
      print()

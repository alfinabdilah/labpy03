PENJELASAN TENTANG LATIHAN 1, LATIHAN 2 DAN PROGRAM 1

LATIHAN 1   
  1. Masukan perintah "n=int(input("Masukan nilai N:"))" untuk nanti menampilkan nilai N atau seberapa kali perulangan ini dilakukan.
  2. masukan perintah "import random" untuk mengimport nilai random yang nantinya akan digunakan oleh data.
  3. Masukan perintah "for i in range(n):" untuk membuat perulangan dengan range atau dengan sebanyak(N).
  4. Masukan perintah "data=random.uniform(0,0.5)" untuk mendefinisikan bahwa data random dimulai dari nilai awal (0) dan nilai        akhir (0,5)
  5. Masukan perintah "i+=1" agar i dimulai dari (1) karena perulangan secara default dimulai dari (0).
  6. Masukan perintah "print("Data ke:",i,"==>",(data))" untuk menampilkan hasil.
![latihan1](https://user-images.githubusercontent.com/56971806/68416809-c5fc7e00-01c7-11ea-961f-b6aaac664b03.png)

LATIHAN 2
  1. Masukan perintah "n=1"
  2. Masukan perintah "max=0" nantinya ini akan digunakan untuk mencari nilai tertinggi.
  3. Gunakan fungsi "while n !=0:" untuk membuat perulangan yang berhenti ketika n=0.
  4. Gunakan fungsi "if n > max:" untuk mendefinisikan bahwa perulangan terjadi jika n>max atau nilainya diatas 10.
  5. "max=n" adalah fungsi untuk mendefinisikan bahwa max=n.
  6. Untuk menampilkan hasil gunakan fungsi "n=int(input("masukan bilangan:"))"
  7. Lalu masukan printah "print("bilangan terbesar adalah",max)"untuk menunjukan bilangan terbesar pada data dan ketika nilai n=0.
![latihan2](https://user-images.githubusercontent.com/56971806/68416812-c6951480-01c7-11ea-9a65-b10de6d6fbbc.png)

PROGRAM 1

  1. Masukan nilai awal atau modal awal untuk nantinya di masukan ke dalam fungsi if "a=100000000"
  2. Lalu masukan fungsi "for i in range(1,9):" untukmembuat perulangan pada nilai awal (1) dan nilai akhir (9) atau dalam range(1,9)
  3. Gunakan perintah dibawah ini untuk menghitung laba di bulan pertama dan kedua,
    if(i>=1 and i<=2):
        b=a*0
        print ("laba bulan ke-",i,":",b)
        
  4. Gunakan perintah dibawah ini untuk menghitung laba di bulan ketiga dan keempat,
    if(i>=3 and i<=4):
        c=a*0.1
        print ("laba bulan ke-",i,":",c)
        
  5. Gunakan perintah dibawah ini untuk menghitung laba di bulan kelima, keenam dan ketujuh,
    if(i>=5 and i<=7):
        d=a*0.5
        print ("laba bulan ke-",i,":",d)
        
  6. Gunakan perintah dibawah ini untuk menghitung laba di bulan kedelapan,
    if(i==8):
        e=a*0.2
        print ("laba bulan ke-",i,":",e)
        
  7. Lalu hitung total dengan menggunakan perintah "total = b+b+c+c+d+d+d+e"
  8. Lalu masukan perintah "print("total:",total)" untuk melihat hasil total Laba.
![program1](https://user-images.githubusercontent.com/56971806/68416813-c6951480-01c7-11ea-9db2-51dd7edcc676.png)

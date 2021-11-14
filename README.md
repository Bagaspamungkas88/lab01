# lab 2 lathian 1


pada lab 2 latihan 1 saya diberi soal sebagai berikut :

untuk mengerjakan saya memasukan syntax dibawah


N=int(input("banyaknya data = "))
if N>0:
    i=1
    x=int(input("data ke -"+str(i)+"="))
    max=x;total=x
    for i in range(2,N+1):
        x=int (input("data ke -"+str(i)+"="))
        total+=x
        if max<x:
            max=x

    print("bilangan terbesar =",max)
dari proses diatas saya mendapatkan output

! [img] (gambar/output1.png)


#  lab2 latihan 2
untuk mengerjakan saya memasukan syntax dibawah


data = []
for i in range (5):
    x =int(input("masukan bilangan : "))
    data.append(x)
print('data sebelum diurutkan: ',data)
list.sort(data)
print('data setelah diurutkan: ',data)
dari proses diatas saya mendapat output


! [img](gambar/output2.png)

#  lab3 lathian 1
untuk mengerjakan saya memasukan syntax dibawah


baris = 10
kolom = baris

for bar in range(baris):
    for col in range(kolom):
        tab = bar+col
        print("{0:>5}".format(tab), end='')
    print()


dari proses diatas saya mendapatkan output

! [img] (gambar/output3.png)

# lab3 lathian 2

untuk mengerjakan soal diatas saya menggunakan syntax dibawah

    import random
    print(40*"=")
    print("Bilangan acak yang lebih kecil dari 0,5")
    print(40*"=")
    jum = int( input("Masukan nilai n : "))
    i = 0
    for i in range(jum):
        i += 1
        angkaDec = random.uniform(0, 0.5)
        print("Data ke", i, " = ", angkaDec)


dari proses diatas saya mendapatkan output dibawah

! [img] (gambar/output4.png)


terima kasih
# pertemuan7
# Mencari angka terbesar dari 3 bilangan
<P> # Deklarasikan variable X,Y,Z sebagai inputan dengan tipe data integer </P>
<P>x = int(input("masukan nilai x:"))</P>
<P>y = int(input("masukan nilai y:"))</P>
<P>z = int(input("masukan nilai z:"))</P>
<P># Gunakan Fungsi if,elif,else</P>
<p>if x > y and x > z:</p>
        <P>print("X adalah yang terbesar")</P>
<P>elif y > x and y > z:</P>
        <p>print("Y adalah yang terbesar")</p>
<p>else :</p>
        <p>print("Z adalah yang terbesar")</p>
        
![gambar](dokumentasi/1.png)

### Output
#### X bilangan terbesar
<P>masukan nilai x:112</P>
<p>masukan nilai y:50</p>
<P>masukan nilai z:78</P>
<p>X yang terbesar, karena nilai X adalah: 112</p>

![gambar](dokumentasi/x.png)
#### Y bilangan terbesar
<P>masukan nilai x:18</P>
<p>masukan nilai y:302</p>
<P>masukan nilai z:283</P>
<p>Y yang terbesar, karena nilai Y adalah: 302</p>

![gambar](dokumentasi/y.png)
#### Z bilangan terbesar
<P>masukan nilai x:29</P>
<p>masukan nilai y:12</p>
<P>masukan nilai z:78</P>
<p>Z yang terbesar, karena nilai Z adalah: 78</p>

![gambar](dokumentasi/z.png)
### Flowchart
![gambar](dokumentasi/fc.png)


## LATIHAN 1
<p># Deklarasikan variable X dan Y sebagai inputan dengan tipe data integer</p>
<p>x = int (input("masukan nilai x:"))</p>
<p>y = int (input("masukan nilai y:"))</p>
<p># Gunakan Fungsi if dan else</p>
<p>if x> y:</p>
    <p>print("X yang terbesar, karena Nilai X adalah:",x)</p>
<p>else :</p>
    <p>print("Y yang terbesar, karena Nilai Y adalah:",y)</p>
    
![gambar](dokumentasi/5.png)
### Output
<P>masukan nilai x:17</P>
<P>masukan nilai y:19</P>
<P>Y yang terbesar, Karena nilai Y adalah: 19</P>

![gambar](dokumentasi/besar1.png)

## LATIHAN 2
<p># Deklarasikan variable X,Y,Z sebagai inputan dengan tipe data integer</p>
<p>x = int(input("Bilangan ke 1:"))</p>
<p>y = int(input("Bilangan ke 2:"))</p>
<p>z = int(input("Bilangan ke 3:"))</p>
<p>data = [x, y, z]</p>
<p>list.sort(data)</p>
<p>print ("urutan data dari yang terkecil:",data)</p>

![gambar](dokumentasi/7.png)
### Output
<p>Bilangan ke 1:39</p>
<p>Bilangan ke 2:100</p>
<p>Bilangan ke 3:28</p>
<p>urutan data dari yang terkecil: [28, 39, 100]</p>

![gambar](dokumentasi/sort1.png)

## LATIHAN 3
<p>baris = 10</p>
<p>kolom = baris</p>
<p>for bar in range(baris):</p>
    <p>for col in range(kolom):</p>
      <p>tab= bar+col</p>
      <p>print("{0:>5}".format(tab), end=")</p>
    <p>print()</p>
    
![gambar](dokumentasi/9.png)
### Output
![gambar](dokumentasi/nested1.png)

## LATIHAN 4
<p>import random</p>
<p>print("\t= Bilangan acak yang lebih kecil dari 0,5 =")</p>
<p>jum = int( input("Masukan nilai: "))</p>
<p>i = 0</p>
<p>while i in range(jum):</p>
<P>i += 1</P>
<p>angkarandom = random.uniform(0,0.5)</p>
<p>print("Bilangan ke :", i, " : ", angkarandom)</p>

![gambar](dokumentasi/11.png)
### Output
<P>=Bilangan acak yang lebih kecil dari 0,5=</P>
<p>Masukan nilai: 4</p>
<p>Bilangan ke : 1 : 0.04082942561795605</p>
<p>Bilangan ke : 2 : 0.4051038920360236</p>
<p>Bilangan ke : 3 : 0.34840141893120163</p>
<p>Bilangan ke : 4 : 0.016989630897285612</p>

![gambar](dokumentasi/random1.png)









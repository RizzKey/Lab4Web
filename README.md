# Praktikum 4 - Pemrograman web

```
   Fitrah Rizki Ardiansyah
   311910465
   TI.19.A.2
```   
   
# LANGKAH 1
# Membuat dokumen HTML dengan nama file lab4_box.html. Setelah itu buat struktur dasar HTML
![image](https://user-images.githubusercontent.com/56240954/115428298-73cce280-a22c-11eb-8802-5c337a6b9dab.png)

# LANGKAH 2
# Membuat box element dengan tag div
![image](https://user-images.githubusercontent.com/56240954/115428388-8d6e2a00-a22c-11eb-9d1a-864739daeb7f.png)

# LANGKAH 3 
# Tambahkan deklarasi CSS pada head untuk membuat float elemen
![image](https://user-images.githubusercontent.com/56240954/115428559-b393ca00-a22c-11eb-81ec-d86913467685.png)

# LANGKAH 4
# Mengatur Clearfix Element. Clearfix digunakan untuk mengatur element setelah float element
![image](https://user-images.githubusercontent.com/56240954/115428698-d9b96a00-a22c-11eb-918d-80fff50edfe0.png)

# Membuat Layout Sederhana

# LANGKAH 1
Buat folder baru dengan nama ```lab4_layout```, kemudian buatlah file baru didalamnya dengan nama ```home.html```, dan file css dengan nama
![image](https://user-images.githubusercontent.com/56240954/115429169-59dfcf80-a22d-11eb-8d47-61c076a66db2.png)

Kemudian coding ```home.html```
![image](https://user-images.githubusercontent.com/56240954/115429421-96abc680-a22d-11eb-8210-c035ccaa2d22.png)
Buka file ```home.html``` pada web browser
![image](https://user-images.githubusercontent.com/56240954/115429598-c0fd8400-a22d-11eb-9f86-8ebc33374ce8.png)

# LANGKAH 2
# Mengatur Navigasi pada CSS
![image](https://user-images.githubusercontent.com/56240954/115429746-e7232400-a22d-11eb-843f-465300ebfc07.png)

# LANGKAH 2
# Membuat Hero Panel
 Tambahkan Coding pada ```home.html``` 
 ``` <section id="hero">
    <h1>Hello World!</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
elit, iaculis innisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
pretium ac.</p>
    <a href="home.html" class="btn btn-large">Learn more &raquo;</a>
</section>
```
Tambahkan Coding pada ```style.css```
``` /* Hero Panel */
#hero {
    background-color: #e4e4e5;
    padding: 50px 20px;
    margin-bottom: 20px;
}
#hero h1 {
    margin-bottom: 20px;
    font-size: 35px;
}
#hero p {
    margin-bottom: 20px;
    font-size: 18px;
    line-height: 25px;
}
```
![image](https://user-images.githubusercontent.com/56240954/115430366-80ead100-a22e-11eb-90ff-0f5c7fb959ee.png)
Hasilnya
![image](https://user-images.githubusercontent.com/56240954/115430453-965ffb00-a22e-11eb-96c8-80fea5c01888.png)

# LANGKAH 3
# Mengatur Layout Main dan Sidebar
![image](https://user-images.githubusercontent.com/56240954/115430598-b394c980-a22e-11eb-9edd-8994168c2ee0.png)

# LANGKAH 4
# Membuat Sidebar Widget
![image](https://user-images.githubusercontent.com/56240954/115430759-d7f0a600-a22e-11eb-98c3-05a3e54e3e3b.png)
Hasilnya
![image](https://user-images.githubusercontent.com/56240954/115435251-d8d80680-a233-11eb-9ffc-94fbec8587ee.png)

# LANGKAH 5
# Selanjutnya mengatur tampilan footer. Tambahkan CSS untuk footer
``` 
/* footer */
footer {
    clear:both;
    background-color:#1d1d1d;
    padding:20px;
    color:#eee;
}
```
![image](https://user-images.githubusercontent.com/56240954/115435452-0a50d200-a234-11eb-9684-019d5e0e22d9.png)

# LANGKAH 6
# Menambahkan Elemen lainnya pada Main Content
![image](https://user-images.githubusercontent.com/56240954/115435586-31a79f00-a234-11eb-89b9-004944773180.png)
Hasilnya
![image](https://user-images.githubusercontent.com/56240954/115435675-45eb9c00-a234-11eb-882e-8109ecf24a1b.png)

# LANGKAH 7
# Selanjutnya membuat content artikel
![image](https://user-images.githubusercontent.com/56240954/115435805-6e739600-a234-11eb-9a35-235df81337a3.png)
Hasilnya
![image](https://user-images.githubusercontent.com/56240954/115435872-7fbca280-a234-11eb-8f97-a51e501fe14a.png)

# TUGAS
# 1. Tambahkan Layout untuk menu About

   Buat file HTML baru dengan ```nama about.html```, dan buat single layout yang berisi deskripsi, portfolio, dll

```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="container">
        <header>
            <h1>About Me</h1>
        </header>
        <nav>
            <a href="home.html" class="active">Home</a>
            <a href="artikel.html">Artikel</a>
            <a href="about.html">About</a>
            <a href="kontak.html">Kontak</a>
        </nav>
        <section id="about">
            <div class="row">
                <img src="venosw.JPG" title="Fitrah Rizki Ardiansyah" alt="Veno Setyoaji Wiratama" class="image-circle" width="200" style="float: left; border: 2px solid black;">
                <h1>Veno Setyoaji Wiratama</h1>
                <p>Nama saya Fitrah Rizki Ardiansyah, Saya adalah seorang mahasiswa Universitas Pelita Bangsa Jurusan Teknik Informatika. Saya lahir di Jakarta, 22 Maret 2001.
                </p>
            </div>
        </section>
    </div>
</body>
</html>
```
Tambahkan Coding pada style.css
```
/* About Panel */
#about{
    background-color: #e4e4e5;
    padding: 50px 20px;
    margin-bottom: 20px;
}
#about h1 {
    margin-bottom: 10px;
    font-size: 35px;
    position: relative;
    left: 15px;
}
#about p {
    margin-bottom: 20px;
    font-size: 18px;
    padding: 30px;
    line-height: 25px;
    position: relative;
    left: 15px;
}
```
![image](https://user-images.githubusercontent.com/56240954/115437108-f908c500-a235-11eb-8bd9-42f2487cc0d1.png)
Hasilnya
![image](https://user-images.githubusercontent.com/56240954/115437176-0f168580-a236-11eb-8bc4-2bf8fc900645.png)

# 2. Tambahkan layout untuk menu Contact
Buat file HTML baru dengan ```nama kontak.html```, dan buat form yang berisi: nama, email, message, dl
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="container">
        <header>
            <h1>Contact Me</h1>
        </header>
        <nav>
            <a href="home.html" class="active">Home</a>
            <a href="artikel.html">Artikel</a>
            <a href="about.html">About</a>
            <a href="kontak.html">Kontak</a>
        </nav>
        <section id="kontak">
            <div class="login">
                <input type="text" placeholder="Your Name" class="input">
                <input type="text" placeholder="Your Email Address" class="input">
            </div>

            <div class="subject">
                <input type="text" placeholder="Subject" class="input">
            </div>

            <div class="msg">
                <textarea cols="35" rows="10" class="area" placeholder="Your Message" class="input"></textarea>
            </div>

            <button type="submit"> Send </button>

        </section>
    </div>
</body>
</html>

    Tambahkan Coding pada style.css

/* Kontak Panel */
#kontak{
    background-color: #e4e4e5;
    padding: 20px 20px;
    margin-bottom: 20px;
}
.input,
.msg, .area{
    width: 100%;
    padding: 10px;
    border: 2px solid white;
    box-sizing: border-box;
    font-size: 15px;
    margin-bottom: 20px;
}
button{
    font-size: 14px;
    background-color: #3f3f3f;
    color: white;
    border-radius: 5px;
    padding: 10px 20px;
    margin-top: 8x;
}
button :hover{
    opacity: 0,9;
}
```
![image](https://user-images.githubusercontent.com/56240954/115437452-6288d380-a236-11eb-90e6-36ebfb82478b.png)
Hasilnya
![image](https://user-images.githubusercontent.com/56240954/115437488-6fa5c280-a236-11eb-8291-362f012ddf26.png)









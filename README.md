<img width="1530" height="877" alt="Screenshot 2025-10-27 133959" src="https://github.com/user-attachments/assets/a84a928d-838d-4ab1-b5c9-9f155ffca7b7" />

<img width="1450" height="879" alt="Screenshot 2025-10-27 134019" src="https://github.com/user-attachments/assets/644426e8-a999-468d-afa0-8b384c7584c4" />

<img width="1489" height="196" alt="Screenshot 2025-10-27 134030" src="https://github.com/user-attachments/assets/8fce6641-29da-4ad6-880b-78640789f157" />

STRUKTUR UTAMA
1. DOCTYPE & HTML Setup
<!DOCTYPE html>
<html lang="id">
  
  # penjelasan
DOCTYPE: Mendeklarasikan dokumen HTML5
lang="id": Bahasa Indonesia untuk aksesibilitas dan SEO
  
2. Head Section
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Layout Sederhana</title>
<link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css" rel="stylesheet">

# penjelasan 
UTF-8: Support karakter internasional
Viewport: Responsive design untuk mobile
Bootstrap 5.3.0: Framework CSS untuk styling
  
  STYLING CUSTOM
3. Warna dan Layout
.navbar-custom { background-color: #f1129f; }
.circle-orange { background-color: #6fe8ea; }
.circle-blue { background-color: #e043ce; }
.circle-teal { background-color: #5df4f1; }
.feature-img { background-color: #48f197; }
# penjelasan 
Warna cerah dan kontras untuk visual menarik
Kombinasi pink, biru, hijau untuk variasi
  
4. Komponen Visual
css
.circle-orange, .circle-blue, .circle-teal {
    width: 120px; height: 120px;
    border-radius: 50%; /* Membuat lingkaran */
}
.feature-img {
    height: 150px; /* Kotak feature placeholder */
}

  STRUKTUR KOMPONEN
5. Header & Navigation
html
<header class="bg-light p-3">
    <h4 class="text-muted mb-0">Layout Sederhana</h4>
</header>

<nav class="navbar navbar-expand-lg navbar-custom">
    <ul class="navbar-nav">
        <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Artikel</a></li>
        <!-- ... -->
    </ul>
</nav>

# penjelasan 
Header: Judul website
Navbar: Menu navigasi dengan warna custom pink

6. Main Content Area
Layout menggunakan sistem grid Bootstrap:
col-lg-9: Konten utama (75% lebar)
col-lg-3: Sidebar widget (25% lebar)

7. Hero Section
html
<section class="p-4">
    <h2>Hello Nadia!</h2>
    <p>Lorem ipsum dolor sit amet...</p>
    <a href="#" class="btn btn-primary">Learn more »</a>
</section>

# penjelasan 
Sambutan personal "Hello Nadia!"
Call-to-action button dengan styling Bootstrap

8. Feature Circles Section
html
<div class="row text-center">
    <div class="col-md-4 mb-4">
        <div class="circle-orange">150 x 150</div>
        <h5>Heading</h5>
        <p class="small">Donec sed odio dui...</p>
        <button class="btn btn-secondary btn-sm">View detail</button>
    </div>
    <!-- 2 circle lainnya -->
</div>

# penjelasan 
3 lingkaran berwarna dengan konten
Responsive: col-md-4 (3 kolom di desktop, stack di mobile)

9. Featurette Sections
<section class="p-4">
    <h4>First featurette heading.</h4>
    <div class="row align-items-center">
        <div class="col-md-5">
            <div class="feature-img">350 x 150</div>
        </div>
        <div class="col-md-7">
            <p class="small">Lorem ipsum dolor...</p>
        </div>
    </div>
</section>

# penjelasan 
Layout alternatif: gambar-kiri teks-kanan dan sebaliknya
align-items-center: Vertikal alignment tengah

10. Sidebar Widgets
<div class="widget-header">Widget Header</div>
<div class="widget-body">
    <a href="#" class="widget-link">Widget Link</a>
    <!-- ... -->
</div>

# penjelasan 
Widget dengan header berwarna biru
List link dengan border bottom
Widget text untuk konten statis

11. Footer
html
<footer>
    <p class="mb-0">© 2025 - Universitas Pelita Bangsa</p>
</footer>

# penjelasan 
Copyright info dengan latar hitam
Tema pendidikan: Menyebut Universitas Pelita Bangsa

FITUR RESPONSIVE
12. Grid System Bootstrap
html
<div class="row">
    <div class="col-lg-9">...</div>
    <div class="col-lg-3">...</div>
</div>

# penjelasan 
lg breakpoint: Sidebar hilang di layar kecil
md breakpoint: Feature circles menjadi 1 kolom

13. Mobile-Friendly
Viewport meta tag
Fluid containers dengan max-width
Padding dan margin yang adaptif

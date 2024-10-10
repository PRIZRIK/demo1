<!DOCTYPE html>
<html lang="en"> <!-- Hujjat turi va tilini belgilaydi. Bu yerda HTML5 va hujjatning tili ingliz tilida ekanligini bildiradi. -->
<head>
    <meta charset="UTF-8"> <!-- Veb-sahifadagi matnlar UTF-8 formatida kodlanishini belgilaydi, bu turli tillardagi maxsus belgilarni to'g'ri ko'rsatishga yordam beradi. -->
    <title>FrontEnd 1</title> <!-- Brauzerning sahifa nomi qismida (tab) ko'rinadigan matn. -->
    <link rel="stylesheet" href="styles.css"/> <!-- Sahifaga tashqi CSS faylini ulash uchun foydalaniladi, bu sahifaga uslubiy o'zgartirishlar kiritadi. -->
</head>
<body>

<div class="top-header"> <!-- Bu qism sahifaning yuqori qismidagi menyuni o'z ichiga oladi. "top-header" CSS klassi orqali uslub qo'llaniladi. -->
    <p>Files</p> <!-- Har bir "p" elementi menyudagi variantlar uchun. Masalan, bu yerda "Files" varianti ko'rsatiladi. -->
    <p>Edit</p>
    <p>Code</p>
    <p>Windows</p>
    <p>View</p>
    <p>Help</p>
    <p>Likes</p>
</div>

<div class="cards"> <!-- Bu qismda kartochkalar to'plami joylashgan. Har bir kartochka bir xil uslubga ega bo'lgan holda, turli ma'lumotlar va rasmlar ko'rsatiladi. -->
    <div class="card"> <!-- Birinchi kartochka (bu yerda "card" deb nomlangan CSS klassi orqali uslub beriladi). -->
        <img src="https://i3.wp.com/cdn.pixabay.com/photo/2023/02/06/13/32/gnome-7772044_1280.jpg"> <!-- Kartochkadagi rasm uchun img tegi. Bu yerda URL orqali rasmni yuklaydi. -->
        <h2>Gnomlar qishlog'i</h2> <!-- Kartochkaning asosiy sarlavhasi (h2 tegi orqali yaratilgan). -->
        <p>Gnomlar kanalchasi</p> <!-- Bu qator kartochkadagi qo'shimcha ma'lumotlar (kanal nomi). -->
        <p>19 mln views.</p> <!-- Ushbu kartochka bilan bog'liq tomosha qilinishlar soni (19 million). -->
        <p>8 month ago</p> <!-- Kartochkadagi kontent qachon yuklanganligini bildiradi (8 oy oldin). -->
    </div>

    <!-- Yuqoridagi kartochka nusxalanib, quyida yana bir necha martalab ko'paya boshlaydi. Bu barcha kartochkalar bir xil formatda bo'ladi, ammo ularning har biri individual kartochka hisoblanadi. -->

    <div class="card">
        <img src="https://i3.wp.com/cdn.pixabay.com/photo/2023/02/06/13/32/gnome-7772044_1280.jpg">
        <h2>Gnomlar qishlog'i</h2>
        <p>Gnomlar kanalchasi</p>
        <p>19 mln views.</p>
        <p>8 month ago</p>
    </div>

    <div class="card">
        <img src="https://i3.wp.com/cdn.pixabay.com/photo/2023/02/06/13/32/gnome-7772044_1280.jpg">
        <h2>Gnomlar qishlog'i</h2>
        <p>Gnomlar kanalchasi</p>
        <p>19 mln views.</p>
        <p>8 month ago</p>
    </div>

    <!-- Bu holatda yana boshqa kartochkalar nusxalanmoqda, xuddi yuqoridagilarday. -->

    <div class="card">
        <img src="https://i3.wp.com/cdn.pixabay.com/photo/2023/02/06/13/32/gnome-7772044_1280.jpg">
        <h2>Gnomlar qishlog'i</h2>
        <p>Gnomlar kanalchasi</p>
        <p>19 mln views.</p>
        <p>8 month ago</p>
    </div>

    <div class="card">
        <img src="https://i3.wp.com/cdn.pixabay.com/photo/2023/02/06/13/32/gnome-7772044_1280.jpg">
        <h2>Gnomlar qishlog'i</h2>
        <p>Gnomlar kanalchasi</p>
        <p>19 mln views.</p>
        <p>8 month ago</p>
    </div>

    <div class="card">
        <img src="https://i3.wp.com/cdn.pixabay.com/photo/2023/02/06/13/32/gnome-7772044_1280.jpg">
        <h2>Gnomlar qishlog'i</h2>
        <p>Gnomlar kanalchasi</p>
        <p>19 mln views.</p>
        <p>8 month ago</p>
    </div>

    <!-- Kartochkalar shu tartibda davom etadi, har bir kartochka bir xil rasm va kontentga ega bo'ladi. -->

    <div class="card">
        <img src="https://i3.wp.com/cdn.pixabay.com/photo/2023/02/06/13/32/gnome-7772044_1280.jpg">
        <h2>Gnomlar qishlog'i</h2>
        <p>Gnomlar kanalchasi</p>
        <p>19 mln views.</p>
        <p>8 month ago</p>
    </div>

    <div class="card">
        <img src="https://i3.wp.com/cdn.pixabay.com/photo/2023/02/06/13/32/gnome-7772044_1280.jpg">
        <h2>Gnomlar qishlog'i</h2>
        <p>Gnomlar kanalchasi</p>
        <p>19 mln views.</p>
        <p>8 month ago</p>
    </div>

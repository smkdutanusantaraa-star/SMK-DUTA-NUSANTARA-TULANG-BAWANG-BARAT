# SMK-DUTA-NUSANTARA-TULANG-BAWANG-BARAT
<html lang="id">
<head>
  <title>SMK Duta Nusantara</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Favicon -->
  <link rel="icon" href="logo-smk.png" type="image/png">

  <!-- Animasi Logo -->
  <style>
    .logo-anim {
      animation: spin 3s linear infinite;
    }

    @keyframes spin {
      from { transform: rotate(0deg); }
      to { transform: rotate(360deg); }
    }
  </style>
</head>
<body class="bg-gray-100 font-sans">

<!-- Navbar -->
<nav class="bg-blue-900 text-white p-4 flex justify-between items-center">
  <div class="flex items-center space-x-3">
   <div class="logo">
  <img src="logo.png" alt="Logo SMK Duta Nusantara">
</div>

<style>
.logo img {
  width: 120px;
  height: auto;
}
</style>
    <h1 class="text-xl font-bold">SMK Duta Nusantara</h1>
  </div>
  <div class="space-x-4">
    <a href="#" class="hover:underline">Beranda</a>
    <a href="#profil" class="hover:underline">Profil</a>
    <a href="#visi" class="hover:underline">Visi Misi</a>
    <a href="#jurusan" class="hover:underline">Jurusan</a>
    <a href="#galeri" class="hover:underline">Galeri</a>
    <a href="#ppdb" class="hover:underline">PPDB</a>
    <a href="#kontak" class="hover:underline">Kontak</a>
  </div>
</nav>

<!-- Hero -->
<section class="bg-blue-800 text-white text-center py-20">
  <h2 class="text-8xl font-bold mb-4">WELCOME</h2>
  <p>Sekolah Kejuruan Unggul, Siap Kerja, Siap Kuliah, Siap Wirausaha</p>
</section>

<!-- Profil -->
<section id="profil" class="p-10">
  <div class="max-w-4xl mx-auto bg-white p-6 rounded-2xl shadow">
    <h2 class="text-2xl font-bold mb-4">Profil Sekolah</h2>
    <p>SMK Duta Nusantara merupakan sekolah menengah kejuruan swasta yang berlokasi di Jl. Pangeran Diponegoro, Lingkungan V RT 001 RW 002, Kelurahan Daya Murni, Kecamatan Tumijajar, Kabupaten Tulang Bawang Barat, Provinsi Lampung, Indonesia. Sekolah ini berdiri berdasarkan Surat Keputusan Pendirian Nomor 800/043/SK/SMK-DT_NS/TBB/VI/2020 yang diterbitkan pada tanggal 2 Juni 2020, dan telah memperoleh izin operasional pada 4 September 2020.

Sebagai lembaga pendidikan kejuruan, SMK Duta Nusantara berkomitmen untuk menyelenggarakan pendidikan yang berorientasi pada pengembangan keterampilan, pengetahuan, dan karakter peserta didik agar siap bersaing di dunia kerja maupun melanjutkan ke jenjang pendidikan yang lebih tinggi. Dengan status kepemilikan di bawah yayasan, sekolah ini terus berupaya meningkatkan kualitas layanan pendidikan serta berkontribusi dalam pembangunan sumber daya manusia di wilayah Lampung.</p>

<!-- Visi -->
<section id="visi" class="p-10 bg-gray-200">
  <div class="max-w-4xl mx-auto bg-white p-6 rounded-2xl shadow">
    <h2 class="text-2xl font-bold mb-4">Visi & Misi</h2>
    <p class="mb-2">Menjadi SMK Unggul di Bidang Perhotelan, Desain Komunikasi Visual dan Bisnis Retail, yang mengedepankan pembentukan karakter profil pancasila serta mengutamakan keberpihakan pada kepentingan dan potensi peserta didik</p>
    <ul class="list-disc pl-5">
      <li>Mengukuhkan Nilai-nilai Pancasila</li>
      <li>Menyediakan Lingkungan Belajar yang Inklusif</li>
      <li>Memaksimalkan Potensi Individui</li>
      <li>Mengintegrasikan Nilai Pancasila dalam Kurikulum</li>
      <li>Membangun kemitraan dan komunitas</li>
    </ul>
  </div>
</section>

<!-- Jurusan -->
<section id="jurusan" class="p-10">
  <h2 class="text-center text-2xl font-bold mb-10">Program Keahlian</h2>
  <div class="grid md:grid-cols-4 gap-6 max-w-6xl mx-auto">
    <div class="bg-blue p-4 rounded-2xl shadow text-center">Perhotelan</div>
    <div class="bg-blue p-4 rounded-2xl shadow text-center">Desain Komunikasi Visual</div>
    <div class="bg-blue p-4 rounded-2xl shadow text-center">Bisnis Retail</div>
  </div>
</section>

<!-- Galeri -->
<section id="galeri" class="p-10 bg-gray-200">
  <div class="max-w-6xl mx-auto">
    <h2 class="text-2xl font-bold mb-6 text-center">Galeri Sekolah</h2>
    <div class="grid md:grid-cols-3 gap-4">
      <img src="https://via.placeholder.com/400x250" class="rounded-2xl shadow">
      <img src="https://via.placeholder.com/400x250" class="rounded-2xl shadow">
      <img src="https://via.placeholder.com/400x250" class="rounded-2xl shadow">
      <img src="https://via.placeholder.com/400x250" class="rounded-2xl shadow">
      <img src="https://via.placeholder.com/400x250" class="rounded-2xl shadow">
      <img src="https://via.placeholder.com/400x250" class="rounded-2xl shadow">
    </div>
  </div>
</section>

<!-- PPDB -->
<section id="ppdb" class="p-10">
  <div class="max-w-3xl mx-auto bg-white p-6 rounded-2xl shadow">
    <h2 class="text-2xl font-bold mb-4">Form Pendaftaran Siswa Baru (PPDB)</h2>
    <form id="formPPDB" class="space-y-4">
      <input type="text" placeholder="Nama Lengkap" class="w-full p-2 border rounded" required>
      <input type="text" placeholder="Asal Sekolah" class="w-full p-2 border rounded" required>
      <input type="text" placeholder="No HP" class="w-full p-2 border rounded" required>
      <select class="w-full p-2 border rounded" required>
        <option value="">Pilih Jurusan</option>
        <option>TKJ</option>
        <option>Multimedia</option>
        <option>AKL</option>
        <option>OTKP</option>
      </select>
      <button type="submit" class="bg-blue-900 text-white px-4 py-2 rounded">Daftar</button>
    </form>
    <p id="successMsg" class="text-green-600 mt-4 hidden">Pendaftaran berhasil!</p>
  </div>
</section>

<!-- Kontak -->
<section id="kontak" class="p-10 bg-gray-200">
  <div class="max-w-4xl mx-auto bg-white p-6 rounded-2xl shadow">
    <h2 class="text-2xl font-bold mb-4">Kontak</h2>
    <p>Alamat: Lampung</p>
    <p>Email: info@smk.sch.id</p>
  </div>
</section>

<!-- Footer -->
<footer class="bg-blue-900 text-white text-center p-4">
  <p>&copy; 2026 SMK Duta Nusantara</p>
</footer>

<script>
  document.getElementById('formPPDB').addEventListener('submit', function(e){
    e.preventDefault();
    document.getElementById('successMsg').classList.remove('hidden');
  });
</script>

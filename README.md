<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Sekolah SMP N1 MOJOGEDANG</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        :root {
            --primary: #4F46E5;
            --secondary: #06B6D4;
            --accent: #10B981;
            --light: #F9FAFB;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        
        .navbar {
            transition: all 0.3s ease;
        }
        
        .navbar.scrolled {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .hero {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
        }
        
        .card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        
        .achievement-item:hover img {
            transform: scale(1.05);
        }
        
        .extracurricular-card {
            transition: all 0.3s ease;
        }
        
        .extracurricular-card:hover {
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .history-timeline {
            position: relative;
        }
        
        .history-timeline::before {
            content: '';
            position: absolute;
            width: 2px;
            background-color: var(--primary);
            top: 0;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
        }
        
        @media (max-width: 768px) {
            .history-timeline::before {
                left: 20px;
            }
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navbar -->
    <nav class="navbar fixed w-full z-50 py-4">
        <div class="container mx-auto px-4 flex justify-between items-center">
            <div class="flex items-center">
                <img src="https://smpn2bandar.sch.id/storage/00-universal/smpn2bandar.sch.id/logo/66b345c6025e3Tut_wuri_handayani-removebg-preview.png" alt="Logo Sekolah ABC - lingkaran biru dengan huruf S di tengah" class="h-10 w-10 mr-2 rounded-full">
                <span class="text-xl font-bold text-white">SPENSAMO</span>
            </div>
            <div class="hidden md:flex space-x-6">
                <a href="#beranda" class="text-white hover:text-gray-200 font-medium">Beranda</a>
                <a href="#sejarah" class="text-white hover:text-gray-200 font-medium">Sejarah</a>
                <a href="#prestasi" class="text-white hover:text-gray-200 font-medium">Prestasi</a>
                <a href="#ekstrakurikuler" class="text-white hover:text-gray-200 font-medium">Ekstrakurikuler</a>
                <a href="#kontak" class="text-white hover:text-gray-200 font-medium">Kontak</a>
            </div>
            <button class="md:hidden text-white">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                </svg>
            </button>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="beranda" class="hero pt-24 pb-16 md:pt-32 md:pb-24 text-white px-4">
        <div class="container mx-auto">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-8 md:mb-0">
                    <h1 class="text-4xl md:text-5xl font-bold mb-4">Selamat datang di Smp N1 MOJOGEDANG</h1>
                    <p class="text-xl mb-6">Sekolah Dengan akreditasi A.</p>
                    <div class="flex space-x-4">
                        <button class="bg-white text-primary-500 hover:bg-gray-100 px-6 py-3 rounded-lg font-medium transition-all">join us</button>
                        <button class="bg-transparent border-2 border-white hover:bg-white hover:text-primary-500 px-6 py-3 rounded-lg font-medium transition-all">Ayo Eksplor</button>
                    </div>
                </div>
                <div class="md:w-1/2">
                    <img src="data:image/jpeg;base64,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" alt="Depan gedung Sekolah ABC dengan halaman hijau, bangunan modern, dan siswa berseragam sedang berjalan" class="rounded-lg shadow-xl w-full">
                </div>
            </div>
        </div>
    </section>

    <!-- Quick Info -->
    <section class="py-12 bg-white">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
                <div class="card bg-gray-50 p-6 rounded-xl text-center">
                    <div class="text-primary-500 mb-4 mx-auto">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 inline-block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M13 7a4 4 0 11-8 0 4 4 0 018 0z" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-2">423 Siswa</h3>
                    <p class="text-gray-600">Siswa aktif dari berbagai jenjang pendidikan</p>
                </div>
                <div class="card bg-gray-50 p-6 rounded-xl text-center">
                    <div class="text-secondary-500 mb-4 mx-auto">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 inline-block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-2">32 Ruang Kelas</h3>
                    <p class="text-gray-600">Dilengkapi fasilitas modern dan nyaman</p>
                </div>
                <div class="card bg-gray-50 p-6 rounded-xl text-center">
                    <div class="text-accent-500 mb-4 mx-auto">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 inline-block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-2">46 Guru</h3>
                    <p class="text-gray-600">Pengajar profesional dan berpengalaman</p>
                </div>
                <div class="card bg-gray-50 p-6 rounded-xl text-center">
                    <div class="text-indigo-500 mb-4 mx-auto">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 inline-block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-2">100+ Prestasi</h3>
                    <p class="text-gray-600">Prestasi akademik dan non-akademik</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Sejarah Sekolah -->
    <section id="sejarah" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold mb-4">SEJARAH SMP NEGERI 1 MOJOGEDANG</h2>
                <div class="w-20 h-1 bg-primary-500 mx-auto"></div>
            </div>
            
            <div class="history-timeline max-w-4xl mx-auto">
                <!-- Timeline Item -->
                <div class="mb-8 flex flex-col md:flex-row items-start">
                    <div class="md:w-1/2 md:pr-10 mb-4 md:mb-0">
                        <div class="p-6 bg-white rounded-lg shadow-md">
                            <h3 class="text-xl font-bold mb-2 text-primary-500">1985 - Pendirian</h3>
                            <p>Sekolah ABC didirikan pada tahun 1985 dengan hanya 3 ruang kelas dan 50 siswa. Pendirian sekolah ini bertujuan untuk memenuhi kebutuhan pendidikan dasar di wilayah ini.</p>
                        </div>
                    </div>
                    <div class="md:w-1/2"></div>
                </div>
                
                <!-- Timeline Item -->
                <div class="mb-8 flex flex-col md:flex-row items-end">
                    <div class="md:w-1/2 hidden md:block"></div>
                    <div class="md:w-1/2 md:pl-10">
                        <div class="p-6 bg-white rounded-lg shadow-md">
                            <h3 class="text-xl font-bold mb-2 text-secondary-500">1995 - Ekspansi Pertama</h3>
                            <p>Pada tahun 1995, sekolah melakukan ekspansi pertama dengan menambah 5 ruang kelas baru dan perpustakaan kecil. Jumlah siswa bertambah menjadi 200 orang.</p>
                        </div>
                    </div>
                </div>
                
                <!-- Timeline Item -->
                <div class="mb-8 flex flex-col md:flex-row items-start">
                    <div class="md:w-1/2 md:pr-10 mb-4 md:mb-0">
                        <div class="p-6 bg-white rounded-lg shadow-md">
                            <h3 class="text-xl font-bold mb-2 text-accent-500">2005 - Pengakuan Nasional</h3>
                            <p>Sekolah ABC mendapatkan akreditasi A dan diakui sebagai salah satu sekolah unggulan di tingkat nasional. Fasilitas laboratorium sains dan komputer pertama kali diperkenalkan.</p>
                        </div>
                    </div>
                    <div class="md:w-1/2"></div>
                </div>
                
                <!-- Timeline Item -->
                <div class="mb-8 flex flex-col md:flex-row items-end">
                    <div class="md:w-1/2 hidden md:block"></div>
                    <div class="md:w-1/2 md:pl-10">
                        <div class="p-6 bg-white rounded-lg shadow-md">
                            <h3 class="text-xl font-bold mb-2 text-indigo-500">2020 - Transformasi Digital</h3>
                            <p>Di era digital, Sekolah ABC meluncurkan program pembelajaran hybrid dengan fasilitas lengkap. Sekarang memiliki lebih dari 40 ruang kelas dan 1200 siswa dengan berbagai prestasi.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Prestasi Sekolah -->
    <section id="prestasi" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold mb-4">Prestasi Sekolah</h2>
                <div class="w-20 h-1 bg-primary-500 mx-auto"></div>
                <p class="max-w-2xl mx-auto mt-4">Berbagai prestasi gemilang yang telah diraih oleh siswa-siswi Sekolah ABC</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Achievement 1 -->
                <div class="achievement-item bg-gray-50 rounded-xl overflow-hidden border border-gray-200 hover:border-primary-500 transition-all">
                    <div class="overflow-hidden">
                        <img src="https://placehold.co/600x400" alt="Siswa Sekolah ABC memegang piala penghargaan Olimpiade Sains Nasional dengan latar belakang panggung merah" class="w-full h-48 object-cover hover:scale-105 transition-transform">
                    </div>
                    <div class="p-6">
                        <div class="flex items-center mb-2">
                            <span class="px-3 py-1 bg-primary-100 text-primary-500 rounded-full text-sm font-medium">Akademik</span>
                        </div>
                        <h3 class="text-xl font-bold mb-2">Juara 1 Olimpiade Sains Nasional</h3>
                        <p class="text-gray-600">Tim sains sekolah meraih juara 1 dalam Olimpiade Sains Nasional tahun 2022, mengalahkan 100+ peserta dari seluruh Indonesia.</p>
                    </div>
                </div>
                
                <!-- Achievement 2 -->
                <div class="achievement-item bg-gray-50 rounded-xl overflow-hidden border border-gray-200 hover:border-primary-500 transition-all">
                    <div class="overflow-hidden">
                        <img src="https://placehold.co/600x400" alt="Tim basket sekolah sedang merayakan kemenangan dengan seragam merah putih, latar belakang lapangan basket" class="w-full h-48 object-cover hover:scale-105 transition-transform">
                    </div>
                    <div class="p-6">
                        <div class="flex items-center mb-2">
                            <span class="px-3 py-1 bg-accent-100 text-accent-500 rounded-full text-sm font-medium">Olahraga</span>
                        </div>
                        <h3 class="text-xl font-bold mb-2">Juara Turnamen Basket Pelajar</h3>
                        <p class="text-gray-600">Tim basket putra menjadi juara turnamen antar sekolah se-provinsi yang diadakan pada bulan Agustus 2023.</p>
                    </div>
                </div>
                
                <!-- Achievement 3 -->
                <div class="achievement-item bg-gray-50 rounded-xl overflow-hidden border border-gray-200 hover:border-primary-500 transition-all">
                    <div class="overflow-hidden">
                        <img src="https://placehold.co/600x400" alt="Karya seni lukis abstrak warna-warni yang dibuat siswa, dipajang di galeri seni dengan pencahayaan dramatis" class="w-full h-48 object-cover hover:scale-105 transition-transform">
                    </div>
                    <div class="p-6">
                        <div class="flex items-center mb-2">
                            <span class="px-3 py-1 bg-secondary-100 text-secondary-500 rounded-full text-sm font-medium">Seni</span>
                        </div>
                        <h3 class="text-xl font-bold mb-2">Penghargaan Karya Seni Nasional</h3>
                        <p class="text-gray-600">Karya seni siswa terpilih untuk dipamerkan di Galeri Nasional dan mendapatkan penghargaan dari Kementerian Pendidikan.</p>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <button class="px-6 py-3 bg-primary-500 text-white rounded-lg hover:bg-primary-600 transition-all font-medium">Lihat Lebih Banyak Prestasi</button>
            </div>
        </div>
    </section>

    <!-- Ekstrakurikuler -->
    <section id="ekstrakurikuler" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold mb-4">Ekstrakurikuler</h2>
                <div class="w-20 h-1 bg-primary-500 mx-auto"></div>
                <p class="max-w-2xl mx-auto mt-4">Berbagai kegiatan ekstrakurikuler untuk mengembangkan bakat dan minat siswa</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Ekstrakurikuler 1 -->
                <div class="extracurricular-card bg-white rounded-xl overflow-hidden shadow-md hover:shadow-lg transition-all">
                    <img src="https://placehold.co/600x400" alt="Siswa sedang bermain robotik dengan latar belakang laboratorium teknologi penuh peralatan canggih" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Robotika</h3>
                        <p class="text-gray-600 mb-4">Mengembangkan keterampilan teknologi dan pemrograman melalui pembuatan robot.</p>
                        <div class="text-sm text-primary-500">Setiap Rabu & Jumat, 15.00 - 17.00</div>
                    </div>
                </div>
                
                <!-- Ekstrakurikuler 2 -->
                <div class="extracurricular-card bg-white rounded-xl overflow-hidden shadow-md hover:shadow-lg transition-all">
                    <img src="https://placehold.co/600x400" alt="Tim paduan suara sekolah sedang berlatih dengan konduktor di aula musik yang terang" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Paduan Suara</h3>
                        <p class="text-gray-600 mb-4">Mengasah bakat menyanyi dan harmoni vokal dalam kelompok paduan suara.</p>
                        <div class="text-sm text-primary-500">Setiap Senin, 14.00 - 16.00</div>
                    </div>
                </div>
                
                <!-- Ekstrakurikuler 3 -->
                <div class="extracurricular-card bg-white rounded-xl overflow-hidden shadow-md hover:shadow-lg transition-all">
                    <img src="https://placehold.co/600x400" alt="Pertandingan futsal intensive di lapangan indoor dengan lampu sorot yang dramatis" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Futsal</h3>
                        <p class="text-gray-600 mb-4">Meningkatkan kebugaran dan keterampilan bermain bola dalam tim futsal.</p>
                        <div class="text-sm text-primary-500">Setiap Selasa & Kamis, 15.30 - 17.30</div>
                    </div>
                </div>
                
                <!-- Ekstrakurikuler 4 -->
                <div class="extracurricular-card bg-white rounded-xl overflow-hidden shadow-md hover:shadow-lg transition-all">
                    <img src="https://placehold.co/600x400" alt="Siswa sedang merangkai bunga dan tanaman dalam kegiatan berkebun di taman sekolah yang hijau" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Berkebun</h3>
                        <p class="text-gray-600 mb-4">Belajar tentang tanaman, ekologi, dan praktik berkebun yang berkelanjutan.</p>
                        <div class="text-sm text-primary-500">Setiap Sabtu, 08.00 - 10.00</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Kontak -->
    <section id="kontak" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="max-w-4xl mx-auto bg-primary-50 rounded-xl overflow-hidden shadow-lg">
                <div class="grid grid-cols-1 md:grid-cols-2">
                    <div class="p-8 md:p-12 text-center md:text-left">
                        <h2 class="text-2xl font-bold mb-4">Hubungi Kami</h2>
                        <p class="mb-6">Jika Anda memiliki pertanyaan tentang sekolah kami atau ingin mendaftarkan anak Anda, jangan ragu untuk menghubungi kami melalui form ini.</p>
                        
                        <div class="space-y-4">
                            <div class="flex items-start">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-primary-500 mt-1 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                                </svg>
                                <span>info@sekolahabc.sch.id</span>
                            </div>
                            <div class="flex items-start">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-primary-500 mt-1 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                                </svg>
                                <span>(021) 12345678</span>
                            </div>
                            <div class="flex items-start">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-primary-500 mt-1 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                                </svg>
                                <span>Jl. Pendidikan No.123, Jakarta Pusat, DKI Jakarta</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="p-8 md:p-12 bg-white">
                        <form>
                            <div class="mb-4">
                                <label class="block text-gray-700 mb-2" for="name">Nama Lengkap</label>
                                <input type="text" id="name" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-primary-500">
                            </div>
                            <div class="mb-4">
                                <label class="block text-gray-700 mb-2" for="email">Email</label>
                                <input type="email" id="email" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-primary-500">
                            </div>
                            <div class="mb-4">
                                <label class="block text-gray-700 mb-2" for="message">Pesan</label>
                                <textarea id="message" rows="4" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-primary-500"></textarea>
                            </div>
                            <button type="submit" class="w-full bg-primary-500 text-white py-3 rounded-lg hover:bg-primary-600 transition-all font-medium">Kirim Pesan</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">Tentang Sekolah ABC</h3>
                    <p>Sekolah unggulan dengan pendidikan berkualitas yang mengedepankan karakter, kreativitas, dan prestasi akademik sejak 1985.</p>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-4">Link Cepat</h3>
                    <ul class="space-y-2">
                        <li><a href="#beranda" class="hover:text-primary-300">Beranda</a></li>
                        <li><a href="#sejarah" class="hover:text-primary-300">Sejarah</a></li>
                        <li><a href="#prestasi" class="hover:text-primary-300">Prestasi</a></li>
                        <li><a href="#ekstrakurikuler" class="hover:text-primary-300">Ekstrakurikuler</a></li>
                        <li><a href="#kontak" class="hover:text-primary-300">Kontak</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-4">Ekstrakurikuler</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="hover:text-primary-300">Robotika</a></li>
                        <li><a href="#" class="hover:text-primary-300">Paduan Suara</a></li>
                        <li><a href="#" class="hover:text-primary-300">Futsal</a></li>
                        <li><a href="#" class="hover:text-primary-300">Berkebun</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-4">Media Sosial</h3>
                    <div class="flex space-x-4">
                        <a href="#" class="bg-gray-700 hover:bg-primary-500 w-10 h-10 rounded-full flex items-center justify-center transition-all">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M22.675 0h-21.35c-.732 0-1.325.593-1.325 1.325v21.351c0 .731.593 1.324 1.325 1.324h11.495v-9.294h-3.128v-3.622h3.128v-2.671c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12v9.293h6.116c.73 0 1.323-.593 1.323-1.325v-21.35c0-.732-.593-1.325-1.325-1.325z"/>
                            </svg>
                        </a>
                        <a href="#" class="bg-gray-700 hover:bg-primary-500 w-10 h-10 rounded-full flex items-center justify-center transition-all">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
                            </svg>
                        </a>
                        <a href="#" class="bg-gray-700 hover:bg-primary-500 w-10 h-10 rounded-full flex items-center justify-center transition-all">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/>
                            </svg>
                        </a>
                        <a href="#" class="bg-gray-700 hover:bg-primary-500 w-10 h-10 rounded-full flex items-center justify-center transition-all">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"/>
                            </svg>
                        </a>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-sm">
                <p>&copy; 2023 Sekolah ABC. Seluruh hak cipta dilindungi.</p>
            </div>
        </div>
    </footer>

    <script>
        // Navbar Scroll Effect
        window.addEventListener('scroll', function() {
            const navbar = document.querySelector('.navbar');
            if (window.scrollY > 50) {
                navbar.classList.add('scrolled');
                navbar.classList.remove('bg-transparent');
                navbar.classList.add('bg-white');
                document.querySelectorAll('.navbar a').forEach(a => {
                    a.classList.remove('text-white');
                    a.classList.add('text-gray-800');
                });
                document.querySelectorAll('.navbar svg').forEach(svg => {
                    svg.classList.remove('text-white');
                    svg.classList.add('text-gray-800');
                });
                document.querySelector('.navbar span').classList.remove('text-white');
                document.querySelector('.navbar span').classList.add('text-gray-800');
            } else {
                navbar.classList.remove('scrolled');
                navbar.classList.add('bg-transparent');
                navbar.classList.remove('bg-white');
                document.querySelectorAll('.navbar a').forEach(a => {
                    a.classList.add('text-white');
                    a.classList.remove('text-gray-800');
                });
                document.querySelectorAll('.navbar svg').forEach(svg => {
                    svg.classList.add('text-white');
                    svg.classList.remove('text-gray-800');
                });
                document.querySelector('.navbar span').classList.add('text-white');
                document.querySelector('.navbar span').classList.remove('text-gray-800');
            }
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
        
        // Mobile menu toggle (would need to be implemented with more JS)
        document.querySelector('.md\\:hidden').addEventListener('click', function() {
            // Implementation for mobile menu toggle
            console.log('Mobile menu clicked');
        });
    </script>
</body>
</html>

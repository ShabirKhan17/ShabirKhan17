<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Branding | Shabir Khan</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; }
        .gradient-text {
            background: linear-gradient(90deg, #3b82f6, #06b6d4);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900 overflow-x-hidden">

    <header class="fixed w-full top-0 bg-white/80 backdrop-blur-md z-50 border-b border-slate-200">
        <nav class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <h1 class="text-xl font-bold gradient-text tracking-tighter">SK.</h1>
            <div class="space-x-6 text-sm font-medium">
                <a href="#about" class="hover:text-blue-600 transition">Tentang</a>
                <a href="#education" class="hover:text-blue-600 transition">Pendidikan</a>
                <a href="#projects" class="hover:text-blue-600 transition">Proyek</a>
                <a href="#skills" class="hover:text-blue-600 transition">Skill</a>
            </div>
        </nav>
    </header>

    <section id="about" class="pt-32 pb-20 px-6">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-5xl md:text-6xl font-bold mb-6">Halo, Saya <span class="gradient-text">Shabir Khan</span></h2>
            <p class="text-lg text-slate-600 leading-relaxed mb-8 max-w-2xl mx-auto">
                Mahasiswa Teknologi Rekayasa Perangkat Lunak di Politeknik Negeri Batam yang berdedikasi dalam pengembangan web full-stack dan arsitektur database. Berpengalaman sebagai pemimpin tim dalam berbagai proyek perangkat lunak.
            </p>
            <div class="flex justify-center space-x-4">
                <a href="mailto:shabir.khan@email.com" class="bg-blue-600 text-white px-6 py-3 rounded-full font-semibold hover:bg-blue-700 transition shadow-lg shadow-blue-200">Hubungi Saya</a>
                <div class="flex space-x-3 items-center ml-4">
                    <a href="https://linkedin.com/in/shabirkhan" class="text-2xl text-slate-400 hover:text-blue-600 transition"><i class="fab fa-linkedin"></i></a>
                    <a href="https://github.com/ShabirKhan17" class="text-2xl text-slate-400 hover:text-slate-900 transition"><i class="fab fa-github"></i></a>
                </div>
            </div>
            <div class="mt-12 p-4 bg-white border border-slate-200 rounded-2xl inline-block shadow-sm">
                <p class="text-sm text-slate-500"><i class="fas fa-map-marker-alt mr-2 text-blue-500"></i> Batam, Kepulauan Riau, Indonesia</p>
            </div>
        </div>
    </section>

    <section id="education" class="py-20 bg-white px-6">
        <div class="max-w-4xl mx-auto">
            <h3 class="text-3xl font-bold mb-12 text-center">Riwayat Pendidikan</h3>
            <div class="space-y-12">
                <div class="flex flex-col md:flex-row border-l-4 border-blue-500 pl-6 relative">
                    <div class="md:w-1/4 mb-2 md:mb-0">
                        <span class="text-blue-600 font-bold">2025 - Sekarang</span>
                    </div>
                    <div class="md:w-3/4">
                        <h4 class="text-xl font-bold">Politeknik Negeri Batam</h4>
                        <p class="text-slate-600">D4 Teknologi Rekayasa Perangkat Lunak (TRPL)</p>
                    </div>
                </div>
                <div class="flex flex-col md:flex-row border-l-4 border-slate-300 pl-6 relative">
                    <div class="md:w-1/4 mb-2 md:mb-0">
                        <span class="text-slate-500 font-bold">2022 - 2025</span>
                    </div>
                    <div class="md:w-3/4">
                        <h4 class="text-xl font-bold">[Nama SMU Anda]</h4>
                        <p class="text-slate-600">Jurusan MIPA / Teknik</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="py-20 px-6 bg-slate-50">
        <div class="max-w-6xl mx-auto">
            <h3 class="text-3xl font-bold mb-12 text-center">Riwayat Pengerjaan Proyek</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-white p-8 rounded-3xl border border-slate-200 hover:shadow-xl transition group">
                    <div class="w-12 h-12 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center mb-6 group-hover:bg-blue-600 group-hover:text-white transition">
                        <i class="fas fa-graduation-cap"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-2">Credemy - Platform E-Learning</h4>
                    <p class="text-sm text-blue-600 font-semibold mb-4">Proyek PBL Semester 1</p>
                    <p class="text-slate-600 mb-6">Membangun platform microcredential serupa Udemy dengan fitur manajemen kursus dan pelacakan progres belajar menggunakan PHP dan MySQL.</p>
                </div>
                <div class="bg-white p-8 rounded-3xl border border-slate-200 hover:shadow-xl transition group">
                    <div class="w-12 h-12 bg-cyan-100 text-cyan-600 rounded-xl flex items-center justify-center mb-6 group-hover:bg-cyan-600 group-hover:text-white transition">
                        <i class="fas fa-users"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-2">TerimaTamu Polibatam</h4>
                    <p class="text-sm text-cyan-600 font-semibold mb-4">Sistem Manajemen Tamu</p>
                    <p class="text-slate-600 mb-6">Sistem registrasi tamu dengan QR Code otomatis dan notifikasi WhatsApp untuk meningkatkan keamanan kampus.</p>
                </div>
                <div class="bg-white p-8 rounded-3xl border border-slate-200 hover:shadow-xl transition group">
                    <div class="w-12 h-12 bg-indigo-100 text-indigo-600 rounded-xl flex items-center justify-center mb-6 group-hover:bg-indigo-600 group-hover:text-white transition">
                        <i class="fas fa-file-invoice"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-2">AjuinAja</h4>
                    <p class="text-sm text-indigo-600 font-semibold mb-4">Aplikasi Layanan Administrasi</p>
                    <p class="text-slate-600 mb-6">Aplikasi untuk mempermudah alur pengajuan dokumen dan registrasi otomatis dengan validasi file yang ketat.</p>
                </div>
                <div class="bg-white p-8 rounded-3xl border border-slate-200 hover:shadow-xl transition group">
                    <div class="w-12 h-12 bg-purple-100 text-purple-600 rounded-xl flex items-center justify-center mb-6 group-hover:bg-purple-600 group-hover:text-white transition">
                        <i class="fas fa-paint-brush"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-2">Mindfloox UI</h4>
                    <p class="text-sm text-purple-600 font-semibold mb-4">Interactive UI Dashboard</p>
                    <p class="text-slate-600 mb-6">Eksperimen antarmuka modern menggunakan Tailwind CSS dan Livewire untuk menciptakan efek visual hover dan navigasi dinamis.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="skills" class="py-20 bg-white px-6">
        <div class="max-w-4xl mx-auto text-center">
            <h3 class="text-3xl font-bold mb-12">Keahlian & Teknologi</h3>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div>
                    <h5 class="font-bold mb-4 text-blue-600 uppercase text-xs tracking-widest">Programming Languages</h5>
                    <div class="flex flex-wrap justify-center gap-2">
                        <span class="px-4 py-2 bg-slate-100 rounded-full text-sm font-medium">PHP</span>
                        <span class="px-4 py-2 bg-slate-100 rounded-full text-sm font-medium">SQL</span>
                        <span class="px-4 py-2 bg-slate-100 rounded-full text-sm font-medium">JavaScript</span>
                    </div>
                </div>
                <div>
                    <h5 class="font-bold mb-4 text-blue-600 uppercase text-xs tracking-widest">Tools & Frameworks</h5>
                    <div class="flex flex-wrap justify-center gap-2">
                        <span class="px-4 py-2 bg-slate-100 rounded-full text-sm font-medium">Laravel</span>
                        <span class="px-4 py-2 bg-slate-100 rounded-full text-sm font-medium">Tailwind CSS</span>
                        <span class="px-4 py-2 bg-slate-100 rounded-full text-sm font-medium">Livewire</span>
                        <span class="px-4 py-2 bg-slate-100 rounded-full text-sm font-medium">MySQL</span>
                    </div>
                </div>
                <div>
                    <h5 class="font-bold mb-4 text-blue-600 uppercase text-xs tracking-widest">Soft Skills</h5>
                    <div class="flex flex-wrap justify-center gap-2">
                        <span class="px-4 py-2 bg-slate-100 rounded-full text-sm font-medium">Kepemimpinan</span>
                        <span class="px-4 py-2 bg-slate-100 rounded-full text-sm font-medium">Kerja Tim</span>
                        <span class="px-4 py-2 bg-slate-100 rounded-full text-sm font-medium">Analisis Kebutuhan</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="py-12 border-t border-slate-200 bg-slate-50 text-center">
        <p class="text-slate-500 text-sm mb-4">&copy; 2026 Shabir Khan. Dibuat dengan GitHub Pages.</p>
        <div class="flex justify-center space-x-6">
            <a href="https://linkedin.com/in/shabirkhan" class="text-slate-400 hover:text-blue-600 transition"><i class="fab fa-linkedin"></i></a>
            <a href="https://github.com/ShabirKhan17" class="text-slate-400 hover:text-slate-900 transition"><i class="fab fa-github"></i></a>
            <a href="mailto:shabir.khan@email.com" class="text-slate-400 hover:text-red-500 transition"><i class="fas fa-envelope"></i></a>
        </div>
    </footer>

</body>
</html>
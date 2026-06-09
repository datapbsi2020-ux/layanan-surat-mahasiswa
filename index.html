<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sistem Informasi Akademik - Layanan Surat FKIP</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        .fade-in { animation: fadeIn 0.4s ease-in-out; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }
        /* Animasi khusus untuk menu admin */
        .slide-down { animation: slideDown 0.3s ease-out; }
        @keyframes slideDown { from { opacity: 0; transform: translateY(-20px); } to { opacity: 1; transform: translateY(0); } }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 font-sans antialiased min-h-screen flex flex-col">

    <nav class="bg-blue-800 text-white shadow-lg relative z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-3">
                <i class="fas fa-graduation-cap text-3xl"></i>
                <div>
                    <h1 class="font-bold text-xl tracking-wide cursor-pointer" onclick="kembaliKeMenu()">Sistem Informasi Akademik</h1>
                </div>
            </div>
            
            <div class="flex items-center space-x-4">
                <span class="hidden sm:block font-medium text-blue-200 text-sm">Layanan Mahasiswa FKIP</span>
                <button onclick="bukaModalLogin()" class="bg-blue-900 hover:bg-gray-900 text-white px-4 py-2 rounded-lg text-sm font-bold transition shadow-inner border border-blue-700 flex items-center gap-2">
                    <i class="fas fa-user-shield"></i> <span class="hidden sm:inline">Menu Admin</span>
                </button>
            </div>
        </div>
    </nav>

    <div id="login-modal" class="hidden fixed inset-0 bg-black bg-opacity-60 flex justify-center items-center z-50 backdrop-blur-sm transition-opacity">
        <div class="bg-white p-8 rounded-2xl shadow-2xl w-full max-w-sm slide-down border-t-4 border-gray-800">
            <div class="text-center mb-6">
                <i class="fas fa-lock text-4xl text-gray-700 mb-3"></i>
                <h2 class="text-2xl font-bold text-gray-800">Otorisasi Admin</h2>
                <p class="text-sm text-gray-500 mt-1">Masukkan PIN untuk mengakses panel.</p>
            </div>
            <input type="password" id="pin-admin" placeholder="PIN Rahasia..." class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 text-center text-xl tracking-widest mb-4 outline-none" onkeypress="cekEnter(event)">
            <p id="error-pin" class="text-red-500 text-sm text-center font-bold hidden mb-4">PIN Salah! Akses Ditolak.</p>
            <div class="flex gap-3">
                <button onclick="tutupModalLogin()" class="w-1/2 bg-gray-200 text-gray-800 font-bold py-2 px-4 rounded-lg hover:bg-gray-300 transition">Batal</button>
                <button onclick="validasiLogin()" class="w-1/2 bg-gray-800 text-white font-bold py-2 px-4 rounded-lg hover:bg-black transition">Masuk</button>
            </div>
        </div>
    </div>

    <main class="flex-grow max-w-5xl mx-auto w-full px-4 sm:px-6 lg:px-8 py-10 relative">
        
        <div id="admin-dashboard" class="hidden fade-in bg-white rounded-2xl shadow-xl p-8 border-t-4 border-gray-800">
            <div class="flex justify-between items-center border-b pb-4 mb-6">
                <h2 class="text-2xl font-black text-gray-800 flex items-center gap-3">
                    <i class="fas fa-user-shield text-gray-600"></i> Panel Kontrol Admin
                </h2>
                <button onclick="logoutAdmin()" class="text-red-500 hover:text-red-700 font-bold px-3 py-1 bg-red-50 rounded-lg transition text-sm flex items-center gap-2">
                    <i class="fas fa-sign-out-alt"></i> Keluar Panel
                </button>
            </div>

            <p class="text-gray-600 mb-8">Selamat datang di pusat kendali. Sistem secara otomatis mencetak surat dan merekap data mahasiswa. Pilih tindakan yang ingin Anda lakukan:</p>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <a href="LINK_FOLDER_GOOGLE_DRIVE_ANDA_DISINI" target="_blank" class="block bg-gradient-to-br from-blue-600 to-blue-800 text-white rounded-xl p-6 shadow-md hover:shadow-xl hover:-translate-y-1 transition transform duration-300 relative overflow-hidden group">
                    <i class="fas fa-print text-6xl opacity-20 absolute right-4 bottom-4 group-hover:scale-110 transition duration-300"></i>
                    <h3 class="text-2xl font-bold mb-2 relative z-10"><i class="fas fa-folder-open mr-2"></i> Cetak Surat</h3>
                    <p class="text-blue-100 text-sm relative z-10">Buka folder Arsip Google Drive untuk mem-print file surat yang sudah terisi otomatis oleh sistem.</p>
                </a>

                <a href="LINK_SPREADSHEET_ANDA_DISINI" target="_blank" class="block bg-gradient-to-br from-green-600 to-green-800 text-white rounded-xl p-6 shadow-md hover:shadow-xl hover:-translate-y-1 transition transform duration-300 relative overflow-hidden group">
                    <i class="fas fa-table text-6xl opacity-20 absolute right-4 bottom-4 group-hover:scale-110 transition duration-300"></i>
                    <h3 class="text-2xl font-bold mb-2 relative z-10"><i class="fas fa-database mr-2"></i> Database Excel</h3>
                    <p class="text-green-100 text-sm relative z-10">Buka Google Sheets untuk melihat rekapitulasi seluruh data pengajuan surat dari mahasiswa.</p>
                </a>
            </div>
        </div>

        <div id="menu-section" class="fade-in">
            <div class="text-center mb-10">
                <h2 class="text-3xl font-extrabold text-gray-900">Pusat Layanan Administrasi</h2>
                <p class="mt-2 text-gray-600">Pilih jenis surat yang ingin Anda ajukan. Data akan otomatis masuk ke sistem Admin.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div onclick="bukaForm('Surat Aktif')" class="bg-white rounded-xl shadow-md p-6 cursor-pointer hover:shadow-xl hover:-translate-y-1 transition transform duration-300 border-t-4 border-blue-500">
                    <div class="text-blue-500 text-4xl mb-4"><i class="fas fa-user-check"></i></div>
                    <h3 class="text-xl font-bold mb-2">Surat Aktif</h3>
                    <p class="text-gray-500 text-sm">Pengajuan surat keterangan mahasiswa aktif kuliah.</p>
                </div>
                <div onclick="bukaForm('Surat Tunjangan Gaji')" class="bg-white rounded-xl shadow-md p-6 cursor-pointer hover:shadow-xl hover:-translate-y-1 transition transform duration-300 border-t-4 border-green-500">
                    <div class="text-green-500 text-4xl mb-4"><i class="fas fa-file-invoice-dollar"></i></div>
                    <h3 class="text-xl font-bold mb-2">Surat Tunjangan Gaji</h3>
                    <p class="text-gray-500 text-sm">Pengajuan surat untuk keperluan tunjangan gaji orang tua.</p>
                </div>
                <div onclick="bukaForm('Surat Penelitian')" class="bg-white rounded-xl shadow-md p-6 cursor-pointer hover:shadow-xl hover:-translate-y-1 transition transform duration-300 border-t-4 border-purple-500">
                    <div class="text-purple-500 text-4xl mb-4"><i class="fas fa-microscope"></i></div>
                    <h3 class="text-xl font-bold mb-2">Surat Penelitian / Instrumen</h3>
                    <p class="text-gray-500 text-sm">Pengajuan surat izin uji validasi instrumen atau observasi sekolah.</p>
                </div>
            </div>
        </div>

        <div id="form-section" class="hidden fade-in bg-white rounded-xl shadow-lg p-8 max-w-3xl mx-auto border-t-4 border-blue-800">
            <button onclick="kembaliKeMenu()" class="text-blue-600 hover:text-blue-800 mb-6 flex items-center font-medium bg-blue-50 px-3 py-2 rounded-lg transition">
                <i class="fas fa-arrow-left mr-2"></i> Kembali ke Menu
            </button>
            <h2 id="form-title" class="text-2xl font-bold text-gray-800 mb-6 border-b pb-3">Formulir</h2>
            
            <form id="pengajuanForm" onsubmit="kirimData(event)">
                <input type="hidden" id="jenis_surat" name="jenis_surat">
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-5">
                    <div><label class="block text-sm font-bold text-gray-700 mb-1">Nama Mahasiswa</label><input type="text" id="nama" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-blue-500 outline-none" required></div>
                    <div><label class="block text-sm font-bold text-gray-700 mb-1">NPM</label><input type="text" id="npm" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-blue-500 outline-none" required></div>
                    <div class="field-akademik"><label class="block text-sm font-bold text-gray-700 mb-1">Semester</label><input type="text" id="semester" placeholder="Contoh: VI (Enam)" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-blue-500 outline-none"></div>
                    <div><label class="block text-sm font-bold text-gray-700 mb-1">Program Studi</label>
                        <select id="prodi" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-blue-500 outline-none" required>
                            <option value="">-- Pilih Program Studi --</option>
                            <option value="Pendidikan Bahasa Inggris">Pendidikan Bahasa Inggris</option>
                            <option value="Pendidikan Bahasa dan Sastra Indonesia">Pendidikan Bahasa dan Sastra Indonesia</option>
                            <option value="Pendidikan Biologi">Pendidikan Biologi</option>
                            <option value="Pendidikan Matematika">Pendidikan Matematika</option>
                        </select>
                    </div>
                    <div class="field-pribadi md:col-span-2"><label class="block text-sm font-bold text-gray-700 mb-1">Tempat, Tanggal Lahir</label><input type="text" id="ttl" placeholder="Contoh: Indramayu, 21 Juli 1998" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-blue-500 outline-none"></div>
                    <div class="field-pribadi md:col-span-2"><label class="block text-sm font-bold text-gray-700 mb-1">Alamat Lengkap</label><textarea id="alamat" rows="2" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-blue-500 outline-none"></textarea></div>
                    <div class="field-aktif"><label class="block text-sm font-bold text-gray-700 mb-1">No. WhatsApp</label><input type="text" id="whatsapp" placeholder="08xxxxxxxxxx" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-blue-500 outline-none"></div>
                    
                    <div class="field-tunjangan hidden bg-green-50 p-5 rounded-lg md:col-span-2 grid grid-cols-1 md:grid-cols-2 gap-4 border border-green-200 mt-2">
                        <h3 class="md:col-span-2 font-extrabold text-green-800 text-sm uppercase tracking-wide border-b border-green-200 pb-2">Data Orang Tua / Wali</h3>
                        <div><label class="block text-sm font-bold text-gray-700 mb-1">Nama Orang Tua</label><input type="text" id="nama_ortu" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-green-500 outline-none"></div>
                        <div><label class="block text-sm font-bold text-gray-700 mb-1">NIP</label><input type="text" id="nip_ortu" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-green-500 outline-none"></div>
                        <div class="md:col-span-2"><label class="block text-sm font-bold text-gray-700 mb-1">Pangkat dan Golongan</label><input type="text" id="pangkat_ortu" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-green-500 outline-none"></div>
                    </div>

                    <div class="field-penelitian hidden bg-purple-50 p-5 rounded-lg md:col-span-2 grid grid-cols-1 gap-4 border border-purple-200 mt-2">
                        <h3 class="font-extrabold text-purple-800 text-sm uppercase tracking-wide border-b border-purple-200 pb-2">Data Penelitian</h3>
                        <div><label class="block text-sm font-bold text-gray-700 mb-1">Tujuan Surat (Kepada Yth.)</label><input type="text" id="tujuan_surat" placeholder="Contoh: Kepala SMA Negeri 2 Indramayu" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-purple-500 outline-none"></div>
                        <div><label class="block text-sm font-bold text-gray-700 mb-1">Judul Skripsi / Penelitian</label><textarea id="judul_skripsi" rows="2" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-purple-500 outline-none"></textarea></div>
                    </div>
                </div>

                <div class="mt-8">
                    <button type="submit" id="btn-submit" class="w-full bg-blue-700 text-white font-bold py-3 px-4 rounded-lg hover:bg-blue-800 transition duration-300 flex justify-center items-center shadow-md">
                        <i class="fas fa-paper-plane mr-2"></i> <span id="btn-text">Kirim Permohonan Surat</span>
                    </button>
                </div>
            </form>
            <div id="pesan-sukses" class="hidden mt-6 bg-green-100 border-l-4 border-green-500 text-green-700 p-4 rounded shadow-sm">
                <strong class="font-bold block">Berhasil Terkirim!</strong><span class="text-sm">Data pengajuan surat telah diproses oleh sistem.</span>
            </div>
        </div>
    </main>

    <footer class="bg-gray-900 text-gray-400 text-center py-5 text-sm mt-auto border-t border-gray-800">
        &copy; 2026 Sistem Informasi Akademik - FKIP UNWIR. All rights reserved.
    </footer>

    <script>
        // --- KONFIGURASI LINK & KEAMANAN ---
        // 1. PIN UNTUK MASUK KE PANEL ADMIN
        const PIN_ADMIN_BENAR = "123456"; 
        
        // 2. URL GOOGLE APPS SCRIPT
        const APPS_SCRIPT_URL = 'https://script.google.com/macros/s/AKfycbweIkYrC6HddF88UnlVhWI4ufwI_t0Jfomkii2cFW5iShN2DdQBgJzVegMe0tzs6O1EkA/exec';

        // --- FUNGSI PANEL ADMIN ---
        function bukaModalLogin() {
            document.getElementById('login-modal').classList.remove('hidden');
            document.getElementById('pin-admin').value = '';
            document.getElementById('error-pin').classList.add('hidden');
            document.getElementById('pin-admin').focus();
        }

        function tutupModalLogin() {
            document.getElementById('login-modal').classList.add('hidden');
        }

        function cekEnter(event) {
            if (event.key === "Enter") validasiLogin();
        }

        function validasiLogin() {
            const pinInput = document.getElementById('pin-admin').value;
            if (pinInput === PIN_ADMIN_BENAR) {
                // PIN Benar: Sembunyikan form mahasiswa, buka panel admin
                tutupModalLogin();
                document.getElementById('menu-section').classList.add('hidden');
                document.getElementById('form-section').classList.add('hidden');
                document.getElementById('admin-dashboard').classList.remove('hidden');
            } else {
                // PIN Salah
                document.getElementById('error-pin').classList.remove('hidden');
            }
        }

        function logoutAdmin() {
            document.getElementById('admin-dashboard').classList.add('hidden');
            document.getElementById('menu-section').classList.remove('hidden');
        }

        // --- FUNGSI FORM MAHASISWA ---
        function bukaForm(jenis) {
            document.getElementById('menu-section').classList.add('hidden');
            document.getElementById('admin-dashboard').classList.add('hidden');
            document.getElementById('form-section').classList.remove('hidden');
            document.getElementById('form-title').innerText = "Form Pengajuan: " + jenis;
            document.getElementById('jenis_surat').value = jenis;
            document.getElementById('pesan-sukses').classList.add('hidden');
            document.getElementById('pengajuanForm').reset();
            document.getElementById('pengajuanForm').classList.remove('hidden');

            const fPribadi = document.querySelectorAll('.field-pribadi');
            const fAktif = document.querySelectorAll('.field-aktif');
            const fAkademik = document.querySelectorAll('.field-akademik');
            const fTunjangan = document.querySelector('.field-tunjangan');
            const fPenelitian = document.querySelector('.field-penelitian');

            fPribadi.forEach(el => el.classList.remove('hidden'));
            fAktif.forEach(el => el.classList.remove('hidden'));
            fAkademik.forEach(el => el.classList.remove('hidden'));
            fTunjangan.classList.add('hidden');
            fPenelitian.classList.add('hidden');

            if (jenis === 'Surat Tunjangan Gaji') {
                fAktif.forEach(el => el.classList.add('hidden')); 
                fTunjangan.classList.remove('hidden'); 
            } else if (jenis === 'Surat Penelitian') {
                fPribadi.forEach(el => el.classList.add('hidden'));
                fAktif.forEach(el => el.classList.add('hidden'));
                fAkademik.forEach(el => el.classList.add('hidden'));
                fPenelitian.classList.remove('hidden'); 
            }
        }

        function kembaliKeMenu() {
            document.getElementById('form-section').classList.add('hidden');
            document.getElementById('admin-dashboard').classList.add('hidden');
            document.getElementById('menu-section').classList.remove('hidden');
        }

        async function kirimData(event) {
            event.preventDefault();
            const btnSubmit = document.getElementById('btn-submit');
            btnSubmit.innerHTML = '<i class="fas fa-circle-notch fa-spin mr-2"></i> <span>Mengirim Data...</span>';
            btnSubmit.disabled = true;
            btnSubmit.classList.replace('bg-blue-700', 'bg-gray-500');

            const data = {
                jenis_surat: document.getElementById('jenis_surat').value,
                nama: document.getElementById('nama').value,
                npm: document.getElementById('npm').value,
                semester: document.getElementById('semester').value,
                prodi: document.getElementById('prodi').value,
                ttl: document.getElementById('ttl') ? document.getElementById('ttl').value : '',
                alamat: document.getElementById('alamat') ? document.getElementById('alamat').value : '',
                whatsapp: document.getElementById('whatsapp') ? document.getElementById('whatsapp').value : '',
                nama_ortu: document.getElementById('nama_ortu') ? document.getElementById('nama_ortu').value : '',
                nip_ortu: document.getElementById('nip_ortu') ? document.getElementById('nip_ortu').value : '',
                pangkat_ortu: document.getElementById('pangkat_ortu') ? document.getElementById('pangkat_ortu').value : '',
                judul_skripsi: document.getElementById('judul_skripsi') ? document.getElementById('judul_skripsi').value : '',
                tujuan_surat: document.getElementById('tujuan_surat') ? document.getElementById('tujuan_surat').value : ''
            };

            try {
                const response = await fetch(APPS_SCRIPT_URL, {
                    method: 'POST',
                    mode: 'no-cors',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(data)
                });
                document.getElementById('pengajuanForm').classList.add('hidden');
                document.getElementById('pesan-sukses').classList.remove('hidden');
            } catch (error) {
                alert("Terjadi kesalahan. Pastikan koneksi internet stabil.");
            } finally {
                btnSubmit.innerHTML = '<i class="fas fa-paper-plane mr-2"></i> <span>Kirim Permohonan Surat</span>';
                btnSubmit.disabled = false;
                btnSubmit.classList.replace('bg-gray-500', 'bg-blue-700');
                if (!document.getElementById('pesan-sukses').classList.contains('hidden')) {
                    setTimeout(() => { kembaliKeMenu(); }, 3000);
                }
            }
        }
    </script>
</body>
</html>

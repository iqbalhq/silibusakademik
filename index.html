<!DOCTYPE html>
<html lang="ms">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sistem Permohonan Aktiviti Silibus Akademik Pelajar - UiTM Perlis</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                    colors: {
                        uitm: {
                            purple: '#4c1d95',
                            darkPurple: '#2e1065',
                            gold: '#d97706',
                            lightGold: '#fef3c7',
                            accent: '#6d28d9'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Modern Micro-interactions & Glassmorphism */
        body {
            background: linear-gradient(135deg, #f8fafc 0%, #eef2ff 100%);
            min-height: 100vh;
        }

        .glass-card {
            background: rgba(255, 255, 255, 0.92);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(226, 232, 240, 0.8);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.05), 0 8px 10px -6px rgba(0, 0, 0, 0.01);
        }

        .input-field {
            transition: all 0.25s ease;
            border: 1.5px solid #cbd5e1;
        }

        .input-field:focus {
            border-color: #6d28d9;
            box-shadow: 0 0 0 4px rgba(109, 40, 217, 0.12);
            outline: none;
        }

        .step-active {
            background: linear-gradient(135deg, #4c1d95 0%, #6d28d9 100%);
            color: white;
            box-shadow: 0 4px 14px 0 rgba(76, 29, 149, 0.39);
        }

        /* PRINT STYLING - Strictly formatting like original PDF */
        @media print {
            @page {
                size: A4 portrait;
                margin: 1.2cm;
            }

            body {
                background: white !important;
                color: black !important;
                font-family: Arial, Helvetica, sans-serif !important;
                font-size: 10pt;
                -webkit-print-color-adjust: exact;
                print-color-adjust: exact;
            }

            .no-print {
                display: none !important;
            }

            .print-only {
                display: block !important;
            }

            .page-break {
                page-break-before: always;
            }

            .pdf-container {
                width: 100% !important;
                margin: 0 !important;
                padding: 0 !important;
                box-shadow: none !important;
                border: none !important;
                background: white !important;
            }

            table {
                width: 100% !important;
                page-break-inside: auto;
            }

            tr {
                page-break-inside: avoid;
                page-break-after: auto;
            }

            h4 {
                page-break-after: avoid;
            }

            table, th, td {
                border: 1px solid #000 !important;
                border-collapse: collapse !important;
                padding: 4px 6px !important;
            }

            .pdf-header {
                display: flex;
                justify-content: space-between;
                align-items: center;
                border-bottom: 2px solid #000;
                padding-bottom: 8px;
                margin-bottom: 15px;
            }
        }

        .print-only {
            display: none;
        }
    </style>
</head>
<body class="font-sans antialiased text-slate-800">

    <!-- Header Navigation Bar (Web Screen Only) -->
    <header class="no-print sticky top-0 z-40 bg-white/80 backdrop-filter backdrop-blur-md border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-4">
                <div class="w-12 h-12 rounded-xl bg-uitm-purple flex items-center justify-center text-white font-bold text-xl shadow-lg shadow-uitm-purple/30">
                    UiTM
                </div>
                <div>
                    <h1 class="font-bold text-slate-900 text-lg leading-tight">Portal Aktiviti Silibus Akademik</h1>
                    <p class="text-xs text-slate-500 font-medium">Bahagian Hal Ehwal Akademik (HEA) Cawangan Perlis</p>
                </div>
            </div>
            
            <div class="flex items-center space-x-3">
                <button onclick="openGoogleSheetHelpModal()" class="px-4 py-2 text-xs font-semibold text-uitm-purple bg-purple-50 hover:bg-purple-100 rounded-lg transition border border-purple-200 flex items-center gap-2">
                    <i class="fa-solid fa-file-excel text-emerald-600"></i> Integrasi Google Sheets
                </button>
                <span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-semibold bg-amber-100 text-amber-800 border border-amber-200">
                    Kod: UiTMPs/HEA/Permohonan Aktiviti-1/2024
                </span>
            </div>
        </div>
    </header>

    <!-- Main Container -->
    <main class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-8">

        <!-- Banner Intro (Web Screen Only) -->
        <div class="no-print glass-card rounded-2xl p-6 sm:p-8 mb-8 border-l-8 border-uitm-purple relative overflow-hidden">
            <div class="relative z-10 flex flex-col md:flex-row md:items-center md:justify-between gap-6">
                <div>
                    <span class="px-3 py-1 bg-purple-100 text-uitm-purple text-xs font-bold rounded-full uppercase tracking-wider">Permohonan Digital 2026</span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold text-slate-900 mt-2">Borang Aktiviti Pelajar Ikut Silibus</h2>
                    <p class="text-slate-600 mt-2 text-sm max-w-2xl">
                        Sistem borang pintar ini direka untuk memudahkan pensyarah membuat permohonan program akademik, pengiraan automatik belanjawan, integrasi ke Google Sheets, dan penjanaan format cetakan rasmi HEA.
                    </p>
                </div>
                <div class="flex flex-col sm:flex-row gap-3">
                    <button type="button" onclick="isiDataUjian()" class="px-4 py-2.5 bg-slate-100 hover:bg-slate-200 text-slate-700 font-semibold text-xs rounded-xl transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-wand-magic-sparkles text-amber-500"></i> Isi Data Contoh
                    </button>
                    <button type="button" onclick="window.print()" class="px-5 py-2.5 bg-slate-800 hover:bg-slate-900 text-white font-semibold text-xs rounded-xl shadow-md transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-print"></i> Cetak Format Borang
                    </button>
                </div>
            </div>
        </div>

        <!-- FORM CONTAINER -->
        <form id="permohonanForm" onsubmit="handleFormSubmit(event)" class="space-y-8">
            
            <!-- SECTION 1: PEMILIHAN FAKULTI & MAKLUMAT PROGRAM -->
            <div class="glass-card rounded-2xl p-6 sm:p-8 space-y-6">
                <div class="flex items-center gap-3 border-b border-slate-200 pb-4">
                    <div class="w-10 h-10 rounded-xl bg-purple-100 text-uitm-purple flex items-center justify-center font-bold text-lg">
                        1
                    </div>
                    <div>
                        <h3 class="text-lg font-bold text-slate-900">Maklumat Fakulti & Program Akademik</h3>
                        <p class="text-xs text-slate-500">Pilih Fakulti/Akademi dan perincian asas aktiviti yang dirancang</p>
                    </div>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <!-- Fakulti Selection (As per prompt requirement) -->
                    <div class="md:col-span-2">
                        <label class="block text-xs font-bold uppercase tracking-wider text-slate-700 mb-2">Fakulti / Akademi / Jabatan <span class="text-rose-500">*</span></label>
                        <select id="fakulti" required class="input-field w-full px-4 py-3 rounded-xl bg-white text-slate-800 font-semibold text-sm">
                            <option value="">-- Sila Pilih Fakulti / Akademi --</option>
                            <option value="Fakulti Sains Gunaan">Fakulti Sains Gunaan</option>
                            <option value="Fakulti Sains Komputer dan Matematik">Fakulti Sains Komputer dan Matematik</option>
                            <option value="Fakulti Sains Sukan dan Rekreasi">Fakulti Sains Sukan dan Rekreasi</option>
                            <option value="Fakulti Alam Bina">Fakulti Alam Bina</option>
                            <option value="Fakulti Perladangan dan Agroteknologi">Fakulti Perladangan dan Agroteknologi</option>
                            <option value="Fakulti Pengurusan Perniagaan">Fakulti Pengurusan Perniagaan</option>
                            <option value="Fakulti Perakaunan">Fakulti Perakaunan</option>
                            <option value="Akademik Pengajian Bahasa (APB)">Akademik Pengajian Bahasa (APB)</option>
                            <option value="Akademik Pengajian Islam dan Kontemporari (ACIS)">Akademik Pengajian Islam dan Kontemporari (ACIS)</option>
                        </select>
                    </div>

                    <div>
                        <label class="block text-xs font-bold uppercase tracking-wider text-slate-700 mb-2">Kod Program <span class="text-rose-500">*</span></label>
                        <input type="text" id="kodProgram" required placeholder="Contoh: CS251 / AS201" class="input-field w-full px-4 py-3 rounded-xl bg-white text-sm">
                    </div>

                    <div>
                        <label class="block text-xs font-bold uppercase tracking-wider text-slate-700 mb-2">Kod Kursus Silibus <span class="text-rose-500">*</span></label>
                        <input type="text" id="kodKursus" required placeholder="Contoh: CSC584 / BIO402" class="input-field w-full px-4 py-3 rounded-xl bg-white text-sm">
                    </div>

                    <div class="md:col-span-2">
                        <label class="block text-xs font-bold uppercase tracking-wider text-slate-700 mb-2">Nama Aktiviti <span class="text-rose-500">*</span></label>
                        <input type="text" id="namaAktiviti" required placeholder="Contoh: Lawatan Industri & Bengkel Pemantapan Silibus Datamining" class="input-field w-full px-4 py-3 rounded-xl bg-white text-sm">
                    </div>

                    <div>
                        <label class="block text-xs font-bold uppercase tracking-wider text-slate-700 mb-2">Tarikh Aktiviti (Mula - Akhir) <span class="text-rose-500">*</span></label>
                        <div class="flex items-center gap-2">
                            <input type="date" id="tarikhMula" required class="input-field w-full px-3 py-3 rounded-xl bg-white text-sm">
                            <span class="text-xs font-bold text-slate-400">-</span>
                            <input type="date" id="tarikhTamat" required class="input-field w-full px-3 py-3 rounded-xl bg-white text-sm">
                        </div>
                    </div>

                    <div>
                        <label class="block text-xs font-bold uppercase tracking-wider text-slate-700 mb-2">Masa (Mula - Akhir) <span class="text-rose-500">*</span></label>
                        <div class="flex items-center gap-2">
                            <input type="time" id="masaMula" required class="input-field w-full px-3 py-3 rounded-xl bg-white text-sm">
                            <span class="text-xs font-bold text-slate-400">-</span>
                            <input type="time" id="masaTamat" required class="input-field w-full px-3 py-3 rounded-xl bg-white text-sm">
                        </div>
                    </div>

                    <div>
                        <label class="block text-xs font-bold uppercase tracking-wider text-slate-700 mb-2">Tempat / Negeri Aktiviti <span class="text-rose-500">*</span></label>
                        <input type="text" id="tempat" required placeholder="Contoh: Penang Science Cluster, Pulau Pinang" class="input-field w-full px-4 py-3 rounded-xl bg-white text-sm">
                    </div>

                    <div>
                        <label class="block text-xs font-bold uppercase tracking-wider text-slate-700 mb-2">Bilangan Peserta Pelajar <span class="text-rose-500">*</span></label>
                        <input type="number" id="bilPeserta" min="1" required value="40" oninput="kiraPerbelanjaanAutomatik()" class="input-field w-full px-4 py-3 rounded-xl bg-white text-sm font-bold text-uitm-purple">
                    </div>
                </div>
            </div>

            <!-- SECTION 2: MAKLUMAT PEMOHON & PEGAWAI PENGIRING -->
            <div class="glass-card rounded-2xl p-6 sm:p-8 space-y-6">
                <div class="flex items-center gap-3 border-b border-slate-200 pb-4">
                    <div class="w-10 h-10 rounded-xl bg-purple-100 text-uitm-purple flex items-center justify-center font-bold text-lg">
                        2
                    </div>
                    <div>
                        <h3 class="text-lg font-bold text-slate-900">Maklumat Pemohon & Pegawai Pengiring</h3>
                        <p class="text-xs text-slate-500">Pensyarah / Penasihat Program dan Nisbah Pegawai (1 Pensyarah : 40 Pelajar)</p>
                    </div>
                </div>

                <!-- Detail Pemohon -->
                <div class="bg-purple-50/50 rounded-xl p-5 border border-purple-100 grid grid-cols-1 md:grid-cols-3 gap-4">
                    <div class="md:col-span-2">
                        <label class="block text-xs font-bold text-slate-700 mb-1">Nama Pemohon (Pensyarah) <span class="text-rose-500">*</span></label>
                        <input type="text" id="namaPemohon" required placeholder="Nama Penuh Pensyarah" class="input-field w-full px-3 py-2.5 rounded-lg bg-white text-sm">
                    </div>
                    <div>
                        <label class="block text-xs font-bold text-slate-700 mb-1">No. Pekerja <span class="text-rose-500">*</span></label>
                        <input type="text" id="noPekerja" required placeholder="Contoh: 234156" class="input-field w-full px-3 py-2.5 rounded-lg bg-white text-sm">
                    </div>
                    <div>
                        <label class="block text-xs font-bold text-slate-700 mb-1">Jawatan <span class="text-rose-500">*</span></label>
                        <input type="text" id="jawatanPemohon" required placeholder="Contoh: Pensyarah Kanan (DM52)" class="input-field w-full px-3 py-2.5 rounded-lg bg-white text-sm">
                    </div>
                    <div>
                        <label class="block text-xs font-bold text-slate-700 mb-1">No. Telefon (HP) <span class="text-rose-500">*</span></label>
                        <input type="text" id="noTel" required placeholder="01X-XXXXXXX" class="input-field w-full px-3 py-2.5 rounded-lg bg-white text-sm">
                    </div>
                    <div>
                        <label class="block text-xs font-bold text-slate-700 mb-1">Alamat E-Mel <span class="text-rose-500">*</span></label>
                        <input type="email" id="email" required placeholder="pensyarah@uitm.edu.my" class="input-field w-full px-3 py-2.5 rounded-lg bg-white text-sm">
                    </div>
                </div>

                <!-- Pegawai Pengiring Table -->
                <div class="space-y-3">
                    <div class="flex items-center justify-between">
                        <label class="text-xs font-bold uppercase tracking-wider text-slate-700">Senarai Pegawai Pengiring (Nisbah 1 : 40 Pelajar)</label>
                        <button type="button" onclick="tambahPegawaiPengiring()" class="text-xs font-bold text-uitm-purple bg-purple-100 hover:bg-purple-200 px-3 py-1.5 rounded-lg transition flex items-center gap-1">
                            <i class="fa-solid fa-plus"></i> Tambah Pegawai
                        </button>
                    </div>

                    <div class="overflow-x-auto rounded-xl border border-slate-200">
                        <table class="w-full text-left text-xs">
                            <thead class="bg-slate-100 text-slate-700 uppercase font-bold">
                                <tr>
                                    <th class="p-3 w-12 text-center">Bil</th>
                                    <th class="p-3">Nama Pegawai Pengiring</th>
                                    <th class="p-3">Jawatan</th>
                                    <th class="p-3">Gred</th>
                                    <th class="p-3 w-16 text-center no-print">Tindakan</th>
                                </tr>
                            </thead>
                            <tbody id="pengiringTableBody" class="divide-y divide-slate-200 bg-white">
                                <tr>
                                    <td class="p-3 text-center font-bold">1</td>
                                    <td class="p-2"><input type="text" class="pengiring-nama input-field w-full px-2 py-1.5 rounded text-xs" placeholder="Nama Pegawai 1"></td>
                                    <td class="p-2"><input type="text" class="pengiring-jawatan input-field w-full px-2 py-1.5 rounded text-xs" placeholder="Jawatan"></td>
                                    <td class="p-2"><input type="text" class="pengiring-gred input-field w-full px-2 py-1.5 rounded text-xs" placeholder="Gred (cth: DM52)"></td>
                                    <td class="p-2 text-center no-print">-</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>

            <!-- SECTION 3: PENCERAMAH, FASILITATOR & JUSTIFIKASI -->
            <div class="glass-card rounded-2xl p-6 sm:p-8 space-y-6">
                <div class="flex items-center gap-3 border-b border-slate-200 pb-4">
                    <div class="w-10 h-10 rounded-xl bg-purple-100 text-uitm-purple flex items-center justify-center font-bold text-lg">
                        3
                    </div>
                    <div>
                        <h3 class="text-lg font-bold text-slate-900">Penceramah, Fasilitator & Justifikasi Program</h3>
                        <p class="text-xs text-slate-500">Lengkapkan maklumat sokongan dan keperluan program silibus</p>
                    </div>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <!-- Penceramah Jemputan -->
                    <div class="space-y-3">
                        <div class="flex items-center justify-between">
                            <label class="block text-xs font-bold uppercase tracking-wider text-slate-700">Penceramah (Sertakan CV & Masukkan Slot Tentatif)</label>
                            <button type="button" onclick="tambahPenceramahInfo()" class="text-[10px] font-bold text-uitm-purple bg-purple-100 hover:bg-purple-200 px-3 py-1 rounded-lg transition flex items-center gap-1"><i class="fa-solid fa-plus"></i> Tambah</button>
                        </div>
                        <div id="penceramahInfoList" class="space-y-2">
                            <div class="flex gap-2 items-center">
                                <input type="text" class="input-penceramah input-field w-full px-3 py-2 rounded-xl text-xs bg-white" placeholder="1. Nama Penceramah & Organisasi">
                            </div>
                        </div>
                    </div>

                    <!-- Fasilitator Staf & Pelajar -->
                    <div class="space-y-3">
                        <div class="flex items-center justify-between">
                            <label class="block text-xs font-bold uppercase tracking-wider text-slate-700">Fasilitator (Staf / Pelajar)</label>
                            <button type="button" onclick="tambahFasilitatorInfo()" class="text-[10px] font-bold text-uitm-purple bg-purple-100 hover:bg-purple-200 px-3 py-1 rounded-lg transition flex items-center gap-1"><i class="fa-solid fa-plus"></i> Tambah</button>
                        </div>
                        <div id="fasilitatorInfoList" class="space-y-2">
                            <div class="flex gap-2 items-center">
                                <input type="text" class="input-fasilitator input-field w-full px-3 py-2 rounded-xl text-xs bg-white" placeholder="Nama / Jawatan / Gred (Staf/Pelajar)">
                            </div>
                        </div>
                    </div>

                    <!-- Justifikasi Program -->
                    <div class="md:col-span-2 space-y-4">
                        <div>
                            <label class="block text-xs font-bold uppercase tracking-wider text-slate-700 mb-1">1. Ringkasan Program & Objektif <span class="text-rose-500">*</span></label>
                            <textarea id="ringkasanProgram" required rows="3" placeholder="Terangkan secara ringkas aktiviti silibus dan hubungkaitnya dengan pencapaian kursus (CLO/PLO)..." class="input-field w-full p-3 rounded-xl bg-white text-xs"></textarea>
                        </div>
                        <div>
                            <label class="block text-xs font-bold uppercase tracking-wider text-slate-700 mb-1">2. Implikasi Sekiranya Aktiviti Silibus Ini Tidak Dapat Dijalankan <span class="text-rose-500">*</span></label>
                            <textarea id="implikasiProgram" required rows="2" placeholder="Impak kepada pelajar dan pemenuhan elemen penilaian silibus..." class="input-field w-full p-3 rounded-xl bg-white text-xs"></textarea>
                        </div>
                    </div>

                    <!-- Tentatif Aktiviti -->
                    <div class="md:col-span-2">
                        <label class="block text-xs font-bold uppercase tracking-wider text-slate-700 mb-1">Tentatif Aktiviti Ringkas <span class="text-rose-500">*</span></label>
                        <textarea id="tentatifAktiviti" required rows="4" placeholder="Hari 1: 08.00 pagi - Bertolak ke lokasi, 10.00 pagi - Slot Penceramah 1...&#10;Hari 2: 09.00 pagi - Sesi Amali / Fasilitator..." class="input-field w-full p-3 rounded-xl bg-white text-xs font-mono"></textarea>
                    </div>
                </div>
            </div>

            <!-- SECTION 4: ANGGARAN PERBELANJAAN (Dynamic Calculator based on UiTM Circular) -->
            <div class="glass-card rounded-2xl p-6 sm:p-8 space-y-6">
                <div class="flex items-center justify-between border-b border-slate-200 pb-4">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-xl bg-purple-100 text-uitm-purple flex items-center justify-center font-bold text-lg">
                            4
                        </div>
                        <div>
                            <h3 class="text-lg font-bold text-slate-900">Anggaran Perbelanjaan & Kewangan</h3>
                            <p class="text-xs text-slate-500">Kiraan automatik berpandukan Pekeliling Perbendaharaan & Naib Canselor UiTM</p>
                        </div>
                    </div>
                    <span class="text-xs font-bold px-3 py-1 bg-emerald-100 text-emerald-800 rounded-full border border-emerald-300">
                        Kiraan Auto Aktif
                    </span>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">

                    <!-- Makanan & Penginapan Pelajar -->
                    <div class="bg-slate-50 rounded-xl p-4 border border-slate-200 space-y-3">
                        <h4 class="font-bold text-xs uppercase text-uitm-purple tracking-wider border-b border-slate-200 pb-2">a) Makanan & Penginapan Pelajar</h4>
                        
                        <div class="grid grid-cols-2 gap-2 text-xs">
                            <div>
                                <label class="block font-semibold text-slate-600">Bil Hari Makan</label>
                                <input type="number" id="bilHariMakan" min="0" value="1" oninput="kiraPerbelanjaanAutomatik()" class="input-field w-full p-2 rounded bg-white font-bold">
                            </div>
                            <div>
                                <label class="block font-semibold text-slate-600">Elaun Makan/Hari (RM)</label>
                                <input type="number" id="kadarMakan" min="0" value="16" oninput="kiraPerbelanjaanAutomatik()" class="input-field w-full p-2 rounded bg-white font-bold">
                                <span class="text-[10px] text-slate-400">(Minum Pagi RM4, T/Hari RM6, Malam RM6)</span>
                            </div>
                        </div>

                        <div class="grid grid-cols-2 gap-2 text-xs pt-2">
                            <div>
                                <label class="block font-semibold text-slate-600">Bil Malam Penginapan</label>
                                <input type="number" id="bilMalamPenginapan" min="0" value="0" oninput="kiraPerbelanjaanAutomatik()" class="input-field w-full p-2 rounded bg-white font-bold">
                            </div>
                            <div>
                                <label class="block font-semibold text-slate-600">Kadar Penginapan/Malam (RM)</label>
                                <input type="number" id="kadarPenginapan" min="0" value="15" oninput="kiraPerbelanjaanAutomatik()" class="input-field w-full p-2 rounded bg-white font-bold">
                                <span class="text-[10px] text-slate-400">(IPT RM15 / Hotel Max RM50)</span>
                            </div>
                        </div>

                        <div class="pt-2 flex justify-between items-center text-xs font-bold border-t border-slate-200">
                            <span>Subtotal Makanan & Penginapan:</span>
                            <span class="text-uitm-purple" id="subtotalMakananPenginapan">RM 640.00</span>
                        </div>
                    </div>

                    <!-- Honorarium Penceramah & Fasilitator -->
                    <div class="bg-slate-50 rounded-xl p-4 border border-slate-200 space-y-3">
                        <h4 class="font-bold text-xs uppercase text-uitm-purple tracking-wider border-b border-slate-200 pb-2">b) Honorarium Penceramah / Fasilitator</h4>

                        <div class="space-y-3 text-xs">
                            <div class="flex items-center justify-between">
                                <label class="block font-semibold text-slate-600">Jawatan Penceramah (Kadar/Jam)</label>
                                <button type="button" onclick="tambahKiraanPenceramah()" class="text-[10px] font-bold text-uitm-purple bg-purple-100 hover:bg-purple-200 px-2 py-1 rounded transition flex items-center gap-1"><i class="fa-solid fa-plus"></i> Tambah Penceramah</button>
                            </div>
                            <div id="kiraanPenceramahList" class="space-y-2">
                                <div class="kiraan-penceramah-row flex items-center gap-2">
                                    <select onchange="kiraPerbelanjaanAutomatik()" class="kadar-penceramah input-field w-full p-2 rounded bg-white font-bold text-slate-700">
                                        <option value="300">Pengurusan Tertinggi (RM300)</option>
                                        <option value="200">Gred 53 & Gred 54 (RM200)</option>
                                        <option value="150" selected>Gred 45 & Gred 52 (RM150)</option>
                                        <option value="120">Gred 41 & Gred 44 (RM120)</option>
                                        <option value="80">Kumpulan Sokongan (RM80)</option>
                                    </select>
                                    <input type="number" min="0" value="2" oninput="kiraPerbelanjaanAutomatik()" class="jam-penceramah input-field w-20 p-2 rounded bg-white font-bold text-center" placeholder="Jam">
                                </div>
                            </div>
                            
                            <div class="flex items-center justify-between border-t border-slate-200 pt-3">
                                <label class="block font-semibold text-slate-600">Jam Fasilitator Pelajar</label>
                                <button type="button" onclick="tambahKiraanFasilitator()" class="text-[10px] font-bold text-uitm-purple bg-purple-100 hover:bg-purple-200 px-2 py-1 rounded transition flex items-center gap-1"><i class="fa-solid fa-plus"></i> Tambah Fasilitator</button>
                            </div>
                            <div id="kiraanFasilitatorList" class="space-y-2">
                                <div class="kiraan-fasilitator-row flex items-center gap-2">
                                    <span class="text-xs font-semibold text-slate-500 w-full">(Kadar RM15.00 / jam)</span>
                                    <input type="number" min="0" value="0" oninput="kiraPerbelanjaanAutomatik()" class="jam-fasilitator input-field w-20 p-2 rounded bg-white font-bold text-center" placeholder="Jam">
                                </div>
                            </div>
                        </div>

                        <div class="pt-6 flex justify-between items-center text-xs font-bold border-t border-slate-200">
                            <span>Subtotal Honorarium:</span>
                            <span class="text-uitm-purple" id="subtotalHonorarium">RM 300.00</span>
                        </div>
                    </div>

                    <!-- Hadiah & Keperluan Program -->
                    <div class="bg-slate-50 rounded-xl p-4 border border-slate-200 space-y-3">
                        <h4 class="font-bold text-xs uppercase text-uitm-purple tracking-wider border-b border-slate-200 pb-2">c & d) Hadiah & Keperluan Program</h4>

                        <div class="space-y-2 text-xs">
                            <div class="flex items-center justify-between">
                                <label class="font-semibold text-slate-600">Hadiah Pertandingan (RM100, RM75, RM70)</label>
                                <input type="number" id="jumlahHadiah" min="0" value="0" oninput="kiraPerbelanjaanAutomatik()" class="input-field w-28 p-1.5 rounded bg-white text-right font-bold">
                            </div>
                            <div class="flex items-center justify-between">
                                <label class="font-semibold text-slate-600">Peralatan (RM4 x Pelajar, max RM1000)</label>
                                <input type="number" id="jumlahPeralatan" min="0" value="160" oninput="kiraPerbelanjaanAutomatik()" class="input-field w-28 p-1.5 rounded bg-white text-right font-bold">
                            </div>
                            <div class="flex items-center justify-between">
                                <label class="font-semibold text-slate-600">Lain-Lain Perbelanjaan (P&P)</label>
                                <input type="number" id="jumlahLainLain" min="0" value="0" oninput="kiraPerbelanjaanAutomatik()" class="input-field w-28 p-1.5 rounded bg-white text-right font-bold">
                            </div>
                        </div>

                        <div class="pt-2 flex justify-between items-center text-xs font-bold border-t border-slate-200">
                            <span>Subtotal Keperluan & Hadiah:</span>
                            <span class="text-uitm-purple" id="subtotalKeperluan">RM 160.00</span>
                        </div>
                    </div>

                    <!-- Summary & Transport Requirements -->
                    <div class="bg-purple-900 text-white rounded-xl p-5 flex flex-col justify-between shadow-lg">
                        <div>
                            <span class="text-xs uppercase font-bold text-purple-300 tracking-wider">Jumlah Keseluruhan Dipohon</span>
                            <div class="text-3xl font-black text-amber-400 mt-1" id="jumlahBesarPerbelanjaan">RM 1,100.00</div>
                            <p class="text-[11px] text-purple-200 mt-2">Dihantar terus ke Pejabat Hal Ehwal Akademik Cawangan Perlis untuk semakan bajet pengurusan.</p>
                        </div>

                        <div class="mt-4 pt-3 border-t border-purple-800 text-xs space-y-2">
                            <span class="font-bold text-amber-300">Pengangkutan Kenderaan UiTM:</span>
                            <div class="flex items-center gap-4">
                                <label class="flex items-center gap-1.5 cursor-pointer">
                                    <input type="radio" name="pengangkutan" value="Perlu" checked class="accent-amber-400"> Perlu Kenderaan
                                </label>
                                <label class="flex items-center gap-1.5 cursor-pointer">
                                    <input type="radio" name="pengangkutan" value="Tidak Perlu" class="accent-amber-400"> Tidak Perlu
                                </label>
                            </div>
                            <input type="text" id="jenisKenderaan" placeholder="Nyatakan Jenis (Bas / Van / Coaster) & Bil Penumpang" class="w-full px-3 py-1.5 rounded text-xs text-slate-800 bg-white">
                        </div>
                    </div>

                </div>
            </div>

            <!-- SECTION 5: MUAT NAIK DOKUMEN SOKONGAN -->
            <div class="glass-card rounded-2xl p-6 sm:p-8 space-y-6">
                <div class="flex items-center gap-3 border-b border-slate-200 pb-4">
                    <div class="w-10 h-10 rounded-xl bg-purple-100 text-uitm-purple flex items-center justify-center font-bold text-lg">
                        5
                    </div>
                    <div>
                        <h3 class="text-lg font-bold text-slate-900">Muat Naik Dokumen Sokongan</h3>
                        <p class="text-xs text-slate-500">Sila muat naik lampiran berkaitan dalam format PDF / Excel</p>
                    </div>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <!-- 1. Silibus -->
                    <div>
                        <label class="block text-xs font-bold uppercase tracking-wider text-slate-700 mb-2">1. Silibus Kursus <span class="text-rose-500">*</span></label>
                        <input type="file" id="failSilibus" accept=".pdf" required class="block w-full text-sm text-slate-500 file:mr-4 file:py-2.5 file:px-4 file:rounded-xl file:border-0 file:text-xs file:font-semibold file:bg-purple-50 file:text-uitm-purple hover:file:bg-purple-100 input-field rounded-xl bg-white border border-slate-200 p-1.5">
                    </div>

                    <!-- 2. Senarai Bilangan Pelajar -->
                    <div>
                        <label class="block text-xs font-bold uppercase tracking-wider text-slate-700 mb-2">2. Senarai Nama & Bilangan Pelajar <span class="text-rose-500">*</span></label>
                        <input type="file" id="failSenaraiPelajar" accept=".pdf,.xls,.xlsx" required class="block w-full text-sm text-slate-500 file:mr-4 file:py-2.5 file:px-4 file:rounded-xl file:border-0 file:text-xs file:font-semibold file:bg-purple-50 file:text-uitm-purple hover:file:bg-purple-100 input-field rounded-xl bg-white border border-slate-200 p-1.5">
                    </div>

                    <!-- 3. CV Penceramah -->
                    <div>
                        <label class="block text-xs font-bold uppercase tracking-wider text-slate-700 mb-2">3. CV Penceramah / Profil Syarikat <span class="text-rose-500">*</span></label>
                        <input type="file" id="failCVPenceramah" accept=".pdf" required class="block w-full text-sm text-slate-500 file:mr-4 file:py-2.5 file:px-4 file:rounded-xl file:border-0 file:text-xs file:font-semibold file:bg-purple-50 file:text-uitm-purple hover:file:bg-purple-100 input-field rounded-xl bg-white border border-slate-200 p-1.5">
                    </div>

                    <!-- 4. Kertas Kerja -->
                    <div>
                        <label class="block text-xs font-bold uppercase tracking-wider text-slate-700 mb-2">4. Kertas Kerja Lengkap <span class="text-rose-500">*</span></label>
                        <input type="file" id="failKertasKerja" accept=".pdf" required class="block w-full text-sm text-slate-500 file:mr-4 file:py-2.5 file:px-4 file:rounded-xl file:border-0 file:text-xs file:font-semibold file:bg-purple-50 file:text-uitm-purple hover:file:bg-purple-100 input-field rounded-xl bg-white border border-slate-200 p-1.5">
                    </div>
                </div>
            </div>

            <!-- SECTION 6: PENGESAHAN & ULASAN KELULUSAN (Workflow Required by User Prompt) -->
            <div class="glass-card rounded-2xl p-6 sm:p-8 space-y-6">
                <div class="flex items-center gap-3 border-b border-slate-200 pb-4">
                    <div class="w-10 h-10 rounded-xl bg-purple-100 text-uitm-purple flex items-center justify-center font-bold text-lg">
                        6
                    </div>
                    <div>
                        <h3 class="text-lg font-bold text-slate-900">Pengesahan Pemohon & Semakan Kelulusan</h3>
                        <p class="text-xs text-slate-500">Perakuan Pemohon, Ketua Pusat Pengajian (KPP) & Timbalan Rektor Akademik</p>
                    </div>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">

                    <!-- Pengesahan Pemohon -->
                    <div class="bg-slate-50 rounded-xl p-4 border border-slate-200 space-y-3">
                        <div class="flex items-center gap-2 border-b border-slate-200 pb-2">
                            <i class="fa-solid fa-file-signature text-uitm-purple"></i>
                            <h4 class="font-bold text-xs uppercase text-slate-800">1. Pengesahan Pemohon</h4>
                        </div>
                        <p class="text-[11px] text-slate-600">Saya mengesahkan maklumat di atas adalah benar dan mematuhi syarat silibus akademik UiTM.</p>
                        
                        <div class="pt-4 border-t border-slate-200 space-y-2 text-xs">
                            <div class="font-bold text-slate-800" id="previewNamaPemohon">Nama Pemohon: [Diisi Dalam Borang]</div>
                            <div class="text-slate-500">Tarikh Hantar: <span id="tarikhHantarCurrent">28/08/2026</span></div>
                            <div class="p-2 bg-emerald-50 text-emerald-700 text-[10px] rounded font-semibold border border-emerald-200 flex items-center gap-1">
                                <i class="fa-solid fa-check-circle"></i> Digital Sign Verified
                            </div>
                        </div>
                    </div>

                    <!-- Ulasan KPP -->
                    <div class="bg-slate-50 rounded-xl p-4 border border-slate-200 space-y-3">
                        <div class="flex items-center gap-2 border-b border-slate-200 pb-2">
                            <i class="fa-solid fa-user-tie text-uitm-purple"></i>
                            <h4 class="font-bold text-xs uppercase text-slate-800">2. Ulasan Ketua Pusat Pengajian</h4>
                        </div>
                        <textarea id="ulasanKPP" rows="3" placeholder="Ulasan KPP: Mengesahkan kertas kerja telah disemak & bersetuju aktiviti dijalankan..." class="input-field w-full p-2.5 rounded bg-white text-xs"></textarea>
                        <div class="text-[10px] text-slate-400">*Boleh diisi oleh KPP atau disemak semasa kelulusan</div>
                    </div>

                    <!-- Ulasan Timbalan Rektor (Akademik) -->
                    <div class="bg-slate-50 rounded-xl p-4 border border-slate-200 space-y-3">
                        <div class="flex items-center gap-2 border-b border-slate-200 pb-2">
                            <i class="fa-solid fa-stamp text-uitm-purple"></i>
                            <h4 class="font-bold text-xs uppercase text-slate-800">3. Ulasan Timbalan Rektor (HEA)</h4>
                        </div>
                        <div class="space-y-2 text-xs">
                            <div class="flex items-center gap-4">
                                <label class="flex items-center gap-1 font-bold text-emerald-700">
                                    <input type="radio" name="statusKelulusan" value="LULUS" checked class="accent-emerald-600"> LULUS
                                </label>
                                <label class="flex items-center gap-1 font-bold text-rose-700">
                                    <input type="radio" name="statusKelulusan" value="TIDAK LULUS" class="accent-rose-600"> TIDAK LULUS
                                </label>
                            </div>
                            <div>
                                <label class="block font-semibold text-slate-600 text-[11px]">Peruntukan Diluluskan (RM)</label>
                                <input type="number" id="peruntukanDiluluskan" placeholder="Diisi oleh Pegawai HEA" class="input-field w-full p-2 rounded bg-amber-50 font-bold text-slate-800">
                                <p class="text-[10px] text-slate-500 mt-1">*Nota: Peruntukan diluluskan hanya dipaparkan pada salinan cetakan PDF rasmi HEA.</p>
                            </div>
                        </div>
                    </div>

                </div>
            </div>

            <!-- SUBMIT BUTTON AREA (Web View) -->
            <div class="no-print flex flex-col sm:flex-row items-center justify-between gap-4 bg-white p-6 rounded-2xl border border-slate-200 shadow-xl">
                <div class="text-xs text-slate-500 flex items-center gap-2">
                    <i class="fa-solid fa-shield-halved text-uitm-purple text-base"></i>
                    <span>Data borang dikodkan secara automatik untuk disinkronkan bersama Google Sheets & HEA Database.</span>
                </div>
                
                <div class="flex items-center gap-3 w-full sm:w-auto">
                    <button type="button" onclick="resetForm()" class="w-1/2 sm:w-auto px-5 py-3 text-xs font-bold text-slate-600 hover:bg-slate-100 rounded-xl transition">
                        Reset Borang
                    </button>
                    <button type="submit" class="w-1/2 sm:w-auto px-8 py-3 bg-gradient-to-r from-uitm-purple to-uitm-accent hover:opacity-95 text-white font-bold text-sm rounded-xl shadow-lg shadow-uitm-purple/30 transition transform hover:-translate-y-0.5 flex items-center justify-center gap-2">
                        <i class="fa-solid fa-paper-plane"></i> Hantar & Jana PDF
                    </button>
                </div>
            </div>
        </form>

        <!-- OFFICIAL PDF PRINTABLE LAYOUT (Matches exact layout of UiTM PDF Document) -->
        <div id="pdfPrintSection" class="print-only pdf-container p-4 bg-white text-black font-sans">
            
            <!-- PAGE 1 OF PDF -->
            <div class="pdf-header text-center">
                <table style="width: 100%; border: none !important;">
                    <tr style="border: none !important;">
                        <td style="width: 20%; border: none !important; text-align: left;">
                            <strong style="font-size: 14pt; color: #4c1d95;">UiTM</strong>
                        </td>
                        <td style="width: 60%; border: none !important; text-align: center;">
                            <h3 style="margin: 0; font-size: 11pt; font-weight: bold;">UNIVERSITI TEKNOLOGI MARA CAWANGAN PERLIS</h3>
                            <h4 style="margin: 2px 0; font-size: 10pt; font-weight: bold;">BAHAGIAN HAL EHWAL AKADEMIK</h4>
                            <p style="margin: 0; font-size: 9pt;">PERMOHONAN AKTIVITI SILIBUS AKADEMIK PELAJAR</p>
                        </td>
                        <td style="width: 20%; border: none !important; text-align: right; font-size: 8pt;">
                            UiTMPs/HEA/Permohonan Aktiviti-1/2024
                        </td>
                    </tr>
                </table>
            </div>

            <table style="width: 100%; margin-top: 10px; font-size: 9pt;">
                <tr>
                    <td style="width: 25%; font-weight: bold; bg-color: #f3f4f6;">FAKULTI / JABATAN:</td>
                    <td colspan="3" id="pdfFakulti" style="font-weight: bold;">-</td>
                </tr>
                <tr>
                    <td style="font-weight: bold;">KOD PROGRAM:</td>
                    <td id="pdfKodProgram" style="width: 25%;"></td>
                    <td style="font-weight: bold; width: 25%;">KOD KURSUS:</td>
                    <td id="pdfKodKursus" style="width: 25%;"></td>
                </tr>
                <tr>
                    <td style="font-weight: bold;">NAMA AKTIVITI:</td>
                    <td colspan="3" id="pdfNamaAktiviti" style="font-weight: bold;"></td>
                </tr>
                <tr>
                    <td style="font-weight: bold;">TARIKH / HARI:</td>
                    <td id="pdfTarikhHari"></td>
                    <td style="font-weight: bold;">MASA:</td>
                    <td id="pdfMasa"></td>
                </tr>
                <tr>
                    <td style="font-weight: bold;">TEMPAT / NEGERI:</td>
                    <td id="pdfTempat"></td>
                    <td style="font-weight: bold;">BIL. PESERTA:</td>
                    <td id="pdfBilPeserta"></td>
                </tr>
                <tr>
                    <td style="font-weight: bold;">JUMLAH DIPOHON:</td>
                    <td id="pdfJumlahDipohon" style="font-weight: bold; color: green;"></td>
                    <td style="font-weight: bold; background-color: #fef3c7;">JUMLAH DILULUSKAN:</td>
                    <td id="pdfJumlahDiluluskan" style="font-weight: bold; background-color: #fef3c7;">(Diisi Pegawai HEA)</td>
                </tr>
            </table>

            <h4 style="font-size: 9pt; font-weight: bold; margin-top: 12px; margin-bottom: 4px; background: #eee; padding: 2px;">MAKLUMAT PEMOHON (PENSYARAH / PENASIAT PROGRAM)</h4>
            <table style="width: 100%; font-size: 9pt;">
                <tr>
                    <td style="width: 20%; font-weight: bold;">NAMA PEMOHON:</td>
                    <td id="pdfNamaPemohon" style="width: 40%;"></td>
                    <td style="width: 15%; font-weight: bold;">NO. PEKERJA:</td>
                    <td id="pdfNoPekerja" style="width: 25%;"></td>
                </tr>
                <tr>
                    <td style="font-weight: bold;">JAWATAN:</td>
                    <td id="pdfJawatanPemohon"></td>
                    <td style="font-weight: bold;">NO. TELEFON (HP):</td>
                    <td id="pdfNoTel"></td>
                </tr>
                <tr>
                    <td style="font-weight: bold;">E-MAIL:</td>
                    <td colspan="3" id="pdfEmail"></td>
                </tr>
            </table>

            <h4 style="font-size: 9pt; font-weight: bold; margin-top: 12px; margin-bottom: 4px; background: #eee; padding: 2px;">SENARAI PEGAWAI PENGIRING (Nisbah 1 Pensyarah : 40 Pelajar)</h4>
            <table style="width: 100%; font-size: 8.5pt;" id="pdfTablePengiring">
                <thead>
                    <tr style="background-color: #f3f4f6;">
                        <th style="width: 8%; text-align: center;">Bil</th>
                        <th>Nama Pegawai Pengiring</th>
                        <th style="width: 30%;">Jawatan</th>
                        <th style="width: 20%;">Gred</th>
                    </tr>
                </thead>
                <tbody id="pdfPengiringBody">
                    <!-- Dynamic -->
                </tbody>
            </table>

            <div class="page-break"></div>

            <!-- PAGE 2 OF PDF -->
            <h4 style="font-size: 9pt; font-weight: bold; margin-top: 10px; margin-bottom: 4px; background: #eee; padding: 2px;">PENCERAMAH & FASILITATOR</h4>
            <table style="width: 100%; font-size: 8.5pt;">
                <tr>
                    <td style="width: 25%; font-weight: bold;">PENCERAMAH:</td>
                    <td id="pdfPenceramah"></td>
                </tr>
                <tr>
                    <td style="font-weight: bold;">FASILITATOR:</td>
                    <td id="pdfFasilitatorStaf"></td>
                </tr>
            </table>

            <h4 style="font-size: 9pt; font-weight: bold; margin-top: 12px; margin-bottom: 4px; background: #eee; padding: 2px;">JUSTIFIKASI PROGRAM & IMPLIKASI</h4>
            <div style="font-size: 8.5pt; border: 1px solid #000; padding: 6px; margin-bottom: 8px;">
                <strong>1. Ringkasan Program:</strong>
                <p id="pdfRingkasan" style="margin: 3px 0 8px 0;"></p>
                <strong>2. Implikasi Sekiranya Aktiviti Silibus Tidak Dapat Dijalankan:</strong>
                <p id="pdfImplikasi" style="margin: 3px 0 0 0;"></p>
            </div>

            <h4 style="font-size: 9pt; font-weight: bold; margin-top: 10px; margin-bottom: 4px; background: #eee; padding: 2px;">TENTATIF AKTIVITI RINGKAS</h4>
            <div style="font-size: 8.5pt; border: 1px solid #000; padding: 6px; white-space: pre-wrap;" id="pdfTentatif"></div>

            <h4 style="font-size: 9pt; font-weight: bold; margin-top: 12px; margin-bottom: 4px; background: #eee; padding: 2px;">RINGKASAN ANGGARAN PERBELANJAAN DIPOHON</h4>
            <table style="width: 100%; font-size: 8.5pt;">
                <tr style="background: #f9fafb;">
                    <th>Perkara / Butiran Perbelanjaan</th>
                    <th style="width: 25%; text-align: right;">Jumlah (RM)</th>
                </tr>
                <tr>
                    <td>a) Makanan dan Penginapan Pelajar</td>
                    <td style="text-align: right;" id="pdfSubMakanan">RM 0.00</td>
                </tr>
                <tr>
                    <td>b) Honorarium / Bayaran Penceramah & Fasilitator</td>
                    <td style="text-align: right;" id="pdfSubHonorarium">RM 0.00</td>
                </tr>
                <tr>
                    <td>c & d) Hadiah, Keperluan Program & Lain-lain (P&P)</td>
                    <td style="text-align: right;" id="pdfSubKeperluan">RM 0.00</td>
                </tr>
                <tr style="font-weight: bold; background: #f3f4f6;">
                    <td>JUMLAH KESELURUHAN DIPOHON:</td>
                    <td style="text-align: right; font-size: 10pt;" id="pdfJumlahBesar">RM 0.00</td>
                </tr>
                <tr>
                    <td>Keperluan Pengangkutan UiTM:</td>
                    <td style="text-align: right;" id="pdfPengangkutanInfo">Tidak Perlu</td>
                </tr>
            </table>

            <h4 style="font-size: 9pt; font-weight: bold; margin-top: 15px; margin-bottom: 4px; background: #eee; padding: 2px;">PENGESAHAN & KELULUSAN</h4>
            <table style="width: 100%; font-size: 8.5pt; text-align: center;">
                <tr>
                    <td style="width: 33%; height: 70px; vertical-align: top; text-align: left;">
                        <strong>Pengesahan Pemohon:</strong><br><br>
                        Tandatangan: <i>(Disahkan secara digital)</i><br>
                        Nama: <span id="pdfSignNama"></span><br>
                        Tarikh: <span id="pdfSignTarikh"></span>
                    </td>
                    <td style="width: 33%; vertical-align: top; text-align: left;">
                        <strong>Ulasan KPP:</strong><br>
                        <span id="pdfSignKPP">Disemak dan disokong.</span><br><br>
                        Tandatangan: _________________<br>
                        Tarikh: ____________________
                    </td>
                    <td style="width: 33%; vertical-align: top; text-align: left; background: #fcf8e3;">
                        <strong>Kelulusan Timbalan Rektor (HEA):</strong><br>
                        Status: <span id="pdfStatusKelulusan" style="font-weight: bold;">LULUS</span><br>
                        Peruntukan Diluluskan: <strong id="pdfPeruntukanPrint" style="color: #b91c1c;">RM ____________</strong><br><br>
                        Tandatangan: _________________<br>
                        Tarikh: ____________________
                    </td>
                </tr>
            </table>

        </div>
    </main>

    <!-- SUCCESS MODAL POPUP -->
    <div id="successModal" class="no-print fixed inset-0 z-50 flex items-center justify-center p-4 bg-slate-900/60 backdrop-blur-sm hidden">
        <div class="bg-white rounded-3xl max-w-lg w-full p-6 sm:p-8 shadow-2xl border border-slate-100 transform transition-all text-center space-y-5">
            <div class="w-16 h-16 bg-emerald-100 text-emerald-600 rounded-2xl flex items-center justify-center mx-auto text-2xl shadow-inner">
                <i class="fa-solid fa-circle-check"></i>
            </div>

            <div>
                <h3 class="text-xl font-extrabold text-slate-900">Permohonan Berjaya Dihantar!</h3>
                <p class="text-slate-600 text-xs mt-2">
                    Maklumat aktiviti silibus telah disinkronkan ke pengkalan data & <strong>Google Sheets HEA UiTM Perlis</strong>.
                </p>
            </div>

            <div class="bg-slate-50 p-4 rounded-xl text-left border border-slate-200 text-xs space-y-1.5">
                <div class="flex justify-between">
                    <span class="text-slate-500">No. Rujukan:</span>
                    <span class="font-bold text-uitm-purple" id="modalRefNo">HEA-2026-8891</span>
                </div>
                <div class="flex justify-between">
                    <span class="text-slate-500">Fakulti:</span>
                    <span class="font-semibold text-slate-800" id="modalFakulti">-</span>
                </div>
                <div class="flex justify-between">
                    <span class="text-slate-500">Jumlah Dipohon:</span>
                    <span class="font-bold text-emerald-600" id="modalJumlah">RM 0.00</span>
                </div>
            </div>

            <div class="flex flex-col sm:flex-row gap-3 pt-2">
                <button onclick="window.print()" class="w-full py-3 bg-uitm-purple hover:bg-uitm-darkPurple text-white font-bold text-xs rounded-xl shadow-lg transition flex items-center justify-center gap-2">
                    <i class="fa-solid fa-file-pdf"></i> Cetak / Simpan PDF Rasmi
                </button>
                <button onclick="closeModal()" class="w-full py-3 bg-slate-100 hover:bg-slate-200 text-slate-700 font-bold text-xs rounded-xl transition">
                    Tutup
                </button>
            </div>
        </div>
    </div>

    <!-- GOOGLE SHEET INTEGRATION MODAL HELP -->
    <div id="googleModal" class="no-print fixed inset-0 z-50 flex items-center justify-center p-4 bg-slate-900/60 backdrop-blur-sm hidden">
        <div class="bg-white rounded-3xl max-w-2xl w-full p-6 sm:p-8 shadow-2xl border border-slate-100 text-left space-y-4 max-h-[90vh] overflow-y-auto">
            <div class="flex items-center justify-between border-b border-slate-200 pb-3">
                <div class="flex items-center gap-2 text-emerald-600 font-bold text-base">
                    <i class="fa-solid fa-file-excel text-xl"></i> Panduan Hubungkan Ke Google Sheets
                </div>
                <button onclick="closeGoogleModal()" class="text-slate-400 hover:text-slate-600">
                    <i class="fa-solid fa-xmark text-lg"></i>
                </button>
            </div>

            <p class="text-xs text-slate-600">
                Data borang ini sedia untuk dihantar ke Google Sheets secara percuma menggunakan **Google Apps Script**. Ikuti langkah mudah di bawah:
            </p>

            <ol class="list-decimal list-inside text-xs text-slate-700 space-y-2 font-medium bg-slate-50 p-4 rounded-xl border border-slate-200">
                <li>Buka Google Sheets baharu di Google Drive anda.</li>
                <li>Klik pada menu <strong>Extensions > Apps Script</strong>.</li>
                <li>Tampal kod Apps Script di bawah dan tekan <strong>Deploy > New Deployment (Web App)</strong>.</li>
                <li>Setkan <em>Who has access</em> kepada <strong>Anyone</strong>.</li>
                <li>Salin URL Web App yang terhasil dan simpan di tetapan perisian.</li>
            </ol>

            <div class="relative">
                <pre class="bg-slate-900 text-emerald-400 p-4 rounded-xl text-[11px] overflow-x-auto font-mono">
function doPost(e) {
  var sheet = SpreadsheetApp.getActiveSpreadsheet().getActiveSheet();
  var data = JSON.parse(e.postData.contents);
  
  sheet.appendRow([
    new Date(),
    data.fakulti,
    data.kodProgram,
    data.kodKursus,
    data.namaAktiviti,
    data.namaPemohon,
    data.bilPeserta,
    data.jumlahBesar,
    data.statusKelulusan
  ]);
  
  return ContentService.createTextOutput(JSON.stringify({"result": "success"}))
    .setMimeType(ContentService.MimeType.JSON);
}</pre>
            </div>

            <div class="pt-2 text-right">
                <button onclick="closeGoogleModal()" class="px-5 py-2.5 bg-slate-800 text-white font-bold text-xs rounded-xl hover:bg-slate-900 transition">
                    Faham & Tutup
                </button>
            </div>
        </div>
    </div>

    <!-- JAVASCRIPT LOGIC -->
    <script>
        // Automatic Calculation Logic on Load
        document.addEventListener('DOMContentLoaded', () => {
            kiraPerbelanjaanAutomatik();
            const today = new Date().toLocaleDateString('ms-MY', { day: '2-digit', month: '2-digit', year: 'numeric' });
            document.getElementById('tarikhHantarCurrent').innerText = today;
            document.getElementById('pdfSignTarikh').innerText = today;
        });

        // Dynamic Rows for Escort Officers
        function tambahPegawaiPengiring() {
            const tbody = document.getElementById('pengiringTableBody');
            const rowCount = tbody.rows.length + 1;
            const tr = document.createElement('tr');
            tr.innerHTML = `
                <td class="p-3 text-center font-bold">${rowCount}</td>
                <td class="p-2"><input type="text" class="pengiring-nama input-field w-full px-2 py-1.5 rounded text-xs" placeholder="Nama Pegawai ${rowCount}"></td>
                <td class="p-2"><input type="text" class="pengiring-jawatan input-field w-full px-2 py-1.5 rounded text-xs" placeholder="Jawatan"></td>
                <td class="p-2"><input type="text" class="pengiring-gred input-field w-full px-2 py-1.5 rounded text-xs" placeholder="Gred"></td>
                <td class="p-2 text-center no-print">
                    <button type="button" onclick="padamRow(this)" class="text-rose-500 hover:text-rose-700 font-bold"><i class="fa-solid fa-trash"></i></button>
                </td>
            `;
            tbody.appendChild(tr);
        }

        function padamRow(btn) {
            const row = btn.closest('tr');
            row.remove();
            // Re-index row numbers
            const tbody = document.getElementById('pengiringTableBody');
            Array.from(tbody.rows).forEach((r, idx) => {
                r.cells[0].innerText = idx + 1;
            });
        }

        // Functions to add dynamic fields for Penceramah and Fasilitator
        function tambahPenceramahInfo() {
            const container = document.getElementById('penceramahInfoList');
            const div = document.createElement('div');
            div.className = 'flex gap-2 items-center';
            div.innerHTML = `
                <input type="text" class="input-penceramah input-field w-full px-3 py-2 rounded-xl text-xs bg-white" placeholder="Nama Penceramah & Organisasi">
                <button type="button" onclick="this.parentElement.remove()" class="text-rose-500 hover:text-rose-700 px-2 font-bold"><i class="fa-solid fa-trash"></i></button>
            `;
            container.appendChild(div);
        }

        function tambahFasilitatorInfo() {
            const container = document.getElementById('fasilitatorInfoList');
            const div = document.createElement('div');
            div.className = 'flex gap-2 items-center';
            div.innerHTML = `
                <input type="text" class="input-fasilitator input-field w-full px-3 py-2 rounded-xl text-xs bg-white" placeholder="Nama / Jawatan / Gred (Staf/Pelajar)">
                <button type="button" onclick="this.parentElement.remove()" class="text-rose-500 hover:text-rose-700 px-2 font-bold"><i class="fa-solid fa-trash"></i></button>
            `;
            container.appendChild(div);
        }

        function tambahKiraanPenceramah() {
            const container = document.getElementById('kiraanPenceramahList');
            const div = document.createElement('div');
            div.className = 'kiraan-penceramah-row flex items-center gap-2';
            div.innerHTML = `
                <select onchange="kiraPerbelanjaanAutomatik()" class="kadar-penceramah input-field w-full p-2 rounded bg-white font-bold text-slate-700">
                    <option value="300">Pengurusan Tertinggi (RM300)</option>
                    <option value="200">Gred 53 & Gred 54 (RM200)</option>
                    <option value="150" selected>Gred 45 & Gred 52 (RM150)</option>
                    <option value="120">Gred 41 & Gred 44 (RM120)</option>
                    <option value="80">Kumpulan Sokongan (RM80)</option>
                </select>
                <input type="number" min="0" value="2" oninput="kiraPerbelanjaanAutomatik()" class="jam-penceramah input-field w-20 p-2 rounded bg-white font-bold text-center" placeholder="Jam">
                <button type="button" onclick="this.parentElement.remove(); kiraPerbelanjaanAutomatik();" class="text-rose-500 hover:text-rose-700 px-1 font-bold"><i class="fa-solid fa-times"></i></button>
            `;
            container.appendChild(div);
            kiraPerbelanjaanAutomatik();
        }

        function tambahKiraanFasilitator() {
            const container = document.getElementById('kiraanFasilitatorList');
            const div = document.createElement('div');
            div.className = 'kiraan-fasilitator-row flex items-center gap-2';
            div.innerHTML = `
                <span class="text-xs font-semibold text-slate-500 w-full">(Kadar RM15.00 / jam)</span>
                <input type="number" min="0" value="0" oninput="kiraPerbelanjaanAutomatik()" class="jam-fasilitator input-field w-20 p-2 rounded bg-white font-bold text-center" placeholder="Jam">
                <button type="button" onclick="this.parentElement.remove(); kiraPerbelanjaanAutomatik();" class="text-rose-500 hover:text-rose-700 px-1 font-bold"><i class="fa-solid fa-times"></i></button>
            `;
            container.appendChild(div);
            kiraPerbelanjaanAutomatik();
        }

        // Automatic Expenditure Calculation based on Circulars
        function kiraPerbelanjaanAutomatik() {
            const bilPeserta = parseInt(document.getElementById('bilPeserta').value) || 0;
            const bilHariMakan = parseInt(document.getElementById('bilHariMakan').value) || 0;
            const kadarMakan = parseFloat(document.getElementById('kadarMakan').value) || 0;
            const bilMalamPenginapan = parseInt(document.getElementById('bilMalamPenginapan').value) || 0;
            const kadarPenginapan = parseFloat(document.getElementById('kadarPenginapan').value) || 0;

            // a) Makanan & Penginapan
            const totalMakanan = bilPeserta * bilHariMakan * kadarMakan;
            const totalPenginapan = bilPeserta * bilMalamPenginapan * kadarPenginapan;
            const subtotalMakananPenginapan = totalMakanan + totalPenginapan;

            // b) Honorarium
            let subtotalHonorarium = 0;
            document.querySelectorAll('.kiraan-penceramah-row').forEach(row => {
                const kadar = parseFloat(row.querySelector('.kadar-penceramah').value) || 0;
                const jam = parseFloat(row.querySelector('.jam-penceramah').value) || 0;
                subtotalHonorarium += (kadar * jam);
            });

            document.querySelectorAll('.kiraan-fasilitator-row').forEach(row => {
                const jam = parseFloat(row.querySelector('.jam-fasilitator').value) || 0;
                subtotalHonorarium += (jam * 15);
            });

            // c & d) Keperluan & Hadiah
            const jumlahHadiah = parseFloat(document.getElementById('jumlahHadiah').value) || 0;
            const jumlahPeralatan = parseFloat(document.getElementById('jumlahPeralatan').value) || 0;
            const jumlahLainLain = parseFloat(document.getElementById('jumlahLainLain').value) || 0;
            const subtotalKeperluan = jumlahHadiah + jumlahPeralatan + jumlahLainLain;

            // Total overall
            const jumlahBesar = subtotalMakananPenginapan + subtotalHonorarium + subtotalKeperluan;

            // Update UI elements
            document.getElementById('subtotalMakananPenginapan').innerText = `RM ${subtotalMakananPenginapan.toLocaleString('en-US', {minimumFractionDigits: 2})}`;
            document.getElementById('subtotalHonorarium').innerText = `RM ${subtotalHonorarium.toLocaleString('en-US', {minimumFractionDigits: 2})}`;
            document.getElementById('subtotalKeperluan').innerText = `RM ${subtotalKeperluan.toLocaleString('en-US', {minimumFractionDigits: 2})}`;
            document.getElementById('jumlahBesarPerbelanjaan').innerText = `RM ${jumlahBesar.toLocaleString('en-US', {minimumFractionDigits: 2})}`;

            // Sync Pemohon Name to Signature box
            const namaPemohonInput = document.getElementById('namaPemohon').value;
            document.getElementById('previewNamaPemohon').innerText = `Nama Pemohon: ${namaPemohonInput || '[Diisi Dalam Borang]'}`;
        }

        // Form Submission & Data Mapping to Print Layout & Sheets Data Format
        function handleFormSubmit(e) {
            e.preventDefault();

            kiraPerbelanjaanAutomatik();

            // Map Web Input values to PDF Print Format
            const getValue = (id) => document.getElementById(id).value || '-';
            
            document.getElementById('pdfFakulti').innerText = getValue('fakulti');
            document.getElementById('pdfKodProgram').innerText = getValue('kodProgram');
            document.getElementById('pdfKodKursus').innerText = getValue('kodKursus');
            document.getElementById('pdfNamaAktiviti').innerText = getValue('namaAktiviti');
            
            const tarikhMula = getValue('tarikhMula');
            const tarikhTamat = getValue('tarikhTamat');
            document.getElementById('pdfTarikhHari').innerText = tarikhMula === tarikhTamat ? tarikhMula : `${tarikhMula} hingga ${tarikhTamat}`;
            
            const masaMula = getValue('masaMula');
            const masaTamat = getValue('masaTamat');
            document.getElementById('pdfMasa').innerText = `${masaMula} - ${masaTamat}`;
            
            document.getElementById('pdfTempat').innerText = getValue('tempat');
            document.getElementById('pdfBilPeserta').innerText = getValue('bilPeserta');
            document.getElementById('pdfNamaPemohon').innerText = getValue('namaPemohon');
            document.getElementById('pdfNoPekerja').innerText = getValue('noPekerja');
            document.getElementById('pdfJawatanPemohon').innerText = getValue('jawatanPemohon');
            document.getElementById('pdfNoTel').innerText = getValue('noTel');
            document.getElementById('pdfEmail').innerText = getValue('email');

            // Justifikasi & Tentatif
            document.getElementById('pdfRingkasan').innerText = getValue('ringkasanProgram');
            document.getElementById('pdfImplikasi').innerText = getValue('implikasiProgram');
            document.getElementById('pdfTentatif').innerText = getValue('tentatifAktiviti');

            // Penceramah & Fasilitator
            const penceramahInputs = document.querySelectorAll('.input-penceramah');
            const penceramahList = Array.from(penceramahInputs).map(input => input.value).filter(val => val.trim() !== '').join(', ');
            document.getElementById('pdfPenceramah').innerText = penceramahList || 'Tiada Penceramah Luar';
            
            const fasilitatorInputs = document.querySelectorAll('.input-fasilitator');
            const fasilitatorList = Array.from(fasilitatorInputs).map(input => input.value).filter(val => val.trim() !== '').join(', ');
            document.getElementById('pdfFasilitatorStaf').innerText = fasilitatorList || 'Tiada Fasilitator';

            // Pengiring Table Population
            const pengiringBody = document.getElementById('pdfPengiringBody');
            pengiringBody.innerHTML = '';
            const rows = document.querySelectorAll('#pengiringTableBody tr');
            rows.forEach((row, index) => {
                const nama = row.querySelector('.pengiring-nama')?.value || '-';
                const jawatan = row.querySelector('.pengiring-jawatan')?.value || '-';
                const gred = row.querySelector('.pengiring-gred')?.value || '-';
                
                const tr = document.createElement('tr');
                tr.innerHTML = `
                    <td style="text-align: center;">${index + 1}</td>
                    <td>${nama}</td>
                    <td>${jawatan}</td>
                    <td>${gred}</td>
                `;
                pengiringBody.appendChild(tr);
            });

            // Financial Summaries
            const jumlahBesarText = document.getElementById('jumlahBesarPerbelanjaan').innerText;
            document.getElementById('pdfJumlahDipohon').innerText = jumlahBesarText;
            document.getElementById('pdfSubMakanan').innerText = document.getElementById('subtotalMakananPenginapan').innerText;
            document.getElementById('pdfSubHonorarium').innerText = document.getElementById('subtotalHonorarium').innerText;
            document.getElementById('pdfSubKeperluan').innerText = document.getElementById('subtotalKeperluan').innerText;
            document.getElementById('pdfJumlahBesar').innerText = jumlahBesarText;

            // Pengangkutan info
            const pengangkutanOpt = document.querySelector('input[name="pengangkutan"]:checked')?.value || 'Tidak Perlu';
            document.getElementById('pdfPengangkutanInfo').innerText = `${pengangkutanOpt} - ${getValue('jenisKenderaan')}`;

            // Signatures & Approval Display Format
            document.getElementById('pdfSignNama').innerText = getValue('namaPemohon');
            document.getElementById('pdfSignKPP').innerText = getValue('ulasanKPP') || 'Disahkan dan disokong oleh KPP.';
            
            const kelulusanStatus = document.querySelector('input[name="statusKelulusan"]:checked')?.value || 'LULUS';
            document.getElementById('pdfStatusKelulusan').innerText = kelulusanStatus;
            
            const peruntukanAmt = document.getElementById('peruntukanDiluluskan').value;
            document.getElementById('pdfPeruntukanPrint').innerText = peruntukanAmt ? `RM ${parseFloat(peruntukanAmt).toLocaleString('en-US', {minimumFractionDigits: 2})}` : 'RM ____________';
            document.getElementById('pdfJumlahDiluluskan').innerText = peruntukanAmt ? `RM ${parseFloat(peruntukanAmt).toLocaleString('en-US', {minimumFractionDigits: 2})}` : '(Diisi Pegawai HEA)';

            // Modal Display Update
            document.getElementById('modalRefNo').innerText = 'HEA-' + Math.floor(100000 + Math.random() * 900000);
            document.getElementById('modalFakulti').innerText = getValue('fakulti');
            document.getElementById('modalJumlah').innerText = jumlahBesarText;

            // Show Success Modal
            document.getElementById('successModal').classList.remove('hidden');

            // Tunjuk paparan format PDF di skrin web selepas selesai isi borang
            document.getElementById('permohonanForm').classList.add('hidden');
            const introBanner = document.querySelector('.glass-card.border-l-8');
            if(introBanner) introBanner.classList.add('hidden');
            
            const pdfSection = document.getElementById('pdfPrintSection');
            pdfSection.classList.remove('print-only');
            pdfSection.classList.add('shadow-2xl', 'border', 'border-slate-300', 'max-w-4xl', 'mx-auto', 'my-8', 'rounded-sm');
        }

        function closeModal() {
            document.getElementById('successModal').classList.add('hidden');
        }

        function openGoogleSheetHelpModal() {
            document.getElementById('googleModal').classList.remove('hidden');
        }

        function closeGoogleModal() {
            document.getElementById('googleModal').classList.add('hidden');
        }

        // Fill Form with Sample Data for Fast Testing
        function isiDataUjian() {
            document.getElementById('fakulti').value = 'Fakulti Sains Komputer dan Matematik';
            document.getElementById('kodProgram').value = 'CS251 - Ijazah Sarjana Muda Sains Komputer (Kepujian)';
            document.getElementById('kodKursus').value = 'CSC584';
            document.getElementById('namaAktiviti').value = 'Bengkel Praktikal Enterprise Cloud Computing & Lawatan Industri Silicon Valley Penang';
            document.getElementById('tarikhMula').value = '2026-11-12';
            document.getElementById('tarikhTamat').value = '2026-11-14';
            document.getElementById('masaMula').value = '08:00';
            document.getElementById('masaTamat').value = '17:00';
            document.getElementById('tempat').value = 'Intel Technology & Penang Science Cluster, Bayan Lepas, Pulau Pinang';
            document.getElementById('bilPeserta').value = '40';

            document.getElementById('namaPemohon').value = 'Dr. Ahmad Zulkarnain Bin Hashim';
            document.getElementById('noPekerja').value = '289412';
            document.getElementById('jawatanPemohon').value = 'Pensyarah Kanan (DM52)';
            document.getElementById('noTel').value = '019-4882190';
            document.getElementById('email').value = 'zulkarnain@uitm.edu.my';

            document.getElementById('penceramahInfoList').innerHTML = `
                <div class="flex gap-2 items-center">
                    <input type="text" class="input-penceramah input-field w-full px-3 py-2 rounded-xl text-xs bg-white" value="Ir. Dr. Hafiz Mansor (Architect Cloud Intel Malaysia)">
                    <button type="button" onclick="this.parentElement.remove()" class="text-rose-500 hover:text-rose-700 px-2 font-bold"><i class="fa-solid fa-trash"></i></button>
                </div>
                <div class="flex gap-2 items-center">
                    <input type="text" class="input-penceramah input-field w-full px-3 py-2 rounded-xl text-xs bg-white" value="Pn. Siti Nurbaya (Senior DevOps Specialist AWS)">
                    <button type="button" onclick="this.parentElement.remove()" class="text-rose-500 hover:text-rose-700 px-2 font-bold"><i class="fa-solid fa-trash"></i></button>
                </div>
            `;

            document.getElementById('fasilitatorInfoList').innerHTML = `
                <div class="flex gap-2 items-center">
                    <input type="text" class="input-fasilitator input-field w-full px-3 py-2 rounded-xl text-xs bg-white" value="En. Khairul Azmi / Pegawai Teknologi Maklumat / FSKM">
                    <button type="button" onclick="this.parentElement.remove()" class="text-rose-500 hover:text-rose-700 px-2 font-bold"><i class="fa-solid fa-trash"></i></button>
                </div>
                <div class="flex gap-2 items-center">
                    <input type="text" class="input-fasilitator input-field w-full px-3 py-2 rounded-xl text-xs bg-white" value="Amirul Aiman (2024819201 - CS251)">
                    <button type="button" onclick="this.parentElement.remove()" class="text-rose-500 hover:text-rose-700 px-2 font-bold"><i class="fa-solid fa-trash"></i></button>
                </div>
            `;

            document.getElementById('ringkasanProgram').value = 'Aktiviti ini menyokong topik penilaian amali silibus CSC584 Bab 6: Cloud Architecture & Deployment. Pelajar akan mendapat pendedahan terus daripada pakar industri cloud.';
            document.getElementById('implikasiProgram').value = 'Pelajar tidak dapat memenuhi 20% markah tugasan amali silibus berasaskan kes industri dan kekurangan pendedahan gunaan cloud terkini.';
            document.getElementById('tentatifAktiviti').value = 'Hari 1 (12 Nov): 08.00 pagi - Pelepasan Bas UiTM Perlis ke Penang.\n14.00 petang - Sesi Taklimat Intel Cloud Infrastructure.\nHari 2 (13 Nov): 09.00 pagi - Sesi Hands-on AWS Kubernetes Workshop (Penceramah 2).\nHari 3 (14 Nov): 10.00 pagi - Pembentangan Projek Pelajar & Perjalanan Pulang.';

            document.getElementById('bilHariMakan').value = '2';
            document.getElementById('kadarMakan').value = '16';
            document.getElementById('bilMalamPenginapan').value = '1';
            document.getElementById('kadarPenginapan').value = '15';

            document.getElementById('kiraanPenceramahList').innerHTML = `
                <div class="kiraan-penceramah-row flex items-center gap-2">
                    <select onchange="kiraPerbelanjaanAutomatik()" class="kadar-penceramah input-field w-full p-2 rounded bg-white font-bold text-slate-700">
                        <option value="300">Pengurusan Tertinggi (RM300)</option>
                        <option value="200">Gred 53 & Gred 54 (RM200)</option>
                        <option value="150" selected>Gred 45 & Gred 52 (RM150)</option>
                        <option value="120">Gred 41 & Gred 44 (RM120)</option>
                        <option value="80">Kumpulan Sokongan (RM80)</option>
                    </select>
                    <input type="number" min="0" value="4" oninput="kiraPerbelanjaanAutomatik()" class="jam-penceramah input-field w-20 p-2 rounded bg-white font-bold text-center" placeholder="Jam">
                    <button type="button" onclick="this.parentElement.remove(); kiraPerbelanjaanAutomatik();" class="text-rose-500 hover:text-rose-700 px-1 font-bold"><i class="fa-solid fa-times"></i></button>
                </div>
            `;

            document.getElementById('kiraanFasilitatorList').innerHTML = `
                <div class="kiraan-fasilitator-row flex items-center gap-2">
                    <span class="text-xs font-semibold text-slate-500 w-full">(Kadar RM15.00 / jam)</span>
                    <input type="number" min="0" value="6" oninput="kiraPerbelanjaanAutomatik()" class="jam-fasilitator input-field w-20 p-2 rounded bg-white font-bold text-center" placeholder="Jam">
                    <button type="button" onclick="this.parentElement.remove(); kiraPerbelanjaanAutomatik();" class="text-rose-500 hover:text-rose-700 px-1 font-bold"><i class="fa-solid fa-times"></i></button>
                </div>
            `;

            document.getElementById('jumlahHadiah').value = '245';
            document.getElementById('jumlahPeralatan').value = '160';

            document.getElementById('ulasanKPP').value = 'Kertas kerja telah disemak, memenuhi kriteria silibus kursus CSC584. Disokong sepenuhnya.';
            document.getElementById('peruntukanDiluluskan').value = '2185';

            kiraPerbelanjaanAutomatik();
        }

        function resetForm() {
            // Membuang fungsi confirm() kerana ia disekat oleh sesetengah pelayar/sistem
            document.getElementById('permohonanForm').reset();
            
            // Set semula jadual pengiring kepada 1 baris asas
            document.getElementById('pengiringTableBody').innerHTML = `
                <tr>
                    <td class="p-3 text-center font-bold">1</td>
                    <td class="p-2"><input type="text" class="pengiring-nama input-field w-full px-2 py-1.5 rounded text-xs" placeholder="Nama Pegawai 1"></td>
                    <td class="p-2"><input type="text" class="pengiring-jawatan input-field w-full px-2 py-1.5 rounded text-xs" placeholder="Jawatan"></td>
                    <td class="p-2"><input type="text" class="pengiring-gred input-field w-full px-2 py-1.5 rounded text-xs" placeholder="Gred (cth: DM52)"></td>
                    <td class="p-2 text-center no-print">-</td>
                </tr>
            `;

            document.getElementById('penceramahInfoList').innerHTML = `
                <div class="flex gap-2 items-center">
                    <input type="text" class="input-penceramah input-field w-full px-3 py-2 rounded-xl text-xs bg-white" placeholder="1. Nama Penceramah & Organisasi">
                </div>
            `;
            
            document.getElementById('fasilitatorInfoList').innerHTML = `
                <div class="flex gap-2 items-center">
                    <input type="text" class="input-fasilitator input-field w-full px-3 py-2 rounded-xl text-xs bg-white" placeholder="Nama / Jawatan / Gred (Staf/Pelajar)">
                </div>
            `;

            document.getElementById('kiraanPenceramahList').innerHTML = `
                <div class="kiraan-penceramah-row flex items-center gap-2">
                    <select onchange="kiraPerbelanjaanAutomatik()" class="kadar-penceramah input-field w-full p-2 rounded bg-white font-bold text-slate-700">
                        <option value="300">Pengurusan Tertinggi (RM300)</option>
                        <option value="200">Gred 53 & Gred 54 (RM200)</option>
                        <option value="150" selected>Gred 45 & Gred 52 (RM150)</option>
                        <option value="120">Gred 41 & Gred 44 (RM120)</option>
                        <option value="80">Kumpulan Sokongan (RM80)</option>
                    </select>
                    <input type="number" min="0" value="2" oninput="kiraPerbelanjaanAutomatik()" class="jam-penceramah input-field w-20 p-2 rounded bg-white font-bold text-center" placeholder="Jam">
                </div>
            `;

            document.getElementById('kiraanFasilitatorList').innerHTML = `
                <div class="kiraan-fasilitator-row flex items-center gap-2">
                    <span class="text-xs font-semibold text-slate-500 w-full">(Kadar RM15.00 / jam)</span>
                    <input type="number" min="0" value="0" oninput="kiraPerbelanjaanAutomatik()" class="jam-fasilitator input-field w-20 p-2 rounded bg-white font-bold text-center" placeholder="Jam">
                </div>
            `;
            
            kiraPerbelanjaanAutomatik();
        }
    </script>
</body>
</html>

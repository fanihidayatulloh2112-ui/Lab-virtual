```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lab Sains Ceria - Simulasi Wujud Zat</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Fredoka:wght@400;600;700&family=Nunito:wght@600;700;800&display=swap');
        
        body {
            font-family: 'Nunito', sans-serif;
            background-color: #e0f2fe;
            color: #1e293b;
            overflow-x: hidden;
            user-select: none;
        }

        h1, h2, h3, .font-title {
            font-family: 'Fredoka', sans-serif;
        }

        /* Background Pola Laboratorium Ceria */
        .lab-bg {
            background-color: #f0f9ff;
            background-image: 
                radial-gradient(#bae6fd 2px, transparent 2px), 
                radial-gradient(#bae6fd 2px, #f0f9ff 2px);
            background-size: 32px 32px;
            background-position: 0 0, 16px 16px;
        }

        /* Custom Slider Ramah Anak */
        input[type=range] {
            -webkit-appearance: none;
            width: 100%;
            background: transparent;
        }
        input[type=range]::-webkit-slider-thumb {
            -webkit-appearance: none;
            height: 28px;
            width: 28px;
            border-radius: 50%;
            background: #ffffff;
            border: 4px solid #f59e0b;
            cursor: pointer;
            margin-top: -8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.15);
            transition: transform 0.1s;
        }
        input[type=range]::-webkit-slider-thumb:hover {
            transform: scale(1.15);
        }
        input[type=range]::-webkit-slider-runnable-track {
            width: 100%;
            height: 14px;
            cursor: pointer;
            background: linear-gradient(to right, #38bdf8, #fcd34d, #f87171);
            border-radius: 10px;
            border: 2px solid #cbd5e1;
        }

        /* Gaya Gelas Kimia (Beaker) untuk Kanvas */
        .beaker-container {
            background: linear-gradient(135deg, rgba(255,255,255,0.9) 0%, rgba(224,242,254,0.7) 100%);
            border: 6px solid #38bdf8;
            border-top: 10px solid #0284c7;
            border-radius: 12px 12px 32px 32px;
            box-shadow: inset 0 0 25px rgba(56, 189, 248, 0.2), 0 12px 25px -5px rgba(0, 0, 0, 0.1);
            position: relative;
        }

        /* Garis Takaran Gelas Kimia */
        .beaker-marks {
            position: absolute;
            right: 16px;
            top: 20%;
            bottom: 15%;
            width: 28px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            pointer-events: none;
            opacity: 0.45;
            z-index: 10;
        }
        .beaker-mark {
            border-bottom: 3px solid #0284c7;
            font-size: 11px;
            font-weight: 800;
            color: #0369a1;
            text-align: right;
            padding-bottom: 2px;
        }

        /* Tombol 3D Kartun */
        .btn-cartoon {
            transition: all 0.15s ease;
            border-bottom-width: 5px;
        }
        .btn-cartoon:active {
            transform: translateY(3px);
            border-bottom-width: 2px;
        }
    </style>
</head>
<body class="lab-bg min-h-screen w-screen flex items-center justify-center p-3 md:p-6">

    <!-- HALAMAN 1: MENU UTAMA (LANDING SCREEN) -->
    <div id="landing-screen" class="w-full max-w-5xl bg-white/95 backdrop-blur-md rounded-[2.5rem] p-6 md:p-10 shadow-2xl border-4 border-sky-300 flex flex-col items-center text-center relative overflow-hidden">
        <!-- Hiasan Sudut -->
        <div class="absolute -top-10 -left-10 w-36 h-36 bg-yellow-300 rounded-full opacity-50 pointer-events-none"></div>
        <div class="absolute -bottom-10 -right-10 w-44 h-44 bg-pink-300 rounded-full opacity-50 pointer-events-none"></div>

        <div class="inline-flex items-center gap-2 px-5 py-2 rounded-full bg-amber-100 text-amber-700 font-extrabold text-sm md:text-base border-2 border-amber-300 mb-4 shadow-sm">
            <span>👩‍🔬</span> Laboratorium Sains Virtual Anak <span>👨‍🔬</span>
        </div>

        <h1 class="text-4xl md:text-6xl font-title font-bold text-sky-600 mb-3 drop-shadow-sm">
            Petualangan Wujud Zat!
        </h1>

        <p class="text-base md:text-lg text-slate-600 max-w-2xl mb-8 font-semibold">
            Halo Ilmuwan Cilik! Yuk, kita amati bagaimana bola-bola partikel bergerak di dalam benda <span class="text-sky-600 font-extrabold">Padat</span>, <span class="text-teal-600 font-extrabold">Cair</span>, dan <span class="text-rose-500 font-extrabold">Gas</span>!
        </p>

        <!-- Kartu Informasi 3 Wujud Zat -->
        <div class="grid grid-cols-1 md:grid-cols-3 gap-5 w-full mb-8 text-left">
            <div class="bg-sky-50 p-5 rounded-3xl border-4 border-sky-200 shadow-sm hover:scale-105 transition-transform">
                <div class="flex items-center gap-3 mb-2">
                    <span class="text-4xl bg-white p-2 rounded-2xl shadow-sm border border-sky-100">🧊</span>
                    <h3 class="text-xl font-title font-bold text-sky-700">Zat Padat</h3>
                </div>
                <p class="text-sm text-slate-600 font-semibold leading-relaxed">Bola partikelnya berbaris sangat rapi, rapat, dan saling berpegangan erat sambil bergetar kecil!</p>
            </div>

            <div class="bg-teal-50 p-5 rounded-3xl border-4 border-teal-200 shadow-sm hover:scale-105 transition-transform">
                <div class="flex items-center gap-3 mb-2">
                    <span class="text-4xl bg-white p-2 rounded-2xl shadow-sm border border-teal-100">🧃</span>
                    <h3 class="text-xl font-title font-bold text-teal-700">Zat Cair</h3>
                </div>
                <p class="text-sm text-slate-600 font-semibold leading-relaxed">Bola partikelnya mulai longgar dan suka meluncur mengikuti bentuk gelas wadahnya!</p>
            </div>

            <div class="bg-rose-50 p-5 rounded-3xl border-4 border-rose-200 shadow-sm hover:scale-105 transition-transform">
                <div class="flex items-center gap-3 mb-2">
                    <span class="text-4xl bg-white p-2 rounded-2xl shadow-sm border border-rose-100">🎈</span>
                    <h3 class="text-xl font-title font-bold text-rose-600">Zat Gas</h3>
                </div>
                <p class="text-sm text-slate-600 font-semibold leading-relaxed">Bola partikelnya terbang bebas dengan super cepat ke segala arah memenuhi ruangan!</p>
            </div>
        </div>

        <!-- Tombol Pilihan Menu Praktikum -->
        <div class="flex flex-col sm:flex-row gap-5 w-full justify-center">
            <button id="btn-menu-properties" class="btn-cartoon flex-1 py-4 px-6 bg-purple-500 hover:bg-purple-400 text-white font-title font-bold text-xl rounded-3xl border-purple-700 shadow-xl flex items-center justify-center gap-4">
                <span class="text-4xl bg-white/20 p-3 rounded-2xl">🧪</span>
                <div class="text-left">
                    <div>1. Lab Sifat Benda</div>
                    <div class="text-xs font-sans font-semibold text-purple-100">Tekan pendorong & miringkan gelas!</div>
                </div>
            </button>

            <button id="btn-menu-particles" class="btn-cartoon flex-1 py-4 px-6 bg-amber-500 hover:bg-amber-400 text-white font-title font-bold text-xl rounded-3xl border-amber-700 shadow-xl flex items-center justify-center gap-4">
                <span class="text-4xl bg-white/20 p-3 rounded-2xl">🌡️</span>
                <div class="text-left">
                    <div>2. Lab Suhu Partikel</div>
                    <div class="text-xs font-sans font-semibold text-amber-100">Panaskan & dinginkan partikel!</div>
                </div>
            </button>
        </div>
    </div>

    <!-- HALAMAN 2: LAB SUHU PARTIKEL -->
    <div id="simulation-screen" class="hidden w-full max-w-6xl bg-white/95 backdrop-blur-md rounded-[2.5rem] p-5 md:p-8 shadow-2xl border-4 border-amber-300 flex-col gap-5">
        
        <!-- Baris Atas (Header) -->
        <div class="flex flex-wrap items-center justify-between gap-4 border-b-2 border-slate-100 pb-4">
            <button id="btn-back-sim" class="btn-cartoon px-5 py-2.5 bg-slate-200 hover:bg-slate-300 text-slate-700 font-extrabold rounded-2xl border-slate-400 flex items-center gap-2 text-sm md:text-base">
                <span>🏠</span> Menu Utama
            </button>
            <div class="flex items-center gap-2">
                <span class="text-3xl">🌡️</span>
                <h2 class="text-2xl md:text-3xl font-title font-bold text-amber-600">Lab Suhu & Gerak Partikel</h2>
            </div>
            <div class="hidden md:block text-sm font-bold text-sky-600 bg-sky-50 px-4 py-2 rounded-xl border border-sky-200">
                💡 Tips: Geser pengatur suhu di kiri bawah!
            </div>
        </div>

        <div class="flex flex-col lg:flex-row gap-6 items-stretch">
            <!-- Panel Kontrol Kiri -->
            <div class="w-full lg:w-1/3 flex flex-col gap-4 justify-between bg-amber-50/70 p-5 rounded-3xl border-2 border-amber-200">
                <div>
                    <h3 class="text-lg font-title font-bold text-slate-700 mb-1">1. Pilih Wujud Benda:</h3>
                    <p class="text-xs text-slate-500 font-bold mb-3">Klik salah satu tombol di bawah ini</p>
                    
                    <div class="flex flex-col gap-3">
                        <button id="btn-solid" class="btn-cartoon w-full py-3 px-4 rounded-2xl font-extrabold text-white bg-sky-500 border-sky-700 flex items-center justify-between shadow-md">
                            <span class="flex items-center gap-2 text-lg"><span>🧊</span> Es Batu (Padat)</span>
                            <span class="text-xs bg-white/25 px-2.5 py-1 rounded-lg">-50 °C</span>
                        </button>
                        <button id="btn-liquid" class="btn-cartoon w-full py-3 px-4 rounded-2xl font-extrabold text-slate-700 bg-white border-slate-300 flex items-center justify-between shadow-sm">
                            <span class="flex items-center gap-2 text-lg"><span>💧</span> Air Minum (Cair)</span>
                            <span class="text-xs bg-slate-100 px-2.5 py-1 rounded-lg">40 °C</span>
                        </button>
                        <button id="btn-gas" class="btn-cartoon w-full py-3 px-4 rounded-2xl font-extrabold text-slate-700 bg-white border-slate-300 flex items-center justify-between shadow-sm">
                            <span class="flex items-center gap-2 text-lg"><span>☁️</span> Uap Air (Gas)</span>
                            <span class="text-xs bg-slate-100 px-2.5 py-1 rounded-lg">130 °C</span>
                        </button>
                    </div>
                </div>

                <!-- Kotak Penjelasan Ramah Anak -->
                <div id="sim-info-box" class="bg-white p-4 rounded-2xl border-2 border-sky-200 shadow-sm">
                    <div class="font-title font-bold text-sky-600 text-base mb-1" id="sim-info-title">🧊 Sedang Mengamati: Padat</div>
                    <p class="text-xs text-slate-600 font-semibold leading-relaxed" id="sim-info-desc">
                        Lihat! Karena dingin, bola-bola partikel kedinginan dan saling berpelukan erat di dasar gelas.
                    </p>
                </div>

                <!-- Pengatur Suhu -->
                <div class="bg-white p-4 rounded-2xl border-2 border-amber-300 shadow-sm">
                    <div class="flex justify-between items-center mb-2">
                        <span class="font-title font-bold text-slate-700">2. Atur Suhu Kompor:</span>
                        <span id="temp-display" class="text-lg font-title font-bold px-3 py-1 rounded-xl bg-sky-100 text-sky-700 border border-sky-300">-50 °C</span>
                    </div>
                    <input type="range" id="temp-slider" min="-100" max="200" value="-50">
                    <div class="flex justify-between text-xs font-extrabold mt-2">
                        <span class="text-sky-600">❄️ Membeku (-100°C)</span>
                        <span class="text-rose-600">🔥 Mendidih (200°C)</span>
                    </div>
                </div>
            </div>

            <!-- Area Gelas Kimia Kanvas (Kanan) -->
            <div class="w-full lg:w-2/3 flex flex-col items-center">
                <div id="canvas-container" class="beaker-container w-full h-[360px] md:h-[440px] overflow-hidden">
                    <div class="beaker-marks">
                        <div class="beaker-mark">400 ml</div>
                        <div class="beaker-mark">300 ml</div>
                        <div class="beaker-mark">200 ml</div>
                        <div class="beaker-mark">100 ml</div>
                    </div>
                    <canvas id="simulationCanvas" class="w-full h-full block"></canvas>
                </div>
                <!-- Indikator Kompor / Pendingin di Bawah Gelas -->
                <div id="stove-indicator" class="w-3/4 h-6 bg-sky-200 rounded-b-2xl border-x-4 border-b-4 border-sky-400 flex items-center justify-center text-xs font-extrabold text-sky-800 transition-colors duration-300 shadow-md">
                    ❄️ Mode Pendingin Aktif ❄️
                </div>
            </div>
        </div>
    </div>

    <!-- HALAMAN 3: LAB SIFAT BENDA (EKSPERIMEN TEKANAN & WADAH) -->
    <div id="properties-screen" class="hidden w-full max-w-6xl bg-white/95 backdrop-blur-md rounded-[2.5rem] p-5 md:p-8 shadow-2xl border-4 border-purple-300 flex-col gap-5">
        
        <!-- Baris Atas (Header) -->
        <div class="flex flex-wrap items-center justify-between gap-4 border-b-2 border-slate-100 pb-4">
            <button id="btn-back-prop" class="btn-cartoon px-5 py-2.5 bg-slate-200 hover:bg-slate-300 text-slate-700 font-extrabold rounded-2xl border-slate-400 flex items-center gap-2 text-sm md:text-base">
                <span>🏠</span> Menu Utama
            </button>
            <div class="flex items-center gap-2">
                <span class="text-3xl">🧪</span>
                <h2 class="text-2xl md:text-3xl font-title font-bold text-purple-600">Lab Uji Sifat Benda</h2>
            </div>
            <div class="hidden md:block text-sm font-bold text-purple-600 bg-purple-50 px-4 py-2 rounded-xl border border-purple-200">
                🔬 Ayo uji kekuatan benda di dalam tabung!
            </div>
        </div>

        <div class="flex flex-col lg:flex-row gap-6 items-stretch">
            <!-- Panel Kontrol Eksperimen (Kiri) -->
            <div class="w-full lg:w-1/3 flex flex-col gap-4 justify-between bg-purple-50/70 p-5 rounded-3xl border-2 border-purple-200">
                <div>
                    <h3 class="text-lg font-title font-bold text-slate-700 mb-2">1. Masukkan Benda ke Tabung:</h3>
                    <div class="grid grid-cols-3 gap-2 mb-5">
                        <button id="exp-btn-solid" class="btn-cartoon py-3 px-2 rounded-2xl font-extrabold text-sm bg-sky-500 text-white border-sky-700 flex flex-col items-center gap-1 shadow-md">
                            <span class="text-2xl">🧱</span>
                            <span>Balok</span>
                            <span class="text-[10px] opacity-80">(Padat)</span>
                        </button>
                        <button id="exp-btn-liquid" class="btn-cartoon py-3 px-2 rounded-2xl font-extrabold text-sm bg-white text-slate-700 border-slate-300 flex flex-col items-center gap-1 shadow-sm">
                            <span class="text-2xl">🧃</span>
                            <span>Sirup</span>
                            <span class="text-[10px] opacity-80">(Cair)</span>
                        </button>
                        <button id="exp-btn-gas" class="btn-cartoon py-3 px-2 rounded-2xl font-extrabold text-sm bg-white text-slate-700 border-slate-300 flex flex-col items-center gap-1 shadow-sm">
                            <span class="text-2xl">🎈</span>
                            <span>Udara</span>
                            <span class="text-[10px] opacity-80">(Gas)</span>
                        </button>
                    </div>

                    <h3 class="text-lg font-title font-bold text-slate-700 mb-2">2. Lakukan Percobaan Seru:</h3>
                    <div class="flex flex-col gap-3">
                        <button id="btn-test-compress" class="btn-cartoon w-full py-3 px-4 bg-amber-400 hover:bg-amber-300 text-slate-900 font-extrabold rounded-2xl border-amber-600 flex items-center justify-between shadow-md">
                            <span>⬇️ Tekan Alat Pendorong!</span>
                            <span class="text-xl">🔨</span>
                        </button>
                        <button id="btn-test-tilt" class="btn-cartoon w-full py-3 px-4 bg-teal-400 hover:bg-teal-300 text-slate-900 font-extrabold rounded-2xl border-teal-600 flex items-center justify-between shadow-md">
                            <span>🔄 Miringkan Gelas Tabung!</span>
                            <span class="text-xl">📐</span>
                        </button>
                        <button id="btn-exp-reset" class="btn-cartoon w-full py-2.5 px-4 bg-rose-100 hover:bg-rose-200 text-rose-700 font-extrabold rounded-2xl border-rose-300 flex items-center justify-center gap-2 text-sm mt-1">
                            <span>🔄 Kembalikan Seperti Semula</span>
                        </button>
                    </div>
                </div>

                <!-- Catatan Ilmuwan Cilik -->
                <div id="exp-conclusion" class="bg-white p-4 rounded-2xl border-4 border-amber-300 shadow-md">
                    <div class="flex items-center gap-2 font-title font-bold text-amber-600 text-base mb-1">
                        <span>📝</span> Catatan Ilmuwan Cilik:
                    </div>
                    <p id="exp-conclusion-text" class="text-xs md:text-sm text-slate-700 font-semibold leading-relaxed">
                        Pilih benda di atas lalu tekan tombol percobaan untuk melihat keajaiban sifat benda!
                    </p>
                </div>
            </div>

            <!-- Area Tabung Eksperimen (Kanan) -->
            <div class="w-full lg:w-2/3 flex items-center justify-center p-2">
                <div id="exp-canvas-container" class="beaker-container w-full h-[360px] md:h-[440px] overflow-hidden transition-transform duration-500">
                    <!-- Alat Pendorong (Plunger) -->
                    <div id="piston-element" class="absolute top-0 left-0 w-full h-12 bg-amber-400 border-b-8 border-amber-600 z-20 transition-all duration-300 flex items-center justify-center shadow-lg" style="transform: translateY(0px);">
                        <!-- Gagang Pendorong -->
                        <div class="absolute bottom-full left-1/2 -translate-x-1/2 w-10 h-64 bg-amber-300 border-x-4 border-amber-500"></div>
                        <span class="font-title font-bold text-xs md:text-sm text-amber-950 bg-white/80 px-4 py-1 rounded-full shadow-sm">
                            ⬇️ ALAT PENDORONG ⬇️
                        </span>
                    </div>

                    <div class="beaker-marks">
                        <div class="beaker-mark">400 ml</div>
                        <div class="beaker-mark">300 ml</div>
                        <div class="beaker-mark">200 ml</div>
                        <div class="beaker-mark">100 ml</div>
                    </div>

                    <canvas id="expCanvas" class="w-full h-full block"></canvas>
                </div>
            </div>
        </div>
    </div>

    <script>
        // Elemen Layar
        const landingScreen = document.getElementById('landing-screen');
        const simulationScreen = document.getElementById('simulation-screen');
        const propertiesScreen = document.getElementById('properties-screen');

        // Tombol Navigasi
        const btnMenuProperties = document.getElementById('btn-menu-properties');
        const btnMenuParticles = document.getElementById('btn-menu-particles');
        const btnBackSim = document.getElementById('btn-back-sim');
        const btnBackProp = document.getElementById('btn-back-prop');

        // Status Aplikasi
        let isSimulationRunning = false;
        let isExpRunning = false;
        let simAnimId = null;
        let expAnimId = null;

        // Navigasi ke Lab Suhu Partikel (Menu 2)
        btnMenuParticles.addEventListener('click', () => {
            landingScreen.classList.add('hidden');
            simulationScreen.classList.remove('hidden');
            simulationScreen.classList.add('flex');

            isSimulationRunning = true;
            requestAnimationFrame(() => {
                resizeSimCanvas();
                updateSimUI();
                initSimParticles();
                if (simAnimId) cancelAnimationFrame(simAnimId);
                animateSim();
            });
        });

        // Navigasi ke Lab Sifat Benda (Menu 1)
        btnMenuProperties.addEventListener('click', () => {
            landingScreen.classList.add('hidden');
            propertiesScreen.classList.remove('hidden');
            propertiesScreen.classList.add('flex');

            isExpRunning = true;
            requestAnimationFrame(() => {
                resizeExpCanvas();
                updateExpButtons();
                initExpParticles();
                if (expAnimId) cancelAnimationFrame(expAnimId);
                animateExp();
            });
        });

        // Kembali ke Menu Utama dari Lab Suhu
        btnBackSim.addEventListener('click', () => {
            isSimulationRunning = false;
            if (simAnimId) cancelAnimationFrame(simAnimId);
            simulationScreen.classList.add('hidden');
            simulationScreen.classList.remove('flex');
            landingScreen.classList.remove('hidden');
        });

        // Kembali ke Menu Utama dari Lab Sifat Benda
        btnBackProp.addEventListener('click', () => {
            isExpRunning = false;
            if (expAnimId) cancelAnimationFrame(expAnimId);
            resetExperiment();
            propertiesScreen.classList.add('hidden');
            propertiesScreen.classList.remove('flex');
            landingScreen.classList.remove('hidden');
        });

        // ==========================================
        // LOGIKA LAB 2: SUHU & GERAK PARTIKEL
        // ==========================================
        const simCanvas = document.getElementById('simulationCanvas');
        const simCtx = simCanvas.getContext('2d');
        const simContainer = document.getElementById('canvas-container');

        const tempSlider = document.getElementById('temp-slider');
        const tempDisplay = document.getElementById('temp-display');
        const stoveIndicator = document.getElementById('stove-indicator');
        const simInfoTitle = document.getElementById('sim-info-title');
        const simInfoDesc = document.getElementById('sim-info-desc');

        const btnSolid = document.getElementById('btn-solid');
        const btnLiquid = document.getElementById('btn-liquid');
        const btnGas = document.getElementById('btn-gas');

        let simParticles = [];
        let currentState = 'solid';
        let temperature = -50;

        function resizeSimCanvas() {
            const rect = simContainer.getBoundingClientRect();
            simCanvas.width = rect.width > 0 ? rect.width : 600;
            simCanvas.height = rect.height > 0 ? rect.height : 400;
        }

        // Fungsi menggambar bola partikel dengan mata lucu agar disukai anak-anak
        function drawCuteParticle(ctx, x, y, radius, fillColor, strokeColor) {
            ctx.beginPath();
            ctx.arc(x, y, radius, 0, Math.PI * 2);
            ctx.fillStyle = fillColor;
            ctx.fill();
            ctx.lineWidth = 2;
            ctx.strokeStyle = strokeColor;
            ctx.stroke();

            // Kilau Putih
            ctx.beginPath();
            ctx.arc(x - radius * 0.3, y - radius * 0.3, radius * 0.25, 0, Math.PI * 2);
            ctx.fillStyle = 'rgba(255, 255, 255, 0.7)';
            ctx.fill();

            // Mata Kartun Kecil
            ctx.fillStyle = '#1e293b';
            ctx.beginPath();
            ctx.arc(x - radius * 0.28, y + radius * 0.05, radius * 0.13, 0, Math.PI * 2);
            ctx.arc(x + radius * 0.28, y + radius * 0.05, radius * 0.13, 0, Math.PI * 2);
            ctx.fill();
        }

        class SimParticle {
            constructor(x, y, radius) {
                this.x = x;
                this.y = y;
                this.targetX = x;
                this.targetY = y;
                this.vx = (Math.random() - 0.5) * 2;
                this.vy = (Math.random() - 0.5) * 2;
                this.radius = radius;
            }

            draw() {
                let fill = '#38bdf8';
                let stroke = '#0284c7';
                if (currentState === 'liquid') {
                    fill = '#2dd4bf';
                    stroke = '#0d9488';
                } else if (currentState === 'gas') {
                    fill = '#fb7185';
                    stroke = '#e11d48';
                }
                drawCuteParticle(simCtx, this.x, this.y, this.radius, fill, stroke);
            }

            update() {
                const jitter = Math.max(0.2, (temperature + 110) * 0.015);

                if (currentState === 'solid') {
                    // Tertahan di formasi dengan getaran kecil
                    const dx = this.targetX - this.x;
                    const dy = this.targetY - this.y;
                    this.vx = dx * 0.2 + (Math.random() - 0.5) * jitter * 2.5;
                    this.vy = dy * 0.2 + (Math.random() - 0.5) * jitter * 2.5;
                    this.x += this.vx;
                    this.y += this.vy;
                } else if (currentState === 'liquid') {
                    // Jatuh ke bawah oleh gravitasi & mengalir bebas
                    this.vy += 0.35;
                    this.vx += (Math.random() - 0.5) * jitter * 0.8;
                    this.vy += (Math.random() - 0.5) * jitter * 0.4;
                    this.vx *= 0.96;
                    this.vy *= 0.96;
                    this.x += this.vx;
                    this.y += this.vy;
                } else if (currentState === 'gas') {
                    // Melayang bebas ke seluruh penjuru
                    const speedMultiplier = 1 + Math.max(0, (temperature - 80) * 0.015);
                    this.vx += (Math.random() - 0.5) * 0.6;
                    this.vy += (Math.random() - 0.5) * 0.6;
                    const speed = Math.hypot(this.vx, this.vy) || 1;
                    const maxSpeed = 4.5 * speedMultiplier;
                    if (speed > maxSpeed) {
                        this.vx = (this.vx / speed) * maxSpeed;
                        this.vy = (this.vy / speed) * maxSpeed;
                    }
                    this.x += this.vx;
                    this.y += this.vy;
                }

                // Batas Dinding Gelas Kimia
                const pad = 14;
                if (this.x - this.radius < pad) {
                    this.x = pad + this.radius;
                    this.vx *= -0.8;
                }
                if (this.x + this.radius > simCanvas.width - pad) {
                    this.x = simCanvas.width - pad - this.radius;
                    this.vx *= -0.8;
                }
                if (this.y - this.radius < pad) {
                    this.y = pad + this.radius;
                    this.vy *= -0.8;
                }
                if (this.y + this.radius > simCanvas.height - pad) {
                    this.y = simCanvas.height - pad - this.radius;
                    this.vy *= currentState === 'gas' ? -0.9 : -0.4;
                }
            }
        }

        function resolveCollisions(arr, stiffness) {
            for (let i = 0; i < arr.length; i++) {
                for (let j = i + 1; j < arr.length; j++) {
                    const p1 = arr[i];
                    const p2 = arr[j];
                    const dx = p2.x - p1.x;
                    const dy = p2.y - p1.y;
                    const dist = Math.hypot(dx, dy);
                    const minDist = p1.radius + p2.radius + 1;

                    if (dist < minDist && dist > 0) {
                        const overlap = (minDist - dist) * 0.5;
                        const nx = dx / dist;
                        const ny = dy / dist;

                        p1.x -= nx * overlap;
                        p1.y -= ny * overlap;
                        p2.x += nx * overlap;
                        p2.y += ny * overlap;

                        p1.vx -= nx * overlap * stiffness;
                        p1.vy -= ny * overlap * stiffness;
                        p2.vx += nx * overlap * stiffness;
                        p2.vy += ny * overlap * stiffness;
                    }
                }
            }
        }

        function initSimParticles() {
            simParticles = [];
            const radius = 14;
            const cols = 10;
            const rows = 6;
            const spacing = radius * 2.15;

            const startX = (simCanvas.width - (cols - 1) * spacing) / 2;
            const startY = simCanvas.height - rows * spacing - 20;

            for (let r = 0; r < rows; r++) {
                for (let c = 0; c < cols; c++) {
                    const tx = startX + c * spacing;
                    const ty = startY + r * spacing;
                    const p = new SimParticle(tx, ty, radius);

                    if (currentState === 'gas') {
                        p.x = 30 + Math.random() * (simCanvas.width - 60);
                        p.y = 30 + Math.random() * (simCanvas.height - 60);
                        p.vx = (Math.random() - 0.5) * 6;
                        p.vy = (Math.random() - 0.5) * 6;
                    } else if (currentState === 'liquid') {
                        p.x = tx + (Math.random() - 0.5) * 15;
                        p.y = ty - Math.random() * 20;
                    }
                    simParticles.push(p);
                }
            }
        }

        function animateSim() {
            if (!isSimulationRunning) return;
            simCtx.clearRect(0, 0, simCanvas.width, simCanvas.height);

            if (currentState !== 'solid') {
                resolveCollisions(simParticles, 0.3);
            }
            for (let i = 0; i < simParticles.length; i++) {
                simParticles[i].update();
                simParticles[i].draw();
            }
            simAnimId = requestAnimationFrame(animateSim);
        }

        function updateSimUI() {
            // Reset gaya tombol
            const inactiveClass = 'btn-cartoon w-full py-3 px-4 rounded-2xl font-extrabold text-slate-700 bg-white border-slate-300 flex items-center justify-between shadow-sm';
            btnSolid.className = inactiveClass;
            btnLiquid.className = inactiveClass;
            btnGas.className = inactiveClass;

            if (currentState === 'solid') {
                btnSolid.className = 'btn-cartoon w-full py-3 px-4 rounded-2xl font-extrabold text-white bg-sky-500 border-sky-700 flex items-center justify-between shadow-md';
                simInfoTitle.innerText = '🧊 Sedang Mengamati: Es Batu (Padat)';
                simInfoDesc.innerText = 'Pada suhu dingin di bawah 0°C, bola-bola partikel tersusun sangat rapat dan hanya bergetar kecil di tempatnya.';
            } else if (currentState === 'liquid') {
                btnLiquid.className = 'btn-cartoon w-full py-3 px-4 rounded-2xl font-extrabold text-white bg-teal-500 border-teal-700 flex items-center justify-between shadow-md';
                simInfoTitle.innerText = '💧 Sedang Mengamati: Air (Cair)';
                simInfoDesc.innerText = 'Pada suhu 0°C sampai 99°C, es mencair! Bola-bola partikel mulai bergerak bebas dan mengalir di dasar gelas.';
            } else {
                btnGas.className = 'btn-cartoon w-full py-3 px-4 rounded-2xl font-extrabold text-white bg-rose-500 border-rose-700 flex items-center justify-between shadow-md';
                simInfoTitle.innerText = '☁️ Sedang Mengamati: Uap Air (Gas)';
                simInfoDesc.innerText = 'Wah, suhunya mencapai 100°C lebih! Air mendidih menjadi gas dan bola partikel melompat terbang ke seluruh ruangan!';
            }

            // Indikator Kompor / Pendingin
            if (temperature < 0) {
                stoveIndicator.className = 'w-3/4 h-7 bg-sky-200 rounded-b-2xl border-x-4 border-b-4 border-sky-400 flex items-center justify-center text-xs font-extrabold text-sky-800 shadow-md';
                stoveIndicator.innerText = '❄️ Lemari Pendingin Aktif (' + temperature + ' °C) ❄️';
            } else if (temperature < 100) {
                stoveIndicator.className = 'w-3/4 h-7 bg-amber-200 rounded-b-2xl border-x-4 border-b-4 border-amber-400 flex items-center justify-center text-xs font-extrabold text-amber-900 shadow-md';
                stoveIndicator.innerText = '☀️ Suhu Hangat Normal (' + temperature + ' °C) ☀️';
            } else {
                stoveIndicator.className = 'w-3/4 h-7 bg-rose-500 rounded-b-2xl border-x-4 border-b-4 border-rose-700 flex items-center justify-center text-xs font-extrabold text-white shadow-md';
                stoveIndicator.innerText = '🔥 Kompor Pemanas Menyala (' + temperature + ' °C) 🔥';
            }
        }

        tempSlider.addEventListener('input', () => {
            temperature = parseInt(tempSlider.value, 10);
            tempDisplay.innerText = `${temperature} °C`;

            let prevState = currentState;
            if (temperature < 0) {
                currentState = 'solid';
            } else if (temperature < 100) {
                currentState = 'liquid';
            } else {
                currentState = 'gas';
            }

            if (prevState !== currentState) {
                initSimParticles();
            }
            updateSimUI();
        });

        btnSolid.addEventListener('click', () => {
            currentState = 'solid';
            temperature = -50;
            tempSlider.value = -50;
            tempDisplay.innerText = '-50 °C';
            updateSimUI();
            initSimParticles();
        });

        btnLiquid.addEventListener('click', () => {
            currentState = 'liquid';
            temperature = 40;
            tempSlider.value = 40;
            tempDisplay.innerText = '40 °C';
            updateSimUI();
            initSimParticles();
        });

        btnGas.addEventListener('click', () => {
            currentState = 'gas';
            temperature = 130;
            tempSlider.value = 130;
            tempDisplay.innerText = '130 °C';
            updateSimUI();
            initSimParticles();
        });

        // ==========================================
        // LOGIKA LAB 1: UJI SIFAT BENDA
        // ==========================================
        const expCanvas = document.getElementById('expCanvas');
        const expCtx = expCanvas.getContext('2d');
        const expContainer = document.getElementById('exp-canvas-container');
        const pistonElement = document.getElementById('piston-element');

        const expBtnSolid = document.getElementById('exp-btn-solid');
        const expBtnLiquid = document.getElementById('exp-btn-liquid');
        const expBtnGas = document.getElementById('exp-btn-gas');

        const btnTestCompress = document.getElementById('btn-test-compress');
        const btnTestTilt = document.getElementById('btn-test-tilt');
        const btnExpReset = document.getElementById('btn-exp-reset');
        const expConclusionText = document.getElementById('exp-conclusion-text');

        let expParticles = [];
        let currentExpState = 'solid';
        let isCompressed = false;
        let isTilted = false;
        let pistonOffsetPx = 0;

        function resizeExpCanvas() {
            const rect = expContainer.getBoundingClientRect();
            expCanvas.width = rect.width > 0 ? rect.width : 600;
            expCanvas.height = rect.height > 0 ? rect.height : 400;
        }

        class ExpParticle {
            constructor(x, y, radius) {
                this.x = x;
                this.y = y;
                this.originX = x;
                this.originY = y;
                this.vx = (Math.random() - 0.5) * 3;
                this.vy = (Math.random() - 0.5) * 3;
                this.radius = radius;
            }

            draw() {
                let fill = '#38bdf8';
                let stroke = '#0284c7';
                if (currentExpState === 'liquid') {
                    fill = '#a855f7';
                    stroke = '#7e22ce';
                } else if (currentExpState === 'gas') {
                    fill = '#f59e0b';
                    stroke = '#b45309';
                }
                drawCuteParticle(expCtx, this.x, this.y, this.radius, fill, stroke);
            }

            update() {
                const topLimit = 48 + pistonOffsetPx;
                const pad = 14;

                if (currentExpState === 'solid') {
                    // Tetap kokoh di posisinya
                    const dx = this.originX - this.x;
                    const dy = this.originY - this.y;
                    this.vx = dx * 0.25 + (Math.random() - 0.5) * 0.4;
                    this.vy = dy * 0.25 + (Math.random() - 0.5) * 0.4;
                    this.x += this.vx;
                    this.y += this.vy;
                } else if (currentExpState === 'liquid') {
                    // Mengalir ke arah miringnya wadah
                    const gx = isTilted ? -0.45 : 0;
                    const gy = 0.35;
                    this.vx += gx + (Math.random() - 0.5) * 0.4;
                    this.vy += gy + (Math.random() - 0.5) * 0.4;
                    this.vx *= 0.94;
                    this.vy *= 0.94;
                    this.x += this.vx;
                    this.y += this.vy;
                } else if (currentExpState === 'gas') {
                    // Memantul cepat di ruang yang tersedia
                    const maxSpd = isCompressed ? 6.5 : 4;
                    this.vx += (Math.random() - 0.5) * 0.5;
                    this.vy += (Math.random() - 0.5) * 0.5;
                    const spd = Math.hypot(this.vx, this.vy) || 1;
                    if (spd > maxSpd) {
                        this.vx = (this.vx / spd) * maxSpd;
                        this.vy = (this.vy / spd) * maxSpd;
                    }
                    this.x += this.vx;
                    this.y += this.vy;
                }

                // Tumbukan dengan Dinding & Alat Pendorong
                if (this.x - this.radius < pad) {
                    this.x = pad + this.radius;
                    this.vx *= -0.8;
                }
                if (this.x + this.radius > expCanvas.width - pad) {
                    this.x = expCanvas.width - pad - this.radius;
                    this.vx *= -0.8;
                }
                if (this.y - this.radius < topLimit) {
                    this.y = topLimit + this.radius;
                    this.vy = Math.abs(this.vy) * 0.8;
                }
                if (this.y + this.radius > expCanvas.height - pad) {
                    this.y = expCanvas.height - pad - this.radius;
                    this.vy *= currentExpState === 'gas' ? -0.9 : -0.4;
                }
            }
        }

        function initExpParticles() {
            expParticles = [];
            const radius = 14;
            const cols = currentExpState === 'gas' ? 7 : 10;
            const rows = currentExpState === 'gas' ? 5 : 6;
            const spacing = radius * 2.15;

            const startX = (expCanvas.width - (cols - 1) * spacing) / 2;
            const startY = expCanvas.height - rows * spacing - 18;

            for (let r = 0; r < rows; r++) {
                for (let c = 0; c < cols; c++) {
                    let x = startX + c * spacing;
                    let y = startY + r * spacing;

                    if (currentExpState === 'gas') {
                        x = 30 + Math.random() * (expCanvas.width - 60);
                        y = 70 + Math.random() * (expCanvas.height - 100);
                    }
                    expParticles.push(new ExpParticle(x, y, radius));
                }
            }
        }

        function animateExp() {
            if (!isExpRunning) return;
            expCtx.clearRect(0, 0, expCanvas.width, expCanvas.height);

            if (currentExpState !== 'solid') {
                resolveCollisions(expParticles, 0.35);
            }
            for (let i = 0; i < expParticles.length; i++) {
                expParticles[i].update();
                expParticles[i].draw();
            }
            expAnimId = requestAnimationFrame(animateExp);
        }

        function updateExpVisuals() {
            pistonElement.style.transform = `translateY(${pistonOffsetPx}px)`;
            if (isTilted) {
                expContainer.style.transform = 'rotate(-10deg)';
            } else {
                expContainer.style.transform = 'rotate(0deg)';
            }
        }

        function resetExperiment() {
            isCompressed = false;
            isTilted = false;
            pistonOffsetPx = 0;
            updateExpVisuals();
            expConclusionText.innerHTML = 'Pilih benda di atas lalu tekan tombol percobaan untuk melihat keajaiban sifat benda!';
            initExpParticles();
        }

        function updateExpButtons() {
            const baseClass = 'btn-cartoon py-3 px-2 rounded-2xl font-extrabold text-sm bg-white text-slate-700 border-slate-300 flex flex-col items-center gap-1 shadow-sm';
            expBtnSolid.className = baseClass;
            expBtnLiquid.className = baseClass;
            expBtnGas.className = baseClass;

            if (currentExpState === 'solid') {
                expBtnSolid.className = 'btn-cartoon py-3 px-2 rounded-2xl font-extrabold text-sm bg-sky-500 text-white border-sky-700 flex flex-col items-center gap-1 shadow-md';
            } else if (currentExpState === 'liquid') {
                expBtnLiquid.className = 'btn-cartoon py-3 px-2 rounded-2xl font-extrabold text-sm bg-purple-500 text-white border-purple-700 flex flex-col items-center gap-1 shadow-md';
            } else {
                expBtnGas.className = 'btn-cartoon py-3 px-2 rounded-2xl font-extrabold text-sm bg-amber-500 text-white border-amber-700 flex flex-col items-center gap-1 shadow-md';
            }
        }

        expBtnSolid.addEventListener('click', () => {
            currentExpState = 'solid';
            updateExpButtons();
            resetExperiment();
        });

        expBtnLiquid.addEventListener('click', () => {
            currentExpState = 'liquid';
            updateExpButtons();
            resetExperiment();
        });

        expBtnGas.addEventListener('click', () => {
            currentExpState = 'gas';
            updateExpButtons();
            resetExperiment();
        });

        btnTestCompress.addEventListener('click', () => {
            isCompressed = true;
            const maxDrop = expCanvas.height - 6 * (14 * 2.15) - 68;

            if (currentExpState === 'solid') {
                pistonOffsetPx = Math.max(40, maxDrop);
                expConclusionText.innerHTML = '🧱 <b>Balok (Padat) Tidak Bisa Ditekan!</b><br>Alat pendorong tertahan! Bola partikel padat sudah sangat rapat sehingga ukurannya (volumenya) selalu tetap.';
            } else if (currentExpState === 'liquid') {
                pistonOffsetPx = Math.max(45, maxDrop + 10);
                expConclusionText.innerHTML = '🧃 <b>Sirup (Cair) Sulit Ditekan!</b><br>Walaupun cair, bola partikelnya sudah berdekatan sehingga tidak bisa dipadatkan lagi.';
            } else {
                pistonOffsetPx = expCanvas.height * 0.52;
                expConclusionText.innerHTML = '🎈 <b>Udara (Gas) Mudah Ditekan!</b><br>Hebat! Karena jarak antar bola partikel gas sangat renggang, alat pendorong bisa menekan ruangannya menjadi sempit!';
            }
            updateExpVisuals();
        });

        btnTestTilt.addEventListener('click', () => {
            isTilted = !isTilted;
            if (isTilted) {
                if (currentExpState === 'solid') {
                    expConclusionText.innerHTML = '🧱 <b>Bentuk Balok (Padat) Tetap!</b><br>Meskipun gelas dimiringkan, balok tidak tumpah atau berubah bentuk karena partikelnya saling mengunci kuat!';
                } else if (currentExpState === 'liquid') {
                    expConclusionText.innerHTML = '🧃 <b>Sirup (Cair) Mengikuti Bentuk Wadah!</b><br>Lihat! Bola-bola partikel sirup langsung meluncur mengalir ke sudut gelas yang lebih rendah.';
                } else {
                    expConclusionText.innerHTML = '🎈 <b>Udara (Gas) Tetap Memenuhi Ruangan!</b><br>Walau gelas miring, partikel gas tetap terbang bebas ke seluruh bagian tabung.';
                }
            } else {
                expConclusionText.innerHTML = 'Gelas tabung sudah ditegakkan kembali!';
            }
            updateExpVisuals();
        });

        btnExpReset.addEventListener('click', resetExperiment);

        window.addEventListener('resize', () => {
            if (isSimulationRunning) {
                resizeSimCanvas();
                initSimParticles();
            }
            if (isExpRunning) {
                resizeExpCanvas();
                initExpParticles();
            }
        });
    </script>
</body>
</html>

```

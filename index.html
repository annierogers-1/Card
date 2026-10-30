```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Take Care Unc - Cozy Interactive Card</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        warmWood: '#2c1810',
                        amberWood: '#4a2c1d',
                        warmGold: '#d4af37',
                        cozyPaper: '#fbf4e9',
                        terracotta: '#c85a32',
                        cozySage: '#556b2f'
                    }
                }
            }
        }
    </script>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600;700;800&family=IM+Fell+English:ital@0;1&family=Outfit:wght@300;400;500;600;700&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: 'Outfit', sans-serif;
            background: #1c0f0a;
            color: #2c1810;
            overflow-x: hidden;
        }

        .font-vintage {
            font-family: 'IM Fell English', serif;
        }

        .font-header {
            font-family: 'Cinzel', serif;
        }

        /* Wooden Desk Environment */
        .wood-desk {
            background-color: #321a11;
            background-image: 
                radial-gradient(circle at 50% 30%, rgba(212, 175, 55, 0.12) 0%, rgba(0, 0, 0, 0.7) 100%),
                linear-gradient(90deg, rgba(255,255,255,0.02) 0%, rgba(0,0,0,0.08) 50%, rgba(255,255,255,0.02) 100%);
        }

        /* 3D Envelope Perspective */
        .perspective-1000 {
            perspective: 1000px;
        }

        .card-container {
            transform-style: preserve-3d;
            transition: transform 0.8s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .flap {
            transform-origin: top;
            transition: transform 0.6s ease-in-out;
            backface-visibility: hidden;
        }

        .flap-open {
            transform: rotateX(180deg);
        }

        /* Steam Animation for Tea Mug */
        @keyframes riseSteam {
            0% { transform: translateY(0) scaleX(1); opacity: 0; }
            50% { opacity: 0.6; }
            100% { transform: translateY(-25px) scaleX(1.5); opacity: 0; }
        }

        .steam-line {
            animation: riseSteam 2.5s infinite ease-in-out;
        }
        .steam-line:nth-child(2) { animation-delay: 0.8s; }
        .steam-line:nth-child(3) { animation-delay: 1.6s; }

        /* Floating particles */
        @keyframes floatParticle {
            0% { transform: translateY(0) rotate(0deg); opacity: 1; }
            100% { transform: translateY(-100vh) rotate(360deg); opacity: 0; }
        }

        .particle {
            position: fixed;
            pointer-events: none;
            z-index: 50;
            animation: floatParticle 3s linear forwards;
        }

        /* Reading glasses blur overlay filter when toggled off */
        .blur-reading {
            filter: blur(1.8px);
            transition: filter 0.4s ease;
        }
        .clear-reading {
            filter: blur(0px);
            transition: filter 0.4s ease;
        }
    </style>
</head>
<body class="min-h-screen wood-desk flex flex-col justify-between items-center p-3 md:p-6 text-slate-800 select-none">

    <!-- Top Navigation / Ambient Controls Bar -->
    <header class="w-full max-w-4xl flex justify-between items-center mb-4 z-20 bg-amberWood/40 backdrop-blur-md p-3 px-5 rounded-2xl border border-warmGold/20 shadow-lg text-cozyPaper">
        <div class="flex items-center space-x-3">
            <span class="text-2xl">☕</span>
            <div>
                <h1 class="font-header text-lg font-bold text-warmGold tracking-wider">UNC's CARE STATION</h1>
                <p class="text-xs text-amber-200/70">Cozy Interactive Greeting Card</p>
            </div>
        </div>

        <div class="flex items-center space-x-2 md:space-x-3">
            <!-- Glasses toggle -->
            <button onclick="toggleGlasses()" id="glassesBtn" class="flex items-center space-x-1 text-xs bg-amberWood/60 hover:bg-amberWood border border-warmGold/30 px-3 py-1.5 rounded-xl transition shadow">
                <span>👓</span>
                <span id="glassesLabel" class="hidden sm:inline text-amber-100">Glasses: ON</span>
            </button>

            <!-- Audio Music Toggle -->
            <button onclick="toggleMusic()" id="musicBtn" class="flex items-center space-x-1 text-xs bg-amberWood/60 hover:bg-amberWood border border-warmGold/30 px-3 py-1.5 rounded-xl transition shadow">
                <span id="musicIcon">📻</span>
                <span id="musicLabel" class="hidden sm:inline text-amber-100">Radio: OFF</span>
            </button>

            <!-- Virtual Hug Shower -->
            <button onclick="triggerHugShower()" class="flex items-center space-x-1 text-xs bg-terracotta hover:bg-amber-700 text-white px-3 py-1.5 rounded-xl font-bold transition shadow">
                <span>🤗</span>
                <span class="hidden sm:inline">Send Hug</span>
            </button>
        </div>
    </header>

    <!-- Main Desk Interactive Stage -->
    <main class="w-full max-w-4xl flex-1 flex flex-col items-center justify-center relative my-2 z-10 min-h-[520px]">

        <!-- Interactive Desk Accessories Around Card -->
        <div class="w-full flex justify-between items-center px-4 mb-3 text-cozyPaper z-10">
            <!-- Hot Tea Brewing Mug -->
            <div onclick="brewTea()" class="cursor-pointer group flex items-center space-x-2 bg-amberWood/50 p-2.5 px-4 rounded-2xl border border-warmGold/20 hover:border-warmGold/60 transition shadow-lg hover:scale-105 active:scale-95" title="Click to sip cozy tea">
                <div class="relative text-3xl">
                    <div class="absolute -top-4 left-1/2 -translate-x-1/2 flex space-x-1">
                        <span class="steam-line text-xs opacity-70">~</span>
                        <span class="steam-line text-xs opacity-70">~</span>
                        <span class="steam-line text-xs opacity-70">~</span>
                    </div>
                    ☕
                </div>
                <div class="text-left">
                    <p id="teaStatus" class="text-xs font-bold text-warmGold">Chamomile Tea</p>
                    <p class="text-[10px] text-amber-200/70">Click to take a warm sip</p>
                </div>
            </div>

            <!-- Morning Wisdom / Newspaper Button -->
            <div onclick="openWisdomModal()" class="cursor-pointer group flex items-center space-x-2 bg-amberWood/50 p-2.5 px-4 rounded-2xl border border-warmGold/20 hover:border-warmGold/60 transition shadow-lg hover:scale-105 active:scale-95" title="Read Unc's Daily Gazette">
                <span class="text-2xl">📰</span>
                <div class="text-left hidden sm:block">
                    <p class="text-xs font-bold text-warmGold">Daily Gazette</p>
                    <p class="text-[10px] text-amber-200/70">Unc's Wisdom & Jokes</p>
                </div>
            </div>
        </div>

        <!-- Envelope & Letter Interactive Wrapper -->
        <div id="cardContentWrapper" class="clear-reading w-full flex justify-center items-center py-4">

            <!-- FOLDED ENVELOPE STATE -->
            <div id="envelopeView" class="w-full max-w-lg cursor-pointer transform hover:scale-[1.02] transition-transform duration-300">
                <div class="relative bg-gradient-to-b from-[#e6d5bc] to-[#cbb292] rounded-2xl shadow-2xl border-2 border-warmGold/40 p-6 md:p-10 flex flex-col items-center text-center overflow-hidden">
                    
                    <!-- Top Flap Shadow & Visual -->
                    <div class="w-0 h-0 border-l-[200px] border-l-transparent border-r-[200px] border-r-transparent border-t-[120px] border-t-[#baa281] absolute top-0 opacity-40"></div>

                    <div class="my-6 z-10 flex flex-col items-center">
                        <span class="text-5xl mb-3 drop-shadow">💌</span>
                        <p class="font-header text-xl md:text-2xl font-extrabold text-amberWood tracking-wider">A Special Delivery for Unc</p>
                        <p class="text-xs font-semibold text-amberWood/70 uppercase tracking-widest mt-1">Personal & Confidential</p>
                    </div>

                    <!-- Clean Wax Seal Action Button -->
                    <button onclick="openLetter()" class="z-20 mt-2 px-6 py-3 rounded-full bg-terracotta hover:bg-red-700 text-cozyPaper font-bold text-sm tracking-wide shadow-xl flex items-center space-x-2 border border-warmGold/40 hover:scale-105 transition-all">
                        <span>Click to open your card, Unc</span>
                        <span>✉️</span>
                    </button>

                    <!-- Vintage Stamp Decorative Element -->
                    <div class="absolute top-4 right-4 bg-amberWood/10 border-2 border-dashed border-amberWood/40 p-2 rounded text-[10px] font-bold text-amberWood transform rotate-6">
                        PAR AVION<br>📮 100% CARE
                    </div>
                </div>
            </div>

            <!-- UNFOLDED LETTER / CARD DISPLAY STATE (Hidden Initially) -->
            <div id="letterView" class="hidden w-full max-w-2xl bg-cozyPaper rounded-3xl p-6 md:p-10 shadow-2xl border-4 border-warmGold/50 relative transform transition-all duration-700 opacity-0 scale-95">
                
                <!-- Close / Refold Button -->
                <button onclick="closeLetter()" class="absolute top-4 right-4 text-amberWood/50 hover:text-amberWood bg-amberWood/10 hover:bg-amberWood/20 rounded-full w-8 h-8 flex items-center justify-center font-bold text-sm transition">
                    ✕
                </button>

                <!-- Header Banner -->
                <div class="text-center border-b-2 border-amberWood/20 pb-4 mb-6">
                    <span class="text-3xl">🍵🛋️✨</span>
                    <h2 class="font-header text-2xl md:text-3xl font-extrabold text-amberWood tracking-wide mt-1">Rest & Recovery Order</h2>
                    <p class="text-xs font-bold text-terracotta uppercase tracking-widest mt-1">Official Notice • Strictly Prescribed</p>
                </div>

                <!-- Resting Illustration Graphic -->
                <div class="my-4 p-4 rounded-2xl bg-amberWood/5 border border-amberWood/10 flex items-center justify-around overflow-hidden relative">
                    <div class="flex items-center space-x-4">
                        <div class="relative flex items-center justify-center bg-warmGold/20 p-3.5 rounded-full border border-warmGold/40 shadow-inner">
                            <svg class="w-10 h-10 text-amberWood" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M2 18h20"/>
                                <path d="M4 18v-4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v4"/>
                                <path d="M6 12V9a3 3 0 0 1 3-3h1"/>
                                <circle cx="12" cy="7" r="2"/>
                                <path d="M18 9a2 2 0 0 0-2-2"/>
                            </svg>
                            <span class="absolute -top-1 -right-1 text-base animate-bounce">💤</span>
                        </div>
                        <div class="text-left">
                            <div class="text-xs font-bold text-terracotta uppercase tracking-wider flex items-center space-x-1">
                                <span>🛌 Unc's Relaxation Zone</span>
                            </div>
                            <p class="text-xs font-vintage text-amberWood/90 italic mt-0.5">
                                Feet kicked back, tea in hand, zero work allowed.
                            </p>
                        </div>
                    </div>
                    <div class="hidden sm:block text-3xl opacity-90" title="Taking a peaceful break">
                        🛋️
                    </div>
                </div>

                <!-- Main Letter Body in Vintage Old-World Font (IM Fell English) -->
                <div class="font-vintage text-xl md:text-2xl text-amberWood leading-relaxed tracking-wide italic p-2 my-2 text-left space-y-4">
                    <p class="font-bold not-italic">Dear Unc,</p>
                    <p>
                        Please take good care of yourself. Don't try to go hunt dinosaurs or try to invent fire, but please just sit back, relax, and get some rest!
                    </p>
                </div>

                <!-- Little Kip / Cozy Rest Tip Box -->
                <div class="my-3 p-3.5 bg-amberWood/10 rounded-2xl border border-warmGold/40 flex items-center space-x-3 text-amberWood text-sm">
                    <span class="text-2xl">💤</span>
                    <div>
                        <p class="font-bold text-xs uppercase text-terracotta tracking-wider">Unc's Rest Tip (A Little Kip):</p>
                        <p class="font-vintage italic text-xs md:text-sm">A 20-minute cozy power nap recharges 100% of your legendary energy.</p>
                    </div>
                </div>

                <!-- Card Sign-off -->
                <div class="mt-6 pt-4 border-t-2 border-amberWood/20 flex flex-col sm:flex-row justify-between items-center text-center sm:text-left">
                    <span class="text-xs font-bold text-amberWood/60 tracking-wider uppercase mb-2 sm:mb-0">TAKE CARE & GET WELL SOON</span>
                    <span class="font-vintage text-xl font-bold text-terracotta italic">
                        From the newborn
                    </span>
                </div>

                <!-- Interactive Card Bottom Bar -->
                <div class="mt-6 pt-4 bg-amberWood/5 rounded-2xl p-3 flex flex-wrap justify-around gap-2 text-xs font-bold text-amberWood">
                    <button onclick="brewTea()" class="hover:text-terracotta flex items-center space-x-1">
                        <span>☕ Brew Tea</span>
                    </button>
                    <button onclick="triggerHugShower()" class="hover:text-terracotta flex items-center space-x-1">
                        <span>🤗 Warm Hug</span>
                    </button>
                    <button onclick="openWisdomModal()" class="hover:text-terracotta flex items-center space-x-1">
                        <span>📰 Unc's Gazette</span>
                    </button>
                    <button onclick="closeLetter()" class="hover:text-terracotta flex items-center space-x-1">
                        <span>✉️ Refold Letter</span>
                    </button>
                </div>
            </div>

        </div>
    </main>

    <!-- Footer -->
    <footer class="w-full max-w-4xl text-center text-cozyPaper/50 text-xs py-3 z-20">
        Crafted with love for Unc • Get well soon & take it easy!
    </footer>

    <!-- Daily Gazette / Wisdom Modal -->
    <div id="wisdomModal" class="fixed inset-0 bg-black/70 backdrop-blur-sm z-50 flex justify-center items-center p-4 hidden">
        <div class="bg-cozyPaper text-amberWood max-w-md w-full rounded-3xl p-6 shadow-2xl border-2 border-warmGold relative">
            <button onclick="closeWisdomModal()" class="absolute top-4 right-4 text-amberWood/60 hover:text-amberWood font-bold">✕</button>
            
            <div class="text-center border-b border-amberWood/20 pb-3 mb-4">
                <p class="text-[10px] font-bold text-terracotta uppercase tracking-widest">UNC'S SPECIAL EDITION</p>
                <h3 class="font-header text-xl font-extrabold text-amberWood">The Daily Rest Gazette 📰</h3>
            </div>

            <div class="space-y-4 text-sm font-vintage">
                <div class="bg-amberWood/5 p-3 rounded-xl border border-amberWood/10">
                    <p class="font-bold text-terracotta text-xs uppercase mb-1">Headline of the Day:</p>
                    <p id="gazetteHeadline" class="text-base italic">"Local Legend Instructed to Sit Back, Relax, and Avoid Prehistoric Chores."</p>
                </div>

                <div class="bg-amberWood/5 p-3 rounded-xl border border-amberWood/10">
                    <p class="font-bold text-terracotta text-xs uppercase mb-1">Daily Wisdom Pick:</p>
                    <p id="gazetteQuote" class="text-base italic">"Resting isn't doing nothing; it's recharging your legendary energy."</p>
                </div>
            </div>

            <button onclick="generateNewWisdom()" class="mt-5 w-full py-2.5 rounded-xl bg-warmAmber hover:bg-amber-600 bg-amberWood text-cozyPaper font-bold text-xs transition shadow">
                🎲 Load Another Daily Joke / Quote
            </button>
        </div>
    </div>

    <!-- Notification Toast Popup -->
    <div id="toast" class="fixed bottom-6 left-1/2 -translate-x-1/2 bg-amberWood text-cozyPaper px-5 py-2.5 rounded-full text-xs font-bold shadow-2xl border border-warmGold/40 pointer-events-none opacity-0 transition-opacity duration-300 z-50">
        Message Toast
    </div>

    <!-- Web Audio Synthesizer Script for Ambient Lo-Fi Melodies -->
    <script>
        let isGlassesOn = true;
        let isMusicPlaying = false;
        let audioCtx = null;
        let musicInterval = null;

        // Wisdom & Jokes array for Gazette
        const wisdomList = [
            { headline: "Unc Officially Banned from Hunting Dinosaurs Today", quote: "Take it easy! The dinosaurs can wait until you are 100% recovered." },
            { headline: "Fire Invention Project Postponed indefinitely", quote: "No need to invent fire today, Unc. Just wrap up in a warm blanket!" },
            { headline: "Doctor's Orders: Strict Couch Time Enforced", quote: "Taking rest is officially your primary job today. Do it like a pro!" },
            { headline: "Unc Voted Most Valuable Uncle of the Year", quote: "Get well soon, because everyone is missing your legendary vibe!" }
        ];

        // Open letter action
        function openLetter() {
            const envelopeView = document.getElementById('envelopeView');
            const letterView = document.getElementById('letterView');

            envelopeView.classList.add('hidden');
            letterView.classList.remove('hidden');

            setTimeout(() => {
                letterView.classList.remove('opacity-0', 'scale-95');
                letterView.classList.add('opacity-100', 'scale-100');
            }, 50);

            showToast("Letter opened! Take care, Unc ❤️");
            triggerParticles('💖');

            // Auto-start music if not started
            if (!isMusicPlaying) {
                toggleMusic();
            }
        }

        // Refold letter action
        function closeLetter() {
            const envelopeView = document.getElementById('envelopeView');
            const letterView = document.getElementById('letterView');

            letterView.classList.remove('opacity-100', 'scale-100');
            letterView.classList.add('opacity-0', 'scale-95');

            setTimeout(() => {
                letterView.classList.add('hidden');
                envelopeView.classList.remove('hidden');
            }, 400);

            showToast("Letter refolded cleanly.");
        }

        // Toggle Glasses (Reading filter)
        function toggleGlasses() {
            isGlassesOn = !isGlassesOn;
            const wrapper = document.getElementById('cardContentWrapper');
            const label = document.getElementById('glassesLabel');

            if (isGlassesOn) {
                wrapper.className = 'clear-reading w-full flex justify-center items-center py-4';
                label.innerText = 'Glasses: ON';
                showToast('Reading glasses put on 👓');
            } else {
                wrapper.className = 'blur-reading w-full flex justify-center items-center py-4';
                label.innerText = 'Glasses: OFF';
                showToast('Reading glasses taken off 🕶️');
            }
        }

        // Tea Sip Action
        const teaFlavors = [
            "Hot Chamomile Sip ☕",
            "Ginger & Honey Blend 🍯",
            "Earl Grey Relaxer 🍃",
            "Peppermint Refresh 🌿"
        ];
        let currentTeaIndex = 0;

        function brewTea() {
            currentTeaIndex = (currentTeaIndex + 1) % teaFlavors.length;
            document.getElementById('teaStatus').innerText = teaFlavors[currentTeaIndex];
            showToast(`Sipped warm ${teaFlavors[currentTeaIndex]}!`);
            triggerParticles('☕');
        }

        // Virtual Hug Shower
        function triggerHugShower() {
            showToast("Sending a huge warm hug to Unc! 🤗❤️");
            for (let i = 0; i < 20; i++) {
                setTimeout(() => {
                    triggerParticles(['🤗', '❤️', '✨', '💐'][Math.floor(Math.random() * 4)]);
                }, i * 100);
            }
        }

        // Floating particles creator
        function triggerParticles(symbol) {
            const particle = document.createElement('div');
            particle.className = 'particle text-2xl';
            particle.innerText = symbol;
            particle.style.left = Math.random() * 90 + 5 + 'vw';
            particle.style.bottom = '10px';
            document.body.appendChild(particle);

            setTimeout(() => {
                particle.remove();
            }, 3000);
        }

        // Gazette Modal Controls
        function openWisdomModal() {
            document.getElementById('wisdomModal').classList.remove('hidden');
        }

        function closeWisdomModal() {
            document.getElementById('wisdomModal').classList.add('hidden');
        }

        function generateNewWisdom() {
            const random = wisdomList[Math.floor(Math.random() * wisdomList.length)];
            document.getElementById('gazetteHeadline').innerText = `"${random.headline}"`;
            document.getElementById('gazetteQuote').innerText = `"${random.quote}"`;
            showToast("Updated Daily Gazette!");
        }

        // Toast notification helper
        function showToast(msg) {
            const toast = document.getElementById('toast');
            toast.innerText = msg;
            toast.classList.remove('opacity-0');
            toast.classList.add('opacity-100');

            setTimeout(() => {
                toast.classList.remove('opacity-100');
                toast.classList.add('opacity-0');
            }, 2500);
        }

        // Synth Web Audio Music Player (Relaxing Lo-Fi Chords)
        function toggleMusic() {
            if (!isMusicPlaying) {
                startLoFiMusic();
                isMusicPlaying = true;
                document.getElementById('musicIcon').innerText = '🎵';
                document.getElementById('musicLabel').innerText = 'Radio: ON';
                showToast("Playing cozy lo-fi ambient music 📻");
            } else {
                stopLoFiMusic();
                isMusicPlaying = false;
                document.getElementById('musicIcon').innerText = '📻';
                document.getElementById('musicLabel').innerText = 'Radio: OFF';
                showToast("Radio turned off 🔇");
            }
        }

        function startLoFiMusic() {
            if (!audioCtx) {
                audioCtx = new (window.AudioContext || window.webkitAudioContext)();
            }

            const chords = [
                [261.63, 329.63, 392.00, 493.88], // Cmaj7
                [220.00, 261.63, 329.63, 392.00], // Am7
                [174.61, 220.00, 261.63, 329.63], // Fmaj7
                [196.00, 246.94, 293.66, 349.23]  // G7
            ];

            let chordStep = 0;

            function playChord() {
                if (!isMusicPlaying || !audioCtx) return;

                const now = audioCtx.currentTime;
                const notes = chords[chordStep % chords.length];

                notes.forEach((freq) => {
                    const osc = audioCtx.createOscillator();
                    const gain = audioCtx.createGain();

                    osc.type = 'sine';
                    osc.frequency.setValueAtTime(freq, now);

                    gain.gain.setValueAtTime(0.001, now);
                    gain.gain.linearRampToValueAtTime(0.04, now + 0.4);
                    gain.gain.exponentialRampToValueAtTime(0.0001, now + 2.8);

                    osc.connect(gain);
                    gain.connect(audioCtx.destination);

                    osc.start(now);
                    osc.stop(now + 3.0);
                });

                chordStep++;
            }

            playChord();
            musicInterval = setInterval(playChord, 3000);
        }

        function stopLoFiMusic() {
            if (musicInterval) {
                clearInterval(musicInterval);
            }
        }
    </script>
</body>
</html>
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>UltraTranslate AI - Pro</title>
    
    <!-- Icons & OCR Library -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <script src="https://unpkg.com/tesseract.js@v2.1.0/dist/tesseract.min.js"></script>

    <!-- 📢 1. AD: SOCIAL BAR (Floating) -->
    <script src="https://pl28770303.effectivegatecpm.com/c0/2a/79/c02a794d8ec7eb97efd3257a83d65279.js"></script>

    <style>
        :root { --primary: #2563EB; --bg: #F3F4F6; --white: #ffffff; --text: #1F2937; --shadow: 0 4px 6px -1px rgba(0,0,0,0.1); }
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
        
        /* Padding for Ads */
        body { background-color: var(--bg); color: var(--text); padding-bottom: 100px; padding-top: 60px; }
        
        /* HEADER */
        header { background: var(--primary); color: var(--white); padding: 15px 20px; display: flex; justify-content: space-between; align-items: center; box-shadow: var(--shadow); position: sticky; top: 0; z-index: 50; }
        .logo { font-weight: bold; font-size: 1.2rem; }
        .badge { background: #FCD34D; color: #000; padding: 2px 6px; border-radius: 4px; font-size: 0.7rem; margin-left: 5px; }
        
        main { padding: 15px; max-width: 600px; margin: 0 auto; }
        .card { background: var(--white); border-radius: 12px; padding: 15px; box-shadow: var(--shadow); margin-bottom: 15px; border: 1px solid #e5e7eb; }
        
        /* INPUTS */
        .lang-selector { display: flex; justify-content: space-between; align-items: center; margin-bottom: 10px; border-bottom: 1px solid #eee; padding-bottom: 10px; }
        select { border: none; font-weight: bold; color: var(--primary); background: transparent; font-size: 1rem; outline: none; max-width: 45%; }
        textarea { width: 100%; height: 120px; border: none; resize: none; font-size: 1.1rem; outline: none; background: transparent; }
        
        /* BUTTONS */
        .controls { display: flex; gap: 10px; margin-top: 10px; }
        .icon-btn { width: 45px; height: 45px; border-radius: 50%; border: none; background: #EFF6FF; color: var(--primary); cursor: pointer; font-size: 1.2rem; }
        .main-btn { width: 100%; padding: 16px; background: var(--primary); color: var(--white); border: none; border-radius: 12px; font-weight: bold; font-size: 1.1rem; margin-bottom: 15px; cursor: pointer; }
        
        /* OUTPUT */
        .output-card { background: #F0F9FF; border: 1px solid #BAE6FD; min-height: 120px; }
        .translation-result { font-size: 1.2rem; color: #0C4A6E; font-weight: 500; }
        .hidden { display: none !important; }
        
        /* 📢 ADS CSS */
        .top-ad-container {
            position: fixed; top: 0; left: 0; width: 100%; height: 60px;
            background: #f0f0f0; z-index: 100; text-align: center;
            display: flex; justify-content: center; align-items: center;
            border-bottom: 1px solid #ccc;
        }
        header { top: 60px; } 

        .bottom-ad-container {
            position: fixed; bottom: 0; left: 0; width: 100%; height: 90px;
            background: #f0f0f0; z-index: 100; text-align: center;
            display: flex; justify-content: center; align-items: center;
            border-top: 1px solid #ccc; overflow: hidden;
        }
        
        .middle-ad-container {
            width: 100%; display: flex; justify-content: center; margin-top: 15px; margin-bottom: 10px; overflow: hidden;
        }

        /* UNLOCK MODAL */
        .modal-overlay {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(0,0,0,0.85); z-index: 2000;
            display: flex; justify-content: center; align-items: center;
        }
        .modal-box {
            background: white; width: 90%; max-width: 350px;
            padding: 20px; border-radius: 12px; text-align: center;
            position: relative;
            box-shadow: 0 10px 25px rgba(0,0,0,0.5);
            max-height: 90vh; overflow-y: auto;
        }
        .unlock-btn {
            background: #10B981; color: white; border: none;
            padding: 12px 20px; font-size: 1.1rem; font-weight: bold;
            border-radius: 8px; margin-top: 15px; cursor: pointer;
            width: 100%; box-shadow: 0 4px 10px rgba(16, 185, 129, 0.4);
        }
        .unlock-btn:active { transform: scale(0.95); }

        /* PRIVACY POLICY STYLES */
        .privacy-link {
            display: block; text-align: center; margin-top: 20px; 
            color: #6B7280; text-decoration: underline; font-size: 0.8rem; cursor: pointer;
        }
        .privacy-content { text-align: left; font-size: 0.85rem; line-height: 1.5; color: #333; }
        .privacy-content h3 { color: var(--primary); margin-top: 15px; margin-bottom: 5px; }
        .privacy-content ul { padding-left: 20px; }
    </style>
</head>
<body>

    <!-- 📢 2. AD: TOP BANNER (320x50) -->
    <div class="top-ad-container">
        <script type="text/javascript">
            atOptions = {
                'key' : '6619ba880875ed3b06a13e348704ad81',
                'format' : 'iframe',
                'height' : 50,
                'width' : 320,
                'params' : {}
            };
        </script>
        <script type="text/javascript" src="https://www.highperformanceformat.com/6619ba880875ed3b06a13e348704ad81/invoke.js"></script>
    </div>

    <!-- App Header -->
    <header>
        <div>
            <div class="logo">UltraTranslate <span class="badge">AI</span></div>
            <div id="unlockTimer" style="font-size: 0.75rem; color: #e0f2fe;">Select Language</div>
        </div>
        <div id="status"><i class="fas fa-wifi"></i></div>
    </header>

    <main>
        <!-- Input Area -->
        <div class="card">
            <div class="lang-selector">
                <!-- Source Language (Now has full list) -->
                <select id="sourceLang">
                    <!-- Populated via JS -->
                </select>
                
                <i class="fas fa-arrow-right" style="color:#9CA3AF;"></i>
                
                <!-- Target Language (Locked) -->
                <select id="targetLang">
                    <!-- Populated via JS -->
                </select>
            </div>
            
            <textarea id="inputText" placeholder="Type text here..."></textarea>
            
            <div class="controls">
                <button id="micBtn" class="icon-btn"><i class="fas fa-microphone"></i></button>
                <input type="file" id="cameraInput" accept="image/*" style="display:none"> 
                <button id="camBtn" class="icon-btn"><i class="fas fa-camera"></i></button>
                <button id="clearBtn" class="icon-btn" style="margin-left:auto"><i class="fas fa-trash"></i></button>
            </div>
        </div>

        <button id="translateBtn" class="main-btn">TRANSLATE NOW</button>

        <div class="card output-card">
            <div id="loading" class="hidden" style="padding:20px; text-align:center; color:#2563EB;">Processing...</div>
            <div id="outputText" class="translation-result">Translation result...</div>
        </div>

        <!-- 📢 3. AD: MIDDLE BANNER (468x60 - Below Output) -->
        <div class="middle-ad-container">
            <script type="text/javascript">
                atOptions = {
                    'key' : '52949a19e9be9776a6e44a0a9470f767',
                    'format' : 'iframe',
                    'height' : 60,
                    'width' : 468,
                    'params' : {}
                };
            </script>
            <script type="text/javascript" src="https://www.highperformanceformat.com/52949a19e9be9776a6e44a0a9470f767/invoke.js"></script>
        </div>

        <!-- Privacy Policy Link -->
        <span id="openPrivacyBtn" class="privacy-link"><i class="fas fa-shield-alt"></i> Privacy Policy</span>

    </main>

    <!-- 📢 4. AD: BOTTOM BANNER (728x90) -->
    <div class="bottom-ad-container">
        <script type="text/javascript">
            atOptions = {
                'key' : 'fccb5160815c660c1a82fb2c30d84f99',
                'format' : 'iframe',
                'height' : 90,
                'width' : 728,
                'params' : {}
            };
        </script>
        <script type="text/javascript" src="https://www.highperformanceformat.com/fccb5160815c660c1a82fb2c30d84f99/invoke.js"></script>
    </div>

    <!-- 🔒 UNLOCK POPUP + 📢 5. AD: BANNER 300x250 (Inside Popup) -->
    <div id="lockModal" class="modal-overlay hidden">
        <div class="modal-box">
            <div style="text-align: right;">
                <button id="closeModal" style="background:none; border:none; font-size:1.2rem; cursor:pointer;">✖</button>
            </div>
            
            <h2 style="margin-top:0; color:#EF4444; font-size: 1.2rem;"><i class="fas fa-lock"></i> Locked</h2>
            <p style="color:#666; font-size:0.8rem; margin-bottom:10px;">
                Ad supports our free app.<br>
                <b>View Ad below to Unlock <span id="lockedLangName">Language</span>.</b>
            </p>

            <!-- 300x250 BANNER AD INSIDE POPUP -->
            <div style="background:#fff; padding:0px; border:1px solid #eee; margin-bottom:10px; display:flex; justify-content:center;">
                <script type="text/javascript">
                    atOptions = {
                        'key' : 'a648428dd3769a1b20f070f6bdca18b0',
                        'format' : 'iframe',
                        'height' : 250,
                        'width' : 300,
                        'params' : {}
                    };
                </script>
                <script type="text/javascript" src="https://www.highperformanceformat.com/a648428dd3769a1b20f070f6bdca18b0/invoke.js"></script>
            </div>

            <!-- UNLOCK BUTTON -->
            <button id="finalUnlockBtn" class="unlock-btn">
                <i class="fas fa-unlock"></i> UNLOCK NOW
            </button>
            <p style="font-size:0.6rem; color:#999; margin-top:5px;">Valid for 5 Minutes</p>
        </div>
    </div>

    <!-- 🛡️ PRIVACY POLICY MODAL -->
    <div id="privacyModal" class="modal-overlay hidden">
        <div class="modal-box" style="text-align: left; max-width: 500px;">
            <div style="text-align: right;">
                <button id="closePrivacy" style="background:none; border:none; font-size:1.5rem; cursor:pointer;">✖</button>
            </div>
            <h2 style="color:var(--primary); text-align:center;">Privacy Policy</h2>
            <div class="privacy-content">
                <p><strong>Last Updated:</strong> 22 February 2026</p>
                <h3>1. Introduction</h3>
                <p>Welcome to UltraTranslate AI – Pro (“we”, “our”, “us”).</p>
                <h3>2. Information We Collect</h3>
                <p>We collect minimum required data only:</p>
                <ul>
                    <li>Text entered for translation</li>
                    <li>Images uploaded for OCR</li>
                </ul>
                <h3>6. Contact Information</h3>
                <p>Email: support@ultratranslate.ai<br>
                Website: https://jagannathsing777-art.github.io/UltraTranslate-AI---Pro-Privacy-policy/</p>
            </div>
        </div>
    </div>

    <script>
        // --- CONFIG ---
        const LANGUAGES = [
            {code: "en", name: "English"}, {code: "hi", name: "Hindi"}, {code: "es", name: "Spanish"}, 
            {code: "fr", name: "French"}, {code: "de", name: "German"}, {code: "ar", name: "Arabic"}, 
            {code: "ur", name: "Urdu"}, {code: "bn", name: "Bengali"}, {code: "ru", name: "Russian"}, 
            {code: "ja", name: "Japanese"}, {code: "pt", name: "Portuguese"}, {code: "it", name: "Italian"}
        ];
        
        let unlockedLangs = {};
        const UNLOCK_TIME = 5 * 60 * 1000; // 5 Minutes
        
        const targetSelect = document.getElementById('targetLang');
        const sourceSelect = document.getElementById('sourceLang'); // NEW LEFT SIDE
        const lockModal = document.getElementById('lockModal');
        const timerDisplay = document.getElementById('unlockTimer');
        let pendingLang = null;

        // --- 1. INIT ---
        function renderOptions() {
            // RENDER RIGHT SIDE (Target)
            const currentTarget = targetSelect.value;
            targetSelect.innerHTML = '<option value="">-- To --</option>';
            
            LANGUAGES.forEach(lang => {
                let opt = document.createElement('option');
                opt.value = lang.code;
                if(isUnlocked(lang.code)) {
                    opt.text = `🔓 ${lang.name}`;
                } else {
                    opt.text = `🔒 ${lang.name}`;
                }
                targetSelect.appendChild(opt);
            });
            if(currentTarget) targetSelect.value = currentTarget;

            // RENDER LEFT SIDE (Source) - FULL LIST NOW
            const currentSource = sourceSelect.value;
            sourceSelect.innerHTML = '<option value="auto">Detect</option>';
            
            LANGUAGES.forEach(lang => {
                let opt = document.createElement('option');
                opt.value = lang.code;
                opt.text = lang.name; // No lock on source (standard practice)
                sourceSelect.appendChild(opt);
            });
            if(currentSource) sourceSelect.value = currentSource;
        }

        function isUnlocked(code) {
            return unlockedLangs[code] && Date.now() < unlockedLangs[code];
        }

        // --- 2. EVENTS ---
        targetSelect.addEventListener('change', (e) => {
            const code = e.target.value;
            if(!code) return; 

            const name = LANGUAGES.find(l => l.code === code).name;

            if(!isUnlocked(code)) {
                // Show Popup
                pendingLang = code;
                document.getElementById('lockedLangName').innerText = name;
                lockModal.classList.remove('hidden');
                e.target.value = ""; 
            } else {
                updateTimerUI(code);
            }
        });

        document.getElementById('closeModal').addEventListener('click', () => {
            lockModal.classList.add('hidden');
            targetSelect.value = "";
        });

        // UNLOCK ACTION
        document.getElementById('finalUnlockBtn').addEventListener('click', () => {
            lockModal.classList.add('hidden');
            unlockedLangs[pendingLang] = Date.now() + UNLOCK_TIME;
            renderOptions();
            targetSelect.value = pendingLang;
            updateTimerUI(pendingLang);
            alert("Success! Language Unlocked.");
        });

        // --- 3. TIMER LOOP ---
        setInterval(() => {
            if(targetSelect.value) {
                if(isUnlocked(targetSelect.value)) {
                    updateTimerUI(targetSelect.value);
                } else {
                    targetSelect.value = ""; 
                    renderOptions();
                    timerDisplay.innerText = "Time Expired. Watch Ad again.";
                }
            }
        }, 1000);

        function updateTimerUI(code) {
            const remaining = Math.ceil((unlockedLangs[code] - Date.now()) / 1000);
            const mins = Math.floor(remaining / 60);
            const secs = remaining % 60;
            timerDisplay.innerText = `Unlocked: ${mins}m ${secs}s left`;
        }

        renderOptions();

        // --- 4. TRANSLATION ---
        document.getElementById('translateBtn').addEventListener('click', async () => {
            const text = document.getElementById('inputText').value;
            const target = targetSelect.value;
            const source = sourceSelect.value; // Get selected source
            
            if(!text) return alert("Enter text");
            if(!target) return alert("Select a target language first");

            const output = document.getElementById('outputText');
            const loading = document.getElementById('loading');
            
            output.classList.add('hidden');
            loading.classList.remove('hidden');

            try {
                // Use selected source in API call
                const res = await fetch(`https://api.mymemory.translated.net/get?q=${encodeURIComponent(text)}&langpair=${source}|${target}`);
                const data = await res.json();
                output.innerText = data.responseData.translatedText;
            } catch(e) {
                output.innerText = "Error: Check internet";
            } finally {
                loading.classList.add('hidden');
                output.classList.remove('hidden');
            }
        });

        document.getElementById('clearBtn').onclick = () => document.getElementById('inputText').value = "";

        // --- 5. PRIVACY POLICY MODAL ---
        const privacyModal = document.getElementById('privacyModal');
        document.getElementById('openPrivacyBtn').addEventListener('click', () => {
            privacyModal.classList.remove('hidden');
        });
        document.getElementById('closePrivacy').addEventListener('click', () => {
            privacyModal.classList.add('hidden');
        });
    </script>
</body>
</html>

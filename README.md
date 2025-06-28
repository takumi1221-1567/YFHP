<!DOCTYPE html>
<html lang="ja" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- SEO Meta Tags -->
    <title>YANFOX - Mixing & Mastering Service</title>
    <meta name="description" content="EDM・HIPHOP・POPSを中心に、あなたの音楽にプロのクオリティを。個人クリエイターYANFOXによる高品質なミックス・マスタリングサービス。初回限定価格でご提供中。">
    <meta name="keywords" content="ミックス, マスタリング, mix, mastering, DTM, 作曲, 編曲, EDM, HIPHOP, POPS, YANFOX, HIROMI MIURA, 音楽制作, 音圧, パラミックス">
    <meta name="author" content="YANFOX">

    <!-- OGP Tags for Social Sharing -->
    <meta property="og:title" content="YANFOX - Mixing & Mastering Service">
    <meta property="og:description" content="EDM・HIPHOP・POPSを中心に、あなたの音楽にプロのクオリティを。高品質なミックス・マスタリングサービス。">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://your-domain.com"> <!-- TODO: Add your domain here -->
    <meta property="og:image" content="https://placehold.co/1200x630/1a202c/718096?text=YANFOX"> <!-- TODO: Replace with your own image -->
    <meta property="og:site_name" content="YANFOX - Mixing & Mastering Service">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:site" content="@yanfox1031">
    <meta name="twitter:title" content="YANFOX - Mixing & Mastering Service">
    <meta name="twitter:description" content="高品質なミックス・マスタリングサービス。EDM・HIPHOP・POPSなどジャンル問わず対応。">
    <meta name="twitter:image" content="https://placehold.co/1200x630/1a202c/718096?text=YANFOX"> <!-- TODO: Replace with your own image -->


    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&family=Noto+Sans+JP:wght@400;700&display=swap" rel="stylesheet">
    
    <!-- Custom Styles -->
    <style>
        body {
            font-family: 'Inter', 'Noto Sans JP', sans-serif;
            background-color: #0c0a09; /* Near black background */
            color: #e2e8f0; /* Light gray text */
        }
        .hero-gradient {
            background: radial-gradient(circle, rgba(29, 78, 216, 0.2) 0%, rgba(12, 10, 9, 0) 60%);
        }
        .section-title {
            font-family: 'Inter', sans-serif;
            font-weight: 900;
            font-size: 2.5rem; /* 40px */
            letter-spacing: -0.05em;
            text-transform: uppercase;
            color: #fff;
            margin-bottom: 2.5rem; /* 40px */
            text-align: center;
        }
        @media (min-width: 768px) {
            .section-title {
                font-size: 4rem; /* 64px */
            }
        }
        .glass-card {
            background: rgba(30, 41, 59, 0.3); /* Slate-800 with opacity */
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 1rem; /* 16px */
            padding: 2rem; /* 32px */
            transition: all 0.3s ease;
        }
        .glass-card:hover {
            border-color: rgba(59, 130, 246, 0.5);
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }
        .btn {
            display: inline-block;
            padding: 0.75rem 2rem;
            border-radius: 9999px;
            font-weight: 700;
            text-transform: uppercase;
            transition: all 0.3s ease;
            text-decoration: none;
        }
        .btn-primary {
            background-color: #2563eb; /* Blue-600 */
            color: #fff;
        }
        .btn-primary:hover {
            background-color: #3b82f6; /* Blue-500 */
            transform: scale(1.05);
        }
        .btn-secondary {
            background-color: transparent;
            color: #e2e8f0;
            border: 2px solid #334155; /* Slate-700 */
        }
        .btn-secondary:hover {
            background-color: #1e293b; /* Slate-800 */
            border-color: #475569; /* Slate-600 */
        }
        .responsive-iframe-container {
            position: relative;
            overflow: hidden;
            width: 100%;
            padding-top: 56.25%; /* 16:9 Aspect Ratio */
            border-radius: 0.5rem;
        }
        .responsive-iframe-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            bottom: 0;
            right: 0;
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header -->
    <header class="sticky top-0 z-50 bg-black/50 backdrop-blur-sm border-b border-slate-800">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-black text-white uppercase tracking-wider">YANFOX</a>
            <nav class="hidden md:flex space-x-8">
                <a href="#about" class="text-slate-300 hover:text-white transition">About</a>
                <a href="#services" class="text-slate-300 hover:text-white transition">Services</a>
                <a href="#portfolio" class="text-slate-300 hover:text-white transition">Portfolio</a>
                <a href="#contact" class="text-slate-300 hover:text-white transition">Contact</a>
            </nav>
            <a href="#contact" class="btn btn-primary hidden md:inline-block">依頼する</a>
        </div>
    </header>

    <!-- Main Content -->
    <main>

        <!-- Hero Section -->
        <section id="hero" class="min-h-screen flex items-center justify-center text-center px-6 relative overflow-hidden hero-gradient">
            <div class="max-w-3xl">
                <h1 class="text-4xl md:text-6xl lg:text-7xl font-black uppercase text-white tracking-tighter leading-tight">
                    <span class="bg-clip-text text-transparent bg-gradient-to-r from-blue-400 to-cyan-400">Professional Quality</span>
                    <br>For Your Music
                </h1>
                <p class="mt-6 text-lg md:text-xl text-slate-400 max-w-2xl mx-auto">
                    あなたの音楽に、プロのクオリティを。 <br class="md:hidden">
                    EDM・HIPHOP・POPSを中心に、ジャンル問わず高品質なミックス・マスタリングを提供します。
                </p>
                <div class="mt-8 bg-blue-900/50 border border-blue-500 inline-block p-4 rounded-lg shadow-lg">
                    <p class="text-xl font-bold text-cyan-300 animate-pulse">初回3件限定：¥3,000で受付中！</p>
                </div>
                <div class="mt-10 flex justify-center gap-4">
                    <a href="#services" class="btn btn-secondary">サービス詳細</a>
                    <a href="#contact" class="btn btn-primary">今すぐ依頼する</a>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="py-20 md:py-32">
            <div class="container mx-auto px-6">
                <h2 class="section-title">About Me</h2>
                <div class="max-w-4xl mx-auto flex flex-col md:flex-row items-center gap-8 md:gap-12">
                    <div class="w-48 h-48 md:w-60 md:h-60 flex-shrink-0">
                        <img src="https://placehold.co/240x240/0c0a09/e2e8f0?text=YF" alt="YANFOX アバター画像" class="w-full h-full rounded-full object-cover border-4 border-slate-700">
                    </div>
                    <div>
                        <h3 class="text-3xl font-bold text-white">YANFOX <span class="text-slate-400 text-lg">(ヤンフォックス)</span></h3>
                        <p class="mt-4 text-slate-300 leading-relaxed">
                            東京を拠点に活動するミックス・マスタリングエンジニアです。
                            自身のアーティスト活動（HIROMI MIURA名義）でも多数の楽曲を手がけ、ジャンルに縛られない音作りを追求しています。
                            初めての方でも安心してご依頼いただけるよう、丁寧なやり取りを心がけています。音楽を通して、あなたの創作活動を全力でサポートします。
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Services Section -->
        <section id="services" class="py-20 md:py-32 bg-slate-900/50">
            <div class="container mx-auto px-6">
                <h2 class="section-title">Services</h2>
                <div class="grid md:grid-cols-2 gap-8 max-w-6xl mx-auto">
                    <!-- Service Details -->
                    <div class="glass-card">
                        <h3 class="text-2xl font-bold text-white mb-6 flex items-center gap-3">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-blue-400"><path d="M12 2a10 10 0 1 0 10 10A10 10 0 0 0 12 2v0Z"/><path d="M12 18a6 6 0 1 0 0-12 6 6 0 0 0 0 12Z"/><path d="M12 14a2 2 0 1 0 0-4 2 2 0 0 0 0 4Z"/></svg>
                            基本内容
                        </h3>
                        <ul class="space-y-4 text-slate-300">
                            <li class="flex items-start"><span class="text-blue-400 mr-3 mt-1">🔹</span><div><strong>ミックス料金：</strong><span class="font-bold text-white">無料</span>（1曲）<br><small>※無料期間終了後、または2曲目以降は1曲 3,000円</small></div></li>
                            <li class="flex items-start"><span class="text-blue-400 mr-3 mt-1">🔹</span><div><strong>対応形式：</strong>パラミックス対応（ステムMIXもOK）</div></li>
                            <li class="flex items-start"><span class="text-blue-400 mr-3 mt-1">🔹</span><div><strong>曲の長さ：</strong><span class="font-bold text-white">無制限</span>（期間限定）</div></li>
                            <li class="flex items-start"><span class="text-blue-400 mr-3 mt-1">🔹</span><div><strong>推奨データ形式：</strong>wav（16bit or 24bit / 44.1kHz or 48kHz）</div></li>
                            <li class="flex items-start"><span class="text-blue-400 mr-3 mt-1">🔹</span><div><strong>修正：</strong><span class="font-bold text-white">2回まで無料対応</span></div></li>
                            <li class="flex items-start"><span class="text-blue-400 mr-3 mt-1">🔹</span><div><strong>納期目安：</strong><span class="font-bold text-white">3〜7日目安</span>（内容や混雑状況により変動）</div></li>
                            <li class="flex items-start"><span class="text-blue-400 mr-3 mt-1">🔹</span><div>着手前に簡単なアンケートにご回答いただき、そちらをもとに方向性を決定します</div></li>
                        </ul>
                    </div>
                    <!-- Workflow -->
                    <div class="glass-card">
                        <h3 class="text-2xl font-bold text-white mb-6 flex items-center gap-3">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-blue-400"><path d="M3 6h18"/><path d="M19 6v14a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V6"/><path d="M8 6V4a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2"/><line x1="10" x2="10" y1="11" y2="17"/><line x1="14" x2="14" y1="11" y2="17"/></svg>
                            ご依頼の流れ
                        </h3>
                        <ol class="space-y-4 text-slate-300">
                            <li class="flex"><span class="text-blue-400 font-bold mr-3">1.</span> <div>DMまたは専用フォームからご連絡ください</div></li>
                            <li class="flex"><span class="text-blue-400 font-bold mr-3">2.</span> <div>アンケートにご回答いただきます</div></li>
                            <li class="flex"><span class="text-blue-400 font-bold mr-3">3.</span> <div>音源（ステム or 2mix）と参考曲などをご提出</div></li>
                            <li class="flex"><span class="text-blue-400 font-bold mr-3">4.</span> <div>ミックス作業開始（確認→修正2回まで）</div></li>
                            <li class="flex"><span class="text-blue-400 font-bold mr-3">5.</span> <div>完成音源を納品</div></li>
                        </ol>
                    </div>
                </div>
                 <div class="text-center mt-12 glass-card max-w-3xl mx-auto">
                    <h3 class="text-xl font-bold text-white">🔻 ご相談だけでもお気軽にどうぞ 🔻</h3>
                    <p class="mt-2 text-slate-400">「こういうジャンルもできる？」「ボーカル処理だけお願いしたい」など柔軟に対応可能です。</p>
                </div>
            </div>
        </section>

        <!-- Portfolio Section -->
        <section id="portfolio" class="py-20 md:py-32">
            <div class="container mx-auto px-6">
                <h2 class="section-title">Portfolio</h2>
                <div class="grid md:grid-cols-2 gap-8 max-w-6xl mx-auto">
                    <div>
                        <div class="responsive-iframe-container shadow-2xl">
                            <iframe src="https://www.youtube.com/embed/2KbRP0tO4YY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                        </div>
                        <h3 class="text-lg font-bold text-white mt-4">HIROMI MIURA - ABALIBERA (Lyric Video)</h3>
                    </div>
                    <div>
                        <div class="responsive-iframe-container shadow-2xl">
                            <iframe src="https://www.youtube.com/embed/lY3BYfBbqF0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                        </div>
                        <h3 class="text-lg font-bold text-white mt-4">HIROMI MIURA - KAMIKAZE NOIZ</h3>
                    </div>
                </div>
            </div>
        </section>

        <!-- Chatbot Section -->
        <section id="chatbot" class="py-20 md:py-32 bg-slate-900/50">
            <div class="container mx-auto px-6">
                 <h2 class="section-title">AI Assistant</h2>
                 <p class="text-center text-slate-400 -mt-8 mb-12 max-w-2xl mx-auto">簡単な質問はこちらのチャットボットでも24時間対応しています。サービス内容や納期など、お気軽にご質問ください。</p>
                 <div class="max-w-4xl mx-auto rounded-lg overflow-hidden border border-slate-700">
                    <iframe
                      src="https://udify.app/chatbot/Y7QUaLYZejoU2MUT"
                      style="width: 100%; height: 600px; min-height: 500px;"
                      frameborder="0"
                      allow="microphone">
                    </iframe>
                 </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20 md:py-32">
            <div class="container mx-auto px-6">
                <h2 class="section-title">Contact & Order</h2>
                <div class="max-w-4xl mx-auto text-center">
                    <p class="text-lg text-slate-300 mb-8">ご依頼、ご相談は以下のフォーム、またはX(旧Twitter)のDMからお気軽にご連絡ください。</p>
                    <div class="flex justify-center items-center gap-6 mb-12">
                         <a href="https://x.com/yanfox1031" target="_blank" rel="noopener noreferrer" class="btn btn-secondary inline-flex items-center gap-2">
                             <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" viewBox="0 0 16 16">
                                <path d="M12.6.75h2.454l-5.36 6.142L16 15.25h-4.937l-3.867-5.07-4.425 5.07H.316l5.733-6.57L0 .75h5.063l3.495 4.633L12.6.75Zm-.86 13.028h1.36L4.323 2.145H2.865l8.875 11.633Z"/>
                             </svg>
                             X (Twitter)で連絡
                         </a>
                    </div>
                    <div class="glass-card text-left">
                        <h3 class="text-2xl font-bold text-white mb-4">ご依頼フォーム</h3>
                        <p class="text-slate-400 mb-6">以下のフォームからご連絡ください（メールアドレスは公開しておりません）。</p>
                        <div class="w-full h-[800px] md:h-[700px] bg-white/5 rounded-lg">
                             <iframe
                                src="https://docs.google.com/forms/d/e/1FAIpQLSe2gs3AoqguuNmDGMAV2ngPwE7TMPuT45-KfCL7Z9mImY_igw/viewform?embedded=true" 
                                width="100%" 
                                height="100%" 
                                frameborder="0" 
                                marginheight="0" 
                                marginwidth="0"
                                class="rounded-lg">
                                読み込んでいます…
                            </iframe>
                        </div>
                   </div>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-black py-8 border-t border-slate-800">
        <div class="container mx-auto px-6 text-center text-slate-500">
            <p>&copy; 2025 YANFOX. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>

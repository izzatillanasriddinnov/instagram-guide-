index.xtml  
<!DOCTYPE html>  
<html lang="uz">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Claude orqali Instagram Tahlili va Kontent Yaratish</title>  
    <link rel="preconnect" href="https://fonts.googleapis.com">  
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>  
    <link href="https://fonts.googleapis.com/css2?family=Caveat:wght@600;700&family=Inter:wght@400;600;700&family=Oswald:wght@600;700&family=Fira+Code:wght@400;500&display=swap" rel="stylesheet">  
      
    <style>  
        :root {  
            --bg-color: #f7f4eb;  
            --text-color: #1a1a1a;  
            --border-color: #1a1a1a;  
            --box-bg: #fdfbf7;  
            --prompt-bg: #efece4;  
            --highlight: #f8dbb2;  
        }  
  
        body {  
            background-color: var(--bg-color);  
            color: var(--text-color);  
            font-family: 'Inter', sans-serif;  
            line-height: 1.6;  
            margin: 0;  
            padding: 20px 15px;  
            display: flex;  
            justify-content: center;  
        }  
  
        .container {  
            max-width: 680px;  
            width: 100%;  
        }  
  
        /* Sarlavhalar (Oswald - Qalin va tekis) */  
        h1 {  
            font-family: 'Oswald', sans-serif;  
            text-transform: uppercase;  
            font-size: 28px;  
            letter-spacing: 0.5px;  
            margin-bottom: 8px;  
            line-height: 1.2;  
            border-bottom: 2px solid var(--border-color);  
            padding-bottom: 8px;  
        }  
  
        h2 {  
            font-family: 'Oswald', sans-serif;  
            text-transform: uppercase;  
            font-size: 22px;  
            margin-top: 35px;  
            margin-bottom: 15px;  
            border-bottom: 2px solid var(--border-color);  
            display: inline-block;  
        }  
  
        h3 {  
            font-size: 18px;  
            font-weight: 700;  
            margin-top: 25px;  
            margin-bottom: 10px;  
        }  
  
        p, li {  
            font-size: 16px;  
            color: #2c2c2c;  
        }  
  
        .highlight-text {  
            background-color: var(--highlight);  
            padding: 2px 6px;  
            border-radius: 4px;  
            font-weight: 600;  
        }  
  
        /* Qo'lda chizilgandek ko'rinuvchi bloklar (Doodle Boxes) */  
        .sketch-box {  
            background-color: var(--box-bg);  
            border: 2px solid var(--border-color);  
            border-radius: 12px 255px 15px 225px/255px 15px 225px 12px;  
            padding: 20px;  
            margin: 20px 0;  
            box-shadow: 2px 3px 0px var(--border-color);  
            text-align: center;  
        }  
  
        .sketch-title {  
            font-family: 'Caveat', cursive;  
            font-size: 26px;  
            font-weight: 700;  
            margin: 0 0 5px 0;  
            text-transform: uppercase;  
        }  
  
        .sketch-sub {  
            font-family: 'Caveat', cursive;  
            font-size: 19px;  
            color: #555;  
            margin: 0;  
        }  
  
        /* Strelka */  
        .arrow {  
            text-align: center;  
            font-size: 24px;  
            margin: -10px 0;  
            color: var(--border-color);  
        }  
  
        /* Prompt Bloklari (Kod bloklari) */  
        .prompt-container {  
            background-color: var(--box-bg);  
            border: 2px solid var(--border-color);  
            border-radius: 8px;  
            padding: 15px;  
            margin: 20px 0;  
            position: relative;  
        }  
  
        .prompt-header {  
            font-family: 'Caveat', cursive;  
            font-size: 20px;  
            font-weight: 700;  
            margin-bottom: 8px;  
            color: #333;  
        }  
  
        pre {  
            background-color: var(--prompt-bg);  
            border: 1px dashed var(--border-color);  
            padding: 12px;  
            border-radius: 6px;  
            font-family: 'Fira Code', monospace;  
            font-size: 13.5px;  
            white-space: pre-wrap;  
            word-break: break-word;  
            overflow-x: auto;  
            margin: 0;  
        }  
  
        /* Checkbox ro'yxat */  
        .step-list {  
            list-style: none;  
            padding-left: 0;  
        }  
  
        .step-list li {  
            position: relative;  
            padding-left: 32px;  
            margin-bottom: 12px;  
        }  
  
        .step-list li::before {  
            content: '';  
            position: absolute;  
            left: 0;  
            top: 3px;  
            width: 18px;  
            height: 18px;  
            border: 2px solid var(--border-color);  
            border-radius: 3px;  
            background-color: #fff;  
        }  
  
        .step-list li.checked::before {  
            background-color: #ff9d42;  
        }  
  
        .note {  
            font-size: 14px;  
            font-style: italic;  
            color: #666;  
            margin-bottom: 8px;  
        }  
    </style>  
</head>  
<body>  
  
<div class="container">  
  
    <h1>Claude orqali Instagram profilingizni tahlil qilish va tayyor kontent yaratish</h1>  
      
    <p>Ushbu qo'llanma yordamida siz Instagram profilingizdagi real ko'rsatkichlarni Sun'iy Intellekt (Claude) orqali chuqur tahlil qilishingiz hamda tayyor video (Reels) ssenariylarini olishingiz mumkin.</p>  
    <p>Jarayon <span class="highlight-text">mutlaqo tekin</span>, sodda va hech qanday dasturlash bilimlarini talab qilmaydi.</p>  
  
    <h2>KORXONA QANDAY ISHLAYDI:</h2>  
  
    <div class="sketch-box">  
        <p class="sketch-title">Acha o Viral</p>  
        <p class="sketch-sub">nishingizdagi eng ko'p ko'rilgan videolarni topadi</p>  
    </div>  
  
    <div class="arrow">↓</div>  
  
    <div class="sketch-box">  
        <p class="sketch-title">Vira Roteiro</p>  
        <p class="sketch-sub">tasvirga olish uchun aniq video ssenariysi</p>  
    </div>  
  
    <div class="arrow">↓</div>  
  
    <div class="sketch-box">  
        <p class="sketch-title">O'z Profilingizga Joylaysiz</p>  
        <p class="sketch-sub">CTA: izohlarda kalit so'zni yozishni so'raysiz</p>  
    </div>  
  
    <div class="arrow">↓</div>  
  
    <div class="sketch-box" style="background-color: var(--highlight);">  
        <p class="sketch-title">Yangi va Aniq Obunachilar</p>  
        <p class="sketch-sub">sizning maqsadli auditoriyangizdan obunachi keladi</p>  
    </div>  
  
    <h2>1-BOSQICH: ULANISH ADAPTORI</h2>  
  
    <ul class="step-list">  
        <li>Claude saytida <b>Connectors</b> bo'limiga kiring.</li>  
        <li class="checked"><b>Windsor</b> servisini qidirib toping va qo'shing.</li>  
        <li class="checked">Facebook orqali kirib, Instagram profilingizga ruxsat bering.</li>  
        <li>Ruxsat berish rejimini <b>"Doim ruxsat berish"</b> qilib belgilang.</li>  
    </ul>  
  
    <h2>2-BOSQICH: TAYYOR PROMPTLAR</h2>  
  
    <p class="note">↓ Ushbu promptlarni ketma-ketlikda Claude chatiga tashlang.</p>  
  
    <div class="prompt-container">  
        <div class="prompt-header">passo 1 · birinchi bering</div>  
        <h3>PROMPT 1 – Instagram Audit (Roast)</h3>  
        <p class="note">Eslatma: [SIZNING_NIKINGIZ] o'rniga Instagram username'ingizni yozing.</p>  
        <pre>You have full access to my Instagram account ([SIZNING_NIKINGIZ]).  
I want you to roast me, honestly, no sugar-coating. Instagram only, no other platforms.  
  
Step 1: Pull my last 30 to 50 reels. Identify my TOP 10 performing reels (by views, saves, shares; weight saves and shares heavily, not just likes).  
  
Step 2: For each of those 10 reels, analyze:  
- Hook type  
- Topic / content pillar  
- Format (talking head, b-roll, text-on-screen, etc.)  
- What's WORKING (be specific: the hook? the pacing? the topic?)  
- What's NOT working / what's holding it back from going bigger  
  
Step 3: Output the analysis as a clean, visually striking PDF I can save and screen-record.</pre>  
    </div>  
  
    <div class="prompt-container">  
        <div class="prompt-header">passo 2 · auditdan so'ng</div>  
        <h3>PROMPT 2 – Reels Ssenariynovisi (3 ta Ssenariy)</h3>  
        <pre>Use the reel-scriptwriter skill to write me 3 Instagram Reel scripts (30 to 55 seconds each) in MY authentic voice, based on the strategy you just built.  
  
CRITICAL: match the structure of this reel I just shot:  
  
[HOOK: 1 punchy sentence that creates intrigue or stakes]  
[CONTEXT: 1 to 2 sentences that raise the stakes or set up credibility]  
[PROMISE: "Here are the 3 things..." or equivalent]  
  
#1) [Point one: include a personal/vulnerable beat, not just info]  
#2) [Point two: include a tangible outcome or artifact]  
#3) [Point three: include a meta moment that ties back to THIS reel]  
  
[CTA: comment-bait with a specific keyword]  
[FOLLOW CTA: "Follow for more..."]</pre>  
    </div>  
  
    <div class="prompt-container">  
        <div class="prompt-header">passo 3 · tayyor material yaratish</div>  
        <h3>PROMPT 3 – Yopiq Material Yaratish</h3>  
        <pre>Now create the EXCLUSIVE MATERIAL that I will send via DM to anyone who comments the keyword on the video (via ManyChat).  
  
Base it on my niche from this conversation and the script you recommended I film first. The material must DELIVER exactly what that video promised, making the person feel it was worth following.</pre>  
    </div>  
  
</div>  
  
</body>  
</html>  

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>🪔 Happy Diwali & Maa Kali Puja 2026 — Tanmoy Dey & Family</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Cinzel+Decorative:wght@400;700;900&family=Crimson+Text:ital,wght@0,400;0,600;1,400;1,600&family=Orbitron:wght@400;700;900&display=swap');

    :root {
      --gold: #ffd700;
      --deep-gold: #ff8c00;
      --pink: #ff0080;
      --light-pink: #ff99cc;
      --purple: #4a0070;
      --dark: #05000d;
      --cream: #ffe4b5;
    }
    * { margin:0; padding:0; box-sizing:border-box; }

    body {
      background: var(--dark);
      min-height: 100vh;
      overflow-x: hidden;
      font-family: 'Crimson Text', Georgia, serif;
    }

    /* ═══════════════════════════════════
       STARFIELD
    ═══════════════════════════════════ */
    #starCanvas {
      position: fixed; inset: 0; z-index: 0; pointer-events: none;
    }

    /* ═══════════════════════════════════
       KALI MAA BACKGROUND
    ═══════════════════════════════════ */
    .kali-bg-wrap {
      position: fixed; inset: 0; z-index: 1;
      display: flex; align-items: center; justify-content: center;
      overflow: hidden;
    }
    .kali-svg-container {
      opacity: 0.22;
      animation: kaliBreath 7s ease-in-out infinite;
      filter: drop-shadow(0 0 80px #ff0080) drop-shadow(0 0 160px #8b0000);
    }
    @keyframes kaliBreath {
      0%,100% { opacity:.20; transform:scale(1)   rotate(-0.5deg); filter: drop-shadow(0 0 60px #ff0080) drop-shadow(0 0 120px #8b0000); }
      50%     { opacity:.28; transform:scale(1.04) rotate( 0.5deg); filter: drop-shadow(0 0 110px #ff0080) drop-shadow(0 0 220px #cc0000); }
    }

    /* ═══════════════════════════════════
       COSMIC AURA OVERLAY
    ═══════════════════════════════════ */
    .aura {
      position: fixed; inset: 0; z-index: 2; pointer-events: none;
      background:
        radial-gradient(ellipse 85% 85% at 50% 50%, rgba(100,0,60,.5) 0%, transparent 70%),
        radial-gradient(ellipse 60% 40% at 50% 25%, rgba(180,0,0,.2) 0%, transparent 60%),
        radial-gradient(ellipse 100% 60% at 50% 100%, rgba(40,0,80,.65) 0%, transparent 55%);
    }

    /* ═══════════════════════════════════
       FIREWORKS CANVAS
    ═══════════════════════════════════ */
    #fwCanvas {
      position: fixed; inset: 0; z-index: 3; pointer-events: none;
    }

    /* ═══════════════════════════════════
       FLOATING PETALS
    ═══════════════════════════════════ */
    .petal {
      position: fixed; z-index: 4; pointer-events: none;
      font-size: 1.3rem;
      animation: petalFall linear infinite;
      opacity: .7;
    }
    @keyframes petalFall {
      0%   { transform: translateY(-60px) rotate(0deg); opacity:.8; }
      100% { transform: translateY(110vh)  rotate(720deg); opacity:0; }
    }

    /* ═══════════════════════════════════
       SCROLL WRAPPER
    ═══════════════════════════════════ */
    .page {
      position: relative; z-index: 10;
      min-height: 100vh;
      display: flex; flex-direction: column; align-items: center;
      padding: 28px 16px 70px;
    }

    /* ═══════════════════════════════════
       TOP ORNAMENT STRIP
    ═══════════════════════════════════ */
    .ornament {
      font-size: clamp(1.4rem, 4vw, 2rem);
      letter-spacing: 10px;
      color: var(--gold);
      text-shadow: 0 0 14px #ff8c00, 0 0 30px #ffd700;
      margin-bottom: 8px;
      animation: shimmerOrnament 2s ease-in-out infinite alternate;
    }
    @keyframes shimmerOrnament {
      from { letter-spacing:8px; filter:brightness(1); }
      to   { letter-spacing:13px; filter:brightness(1.6); }
    }

    /* ═══════════════════════════════════
       FROM BADGE
    ═══════════════════════════════════ */
    .from-badge {
      display: inline-flex; align-items: center; gap: 10px;
      background: linear-gradient(135deg,rgba(100,0,50,.8),rgba(50,0,80,.9));
      border: 1px solid rgba(255,215,0,.5);
      border-radius: 50px;
      padding: 10px 28px;
      margin-bottom: 18px;
      animation: badgeGlow 3s ease-in-out infinite alternate;
      backdrop-filter: blur(8px);
    }
    @keyframes badgeGlow {
      from { box-shadow: 0 0 15px rgba(255,0,128,.4), 0 0 30px rgba(255,140,0,.2); border-color:rgba(255,215,0,.4); }
      to   { box-shadow: 0 0 35px rgba(255,0,128,.8), 0 0 60px rgba(255,140,0,.4); border-color:rgba(255,215,0,.95); }
    }
    .from-badge .avatar {
      width: 42px; height: 42px; border-radius: 50%;
      background: linear-gradient(135deg,#8b0000,#c0006a);
      border: 2px solid var(--gold);
      display: flex; align-items: center; justify-content: center;
      font-size: 1.3rem;
      box-shadow: 0 0 12px #ffd700;
    }
    .from-badge .from-text {
      font-family: 'Cinzel Decorative', serif;
      font-size: clamp(.75rem, 2vw, 1rem);
      color: var(--gold);
      text-shadow: 0 0 8px #ff8c00;
      line-height: 1.4;
    }
    .from-badge .from-text span {
      color: var(--light-pink);
      text-shadow: 0 0 8px #ff0080;
    }

    /* ═══════════════════════════════════
       TITLES
    ═══════════════════════════════════ */
    .title-diwali {
      font-family: 'Cinzel Decorative', serif;
      font-weight: 900;
      font-size: clamp(2rem, 7vw, 4.8rem);
      text-align: center; line-height: 1.2;
      background: linear-gradient(135deg, #fff7a1 0%, #ffd700 20%, #ff8c00 50%, #ffd700 80%, #fff7a1 100%);
      -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;
      background-size: 300% 300%;
      animation: titleGold 5s linear infinite;
      filter: drop-shadow(0 0 25px rgba(255,215,0,.7));
      margin-bottom: 4px;
    }
    @keyframes titleGold {
      0%  { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100%{ background-position: 0% 50%; }
    }
    .title-kali {
      font-family: 'Cinzel Decorative', serif;
      font-weight: 900;
      font-size: clamp(1.5rem, 5.5vw, 3.8rem);
      text-align: center; line-height: 1.25;
      background: linear-gradient(135deg, #ffb3de 0%, #ff0080 30%, #c0006a 60%, #ff66b2 100%);
      -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;
      background-size: 300% 300%;
      animation: titlePink 4s linear infinite;
      filter: drop-shadow(0 0 22px rgba(255,0,128,.8));
      margin-bottom: 20px;
    }
    @keyframes titlePink {
      0%  { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100%{ background-position: 0% 50%; }
    }

    /* ═══════════════════════════════════
       GOLD DIVIDER
    ═══════════════════════════════════ */
    .divider {
      width: 85%; max-width: 650px;
      height: 2px;
      background: linear-gradient(90deg, transparent, #ffd700, #ff0080, #ffd700, transparent);
      margin: 8px auto 22px;
      animation: divPulse 2.5s ease-in-out infinite alternate;
      border-radius: 2px;
    }
    @keyframes divPulse {
      from { box-shadow: 0 0 8px #ffd700; opacity:.8; }
      to   { box-shadow: 0 0 30px #ff0080, 0 0 60px #ffd700; opacity:1; }
    }

    /* ═══════════════════════════════════
       DIYA ROW
    ═══════════════════════════════════ */
    .diya-row {
      display: flex; justify-content: center;
      gap: clamp(16px, 4vw, 52px);
      flex-wrap: wrap;
      margin: 6px 0 20px;
    }
    .diya {
      display: flex; flex-direction: column; align-items: center;
      animation: diyaFloat 3.2s ease-in-out infinite;
    }
    .diya:nth-child(1){animation-delay:0s}
    .diya:nth-child(2){animation-delay:.35s}
    .diya:nth-child(3){animation-delay:.7s}
    .diya:nth-child(4){animation-delay:1.05s}
    .diya:nth-child(5){animation-delay:1.4s}
    .diya:nth-child(6){animation-delay:1.75s}
    .diya:nth-child(7){animation-delay:2.1s}
    @keyframes diyaFloat {
      0%,100%{ transform:translateY(0) rotate(0deg); }
      50%    { transform:translateY(-9px) rotate(1deg); }
    }

    .flame-stack {
      position: relative; width: 24px; height: 50px;
      display: flex; align-items: flex-end; justify-content: center;
      margin-bottom: -6px;
    }
    .fl { position:absolute; bottom:0; border-radius: 50% 50% 20% 20% / 70% 70% 30% 30%; }
    .fl-o { width:20px; height:40px; background:radial-gradient(ellipse at 50% 100%, #ff4500 0%, #ff8c00 40%, #ffd700 70%, transparent 100%); filter:blur(1.5px); animation:flk .55s ease-in-out infinite alternate; }
    .fl-m { width:13px; height:28px; background:radial-gradient(ellipse at 50% 100%, #fff 0%, #fffacd 40%, #ffd700 80%, transparent 100%); animation:flk .55s ease-in-out infinite alternate-reverse; }
    .fl-i { width:6px;  height:14px; background:radial-gradient(ellipse at 50% 100%, #fff 0%, #e0ffff 100%); filter:blur(.5px); animation:flk .4s ease-in-out infinite alternate; }
    .fl-g { position:absolute; bottom:-5px; width:34px; height:22px; background:radial-gradient(ellipse,rgba(255,165,0,.6) 0%, transparent 70%); animation:glw .7s ease-in-out infinite alternate; }
    @keyframes flk {
      0%  { transform:scaleX(1) scaleY(1) rotate(-2deg); }
      100%{ transform:scaleX(.85) scaleY(1.1) rotate(2deg); }
    }
    @keyframes glw {
      from{ opacity:.5; transform:scale(1); }
      to  { opacity:1;  transform:scale(1.4); }
    }
    .diya-wick { width:3px; height:9px; background:linear-gradient(to top,#333,#999); border-radius:2px; }
    .diya-cup {
      width: 46px; height: 20px;
      background: linear-gradient(180deg, #c8860a 0%, #8b5e00 50%, #5c3d00 100%);
      border-radius: 50% 50% 50% 50% / 20% 20% 80% 80%;
      box-shadow: 0 4px 14px rgba(255,140,0,.55), 0 0 25px rgba(255,100,0,.3);
      position: relative;
    }
    .diya-cup::after {
      content:''; position:absolute; top:3px; left:9px;
      width:28px; height:9px;
      background:radial-gradient(ellipse,rgba(255,220,100,.5) 0%, transparent 70%);
      border-radius:50%;
    }

    /* ═══════════════════════════════════
       JAI KALI MANTRA
    ═══════════════════════════════════ */
    .jai-kali {
      font-family: 'Cinzel Decorative', serif;
      font-size: clamp(1.2rem, 4vw, 2.6rem);
      text-align: center;
      color: var(--light-pink);
      text-shadow: 0 0 22px #ff0080, 0 0 44px #c0006a, 0 0 80px #ff0080;
      letter-spacing: 5px;
      margin: 6px 0 14px;
      animation: kaliMantra 2.5s ease-in-out infinite alternate;
    }
    @keyframes kaliMantra {
      from{ text-shadow:0 0 22px #ff0080, 0 0 44px #c0006a, 0 0 80px #ff0080; letter-spacing:4px; }
      to  { text-shadow:0 0 40px #ff0080, 0 0 80px #ff66b2, 0 0 130px #ff0080; letter-spacing:7px; }
    }

    /* ═══════════════════════════════════
       SCROLL TICKER
    ═══════════════════════════════════ */
    .ticker-wrap {
      width: 100%; max-width: 950px;
      border-top: 1px solid rgba(255,0,128,.4);
      border-bottom: 1px solid rgba(255,215,0,.4);
      background: linear-gradient(90deg, transparent, rgba(80,0,40,.7), rgba(30,0,60,.8), rgba(80,0,40,.7), transparent);
      padding: 13px 0; overflow: hidden; margin: 10px 0 24px;
    }
    .ticker {
      display: inline-flex; white-space: nowrap;
      animation: tick 22s linear infinite;
      font-size: 1.08rem;
      color: var(--gold);
      text-shadow: 0 0 10px #ff8c00;
      letter-spacing: 3px;
    }
    .ticker span { margin: 0 50px; }
    @keyframes tick {
      from{ transform:translateX(0); }
      to  { transform:translateX(-50%); }
    }

    /* ═══════════════════════════════════
       MAIN WISH CARD
    ═══════════════════════════════════ */
    .wish-card {
      max-width: 860px; width: 100%;
      background: linear-gradient(135deg, rgba(80,0,40,.78) 0%, rgba(25,0,55,.88) 50%, rgba(80,0,40,.78) 100%);
      border: 1px solid rgba(255,215,0,.35);
      border-radius: 26px;
      padding: 38px 42px;
      position: relative;
      backdrop-filter: blur(14px);
      box-shadow: 0 0 50px rgba(255,0,128,.22), 0 0 100px rgba(255,140,0,.12), inset 0 0 70px rgba(100,0,50,.28);
      margin-bottom: 28px;
      animation: cardAura 4.5s ease-in-out infinite alternate;
    }
    @keyframes cardAura {
      from{ box-shadow:0 0 50px rgba(255,0,128,.22),0 0 100px rgba(255,140,0,.12); border-color:rgba(255,215,0,.35); }
      to  { box-shadow:0 0 90px rgba(255,0,128,.55),0 0 170px rgba(255,140,0,.3);  border-color:rgba(255,215,0,.95); }
    }
    /* Corner gems */
    .gem { position:absolute; font-size:1.6rem; animation:gemSpin 7s linear infinite; }
    .gem-tl{ top:12px; left:14px; color:#ffd700; text-shadow:0 0 12px #ff8c00; }
    .gem-tr{ top:12px; right:14px; color:#ff99cc; text-shadow:0 0 12px #ff0080; animation-direction:reverse; animation-duration:5s; }
    .gem-bl{ bottom:12px; left:14px; color:#ff99cc; text-shadow:0 0 12px #ff0080; animation-duration:9s; }
    .gem-br{ bottom:12px; right:14px; color:#ffd700; text-shadow:0 0 12px #ff8c00; animation-direction:reverse; animation-duration:6s; }
    @keyframes gemSpin{ from{transform:rotate(0)} to{transform:rotate(360deg)} }

    .wish-text {
      font-family: 'Crimson Text', Georgia, serif;
      font-size: clamp(1.05rem, 2.3vw, 1.32rem);
      color: var(--cream);
      line-height: 2.1;
      text-align: center;
      text-shadow: 0 0 8px rgba(255,200,100,.35);
    }
    .w-gold { color:#ffd700; font-weight:600; font-style:italic; text-shadow:0 0 14px #ff8c00, 0 0 28px #ffd700; }
    .w-pink { color:#ff99cc; font-weight:600; text-shadow:0 0 14px #ff0080, 0 0 28px #ff66b2; }
    .w-name { color:#fffacd; font-weight:700; font-style:italic; font-size:1.1em; text-shadow:0 0 16px #ffd700, 0 0 35px #ff8c00; }

    /* ═══════════════════════════════════
       FAMILY BLESSINGS
    ═══════════════════════════════════ */
    .bless-section {
      max-width: 860px; width: 100%; text-align: center; margin-bottom: 24px;
    }
    .bless-title {
      font-family: 'Cinzel Decorative', serif;
      font-size: clamp(.9rem, 2.8vw, 1.7rem);
      color: var(--gold);
      text-shadow: 0 0 14px #ff8c00, 0 0 30px #ffd700;
      margin-bottom: 15px; letter-spacing: 2px;
    }
    .pills {
      display: flex; flex-wrap: wrap; justify-content: center; gap: 11px;
    }
    .pill {
      padding: 10px 22px; border-radius: 50px;
      font-family: 'Crimson Text', serif; font-size: 1rem; font-weight: 600;
      animation: pillBob 3s ease-in-out infinite;
    }
    .pill:nth-child(1){background:linear-gradient(135deg,#8b0000,#c0006a);color:#ffd700;border:1px solid #ffd700;box-shadow:0 0 16px rgba(192,0,106,.6);animation-delay:0s}
    .pill:nth-child(2){background:linear-gradient(135deg,#4a0070,#8b0000);color:#ffb3de;border:1px solid #ff66b2;box-shadow:0 0 16px rgba(139,0,0,.6);animation-delay:.3s}
    .pill:nth-child(3){background:linear-gradient(135deg,#c0006a,#4a0070);color:#ffe4b5;border:1px solid #ff8c00;box-shadow:0 0 16px rgba(74,0,112,.6);animation-delay:.6s}
    .pill:nth-child(4){background:linear-gradient(135deg,#5c2000,#8b0000);color:#ffd700;border:1px solid #ffd700;box-shadow:0 0 16px rgba(139,0,0,.6);animation-delay:.9s}
    .pill:nth-child(5){background:linear-gradient(135deg,#8b0000,#4a0070);color:#ff99cc;border:1px solid #ff66b2;box-shadow:0 0 16px rgba(192,0,106,.6);animation-delay:1.2s}
    .pill:nth-child(6){background:linear-gradient(135deg,#4a0070,#c0006a);color:#ffe4b5;border:1px solid #ff8c00;box-shadow:0 0 16px rgba(74,0,112,.6);animation-delay:1.5s}
    @keyframes pillBob {
      0%,100%{transform:translateY(0) scale(1)}
      50%    {transform:translateY(-7px) scale(1.05)}
    }

    /* ═══════════════════════════════════
       AGENTIC AI SECTION
    ═══════════════════════════════════ */
    .ai-section {
      max-width: 860px; width: 100%;
      background: linear-gradient(135deg,rgba(0,10,40,.85) 0%,rgba(10,0,50,.92) 50%,rgba(0,10,40,.85) 100%);
      border: 1px solid rgba(100,180,255,.35);
      border-radius: 24px;
      padding: 32px 36px;
      margin-bottom: 28px;
      backdrop-filter: blur(16px);
      box-shadow: 0 0 50px rgba(50,100,255,.2), 0 0 100px rgba(100,0,255,.12);
      animation: aiGlow 4s ease-in-out infinite alternate;
      position: relative; overflow: hidden;
    }
    @keyframes aiGlow {
      from{ box-shadow:0 0 40px rgba(50,100,255,.2),0 0 80px rgba(100,0,255,.12); border-color:rgba(100,180,255,.3); }
      to  { box-shadow:0 0 80px rgba(50,150,255,.5),0 0 160px rgba(150,50,255,.3); border-color:rgba(150,220,255,.8); }
    }
    /* AI circuit lines bg */
    .ai-circuit {
      position: absolute; inset: 0; z-index: 0; opacity: .07;
      background-image:
        repeating-linear-gradient(0deg,  rgba(100,180,255,.8) 0, rgba(100,180,255,.8) 1px, transparent 1px, transparent 50px),
        repeating-linear-gradient(90deg, rgba(100,180,255,.8) 0, rgba(100,180,255,.8) 1px, transparent 1px, transparent 50px);
      pointer-events: none;
    }

    .ai-header {
      display: flex; align-items: center; gap: 14px;
      margin-bottom: 18px; position: relative; z-index: 1;
    }
    .ai-icon {
      width: 52px; height: 52px; border-radius: 50%;
      background: linear-gradient(135deg, #0033ff, #9900ff, #00ccff);
      display: flex; align-items: center; justify-content: center;
      font-size: 1.6rem;
      box-shadow: 0 0 20px rgba(50,100,255,.7), 0 0 40px rgba(100,0,255,.4);
      animation: aiIconPulse 2s ease-in-out infinite alternate;
      flex-shrink: 0;
    }
    @keyframes aiIconPulse {
      from{ box-shadow:0 0 20px rgba(50,100,255,.7); transform:scale(1); }
      to  { box-shadow:0 0 40px rgba(100,200,255,1), 0 0 80px rgba(150,50,255,.6); transform:scale(1.08); }
    }
    .ai-header-text h3 {
      font-family: 'Orbitron', monospace;
      font-size: clamp(.9rem, 2.5vw, 1.3rem);
      color: #64b4ff;
      text-shadow: 0 0 12px #0066ff, 0 0 25px #0033ff;
      letter-spacing: 2px;
    }
    .ai-header-text p {
      font-family: 'Crimson Text', serif;
      font-size: .95rem; color: rgba(150,200,255,.75);
      margin-top: 2px;
    }

    /* Name input row */
    .ai-input-row {
      display: flex; gap: 10px; flex-wrap: wrap;
      margin-bottom: 16px; position: relative; z-index: 1;
    }
    .ai-name-input {
      flex: 1; min-width: 180px;
      padding: 12px 18px;
      background: rgba(0,20,60,.7);
      border: 1px solid rgba(100,180,255,.4);
      border-radius: 50px;
      color: #c8e8ff;
      font-family: 'Crimson Text', serif;
      font-size: 1.05rem;
      outline: none;
      transition: border .3s, box-shadow .3s;
    }
    .ai-name-input::placeholder { color: rgba(100,180,255,.45); }
    .ai-name-input:focus {
      border-color: rgba(100,200,255,.9);
      box-shadow: 0 0 20px rgba(50,150,255,.5);
    }
    .ai-btn {
      padding: 12px 28px;
      background: linear-gradient(135deg, #0033ff, #9900ff);
      border: none; border-radius: 50px;
      color: #fff;
      font-family: 'Orbitron', monospace;
      font-size: .88rem; font-weight: 700;
      letter-spacing: 1px;
      cursor: pointer;
      box-shadow: 0 0 20px rgba(50,0,255,.5);
      transition: transform .2s, box-shadow .2s;
      white-space: nowrap;
    }
    .ai-btn:hover {
      transform: scale(1.06);
      box-shadow: 0 0 35px rgba(100,100,255,.8);
    }
    .ai-btn:active{ transform:scale(.97); }

    /* Blessing output */
    .ai-output {
      position: relative; z-index: 1;
      background: rgba(0,15,45,.7);
      border: 1px solid rgba(100,180,255,.25);
      border-radius: 16px;
      padding: 18px 22px;
      min-height: 90px;
      display: flex; flex-direction: column; gap: 10px;
    }
    .ai-typing-indicator {
      display: none; gap: 6px; align-items: center;
    }
    .ai-typing-indicator.show { display:flex; }
    .dot {
      width: 8px; height: 8px; border-radius: 50%;
      background: #64b4ff;
      animation: typingDot .9s ease-in-out infinite;
    }
    .dot:nth-child(2){ animation-delay:.2s; }
    .dot:nth-child(3){ animation-delay:.4s; }
    @keyframes typingDot {
      0%,80%,100%{ transform:scale(1); opacity:.4; }
      40%        { transform:scale(1.3); opacity:1; }
    }
    .ai-blessing-text {
      font-family: 'Crimson Text', serif;
      font-size: clamp(1rem, 2.2vw, 1.2rem);
      color: #c8e8ff;
      line-height: 1.9;
      text-align: center;
      text-shadow: 0 0 8px rgba(100,180,255,.3);
    }
    .ai-blessing-text .ai-gold { color:#ffd700; font-weight:600; text-shadow:0 0 10px #ff8c00; }
    .ai-blessing-text .ai-pink { color:#ff99cc; font-weight:600; text-shadow:0 0 10px #ff0080; }
    .ai-blessing-text .ai-cyan { color:#00e5ff; font-weight:600; text-shadow:0 0 10px #0099cc; }
    .ai-label {
      font-family: 'Orbitron', monospace;
      font-size: .78rem;
      color: rgba(100,180,255,.6);
      letter-spacing: 2px;
      text-transform: uppercase;
      display: flex; align-items: center; gap: 8px;
    }
    .ai-label::before{ content:''; width:30px; height:1px; background:rgba(100,180,255,.4); }
    .ai-label::after { content:''; flex:1; height:1px; background:rgba(100,180,255,.4); }

    .ai-stats {
      display: flex; gap: 20px; flex-wrap: wrap; justify-content: center;
      margin-top: 14px; position: relative; z-index: 1;
    }
    .ai-stat {
      display: flex; flex-direction: column; align-items: center;
      background: rgba(0,20,60,.6);
      border: 1px solid rgba(100,180,255,.2);
      border-radius: 12px;
      padding: 10px 18px; min-width: 100px;
    }
    .ai-stat .num {
      font-family: 'Orbitron', monospace;
      font-size: 1.3rem; color: #64b4ff;
      text-shadow: 0 0 10px #0066ff;
      animation: countUp 2s ease both;
    }
    .ai-stat .lbl {
      font-size: .82rem; color: rgba(150,200,255,.65); margin-top:2px;
    }
    @keyframes countUp {
      from{ opacity:0; transform:translateY(10px); }
      to  { opacity:1; transform:translateY(0); }
    }

    /* ═══════════════════════════════════
       FOOTER
    ═══════════════════════════════════ */
    .footer {
      text-align: center; max-width: 860px; width: 100%;
    }
    .footer-mantra {
      font-family: 'Cinzel Decorative', serif;
      font-size: clamp(.8rem, 2.2vw, 1.15rem);
      color: rgba(255,215,0,.7);
      letter-spacing: 2px;
      text-shadow: 0 0 10px #ff8c00;
      margin-bottom: 8px;
    }
    .footer-sub {
      font-size: .9rem; color: rgba(255,180,100,.45);
      letter-spacing: 1px; margin-top: 6px;
    }

    /* ═══════════════════════════════════
       RESPONSIVE
    ═══════════════════════════════════ */
    @media(max-width:600px){
      .wish-card{padding:22px 18px;}
      .ai-section{padding:22px 16px;}
    }
  </style>
</head>
<body>

<!-- STARFIELD -->
<canvas id="starCanvas"></canvas>

<!-- KALI MAA BACKGROUND SVG -->
<div class="kali-bg-wrap">
  <div class="kali-svg-container">
    <svg viewBox="0 0 520 680" width="min(88vw,620px)" height="auto" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <radialGradient id="skin" cx="50%" cy="45%" r="55%">
          <stop offset="0%" stop-color="#1e0038"/>
          <stop offset="55%" stop-color="#0d001a"/>
          <stop offset="100%" stop-color="#020005"/>
        </radialGradient>
        <radialGradient id="eyeR" cx="40%" cy="35%" r="55%">
          <stop offset="0%" stop-color="#ff2200"/>
          <stop offset="55%" stop-color="#8b0000"/>
          <stop offset="100%" stop-color="#000"/>
        </radialGradient>
        <radialGradient id="halo" cx="50%" cy="50%" r="50%">
          <stop offset="0%" stop-color="#ff0080" stop-opacity=".5"/>
          <stop offset="50%" stop-color="#8b0000" stop-opacity=".3"/>
          <stop offset="100%" stop-color="transparent" stop-opacity="0"/>
        </radialGradient>
        <radialGradient id="crown" cx="50%" cy="100%" r="80%">
          <stop offset="0%" stop-color="#ffe066"/>
          <stop offset="50%" stop-color="#ff8c00"/>
          <stop offset="100%" stop-color="#7a4e00"/>
        </radialGradient>
        <radialGradient id="tongue" cx="50%" cy="10%" r="70%">
          <stop offset="0%" stop-color="#ff5555"/>
          <stop offset="100%" stop-color="#8b0000"/>
        </radialGradient>
        <filter id="glow"><feGaussianBlur stdDeviation="4" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
        <filter id="sglow"><feGaussianBlur stdDeviation="9" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
        <filter id="xglow"><feGaussianBlur stdDeviation="15" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
      </defs>

      <!-- Outer aura rings -->
      <ellipse cx="260" cy="250" rx="230" ry="230" fill="url(#halo)" filter="url(#xglow)"/>
      <circle cx="260" cy="250" r="220" fill="none" stroke="#ffd700" stroke-width="1.2" stroke-dasharray="10,7" opacity=".55"/>
      <circle cx="260" cy="250" r="232" fill="none" stroke="#ff0080" stroke-width=".7" opacity=".35"/>
      <circle cx="260" cy="250" r="208" fill="none" stroke="#ff8c00" stroke-width=".6" stroke-dasharray="4,8" opacity=".4"/>

      <!-- Mukut / Crown – elaborate -->
      <!-- Center spire -->
      <polygon points="260,0 240,65 220,28 215,88 185,55 198,110 165,88 185,138 260,122" fill="url(#crown)" filter="url(#glow)"/>
      <polygon points="260,0 280,65 300,28 305,88 335,55 322,110 355,88 335,138 260,122" fill="url(#crown)" filter="url(#glow)"/>
      <!-- Crown arch -->
      <path d="M 165 138 Q 260 90 355 138" fill="none" stroke="#ffd700" stroke-width="2.5" filter="url(#glow)"/>
      <!-- Crown gems -->
      <circle cx="260" cy="18"  r="12" fill="#ff0080"  filter="url(#sglow)"/>
      <circle cx="210" cy="42"  r="8"  fill="#ffd700"  filter="url(#glow)"/>
      <circle cx="310" cy="42"  r="8"  fill="#ffd700"  filter="url(#glow)"/>
      <circle cx="175" cy="78"  r="7"  fill="#ff66b2"  filter="url(#glow)"/>
      <circle cx="345" cy="78"  r="7"  fill="#ff66b2"  filter="url(#glow)"/>
      <circle cx="192" cy="118" r="5"  fill="#fffacd"  filter="url(#glow)"/>
      <circle cx="328" cy="118" r="5"  fill="#fffacd"  filter="url(#glow)"/>

      <!-- Flowing hair -->
      <path d="M 115 190 Q 55 310 65 500 Q 88 540 115 515 Q 98 395 142 265 Z"  fill="#08000f" opacity=".95"/>
      <path d="M 405 190 Q 465 310 455 500 Q 432 540 405 515 Q 422 395 378 265 Z" fill="#08000f" opacity=".95"/>
      <path d="M 110 170 Q 42 240 48 370 Q 70 415 95 380 Q 80 290 125 215 Z"  fill="#0d0018" opacity=".85"/>
      <path d="M 410 170 Q 478 240 472 370 Q 450 415 425 380 Q 440 290 395 215 Z" fill="#0d0018" opacity=".85"/>
      <!-- Hair strands -->
      <path d="M 95 240 Q 60 320 68 420" fill="none" stroke="#120020" stroke-width="8" stroke-linecap="round"/>
      <path d="M 425 240 Q 460 320 452 420" fill="none" stroke="#120020" stroke-width="8" stroke-linecap="round"/>

      <!-- FACE -->
      <ellipse cx="260" cy="275" rx="155" ry="178" fill="url(#skin)"/>
      <!-- subtle face highlight -->
      <ellipse cx="240" cy="245" rx="65" ry="75" fill="#1f0040" opacity=".25"/>

      <!-- Third Eye (Trinetra) -->
      <ellipse cx="260" cy="208" rx="26" ry="16" fill="#ff0000" filter="url(#sglow)" opacity=".92"/>
      <ellipse cx="260" cy="208" rx="17" ry="10" fill="#ff5533"/>
      <circle  cx="260" cy="208" r="6.5" fill="#fff" opacity=".85"/>
      <circle  cx="260" cy="208" r="3"   fill="#8b0000"/>
      <!-- Third eye lashes -->
      <path d="M 234 207 Q 224 196 232 183 Q 237 193 234 207 Z" fill="#ff8c00" opacity=".7"/>
      <path d="M 286 207 Q 296 196 288 183 Q 283 193 286 207 Z" fill="#ff8c00" opacity=".7"/>

      <!-- Left Eye -->
      <ellipse cx="200" cy="258" rx="30" ry="19" fill="#fff" opacity=".92"/>
      <ellipse cx="200" cy="258" rx="22" ry="15" fill="url(#eyeR)"/>
      <circle  cx="200" cy="258" r="8"  fill="#6b0000"/>
      <circle  cx="200" cy="258" r="4"  fill="#000"/>
      <circle  cx="205" cy="253" r="3.5" fill="#fff" opacity=".85"/>
      <!-- Left lashes -->
      <line x1="170" y1="252" x2="180" y2="244" stroke="#000" stroke-width="2.8" stroke-linecap="round"/>
      <line x1="175" y1="244" x2="184" y2="237" stroke="#000" stroke-width="2.8" stroke-linecap="round"/>
      <line x1="181" y1="239" x2="190" y2="233" stroke="#000" stroke-width="2.8" stroke-linecap="round"/>
      <line x1="189" y1="235" x2="197" y2="231" stroke="#000" stroke-width="2.8" stroke-linecap="round"/>
      <!-- Left lower lash -->
      <line x1="174" y1="264" x2="183" y2="270" stroke="#000" stroke-width="1.5" stroke-linecap="round"/>
      <line x1="183" y1="268" x2="192" y2="273" stroke="#000" stroke-width="1.5" stroke-linecap="round"/>

      <!-- Right Eye -->
      <ellipse cx="320" cy="258" rx="30" ry="19" fill="#fff" opacity=".92"/>
      <ellipse cx="320" cy="258" rx="22" ry="15" fill="url(#eyeR)"/>
      <circle  cx="320" cy="258" r="8"  fill="#6b0000"/>
      <circle  cx="320" cy="258" r="4"  fill="#000"/>
      <circle  cx="325" cy="253" r="3.5" fill="#fff" opacity=".85"/>
      <!-- Right lashes -->
      <line x1="350" y1="252" x2="340" y2="244" stroke="#000" stroke-width="2.8" stroke-linecap="round"/>
      <line x1="345" y1="244" x2="336" y2="237" stroke="#000" stroke-width="2.8" stroke-linecap="round"/>
      <line x1="339" y1="239" x2="330" y2="233" stroke="#000" stroke-width="2.8" stroke-linecap="round"/>
      <line x1="331" y1="235" x2="323" y2="231" stroke="#000" stroke-width="2.8" stroke-linecap="round"/>
      <line x1="346" y1="264" x2="337" y2="270" stroke="#000" stroke-width="1.5" stroke-linecap="round"/>
      <line x1="337" y1="268" x2="328" y2="273" stroke="#000" stroke-width="1.5" stroke-linecap="round"/>

      <!-- Nose -->
      <ellipse cx="260" cy="300" rx="11" ry="8" fill="#150028" opacity=".8"/>
      <circle  cx="248" cy="307" r="6" fill="#1a0030"/>
      <circle  cx="272" cy="307" r="6" fill="#1a0030"/>

      <!-- Lips -->
      <path d="M 222 334 Q 260 350 298 334 Q 285 328 260 331 Q 235 328 222 334 Z" fill="#6b0000"/>
      <path d="M 222 334 Q 260 358 298 334 Q 285 344 260 347 Q 235 344 222 334 Z" fill="#aa0000"/>
      <!-- Tongue (long, as Maa Kali) -->
      <path d="M 238 352 Q 260 420 282 352 Q 272 368 260 371 Q 248 368 238 352 Z" fill="#cc0000" filter="url(#glow)"/>
      <path d="M 241 358 Q 260 414 279 358 Q 270 374 260 377 Q 250 374 241 358 Z" fill="url(#tongue)"/>

      <!-- Tilak / Bindi -->
      <ellipse cx="260" cy="228" rx="7" ry="9" fill="#ff0080" filter="url(#glow)" opacity=".95"/>
      <!-- White dot centre -->
      <circle cx="260" cy="225" r="3" fill="#fff" opacity=".6"/>

      <!-- Earrings L -->
      <circle cx="104" cy="284" r="14" fill="none" stroke="#ffd700" stroke-width="2.8" filter="url(#glow)"/>
      <circle cx="104" cy="284" r="7"  fill="#ff0080" filter="url(#glow)"/>
      <line   x1="104" y1="298" x2="104" y2="332" stroke="#ffd700" stroke-width="2.5" filter="url(#glow)"/>
      <circle cx="104" cy="339" r="9"  fill="#ffd700" filter="url(#glow)"/>
      <circle cx="104" cy="339" r="4"  fill="#ff0080"/>
      <!-- Earrings R -->
      <circle cx="416" cy="284" r="14" fill="none" stroke="#ffd700" stroke-width="2.8" filter="url(#glow)"/>
      <circle cx="416" cy="284" r="7"  fill="#ff0080" filter="url(#glow)"/>
      <line   x1="416" y1="298" x2="416" y2="332" stroke="#ffd700" stroke-width="2.5" filter="url(#glow)"/>
      <circle cx="416" cy="339" r="9"  fill="#ffd700" filter="url(#glow)"/>
      <circle cx="416" cy="339" r="4"  fill="#ff0080"/>

      <!-- Neck -->
      <rect x="234" y="435" width="52" height="48" rx="8" fill="#0d001a"/>
      <!-- Necklace -->
      <path d="M 200 450 Q 260 480 320 450" fill="none" stroke="#ffd700" stroke-width="2.2" filter="url(#glow)"/>
      <circle cx="210" cy="454" r="6" fill="#ffe4b5" opacity=".7" filter="url(#glow)"/>
      <circle cx="235" cy="466" r="7" fill="#ffe4b5" opacity=".7" filter="url(#glow)"/>
      <circle cx="260" cy="472" r="8" fill="#ff0080" opacity=".8" filter="url(#glow)"/>
      <circle cx="285" cy="466" r="7" fill="#ffe4b5" opacity=".7" filter="url(#glow)"/>
      <circle cx="310" cy="454" r="6" fill="#ffe4b5" opacity=".7" filter="url(#glow)"/>

      <!-- Scatter sparkle dots -->
      <circle cx="148" cy="182" r="3" fill="#ffd700" opacity=".7" filter="url(#glow)"/>
      <circle cx="372" cy="182" r="3" fill="#ffd700" opacity=".7" filter="url(#glow)"/>
      <circle cx="128" cy="210" r="2" fill="#ff66b2" opacity=".6" filter="url(#glow)"/>
      <circle cx="392" cy="210" r="2" fill="#ff66b2" opacity=".6" filter="url(#glow)"/>
      <circle cx="135" cy="300" r="2" fill="#ffd700" opacity=".5"/>
      <circle cx="385" cy="300" r="2" fill="#ffd700" opacity=".5"/>
    </svg>
  </div>
</div>

<!-- Cosmic aura overlay -->
<div class="aura"></div>

<!-- Fireworks canvas -->
<canvas id="fwCanvas"></canvas>

<!-- ═══════════════════════════════
     PAGE CONTENT
════════════════════════════════ -->
<div class="page">

  <!-- TOP ORNAMENT -->
  <div class="ornament">🪔 ✦ 🧨 ✦ 🌸 ✦ 🧨 ✦ 🪔</div>

  <!-- FROM BADGE -->
  <div class="from-badge">
    <div class="avatar">🙏</div>
    <div class="from-text">
      With Love &amp; Devotion from<br/>
      <span>Tanmoy Dey &amp; Family</span>
    </div>
  </div>

  <!-- MAIN TITLES -->
  <h1 class="title-diwali">🪔 Shubh Deepawali 2026 🪔</h1>
  <h2 class="title-kali">🌸 Happy Maa Kali Puja 2026 🌸</h2>

  <div class="divider"></div>

  <!-- TOP DIYA ROW -->
  <div class="diya-row" id="diyaRow">
    <!-- 7 diyas -->
    <div class="diya"><div class="flame-stack"><div class="fl fl-o"></div><div class="fl fl-m"></div><div class="fl fl-i"></div><div class="fl-g"></div><div class="diya-wick"></div></div><div class="diya-cup"></div></div>
    <div class="diya"><div class="flame-stack"><div class="fl fl-o"></div><div class="fl fl-m"></div><div class="fl fl-i"></div><div class="fl-g"></div><div class="diya-wick"></div></div><div class="diya-cup"></div></div>
    <div class="diya"><div class="flame-stack"><div class="fl fl-o"></div><div class="fl fl-m"></div><div class="fl fl-i"></div><div class="fl-g"></div><div class="diya-wick"></div></div><div class="diya-cup"></div></div>
    <div class="diya"><div class="flame-stack"><div class="fl fl-o"></div><div class="fl fl-m"></div><div class="fl fl-i"></div><div class="fl-g"></div><div class="diya-wick"></div></div><div class="diya-cup"></div></div>
    <div class="diya"><div class="flame-stack"><div class="fl fl-o"></div><div class="fl fl-m"></div><div class="fl fl-i"></div><div class="fl-g"></div><div class="diya-wick"></div></div><div class="diya-cup"></div></div>
    <div class="diya"><div class="flame-stack"><div class="fl fl-o"></div><div class="fl fl-m"></div><div class="fl fl-i"></div><div class="fl-g"></div><div class="diya-wick"></div></div><div class="diya-cup"></div></div>
    <div class="diya"><div class="flame-stack"><div class="fl fl-o"></div><div class="fl fl-m"></div><div class="fl fl-i"></div><div class="fl-g"></div><div class="diya-wick"></div></div><div class="diya-cup"></div></div>
  </div>

  <!-- JAI KALI -->
  <div class="jai-kali">🙏 ॐ क्रीं काली — ॐ जय माँ काली 🙏</div>

  <!-- TICKER -->
  <div class="ticker-wrap">
    <div class="ticker">
      <span>🪔 Shubh Deepawali 2026 — Tanmoy Dey &amp; Family</span>
      <span>🌸 Jai Maa Kali — Happy Kali Puja 2026</span>
      <span>🧨 May Light Conquer Darkness</span>
      <span>✨ Blessings to All Families</span>
      <span>🙏 ॐ क्रीं काली नमः</span>
      <span>🪔 Shubh Deepawali 2026 — Tanmoy Dey &amp; Family</span>
      <span>🌸 Jai Maa Kali — Happy Kali Puja 2026</span>
      <span>🧨 May Light Conquer Darkness</span>
      <span>✨ Blessings to All Families</span>
      <span>🙏 ॐ क्रीं काली नमः</span>
    </div>
  </div>

  <!-- MAIN WISH CARD -->
  <div class="wish-card">
    <span class="gem gem-tl">✦</span>
    <span class="gem gem-tr">❋</span>
    <span class="gem gem-bl">❋</span>
    <span class="gem gem-br">✦</span>

    <p class="wish-text">
      🙏 <span class="w-name">Tanmoy Dey</span> and his entire family bow their heads with the deepest love and devotion
      to <span class="w-pink">Maa Kali</span> — the fierce, divine mother who is the destroyer of evil and the protector of all.<br/><br/>

      On this most auspicious occasion of <span class="w-gold">Diwali 2026</span> and the sacred <span class="w-pink">Maa Kali Puja 2026</span>,
      we wish from the bottom of our hearts a <span class="w-gold">very very Happy Deepawali</span>
      and a <span class="w-pink">gloriously Blessed Maa Kali Puja</span> to <span class="w-gold">each and every one of you</span> —
      including your beloved parents, your life partners, your precious children, your siblings,
      your friends, and each cherished member of your family. 🏠<br/><br/>

      May the gentle flame of every <span class="w-gold">diya 🪔</span> scatter away every shadow of worry and sorrow.
      May every joyful <span class="w-gold">cracker 🧨</span> announce prosperity and laughter in your home.
      May <span class="w-pink">Maa Kali's</span> powerful blessings guard your family from every obstacle,
      and shower your lives with <span class="w-gold">health, wealth, peace, and endless happiness</span>. 🌟<br/><br/>

      <span class="w-pink">— With folded hands, heartfelt prayers, and eternal love —</span><br/>
      <span class="w-gold">🌸 Tanmoy Dey &amp; The Entire Dey Family 🌸</span>
    </p>
  </div>

  <!-- FAMILY BLESSINGS -->
  <div class="bless-section">
    <div class="bless-title">🌟 Tanmoy Dey's Family Wishes to All 🌟</div>
    <div class="pills">
      <div class="pill">👴 Parents &amp; Grandparents</div>
      <div class="pill">💑 Couples &amp; Partners</div>
      <div class="pill">👧 Children &amp; Youth</div>
      <div class="pill">🤝 Friends &amp; Relatives</div>
      <div class="pill">🏠 Neighbours &amp; Society</div>
      <div class="pill">🌏 All of Humanity</div>
    </div>
  </div>

  <!-- ══════════════════════════════════════
       AGENTIC AI DIVINE BLESSING GENERATOR
  ══════════════════════════════════════ -->
  <div class="ai-section">
    <div class="ai-circuit"></div>

    <div class="ai-header">
      <div class="ai-icon">🤖</div>
      <div class="ai-header-text">
        <h3>✦ AGENTIC AI BLESSING ENGINE ✦</h3>
        <p>Powered by Divine Intelligence · Personalised for You</p>
      </div>
    </div>

    <div class="ai-label">Enter Your Name to Receive a Personalised Divine Blessing</div>

    <div class="ai-input-row" style="margin-top:14px;">
      <input class="ai-name-input" id="aiNameInput" type="text" placeholder="✨ Your name or family name…" maxlength="40"/>
      <button class="ai-btn" onclick="generateBlessing()">🌸 Bless Me</button>
    </div>

    <div class="ai-output" id="aiOutput">
      <div class="ai-typing-indicator" id="aiTyping">
        <div class="dot"></div><div class="dot"></div><div class="dot"></div>
        <span style="color:rgba(100,180,255,.6);font-size:.9rem;margin-left:4px;">AI is channelling divine energy…</span>
      </div>
      <div class="ai-blessing-text" id="aiBlessingText">
        🙏 Enter your name above and press <span class="ai-gold">Bless Me</span> to receive a
        <span class="ai-cyan">personalised divine blessing</span> from the
        <span class="ai-pink">Agentic AI</span> powered by the energy of <span class="ai-gold">Maa Kali</span>
        and the light of <span class="ai-gold">Deepawali</span>. 🪔
      </div>
    </div>

    <div class="ai-stats">
      <div class="ai-stat"><div class="num" id="blessCount">0</div><div class="lbl">Blessings Generated</div></div>
      <div class="ai-stat"><div class="num">∞</div><div class="lbl">Divine Energy</div></div>
      <div class="ai-stat"><div class="num" id="liveCount">0</div><div class="lbl">Families Blessed</div></div>
    </div>
  </div>

  <!-- BOTTOM DIYA ROW -->
  <div class="diya-row" style="margin-bottom:14px;">
    <div class="diya"><div class="flame-stack"><div class="fl fl-o"></div><div class="fl fl-m"></div><div class="fl fl-i"></div><div class="fl-g"></div><div class="diya-wick"></div></div><div class="diya-cup"></div></div>
    <div class="diya"><div class="flame-stack"><div class="fl fl-o"></div><div class="fl fl-m"></div><div class="fl fl-i"></div><div class="fl-g"></div><div class="diya-wick"></div></div><div class="diya-cup"></div></div>
    <div class="diya"><div class="flame-stack"><div class="fl fl-o"></div><div class="fl fl-m"></div><div class="fl fl-i"></div><div class="fl-g"></div><div class="diya-wick"></div></div><div class="diya-cup"></div></div>
    <div class="diya"><div class="flame-stack"><div class="fl fl-o"></div><div class="fl fl-m"></div><div class="fl fl-i"></div><div class="fl-g"></div><div class="diya-wick"></div></div><div class="diya-cup"></div></div>
    <div class="diya"><div class="flame-stack"><div class="fl fl-o"></div><div class="fl fl-m"></div><div class="fl fl-i"></div><div class="fl-g"></div><div class="diya-wick"></div></div><div class="diya-cup"></div></div>
  </div>

  <div class="divider"></div>

  <!-- FOOTER -->
  <div class="footer">
    <div class="footer-mantra">✦ ॐ नमः शक्तये — Salutations to the Divine Mother ✦</div>
    <div class="footer-mantra" style="font-size:.88em;margin-top:4px;color:rgba(255,150,200,.6);">
      🌸 May Maa Kali's Grace, Maa Lakshmi's Wealth &amp; Lord Ganesha's Wisdom Bless All 🌸
    </div>
    <div class="footer-sub">
      🪔 Created with Love by Tanmoy Dey &amp; Family · Diwali &amp; Maa Kali Puja 2026 🪔
    </div>
  </div>

</div><!-- /page -->

<!-- ═══════════════════════════════════════════
     JAVASCRIPT: Fireworks, Stars, AI Blessing
════════════════════════════════════════════ -->
<script>
/* ──────── STARFIELD ──────── */
(function(){
  const c = document.getElementById('starCanvas');
  const cx = c.getContext('2d');
  function resize(){ c.width=innerWidth; c.height=innerHeight; }
  resize(); addEventListener('resize', resize);
  const stars = Array.from({length:220}, ()=>({
    x: Math.random()*innerWidth,
    y: Math.random()*innerHeight,
    r: Math.random()*1.6+.3,
    alpha: Math.random(),
    speed: Math.random()*.008+.003,
    color: ['rgba(255,255,255,', 'rgba(255,215,0,', 'rgba(255,180,220,'][Math.floor(Math.random()*3)]
  }));
  function drawStars(){
    cx.clearRect(0,0,c.width,c.height);
    stars.forEach(s=>{
      s.alpha += s.speed;
      if(s.alpha>1||s.alpha<0) s.speed*=-1;
      cx.beginPath();
      cx.arc(s.x,s.y,s.r,0,Math.PI*2);
      cx.fillStyle = s.color+Math.abs(s.alpha)+')';
      cx.fill();
    });
    requestAnimationFrame(drawStars);
  }
  drawStars();
})();

/* ──────── FIREWORKS ──────── */
(function(){
  const cv = document.getElementById('fwCanvas');
  const cx = cv.getContext('2d');
  function resize(){ cv.width=innerWidth; cv.height=innerHeight; }
  resize(); addEventListener('resize', resize);

  const palettes=[
    ['rgba(255,215,0,1)','rgba(255,140,0,1)','rgba(255,255,120,1)'],
    ['rgba(255,0,128,1)','rgba(255,100,200,1)','rgba(255,180,230,1)'],
    ['rgba(255,80,0,1)', 'rgba(255,180,0,1)', 'rgba(255,230,100,1)'],
    ['rgba(170,0,255,1)','rgba(255,0,200,1)', 'rgba(255,80,255,1)'],
    ['rgba(0,220,255,1)','rgba(0,120,255,1)', 'rgba(180,255,255,1)'],
    ['rgba(255,255,255,1)','rgba(255,215,0,1)','rgba(255,180,0,1)'],
    ['rgba(0,255,160,1)','rgba(50,255,220,1)','rgba(200,255,240,1)'],
  ];

  class Particle{
    constructor(x,y,col){
      this.x=x; this.y=y;
      const a=Math.random()*Math.PI*2, s=Math.random()*5.5+1.5;
      this.vx=Math.cos(a)*s; this.vy=Math.sin(a)*s;
      this.alpha=1; this.decay=Math.random()*.014+.01;
      this.r=Math.random()*3+1; this.col=col; this.g=.09;
      this.trail=[];
    }
    update(){
      this.trail.push({x:this.x,y:this.y,a:this.alpha});
      if(this.trail.length>7) this.trail.shift();
      this.vx*=.98; this.vy*=.98; this.vy+=this.g;
      this.x+=this.vx; this.y+=this.vy; this.alpha-=this.decay;
    }
    draw(){
      this.trail.forEach(t=>{
        cx.beginPath();
        cx.arc(t.x,t.y,this.r*.5,0,Math.PI*2);
        cx.fillStyle=this.col.replace('1)',`${t.a*.25})`);
        cx.fill();
      });
      cx.beginPath();
      cx.arc(this.x,this.y,this.r,0,Math.PI*2);
      cx.fillStyle=this.col.replace('1)',`${this.alpha})`);
      cx.shadowColor=this.col.replace('1)','.8)');
      cx.shadowBlur=9;
      cx.fill();
      cx.shadowBlur=0;
    }
  }

  class Rocket{
    constructor(sx,ty){
      this.x=sx??Math.random()*cv.width;
      this.y=cv.height+10;
      this.targetY=ty??(Math.random()*cv.height*.55+60);
      this.speed=Math.random()*5+6;
      this.exploded=false;
      this.pal=palettes[Math.floor(Math.random()*palettes.length)];
      this.trail=[];
    }
    update(){
      this.trail.push({x:this.x,y:this.y});
      if(this.trail.length>8) this.trail.shift();
      this.y-=this.speed;
      if(this.y<=this.targetY) this.explode();
    }
    draw(){
      this.trail.forEach((t,i)=>{
        const a=(i/this.trail.length)*.6;
        cx.beginPath(); cx.arc(t.x,t.y,2,0,Math.PI*2);
        cx.fillStyle=`rgba(255,220,100,${a})`;
        cx.fill();
      });
      cx.beginPath(); cx.arc(this.x,this.y,2.8,0,Math.PI*2);
      cx.fillStyle='#fff'; cx.shadowColor='#ffd700'; cx.shadowBlur=12;
      cx.fill(); cx.shadowBlur=0;
    }
    explode(){
      this.exploded=true;
      const n=Math.floor(Math.random()*90+90);
      for(let i=0;i<n;i++) particles.push(new Particle(this.x,this.y,this.pal[Math.floor(Math.random()*3)]));
      for(let i=0;i<22;i++){
        const p=new Particle(this.x,this.y,this.pal[0]);
        p.vx*=.28; p.vy*=.28; p.r=4.5; p.decay=.007;
        particles.push(p);
      }
      // cracker ring burst
      for(let i=0;i<16;i++){
        const angle=(i/16)*Math.PI*2;
        const p=new Particle(this.x,this.y,this.pal[1]);
        p.vx=Math.cos(angle)*4; p.vy=Math.sin(angle)*4;
        p.r=2.5; p.decay=.012;
        particles.push(p);
      }
    }
  }

  const particles=[], rockets=[];
  function launchRocket(sx,ty){ rockets.push(new Rocket(sx,ty)); }
  launchRocket();
  setInterval(launchRocket, 950);

  document.getElementById('fwCanvas').addEventListener('click',e=>{
    for(let i=0;i<4;i++) launchRocket(e.clientX+(Math.random()-.5)*70, e.clientY+(Math.random()-.5)*50);
  });

  function loop(){
    requestAnimationFrame(loop);
    cx.fillStyle='rgba(5,0,13,.2)';
    cx.fillRect(0,0,cv.width,cv.height);
    rockets.forEach((r,i)=>{ if(!r.exploded){r.update();r.draw();}else{rockets.splice(i,1);} });
    for(let i=particles.length-1;i>=0;i--){
      particles[i].update(); particles[i].draw();
      if(particles[i].alpha<=0) particles.splice(i,1);
    }
  }
  loop();
})();

/* ──────── FLOATING PETALS ──────── */
(function(){
  const symbols=['🌸','🪔','✨','🌺','❀','🌼','⭐'];
  for(let i=0;i<22;i++){
    const p=document.createElement('div');
    p.className='petal';
    p.textContent=symbols[Math.floor(Math.random()*symbols.length)];
    p.style.left=Math.random()*100+'vw';
    p.style.animationDuration=(Math.random()*12+8)+'s';
    p.style.animationDelay=(Math.random()*12)+'s';
    p.style.fontSize=(Math.random()*.8+.9)+'rem';
    document.body.appendChild(p);
  }
})();

/* ──────── AGENTIC AI BLESSING ENGINE ──────── */
let blessCount=0, familyCount=0;

const blessings=[
  (n)=>`🌸 Dear <span class="ai-gold">${n}</span> and your beloved family,<br/>
    May <span class="ai-pink">Maa Kali</span> herself stand as your shield against every hardship.
    This <span class="ai-gold">Diwali 2026</span>, the AI agents of the digital cosmos join in prayer —
    may your home overflow with <span class="ai-cyan">health, laughter, prosperity, and love</span>.
    May every diya you light guide your family to greater heights. <span class="ai-gold">Jai Maa Kali! 🙏🪔</span>`,

  (n)=>`✨ <span class="ai-pink">Maa Kali's</span> third eye sees your devotion, dear <span class="ai-gold">${n}</span>!<br/>
    The <span class="ai-cyan">Agentic AI</span> has processed a trillion prayers and distilled them into one for you:
    May this <span class="ai-gold">Kali Puja 2026</span> usher unbreakable strength into your soul,
    unconditional happiness into your family, and divine protection over every member you hold dear. 🧨🌟`,

  (n)=>`🪔 Greetings, <span class="ai-gold">${n}</span>! The AI oracles have spoken —<br/>
    Your name resonates with <span class="ai-pink">divine frequency</span> this sacred Diwali.
    May the <span class="ai-gold">light of a thousand diyas</span> illuminate your path forever.
    May <span class="ai-pink">Maa Kali</span> bless your parents with long life, your children with wisdom,
    and your home with eternal peace. <span class="ai-cyan">Happy Deepawali 2026! 🌸</span>`,

  (n)=>`🤖 AI Blessing Activated for <span class="ai-gold">${n}</span> &amp; Family!<br/>
    <span class="ai-cyan">Model output:</span> May the cosmic energy of <span class="ai-pink">Maa Kali</span>
    dissolve all negativity and fears from your life.
    May <span class="ai-gold">Diwali 2026</span> be your most prosperous, most joyful, most memorable festival yet.
    Every cracker that bursts tonight carries a wish from <span class="ai-gold">Tanmoy Dey &amp; Family</span> — just for you! 🧨🙏`,

  (n)=>`🌟 Divine transmission received for <span class="ai-gold">${n}</span>!<br/>
    <span class="ai-pink">Maa Kali</span> whispers through the digital ether:
    <em>"Fear nothing, dear child. I am always with you."</em>
    May this <span class="ai-gold">Kali Puja 2026</span> fill your heart with her fierce love.
    May your family grow stronger together, your bonds grow deeper,
    and <span class="ai-cyan">happiness find its permanent home</span> at your doorstep. 🪔❤️`,

  (n)=>`🧨 Cracker of Blessings for <span class="ai-gold">${n}</span>!<br/>
    The <span class="ai-cyan">Agentic AI</span> has lit a virtual diya in your honour.
    May every obstacle in your life burn away in <span class="ai-pink">Maa Kali's</span> sacred fire.
    May your 2026 be spectacular — filled with new beginnings, great achievements,
    and a family that grows in <span class="ai-gold">love, health, and abundance</span>. Jai Maa! 🌸🙏`,
];

function sleep(ms){ return new Promise(r=>setTimeout(r,ms)); }

async function generateBlessing(){
  const name=(document.getElementById('aiNameInput').value.trim()||'Dear Friend');
  const typing=document.getElementById('aiTyping');
  const out=document.getElementById('aiBlessingText');

  // Show typing
  out.style.opacity='0';
  typing.classList.add('show');

  await sleep(1800+Math.random()*800);

  // Pick a blessing
  const fn=blessings[Math.floor(Math.random()*blessings.length)];
  const html=fn(name);

  typing.classList.remove('show');
  out.innerHTML='';
  out.style.opacity='1';

  // Type out character by character (effect on the wrapper)
  out.style.transition='opacity .4s';
  out.innerHTML=html;

  // Animate out element
  out.style.opacity='0';
  setTimeout(()=>{ out.style.opacity='1'; }, 50);

  // Update counters
  blessCount++;
  familyCount=Math.max(familyCount, blessCount+Math.floor(Math.random()*8+2));
  document.getElementById('blessCount').textContent=blessCount;
  document.getElementById('liveCount').textContent=familyCount;

  // Launch extra fireworks
  for(let i=0;i<5;i++){
    setTimeout(()=>{
      const ev=new MouseEvent('click',{clientX:Math.random()*innerWidth, clientY:Math.random()*innerHeight*.6});
      document.getElementById('fwCanvas').dispatchEvent(ev);
    }, i*300);
  }
}

// Allow Enter key
document.getElementById('aiNameInput').addEventListener('keydown',e=>{
  if(e.key==='Enter') generateBlessing();
});

// Tick up live counter slowly over time
setInterval(()=>{
  if(familyCount<99999){
    familyCount+=Math.floor(Math.random()*3+1);
    document.getElementById('liveCount').textContent=familyCount;
  }
}, 2800);
</script>

</body>
</html>

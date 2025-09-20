<!doctype html><html lang="ja"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>WP Loud Cute</title>
<style>
  :root{
    --pink:#ffa7c4; --mint:#a8f0d1; --yuzu:#ffe3a3; --sky:#b9e6ff; --lav:#d8c7ff; --bg:transparent;
  }
  html,body{margin:0;height:100%;background:var(--bg);overflow:hidden}
  .wrap{position:absolute;inset:0;display:flex;align-items:center;justify-content:center;pointer-events:none}
  .msg{position:absolute;bottom:12%;left:50%;transform:translateX(-50%);
       color:#fff;font:800 clamp(22px,4vw,46px)/1.15 ui-rounded, "Segoe UI", system-ui;
       -webkit-text-stroke:2px rgba(0,0,0,.25); text-shadow:0 6px 16px rgba(0,0,0,.35);
       padding:.25em .75em; border-radius:20px; background:rgba(0,0,0,.18)}
  .confetti{position:absolute;inset:0}
  .shape{position:absolute; width:18px; height:18px; opacity:.95; filter:drop-shadow(0 6px 10px rgba(0,0,0,.25))}
  .heart{background:conic-gradient(from 0deg at 50% 58%, var(--pink) 0 25%, var(--mint) 0 50%, var(--yuzu) 0 75%, var(--lav) 0 100%);
         clip-path: path("M9 3 C9 1.8 8 .8 6.8 .8 C5.6 .8 4.8 1.7 4.5 2.6 C4.2 1.7 3.3 .8 2.1 .8 C.9 .8 0 1.8 0 3 C0 5.8 4.5 8 4.5 8 S9 5.8 9 3 Z");}
  .star{background: radial-gradient(circle at 30% 30%, #fff 0 35%, transparent 40%), linear-gradient(135deg, var(--sky), var(--lav)); clip-path: polygon(50% 0,61% 35%,98% 35%,68% 57%,79% 91%,50% 72%,21% 91%,32% 57%,2% 35%,39% 35%);}
  @keyframes fall{to{transform:translateY(120vh) rotate(360deg)}}
  @keyframes fadeout{to{opacity:0;transform:scale(.98)}}
</style></head><body>
<div class="wrap">
  <div class="confetti" id="confetti"></div>
  <div class="msg" id="msg">初見さんいらっしゃい🩷</div>
  <audio id="se" preload="auto" src="./cute_fanfare.mp3"></audio> <!-- ファンファーレ（効果音ラボ等に差し替え） -->
</div>
<script>
  const qp=new URLSearchParams(location.search);
  const DURATION=+qp.get("duration")||3600;
  const TEXT=qp.get("text")||"初見さんいらっしゃい🩷";
  msg.textContent=TEXT;

  // 紙吹雪（ハート＆スター）
  const colors=["#ffa7c4","#a8f0d1","#ffe3a3","#b9e6ff","#d8c7ff","#ffffff"];
  for(let i=0;i<120;i++){
    const el=document.createElement("div");
    el.className="shape "+(Math.random()<.6?"heart":"star");
    el.style.left=(Math.random()*100)+"vw";
    el.style.top=(-10 - Math.random()*30)+"vh";
    el.style.transform=`rotate(${Math.random()*360}deg)`;
    el.style.background = el.classList.contains("heart") ? "" : `linear-gradient(135deg, ${colors[i%colors.length]}, ${colors[(i+2)%colors.length]})`;
    el.style.animation=`fall ${4+Math.random()*5}s linear ${Math.random()*-2}s forwards`;
    document.getElementById("confetti").appendChild(el);
  }

  const se=document.getElementById("se"); se.volume=.9;
  se.play().catch(()=>{se.muted=true; se.play().then(()=>se.muted=false).catch(()=>{})});

  setTimeout(()=>{document.body.style.animation="fadeout .35s ease forwards"}, Math.max(800, DURATION-350));
</script></body></html>

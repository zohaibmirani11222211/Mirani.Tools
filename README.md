<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Group Buy SEO & AI Tools</title>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@400;600;800&display=swap" rel="stylesheet">
<style>
:root{--bg:#0d1130;--bg2:#161b45;--ink:#f3f1ff;--mute:#a8acd6;--a:#ffb454;--b:#4fd1c5;--c:#ff6b9a;--line:#2a3070}
*{box-sizing:border-box;margin:0}
html{scroll-behavior:smooth}
body{font-family:'Bricolage Grotesque',system-ui,sans-serif;background:var(--bg);color:var(--ink);overflow-x:hidden;line-height:1.5}
.orb{position:fixed;border-radius:50%;filter:blur(90px);opacity:.35;z-index:0;animation:float 14s ease-in-out infinite}
.o1{width:420px;height:420px;background:var(--c);top:-120px;left:-100px}
.o2{width:380px;height:380px;background:var(--b);bottom:-100px;right:-80px;animation-delay:-6s}
.o3{width:300px;height:300px;background:var(--a);top:40%;left:55%;animation-delay:-3s;opacity:.18}
@keyframes float{50%{transform:translate(40px,-50px) scale(1.15)}}
main{position:relative;z-index:1;max-width:1180px;margin:0 auto;padding:0 20px 80px}
.hero{text-align:center;padding:90px 0 40px}
.badge{display:inline-flex;gap:8px;align-items:center;border:1px solid var(--line);background:#ffffff0d;padding:6px 16px;border-radius:99px;font-size:14px;color:var(--mute);animation:drop .8s both}
.dot{width:9px;height:9px;border-radius:50%;background:#3dff9a;box-shadow:0 0 0 0 #3dff9a99;animation:pulse 1.6s infinite}
@keyframes pulse{70%{box-shadow:0 0 0 9px #3dff9a00}100%{box-shadow:0 0 0 0 #3dff9a00}}
@keyframes drop{from{opacity:0;transform:translateY(-20px)}}
h1{font-size:clamp(34px,6.5vw,76px);font-weight:800;line-height:1.05;margin:22px 0 14px;letter-spacing:-1.5px;animation:rise 1s .15s both}
@keyframes rise{from{opacity:0;transform:translateY(30px)}}
.buy{display:block;margin-top:10px;min-height:1.15em;background:linear-gradient(90deg,var(--a),var(--c),var(--b));background-size:200% auto;-webkit-background-clip:text;background-clip:text;color:transparent;animation:shine 4s linear infinite}
@keyframes shine{to{background-position:200% center}}
.caret{display:inline-block;width:4px;height:.85em;background:var(--ink);margin-left:6px;vertical-align:-.05em;animation:blink .8s steps(1) infinite}
@keyframes blink{50%{opacity:0}}
.sub{color:var(--mute);max-width:640px;margin:0 auto;font-size:18px;animation:rise 1s .35s both}
.stats{display:flex;justify-content:center;gap:34px;flex-wrap:wrap;margin:34px 0 10px;animation:rise 1s .5s both}
.stats b{display:block;font-size:34px;color:var(--a)}
.stats span{color:var(--mute);font-size:14px}
.ticker{overflow:hidden;border-block:1px solid var(--line);margin:30px -20px;padding:14px 0;background:#ffffff08}
.track{display:flex;gap:44px;width:max-content;animation:scroll 50s linear infinite}
.ticker:hover .track{animation-play-state:paused}
@keyframes scroll{to{transform:translateX(-50%)}}
.track span{white-space:nowrap;color:var(--mute);display:flex;gap:10px;align-items:center}
.track b{color:var(--ink)}
.controls{display:flex;flex-wrap:wrap;gap:14px;justify-content:space-between;align-items:center;margin:40px 0 26px}
.tabs{display:flex;background:var(--bg2);border:1px solid var(--line);border-radius:99px;padding:5px;position:relative}
.tab{border:0;background:none;color:var(--mute);font:inherit;font-weight:600;padding:10px 24px;border-radius:99px;cursor:pointer;position:relative;z-index:1;transition:color .3s}
.tab.on{color:#14122e}
.pill{position:absolute;top:5px;bottom:5px;border-radius:99px;background:linear-gradient(90deg,var(--a),var(--c));transition:all .4s cubic-bezier(.7,0,.2,1)}
input{background:var(--bg2);border:1px solid var(--line);color:var(--ink);font:inherit;padding:12px 20px;border-radius:99px;min-width:240px;outline:none;transition:border .3s,box-shadow .3s}
input:focus{border-color:var(--b);box-shadow:0 0 0 4px #4fd1c533}
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:20px;perspective:1000px}
.card{background:linear-gradient(160deg,var(--bg2),#11153a);border:1px solid var(--line);border-radius:20px;padding:22px;cursor:pointer;position:relative;overflow:hidden;opacity:0;animation:pop .6s forwards;transition:transform .25s,border-color .3s;transform-style:preserve-3d}
@keyframes pop{from{opacity:0;transform:translateY(40px) scale(.92)}to{opacity:1}}
.card::before{content:"";position:absolute;inset:0;background:radial-gradient(260px circle at var(--x,50%) var(--y,0%),#ffb45426,transparent 60%);opacity:0;transition:opacity .3s}
.card:hover{border-color:var(--a)}
.card:hover::before{opacity:1}
.top{display:flex;justify-content:space-between;align-items:center;margin-bottom:16px}
.ico{width:46px;height:46px;border-radius:14px;display:grid;place-items:center;font-weight:800;font-size:20px;color:#14122e}
.live{font-size:12px;color:#3dff9a;display:flex;gap:6px;align-items:center}
.card h3{font-size:20px;margin-bottom:4px}
.cat{font-size:13px;color:var(--b);margin-bottom:10px}
.card p{color:var(--mute);font-size:14.5px}
.tags{display:flex;flex-wrap:wrap;gap:6px;margin-top:14px}
.tags i{font-style:normal;font-size:12px;border:1px solid var(--line);padding:3px 10px;border-radius:99px;color:var(--mute)}
.dot.off{background:#ff5d6c;animation:none;box-shadow:none}
.live.off{color:#ff5d6c}
.card.isoff{filter:grayscale(.8);opacity:.6!important}
.card.isoff:hover{filter:grayscale(.4)}
.status{display:flex;gap:8px;flex-wrap:wrap}
.chip{border:1px solid var(--line);background:var(--bg2);color:var(--mute);font:inherit;font-size:14px;padding:8px 16px;border-radius:99px;cursor:pointer;transition:all .25s}
.chip.on{color:#14122e;background:var(--b);border-color:var(--b);font-weight:600}
.cta.dis{background:#3a3f78;color:var(--mute);cursor:not-allowed}
.cta.dis:hover{transform:none}
.empty{grid-column:1/-1;text-align:center;color:var(--mute);padding:50px}
.modal{position:fixed;inset:0;background:#05061ccc;backdrop-filter:blur(6px);display:grid;place-items:center;z-index:10;opacity:0;pointer-events:none;transition:opacity .3s;padding:20px}
.modal.open{opacity:1;pointer-events:auto}
.box{background:var(--bg2);border:1px solid var(--line);border-radius:26px;max-width:540px;width:100%;padding:32px;transform:translateY(40px) scale(.9);transition:transform .4s cubic-bezier(.2,1.3,.4,1);position:relative}
.modal.open .box{transform:none}
.box h2{font-size:30px;margin:14px 0 4px}
.box ul{list-style:none;padding:0;margin:18px 0}
.box li{padding:9px 0 9px 28px;border-bottom:1px solid var(--line);position:relative;color:var(--mute)}
.box li::before{content:"✓";position:absolute;left:0;color:#3dff9a;font-weight:800}
.x{position:absolute;top:16px;right:18px;background:none;border:0;color:var(--mute);font-size:28px;cursor:pointer}
.cta{display:inline-block;margin-top:8px;background:linear-gradient(90deg,var(--a),var(--c));color:#14122e;font-weight:800;border:0;padding:13px 28px;border-radius:99px;font:inherit;font-weight:800;cursor:pointer;transition:transform .2s}
.cta:hover{transform:scale(1.06)}
.why{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:18px;margin-top:80px}
.why div{border:1px solid var(--line);border-radius:18px;padding:22px;background:#ffffff08}
.why h4{font-size:18px;margin-bottom:6px;color:var(--a)}
.why p{color:var(--mute);font-size:14.5px}
footer{text-align:center;color:var(--mute);margin-top:60px;font-size:14px}
:focus-visible{outline:3px solid var(--b);outline-offset:3px}
@media(prefers-reduced-motion:reduce){*{animation-duration:.01s!important;animation-iteration-count:1!important;transition:none!important}.card{opacity:1}}
</style>
</head>
<body>
<div class="orb o1"></div><div class="orb o2"></div><div class="orb o3"></div>
<main>
<section class="hero">
  <div class="badge"><span class="dot"></span> <span id="liveCount"></span> tools are on right now</div>
  <h1>Group Buy SEO & AI Tools<span class="buy"><span id="typed"></span><span class="caret"></span></span></h1>
  <p class="sub">Premium SEO and AI tools in one place. Browse every tool, read what it does, and see what you get with each one.</p>
  <div class="stats">
    <div><b data-n="60">0</b><span>Total tools</span></div>
    <div><b id="onN">0</b><span>Tools on</span></div>
    <div><b id="offN">0</b><span>Tools off</span></div>
    <div><b data-n="30">0</b><span>SEO tools</span></div>
    <div><b data-n="30">0</b><span>AI tools</span></div>
  </div>
</section>

<div class="ticker"><div class="track" id="track"></div></div>

<div class="controls">
  <div class="tabs" id="tabs">
    <span class="pill" id="pill"></span>
    <button class="tab on" data-t="seo">SEO Tools</button>
    <button class="tab" data-t="ai">AI Tools</button>
  </div>
  <div class="status" id="status"><button class="chip on" data-s="all">All</button><button class="chip" data-s="on">On</button><button class="chip" data-s="off">Off</button></div>
  <input id="q" type="search" placeholder="Search a tool name..." aria-label="Search tools">
</div>

<div class="grid" id="grid"></div>

<section class="why">
  <div><h4>Live access</h4><p>Every tool listed here is running and ready to use.</p></div>
  <div><h4>Shared group access</h4><p>Tools are shared in a group, so you use premium features without a separate account for each one.</p></div>
  <div><h4>SEO and AI together</h4><p>Research keywords, audit your site, write content and make images from one list.</p></div>
  <div><h4>Support</h4><p>Message us if a tool stops working. We check and fix access.</p></div>
</section>
<footer>© Group Buy Tools. All tool names belong to their respective owners.</footer>
</main>

<div class="modal" id="modal"><div class="box" id="box"></div></div>

<script>
const SEO=[
["Semrush","All-in-one SEO suite","Keyword research, competitor analysis, site audit and rank tracking in one dashboard.","Keywords|Audit|Backlinks"],
["Ahrefs","Backlink and keyword research","See who links to any site, find keyword gaps and track your rankings.","Backlinks|Keywords|Rank tracker"],
["Moz Pro","SEO suite","Domain Authority metrics, keyword explorer, link research and on-page grader.","DA|Keywords|On-page"],
["Ubersuggest","Keyword ideas","Fast keyword suggestions with volume, difficulty and content ideas.","Keywords|Content ideas"],
["SpyFu","Competitor research","See the keywords and ads your competitors rank and bid on.","Competitors|PPC|Keywords"],
["Majestic","Link intelligence","Large link index with Trust Flow and Citation Flow scores.","Backlinks|Trust Flow"],
["SE Ranking","Rank tracking platform","Daily rank tracking, site audit and marketing plan tools.","Rank tracker|Audit"],
["Mangools","Beginner friendly SEO","KWFinder, SERPChecker, SERPWatcher and LinkMiner in a clean interface.","KWFinder|SERP|Links"],
["Surfer SEO","On-page content optimizer","Score your content against top ranking pages and get clear edits.","Content score|SERP analyzer"],
["Screaming Frog","Website crawler","Crawl any site to find broken links, redirects and missing tags.","Crawler|Broken links"],
["Serpstat","Growth SEO platform","Keyword, backlink and competitor data with a built in audit.","Keywords|Audit|Competitors"],
["Similarweb","Traffic analytics","Estimate a site's traffic, sources and audience.","Traffic|Audience"],
["Link Whisper","Internal linking","Suggests internal links while you write, saving hours of manual work.","Internal links|WordPress"],
["Keywords Everywhere","Browser keyword data","Shows search volume and related keywords right inside Google.","Browser add-on|Volume"],
["Rank Math Pro","WordPress SEO plugin","Schema, redirections, and advanced on-page SEO inside WordPress.","Schema|Redirects|WordPress"],
["Yoast SEO Premium","WordPress SEO plugin","Readability and SEO checks with redirect manager and related keyphrases.","Readability|Redirects"],
["Frase","Content briefs","Build SEO briefs and optimize articles from SERP research.","Briefs|Optimization"],
["Clearscope","Content grading","Grades your content and lists the terms top pages use.","Content grade|Terms"],
["MarketMuse","Content strategy","Plans topics and finds content gaps with topic modeling.","Topics|Gaps"],
["Sitebulb","Technical audits","Visual crawler with clear hints and prioritized fixes.","Crawler|Hints"],
["CognitiveSEO","Link and content analysis","Backlink analysis, rank tracking and content optimizer.","Backlinks|Content"],
["AccuRanker","Fast rank tracker","On demand rank refresh with accurate local and mobile results.","Rank tracker|Local"],
["Wincher","Simple rank tracking","Track keywords daily and watch your progress over time.","Rank tracker|Reports"],
["Linkody","Backlink monitoring","Monitor new and lost links and get alerts by email.","Backlinks|Alerts"],
["SEOptimer","Website audit","Instant site audit with a clear report you can share.","Audit|Reports"],
["Seobility","Site checker","Crawl, audit and track your site's SEO health.","Crawler|Audit"],
["Dinorank","SEO and link tools","Keyword research, rank tracking and link analysis.","Keywords|Links"],
["Morningscore","Gamified SEO","Simple SEO tasks and scores that keep you moving forward.","Tasks|Score"],
["Nightwatch","Rank tracking","Daily rankings with local and AI search tracking and clean reports.","Rankings|Reports"],
["Raven Tools","Marketing reports","Site audit, rank tracking and white label reports in one place.","Reports|Audit"]];
const AI=[
["ChatGPT Plus","AI assistant","Chat, write, analyze and code with advanced OpenAI models.","Chat|Writing|Code"],
["Claude Pro","AI assistant","Long context writing, analysis and coding with Anthropic's Claude.","Chat|Analysis|Code"],
["Gemini Advanced","AI assistant","Google's AI for writing, research and working across Google apps.","Chat|Research"],
["Perplexity Pro","AI search","Answers with sources, so research is quick and easy to verify.","Search|Sources"],
["Midjourney","AI image generation","Create detailed, artistic images from a text prompt.","Images|Art"],
["Jasper","AI marketing writer","Write ads, blogs and emails in your brand voice.","Copywriting|Brand voice"],
["Copy.ai","AI copywriting","Generate sales copy and run content workflows.","Copywriting|Workflows"],
["Writesonic","AI article writer","Create SEO articles, landing pages and product descriptions.","Articles|SEO"],
["Grammarly Premium","Writing assistant","Fixes grammar, tone and clarity as you write.","Grammar|Tone"],
["QuillBot","Paraphraser","Rewrite, summarize and check grammar in seconds.","Paraphrase|Summarize"],
["Canva Pro","Design platform","Templates, Magic Studio AI tools and background remover.","Design|AI images"],
["Leonardo AI","AI image creation","Generate game art, product images and concept designs.","Images|Models"],
["Runway","AI video","Generate and edit video with text and image prompts.","Video|Editing"],
["ElevenLabs","AI voice","Realistic voiceovers and voice cloning in many languages.","Voice|Text to speech"],
["Synthesia","AI video avatars","Turn a script into a video with a lifelike presenter.","Avatars|Video"],
["HeyGen","AI avatar video","Make talking avatar videos and translate them to other languages.","Avatars|Translation"],
["Descript","Audio and video editor","Edit video by editing the transcript text.","Editing|Transcripts"],
["Notion AI","Workspace AI","Summarize notes, draft docs and answer questions inside Notion.","Notes|Docs"],
["GitHub Copilot","AI coding helper","Suggests code and explains it directly in your editor.","Code|Editor"],
["Cursor","AI code editor","Edit and build projects by chatting with your codebase.","Code|Agent"],
["Poe","Many AI models","Chat with several AI models in a single app.","Multi model|Chat"],
["Pika","AI video","Create short clips from text or an image with effects.","Video|Effects"],
["Suno","AI music","Create full songs with vocals from a short prompt.","Music|Vocals"],
["Murf AI","AI voiceover","Studio quality voices for videos and presentations.","Voice|Studio"],
["Adobe Firefly","AI creative tools","Generate images and edit photos with generative fill.","Images|Fill"],
["Gamma","AI presentations","Create slides, docs and web pages from a prompt.","Slides|Docs"],
["Fireflies.ai","Meeting notes","Records, transcribes and summarizes your meetings.","Meetings|Summaries"],
["Otter.ai","Transcription","Live transcripts and summaries for calls and lectures.","Transcripts|Live"],
["Ideogram","AI images with text","Make images with clean, readable text inside them.","Images|Text"],
["Kling AI","AI video","Generate smooth, realistic video from text or images.","Video|Realistic"]];

/* Ready-made status. Tools listed here show OFF. Remove a name to turn it ON, add a name to turn it OFF. */
const OFF=new Set(["Majestic","Link Whisper","Seobility","Midjourney","Suno","Kling AI"]);
const isOn=n=>!OFF.has(n);
const COLORS=['#ffb454','#4fd1c5','#ff6b9a','#9b8cff','#7ee081'];
const $=s=>document.querySelector(s);
let tab='seo',st='all';
const all=[...SEO.map(t=>({t,k:'SEO'})),...AI.map(t=>({t,k:'AI'}))];

/* headline: types "Buy <tool>" then rewrites with the next tool */
const names=all.map(x=>x.t[0]).filter(isOn);
let ni=Math.floor(Math.random()*names.length);
const typed=$('#typed');
async function loop(){
  const wait=ms=>new Promise(r=>setTimeout(r,ms));
  while(true){
    const s='Buy '+names[ni%names.length];
    for(let i=1;i<=s.length;i++){typed.textContent=s.slice(0,i);await wait(70)}
    await wait(1300);
    for(let i=s.length;i>=4;i--){typed.textContent=s.slice(0,i);await wait(32)}
    ni++;
  }
}
loop();

/* live ticker */
const items=names.map(n=>`<span><i class="dot"></i><b>${n}</b> live</span>`).join('');
$('#track').innerHTML=items+items;

/* counters */
$('#liveCount').textContent=names.length;$('#onN').dataset.n=names.length;$('#offN').dataset.n=all.length-names.length;
document.querySelectorAll('[data-n],#onN,#offN').forEach(el=>{
  const end=+el.dataset.n;let c=0;
  const id=setInterval(()=>{c++;el.textContent=c;if(c>=end)clearInterval(id)},1500/end);
});

function render(){
  const q=$('#q').value.trim().toLowerCase();
  const list=(tab==='seo'?SEO:AI).filter(t=>(st==='all'||(st==='on')===isOn(t[0]))&&(!q||t[0].toLowerCase().includes(q)||t[2].toLowerCase().includes(q)));
  const g=$('#grid');
  g.innerHTML=list.length?list.map((t,i)=>`
   <article class="card ${isOn(t[0])?'':'isoff'}" tabindex="0" data-i="${(tab==='seo'?SEO:AI).indexOf(t)}" style="animation-delay:${i*45}ms">
     <div class="top"><div class="ico" style="background:${COLORS[i%5]}">${t[0][0]}</div><span class="live ${isOn(t[0])?'':'off'}"><i class="dot ${isOn(t[0])?'':'off'}"></i>${isOn(t[0])?'On':'Off'}</span></div>
     <h3>${t[0]}</h3><div class="cat">${t[1]}</div><p>${t[2]}</p>
     <div class="tags">${t[3].split('|').map(x=>`<i>${x}</i>`).join('')}</div>
   </article>`).join(''):'<div class="empty">No tool found. Try another name.</div>';
}
function pill(){
  const b=document.querySelector('.tab.on');const p=$('#pill');
  p.style.left=b.offsetLeft+'px';p.style.width=b.offsetWidth+'px';
}
document.querySelectorAll('.tab').forEach(b=>b.onclick=()=>{
  document.querySelectorAll('.tab').forEach(x=>x.classList.remove('on'));
  b.classList.add('on');tab=b.dataset.t;pill();render();
});
document.querySelectorAll('.chip').forEach(b=>b.onclick=()=>{
  document.querySelectorAll('.chip').forEach(x=>x.classList.remove('on'));
  b.classList.add('on');st=b.dataset.s;render();
});
$('#q').oninput=render;
window.onresize=pill;

/* spotlight + 3D tilt */
$('#grid').addEventListener('mousemove',e=>{
  const c=e.target.closest('.card');if(!c)return;
  const r=c.getBoundingClientRect();const x=e.clientX-r.left,y=e.clientY-r.top;
  c.style.setProperty('--x',x+'px');c.style.setProperty('--y',y+'px');
  c.style.transform=`rotateX(${(y/r.height-.5)*-8}deg) rotateY(${(x/r.width-.5)*8}deg) translateY(-4px)`;
});
$('#grid').addEventListener('mouseout',e=>{const c=e.target.closest('.card');if(c)c.style.transform=''});

/* detail popup */
function open(c){
  const list=tab==='seo'?SEO:AI;const t=list[c.dataset.i];
  const col=COLORS[[...c.parentNode.children].indexOf(c)%5];
  $('#box').innerHTML=`<button class="x" aria-label="Close">×</button>
   <div class="ico" style="background:${col}">${t[0][0]}</div>
   <h2>${t[0]}</h2><div class="cat">${t[1]} · <span class="live ${isOn(t[0])?'':'off'}" style="display:inline-flex"><i class="dot ${isOn(t[0])?'':'off'}"></i>${isOn(t[0])?'On, live now':'Off right now'}</span></div>
   <p style="color:var(--mute)">${t[2]}</p>
   <ul><li>Main features: ${t[3].split('|').join(', ')}</li><li>Shared group access, no separate premium account needed</li><li>Status: ${isOn(t[0])?'On, ready to use':'Off, coming back soon'}</li><li>Support available if access stops working</li></ul>
   <button class="cta ${isOn(t[0])?'':'dis'}">${isOn(t[0])?'Buy '+t[0]:'Currently off'}</button>`;
  $('#modal').classList.add('open');
  $('.x').onclick=$('.cta').onclick=close;
}
function close(){$('#modal').classList.remove('open')}
$('#grid').addEventListener('click',e=>{const c=e.target.closest('.card');if(c)open(c)});
$('#grid').addEventListener('keydown',e=>{if(e.key==='Enter'){const c=e.target.closest('.card');if(c)open(c)}});
$('#modal').onclick=e=>{if(e.target.id==='modal')close()};
document.addEventListener('keydown',e=>{if(e.key==='Escape')close()});

render();
requestAnimationFrame(pill);
document.fonts&&document.fonts.ready.then(pill);
</script>
</body>
</html>

<!DOCTYPE html>

<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="theme-color" content="#4FC3F7">
<title>Lessi Bird 🐦</title>
<link href="https://fonts.googleapis.com/css2?family=Fredoka+One&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent;}
html,body{width:100%;height:100%;overflow:hidden;background:#1565C0;font-family:'Fredoka One',cursive;touch-action:none;user-select:none;-webkit-user-select:none;}
#c{position:fixed;top:0;left:0;width:100%;height:100%;display:block;}

/* ── HUD ── */
#hud{position:fixed;top:max(env(safe-area-inset-top,0px),14px);left:0;right:0;padding:0 14px;display:none;justify-content:space-between;align-items:center;pointer-events:none;z-index:10;}
.hp{background:rgba(255,255,255,0.92);border:3px solid #222;border-radius:14px;padding:6px 16px;color:#222;font-size:clamp(18px,5vw,24px);box-shadow:3px 3px 0 #222;}
.hp span{color:#FF5500;}

/* phase badge */
#phaseBadge{
position:fixed;top:max(env(safe-area-inset-top,0px),14px);left:50%;transform:translateX(-50%);
background:rgba(0,0,0,0.45);backdrop-filter:blur(10px);-webkit-backdrop-filter:blur(10px);
border:2px solid rgba(255,255,255,0.25);border-radius:50px;
padding:5px 16px;color:white;font-size:clamp(12px,3.2vw,15px);
pointer-events:none;z-index:10;display:none;white-space:nowrap;
opacity:0;transition:opacity .5s;
}

/* combo */
#combo{
position:fixed;top:40%;left:50%;transform:translate(-50%,-50%);
font-size:clamp(30px,9vw,46px);color:#FFF700;
-webkit-text-stroke:3px #222;pointer-events:none;z-index:12;opacity:0;
}
#combo.flash{animation:cF .75s ease-out forwards;}
@keyframes cF{0%{opacity:1;transform:translate(-50%,-62%) scale(.4);}50%{opacity:1;transform:translate(-50%,-70%) scale(1.35);}100%{opacity:0;transform:translate(-50%,-86%) scale(1);}}

#tap{position:fixed;inset:0;z-index:5;display:none;}

/* music btn */
#musicBtn{
position:fixed;bottom:max(env(safe-area-inset-bottom,0px),16px);right:14px;
width:46px;height:46px;background:rgba(255,255,255,0.9);
border:3px solid #222;border-radius:50%;display:none;
align-items:center;justify-content:center;font-size:21px;
cursor:pointer;z-index:11;box-shadow:2px 2px 0 #222;
}

/* ── START ── */
#start{
position:fixed;inset:0;z-index:20;display:flex;flex-direction:column;
align-items:center;justify-content:center;overflow:hidden;
padding:20px;
padding-top:max(env(safe-area-inset-top,0px),20px);
padding-bottom:max(env(safe-area-inset-bottom,0px),20px);
}
#sBg{position:absolute;inset:0;}
.sw{position:relative;z-index:2;display:flex;flex-direction:column;align-items:center;width:100%;max-width:380px;}
.sc{background:white;border:4px solid #222;border-radius:22px;padding:14px 28px 10px;text-align:center;box-shadow:5px 5px 0 #222;margin-bottom:10px;width:min(320px,90vw);}
.st1{font-size:clamp(36px,11vw,52px);color:#FF5500;line-height:1;}
.st2{font-size:clamp(17px,5vw,26px);color:#222;line-height:1.15;}
.st3{font-size:clamp(10px,2.8vw,13px);color:#999;margin-top:2px;}
#sb{font-size:clamp(72px,22vw,112px);display:block;line-height:1;animation:sf 1.1s ease-in-out infinite;filter:drop-shadow(4px 5px 0 rgba(0,0,0,0.18));margin:4px 0;}
@keyframes sf{0%,100%{transform:translateY(0) rotate(-6deg) scaleX(-1);}50%{transform:translateY(-18px) rotate(6deg) scaleX(-1);}}
.sh{background:rgba(255,255,255,0.93);border:3px solid #222;border-radius:14px;padding:10px 18px;font-size:clamp(12px,3.3vw,15px);color:#333;line-height:1.9;text-align:center;margin:8px 0 14px;width:min(295px,88vw);box-shadow:3px 3px 0 #222;}
.sh b{color:#FF5500;}
.btnGo{background:#FF5500;border:4px solid #222;border-radius:16px;color:white;font-family:‘Fredoka One’,cursive;font-size:clamp(22px,7vw,30px);padding:clamp(12px,3.5vw,17px) clamp(40px,12vw,64px);cursor:pointer;-webkit-appearance:none;box-shadow:5px 5px 0 #222;transition:transform .08s,box-shadow .08s;}
.btnGo:active{transform:translate(3px,3px);box-shadow:2px 2px 0 #222;}

/* ── GAME OVER ── */
#over{position:fixed;inset:0;display:none;flex-direction:column;align-items:center;justify-content:center;z-index:20;background:rgba(0,0,0,0.6);padding:20px;padding-bottom:max(env(safe-area-inset-bottom,0px),20px);}
.oc{background:white;border:5px solid #222;border-radius:26px;padding:clamp(20px,5.5vw,36px) clamp(20px,7.5vw,46px);text-align:center;width:min(330px,90vw);box-shadow:6px 6px 0 #222;}
.oe{font-size:clamp(46px,14vw,68px);display:block;margin-bottom:4px;}
.ot{font-size:clamp(26px,8vw,40px);color:#FF5500;}
.om{display:flex;justify-content:center;gap:5px;margin:4px 0 10px;font-size:clamp(20px,5.5vw,26px);}
.ol{color:#bbb;font-size:clamp(10px,2.8vw,12px);text-transform:uppercase;letter-spacing:1px;}
.osc{font-size:clamp(60px,18vw,84px);color:#222;line-height:1;}
.ob2{color:#999;font-size:clamp(11px,3.2vw,14px);margin-bottom:16px;}
.ob2 b{color:#FF5500;}
.bov{border:4px solid #222;border-radius:14px;font-family:‘Fredoka One’,cursive;cursor:pointer;-webkit-appearance:none;width:100%;display:block;box-shadow:4px 4px 0 #222;transition:transform .08s,box-shadow .08s;}
.bov:active{transform:translate(2px,2px);box-shadow:2px 2px 0 #222;}
.bR{background:#FF5500;color:white;font-size:clamp(19px,5.5vw,24px);padding:clamp(10px,3vw,14px) 0;margin-bottom:9px;}
.bH{background:#F5F5F5;color:#222;font-size:clamp(14px,4vw,18px);padding:clamp(8px,2.5vw,12px) 0;}

/* score pop */
.spop{position:fixed;font-family:‘Fredoka One’,cursive;font-size:clamp(21px,6vw,29px);color:white;-webkit-text-stroke:2px #222;pointer-events:none;z-index:15;animation:spA .9s ease-out forwards;}
@keyframes spA{0%{opacity:1;transform:translateY(0) scale(.65);}50%{opacity:1;transform:translateY(-44px) scale(1.25);}100%{opacity:0;transform:translateY(-88px) scale(1);}}

/* death flash */
#fl{position:fixed;inset:0;background:white;opacity:0;pointer-events:none;z-index:19;}
#fl.pop{animation:fA .35s ease-out forwards;}
@keyframes fA{0%{opacity:.65;}100%{opacity:0;}}

/* phase transition flash */
#phaseFlash{position:fixed;inset:0;pointer-events:none;z-index:18;opacity:0;}
#phaseFlash.pop{animation:pfA .6s ease-out forwards;}
@keyframes pfA{0%{opacity:.45;}100%{opacity:0;}}

.hidden{display:none!important;}
</style>

</head>
<body>
<canvas id="c"></canvas>
<div id="fl"></div>
<div id="phaseFlash"></div>

<div id="hud">
  <div class="hp">🐦 <span id="sv">0</span></div>
  <div class="hp">⭐ <span id="bv">0</span></div>
</div>
<div id="phaseBadge"></div>
<div id="combo"></div>
<div id="tap"></div>
<div id="musicBtn">🎵</div>

<!-- START -->

<div id="start">
  <canvas id="sBg"></canvas>
  <div class="sw">
    <div class="sc">
      <div class="st1">Lessi Bird</div>
      <div class="st2">🏙️ La ville t'attend !</div>
      <div class="st3">✨ Le jeu de Lessi ✨</div>
    </div>
    <span id="sb">🐦</span>
    <div class="sh">
      <b>Appuie</b> pour battre des ailes !<br>
      Passe entre les immeubles 🏙️<br>
      🌅 Jour → Coucher → 🌙 Nuit → ⛈️ Orage
    </div>
    <button class="btnGo" id="btnS">JOUER ! 🎮</button>
  </div>
</div>

<!-- GAME OVER -->

<div id="over">
  <div class="oc">
    <span class="oe" id="oEm">😵</span>
    <div class="ot" id="oTi">Aïe !</div>
    <div class="om" id="oMed"></div>
    <div class="ol">SCORE</div>
    <div class="osc" id="oSc">0</div>
    <div class="ob2">Record : <b id="oBe">0</b></div>
    <button class="bov bR" id="btnR">REJOUER ! 🔄</button>
    <button class="bov bH" id="btnH">Accueil 🏠</button>
  </div>
</div>

<script>
// ══════════════════════════════════════════
//  CANVAS SETUP
// ══════════════════════════════════════════
const canvas=document.getElementById('c'),ctx=canvas.getContext('2d');
let W,H,DPR;
function resize(){
  DPR=window.devicePixelRatio||1;
  W=window.innerWidth;H=window.innerHeight;
  canvas.width=Math.round(W*DPR);canvas.height=Math.round(H*DPR);
  canvas.style.width=W+'px';canvas.style.height=H+'px';
  ctx.setTransform(DPR,0,0,DPR,0,0);
}
resize();
window.addEventListener('resize',()=>{resize();buildStartBg();if(state!=='playing')initGame();});

// ══════════════════════════════════════════
//  DOM REFS
// ══════════════════════════════════════════
const hudEl=document.getElementById('hud'),startEl=document.getElementById('start'),overEl=document.getElementById('over'),tapEl=document.getElementById('tap');
const svEl=document.getElementById('sv'),bvEl=document.getElementById('bv');
const oScEl=document.getElementById('oSc'),oBeEl=document.getElementById('oBe'),oEmEl=document.getElementById('oEm'),oTiEl=document.getElementById('oTi'),oMedEl=document.getElementById('oMed');
const comboEl=document.getElementById('combo'),flEl=document.getElementById('fl'),pfEl=document.getElementById('phaseFlash');
const musicBtn=document.getElementById('musicBtn'),phaseBadge=document.getElementById('phaseBadge');

// ══════════════════════════════════════════
//  AUDIO ENGINE
// ══════════════════════════════════════════
let audioCtx=null,musicOn=false;
let beatTmr=null,melTmr=null,bassTmr=null;
let beatStep=0,melStep=0,bassStep=0;

const SCALES={
  day:   [523,587,659,784,880,988,1047,784],
  dusk:  [466,523,587,622,698,784,880,698],
  night: [392,440,466,523,587,622,698,587],
  storm: [349,392,415,466,523,523,415,392],
};
const BASS_NOTES=[131,147,165,175,196,175,165,147];
const bassPat=[0,0,2,0,1,1,3,1,0,2,1,0,3,2,0,1];
const melPat= [0,2,4,5,4,2,0,2,4,7,5,4,2,0,5,4];

function initAudio(){if(audioCtx)return;audioCtx=new(window.AudioContext||window.webkitAudioContext)();}

function tone(freq,type,vol,dur,when,dest){
  if(!audioCtx||!musicOn)return;
  const o=audioCtx.createOscillator(),g=audioCtx.createGain();
  o.connect(g);g.connect(dest||audioCtx.destination);
  o.type=type;o.frequency.setValueAtTime(freq,when);
  g.gain.setValueAtTime(0,when);g.gain.linearRampToValueAtTime(vol,when+.01);
  g.gain.exponentialRampToValueAtTime(.001,when+dur);
  o.start(when);o.stop(when+dur+.05);
}
function sfxJump(){
  if(!audioCtx)return;const t=audioCtx.currentTime;
  tone(500,'square',.14,.07,t);tone(680,'square',.09,.05,t+.045);
}
function sfxScore(c){
  if(!audioCtx)return;const t=audioCtx.currentTime;
  const n=[523,659,784,1047][Math.min(c-1,3)];
  tone(n,'square',.17,.1,t);tone(n*1.5,'square',.08,.07,t+.08);
}
function sfxHit(){
  if(!audioCtx)return;const t=audioCtx.currentTime;
  tone(200,'sawtooth',.22,.08,t);tone(140,'sawtooth',.17,.12,t+.06);tone(90,'square',.13,.2,t+.1);
}
function sfxPhase(){
  if(!audioCtx)return;const t=audioCtx.currentTime;
  [523,659,784,1047].forEach((n,i)=>tone(n,'square',.11,.1,t+i*.07));
}

function startMusic(){
  stopMusic();if(!audioCtx||!musicOn)return;
  const bpm=132+phase*4,b=60/bpm; // slightly faster each phase for feel
  const scale=phase<2?SCALES.day:phase<4?SCALES.dusk:phase<6?SCALES.night:SCALES.storm;
  beatTmr=setInterval(()=>{
    if(!musicOn)return;const t=audioCtx.currentTime;
    if(beatStep%4===0){// kick
      const o=audioCtx.createOscillator(),g=audioCtx.createGain();
      o.connect(g);g.connect(audioCtx.destination);
      o.frequency.setValueAtTime(160,t);o.frequency.exponentialRampToValueAtTime(50,t+.15);
      g.gain.setValueAtTime(.28,t);g.gain.exponentialRampToValueAtTime(.001,t+.18);o.start(t);o.stop(t+.22);
    }
    if(beatStep%4===2){// snare
      const buf=audioCtx.createBuffer(1,audioCtx.sampleRate*.1,audioCtx.sampleRate);
      const d=buf.getChannelData(0);for(let i=0;i<d.length;i++)d[i]=Math.random()*2-1;
      const s2=audioCtx.createBufferSource(),f=audioCtx.createBiquadFilter(),g=audioCtx.createGain();
      s2.buffer=buf;f.type='highpass';f.frequency.value=2400;
      s2.connect(f);f.connect(g);g.connect(audioCtx.destination);
      g.gain.setValueAtTime(.11,t);g.gain.exponentialRampToValueAtTime(.001,t+.08);s2.start(t);
    }
    if(beatStep%2===1&&phase>=3){// hi-hat at night
      const buf=audioCtx.createBuffer(1,audioCtx.sampleRate*.04,audioCtx.sampleRate);
      const d=buf.getChannelData(0);for(let i=0;i<d.length;i++)d[i]=Math.random()*2-1;
      const s2=audioCtx.createBufferSource(),f=audioCtx.createBiquadFilter(),g=audioCtx.createGain();
      s2.buffer=buf;f.type='highpass';f.frequency.value=8000;
      s2.connect(f);f.connect(g);g.connect(audioCtx.destination);
      g.gain.setValueAtTime(.04,t);g.gain.exponentialRampToValueAtTime(.001,t+.04);s2.start(t);
    }
    beatStep++;
  },b*500);
  melTmr=setInterval(()=>{if(!musicOn)return;const t=audioCtx.currentTime;tone(scale[melPat[melStep%melPat.length]],'square',.07,b*.92,t);melStep++;},b*1000);
  bassTmr=setInterval(()=>{if(!musicOn)return;const t=audioCtx.currentTime;tone(BASS_NOTES[bassPat[bassStep%bassPat.length]],'triangle',.10,b*1.85,t);bassStep++;},b*2000);
}
function stopMusic(){clearInterval(beatTmr);clearInterval(melTmr);clearInterval(bassTmr);}
musicBtn.addEventListener('click',toggleMusic);
musicBtn.addEventListener('touchend',e=>{e.preventDefault();toggleMusic();});
function toggleMusic(){
  initAudio();musicOn=!musicOn;musicBtn.textContent=musicOn?'🔊':'🔇';
  if(musicOn&&state==='playing')startMusic();else stopMusic();
  if(audioCtx?.state==='suspended')audioCtx.resume();
}

// ══════════════════════════════════════════
//  PHASE SYSTEM — 8 visual phases
//  Gameplay IDENTIQUE (vitesse, gap, gravité fixes)
//  Seul l'environnement change pour brouiller la lisibilité
// ══════════════════════════════════════════
const PHASES=[
  // 0 — Matin clair
  {
    name:'☀️ Matin clair',color:'#FFD700',
    sky:['#4FC3F7','#29B6F6','#81D4FA','#E1F5FE'],
    ground:'#78909C',road:'#455A64',mid:'#607D8B',far:'#90A4AE',
    fogAlpha:0,rainAlpha:0,snowAlpha:0,dustAlpha:0,
    nightOverlay:0,glitchAlpha:0,
    lampOn:false,stars:false,moon:false,sun:true,
    pipes_tint:null, // no tint on buildings
  },
  // 1 — Après-midi venteux (nuages qui bougent vite, légère brume)
  {
    name:'🌤️ Après-midi',color:'#FFA726',
    sky:['#1E88E5','#1976D2','#42A5F5','#90CAF9'],
    ground:'#607D8B',road:'#37474F',mid:'#546E7A',far:'#78909C',
    fogAlpha:0.06,rainAlpha:0,snowAlpha:0,dustAlpha:0,
    nightOverlay:0,glitchAlpha:0,
    lampOn:false,stars:false,moon:false,sun:true,
    pipes_tint:null,
  },
  // 2 — Coucher de soleil (teintes orangées, contraste réduit)
  {
    name:'🌅 Coucher de soleil',color:'#FF7043',
    sky:['#E64A19','#FF5722','#FF8A65','#FFCCBC'],
    ground:'#5D4037',road:'#3E2723',mid:'#795548',far:'#A1887F',
    fogAlpha:0.1,rainAlpha:0,snowAlpha:0,dustAlpha:0.04,
    nightOverlay:0,glitchAlpha:0,
    lampOn:false,stars:false,moon:false,sun:true,sunOrange:true,
    pipes_tint:'rgba(255,120,40,0.25)',
  },
  // 3 — Crépuscule (ciel violet, lumières allumées, début de brume)
  {
    name:'🌆 Crépuscule',color:'#CE93D8',
    sky:['#4A148C','#6A1B9A','#9C27B0','#CE93D8'],
    ground:'#37474F',road:'#212121',mid:'#455A64',far:'#546E7A',
    fogAlpha:0.15,rainAlpha:0,snowAlpha:0,dustAlpha:0,
    nightOverlay:0.18,glitchAlpha:0,
    lampOn:true,stars:true,moon:false,sun:false,
    pipes_tint:'rgba(80,0,120,0.2)',
  },
  // 4 — Nuit (étoiles, lune, brume épaisse, lumières néons)
  {
    name:'🌙 Nuit',color:'#5C6BC0',
    sky:['#0D0525','#1A0A2E','#1E1060','#0D1B4B'],
    ground:'#263238',road:'#1C1C1C',mid:'#2D3436',far:'#37474F',
    fogAlpha:0.22,rainAlpha:0,snowAlpha:0,dustAlpha:0,
    nightOverlay:0.4,glitchAlpha:0,
    lampOn:true,stars:true,moon:true,sun:false,
    pipes_tint:'rgba(0,0,40,0.35)',
  },
  // 5 — Nuit pluvieuse (pluie, réflexions, brume forte)
  {
    name:'🌧️ Nuit pluvieuse',color:'#42A5F5',
    sky:['#050510','#0A0520','#0D0A30','#101040'],
    ground:'#1A1A2E',road:'#0D0D0D',mid:'#1C1C2E',far:'#252540',
    fogAlpha:0.30,rainAlpha:0.7,snowAlpha:0,dustAlpha:0,
    nightOverlay:0.5,glitchAlpha:0,
    lampOn:true,stars:false,moon:false,sun:false,
    pipes_tint:'rgba(0,10,50,0.40)',
  },
  // 6 — Orage (éclairs, forte pluie, ciel rouge sombre)
  {
    name:'⛈️ Orage',color:'#EF5350',
    sky:['#1A0A0A','#2C1010','#3D1515','#5C2020'],
    ground:'#1A1A1A',road:'#0D0D0D',mid:'#222222',far:'#2D2D2D',
    fogAlpha:0.25,rainAlpha:1.0,snowAlpha:0,dustAlpha:0,
    nightOverlay:0.55,glitchAlpha:0,
    lampOn:true,stars:false,moon:false,sun:false,lightning:true,
    pipes_tint:'rgba(60,0,0,0.45)',
  },
  // 7 — Minuit absolu (quasi invisible, légère neige, effet glitch)
  {
    name:'🌑 Minuit',color:'#E040FB',
    sky:['#000000','#020108','#050210','#080318'],
    ground:'#111118',road:'#090909',mid:'#111120','far':'#181828',
    fogAlpha:0.40,rainAlpha:0,snowAlpha:0.6,dustAlpha:0,
    nightOverlay:0.65,glitchAlpha:0.06,
    lampOn:true,stars:true,moon:true,sun:false,
    pipes_tint:'rgba(0,0,20,0.55)',
  },
];

const PIPES_PER_PHASE=10; // every 10 pipes = new phase
let phase=0,phaseT=0; // smooth lerp between phases
let totalPassed=0;

// lerp hex colors
function lerpHex(a,b,t){
  const pr=parseInt(a.slice(1,3),16),pg=parseInt(a.slice(3,5),16),pb2=parseInt(a.slice(5,7),16);
  const nr=parseInt(b.slice(1,3),16),ng=parseInt(b.slice(3,5),16),nb=parseInt(b.slice(5,7),16);
  return`rgb(${Math.round(pr+(nr-pr)*t)},${Math.round(pg+(ng-pg)*t)},${Math.round(pb2+(nb-pb2)*t)})`;
}

function getEnv(){
  const A=PHASES[phase],B=PHASES[Math.min(phase+1,PHASES.length-1)],t=phaseT;
  return{
    name:A.name,color:A.color,
    sky:A.sky.map((c,i)=>lerpHex(c,B.sky[i],t)),
    ground:lerpHex(A.ground,B.ground,t),
    road:lerpHex(A.road,B.road,t),
    mid:lerpHex(A.mid,B.mid,t),
    far:lerpHex(A.far,B.far,t),
    fogAlpha:A.fogAlpha+(B.fogAlpha-A.fogAlpha)*t,
    rainAlpha:A.rainAlpha+(B.rainAlpha-A.rainAlpha)*t,
    snowAlpha:A.snowAlpha+(B.snowAlpha-A.snowAlpha)*t,
    dustAlpha:A.dustAlpha+(B.dustAlpha-A.dustAlpha)*t,
    nightOverlay:A.nightOverlay+(B.nightOverlay-A.nightOverlay)*t,
    glitchAlpha:A.glitchAlpha+(B.glitchAlpha-A.glitchAlpha)*t,
    lampOn:A.lampOn,stars:A.stars,moon:A.moon,sun:A.sun,sunOrange:A.sunOrange,lightning:A.lightning,
    pipes_tint:A.pipes_tint,
  };
}

// ══════════════════════════════════════════
//  GAME CONSTANTS — FIXED (no progression)
// ══════════════════════════════════════════
const FIXED_SPD   = 3.0;  // px/frame, NEVER changes
const FIXED_GAP   = 195;  // gap between buildings, NEVER changes
const FIXED_GR    = 0.30; // gravity multiplier, NEVER changes
const FIXED_JMP   = -8.0; // jump force, NEVER changes
const PIPE_INTERVAL = 95; // frames between pipes, NEVER changes

function K(){
  const s=Math.min(W,460)/400;
  return{
    GR:FIXED_GR*s, JMP:FIXED_JMP*s, SPD:FIXED_SPD*s,
    PW:Math.round(62*s), GAP:Math.max(FIXED_GAP,H*0.28),
    BR:Math.round(15*s), GH:Math.round(Math.min(H*0.115,70)), s
  };
}

// ══════════════════════════════════════════
//  GAME STATE
// ══════════════════════════════════════════
let best=0,score=0,combo=0,state='start',raf;
let bird,pipes,parts,feathers,bgBuilds,midBuilds,clouds,starsArr,frameCount,roadOff=0;
// weather particles
let rainDrops=[],snowFlakes=[];
let lightningT=0,lightningFlash=0;

// ══════════════════════════════════════════
//  BIRD
// ══════════════════════════════════════════
function makeBird(){return{x:W*0.22,y:H/2,vy:0,wingAngle:0,wingDir:1,squish:1,trail:[]};}

function drawBird(){
  const{s}=K();
  // motion trail
  bird.trail.push({x:bird.x,y:bird.y});
  if(bird.trail.length>9)bird.trail.shift();
  bird.trail.forEach((t,i)=>{
    ctx.globalAlpha=(i/bird.trail.length)*0.28;
    ctx.fillStyle='#FFE082';
    ctx.beginPath();ctx.arc(t.x,t.y,(i/bird.trail.length)*9*s,0,Math.PI*2);ctx.fill();
  });
  ctx.globalAlpha=1;
  ctx.save();
  ctx.translate(bird.x,bird.y);
  ctx.rotate(Math.max(-.4,Math.min(.78,bird.vy*.055)));
  bird.squish+=(1-bird.squish)*.22;
  ctx.scale(-bird.squish,1/bird.squish);
  bird.wingAngle+=bird.wingDir*.2;
  if(bird.wingAngle>1)bird.wingDir=-1;
  if(bird.wingAngle<-.3)bird.wingDir=1;
  birdDraw(s,bird.wingAngle);
  ctx.restore();
}

function birdDraw(s,wa){
  const lw=2.6*s;
  const ol=()=>{ctx.strokeStyle='#222';ctx.lineWidth=lw;};
  // tail
  ol();ctx.fillStyle='#E65100';ctx.beginPath();ctx.ellipse(15*s,3*s,11*s,4.5*s,.35,0,Math.PI*2);ctx.fill();ctx.stroke();
  ctx.fillStyle='#FF8C00';ctx.beginPath();ctx.ellipse(14*s,-1*s,10*s,3.5*s,.1,0,Math.PI*2);ctx.fill();ctx.stroke();
  ctx.fillStyle='#FFA726';ctx.beginPath();ctx.ellipse(15*s,7*s,9*s,3*s,.55,0,Math.PI*2);ctx.fill();ctx.stroke();
  // bottom wing
  ctx.save();ctx.rotate(wa*.3);ol();ctx.fillStyle='#E65100';
  ctx.beginPath();ctx.ellipse(2*s,9*s,15*s,5.5*s,.3,0,Math.PI*2);ctx.fill();ctx.stroke();ctx.restore();
  // body
  ctx.fillStyle='#FFB300';ol();ctx.beginPath();ctx.ellipse(0,1*s,18*s,13*s,0,0,Math.PI*2);ctx.fill();ctx.stroke();
  ctx.fillStyle='#FFF3E0';ctx.strokeStyle='#222';ctx.lineWidth=lw*.5;
  ctx.beginPath();ctx.ellipse(3*s,4*s,10*s,8*s,0,0,Math.PI*2);ctx.fill();ctx.stroke();
  // top wing
  ctx.save();ctx.rotate(-wa*.5);ol();ctx.fillStyle='#FFA726';
  ctx.beginPath();ctx.ellipse(-1*s,-8*s,16*s,6*s,-.25,0,Math.PI*2);ctx.fill();ctx.stroke();
  ctx.strokeStyle='#E65100';ctx.lineWidth=1.5*s;ctx.lineCap='round';
  for(let i=0;i<3;i++){ctx.beginPath();ctx.moveTo((-9+i*5)*s,(-10+i)*s);ctx.lineTo((-6+i*5)*s,(-7+i)*s);ctx.stroke();}
  ctx.restore();
  // head
  ctx.fillStyle='#FFB300';ol();ctx.beginPath();ctx.ellipse(-3*s,-12*s,13*s,12*s,0,0,Math.PI*2);ctx.fill();ctx.stroke();
  ctx.fillStyle='#FF8C00';ctx.strokeStyle='#222';ctx.lineWidth=lw*.6;
  ctx.beginPath();ctx.ellipse(-3*s,-21*s,5*s,4.5*s,-.2,0,Math.PI*2);ctx.fill();ctx.stroke();
  ctx.fillStyle='#FFB300';ctx.beginPath();ctx.ellipse(-5*s,-22*s,3.5*s,3*s,.3,0,Math.PI*2);ctx.fill();ctx.stroke();
  // eye
  ctx.fillStyle='white';ol();ctx.beginPath();ctx.ellipse(-8*s,-13*s,6.5*s,7*s,0,0,Math.PI*2);ctx.fill();ctx.stroke();
  ctx.fillStyle='#111';ctx.beginPath();ctx.ellipse(-8*s,-13.5*s,3.8*s,4.5*s,0,0,Math.PI*2);ctx.fill();
  ctx.fillStyle='white';ctx.beginPath();ctx.ellipse(-6.2*s,-11.8*s,1.6*s,1.9*s,0,0,Math.PI*2);ctx.fill();
  // beak
  ctx.fillStyle='#FF6D00';ol();ctx.beginPath();ctx.moveTo(-16*s,-14*s);ctx.lineTo(-26*s,-11*s);ctx.lineTo(-16*s,-8*s);ctx.closePath();ctx.fill();ctx.stroke();
  ctx.strokeStyle='#222';ctx.lineWidth=1.5*s;ctx.beginPath();ctx.moveTo(-16*s,-11*s);ctx.lineTo(-25*s,-11*s);ctx.stroke();
  // blush
  ctx.fillStyle='rgba(255,100,80,.25)';ctx.beginPath();ctx.ellipse(-10*s,-8*s,6*s,3.5*s,0,0,Math.PI*2);ctx.fill();
  // feet
  ctx.strokeStyle='#FF6D00';ctx.lineWidth=lw*.7;ctx.lineCap='round';
  ctx.beginPath();ctx.moveTo(-2*s,12*s);ctx.lineTo(-2*s,18*s);ctx.lineTo(-8*s,22*s);ctx.stroke();
  ctx.beginPath();ctx.moveTo(-2*s,18*s);ctx.lineTo(2*s,22*s);ctx.stroke();
  ctx.beginPath();ctx.moveTo(6*s,12*s);ctx.lineTo(6*s,18*s);ctx.lineTo(0,22*s);ctx.stroke();
  ctx.beginPath();ctx.moveTo(6*s,18*s);ctx.lineTo(10*s,22*s);ctx.stroke();
}

// ══════════════════════════════════════════
//  BUILDINGS
// ══════════════════════════════════════════
const BSTYLES=[
  {wall:'#E53935',trim:'#B71C1C',win:'#FFF9C4',roof:'antenna'},
  {wall:'#1E88E5',trim:'#0D47A1',win:'#E3F2FD',roof:'step'},
  {wall:'#43A047',trim:'#1B5E20',win:'#F1F8E9',roof:'flat'},
  {wall:'#FB8C00',trim:'#E65100',win:'#FFF8E1',roof:'antenna'},
  {wall:'#8E24AA',trim:'#4A148C',win:'#F3E5F5',roof:'step'},
  {wall:'#00ACC1',trim:'#006064',win:'#E0F7FA',roof:'flat'},
  {wall:'#F06292',trim:'#C2185B',win:'#FCE4EC',roof:'antenna'},
  {wall:'#546E7A',trim:'#263238',win:'#ECEFF1',roof:'step'},
];
let bsi=0;

function makePipe(){
  const{GAP,GH}=K();
  const gapY=100+Math.random()*(H-GH-200);
  return{x:W+40,gapY,passed:false,sTop:BSTYLES[bsi++%BSTYLES.length],sBot:BSTYLES[bsi++%BSTYLES.length]};
}

function drawPipe(p,env){
  const{PW,GAP}=K();
  const topH=p.gapY-GAP/2,botY=p.gapY+GAP/2;
  if(topH>4)   drawBuilding(p.x,0,PW,topH,p.sTop,'top',env);
  if(H-botY>4) drawBuilding(p.x,botY,PW,H-botY,p.sBot,'bot',env);
  // gap indicator (very subtle)
  ctx.globalAlpha=.1;ctx.fillStyle='white';
  ctx.beginPath();ctx.arc(p.x+PW/2,p.gapY,PW*.15,0,Math.PI*2);ctx.fill();
  ctx.globalAlpha=1;
}

function darkHex(hex,t){
  const r=parseInt(hex.slice(1,3),16),g=parseInt(hex.slice(3,5),16),b=parseInt(hex.slice(5,7),16);
  return`rgb(${Math.round(r*(1-t))},${Math.round(g*(1-t))},${Math.round(b*(1-t))})`;
}

function drawBuilding(x,y,w,h,st,which,env){
  if(h<3)return;
  const s=K().s,lw=2.8*s,nf=Math.min(env.nightOverlay,0.85);
  const wallC=nf>0?darkHex(st.wall,nf*.6):st.wall;
  const trimC=nf>0?darkHex(st.trim,nf*.5):st.trim;

  ctx.fillStyle=wallC;ctx.strokeStyle='#222';ctx.lineWidth=lw;
  ctx.beginPath();ctx.rect(x,y,w,h);ctx.fill();ctx.stroke();
  // side shade
  ctx.fillStyle='rgba(0,0,0,.12)';ctx.fillRect(x+w-7*s,y,7*s,h);

  // windows
  const wW=Math.round(w*.28),wH=Math.round(w*.24),pad=(w-2*wW)/3;
  let wy=y+pad;
  while(wy+wH < y+h-(which==='top'?16*s:5*s)){
    for(let c=0;c<2;c++){
      const wx=x+pad+c*(wW+pad);
      const lit=env.nightOverlay>.25&&Math.sin(wx*11+wy*7)>-.1;
      ctx.fillStyle='#222';ctx.fillRect(wx-1,wy-1,wW+2,wH+2);
      ctx.fillStyle=lit?'#FFF9C4':(nf>.5?'#0a0a1a':st.win);
      ctx.fillRect(wx,wy,wW,wH);
      if(!lit){ctx.fillStyle='rgba(255,255,255,.35)';ctx.fillRect(wx+1,wy+1,wW*.4,wH*.38);}
      if(lit){
        ctx.fillStyle='rgba(255,240,100,.4)';ctx.fillRect(wx,wy,wW,wH);
        // window glow
        ctx.shadowColor='rgba(255,240,100,.5)';ctx.shadowBlur=8;
        ctx.fillStyle='rgba(255,240,100,.15)';ctx.fillRect(wx-3,wy-3,wW+6,wH+6);
        ctx.shadowBlur=0;
      }
    }
    wy+=wH+pad*.9;
  }

  // trim
  ctx.fillStyle=trimC;ctx.strokeStyle='#222';ctx.lineWidth=lw*.8;
  const tw=7*s;
  if(which==='top'){ctx.fillRect(x,y+h-tw,w,tw);ctx.strokeRect(x,y+h-tw,w,tw);}
  else{ctx.fillRect(x,y,w,tw);ctx.strokeRect(x,y,w,tw);}

  // roof deco (top buildings)
  if(which==='top'&&h>65*s){
    const rx=x+w/2,ry=y;
    if(st.roof==='antenna'){
      ctx.strokeStyle='#455A64';ctx.lineWidth=2.5*s;
      ctx.beginPath();ctx.moveTo(rx,ry);ctx.lineTo(rx,ry-22*s);ctx.stroke();
      const blink=Math.sin(frameCount*.12)>0;
      ctx.fillStyle=blink?'#FF1744':'#880000';ctx.strokeStyle='#222';ctx.lineWidth=2*s;
      ctx.shadowColor=blink?'rgba(255,0,0,.6)':'transparent';ctx.shadowBlur=blink?10:0;
      ctx.beginPath();ctx.arc(rx,ry-24*s,4.5*s,0,Math.PI*2);ctx.fill();ctx.stroke();
      ctx.shadowBlur=0;
      ctx.fillStyle='#9E9E9E';ctx.strokeStyle='#222';ctx.lineWidth=1.5*s;
      ctx.beginPath();ctx.ellipse(rx+9*s,ry-10*s,8*s,5*s,-.4,0,Math.PI*2);ctx.fill();ctx.stroke();
    } else if(st.roof==='step'){
      [w*.8,w*.5,w*.24].forEach((sw2,i)=>{
        ctx.fillStyle=trimC;ctx.strokeStyle='#222';ctx.lineWidth=lw;
        const sh2=9*s,sy=ry-(i+1)*sh2;
        ctx.beginPath();ctx.rect(x+(w-sw2)/2,sy,sw2,sh2);ctx.fill();ctx.stroke();
      });
    } else {
      ctx.fillStyle=trimC;ctx.strokeStyle='#222';ctx.lineWidth=lw;
      ctx.beginPath();ctx.rect(x-5,ry-9*s,w+10,9*s);ctx.fill();ctx.stroke();
    }
  }

  // pipe color tint (phase visual effect on buildings)
  if(env.pipes_tint){
    ctx.fillStyle=env.pipes_tint;
    ctx.fillRect(x,y,w,h);
  }
}

// ══════════════════════════════════════════
//  BACKGROUND
// ══════════════════════════════════════════
function makeBgBuilds(){
  const a=[];let x=0;
  while(x<W+100){const w=25+Math.random()*48,h=H*.12+Math.random()*H*.28;a.push({x,w,h,spd:.28+Math.random()*.08,wo:Math.random()*100});x+=w+Math.random()*4+2;}
  return a;
}
function makeMidBuilds(){
  const a=[];let x=0;
  while(x<W+80){const w=18+Math.random()*26,h=H*.06+Math.random()*H*.14;a.push({x,w,h,spd:.62+Math.random()*.12});x+=w+Math.random()*3+1;}
  return a;
}
function makeClouds(){
  return Array.from({length:9},(_,i)=>({x:(W/9)*i+Math.random()*50,y:10+Math.random()*H*.28,w:45+Math.random()*95,spd:.4+Math.random()*.55}));
}
function makeStars(){
  return Array.from({length:100},()=>({x:Math.random()*W,y:Math.random()*H*.65,r:.4+Math.random()*2,tw:Math.random()*Math.PI*2,sp:.012+Math.random()*.04}));
}
function makeRain(){
  return Array.from({length:140},()=>({x:Math.random()*W,y:Math.random()*H,spd:8+Math.random()*6,len:12+Math.random()*16,dx:-1.5+Math.random()*.5}));
}
function makeSnow(){
  return Array.from({length:80},()=>({x:Math.random()*W,y:Math.random()*H,spd:.6+Math.random()*1.2,r:1.5+Math.random()*2.5,dx:Math.random()*.4-.2,sway:Math.random()*Math.PI*2}));
}

function drawBackground(env){
  const{GH}=K();

  // Sky gradient
  const g=ctx.createLinearGradient(0,0,0,H);
  env.sky.forEach((c,i)=>g.addColorStop(i/3,c));
  ctx.fillStyle=g;ctx.fillRect(0,0,W,H);

  // Stars
  if(env.stars||env.nightOverlay>.3){
    const sa=Math.min(env.nightOverlay*1.3,1);
    starsArr.forEach(st=>{
      st.tw+=st.sp;
      ctx.globalAlpha=sa*(.45+.55*Math.sin(st.tw));
      ctx.fillStyle='white';
      ctx.beginPath();ctx.arc(st.x,st.y,st.r,0,Math.PI*2);ctx.fill();
    });
    ctx.globalAlpha=1;
  }

  // Lightning (storm)
  if(env.lightning){
    lightningT-=1;
    if(lightningT<=0){
      lightningFlash=Math.random()<.022?8:0;
      lightningT=30+Math.random()*90;
    }
    if(lightningFlash>0){
      lightningFlash--;
      if(lightningFlash%2===0){
        ctx.globalAlpha=.4;ctx.fillStyle='rgba(220,220,255,.6)';ctx.fillRect(0,0,W,H);ctx.globalAlpha=1;
        // lightning bolt
        ctx.save();ctx.strokeStyle='#FFFDE7';ctx.lineWidth=3;ctx.shadowColor='white';ctx.shadowBlur=25;
        let lx=W*.2+Math.random()*W*.6,ly=0;ctx.beginPath();ctx.moveTo(lx,ly);
        for(let i=0;i<7;i++){lx+=Math.random()*50-25;ly+=H/7;ctx.lineTo(lx,ly);}
        ctx.stroke();ctx.shadowBlur=0;ctx.restore();
      }
    }
  }

  // Sun or Moon
  const celX=W*.83,celY=H*.09,celR=H*.052;
  if(env.sun){
    ctx.globalAlpha=.2;ctx.fillStyle='#FFF9C4';ctx.beginPath();ctx.arc(celX,celY,celR*2.2,0,Math.PI*2);ctx.fill();
    ctx.globalAlpha=.5;ctx.beginPath();ctx.arc(celX,celY,celR*1.4,0,Math.PI*2);ctx.fill();ctx.globalAlpha=1;
    const sunCol=env.sunOrange?'#FF8A50':'#FFF176';
    const sunStroke=env.sunOrange?'#E64A19':'#F9A825';
    ctx.fillStyle=sunCol;ctx.strokeStyle=sunStroke;ctx.lineWidth=3;
    ctx.beginPath();ctx.arc(celX,celY,celR,0,Math.PI*2);ctx.fill();ctx.stroke();
    // rays (orange sunset has longer rays)
    if(!env.sunOrange){
      for(let i=0;i<8;i++){
        const a=i/8*Math.PI*2,r1=celR*1.35,r2=celR*1.8;
        ctx.strokeStyle='rgba(249,168,37,.6)';ctx.lineWidth=2;
        ctx.beginPath();ctx.moveTo(celX+Math.cos(a)*r1,celY+Math.sin(a)*r1);ctx.lineTo(celX+Math.cos(a)*r2,celY+Math.sin(a)*r2);ctx.stroke();
      }
    }
    // sun face
    ctx.fillStyle=env.sunOrange?'rgba(0,0,0,.35)':'#F57F17';
    ctx.beginPath();ctx.ellipse(celX-celR*.3,celY-celR*.1,celR*.12,celR*.16,0,0,Math.PI*2);ctx.fill();
    ctx.beginPath();ctx.ellipse(celX+celR*.3,celY-celR*.1,celR*.12,celR*.16,0,0,Math.PI*2);ctx.fill();
    ctx.strokeStyle=env.sunOrange?'rgba(0,0,0,.35)':'#F57F17';ctx.lineWidth=2;ctx.lineCap='round';
    ctx.beginPath();ctx.arc(celX,celY+celR*.1,celR*.28,.1,Math.PI-.1);ctx.stroke();
  }
  if(env.moon){
    const moonA=Math.min(env.nightOverlay*1.8,1);
    ctx.globalAlpha=moonA*.9;
    ctx.fillStyle='#FFF9C4';ctx.strokeStyle='#F9A825';ctx.lineWidth=2;
    ctx.beginPath();ctx.arc(celX,celY,celR,0,Math.PI*2);ctx.fill();ctx.stroke();
    // craters
    ctx.fillStyle='rgba(0,0,0,.14)';
    [[-.2,-.1,.18],[.22,.16,.12],[.02,.22,.09]].forEach(([dx,dy,r])=>{ctx.beginPath();ctx.arc(celX+dx*celR*2,celY+dy*celR*2,r*celR,0,Math.PI*2);ctx.fill();});
    ctx.globalAlpha=1;
  }

  // Clouds (hide in heavy rain/storm)
  if(env.nightOverlay<.7){
    clouds.forEach(cl=>{
      if(state==='playing')cl.x-=cl.spd;
      if(cl.x<-cl.w-20)cl.x=W+cl.w+20;
      ctx.globalAlpha=Math.max(0,(1-env.nightOverlay*.9)*(1-env.rainAlpha*.6));
      drawCloud(cl.x,cl.y,cl.w,env);
      ctx.globalAlpha=1;
    });
  }

  // Far bg buildings
  bgBuilds.forEach(b=>{
    if(state==='playing')b.x-=b.spd;
    if(b.x+b.w<-5){b.x=W+5;b.h=H*.12+Math.random()*H*.28;}
    ctx.fillStyle=env.far;ctx.strokeStyle='rgba(0,0,0,.12)';ctx.lineWidth=1;
    ctx.fillRect(b.x,H-GH-b.h,b.w,b.h);ctx.strokeRect(b.x,H-GH-b.h,b.w,b.h);
    for(let wy2=H-GH-b.h+4;wy2<H-GH-6;wy2+=9){
      for(let wc=0;wc<2;wc++){
        const lit=env.nightOverlay>.4&&Math.sin(b.wo+wy2*.1+wc)>.08;
        ctx.fillStyle=lit?'rgba(255,235,100,.5)':'rgba(0,0,0,.06)';
        ctx.fillRect(b.x+3+wc*9,wy2,5,5);
        if(lit){ctx.shadowColor='rgba(255,235,100,.4)';ctx.shadowBlur=5;ctx.fillRect(b.x+3+wc*9,wy2,5,5);ctx.shadowBlur=0;}
      }
    }
    // building color tint at night
    if(env.nightOverlay>.3){ctx.fillStyle=`rgba(0,0,20,${env.nightOverlay*.35})`;ctx.fillRect(b.x,H-GH-b.h,b.w,b.h);}
  });

  // Mid buildings
  midBuilds.forEach(b=>{
    if(state==='playing')b.x-=b.spd;
    if(b.x+b.w<-5){b.x=W+5;b.h=H*.06+Math.random()*H*.14;}
    ctx.fillStyle=env.mid;ctx.strokeStyle='rgba(0,0,0,.18)';ctx.lineWidth=1.5;
    ctx.fillRect(b.x,H-GH-b.h,b.w,b.h);ctx.strokeRect(b.x,H-GH-b.h,b.w,b.h);
  });

  // Ground
  ctx.fillStyle=env.ground;ctx.strokeStyle='#222';ctx.lineWidth=2;
  ctx.fillRect(0,H-GH,W,GH);ctx.strokeRect(0,H-GH,W,GH);
  const roadY=H-GH*.52;
  ctx.fillStyle=env.road;ctx.strokeStyle='#222';ctx.lineWidth=2;
  ctx.fillRect(0,roadY,W,H-roadY);
  ctx.beginPath();ctx.moveTo(0,roadY);ctx.lineTo(W,roadY);ctx.stroke();

  // Road markings
  if(state==='playing')roadOff=(roadOff+K().SPD*.9)%54;
  ctx.fillStyle='#FFF176';ctx.strokeStyle='#222';ctx.lineWidth=1;
  for(let x=-54+roadOff;x<W+54;x+=54){ctx.fillRect(x,roadY+GH*.18,32,5);ctx.strokeRect(x,roadY+GH*.18,32,5);}
  // rain reflection on road (at night)
  if(env.rainAlpha>.2){
    ctx.fillStyle=`rgba(100,160,255,${env.rainAlpha*.12})`;ctx.fillRect(0,roadY,W,H-roadY);
  }
  // pavement tiles
  ctx.strokeStyle='rgba(0,0,0,.1)';ctx.lineWidth=1;
  for(let x=0;x<W;x+=28){ctx.beginPath();ctx.moveTo(x,H-GH*.52);ctx.lineTo(x,H);ctx.stroke();}

  // Street lamps — 5 fixed positions
  [W*.08,W*.29,W*.52,W*.75,W*.94].forEach(lx=>drawLamp(lx,roadY,env.lampOn,GH,env));
}

function drawCloud(x,y,w,env){
  const isStorm=phase>=6;
  const cloudColor=isStorm?'#666':'white';
  ctx.fillStyle='rgba(0,0,0,.1)';
  [[0,0,w*.43],[w*.27,-w*.15,w*.29],[-.25*w,-w*.12,w*.27],[.06*w,-w*.25,w*.25]].forEach(([dx,dy,r])=>{ctx.beginPath();ctx.arc(x+dx,y+dy,r+3,0,Math.PI*2);ctx.fill();});
  ctx.fillStyle=cloudColor;
  [[0,0,w*.43],[w*.27,-w*.15,w*.29],[-.25*w,-w*.12,w*.27],[.06*w,-w*.25,w*.25]].forEach(([dx,dy,r])=>{ctx.beginPath();ctx.arc(x+dx,y+dy,r,0,Math.PI*2);ctx.fill();});
}

function drawLamp(x,groundY,on,GH,env){
  const s=K().s,ph=GH*1.1,pt=groundY-ph,lx=x+20*s,ly=pt-2*s;
  ctx.strokeStyle='#455A64';ctx.lineWidth=3.5*s;ctx.lineCap='round';
  ctx.beginPath();ctx.moveTo(x,groundY);ctx.lineTo(x,pt);ctx.stroke();
  ctx.lineWidth=3*s;
  ctx.beginPath();ctx.moveTo(x,pt);ctx.quadraticCurveTo(x+13*s,pt-9*s,lx,ly);ctx.stroke();
  if(on){
    // cone of light on ground
    ctx.save();
    ctx.globalAlpha=.08+env.nightOverlay*.06;
    ctx.fillStyle='#FFF9C4';
    ctx.beginPath();ctx.moveTo(lx,ly);ctx.lineTo(lx-30*s,groundY);ctx.lineTo(lx+30*s,groundY);ctx.closePath();ctx.fill();
    ctx.restore();
    // glow halo
    ctx.globalAlpha=.25+env.nightOverlay*.15;ctx.fillStyle='#FFF9C4';
    ctx.beginPath();ctx.arc(lx,ly,16*s,0,Math.PI*2);ctx.fill();ctx.globalAlpha=1;
    if(env.nightOverlay>.5){
      ctx.shadowColor='rgba(255,249,196,.6)';ctx.shadowBlur=20;
    }
  }
  ctx.fillStyle=on?'#FFF9C4':'#BDBDBD';ctx.strokeStyle='#222';ctx.lineWidth=2.5*s;
  ctx.beginPath();ctx.ellipse(lx,ly,7*s,4.5*s,0,0,Math.PI*2);ctx.fill();ctx.stroke();
  ctx.shadowBlur=0;
  ctx.fillStyle='#546E7A';ctx.strokeStyle='#222';ctx.lineWidth=2*s;
  ctx.beginPath();ctx.rect(x-4*s,groundY-5*s,8*s,5*s);ctx.fill();ctx.stroke();
}

// ── WEATHER OVERLAYS ──
function drawWeather(env){
  // FOG — gradient from bottom
  if(env.fogAlpha>0){
    const fg=ctx.createLinearGradient(0,H*.4,0,H);
    fg.addColorStop(0,'rgba(180,180,200,0)');
    fg.addColorStop(0.6,`rgba(180,180,200,${env.fogAlpha*.5})`);
    fg.addColorStop(1,`rgba(180,180,200,${env.fogAlpha})`);
    ctx.fillStyle=fg;ctx.fillRect(0,0,W,H);
  }

  // RAIN
  if(env.rainAlpha>0){
    ctx.globalAlpha=env.rainAlpha*.75;
    ctx.strokeStyle='rgba(174,214,241,0.85)';ctx.lineWidth=1.2;ctx.lineCap='round';
    rainDrops.forEach(r=>{
      if(state==='playing'){r.x+=r.dx*2;r.y+=r.spd;}
      if(r.y>H){r.y=-20;r.x=Math.random()*W;}
      if(r.x<0)r.x=W;if(r.x>W)r.x=0;
      ctx.beginPath();ctx.moveTo(r.x,r.y);ctx.lineTo(r.x+r.dx*3,r.y+r.len);ctx.stroke();
    });
    ctx.globalAlpha=1;
    // rain splashes on ground
    const{GH}=K();
    ctx.strokeStyle='rgba(174,214,241,0.4)';ctx.lineWidth=1;
    for(let i=0;i<6;i++){
      const sx=(Math.sin(frameCount*.1+i*2)*W*.5+W*.5);
      ctx.beginPath();ctx.arc(sx,H-GH*.55,2+Math.sin(frameCount*.15+i)*2,Math.PI,0);ctx.stroke();
    }
  }

  // SNOW
  if(env.snowAlpha>0){
    ctx.globalAlpha=env.snowAlpha*.85;
    snowFlakes.forEach(f=>{
      f.sway+=.02;
      if(state==='playing'){f.x+=Math.sin(f.sway)*f.dx+.3;f.y+=f.spd;}
      if(f.y>H){f.y=-10;f.x=Math.random()*W;}
      if(f.x>W)f.x=0;if(f.x<0)f.x=W;
      ctx.fillStyle='white';ctx.beginPath();ctx.arc(f.x,f.y,f.r,0,Math.PI*2);ctx.fill();
    });
    ctx.globalAlpha=1;
  }

  // DUST (sunset)
  if(env.dustAlpha>0){
    ctx.globalAlpha=env.dustAlpha;
    ctx.fillStyle='rgba(255,160,60,.6)';
    for(let i=0;i<8;i++){
      const dx=(frameCount*1.2+i*W/8)%W,dy=H*.3+Math.sin(frameCount*.015+i)*H*.15;
      ctx.beginPath();ctx.ellipse(dx,dy,22,5,0,0,Math.PI*2);ctx.fill();
    }
    ctx.globalAlpha=1;
  }

  // NIGHT OVERLAY
  if(env.nightOverlay>0){
    ctx.fillStyle=`rgba(5,0,30,${env.nightOverlay*.4})`;ctx.fillRect(0,0,W,H);
  }

  // GLITCH (midnight)
  if(env.glitchAlpha>0&&Math.random()<.04){
    const gy=Math.random()*H,gh=4+Math.random()*20;
    ctx.save();ctx.globalAlpha=env.glitchAlpha;
    const id=ctx.getImageData(0,gy*DPR,(W+20)*DPR,gh*DPR);
    ctx.putImageData(id,(Math.random()*20-10)*DPR,gy*DPR);
    ctx.restore();
  }
}

// ── START SCREEN BG ──
function buildStartBg(){
  const sc=document.getElementById('sBg');
  sc.width=W;sc.height=H;sc.style.width=W+'px';sc.style.height=H+'px';
  const c2=sc.getContext('2d');
  const g=c2.createLinearGradient(0,0,0,H);
  g.addColorStop(0,'#1565C0');g.addColorStop(.4,'#1E88E5');g.addColorStop(.75,'#64B5F6');g.addColorStop(1,'#B3E5FC');
  c2.fillStyle=g;c2.fillRect(0,0,W,H);
  c2.globalAlpha=.18;c2.fillStyle='#FFF9C4';c2.beginPath();c2.arc(W*.82,H*.1,H*.08,0,Math.PI*2);c2.fill();c2.globalAlpha=1;
  c2.fillStyle='#FFF176';c2.strokeStyle='#F9A825';c2.lineWidth=3;c2.beginPath();c2.arc(W*.82,H*.1,H*.05,0,Math.PI*2);c2.fill();c2.stroke();
  c2.fillStyle='#37474F';
  for(let i=0;i<22;i++){const bx=(W/22)*i,bw=(W/22)*.84,bh=H*.1+Math.sin(i*1.9)*H*.12;c2.fillRect(bx,H*.72-bh,bw,bh+H*.28);}
  c2.strokeStyle='rgba(0,0,0,.15)';c2.lineWidth=1;
  for(let i=0;i<22;i++){const bx=(W/22)*i,bw=(W/22)*.84,bh=H*.1+Math.sin(i*1.9)*H*.12;c2.strokeRect(bx,H*.72-bh,bw,bh+H*.28);}
  c2.fillStyle='#424242';c2.fillRect(0,H*.88,W,H*.12);
  c2.strokeStyle='#222';c2.lineWidth=2;c2.beginPath();c2.moveTo(0,H*.88);c2.lineTo(W,H*.88);c2.stroke();
  // tiny road markings
  c2.fillStyle='#FFF176';for(let x=0;x<W;x+=54){c2.fillRect(x,H*.92,32,5);}
  // lamps on start
  c2.strokeStyle='#455A64';c2.lineWidth=3;c2.lineCap='round';
  [W*.15,W*.45,W*.75].forEach(lx=>{c2.beginPath();c2.moveTo(lx,H*.88);c2.lineTo(lx,H*.78);c2.stroke();c2.beginPath();c2.moveTo(lx,H*.78);c2.quadraticCurveTo(lx+10,H*.75,lx+18,H*.77);c2.stroke();c2.fillStyle='#FFF9C4';c2.beginPath();c2.ellipse(lx+18,H*.77,6,4,0,0,Math.PI*2);c2.fill();});
}
buildStartBg();

// ══════════════════════════════════════════
//  PARTICLES & FEATHERS
// ══════════════════════════════════════════
function spawnP(x,y,big){
  const n=big?20:10,cols=['#FFF176','#FF5500','#FFB300','#64B5F6','#43A047','white','#E53935','#FFD54F'];
  for(let i=0;i<n;i++){const a=(Math.PI*2/n)*i+Math.random()*.6,sp=(big?4:2.5)+Math.random()*(big?5:3.5);parts.push({x,y,vx:Math.cos(a)*sp,vy:Math.sin(a)*sp,life:1,size:(big?6:3.5)+Math.random()*5.5,col:cols[Math.floor(Math.random()*cols.length)]});}
}
function spawnF(x,y){
  for(let i=0;i<8;i++){const a=Math.random()*Math.PI*2,sp=1.5+Math.random()*3;feathers.push({x,y,vx:Math.cos(a)*sp,vy:Math.sin(a)*sp-2,rot:Math.random()*Math.PI*2,vr:.1+Math.random()*.2,life:1,size:8+Math.random()*8,col:['#FFB300','#FF8C00','#E65100'][Math.floor(Math.random()*3)]});}
}

// ══════════════════════════════════════════
//  COLLISION
// ══════════════════════════════════════════
function hit(){
  const{BR,PW,GAP,GH}=K();
  if(bird.y+BR>=H-GH||bird.y-BR<=0)return true;
  for(let p of pipes){
    if(bird.x+BR>p.x-3&&bird.x-BR<p.x+PW+3){
      if(bird.y-BR<p.gapY-GAP/2)return true;
      if(bird.y+BR>p.gapY+GAP/2)return true;
    }
  }
  return false;
}

// ══════════════════════════════════════════
//  POPUPS
// ══════════════════════════════════════════
function showPop(txt,x,y){
  const el=document.createElement('div');el.className='spop';el.textContent=txt;
  el.style.left=x+'px';el.style.top=y+'px';
  document.body.appendChild(el);setTimeout(()=>el.remove(),950);
}
function showCombo(n){
  comboEl.textContent=`${n}x COMBO 🔥`;
  comboEl.classList.remove('flash');void comboEl.offsetWidth;comboEl.classList.add('flash');
}
function triggerPhaseFlash(col){
  pfEl.style.background=col;
  pfEl.classList.remove('pop');void pfEl.offsetWidth;pfEl.classList.add('pop');
}
function showBadge(txt){
  phaseBadge.textContent=txt;
  phaseBadge.style.opacity='1';
  setTimeout(()=>{phaseBadge.style.opacity='0';},3000);
}

// ══════════════════════════════════════════
//  INIT
// ══════════════════════════════════════════
function initGame(){
  bird=makeBird();pipes=[];parts=[];feathers=[];
  bgBuilds=makeBgBuilds();midBuilds=makeMidBuilds();
  clouds=makeClouds();starsArr=makeStars();
  rainDrops=makeRain();snowFlakes=makeSnow();
  score=0;combo=0;frameCount=0;bsi=0;roadOff=0;
  totalPassed=0;phase=0;phaseT=0;
  lightningT=60;lightningFlash=0;
  svEl.textContent='0';bvEl.textContent=best;
}

// ══════════════════════════════════════════
//  MAIN LOOP
// ══════════════════════════════════════════
function loop(){
  frameCount++;
  const env=getEnv();
  ctx.clearRect(0,0,W,H);
  drawBackground(env);

  const k=K();

  if(state==='playing'){
    // Physics — ALWAYS THE SAME
    bird.vy+=k.GR;
    bird.y+=bird.vy;

    // Pipes — ALWAYS THE SAME interval
    if(frameCount%PIPE_INTERVAL===0)pipes.push(makePipe());
    pipes.forEach(p=>p.x-=k.SPD);
    pipes=pipes.filter(p=>p.x>-k.PW-60);

    pipes.forEach(p=>{
      if(!p.passed&&p.x+k.PW<bird.x){
        p.passed=true;combo++;totalPassed++;

        // Phase progression — purely visual
        const newPhase=Math.min(Math.floor(totalPassed/PIPES_PER_PHASE),PHASES.length-1);
        phaseT=((totalPassed%PIPES_PER_PHASE)/PIPES_PER_PHASE);
        if(newPhase>phase){
          phase=newPhase;phaseT=0;
          triggerPhaseFlash(PHASES[phase].color);
          showBadge(PHASES[phase].name);
          sfxPhase();
          if(musicOn)startMusic();
        }

        const pts=combo>=3?2:1;score+=pts;
        if(score>best)best=score;
        svEl.textContent=score;bvEl.textContent=best;
        showPop(combo>=3?`+${pts} 🔥`:`+1 ⭐`,bird.x-10,bird.y-62);
        if(combo>=3)showCombo(combo);
        spawnP(bird.x,bird.y,false);
        sfxScore(combo);
      }
    });

    if(hit()&&state==='playing'){
      state='dead';combo=0;sfxHit();
      spawnF(bird.x,bird.y);spawnP(bird.x,bird.y,true);
      flEl.classList.remove('pop');void flEl.offsetWidth;flEl.classList.add('pop');
      stopMusic();setTimeout(gameOver,800);
    }
  }

  pipes.forEach(p=>drawPipe(p,env));

  // Weather on top of buildings
  drawWeather(env);

  // Feathers
  feathers=feathers.filter(f=>f.life>0);
  feathers.forEach(f=>{
    f.x+=f.vx;f.y+=f.vy;f.vy+=.14;f.vx*=.98;f.rot+=f.vr;f.life-=.022;
    ctx.save();ctx.translate(f.x,f.y);ctx.rotate(f.rot);ctx.globalAlpha=f.life;
    ctx.fillStyle=f.col;ctx.strokeStyle='#222';ctx.lineWidth=1.5;
    ctx.beginPath();ctx.ellipse(0,0,f.size*.4,f.size,0,0,Math.PI*2);ctx.fill();ctx.stroke();
    ctx.restore();ctx.globalAlpha=1;
  });

  // Particles
  parts=parts.filter(p=>p.life>0);
  parts.forEach(p=>{
    p.x+=p.vx;p.y+=p.vy;p.vy+=.18;p.life-=.026;p.size*=.97;
    ctx.globalAlpha=p.life;ctx.fillStyle=p.col;ctx.strokeStyle='rgba(0,0,0,.2)';ctx.lineWidth=1;
    ctx.beginPath();ctx.arc(p.x,p.y,p.size/2,0,Math.PI*2);ctx.fill();ctx.stroke();
  });
  ctx.globalAlpha=1;

  // Bird idle float on start
  if(state==='start')bird.y=H/2+Math.sin(frameCount*.038)*24;
  if(state!=='dead'||frameCount%4<3)drawBird();

  raf=requestAnimationFrame(loop);
}

// ══════════════════════════════════════════
//  GAME OVER
// ══════════════════════════════════════════
function gameOver(){
  oScEl.textContent=score;oBeEl.textContent=best;
  const m=[];
  if(score>=5)m.push('🥉');if(score>=15)m.push('🥈');if(score>=30)m.push('🥇');if(score>=50)m.push('🏆');
  oMedEl.textContent=m.join(' ');
  const reached=PHASES[Math.min(phase,PHASES.length-1)].name;
  if(score>=50){oEmEl.textContent='🏆';oTiEl.textContent='Légendaire !';}
  else if(score>=30){oEmEl.textContent='🥇';oTiEl.textContent='Incroyable !';}
  else if(score>=15){oEmEl.textContent='😄';oTiEl.textContent='Trop forte !';}
  else if(score>=5){oEmEl.textContent='😊';oTiEl.textContent='Bien joué !';}
  else{oEmEl.textContent='😵';oTiEl.textContent='Aïe !';}
  overEl.style.display='flex';
  tapEl.style.display='none';hudEl.style.display='none';
  musicBtn.style.display='none';phaseBadge.style.display='none';
}

// ══════════════════════════════════════════
//  START / INPUT
// ══════════════════════════════════════════
function startGame(){
  startEl.classList.add('hidden');overEl.style.display='none';
  hudEl.style.display='flex';tapEl.style.display='block';
  musicBtn.style.display='flex';phaseBadge.style.display='block';phaseBadge.style.opacity='0';
  initAudio();initGame();state='playing';
  if(musicOn)startMusic();
  if(raf)cancelAnimationFrame(raf);loop();
}

function jump(){
  if(state!=='playing')return;
  bird.vy=K().JMP;bird.squish=.72;bird.wingAngle=1.2;bird.wingDir=-1;bird.trail=[];
  sfxJump();spawnP(bird.x+12,bird.y+8,false);
}

tapEl.addEventListener('touchstart',e=>{e.preventDefault();jump();},{passive:false});
tapEl.addEventListener('mousedown',e=>{e.preventDefault();jump();});
document.addEventListener('keydown',e=>{if(e.code==='Space'||e.code==='ArrowUp')jump();});

function addBtn(id,fn){
  const el=document.getElementById(id);
  el.addEventListener('click',fn);
  el.addEventListener('touchend',e=>{e.preventDefault();fn();});
}
addBtn('btnS',startGame);
addBtn('btnR',startGame);
addBtn('btnH',()=>{
  state='start';overEl.style.display='none';tapEl.style.display='none';
  hudEl.style.display='none';musicBtn.style.display='none';phaseBadge.style.display='none';
  startEl.classList.remove('hidden');stopMusic();
  if(raf)cancelAnimationFrame(raf);initGame();loop();
});

// Boot
initGame();state='start';loop();
</script>

</body>
</html>
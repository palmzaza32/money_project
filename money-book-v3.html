<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>สมุดเงิน</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#F3F7FE; --card:#FFFFFF; --soft:#EEF3FC; --ink:#0F1F3D; --mut:#5E6E8C; --line:#E1E8F5;
  --pri:#2563EB; --pri-d:#1D4ED8; --inc:#0E9F6E; --exp:#E5484D; --inv:#2563EB; --sav:#0EA5E9; --tax:#6366F1;
  color-scheme:light;
}
*{box-sizing:border-box;margin:0}
body{background:var(--bg);color:var(--ink);font:400 15px/1.55 'Noto Sans Thai','Sarabun',system-ui,sans-serif;-webkit-font-smoothing:antialiased}
button,input,textarea{font:inherit;color:inherit}
.wrap{max-width:1080px;margin:0 auto;padding:0 16px}
.page{padding-top:20px;padding-bottom:72px}
.mut{color:var(--mut)} .sm{font-size:12.5px} .grow{flex:1;min-width:0}
h2{font-size:15px;font-weight:600;margin-bottom:14px}

/* app bar */
.appbar{background:var(--card);border-bottom:1px solid var(--line);position:sticky;top:0;z-index:6}
.appbar .wrap{display:flex;align-items:center;gap:20px;min-height:58px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:10px;font-weight:600}
.mark{width:26px;height:26px;border-radius:8px;background:var(--pri);display:grid;place-items:center;color:#fff;font-size:13px;font-weight:600}
nav.tabs{display:flex;gap:2px;overflow-x:auto;scrollbar-width:none;flex:1}
.tab{border:0;background:transparent;color:var(--mut);padding:18px 12px 16px;font-weight:500;cursor:pointer;white-space:nowrap;border-bottom:2px solid transparent}
.tab:hover{color:var(--ink)}
.tab[aria-selected=true]{color:var(--ink);border-bottom-color:var(--pri)}
.me{display:flex;align-items:center;gap:8px;border:1px solid var(--line);background:var(--card);border-radius:999px;padding:4px 12px 4px 4px;cursor:pointer}
.me[aria-pressed=true]{background:var(--soft)}
.av{width:28px;height:28px;border-radius:50%;background:var(--soft);display:grid;place-items:center;font-weight:600;font-size:13px;color:var(--pri-d);flex:none}
.ti,.short{display:none}
.tab{display:flex;align-items:center;gap:6px}
.ti{width:22px;height:22px;fill:none;stroke:currentColor;stroke-width:1.8;stroke-linecap:round;stroke-linejoin:round}
@media(max-width:760px){
  .appbar .wrap{min-height:52px}.me{margin-left:auto}
  nav.tabs{position:fixed;left:0;right:0;bottom:0;z-index:9;background:var(--card);border-top:1px solid var(--line);padding:0 4px env(safe-area-inset-bottom);gap:0;justify-content:space-around;overflow:visible}
  .tab{flex:1;flex-direction:column;gap:2px;padding:8px 2px 9px;font-size:11px;border-bottom:0;justify-content:center}
  .tab[aria-selected=true]{border-bottom:0;color:var(--pri)}
  .ti{display:block}.short{display:inline}.full{display:none}
  .page{padding-bottom:96px}#toast{bottom:84px}
}

.banner{background:#FFF7DD;border-bottom:1px solid #F2DA8C;color:#5B4A0A;font-size:13.5px}
.banner .wrap{display:flex;gap:12px;align-items:center;justify-content:space-between;padding-top:8px;padding-bottom:8px;flex-wrap:wrap}

.card{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:20px;min-width:0}
.cols{display:grid;gap:16px;grid-template-columns:minmax(0,1fr);margin-top:16px}
@media(min-width:900px){.cols.two{grid-template-columns:1.15fr .85fr}.cols.tax{grid-template-columns:minmax(0,1fr) 430px;align-items:start}.sticky{position:sticky;top:78px}}
.stack{display:grid;gap:16px;align-content:start;min-width:0}
.band{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));background:var(--card);border:1px solid var(--line);border-radius:14px;overflow:hidden}
.stat{padding:16px 20px;border-left:1px solid var(--line)} .stat:first-child{border-left:0}
.num{font-size:22px;font-weight:600;font-variant-numeric:tabular-nums;line-height:1.3}
.chip{--c:var(--pri);border:1px solid var(--line);background:var(--card);padding:7px 12px;border-radius:8px;cursor:pointer;display:inline-flex;gap:6px;align-items:center;font-size:14px;transition:background .12s,border-color .12s}
.chip:hover{background:var(--soft)}
.chip[aria-pressed=true]{background:color-mix(in srgb,var(--c) 11%,var(--card));border-color:var(--c);color:var(--ink);font-weight:500}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.seg{display:grid;grid-template-columns:1fr 1fr;background:var(--soft);padding:3px;border-radius:10px;gap:3px}
.seg.n3{grid-template-columns:repeat(3,1fr)}
.seg button{border:0;padding:8px;border-radius:8px;background:transparent;cursor:pointer;color:var(--mut)}
.seg button[aria-pressed=true]{background:var(--card);color:var(--c,var(--pri-d));box-shadow:0 0 0 1px var(--line);font-weight:600}
.in{width:100%;border:1px solid var(--line);background:var(--card);border-radius:10px;padding:10px 12px;min-height:42px}
.in:focus{outline:none;border-color:var(--pri);box-shadow:0 0 0 3px color-mix(in srgb,var(--pri) 18%,transparent)}
.btn:focus-visible,.chip:focus-visible,.tab:focus-visible,.cd:focus-visible,.nb:focus-visible,.mp:focus-visible,.x:focus-visible,.lnk:focus-visible,.me:focus-visible{outline:2px solid var(--pri);outline-offset:2px}
.fld{display:grid;gap:5px;font-size:13.5px} .fld span{font-weight:500} .fld small{color:var(--mut);font-size:12px}
.form{display:grid;gap:14px}
.two-in{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.lbl{font-size:13.5px;font-weight:500;margin-bottom:8px}
.btn{background:var(--pri);color:#fff;border:0;border-radius:10px;padding:11px 18px;font-weight:500;cursor:pointer;width:100%}
.btn:hover{filter:brightness(1.07)}
.btn.ghost{background:var(--card);color:var(--ink);border:1px solid var(--line);width:auto;padding:8px 14px}
.btn.ghost:hover{background:var(--soft)}
.btn.s{padding:5px 11px;font-size:13px;border-radius:8px}
.btn.danger{color:var(--exp);border-color:color-mix(in srgb,var(--exp) 45%,var(--line))}
.btn:disabled{opacity:.4;cursor:default}
.lnk{border:0;background:transparent;color:var(--pri);cursor:pointer;font-size:13px;padding:6px 8px;border-radius:8px}
.lnk:hover{background:var(--soft)}
.row{display:flex;gap:12px;align-items:center;padding:12px 0;border-top:1px solid var(--line)}
.row:first-of-type{border-top:0}
.dot{width:9px;height:9px;border-radius:50%;flex:none}
.amt{font-weight:600;font-variant-numeric:tabular-nums;white-space:nowrap}
.x{border:0;background:transparent;color:var(--mut);width:32px;height:32px;border-radius:8px;cursor:pointer;flex:none}
.x:hover{background:var(--soft);color:var(--exp)}
.edit{background:var(--soft);border-radius:10px;padding:12px;margin:0 0 10px;display:grid;gap:10px}
.datebar{display:flex;align-items:center;gap:12px;flex-wrap:wrap}
.nb{width:42px;height:42px;border-radius:10px;border:1px solid var(--line);background:var(--card);cursor:pointer;font-size:20px}
.nb:hover{background:var(--soft)} .nb:disabled{opacity:.35;cursor:default}
.dtxt{flex:1;min-width:150px}.big{font-size:20px;font-weight:600}
.datebar input[type=date]{width:auto}
.months{display:flex;gap:4px;overflow-x:auto;padding:14px 2px 2px;scrollbar-width:none}
.mp{border:0;background:transparent;padding:6px 12px;border-radius:8px;cursor:pointer;color:var(--mut);white-space:nowrap}
.mp:hover{background:var(--soft)} .mp[aria-pressed=true]{background:var(--pri);color:#fff}
.cal{display:grid;grid-template-columns:repeat(7,1fr);gap:4px}
.cal .h{text-align:center;font-size:12px;color:var(--mut);padding:4px 0}
.cd{aspect-ratio:1;border-radius:10px;border:0;background:transparent;cursor:pointer;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:3px;font-variant-numeric:tabular-nums}
.cd:hover{background:var(--soft)} .cd.sel{background:var(--pri);color:#fff}
.dots{display:flex;gap:3px;height:6px}.dots i{width:5px;height:5px;border-radius:50%}
.bar{height:6px;background:var(--soft);border-radius:99px;overflow:hidden}.bar>i{display:block;height:100%;border-radius:99px;background:var(--c,var(--pri))}
.donut{width:100%;max-width:220px;display:block;margin:0 auto 14px}
.dc-v{font-size:17px;font-weight:600;fill:var(--ink)}.dc-s{font-size:9.5px;fill:var(--mut)}
.lg{display:grid;gap:9px}.lg>div{display:flex;align-items:center;gap:9px;font-size:14px}
.lg i{width:10px;height:10px;border-radius:3px;flex:none}.lg b{font-weight:500;font-variant-numeric:tabular-nums}
.pill{display:inline-block;padding:2px 9px;border-radius:99px;font-size:12px;font-weight:500;background:var(--soft);color:var(--mut)}
.pill.pri{background:color-mix(in srgb,var(--pri) 13%,var(--card));color:var(--pri-d)}
.pos{background:color-mix(in srgb,var(--inc) 14%,var(--card));color:var(--inc)}
.neg{background:color-mix(in srgb,var(--exp) 14%,var(--card));color:var(--exp)}
.svgc{width:100%;height:auto;display:block}
.svgc text{fill:var(--mut);font-size:10.5px;font-family:inherit}
.tr{display:flex;justify-content:space-between;gap:12px;padding:8px 0;border-top:1px solid var(--line);font-variant-numeric:tabular-nums}
.tr:first-child{border-top:0}
.hero{font-size:32px;font-weight:600;font-variant-numeric:tabular-nums;line-height:1.25}
.note{background:var(--soft);border-radius:10px;padding:12px 14px;font-size:13px;color:var(--mut)}
.welcome{display:flex;gap:16px;align-items:center;justify-content:space-between;flex-wrap:wrap;margin-bottom:16px}
input[type=range]{width:100%;accent-color:var(--pri)}
.empty{color:var(--mut);text-align:center;padding:22px 8px;font-size:14px}
.goal{padding:14px 0;border-top:1px solid var(--line)}.goal:first-of-type{border-top:0}
.foot{margin-top:28px;display:flex;gap:10px;flex-wrap:wrap;align-items:center;color:var(--mut);font-size:12.5px}
#toast{position:fixed;left:50%;bottom:24px;transform:translate(-50%,16px);background:var(--ink);color:var(--card);padding:9px 16px;border-radius:10px;font-size:14px;opacity:0;pointer-events:none;transition:.2s;z-index:30;max-width:90vw}
#toast.on{opacity:1;transform:translate(-50%,0)}

/* auth + admin */
.auth{min-height:100vh;display:grid;place-items:center;padding:24px}
.auth .card{width:100%;max-width:380px;padding:28px}
.auth .brand{margin-bottom:6px;font-size:18px}
.err{color:var(--exp);font-size:13.5px;min-height:20px}
.subnav{display:flex;gap:4px;overflow-x:auto;scrollbar-width:none;margin-bottom:16px;border-bottom:1px solid var(--line)}
.sn{border:0;background:transparent;padding:9px 14px;color:var(--mut);cursor:pointer;border-bottom:2px solid transparent;white-space:nowrap;margin-bottom:-1px}
.sn[aria-pressed=true]{color:var(--pri-d);border-bottom-color:var(--pri);font-weight:500}
.urow{display:flex;gap:12px;align-items:center;padding:14px 0;border-top:1px solid var(--line);flex-wrap:wrap}
.urow:first-of-type{border-top:0}
.acts{display:flex;gap:6px;flex-wrap:wrap}
.cfgrow{display:flex;gap:8px;align-items:center;margin-bottom:8px}
.cfgrow .in{min-height:38px;padding:7px 10px}
.logrow{display:flex;gap:12px;padding:9px 0;border-top:1px solid var(--line);font-size:13.5px}
.logrow:first-child{border-top:0}
.logrow time{color:var(--mut);white-space:nowrap;min-width:112px;font-variant-numeric:tabular-nums}
textarea.in{min-height:140px;font-family:ui-monospace,Menlo,monospace;font-size:12px;resize:vertical}
@media(prefers-reduced-motion:reduce){*{transition:none!important}}
@media(max-width:520px){.hero{font-size:26px}.num{font-size:20px}.stat{padding:14px 16px}}
</style>
</head>
<body>
<div id="root"></div>
<div id="toast" role="status" aria-live="polite"></div>

<script>
/* ================= constants & helpers ================= */
let YEAR=2027, MIN='2027-01-01', MAX='2027-12-31';
const SHARED=true;
function setYear(y){YEAR=y;MIN=y+'-01-01';MAX=y+'-12-31'}
const todayStr=()=>{const n=new Date();return ymd(n.getFullYear(),n.getMonth()+1,n.getDate())};
const TH_M=['มกราคม','กุมภาพันธ์','มีนาคม','เมษายน','พฤษภาคม','มิถุนายน','กรกฎาคม','สิงหาคม','กันยายน','ตุลาคม','พฤศจิกายน','ธันวาคม'];
const TH_MS=['ม.ค.','ก.พ.','มี.ค.','เม.ย.','พ.ค.','มิ.ย.','ก.ค.','ส.ค.','ก.ย.','ต.ค.','พ.ย.','ธ.ค.'];
const TH_D=['อาทิตย์','จันทร์','อังคาร','พุธ','พฤหัสบดี','ศุกร์','เสาร์'];
const TH_DS=['อา','จ','อ','พ','พฤ','ศ','ส'];
const PAL=['#2563EB','#60A5FA','#1E3A8A','#38BDF8','#6366F1','#0EA5E9','#93C5FD','#A5B4FC','#64748B','#94A3B8','#CBD5E1'];
const GOAL_COL=['#2563EB','#38BDF8','#6366F1','#1E3A8A','#60A5FA','#0EA5E9','#A5B4FC'];
const PRESETS=[['สมดุล',20,20],['เน้นออม',30,15],['เน้นลงทุน',15,30],['ปลอดภัย',30,10]];
const DEF_CFG=()=>({appName:'สมุดเงิน',allowReg:true,
  inc:[{k:'salary',n:'เงินเดือน'},{k:'bonus',n:'โบนัส'},{k:'free',n:'ฟรีแลนซ์'},{k:'div',n:'ดอกเบี้ย/ปันผล'},{k:'sell',n:'ขายของ'},{k:'otherin',n:'รายรับอื่น ๆ'}],
  exp:[{k:'food',n:'อาหาร'},{k:'travel',n:'เดินทาง'},{k:'home',n:'ที่พัก'},{k:'bills',n:'น้ำ ไฟ เน็ต'},{k:'shop',n:'ช้อปปิ้ง'},{k:'health',n:'สุขภาพ'},{k:'fun',n:'บันเทิง'},{k:'edu',n:'การศึกษา'},{k:'family',n:'ครอบครัว'},{k:'debt',n:'ผ่อนชำระ'},{k:'other',n:'รายจ่ายอื่น ๆ'}],
  assets:[{k:'thstock',n:'หุ้นไทย',c:'#2563EB'},{k:'gstock',n:'หุ้นต่างประเทศ',c:'#38BDF8'},{k:'fund',n:'กองทุนรวม',c:'#6366F1'},{k:'gold',n:'ทองคำ',c:'#F2B01E'},{k:'bond',n:'ตราสารหนี้',c:'#1E3A8A'},{k:'crypto',n:'คริปโต',c:'#0EA5E9'},{k:'reit',n:'REIT/อสังหาฯ',c:'#93C5FD'},{k:'oth',n:'อื่น ๆ',c:'#94A3B8'}],
  goals:['กองทุนฉุกเฉิน','ท่องเที่ยว','ดาวน์บ้าน','ซื้อรถ','เกษียณ','การศึกษา','แต่งงาน'],
  tax:{personal:60000,expRate:50,expCap:100000,br:[[150000,0],[300000,5],[500000,10],[750000,15],[1000000,20],[2000000,25],[5000000,30],[null,35]]}});
function mergeCfg(c){const b=DEF_CFG();c=c||{};const o=Object.assign(b,c);o.tax=Object.assign(DEF_CFG().tax,c.tax||{});return o}
let CFG=DEF_CFG();

const pad=n=>String(n).padStart(2,'0');
const ymd=(y,m,d)=>`${y}-${pad(m)}-${pad(d)}`;
const parse=s=>{const [y,m,d]=s.split('-').map(Number);return new Date(y,m-1,d)};
const addDays=(s,n)=>{const d=parse(s);d.setDate(d.getDate()+n);return ymd(d.getFullYear(),d.getMonth()+1,d.getDate())};
const clampD=s=>s<MIN?MIN:s>MAX?MAX:s;
const money=n=>Math.round(n||0).toLocaleString('th-TH');
const money2=n=>(n||0).toLocaleString('th-TH',{minimumFractionDigits:0,maximumFractionDigits:2});
const sum=(a,f)=>a.reduce((s,x)=>s+f(x),0);
const uid=()=>Math.random().toString(36).slice(2,10);
const esc=s=>String(s??'').replace(/[&<>"]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c]));
const $=s=>document.querySelector(s);
const pct=(a,b)=>b>0?a/b*100:0;
const isObj=o=>o&&typeof o==='object'&&!Array.isArray(o);
const fmtT=t=>{if(!t)return 'ยังไม่เคย';const d=new Date(t);return `${d.getDate()} ${TH_MS[d.getMonth()]} ${pad(d.getHours())}:${pad(d.getMinutes())}`};
const catOf=t=>CFG.inc.find(c=>c.k===t.cat)||CFG.exp.find(c=>c.k===t.cat)||{n:'ไม่ระบุหมวด'};
const assetOf=k=>CFG.assets.find(a=>a.k===k)||{k,n:'อื่น ๆ',c:'#8A94A6'};
const expColor=k=>PAL[Math.max(CFG.exp.findIndex(c=>c.k===k),0)%PAL.length];

/* ================= storage (window.storage with in-memory fallback) ================= */
const MEM={};
const HAS_STORE=typeof window.storage!=='undefined';
const st={
  async get(k,sh){try{if(HAS_STORE){const r=await window.storage.get(k,sh);if(r&&r.value!=null)return JSON.parse(r.value)}}catch(e){}return MEM[k]??null},
  async set(k,v,sh){MEM[k]=v;try{if(HAS_STORE)await window.storage.set(k,JSON.stringify(v),sh)}catch(e){}},
  async del(k,sh){delete MEM[k];try{if(HAS_STORE)await window.storage.delete(k,sh)}catch(e){}}
};

/* ================= password hashing ================= */
const b64e=u=>btoa(String.fromCharCode(...u));
const b64d=s=>Uint8Array.from(atob(s),c=>c.charCodeAt(0));
async function hashPw(pw,salt){
  try{
    if(window.crypto&&crypto.subtle){
      const k=await crypto.subtle.importKey('raw',new TextEncoder().encode(pw),'PBKDF2',false,['deriveBits']);
      const bits=await crypto.subtle.deriveBits({name:'PBKDF2',salt:b64d(salt),iterations:120000,hash:'SHA-256'},k,256);
      return 'p'+b64e(new Uint8Array(bits));
    }
  }catch(e){}
  let h1=0xdeadbeef,h2=0x41c6ce57;const s=salt+'|'+pw+'|'+salt;
  for(let r=0;r<2000;r++)for(let i=0;i<s.length;i++){const c=s.charCodeAt(i);h1=Math.imul(h1^c,2654435761);h2=Math.imul(h2^c,1597334677)}
  h1=Math.imul(h1^(h1>>>16),2246822507)^Math.imul(h2^(h2>>>13),3266489909);
  return 'f'+(h1>>>0).toString(16)+(h2>>>0).toString(16);
}
const newSalt=()=>{const a=new Uint8Array(16);(window.crypto||{getRandomValues:x=>x.forEach((_,i)=>x[i]=Math.random()*256)}).getRandomValues(a);return b64e(a)};
async function makeUser({username,name,pw,role}){const salt=newSalt();return {id:uid(),username,name,role,active:true,salt,hash:await hashPw(pw,salt),created:Date.now(),last:0}}
function checkNew(username,pw,existing){
  if(!/^[a-z0-9_.]{3,20}$/.test(username))return 'ชื่อผู้ใช้ใช้ได้เฉพาะ a-z 0-9 _ . ยาว 3–20 ตัว';
  if(pw.length<6)return 'รหัสผ่านต้องยาวอย่างน้อย 6 ตัวอักษร';
  if(SYS.users.some(u=>u.username===username&&u.id!==existing))return 'ชื่อผู้ใช้นี้ถูกใช้แล้ว';
  return '';
}

/* ================= state ================= */
const defaults=()=>({year:2027,tx:[],inv:[],sav:[],goals:[],sel:'2027-01-01',plan:{save:20,invest:20},proj:{p:0,m:5000,r:7,y:10},
  tax:{i1:0,i2:0,i4:0,withheld:0,spouse:0,kids:0,kids2:0,parents:0,disabled:0,life:0,health:0,pHealth:0,sso:0,annuity:0,pvd:0,rmf:0,ssf:0,esg:0,home:0,donate:0}});
const D=defaults();
const U={tab:'overview',dTx:{type:'out',cat:'food',amount:'',note:''},edit:null,
  dInv:{cat:'fund',name:'',date:'',cost:'',value:'',div:''},pie:'cost',
  dSav:{type:'in',goal:'',date:'',amount:'',note:''},dGoal:{name:'',target:'',date:'2027-12-31'},
  auth:{u:'',p:'',p2:'',name:'',err:'',legacy:true,mode:'login',busy:false},
  viewAs:null,adm:'users',stats:null,resetFor:null,resetPw:'',nu:{name:'',username:'',pw:'',role:'user',err:''},
  acc:{name:'',cur:'',pw:'',msg:'',err:''},backup:'',imp:''};
const ROOT={D,U};
let SYS={users:[],log:[]},ME=null,READY=false,DOWNER=null,LEGACY=null,CFARM=null,ARMED=null;
const FAILS={};

function setPath(p,v){const a=p.split('.');let o=ROOT;for(let i=0;i<a.length-1;i++)o=o[a[i]];o[a[a.length-1]]=v}
function toast(m){const t=$('#toast');t.textContent=m;t.classList.add('on');clearTimeout(toast._t);toast._t=setTimeout(()=>t.classList.remove('on'),2000)}
function confirm2(key){if(ARMED===key)return true;CFARM=key;render();return false}

async function refreshSys(){const s=await st.get('mb:sys',SHARED);if(s){SYS.users=s.users||[];CFG=mergeCfg(s.cfg);if(ME){const m=SYS.users.find(x=>x.id===ME.id);if(m)ME=m}}}
async function saveSys(){await st.set('mb:sys',{users:SYS.users,cfg:CFG},SHARED)}
async function mutate(fn){await refreshSys();if(fn()===false)return false;await saveSys();return true}
async function log(a){SYS.log.unshift({t:Date.now(),who:ME?.username||'-',a});SYS.log=SYS.log.slice(0,200);await st.set('mb:log',SYS.log,SHARED)}

async function loadData(uid){
  const s=await st.get('mb:data:'+uid,SHARED),d=defaults();
  if(s)Object.keys(d).forEach(k=>{if(s[k]!==undefined)d[k]=isObj(d[k])?Object.assign(d[k],s[k]):s[k]});
  Object.keys(D).forEach(k=>delete D[k]);Object.assign(D,d);DOWNER=uid;setYear(D.year||2027);if(D.sel<MIN||D.sel>MAX)D.sel=MIN;U.dGoal.date=MAX;
}
let _t;
function save(){clearTimeout(_t);_t=setTimeout(flush,400)}
async function flush(){clearTimeout(_t);if(DOWNER)await st.set('mb:data:'+DOWNER,D,SHARED)}

async function boot(){
  const s=await st.get('mb:sys',SHARED);
  SYS.users=s?.users||[];CFG=mergeCfg(s?.cfg);
  SYS.log=(await st.get('mb:log',SHARED))||[];
  LEGACY=await st.get('money-book-2027-v1',false);
  const ses=await st.get('mb:session',false);
  if(ses){const u=SYS.users.find(x=>x.id===ses.uid&&x.active);if(u){ME=u;await loadData(u.id)}}
  READY=true;render();
}

/* ================= auth actions ================= */
function authErr(m){U.auth.err=m;U.auth.busy=false;render()}
async function startSession(user){
  ME=user;U.viewAs=null;await loadData(user.id);await st.set('mb:session',{uid:user.id},false);
  U.tab='overview';U.auth={u:'',p:'',p2:'',name:'',err:'',legacy:true,mode:'login',busy:false};render();
}
async function doLogin(){
  const uname=U.auth.u.trim().toLowerCase(),p=U.auth.p;
  if(!uname||!p)return authErr('กรอกชื่อผู้ใช้และรหัสผ่านก่อนนะ');
  const f=FAILS[uname];if(f&&f.until>Date.now())return authErr(`ลองผิดหลายครั้ง รออีก ${Math.ceil((f.until-Date.now())/1000)} วินาที`);
  U.auth.busy=true;await refreshSys();
  const user=SYS.users.find(x=>x.username===uname);
  if(!user||await hashPw(p,user.salt)!==user.hash){const n=((FAILS[uname]?.n)||0)+1;FAILS[uname]={n,until:n>=5?Date.now()+30000:0};if(n>=5)FAILS[uname].n=0;return authErr('ชื่อผู้ใช้หรือรหัสผ่านไม่ถูกต้อง')}
  if(!user.active)return authErr('บัญชีนี้ถูกปิดใช้งาน กรุณาติดต่อแอดมิน');
  delete FAILS[uname];
  await mutate(()=>{const u=SYS.users.find(x=>x.id===user.id);if(u)u.last=Date.now()});
  const u=SYS.users.find(x=>x.id===user.id);ME=u;await log('เข้าสู่ระบบ');await startSession(u);
}
async function doSetup(){
  const a=U.auth,uname=a.u.trim().toLowerCase();
  if(!a.name.trim())return authErr('ใส่ชื่อที่แสดงก่อนนะ');
  const e=checkNew(uname,a.p,null);if(e)return authErr(e);
  if(a.p!==a.p2)return authErr('รหัสผ่านสองช่องไม่ตรงกัน');
  const u=await makeUser({username:uname,name:a.name.trim(),pw:a.p,role:'admin'});u.last=Date.now();
  SYS.users=[u];await saveSys();
  if(a.legacy&&LEGACY)await st.set('mb:data:'+u.id,LEGACY,SHARED);
  ME=u;await log('สร้างบัญชีแอดมินคนแรก');await startSession(u);
}
async function doRegister(){
  const a=U.auth,uname=a.u.trim().toLowerCase();
  await refreshSys();if(!CFG.allowReg)return authErr('ขณะนี้ปิดรับสมัครสมาชิก');
  if(!a.name.trim())return authErr('ใส่ชื่อที่แสดงก่อนนะ');
  const e=checkNew(uname,a.p,null);if(e)return authErr(e);
  if(a.p!==a.p2)return authErr('รหัสผ่านสองช่องไม่ตรงกัน');
  const u=await makeUser({username:uname,name:a.name.trim(),pw:a.p,role:'user'});u.last=Date.now();
  await mutate(()=>{SYS.users.push(u)});ME=u;await log('สมัครสมาชิกใหม่');await startSession(u);
}
async function doLogout(){await flush();ME=null;DOWNER=null;U.viewAs=null;U.stats=null;await st.set('mb:session',null,false);render()}

/* ================= charts ================= */
function donut(items,center,sub){
  const tot=sum(items,i=>i.value),R=70,C=2*Math.PI*R;let off=0,segs='';const act=items.filter(i=>i.value>0);
  if(tot>0){act.forEach(i=>{const len=i.value/tot*C,g=act.length>1?2.5:0,l=Math.max(len-g,.5);
    segs+=`<circle r="${R}" cx="100" cy="100" fill="none" stroke="${i.color}" stroke-width="26" stroke-dasharray="${l} ${C-l}" stroke-dashoffset="${-off}" transform="rotate(-90 100 100)"><title>${esc(i.label)}</title></circle>`;off+=len;});}
  else segs=`<circle r="${R}" cx="100" cy="100" fill="none" stroke="var(--line)" stroke-width="26"/>`;
  return `<svg viewBox="0 0 200 200" class="donut" role="img" aria-label="กราฟวงกลมแสดงสัดส่วน">${segs}<text x="100" y="99" text-anchor="middle" class="dc-v">${center}</text><text x="100" y="116" text-anchor="middle" class="dc-s">${sub}</text></svg>`;
}
function legend(items,amt=true){
  const tot=sum(items,i=>i.value);
  return `<div class="lg">${items.map(i=>`<div><i style="background:${i.color}"></i><span class="grow">${esc(i.label)}</span><b>${pct(i.value,tot).toFixed(1)}%</b>${amt?`<span class="mut sm" style="min-width:76px;text-align:right">${money(i.value)}</span>`:''}</div>`).join('')}</div>`;
}
function bars(inc,exp){
  const W=720,H=230,pb=26,pt=12,max=Math.max(...inc,...exp,1),gw=W/12,bw=gw*.27,ch=H-pb-pt;let g='';
  for(let i=0;i<=3;i++){const y=pt+ch*i/3;g+=`<line x1="0" x2="${W}" y1="${y}" y2="${y}" stroke="var(--line)"/>`;}
  for(let m=0;m<12;m++){const x0=gw*m+gw/2,hi=inc[m]/max*ch,he=exp[m]/max*ch;
    g+=`<rect x="${x0-bw-1.5}" y="${pt+ch-hi}" width="${bw}" height="${Math.max(hi,0)}" rx="3" fill="var(--inc)"><title>${TH_M[m]} รายรับ ${money(inc[m])}</title></rect>`;
    g+=`<rect x="${x0+1.5}" y="${pt+ch-he}" width="${bw}" height="${Math.max(he,0)}" rx="3" fill="var(--exp)"><title>${TH_M[m]} รายจ่าย ${money(exp[m])}</title></rect>`;
    g+=`<text x="${x0}" y="${H-8}" text-anchor="middle">${TH_MS[m]}</text>`;}
  g+=`<text x="2" y="${pt-1}">สูงสุด ${money(max)}</text>`;
  return `<svg viewBox="0 0 ${W} ${H}" class="svgc" role="img" aria-label="กราฟแท่งรายรับรายจ่ายรายเดือน">${g}</svg>`;
}
function lineChart(a,b){
  const W=640,H=210,pl=4,pb=22,pt=10,n=a.length-1,max=Math.max(...a,...b,1),cw=W-pl*2,ch=H-pb-pt;
  const P=arr=>arr.map((v,i)=>`${i?'L':'M'}${(pl+cw*i/n).toFixed(1)},${(pt+ch-v/max*ch).toFixed(1)}`).join('');
  const yrs=n/12;let ticks='';
  for(let y=0;y<=yrs;y+=Math.max(1,Math.ceil(yrs/6)))ticks+=`<text x="${pl+cw*(y*12)/n}" y="${H-6}" text-anchor="middle">ปีที่ ${y}</text>`;
  return `<svg viewBox="0 0 ${W} ${H}" class="svgc" role="img" aria-label="กราฟการเติบโตของเงินลงทุน"><line x1="0" x2="${W}" y1="${pt+ch}" y2="${pt+ch}" stroke="var(--line)"/>
  <path d="${P(a)}L${pl+cw},${pt+ch}L${pl},${pt+ch}Z" fill="var(--inv)" opacity=".1"/>
  <path d="${P(a)}" fill="none" stroke="var(--inv)" stroke-width="2.2" stroke-linejoin="round"/>
  <path d="${P(b)}" fill="none" stroke="var(--mut)" stroke-width="1.6" stroke-dasharray="5 5"/>${ticks}</svg>`;
}

/* ================= derived ================= */
const txOn=d=>D.tx.filter(t=>t.date===d);
const totIn=a=>sum(a.filter(t=>t.type==='in'),t=>t.amount);
const totOut=a=>sum(a.filter(t=>t.type==='out'),t=>t.amount);
const savedTotal=()=>sum(D.sav,s=>s.type==='in'?s.amount:-s.amount);
const investedCost=()=>sum(D.inv,i=>i.cost);
const inY=d=>d.startsWith(YEAR+'-');
const TXY=()=>D.tx.filter(t=>inY(t.date));
const savedY=()=>sum(D.sav.filter(s=>inY(s.date)),s=>s.type==='in'?s.amount:-s.amount);
const investedY=()=>sum(D.inv.filter(i=>inY(i.date)),i=>i.cost);
function freqTx(){const m={};D.tx.slice(-300).forEach(t=>{if(![...CFG.inc,...CFG.exp].some(c=>c.k===t.cat))return;const k=[t.type,t.cat,t.amount,t.note].join('|');(m[k]??={n:0,t}).n++});return Object.values(m).filter(x=>x.n>=2).sort((a,b)=>b.n-a.n).slice(0,6).map(x=>x.t)}

/* ================= AUTH VIEWS ================= */
const brand=()=>`<div class="brand"><span class="mark">฿</span>${esc(CFG.appName)}</div>`;
const authFld=(label,k,type='text',ph='',enter='')=>`<label class="fld"><span>${label}</span><input class="in" type="${type}" placeholder="${ph}" autocomplete="${type==='password'?'current-password':'off'}" value="${esc(getP(k))}" data-k="${k}" ${enter?`data-enter="${enter}"`:''}></label>`;
const getP=p=>p.split('.').reduce((o,k)=>o?.[k],ROOT)??'';
const storeWarn=()=>HAS_STORE?'':`<div class="note">สภาพแวดล้อมนี้ไม่มีที่เก็บข้อมูลถาวร บัญชีและข้อมูลจะอยู่ถึงแค่ปิดหน้านี้</div>`;
function viewSetup(){
  return `<div class="auth"><div class="card form">${brand()}<div class="mut sm" style="margin-top:-6px">ตั้งค่าครั้งแรก · สร้างบัญชีแอดมิน</div>
  ${authFld('ชื่อที่แสดง','U.auth.name','text','เช่น สมชาย')}${authFld('ชื่อผู้ใช้','U.auth.u','text','a-z 0-9 _ .')}
  ${authFld('รหัสผ่าน (อย่างน้อย 6 ตัว)','U.auth.p','password')}${authFld('ยืนยันรหัสผ่าน','U.auth.p2','password','','setup')}
  ${LEGACY?`<button class="chip" aria-pressed="${U.auth.legacy}" data-act="legacy">${U.auth.legacy?'✓':'+'} นำเข้าข้อมูลเดิมจากเวอร์ชันก่อน</button>`:''}
  <div class="err">${esc(U.auth.err)}</div><button class="btn" data-act="setup" ${U.auth.busy?'disabled':''}>สร้างบัญชีแอดมิน</button>${storeWarn()}</div></div>`;
}
function viewLogin(){
  const reg=U.auth.mode==='reg';
  return `<div class="auth"><div class="card form">${brand()}<div class="mut sm" style="margin-top:-6px">${reg?'สมัครสมาชิกใหม่':'เข้าสู่ระบบเพื่อดูสมุดเงินของคุณ'}</div>
  ${reg?authFld('ชื่อที่แสดง','U.auth.name'):''}${authFld('ชื่อผู้ใช้','U.auth.u','text','',reg?'':'login')}
  ${authFld('รหัสผ่าน','U.auth.p','password','',reg?'':'login')}${reg?authFld('ยืนยันรหัสผ่าน','U.auth.p2','password','','register'):''}
  <div class="err">${esc(U.auth.err)}</div>
  <button class="btn" data-act="${reg?'register':'login'}" ${U.auth.busy?'disabled':''}>${reg?'สมัครสมาชิก':'เข้าสู่ระบบ'}</button>
  ${CFG.allowReg?`<button class="lnk" data-act="authMode" data-a="${reg?'login':'reg'}">${reg?'มีบัญชีแล้ว? เข้าสู่ระบบ':'ยังไม่มีบัญชี? สมัครสมาชิก'}</button>`:'<div class="mut sm" style="text-align:center">หากต้องการบัญชี ติดต่อแอดมิน</div>'}
  ${storeWarn()}</div></div>`;
}

/* ================= SHELL ================= */
function shell(){
  const IC={overview:'<path d="M4 13h6V4H4zM14 20h6V11h-6zM14 4h6v4h-6zM4 17h6v3H4z"/>',daily:'<rect x="4" y="5" width="16" height="15" rx="2"/><path d="M8 3v4M16 3v4M4 10h16"/>',invest:'<path d="M4 17l5-5 4 4 7-8"/><path d="M15 8h5v5"/>',save:'<circle cx="12" cy="12" r="8"/><circle cx="12" cy="12" r="3.5"/>',tax:'<path d="M7 3h8l4 4v14H7z"/><path d="M15 3v4h4M10 12h6M10 16h6"/>',admin:'<path d="M12 3l7 3v5c0 5-3 8-7 10-4-2-7-5-7-10V6z"/>'};
  const tabs=[['overview','ภาพรวม','ภาพรวม'],['daily','รายวัน','รายวัน'],['invest','ลงทุน','ลงทุน'],['save','ออมและเป้าหมาย','ออม'],['tax','ภาษีเงินได้','ภาษี']];
  if(ME.role==='admin')tabs.push(['admin','แอดมิน','แอดมิน']);
  const vu=U.viewAs?SYS.users.find(u=>u.id===U.viewAs):null;
  return `<header class="appbar"><div class="wrap">${brand()}
    <nav class="tabs" aria-label="เมนูหลัก">${tabs.map(t=>`<button class="tab" aria-selected="${U.tab===t[0]}" data-act="tab" data-a="${t[0]}"><svg class="ti" viewBox="0 0 24 24" aria-hidden="true">${IC[t[0]]}</svg><span class="full">${t[1]}</span><span class="short">${t[2]}</span></button>`).join('')}</nav>
    <button class="me" aria-pressed="${U.tab==='account'}" data-act="tab" data-a="account"><span class="av">${esc((ME.name||ME.username)[0].toUpperCase())}</span><span class="sm">${esc(ME.name)}</span></button></div>
    ${vu?`<div class="banner"><div class="wrap"><span>กำลังจัดการข้อมูลของ <b>${esc(vu.name)}</b> (@${esc(vu.username)}) ในฐานะแอดมิน</span><button class="btn ghost s" data-act="exitView">กลับสู่ข้อมูลของฉัน</button></div></div>`:''}</header>
  <div class="wrap page" id="view"></div>`;
}

/* ================= DAILY ================= */
function viewDaily(){
  const d=D.sel,[y,m,dd]=d.split('-').map(Number),dt=parse(d),list=txOn(d);
  const ts=todayStr(),yrs=Array.from({length:9},(_,i)=>2025+i);if(!yrs.includes(YEAR))yrs.push(YEAR);yrs.sort();
  const fq=freqTx();U.freq=fq;
  const quickHtml=fq.length?`<div><div class="lbl">ใช้บ่อย · แตะเพื่อเพิ่มทันที</div><div class="chips">${fq.map((t,i)=>`<button class="chip" style="--c:${t.type==='in'?'var(--inc)':'var(--exp)'}" data-act="quickTx" data-a="${i}">${esc(catOf(t).n)} ${money2(t.amount)}${t.note?' · '+esc(t.note):''}</button>`).join('')}</div></div>`:'';
  const ti=totIn(list),te=totOut(list),cats=U.dTx.type==='in'?CFG.inc:CFG.exp;
  if(!cats.some(c=>c.k===U.dTx.cat))U.dTx.cat=cats[0].k;
  const prefix=`${y}-${pad(m)}-`,mt=D.tx.filter(t=>t.date.startsWith(prefix)),mi=totIn(mt),me=totOut(mt);
  const idx={};mt.forEach(t=>{(idx[t.date]??={})[t.type]=1});
  const first=new Date(y,m-1,1).getDay(),n=new Date(y,m,0).getDate();
  let cells=TH_DS.map(x=>`<div class="h">${x}</div>`).join('');
  for(let i=0;i<first;i++)cells+='<span></span>';
  for(let k=1;k<=n;k++){const ds=ymd(y,m,k),x=idx[ds]||{};
    cells+=`<button class="cd ${ds===d?'sel':''}" data-act="pick" data-a="${ds}" aria-label="วันที่ ${k} ${TH_M[m-1]}"><span>${k}</span><span class="dots">${x.in?'<i style="background:var(--inc)"></i>':''}${x.out?'<i style="background:var(--exp)"></i>':''}</span></button>`;}
  const byCat={};mt.filter(t=>t.type==='out').forEach(t=>byCat[t.cat]=(byCat[t.cat]||0)+t.amount);
  const top=Object.entries(byCat).sort((a,b)=>b[1]-a[1])[0];
  const rows=list.map(t=>{const c=catOf(t),col=t.type==='in'?'var(--inc)':'var(--exp)';
    return `<div class="row"><span class="dot" style="background:${col}"></span>
      <div class="grow"><b style="font-weight:500">${esc(c.n)}</b><div class="mut sm">${esc(t.note)||(t.type==='in'?'รายรับ':'รายจ่าย')}</div></div>
      <div class="amt" style="color:${col}">${t.type==='in'?'+':'−'}${money2(t.amount)}</div>
      <button class="lnk" data-act="edit" data-a="${t.id}">${U.edit===t.id?'ปิด':'เปลี่ยนประเภท'}</button>
      <button class="x" data-act="delTx" data-a="${t.id}" aria-label="ลบรายการ">✕</button></div>${U.edit===t.id?editPanel(t):''}`}).join('');
  return `
  <div class="card"><div class="datebar">
    <button class="nb" data-act="day" data-a="-1" ${d<=MIN?'disabled':''} aria-label="วันก่อนหน้า">‹</button>
    <div class="dtxt"><div class="big">${dd} ${TH_M[m-1]} ${y}</div><div class="mut sm">วัน${TH_D[dt.getDay()]} · พ.ศ. ${y+543}</div></div>
    <button class="nb" data-act="day" data-a="1" ${d>=MAX?'disabled':''} aria-label="วันถัดไป">›</button>
    ${ts.startsWith(YEAR+'-')&&ts!==d?`<button class="btn ghost s" data-act="today">วันนี้</button>`:''}
    <select class="in" style="width:auto" data-change="year" aria-label="เลือกปี">${yrs.map(y=>`<option value="${y}" ${y===YEAR?'selected':''}>${y}</option>`).join('')}</select>
    <input class="in" type="date" min="${MIN}" max="${MAX}" value="${d}" data-change="date" aria-label="เลือกวันที่">
  </div><div class="months">${TH_M.map((x,i)=>`<button class="mp" aria-pressed="${i+1===m}" data-act="month" data-a="${i+1}">${TH_MS[i]}</button>`).join('')}</div></div>
  <div class="cols two">
   <div class="stack">
    <div class="card form"><h2 style="margin:0">เพิ่มรายการวันที่ ${dd} ${TH_MS[m-1]}</h2>${quickHtml}
      <div class="seg" role="group" aria-label="ชนิดรายการ">
        <button style="--c:var(--inc)" aria-pressed="${U.dTx.type==='in'}" data-act="txType" data-a="in">รายรับ</button>
        <button style="--c:var(--exp)" aria-pressed="${U.dTx.type==='out'}" data-act="txType" data-a="out">รายจ่าย</button></div>
      <div><div class="lbl">ประเภท</div><div class="chips">${cats.map(c=>`<button class="chip" style="--c:${U.dTx.type==='in'?'var(--inc)':'var(--exp)'}" aria-pressed="${U.dTx.cat===c.k}" data-act="txCat" data-a="${c.k}">${esc(c.n)}</button>`).join('')}</div></div>
      <label class="fld"><span>จำนวนเงิน (บาท)</span><input id="amt" class="in" type="number" inputmode="decimal" min="0" placeholder="0" value="${U.dTx.amount||''}" data-k="U.dTx.amount" data-enter="addTx"></label>
      <div class="chips">${[50,100,500,1000].map(v=>`<button class="chip" data-act="quick" data-a="${v}">+${money(v)}</button>`).join('')}<button class="chip" data-act="quick" data-a="clear">ล้าง</button></div>
      <label class="fld"><span>บันทึกช่วยจำ <small>ไม่บังคับ</small></span><input class="in" type="text" maxlength="60" placeholder="เช่น ข้าวกลางวัน" value="${esc(U.dTx.note)}" data-k="U.dTx.note" data-enter="addTx"></label>
      <button class="btn" data-act="addTx">เพิ่มรายการ</button></div>
    <div class="card"><div style="display:flex;justify-content:space-between;align-items:baseline;gap:8px;flex-wrap:wrap;margin-bottom:6px"><h2 style="margin:0">รายการของวันนี้ <span class="mut sm">(${list.length})</span></h2>
      <span class="sm"><b style="color:var(--inc)">+${money2(ti)}</b> &nbsp; <b style="color:var(--exp)">−${money2(te)}</b> &nbsp; <b>= ${money2(ti-te)}</b></span></div>
      ${rows||'<div class="empty">ยังไม่มีรายการในวันนี้<br>เพิ่มได้หลายรายการต่อวัน</div>'}</div>
   </div>
   <div class="stack">
    <div class="card"><h2>${TH_M[m-1]} ${y}</h2><div class="cal">${cells}</div>
      <div class="sm mut" style="margin-top:12px;display:flex;gap:14px"><span><i style="display:inline-block;width:8px;height:8px;border-radius:50%;background:var(--inc)"></i> มีรายรับ</span><span><i style="display:inline-block;width:8px;height:8px;border-radius:50%;background:var(--exp)"></i> มีรายจ่าย</span></div></div>
    <div class="card"><h2>สรุปเดือน${TH_M[m-1]}</h2>
      <div class="tr"><span>รายรับ</span><b style="color:var(--inc)">${money2(mi)}</b></div>
      <div class="tr"><span>รายจ่าย</span><b style="color:var(--exp)">${money2(me)}</b></div>
      <div class="tr"><span>คงเหลือ</span><b>${money2(mi-me)}</b></div>
      ${top?`<div class="tr"><span class="mut">จ่ายมากสุด</span><span>${esc(catOf({cat:top[0]}).n)} · ${money(top[1])}</span></div>`:''}</div>
   </div></div>`;
}
function editPanel(t){
  const cats=t.type==='in'?CFG.inc:CFG.exp;
  return `<div class="edit"><div class="seg"><button style="--c:var(--inc)" aria-pressed="${t.type==='in'}" data-act="setType" data-a="${t.id}" data-b="in">รายรับ</button><button style="--c:var(--exp)" aria-pressed="${t.type==='out'}" data-act="setType" data-a="${t.id}" data-b="out">รายจ่าย</button></div>
  <div class="chips">${cats.map(c=>`<button class="chip" style="--c:${t.type==='in'?'var(--inc)':'var(--exp)'}" aria-pressed="${t.cat===c.k}" data-act="setCat" data-a="${t.id}" data-b="${c.k}">${esc(c.n)}</button>`).join('')}</div></div>`;
}

/* ================= OVERVIEW ================= */
function viewOverview(){
  const TX=TXY(),I=totIn(TX),E=totOut(TX),saved=savedY(),invd=investedY();
  const mi=Array(12).fill(0),me=Array(12).fill(0);
  TX.forEach(t=>{(t.type==='in'?mi:me)[+t.date.slice(5,7)-1]+=t.amount});
  const byCat={};TX.filter(t=>t.type==='out').forEach(t=>byCat[t.cat]=(byCat[t.cat]||0)+t.amount);
  const items=Object.entries(byCat).map(([k,v])=>({label:catOf({cat:k}).n,value:v,color:expColor(k)})).sort((a,b)=>b.value-a.value);
  const empty=!D.tx.length&&!D.inv.length&&!D.sav.length;
  return `${empty?`<div class="card welcome"><div><b>เริ่มต้นได้เลย</b><div class="mut sm">ไปที่แท็บ “รายวัน” เพื่อจดรายการ หรือโหลดข้อมูลตัวอย่างมาดูหน้าตาก่อน</div></div><button class="btn ghost" data-act="sample">โหลดข้อมูลตัวอย่าง</button></div>`:''}
  <div class="band">
    <div class="stat"><div class="mut sm">รายรับปี ${YEAR}</div><div class="num" style="color:var(--inc)">${money(I)}</div></div>
    <div class="stat"><div class="mut sm">รายจ่ายปี ${YEAR}</div><div class="num" style="color:var(--exp)">${money(E)}</div></div>
    <div class="stat"><div class="mut sm">คงเหลือสุทธิ</div><div class="num">${money(I-E)}</div></div>
    <div class="stat"><div class="mut sm">ออม + ลงทุน</div><div class="num" style="color:var(--pri)">${money(saved+invd)}</div><div class="mut sm">${pct(saved+invd,I).toFixed(1)}% ของรายรับ</div></div></div>
  <div class="cols two">
    <div class="card"><h2>รายรับ–รายจ่ายรายเดือน</h2>${bars(mi,me)}
      <div class="sm mut" style="margin-top:8px;display:flex;gap:14px"><span style="color:var(--inc)">■ รายรับ</span><span style="color:var(--exp)">■ รายจ่าย</span></div></div>
    <div class="card"><h2>สัดส่วนรายจ่าย</h2>${items.length?donut(items,money(E),'บาททั้งปี')+legend(items.slice(0,7)):'<div class="empty">ยังไม่มีรายจ่าย</div>'}</div></div>
  <div class="card" style="margin-top:16px"><h2>แบ่งเงินรายรับ: ใช้จ่าย · ออม · ลงทุน</h2>
    <div class="chips" style="margin-bottom:16px">${PRESETS.map(p=>`<button class="chip" aria-pressed="${D.plan.save===p[1]&&D.plan.invest===p[2]}" data-act="preset" data-a="${p[1]}" data-b="${p[2]}">${p[0]} ${100-p[1]-p[2]}/${p[1]}/${p[2]}</button>`).join('')}</div>
    <div class="two-in" style="gap:20px">
      <label class="fld"><span>สัดส่วนออม: <b id="pvS">${D.plan.save}</b>%</span><input type="range" min="0" max="80" step="5" value="${D.plan.save}" data-k="D.plan.save" data-num="1"></label>
      <label class="fld"><span>สัดส่วนลงทุน: <b id="pvI">${D.plan.invest}</b>%</span><input type="range" min="0" max="80" step="5" value="${D.plan.invest}" data-k="D.plan.invest" data-num="1"></label></div>
    <div id="planOut" style="margin-top:18px"></div></div>`;
}
function renderPlanOut(){
  const el=$('#planOut');if(!el)return;
  const TX=TXY(),I=totIn(TX),E=totOut(TX),S=savedY(),V=investedY(),sp=100-D.plan.save-D.plan.invest;
  $('#pvS').textContent=D.plan.save;$('#pvI').textContent=D.plan.invest;
  const rows=[['ใช้จ่าย',sp,E,'var(--exp)',true],['เงินออม',D.plan.save,S,'var(--sav)'],['เงินลงทุน',D.plan.invest,V,'var(--inv)']];
  el.innerHTML=rows.map(r=>{const tg=I*r[1]/100,p=pct(r[2],tg),over=r[4]&&p>100;
    return `<div style="margin-bottom:14px"><div style="display:flex;justify-content:space-between;gap:8px;font-size:14px;margin-bottom:6px"><span><b style="font-weight:600">${r[0]}</b> <span class="mut">${r[1]}%</span></span>
    <span class="mut sm">${I>0?`${money(r[2])} จากเป้า ${money(tg)}${over?' · เกินเป้า':''}`:'ยังไม่มีรายรับ'}</span></div>
    <div class="bar" style="--c:${over?'var(--exp)':r[3]}"><i style="width:${Math.min(p,100)}%"></i></div></div>`}).join('')
  +(I>0?`<div class="note">เงินที่ยังไม่ได้จัดสรร: <b style="color:var(--ink)">${money(I-E-S-V)}</b> บาท (รายรับ − ใช้จ่าย − ออม − ลงทุน)</div>`:'');
}

/* ================= INVEST ================= */
function invStats(){
  const g={};CFG.assets.forEach(a=>g[a.k]={...a,cost:0,value:0,div:0});
  D.inv.forEach(i=>{const x=g[i.cat]||(g[i.cat]={...assetOf(i.cat),cost:0,value:0,div:0});x.cost+=i.cost;x.value+=i.value;x.div+=i.div||0});
  const cost=sum(D.inv,i=>i.cost),value=sum(D.inv,i=>i.value),div=sum(D.inv,i=>i.div||0),profit=value+div-cost;
  return {g,list:Object.values(g),cost,value,div,profit,roi:pct(profit,cost)};
}
const roiPill=r=>`<span class="pill ${r>=0?'pos':'neg'}">${r>=0?'+':''}${r.toFixed(2)}%</span>`;
function viewInvest(){
  const s=invStats(),f=U.dInv;
  if(!CFG.assets.some(a=>a.k===f.cat))f.cat=CFG.assets[0]?.k;
  const items=s.list.map(a=>({label:a.n,value:U.pie==='cost'?a.cost:a.value,color:a.c})).filter(i=>i.value>0).sort((a,b)=>b.value-a.value);
  const tot=sum(items,i=>i.value);
  const rows=[...D.inv].sort((a,b)=>b.date.localeCompare(a.date)).map(i=>{const a=assetOf(i.cat),p=i.value+(i.div||0)-i.cost;
    return `<div class="row" style="align-items:flex-start;flex-wrap:wrap"><span class="dot" style="background:${a.c};margin-top:8px"></span>
    <div class="grow"><b style="font-weight:500">${esc(i.name)||esc(a.n)}</b><div class="mut sm">${esc(a.n)} · ${+i.date.slice(8)} ${TH_MS[+i.date.slice(5,7)-1]} · ต้นทุน ${money(i.cost)}${i.div?` · ปันผล ${money(i.div)}`:''}</div></div>
    <div style="text-align:right"><div>${roiPill(pct(p,i.cost))}</div><div class="sm mut" style="margin-top:3px">${p>=0?'+':'−'}${money(Math.abs(p))}</div></div>
    <button class="x" data-act="delInv" data-a="${i.id}" aria-label="ลบ">✕</button>
    <label class="fld" style="width:100%;grid-template-columns:auto 1fr;align-items:center;gap:10px;padding-left:21px"><span class="mut sm" style="font-weight:400">มูลค่าปัจจุบัน</span><input class="in" style="min-height:36px;padding:6px 10px" type="number" min="0" inputmode="decimal" value="${i.value}" data-change="invval" data-id="${i.id}"></label></div>`}).join('');
  const perClass=s.list.filter(a=>a.cost>0).map(a=>{const p=a.value+a.div-a.cost;return `<div class="tr"><span><i style="display:inline-block;width:9px;height:9px;border-radius:3px;background:${a.c};margin-right:8px"></i>${esc(a.n)}</span><span>${money(a.value)} ${roiPill(pct(p,a.cost))}</span></div>`}).join('');
  return `
  <div class="band">
    <div class="stat"><div class="mut sm">เงินลงทุน (ต้นทุน)</div><div class="num">${money(s.cost)}</div></div>
    <div class="stat"><div class="mut sm">มูลค่าปัจจุบัน</div><div class="num" style="color:var(--inv)">${money(s.value)}</div></div>
    <div class="stat"><div class="mut sm">กำไร / ขาดทุน</div><div class="num" style="color:${s.profit>=0?'var(--inc)':'var(--exp)'}">${s.profit>=0?'+':'−'}${money(Math.abs(s.profit))}</div><div class="mut sm">รวมปันผลแล้ว ${money(s.div)}</div></div>
    <div class="stat"><div class="mut sm">ผลตอบแทนรวม</div><div class="num" style="color:${s.roi>=0?'var(--inc)':'var(--exp)'}">${s.roi>=0?'+':''}${s.roi.toFixed(2)}%</div></div></div>
  <div class="cols two">
   <div class="stack">
    <div class="card form"><h2 style="margin:0">เพิ่มเงินลงทุน</h2>
      <div><div class="lbl">ประเภทสินทรัพย์</div><div class="chips">${CFG.assets.map(a=>`<button class="chip" style="--c:${a.c}" aria-pressed="${f.cat===a.k}" data-act="invCat" data-a="${a.k}">${esc(a.n)}</button>`).join('')}</div></div>
      <label class="fld"><span>ชื่อ <small>ไม่บังคับ</small></span><input class="in" maxlength="40" placeholder="เช่น กองทุน SET50" value="${esc(f.name)}" data-k="U.dInv.name"></label>
      <div class="two-in">
        <label class="fld"><span>วันที่ลงทุน</span><input class="in" type="date" min="${MIN}" max="${MAX}" value="${f.date||D.sel}" data-k="U.dInv.date"></label>
        <label class="fld"><span>เงินลงทุน (บาท)</span><input class="in" type="number" inputmode="decimal" min="0" placeholder="0" value="${f.cost||''}" data-k="U.dInv.cost"></label>
        <label class="fld"><span>มูลค่าปัจจุบัน</span><input class="in" type="number" inputmode="decimal" min="0" placeholder="เท่าต้นทุน" value="${f.value||''}" data-k="U.dInv.value"></label>
        <label class="fld"><span>ปันผล/ดอกเบี้ยที่ได้</span><input class="in" type="number" inputmode="decimal" min="0" placeholder="0" value="${f.div||''}" data-k="U.dInv.div"></label></div>
      <button class="btn" data-act="addInv">เพิ่มเงินลงทุน</button></div>
    <div class="card"><h2>รายการลงทุน (${D.inv.length})</h2>${rows||'<div class="empty">ยังไม่มีรายการลงทุน</div>'}</div>
   </div>
   <div class="stack">
    <div class="card"><h2>ภาพรวมพอร์ต</h2>
      <div class="seg" style="margin-bottom:16px"><button aria-pressed="${U.pie==='cost'}" data-act="pie" data-a="cost">ตามต้นทุน</button><button aria-pressed="${U.pie==='value'}" data-act="pie" data-a="value">ตามมูลค่าปัจจุบัน</button></div>
      ${items.length?donut(items,money(tot),'บาท')+legend(items):'<div class="empty">เพิ่มรายการลงทุนเพื่อดูสัดส่วน</div>'}</div>
    ${perClass?`<div class="card"><h2>ผลตอบแทนแยกประเภท</h2>${perClass}</div>`:''}
    <div class="card"><h2>คาดการณ์การเติบโต</h2>
      <div class="two-in" style="margin-bottom:14px">
        <label class="fld"><span>เงินต้น (บาท)</span><input class="in" type="number" min="0" inputmode="decimal" placeholder="${money(s.value)}" value="${D.proj.p||''}" data-k="D.proj.p"><small>เว้นว่าง = ใช้มูลค่าพอร์ตปัจจุบัน</small></label>
        <label class="fld"><span>ลงทุนเพิ่มต่อเดือน</span><input class="in" type="number" min="0" inputmode="decimal" value="${D.proj.m}" data-k="D.proj.m"></label>
        <label class="fld"><span>ผลตอบแทนคาดหวัง (%/ปี)</span><input class="in" type="number" min="0" max="50" step="0.5" inputmode="decimal" value="${D.proj.r}" data-k="D.proj.r"></label>
        <label class="fld"><span>ระยะเวลา (ปี)</span><input class="in" type="number" min="1" max="40" inputmode="numeric" value="${D.proj.y}" data-k="D.proj.y"></label></div><div id="projOut"></div></div>
   </div></div>`;
}
function renderProj(){
  const el=$('#projOut');if(!el)return;
  const s=invStats(),p=D.proj.p>0?D.proj.p:s.value,m=D.proj.m||0,r=D.proj.r||0,y=Math.min(Math.max(Math.round(D.proj.y)||1,1),40);
  const mr=r/100/12;let b=p;const pts=[b],cont=[p];
  for(let i=1;i<=y*12;i++){b=b*(1+mr)+m;pts.push(b);cont.push(p+m*i)}
  const contrib=p+m*y*12;
  el.innerHTML=`<div class="mut sm">มูลค่าที่คาดว่าจะได้ใน ${y} ปี</div><div class="hero" style="color:var(--inv)">${money(b)} <span class="sm mut" style="font-weight:400">บาท</span></div>
  <div class="sm mut" style="margin:4px 0 12px">เงินที่ใส่ ${money(contrib)} · กำไรจากการลงทุน <b style="color:var(--inc)">${money(b-contrib)}</b></div>${lineChart(pts,cont)}
  <div class="sm mut" style="margin-top:6px"><span style="color:var(--inv)">━</span> มูลค่าพอร์ต &nbsp; ┅ เงินต้นสะสม &nbsp; (ทบต้นรายเดือน ไม่รวมภาษี/ค่าธรรมเนียม)</div>`;
}

/* ================= SAVE & GOALS ================= */
function goalSaved(id){return sum(D.sav.filter(s=>(s.goal||'')===id),s=>s.type==='in'?s.amount:-s.amount)}
function viewSave(){
  const f=U.dSav,total=savedTotal(),ref=parse(D.sel);
  const gi=D.goals.map((g,i)=>({label:g.name,value:Math.max(goalSaved(g.id),0),color:GOAL_COL[i%GOAL_COL.length]}));
  const gen=Math.max(goalSaved(''),0);if(gen>0)gi.push({label:'ออมทั่วไป',value:gen,color:'#8A94A6'});
  const items=gi.filter(x=>x.value>0);
  const goals=D.goals.map((g,i)=>{const sv=goalSaved(g.id),p=pct(sv,g.target),rem=Math.max(g.target-sv,0),dl=parse(g.date),col=GOAL_COL[i%GOAL_COL.length];
    const months=Math.max(1,Math.round((dl-ref)/(30.44*864e5)));
    const need=rem<=0?'ครบเป้าหมายแล้ว':dl<ref?'เลยกำหนดแล้ว':`ออมเดือนละ ~${money(rem/months)} บาท (อีก ${months} เดือน)`;
    return `<div class="goal"><div style="display:flex;justify-content:space-between;gap:8px"><b style="font-weight:600">${esc(g.name)}</b><button class="x" style="width:28px;height:28px" data-act="delGoal" data-a="${g.id}" aria-label="ลบเป้าหมาย">✕</button></div>
      <div class="bar" style="--c:${col};margin:8px 0"><i style="width:${Math.min(p,100)}%"></i></div>
      <div style="display:flex;justify-content:space-between;font-size:13.5px;gap:8px;flex-wrap:wrap"><span><b>${money(sv)}</b> <span class="mut">/ ${money(g.target)} (${p.toFixed(0)}%)</span></span><span class="mut">กำหนด ${+g.date.slice(8)} ${TH_MS[+g.date.slice(5,7)-1]} ${g.date.slice(0,4)}</span></div>
      <div class="sm mut" style="margin-top:3px">${need}</div></div>`}).join('');
  const recent=[...D.sav].sort((a,b)=>b.date.localeCompare(a.date)).slice(0,12).map(s=>{const g=D.goals.find(x=>x.id===s.goal);
    return `<div class="row"><div class="grow"><b style="font-weight:500">${g?esc(g.name):'ออมทั่วไป'}</b><div class="mut sm">${+s.date.slice(8)} ${TH_MS[+s.date.slice(5,7)-1]}${s.note?' · '+esc(s.note):''}</div></div>
    <div class="amt" style="color:${s.type==='in'?'var(--sav)':'var(--exp)'}">${s.type==='in'?'+':'−'}${money2(s.amount)}</div><button class="x" data-act="delSav" data-a="${s.id}" aria-label="ลบ">✕</button></div>`}).join('');
  return `
  <div class="band"><div class="stat"><div class="mut sm">เงินออมสะสม</div><div class="num" style="color:var(--sav)">${money(total)}</div></div>
   <div class="stat"><div class="mut sm">เป้าหมายทั้งหมด</div><div class="num">${D.goals.length}</div></div>
   <div class="stat"><div class="mut sm">เป้าหมายรวม</div><div class="num">${money(sum(D.goals,g=>g.target))}</div></div></div>
  <div class="cols two">
   <div class="stack">
    <div class="card form"><h2 style="margin:0">บันทึกเงินออม</h2>
      <div class="seg"><button style="--c:var(--sav)" aria-pressed="${f.type==='in'}" data-act="savType" data-a="in">ฝากเพิ่ม</button><button style="--c:var(--exp)" aria-pressed="${f.type==='out'}" data-act="savType" data-a="out">ถอนออก</button></div>
      <div><div class="lbl">แบ่งเข้าเป้าหมาย</div><div class="chips"><button class="chip" style="--c:#8A94A6" aria-pressed="${!f.goal}" data-act="savGoal" data-a="">ออมทั่วไป</button>
      ${D.goals.map((g,i)=>`<button class="chip" style="--c:${GOAL_COL[i%GOAL_COL.length]}" aria-pressed="${f.goal===g.id}" data-act="savGoal" data-a="${g.id}">${esc(g.name)}</button>`).join('')}</div></div>
      <div class="two-in"><label class="fld"><span>วันที่</span><input class="in" type="date" min="${MIN}" max="${MAX}" value="${f.date||D.sel}" data-k="U.dSav.date"></label>
      <label class="fld"><span>จำนวนเงิน (บาท)</span><input class="in" type="number" min="0" inputmode="decimal" placeholder="0" value="${f.amount||''}" data-k="U.dSav.amount"></label></div>
      <label class="fld"><span>บันทึก <small>ไม่บังคับ</small></span><input class="in" maxlength="50" value="${esc(f.note)}" data-k="U.dSav.note"></label>
      <button class="btn" data-act="addSav">บันทึกเงินออม</button></div>
    <div class="card"><h2>ประวัติล่าสุด</h2>${recent||'<div class="empty">ยังไม่มีรายการออม</div>'}</div>
   </div>
   <div class="stack">
    <div class="card"><h2>เป้าหมายการออม</h2>${goals||'<div class="empty">ยังไม่มีเป้าหมาย ตั้งเป้าหมายแรกด้านล่างได้เลย</div>'}</div>
    <div class="card form"><h2 style="margin:0">ตั้งเป้าหมายใหม่</h2>
      <div class="chips">${CFG.goals.map(n=>`<button class="chip" aria-pressed="${U.dGoal.name===n}" data-act="goalPreset" data-a="${esc(n)}">${esc(n)}</button>`).join('')}</div>
      <label class="fld"><span>ชื่อเป้าหมาย</span><input class="in" maxlength="40" value="${esc(U.dGoal.name)}" data-k="U.dGoal.name"></label>
      <div class="two-in"><label class="fld"><span>จำนวนเงินเป้าหมาย</span><input class="in" type="number" min="0" inputmode="decimal" value="${U.dGoal.target||''}" data-k="U.dGoal.target"></label>
      <label class="fld"><span>ต้องการภายใน</span><input class="in" type="date" min="${MIN}" value="${U.dGoal.date}" data-k="U.dGoal.date"></label></div>
      <button class="btn" data-act="addGoal">เพิ่มเป้าหมาย</button></div>
    <div class="card"><h2>สัดส่วนเงินออม</h2>${items.length?donut(items,money(sum(items,i=>i.value)),'บาท')+legend(items):'<div class="empty">ยังไม่มีเงินออม</div>'}</div>
   </div></div>`;
}

/* ================= TAX ================= */
const brk=()=>CFG.tax.br.map(b=>[b[0]==null?Infinity:b[0],b[1]/100]);
function taxOf(net){let prev=0,t=0;const sl=[];for(const [hi,r] of brk()){const a=Math.max(Math.min(net,hi)-prev,0);sl.push({lo:prev,hi,r,a,t:a*r});t+=a*r;prev=hi}return {t,sl}}
function calcTax(x){
  const c=CFG.tax,n=k=>Math.max(+x[k]||0,0),gross=n('i1')+n('i2')+n('i4'),expD=Math.min((n('i1')+n('i2'))*c.expRate/100,c.expCap);
  const personal=c.personal,spouse=x.spouse?60000:0,kids=n('kids')*30000+Math.min(n('kids2'),n('kids'))*30000,parents=Math.min(n('parents'),4)*30000,dis=n('disabled')*60000;
  const lifeH=Math.min(Math.min(n('life'),100000)+Math.min(n('health'),25000),100000),pH=Math.min(n('pHealth'),15000),sso=Math.min(n('sso'),9000),home=Math.min(n('home'),100000);
  const annuity=Math.min(n('annuity'),gross*.15,200000),pvd=Math.min(n('pvd'),n('i1')*.15,500000),rmf=Math.min(n('rmf'),gross*.3,500000),ssf=Math.min(n('ssf'),gross*.3,200000);
  const retire=Math.min(annuity+pvd+rmf+ssf,500000),esg=Math.min(n('esg'),gross*.3,300000);
  const list=[['ค่าลดหย่อนส่วนตัว',personal],['คู่สมรส',spouse],['บุตร',kids],['บิดามารดา',parents],['ผู้พิการ',dis],['ประกันชีวิต/สุขภาพ',lifeH],['ประกันสุขภาพบิดามารดา',pH],['ประกันสังคม',sso],['ดอกเบี้ยบ้าน',home],['กลุ่มเกษียณ (บำนาญ/PVD/RMF/SSF)',retire],['Thai ESG',esg]].filter(r=>r[1]>0);
  const ded=sum(list,r=>r[1]),pre=Math.max(gross-expD-ded,0),don=Math.min(n('donate'),pre*.1),net=Math.max(pre-don,0);
  if(don>0)list.push(['เงินบริจาค',don]);
  const {t,sl}=taxOf(net),mr=sl.filter(s=>s.a>0).pop()?.r??0;
  return {gross,expD,list,ded:ded+don,net,tax:t,sl,mr,retire,diff:t-n('withheld'),per10:t-taxOf(Math.max(net-10000,0)).t};
}
const TAXF=()=>[
 ['เงินได้ทั้งปี',[['i1','เงินเดือน / โบนัส (40(1))',`หักค่าใช้จ่าย ${CFG.tax.expRate}% รวมไม่เกิน ${money(CFG.tax.expCap)}`],['i2','ค่าจ้างอิสระ / ฟรีแลนซ์ (40(2))','รวมกับ 40(1) ในวงเงินหักค่าใช้จ่าย'],['i4','เงินได้อื่น ๆ','ดอกเบี้ย ปันผล ขายของ ฯลฯ (ไม่หักค่าใช้จ่ายเหมา)'],['withheld','ภาษีที่ถูกหัก ณ ที่จ่ายแล้ว','ดูจากหนังสือรับรอง 50 ทวิ']]],
 ['ครอบครัว',[['kids','จำนวนบุตร','คนละ 30,000'],['kids2','บุตรคนที่ 2 ขึ้นไป (เกิดตั้งแต่ 2561)','เพิ่มอีกคนละ 30,000'],['parents','บิดามารดาที่เลี้ยงดู','คนละ 30,000 สูงสุด 4 คน'],['disabled','ผู้พิการที่เลี้ยงดู','คนละ 60,000']]],
 ['ประกันและประกันสังคม',[['life','เบี้ยประกันชีวิต','สูงสุด 100,000'],['health','เบี้ยประกันสุขภาพ','สูงสุด 25,000 (รวมกับชีวิตไม่เกิน 100,000)'],['pHealth','ประกันสุขภาพบิดามารดา','สูงสุด 15,000'],['sso','เงินสมทบประกันสังคม','สูงสุด 9,000']]],
 ['ออมเพื่อเกษียณและกองทุน',[['annuity','ประกันชีวิตแบบบำนาญ','15% ของเงินได้ ไม่เกิน 200,000'],['pvd','กองทุนสำรองเลี้ยงชีพ','15% ของเงินเดือน ไม่เกิน 500,000'],['rmf','RMF','30% ของเงินได้ ไม่เกิน 500,000'],['ssf','SSF','30% ของเงินได้ ไม่เกิน 200,000'],['esg','Thai ESG*','30% ของเงินได้ ไม่เกิน 300,000']]],
 ['อื่น ๆ',[['home','ดอกเบี้ยเงินกู้ซื้อที่อยู่อาศัย','สูงสุด 100,000'],['donate','เงินบริจาค','ไม่เกิน 10% ของเงินได้สุทธิ']]]];
function viewTax(){
  return `<div class="cols tax" style="margin-top:0"><div class="stack">
   <div class="card"><div style="display:flex;justify-content:space-between;align-items:center;gap:10px;flex-wrap:wrap"><div><h2 style="margin:0">เงินได้ปีภาษี ${YEAR}</h2><div class="mut sm">ดึงยอดจากรายรับที่จดไว้ หรือกรอกเองก็ได้</div></div><button class="btn ghost" data-act="pullTax">ดึงจากรายรับ</button></div></div>
   ${TAXF().map((sec,si)=>`<div class="card form"><h2 style="margin:0">${sec[0]}</h2>
     ${si===1?`<div class="chips"><button class="chip" style="--c:var(--tax)" aria-pressed="${!!D.tax.spouse}" data-act="spouse">${D.tax.spouse?'✓':'+'} คู่สมรสไม่มีเงินได้ (60,000)</button></div>`:''}
     <div class="two-in">${sec[1].map(f=>`<label class="fld"><span>${f[1]}</span><input class="in" type="number" min="0" inputmode="decimal" placeholder="0" value="${D.tax[f[0]]||''}" data-k="D.tax.${f[0]}"><small>${f[2]}</small></label>`).join('')}</div></div>`).join('')}
   </div>
   <div class="stack sticky"><div class="card" id="taxOut"></div>
    <div class="note">คำนวณเพื่อประมาณการ อัตราและวงเงินตั้งค่าได้ที่หน้าแอดมิน กฎของปี 2027 อาจเปลี่ยน โดยเฉพาะมาตรการ Thai ESG* ยังไม่รวมภาษีขั้นต่ำ 0.5% ควรตรวจสอบกับกรมสรรพากรก่อนยื่นจริง</div></div></div>`;
}
function renderTaxOut(){
  const el=$('#taxOut');if(!el)return;const r=calcTax(D.tax),mx=Math.max(...r.sl.map(s=>s.a),1);
  el.innerHTML=`<div class="mut sm">ภาษีที่ต้องชำระทั้งปี</div><div class="hero" style="color:var(--tax)">${money(r.tax)} <span class="sm mut" style="font-weight:400">บาท</span></div>
  <div class="sm mut" style="margin:2px 0 14px">อัตราภาษีจริง ${pct(r.tax,r.gross).toFixed(2)}% ของเงินได้ · ขั้นสูงสุดของคุณ ${(r.mr*100).toFixed(0)}%</div>
  ${D.tax.withheld>0?`<div class="note" style="margin-bottom:14px;color:var(--ink)">${r.diff>0?`ต้องชำระเพิ่ม <b>${money(r.diff)}</b> บาท`:r.diff<0?`ขอคืนภาษีได้ประมาณ <b style="color:var(--inc)">${money(-r.diff)}</b> บาท`:'พอดีกับที่ถูกหักไว้'}</div>`:''}
  <div class="tr"><span>เงินได้รวม</span><b>${money(r.gross)}</b></div><div class="tr"><span>หักค่าใช้จ่าย</span><b>−${money(r.expD)}</b></div>
  <div class="tr"><span>หักลดหย่อนรวม</span><b>−${money(r.ded)}</b></div><div class="tr"><span><b>เงินได้สุทธิ</b></span><b>${money(r.net)}</b></div>
  <h2 style="margin:18px 0 8px;font-size:14px">ภาษีแต่ละขั้น</h2>
  ${r.sl.filter((s,i)=>s.a>0||i===0).map(s=>`<div style="margin-bottom:9px"><div style="display:flex;justify-content:space-between;font-size:13px"><span class="mut">${money(s.lo+(s.lo?1:0))}${s.hi===Infinity?'+':'–'+(s.hi===Infinity?'':money(s.hi))} · ${(s.r*100).toFixed(0)}%</span><span>${s.t>0?money(s.t):'ยกเว้น'}</span></div><div class="bar" style="--c:var(--tax)"><i style="width:${s.a/mx*100}%"></i></div></div>`).join('')}
  <h2 style="margin:18px 0 8px;font-size:14px">รายการลดหย่อนที่ใช้</h2>
  ${r.list.map(x=>`<div class="tr" style="font-size:13.5px"><span class="mut">${x[0]}</span><span>${money(x[1])}</span></div>`).join('')}
  ${r.gross>0&&r.mr>0?`<div class="note" style="margin-top:14px">เคล็ดลับ: ทุก 10,000 บาทที่ลดหย่อนเพิ่ม ประหยัดภาษีได้ประมาณ <b style="color:var(--ink)">${money(r.per10)}</b> บาท · วงเงินกลุ่มเกษียณใช้แล้ว ${money(r.retire)} จาก 500,000</div>`:''}`;
}

/* ================= ACCOUNT ================= */
function viewAccount(){
  const a=U.acc;
  return `<div class="cols two" style="margin-top:0"><div class="stack">
   <div class="card form"><h2 style="margin:0">บัญชีของฉัน</h2>
     <div class="tr"><span class="mut">ชื่อผู้ใช้</span><span>@${esc(ME.username)}</span></div>
     <div class="tr"><span class="mut">บทบาท</span><span>${ME.role==='admin'?'แอดมิน':'ผู้ใช้'}</span></div>
     <label class="fld"><span>ชื่อที่แสดง</span><input class="in" maxlength="30" value="${esc(a.name||ME.name)}" data-k="U.acc.name" data-enter="saveName"></label>
     <button class="btn ghost" style="width:fit-content" data-act="saveName">บันทึกชื่อ</button></div>
   <div class="card form"><h2 style="margin:0">เปลี่ยนรหัสผ่าน</h2>
     ${authFld('รหัสผ่านปัจจุบัน','U.acc.cur','password')}${authFld('รหัสผ่านใหม่ (อย่างน้อย 6 ตัว)','U.acc.pw','password','','savePw')}
     <div class="err" style="${a.msg?'color:var(--inc)':''}">${esc(a.err||a.msg)}</div>
     <button class="btn" data-act="savePw">เปลี่ยนรหัสผ่าน</button></div></div>
   <div class="stack"><div class="card"><h2>ออกจากระบบ</h2><button class="btn ghost" data-act="logout">ออกจากระบบ</button></div></div></div>`;
}

/* ================= ADMIN ================= */
function viewAdmin(){
  const tabs=[['users','ผู้ใช้'],['cats','หมวดหมู่'],['taxcfg','ภาษี'],['log','กิจกรรม'],['sys','ระบบและสำรองข้อมูล']];
  const body={users:admUsers,cats:admCats,taxcfg:admTax,log:admLog,sys:admSys}[U.adm]();
  return `<div class="subnav">${tabs.map(t=>`<button class="sn" aria-pressed="${U.adm===t[0]}" data-act="adm" data-a="${t[0]}">${t[1]}</button>`).join('')}</div>${body}`;
}
function admUsers(){
  const rows=SYS.users.map(u=>{const s=U.stats?.[u.id],me=u.id===ME.id;
    return `<div class="urow"><span class="av">${esc((u.name||u.username)[0].toUpperCase())}</span>
    <div class="grow"><div><b style="font-weight:600">${esc(u.name)}</b> <span class="mut sm">@${esc(u.username)}</span> <span class="pill ${u.role==='admin'?'pri':''}">${u.role==='admin'?'แอดมิน':'ผู้ใช้'}</span>${u.active?'':' <span class="pill neg">ปิดใช้งาน</span>'}</div>
    <div class="mut sm">${s?`${s.n} รายการ · รับ ${money(s.i)} · จ่าย ${money(s.e)} · ลงทุน ${s.v} รายการ`:'กำลังโหลดสถิติ…'} · เข้าล่าสุด ${fmtT(u.last)}</div></div>
    <div class="acts"><button class="btn ghost s" data-act="viewAs" data-a="${u.id}">จัดการข้อมูล</button>
      <button class="btn ghost s" data-act="resetPw" data-a="${u.id}">รีเซ็ตรหัส</button>
      <button class="btn ghost s" data-act="toggleRole" data-a="${u.id}" ${me?'disabled':''}>${u.role==='admin'?'ลดเป็นผู้ใช้':'เป็นแอดมิน'}</button>
      <button class="btn ghost s" data-act="toggleActive" data-a="${u.id}" ${me?'disabled':''}>${u.active?'ปิดใช้งาน':'เปิดใช้งาน'}</button>
      <button class="btn ghost s danger" data-act="delUser" data-a="${u.id}" ${me?'disabled':''}>${CFARM==='del:'+u.id?'ยืนยันลบ?':'ลบ'}</button></div></div>
    ${U.resetFor===u.id?`<div class="edit"><div class="two-in"><input class="in" type="password" placeholder="รหัสผ่านใหม่ (6 ตัวขึ้นไป)" value="${esc(U.resetPw)}" data-k="U.resetPw" data-enter="saveReset"><button class="btn" data-act="saveReset" data-a="${u.id}">ตั้งรหัสผ่านใหม่</button></div></div>`:''}`}).join('');
  return `<div class="card"><h2>ผู้ใช้ทั้งหมด (${SYS.users.length})</h2>${rows}</div>
  <div class="card form" style="margin-top:16px"><h2 style="margin:0">สร้างผู้ใช้ใหม่</h2>
   <div class="two-in">${authFld('ชื่อที่แสดง','U.nu.name')}${authFld('ชื่อผู้ใช้','U.nu.username','text','a-z 0-9 _ .')}</div>
   ${authFld('รหัสผ่านเริ่มต้น','U.nu.pw','password')}
   <div class="seg" style="max-width:260px"><button aria-pressed="${U.nu.role==='user'}" data-act="nuRole" data-a="user">ผู้ใช้</button><button aria-pressed="${U.nu.role==='admin'}" data-act="nuRole" data-a="admin">แอดมิน</button></div>
   <div class="err">${esc(U.nu.err)}</div><button class="btn" style="width:fit-content" data-act="createUser">สร้างผู้ใช้</button></div>`;
}
function catCard(title,l,hint){
  const list=CFG[l];
  return `<div class="card"><h2>${title}</h2>${list.map((c,i)=>{const nm=typeof c==='string'?c:c.n;return `<div class="cfgrow"><input class="in" maxlength="30" value="${esc(nm)}" data-change="catName" data-l="${l}" data-i="${i}" aria-label="ชื่อ"><button class="x" data-act="delCat" data-a="${l}" data-b="${i}" aria-label="ลบ">✕</button></div>`}).join('')}
  <div class="cfgrow" style="margin-top:12px"><input class="in" id="new-${l}" maxlength="30" placeholder="เพิ่มรายการใหม่" data-enter="addCat" data-l="${l}"><button class="btn ghost" data-act="addCat" data-a="${l}">เพิ่ม</button></div>
  ${hint?`<div class="mut sm">${hint}</div>`:''}</div>`;
}
function admCats(){
  return `<div class="note" style="margin-bottom:16px">การเปลี่ยนชื่อมีผลกับผู้ใช้ทุกคนทันที ข้อมูลเดิมที่ผูกกับหมวดที่ถูกลบจะแสดงเป็น “ไม่ระบุหมวด”</div>
  <div class="cols two" style="margin-top:0"><div class="stack">${catCard('หมวดรายรับ','inc')}${catCard('หมวดรายจ่าย','exp')}</div>
  <div class="stack">${catCard('ประเภทสินทรัพย์ลงทุน','assets')}${catCard('ชื่อเป้าหมายแนะนำ','goals')}</div></div>`;
}
function admTax(){
  const c=CFG.tax;
  return `<div class="cols two" style="margin-top:0"><div class="card form"><h2 style="margin:0">ตัวแปรภาษีเงินได้บุคคลธรรมดา</h2>
   <div class="two-in"><label class="fld"><span>ลดหย่อนส่วนตัว (บาท)</span><input class="in" type="number" min="0" value="${c.personal}" data-change="taxcfg" data-f="personal"></label>
   <label class="fld"><span>หักค่าใช้จ่ายเหมา (%)</span><input class="in" type="number" min="0" max="100" value="${c.expRate}" data-change="taxcfg" data-f="expRate"></label>
   <label class="fld"><span>เพดานค่าใช้จ่ายเหมา (บาท)</span><input class="in" type="number" min="0" value="${c.expCap}" data-change="taxcfg" data-f="expCap"></label></div>
   <button class="btn ghost" style="width:fit-content" data-act="taxReset">คืนค่าเริ่มต้น</button></div>
  <div class="card"><h2>ขั้นอัตราภาษี</h2>
   <div class="cfgrow sm mut"><span style="flex:1">เงินได้สุทธิสูงสุดของขั้น (บาท)</span><span style="width:100px">อัตรา (%)</span></div>
   ${c.br.map((b,i)=>`<div class="cfgrow"><input class="in" type="number" min="0" ${b[0]==null?'disabled placeholder="ไม่จำกัด"':`value="${b[0]}"`} data-change="taxbr" data-i="${i}" data-f="0"><input class="in" style="width:100px" type="number" min="0" max="100" value="${b[1]}" data-change="taxbr" data-i="${i}" data-f="1"></div>`).join('')}</div></div>`;
}
function admLog(){
  return `<div class="card"><h2>กิจกรรมล่าสุด</h2>${SYS.log.length?SYS.log.slice(0,80).map(l=>`<div class="logrow"><time>${fmtT(l.t)}</time><span><b style="font-weight:500">@${esc(l.who)}</b> ${esc(l.a)}</span></div>`).join(''):'<div class="empty">ยังไม่มีกิจกรรม</div>'}</div>`;
}
function admSys(){
  return `<div class="cols two" style="margin-top:0"><div class="stack"><div class="card form"><h2 style="margin:0">ตั้งค่าระบบ</h2>
    <label class="fld"><span>ชื่อแอป</span><input class="in" maxlength="24" value="${esc(CFG.appName)}" data-change="appName"></label>
    <div class="chips"><button class="chip" aria-pressed="${CFG.allowReg}" data-act="toggleReg">${CFG.allowReg?'✓':'+'} เปิดให้สมัครสมาชิกเอง</button></div></div>
   <div class="note"><b style="color:var(--ink)">เรื่องความปลอดภัย</b><br>ระบบบัญชีนี้ทำงานฝั่งเบราว์เซอร์ รหัสผ่านถูกเข้ารหัสแบบแฮชก่อนเก็บ แต่ข้อมูลทั้งหมดอยู่ในที่เก็บข้อมูลของแอปนี้ ไม่ใช่เซิร์ฟเวอร์จริง ผู้ที่เข้าถึงที่เก็บข้อมูลได้ในทางเทคนิคอาจอ่านข้อมูลได้ เหมาะกับใช้ในครอบครัวหรือทีมเล็ก หากต้องการความปลอดภัยระดับใช้งานจริง ต้องมีเซิร์ฟเวอร์และฐานข้อมูลแยกต่างหาก</div></div>
   <div class="stack"><div class="card form"><h2 style="margin:0">สำรองและกู้คืนข้อมูล</h2>
    <button class="btn ghost" style="width:fit-content" data-act="makeBackup">สร้างข้อมูลสำรอง</button>
    ${U.backup?`<textarea class="in" readonly onclick="this.select()">${esc(U.backup)}</textarea><div class="mut sm">แตะข้อความเพื่อเลือกทั้งหมด แล้วคัดลอกไปเก็บไว้ (มีแฮชรหัสผ่านอยู่ด้วย เก็บให้ปลอดภัย)</div>`:''}
    <label class="fld"><span>วางข้อมูลสำรองเพื่อกู้คืน</span><textarea class="in" data-k="U.imp" placeholder="วาง JSON ที่นี่">${esc(U.imp)}</textarea></label>
    <button class="btn ghost danger" style="width:fit-content" data-act="importBackup">${CFARM==='imp'?'ยืนยัน: แทนที่ข้อมูลทั้งหมด?':'กู้คืนข้อมูล'}</button></div></div></div>`;
}

/* ================= sample data & helpers ================= */
function pullTax(silent){
  const s=c=>sum(TXY().filter(t=>t.type==='in'&&c.includes(t.cat)),t=>t.amount),all=totIn(TXY());
  D.tax.i1=s(['salary','bonus']);D.tax.i2=s(['free']);D.tax.i4=all-D.tax.i1-D.tax.i2;
  if(silent!==true){save();render();toast('ดึงเงินได้จากรายรับแล้ว')}
}
function sample(){
  let s=11;const r=()=>(s=(s*16807)%2147483647)/2147483647,ri=(a,b)=>Math.round(a+r()*(b-a));
  D.tx=[];D.inv=[];D.sav=[];const g=[uid(),uid(),uid()];
  D.goals=[{id:g[0],name:'กองทุนฉุกเฉิน',target:150000,date:YEAR+'-12-31'},{id:g[1],name:'ท่องเที่ยว',target:60000,date:YEAR+'-10-31'},{id:g[2],name:'ดาวน์บ้าน',target:500000,date:(YEAR+2)+'-12-31'}];
  const T=(date,type,cat,amount,note='')=>D.tx.push({id:uid(),date,type,cat,amount,note});
  for(let m=1;m<=12;m++){const n=new Date(YEAR,m,0).getDate(),dt=d=>ymd(YEAR,m,d);
    T(dt(25),'in','salary',38000,'เงินเดือน');if(m===3)T(dt(28),'in','bonus',40000,'โบนัสประจำปี');
    if(r()<.6)T(dt(ri(8,20)),'in','free',ri(3000,8000),'งานเสริม');if(m===6||m===12)T(dt(30),'in','div',2500,'ปันผล');
    T(dt(1),'out','home',8500,'ค่าเช่า');T(dt(5),'out','bills',ri(1500,2100),'น้ำ ไฟ เน็ต');T(dt(10),'out','debt',3200,'ผ่อนชำระ');
    for(let d=1;d<=n;d++){if(r()<.9)T(dt(d),'out','food',ri(60,180),'ข้าวเที่ยง');if(r()<.5)T(dt(d),'out','food',ri(80,350),'มื้อเย็น');if(r()<.5)T(dt(d),'out','travel',ri(40,150));if(r()<.08)T(dt(d),'out','shop',ri(300,1500));if(r()<.06)T(dt(d),'out','fun',ri(200,900));if(r()<.03)T(dt(d),'out','health',ri(200,800));}
    D.sav.push({id:uid(),date:dt(26),type:'in',goal:g[0],amount:5000,note:''},{id:uid(),date:dt(26),type:'in',goal:g[2],amount:4000,note:''});
    if(m<=8)D.sav.push({id:uid(),date:dt(26),type:'in',goal:g[1],amount:3000,note:''});}
  [['fund','กองทุนดัชนี SET50',YEAR+'-01-26',30000,33200,0],['gstock','S&P 500 ETF',YEAR+'-02-26',60000,68900,0],['gold','ทองคำแท่ง',YEAR+'-03-10',40000,44100,0],['thstock','หุ้นปันผล',YEAR+'-04-15',35000,33700,1800],['bond','พันธบัตรออมทรัพย์',YEAR+'-05-05',50000,51500,0],['crypto','Bitcoin',YEAR+'-06-20',15000,19300,0],['reit','กองรีท',YEAR+'-07-12',25000,25900,600]]
   .forEach(a=>D.inv.push({id:uid(),cat:a[0],name:a[1],date:a[2],cost:a[3],value:a[4],div:a[5]}));
  D.sel=YEAR+'-01-26';D.tax.sso=9000;D.tax.life=20000;D.tax.rmf=30000;pullTax(true);D.tax.withheld=Math.round(calcTax(D.tax).tax*.8);
  save();render();toast('โหลดข้อมูลตัวอย่างแล้ว');
}
async function loadStats(){
  const out={};
  for(const u of SYS.users){const d=await st.get('mb:data:'+u.id,SHARED)||{};out[u.id]={n:(d.tx||[]).length,i:totIn(d.tx||[]),e:totOut(d.tx||[]),v:(d.inv||[]).length}}
  U.stats=out;if(U.tab==='admin'&&U.adm==='users')render();
}
const activeAdmins=()=>SYS.users.filter(u=>u.role==='admin'&&u.active).length;

/* ================= actions ================= */
function setSel(s){D.sel=clampD(s);save();render()}
const ACT={
 /* auth */
 login:()=>doLogin(), setup:()=>doSetup(), register:()=>doRegister(), logout:()=>doLogout(),
 legacy:()=>{U.auth.legacy=!U.auth.legacy;render()},
 authMode:a=>{U.auth={...U.auth,mode:a,err:'',p:'',p2:''};render()},
 /* nav */
 tab:a=>{U.tab=a;if(a==='admin'){U.stats=null;loadStats()}render();window.scrollTo?.({top:0})},
 adm:a=>{U.adm=a;if(a==='users')loadStats();render()},
 /* daily */
 day:a=>setSel(addDays(D.sel,+a)), pick:a=>setSel(a), today:()=>setSel(todayStr()),
 quickTx:a=>{const t=U.freq?.[+a];if(!t)return;D.tx.push({id:uid(),date:D.sel,type:t.type,cat:t.cat,amount:t.amount,note:t.note||''});save();render();toast('เพิ่มรายการแล้ว')},
 month:a=>{const [,,d]=D.sel.split('-').map(Number),n=new Date(YEAR,+a,0).getDate();setSel(ymd(YEAR,+a,Math.min(d,n)))},
 txType:a=>{U.dTx.type=a;U.dTx.cat=(a==='in'?CFG.inc:CFG.exp)[0].k;render()},
 txCat:a=>{U.dTx.cat=a;render()},
 quick:a=>{U.dTx.amount=a==='clear'?'':(+U.dTx.amount||0)+ +a;render()},
 addTx:()=>{const a=+U.dTx.amount;if(!(a>0))return toast('ใส่จำนวนเงินก่อนนะ');
   D.tx.push({id:uid(),date:D.sel,type:U.dTx.type,cat:U.dTx.cat,amount:a,note:U.dTx.note.trim()});U.dTx.amount='';U.dTx.note='';save();render();toast('เพิ่มรายการแล้ว');$('#amt')?.focus({preventScroll:true})},
 delTx:a=>{D.tx=D.tx.filter(t=>t.id!==a);save();render();toast('ลบรายการแล้ว')},
 edit:a=>{U.edit=U.edit===a?null:a;render()},
 setType:(a,b)=>{const t=D.tx.find(x=>x.id===a);if(!t)return;t.type=b;const l=b==='in'?CFG.inc:CFG.exp;if(!l.some(c=>c.k===t.cat))t.cat=l[0].k;save();render()},
 setCat:(a,b)=>{const t=D.tx.find(x=>x.id===a);if(t){t.cat=b;save();render()}},
 /* invest */
 invCat:a=>{U.dInv.cat=a;render()},
 addInv:()=>{const f=U.dInv,c=+f.cost;if(!(c>0))return toast('ใส่จำนวนเงินลงทุนก่อนนะ');
   D.inv.push({id:uid(),cat:f.cat,name:f.name.trim(),date:clampD(f.date||D.sel),cost:c,value:f.value>0?+f.value:c,div:+f.div||0});
   Object.assign(U.dInv,{name:'',cost:'',value:'',div:''});save();render();toast('เพิ่มเงินลงทุนแล้ว')},
 delInv:a=>{D.inv=D.inv.filter(i=>i.id!==a);save();render()},
 pie:a=>{U.pie=a;render()},
 /* savings */
 savType:a=>{U.dSav.type=a;render()}, savGoal:a=>{U.dSav.goal=a;render()},
 addSav:()=>{const f=U.dSav,a=+f.amount;if(!(a>0))return toast('ใส่จำนวนเงินก่อนนะ');
   D.sav.push({id:uid(),date:clampD(f.date||D.sel),type:f.type,goal:f.goal,amount:a,note:f.note.trim()});f.amount='';f.note='';save();render();toast(f.type==='in'?'บันทึกเงินออมแล้ว':'บันทึกการถอนแล้ว')},
 delSav:a=>{D.sav=D.sav.filter(s=>s.id!==a);save();render()},
 goalPreset:a=>{U.dGoal.name=a;render()},
 addGoal:()=>{const f=U.dGoal;if(!f.name.trim()||!(+f.target>0))return toast('ใส่ชื่อและจำนวนเงินเป้าหมายก่อนนะ');
   D.goals.push({id:uid(),name:f.name.trim(),target:+f.target,date:f.date||MAX});Object.assign(f,{name:'',target:''});save();render();toast('เพิ่มเป้าหมายแล้ว')},
 delGoal:a=>{D.goals=D.goals.filter(g=>g.id!==a);D.sav.forEach(s=>{if(s.goal===a)s.goal=''});save();render()},
 preset:(a,b)=>{D.plan.save=+a;D.plan.invest=+b;save();render()},
 spouse:()=>{D.tax.spouse=D.tax.spouse?0:1;save();render()}, pullTax:()=>pullTax(), sample:()=>sample(),
 resetAll:()=>{if(!confirm2('reset'))return;Object.assign(D,defaults());save();render();toast('ล้างข้อมูลแล้ว')},
 /* account */
 saveName:async()=>{const n=(U.acc.name||ME.name).trim();if(!n)return;await mutate(()=>{const u=SYS.users.find(x=>x.id===ME.id);u.name=n});U.acc.name='';render();toast('บันทึกชื่อแล้ว')},
 savePw:async()=>{const a=U.acc;a.msg='';a.err='';
   if(await hashPw(a.cur,ME.salt)!==ME.hash){a.err='รหัสผ่านปัจจุบันไม่ถูกต้อง';return render()}
   if(a.pw.length<6){a.err='รหัสผ่านใหม่ต้องยาวอย่างน้อย 6 ตัวอักษร';return render()}
   const salt=newSalt(),hash=await hashPw(a.pw,salt);
   await mutate(()=>{const u=SYS.users.find(x=>x.id===ME.id);u.salt=salt;u.hash=hash});await log('เปลี่ยนรหัสผ่านของตนเอง');
   U.acc={name:'',cur:'',pw:'',msg:'เปลี่ยนรหัสผ่านแล้ว',err:''};render()},
 /* admin: users */
 nuRole:a=>{U.nu.role=a;render()},
 createUser:async()=>{const n=U.nu,uname=n.username.trim().toLowerCase();await refreshSys();
   if(!n.name.trim()){n.err='ใส่ชื่อที่แสดงก่อนนะ';return render()}
   const e=checkNew(uname,n.pw,null);if(e){n.err=e;return render()}
   const u=await makeUser({username:uname,name:n.name.trim(),pw:n.pw,role:n.role});
   await mutate(()=>{SYS.users.push(u)});await log(`สร้างผู้ใช้ @${uname}`);U.nu={name:'',username:'',pw:'',role:'user',err:''};loadStats();render();toast('สร้างผู้ใช้แล้ว')},
 resetPw:a=>{U.resetFor=U.resetFor===a?null:a;U.resetPw='';render()},
 saveReset:async a=>{a=a||U.resetFor;if(U.resetPw.length<6)return toast('รหัสผ่านต้องยาวอย่างน้อย 6 ตัวอักษร');
   const salt=newSalt(),hash=await hashPw(U.resetPw,salt);let nm='';
   await mutate(()=>{const u=SYS.users.find(x=>x.id===a);if(!u)return false;u.salt=salt;u.hash=hash;nm=u.username});
   await log(`รีเซ็ตรหัสผ่านของ @${nm}`);U.resetFor=null;U.resetPw='';render();toast('ตั้งรหัสผ่านใหม่แล้ว')},
 toggleRole:async a=>{let ok=true;await mutate(()=>{const u=SYS.users.find(x=>x.id===a);if(!u)return false;
   if(u.role==='admin'&&activeAdmins()<=1){ok=false;return false}u.role=u.role==='admin'?'user':'admin'});
   if(!ok)toast('ต้องมีแอดมินอย่างน้อย 1 คน');else await log('เปลี่ยนบทบาทผู้ใช้');render()},
 toggleActive:async a=>{let ok=true;await mutate(()=>{const u=SYS.users.find(x=>x.id===a);if(!u)return false;
   if(u.active&&u.role==='admin'&&activeAdmins()<=1){ok=false;return false}u.active=!u.active});
   if(!ok)toast('ต้องมีแอดมินที่ใช้งานอยู่อย่างน้อย 1 คน');else await log('เปลี่ยนสถานะผู้ใช้');render()},
 delUser:async a=>{if(a===ME.id)return;if(!confirm2('del:'+a))return;let nm='',ok=true;
   await mutate(()=>{const u=SYS.users.find(x=>x.id===a);if(!u)return false;if(u.role==='admin'&&activeAdmins()<=1){ok=false;return false}nm=u.username;SYS.users=SYS.users.filter(x=>x.id!==a)});
   if(!ok)return toast('ลบแอดมินคนสุดท้ายไม่ได้');await st.del('mb:data:'+a,SHARED);await log(`ลบผู้ใช้ @${nm}`);loadStats();render();toast('ลบผู้ใช้แล้ว')},
 viewAs:async a=>{await flush();U.viewAs=a===ME.id?null:a;await loadData(a);U.tab='daily';await log('เข้าจัดการข้อมูลของผู้ใช้');render()},
 exitView:async()=>{await flush();U.viewAs=null;await loadData(ME.id);U.tab='admin';U.stats=null;loadStats();render()},
 /* admin: categories & config */
 addCat:async(a,b,el)=>{const l=a||el?.dataset.l,inp=$('#new-'+l),v=(inp?.value||'').trim();if(!v)return;
   await mutate(()=>{const arr=CFG[l];if(l==='goals')arr.push(v);else if(l==='assets')arr.push({k:'a'+uid(),n:v,c:PAL[arr.length%PAL.length]});else arr.push({k:'c'+uid(),n:v})});render();toast('เพิ่มแล้ว')},
 delCat:async(a,b)=>{let ok=true;await mutate(()=>{if(CFG[a].length<=1){ok=false;return false}CFG[a].splice(+b,1)});if(!ok)toast('ต้องเหลืออย่างน้อย 1 รายการ');render()},
 taxReset:async()=>{await mutate(()=>{CFG.tax=DEF_CFG().tax});render();toast('คืนค่าเริ่มต้นแล้ว')},
 toggleReg:async()=>{await mutate(()=>{CFG.allowReg=!CFG.allowReg});render()},
 makeBackup:async()=>{await flush();const data={};for(const u of SYS.users)data[u.id]=await st.get('mb:data:'+u.id,SHARED);
   U.backup=JSON.stringify({v:1,sys:{users:SYS.users,cfg:CFG},data});render()},
 importBackup:async()=>{if(!confirm2('imp'))return;let o;try{o=JSON.parse(U.imp)}catch(e){return toast('รูปแบบข้อมูลไม่ถูกต้อง')}
   if(!o?.sys?.users?.length||!o.data)return toast('ไม่พบข้อมูลสำรองที่ใช้ได้');
   SYS.users=o.sys.users;CFG=mergeCfg(o.sys.cfg);await saveSys();for(const id of Object.keys(o.data))if(o.data[id])await st.set('mb:data:'+id,o.data[id],SHARED);
   const me=SYS.users.find(u=>u.id===ME.id&&u.active);U.imp='';U.backup='';
   if(!me){toast('กู้คืนแล้ว กรุณาเข้าสู่ระบบใหม่');return doLogout()}ME=me;await loadData(U.viewAs||me.id);await log('กู้คืนข้อมูลสำรอง');render();toast('กู้คืนข้อมูลแล้ว')}
};
const CHG={
 date:el=>{if(el.value)setSel(el.value)},
 year:el=>{const y=+el.value;if(!y)return;const [,m,d]=D.sel.split('-').map(Number);setYear(y);D.year=y;D.sel=ymd(y,m,Math.min(d,new Date(y,m,0).getDate()));U.dGoal.date=MAX;U.dInv.date='';U.dSav.date='';save();render()},
 invval:el=>{const i=D.inv.find(x=>x.id===el.dataset.id);if(i){i.value=Math.max(+el.value||0,0);save();render()}},
 catName:async el=>{const l=el.dataset.l,i=+el.dataset.i,v=el.value.trim();if(!v)return render();
   await mutate(()=>{const c=CFG[l][i];if(typeof c==='string')CFG[l][i]=v;else c.n=v});toast('บันทึกแล้ว')},
 appName:async el=>{const v=el.value.trim();if(!v)return;await mutate(()=>{CFG.appName=v});render()},
 taxcfg:async el=>{const f=el.dataset.f;await mutate(()=>{CFG.tax[f]=Math.max(+el.value||0,0)});toast('บันทึกแล้ว')},
 taxbr:async el=>{const i=+el.dataset.i,f=+el.dataset.f,v=Math.max(+el.value||0,0);let bad=false;
   await mutate(()=>{const br=CFG.tax.br.map(b=>b.slice());br[i][f]=v;
     for(let k=1;k<br.length-1;k++)if(br[k][0]<=br[k-1][0])bad=true;
     if(bad)return false;CFG.tax.br=br});
   if(bad){toast('ขีดจำกัดของขั้นต้องเรียงจากน้อยไปมาก');render()}else toast('บันทึกแล้ว')}
};
document.addEventListener('click',e=>{const b=e.target.closest('[data-act]');if(!b)return;ARMED=CFARM;CFARM=null;const r=ACT[b.dataset.act]?.(b.dataset.a,b.dataset.b,b);r&&r.catch?.(err=>console.error(err))});
document.addEventListener('change',e=>{const el=e.target;if(el.dataset.change)CHG[el.dataset.change]?.(el)});
document.addEventListener('keydown',e=>{const el=e.target;if(e.key==='Enter'&&el.dataset?.enter&&el.tagName==='INPUT'){e.preventDefault();ARMED=null;ACT[el.dataset.enter]?.(el.dataset.a,el.dataset.b,el)}});
document.addEventListener('input',e=>{
  const el=e.target,k=el.dataset.k;if(!k)return;
  setPath(k,(el.type==='number'||el.dataset.num)?(el.value===''?'':parseFloat(el.value)):el.value);
  if(k.startsWith('D.tax')){const f=k.split('.')[2];D.tax[f]=+D.tax[f]||0;renderTaxOut();save()}
  else if(k.startsWith('D.proj')){renderProj();save()}
  else if(k.startsWith('D.plan')){const key=k.split('.')[2],o=key==='save'?'invest':'save';
    if(D.plan.save+D.plan.invest>100){D.plan[o]=100-D.plan[key];const oe=document.querySelector(`[data-k="D.plan.${o}"]`);if(oe)oe.value=D.plan[o]}
    renderPlanOut();save()}
  else if(k.startsWith('U.auth'))U.auth.err='';
});

/* ================= render ================= */
function render(){
  const root=$('#root');
  if(!READY){root.innerHTML='<div class="auth"><div class="mut">กำลังโหลด…</div></div>';return}
  if(!SYS.users.length){root.innerHTML=viewSetup();return}
  if(!ME){root.innerHTML=viewLogin();return}
  if(U.tab==='admin'&&ME.role!=='admin')U.tab='overview';
  root.innerHTML=shell();
  $('#view').innerHTML=({overview:viewOverview,daily:viewDaily,invest:viewInvest,save:viewSave,tax:viewTax,account:viewAccount,admin:viewAdmin})[U.tab]()+
    (['account','admin'].includes(U.tab)?'':`<div class="foot"><span>บันทึกอัตโนมัติ</span><button class="btn ghost s" data-act="sample">โหลดข้อมูลตัวอย่าง</button><button class="btn ghost s ${CFARM==='reset'?'danger':''}" data-act="resetAll">${CFARM==='reset'?'กดอีกครั้งเพื่อล้างข้อมูลของบัญชีนี้':'ล้างข้อมูลของบัญชีนี้'}</button></div>`);
  if(U.tab==='overview')renderPlanOut();
  if(U.tab==='invest')renderProj();
  if(U.tab==='tax')renderTaxOut();
}
render();boot();
</script>
</body>
</html>

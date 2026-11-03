<!DOCTYPE html>
<html lang="en"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>RAK.Ai – Reviewer Generator</title>
<style>
:root{--bg:#f6f7fb;--card:#fff;--tx:#1b1d2a;--mut:#667;--pri:#4f46e5;--pri2:#eef0ff;--acc:#f59e0b;--bd:#e3e5ee;--ok:#16a34a;--bad:#dc2626;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#12131c;--card:#1b1d2b;--tx:#eceefa;--mut:#9aa0b8;--pri:#818cf8;--pri2:#252849;--bd:#2c2f45}}
:root[data-theme="dark"]{--bg:#12131c;--card:#1b1d2b;--tx:#eceefa;--mut:#9aa0b8;--pri:#818cf8;--pri2:#252849;--bd:#2c2f45}
*{box-sizing:border-box}html,body{height:100%;margin:0}
body{background:var(--bg);color:var(--tx);font:15px/1.5 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
button,input,textarea,select{font:inherit;color:inherit}
.btn{background:var(--pri);color:#fff;border:0;border-radius:10px;padding:9px 16px;cursor:pointer;font-weight:600}
.btn.g{background:var(--pri2);color:var(--pri)}.btn.s{padding:5px 10px;font-size:13px}.btn.d{background:transparent;color:var(--bad);border:1px solid var(--bd)}
.btn:disabled{opacity:.5;cursor:default}
input,textarea,select{background:var(--card);border:1px solid var(--bd);border-radius:10px;padding:9px 12px;width:100%}
textarea{min-height:110px;resize:vertical}
.card{background:var(--card);border:1px solid var(--bd);border-radius:16px;padding:18px}
.logo{font-weight:800;font-size:22px;letter-spacing:-.5px}.logo b{color:var(--pri)}.logo i{color:var(--acc);font-style:normal}
#auth{min-height:100%;display:grid;place-items:center;padding:20px}
#auth .card{width:100%;max-width:400px}
.tabs{display:flex;gap:6px;margin:14px 0}.tabs button{flex:1;padding:8px;border-radius:10px;border:1px solid var(--bd);background:transparent;cursor:pointer}
.tabs button.on{background:var(--pri2);color:var(--pri);border-color:var(--pri);font-weight:600}.tabs button:disabled{opacity:.4;cursor:default}
label{display:block;margin:10px 0 4px;font-size:13px;color:var(--mut)}
#app{display:none;height:100%}#app.show{display:flex}
aside{width:230px;background:var(--card);border-right:1px solid var(--bd);padding:16px 12px;display:flex;flex-direction:column;gap:4px;flex-shrink:0;overflow:auto}
aside .logo{padding:4px 8px 12px}
.nav{display:flex;gap:10px;align-items:center;padding:10px 12px;border-radius:10px;cursor:pointer;border:0;background:none;text-align:left;width:100%}
.nav.on{background:var(--pri2);color:var(--pri);font-weight:600}.nav:hover{background:var(--pri2)}
main{flex:1;display:flex;flex-direction:column;min-width:0}
header{display:flex;gap:10px;align-items:center;padding:12px 20px;border-bottom:1px solid var(--bd);background:var(--card);position:relative}
.sw{position:relative;flex:1;max-width:520px}
#rec{display:none;position:absolute;top:44px;left:0;right:0;background:var(--card);border:1px solid var(--bd);border-radius:12px;padding:8px;z-index:5;box-shadow:0 8px 24px #0002}
#rec div{padding:6px 10px;border-radius:8px;cursor:pointer}#rec div:hover{background:var(--pri2)}#rec small{color:var(--mut);padding:0 10px}
#view{flex:1;overflow:auto;padding:22px}
h1{font-size:24px;margin:0 0 4px}h2{font-size:18px;margin:0 0 10px}.mut{color:var(--mut)}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px;margin:16px 0}
.feat{cursor:pointer;transition:.15s}.feat:hover{border-color:var(--pri);transform:translateY(-2px)}.feat .ic{font-size:28px}
.gt.sel{border-color:var(--pri);background:var(--pri2)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:10px 0}
.chip{background:var(--pri2);color:var(--pri);border-radius:99px;padding:5px 12px;font-size:13px;cursor:pointer;display:inline-flex;gap:6px;align-items:center}
.chip.sel{outline:2px solid var(--pri)}.dot{width:16px;height:16px;border-radius:50%;display:inline-block}
.row{display:flex;gap:8px;flex-wrap:wrap;align-items:center}
.item{display:flex;gap:12px;align-items:center;justify-content:space-between;flex-wrap:wrap;padding:12px 0;border-bottom:1px solid var(--bd)}
.item:last-child{border:0}.badge{font-size:11px;padding:2px 8px;border-radius:99px;background:var(--pri2);color:var(--pri);font-weight:700;margin-right:6px}
.badge.p{background:#fef3c7;color:#92400e}.badge.l{background:#dcfce7;color:#166534}
.out{line-height:1.65}.out h1,.out h2,.out h3{margin:16px 0 6px}.out ul,.out ol{padding-left:22px}
.chat{display:flex;flex-direction:column;gap:10px;margin-bottom:12px}
.msg{padding:10px 14px;border-radius:14px;max-width:85%}.msg.u{background:var(--pri);color:#fff;align-self:flex-end}.msg.a{background:var(--card);border:1px solid var(--bd)}
.note{font-size:13px;color:var(--mut);background:var(--pri2);border-radius:10px;padding:8px 12px;margin:8px 0}
.err{color:var(--bad);font-size:13px;margin-top:8px}
.opt{cursor:pointer}.opt.ok{color:var(--ok);font-weight:600}.opt.bad{color:var(--bad)}
.bar{height:8px;border-radius:9px;background:var(--bd);overflow:hidden}.bar i{display:block;height:100%;background:var(--pri)}
input[type=color]{width:46px;height:36px;padding:2px}
.mg{display:grid;grid-template-columns:repeat(auto-fill,minmax(150px,1fr));gap:10px}
.mc{min-height:96px;border-radius:12px;border:2px solid var(--bd);background:var(--card);cursor:pointer;padding:8px;font-size:13px}
.mc.open{border-color:var(--pri);background:var(--pri2)}.mc.done{border-color:var(--ok);opacity:.5;cursor:default}
#menu{display:none}
@media(max-width:760px){aside{position:fixed;inset:0 auto 0 0;z-index:9;transform:translateX(-100%);transition:.2s;padding-top:calc(16px + env(safe-area-inset-top,0px))}aside.open{transform:none;box-shadow:0 0 40px #0006}#menu{display:inline-block}#view{padding:16px}}
</style></head><body>

<section id="auth"><div class="card">
 <div class="logo">RAK<i>.</i><b>Ai</b></div>
 <p class="mut" style="margin:6px 0 0">An AI-based, student-friendly reviewer generator for Cabiao Senior High School. Log in or sign up to enter your dashboard.</p>
 <div class="tabs"><button id="tL" class="on">Log in</button><button id="tS">Sign up</button></div>
 <div id="nmW" style="display:none"><label>Full name</label><input id="nm" autocomplete="name"></div>
 <label>Email</label><input id="em" type="email" autocomplete="email">
 <label>Password</label><input id="pw" type="password" autocomplete="current-password">
 <button class="btn" id="go" style="width:100%;margin-top:16px">Log in</button>
 <div class="err" id="aerr"></div>
</div></section>

<div id="app">
 <aside id="side"><div class="logo">RAK<i>.</i><b>Ai</b></div>
  <button class="nav" data-v="dash">🏠 Dashboard</button>
  <button class="nav" data-v="reviewer">📘 Reviewer Generator</button>
  <button class="nav" data-v="practice">📝 Practice Questions</button>
  <button class="nav" data-v="games">🎮 Review Games</button>
  <button class="nav" data-v="organizer">🗂️ Organizer</button>
  <button class="nav" data-v="agent">🤖 AI Agent</button>
  <button class="nav" data-v="settings">⚙️ Settings</button>
  <div style="flex:1"></div>
  <div class="mut" style="padding:8px 12px;font-size:13px" id="who"></div>
  <button class="nav" id="out">🚪 Log out</button>
 </aside>
 <main>
  <header>
   <button class="btn g s" id="menu">☰</button>
   <div class="sw"><input id="q" placeholder="🔍 Search saved reviewers &amp; questions…" autocomplete="off"><div id="rec"></div></div>
  </header>
  <div id="view"></div>
 </main>
</div>

<script>
const $=s=>document.querySelector(s),$$=s=>[...document.querySelectorAll(s)];
const mem={};
const st={get(k,d){try{const v=localStorage.getItem(k);if(v!==null)return JSON.parse(v)}catch(e){}return k in mem?mem[k]:d},set(k,v){mem[k]=v;try{localStorage.setItem(k,JSON.stringify(v))}catch(e){}}};
const esc=s=>String(s).replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
function md(t){
 let h=esc(t).split('\n'),o='',l=null;
 const cl=()=>{if(l){o+='</'+l+'>';l=null}};
 const inl=s=>s.replace(/\*\*(.+?)\*\*/g,'<b>$1</b>').replace(/\*(.+?)\*/g,'<i>$1</i>').replace(/`(.+?)`/g,'<code>$1</code>');
 for(const x of h){let m;
  if(m=x.match(/^(#{1,4})\s+(.*)/)){cl();const n=Math.min(m[1].length+1,4);o+=`<h${n}>${inl(m[2])}</h${n}>`}
  else if(m=x.match(/^\s*[-*•]\s+(.*)/)){if(l!='ul'){cl();o+='<ul>';l='ul'}o+=`<li>${inl(m[1])}</li>`}
  else if(m=x.match(/^\s*\d+[.)]\s+(.*)/)){if(l!='ol'){cl();o+='<ol>';l='ol'}o+=`<li>${inl(m[1])}</li>`}
  else if(!x.trim()){cl()}
  else if(/^-{3,}$/.test(x.trim())){cl();o+='<hr>'}
  else{cl();o+=`<p>${inl(x)}</p>`}}
 cl();return o}
const shuf=a=>a.map(x=>[Math.random(),x]).sort((a,b)=>a[0]-b[0]).map(x=>x[1]);
const norm=s=>String(s==null?'':s).toLowerCase().replace(/[^\p{L}\p{N}\s]/gu,'').replace(/\s+/g,' ').trim();
const ok=(x,a)=>!!a&&(norm(a)===norm(x.answer)||(x.alts||[]).some(t=>norm(t)===norm(a)));
const lt=x=>{const ch=x.choices;if(!ch||x.type==='id')return x.answer;const j=ch.findIndex(c=>norm(c)===norm(x.answer));return j<0?x.answer:'ABCD'[j]+'. '+ch[j]};
/* clean up a model-written question and randomise where the correct choice sits */
function fix(x){if(!x||!x.q||x.answer==null)return null;x.q=String(x.q);x.answer=String(x.answer);const cl=s=>String(s).replace(/^[A-Da-d][.)]\s+/,'').trim();
 if(x.type==='tf'){x.choices=['True','False'];x.answer=/^t/i.test(x.answer.trim())?'True':'False';return x}
 if(x.type==='id'||!Array.isArray(x.choices)){x.type='id';delete x.choices;return x}
 x.choices=x.choices.map(cl);let a=cl(x.answer);
 if(/^[A-Da-d]$/.test(a)&&x.choices[a.toUpperCase().charCodeAt(0)-65])a=x.choices[a.toUpperCase().charCodeAt(0)-65];
 if(!x.choices.some(c=>norm(c)===norm(a)))return null;
 x.answer=a;x.type='mc';x.choices=shuf(x.choices);return x}
const reshuf=x=>({...x,choices:(x.type==='mc'&&x.choices&&x.choices.length>2)?shuf(x.choices):x.choices});
const emsg=e=>e&&e.code==='not_granted'?'Permission is needed to use the AI.':e&&e.code==='rate_limited'?'Too many requests. Please try again in a moment.':'Something went wrong: '+((e&&e.message)||'please try again');
const sel=(id,o,v)=>`<select id='${id}'>`+o.map(x=>{const a=Array.isArray(x)?x[0]:x,b=Array.isArray(x)?x[1]:x;return `<option value='${esc(a)}' ${String(a)===String(v)?'selected':''}>${esc(b)}</option>`}).join('')+'</select>';

let U=null,items=[],recents=[],view='dash',att=[],cur={},chat=[];
const K=k=>k+'_'+U;
const saveItems=()=>st.set(K('rak_items'),items);
async function hash(s){try{const b=await crypto.subtle.digest('SHA-256',new TextEncoder().encode(s));return [...new Uint8Array(b)].map(x=>x.toString(16).padStart(2,'0')).join('')}catch(e){return btoa(unescape(encodeURIComponent(s)))}}

/* ---------- constants & settings ---------- */
const LANGS=['English','Filipino','Taglish (Tagalog-English)','Ilocano','Kapampangan','Cebuano','Spanish','French','German','Japanese','Korean','Chinese (Simplified)','Arabic'];
const STY=['Full reviewer (concepts, examples, summary)','Quick cheat sheet','Flashcard-style Q&A','Mnemonics & memory tricks'];
const TYP=['Mixed (multiple choice, true/false, identification)','Multiple choice','True or False','Identification'];
const DIF=['Easy','Medium','Hard'];
const LV={Easy:'Easy (basic recall and definitions, clearly different choices)',Medium:'Medium (understanding and application, plausible distractors)',Hard:'Hard (analysis and multi-step reasoning, very plausible and tricky distractors)'};
const PRE={classic:['#4f46e5','#f59e0b','Classic'],ocean:['#0284c7','#14b8a6','Ocean'],forest:['#16a34a','#eab308','Forest'],sunset:['#ea580c','#e11d48','Sunset'],rose:['#db2777','#8b5cf6','Rose'],slate:['#475569','#0ea5e9','Slate']};
const DEF={lang:'English',tl:'Filipino',mode:'system',preset:'classic',accent:'',font:15,sty:STY[0],nq:10,ty:TYP[0],df:'Medium',gtime:20,gn:10};
const SET=()=>({...DEF,...(st.get(K('rak_set'),{})||{})});
const SYS0='You are RAK.Ai, a friendly study assistant for Senior High School students at Cabiao Senior High School in the Philippines. Write clearly in simple, student-friendly language. Output Markdown only.';
let SYS=SYS0;
function applyAll(){const S=SET(),r=document.documentElement,p=PRE[S.preset]||PRE.classic,c=S.accent||p[0];
 if(S.mode==='system')r.removeAttribute('data-theme');else r.setAttribute('data-theme',S.mode);
 r.style.setProperty('--pri',c);r.style.setProperty('--pri2','color-mix(in srgb, '+c+' 15%, var(--card))');r.style.setProperty('--acc',p[1]);
 document.body.style.fontSize=S.font+'px';
 SYS=SYS0+(S.lang==='auto'?' Reply in the same language as the student’s material.':' LANGUAGE RULE: Always write in '+S.lang+'.')}
const upd=o=>{st.set(K('rak_set'),{...SET(),...o});applyAll()};

/* ---------- AUTH ---------- */
let signup=false;
function authMode(s){signup=s;$('#tL').classList.toggle('on',!s);$('#tS').classList.toggle('on',s);$('#nmW').style.display=s?'block':'none';$('#go').textContent=s?'Create account':'Log in';$('#aerr').textContent=''}
$('#tL').onclick=()=>authMode(false);$('#tS').onclick=()=>authMode(true);
$('#go').onclick=async()=>{
 const e=$('#em').value.trim().toLowerCase(),p=$('#pw').value,n=$('#nm').value.trim(),us=st.get('rak_users',{})||{};
 if(!/^\S+@\S+\.\S+$/.test(e))return $('#aerr').textContent='Please enter a valid email address.';
 if(p.length<6)return $('#aerr').textContent='Password must be at least 6 characters.';
 const h=await hash(p);
 if(signup){if(!n)return $('#aerr').textContent='Please enter your name.';if(us[e])return $('#aerr').textContent='An account with this email already exists. Please log in.';us[e]={name:n,h};st.set('rak_users',us)}
 else if(!us[e]||us[e].h!==h)return $('#aerr').textContent='Incorrect email or password.';
 st.set('rak_session',e);enter(e)};
['em','pw','nm'].forEach(i=>$('#'+i).addEventListener('keydown',e=>{if(e.key==='Enter')$('#go').click()}));
function enter(e){U=e;items=st.get(K('rak_items'),[])||[];recents=st.get(K('rak_recent'),[])||[];chat=[];
 $('#auth').style.display='none';$('#app').classList.add('show');
 $('#who').textContent=((st.get('rak_users',{})||{})[e]||{}).name||e;go('dash')}
$('#out').onclick=()=>{clearInterval(TM);st.set('rak_session',null);U=null;$('#app').classList.remove('show');$('#auth').style.display='grid';$('#pw').value=''};

/* ---------- NAV ---------- */
function go(v,arg){clearInterval(TM);applyAll();view=v;att=[];
 $$('.nav[data-v]').forEach(b=>b.classList.toggle('on',b.dataset.v===(v==='item'?'organizer':v)));
 $('#side').classList.remove('open');$('#rec').style.display='none';
 ({dash,reviewer:()=>gen('reviewer'),practice:()=>gen('practice'),organizer:()=>org(arg),agent,search:()=>srch(arg),item:()=>openItem(arg),games,settings})[v]();$('#view').scrollTop=0}
$$('.nav[data-v]').forEach(b=>b.onclick=()=>go(b.dataset.v));
$('#menu').onclick=()=>$('#side').classList.toggle('open');

/* ---------- SEARCH ---------- */
const q=$('#q'),rec=$('#rec');
function showRec(){if(!recents.length){rec.style.display='none';return}rec.innerHTML='<small>Recent searches</small>'+recents.map(r=>`<div data-r="${esc(r)}">🕘 ${esc(r)}</div>`).join('')+'<div data-clear="1" class="mut">Clear recent searches</div>';rec.style.display='block'}
q.onfocus=()=>{if(!q.value)showRec()};
q.oninput=()=>{if(q.value.trim()){rec.style.display='none';go('search',q.value.trim())}else showRec()};
q.onkeydown=e=>{if(e.key==='Enter'&&q.value.trim()){addRecent(q.value.trim());rec.style.display='none'}};
rec.onmousedown=e=>{const d=e.target.closest('div');if(!d)return;e.preventDefault();if(d.dataset.clear){recents=[];st.set(K('rak_recent'),recents);rec.style.display='none'}else{q.value=d.dataset.r;go('search',q.value)}};
q.onblur=()=>setTimeout(()=>rec.style.display='none',150);
function addRecent(s){recents=[s,...recents.filter(x=>x!==s)].slice(0,8);st.set(K('rak_recent'),recents)}
function srch(s){const k=s.toLowerCase(),r=items.filter(i=>(i.title+' '+i.content).toLowerCase().includes(k));
 $('#view').innerHTML=`<h1>Search results</h1><p class="mut">${r.length} result(s) for “${esc(s)}”</p><div class="card">${r.length?r.map(itemRow).join(''):'<p class="mut">Nothing found. Try a different keyword.</p>'}</div>`;bindItems()}

/* ---------- DASHBOARD ---------- */
function dash(){const nm=(((st.get('rak_users',{})||{})[U]||{}).name||'').split(' ')[0];
 $('#view').innerHTML=`<h1>Hi, ${esc(nm)}! 👋</h1><p class="mut">What are we studying today?</p>
 <div class="grid">
  <div class="card feat" data-g="reviewer"><div class="ic">📘</div><h2>Reviewer Generator</h2><p class="mut">Turn your notes, photos, files, or links into a student-friendly reviewer.</p></div>
  <div class="card feat" data-g="practice"><div class="ic">📝</div><h2>Practice Questions</h2><p class="mut">Unlimited questions you can answer, submit, and check. Pick Easy, Medium, or Hard.</p></div>
  <div class="card feat" data-g="games"><div class="ic">🎮</div><h2>Review Games</h2><p class="mut">Six games to review your way. Play solo or compete with a friend.</p></div>
  <div class="card feat" data-g="organizer"><div class="ic">🗂️</div><h2>Organizer</h2><p class="mut">${items.length} saved item(s). Search, rename, translate, and copy.</p></div>
  <div class="card feat" data-g="agent"><div class="ic">🤖</div><h2>AI Agent</h2><p class="mut">Ask anything about your lessons.</p></div>
  <div class="card feat" data-g="settings"><div class="ic">⚙️</div><h2>Settings</h2><p class="mut">Language, theme, defaults, and data.</p></div>
 </div>
 <div class="card"><h2>Recently saved</h2>${items.length?items.slice(0,5).map(itemRow).join(''):'<p class="mut">Nothing saved yet. Start with the Reviewer Generator!</p>'}</div>
 ${recents.length?`<div class="card" style="margin-top:14px"><h2>Recent searches</h2><div class="chips">${recents.map(r=>`<span class="chip" data-s="${esc(r)}">🕘 ${esc(r)}</span>`).join('')}</div></div>`:''}`;
 $$('[data-g]').forEach(c=>c.onclick=()=>go(c.dataset.g));$$('[data-s]').forEach(c=>c.onclick=()=>{q.value=c.dataset.s;go('search',c.dataset.s)});bindItems()}

/* ---------- ITEMS / ORGANIZER ---------- */
function itemRow(i){return `<div class="item" data-id="${i.id}"><div style="min-width:0;flex:1"><span class="badge ${i.type==='practice'?'p':''}">${i.type==='practice'?'Practice':'Reviewer'}</span>${i.level?`<span class="badge l">${esc(i.level)}</span>`:''}${i.lang?`<span class="badge">${esc(i.lang)}</span>`:''}<span class="tt" data-open="${i.id}" style="cursor:pointer;font-weight:600">${esc(i.title)}</span><div class="mut" style="font-size:12px">${new Date(i.at).toLocaleString()}</div></div>
 <div class="row"><button class="btn g s" data-open="${i.id}">Open</button><button class="btn g s" data-ren="${i.id}">✏️ Rename</button><button class="btn g s" data-cp="${i.id}">Copy</button><button class="btn d s" data-del="${i.id}">Delete</button></div></div>`}
function bindItems(){
 $$('[data-open]').forEach(b=>b.onclick=()=>go('item',b.dataset.open));
 $$('[data-cp]').forEach(b=>b.onclick=()=>copy(items.find(i=>i.id===b.dataset.cp).content,b));
 $$('[data-del]').forEach(b=>b.onclick=()=>{if(b.dataset.c){items=items.filter(i=>i.id!==b.dataset.del);saveItems();go(view==='search'?'search':view,view==='search'?q.value:undefined)}else{b.dataset.c=1;b.textContent='Sure?'}});
 $$('[data-ren]').forEach(b=>b.onclick=()=>{const row=b.closest('.item'),t=row.querySelector('.tt'),it=items.find(i=>i.id===b.dataset.ren);
  const inp=document.createElement('input');inp.value=it.title;inp.style.maxWidth='320px';t.replaceWith(inp);inp.focus();inp.select();
  const fin=()=>{it.title=inp.value.trim()||it.title;saveItems();const s=document.createElement('span');s.className='tt';s.style.cssText='cursor:pointer;font-weight:600';s.textContent=it.title;inp.replaceWith(s);s.onclick=()=>go('item',it.id)};
  inp.onblur=fin;inp.onkeydown=e=>{if(e.key==='Enter')inp.blur()}})}
async function copy(t,b){try{await navigator.clipboard.writeText(t)}catch(e){const a=document.createElement('textarea');a.value=t;document.body.appendChild(a);a.select();try{document.execCommand('copy')}catch(_){}a.remove()}
 if(b){const o=b.textContent;b.textContent='✓ Copied!';setTimeout(()=>b.textContent=o,1400)}}
function org(tab){tab=tab||'all';const f=items.filter(i=>tab==='all'||i.type===tab);
 $('#view').innerHTML=`<h1>🗂️ Organizer</h1><p class="mut">All your saved reviewers and practice questions.</p>
 <div class="tabs" style="max-width:480px">${[['all','All ('+items.length+')'],['reviewer','Reviewers ('+items.filter(i=>i.type==='reviewer').length+')'],['practice','Practice ('+items.filter(i=>i.type==='practice').length+')']].map(t=>`<button class="${t[0]===tab?'on':''}" data-t="${t[0]}">${t[1]}</button>`).join('')}</div>
 <div class="card">${f.length?f.map(itemRow).join(''):'<p class="mut">Nothing here yet.</p>'}</div>`;
 $$('[data-t]').forEach(b=>b.onclick=()=>org(b.dataset.t));bindItems()}

/* ---------- TRANSLATOR ---------- */
const tbarHtml=()=>`<div class='row' style='margin-top:12px'><select id='tlg' style='width:auto'>${LANGS.map(l=>`<option ${l===SET().tl?'selected':''}>${l}</option>`).join('')}</select><button class='btn g s' id='tbtn'>🌐 Translate</button><button class='btn g s' id='torig' style='display:none'>↩ Show original</button><span class='mut' id='tmsg'></span></div>`;
function tbarBind(doT,doO){$('#tbtn').onclick=async()=>{const l=$('#tlg').value;$('#tbtn').disabled=true;$('#tmsg').textContent='Translating…';
  try{await doT(l);const o=$('#torig'),m=$('#tmsg');if(o)o.style.display='inline-block';if(m)m.textContent=''}catch(e){const m=$('#tmsg');if(m)m.textContent=emsg(e)}
  const b=$('#tbtn');if(b)b.disabled=false};$('#torig').onclick=doO}
async function translate(sample,d,lang){
 if(d.qs&&d.qs.length){const out=[];
  for(let i=0;i<d.qs.length;i+=12){const part=d.qs.slice(i,i+12).map(({q,type,choices,answer,alts,explain})=>({q,type,choices,answer,alts,explain}));
   const r=await sample.json('Translate every text field of this quiz into '+lang+'. Keep the same JSON structure, the same order, the same "type" values and the same order of choices. The "answer" must be exactly equal to one of the translated choices (for "id" questions, the translated short answer). Return ONLY the JSON array. '+JSON.stringify(part),{cache:false});
   const a=Array.isArray(r)?r:(r&&r.questions)||[];if(a.length!==part.length)throw new Error('the translation came back incomplete');out.push(...a)}
  return {qs:out,text:qsText(out)}}
 const r=await sample('Translate this study material into '+lang+'. Keep the Markdown formatting. Output only the translation.\n\n'+d.text,{cache:false});return {text:r.text}}
async function getSample(){const s=await claude.use('sample');if(!s)throw new Error('the AI is not available in this view. Open the published link on claude.ai');return s}

function openItem(id){const it=items.find(i=>i.id===id);if(!it)return go('organizer');
 if(it.qs&&!it.S)it.S={ans:{},done:false};let d={text:it.content,qs:it.qs,S:it.S},tr=false;
 $('#view').innerHTML=`<button class="btn g s" id="bk">← Back</button><div class="card" style="margin-top:12px"><div class="row" style="justify-content:space-between"><h1 style="margin:0">${esc(it.title)}</h1><button class="btn g s" id="cp">Copy</button></div>${tbarHtml()}<div id="svt" style="display:none;margin-top:8px"><button class="btn s" id="svtb">💾 Save translation as a new item</button></div><hr style="border:0;border-top:1px solid var(--bd);margin:12px 0"><div class="out" id="qz"></div></div>`;
 const paint=()=>{if(d.qs)quiz($('#qz'),d.qs,d.S,tr?null:()=>saveItems());else $('#qz').innerHTML=md(d.text)};paint();
 $('#bk').onclick=()=>go('organizer');$('#cp').onclick=e=>copy(d.text,e.target);
 tbarBind(async l=>{const sm=await getSample(),r=await translate(sm,{text:it.content,qs:it.qs},l);d={text:r.text,qs:r.qs,S:{ans:{},done:false},lang:l};tr=true;$('#svt').style.display='block';paint()},
  ()=>{d={text:it.content,qs:it.qs,S:it.S};tr=false;$('#svt').style.display='none';$('#torig').style.display='none';paint()});
 $('#svtb').onclick=e=>{items.unshift({...(d.qs?{qs:d.qs,S:{ans:{},done:false}}:{}),id:'i'+Date.now(),type:it.type,level:it.level,lang:d.lang,title:it.title+' ('+d.lang+')',content:d.text,at:Date.now()});saveItems();e.target.textContent='✓ Saved';e.target.disabled=true}}

/* ---------- QUIZ WIDGET (answer, submit, see correct/wrong) ---------- */
function qsText(qs){return qs.map((x,i)=>`${i+1}. ${x.q}`+(x.choices?'\n'+x.choices.map((c,j)=>`   ${'ABCD'[j]||j+1}. ${c}`).join('\n'):'')).join('\n\n')+'\n\nAnswer Key\n'+qs.map((x,i)=>`${i+1}. ${lt(x)} – ${x.explain||''}`).join('\n')}
function quiz(el,qs,S,onSub,hide){
 const draw=()=>{
  const sc=S.done?qs.filter((x,i)=>ok(x,S.ans[i])).length:0;
  el.innerHTML=(S.done?`<div class='note' style='font-size:16px'><b>Score: ${sc}/${qs.length}</b> (${Math.round(sc/qs.length*100)}%) · ✅ ${sc} correct · ❌ ${qs.length-sc} wrong</div>`:'')+qs.map((x,i)=>{
   const a=S.ans[i],r=S.done&&ok(x,a),ch=x.choices;let body;
   if(!ch||x.type==='id')body=`<input data-a='${i}' value='${esc(a||'')}' placeholder='Type your answer…' ${S.done?'disabled':''}>`;
   else body=ch.map((c,j)=>{const s=a===c,corr=S.done&&norm(c)===norm(x.answer);return `<label class='opt ${S.done?(corr?'ok':s?'bad':''):''}' style='display:flex;gap:8px;align-items:center;margin:4px 0;color:var(--tx);font-size:inherit'><input type='radio' style='width:auto' name='q${i}' data-a='${i}' value='${esc(c)}' ${s?'checked':''} ${S.done?'disabled':''}><b>${'ABCD'[j]||j+1}.</b> ${esc(c)}</label>`}).join('');
   return `<div class='card' style='margin:10px 0;${S.done?'border-color:'+(r?'var(--ok)':'var(--bad)'):''}'><b>${i+1}. ${esc(x.q)}</b><div style='margin-top:8px'>${body}</div>${S.done?`<div style='margin-top:8px'>${r?'✅ <b style="color:var(--ok)">Correct!</b>':'❌ <b style="color:var(--bad)">'+(a?'Wrong.':'No answer.')+'</b> Correct answer: <b>'+esc(lt(x))+'</b>'}<div class='mut'>${esc(x.explain||'')}</div></div>`:''}</div>`}).join('')+
  (qs.length&&!hide?`<div class='row'>${S.done?`<button class='btn g' data-re>🔄 Try again</button>`:`<button class='btn' data-sub>📨 Submit answers</button>`}</div>`:'');
  el.querySelectorAll('[data-a]').forEach(n=>n.oninput=()=>{S.ans[n.dataset.a]=n.value;onSub&&onSub()});
  const sb=el.querySelector('[data-sub]'),rb=el.querySelector('[data-re]');
  if(sb)sb.onclick=()=>{S.done=true;onSub&&onSub();draw();el.scrollIntoView({block:'start'})};
  if(rb)rb.onclick=()=>{S.ans={};S.done=false;onSub&&onSub();draw()};
 };draw()}

/* ---------- GENERATOR ---------- */
function gen(mode){const R=mode==='reviewer',S=SET();cur={mode,text:'',qs:[],S:{ans:{},done:false},title:'',level:'',lang:'',orig:null};
 $('#view').innerHTML=`<h1>${R?'📘 Reviewer Generator':'📝 Practice Question Generator'}</h1>
 <p class="mut">${R?'Enter a topic or upload your materials to generate a reviewer.':'Generate as many practice questions as you want, then answer them, submit, and see what you got right and wrong.'}</p>
 <div class="card"><label>Topic / notes</label><textarea id="tp" placeholder="e.g. Photosynthesis, Grade 11 General Mathematics – Functions…"></textarea>
 <label>Link (optional)</label><input id="lk" placeholder="https://…">
 <label>Upload materials</label>
 <div class="row">
  <button class="btn g s" data-u="cam">📷 Take a photo</button><button class="btn g s" data-u="img">🖼️ Upload photo</button><button class="btn g s" data-u="vid">🎬 Video</button><button class="btn g s" data-u="aud">🎧 Audio</button><button class="btn g s" data-u="file">📄 Files</button>
 </div>
 <input type="file" id="f_cam" accept="image/*" capture="environment" hidden><input type="file" id="f_img" accept="image/*" multiple hidden><input type="file" id="f_vid" accept="video/*" hidden><input type="file" id="f_aud" accept="audio/*" hidden><input type="file" id="f_file" multiple hidden>
 <div class="chips" id="ch"></div>
 <div class="note">The AI can read photos and text files (.txt, .md, .csv). For video, audio, PDF, or Word files, also paste the transcript or notes above for the best results.</div>
 ${R?`<label>Style</label>${sel('sty',STY,S.sty)}`
 :`<div class="row"><div style="flex:1;min-width:140px"><label>Number of questions (no limit)</label><input id="nq" type="number" min="1" value="${S.nq}"></div><div style="flex:2;min-width:180px"><label>Question type</label>${sel('ty',TYP,S.ty)}</div><div style="flex:1;min-width:140px"><label>Level</label>${sel('df',DIF,S.df)}</div></div>`}
 <div class="row" style="margin-top:16px"><button class="btn" id="run">✨ Generate</button></div><div class="err" id="ge"></div></div>
 <div class="card" id="res" style="margin-top:14px;display:none"></div>`;
 $$('[data-u]').forEach(b=>b.onclick=()=>$('#f_'+b.dataset.u).click());
 $$('input[type=file]').forEach(f=>f.onchange=()=>{[...f.files].forEach(x=>att.push({k:f.id.slice(2),f:x}));f.value='';chips()});
 $('#run').onclick=()=>run(false)}
function chips(){$('#ch').innerHTML=att.map((a,i)=>`<span class="chip">${{cam:'📷',img:'🖼️',vid:'🎬',aud:'🎧',file:'📄'}[a.k]} ${esc(a.f.name||'photo')} <b data-x="${i}" style="cursor:pointer">✕</b></span>`).join('');$$('[data-x]').forEach(x=>x.onclick=()=>{att.splice(+x.dataset.x,1);chips()})}
async function readText(f){return new Promise(r=>{const fr=new FileReader();fr.onload=()=>r(String(fr.result).slice(0,30000));fr.onerror=()=>r('');fr.readAsText(f)})}
async function run(more){
 const ge=$('#ge');ge.textContent='';let sample;try{sample=await getSample()}catch(e){ge.textContent=emsg(e);return}
 const R=cur.mode==='reviewer',tp=$('#tp').value.trim(),lk=$('#lk').value.trim();
 if(!tp&&!lk&&!att.length&&!more){ge.textContent='Enter a topic, add a link, or upload something first.';return}
 let ctx='',imgs=[];
 if(tp)ctx+='Topic/notes from student:\n'+tp+'\n\n';
 if(lk)ctx+='Link provided (you cannot open it; use it only as a hint about the topic): '+lk+'\n\n';
 const lim=await sample.limits().catch(()=>({}));
 for(const a of att){
  if(a.f.type.startsWith('image/')){if(lim.images&&imgs.length<4)imgs.push(a.f);else ctx+='[Image '+a.f.name+' could not be attached]\n'}
  else if(/^(text\/|application\/json)/.test(a.f.type)||/\.(txt|md|csv|json)$/i.test(a.f.name))ctx+='File "'+a.f.name+'":\n'+await readText(a.f)+'\n\n';
  else ctx+='[Attached '+a.k+' file named "'+a.f.name+'" – its content is not readable; rely on the student’s notes/topic.]\n'}
 if(more&&cur.orig){cur.text=cur.orig.text;cur.qs=cur.orig.qs||[];cur.orig=null;cur.lang=''}
 const res=$('#res');res.style.display='block';$('#run').disabled=true;
 if(!more){cur.text='';cur.qs=[];cur.S={ans:{},done:false};cur.orig=null;cur.lang='';cur.title=(tp.split('\n')[0]||lk||(att[0]&&att[0].f.name)||'Untitled').slice(0,50)}
 else cur.S.done=false;
 const paint=busy=>{if(R)$('#qz').innerHTML=md(cur.text);else quiz($('#qz'),cur.qs,cur.S,null,busy)};
 const show=busy=>{res.innerHTML=`<div class="row" style="justify-content:space-between"><h2 style="margin:0">${R?'Your reviewer':'Your practice quiz'}${!R&&cur.level?' · '+cur.level:''}${cur.lang?' · '+esc(cur.lang):''}</h2>${busy?'<span class="mut">Generating…</span>':`<div class="row"><button class="btn s" id="sv">💾 Save</button><button class="btn g s" id="cpy">Copy</button>${R?'':'<button class="btn g s" id="more">➕ Generate more</button>'}</div>`}</div>${busy?'':tbarHtml()}<div id="qz" class="out" style="margin-top:10px"></div>`;
  paint(busy);
  if(!busy){$('#sv').onclick=save;$('#cpy').onclick=e=>copy(cur.text,e.target);if(!R)$('#more').onclick=()=>run(true);
   tbarBind(async l=>{const sm=await getSample(),o=cur.orig||{text:cur.text,qs:JSON.parse(JSON.stringify(cur.qs||[]))},r=await translate(sm,o,l);cur.orig=o;cur.text=r.text;if(r.qs){cur.qs=r.qs;cur.S={ans:{},done:false}}cur.lang=l;show(false)},
    ()=>{cur.text=cur.orig.text;if(cur.orig.qs&&!R){cur.qs=cur.orig.qs;cur.S={ans:{},done:false}}cur.orig=null;cur.lang='';show(false)});
   if(cur.orig)$('#torig').style.display='inline-block'}};
 try{
  if(R){await sample(SYS+'\n\n'+ctx+'Create a reviewer in this style: '+$('#sty').value+'. Include a title, key concepts with simple definitions, examples, memory tips, and a short self-check at the end.',{images:imgs,cache:false,onText:({text})=>{cur.text=text;show(true)}})}
  else{const n=Math.max(1,parseInt($('#nq').value)||10),ty=$('#ty').value,df=$('#df').value;cur.level=df;let done=0,tries=0;
   while(done<n&&tries++<n+3){const c=Math.min(10,n-done),prev=cur.qs.slice(-40).map(x=>x.q).join(' | ').slice(-2500);
    const p=SYS+'\n\n'+ctx+(prev?'Already written (do NOT repeat): '+prev+'\n\n':'')+`Write exactly ${c} new practice questions. Type: ${ty}. Level: ${LV[df]}. Make the correct choice land on a random letter (do not favor A). Return ONLY a JSON array (no markdown fences, no extra text). Each item: {"q":"question","type":"mc" or "tf" or "id","choices":[exactly 4 options for mc, without letter prefixes; omit for tf and id],"answer":"exact text of the correct choice (True or False for tf; the short answer for id)","alts":[acceptable alternative answers, id only],"explain":"1-2 sentence explanation"}`;
    const r=await sample.json(p,{images:imgs,cache:false}),arr=(Array.isArray(r)?r:(r&&r.questions)||[]).map(fix).filter(Boolean);
    cur.qs.push(...arr);done+=arr.length;cur.text=qsText(cur.qs);show(true)}}
  show(false)
 }catch(e){ge.textContent=emsg(e);if(cur.text||cur.qs.length)show(false)}
 $('#run').disabled=false}
function save(){const b=$('#sv'),R=cur.mode==='reviewer';
 items.unshift({id:'i'+Date.now(),type:cur.mode,title:(R?'Reviewer – ':'Practice – ')+cur.title+(cur.lang?' ('+cur.lang+')':''),content:cur.text,at:Date.now(),level:R?'':cur.level,lang:cur.lang,...(R?{}:{qs:JSON.parse(JSON.stringify(cur.qs)),S:JSON.parse(JSON.stringify(cur.S))})});
 saveItems();b.textContent='✓ Saved to Organizer';b.disabled=true}

/* ---------- AI AGENT ---------- */
function agent(){
 $('#view').innerHTML=`<h1>🤖 RAK AI Agent</h1><p class="mut">Ask about lessons, homework help, or study tips.</p>
 <div class="card"><div class="chat" id="cb">${chat.length?'':'<div class="msg a">Hi! I’m RAK. What would you like to study today?</div>'}${chat.map(m=>`<div class="msg ${m.role==='user'?'u':'a'}">${m.role==='user'?esc(m.content):md(m.content)}</div>`).join('')}</div>
 <div class="row"><input id="ci" placeholder="Type your question…" style="flex:1"><button class="btn" id="cs">Send</button></div><div class="err" id="ce"></div></div>`;
 const send=async()=>{const v=$('#ci').value.trim();if(!v)return;let sample;try{sample=await getSample()}catch(e){return $('#ce').textContent=emsg(e)}
  $('#ci').value='';$('#ce').textContent='';chat.push({role:'user',content:v});
  $('#cb').insertAdjacentHTML('beforeend',`<div class="msg u">${esc(v)}</div><div class="msg a" id="ans">…</div>`);
  const hist=chat.slice(-12).map(m=>({role:m.role,content:m.content}));
  hist[0]={role:'user',content:SYS+'\n\nYou are the RAK AI Agent: answer questions, explain lessons step by step, and keep replies concise.\n\n'+hist[0].content};
  $('#cs').disabled=true;
  try{const r=await sample(hist,{cache:false,onText:({text})=>{$('#ans').innerHTML=md(text||'…')}});chat.push({role:'assistant',content:r.text})}
  catch(e){$('#ans').remove();chat.pop();$('#ce').textContent=emsg(e)}
  $('#cs').disabled=false};
 $('#cs').onclick=send;$('#ci').onkeydown=e=>{if(e.key==='Enter')send()}}

/* ---------- SETTINGS ---------- */
function settings(){const S=SET(),us=st.get('rak_users',{})||{};
 const f=(l,c)=>`<div style='margin:10px 0'><label>${l}</label>${c}</div>`;
 $('#view').innerHTML=`<h1>⚙️ Settings</h1><p class='mut'>Customize RAK.Ai. Changes are saved automatically.</p>
 <div class='card' style='margin-bottom:14px'><h2>👤 Account</h2>${f('Name',`<div class='row'><input id='sn' value='${esc((us[U]||{}).name||'')}' style='flex:1;min-width:160px'><button class='btn s' id='snb'>Save</button></div>`)}<div class='mut'>${esc(U)}</div></div>
 <div class='card' style='margin-bottom:14px'><h2>🌐 Language</h2>${f('Content language (reviewers, questions, AI Agent)',sel('lang',[['auto','Auto (match my material)'],...LANGS.map(l=>[l,l])],S.lang))}${f('Default translation language',sel('tl',LANGS,S.tl))}<div class='mut'>Use the 🌐 Translate button on any reviewer or quiz to convert it to another language.</div></div>
 <div class='card' style='margin-bottom:14px'><h2>🎨 Appearance &amp; Theme</h2>${f('Mode',`<div class='tabs' style='max-width:380px;margin:0'>${[['system','System'],['light','☀️ Light'],['dark','🌙 Dark']].map(m=>`<button data-md='${m[0]}' class='${S.mode===m[0]?'on':''}'>${m[1]}</button>`).join('')}</div>`)}${f('Color theme',`<div class='chips'>${Object.entries(PRE).map(([k,v])=>`<span class='chip ${S.preset===k&&!S.accent?'sel':''}' data-pr='${k}'><i class='dot' style='background:${v[0]}'></i>${v[2]}</span>`).join('')}</div>`)}${f('Custom accent color',`<div class='row'><input type='color' id='ac' value='${S.accent||PRE[S.preset][0]}'><button class='btn g s' id='acr'>Reset</button></div>`)}${f('Text size',sel('fs',[[14,'Small'],[15,'Medium'],[17,'Large'],[19,'Extra large']],S.font))}</div>
 <div class='card' style='margin-bottom:14px'><h2>📚 Study defaults</h2>${f('Reviewer style',sel('dsty',STY,S.sty))}<div class='row'><div style='flex:1;min-width:130px'>${f('Questions per practice set',`<input id='dnq' type='number' min='1' value='${S.nq}'>`)}</div><div style='flex:2;min-width:180px'>${f('Question type',sel('dty',TYP,S.ty))}</div><div style='flex:1;min-width:120px'>${f('Level',sel('ddf',DIF,S.df))}</div></div></div>
 <div class='card' style='margin-bottom:14px'><h2>🎮 Game defaults</h2><div class='row'><div style='flex:1;min-width:150px'>${f('Seconds per question',`<input id='dgt' type='number' min='5' max='120' value='${S.gtime}'>`)}</div><div style='flex:1;min-width:150px'>${f('Questions per game',`<input id='dgn' type='number' min='3' value='${S.gn}'>`)}</div></div><div class='mut'>The game level uses your default Level above unless you change it when starting a game.</div></div>
 <div class='card'><h2>🗄️ Data &amp; privacy</h2><p class='mut'>${items.length} saved item(s) · ${recents.length} recent search(es). Your data is stored only in this browser on this device.</p><div class='row'><button class='btn g s' id='bk1'>Copy backup (JSON)</button><button class='btn g s' id='cr'>Clear recent searches</button><button class='btn d s' id='di'>Delete all saved items</button><button class='btn d s' id='da'>Delete account</button></div><div class='mut' id='dm' style='margin-top:8px'></div></div>`;
 const on=(id,ev,fn)=>$('#'+id).addEventListener(ev,fn),two=(id,fn)=>{const b=$('#'+id);b.onclick=()=>{if(b.dataset.c)fn();else{b.dataset.c=1;b.textContent='Are you sure? Click again'}}};
 on('snb','click',()=>{const n=$('#sn').value.trim();if(!n)return;const u=st.get('rak_users',{})||{};u[U].name=n;st.set('rak_users',u);$('#who').textContent=n;$('#dm').textContent='✓ Name updated'});
 on('lang','change',e=>upd({lang:e.target.value}));on('tl','change',e=>upd({tl:e.target.value}));
 $$('[data-md]').forEach(b=>b.onclick=()=>{upd({mode:b.dataset.md});settings()});
 $$('[data-pr]').forEach(b=>b.onclick=()=>{upd({preset:b.dataset.pr,accent:''});settings()});
 on('ac','input',e=>upd({accent:e.target.value}));on('acr','click',()=>{upd({accent:''});settings()});
 on('fs','change',e=>upd({font:+e.target.value}));on('dsty','change',e=>upd({sty:e.target.value}));on('dnq','change',e=>upd({nq:Math.max(1,parseInt(e.target.value)||10)}));on('dty','change',e=>upd({ty:e.target.value}));on('ddf','change',e=>upd({df:e.target.value}));
 on('dgt','change',e=>upd({gtime:Math.min(120,Math.max(5,parseInt(e.target.value)||20))}));on('dgn','change',e=>upd({gn:Math.max(3,parseInt(e.target.value)||10)}));
 on('bk1','click',e=>copy(JSON.stringify(items,null,1),e.target));
 on('cr','click',()=>{recents=[];st.set(K('rak_recent'),recents);$('#dm').textContent='✓ Recent searches cleared'});
 two('di',()=>{items=[];saveItems();settings()});
 two('da',()=>{const u=st.get('rak_users',{})||{};delete u[U];st.set('rak_users',u);['rak_items','rak_recent','rak_set','rak_lb'].forEach(k=>{delete mem[K(k)];try{localStorage.removeItem(K(k))}catch(e){}});$('#out').click()})}

/* ---------- GAMES ---------- */
let G=null,TM=null,gsel='speed',gpm=1;
const GM=[['speed','⚡','Speed Quiz','Answer fast: quicker answers earn more points.'],['survival','❤️','Survival','3 lives. Every wrong answer costs one.'],['ladder','🪜','Quiz Ladder','Points grow with every correct answer, but one mistake and you’re out. Each player gets one 50:50 lifeline.'],['rapid','🔥','Rapid Fire','Is the proposed answer right? True or False. Build a streak for bonus points.'],['match','🧩','Memory Match','Flip cards to match every question with its answer.'],['cards','🃏','Flashcards','Flip each card and mark what you already know.']];
const TN=Object.fromEntries(GM.map(g=>[g[0],g[2]])),LIVES={speed:99,survival:3,ladder:1,rapid:99},MULT={Easy:1.5,Medium:1,Hard:.7};
const LB=()=>st.get(K('rak_lb'),[])||[];
function games(){const S=SET(),sv=items.filter(i=>i.qs&&i.qs.length),lb=LB().slice(0,8);gsel='speed';gpm=1;
 $('#view').innerHTML=`<h1>🎮 Review Games</h1><p class='mut'>Review your way: pick a game, play solo or compete, choose a level, and choose where the questions come from. Correct answers are placed on random letters.</p>
 <div class='card' style='margin-bottom:14px'><h2>1. Choose a game</h2><div class='grid' style='margin:8px 0'>${GM.map((g,i)=>`<div class='card feat gt ${i?'':'sel'}' data-gt='${g[0]}'><div class='ic'>${g[1]}</div><b>${g[2]}</b><div class='mut' style='font-size:13px'>${g[3]}</div></div>`).join('')}</div>
 <h2>2. Solo or versus?</h2><div class='tabs' style='max-width:380px'><button class='on' data-pm='1'>🙋 Solo</button><button data-pm='2' id='pmv'>🏆 Versus (highest score wins)</button></div>
 <div id='pn' style='display:none'><label>Player names (2–4, separated by commas). Players take turns on the same device.</label><input id='gpn' value='Player 1, Player 2'></div>
 <h2 style='margin-top:16px'>3. Level</h2><div style='max-width:260px'>${sel('glv',DIF,S.df)}</div><div class='mut' style='font-size:13px'>Easy gives more time, Hard gives less time and trickier questions (for new topics).</div>
 <h2 style='margin-top:16px'>4. Where do the questions come from?</h2><select id='gs'><option value='new'>✨ Generate new ones from a topic</option>${sv.map(i=>`<option value='${i.id}'>📝 ${esc(i.title)}</option>`).join('')}</select>
 <div id='gnw'><label>Topic</label><input id='gtp' placeholder='e.g. Photosynthesis, Functions, Philippine History…'></div>
 <div class='row'><div style='flex:1;min-width:140px'><label>Questions (new topic)</label><input id='gn' type='number' min='3' value='${S.gn}'></div><div style='flex:1;min-width:140px'><label>Seconds per question</label><input id='gtm' type='number' min='5' max='120' value='${S.gtime}'></div></div>
 <button class='btn' id='gb' style='margin-top:16px'>▶️ Start game</button><div class='err' id='gerr'></div></div>
 <div class='card'><h2>🏅 Leaderboard (this device)</h2>${lb.length?lb.map((r,i)=>`<div class='item'><span>${i+1}. <b>${esc(r.name)}</b> <span class='mut'>· ${esc(r.type)}${r.level?' · '+esc(r.level):''}${r.topic?' · '+esc(r.topic):''}</span></span><b>${r.score}</b></div>`).join(''):`<p class='mut'>No scores yet. Go play!</p>`}</div>`;
 $$('[data-gt]').forEach(c=>c.onclick=()=>{gsel=c.dataset.gt;$$('.gt').forEach(x=>x.classList.toggle('sel',x===c));$('#pmv').disabled=gsel==='cards';if(gsel==='cards'){gpm=1;$$('[data-pm]').forEach(b=>b.classList.toggle('on',b.dataset.pm==='1'));$('#pn').style.display='none'}});
 $$('[data-pm]').forEach(b=>b.onclick=()=>{if(b.disabled)return;gpm=+b.dataset.pm;$$('[data-pm]').forEach(x=>x.classList.toggle('on',x===b));$('#pn').style.display=gpm>1?'block':'none'});
 $('#gs').onchange=()=>{$('#gnw').style.display=$('#gs').value==='new'?'block':'none'};
 $('#gb').onclick=startGame}
async function startGame(){const ge=$('#gerr'),src=$('#gs').value,lv=$('#glv').value;ge.textContent='';let qs=[],topic='';
 if(src==='new'){topic=$('#gtp').value.trim();if(!topic)return ge.textContent='Please enter a topic.';
  let sample;try{sample=await getSample()}catch(e){return ge.textContent=emsg(e)}
  const n=Math.max(3,parseInt($('#gn').value)||10);$('#gb').disabled=true;ge.textContent='Generating questions…';let tries=0;
  try{while(qs.length<n&&tries++<n){const c=Math.min(10,n-qs.length),r=await sample.json(SYS+' Topic: '+topic+'. Write '+c+' multiple-choice questions with exactly 4 choices each for a review game. Level: '+LV[lv]+'. Put the correct choice on a random letter.'+(qs.length?' Do NOT repeat: '+qs.map(x=>x.q).join(' | ').slice(-2000):'')+' Return ONLY a JSON array of objects like {"q":"question","type":"mc","choices":["a","b","c","d"],"answer":"exact text of the correct choice","explain":"short explanation"}.',{cache:false});
   qs.push(...(Array.isArray(r)?r:(r&&r.questions)||[]).map(x=>{if(x)x.type='mc';return fix(x)}).filter(Boolean))}}
  catch(e){ge.textContent=emsg(e);if(qs.length<3){$('#gb').disabled=false;return}}}
 else{const it=items.find(i=>i.id===src);topic=it.title;qs=it.qs.filter(x=>x.choices&&x.type!=='id').map(reshuf)}
 if(qs.length<1){ge.textContent='This quiz has no multiple-choice or true/false questions to play.';$('#gb').disabled=false;return}
 if(gsel==='match'&&qs.length<3){ge.textContent='Memory Match needs at least 3 questions.';$('#gb').disabled=false;return}
 const solo=!(gpm>1&&gsel!=='cards');
 const names=solo?[(((st.get('rak_users',{})||{})[U]||{}).name||'Me').split(' ')[0]]:$('#gpn').value.split(',').map(s=>s.trim()).filter(Boolean).slice(0,4);
 while(!solo&&names.length<2)names.push('Player '+(names.length+1));
 const base=Math.min(120,Math.max(5,parseInt($('#gtm').value)||20));
 G={type:gsel,level:lv,qs:shuf(qs),i:0,turn:0,tl:Math.max(5,Math.round(base*MULT[lv])),topic:topic.slice(0,30),players:names.map(n=>({name:n,score:0,lives:LIVES[gsel]||99,ok:0,streak:0,ll:false})),deck:[],pos:0,known:0,missed:[]};
 begin()}
function begin(){G.deck=G.qs;G.pos=0;G.known=0;G.missed=[];G.i=0;G.turn=0;G.type==='cards'?cards():G.type==='match'?matchGame():playQ()}
function playQ(){clearInterval(TM);const n=G.players.length,T=G.type;
 let g=0;while(G.players[G.turn].lives<=0&&g++<n)G.turn=(G.turn+1)%n;
 if(G.i>=G.qs.length||G.players.every(p=>p.lives<=0))return endGame();
 const P=G.players[G.turn],x=G.qs[G.i],cj=x.choices.findIndex(c=>norm(c)===norm(x.answer));
 const wrongs=x.choices.filter(c=>norm(c)!==norm(x.answer)),isT=Math.random()<.5||!wrongs.length,prop=isT?x.answer:wrongs[Math.floor(Math.random()*wrongs.length)];
 let left=T==='rapid'?Math.max(5,Math.round(G.tl/2)):G.tl;const total=left;let locked=false;
 const stat=p=>T==='survival'?' '+'❤️'.repeat(Math.max(0,p.lives)):(T==='ladder'||T==='rapid')&&p.streak?' 🔥'+p.streak:'';
 const body=T==='rapid'?`<p style='font-size:17px'>Proposed answer: <b>${esc(prop)}</b></p><div class='row'><button class='btn g gc' data-c='1' style='flex:1;padding:14px'>✅ True</button><button class='btn g gc' data-c='0' style='flex:1;padding:14px'>❌ False</button></div>`
  :x.choices.map((c,j)=>`<button class='btn g gc' data-c='${j}' style='display:block;width:100%;text-align:left;margin:6px 0;padding:12px 16px'><b>${'ABCD'[j]||j+1}.</b> ${esc(c)}</button>`).join('');
 $('#view').innerHTML=`<div class='row' style='justify-content:space-between'><button class='btn g s' id='ex'>← Leave</button><span class='mut'>${TN[T]} · ${G.level} · Question ${G.i+1}/${G.qs.length}</span></div>
 <div class='chips'>${G.players.map((p,i)=>`<span class='chip ${i===G.turn?'sel':''}'>${esc(p.name)} · <b>${p.score}</b>${stat(p)}${p.lives<=0?' 💀':''}</span>`).join('')}</div>
 <div class='card'><div class='mut'>🎯 ${esc(P.name)}’s turn${T==='ladder'?' · Step '+(P.streak+1)+' · worth '+100*(P.streak+1)+' pts':''}</div><h2 style='margin-top:6px'>${esc(x.q)}</h2><div class='bar' style='margin:10px 0'><i id='tb' style='width:100%'></i></div><div>${body}</div>${T==='ladder'&&!P.ll&&x.choices.length>2?`<button class='btn g s' id='ll' style='margin-top:6px'>🎯 50:50 lifeline</button>`:''}<div id='fb'></div></div>`;
 $('#ex').onclick=()=>go('games');
 if($('#ll'))$('#ll').onclick=()=>{P.ll=true;const bs=$$('.gc');shuf(x.choices.map((c,j)=>j).filter(j=>j!==cj)).slice(0,2).forEach(j=>{bs[j].disabled=true;bs[j].style.opacity='.25'});$('#ll').remove()};
 const fin=j=>{if(locked)return;locked=true;clearInterval(TM);
  const good=T==='rapid'?j===(isT?1:0):j===cj,cor=T==='rapid'?(isT?1:0):cj;
  $$('.gc').forEach(b=>{b.disabled=true;const k=+b.dataset.c;if(k===cor){b.style.background='var(--ok)';b.style.color='#fff'}else if(k===j){b.style.background='var(--bad)';b.style.color='#fff'}});
  let pts=0;
  if(good){pts=T==='speed'?100+Math.round(Math.max(left,0))*10:T==='survival'?100+Math.round(Math.max(left,0))*5:T==='ladder'?100*(P.streak+1):50+Math.min(P.streak,10)*25;P.score+=pts;P.ok++;P.streak++}
  else{P.streak=0;if(T==='survival'||T==='ladder')P.lives--}
  const out=T==='ladder'&&!good?' You’re out of the ladder!':T==='survival'&&!good?' −1 ❤️':'';
  $('#fb').innerHTML=`<div class='note'>${good?'✅ <b>Correct!</b> +'+pts+' pts':(j<0?'⏰ <b>Time’s up!</b>':'❌ <b>Wrong.</b>')+out}${T==='rapid'?'<div>The correct answer is <b>'+esc(lt(x))+'</b>.</div>':good?'':'<div>Correct answer: <b>'+esc(lt(x))+'</b></div>'}<div>${esc(x.explain||'')}</div></div><button class='btn' id='nx'>Next ➡️</button>`;
  $('#nx').onclick=()=>{G.i++;G.turn=(G.turn+1)%n;playQ()}};
 $$('.gc').forEach(b=>b.onclick=()=>fin(+b.dataset.c));
 TM=setInterval(()=>{left-=.25;const t=$('#tb');if(t)t.style.width=Math.max(0,left/total*100)+'%';if(left<=0)fin(-1)},250)}
function matchGame(){clearInterval(TM);const k=G.level==='Easy'?4:G.level==='Hard'?8:6,ps=G.qs.slice(0,k);
 let cs=shuf(ps.flatMap((x,i)=>[{p:i,t:'Q',x:x.q},{p:i,t:'A',x:x.answer}])),open=[],lock=false,found=0;G.i=ps.length;G.turn=0;
 const P=()=>G.players[G.turn];
 const draw=()=>{$('#view').innerHTML=`<div class='row' style='justify-content:space-between'><button class='btn g s' id='ex'>← Leave</button><span class='mut'>Memory Match · ${G.level} · ${found}/${ps.length} pairs</span></div><div class='chips'>${G.players.map((p,i)=>`<span class='chip ${i===G.turn?'sel':''}'>${esc(p.name)} · <b>${p.score}</b></span>`).join('')}</div><p class='mut'>🎯 ${esc(P().name)}’s turn: match each question with its correct answer. A match earns another turn.</p><div class='mg'>${cs.map((c,i)=>`<button class='mc ${c.done?'done':open.includes(i)?'open':''}' data-i='${i}'>${c.done||open.includes(i)?`<small>${c.t==='Q'?'Question':'Answer'}</small><br>${esc(c.x.length>90?c.x.slice(0,88)+'…':c.x)}`:'❓'}</button>`).join('')}</div>`;
  $('#ex').onclick=()=>go('games');
  $$('.mc').forEach(b=>b.onclick=()=>{const i=+b.dataset.i;if(lock||cs[i].done||open.includes(i))return;open.push(i);draw();
   if(open.length===2){lock=true;const a=cs[open[0]],c=cs[open[1]];
    setTimeout(()=>{if(a.p===c.p&&a.t!==c.t){a.done=c.done=true;found++;P().score+=100;P().ok++;open=[];lock=false;if(found===ps.length)return endGame();draw()}
     else{open=[];lock=false;G.turn=(G.turn+1)%G.players.length;draw()}},900)}})};
 draw()}
function endGame(){clearInterval(TM);const ps=[...G.players].sort((a,b)=>b.score-a.score),w=ps[0],tie=ps.length>1&&ps[1].score===w.score;
 const lb=LB();ps.forEach(p=>lb.push({name:p.name,score:p.score,type:TN[G.type],level:G.level,topic:G.topic,at:Date.now()}));lb.sort((a,b)=>b.score-a.score);st.set(K('rak_lb'),lb.slice(0,20));
 $('#view').innerHTML=`<div class='card' style='text-align:center'><div style='font-size:48px'>🏆</div><h1>${ps.length>1?(tie?'It’s a tie!':esc(w.name)+' wins!'):'Game over!'}</h1><div class='mut'>${TN[G.type]} · ${G.level}</div>${ps.map((p,i)=>`<div class='item'><span>${i+1}. <b>${esc(p.name)}</b> <span class='mut'>· ${p.ok} correct</span></span><b>${p.score} pts</b></div>`).join('')}<div class='row' style='justify-content:center;margin-top:14px'><button class='btn' id='pa'>🔄 Play again</button><button class='btn g' id='bk2'>Back to Games</button></div></div>`;
 $('#bk2').onclick=()=>go('games');
 $('#pa').onclick=()=>{G.players.forEach(p=>{p.score=0;p.lives=LIVES[G.type]||99;p.ok=0;p.streak=0;p.ll=false});G.qs=shuf(G.qs.map(reshuf));begin()}}
function cards(){clearInterval(TM);if(G.pos>=G.deck.length)return fcEnd();const x=G.deck[G.pos];
 $('#view').innerHTML=`<div class='row' style='justify-content:space-between'><button class='btn g s' id='ex'>← Leave</button><span class='mut'>Flashcards · Card ${G.pos+1}/${G.deck.length}</span></div><div class='card' style='margin-top:10px'><h2>${esc(x.q)}</h2>${x.choices.map((c,j)=>`<div style='margin:4px 0'><b>${'ABCD'[j]||j+1}.</b> ${esc(c)}</div>`).join('')}<div id='fa' style='margin-top:14px'><button class='btn' id='fr'>👀 Show answer</button></div></div>`;
 $('#ex').onclick=()=>go('games');
 $('#fr').onclick=()=>{$('#fa').innerHTML=`<div class='note'><b>Answer: ${esc(lt(x))}</b><div>${esc(x.explain||'')}</div></div><div class='row'><button class='btn' id='fk'>✅ I know this</button><button class='btn g' id='fm'>❌ Review again</button></div>`;$('#fk').onclick=()=>{G.known++;G.pos++;cards()};$('#fm').onclick=()=>{G.missed.push(x);G.pos++;cards()}}}
function fcEnd(){const m=G.missed.length;$('#view').innerHTML=`<div class='card' style='text-align:center'><div style='font-size:48px'>🎉</div><h1>Deck complete!</h1><p>✅ Known: <b>${G.known}</b> · ❌ Review again: <b>${m}</b></p><div class='row' style='justify-content:center'>${m?`<button class='btn' id='rm'>Review missed (${m})</button>`:''}<button class='btn g' id='bk2'>Back to Games</button></div></div>`;$('#bk2').onclick=()=>go('games');if(m)$('#rm').onclick=()=>{G.deck=G.missed;G.missed=[];G.pos=0;cards()}}

/* ---------- BOOT ---------- */
const s0=st.get('rak_session',null);if(s0&&(st.get('rak_users',{})||{})[s0])enter(s0);
</script></body></html>

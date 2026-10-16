<!DOCTYPE html>
<html lang="th"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>จองคิวแพทย์แผนไทย</title>
<base target="_top">
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif+Thai:wght@600;700&family=Noto+Sans+Thai:wght@300;400;500;600&display=swap" rel="stylesheet">
<script src="https://static.line-scdn.net/liff/edge/2/sdk.js"></script>
<style>
:root{--g1:#34502a;--g2:#5f8a35;--g3:#eef2dc;--gold:#d4961c;--cream:#fbf6e8;--ink:#2b2a1c;--mut:#857f68;--line:#ece5cf;--r:18px}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
body{margin:0;font-family:'Noto Sans Thai',sans-serif;background:var(--cream);color:var(--ink)}
.hero{position:relative;overflow:hidden;color:#fff;padding:34px 20px 70px;background:linear-gradient(145deg,var(--g1),var(--g2) 70%,#d4961c 135%)}
.hero:before,.hero:after{content:"";position:absolute;border-radius:50%;background:#ffffff12}
.hero:before{width:260px;height:260px;right:-70px;top:-90px}.hero:after{width:180px;height:180px;left:-60px;bottom:-90px}
.hero .in{position:relative;max-width:560px;margin:auto}
.badge{display:inline-block;font-size:12px;letter-spacing:.08em;background:#d4961c33;border:1px solid #f0c66a99;padding:4px 12px;border-radius:20px;margin-bottom:12px}
.hero h1{font-family:'Noto Serif Thai',serif;font-size:27px;line-height:1.3;margin:0 0 6px}
.hero p{margin:0;opacity:.88;font-size:14px;font-weight:300}
.hero .leaf{position:absolute;right:18px;bottom:12px;font-size:64px;opacity:.9;transform:rotate(-12deg)}
.wrap{max-width:560px;margin:-44px auto 40px;padding:0 14px;position:relative}
.seg{display:flex;background:#fff;border-radius:40px;padding:5px;box-shadow:0 6px 22px #34502a22;margin-bottom:16px}
.seg button{flex:1;border:0;background:none;padding:10px 4px;border-radius:30px;font:inherit;font-size:14px;color:var(--mut);transition:.2s}
.seg button.on{background:linear-gradient(135deg,var(--g1),var(--g2));color:#fff;font-weight:500;box-shadow:0 4px 12px #5f8a3555}
.card{background:#fff;border-radius:var(--r);padding:18px;margin-bottom:14px;box-shadow:0 2px 14px #34502a12;animation:up .4s both}
@keyframes up{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:none}}
.st{display:flex;align-items:center;gap:10px;margin:0 0 14px;font-size:16px;font-weight:600}
.st i{font-style:normal;width:26px;height:26px;border-radius:50%;background:#fbefd0;color:#8a5d0a;display:grid;place-items:center;font-size:13px}
.st small{font-weight:300;color:var(--mut);font-size:12px}
.svs{display:grid;gap:10px}
.sv{display:flex;gap:14px;align-items:center;text-align:left;width:100%;padding:14px;border:1.5px solid var(--line);border-radius:14px;background:#fff;font:inherit;transition:.2s}
.sv .ic{font-size:28px;width:52px;height:52px;border-radius:14px;background:var(--g3);display:grid;place-items:center;flex:none}
.sv b{display:block;font-size:15px}.sv span{font-size:12.5px;color:var(--mut)}
.sv.on{border-color:var(--g2);background:#f8f7e8;box-shadow:0 4px 14px #5f8a3525}
.sv.on .ic{background:var(--g2)}
.scroll{display:flex;gap:10px;overflow-x:auto;padding:2px 2px 8px;scroll-snap-type:x mandatory;scrollbar-width:none}.scroll::-webkit-scrollbar{display:none}
.dc{flex:none;width:64px;padding:10px 0;text-align:center;border:1.5px solid var(--line);border-radius:14px;background:#fff;font:inherit;scroll-snap-align:start;transition:.2s}
.dc small{display:block;font-size:11px;color:var(--mut)}.dc b{display:block;font-size:22px;line-height:1.2;font-family:'Noto Serif Thai',serif}
.dc.on{background:linear-gradient(160deg,var(--g1),var(--g2));border-color:transparent;color:#fff}.dc.on small{color:#ffffffbb}
.dc:disabled{background:#f1eee2;color:#b9b49e;border-style:dashed}
.dc em{display:block;font-style:normal;font-size:10px;color:#c0563b;margin-top:2px}
.slots{display:grid;grid-template-columns:repeat(3,1fr);gap:10px}
.sl{padding:12px 0;border:1.5px solid var(--line);border-radius:12px;background:#fff;font:inherit;font-size:15px;font-weight:500;transition:.2s}
.sl.on{background:var(--g2);border-color:var(--g2);color:#fff;box-shadow:0 4px 12px #5f8a3544}
.sl:disabled{background:#f1eee2;color:#b9b49e;text-decoration:line-through;font-weight:400}
.hint{color:var(--mut);font-size:13px;text-align:center;padding:10px 0}
label{display:block;font-size:13px;color:var(--mut);margin:0 0 6px 2px}
input{width:100%;padding:13px 14px;border:1.5px solid var(--line);border-radius:12px;font:inherit;margin-bottom:12px;background:#fffdf6;transition:.2s}
input:focus{outline:0;border-color:var(--g2);box-shadow:0 0 0 4px #5f8a351f}
.sum{background:var(--g3);border-radius:12px;padding:12px 14px;font-size:13.5px;margin-bottom:12px;color:var(--g1);line-height:1.6}
.btn{width:100%;padding:15px;border:0;border-radius:14px;background:linear-gradient(135deg,var(--g1),var(--g2));color:#fff;font:inherit;font-size:16px;font-weight:600;box-shadow:0 8px 20px #5f8a3544;transition:.2s}
.btn:active{transform:scale(.98)}.btn:disabled{opacity:.6}
.btn.s{width:auto;padding:7px 14px;font-size:13px;background:#fff;color:#c0392b;border:1.5px solid #f0c9c4;box-shadow:none;font-weight:500}
.ok{text-align:center;background:linear-gradient(160deg,#f8f7e8,#fff);border:1.5px solid #dcd29a;padding:26px 18px}
.ok .big{font-size:46px}.ok h2{font-family:'Noto Serif Thai',serif;color:var(--g1);margin:6px 0}
.err{background:#fdecea;color:#b3261e;padding:12px 14px;border-radius:12px;margin-bottom:14px;font-size:14px}
.item{display:flex;justify-content:space-between;align-items:center;gap:10px;padding:12px 0;border-bottom:1px dashed var(--line)}
.item:last-child{border:0}.item .t{font-weight:500;font-size:14.5px}.item .m{color:var(--mut);font-size:12.5px}
.pill{background:#fbefd0;color:#8a5d0a;padding:3px 10px;border-radius:20px;font-size:12.5px;font-weight:500;white-space:nowrap}
.gold{color:var(--gold)}
.hide{display:none!important}
footer{text-align:center;color:var(--mut);font-size:12px;padding:0 0 30px}
.qt{padding:10px 0;text-align:center;border-radius:12px;font-size:14px;font-weight:500}.qt small{display:block;font-weight:300;font-size:11px}.qt.f{background:var(--g3);color:var(--g1)}.qt.b{background:#fbe3dc;color:#b04a2f}.qt.p{background:#f1eee2;color:#b9b49e}
.ch{display:flex;justify-content:space-between;align-items:center;margin-bottom:10px}.ch b{font-family:'Noto Serif Thai',serif;color:var(--g1);font-size:16px}
.ch button{width:38px;height:38px;border-radius:50%;border:1.5px solid var(--line);background:#fff;font-size:20px;color:var(--g1);cursor:pointer}.ch button:disabled{opacity:.3}
.cg{display:grid;grid-template-columns:repeat(7,1fr);gap:6px}.cw{text-align:center;font-size:12px;color:var(--mut);padding:4px 0}
.cd{aspect-ratio:1;border:1.5px solid var(--line);border-radius:12px;background:#fff;font:inherit;font-size:15px;line-height:1.1;padding:0;display:flex;flex-direction:column;align-items:center;justify-content:center;cursor:pointer;color:var(--ink)}
.cd small{font-size:9px;color:#c0563b;margin-top:2px}.cd.td{border-color:var(--gold)}
.cd.on{background:linear-gradient(160deg,var(--g1),var(--g2));color:#fff;border-color:transparent}
.cd:disabled{background:#f1eee2;color:#b9b49e;border-color:transparent;cursor:default}.cd.dof:disabled{background:#fbe3dc;color:#b04a2f}
</style></head><body>
<div class="hero"><div class="in">
 <span class="badge">🌿 คลินิกแพทย์แผนไทย</span>
 <h1>จองคิวนวด อบ ประคบ<br>ง่ายๆ ในไม่กี่ขั้นตอน</h1>
 <p id="hi">กำลังเข้าสู่ระบบ LINE...</p>
 <div class="leaf">🍃</div>
</div></div>
<div class="wrap">
<div class="seg"><button class="on" data-t="b">จองคิว</button><button data-t="q">คิวที่ยืนยันแล้ว</button><button data-t="a">เจ้าหน้าที่</button></div>
<div id="err" class="err hide"></div>
<section id="b">
 <div class="card"><div class="st"><i>1</i>เลือกบริการ</div><div class="svs" id="sv"></div></div>
 <div class="card"><div class="st"><i>2</i><div>เลือกวัน<br><small>เปิดจอง จันทร์–ศุกร์ · จองล่วงหน้าได้หลายเดือน</small></div></div>
  <div class="ch"><button id="cprev">‹</button><b id="mt"></b><button id="cnext">›</button></div><div class="cg" id="cg"></div>
  <div class="hint" style="text-align:left;margin-top:8px">เสาร์–อาทิตย์ปิดทำการ · "ไม่อยู่" = แพทย์แผนไทยไม่อยู่ · "เต็ม" = คิวเต็มแล้ว</div></div>
 <div class="card"><div class="st"><i>3</i>เลือกเวลา</div><div class="slots" id="sl"></div><div class="hint" id="slh">กรุณาเลือกวันก่อน</div></div>
 <div class="card"><div class="st"><i>4</i>ข้อมูลผู้จอง</div>
  <label>ชื่อ-นามสกุล</label><input id="nm" placeholder="เช่น สมชาย ใจดี">
  <label>เบอร์โทรศัพท์</label><input id="ph" type="tel" inputmode="numeric" placeholder="0812345678">
  <div class="sum" id="sum">ยังไม่ได้เลือกรายการ</div>
  <button class="btn" id="go">ยืนยันการจอง</button></div>
 <div id="done" class="card ok hide"></div>
</section>
<section id="q" class="hide"><div class="card"><div class="st"><i>📅</i>ดูสถานะคิวรายวัน</div>
 <input id="qd" type="date"><div class="slots" id="qs"></div><div class="hint" id="qh">เลือกวันที่เพื่อดูคิวว่าง / คิวที่ยืนยันแล้ว</div></div></section>
<section id="a" class="hide">
 <div class="card" id="lg"><div class="st"><i>🔒</i>เข้าสู่ระบบเจ้าหน้าที่</div><input id="pin" type="password" placeholder="รหัสเจ้าหน้าที่"><button class="btn" id="li">เข้าสู่ระบบ</button></div>
 <div id="ad" class="hide">
  <div class="card"><div class="st"><i>🗓️</i><div>จัดการรายวัน<br><small>เลือกวันที่ เพื่อดูคิวและแจ้งแผนไทยไม่อยู่</small></div></div>
   <label>วันที่</label><input id="cd" type="date"><div class="sum" id="dof"></div>
   <label>เหตุผล (ไปธุระ / อบรม / วันหยุดพิเศษ)</label><input id="cn" placeholder="เช่น ไปธุระ">
   <button class="btn" id="cs">บันทึกวันที่แผนไทยไม่อยู่</button>
   <div style="height:10px"></div><button class="btn s hide" id="cr">ยกเลิกวันหยุดของวันนี้</button>
   <div class="hint">ถ้ามีคิวที่ยืนยันแล้ว ต้องยกเลิกคิวก่อน ระบบจะแจ้งผู้จองทาง LINE</div></div>
  <div class="card"><div class="st"><i>📋</i>คิวของวันที่เลือก</div><div id="bl"></div></div>
 </div>
</section>
<footer>🌿 ขอบคุณที่ใช้บริการ</footer>
</div>
<script>
const LIFF_ID='2012052461-iCqWd1tf';
const API_URL='https://script.google.com/macros/s/AKfycbxhHQdYwRwQr6OiU22Uu_bnf2CmcL6bkK2grPmyuxyaxdAAlIDDV4fB9L3CU3mfPTqv/exec';
const SV=[{n:'นวดแผนไทย',i:'💆',d:'คลายกล้ามเนื้อ ปรับสมดุลร่างกาย'},{n:'อบสมุนไพร',i:'♨️',d:'ไอน้ำสมุนไพร ผ่อนคลาย ขับเหงื่อ'},{n:'ประคบสมุนไพร',i:'🌿',d:'ลูกประคบร้อน บรรเทาปวดเมื่อย'}];
const $=s=>document.querySelector(s);
const run=async(f,...a)=>{
 const r=await fetch(API_URL,{method:'POST',headers:{'Content-Type':'text/plain;charset=utf-8'},body:JSON.stringify({f,a})});
 const j=await r.json().catch(()=>{throw new Error('เชื่อมต่อหลังบ้านไม่ได้ ตรวจ API_URL และการ Deploy')});
 if(!j.ok)throw new Error(j.error);
 return j.data;
};
const dt=k=>new Date(k+'T00:00:00');
const th=k=>dt(k).toLocaleDateString('th-TH',{weekday:'short',day:'numeric',month:'short',year:'2-digit'});
const esc=s=>String(s).replace(/[&<>"]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c]));
const key=d=>d.getFullYear()+'-'+String(d.getMonth()+1).padStart(2,'0')+'-'+String(d.getDate()).padStart(2,'0');
let AV={},S={},tok='',pin='';
function err(e){const x=$('#err');x.textContent=e?(e.message||e):'';x.classList.toggle('hide',!e);if(e)scrollTo({top:0,behavior:'smooth'})}
async function av(d,force){if(force||!AV[d])AV[d]=await run('getAvailability',d);return AV[d]}
document.querySelectorAll('.seg button').forEach(b=>b.onclick=()=>{
 document.querySelectorAll('.seg button').forEach(x=>x.classList.toggle('on',x==b));
 ['b','q','a'].forEach(i=>$('#'+i).classList.toggle('hide',i!=b.dataset.t));err();});
const AHEAD_MONTHS=3,TODAY=key(new Date());
const MAXD=(()=>{const d=new Date();d.setMonth(d.getMonth()+AHEAD_MONTHS);return key(d)})();
const MN=['มกราคม','กุมภาพันธ์','มีนาคม','เมษายน','พฤษภาคม','มิถุนายน','กรกฎาคม','สิงหาคม','กันยายน','ตุลาคม','พฤศจิกายน','ธันวาคม'];
let V={y:new Date().getFullYear(),m:new Date().getMonth()},MS={};
async function loadMS(){
 const id=V.y+'-'+V.m;if(MS[id])return;MS[id]={dayOffs:{},full:[]};
  try{MS[id]=(await run('getMonthStatus',key(new Date(V.y,V.m,1)),key(new Date(V.y,V.m+1,0))))||{dayOffs:{},full:[]}}catch(e){err(e)}
 renderCal();
}
function renderCal(){
 const st=MS[V.y+'-'+V.m]||{dayOffs:{},full:[]},now=new Date(),mx=new Date(MAXD+'T00:00:00');
 $('#mt').textContent=MN[V.m]+' '+(V.y+543);
 const first=new Date(V.y,V.m,1).getDay(),n=new Date(V.y,V.m+1,0).getDate();
 let h=['อา','จ','อ','พ','พฤ','ศ','ส'].map(x=>`<div class="cw">${x}</div>`).join('')+'<div></div>'.repeat(first);
 for(let d=1;d<=n;d++){const x=new Date(V.y,V.m,d),k=key(x),wk=x.getDay()%6==0,off=k in st.dayOffs,full=st.full.includes(k),dis=wk||k<TODAY||k>MAXD||off||full;
  h+=`<button class="cd${S.date==k?' on':''}${k==TODAY?' td':''}${off?' dof':''}" data-v="${k}" ${dis?'disabled':''}>${d}${off?'<small>ไม่อยู่</small>':full?'<small>เต็ม</small>':''}</button>`}
 $('#cg').innerHTML=h;
 $('#cg').querySelectorAll('.cd').forEach(b=>b.onclick=async()=>{S.date=b.dataset.v;S.time='';draw();try{await av(S.date)}catch(e){err(e)}draw()});
 $('#cprev').disabled=V.y*12+V.m<=now.getFullYear()*12+now.getMonth();
 $('#cnext').disabled=V.y*12+V.m>=mx.getFullYear()*12+mx.getMonth();
 loadMS();
}
$('#cprev').onclick=()=>{if(--V.m<0){V.m=11;V.y--}renderCal()};
$('#cnext').onclick=()=>{if(++V.m>11){V.m=0;V.y++}renderCal()};
function draw(){
 $('#sv').innerHTML=SV.map(s=>`<button class="sv${S.service==s.n?' on':''}" data-v="${s.n}"><div class="ic">${s.i}</div><div><b>${s.n}</b><span>${s.d}</span></div></button>`).join('');
 $('#sv').querySelectorAll('button').forEach(b=>b.onclick=()=>{S.service=b.dataset.v;draw()});
 renderCal();
 const a=S.date&&AV[S.date];
 $('#slh').classList.toggle('hide',!!a);$('#slh').textContent=S.date?'กำลังโหลดคิว...':'กรุณาเลือกวันก่อน';
 $('#sl').innerHTML=a?a.slots.map(s=>`<button class="sl${S.time==s.time?' on':''}" data-v="${s.time}" ${s.available?'':'disabled'}>${s.time}</button>`).join(''):'';
 $('#sl').querySelectorAll('button').forEach(b=>b.onclick=()=>{S.time=b.dataset.v;draw()});
 $('#sum').innerHTML=(S.service||S.date||S.time)?`<b>${S.service||'—'}</b><br>📅 ${S.date?th(S.date):'—'} &nbsp; ⏰ ${S.time?S.time+' น.':'—'}`:'ยังไม่ได้เลือกรายการ';
}
async function init(){
 draw();
 try{
  if(!LIFF_ID)throw new Error('ยังไม่ได้ตั้งค่า LIFF_ID');
  await liff.init({liffId:LIFF_ID,withLoginOnExternalBrowser:true});
  if(!liff.isLoggedIn()){
   const u='https://liff.line.me/'+LIFF_ID;
   $('#hi').innerHTML='<a href="'+u+'" target="_top" style="color:#fff;font-weight:600;text-decoration:underline">👉 แตะเพื่อเข้าสู่ระบบด้วย LINE</a>';
   return err('กรุณาเปิดลิงก์จองผ่านแอป LINE: '+u);
  }
  tok=liff.getAccessToken();const p=await liff.getProfile();$('#hi').textContent='สวัสดีคุณ '+p.displayName+' 👋';
  $('#nm').value=p.displayName;
 }catch(e){err(e)}
}
$('#go').onclick=async()=>{
 err();
 if(!S.service||!S.date||!S.time)return err('กรุณาเลือกบริการ วัน และเวลา');
  if(!tok)return err('กรุณาเปิดหน้านี้ผ่านแอป LINE ก่อนจอง');
 const b=$('#go');b.disabled=true;b.textContent='กำลังบันทึก...';
 const d=S.date;
 try{
  const r=await run('createBooking',{service:S.service,date:S.date,time:S.time,name:$('#nm').value,phone:$('#ph').value},tok);
  const x=$('#done');x.classList.remove('hide');
  x.innerHTML=`<div class="big">✅</div><h2>จองคิวสำเร็จ</h2><div class="t"><b>${esc(S.service)}</b><br>${th(S.date)} · ${S.time} น.</div><div class="hint">${esc(r.notificationMessage)}</div>`;
  x.scrollIntoView({behavior:'smooth'});S={};
 }catch(e){err(e)}
 try{await av(d,true)}catch(_){}
 draw();b.disabled=false;b.textContent='ยืนยันการจอง';
};
// ---- แท็บดูคิว ----
$('#qd').min=TODAY;$('#qd').max=MAXD;
$('#qd').onchange=async()=>{
 const d=$('#qd').value;if(!d)return;err();$('#qh').classList.remove('hide');$('#qh').textContent='กำลังโหลด...';$('#qs').innerHTML='';
 try{const a=await av(d,true);
  if(a.isWeekend||a.isDayOff){$('#qh').textContent=a.isWeekend?'คลินิกหยุดเสาร์-อาทิตย์':'แผนไทยไม่อยู่: '+a.dayOffReason;return}
  $('#qh').classList.add('hide');
  $('#qs').innerHTML=a.slots.map(s=>`<div class="qt ${s.booked?'b':s.past?'p':'f'}">${s.time}<small>${s.booked?'จองแล้ว':s.past?'ผ่านแล้ว':'ว่าง'}</small></div>`).join('');
 }catch(e){err(e)}
};
// ---- เจ้าหน้าที่ ----
async function loadA(){
 const d=$('#cd').value;if(!d)return;
 try{const r=await run('getAdminData',pin,d);
  $('#dof').innerHTML=r.dayOff?'🚫 วันนี้แผนไทยไม่อยู่: '+esc(r.dayOff.reason):'✅ วันนี้เปิดให้บริการตามปกติ';
  $('#cr').classList.toggle('hide',!r.dayOff);
  $('#bl').innerHTML=r.bookings.length?r.bookings.map(b=>`<div class="item"><div><div class="t">${b.time} น. · ${esc(b.service)}</div><div class="m">${esc(b.name)} · ${esc(b.phone)} · ${b.status=='CONFIRMED'?'ยืนยันแล้ว':'ยกเลิกแล้ว'}</div></div>${b.status=='CONFIRMED'?`<button class="btn s" data-i="${b.id}">ยกเลิก</button>`:''}</div>`).join(''):'<div class="hint">ไม่มีคิวในวันนี้</div>';
  document.querySelectorAll('[data-i]').forEach(b=>b.onclick=async()=>{if(!confirm('ยกเลิกคิวนี้และแจ้งผู้จองทาง LINE?'))return;err();try{await run('cancelBooking',pin,b.dataset.i);delete AV[d];MS={};renderCal();loadA()}catch(e){err(e)}});
 }catch(e){err(e)}
}
$('#li').onclick=async()=>{err();pin=$('#pin').value;try{await run('verifyAdmin',pin);$('#lg').classList.add('hide');$('#ad').classList.remove('hide');$('#cd').value=key(new Date());loadA()}catch(e){err(e)}};
$('#cd').onchange=loadA;
$('#cs').onclick=async()=>{err();const d=$('#cd').value;if(!d)return err('กรุณาเลือกวันที่');
 try{await run('addDayOff',pin,d,$('#cn').value);delete AV[d];MS={};renderCal();loadA()}catch(e){err(e)}};
$('#cr').onclick=async()=>{err();const d=$('#cd').value;try{await run('removeDayOff',pin,d);delete AV[d];MS={};renderCal();loadA()}catch(e){err(e)}};
init();
</script></body></html>

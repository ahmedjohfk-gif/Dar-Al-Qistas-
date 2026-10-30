<!doctype html><html lang="ar" dir="rtl"><head><meta charset="utf-8"><meta name="viewport" content="width=device-width,initial-scale=1"><title>منتدى دار القسطاس</title>
<link href="https://fonts.googleapis.com/css2?family=Amiri:wght@400;700&family=Cairo:wght@400;700&display=swap" rel="stylesheet"><style>
*{box-sizing:border-box}body{margin:0;background:#fff;color:#111;font:16px/1.9 Cairo,Tahoma,sans-serif}a{color:#111}
.wrap{max-width:1000px;margin:auto;padding:0 12px 20px}.hd{background:#000;color:#fff;text-align:center;padding:22px 12px;background:linear-gradient(#000,#222)}.hd h1{margin:0;font:700 clamp(38px,9vw,72px) Amiri,serif}.hd p{margin:4px 0 0;font-size:17px;color:#ddd}.hd .ay{font:700 20px Amiri,serif;margin-top:10px;color:#fff}
.tk{background:#000;color:#fff;overflow:hidden;white-space:nowrap;direction:ltr;padding:7px 0;border-bottom:3px solid #fff;outline:1px solid #000;font-size:15px}
.tk span{display:inline-block;padding-left:100%;direction:rtl;animation:t 32s linear infinite}.tk:hover span{animation-play-state:paused}@keyframes t{to{transform:translateX(-100%)}}
nav{background:#111}nav .wrap{display:flex;flex-wrap:wrap;gap:4px;align-items:center;padding:0 12px}nav button{background:none;color:#fff;padding:8px 14px}nav button:hover{background:#fff;color:#000}nav .sp{flex:1}nav i{color:#fff;font-style:normal;padding:8px}
h2,h3{font-family:Amiri,serif;font-size:24px}.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:12px;margin:22px 0}
.tile{display:flex;flex-direction:column;gap:2px;align-items:center;justify-content:center;min-height:100px;padding:14px;border:2px solid #000;background:#000;color:#fff;font:700 20px Amiri,serif}
.tile span{font:13px Cairo;opacity:.75}.tile:hover{background:#fff;color:#000}.tile:hover span{opacity:.8}
.box{border:1px solid #000}.row{display:flex;justify-content:space-between;gap:10px;padding:10px 14px;border-bottom:1px solid #ddd;cursor:pointer}.row:last-child{border:0}.row:nth-child(even){background:#f5f5f5}.row:hover{background:#e6e6e6}
.mut{color:#666;font-size:13px}.post{border:1px solid #000;margin:14px 0}.post .h{background:#eee;border-bottom:1px solid #000;padding:6px 14px;display:flex;justify-content:space-between;font-size:14px}
.post .b,.page{padding:12px 14px;overflow-wrap:anywhere}.page{border:1px solid #000;font-size:18px}.m{max-width:100%;margin-top:10px;border:1px solid #000;background:#000}
input,textarea{width:100%;padding:9px;border:1px solid #000;font:inherit;background:#fff;margin:4px 0 12px}
button{background:#000;color:#fff;border:0;padding:8px 22px;font:inherit;cursor:pointer}button:hover{background:#444}.s{padding:2px 10px;font-size:13px}.w{background:#fff;color:#000;border:1px solid #000}.w:hover{background:#eee}
.err{background:#000;color:#fff;padding:8px 12px;margin-bottom:12px}.card{max-width:420px;margin:30px auto;border:1px solid #000;padding:20px}footer{text-align:center;padding:20px;color:#666;font-size:13px;border-top:1px solid #000}
.refs{border-top:1px dashed #999;margin-top:12px;padding-top:8px;font-size:14px}.msg{padding:6px 12px;border-bottom:1px solid #eee}.bar{display:flex;gap:8px;margin:14px 0;flex-wrap:wrap}
</style></head><body>
<div class="hd"><h1>منتدى دار القسطاس</h1><p>منتدى أهل الأثر للدروس والرد على شبهات المخالفين</p><div class="ay">﴿قُلْ هَاتُوا بُرْهَانَكُمْ إِنْ كُنْتُمْ صَادِقِينَ﴾</div></div>
<div class="tk"><span>موقع تعليمي علمي فقط — لا يتبنى هذا المنتدى ولا يدعو إلى أي فكر متطرف أو عنف، ونحن سلفيون منهجيون غير تابعين ولا ممولين من أي جماعة متطرفة — غايتنا نشر العلم الشرعي والنقاش العلمي بالدليل &nbsp;&nbsp;✦&nbsp;&nbsp; موقع تعليمي علمي فقط — لا يتبنى هذا المنتدى ولا يدعو إلى أي فكر متطرف أو عنف</span></div>
<nav><div class="wrap" id="nav"></div></nav><div class="wrap" id="app"></div>
<footer>© 2026 منتدى دار القسطاس — جميع الحقوق محفوظة · موقع تعليمي</footer>
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2.45.4/dist/umd/supabase.js"></script>
<script>
const CFG={URL:'https://jejdinzltqxugmlxgabv.supabase.co',KEY:'sb_publishable_-akCooKAiwDb_QFlC6PCOg_EC_U2ZIm'},MAXMB=50;
const SEC=[{k:'rd',n:'الردود على الشبهات',d:'ينشرها المشرفون فقط',t:'p',adm:1},{k:'vd',n:'فيديوهات الدروس',d:'دروس مرئية علمية',t:'p'},{k:'rl',n:'القوانين',d:'ضوابط المنتدى',t:'g'},{k:'mn',n:'منهجنا',d:'من نحن وما غايتنا',t:'g'},
{k:'sh',n:'شيوخنا',d:'علماء نأخذ عنهم',t:'g'},{k:'ch',n:'الشات',d:'محادثة الأعضاء',t:'c'},{k:'ad',n:'حسابات المشرفين',d:'للتواصل مع الإدارة',t:'g'},{k:'ps',n:'المنشورات',d:'مواضيع الأعضاء',t:'p'}];
const DEF={rl:'1) الغرض من المنتدى علمي ديني، ونلتزم بالأدب والأمانة العلمية.\n2) يُمنع منعاً باتاً نشر أي دعوة إلى العنف أو التكفير أو أي فكر متطرف.\n3) الرد على الشبهات يكون بالدليل وبأسلوب علمي هادئ دون سبّ أو تجريح للأشخاص.\n4) يُنقل كلام أهل العلم بأمانة مع ذكر المصدر.\n5) يُمنع الإعلان والروابط المشبوهة والمواضيع خارج اختصاص المنتدى.\n6) فيديوهات الدروس تكون علمية ومن مصادر معروفة.\n7) للمشرفين حذف أي مشاركة مخالفة وحظر صاحبها.',
mn:'منتدى دار القسطاس منتدى ديني علمي، غايته نشر العلم الشرعي والرد على الشبهات بالدليل.\n\nنحن سلفيون منهجيون: نتبع الكتاب والسنة على فهم السلف الصالح.\n\nالمنتدى مستقل، ولسنا تابعين لأي جماعة أو حزب، ولسنا ممولين من أي جماعة متطرفة، ونتبرأ من كل فكر متطرف أو عنفي.\n\nالمنتدى تعليمي فقط.',
sh:'• الشيخ صالح الفوزان\n• الشيخ عبد العزيز بن باز رحمه الله\n• الشيخ محمد بن صالح العثيمين رحمه الله\n• شيخ الإسلام ابن تيمية رحمه الله\n• الإمام ابن القيم رحمه الله\n• الأئمة الأربعة: أبو حنيفة ومالك والشافعي وأحمد رحمهم الله\n• وغيرهم من علماء أهل السنة والجماعة',
ad:'لم تُضف حسابات المشرفين بعد.\n(للمشرف: اضغط «تعديل» وأضف الحسابات.)'};

const $=s=>document.querySelector(s);
const esc=s=>String(s??'').replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
const rich=s=>esc(s).replace(/(https?:\/\/[^\s<]+)/g,'<a href="$1" target="_blank" rel="noopener nofollow">$1</a>').replace(/\n/g,'<br>');
const fd=t=>new Date(t).toLocaleString('ar-EG-u-nu-latn',{dateStyle:'short',timeStyle:'short'});
let sb,me=null,view='home',timer=null;
const un=o=>esc(o.profiles?.username||'محذوف'),sec=k=>SEC.find(s=>s.k==k),adm=()=>me&&me.role=='admin',can=o=>me&&(adm()||me.id==o.user_id);
const q=async p=>{const{data,error}=await p;if(error)throw error;return data},go=x=>{view=x;render()};
const em=n=>[...new TextEncoder().encode(n.toLowerCase())].map(b=>b.toString(16).padStart(2,'0')).join('')+'@users.qistas.app';
const url=p=>sb.storage.from('media').getPublicUrl(p).data.publicUrl,rm=p=>p&&sb.storage.from('media').remove([p]);
const med=o=>o.media_path?(o.media_type=='v'?`<video class="m" controls preload="metadata" src="${url(o.media_path)}"></video>`:`<img class="m" src="${url(o.media_path)}">`):'';
async function up(f){if(!f||!f.size)return{};if(f.size>MAXMB*1048576)throw'حجم الملف أكبر من '+MAXMB+' ميجابايت (للفيديو الأكبر ضع رابط يوتيوب في خانة المراجع)';if(!/^(image|video)\//.test(f.type))throw'نوع الملف غير مدعوم';
const ext=((f.name.split('.').pop()||'bin').toLowerCase().replace(/[^a-z0-9]/g,'').slice(0,5))||'bin',p=`${me.id}/${Date.now()}${Math.random().toString(36).slice(2,7)}.${ext}`;
const{error}=await sb.storage.from('media').upload(p,f,{contentType:f.type});if(error)throw error;return{media_path:p,media_type:f.type[0]=='v'?'v':'i'}}
async function loadMe(){const{data:{session}}=await sb.auth.getSession();me=null;if(session)me=(await sb.from('profiles').select('*').eq('id',session.user.id).maybeSingle()).data}
const mf='<label>صورة أو فيديو (حتى '+MAXMB+' ميجابايت)</label><input type="file" name="media" accept="video/*,image/*">';
const back=k=>`<div class="bar"><button class="w" data-go="home">← الرئيسية</button>${k?`<button class="w" data-go="sec/${k}">← ${sec(k).n}</button>`:''}</div>`;
const trow=t=>`<div class="row" data-go="topic/${t.id}"><div><b>${esc(t.title)}</b><div class="mut">${un(t)} · ${fd(t.created)}</div></div><div class="mut">${t.replies?.[0]?.count||0} ردّ</div></div>`;
const acts=(ty,o)=>can(o)?`<span><button class="s" data-go="edit/${ty}/${o.id}">تعديل</button> <button class="s" data-del="${ty}/${o.id}">حذف</button></span>`:'';
async function loadChat(){const c=$('#cl');if(!c)return;const d=await q(sb.from('chat').select('*,profiles(username)').order('id',{ascending:false}).limit(100));
c.innerHTML=d.reverse().map(m=>`<div class="msg"><b>${un(m)}</b> <span class="mut">${fd(m.created)}</span><br>${rich(m.text)}</div>`).join('')||'<div class="msg mut">لا رسائل بعد.</div>';c.scrollTop=c.scrollHeight}
async function render(){clearInterval(timer);const[v,a,b]=view.split('/');let o='';
$('#nav').innerHTML='<button data-go="home">الرئيسية</button><span class="sp"></span>'+(me?`<i>أهلاً ${esc(me.username)}${adm()?' (مشرف)':''}</i><button data-act="out">خروج</button>`:'<button data-go="login">دخول</button><button data-go="register">تسجيل</button>');
try{
if(v=='home')o=`<div class="grid">${SEC.map(s=>`<button class="tile" data-go="sec/${s.k}">${s.n}<span>${s.d}</span></button>`).join('')}</div>`;
else if(v=='login'||v=='register')o=back()+`<div class="card"><h2>${v=='login'?'تسجيل الدخول':'إنشاء حساب'}</h2><form data-f="${v}"><label>اسم المستخدم</label><input name="name" required><label>كلمة المرور</label><input type="password" name="pass" required><button>${v=='login'?'دخول':'تسجيل'}</button></form></div>`;
else if(v=='sec'){const s=sec(a);o=back()+`<h2>${s.n}</h2>`;
 if(s.t=='g'){const pg=await q(sb.from('pages').select('text').eq('key',a).maybeSingle());o+=`<div class="page">${rich(pg?pg.text:DEF[a])}</div>`+(adm()?`<div class="bar"><button data-go="pg/${a}">تعديل المحتوى</button></div>`:'')}
 else if(s.t=='c')o+='<div class="box" id="cl" style="max-height:380px;overflow:auto"></div>'+(me?'<form data-f="chat" style="margin-top:12px"><input name="text" placeholder="اكتب رسالتك..." maxlength="500" required autocomplete="off"><button>إرسال</button></form>':'<p><a href="#" data-go="login">سجّل دخولك</a> للمشاركة في الشات.</p>');
 else{const ts=await q(sb.from('topics').select('id,title,created,profiles(username),replies(count)').eq('sec',a).order('id',{ascending:false}).limit(100));
  o+=(me&&(!s.adm||adm())?`<div class="bar"><button data-go="new/${a}">+ ${a=='vd'?'فيديو جديد':'موضوع جديد'}</button></div>`:s.adm?'<p class="mut">النشر في هذا القسم للمشرفين فقط، ويمكن للأعضاء الرد.</p>':'<p class="mut">سجّل دخولك للنشر.</p>')+`<div class="box">${ts.map(trow).join('')||'<div class="row">لا توجد مشاركات بعد.</div>'}</div>`}}
else if(v=='pg'){if(!adm())return go('home');const pg=await q(sb.from('pages').select('text').eq('key',a).maybeSingle());o=back(a)+`<h2>تعديل: ${sec(a).n}</h2><form data-f="pg" data-k="${a}"><textarea name="text" rows="14">${esc(pg?pg.text:DEF[a])}</textarea><button>حفظ</button></form>`}
else if(v=='new'){const s=sec(a);if(!me||(s.adm&&!adm()))return go('home');o=back(a)+`<h2>جديد في: ${s.n}</h2><form data-f="new" data-s="${a}"><label>العنوان</label><input name="title" required maxlength="200"><label>النص</label><textarea name="body" rows="9" required></textarea><label>روابط ومراجع (سطر لكل رابط)</label><textarea name="refs" rows="3"></textarea>${mf}<button>نشر</button></form>`}
else if(v=='topic'){const t=await q(sb.from('topics').select('*,profiles(username)').eq('id',a).single()),rs=await q(sb.from('replies').select('*,profiles(username)').eq('topic_id',a).order('id'));
 o=back(t.sec)+`<h2>${esc(t.title)}</h2><div class="post"><div class="h"><span>${un(t)} · ${fd(t.created)}</span>${acts('t',t)}</div><div class="b">${rich(t.body)}${med(t)}${t.refs?`<div class="refs"><b>روابط ومراجع:</b><br>${rich(t.refs)}</div>`:''}</div></div>`
 +rs.map(x=>`<div class="post"><div class="h"><span>${un(x)} · ${fd(x.created)}</span>${acts('r',x)}</div><div class="b">${rich(x.body)}${med(x)}</div></div>`).join('')
 +(me?`<h3>أضف رداً</h3><form data-f="reply" data-t="${t.id}"><textarea name="body" rows="5"></textarea>${mf}<button>إرسال الرد</button></form>`:'<p><a href="#" data-go="login">سجّل دخولك</a> للرد.</p>')}
else if(v=='edit'){const e=await q(sb.from(a=='t'?'topics':'replies').select('*').eq('id',b).single());if(!can(e))return go('home');
 o=back()+`<h2>تعديل</h2><form data-f="edit" data-ty="${a}" data-id="${e.id}">${a=='t'?`<label>العنوان</label><input name="title" value="${esc(e.title)}">`:''}<label>النص</label><textarea name="body" rows="9">${esc(e.body)}</textarea>${a=='t'?`<label>روابط ومراجع</label><textarea name="refs" rows="3">${esc(e.refs)}</textarea>`:''}${mf}${e.media_path?'<label><input type="checkbox" name="rm" style="width:auto"> حذف المرفق الحالي</label>':''}<button>حفظ</button></form>`}
}catch(x){o=back()+'<div class="err">'+esc(x.message||x)+'</div>'}
$('#app').innerHTML=o;scrollTo(0,0);if(v=='sec'&&a=='ch'){loadChat().catch(()=>{});timer=setInterval(()=>loadChat().catch(()=>{}),4000)}}
document.addEventListener('submit',async e=>{e.preventDefault();const f=e.target,d=Object.fromEntries(new FormData(f)),D=f.dataset;
try{switch(D.f){
case'register':{const n=d.name.trim();if(n.length<3||new TextEncoder().encode(n).length>30)throw'اسم المستخدم من 3 أحرف وحتى نحو 15 حرفاً';if(d.pass.length<6)throw'كلمة المرور 6 أحرف على الأقل';
 const{data,error}=await sb.auth.signUp({email:em(n),password:d.pass,options:{data:{username:n}}});if(error)throw/regist|exist|database/i.test(error.message)?'اسم المستخدم مستخدم مسبقاً':error.message;
 if(!data.session)throw'تم إنشاء الحساب، لكن تأكيد البريد مفعّل في Supabase. عطّله من Authentication ثم سجّل الدخول.';await loadMe();go('home');break}
case'login':{const{error}=await sb.auth.signInWithPassword({email:em(d.name.trim()),password:d.pass});if(error)throw'اسم المستخدم أو كلمة المرور غير صحيحة';await loadMe();go('home');break}
case'new':{const m=await up(f.media.files[0]),r=await q(sb.from('topics').insert({sec:D.s,title:d.title.trim(),body:d.body.trim(),refs:d.refs.trim(),...m}).select('id').single());go('topic/'+r.id);break}
case'reply':{const m=await up(f.media.files[0]);if(!d.body.trim()&&!m.media_path)throw'اكتب نص الرد';await q(sb.from('replies').insert({topic_id:+D.t,body:d.body.trim(),...m}));go('topic/'+D.t);break}
case'edit':{const t=D.ty=='t',tb=t?'topics':'replies',old=await q(sb.from(tb).select(t?'media_path':'media_path,topic_id').eq('id',D.id).single()),m=await up(f.media.files[0]),p=t?{title:d.title.trim(),body:d.body.trim(),refs:d.refs.trim()}:{body:d.body.trim()};
 if(m.media_path||d.rm){rm(old.media_path);p.media_path=m.media_path||null;p.media_type=m.media_type||null}await q(sb.from(tb).update(p).eq('id',D.id));go('topic/'+(t?D.id:old.topic_id));break}
case'pg':{await q(sb.from('pages').upsert({key:D.k,text:d.text}));go('sec/'+D.k);break}
case'chat':{await q(sb.from('chat').insert({text:d.text.trim()}));f.reset();loadChat();break}
}}catch(x){let er=f.querySelector('.err');if(!er){er=document.createElement('div');er.className='err';f.prepend(er)}er.textContent=x.message||x}});
document.addEventListener('click',async e=>{const g=e.target.closest('[data-go]');if(g){e.preventDefault();return go(g.dataset.go)}
if(e.target.closest('[data-act=out]')){await sb.auth.signOut();me=null;return go('home')}
const b=e.target.closest('[data-del]');if(!b)return;if(b.dataset.c!=1){b.dataset.c=1;b.textContent='تأكيد؟';return}const[ty,id]=b.dataset.del.split('/');
try{if(ty=='t'){const t=await q(sb.from('topics').select('sec,media_path').eq('id',id).single()),rs=await q(sb.from('replies').select('media_path').eq('topic_id',id));[t,...rs].forEach(x=>rm(x.media_path));await q(sb.from('topics').delete().eq('id',id));go('sec/'+t.sec)}
else{const r=await q(sb.from('replies').select('media_path,topic_id').eq('id',id).single());rm(r.media_path);await q(sb.from('replies').delete().eq('id',id));go('topic/'+r.topic_id)}}
catch(x){$('#app').insertAdjacentHTML('afterbegin','<div class="err">'+esc(x.message||x)+'</div>')}});
(async()=>{if(CFG.URL.startsWith('PUT_')){$('#app').innerHTML='<div class="card"><h2>الموقع غير مربوط بعد</h2><p>ضع رابط Supabase والمفتاح العام في أول السكربت.</p></div>';return}
sb=supabase.createClient(CFG.URL,CFG.KEY);await loadMe().catch(()=>{});render()})();
</script></body></html>

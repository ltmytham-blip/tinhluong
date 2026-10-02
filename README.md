[index.html](https://github.com/user-attachments/files/32970967/index.html)
<!DOCTYPE html><html lang="vi"><head><meta charset="utf-8"><title>LUONG AI – Tính lương giáo viên</title>
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:wght@400;500;700;800&display=swap">
<style>
:root{box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);--bg:#eef3f8;--ink:#1d2a3a;--mute:#5d6b7d;--line:#d6dfea;--in:#fff;--c1:#e6f2ff;--c2:#e5f6ec;--c3:#fff1e0;--c4:#efeafc;--c5:#e3f4f4;--c6:#fdeaf0;--c7:#fff8d9;--c8:#eaf0f7;--net:#16463f;--netink:#fff;--acc:#16463f}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#121a24;--ink:#e6edf5;--mute:#98a6b8;--line:#2e3b4c;--in:#1a2533;--c1:#1b2b40;--c2:#1b3328;--c3:#3a2c1a;--c4:#2a2440;--c5:#17353a;--c6:#3b2230;--c7:#38331a;--c8:#222d3b;--net:#2f8f7d;--acc:#4fc3ad}}
:root[data-theme="dark"]{--bg:#121a24;--ink:#e6edf5;--mute:#98a6b8;--line:#2e3b4c;--in:#1a2533;--c1:#1b2b40;--c2:#1b3328;--c3:#3a2c1a;--c4:#2a2440;--c5:#17353a;--c6:#3b2230;--c7:#38331a;--c8:#222d3b;--net:#2f8f7d;--acc:#4fc3ad}
*,*::before,*::after{box-sizing:inherit}html,body{margin:0}
body{background:var(--bg);color:var(--ink);font:15px/1.5 'Be Vietnam Pro',system-ui,-apple-system,'Segoe UI',Roboto,sans-serif}
header{padding:20px 16px 4px;max-width:1100px;margin:auto}header h1{margin:0;font-size:26px;font-weight:800;letter-spacing:.5px}header p{margin:2px 0 0;color:var(--mute)}header small{color:var(--mute)}
main{max-width:1100px;margin:auto;padding:12px 16px 96px}
.cols{display:grid;grid-template-columns:repeat(auto-fit,minmax(310px,1fr));gap:14px}
.card{border-radius:14px;padding:16px;border:1px solid var(--line)}.card h2{margin:0 0 10px;font-size:16px;font-weight:700}.card h3{font-size:14px;margin:14px 0 6px}
.c1{background:var(--c1)}.c2{background:var(--c2)}.c3{background:var(--c3)}.c4{background:var(--c4)}.c5{background:var(--c5)}.c6{background:var(--c6)}.c7{background:var(--c7)}.c8{background:var(--c8)}.wide{grid-column:1/-1}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:10px}
label{display:block;font-size:13px;color:var(--mute)}
input,textarea{display:block;width:100%;margin-top:3px;padding:9px 10px;font:inherit;color:var(--ink);background:var(--in);border:1px solid var(--line);border-radius:8px}
input:focus-visible,textarea:focus-visible,button:focus-visible,summary:focus-visible{outline:2px solid var(--acc);outline-offset:1px}
.scroll{overflow-x:auto}table{border-collapse:collapse;width:100%;min-width:560px}th,td{padding:4px 6px;text-align:left;font-size:13px}thead th{color:var(--mute);font-weight:500}tbody th{font-weight:500;white-space:nowrap}td input{margin:0;padding:6px 8px}.r{text-align:right;white-space:nowrap}
.kv{display:flex;justify-content:space-between;gap:12px;padding:6px 0;border-top:1px solid var(--line)}.kv:first-child{margin-top:0}[id^=o_]{margin-top:10px}
details>summary{cursor:pointer;color:var(--acc);font-size:13px;padding:6px 0;font-weight:500}.calc{background:var(--in);border:1px solid var(--line);border-radius:8px;padding:6px 12px;font-size:13px}.calc p{margin:8px 0}.calc .tot{font-weight:700}
.set{background:var(--c8);margin-top:14px}.set>summary{list-style:none;color:var(--ink)}.set>summary h2{display:inline;margin:0}.hint{color:var(--mute);font-size:13px}.err{color:#b3261e;font-size:13px;min-height:1em;margin:4px 0}
.net{margin-top:14px;background:var(--net);color:var(--netink);border-radius:18px;padding:22px 20px;box-shadow:0 6px 18px rgba(22,70,63,.25)}.net p{margin:0;font-weight:500;opacity:.9}.net strong{display:block;font-size:clamp(34px,8vw,56px);font-weight:800;line-height:1.15;letter-spacing:-.5px}.net small{opacity:.85}
button{font:inherit;font-weight:500;border:0;border-radius:10px;padding:10px 16px;background:var(--acc);color:#fff;cursor:pointer}button.ghost{background:transparent;color:var(--ink);border:1px solid var(--line)}.set button{margin-top:12px}
.bar{position:fixed;left:0;right:0;bottom:0;display:flex;gap:10px;align-items:center;padding:10px 16px calc(10px + env(safe-area-inset-bottom,0px));background:var(--bg);border-top:1px solid var(--line)}.bar span{color:var(--mute);font-size:13px}
@media (max-width:480px){.grid{grid-template-columns:1fr 1fr}.card{padding:14px}}
@media (prefers-reduced-motion:reduce){*{transition:none!important;animation:none!important}}
</style></head><body>
<header><h1>LUONG AI</h1><p>Tính lương giáo viên - nhanh, rõ ràng, chính xác</p><small>Tác giả: mythamlee · Tính toán ngay trên trình duyệt, dữ liệu không rời khỏi máy bạn.</small></header>
<main id="app"></main>
<script>
(function(g){
const PERIODS=[['hdtn','HĐTN'],['c2','Cấp 2'],['c3','Cấp 3'],['k12','Khối 12'],['ntc2','Nội trú C2'],['ntc3','Nội trú C3'],['nt','Nội trú']];
const EXTRA=[['coithi','Coi thi (tổng số tiết)'],['phudao','Phụ đạo (tổng số tiết)'],['boiduong','Bồi dưỡng (tổng số tiết)']];
const DEFAULT_CONFIG={year:2026,personalDeduction:15500000,dependentDeduction:6200000,
 rates:{bhxh:.08,bhyt:.015,bhtn:.01},union:.005,
 brackets:[{upTo:1e7,rate:.05},{upTo:3e7,rate:.10},{upTo:6e7,rate:.20},{upTo:1e8,rate:.30},{upTo:Infinity,rate:.35}],
 unitPrices:{hdtn:0,c2:0,c3:0,k12:0,ntc2:0,ntc3:0,nt:0}};
EXTRA.forEach(([k])=>DEFAULT_CONFIG.unitPrices[k]=0);
const MAX=1e12;
const fin=x=>Number.isFinite(x)?x:0;
const num=x=>Math.min(MAX,Math.max(0,fin(Number(x))));
function parseMoney(s){
 if(typeof s==='number')return num(s);
 if(s==null)return 0;
 let t=String(s).trim().replace(/[₫đĐ\s]/g,'').replace(/[^\d.,-]/g,'');
 if(!t||t[0]==='-')return 0; // số âm không hợp lệ
 t=t.replace(/-/g,'');
 const d=t.includes('.'),c=t.includes(',');
 if(d&&c){const dec=t.lastIndexOf('.')>t.lastIndexOf(',')?'.':',';const th=dec==='.'?',':'.';t=t.split(th).join('').replace(dec,'.');}
 else if(d||c){const sep=d?'.':',';const parts=t.split(sep);
  if(parts.length>2||(parts.length===2&&/^\d{3}$/.test(parts[1])&&parts[0]!==''&&parts[0]!=='0'))t=parts.join('');
  else t=parts.join('.');}
 return num(parseFloat(t));
}
const parseInt0=s=>Math.floor(parseMoney(s));
function formatVND(n){const v=Math.round(fin(n));const neg=v<0;const s=String(Math.abs(v)).replace(/\B(?=(\d{3})+(?!\d))/g,'.');return (neg?'-':'')+s+' đ';}
const formatPct=r=>String(+(r*100).toFixed(4)).replace('.',',')+'%';
const calculateDailyIncome=(agreed,std)=>std>0?num(agreed)/std:0;
const calculateAllowances=a=>['uudai','chunhiem','chucvu','ngutrua','khac'].reduce((s,k)=>s+num(a[k]),0);
function calculateTeachingPay(periods,cfg){
 const rows=PERIODS.map(([k,label])=>{const p=periods[k]||{};const std=num(p.std),act=num(p.act);
  const rate=(p.rate===''||p.rate==null)?num(cfg.unitPrices[k]):num(p.rate);
  const excess=Math.max(0,act-std);return{key:k,label,std,act,excess,rate,amount:excess*rate};});
 return{rows,total:rows.reduce((s,r)=>s+r.amount,0)};
}
function calculateExtraPay(extra,cfg){
 const rows=EXTRA.map(([k,label])=>{const x=extra[k]||{};const count=num(x.count);
  const rate=(x.rate===''||x.rate==null)?num(cfg.unitPrices[k]):num(x.rate);
  return{key:k,label,count,rate,amount:count*rate};});
 return{rows,total:rows.reduce((s,r)=>s+r.amount,0)};
}
const calculateBoardingPay=b=>({base:num(b.amount)*num(b.days),allowance:num(b.allowance),total:num(b.amount)*num(b.days)+num(b.allowance)});
const calculateGrossIncome=p=>num(p.byDays)+num(p.other)+num(p.teaching)+num(p.boarding)+num(p.extra)+num(p.summer)+num(p.adjUp)-num(p.adjDown);
function calculateInsurance(base,cfg){const b=num(base);const r=cfg.rates;
 const bhxh=b*r.bhxh,bhyt=b*r.bhyt,bhtn=b*r.bhtn;return{base:b,bhxh,bhyt,bhtn,total:bhxh+bhyt+bhtn};}
const calculateUnionFee=(base,cfg)=>num(base)*cfg.union;
function calculateTaxableIncome(gross,insurance,deps,cfg,otherDeduction=0){
 const d=Math.max(0,Math.floor(fin(deps)));
 const family=cfg.personalDeduction+cfg.dependentDeduction*d;
 const raw=fin(gross)-insurance-family-num(otherDeduction);
 return{family,dependents:d,taxable:Math.max(0,raw)};
}
function calculatePersonalIncomeTax(taxable,cfg){
 let prev=0,tax=0;const steps=[];const t=Math.max(0,fin(taxable));
 for(const b of cfg.brackets){
  const amt=Math.max(0,Math.min(t,b.upTo)-prev);
  steps.push({from:prev,to:b.upTo,rate:b.rate,amount:amt,tax:amt*b.rate});
  tax+=amt*b.rate;prev=b.upTo;if(t<=b.upTo)break;}
 return{tax,steps};
}
function calculateNetSalary(gross,deductions){return Math.round(gross)-deductions;}
function calculateAll(inp,cfg=DEFAULT_CONFIG){
 const daily=calculateDailyIncome(inp.agreed,num(inp.stdDays));
 const byDays=daily*num(inp.workDays);
 const allowances=calculateAllowances(inp.allow||{});
 const teach=calculateTeachingPay(inp.periods||{},cfg);
 const extra=calculateExtraPay(inp.extra||{},cfg);
 const board=calculateBoardingPay(inp.boarding||{});
 const gross=calculateGrossIncome({byDays,other:allowances,teaching:teach.total,extra:extra.total,boarding:board.total,summer:inp.summer,adjUp:inp.adjUp,adjDown:inp.adjDown});
 const ins=calculateInsurance(inp.bhBase,cfg);
 const union=calculateUnionFee(inp.bhBase,cfg);
 const tx=calculateTaxableIncome(gross,ins.total,inp.dependents,cfg);
 const pit=calculatePersonalIncomeTax(tx.taxable,cfg);
 const R={gross:Math.round(gross),insurance:Math.round(ins.total),union:Math.round(union),tax:Math.round(pit.tax)};
 R.deductions=R.insurance+R.union+R.tax;
 R.net=calculateNetSalary(gross,R.deductions);
 return{daily,byDays,allowances,teach,extra,board,gross,ins,union,tx,pit,R};
}
const api={PERIODS,EXTRA,calculateExtraPay,DEFAULT_CONFIG,parseMoney,parseInt0,formatVND,formatPct,calculateDailyIncome,calculateAllowances,calculateTeachingPay,calculateBoardingPay,calculateGrossIncome,calculateInsurance,calculateUnionFee,calculateTaxableIncome,calculatePersonalIncomeTax,calculateNetSalary,calculateAll};
if(typeof module!=='undefined')module.exports=api;else g.LuongEngine=api;
})(typeof window!=='undefined'?window:globalThis);

</script><script>
(function(){
const E=LuongEngine,$=s=>document.querySelector(s),KEY='luongai.v1';
const clone=o=>JSON.parse(JSON.stringify(o,(k,v)=>v===Infinity?'inf':v),(k,v)=>v==='inf'?Infinity:v);
let cfg=clone(E.DEFAULT_CONFIG),S={},msg='';
const now=new Date();
const DEF={month:String(now.getMonth()+1),year:'2026',dependents:'0',workDays:'',stdDays:'26'};
const money=n=>E.formatVND(n);
const fnum=n=>{const s=String(+n.toFixed(4));const[a,b]=s.split('.');return a.replace(/\B(?=(\d{3})+(?!\d))/g,'.')+(b?','+b:'');};
const esc=s=>String(s).replace(/[&<>"]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c]));
const mf=(id,l)=>`<label>${l}<input data-k="${id}" data-t="m" inputmode="decimal" autocomplete="off"></label>`;
const tf=(id,l)=>`<label>${l}<input data-k="${id}" data-t="t" autocomplete="off"></label>`;
const nf=(id,l)=>`<label>${l}<input data-k="${id}" data-t="i" inputmode="numeric" autocomplete="off"></label>`;
const card=(cls,title,body)=>`<section class="card ${cls}"><h2>${title}</h2>${body}</section>`;
const per=E.PERIODS.map(([k,l])=>`<tr><th>${l}</th><td><input data-k="p_${k}_std" data-t="m" inputmode="decimal" aria-label="${l} tiết chuẩn"></td><td><input data-k="p_${k}_act" data-t="m" inputmode="decimal" aria-label="${l} tiết thực hiện"></td><td id="ex_${k}" class="r">0</td><td><input data-k="p_${k}_rate" data-t="m" inputmode="decimal" placeholder="mặc định" aria-label="${l} đơn giá"></td><td id="am_${k}" class="r">0 đ</td></tr>`).join('');
const xrows=E.EXTRA.map(([k,l])=>`<tr><th>${l}</th><td><input data-k="x_${k}_n" data-t="m" inputmode="decimal" aria-label="${l} số tiết"></td><td><input data-k="x_${k}_rate" data-t="m" inputmode="decimal" placeholder="mặc định" aria-label="${l} đơn giá"></td><td id="xa_${k}" class="r">0 đ</td></tr>`).join('');
const settings=`<details class="card set"><summary><h2>Cài đặt chính sách</h2></summary><p class="hint">Khi chính sách thay đổi, chỉ cần sửa các giá trị ở đây — công thức không đổi. Giá trị mặc định theo quy định thuế TNCN áp dụng từ năm 2026; hãy đối chiếu với văn bản hiện hành trước khi dùng chính thức.</p><div class="grid">
${['year:Năm','personal:Giảm trừ bản thân (đ/tháng)','dependent:Giảm trừ mỗi người phụ thuộc (đ/tháng)','bhxh:BHXH (%)','bhyt:BHYT (%)','bhtn:BHTN (%)','union:Công đoàn (%)'].map(x=>{const[i,l]=x.split(':');return`<label>${l}<input data-c="${i}" inputmode="decimal"></label>`}).join('')}</div>
<label>Biểu thuế lũy tiến (mỗi dòng: ngưỡng trên | thuế suất %; dòng cuối dùng ∞)<textarea data-c="brackets" rows="5"></textarea></label><p id="brErr" class="err"></p>
<h3>Đơn giá tiết mặc định (đ/tiết)</h3><div class="grid">${E.PERIODS.concat(E.EXTRA).map(([k,l])=>`<label>${l}<input data-c="up_${k}" inputmode="decimal"></label>`).join('')}</div>
<button type="button" id="resetCfg" class="ghost">Khôi phục cấu hình mặc định</button></details>`;
$('#app').innerHTML=`<div class="cols">
${card('c1','Thông tin cá nhân',`<div class="grid">${tf('name','Họ tên')}${tf('code','Mã CB/GV')}${tf('unit','Đơn vị')}${tf('role','Chức vụ')}${nf('month','Tháng')}${nf('year','Năm')}${nf('dependents','Số người phụ thuộc')}</div>`)}
${card('c2','Thu nhập',`<div class="grid">${mf('agreed','Thu nhập thỏa thuận (đ)')}${mf('workDays','Ngày công')}${mf('stdDays','Ngày công chuẩn')}${mf('summer','Lương hè (đ)')}${mf('adjUp','Điều chỉnh tăng (đ)')}${mf('adjDown','Điều chỉnh giảm (đ)')}</div><div id="o_inc"></div>`)}
${card('c3','Phụ cấp',`<div class="grid">${mf('a_uudai','Phụ cấp ưu đãi')}${mf('a_chunhiem','Phụ cấp chủ nhiệm')}${mf('a_chucvu','Chức vụ/trách nhiệm')}${mf('a_ngutrua','Quản lý HS ngủ trưa')}${mf('a_khac','Phụ cấp khác')}</div><div id="o_all"></div>`)}
${card('c4 wide','Tiết dạy',`<div class="scroll"><table><thead><tr><th>Loại tiết</th><th>Chuẩn</th><th>Thực hiện</th><th>Vượt</th><th>Đơn giá</th><th>Thành tiền</th></tr></thead><tbody>${per}</tbody></table></div><div id="o_teach"></div>`)}
${card('c4 wide','Coi thi, phụ đạo, bồi dưỡng',`<div class="scroll"><table><thead><tr><th>Hạng mục</th><th>Số tiết</th><th>Đơn giá</th><th>Thành tiền</th></tr></thead><tbody>${xrows}</tbody></table></div><div id="o_extra"></div>`)}
${card('c5','Nội trú',`<div class="grid">${mf('b_amount','Mức tiền (đ/ngày)')}${mf('b_days','Ngày công nội trú')}${mf('b_allow','Phụ cấp nội trú (đ)')}</div><div id="o_board"></div>`)}
${card('c6','Bảo hiểm & công đoàn',`${mf('bhBase','Mức lương tham gia BHXH (đ)')}<div id="o_ins"></div>`)}
${card('c7','Thuế TNCN',`<div id="o_tax"></div>`)}
${card('c8 wide','Tổng kết',`<div id="o_sum"></div>`)}
</div><div id="o_net"></div>${settings}
<div class="bar"><button type="button" id="save">Lưu bảng lương</button><button type="button" id="clear" class="ghost">Xóa dữ liệu</button><span id="st" role="status"></span></div>`;
const get=k=>S[k]??DEF[k]??'';
const P=id=>E.parseMoney(get(id));
function inputs(){const periods={};E.PERIODS.forEach(([k])=>periods[k]={std:P(`p_${k}_std`),act:P(`p_${k}_act`),rate:get(`p_${k}_rate`)===''?'':P(`p_${k}_rate`)});
 const extra={};E.EXTRA.forEach(([k])=>extra[k]={count:P(`x_${k}_n`),rate:get(`x_${k}_rate`)===''?'':P(`x_${k}_rate`)});const std=P('stdDays');return{agreed:P('agreed'),workDays:get('workDays')===''?std:P('workDays'),stdDays:std,bhBase:P('bhBase'),dependents:E.parseInt0(get('dependents')),summer:P('summer'),adjUp:P('adjUp'),adjDown:P('adjDown'),
 allow:{uudai:P('a_uudai'),chunhiem:P('a_chunhiem'),chucvu:P('a_chucvu'),ngutrua:P('a_ngutrua'),khac:P('a_khac')},periods,extra,boarding:{amount:P('b_amount'),days:P('b_days'),allowance:P('b_allow')}};}
const det=(id,rows,total)=>`<details data-id="${id}"><summary>Xem cách tính</summary><div class="calc">${rows.map(r=>`<p>${r}</p>`).join('')}${total?`<p class="tot">${total}</p>`:''}</div></details>`;
const line=(l,v)=>`<div class="kv"><span>${l}</span><b>${v}</b></div>`;
function render(){
 const open=[...document.querySelectorAll('details[data-id][open]')].map(d=>d.dataset.id);
 const i=inputs(),r=E.calculateAll(i,cfg),R=r.R,pc=E.formatPct;
 $('#o_inc').innerHTML=line('Thu nhập theo ngày công',money(r.byDays))+line('Tổng thu nhập',money(R.gross))+det('inc',[
  `Thu nhập/ngày = ${money(i.agreed)} ÷ ${fnum(i.stdDays)} ngày = ${money(r.daily)}`,
  `Theo ngày công = ${money(r.daily)} × ${fnum(i.workDays)} = ${money(r.byDays)}`,
  `+ Phụ cấp/khác ${money(r.allowances)} + Tiết vượt ${money(r.teach.total)} + Coi thi/phụ đạo/bồi dưỡng ${money(r.extra.total)} + Nội trú ${money(r.board.total)}`,
  `+ Lương hè ${money(i.summer)} + Điều chỉnh tăng ${money(i.adjUp)} − Điều chỉnh giảm ${money(i.adjDown)}`],`Tổng thu nhập = ${money(R.gross)}`);
 $('#o_all').innerHTML=line('Tổng phụ cấp',money(r.allowances));
 r.teach.rows.forEach(x=>{$('#ex_'+x.key).textContent=fnum(x.excess);$('#am_'+x.key).textContent=money(x.amount)});
 $('#o_teach').innerHTML=line('Tổng thù lao tiết vượt',money(r.teach.total))+det('teach',r.teach.rows.filter(x=>x.excess>0).map(x=>`${x.label}: vượt = max(0, ${fnum(x.act)} − ${fnum(x.std)}) = ${fnum(x.excess)} tiết × ${money(x.rate)} = ${money(x.amount)}`).concat(r.teach.total===0?['Chưa có tiết vượt.']:[]),`Tổng = ${money(r.teach.total)}`);
 r.extra.rows.forEach(x=>$('#xa_'+x.key).textContent=money(x.amount));
 $('#o_extra').innerHTML=line('Tổng coi thi, phụ đạo, bồi dưỡng',money(r.extra.total))+det('extra',r.extra.rows.filter(x=>x.amount>0).map(x=>`${x.label}: ${fnum(x.count)} tiết × ${money(x.rate)} = ${money(x.amount)}`).concat(r.extra.total===0?['Chưa nhập số tiết hoặc đơn giá.']:[]),`Tổng = ${money(r.extra.total)}`);
 $('#o_board').innerHTML=line('Thu nhập nội trú',money(r.board.total))+det('board',[`${money(i.boarding.amount)} × ${fnum(i.boarding.days)} ngày = ${money(r.board.base)}`,`+ Phụ cấp ${money(r.board.allowance)}`],`Nội trú = ${money(r.board.total)}`);
 const c=cfg.rates;
 $('#o_ins').innerHTML=line('Bảo hiểm bắt buộc',money(R.insurance))+line('Công đoàn',money(R.union))+det('ins',[`BHXH<br>${money(i.bhBase)} × ${pc(c.bhxh)} = ${money(r.ins.bhxh)}`,`BHYT<br>${money(i.bhBase)} × ${pc(c.bhyt)} = ${money(r.ins.bhyt)}`,`BHTN<br>${money(i.bhBase)} × ${pc(c.bhtn)} = ${money(r.ins.bhtn)}`],`Tổng bảo hiểm = ${money(R.insurance)}`)+det('uni',[`${money(i.bhBase)} × ${pc(cfg.union)} = ${money(r.union)}`],`Công đoàn = ${money(R.union)}`);
 const T=r.tx;
 $('#o_tax').innerHTML=line('Thu nhập tính thuế',money(T.taxable))+line('Thuế TNCN',money(R.tax))+det('tax',[`Giảm trừ = ${money(cfg.personalDeduction)} + ${money(cfg.dependentDeduction)} × ${T.dependents} người = ${money(T.family)}`,`Thu nhập tính thuế = max(0, ${money(r.gross)} − ${money(r.ins.total)} bảo hiểm − ${money(T.family)}) = ${money(T.taxable)}`].concat(T.taxable>0?r.pit.steps.filter(s=>s.amount>0).map(s=>`Phần ${money(s.from)} → ${s.to===Infinity?'trở lên':money(s.to)}: ${money(s.amount)} × ${pc(s.rate)} = ${money(s.tax)}`):['Không có thu nhập tính thuế → thuế = 0']),`Thuế phải nộp = ${money(R.tax)} (làm tròn ở kết quả cuối)`);
 $('#o_sum').innerHTML=line('Tổng thu nhập',money(R.gross))+line('Bảo hiểm',money(R.insurance))+line('Công đoàn',money(R.union))+line('Thuế TNCN',money(R.tax))+line('Tổng giảm trừ',money(R.deductions))+det('sum',[`${money(R.insurance)} + ${money(R.union)} + ${money(R.tax)} = ${money(R.deductions)}`,`Thực nhận = ${money(R.gross)} − ${money(R.deductions)} = ${money(R.net)}`]);
 const who=[get('name'),get('code')].filter(Boolean).map(esc).join(' · ');
 $('#o_net').innerHTML=`<section class="net"><div><p>THỰC NHẬN tháng ${esc(get('month'))}/${esc(get('year'))}</p><strong>${money(R.net)}</strong>${who?`<small>${who}</small>`:''}</div></section>`;
 open.forEach(id=>{const d=document.querySelector(`details[data-id="${id}"]`);if(d)d.open=true});
}
const st=t=>{$('#st').textContent=t;clearTimeout(st.t);st.t=setTimeout(()=>$('#st').textContent='',2500)};
function save(){try{localStorage.setItem(KEY,JSON.stringify({S,cfg:JSON.parse(JSON.stringify(cfg,(k,v)=>v===Infinity?null:v))}));return true}catch(e){st('Không lưu được: trình duyệt chặn lưu trữ.');return false}}
let tm;const later=()=>{clearTimeout(tm);tm=setTimeout(save,400)};
function load(){try{const d=JSON.parse(localStorage.getItem(KEY)||'null');if(!d)return;S=d.S||{};if(d.cfg){d.cfg.brackets=d.cfg.brackets.map(b=>({...b,upTo:b.upTo==null?Infinity:b.upTo}));cfg={...cfg,...d.cfg,rates:{...cfg.rates,...d.cfg.rates},unitPrices:{...cfg.unitPrices,...d.cfg.unitPrices}}}}catch(e){S={}}}
function fillForm(){document.querySelectorAll('[data-k]').forEach(el=>{el.value=S[el.dataset.k]??(DEF[el.dataset.k]??'')});
 const m={year:cfg.year,personal:fnum(cfg.personalDeduction),dependent:fnum(cfg.dependentDeduction),bhxh:fnum(cfg.rates.bhxh*100),bhyt:fnum(cfg.rates.bhyt*100),bhtn:fnum(cfg.rates.bhtn*100),union:fnum(cfg.union*100)};
 Object.entries(m).forEach(([k,v])=>$(`[data-c="${k}"]`).value=v);E.PERIODS.concat(E.EXTRA).forEach(([k])=>$(`[data-c="up_${k}"]`).value=fnum(cfg.unitPrices[k]));
 $('[data-c="brackets"]').value=cfg.brackets.map(b=>`${b.upTo===Infinity?'∞':b.upTo} | ${+(b.rate*100).toFixed(4)}`).join('\n');}
function parseBr(t){const rows=t.split('\n').map(l=>l.trim()).filter(Boolean).map(l=>{const[a,b]=l.split('|');const inf=/∞|inf/i.test(a)||a.trim()==='';return{upTo:inf?Infinity:E.parseMoney(a),rate:E.parseMoney(b)/100,ok:b!==undefined}});
 if(!rows.length||rows.some(x=>!x.ok||x.rate>1))return null;for(let j=0;j<rows.length;j++){if(j&&rows[j].upTo<=rows[j-1].upTo)return null;if(j<rows.length-1&&rows[j].upTo===Infinity)return null}
 if(rows[rows.length-1].upTo!==Infinity)return null;return rows.map(({upTo,rate})=>({upTo,rate}));}
document.addEventListener('input',e=>{const el=e.target;
 if(el.dataset.k){S[el.dataset.k]=el.value;render();later();}
 else if(el.dataset.c){const k=el.dataset.c,v=el.value;
  if(k==='brackets'){const b=parseBr(v);$('#brErr').textContent=b?'':'Biểu thuế chưa hợp lệ: ngưỡng phải tăng dần, dòng cuối là ∞, thuế suất 0–100%. Đang dùng biểu thuế trước đó.';if(b)cfg.brackets=b}
  else if(k==='year')cfg.year=E.parseInt0(v);else if(k==='personal')cfg.personalDeduction=E.parseMoney(v);else if(k==='dependent')cfg.dependentDeduction=E.parseMoney(v);
  else if(k==='union')cfg.union=E.parseMoney(v)/100;else if(['bhxh','bhyt','bhtn'].includes(k))cfg.rates[k]=E.parseMoney(v)/100;else if(k.startsWith('up_'))cfg.unitPrices[k.slice(3)]=E.parseMoney(v);
  render();later();}});
document.addEventListener('focusout',e=>{const el=e.target,t=el.dataset&&el.dataset.t;if(!t||el.value==='')return;
 if(t==='m'){el.value=fnum(E.parseMoney(el.value))}else if(t==='i'){el.value=String(E.parseInt0(el.value))}S[el.dataset.k]=el.value;render();later();});
$('#save').onclick=()=>{if(save())st('Đã lưu bảng lương.')};
$('#clear').onclick=()=>{if(confirm('Xóa toàn bộ dữ liệu bảng lương đã nhập? Cài đặt chính sách được giữ nguyên.')){S={};save();fillForm();render();st('Đã xóa dữ liệu.')}};
$('#resetCfg').onclick=()=>{if(confirm('Khôi phục cấu hình mặc định?')){cfg=clone(E.DEFAULT_CONFIG);$('#brErr').textContent='';fillForm();render();save()}};
load();fillForm();render();
})();

</script></body></html>

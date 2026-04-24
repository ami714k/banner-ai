<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BannerAI — バナージェネレーター</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@700;800&family=Noto+Sans+JP:wght@300;400;500;700;900&display=swap" rel="stylesheet">
<style>
:root{--bg:#07070e;--s1:#101018;--s2:#17171f;--s3:#1e1e28;--a1:#7c6aff;--a2:#ff6a8a;--a3:#4aefc0;--tx:#f0f0fa;--mu:#5858a0;--bd:#1a1a30;--r:16px;}
*{margin:0;padding:0;box-sizing:border-box;}
body{background:var(--bg);color:var(--tx);font-family:'Noto Sans JP',sans-serif;min-height:100vh;}
body::before{content:'';position:fixed;inset:0;background:radial-gradient(ellipse 60% 50% at 15% 15%,rgba(124,106,255,.1) 0%,transparent 55%),radial-gradient(ellipse 50% 40% at 85% 80%,rgba(255,106,138,.07) 0%,transparent 55%);pointer-events:none;z-index:0;}
.wrap{max-width:1160px;margin:0 auto;padding:0 24px;position:relative;z-index:1;}
header{padding:28px 0 16px;display:flex;align-items:center;gap:10px;}
.logo{font-family:'Syne',sans-serif;font-size:22px;font-weight:800;background:linear-gradient(130deg,var(--a1),var(--a2));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;letter-spacing:-1px;}
.badge{background:rgba(124,106,255,.15);border:1px solid rgba(124,106,255,.3);color:var(--a1);font-size:9px;font-weight:700;padding:3px 8px;border-radius:20px;letter-spacing:1px;}
.hero{margin-bottom:28px;}
.hero h1{font-family:'Syne',sans-serif;font-size:clamp(24px,4vw,44px);font-weight:800;line-height:1.1;letter-spacing:-2px;margin-bottom:8px;}
.hero h1 em{font-style:normal;background:linear-gradient(130deg,var(--a1),var(--a2),var(--a3));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.hero p{color:var(--mu);font-size:13px;line-height:1.7;}
.grid{display:grid;grid-template-columns:380px 1fr;gap:18px;align-items:start;}
@media(max-width:820px){.grid{grid-template-columns:1fr;}}
.panel{background:var(--s1);border:1px solid var(--bd);border-radius:var(--r);padding:22px;}
.plabel{font-family:'Syne',sans-serif;font-size:9px;font-weight:700;letter-spacing:2.5px;text-transform:uppercase;color:var(--mu);margin-bottom:18px;}
.fg{margin-bottom:14px;}
label{display:block;font-size:11px;font-weight:600;color:var(--mu);margin-bottom:5px;}
label .req{color:var(--a2);}
input,textarea,select{width:100%;background:var(--s2);border:1px solid var(--bd);border-radius:8px;color:var(--tx);font-family:'Noto Sans JP',sans-serif;font-size:13px;padding:9px 12px;outline:none;transition:border-color .2s,box-shadow .2s;}
input:focus,textarea:focus,select:focus{border-color:var(--a1);box-shadow:0 0 0 3px rgba(124,106,255,.1);}
textarea{resize:vertical;min-height:60px;}
select option{background:var(--s2);}
.chips{display:flex;flex-wrap:wrap;gap:5px;}
.chip{background:var(--s2);border:1px solid var(--bd);border-radius:6px;color:var(--mu);font-size:10px;font-weight:500;padding:5px 9px;cursor:pointer;transition:all .15s;white-space:nowrap;user-select:none;}
.chip:hover{border-color:var(--a1);color:var(--a1);}
.chip.on{background:rgba(124,106,255,.14);border-color:var(--a1);color:var(--a1);}
.upload-area{background:var(--s2);border:1.5px dashed var(--bd);border-radius:9px;padding:16px;text-align:center;cursor:pointer;transition:all .2s;position:relative;overflow:hidden;}
.upload-area:hover{border-color:var(--a1);}
.upload-area input[type=file]{position:absolute;inset:0;opacity:0;cursor:pointer;width:100%;height:100%;}
.uico{font-size:22px;margin-bottom:4px;opacity:.35;}
.utxt{font-size:10px;color:var(--mu);line-height:1.5;}
#uprev{width:100%;height:64px;object-fit:cover;border-radius:6px;margin-top:6px;display:none;}
.pgrid{display:grid;grid-template-columns:repeat(3,1fr);gap:3px;margin-top:6px;}
.pbtn{background:var(--s3);border:1px solid var(--bd);border-radius:5px;padding:5px 3px;font-size:9px;color:var(--mu);cursor:pointer;text-align:center;transition:all .15s;}
.pbtn:hover,.pbtn.on{background:rgba(124,106,255,.15);border-color:var(--a1);color:var(--a1);}
.btn{width:100%;background:linear-gradient(130deg,var(--a1),var(--a2));border:none;border-radius:10px;color:#fff;font-family:'Syne',sans-serif;font-size:14px;font-weight:700;padding:13px;cursor:pointer;transition:opacity .2s,transform .12s;margin-top:4px;}
.btn:hover{opacity:.88;transform:translateY(-1px);}
.btn:active{transform:translateY(0);}
.hint{background:rgba(124,106,255,.07);border:1px solid rgba(124,106,255,.15);border-radius:8px;padding:11px 13px;font-size:10px;color:var(--mu);line-height:1.8;margin-top:12px;}
.hint strong{color:var(--a1);}
.div{height:1px;background:var(--bd);margin:14px 0;}
.out{display:flex;flex-direction:column;gap:16px;}
.pbox{background:var(--s1);border:1px solid var(--bd);border-radius:var(--r);padding:18px;}
.pc{display:flex;justify-content:center;align-items:center;flex-direction:column;gap:8px;}
.empty{text-align:center;padding:36px 16px;color:var(--mu);}
.eico{font-size:38px;margin-bottom:10px;opacity:.3;}
.empty p{font-size:12px;line-height:1.7;}
.cbox{background:var(--s1);border:1px solid var(--bd);border-radius:var(--r);padding:20px;}
.clist{display:flex;flex-direction:column;gap:10px;}
.ccard{background:var(--s2);border:1.5px solid var(--bd);border-radius:10px;padding:13px;cursor:pointer;transition:all .18s;position:relative;overflow:hidden;}
.ccard::before{content:'';position:absolute;inset:0;background:linear-gradient(130deg,rgba(124,106,255,.07),rgba(255,106,138,.04));opacity:0;transition:opacity .2s;}
.ccard:hover{border-color:var(--a1);}
.ccard:hover::before,.ccard.sel::before{opacity:1;}
.ccard.sel{border-color:var(--a1);}
.cn{font-family:'Syne',sans-serif;font-size:9px;font-weight:700;color:var(--a1);letter-spacing:1.5px;margin-bottom:3px;}
.cname{font-weight:700;font-size:12px;margin-bottom:3px;}
.ccopy{font-size:10px;color:var(--a3);font-style:italic;margin-bottom:5px;}
.cdesc{font-size:9px;color:var(--mu);line-height:1.6;}
.cdots{display:flex;gap:4px;margin-top:7px;align-items:center;}
.dot{width:13px;height:13px;border-radius:50%;border:1.5px solid rgba(255,255,255,.08);}
.dlabel{font-size:9px;color:var(--mu);margin-left:3px;}
.arow{display:flex;gap:6px;flex-wrap:wrap;margin-top:8px;justify-content:center;}
.abtn{background:var(--s2);border:1px solid var(--bd);border-radius:7px;color:var(--mu);font-size:10px;font-family:'Noto Sans JP',sans-serif;padding:7px 12px;cursor:pointer;transition:all .15s;}
.abtn:hover{border-color:var(--a1);color:var(--a1);}
.abtn.g{background:rgba(74,239,192,.1);border-color:rgba(74,239,192,.3);color:var(--a3);}
.abtn.g:hover{background:rgba(74,239,192,.2);}
.slbl{font-size:9px;color:var(--mu);margin-top:6px;}
footer{text-align:center;padding:36px 0 20px;color:var(--mu);font-size:9px;}
@keyframes fu{from{opacity:0;transform:translateY(10px);}to{opacity:1;transform:translateY(0);}}
.fu{animation:fu .32s ease forwards;}
</style>
</head>
<body>
<div class="wrap">
  <header><div class="logo">BannerAI</div><div class="badge">PRO</div></header>
  <div class="hero">
    <h1>情報を入れるだけで<br><em>プロ品質のバナーが生まれる。</em></h1>
    <p>配色・装飾・写真・文字を自動生成。JPG保存対応。APIキー不要で完全無料。</p>
  </div>
  <div class="grid">
    <div class="panel">
      <div class="plabel">バナー情報を入力</div>
      <div class="fg">
        <label>バナーの用途<span class="req">*</span></label>
        <select id="useCase">
          <option value="">選択してください</option>
          <option value="SNS投稿（Instagram）">SNS投稿（Instagram）</option>
          <option value="SNS投稿（Twitter/X）">SNS投稿（Twitter/X）</option>
          <option value="Webサイトのバナー広告">Webサイトのバナー広告</option>
          <option value="LPヘッダー">LPヘッダー</option>
          <option value="メールマガジンヘッダー">メールマガジンヘッダー</option>
          <option value="キャンペーン告知バナー">キャンペーン告知バナー</option>
          <option value="商品・サービス紹介バナー">商品・サービス紹介バナー</option>
          <option value="求人・採用バナー">求人・採用バナー</option>
        </select>
      </div>
      <div class="fg">
        <label>サイズ</label>
        <div class="chips" id="sc">
          <div class="chip on" data-w="600" data-h="600" data-l="1080×1080（正方形）">正方形</div>
          <div class="chip" data-w="600" data-h="314" data-l="1200×628（OGP）">OGP横長</div>
          <div class="chip" data-w="270" data-h="480" data-l="1080×1920（ストーリー）">ストーリー縦</div>
          <div class="chip" data-w="560" data-h="70" data-l="728×90（横長）">横長バナー</div>
          <div class="chip" data-w="360" data-h="300" data-l="300×250（レクタングル）">レクタングル</div>
        </div>
      </div>
      <div class="fg">
        <label>商品・サービス名 / テーマ<span class="req">*</span></label>
        <input type="text" id="product" placeholder="例：夏の新作コスメ、転職サービス">
      </div>
      <div class="fg">
        <label>キャッチコピー（空欄で自動生成）</label>
        <input type="text" id="catch" placeholder="例：あなたの毎日を、もっと輝かせよう。">
      </div>
      <div class="fg">
        <label>サブテキスト</label>
        <input type="text" id="sub" placeholder="例：期間限定キャンペーン実施中">
      </div>
      <div class="fg">
        <label>ターゲット層</label>
        <input type="text" id="target" placeholder="例：20〜30代女性">
      </div>
      <div class="fg">
        <label>雰囲気・トーン</label>
        <select id="tone">
          <option value="auto">おまかせ（自動判断）</option>
          <option value="luxury">高級感・洗練</option>
          <option value="pop">ポップ・かわいい</option>
          <option value="cool">クール・スタイリッシュ</option>
          <option value="natural">ナチュラル・やわらか</option>
          <option value="bold">力強い・インパクト重視</option>
          <option value="minimal">シンプル・ミニマル</option>
          <option value="trust">信頼感・誠実</option>
          <option value="feminine">エレガント・フェミニン</option>
        </select>
      </div>
      <div class="fg">
        <label>写真をアップロード（任意）</label>
        <div class="upload-area">
          <input type="file" id="photo" accept="image/*" onchange="onPhoto(event)">
          <div class="uico">📷</div>
          <div class="utxt">クリックまたはドラッグ＆ドロップ</div>
          <img id="uprev">
        </div>
        <div class="pgrid" id="pg" style="display:none">
          <div class="pbtn on" data-p="left">左配置</div>
          <div class="pbtn" data-p="center">中央</div>
          <div class="pbtn" data-p="right">右配置</div>
          <div class="pbtn" data-p="bg">背景全体</div>
          <div class="pbtn" data-p="top">上部</div>
          <div class="pbtn" data-p="bottom">下部</div>
        </div>
      </div>
      <button class="btn" onclick="gen()">✦ バナーを生成する</button>
      <div class="div"></div>
      <div class="hint"><strong>💡 ヒント</strong><br>コンセプトカードをクリックでデザイン切り替え。JPG保存でそのまま使えます。</div>
    </div>
    <div class="out">
      <div class="pbox">
        <div class="plabel">バナープレビュー</div>
        <div class="pc" id="pa"><div class="empty"><div class="eico">🎨</div><p>左のフォームを入力して<br>「バナーを生成する」を押してください</p></div></div>
      </div>
      <div class="cbox">
        <div class="plabel">デザインコンセプト案</div>
        <div id="ca"><div class="empty" style="padding:16px"><p>生成すると3パターンのコンセプトが表示されます</p></div></div>
      </div>
    </div>
  </div>
  <footer>BannerAI — South Agency AI Contest 2026</footer>
</div>
<script>
let photo=null,ppos='left',concepts=[],si=0,bw=600,bh=600,bl='1080×1080（正方形）';

// size chips
document.querySelectorAll('#sc .chip').forEach(c=>c.addEventListener('click',()=>{
  document.querySelectorAll('#sc .chip').forEach(x=>x.classList.remove('on'));
  c.classList.add('on');bw=+c.dataset.w;bh=+c.dataset.h;bl=c.dataset.l;
}));

// photo pos
document.querySelectorAll('.pbtn').forEach(b=>b.addEventListener('click',()=>{
  document.querySelectorAll('.pbtn').forEach(x=>x.classList.remove('on'));
  b.classList.add('on');ppos=b.dataset.p;
  if(concepts.length)render(concepts[si]);
}));

function onPhoto(e){
  const f=e.target.files[0];if(!f)return;
  const r=new FileReader();
  r.onload=ev=>{photo=ev.target.result;const p=document.getElementById('uprev');p.src=photo;p.style.display='block';document.getElementById('pg').style.display='grid';};
  r.readAsDataURL(f);
}

// ── TONE DATABASE ──
const TD={
  luxury:{
    pals:[
      {n:'ダークゴールド',bg:'#0c0800',bg2:'#1c1200',tx:'#f0dfa0',ac:'#c9a84c',sc:'rgba(240,223,160,.6)',pt:'geometric'},
      {n:'ディープネイビー',bg:'#060c16',bg2:'#0c1826',tx:'#e0eaff',ac:'#8899cc',sc:'rgba(224,234,255,.6)',pt:'lines'},
    ],
    cats:['{p}の新しいスタンダード。','{p}、上質な選択。','本物を、あなたに。'],
  },
  pop:{
    pals:[
      {n:'ビビッドコーラル',bg:'#ff5555',bg2:'#ff8040',tx:'#fff',ac:'#ffd93d',sc:'rgba(255,255,255,.85)',pt:'dots'},
      {n:'ポップミント',bg:'#00c090',bg2:'#00a0cc',tx:'#fff',ac:'#ff6bae',sc:'rgba(255,255,255,.85)',pt:'circles'},
    ],
    cats:['毎日が楽しくなる！{p}','わくわくが止まらない♪{p}','かわいい！{p}'],
  },
  cool:{
    pals:[
      {n:'サイバーブルー',bg:'#050815',bg2:'#090f25',tx:'#c8e0ff',ac:'#00ccff',sc:'rgba(200,224,255,.6)',pt:'grid'},
      {n:'ミッドナイト',bg:'#07000f',bg2:'#100018',tx:'#ddd0ff',ac:'#aa55ff',sc:'rgba(221,208,255,.6)',pt:'diagonal'},
    ],
    cats:['{p}が、常識を変える。','次世代の{p}、ここに。','一歩先を行く{p}。'],
  },
  natural:{
    pals:[
      {n:'アースグリーン',bg:'#eef5ee',bg2:'#e2f0e2',tx:'#183018',ac:'#4caf50',sc:'rgba(24,48,24,.6)',pt:'organic'},
      {n:'テラコッタ',bg:'#f8f0e0',bg2:'#f0e4cc',tx:'#3c2c18',ac:'#c87840',sc:'rgba(60,44,24,.6)',pt:'organic'},
    ],
    cats:['自然の力で、{p}。','{p}、大地からの贈り物。','やさしい{p}で笑顔に。'],
  },
  bold:{
    pals:[
      {n:'レッド×ブラック',bg:'#0c0000',bg2:'#180000',tx:'#fff',ac:'#ff1a1a',sc:'rgba(255,255,255,.75)',pt:'diagonal'},
      {n:'イエロー×ブラック',bg:'#070700',bg2:'#121200',tx:'#fff',ac:'#ffd600',sc:'rgba(255,255,255,.75)',pt:'diagonal'},
    ],
    cats:['圧倒的な{p}。','{p}が、すべてを変える。','今すぐ手に入れろ。{p}。'],
  },
  minimal:{
    pals:[
      {n:'ホワイト×ブラック',bg:'#ffffff',bg2:'#f6f6f6',tx:'#111',ac:'#222',sc:'rgba(17,17,17,.5)',pt:'none'},
      {n:'オフホワイト',bg:'#f4f2ef',bg2:'#eae6e0',tx:'#1a1a1a',ac:'#777',sc:'rgba(26,26,26,.45)',pt:'none'},
    ],
    cats:['{p}。それだけでいい。','シンプルに、{p}。','余計なものは、いらない。'],
  },
  trust:{
    pals:[
      {n:'ネイビー',bg:'#001230',bg2:'#002060',tx:'#fff',ac:'#4d9fff',sc:'rgba(255,255,255,.7)',pt:'lines'},
      {n:'フォレスト',bg:'#08201a',bg2:'#122e24',tx:'#fff',ac:'#4ecb71',sc:'rgba(255,255,255,.7)',pt:'lines'},
    ],
    cats:['{p}で、安心を。','信頼の{p}。','実績が証明する、{p}の力。'],
  },
  feminine:{
    pals:[
      {n:'ローズゴールド',bg:'#fff0f4',bg2:'#ffe0ec',tx:'#48182e',ac:'#d46898',sc:'rgba(72,24,46,.6)',pt:'floral'},
      {n:'ラベンダー',bg:'#f4f0ff',bg2:'#eae0ff',tx:'#2a0e5c',ac:'#9c5fd4',sc:'rgba(42,14,92,.6)',pt:'floral'},
    ],
    cats:['{p}で、もっと美しく。','あなたのための{p}。','上品さを、日常に。'],
  },
  auto:{
    pals:[
      {n:'モダンパープル',bg:'#08081e',bg2:'#0e0e2c',tx:'#fff',ac:'#7c6aff',sc:'rgba(255,255,255,.65)',pt:'geometric'},
      {n:'ウォームアンバー',bg:'#100600',bg2:'#1c0e00',tx:'#fff8e8',ac:'#ff8c42',sc:'rgba(255,248,232,.65)',pt:'geometric'},
      {n:'フレッシュブルー',bg:'#eef6ff',bg2:'#e0f0ff',tx:'#082840',ac:'#2196f3',sc:'rgba(8,40,64,.6)',pt:'lines'},
    ],
    cats:['{p}、新しい体験へ。','選ばれる理由がある。{p}。','{p}で、毎日が変わる。'],
  },
};

function pick(arr){return arr[Math.floor(Math.random()*arr.length)];}

function makeCatch(product,tone){
  const c=document.getElementById('catch').value.trim();
  if(c)return c;
  const short=product.length>10?product.slice(0,10):product;
  return pick(TD[tone]?.cats||TD.auto.cats).replace(/{p}/g,short);
}

function gen(){
  const uc=document.getElementById('useCase').value;
  const pr=document.getElementById('product').value.trim();
  const sb=document.getElementById('sub').value.trim();
  const tg=document.getElementById('target').value.trim();
  let tn=document.getElementById('tone').value;
  if(!uc){alert('バナーの用途を選択してください');return;}
  if(!pr){alert('商品・サービス名を入力してください');return;}
  const chip=document.querySelector('#sc .chip.on');
  bw=+(chip?.dataset.w||600);bh=+(chip?.dataset.h||600);bl=chip?.dataset.l||'';
  if(tn==='auto'){if(uc.includes('求人'))tn='trust';else if(uc.includes('Instagram'))tn='pop';else if(uc.includes('商品'))tn='cool';}
  const td=TD[tn]||TD.auto;
  const pals=td.pals;
  const names=['クリーン＆モダン','インパクト重視','バランス型'];
  const lays=['center','left','split'];
  concepts=[];
  for(let i=0;i<3;i++){
    const p=pals[i%pals.length];
    concepts.push({name:names[i],catch:makeCatch(pr,tn),sub:sb||(tg?`${tg}向け`:''),bg:p.bg,bg2:p.bg2,tx:p.tx,ac:p.ac,sc:p.sc,cols:[p.bg,p.ac,p.tx],cn:p.n,pt:p.pt,lay:lays[i]});
  }
  si=0;renderConcepts(pr);render(concepts[0]);
}

function render(c){
  const area=document.getElementById('pa');
  const maxW=Math.min(bw,480);
  const scale=maxW/bw;
  const dh=Math.round(bh*scale);
  const cv=document.createElement('canvas');
  cv.width=bw;cv.height=bh;
  cv.style.cssText=`width:${maxW}px;height:${dh}px;border-radius:8px;box-shadow:0 10px 40px rgba(0,0,0,.6);display:block;`;
  cv.id='BC';
  const ctx=cv.getContext('2d');
  const g=ctx.createLinearGradient(0,0,bw,bh);
  g.addColorStop(0,c.bg);g.addColorStop(1,c.bg2||c.bg);
  ctx.fillStyle=g;ctx.fillRect(0,0,bw,bh);
  drawDeco(ctx,c,bw,bh);
  const fin=()=>{drawTxt(ctx,c,bw,bh);done(area,cv,maxW,dh);};
  if(photo)drawPhoto(ctx,c,bw,bh,fin);else fin();
  window._cc=c;
}

function done(area,cv,mw,dh){
  area.innerHTML='';
  const w=document.createElement('div');w.style.textAlign='center';
  w.appendChild(cv);
  const l=document.createElement('div');l.className='slbl';l.style.marginTop='6px';
  l.textContent=bl+' · プレビュー縮小表示';w.appendChild(l);
  const r=document.createElement('div');r.className='arow';
  r.innerHTML=`<button class="abtn g" onclick="saveJPG()">⬇ JPGで保存</button><button class="abtn" onclick="copyCols()">配色コピー</button><button class="abtn" onclick="copyAll()">コンセプトコピー</button>`;
  w.appendChild(r);area.appendChild(w);
}

function drawDeco(ctx,c,w,h){
  ctx.save();ctx.globalAlpha=.07;
  const pt=c.pt||'geometric';
  if(pt==='geometric'){
    ctx.strokeStyle=c.ac;ctx.lineWidth=1.5;
    const s=Math.round(w/8);
    for(let x=-s;x<w+s;x+=s)for(let y=-s;y<h+s;y+=s){ctx.beginPath();ctx.moveTo(x,y+s/2);ctx.lineTo(x+s/2,y);ctx.lineTo(x+s,y+s/2);ctx.lineTo(x+s/2,y+s);ctx.closePath();ctx.stroke();}
  }else if(pt==='lines'){
    ctx.strokeStyle=c.ac;ctx.lineWidth=1;
    for(let i=0;i<w+h;i+=Math.round(w/12)){ctx.beginPath();ctx.moveTo(i,0);ctx.lineTo(0,i);ctx.stroke();}
  }else if(pt==='dots'){
    ctx.fillStyle=c.ac;const sp=Math.round(w/14);
    for(let x=sp/2;x<w;x+=sp)for(let y=sp/2;y<h;y+=sp){ctx.beginPath();ctx.arc(x,y,sp/8,0,Math.PI*2);ctx.fill();}
  }else if(pt==='circles'){
    ctx.strokeStyle=c.ac;ctx.lineWidth=2;
    for(let i=0;i<4;i++){ctx.beginPath();ctx.arc(w*.8,h*.2,w*(.08+i*.11),0,Math.PI*2);ctx.stroke();}
  }else if(pt==='grid'){
    ctx.strokeStyle=c.ac;ctx.lineWidth=.8;const g=Math.round(w/16);
    for(let x=0;x<w;x+=g){ctx.beginPath();ctx.moveTo(x,0);ctx.lineTo(x,h);ctx.stroke();}
    for(let y=0;y<h;y+=g){ctx.beginPath();ctx.moveTo(0,y);ctx.lineTo(w,y);ctx.stroke();}
  }else if(pt==='diagonal'){
    ctx.strokeStyle=c.ac;ctx.lineWidth=2;const st=Math.round(w/10);
    for(let i=-h;i<w+h;i+=st){ctx.beginPath();ctx.moveTo(i,0);ctx.lineTo(i+h,h);ctx.stroke();}
  }else if(pt==='floral'){
    ctx.fillStyle=c.ac;const pe=8,cx=w*.88,cy=h*.12,r=Math.round(w/5);
    for(let p=0;p<pe;p++){const a=(p/pe)*Math.PI*2;ctx.beginPath();ctx.ellipse(cx+Math.cos(a)*r*.5,cy+Math.sin(a)*r*.5,r*.22,r*.48,a,0,Math.PI*2);ctx.fill();}
  }else if(pt==='organic'){
    ctx.strokeStyle=c.ac;ctx.lineWidth=2;
    ctx.beginPath();ctx.arc(w*.88,h*.12,w*.18,0,Math.PI*2);ctx.stroke();
    ctx.beginPath();ctx.arc(w*.1,h*.88,w*.13,0,Math.PI*2);ctx.stroke();
  }
  ctx.globalAlpha=.1;
  const rg=ctx.createRadialGradient(w*.2,h*.2,0,w*.2,h*.2,w*.65);
  rg.addColorStop(0,'rgba(255,255,255,1)');rg.addColorStop(1,'rgba(255,255,255,0)');
  ctx.fillStyle=rg;ctx.fillRect(0,0,w,h);
  ctx.restore();
}

function drawPhoto(ctx,c,w,h,cb){
  const img=new Image();
  img.onload=()=>{
    ctx.save();
    const di=(x,y,iw,ih,a,cl)=>{
      ctx.globalAlpha=a;const s=Math.max(iw/img.width,ih/img.height);
      const sw=img.width*s,sh=img.height*s;
      if(cl){ctx.beginPath();ctx.rect(x,y,iw,ih);ctx.clip();}
      ctx.drawImage(img,x+(iw-sw)/2,y+(ih-sh)/2,sw,sh);
    };
    if(ppos==='bg'){di(0,0,w,h,.3,false);}
    else if(ppos==='left'){
      di(0,0,Math.round(w*.45),h,1,true);
      const gr=ctx.createLinearGradient(0,0,Math.round(w*.45),0);
      gr.addColorStop(.55,'rgba(0,0,0,0)');gr.addColorStop(1,c.bg);
      ctx.globalAlpha=1;ctx.fillStyle=gr;ctx.fillRect(0,0,Math.round(w*.45),h);
    }else if(ppos==='right'){
      const px=Math.round(w*.55);di(px,0,Math.round(w*.45),h,1,true);
      const gr=ctx.createLinearGradient(px,0,px+Math.round(w*.45),0);
      gr.addColorStop(0,c.bg);gr.addColorStop(.45,'rgba(0,0,0,0)');
      ctx.globalAlpha=1;ctx.fillStyle=gr;ctx.fillRect(px,0,Math.round(w*.45),h);
    }else if(ppos==='center'){di(0,0,w,h,.35,false);}
    else if(ppos==='top'){
      const ih2=Math.round(h*.45);di(0,0,w,ih2,1,true);
      const gr=ctx.createLinearGradient(0,0,0,ih2);
      gr.addColorStop(.5,'rgba(0,0,0,0)');gr.addColorStop(1,c.bg);
      ctx.globalAlpha=1;ctx.fillStyle=gr;ctx.fillRect(0,0,w,ih2);
    }else{
      const iy=Math.round(h*.55),ih2=Math.round(h*.45);di(0,iy,w,ih2,1,true);
      const gr=ctx.createLinearGradient(0,iy,0,iy+ih2);
      gr.addColorStop(0,c.bg);gr.addColorStop(.45,'rgba(0,0,0,0)');
      ctx.globalAlpha=1;ctx.fillStyle=gr;ctx.fillRect(0,iy,w,ih2);
    }
    ctx.globalAlpha=1;ctx.restore();cb();
  };
  img.src=photo;
}

function wrap(ctx,text,maxW){
  const lines=[];let cur='';
  for(const ch of text){if(ctx.measureText(cur+ch).width>maxW&&cur!==''){lines.push(cur);cur=ch;}else cur+=ch;}
  if(cur)lines.push(cur);return lines;
}
function rrect(ctx,x,y,w,h,r){
  ctx.beginPath();ctx.moveTo(x+r,y);ctx.lineTo(x+w-r,y);ctx.quadraticCurveTo(x+w,y,x+w,y+r);
  ctx.lineTo(x+w,y+h-r);ctx.quadraticCurveTo(x+w,y+h,x+w-r,y+h);
  ctx.lineTo(x+r,y+h);ctx.quadraticCurveTo(x,y+h,x,y+h-r);
  ctx.lineTo(x,y+r);ctx.quadraticCurveTo(x,y,x+r,y);ctx.closePath();ctx.fill();
}

function drawTxt(ctx,c,w,h){
  const narrow=h<100;
  const pad=Math.round(w*.08);
  const pr=document.getElementById('product').value.trim();
  const lay=c.lay||'center';
  if(!narrow){
    ctx.fillStyle=c.ac;
    ctx.fillRect(0,0,w,Math.round(h*.005));
    if(lay!=='center')ctx.fillRect(0,0,Math.round(w*.005),h);
  }
  let tx=pad,ty=Math.round(h*.42);
  if(lay==='center'){tx=w/2;ty=h/2;}
  if(lay==='split'&&photo&&ppos==='left')tx=Math.round(w*.53);
  if(lay==='split'&&photo&&ppos==='right')tx=pad;
  const al=lay==='center'?'center':'left';
  ctx.textAlign=al;

  // TAG
  if(!narrow&&h>150){
    const tag=document.getElementById('useCase').value.split('（')[0]||'';
    if(tag){
      const tf=Math.round(w*.022),tpx=Math.round(w*.022),tpy=Math.round(h*.012);
      ctx.font=`700 ${tf}px 'Noto Sans JP'`;
      const tw=ctx.measureText(tag).width+tpx*2,th=tf+tpy*2;
      const tx2=lay==='center'?w/2-tw/2:tx;
      const ty2=ty-Math.round(h*.3)-th;
      ctx.fillStyle=c.ac;rrect(ctx,tx2,ty2,tw,th,Math.round(th*.4));
      ctx.fillStyle='#fff';
      ctx.fillText(tag,tx2+tpx,ty2+tpy+tf*.82);
    }
  }

  const cf=narrow?Math.round(h*.35):Math.round(w*.07);
  ctx.font=`900 ${cf}px 'Noto Sans JP'`;ctx.fillStyle=c.tx;
  const mw=lay==='center'?w*.78:(photo&&(ppos==='left'||ppos==='right'))?w*.42:w-pad*2;
  const lines=narrow?[c.catch]:wrap(ctx,c.catch,mw);
  const lh=cf*1.28,th2=lines.length*lh;
  let sy=lay==='center'?h/2-th2/2+cf*.45:ty-th2/2+cf*.45;
  if(lay==='split')sy=Math.round(h*.32);
  if(narrow)sy=h/2+cf*.35;

  ctx.shadowColor=c.ac;ctx.shadowBlur=Math.round(w*.012);
  lines.forEach((l,i)=>ctx.fillText(l,tx,sy+i*lh));
  ctx.shadowBlur=0;

  if(!narrow){
    ctx.fillStyle=c.ac;
    const ulw=Math.round(w*.07),ulx=lay==='center'?w/2-ulw/2:tx;
    ctx.fillRect(ulx,sy+th2+Math.round(h*.015),ulw,Math.round(h*.006));
  }
  if(c.sub&&!narrow){
    const sf=Math.round(w*.03);
    ctx.font=`400 ${sf}px 'Noto Sans JP'`;ctx.fillStyle=c.sc||c.tx;
    ctx.fillText(c.sub,tx,sy+th2+Math.round(h*.06));
  }
  if(!narrow){
    ctx.font=`500 ${Math.round(w*.022)}px 'Noto Sans JP'`;
    ctx.fillStyle=c.sc||c.tx;ctx.textAlign='right';
    ctx.fillText(pr,w-pad,h-Math.round(h*.04));
  }
}

function renderConcepts(){
  const area=document.getElementById('ca');area.innerHTML='';
  const list=document.createElement('div');list.className='clist';
  concepts.forEach((c,i)=>{
    const card=document.createElement('div');
    card.className='ccard fu'+(i===0?' sel':'');
    card.style.animationDelay=`${i*.08}s`;
    card.innerHTML=`
      <div class="cn">CONCEPT ${i+1} — ${c.name}</div>
      <div class="cname">「${c.catch}」</div>
      <div class="ccopy">${c.sub||'—'}</div>
      <div class="cdesc">配色：${c.cn}　装飾：${c.pt}パターン</div>
      <div class="cdots">${c.cols.map(col=>`<div class="dot" style="background:${col}"></div>`).join('')}<span class="dlabel">${c.cols.join(' · ')}</span></div>
    `;
    card.onclick=()=>{
      document.querySelectorAll('.ccard').forEach(x=>x.classList.remove('sel'));
      card.classList.add('sel');si=i;render(concepts[i]);
    };
    list.appendChild(card);
  });
  area.appendChild(list);
}

function saveJPG(){
  const c=window._cc;if(!c){alert('まずバナーを生成してください');return;}
  const full=document.createElement('canvas');full.width=bw;full.height=bh;
  const ctx=full.getContext('2d');
  const g=ctx.createLinearGradient(0,0,bw,bh);
  g.addColorStop(0,c.bg);g.addColorStop(1,c.bg2||c.bg);
  ctx.fillStyle=g;ctx.fillRect(0,0,bw,bh);
  drawDeco(ctx,c,bw,bh);
  const fin=()=>{
    drawTxt(ctx,c,bw,bh);
    const a=document.createElement('a');
    const pr=document.getElementById('product').value.trim()||'banner';
    a.download=`banner_${pr.slice(0,10)}_${Date.now()}.jpg`;
    a.href=full.toDataURL('image/jpeg',.95);a.click();
  };
  if(photo)drawPhoto(ctx,c,bw,bh,fin);else fin();
}

function copyCols(){
  if(!concepts.length)return;const c=concepts[si];
  const t=`【${c.cn}】\n背景: ${c.bg}\nテキスト: ${c.tx}\nアクセント: ${c.ac}`;
  navigator.clipboard.writeText(t).then(()=>alert('配色コードをコピーしました！\n\n'+t));
}
function copyAll(){
  if(!concepts.length)return;const c=concepts[si];
  const t=`【コンセプト${si+1}：${c.name}】\nキャッチコピー：${c.catch}\nサブテキスト：${c.sub}\n配色：${c.cn}\n背景：${c.bg} / テキスト：${c.tx} / アクセント：${c.ac}\n装飾：${c.pt}パターン`;
  navigator.clipboard.writeText(t).then(()=>alert('コンセプトをコピーしました！'));
}
</script>
</body>
</html>

<title>영미문학읽기 포토부스</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Gaegu:wght@400;700&family=Gowun+Dodum&display=swap">
<style>
  /* Single look on purpose: the crayon-sky world of the frames themselves. */
  :root{
    --sky:#cfe5f6;
    --sky-deep:#8fc0e6;
    --paper:#fbfcf7;
    --ink:#1f3354;      /* BIHS uniform navy */
    --ink-soft:#4d6182;
    --leaf:#5e9e3f;
    --leaf-deep:#447a2c;
    --bark:#8a5a3b;
    --line:#b9d3e8;
    --display:"Gaegu","Gowun Dodum","Apple SD Gothic Neo","Malgun Gothic",sans-serif;
    --body:"Gowun Dodum","Apple SD Gothic Neo","Malgun Gothic",system-ui,sans-serif;
  }
  *{box-sizing:border-box}
  [hidden]{display:none!important}
  html,body{background:var(--sky);color:var(--ink)}
  body{
    font-family:var(--body);font-size:15px;line-height:1.55;
    background:linear-gradient(180deg,var(--sky-deep) 0%,var(--sky) 38%,#e6f1e0 100%) fixed,var(--sky);
    padding-inline:16px;padding-block:20px 120px;min-height:100%;
  }
  .wrap{max-width:900px;margin:0 auto;display:grid;gap:20px}

  header{display:grid;gap:2px;text-align:left}
  .school{font-size:13px;letter-spacing:.08em;color:var(--ink-soft)}
  h1{font-family:var(--display);font-weight:700;font-size:clamp(30px,7vw,44px);line-height:1.05;margin:0;text-wrap:balance}
  h1 .en{display:block;font-size:.55em;font-weight:400;color:var(--ink-soft);letter-spacing:.02em;margin-top:4px}

  .layout{display:grid;gap:20px;grid-template-columns:1fr}
  @media (min-width:760px){
    .layout{grid-template-columns:minmax(0,340px) 1fr;align-items:start}
    .strip-col{position:sticky;top:calc(env(safe-area-inset-top,0px) + 16px)}
    body{padding-bottom:40px}
  }

  .panel{background:var(--paper);border:2px solid var(--ink);border-radius:18px;padding:16px;display:grid;gap:12px;box-shadow:4px 4px 0 var(--ink)}
  .label{font-family:var(--display);font-size:22px;font-weight:700;line-height:1.1;margin:0}
  .hint{margin:0;color:var(--ink-soft);font-size:14px}

  .frames{display:grid;grid-template-columns:1fr 1fr;gap:12px}
  .frame-opt{appearance:none;border:2px solid var(--line);background:#fff;border-radius:14px;padding:8px;cursor:pointer;display:grid;gap:6px;justify-items:center;font:inherit;color:var(--ink);transition:border-color .15s,transform .15s}
  .frame-opt img{width:100%;max-width:120px;aspect-ratio:1/3;object-fit:cover;border-radius:6px;background:var(--sky)}
  .frame-opt span{font-family:var(--display);font-size:19px;font-weight:700}
  .frame-opt[aria-pressed="true"]{border-color:var(--leaf);box-shadow:0 0 0 3px #d6ebc9;transform:translateY(-2px)}
  .frame-opt:focus-visible,.btn:focus-visible,.slot:focus-visible{outline:3px solid var(--bark);outline-offset:2px}

  .strip-col{display:grid;justify-items:center;gap:10px}
  .strip{position:relative;width:min(300px,72vw);max-width:100%;aspect-ratio:1/3;border-radius:10px;overflow:hidden;box-shadow:0 10px 30px rgba(31,51,84,.25)}
  .strip canvas{display:block;width:100%;height:100%}
  .slot{position:absolute;left:5%;width:90%;height:20%;border:0;background:transparent;cursor:pointer;border-radius:4px;padding:0}
  .slot[data-i="0"]{top:1.667%}
  .slot[data-i="1"]{top:23.333%}
  .slot[data-i="2"]{top:45%}
  .slot.active{box-shadow:inset 0 0 0 3px var(--leaf),0 0 0 2px #fff}
  .strip-note{font-size:13px;color:var(--ink-soft);margin:0;text-align:center}

  .progress{display:flex;gap:8px;align-items:center;font-variant-numeric:tabular-nums}
  .dot{width:30px;height:30px;border-radius:50%;border:2px solid var(--ink);display:grid;place-items:center;font-family:var(--display);font-weight:700;font-size:18px;background:#fff}
  .dot.done{background:var(--leaf);color:#fff;border-color:var(--leaf-deep)}
  .dot.cur{box-shadow:0 0 0 3px #d6ebc9}
  .progress .count{margin-left:auto;font-size:14px;color:var(--ink-soft)}

  .actions{display:grid;grid-template-columns:1fr 1fr;gap:10px}
  .btn{appearance:none;font:inherit;font-family:var(--display);font-weight:700;font-size:21px;line-height:1.1;border-radius:14px;padding:13px 10px;cursor:pointer;border:2px solid var(--ink);background:#fff;color:var(--ink);text-align:center}
  .btn.primary{background:var(--leaf);border-color:var(--leaf-deep);color:#fff;box-shadow:0 3px 0 var(--leaf-deep)}
  .btn.navy{background:var(--ink);color:#fff}
  .btn.wide{grid-column:1/-1}
  .btn:active{transform:translateY(2px);box-shadow:none}
  .btn[disabled]{opacity:.45;cursor:default}
  .text-btn{appearance:none;background:none;border:0;font:inherit;color:var(--ink-soft);text-decoration:underline;cursor:pointer;justify-self:start;padding:4px 0}

  /* Phone: keep the camera buttons under the thumb */
  @media (max-width:759px){
    .dock{position:fixed;left:0;right:0;bottom:0;z-index:5;background:rgba(251,252,247,.96);border-top:2px solid var(--ink);padding:10px 16px calc(10px + env(safe-area-inset-bottom,0px));backdrop-filter:blur(6px)}
    .dock .actions{max-width:520px;margin:0 auto}
    .controls-panel .actions{display:none}
  }
  @media (min-width:760px){ .dock{display:none} }

  /* Result sheet */
  .sheet{position:fixed;inset:0;z-index:10;background:rgba(20,34,58,.72);display:grid;place-items:start center;overflow-y:auto;padding:calc(16px + env(safe-area-inset-top,0px)) 16px calc(24px + env(safe-area-inset-bottom,0px))}
  .sheet-card{width:min(420px,100%);background:var(--paper);border-radius:20px;border:2px solid var(--ink);padding:18px;display:grid;gap:12px;justify-items:center}
  .sheet-card h2{font-family:var(--display);font-size:32px;margin:0;line-height:1}
  .result{width:min(300px,78vw);max-width:100%;border-radius:8px;box-shadow:0 8px 24px rgba(31,51,84,.3);-webkit-touch-callout:default;user-select:auto}
  .save-tip{margin:0;background:#eaf4e2;border:1.5px dashed var(--leaf);border-radius:12px;padding:10px 12px;font-size:14px;text-align:center;width:100%}
  .save-tip b{color:var(--leaf-deep)}
  .sheet-card .actions{width:100%}

  .busy{position:fixed;inset:0;z-index:20;display:grid;place-items:center;background:rgba(207,229,246,.7);font-family:var(--display);font-size:26px;font-weight:700}
  @media (prefers-reduced-motion:reduce){*{transition:none!important}}
</style>

<div class="wrap">
  <header>
    <div class="school">부산국제고등학교 · BIHS</div>
    <h1>영미문학읽기 포토부스<span class="en">2026학년도 2학기 · English &amp; American Literature</span></h1>
  </header>

  <div class="layout">
    <div class="strip-col">
      <div class="strip" id="strip">
        <canvas id="preview" width="600" height="1800" aria-label="포토 프레임 미리보기"></canvas>
        <button class="slot" data-i="0" aria-label="1번 컷 선택"></button>
        <button class="slot" data-i="1" aria-label="2번 컷 선택"></button>
        <button class="slot" data-i="2" aria-label="3번 컷 선택"></button>
      </div>
      <p class="strip-note">칸을 누르면 그 컷만 다시 찍을 수 있어요</p>
    </div>

    <div style="display:grid;gap:20px">
      <section class="panel">
        <h2 class="label">프레임 고르기</h2>
        <div class="frames">
          <button class="frame-opt" id="opt-forest" data-frame="forest" aria-pressed="true">
            <img src="frame-forest.png" alt="숲길 프레임">
            <span>숲길 친구</span>
          </button>
          <button class="frame-opt" id="opt-tree" data-frame="tree" aria-pressed="false">
            <img src="frame-tree.png" alt="나무 프레임">
            <span>나무 친구</span>
          </button>
        </div>
      </section>

      <section class="panel controls-panel">
        <h2 class="label">세 컷 채우기</h2>
        <p class="hint">세 컷을 찍거나 앨범에서 고르면 프레임에 바로 들어가요. 사진은 서버로 보내지 않고 이 휴대폰 안에서만 만들어져요.</p>
        <div class="progress" id="progress"></div>
        <div class="actions" data-actions></div>
        <button class="text-btn" id="reset">처음부터 다시 하기</button>
      </section>
    </div>
  </div>
</div>

<div class="dock"><div class="actions" data-actions></div></div>

<input type="file" id="cam" accept="image/*" capture="user" hidden>
<input type="file" id="album" accept="image/*" multiple hidden>

<div class="sheet" id="sheet" hidden role="dialog" aria-modal="true" aria-labelledby="sheet-title">
  <div class="sheet-card">
    <h2 id="sheet-title">완성!</h2>
    <img class="result" id="result" alt="완성된 영미문학읽기 네컷 사진">
    <p class="save-tip" id="save-tip"><b>사진을 길게 눌러</b> ‘사진에 저장’(아이폰) 또는 ‘이미지 다운로드’(안드로이드)를 선택하세요.</p>
    <div class="actions">
      <button class="btn" id="close">닫고 고치기</button>
      <button class="btn navy" id="again">새로 찍기</button>
    </div>
  </div>
</div>

<div class="busy" id="busy" hidden>사진 넣는 중…</div>

<script>
(() => {
  const SLOTS = [[30,30,540,360],[30,420,540,360],[30,810,540,360]];
  const W = 600, H = 1800, OUT = 2; // export at 1200×3600
  const FRAMES = { forest: 'frame-forest.png', tree: 'frame-tree.png' };
  const frameImgs = {};
  const photos = [null, null, null];
  let frameKey = 'forest';
  let active = 0;
  let target = 0;

  const $ = s => document.querySelector(s);
  const preview = $('#preview');
  const cam = $('#cam'), album = $('#album');

  function loadImg(src){
    return new Promise((res, rej) => { const i = new Image(); i.onload = () => res(i); i.onerror = rej; i.src = src; });
  }

  function drawCover(ctx, img, x, y, w, h){
    const iw = img.naturalWidth || img.width, ih = img.naturalHeight || img.height;
    const s = Math.max(w / iw, h / ih);
    const sw = w / s, sh = h / s;
    ctx.drawImage(img, (iw - sw) / 2, (ih - sh) / 2, sw, sh, x, y, w, h);
  }

  function compose(ctx, scale, withPlaceholders){
    ctx.save();
    ctx.scale(scale, scale);
    ctx.fillStyle = '#ffffff';
    ctx.fillRect(0, 0, W, H);
    SLOTS.forEach(([x, y, w, h], i) => {
      // bleed 2px under the frame edge so no seam shows
      if (photos[i]) drawCover(ctx, photos[i], x - 2, y - 2, w + 4, h + 4);
      else {
        ctx.fillStyle = '#eef5fb';
        ctx.fillRect(x - 2, y - 2, w + 4, h + 4);
        if (withPlaceholders){
          ctx.fillStyle = '#8fb3d1';
          ctx.textAlign = 'center'; ctx.textBaseline = 'middle';
          ctx.font = '700 120px Gaegu, sans-serif';
          ctx.fillText(String(i + 1), x + w / 2, y + h / 2 - 22);
          ctx.font = '700 40px Gaegu, sans-serif';
          ctx.fillText('눌러서 찍기', x + w / 2, y + h / 2 + 62);
        }
      }
    });
    if (frameImgs[frameKey]) ctx.drawImage(frameImgs[frameKey], 0, 0, W, H);
    ctx.restore();
  }

  function render(){
    compose(preview.getContext('2d'), 1, true);
    document.querySelectorAll('.slot').forEach(b => b.classList.toggle('active', +b.dataset.i === active));
    const filled = photos.filter(Boolean).length;
    $('#progress').innerHTML = SLOTS.map((_, i) =>
      `<span class="dot ${photos[i] ? 'done' : ''} ${i === active ? 'cur' : ''}">${i + 1}</span>`
    ).join('') + `<span class="count">${filled} / 3 컷</span>`;
    const done = filled === 3;
    const html = done
      ? `<button class="btn primary wide" data-act="finish">완성하고 저장하기</button>`
      : `<button class="btn primary" data-act="cam">${active + 1}번 컷 찍기</button>
         <button class="btn" data-act="album">앨범에서 고르기</button>`;
    document.querySelectorAll('[data-actions]').forEach(el => el.innerHTML = html);
  }

  function nextEmpty(from){
    for (let k = 0; k < 3; k++){ const i = (from + k) % 3; if (!photos[i]) return i; }
    return from;
  }

  async function fileToImg(file){
    const url = URL.createObjectURL(file);
    try { return await loadImg(url); }
    finally { setTimeout(() => URL.revokeObjectURL(url), 0); }
  }

  async function place(files){
    if (!files.length) return;
    $('#busy').hidden = false;
    try {
      let i = target;
      for (const f of files){
        if (!f.type.startsWith('image/') && !/\.(heic|heif)$/i.test(f.name)) continue;
        photos[i] = await fileToImg(f);
        i = nextEmpty((i + 1) % 3);
        if (photos.every(Boolean)) break;
      }
      active = photos.every(Boolean) ? active : nextEmpty(target);
    } catch (e) {
      alertInline('이 사진은 열 수 없어요. JPG나 PNG 사진으로 다시 골라 주세요.');
    } finally {
      $('#busy').hidden = true;
      render();
      if (photos.every(Boolean)) finish();
    }
  }

  function alertInline(msg){
    const p = document.createElement('p');
    p.className = 'hint'; p.style.color = '#a0412a'; p.textContent = msg;
    const panel = document.querySelector('.controls-panel');
    panel.appendChild(p); setTimeout(() => p.remove(), 5000);
  }

  function finish(){
    const c = document.createElement('canvas');
    c.width = W * OUT; c.height = H * OUT;
    const ctx = c.getContext('2d');
    ctx.imageSmoothingQuality = 'high';
    compose(ctx, OUT, false);
    $('#result').src = c.toDataURL('image/jpeg', 0.92);
    $('#sheet').hidden = false;
  }

  function resetAll(){
    photos.fill(null); active = 0; target = 0;
    $('#sheet').hidden = true; render();
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }

  document.addEventListener('click', e => {
    const act = e.target.closest('[data-act]')?.dataset.act;
    if (act === 'cam'){ target = active; cam.value = ''; cam.click(); }
    else if (act === 'album'){ target = active; album.value = ''; album.click(); }
    else if (act === 'finish') finish();
  });

  document.querySelectorAll('.slot').forEach(b => b.addEventListener('click', () => {
    active = +b.dataset.i; render();
    if (photos.every(Boolean)){
      // all filled: tapping a shot means "retake this one"
      document.querySelectorAll('[data-actions]').forEach(el => el.innerHTML =
        `<button class="btn primary" data-act="cam">${active + 1}번 다시 찍기</button>
         <button class="btn" data-act="album">앨범에서 바꾸기</button>
         <button class="btn navy wide" data-act="finish">이대로 완성하기</button>`);
    }
  }));

  cam.addEventListener('change', () => place([...cam.files]));
  album.addEventListener('change', () => place([...album.files]));

  document.querySelectorAll('.frame-opt').forEach(b => b.addEventListener('click', () => {
    frameKey = b.dataset.frame;
    document.querySelectorAll('.frame-opt').forEach(o => o.setAttribute('aria-pressed', String(o === b)));
    render();
  }));

  $('#reset').addEventListener('click', resetAll);
  $('#again').addEventListener('click', resetAll);
  $('#close').addEventListener('click', () => { $('#sheet').hidden = true; });

  if (!/Android|iPhone|iPad|iPod/i.test(navigator.userAgent)){
    $('#save-tip').innerHTML = '<b>사진에서 오른쪽 클릭</b> → ‘이미지를 다른 이름으로 저장’을 선택하세요.';
  }

  render();
  Promise.all(Object.entries(FRAMES).map(([k, src]) => loadImg(src).then(i => { frameImgs[k] = i; })))
    .then(() => (document.fonts ? document.fonts.ready : null))
    .then(render)
    .catch(() => alertInline('프레임을 불러오지 못했어요. 페이지를 새로고침해 주세요.'));
})();
</script>

<title>Python Online</title>
<style>
:root{
  /* Layout: grille d'atelier. Barre de titre en haut, barre d'activité + explorateur à gauche, éditeur et panneau à droite, barre d'état en bas. */
  --titlebar:#3c3c3c; --activity:#333333; --sidebar:#252526; --editor:#1e1e1e; --tab-off:#2d2d2d; --status:#007acc;
  --fg:#cccccc; --dim:#858585; --line:#454545; --accent:#007acc; --sel:#37373d; --hover:#2a2d2e; --err:#f14c4c; --ok:#89d185;
  --ui:"Segoe UI",system-ui,-apple-system,"Helvetica Neue",Arial,sans-serif;
  --mono:Consolas,"SF Mono",Menlo,"DejaVu Sans Mono","Liberation Mono","Courier New",monospace;
  --fs:14px; --lh:19px; --panel-h:210px;
  color-scheme:dark;
}
*{box-sizing:border-box}
html,body{height:100%}
body{background:var(--editor);color:var(--fg);font:13px/1.4 var(--ui);overflow:hidden;-webkit-text-size-adjust:100%}
button{font:inherit;color:inherit;background:none;border:0;padding:0;cursor:pointer}
input{font:inherit}
:focus-visible{outline:1px solid var(--accent);outline-offset:-1px}
.ib{width:22px;height:22px;display:inline-grid;place-items:center;border-radius:5px;color:#c5c5c5}
.ib:hover{background:#ffffff1f}
svg{display:block;flex:none}

#app{height:100%;display:grid;grid-template-rows:30px minmax(0,1fr) 22px}

/* Barre de titre */
#titlebar{background:var(--titlebar);display:flex;align-items:center;gap:6px;padding:0 10px;min-width:0;color:#ccc}
#menubar{display:flex;overflow-x:auto;scrollbar-width:none;flex:none;max-width:100%}
#menubar button{padding:0 8px;height:22px;border-radius:4px;white-space:nowrap}
#menubar button:hover,#menubar button.open{background:#ffffff1f}
#wtitle{flex:1;min-width:0;text-align:center;color:#9d9d9d;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;padding-right:60px}

/* Menus déroulants */
.dd{position:fixed;z-index:50;min-width:250px;background:#252526;border:1px solid #454545;border-radius:5px;box-shadow:0 2px 10px #000a;padding:4px 0}
.mi{display:flex;justify-content:space-between;gap:28px;width:100%;padding:4px 24px;text-align:left;color:#ccc}
.mi:hover,.mi:focus-visible{background:#094771;color:#fff;outline:0}
.mi kbd{font:inherit;color:#9d9d9d}
.mi:hover kbd{color:#d0d0d0}
.sep{height:1px;background:#454545;margin:4px 0}

#main{display:flex;min-height:0;position:relative}

/* Barre d'activité */
#activity{width:48px;flex:none;background:var(--activity);display:flex;flex-direction:column}
#activity button{height:48px;display:grid;place-items:center;color:#858585;border-left:2px solid transparent}
#activity button:hover{color:#fff}
#activity button.on{color:#fff;border-left-color:#fff}

/* Barre latérale */
#sidebar{width:250px;flex:none;background:var(--sidebar);display:flex;flex-direction:column;min-width:0;min-height:0}
#sidebar>div{display:flex;flex-direction:column;min-height:0;flex:1}
.sb-title{height:35px;flex:none;display:flex;align-items:center;justify-content:space-between;padding:0 8px 0 20px;font-size:11px;letter-spacing:.05em;text-transform:uppercase;color:#bbb}
.sec{height:22px;flex:none;display:flex;align-items:center;gap:2px;padding:0 8px;font-size:11px;font-weight:700;text-transform:uppercase;color:#ccc;background:#ffffff08}
#files{overflow:auto;flex:1;min-height:0;padding-bottom:12px}
.file{display:flex;align-items:center;gap:6px;height:22px;padding:0 6px 0 22px;cursor:pointer;color:#ccc}
.file:hover{background:var(--hover)}
.file.on{background:var(--sel);color:#fff}
.file .fn{overflow:hidden;text-overflow:ellipsis;white-space:nowrap;min-width:0}
.file .acts{margin-left:auto;display:none;gap:0}
.file:hover .acts,.file:focus-within .acts{display:flex}
.file .ib{width:20px;height:20px}
.file .dl.arm{background:var(--err);color:#fff}
.file .ren{flex:1;min-width:0;height:20px;background:#3c3c3c;border:1px solid var(--accent);color:#fff;padding:0 4px;outline:0}
.empty{padding:12px 20px;color:#858585}
.sr-box{padding:0 12px 8px}
.sr-box input{width:100%;height:26px;background:#3c3c3c;border:1px solid transparent;color:#ddd;padding:0 8px;outline:0}
.sr-box input:focus{border-color:var(--accent)}
#results{overflow:auto;flex:1;min-height:0}
.sg{display:flex;align-items:center;gap:6px;height:22px;padding:0 12px;font-weight:600;color:#ddd;background:#ffffff08}
.sg span.n{margin-left:auto;background:#4d4d4d;border-radius:9px;padding:0 6px;font-size:11px;line-height:16px}
.sh{display:block;width:100%;text-align:left;height:22px;padding:0 12px 0 28px;white-space:pre;overflow:hidden;text-overflow:ellipsis;color:#bbb}
.sh:hover{background:var(--hover)}
.sh b{background:#613214;color:#fff;font-weight:400;border-radius:2px}

/* Établi */
#workbench{flex:1;min-width:0;min-height:0;display:flex;flex-direction:column;background:var(--editor)}
#tabbar{display:flex;height:35px;flex:none;background:var(--sidebar)}
#tabs{display:flex;flex:1;min-width:0;overflow-x:auto;scrollbar-width:none}
.tab{display:flex;align-items:center;gap:6px;padding:0 6px 0 12px;background:var(--tab-off);color:#969696;border-right:1px solid var(--sidebar);cursor:pointer;white-space:nowrap;position:relative;flex:none}
.tab.on{background:var(--editor);color:#fff}
.tab.on::before{content:"";position:absolute;left:0;right:0;top:0;height:1px;background:var(--accent)}
.tab .x{width:20px;height:20px;border-radius:4px;display:grid;place-items:center;opacity:0}
.tab.on .x,.tab:hover .x{opacity:1}
.tab .x:hover{background:#ffffff1f}
#tabact{display:flex;align-items:center;padding:0 8px;gap:2px;flex:none}
#runbtn{width:28px;height:28px;color:#cccccc}
#runbtn.run-on{color:var(--err)}
#crumbs{height:22px;flex:none;display:flex;align-items:center;gap:4px;padding:0 14px;color:#a9a9a9;font-size:12px;white-space:nowrap;overflow:hidden}
#crumbs i{font-style:normal;color:#6e6e6e}
#crumbs b{font-weight:400;color:#cccccc}

/* Éditeur */
#editor{flex:1;min-height:0;display:flex;position:relative;font:var(--fs)/var(--lh) var(--mono)}
#gutter{flex:none;overflow:hidden;position:relative;color:#858585;text-align:right;user-select:none;-webkit-user-select:none}
#gnums{will-change:transform}
#gnums div{padding:0 12px 0 0;height:var(--lh)}
#gnums div.on{color:#c6c6c6}
#gnums div.bad{color:var(--err)}
#scroller{flex:1;min-width:0;position:relative;overflow:hidden}
#curline,#errline{position:absolute;left:0;right:0;height:var(--lh);pointer-events:none}
#curline{background:#ffffff0b}
#errline{background:#f14c4c26}
#layer{position:absolute;left:0;top:0;will-change:transform;pointer-events:none}
#hl,#ta{margin:0;padding:0 14px 0 6px;font:inherit;letter-spacing:0;word-spacing:0;tab-size:4;-moz-tab-size:4;white-space:pre;font-variant-ligatures:none;font-kerning:none;text-rendering:auto}
#hl{display:block;color:#d4d4d4}
#ta{position:absolute;inset:0;width:100%;height:100%;resize:none;border:0;outline:0;background:transparent;color:transparent;-webkit-text-fill-color:transparent;caret-color:#aeafad;overflow:auto;padding-bottom:50vh;scrollbar-width:thin;scrollbar-color:#4f4f4f transparent;-webkit-text-size-adjust:100%}
#ta::selection{background:#3a7bc85c;-webkit-text-fill-color:transparent}
#ta::-webkit-scrollbar{width:12px;height:12px}
#ta::-webkit-scrollbar-thumb{background:#79797966}
#ta::-webkit-scrollbar-thumb:hover{background:#646464b3}
#ta::-webkit-scrollbar-corner{background:transparent}
.c{color:#6a9955}.s{color:#ce9178}.d{color:#dcdcaa}.n{color:#b5cea8}.k{color:#569cd6}.k2{color:#c586c0}
.f{color:#dcdcaa}.t{color:#4ec9b0}.v{color:#9cdcfe}.cn{color:#4fc1ff}

#welcome{flex:1;min-height:0;display:grid;place-items:center;color:#6e6e6e;padding:16px}
#welcome .w{display:grid;gap:18px;justify-items:center}
#welcome h2{margin:0;font-size:22px;font-weight:300;color:#8a8a8a;letter-spacing:.01em}
#welcome dl{display:grid;grid-template-columns:auto auto;gap:8px 28px;margin:0}
#welcome dt{text-align:right;color:#8a8a8a}
#welcome dd{margin:0;color:#c0c0c0}
#welcome button{color:#3794ff}
#welcome button:hover{text-decoration:underline}

/* Panneau */
#sash{height:0;position:relative;z-index:4;flex:none}
#sash::before{content:"";position:absolute;left:0;right:0;top:-3px;height:6px;cursor:ns-resize}
#sash:hover::before{background:var(--accent)}
#panel{height:var(--panel-h);flex:none;display:flex;flex-direction:column;min-height:0;border-top:1px solid var(--line);background:var(--editor)}
#ptabs{display:flex;align-items:center;height:35px;flex:none;padding:0 8px 0 14px;gap:18px}
.ptab{display:flex;align-items:center;gap:6px;height:35px;font-size:11px;text-transform:uppercase;letter-spacing:.03em;color:#969696;border-bottom:1px solid transparent}
.ptab:hover{color:#e7e7e7}
.ptab.on{color:#e7e7e7;border-bottom-color:#e7e7e7}
.badge{background:var(--accent);color:#fff;border-radius:9px;padding:0 5px;font-size:10px;min-width:16px;line-height:16px;text-align:center}
#pacts{margin-left:auto;display:flex;gap:2px}
#pbody{flex:1;min-height:0;overflow:auto;font:13px/1.5 var(--mono);padding:2px 14px 10px}
#term{white-space:pre-wrap;word-break:break-word;color:#cccccc}
#term .cmd{color:#cccccc;font-weight:700}
#term .dim{color:#858585}
#term .err{color:var(--err)}
#term .ok{color:var(--ok)}
.tin{background:transparent;border:0;outline:0;color:#fff;font:inherit;padding:0;min-width:2ch;width:2ch;caret-color:#fff}
.prob{display:flex;align-items:flex-start;gap:8px;width:100%;text-align:left;padding:3px 6px;font:13px/1.5 var(--ui);border-radius:3px}
.prob:hover{background:var(--hover)}
.prob svg{margin-top:3px;color:var(--err)}
.prob .loc{color:#858585;white-space:nowrap}
.prob .msg{overflow-wrap:anywhere}
.none{font:13px var(--ui);color:#858585;padding:6px}

/* Barre d'état */
#status{background:var(--status);color:#fff;display:flex;align-items:center;justify-content:space-between;font-size:12px;padding:0 6px;min-width:0;overflow:hidden;white-space:nowrap}
#status .sl,#status .sr{display:flex;align-items:center;min-width:0}
#status .sr{flex:none}
#status button,#status .it{display:flex;align-items:center;gap:5px;height:22px;padding:0 7px}
#status button:hover{background:#ffffff24}
#st-msg{padding:0 8px;overflow:hidden;text-overflow:ellipsis}

@media (max-width:700px){
  #sidebar{position:absolute;left:48px;top:0;bottom:0;width:min(260px,calc(100% - 48px));z-index:20;box-shadow:4px 0 14px #000a}
  .hide-sm,#wtitle{display:none}
  #menubar{flex:1}
}
@media (prefers-reduced-motion:no-preference){.tab .x,.file .acts{transition:opacity .08s}}
</style>

<div id="app">
  <header id="titlebar">
    <span id="tlogo" aria-hidden="true"></span>
    <nav id="menubar" aria-label="Menus"></nav>
    <div id="wtitle"></div>
  </header>

  <div id="main">
    <nav id="activity" aria-label="Barre d'activité">
      <button id="ab-explorer" class="on" title="Explorateur (Ctrl+Maj+E)" aria-label="Explorateur"></button>
      <button id="ab-search" title="Rechercher (Ctrl+Maj+F)" aria-label="Rechercher"></button>
    </nav>

    <aside id="sidebar">
      <div id="v-explorer">
        <div class="sb-title"><span>Explorateur</span><span><button id="btn-new" class="ib" title="Nouveau fichier (Alt+N)" aria-label="Nouveau fichier"></button></span></div>
        <div class="sec"><span id="chev"></span>python-online</div>
        <div id="files" role="list" aria-label="Fichiers"></div>
      </div>
      <div id="v-search" hidden>
        <div class="sb-title"><span>Rechercher</span></div>
        <div class="sr-box"><input id="q" type="search" placeholder="Rechercher" autocomplete="off" spellcheck="false" aria-label="Rechercher dans les fichiers"></div>
        <div id="results"></div>
      </div>
    </aside>

    <div id="workbench">
      <div id="tabbar">
        <div id="tabs" role="tablist" aria-label="Fichiers ouverts"></div>
        <div id="tabact"><button id="runbtn" class="ib"></button></div>
      </div>
      <div id="crumbs"></div>

      <div id="editor">
        <div id="gutter"><div id="gnums"></div></div>
        <div id="scroller">
          <div id="curline"></div>
          <div id="errline" hidden></div>
          <div id="layer"><pre id="hl" aria-hidden="true"></pre></div>
          <textarea id="ta" wrap="off" spellcheck="false" autocomplete="off" autocapitalize="off" autocorrect="off" aria-label="Éditeur de code Python"></textarea>
        </div>
      </div>

      <div id="welcome" hidden>
        <div class="w">
          <div id="wlogo"></div>
          <h2>Python Online</h2>
          <dl>
            <dt>Nouveau fichier</dt><dd><button id="w-new">Alt+N</button></dd>
            <dt>Exécuter le fichier</dt><dd>F5</dd>
            <dt>Enregistrer</dt><dd>Ctrl+S</dd>
            <dt>Commenter une ligne</dt><dd>Ctrl+/</dd>
          </dl>
        </div>
      </div>

      <div id="sash" title="Redimensionner le panneau"></div>
      <section id="panel" aria-label="Panneau">
        <div id="ptabs">
          <button class="ptab" id="pt-problems">Problèmes <span class="badge" id="pbadge" hidden>0</span></button>
          <button class="ptab on" id="pt-terminal">Terminal</button>
          <div id="pacts">
            <button class="ib" id="p-clear" title="Effacer le terminal" aria-label="Effacer le terminal"></button>
            <button class="ib" id="p-close" title="Fermer le panneau" aria-label="Fermer le panneau"></button>
          </div>
        </div>
        <div id="pbody">
          <div id="term"></div>
          <div id="probs" hidden></div>
        </div>
      </section>
    </div>
  </div>

  <footer id="status">
    <div class="sl">
      <button id="st-prob" title="Problèmes"></button>
      <span id="st-msg"></span>
    </div>
    <div class="sr">
      <span class="it" id="st-cur"></span>
      <span class="it hide-sm">Espaces : 4</span>
      <span class="it hide-sm">UTF-8</span>
      <span class="it hide-sm">LF</span>
      <span class="it" id="st-eng"></span>
    </div>
  </footer>
</div>

<script src="https://cdn.jsdelivr.net/npm/skulpt@1.2.0/dist/skulpt.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/skulpt@1.2.0/dist/skulpt-stdlib.js"></script>
<script>
(function(){
'use strict';

/* ---------- Utilitaires ---------- */
const $=(s,r)=>(r||document).querySelector(s);
const root=document.documentElement;
function h(tag,props,html){const n=document.createElement(tag);if(props)Object.assign(n,props);if(html!=null)n.innerHTML=html;return n}
function esc(s){return s.replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;')}
const svg=(d,w,extra)=>`<svg width="${w||16}" height="${w||16}" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.3" stroke-linecap="round" stroke-linejoin="round" ${extra||''}>${d}</svg>`;
const ICON={
  py:`<svg width="16" height="16" viewBox="0 0 16 16"><path d="M7.9 1C5.3 1 5.4 2.2 5.4 2.2v1.2H8v.4H4.3S2.5 3.6 2.5 6.4s1.6 2.7 1.6 2.7H5V7.9s0-1.6 1.6-1.6h2.6s1.5 0 1.5-1.5V2.5S10.5 1 7.9 1z" fill="#3776ab"/><path d="M8.1 15c2.6 0 2.5-1.2 2.5-1.2v-1.2H8v-.4h3.7s1.8.2 1.8-2.6-1.6-2.7-1.6-2.7H11v1.2s0 1.6-1.6 1.6H6.8S5.3 9.7 5.3 11.2v2.3S5.5 15 8.1 15z" fill="#ffd43b"/><circle cx="6.4" cy="2.5" r=".55" fill="#1e1e1e"/><circle cx="9.6" cy="13.5" r=".55" fill="#1e1e1e"/></svg>`,
  pyBig:`<svg width="72" height="72" viewBox="0 0 16 16" style="opacity:.28"><path d="M7.9 1C5.3 1 5.4 2.2 5.4 2.2v1.2H8v.4H4.3S2.5 3.6 2.5 6.4s1.6 2.7 1.6 2.7H5V7.9s0-1.6 1.6-1.6h2.6s1.5 0 1.5-1.5V2.5S10.5 1 7.9 1z" fill="#3776ab"/><path d="M8.1 15c2.6 0 2.5-1.2 2.5-1.2v-1.2H8v-.4h3.7s1.8.2 1.8-2.6-1.6-2.7-1.6-2.7H11v1.2s0 1.6-1.6 1.6H6.8S5.3 9.7 5.3 11.2v2.3S5.5 15 8.1 15z" fill="#ffd43b"/></svg>`,
  play:`<svg width="16" height="16" viewBox="0 0 16 16"><path d="M4.5 2.5v11l9-5.5z" fill="currentColor"/></svg>`,
  stop:`<svg width="16" height="16" viewBox="0 0 16 16"><rect x="3.5" y="3.5" width="9" height="9" rx="1" fill="currentColor"/></svg>`,
  close:svg('<path d="M4 4l8 8M12 4l-8 8"/>'),
  plus:svg('<path d="M8 3v10M3 8h10"/>'),
  trash:svg('<path d="M3 4.5h10M6.5 4.5V3h3v1.5M4.8 4.5l.5 8.5h5.4l.5-8.5"/>'),
  pencil:svg('<path d="M3 13l.7-3L10.6 3.1l2.3 2.3L6 12.3z"/>'),
  chev:svg('<path d="M4 6l4 4 4-4"/>'),
  err:svg('<circle cx="8" cy="8" r="5.5"/><path d="M6 6l4 4M10 6l-4 4"/>',14),
  clear:svg('<circle cx="8" cy="8" r="5.5"/><path d="M4.1 11.9l7.8-7.8"/>'),
  explorer:`<svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linejoin="round"><path d="M14 3H7.5A1.5 1.5 0 0 0 6 4.5v12A1.5 1.5 0 0 0 7.5 18h9a1.5 1.5 0 0 0 1.5-1.5V7z"/><path d="M14 3v4h4"/><path d="M9 21h8.5a2.5 2.5 0 0 0 2.5-2.5V10"/></svg>`,
  search:`<svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round"><circle cx="14" cy="10" r="5.5"/><path d="M10 14l-5.5 5.5"/></svg>`,
  chevR:svg('<path d="M6 4l4 4-4 4"/>',10)
};

/* ---------- État et persistance ---------- */
const KEY='python-online.v1';
const SAMPLE_MAIN=`# Bienvenue ! Appuie sur F5 (ou sur le bouton ▶) pour exécuter ce fichier.
from utils import fibonacci, is_prime


class Joueur:
    def __init__(self, nom):
        self.nom = nom
        self.score = 0

    def gagner(self, points):
        self.score += points
        return self


nom = input("Ton prénom ? ")
joueur = Joueur(nom).gagner(10).gagner(5)
print(f"Salut {joueur.nom}, ton score est {joueur.score}")

print("Fibonacci :", [fibonacci(i) for i in range(10)])
print("Nombres premiers < 30 :", [n for n in range(30) if is_prime(n)])
`;
const SAMPLE_UTILS=`def fibonacci(n):
    a, b = 0, 1
    for _ in range(n):
        a, b = b, a + b
    return a


def is_prime(n):
    if n < 2:
        return False
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True
`;
let S=null;
try{S=JSON.parse(localStorage.getItem(KEY)||'null')}catch(e){S=null}
if(!S||!Array.isArray(S.files)){
  S={files:[{name:'main.py',content:SAMPLE_MAIN},{name:'utils.py',content:SAMPLE_UTILS}],open:['main.py'],active:'main.py',fs:14};
}
S.open=(S.open||[]).filter(n=>S.files.some(f=>f.name===n));
if(!S.active||!S.open.includes(S.active))S.active=S.open[S.open.length-1]||null;
S.fs=Math.min(28,Math.max(10,S.fs||14));
let saveTimer=0;
function persist(){clearTimeout(saveTimer);saveTimer=setTimeout(persistNow,250)}
function persistNow(){try{localStorage.setItem(KEY,JSON.stringify(S))}catch(e){}}
const file=n=>S.files.find(f=>f.name===n);
const views={};

/* ---------- Références DOM ---------- */
const ta=$('#ta'),hl=$('#hl'),layer=$('#layer'),gnums=$('#gnums'),gutter=$('#gutter');
const curline=$('#curline'),errline=$('#errline');
const tabsEl=$('#tabs'),filesEl=$('#files'),crumbs=$('#crumbs');
const term=$('#term'),probs=$('#probs'),pbody=$('#pbody'),panel=$('#panel'),sash=$('#sash');
const stMsg=$('#st-msg'),stCur=$('#st-cur'),stEng=$('#st-eng'),stProb=$('#st-prob');
const runbtn=$('#runbtn');
const narrow=()=>window.matchMedia('(max-width:700px)').matches;

$('#tlogo').innerHTML=ICON.py;
$('#wlogo').innerHTML=ICON.pyBig;
$('#ab-explorer').innerHTML=ICON.explorer;
$('#ab-search').innerHTML=ICON.search;
$('#btn-new').innerHTML=ICON.plus;
$('#chev').innerHTML=ICON.chev;
$('#p-clear').innerHTML=ICON.clear;
$('#p-close').innerHTML=ICON.close;

/* ---------- Coloration syntaxique ---------- */
/*HL-START*/
const PURPLE=new Set('import from as if elif else for while break continue return try except finally raise with yield pass assert await async'.split(' '));
const BLUE=new Set('def class lambda and or not in is global nonlocal del True False None self cls'.split(' '));
const TYPES=new Set('int float str list dict set tuple bool object bytes range type complex frozenset Exception ValueError TypeError KeyError IndexError'.split(' '));
const TOK=/(#[^\n]*)|((?:[rRbBuUfF]{1,2})?(?:"""[\s\S]*?(?:"""|$)|'''[\s\S]*?(?:'''|$)|"(?:\\[\s\S]|[^"\\\n])*(?:"|(?=\n)|$)|'(?:\\[\s\S]|[^'\\\n])*(?:'|(?=\n)|$)))|(@[A-Za-z_][\w.]*)|(0[xX][\da-fA-F_]+|0[bB][01_]+|0[oO][0-7_]+|(?:\d[\d_]*\.?[\d_]*|\.\d[\d_]*)(?:[eE][+-]?\d+)?[jJ]?)|([A-Za-z_]\w*)|([\s\S])/g;
function parenNext(src,i){while(src[i]===' '||src[i]==='\t')i++;return src[i]==='('}
function highlight(src){
  let out='',m,prevKw='',prevDot=false;
  TOK.lastIndex=0;
  while((m=TOK.exec(src))){
    const t=m[0];
    if(m[1]){out+='<span class="c">'+esc(t)+'</span>';continue}
    if(m[2]){out+='<span class="s">'+esc(t)+'</span>';prevKw='';prevDot=false;continue}
    if(m[3]){out+='<span class="d">'+esc(t)+'</span>';prevKw='';prevDot=false;continue}
    if(m[4]){out+='<span class="n">'+esc(t)+'</span>';prevKw='';prevDot=false;continue}
    if(m[5]){
      let cls;
      const call=parenNext(src,TOK.lastIndex);
      if(prevKw==='def')cls='f';
      else if(prevKw==='class')cls='t';
      else if(prevDot)cls=call?'f':'v';
      else if(PURPLE.has(t))cls='k2';
      else if(BLUE.has(t))cls='k';
      else if(TYPES.has(t))cls='t';
      else if(call)cls=/^[A-Z]/.test(t)?'t':'f';
      else if(/^[A-Z][A-Z0-9_]+$/.test(t))cls='cn';
      else if(/^[A-Z]/.test(t))cls='t';
      else cls='v';
      out+='<span class="'+cls+'">'+t+'</span>';
      prevKw=(t==='def'||t==='class')?t:'';
      prevDot=false;
      continue;
    }
    out+=esc(t);
    if(t==='.')prevDot=true;
    else if(!/\s/.test(t)){prevDot=false;prevKw=''}
  }
  return out;
}
/*HL-END*/

/* ---------- Éditeur ---------- */
let LH=19,nLines=0,curLn=1,errMark=null;
function applyFont(){
  LH=Math.round(S.fs*1.36);
  root.style.setProperty('--fs',S.fs+'px');
  root.style.setProperty('--lh',LH+'px');
  syncScroll();positionMarks();
}
function renderHL(){
  const v=ta.value;
  hl.innerHTML=highlight(v)+'\n';
  const n=v.split('\n').length;
  if(n!==nLines){
    nLines=n;
    const f=document.createDocumentFragment();
    for(let i=1;i<=n;i++){const d=document.createElement('div');d.textContent=i;f.appendChild(d)}
    gnums.replaceChildren(f);
    gutter.style.width='calc('+Math.max(2,String(n).length)+'ch + 36px)';
    markGutter();
  }
}
function markGutter(){
  const prev=gnums.querySelector('.on');if(prev)prev.classList.remove('on');
  const bad=gnums.querySelector('.bad');if(bad)bad.classList.remove('bad');
  const c=gnums.children[curLn-1];if(c)c.classList.add('on');
  if(errMark&&errMark.file===S.active){const e=gnums.children[errMark.line-1];if(e)e.classList.add('bad')}
}
function syncScroll(){
  layer.style.transform='translate('+(-ta.scrollLeft)+'px,'+(-ta.scrollTop)+'px)';
  gnums.style.transform='translateY('+(-ta.scrollTop)+'px)';
  positionMarks();
}
function positionMarks(){
  curline.style.top=((curLn-1)*LH-ta.scrollTop)+'px';
  if(errMark&&errMark.file===S.active){
    errline.hidden=false;errline.style.top=((errMark.line-1)*LH-ta.scrollTop)+'px';
  }else errline.hidden=true;
}
function symbolPath(ln){
  const lines=ta.value.split('\n'),stack=[];
  for(let i=0;i<ln&&i<lines.length;i++){
    const l=lines[i];if(!l.trim()||/^\s*#/.test(l))continue;
    const ind=l.match(/^\s*/)[0].length;
    const m=l.match(/^\s*(?:async\s+)?(class|def)\s+(\w+)/);
    while(stack.length&&stack[stack.length-1].ind>=ind)stack.pop();
    if(m)stack.push({ind,name:m[2]});
  }
  return stack.map(s=>s.name);
}
function renderCrumbs(){
  const f=file(S.active);
  if(!f){crumbs.innerHTML='';return}
  const parts=[f.name].concat(symbolPath(curLn));
  crumbs.innerHTML=parts.map((p,i)=>(i?'<i>›</i>':'')+(i===parts.length-1?'<b>'+esc(p)+'</b>':'<span>'+esc(p)+'</span>')).join('');
}
function updateCursor(){
  if(!file(S.active)){stCur.textContent='';return}
  const v=ta.value,s=ta.selectionStart,e=ta.selectionEnd;
  const pos=(e>s&&ta.selectionDirection!=='backward')?e:s;
  const pre=v.slice(0,pos);
  const ln=pre.split('\n').length,col=pos-pre.lastIndexOf('\n');
  const lnChanged=ln!==curLn;
  curLn=ln;
  stCur.textContent='Ln '+ln+', Col '+col+(e>s?' ('+(e-s)+' sélectionné'+(e-s>1?'s':'')+')':'');
  curline.hidden=e!==s;
  markGutter();positionMarks();
  if(lnChanged||!crumbs.firstChild)renderCrumbs();
}
function saveView(){
  if(S.active&&file(S.active))views[S.active]={s:ta.selectionStart,e:ta.selectionEnd,t:ta.scrollTop,l:ta.scrollLeft};
}
function loadEditor(focus){
  const f=file(S.active);
  $('#editor').hidden=!f;$('#welcome').hidden=!!f;
  $('#crumbs').hidden=!f;
  $('#wtitle').textContent=f?f.name+' - Python Online':'Python Online';
  if(!f){stCur.textContent='';return}
  ta.value=f.content;nLines=0;
  renderHL();
  const v=views[f.name];
  if(v){ta.setSelectionRange(v.s,v.e);ta.scrollTop=v.t;ta.scrollLeft=v.l}
  else{ta.setSelectionRange(0,0);ta.scrollTop=0;ta.scrollLeft=0}
  curLn=1;updateCursor();renderCrumbs();syncScroll();
  if(focus)ta.focus({preventScroll:true});
}
ta.addEventListener('input',()=>{
  const f=file(S.active);if(!f)return;
  f.content=ta.value;clearErr();renderHL();persist();updateCursor();
});
ta.addEventListener('scroll',syncScroll);
document.addEventListener('selectionchange',()=>{if(document.activeElement===ta)updateCursor()});

/* Édition : insertion qui garde l'historique d'annulation */
function edit(start,end,text){
  ta.focus();ta.setSelectionRange(start,end);
  let ok=false;try{ok=document.execCommand('insertText',false,text)}catch(e){}
  if(!ok){ta.setRangeText(text,start,end,'end');ta.dispatchEvent(new Event('input',{bubbles:true}))}
}
function removeRange(start,end){
  ta.focus();ta.setSelectionRange(start,end);
  let ok=false;try{ok=document.execCommand('delete')}catch(e){}
  if(!ok){ta.setRangeText('',start,end,'end');ta.dispatchEvent(new Event('input',{bubbles:true}))}
}
const PAIRS={'(':')','[':']','{':'}','"':'"',"'":"'"};
const CLOSERS=new Set([')',']','}','"',"'"]);
function lineRange(){
  const v=ta.value,s=ta.selectionStart,en=ta.selectionEnd;
  const a=v.lastIndexOf('\n',s-1)+1;
  let b=v.indexOf('\n',(en>s&&v[en-1]==='\n')?en-1:en);
  if(b<0)b=v.length;
  return [a,b];
}
function newline(){
  const v=ta.value,s=ta.selectionStart,en=ta.selectionEnd;
  const ls=v.lastIndexOf('\n',s-1)+1,before=v.slice(ls,s);
  let ind=before.match(/^[ \t]*/)[0];
  const opens=/:\s*(#.*)?$/.test(before)||/[(\[{]\s*$/.test(before);
  const extra=opens?'    ':'';
  const a=v[s-1],b=v[en];
  if(s===en&&a&&a!=='"'&&a!=="'"&&PAIRS[a]&&PAIRS[a]===b){
    edit(s,en,'\n'+ind+'    \n'+ind);
    const p=s+1+ind.length+4;ta.setSelectionRange(p,p);return;
  }
  if(!extra&&/^\s*(return|break|continue|pass|raise)\b/.test(before)&&ind.length>=4)ind=ind.slice(0,-4);
  edit(s,en,'\n'+ind+extra);
}
function indent(){
  const v=ta.value,s=ta.selectionStart,en=ta.selectionEnd;
  if(s===en){const ls=v.lastIndexOf('\n',s-1)+1;edit(s,s,' '.repeat(4-((s-ls)%4)));return}
  const [a,b]=lineRange();const lines=v.slice(a,b).split('\n');
  const cnt=lines.filter(l=>l.length).length;
  edit(a,b,lines.map(l=>l.length?'    '+l:l).join('\n'));
  ta.setSelectionRange(s+(lines[0].length?4:0),en+4*cnt);
}
function outdent(){
  const v=ta.value,s=ta.selectionStart,en=ta.selectionEnd;
  const [a,b]=lineRange();let first=0,total=0;
  const out=v.slice(a,b).split('\n').map((l,i)=>{
    const m=l.match(/^( {1,4}|\t)/),r=m?m[0].length:0;
    if(i===0)first=r;total+=r;return l.slice(r);
  });
  if(!total)return;
  edit(a,b,out.join('\n'));
  ta.setSelectionRange(Math.max(a,s-first),Math.max(a,en-total));
}
function toggleComment(){
  const v=ta.value,s=ta.selectionStart,en=ta.selectionEnd;
  const [a,b]=lineRange();const lines=v.slice(a,b).split('\n');
  const ne=lines.filter(l=>l.trim());if(!ne.length)return;
  const all=ne.every(l=>/^\s*#/.test(l));
  let d0=0,total=0,out;
  if(all){
    out=lines.map((l,i)=>{
      if(!l.trim())return l;
      const m=l.match(/^(\s*)# ?/),r=m[0].length-m[1].length;
      if(i===0)d0=-r;total-=r;return m[1]+l.slice(m[0].length);
    });
  }else{
    const ind=Math.min.apply(null,ne.map(l=>l.match(/^\s*/)[0].length));
    out=lines.map((l,i)=>{
      if(!l.trim())return l;
      if(i===0)d0=2;total+=2;return l.slice(0,ind)+'# '+l.slice(ind);
    });
  }
  edit(a,b,out.join('\n'));
  ta.setSelectionRange(Math.max(a,s+d0),Math.max(a,en+total));
}
function zoom(d){
  S.fs=d===0?14:Math.min(28,Math.max(10,S.fs+d));
  applyFont();persist();flash('Taille de police : '+S.fs+' px');
}
ta.addEventListener('keydown',e=>{
  if(e.isComposing)return;
  const v=ta.value,s=ta.selectionStart,en=ta.selectionEnd,mod=e.ctrlKey||e.metaKey;
  if(mod&&!e.shiftKey&&!e.altKey){
    if(e.key==='/'){e.preventDefault();toggleComment();return}
    if(e.key==='='||e.key==='+'){e.preventDefault();zoom(1);return}
    if(e.key==='-'){e.preventDefault();zoom(-1);return}
    if(e.key==='0'){e.preventDefault();zoom(0);return}
  }
  if(e.key==='Tab'&&!mod&&!e.altKey){e.preventDefault();e.shiftKey?outdent():indent();return}
  if(e.key==='Enter'&&!mod&&!e.altKey){e.preventDefault();newline();return}
  if(e.key==='Backspace'&&s===en&&s>0&&!mod&&!e.altKey){
    const a=v[s-1],b=v[s];
    if(PAIRS[a]&&PAIRS[a]===b){e.preventDefault();removeRange(s-1,s+1);return}
  }
  if(!mod&&!e.altKey&&e.key.length===1){
    const k=e.key;
    if(CLOSERS.has(k)&&s===en&&v[s]===k){e.preventDefault();ta.setSelectionRange(s+1,s+1);return}
    if(PAIRS[k]){
      if(s!==en){e.preventDefault();edit(s,en,k+v.slice(s,en)+PAIRS[k]);ta.setSelectionRange(s+1,en+1);return}
      const prev=v[s-1]||'',next=v[s]||'';
      if(k==='"'||k==="'"){
        const prefix=/[rRbBuUfF]/.test(prev)&&!/\w/.test(v[s-2]||'');
        if((/\w/.test(prev)&&!prefix)||prev===k)return;
      }
      if(/\w/.test(next))return;
      e.preventDefault();edit(s,s,k+PAIRS[k]);ta.setSelectionRange(s+1,s+1);
    }
  }
});

/* ---------- Fichiers, onglets, explorateur ---------- */
let armed=null,armTimer=0;
function openFile(name,focus){
  if(!file(name))return;
  saveView();
  if(!S.open.includes(name))S.open.push(name);
  const changed=S.active!==name;
  S.active=name;
  renderTabs();renderFiles();
  if(changed||$('#editor').hidden)loadEditor(focus!==false);
  else if(focus!==false)ta.focus({preventScroll:true});
  if(narrow())hideSidebar();
  persist();
}
function closeTab(name){
  saveView();
  const i=S.open.indexOf(name);if(i<0)return;
  S.open.splice(i,1);
  if(S.active===name)S.active=S.open[Math.min(i,S.open.length-1)]||null;
  renderTabs();renderFiles();loadEditor(false);persist();
}
function renderTabs(){
  tabsEl.replaceChildren();
  for(const n of S.open){
    const t=h('div',{className:'tab'+(n===S.active?' on':''),role:'tab'},ICON.py+'<span></span><button class="x" aria-label="Fermer">'+ICON.close+'</button>');
    t.setAttribute('aria-selected',n===S.active?'true':'false');
    t.setAttribute('data-name',n);t.title=n;
    t.children[1].textContent=n;
    tabsEl.appendChild(t);
  }
  const on=tabsEl.querySelector('.tab.on');if(on&&on.scrollIntoView)on.scrollIntoView({block:'nearest',inline:'nearest'});
}
tabsEl.addEventListener('click',e=>{
  const t=e.target.closest('.tab');if(!t)return;
  const n=t.getAttribute('data-name');
  if(e.target.closest('.x'))closeTab(n);else openFile(n);
});
tabsEl.addEventListener('auxclick',e=>{
  const t=e.target.closest('.tab');if(t&&e.button===1){e.preventDefault();closeTab(t.getAttribute('data-name'))}
});
function renderFiles(){
  filesEl.replaceChildren();
  if(!S.files.length){filesEl.appendChild(h('div',{className:'empty'},'Aucun fichier. Utilise + pour en créer un.'));return}
  for(const f of S.files){
    const row=h('div',{className:'file'+(f.name===S.active?' on':''),role:'listitem',tabIndex:0},
      ICON.py+'<span class="fn"></span><span class="acts"><button class="ib rn" title="Renommer (F2)" aria-label="Renommer">'+ICON.pencil+'</button><button class="ib dl'+(armed===f.name?' arm':'')+'" title="'+(armed===f.name?'Cliquer pour confirmer la suppression':'Supprimer')+'" aria-label="Supprimer">'+ICON.trash+'</button></span>');
    row.setAttribute('data-name',f.name);
    row.querySelector('.fn').textContent=f.name;
    filesEl.appendChild(row);
  }
}
filesEl.addEventListener('click',e=>{
  const row=e.target.closest('.file');if(!row||e.target.closest('.ren'))return;
  const n=row.getAttribute('data-name');
  if(e.target.closest('.rn'))startRename(n);
  else if(e.target.closest('.dl'))deleteFile(n);
  else openFile(n);
});
filesEl.addEventListener('keydown',e=>{
  const row=e.target.closest('.file');if(!row||e.target.classList.contains('ren'))return;
  const n=row.getAttribute('data-name');
  if(e.key==='Enter')openFile(n);
  else if(e.key==='F2'){e.preventDefault();startRename(n)}
  else if(e.key==='Delete')deleteFile(n);
});
function deleteFile(n){
  if(armed!==n){
    armed=n;clearTimeout(armTimer);armTimer=setTimeout(()=>{armed=null;renderFiles()},3000);
    renderFiles();flash('Clique encore sur la corbeille pour supprimer '+n);return;
  }
  armed=null;clearTimeout(armTimer);saveView();
  S.files=S.files.filter(f=>f.name!==n);
  const i=S.open.indexOf(n);if(i>=0)S.open.splice(i,1);
  if(S.active===n)S.active=S.open[Math.min(Math.max(i,0),S.open.length-1)]||null;
  delete views[n];
  renderTabs();renderFiles();loadEditor(false);persist();flash(n+' supprimé');
}
function uniqueName(base){
  if(!file(base))return base;
  const m=base.match(/^(.*?)(\.[^.]*)?$/);let i=2;
  while(file(m[1]+i+(m[2]||'')))i++;
  return m[1]+i+(m[2]||'');
}
function newFile(){
  const n=uniqueName('nouveau.py');
  S.files.push({name:n,content:''});
  showView('explorer',true);
  openFile(n,false);
  startRename(n);
  persist();
}
function startRename(name){
  showView('explorer',true);
  const row=[...filesEl.querySelectorAll('.file')].find(r=>r.getAttribute('data-name')===name);
  if(!row)return;
  const fn=row.querySelector('.fn');
  const inp=h('input',{className:'ren',value:name,type:'text'});
  inp.setAttribute('aria-label','Nouveau nom du fichier');inp.spellcheck=false;
  fn.replaceWith(inp);row.querySelector('.acts').hidden=true;
  inp.focus();inp.setSelectionRange(0,name.lastIndexOf('.')>0?name.lastIndexOf('.'):name.length);
  let done=false;
  const finish=ok=>{
    if(done)return;done=true;
    let v=inp.value.trim();
    if(ok&&v&&v!==name){
      if(/[\\/]/.test(v)){flash('Le nom ne peut pas contenir de barre oblique');v=''}
      else{
        if(!/\.[^.]+$/.test(v))v+='.py';
        if(file(v)){flash(v+' existe déjà');v=''}
      }
      if(v){
        const f=file(name);f.name=v;
        S.open=S.open.map(n=>n===name?v:n);
        if(S.active===name)S.active=v;
        if(views[name]){views[v]=views[name];delete views[name]}
        persist();flash('Renommé en '+v);
      }
    }
    renderFiles();renderTabs();
    $('#wtitle').textContent=S.active?S.active+' - Python Online':'Python Online';
    renderCrumbs();
  };
  inp.addEventListener('keydown',e=>{
    e.stopPropagation();
    if(e.key==='Enter'){e.preventDefault();finish(true)}
    else if(e.key==='Escape'){e.preventDefault();finish(false)}
  });
  inp.addEventListener('blur',()=>finish(true));
}
$('#btn-new').addEventListener('click',newFile);
$('#w-new').addEventListener('click',newFile);

/* ---------- Barre latérale ---------- */
let sideOpen=!narrow(),sideView='explorer';
function renderSide(){
  $('#sidebar').hidden=!sideOpen;
  $('#v-explorer').hidden=sideView!=='explorer';
  $('#v-search').hidden=sideView!=='search';
  $('#ab-explorer').classList.toggle('on',sideOpen&&sideView==='explorer');
  $('#ab-search').classList.toggle('on',sideOpen&&sideView==='search');
}
function showView(v,force){
  if(!force&&sideOpen&&sideView===v)sideOpen=false;
  else{sideOpen=true;sideView=v}
  renderSide();
  if(sideOpen&&v==='search'){const q=$('#q');q.focus();q.select()}
}
function hideSidebar(){sideOpen=false;renderSide()}
$('#ab-explorer').addEventListener('click',()=>showView('explorer'));
$('#ab-search').addEventListener('click',()=>showView('search'));

function gotoLine(name,line,col,len){
  openFile(name,false);
  const v=ta.value;let idx=0;
  for(let i=1;i<line;i++){const j=v.indexOf('\n',idx);if(j<0)break;idx=j+1}
  const p=Math.min(v.length,idx+Math.max(0,(col||1)-1));
  ta.focus({preventScroll:true});
  ta.setSelectionRange(p,p+(len||0));
  ta.scrollTop=Math.max(0,(line-1)*LH-ta.clientHeight/2);
  syncScroll();updateCursor();
}
function doSearch(){
  const q=$('#q').value,res=$('#results');res.replaceChildren();
  if(!q)return;
  const ql=q.toLowerCase();let total=0;
  for(const f of S.files){
    const hits=[];
    f.content.split('\n').forEach((l,i)=>{const k=l.toLowerCase().indexOf(ql);if(k>=0)hits.push({i,k,l})});
    if(!hits.length)continue;total+=hits.length;
    const g=h('div',{className:'sg'},ICON.py+'<span></span><span class="n">'+hits.length+'</span>');
    g.children[1].textContent=f.name;res.appendChild(g);
    for(const x of hits){
      const b=h('button',{className:'sh'});
      const start=Math.max(0,x.k-20);
      b.append(document.createTextNode((start?'…':'')+x.l.slice(start,x.k).replace(/^\s+/,'')));
      const m=document.createElement('b');m.textContent=x.l.slice(x.k,x.k+q.length);b.appendChild(m);
      b.append(document.createTextNode(x.l.slice(x.k+q.length,x.k+q.length+80)));
      b.addEventListener('click',()=>gotoLine(f.name,x.i+1,x.k+1,q.length));
      res.appendChild(b);
    }
  }
  if(!total)res.appendChild(h('div',{className:'empty'},'Aucun résultat.'));
}
$('#q').addEventListener('input',doSearch);

/* ---------- Panneau : terminal et problèmes ---------- */
let panelOpen=true,pview='terminal',problems=[];
function showPanel(v){
  panelOpen=true;if(v)pview=v;renderPanel();
}
function renderPanel(){
  panel.hidden=!panelOpen;sash.hidden=!panelOpen;
  term.hidden=pview!=='terminal';probs.hidden=pview!=='problems';
  $('#pt-terminal').classList.toggle('on',pview==='terminal');
  $('#pt-problems').classList.toggle('on',pview==='problems');
  $('#p-clear').hidden=pview!=='terminal';
}
function togglePanel(){panelOpen=!panelOpen;renderPanel()}
$('#pt-terminal').addEventListener('click',()=>showPanel('terminal'));
$('#pt-problems').addEventListener('click',()=>showPanel('problems'));
$('#p-close').addEventListener('click',()=>{panelOpen=false;renderPanel()});
$('#p-clear').addEventListener('click',clearTerm);
stProb.addEventListener('click',()=>showPanel('problems'));
function clearTerm(){term.replaceChildren()}
function twrite(text,cls){
  if(!text)return;
  const pending=term.querySelector('.tin');
  let node;
  if(cls){node=document.createElement('span');node.className=cls;node.textContent=text}
  else node=document.createTextNode(text);
  term.appendChild(node);
  pbody.scrollTop=pbody.scrollHeight;
  return pending;
}
function renderProblems(){
  const n=problems.length;
  $('#pbadge').hidden=!n;$('#pbadge').textContent=n;
  stProb.innerHTML=ICON.err+'<span>'+n+'</span>';
  stProb.setAttribute('aria-label',n+' problème'+(n>1?'s':''));
  probs.replaceChildren();
  if(!n){probs.appendChild(h('div',{className:'none'},"Aucun problème détecté. Les erreurs d'exécution apparaissent ici."));return}
  for(const p of problems){
    const b=h('button',{className:'prob'},ICON.err+'<span class="msg"></span><span class="loc"></span>');
    b.querySelector('.msg').textContent=p.msg;
    b.querySelector('.loc').textContent=p.file+' ['+(p.line?'Ln '+p.line+', Col '+(p.col||1):'')+']';
    b.addEventListener('click',()=>{if(p.line&&file(p.file))gotoLine(p.file,p.line,p.col)});
    probs.appendChild(b);
  }
}
function clearProblems(){problems=[];renderProblems();clearErr()}
function clearErr(){if(errMark){errMark=null;markGutter();positionMarks()}}
let flashTimer=0;
function flash(t){stMsg.textContent=t;clearTimeout(flashTimer);flashTimer=setTimeout(()=>{stMsg.textContent=''},3500)}

/* Séparateur redimensionnable */
sash.addEventListener('pointerdown',e=>{
  e.preventDefault();sash.setPointerCapture(e.pointerId);
  const wb=$('#workbench');
  const move=ev=>{
    const r=wb.getBoundingClientRect();
    const hgt=Math.max(80,Math.min(r.height-170,r.bottom-ev.clientY));
    root.style.setProperty('--panel-h',hgt+'px');
  };
  const up=()=>{sash.removeEventListener('pointermove',move);sash.removeEventListener('pointerup',up)};
  sash.addEventListener('pointermove',move);sash.addEventListener('pointerup',up);
});

/* ---------- Exécution Python (Skulpt) ---------- */
let running=false,stopFlag=false,pendingInput=null;
const hasEngine=()=>typeof Sk!=='undefined'&&Sk&&Sk.configure;
function engineLabel(){return !hasEngine()?'Moteur indisponible':(running?'Exécution…':'Python 3 (Skulpt)')}
function setRunUI(){
  runbtn.innerHTML=running?ICON.stop:ICON.play;
  runbtn.title=running?'Arrêter (Maj+F5)':'Exécuter le fichier Python (F5)';
  runbtn.setAttribute('aria-label',runbtn.title);
  runbtn.classList.toggle('run-on',running);
  stEng.textContent=engineLabel();
}
function readFileForSkulpt(x){
  if(Sk.builtinFiles&&Sk.builtinFiles.files&&Sk.builtinFiles.files[x]!==undefined)return Sk.builtinFiles.files[x];
  const base=String(x).replace(/^.*\//,'');
  if(/\.py$/.test(base)){const uf=file(base);if(uf)return uf.content}
  throw "File not found: '"+x+"'";
}
function readLine(prompt){
  return new Promise(res=>{
    if(prompt)twrite(String(prompt));
    const inp=h('input',{className:'tin',type:'text'});
    inp.setAttribute('aria-label','Entrée du programme');inp.spellcheck=false;inp.autocomplete='off';
    term.appendChild(inp);pbody.scrollTop=pbody.scrollHeight;inp.focus();
    const finish=v=>{
      if(!pendingInput||pendingInput.inp!==inp)return;
      pendingInput=null;inp.replaceWith(document.createTextNode(v+'\n'));res(v);
    };
    inp.addEventListener('input',()=>{inp.style.width=Math.max(2,inp.value.length+1)+'ch'});
    inp.addEventListener('keydown',e=>{if(e.key==='Enter'){e.preventDefault();finish(inp.value)}});
    pendingInput={inp,finish};
  });
}
function mapName(fn,fallback){
  if(!fn)return fallback;
  const b=String(fn).replace(/^.*\//,'');
  return /^<stdin>(\.py)?$/.test(b)?fallback:b;
}
function reportError(err,f){
  if(err&&err.message==='__STOP__'){twrite('\nKeyboardInterrupt\n','err');return}
  const raw=String(err&&err.toString?err.toString():err);
  const isPy=err&&(err.tp$name||(hasEngine()&&Sk.builtin.BaseException&&err instanceof Sk.builtin.BaseException));
  if(!isPy&&/unsafe-eval|EvalError|Content Security Policy/i.test(raw+(err&&err.name||''))){
    const m="Le navigateur bloque l'exécution de code compilé dans cette page, donc le moteur Python ne peut pas tourner ici.";
    twrite(m+'\n','err');problems=[{file:f.name,line:0,col:0,msg:m}];renderProblems();return;
  }
  if(!isPy){
    const m='Erreur interne du moteur : '+raw;
    twrite(m+'\n','err');problems=[{file:f.name,line:0,col:0,msg:m}];renderProblems();return;
  }
  const tb=Array.isArray(err.traceback)?err.traceback:[];
  const msg=raw.replace(/\s+on line \d+\s*$/,'').replace(/\s+at line \d+\s*$/,'');
  let line=0,col=0,fname=f.name;
  if(tb.length){
    const inner=tb[0];
    line=inner.lineno||0;col=inner.colno?inner.colno+1:1;fname=mapName(inner.filename,f.name);
  }else{
    const m=raw.match(/on line (\d+)/);if(m)line=+m[1];
  }
  let text='Traceback (most recent call last):\n';
  const frames=tb.slice().reverse();
  if(frames.length)for(const fr of frames)text+='  File "'+mapName(fr.filename,f.name)+'", line '+(fr.lineno||'?')+'\n';
  else if(line)text+='  File "'+f.name+'", line '+line+'\n';
  text+=msg+'\n';
  twrite(text,'err');
  problems=[{file:fname,line,col,msg}];renderProblems();
  if(line&&file(fname)){errMark={file:fname,line};markGutter();positionMarks()}
}
async function run(){
  if(running){stop();return}
  const f=file(S.active);
  if(!f){flash("Ouvre ou crée un fichier d'abord");return}
  persistNow();
  showPanel('terminal');clearProblems();
  twrite('> python '+f.name+'\n','cmd');
  if(!hasEngine()){
    twrite("Le moteur Python n'a pas pu se charger (connexion ou CDN bloqué). Recharge la page puis réessaie.\n",'err');
    stEng.textContent=engineLabel();return;
  }
  running=true;stopFlag=false;setRunUI();
  const t0=performance.now();let code=0;
  try{
    Sk.configure({
      output:t=>{twrite(t)},
      read:readFileForSkulpt,
      inputfun:p=>readLine(p),
      inputfunTakesPrompt:true,
      __future__:Sk.python3,
      yieldLimit:100
    });
    await Sk.misceval.asyncToPromise(
      ()=>Sk.importMainWithBody('<stdin>',false,f.content,true),
      {'*':()=>{if(stopFlag)throw new Error('__STOP__')}}
    );
  }catch(err){
    code=(err&&err.message==='__STOP__')?130:1;
    try{reportError(err,f)}catch(e2){twrite(String(err)+'\n','err')}
  }
  if(pendingInput){const p=pendingInput;pendingInput=null;p.inp.remove()}
  running=false;setRunUI();
  const dt=((performance.now()-t0)/1000).toFixed(2);
  twrite('\n[Terminé avec le code '+code+' en '+dt+' s]\n','dim');
}
function stop(){
  if(!running)return;
  stopFlag=true;
  if(pendingInput)pendingInput.finish('');
}
runbtn.addEventListener('click',run);
function about(){
  showPanel('terminal');
  twrite('Python Online : moteur Skulpt (Python 3, sous-ensemble).\n'+
    "Disponible : les bases du langage et des modules comme math, random, time, re, json, collections, itertools.\n"+
    "Pas de pip, de numpy ni d'accès réseau. input() lit dans ce terminal, et tu peux importer tes autres fichiers .py.\n\n",'dim');
}

/* ---------- Menus ---------- */
const exec=c=>{ta.focus();try{document.execCommand(c)}catch(e){}};
const MENUS=[
  ['Fichier',[['Nouveau fichier','Alt+N',newFile],['Enregistrer','Ctrl+S',save],['Renommer','F2',()=>S.active&&startRename(S.active)],['Fermer l\'onglet','Alt+W',()=>S.active&&closeTab(S.active)]]],
  ['Édition',[['Annuler','Ctrl+Z',()=>exec('undo')],['Rétablir','Ctrl+Y',()=>exec('redo')],null,['Tout sélectionner','Ctrl+A',()=>{ta.focus();ta.select()}],['Commenter la ligne','Ctrl+/',()=>{ta.focus();toggleComment()}]]],
  ['Affichage',[['Explorateur','Ctrl+Maj+E',()=>showView('explorer',true)],['Rechercher','Ctrl+Maj+F',()=>showView('search',true)],['Panneau','Ctrl+J',togglePanel],null,['Zoom avant','Ctrl+=',()=>zoom(1)],['Zoom arrière','Ctrl+-',()=>zoom(-1)],['Réinitialiser le zoom','Ctrl+0',()=>zoom(0)]]],
  ['Exécuter',[['Exécuter le fichier Python','F5',run],['Arrêter','Maj+F5',stop]]],
  ['Terminal',[['Afficher le terminal','',()=>showPanel('terminal')],['Effacer le terminal','',clearTerm]]],
  ['Aide',[['À propos du moteur Python','',about]]]
];
let openMenu=null;
function closeDD(){if(openMenu){openMenu.dd.remove();openMenu.btn.classList.remove('open');openMenu=null}}
function openDD(btn,items){
  closeDD();
  const r=btn.getBoundingClientRect();
  const dd=h('div',{className:'dd',role:'menu'});
  dd.style.left=Math.min(r.left,window.innerWidth-260)+'px';dd.style.top=r.bottom+'px';
  for(const it of items){
    if(!it){dd.appendChild(h('div',{className:'sep'}));continue}
    const b=h('button',{className:'mi',role:'menuitem'},'<span></span><kbd></kbd>');
    b.children[0].textContent=it[0];b.children[1].textContent=it[1];
    b.addEventListener('click',()=>{closeDD();it[2]()});
    dd.appendChild(b);
  }
  document.body.appendChild(dd);btn.classList.add('open');openMenu={btn,dd};
}
const bar=$('#menubar');
for(const [label,items] of MENUS){
  const b=h('button',{type:'button'});b.textContent=label;
  b.addEventListener('click',()=>{openMenu&&openMenu.btn===b?closeDD():openDD(b,items)});
  b.addEventListener('mouseenter',()=>{if(openMenu&&openMenu.btn!==b)openDD(b,items)});
  bar.appendChild(b);
}
document.addEventListener('pointerdown',e=>{if(openMenu&&!openMenu.dd.contains(e.target)&&!bar.contains(e.target))closeDD()});

/* ---------- Raccourcis globaux ---------- */
function save(){
  const f=file(S.active);if(!f)return;
  persistNow();flash(f.name+' enregistré dans ce navigateur');
}
document.addEventListener('keydown',e=>{
  const mod=e.ctrlKey||e.metaKey,k=e.key;
  if(k==='Escape'&&openMenu){closeDD();return}
  if(k==='F5'&&!e.shiftKey){e.preventDefault();run();return}
  if(k==='F5'&&e.shiftKey){e.preventDefault();stop();return}
  if(mod&&!e.shiftKey&&!e.altKey&&k.toLowerCase()==='s'){e.preventDefault();save();return}
  if(mod&&!e.shiftKey&&k==='Enter'&&document.activeElement!==ta){e.preventDefault();run();return}
  if(mod&&!e.shiftKey&&!e.altKey&&k.toLowerCase()==='j'){e.preventDefault();togglePanel();return}
  if(mod&&e.shiftKey&&k.toLowerCase()==='e'){e.preventDefault();showView('explorer',true);return}
  if(mod&&e.shiftKey&&k.toLowerCase()==='f'){e.preventDefault();showView('search',true);return}
  if(mod&&!e.shiftKey&&!e.altKey&&k==='Enter'&&document.activeElement===ta){e.preventDefault();run();return}
  if(e.altKey&&!mod&&k.toLowerCase()==='n'){e.preventDefault();newFile();return}
  if(e.altKey&&!mod&&k.toLowerCase()==='w'){e.preventDefault();if(S.active)closeTab(S.active);return}
  if(k==='F2'&&document.activeElement===ta&&S.active){e.preventDefault();startRename(S.active)}
});
term.addEventListener('click',()=>{
  const sel=window.getSelection();
  if(pendingInput&&(!sel||sel.isCollapsed))pendingInput.inp.focus();
});

/* ---------- Démarrage ---------- */
applyFont();
renderTabs();renderFiles();renderSide();renderPanel();renderProblems();loadEditor(false);setRunUI();
term.appendChild(h('span',{className:'dim'}));
term.lastChild.textContent='Prêt. Appuie sur F5 ou sur le bouton ▶ pour exécuter le fichier actif.\n';
if(!hasEngine())flash("Le moteur Python n'a pas pu se charger");
})();
</script>

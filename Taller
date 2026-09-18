<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Hierro Crudo — Muebles industriales a medida</title>
<meta name="description" content="Taller de muebles industriales: acero y madera maciza. Mesas, escritorios, estanterías y piezas a medida.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,700;12..96,800&family=Archivo:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --concreto:#CFCBC3;
  --papel:#E5E2DC;
  --tinta:#17191A;
  --tinta-suave:#5A6166;
  --acero:#3E474C;
  --linea:#A8A49B;
  --madera:#9A5F2E;
  --senal:#E5A600;
  --sombra:rgba(23,25,26,.16);
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){
    --concreto:#131618;
    --papel:#1D2225;
    --tinta:#E8E5E0;
    --tinta-suave:#9AA3A8;
    --acero:#C3CBCF;
    --linea:#3A4246;
    --madera:#C98B4B;
    --senal:#F0BC26;
    --sombra:rgba(0,0,0,.5);
  }
}
:root[data-theme="dark"]{
  --concreto:#131618;
  --papel:#1D2225;
  --tinta:#E8E5E0;
  --tinta-suave:#9AA3A8;
  --acero:#C3CBCF;
  --linea:#3A4246;
  --madera:#C98B4B;
  --senal:#F0BC26;
  --sombra:rgba(0,0,0,.5);
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
@media (prefers-reduced-motion: reduce){html{scroll-behavior:auto} *{animation:none!important;transition:none!important}}
body{
  margin:0;
  background:var(--concreto);
  color:var(--tinta);
  font-family:"Archivo",system-ui,-apple-system,"Segoe UI",sans-serif;
  font-size:17px;
  line-height:1.6;
  -webkit-font-smoothing:antialiased;
}
body::before{
  content:"";position:fixed;inset:0;pointer-events:none;z-index:0;opacity:.35;
  background-image:radial-gradient(var(--linea) .5px, transparent .6px);
  background-size:4px 4px;
}
.wrap{max-width:1180px;margin:0 auto;padding:0 24px;position:relative;z-index:1}
h1,h2,h3{font-family:"Bricolage Grotesque",Archivo,sans-serif;font-weight:800;letter-spacing:-.02em;line-height:1.02;margin:0}
h1{font-size:clamp(2.6rem,7vw,5.2rem)}
h2{font-size:clamp(1.9rem,3.6vw,2.9rem)}
h3{font-size:1.15rem;font-weight:700;letter-spacing:-.01em}
p{margin:0 0 1em;max-width:62ch}
a{color:inherit}
:focus-visible{outline:2px solid var(--senal);outline-offset:3px}

/* barra superior */
header.top{
  position:sticky;top:0;z-index:20;
  background:color-mix(in srgb, var(--concreto) 88%, transparent);
  backdrop-filter:blur(8px);
  border-bottom:1px solid var(--linea);
}
.top .wrap{display:flex;align-items:center;gap:20px;height:62px}
.marca{display:flex;align-items:center;gap:10px;font-family:"Bricolage Grotesque",sans-serif;font-weight:800;font-size:1.05rem;letter-spacing:-.01em;text-decoration:none}
.marca svg{flex:none}
nav.menu{margin-left:auto;display:flex;gap:22px}
nav.menu a{text-decoration:none;font-size:.95rem;color:var(--tinta-suave);padding:4px 0;border-bottom:2px solid transparent}
nav.menu a:hover{color:var(--tinta);border-bottom-color:var(--senal)}
@media (max-width:820px){nav.menu{display:none}}
.tema{margin-left:auto;border:1px solid var(--linea);background:none;color:var(--tinta-suave);font:inherit;font-size:.85rem;padding:6px 12px;cursor:pointer}
@media (min-width:821px){.tema{margin-left:22px}}
.tema:hover{color:var(--tinta);border-color:var(--acero)}

/* hero como hoja de taller */
.hero{padding:56px 0 20px}
.hoja{
  border:1px solid var(--acero);
  background:var(--papel);
  box-shadow:6px 6px 0 var(--sombra);
}
.hoja-cabeza{
  display:flex;flex-wrap:wrap;gap:8px 28px;align-items:baseline;
  border-bottom:1px solid var(--linea);padding:12px 22px;font-size:.82rem;color:var(--tinta-suave)
}
.hoja-cabeza b{color:var(--tinta);font-weight:600}
.hoja-cuerpo{display:grid;grid-template-columns:1.05fr 1fr;gap:0}
@media (max-width:900px){.hoja-cuerpo{grid-template-columns:1fr}}
.hoja-texto{padding:38px 32px 34px}
.hoja-dibujo{border-left:1px solid var(--linea);padding:18px;display:flex;align-items:center;justify-content:center;background:
  linear-gradient(var(--linea) 1px, transparent 1px) 0 0/100% 28px,
  linear-gradient(90deg, var(--linea) 1px, transparent 1px) 0 0/28px 100%;
  background-color:transparent;
}
@media (max-width:900px){.hoja-dibujo{border-left:none;border-top:1px solid var(--linea)}}
.hoja-dibujo svg{width:100%;height:auto;max-width:100%}
.sub{font-size:1.12rem;color:var(--tinta-suave);margin-top:20px}
.acciones{display:flex;flex-wrap:wrap;gap:12px;margin-top:26px}
.btn{
  display:inline-block;text-decoration:none;font:inherit;font-weight:600;font-size:.98rem;
  padding:13px 22px;border:1px solid var(--tinta);background:var(--senal);color:#17191A;cursor:pointer;
  transition:transform .12s ease, box-shadow .12s ease;
  box-shadow:3px 3px 0 var(--tinta);
}
.btn:hover{transform:translate(-1px,-1px);box-shadow:5px 5px 0 var(--tinta)}
.btn:active{transform:translate(1px,1px);box-shadow:1px 1px 0 var(--tinta)}
.btn.ghost{background:transparent;color:var(--tinta);box-shadow:3px 3px 0 var(--linea)}
.btn.ghost:hover{box-shadow:5px 5px 0 var(--linea)}
.datos{display:flex;flex-wrap:wrap;gap:26px;margin-top:30px;padding-top:20px;border-top:1px dashed var(--linea)}
.datos div{font-size:.9rem;color:var(--tinta-suave);max-width:20cEh}
.datos strong{display:block;font-family:"Bricolage Grotesque",sans-serif;font-size:1.25rem;color:var(--tinta);font-weight:700;letter-spacing:-.01em}

/* secciones */
section{padding:72px 0}
.enc{display:flex;align-items:flex-end;justify-content:space-between;gap:24px;flex-wrap:wrap;margin-bottom:34px}
.enc p{color:var(--tinta-suave);margin:10px 0 0}
.cota{display:flex;align-items:center;gap:0;margin:0 0 34px}
.cota i{display:block;width:1px;height:12px;background:var(--acero)}
.cota span{flex:1;height:1px;background:var(--acero)}

/* catálogo */
.piezas{display:grid;grid-template-columns:repeat(3,1fr);gap:1px;background:var(--linea);border:1px solid var(--linea)}
@media (max-width:900px){.piezas{grid-template-columns:repeat(2,1fr)}}
@media (max-width:600px){.piezas{grid-template-columns:1fr}}
.pieza{background:var(--papel);padding:22px;display:flex;flex-direction:column}
.pieza figure{margin:0 0 16px;background:var(--concreto);border:1px solid var(--linea);padding:14px;display:flex;align-items:center;justify-content:center;min-height:170px}
.pieza figure svg{width:100%;height:auto;max-height:150px}
.pieza h3{margin-bottom:8px}
.pieza .desc{font-size:.92rem;color:var(--tinta-suave);margin:0 0 14px}
.specs{list-style:none;margin:0 0 18px;padding:0;font-size:.86rem;color:var(--tinta-suave);border-top:1px solid var(--linea)}
.specs li{display:flex;justify-content:space-between;gap:12px;padding:6px 0;border-bottom:1px solid var(--linea)}
.specs li b{color:var(--tinta);font-weight:500;text-align:right}
.precio{margin-top:auto;display:flex;align-items:baseline;justify-content:space-between;gap:12px}
.precio .q{font-family:"Bricolage Grotesque",sans-serif;font-weight:700;font-size:1.5rem;letter-spacing:-.02em}
.precio small{color:var(--tinta-suave);font-size:.78rem}
.pieza .btn{margin-top:14px;text-align:center;font-size:.9rem;padding:11px 16px}

/* cotizador */
.cotiza{display:grid;grid-template-columns:1.1fr .9fr;gap:1px;background:var(--linea);border:1px solid var(--acero);box-shadow:6px 6px 0 var(--sombra)}
@media (max-width:820px){.cotiza{grid-template-columns:1fr}}
.cotiza > div{background:var(--papel);padding:28px}
.campo{margin-bottom:20px}
.campo label{display:block;font-size:.88rem;font-weight:600;margin-bottom:8px}
.campo .val{float:right;font-weight:400;color:var(--tinta-suave)}
select,input[type=text],input[type=email],textarea{
  width:100%;font:inherit;font-size:.95rem;padding:11px 12px;color:var(--tinta);
  background:var(--concreto);border:1px solid var(--acero);border-radius:0;
}
textarea{min-height:110px;resize:vertical}
input[type=range]{width:100%;accent-color:var(--senal);background:transparent}
.opciones{display:flex;flex-wrap:wrap;gap:8px}
.opciones button{
  font:inherit;font-size:.9rem;padding:9px 14px;cursor:pointer;
  background:var(--concreto);color:var(--tinta);border:1px solid var(--acero);
}
.opciones button[aria-pressed="true"]{background:var(--senal);color:#17191A;border-color:var(--tinta)}
.resumen{display:flex;flex-direction:column}
.resumen dl{margin:0 0 18px;font-size:.92rem}
.resumen dl div{display:flex;justify-content:space-between;gap:12px;padding:8px 0;border-bottom:1px solid var(--linea)}
.resumen dt{color:var(--tinta-suave)}
.resumen dd{margin:0;font-weight:500}
.total{font-family:"Bricolage Grotesque",sans-serif;font-weight:800;font-size:clamp(2rem,5vw,2.8rem);letter-spacing:-.03em;line-height:1;margin:6px 0 4px}
.nota{font-size:.82rem;color:var(--tinta-suave);margin:0 0 18px}

/* proceso */
.pasos{display:grid;grid-template-columns:repeat(4,1fr);gap:26px}
@media (max-width:900px){.pasos{grid-template-columns:repeat(2,1fr)}}
@media (max-width:540px){.pasos{grid-template-columns:1fr}}
.paso{border-top:3px solid var(--acero);padding-top:14px}
.paso b{display:block;font-family:"Bricolage Grotesque",sans-serif;font-size:1.6rem;line-height:1;color:var(--senal);margin-bottom:6px}
.paso p{font-size:.92rem;color:var(--tinta-suave);margin:6px 0 0}

/* materiales */
.mats{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
@media (max-width:820px){.mats{grid-template-columns:1fr}}
.mat{display:flex;gap:16px;align-items:flex-start}
.muestra{flex:none;width:62px;height:62px;border:1px solid var(--acero)}
.m-negro{background:linear-gradient(135deg,#2A2E31,#101314)}
.m-crudo{background:linear-gradient(135deg,#9AA0A3,#6E7679)}
.m-galv{background:repeating-linear-gradient(45deg,#B9BEC0,#B9BEC0 6px,#98A0A3 6px,#98A0A3 12px)}
.m-conacaste{background:linear-gradient(135deg,#8A5A33,#5E3A1E)}
.m-pino{background:linear-gradient(135deg,#D9B183,#B78A54)}
.m-cedro{background:linear-gradient(135deg,#A9683C,#7A4526)}
.mat h3{font-size:1rem}
.mat p{font-size:.9rem;color:var(--tinta-suave);margin:4px 0 0}

/* contacto */
.contacto{display:grid;grid-template-columns:1fr 1fr;gap:40px}
@media (max-width:820px){.contacto{grid-template-columns:1fr}}
.lista{list-style:none;margin:22px 0 0;padding:0}
.lista li{padding:12px 0;border-bottom:1px solid var(--linea);font-size:.95rem;display:flex;gap:14px}
.lista li span{color:var(--tinta-suave);min-width:110px}
footer{border-top:1px solid var(--linea);padding:28px 0;font-size:.85rem;color:var(--tinta-suave)}
footer .wrap{display:flex;flex-wrap:wrap;gap:14px;justify-content:space-between}
.stroke{fill:none;stroke:var(--acero);stroke-width:2;stroke-linecap:square}
.thin{fill:none;stroke:var(--linea);stroke-width:1}
.wood{fill:var(--madera);opacity:.85}
.cotatxt{fill:var(--tinta-suave);font-family:Archivo,sans-serif;font-size:11px}
</style>
</head>
<body>

<header class="top">
  <div class="wrap">
    <a class="marca" href="#inicio">
      <svg width="24" height="24" viewBox="0 0 24 24" aria-hidden="true"><rect x="2" y="5" width="20" height="3" fill="var(--senal)"/><path d="M5 8v11M19 8v11M5 13h14" stroke="var(--tinta)" stroke-width="2" fill="none"/></svg>
      Hierro Crudo
    </a>
    <nav class="menu">
      <a href="#catalogo">Catálogo</a>
      <a href="#medida">A medida</a>
      <a href="#proceso">Cómo trabajamos</a>
      <a href="#materiales">Materiales</a>
      <a href="#contacto">Contacto</a>
    </nav>
    <button class="tema" id="tema" aria-label="Cambiar entre modo claro y oscuro">Modo oscuro</button>
  </div>
</header>

<main id="inicio">

<div class="wrap hero">
  <div class="hoja">
    <div class="hoja-cabeza">
      <span>Taller <b>Hierro Crudo</b></span>
      <span>Ciudad de Guatemala</span>
      <span>Acero + madera maciza</span>
      <span>Plano <b>HC-001</b></span>
    </div>
    <div class="hoja-cuerpo">
      <div class="hoja-texto">
        <h1>Muebles que se ven por dentro</h1>
        <p class="sub">Soldamos estructura de acero y la montamos con madera maciza local. Cada pieza sale del taller con sus medidas reales, no con una talla estándar.</p>
        <div class="acciones">
          <a class="btn" href="#catalogo">Ver el catálogo</a>
          <a class="btn ghost" href="#medida">Cotizar una pieza a medida</a>
        </div>
        <div class="datos">
          <div><strong>3 a 4 semanas</strong>de fabricación</div>
          <div><strong>5 años</strong>de garantía en la soldadura</div>
          <div><strong>Entrega</strong>en toda Guatemala</div>
        </div>
      </div>
      <div class="hoja-dibujo">
        <svg viewBox="0 0 420 300" role="img" aria-label="Dibujo técnico de una mesa industrial con sus medidas">
          <!-- tablón -->
          <rect class="wood" x="60" y="92" width="300" height="20"/>
          <rect class="stroke" x="60" y="92" width="300" height="20"/>
          <line class="thin" x1="60" y1="102" x2="360" y2="102"/>
          <!-- patas tipo A -->
          <path class="stroke" d="M95 112 L80 250 M145 112 L160 250 M86 195 L154 195 M72 250 L100 250 M148 250 L172 250"/>
          <path class="stroke" d="M275 112 L260 250 M325 112 L340 250 M266 195 L334 195 M252 250 L280 250 M328 250 L352 250"/>
          <!-- travesaño -->
          <path class="stroke" d="M120 160 L300 160"/>
          <!-- cotas -->
          <path class="thin" d="M60 70 L360 70 M60 62 L60 78 M360 62 L360 78"/>
          <text class="cotatxt" x="188" y="62" text-anchor="middle">200 cm</text>
          <path class="thin" d="M390 92 L390 250 M382 92 L398 92 M382 250 L398 250"/>
          <text class="cotatxt" x="386" y="175" text-anchor="middle" transform="rotate(90 386 175)">75 cm</text>
          <path class="thin" d="M40 92 L40 112 M32 92 L48 92 M32 112 L48 112"/>
          <text class="cotatxt" x="14" y="107">5 cm</text>
          <!-- referencia -->
          <circle class="thin" cx="210" cy="92" r="16"/>
          <text class="cotatxt" x="210" y="96" text-anchor="middle">A</text>
          <text class="cotatxt" x="60" y="278">A — tablón de conacaste, acabado aceite mate</text>
        </svg>
      </div>
    </div>
  </div>
</div>

<section id="catalogo">
  <div class="wrap">
    <div class="enc">
      <div>
        <h2>Catálogo del taller</h2>
        <p>Piezas que fabricamos de forma recurrente. Todas admiten cambio de medidas, acabado y tipo de madera.</p>
      </div>
      <a class="btn ghost" href="#contacto">Pedir el catálogo en PDF</a>
    </div>

    <div class="piezas">

      <article class="pieza">
        <figure>
          <svg viewBox="0 0 220 150" role="img" aria-label="Mesa de comedor con patas de acero en A">
            <rect class="wood" x="20" y="40" width="180" height="12"/><rect class="stroke" x="20" y="40" width="180" height="12"/>
            <path class="stroke" d="M45 52 L32 125 M80 52 L93 125 M40 95 L86 95 M60 75 L165 75 M145 52 L132 125 M180 52 L193 125 M140 95 L186 95"/>
          </svg>
        </figure>
        <h3>Mesa de comedor Taller</h3>
        <p class="desc">Tablón de una sola pieza sobre patas en A soldadas a tope.</p>
        <ul class="specs">
          <li>Medidas <b>200 × 90 × 75 cm</b></li>
          <li>Estructura <b>Tubo 2" cal. 14</b></li>
          <li>Tapa <b>Conacaste 5 cm</b></li>
          <li>Capacidad <b>8 personas</b></li>
        </ul>
        <div class="precio"><span class="q">Q 7,450</span><small>IVA incluido</small></div>
        <a class="btn" href="#contacto">Cotizar esta mesa</a>
      </article>

      <article class="pieza">
        <figure>
          <svg viewBox="0 0 220 150" role="img" aria-label="Escritorio con estructura de acero y cajón">
            <rect class="wood" x="25" y="45" width="170" height="10"/><rect class="stroke" x="25" y="45" width="170" height="10"/>
            <path class="stroke" d="M40 55 L40 125 M195 55 L195 125 M40 125 L195 125 M40 70 L195 70"/>
            <rect class="stroke" x="120" y="58" width="60" height="26"/>
            <path class="stroke" d="M142 71 L158 71"/>
          </svg>
        </figure>
        <h3>Escritorio Planta</h3>
        <p class="desc">Superficie limpia, pasacables oculto y un cajón metálico bajo la tapa.</p>
        <ul class="specs">
          <li>Medidas <b>140 × 65 × 75 cm</b></li>
          <li>Estructura <b>Tubo cuadrado 1½"</b></li>
          <li>Tapa <b>Pino macizo 3 cm</b></li>
          <li>Extras <b>Cajón + pasacables</b></li>
        </ul>
        <div class="precio"><span class="q">Q 3,980</span><small>IVA incluido</small></div>
        <a class="btn" href="#contacto">Cotizar este escritorio</a>
      </article>

      <article class="pieza">
        <figure>
          <svg viewBox="0 0 220 150" role="img" aria-label="Estantería abierta de cinco niveles">
            <path class="stroke" d="M45 15 L45 135 M175 15 L175 135"/>
            <rect class="wood" x="45" y="35" width="130" height="8"/><rect class="stroke" x="45" y="35" width="130" height="8"/>
            <rect class="wood" x="45" y="65" width="130" height="8"/><rect class="stroke" x="45" y="65" width="130" height="8"/>
            <rect class="wood" x="45" y="95" width="130" height="8"/><rect class="stroke" x="45" y="95" width="130" height="8"/>
            <rect class="wood" x="45" y="125" width="130" height="8"/><rect class="stroke" x="45" y="125" width="130" height="8"/>
            <path class="thin" d="M45 15 L175 15"/>
          </svg>
        </figure>
        <h3>Estantería Andamio</h3>
        <p class="desc">Cuatro repisas fijas, anclaje a muro incluido. Se puede apilar en módulos.</p>
        <ul class="specs">
          <li>Medidas <b>90 × 40 × 180 cm</b></li>
          <li>Estructura <b>Ángulo 1¼"</b></li>
          <li>Repisas <b>Pino 2.5 cm</b></li>
          <li>Carga <b>60 kg por nivel</b></li>
        </ul>
        <div class="precio"><span class="q">Q 3,150</span><small>IVA incluido</small></div>
        <a class="btn" href="#contacto">Cotizar esta estantería</a>
      </article>

      <article class="pieza">
        <figure>
          <svg viewBox="0 0 220 150" role="img" aria-label="Banco alto tipo taburete">
            <rect class="wood" x="70" y="40" width="80" height="10" rx="2"/><rect class="stroke" x="70" y="40" width="80" height="10"/>
            <path class="stroke" d="M80 50 L70 130 M140 50 L150 130 M76 95 L144 95 M62 130 L88 130 M132 130 L158 130"/>
          </svg>
        </figure>
        <h3>Banco Cuadrilla</h3>
        <p class="desc">Altura de barra, apilable de a tres. Se vende por unidad o por juego.</p>
        <ul class="specs">
          <li>Medidas <b>38 × 32 × 75 cm</b></li>
          <li>Estructura <b>Solera ¼"</b></li>
          <li>Asiento <b>Cedro 3 cm</b></li>
          <li>Carga <b>140 kg</b></li>
        </ul>
        <div class="precio"><span class="q">Q 690</span><small>por unidad</small></div>
        <a class="btn" href="#contacto">Cotizar bancos</a>
      </article>

      <article class="pieza">
        <figure>
          <svg viewBox="0 0 220 150" role="img" aria-label="Mesa de centro baja con repisa inferior">
            <rect class="wood" x="30" y="50" width="160" height="10"/><rect class="stroke" x="30" y="50" width="160" height="10"/>
            <rect class="wood" x="55" y="95" width="110" height="7"/><rect class="stroke" x="55" y="95" width="110" height="7"/>
            <path class="stroke" d="M50 60 L50 120 M170 60 L170 120 M50 120 L170 120"/>
          </svg>
        </figure>
        <h3>Mesa de centro Placa</h3>
        <p class="desc">Base soldada en U con repisa inferior para revistas o canastos.</p>
        <ul class="specs">
          <li>Medidas <b>110 × 55 × 42 cm</b></li>
          <li>Estructura <b>Platina 3 mm</b></li>
          <li>Tapa <b>Conacaste 4 cm</b></li>
          <li>Extras <b>Repisa inferior</b></li>
        </ul>
        <div class="precio"><span class="q">Q 2,480</span><small>IVA incluido</small></div>
        <a class="btn" href="#contacto">Cotizar esta mesa</a>
      </article>

      <article class="pieza">
        <figure>
          <svg viewBox="0 0 220 150" role="img" aria-label="Perchero industrial con barra y repisa">
            <path class="stroke" d="M50 20 L50 130 M170 20 L170 130 M50 20 L170 20 M40 130 L70 130 M150 130 L180 130"/>
            <rect class="wood" x="50" y="45" width="120" height="8"/><rect class="stroke" x="50" y="45" width="120" height="8"/>
            <path class="thin" d="M75 20 L75 32 M110 20 L110 32 M145 20 L145 32"/>
          </svg>
        </figure>
        <h3>Perchero Bodega</h3>
        <p class="desc">Barra para colgar con repisa superior. Pensado para tiendas y entradas.</p>
        <ul class="specs">
          <li>Medidas <b>120 × 45 × 170 cm</b></li>
          <li>Estructura <b>Tubo 1½"</b></li>
          <li>Repisa <b>Pino 2.5 cm</b></li>
          <li>Carga <b>45 kg en barra</b></li>
        </ul>
        <div class="precio"><span class="q">Q 2,190</span><small>IVA incluido</small></div>
        <a class="btn" href="#contacto">Cotizar este perchero</a>
      </article>

    </div>
  </div>
</section>

<section id="medida">
  <div class="wrap">
    <div class="enc">
      <div>
        <h2>Calcula tu pieza a medida</h2>
        <p>Mové las medidas y elegí materiales para tener un estimado antes de escribirnos. El precio final se confirma con el plano.</p>
      </div>
    </div>

    <div class="cotiza">
      <div>
        <div class="campo">
          <label for="tipo">Qué querés fabricar</label>
          <select id="tipo">
            <option value="mesa">Mesa de comedor</option>
            <option value="escritorio">Escritorio</option>
            <option value="estante">Estantería</option>
            <option value="barra">Barra o isla de cocina</option>
          </select>
        </div>

        <div class="campo">
          <label for="largo">Largo <span class="val"><span id="largoVal">180</span> cm</span></label>
          <input type="range" id="largo" min="60" max="320" step="5" value="180">
        </div>

        <div class="campo">
          <label for="ancho">Ancho <span class="val"><span id="anchoVal">80</span> cm</span></label>
          <input type="range" id="ancho" min="30" max="140" step="5" value="80">
        </div>

        <div class="campo">
          <label>Madera de la tapa</label>
          <div class="opciones" id="madera">
            <button type="button" data-v="pino" data-f="1" aria-pressed="true">Pino</button>
            <button type="button" data-v="conacaste" data-f="1.45" aria-pressed="false">Conacaste</button>
            <button type="button" data-v="cedro" data-f="1.75" aria-pressed="false">Cedro</button>
          </div>
        </div>

        <div class="campo" style="margin-bottom:0">
          <label>Acabado del acero</label>
          <div class="opciones" id="acabado">
            <button type="button" data-v="negro mate" data-f="1" aria-pressed="true">Negro mate</button>
            <button type="button" data-v="crudo encerado" data-f="1.08" aria-pressed="false">Crudo encerado</button>
            <button type="button" data-v="galvanizado" data-f="1.2" aria-pressed="false">Galvanizado</button>
          </div>
        </div>
      </div>

      <div class="resumen">
        <dl>
          <div><dt>Pieza</dt><dd id="rTipo">Mesa de comedor</dd></div>
          <div><dt>Medidas</dt><dd id="rMed">180 × 80 cm</dd></div>
          <div><dt>Madera</dt><dd id="rMad">Pino</dd></div>
          <div><dt>Acabado</dt><dd id="rAca">Negro mate</dd></div>
        </dl>
        <div>
          <div class="nota">Estimado, IVA incluido</div>
          <div class="total" id="total">Q 5,200</div>
          <p class="nota">Incluye estructura, tapa, acabado y armado en el taller. El flete se cotiza aparte según el municipio.</p>
        </div>
        <a class="btn" id="enviarCotiza" href="#contacto">Enviar este estimado por WhatsApp</a>
      </div>
    </div>
  </div>
</section>

<section id="proceso">
  <div class="wrap">
    <h2>Cómo trabajamos</h2>
    <div class="cota" aria-hidden="true"><i></i><span></span><i></i></div>
    <div class="pasos">
      <div class="paso"><b>1</b><h3>Medidas</h3><p>Nos mandás el espacio y el uso. Si estás en la capital, vamos a medir sin costo.</p></div>
      <div class="paso"><b>2</b><h3>Plano y anticipo</h3><p>Te enviamos el dibujo con medidas y precio cerrado. Se arranca con 50%.</p></div>
      <div class="paso"><b>3</b><h3>Fabricación</h3><p>Corte, soldadura, pintura y montaje de la madera. De 3 a 4 semanas.</p></div>
      <div class="paso"><b>4</b><h3>Entrega</h3><p>Llevamos y nivelamos la pieza en tu espacio. Saldo contra entrega.</p></div>
    </div>
  </div>
</section>

<section id="materiales">
  <div class="wrap">
    <div class="enc">
      <div>
        <h2>Materiales y acabados</h2>
        <p>Trabajamos con acero nacional y madera seca de proveedores locales. Podés pedir muestras físicas antes de decidir.</p>
      </div>
    </div>
    <div class="mats">
      <div class="mat"><div class="muestra m-negro"></div><div><h3>Negro mate</h3><p>Pintura electrostática horneada. El acabado más pedido, no marca huellas.</p></div></div>
      <div class="mat"><div class="muestra m-crudo"></div><div><h3>Acero crudo encerado</h3><p>Se ve la soldadura y la textura del metal, sellado con cera para evitar óxido.</p></div></div>
      <div class="mat"><div class="muestra m-galv"></div><div><h3>Galvanizado</h3><p>Para piezas de patio o cocina comercial, resiste humedad y limpieza fuerte.</p></div></div>
      <div class="mat"><div class="muestra m-conacaste"></div><div><h3>Conacaste</h3><p>Veta ancha y tono oscuro. Es la madera más estable para tablones grandes.</p></div></div>
      <div class="mat"><div class="muestra m-pino"></div><div><h3>Pino</h3><p>Claro y liviano, la opción más económica. Buena para repisas y escritorios.</p></div></div>
      <div class="mat"><div class="muestra m-cedro"></div><div><h3>Cedro</h3><p>Tono rojizo, aroma y peso medio. Se usa en asientos y piezas pequeñas.</p></div></div>
    </div>
  </div>
</section>

<section id="contacto">
  <div class="wrap">
    <div class="contacto">
      <div>
        <h2>Contanos qué necesitás</h2>
        <p>Respondemos el mismo día hábil. Si ya tenés medidas o una foto de referencia, mandalas por WhatsApp y te cotizamos más rápido.</p>
        <ul class="lista">
          <li><span>WhatsApp</span> <a href="https://wa.me/50200000000">+502 0000 0000</a></li>
          <li><span>Correo</span> <a href="mailto:taller@hierrocrudo.gt">taller@hierrocrudo.gt</a></li>
          <li><span>Taller</span> 4a calle 12-30, zona 12, Ciudad de Guatemala</li>
          <li><span>Horario</span> Lunes a viernes 8:00–17:00 · Sábado 8:00–12:00</li>
          <li><span>Pagos</span> Transferencia, tarjeta y cuotas sin intereses</li>
        </ul>
      </div>
      <div>
        <div class="campo"><label for="nom">Tu nombre</label><input type="text" id="nom" placeholder="Nombre y apellido"></div>
        <div class="campo"><label for="tel">Teléfono o correo</label><input type="text" id="tel" placeholder="Para responderte"></div>
        <div class="campo"><label for="msj">Qué pieza querés</label><textarea id="msj" placeholder="Ej. una mesa de 220 × 90 para 10 personas, entrega en Antigua"></textarea></div>
        <button class="btn" id="enviarForm" type="button">Enviar por WhatsApp</button>
        <p class="nota" id="avisoForm" style="margin-top:12px"></p>
      </div>
    </div>
  </div>
</section>

</main>

<footer>
  <div class="wrap">
    <span>Hierro Crudo · Taller de muebles industriales · Ciudad de Guatemala</span>
    <span>Fabricación propia desde 2016</span>
  </div>
</footer>

<script>
(function(){
  // tema
  var btn = document.getElementById('tema');
  var oscuro = window.matchMedia('(prefers-color-scheme: dark)').matches;
  try{ var g = localStorage.getItem('hc-tema'); if(g){ oscuro = g === 'dark'; } }catch(e){}
  function aplicar(){
    document.documentElement.setAttribute('data-theme', oscuro ? 'dark' : 'light');
    btn.textContent = oscuro ? 'Modo claro' : 'Modo oscuro';
  }
  aplicar();
  btn.addEventListener('click', function(){
    oscuro = !oscuro; aplicar();
    try{ localStorage.setItem('hc-tema', oscuro ? 'dark' : 'light'); }catch(e){}
  });

  // cotizador
  var base = {
    mesa:      {n:'Mesa de comedor', fijo:1900, m2:2100},
    escritorio:{n:'Escritorio',      fijo:1500, m2:1850},
    estante:   {n:'Estantería',      fijo:1400, m2:1600},
    barra:     {n:'Barra o isla de cocina', fijo:2600, m2:2400}
  };
  var tipo = document.getElementById('tipo');
  var largo = document.getElementById('largo'), ancho = document.getElementById('ancho');
  var fMad = 1, nMad = 'Pino', fAca = 1, nAca = 'Negro mate';

  function grupo(id, cb){
    var c = document.getElementById(id);
    c.addEventListener('click', function(e){
      var b = e.target.closest('button'); if(!b) return;
      c.querySelectorAll('button').forEach(function(x){ x.setAttribute('aria-pressed','false'); });
      b.setAttribute('aria-pressed','true');
      cb(parseFloat(b.dataset.f), b.textContent.trim());
      calcular();
    });
  }
  grupo('madera', function(f,n){ fMad=f; nMad=n; });
  grupo('acabado', function(f,n){ fAca=f; nAca=n; });

  function calcular(){
    var b = base[tipo.value];
    var area = (largo.value/100) * (ancho.value/100);
    var p = (b.fijo + area * b.m2 * fMad) * fAca;
    document.getElementById('largoVal').textContent = largo.value;
    document.getElementById('anchoVal').textContent = ancho.value;
    document.getElementById('rTipo').textContent = b.n;
    document.getElementById('rMed').textContent = largo.value + ' × ' + ancho.value + ' cm';
    document.getElementById('rMad').textContent = nMad;
    document.getElementById('rAca').textContent = nAca;
    document.getElementById('total').textContent = 'Q ' + (Math.round(p/10)*10).toLocaleString('es-GT');
  }
  [tipo, largo, ancho].forEach(function(el){ el.addEventListener('input', calcular); });
  calcular();

  var TEL = '50200000000';
  document.getElementById('enviarCotiza').addEventListener('click', function(e){
    e.preventDefault();
    var t = 'Hola, quiero cotizar ' + document.getElementById('rTipo').textContent.toLowerCase() +
            ' de ' + document.getElementById('rMed').textContent +
            ', madera ' + document.getElementById('rMad').textContent.toLowerCase() +
            ', acabado ' + document.getElementById('rAca').textContent.toLowerCase() +
            '. La página me dio un estimado de ' + document.getElementById('total').textContent + '.';
    window.open('https://wa.me/' + TEL + '?text=' + encodeURIComponent(t), '_blank');
  });

  document.getElementById('enviarForm').addEventListener('click', function(){
    var n = document.getElementById('nom').value.trim();
    var c = document.getElementById('tel').value.trim();
    var m = document.getElementById('msj').value.trim();
    var aviso = document.getElementById('avisoForm');
    if(!n || !m){ aviso.textContent = 'Escribí tu nombre y qué pieza querés para poder cotizarte.'; return; }
    aviso.textContent = '';
    var t = 'Hola, soy ' + n + (c ? ' (' + c + ')' : '') + '. ' + m;
    window.open('https://wa.me/' + TEL + '?text=' + encodeURIComponent(t), '_blank');
  });
})();
</script>
</body>
</html>

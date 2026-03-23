<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Révision DCG UE5 – Économie Contemporaine</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&display=swap');
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: 'Segoe UI', Arial, sans-serif; background: #f4f6f9; color: #222; line-height: 1.7; font-size: 15px; }
@keyframes fadeIn { from { opacity:0; transform:translateY(6px); } to { opacity:1; transform:none; } }

/* ── NAVIGATION BAR ── */
.navbar {
  display: none;
  position: sticky;
  top: 0;
  z-index: 100;
  background: #1e3a5f;
  color: white;
  padding: 0 20px;
  align-items: center;
  gap: 12px;
  height: 54px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.25);
}
.navbar.visible { display: flex; }
.navbar-back {
  background: rgba(255,255,255,0.15);
  border: none;
  color: white;
  padding: 7px 16px;
  border-radius: 6px;
  cursor: pointer;
  font-size: 0.92em;
  font-weight: 600;
  white-space: nowrap;
  transition: background 0.2s;
}
.navbar-back:hover { background: rgba(255,255,255,0.28); }
.navbar-title { font-weight: 700; font-size: 1em; opacity: 0.95; }
.navbar-toc {
  margin-left: auto;
  display: flex;
  gap: 8px;
  flex-wrap: wrap;
}
.navbar-toc a {
  color: rgba(255,255,255,0.8);
  text-decoration: none;
  font-size: 0.8em;
  padding: 3px 9px;
  border-radius: 4px;
  background: rgba(255,255,255,0.1);
  white-space: nowrap;
}
.navbar-toc a:hover { background: rgba(255,255,255,0.25); color: white; }

/* ── PAGES ── */
.page { display: none; }
.page.active { display: block; }

/* ── HOME COVER ── */
.home-cover {
  background: linear-gradient(135deg, #1e3a5f 0%, #2d6a9f 100%);
  color: white;
  text-align: center;
  padding: 60px 30px 50px;
}
.home-cover h1 { font-size: 2.4em; margin-bottom: 8px; }
.home-cover p { font-size: 1.05em; opacity: 0.9; margin-top: 6px; }
.home-cover .badge {
  display: inline-block;
  background: rgba(255,255,255,0.2);
  border-radius: 20px;
  padding: 4px 18px;
  margin-top: 14px;
  font-size: 0.88em;
  font-weight: 600;
}

/* ── BASES SECTION ON HOME ── */
.bases-section {
  max-width: 920px;
  margin: 36px auto 10px;
  padding: 0 20px;
}
.bases-section h2 {
  font-size: 1.15em;
  color: #1e3a5f;
  margin-bottom: 16px;
  padding-bottom: 6px;
  border-bottom: 2px solid #d0e4f5;
}
.bases-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(270px, 1fr));
  gap: 14px;
}
.base-card {
  background: white;
  border-radius: 8px;
  padding: 16px 18px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.07);
  border-left: 4px solid #2d6a9f;
}
.base-card h4 { font-size: 0.92em; color: #1e3a5f; margin-bottom: 6px; font-weight: 700; }
.base-card p { font-size: 0.86em; color: #444; margin: 0; line-height: 1.55; }
.base-card .formula {
  background: #1e3a5f;
  color: white;
  font-family: monospace;
  font-size: 0.82em;
  padding: 5px 10px;
  border-radius: 4px;
  margin-top: 7px;
  display: block;
  text-align: center;
}

/* ── THEME CARDS GRID ── */
.cards-section {
  max-width: 920px;
  margin: 30px auto 50px;
  padding: 0 20px;
}
.cards-section h2 {
  font-size: 1.15em;
  color: #1e3a5f;
  margin-bottom: 16px;
  padding-bottom: 6px;
  border-bottom: 2px solid #d0e4f5;
}
.cards-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 18px;
}
.theme-card {
  border-radius: 12px;
  padding: 26px 22px;
  cursor: pointer;
  color: white;
  transition: transform 0.18s, box-shadow 0.18s;
  box-shadow: 0 4px 16px rgba(0,0,0,0.12);
  user-select: none;
  position: relative;
  overflow: hidden;
}
.theme-card::after {
  content: '→';
  position: absolute;
  right: 18px;
  bottom: 18px;
  font-size: 1.5em;
  opacity: 0.5;
}
.theme-card:hover { transform: translateY(-4px); box-shadow: 0 8px 28px rgba(0,0,0,0.18); }
.theme-card:active { transform: translateY(-1px); }
.theme-card .card-num { font-size: 0.76em; font-weight: 700; letter-spacing: 2px; text-transform: uppercase; opacity: 0.8; margin-bottom: 6px; }
.theme-card h3 { font-size: 1.05em; font-weight: 700; margin-bottom: 10px; line-height: 1.35; }
.theme-card .card-dossiers { font-size: 0.8em; opacity: 0.85; line-height: 1.5; }

.card-t1 { background: linear-gradient(135deg, #1e3a5f, #2d6a9f); }
.card-t2 { background: linear-gradient(135deg, #0e6655, #16a085); }
.card-t3 { background: linear-gradient(135deg, #7d5a0a, #c07d0a); }
.card-t4 { background: linear-gradient(135deg, #4a1a6e, #8e44ad); }
.card-t5 { background: linear-gradient(135deg, #1e4a12, #3a7d2c); }
.card-tm { background: linear-gradient(135deg, #922b21, #c0392b); }

/* ── THEME PAGE COVER ── */
.theme-cover {
  color: white;
  padding: 40px 30px 30px;
  text-align: center;
}
.theme-cover .tc-num { font-size: 0.82em; font-weight: 700; letter-spacing: 2px; text-transform: uppercase; opacity: 0.8; margin-bottom: 6px; }
.theme-cover h2 { font-size: 1.8em; margin-bottom: 10px; }
.theme-cover p { font-size: 0.95em; opacity: 0.88; }

.tc-t1 { background: linear-gradient(135deg, #1e3a5f, #2d6a9f); }
.tc-t2 { background: linear-gradient(135deg, #0e6655, #16a085); }
.tc-t3 { background: linear-gradient(135deg, #7d5a0a, #c07d0a); }
.tc-t4 { background: linear-gradient(135deg, #4a1a6e, #8e44ad); }
.tc-t5 { background: linear-gradient(135deg, #1e4a12, #3a7d2c); }
.tc-tm { background: linear-gradient(135deg, #922b21, #c0392b); }

/* ── FICHES ── */
.fiche {
  background: white;
  max-width: 900px;
  margin: 30px auto;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.09);
  overflow: hidden;
}
.fiche-header { padding: 22px 30px 16px; border-bottom: 3px solid; }
.fiche-header .num { font-size: 0.85em; font-weight: 600; letter-spacing: 1px; text-transform: uppercase; opacity: 0.8; }
.fiche-header h2 { font-size: 1.4em; margin-top: 4px; }
.fiche-body { padding: 24px 30px 30px; }

.d1 .fiche-header { background: #e8f4fd; border-color: #2d6a9f; color: #1e3a5f; }
.d2 .fiche-header { background: #eaf7f0; border-color: #27ae60; color: #1a5e38; }
.d3 .fiche-header { background: #fdf3e8; border-color: #e67e22; color: #7f4800; }
.d4 .fiche-header { background: #f3e8fd; border-color: #8e44ad; color: #4a1a6e; }
.d5 .fiche-header { background: #e8f8f5; border-color: #16a085; color: #0e6655; }
.d6 .fiche-header { background: #fdecea; border-color: #c0392b; color: #6e1a1a; }
.d7 .fiche-header { background: #eaf2fb; border-color: #1a5276; color: #1a3a5c; }
.d8 .fiche-header { background: #fef9e7; border-color: #b7770d; color: #7d5a0a; }
.d9 .fiche-header { background: #eafaf1; border-color: #1e8449; color: #145a32; }
.d10 .fiche-header { background: #fdf2e9; border-color: #ca6f1e; color: #784212; }
.d11 .fiche-header { background: #eae8fd; border-color: #5b4fcf; color: #2d1b8e; }
.d12 .fiche-header { background: #edf7e8; border-color: #3a7d2c; color: #1e4a12; }
.d13 .fiche-header { background: #e8f5fd; border-color: #0b7aaa; color: #054a6e; }
.dm .fiche-header { background: #fdeaea; border-color: #c0392b; color: #6e1a1a; }

.section-title { font-size: 1.05em; font-weight: 700; color: #1e3a5f; margin: 22px 0 10px; padding-bottom: 4px; border-bottom: 2px solid #e0e8f0; }
.section-title.green { color: #1a5e38; border-color: #c8f0da; }
.section-title.orange { color: #7f4800; border-color: #f5dbb8; }
.section-title.purple { color: #4a1a6e; border-color: #e8d5f7; }
.section-title.red { color: #6e1a1a; border-color: #f7d5d5; }
.section-title.teal { color: #0e6655; border-color: #a2d9ce; }
.section-title.darkred { color: #6e1a1a; border-color: #f5b7b1; }
.section-title.navy { color: #1a3a5c; border-color: #aed6f1; }
.section-title.gold { color: #7d5a0a; border-color: #f9e79f; }
.section-title.forest { color: #145a32; border-color: #a9dfbf; }
.section-title.brown { color: #784212; border-color: #f5cba7; }
.section-title.indigo { color: #2d1b8e; border-color: #c5bef5; }
.section-title.olive { color: #1e4a12; border-color: #b8e0a8; }
.section-title.cerulean { color: #054a6e; border-color: #a0d6f0; }

p { margin-bottom: 10px; }

.def-box { background: #eef5fb; border-left: 4px solid #2d6a9f; padding: 12px 16px; border-radius: 0 6px 6px 0; margin: 12px 0; font-size: 0.97em; }
.def-box.green { background: #eafaf1; border-color: #27ae60; }
.def-box.orange { background: #fef9ef; border-color: #e67e22; }
.def-box.purple { background: #f5effe; border-color: #8e44ad; }
.def-box.red { background: #fef0ef; border-color: #c0392b; }
.def-box.teal { background: #e8f8f5; border-color: #16a085; }
.def-box.darkred { background: #fdedec; border-color: #c0392b; }
.def-box.navy { background: #eaf2fb; border-color: #1a5276; }
.def-box.gold { background: #fef9e7; border-color: #b7770d; }
.def-box.forest { background: #eafaf1; border-color: #1e8449; }
.def-box.brown { background: #fdf2e9; border-color: #ca6f1e; }
.def-box.indigo { background: #eae8fd; border-color: #5b4fcf; }
.def-box.olive { background: #edf7e8; border-color: #3a7d2c; }
.def-box.cerulean { background: #e8f5fd; border-color: #0b7aaa; }

.formule { background: #1e3a5f; color: white; padding: 12px 20px; border-radius: 6px; font-family: monospace; font-size: 1.02em; text-align: center; margin: 14px 0; }
.formule.green { background: #1a5e38; }
.formule.orange { background: #7f4800; }
.formule.purple { background: #4a1a6e; }
.formule.teal { background: #0e6655; }
.formule.darkred { background: #922b21; }
.formule.navy { background: #1a5276; }
.formule.gold { background: #7d5a0a; }
.formule.forest { background: #145a32; }
.formule.brown { background: #784212; }
.formule.indigo { background: #2d1b8e; }
.formule.olive { background: #1e4a12; }
.formule.cerulean { background: #054a6e; }

.highlight { background: #fff8e1; border: 1px solid #f9c740; border-radius: 5px; padding: 10px 14px; margin: 12px 0; }
.highlight strong { color: #7a5800; }

.mini-table { width: 100%; border-collapse: collapse; margin: 14px 0; font-size: 0.93em; }
.mini-table th { background: #1e3a5f; color: white; padding: 9px 12px; text-align: left; }
.mini-table td { padding: 8px 12px; border-bottom: 1px solid #e5e5e5; }
.mini-table tr:nth-child(even) td { background: #f7fafd; }

.mini-table.green th { background: #1a5e38; }
.mini-table.orange th { background: #7f4800; }
.mini-table.purple th { background: #4a1a6e; }
.mini-table.red th { background: #6e1a1a; }
.mini-table.teal th { background: #0e6655; }
.mini-table.darkred th { background: #922b21; }
.mini-table.navy th { background: #1a5276; }
.mini-table.gold th { background: #7d5a0a; }
.mini-table.forest th { background: #145a32; }
.mini-table.brown th { background: #784212; }
.mini-table.indigo th { background: #2d1b8e; }
.mini-table.olive th { background: #1e4a12; }
.mini-table.cerulean th { background: #054a6e; }

.actu { background: #fff3cd; border: 1px solid #ffc107; border-radius: 6px; padding: 10px 14px; margin: 12px 0; font-size: 0.93em; }
.actu::before { content: "📊 Chiffre clé — "; font-weight: bold; }
.exemple { background: #f0f0f0; border-radius: 6px; padding: 10px 14px; margin: 10px 0; font-size: 0.93em; }
.exemple::before { content: "Exemple : "; font-weight: bold; color: #555; }
.piege { background: #fdecea; border-left: 4px solid #e74c3c; padding: 10px 14px; border-radius: 0 6px 6px 0; margin: 12px 0; font-size: 0.93em; }
.piege::before { content: "⚠️ À retenir — "; font-weight: bold; color: #c0392b; }
.auteur { display: inline-block; background: #d5e8f5; color: #1e3a5f; border-radius: 4px; padding: 1px 8px; font-size: 0.88em; font-weight: 600; margin: 0 2px; }

.page-footer { text-align: center; padding: 30px; color: #888; font-size: 0.88em; }

/* ── FICHE HEADER clickable hint ── */
.fiche-header {
  cursor: pointer;
  transition: filter 0.15s;
  position: relative;
}
.fiche-header:hover { filter: brightness(0.94); }
.fiche-header::after {
  content: "👁 Résumé rapide";
  position: absolute;
  right: 16px; top: 50%; transform: translateY(-50%);
  font-size: 0.75em; font-weight: 600; opacity: 0.55;
  background: rgba(0,0,0,0.12);
  padding: 3px 10px; border-radius: 12px;
  pointer-events: none;
}

/* ── MODAL ── */
.modal-overlay {
  display: none;
  position: fixed; inset: 0;
  background: rgba(0,0,0,0.52);
  z-index: 999;
  align-items: center;
  justify-content: center;
  padding: 20px;
  animation: fadeIn 0.18s ease;
}
.modal-overlay.open { display: flex; }
@keyframes fadeIn { from { opacity:0 } to { opacity:1 } }

.modal-box {
  background: white;
  border-radius: 14px;
  max-width: 700px;
  width: 100%;
  max-height: 88vh;
  overflow-y: auto;
  box-shadow: 0 20px 60px rgba(0,0,0,0.35);
  animation: slideUp 0.2s ease;
}
@keyframes slideUp { from { transform: translateY(24px); opacity:0 } to { transform: translateY(0); opacity:1 } }

.modal-header {
  padding: 20px 24px 16px;
  border-bottom: 3px solid;
  display: flex;
  align-items: flex-start;
  gap: 12px;
}
.modal-header-text { flex: 1; }
.modal-header .dnum { font-size: 0.78em; font-weight: 700; text-transform: uppercase; letter-spacing: 1px; opacity: 0.7; }
.modal-header h3 { font-size: 1.2em; margin-top: 3px; }
.modal-close {
  background: rgba(0,0,0,0.1); border: none; border-radius: 50%;
  width: 32px; height: 32px; cursor: pointer; font-size: 1.1em;
  display: flex; align-items: center; justify-content: center;
  flex-shrink: 0; transition: background 0.15s;
}
.modal-close:hover { background: rgba(0,0,0,0.22); }

.modal-body { padding: 20px 24px 24px; }

.modal-section { margin-bottom: 18px; }
.modal-section-title {
  font-size: 0.78em; font-weight: 700; text-transform: uppercase; letter-spacing: 1px;
  color: #888; margin-bottom: 8px; display: flex; align-items: center; gap: 6px;
}
.modal-section-title::after { content: ''; flex: 1; height: 1px; background: #e5e5e5; }

.modal-summary {
  background: #f7fafd;
  border-left: 4px solid #2d6a9f;
  padding: 12px 16px;
  border-radius: 0 8px 8px 0;
  font-size: 0.96em;
  line-height: 1.65;
  color: #333;
}

.modal-theories { display: flex; flex-direction: column; gap: 8px; }
.theory-item {
  display: flex; gap: 10px; align-items: flex-start;
  background: #fafafa; border: 1px solid #eee;
  border-radius: 8px; padding: 10px 14px;
}
.theory-name {
  font-weight: 700; font-size: 0.85em;
  background: #1e3a5f; color: white;
  border-radius: 5px; padding: 2px 9px;
  white-space: nowrap; flex-shrink: 0;
  align-self: flex-start; margin-top: 2px;
}
.theory-desc { font-size: 0.9em; color: #444; line-height: 1.5; }

.modal-keywords { display: flex; flex-wrap: wrap; gap: 7px; }
.keyword {
  background: #e8f4fd; color: #1e3a5f;
  border: 1px solid #b8d8f5; border-radius: 20px;
  padding: 4px 13px; font-size: 0.84em; font-weight: 600;
}

.modal-btn-fiche {
  display: block; width: 100%;
  margin-top: 18px; padding: 11px;
  background: #1e3a5f; color: white;
  border: none; border-radius: 8px;
  font-size: 0.95em; font-weight: 700;
  cursor: pointer; transition: background 0.15s;
  text-align: center;
}
.modal-btn-fiche:hover { background: #2d6a9f; }
</style>
</head>
<body>

<!-- ══════════════════════════════════════════ -->
<!-- MODAL RÉSUMÉ DOSSIER -->
<!-- ══════════════════════════════════════════ -->
<div class="modal-overlay" id="modalOverlay" onclick="closeModal(event)">
  <div class="modal-box" id="modalBox">
    <div class="modal-header" id="modalHeader">
      <div class="modal-header-text">
        <div class="dnum" id="modalDnum"></div>
        <h3 id="modalTitle"></h3>
      </div>
      <button class="modal-close" onclick="closeModal()">✕</button>
    </div>
    <div class="modal-body">
      <div class="modal-section">
        <div class="modal-section-title">📝 Résumé</div>
        <div class="modal-summary" id="modalSummary"></div>
      </div>
      <div class="modal-section">
        <div class="modal-section-title">📚 Théories & Auteurs clés</div>
        <div class="modal-theories" id="modalTheories"></div>
      </div>
      <div class="modal-section">
        <div class="modal-section-title">🔑 Mots-clés fondamentaux</div>
        <div class="modal-keywords" id="modalKeywords"></div>
      </div>
      <button class="modal-btn-fiche" id="modalBtnFiche">📖 Voir la fiche complète ↓</button>
    </div>
  </div>
</div>

<!-- ══════════════════════════════════════════ -->
<!-- NAVBAR (sticky, shown on theme pages) -->
<!-- ══════════════════════════════════════════ -->
<nav class="navbar" id="mainNav">
  <button class="navbar-back" onclick="goHome()">← Accueil</button>
  <span class="navbar-title" id="navTitle"></span>
  <div class="navbar-toc" id="navToc"></div>
</nav>

<!-- ══════════════════════════════════════════ -->
<!-- PAGE : ACCUEIL -->
<!-- ══════════════════════════════════════════ -->
<div class="page active" id="page-home">

  <div class="home-cover">
    <h1>📚 Révision DCG UE5</h1>
    <p>Économie Contemporaine</p>
    <p>13 dossiers · 5 thèmes · Fiches claires et complètes</p>
    <div class="badge">Clique sur un thème pour commencer 👇</div>
  </div>

  <!-- BASES DE L'ÉCONOMIE -->
  <div class="bases-section">
    <h2>📌 Les bases à connaître absolument</h2>
    <div class="bases-grid">

      <div class="base-card">
        <h4>L'économie en une phrase</h4>
        <p>C'est la science qui étudie comment des <strong>ressources rares</strong> sont utilisées pour satisfaire des <strong>besoins illimités</strong>. Tout arbitrage a un coût d'opportunité.</p>
      </div>

      <div class="base-card">
        <h4>Les 6 agents économiques</h4>
        <p>Ménages · Sociétés non financières · Sociétés financières · État (APU) · ISBLSM · Reste du monde. Chacun a un rôle précis dans le circuit économique.</p>
      </div>

      <div class="base-card">
        <h4>La Valeur Ajoutée (VA)</h4>
        <p>Richesse nouvelle créée par une entreprise.</p>
        <span class="formula">VA = CA – Consommations Intermédiaires</span>
      </div>

      <div class="base-card">
        <h4>Le PIB</h4>
        <p>Somme des VA produites sur un territoire en un an. Mesure la richesse créée et la croissance économique.</p>
        <span class="formula">PIB = C + I + ΔS + (X – M)</span>
      </div>

      <div class="base-card">
        <h4>Taux de croissance</h4>
        <p>Variation du PIB réel (en volume, hors inflation) d'une année à l'autre.</p>
        <span class="formula">(Valeur arrivée – Valeur départ) / Valeur départ × 100</span>
      </div>

      <div class="base-card">
        <h4>Déficit ≠ Dette</h4>
        <p><strong>Déficit</strong> = flux annuel (dépenses &gt; recettes sur 1 an). <strong>Dette</strong> = stock = accumulation de tous les déficits passés. France 2024 : -5,8% / 113% du PIB.</p>
      </div>

      <div class="base-card">
        <h4>Marché : offre & demande</h4>
        <p>Le marché est le lieu où offre et demande se rencontrent pour former un <strong>prix d'équilibre</strong>. La CPP (5 conditions) est le modèle idéal, rarement atteint en pratique.</p>
      </div>

      <div class="base-card">
        <h4>IDH</h4>
        <p>Indice composite qui mesure le développement humain sur 3 dimensions : santé (espérance de vie), éducation, niveau de vie (RNB/hab en PPA). Créé par Amartya Sen / PNUD 1990.</p>
      </div>

      <div class="base-card">
        <h4>Les 3D de Bourguignon</h4>
        <p>Depuis les années 1980 : <strong>D</strong>ésintermédiation + <strong>D</strong>écloisonnement + <strong>D</strong>éréglementation → montée des marchés financiers et fragilisation du système.</p>
      </div>

    </div>
  </div>

  <!-- THEME CARDS -->
  <div class="cards-section">
    <h2>📂 Choisir un thème</h2>
    <div class="cards-grid">

      <div class="theme-card card-t1" onclick="showPage('page-t1', 'Thème 1', 'T1')">
        <div class="card-num">Thème 1</div>
        <h3>Les fondements de l'activité économique</h3>
        <div class="card-dossiers">
          D1 · Rareté & besoins<br>
          D2 · Agents, conso, épargne, investissement<br>
          D3 · Création de richesse (VA)<br>
          D4 · PIB & indicateurs alternatifs
        </div>
      </div>

      <div class="theme-card card-t2" onclick="showPage('page-t2', 'Thème 2', 'T2')">
        <div class="card-num">Thème 2</div>
        <h3>L'économie de marché</h3>
        <div class="card-dossiers">
          D5 · Marché, CPP, concurrence<br>
          D6 · Encadrement du marché, biens publics, externalités
        </div>
      </div>

      <div class="theme-card card-t3" onclick="showPage('page-t3', 'Thème 3', 'T3')">
        <div class="card-num">Thème 3</div>
        <h3>Le financement de l'économie</h3>
        <div class="card-dossiers">
          D7 · Besoin & capacité de financement<br>
          D8 · Banques, marchés financiers, 3D
        </div>
      </div>

      <div class="theme-card card-t4" onclick="showPage('page-t4', 'Thème 4', 'T4')">
        <div class="card-num">Thème 4</div>
        <h3>La régulation publique</h3>
        <div class="card-dossiers">
          D9 · Place et rôle de l'État<br>
          D10 · Politiques économiques<br>
          D11 · Appartenance à l'UE
        </div>
      </div>

      <div class="theme-card card-t5" onclick="showPage('page-t5', 'Thème 5', 'T5')">
        <div class="card-num">Thème 5</div>
        <h3>La croissance économique</h3>
        <div class="card-dossiers">
          D12 · Croissance, cycles, développement durable<br>
          D13 · Facteurs de production & progrès technique
        </div>
      </div>

      <div class="theme-card card-tm" onclick="showPage('page-tm', 'Méthode', 'TM')">
        <div class="card-num">Méthode</div>
        <h3>Fiches Méthode</h3>
        <div class="card-dossiers">
          Analyser un graphique en 3 étapes<br>
          Verbes directeurs à l'examen<br>
          Repères historiques clés
        </div>
      </div>

    </div>
  </div>

  <!-- SECTION CARTES MENTALES -->
  <div class="cards-section" style="margin-top:0">
    <h2>🧠 Cartes Mentales par Thème</h2>
    <p style="color:#666;font-size:0.9em;margin-bottom:18px;margin-top:-8px">Une vue d'ensemble visuelle de chaque thème pour mieux retenir les liens entre les notions.</p>
    <div class="cards-grid">
      <div class="theme-card" style="background:linear-gradient(135deg,#243b62,#3a7ec4)" onclick="showMM('mm-t1')">
        <div class="card-num">🧠 Carte Mentale</div>
        <h3>Thème 1 · Fondements</h3>
        <div class="card-dossiers">D1 Rareté · D2 Activité éco.<br>D3 Valeur Ajoutée · D4 PIB</div>
      </div>
      <div class="theme-card" style="background:linear-gradient(135deg,#0d5c49,#1abc9c)" onclick="showMM('mm-t2')">
        <div class="card-num">🧠 Carte Mentale</div>
        <h3>Thème 2 · Économie de marché</h3>
        <div class="card-dossiers">D5 Marché & concurrence<br>D6 Encadrement & défaillances</div>
      </div>
      <div class="theme-card" style="background:linear-gradient(135deg,#6b4a08,#d4861a)" onclick="showMM('mm-t3')">
        <div class="card-num">🧠 Carte Mentale</div>
        <h3>Thème 3 · Financement</h3>
        <div class="card-dossiers">D7 Besoin & capacité<br>D8 Banques & marchés financiers</div>
      </div>
      <div class="theme-card" style="background:linear-gradient(135deg,#3d1560,#9b59b6)" onclick="showMM('mm-t4')">
        <div class="card-num">🧠 Carte Mentale</div>
        <h3>Thème 4 · Régulation publique</h3>
        <div class="card-dossiers">D9 Rôle de l'État · D10 Politiques<br>D11 Appartenance à l'UE</div>
      </div>
      <div class="theme-card" style="background:linear-gradient(135deg,#1a400f,#4caf50)" onclick="showMM('mm-t5')">
        <div class="card-num">🧠 Carte Mentale</div>
        <h3>Thème 5 · Croissance</h3>
        <div class="card-dossiers">D12 Croissance & développement<br>D13 Déterminants du potentiel</div>
      </div>
    </div>
  </div>

  <div class="page-footer">DCG UE5 – Économie Contemporaine · Courage pour tes examens 💪</div>
</div>


<!-- ══════════════════════════════════════════ -->
<!-- PAGE : THÈME 1 -->
<!-- ══════════════════════════════════════════ -->
<div class="page" id="page-t1">
  <div class="theme-cover tc-t1">
    <div class="tc-num">Thème 1</div>
    <h2>Les fondements de l'activité économique</h2>
    <p>Dossiers 1 à 4 · Rareté, agents, création de richesse, PIB</p>
  </div>

<div class="fiche d1" id="d1">
  <div class="fiche-header" onclick="openModal('d1')"><div class="num">Dossier 1 – Séquence 1</div><h2>L'économie, science de la rareté</h2></div>
  <div class="fiche-body">
    <div class="section-title">1. Qu'est-ce que la science économique ?</div>
    <div class="def-box">L'économie est la science qui étudie comment des <strong>ressources rares</strong> sont employées pour satisfaire les <strong>besoins illimités</strong> des individus vivant en société. <span class="auteur">Malinvaud, 1986</span></div>
    <p>En clair : on n'a jamais assez d'argent, de temps ou de ressources pour tout faire. L'économie nous aide à comprendre comment les individus, les entreprises et les États font leurs choix face à ces contraintes.</p>
    <div class="piege">L'économie n'est pas seulement une science de l'argent. Elle étudie tous les choix face à la rareté : ton temps est une ressource rare, tes décisions quotidiennes sont des choix économiques.</div>

    <div class="section-title">2. La rareté : le problème central</div>
    <p>La <strong>rareté</strong>, c'est le fait que les ressources disponibles dans la société sont limitées, alors que les besoins sont illimités. On ne peut pas tout produire pour tout le monde.</p>
    <table class="mini-table">
      <tr><th>Type de ressource</th><th>Ce que c'est</th><th>Exemples concrets</th></tr>
      <tr><td>Naturelles renouvelables</td><td>Se reconstituent si on les préserve</td><td>Eau douce, forêts, énergie solaire</td></tr>
      <tr><td>Naturelles non renouvelables</td><td>Stock fini : une fois utilisé, c'est perdu</td><td>Pétrole, charbon, gaz naturel</td></tr>
      <tr><td>Humaines</td><td>Travail, compétences, temps des individus</td><td>Un chirurgien, un développeur, un ouvrier</td></tr>
      <tr><td>Immatérielles</td><td>Savoirs, brevets, données numériques</td><td>Un algorithme de Netflix, un brevet Apple</td></tr>
    </table>
    <div class="exemple">Les puces électroniques (semi-conducteurs) nécessaires pour fabriquer les smartphones, voitures, et consoles de jeux sont très rares. En 2021-2022, leur pénurie mondiale a bloqué des usines entières → c'est la rareté à l'œuvre.</div>

    <div class="section-title">3. Les besoins humains : la pyramide de Maslow</div>
    <p><span class="auteur">Abraham Maslow</span> (1908-1970) était un psychologue américain. Il a montré que les besoins humains sont <strong>hiérarchisés</strong> : on satisfait d'abord les besoins du bas avant de chercher à satisfaire les besoins du haut.</p>
    <table class="mini-table">
      <tr><th>Niveau</th><th>Type de besoin</th><th>Exemples concrets</th></tr>
      <tr><td>1 (base)</td><td>Physiologiques = survie</td><td>Manger, dormir, se chauffer, respirer</td></tr>
      <tr><td>2</td><td>Sécurité = protection</td><td>Un logement stable, un emploi, une assurance</td></tr>
      <tr><td>3</td><td>Appartenance = social</td><td>Avoir des amis, une famille, être accepté</td></tr>
      <tr><td>4</td><td>Estime = reconnaissance</td><td>Être respecté, avoir un statut social, réussir</td></tr>
      <tr><td>5 (sommet)</td><td>Accomplissement de soi</td><td>Créer, apprendre, réaliser ses rêves</td></tr>
    </table>
    <div class="exemple">Pourquoi quelqu'un dans la rue ne pense qu'à manger alors qu'un cadre parisien pense à sa promotion ? Maslow répond : on ne pense aux besoins du niveau 4 que quand les niveaux 1, 2 et 3 sont satisfaits.</div>

    <div class="section-title">4. Biens libres vs biens économiques</div>
    <p>Un <strong>bien libre</strong> est disponible en quantité illimitée, sans coût (l'air que tu respires). Un <strong>bien économique</strong> est rare et a un coût de production.</p>
    <p>Les biens économiques peuvent être <strong>matériels</strong> (un téléphone, une voiture) ou <strong>immatériels</strong> (un abonnement Netflix, une consultation médicale, l'éducation publique). Les services non marchands comme l'école publique ont un coût, mais il est payé par l'impôt, pas directement par toi.</p>
    <div class="piege">Un bien "gratuit" n'est pas forcément un bien libre ! L'école publique est gratuite pour toi mais coûte cher à la société (financée par l'impôt). Seul l'air est vraiment "libre"… pour l'instant.</div>

    <div class="section-title">5. Le coût d'opportunité : le vrai prix de chaque choix</div>
    <div class="def-box">Le <strong>coût d'opportunité</strong> est la valeur de la meilleure alternative à laquelle on renonce quand on fait un choix. Chaque décision a un coût : celui de ce qu'on n'a pas choisi.</div>
    <div class="exemple">Tu hésites entre travailler (gagner 1 200€/mois) et faire le DCG à plein temps. Le coût d'opportunité de tes études = le salaire que tu ne gagnes pas. C'est pourquoi les études sont un investissement : tu sacrifies un revenu maintenant pour en gagner davantage plus tard.</div>
    <div class="exemple">L'État décide de construire un hôpital. Le coût d'opportunité = les écoles ou les routes qu'il aurait pu construire avec cet argent. Les ressources publiques sont rares, il faut choisir.</div>
    <div class="actu"><strong>Le retour de la rareté (Artus & Pastré, 2022) :</strong> après 20 ans d'abondance bon marché (pétrole pas cher, main-d'œuvre asiatique peu coûteuse), la crise Covid-19 + la guerre en Ukraine ont provoqué des tensions sur l'énergie, les semi-conducteurs, le blé et les engrais. La rareté est revenue au cœur des préoccupations économiques mondiales.</div>
  </div>
</div>

<div class="fiche d2" id="d2">
  <div class="fiche-header" onclick="openModal('d2')"><div class="num">Dossier 2 – Séquence 2</div><h2>Qu'est-ce que l'activité économique ?</h2></div>
  <div class="fiche-body">
    <div class="section-title green">1. Les 6 agents économiques</div>
    <p>L'économie repose sur des acteurs bien identifiés qu'on appelle <strong>agents économiques</strong>. Chacun a un rôle précis :</p>
    <table class="mini-table green">
      <tr><th>Agent</th><th>Ce qu'il fait concrètement</th></tr>
      <tr><td><strong>Ménages</strong></td><td>Consomment (achètent des biens et services) et offrent leur travail contre un salaire</td></tr>
      <tr><td><strong>Sociétés non financières (SNF)</strong></td><td>Produisent des biens et services marchands (Renault, LVMH, boulangerie du coin…)</td></tr>
      <tr><td><strong>Sociétés financières (SF)</strong></td><td>BNP Paribas, AXA : collectent l'épargne et financent l'économie</td></tr>
      <tr><td><strong>État / Administrations Publiques (APU)</strong></td><td>Fournissent des services non marchands payés par l'impôt (école, hôpital, police…)</td></tr>
      <tr><td><strong>ISBLSM</strong></td><td>Associations, ONG, syndicats : produisent des services sans but lucratif (Croix-Rouge, WWF…)</td></tr>
      <tr><td><strong>Reste du monde</strong></td><td>Tous les agents étrangers avec qui on échange (Toyota qui vend en France, Airbus qui exporte…)</td></tr>
    </table>

    <div class="section-title green">2. La consommation : deux visions différentes</div>
    <div class="def-box green"><strong>Consommation finale</strong> = ce que tu paies directement (les 7€ chez le médecin). <strong>Consommation effective</strong> = ce que tu consommes réellement, y compris ce que l'État paie pour toi (les 25€ de la consultation dont la Sécu paie 18€). La consommation effective est TOUJOURS supérieure à la finale.</div>
    <div class="exemple">Tu vas chez le médecin. Tu paies 7€ de ta poche = consommation finale. Mais la consultation coûte 25€ en réalité : la Sécurité sociale paie 18€ pour toi. Ta consommation effective est donc de 25€.</div>

    <p>Sur la <strong>théorie de la consommation</strong>, deux économistes s'affrontent :</p>
    <table class="mini-table green">
      <tr><th>Auteur</th><th>Ce qu'il dit</th><th>Conséquence pratique</th></tr>
      <tr><td><span class="auteur">Keynes</span> (1936)</td><td>Tu consommes selon ton revenu du MOMENT. Si tu gagnes plus ce mois-ci, tu consommes plus.</td><td>Une prime aujourd'hui = consommation qui augmente immédiatement</td></tr>
      <tr><td><span class="auteur">Friedman</span> (1957)</td><td>Tu consommes selon ce que tu espères gagner sur TOUTE TA VIE. Une prime exceptionnelle ? Tu l'épargnes plutôt que de la dépenser.</td><td>Une prime exceptionnelle = surtout épargnée, pas dépensée</td></tr>
    </table>
    <div class="piege">À l'examen : si on te demande ce que fait Friedman de différent de Keynes → Friedman regarde le revenu permanent (toute la vie), Keynes regarde le revenu courant (maintenant).</div>

    <p>La <strong>loi d'Engel (1857)</strong> : quand le revenu d'un ménage augmente, la part consacrée à l'alimentation diminue et celle consacrée aux loisirs, transports et culture augmente. En France en 1960 : 35% du budget pour manger. En 2024 : moins de 20%.</p>

    <div class="section-title green">3. L'épargne et ses théories</div>
    <div class="def-box green">L'<strong>épargne</strong> = revenu disponible – consommation. C'est la partie du revenu qu'on ne dépense pas tout de suite.</div>
    <p><span class="auteur">Modigliani</span> (Prix Nobel 1985) explique le comportement d'épargne par le <strong>cycle de vie</strong> : on s'endette jeune (emprunt immobilier, études), on épargne pendant la vie active, et on désépargne à la retraite pour maintenir son niveau de vie. C'est pourquoi les retraités consomment davantage leur épargne.</p>
    <div class="def-box green"><strong>⚠️ Paradoxe de l'épargne (Keynes) :</strong> Si tout le monde décide d'épargner davantage en même temps → la consommation chute → les entreprises vendent moins → elles licencient → les revenus baissent → on finit par épargner MOINS qu'avant. Ce qui est rationnel individuellement devient catastrophique collectivement.</div>
    <div class="exemple">En 2008 après la crise financière, les ménages paniqués ont tous épargné en même temps → chute de la consommation → récession aggravée. C'est exactement ce que Keynes avait prédit.</div>

    <div class="section-title green">4. L'investissement (FBCF)</div>
    <p>L'investissement se mesure par la <strong>FBCF</strong> (Formation Brute de Capital Fixe). Ce sont les achats de biens durables (> 1 an) pour accroître ou maintenir la capacité de production.</p>
    <table class="mini-table green">
      <tr><th>Type d'investissement</th><th>Exemple concret</th></tr>
      <tr><td>De capacité</td><td>Amazon ouvre un nouveau entrepôt en France</td></tr>
      <tr><td>De remplacement</td><td>Air France remplace ses vieux Airbus par des A320neo</td></tr>
      <tr><td>De productivité</td><td>Renault installe des robots dans son usine</td></tr>
      <tr><td>Immatériel</td><td>Capgemini investit dans la formation de ses ingénieurs en IA</td></tr>
    </table>
    <div class="formule green">Équilibre ressources-emplois : Production intérieure + Importations = Consommation + FBCF + Exportations + Variations de stocks</div>
    <div class="piege">Les exportations sont dans les "emplois" car elles "sortent" du territoire national. On raisonne du point de vue des ressources disponibles pour l'économie nationale.</div>
  </div>
</div>

<div class="fiche d3" id="d3">
  <div class="fiche-header" onclick="openModal('d3')"><div class="num">Dossier 3 – Séquence 3</div><h2>Comment l'activité économique crée-t-elle de la richesse ?</h2></div>
  <div class="fiche-body">
    <div class="section-title orange">1. La Valeur Ajoutée (VA) : la richesse vraiment créée</div>
    <div class="def-box orange">La <strong>Valeur Ajoutée</strong> est la richesse nouvelle créée lors de la production. C'est ce que l'entreprise "ajoute" à ce qu'elle a acheté à l'extérieur.</div>
    <div class="formule orange">VA = Chiffre d'Affaires (CA) – Consommations Intermédiaires (CI)</div>
    <p>Les <strong>Consommations Intermédiaires (CI)</strong> sont les biens ou services achetés à d'autres entreprises et détruits ou transformés dans la production (matières premières, électricité, emballages…). <strong>Attention : les machines ne sont PAS des CI</strong> — elles durent plus d'un an et font partie du capital fixe.</p>
    <div class="exemple">
      <strong>Exemple du jean :</strong> Un fabricant achète du tissu (10€), des boutons (2€), du fil (1€) = CI de 13€. Il vend le jean 60€. <br>
      VA = 60€ – 13€ = <strong>47€</strong><br>
      Avec ces 47€, il paye : ses salariés (couturières), sa banque (intérêts du prêt), ses impôts, et garde une partie pour s'autofinancer.
    </div>
    <div class="piege">Ne pas confondre le CA (tout ce que l'entreprise encaisse) et la VA (la richesse qu'elle crée réellement). Si tu achètes des matières premières 80€ et revends 100€, ta VA n'est que de 20€, pas 100€.</div>

    <div class="section-title orange">2. Comment la VA est-elle répartie ?</div>
    <p>La VA créée est ensuite <strong>répartie</strong> entre tous ceux qui ont contribué à la production :</p>
    <table class="mini-table orange">
      <tr><th>Qui reçoit ?</th><th>Sous quelle forme ?</th><th>Part en France (2024)</th></tr>
      <tr><td><strong>Salariés</strong></td><td>Salaires + cotisations sociales patronales</td><td>~63% de la VA</td></tr>
      <tr><td><strong>Banques / prêteurs</strong></td><td>Intérêts sur les emprunts</td><td>variable</td></tr>
      <tr><td><strong>Actionnaires</strong></td><td>Dividendes</td><td>~10-12%</td></tr>
      <tr><td><strong>État</strong></td><td>Impôts sur la production, TVA</td><td>~3%</td></tr>
      <tr><td><strong>Entreprise elle-même</strong></td><td>EBE = bénéfices mis en réserve (autofinancement)</td><td>~22-24%</td></tr>
    </table>
    <p>On distingue la <strong>répartition primaire</strong> (partage de la VA avant intervention de l'État) et la <strong>répartition secondaire</strong> (après redistribution par l'État via les impôts et les allocations sociales). Le RSA, les allocations chômage ou familiales font partie de la répartition secondaire.</p>

    <div class="section-title orange">3. Les 3 secteurs économiques (Colin Clark)</div>
    <p><span class="auteur">Colin Clark (1905-1989)</span>, économiste britannique, est le premier à avoir divisé l'économie en trois grands secteurs pour analyser le développement économique :</p>
    <table class="mini-table orange">
      <tr><th>Secteur</th><th>Ce qu'il produit</th><th>Exemples en France</th></tr>
      <tr><td><strong>Primaire</strong></td><td>Exploitation directe de la nature</td><td>Agriculture, pêche, exploitation forestière, mines</td></tr>
      <tr><td><strong>Secondaire</strong></td><td>Transformation et industrie</td><td>Automobile (Renault), agroalimentaire (Danone), BTP</td></tr>
      <tr><td><strong>Tertiaire</strong></td><td>Services de toute nature</td><td>Commerce (Carrefour), finance (BNP), tourisme, éducation, santé</td></tr>
    </table>
    <div class="actu">En 2024, le tertiaire représente ~77% des emplois et ~80% du PIB en France. La France est passée d'une économie industrielle à une économie de services en moins de 50 ans.</div>
    <div class="exemple">Dans les années 1970, Renault et les mines de charbon embauchaient des centaines de milliers de salariés. Aujourd'hui, les plus gros employeurs privés français sont des entreprises de services : La Poste, Sodexo, Auchan… C'est le basculement vers le tertiaire décrit par Clark.</div>

    <div class="section-title orange">4. L'Économie Sociale et Solidaire (ESS)</div>
    <p>L'<strong>ESS</strong> regroupe des organisations qui ne cherchent pas à maximiser le profit mais à concilier performance économique et utilité sociale. Elles fonctionnent selon des principes de démocratie interne et de solidarité :</p>
    <table class="mini-table orange">
      <tr><th>Forme</th><th>Principe</th><th>Exemples</th></tr>
      <tr><td>Coopératives</td><td>Appartient aux salariés ou producteurs</td><td>Crédit Agricole, E.Leclerc, coopératives agricoles</td></tr>
      <tr><td>Mutuelles</td><td>Gérée par ses membres, sans profit</td><td>MAIF, Mutuelle des étudiants</td></tr>
      <tr><td>Associations</td><td>But non lucratif, utilité sociale</td><td>Croix-Rouge, Les Restos du Cœur, clubs sportifs</td></tr>
      <tr><td>Fondations</td><td>Patrimoine dédié à une cause</td><td>Fondation Abbé Pierre, Fondation de France</td></tr>
    </table>
    <div class="actu">L'ESS représente ~10% de l'emploi salarié en France, soit plus de 2,4 millions de personnes. C'est plus que l'industrie automobile mondiale dans l'Hexagone.</div>
  </div>
</div>

<div class="fiche d4" id="d4">
  <div class="fiche-header" onclick="openModal('d4')"><div class="num">Dossier 4 – Séquence 4</div><h2>Comment rendre compte de la situation économique d'un pays ?</h2></div>
  <div class="fiche-body">
    <div class="section-title purple">1. Le PIB : définition et calcul</div>
    <div class="def-box purple">Le <strong>PIB</strong> (Produit Intérieur Brut) est la somme de toutes les valeurs ajoutées produites sur le territoire français en un an, plus la TVA et les droits de douane. C'est l'indicateur numéro 1 pour mesurer la richesse créée et la croissance d'un pays.</div>
    <p>Il existe <strong>3 façons de le calculer</strong>, toutes équivalentes (elles donnent le même résultat) :</p>
    <div class="formule purple">Approche offre : PIB = Σ VA + TVA + droits de douane</div>
    <div class="formule purple">Approche demande : PIB = C (conso) + I (invest.) + ΔS (variation stocks) + (X – M) (solde commercial)</div>
    <div class="formule purple">Approche revenus : PIB = Salaires + EBE + (Impôts sur prod. – Subventions)</div>
    <div class="exemple">En 2024, le PIB de la France est d'environ 2 800 milliards d'euros. L'Allemagne est à ~4 000 Mds€, les États-Unis à ~28 000 Mds€.</div>

    <p><strong>PIB en valeur vs PIB en volume :</strong> si les prix augmentent de 5% mais que la production ne change pas, le PIB en valeur monte de 5% mais le PIB en volume (corrigé de l'inflation) reste à 0%. À l'examen, <strong>on parle toujours de croissance en volume</strong> (= croissance réelle). Pour comparer des pays aux niveaux de prix différents, on utilise le <strong>PIB par habitant en PPA</strong> (Parité de Pouvoir d'Achat).</p>
    <div class="piege">Le PIB est un indicateur TERRITORIAL : il compte ce qui est produit EN France, peu importe si c'est une entreprise française ou étrangère. ≠ PNB (Produit National Brut) qui compte ce que produisent les Français partout dans le monde.</div>

    <div class="section-title purple">2. Les limites du PIB : ce qu'il ne mesure pas</div>
    <p>Le PIB est un outil imparfait pour mesurer le bien-être d'une population :</p>
    <table class="mini-table purple">
      <tr><th>Limite</th><th>Explication concrète</th></tr>
      <tr><td>Travail non marchand ignoré</td><td>Elever ses enfants, faire la cuisine, aider ses parents âgés ne comptent pas. Pourtant ce sont des activités qui créent de la valeur.</td></tr>
      <tr><td>Activités néfastes comptabilisées</td><td>Une marée noire fait monter le PIB (nettoyage = activité économique). Paradoxal.</td></tr>
      <tr><td>Masque les inégalités</td><td>Le PIB par habitant en Qatar est très élevé… mais la moitié de la population est constituée de travailleurs immigrés peu payés.</td></tr>
      <tr><td>Économie souterraine exclue</td><td>Travail au noir, trafics illicites, échanges entre voisins ne sont pas comptabilisés.</td></tr>
    </table>
    <div class="def-box purple"><strong>Paradoxe d'Easterlin (Richard Easterlin, 1974) :</strong> Au-delà d'un certain seuil de richesse, augmenter le PIB ne rend plus les gens plus heureux. Les États-Unis ont vu leur PIB tripler depuis 1960 mais le taux de bonheur déclaré est resté quasi stable. Richesse ≠ bonheur.</div>
    <div class="exemple">Le Bhoutan, petit pays d'Asie, a renoncé à maximiser son PIB pour maximiser son "Bonheur National Brut". Les habitants travaillent moins, polluent moins, et se déclarent parmi les plus heureux d'Asie.</div>

    <div class="section-title purple">3. Les indicateurs alternatifs</div>
    <p>Depuis les années 1990, plusieurs indicateurs ont été créés pour aller au-delà du PIB :</p>
    <table class="mini-table purple">
      <tr><th>Indicateur</th><th>Ce qu'il mesure en plus du PIB</th><th>Qui l'a créé</th></tr>
      <tr><td><strong>IDH</strong></td><td>Espérance de vie + années d'éducation + RNB/hab en PPA. Échelle de 0 à 1.</td><td><span class="auteur">Amartya Sen</span> (Prix Nobel) / PNUD, 1990</td></tr>
      <tr><td><strong>Better Life Index (BLI)</strong></td><td>11 dimensions : logement, emploi, santé, sécurité, satisfaction de vie…</td><td>OCDE, 2011</td></tr>
      <tr><td><strong>Épargne Nette Ajustée</strong></td><td>Mesure si on "consomme" ou "préserve" le capital naturel pour les générations futures</td><td>Banque mondiale</td></tr>
    </table>
    <div class="exemple"><strong>L'IDH en pratique :</strong> La Norvège a un PIB/habitant parmi les plus élevés du monde ET un IDH proche de 1. Le Niger a l'un des IDH les plus bas (0,394 en 2021) malgré d'importantes ressources en uranium. L'IDH révèle que la richesse extractive ne se traduit pas toujours en bien-être humain.</div>
    <div class="auteur" style="display:block;background:#f3effe;padding:12px 16px;border-radius:6px;margin-top:12px;font-size:0.95em;color:#4a235a">
      <strong>Qui est Amartya Sen ?</strong> Économiste indien (né en 1933), Prix Nobel d'économie 1998. Il a développé l'idée que le développement ne doit pas être mesuré par l'argent, mais par les <em>libertés réelles</em> dont disposent les individus : accès à la santé, à l'éducation, à la participation politique. Il a co-créé l'IDH avec le PNUD en 1990.
    </div>
  </div>
</div>

  <div class="page-footer">Thème 1 · DCG UE5 · <button onclick="goHome()" style="background:none;border:none;color:#2d6a9f;cursor:pointer;font-size:1em;">← Retour à l'accueil</button></div>
</div>


<!-- ══════════════════════════════════════════ -->
<!-- PAGE : THÈME 2 -->
<!-- ══════════════════════════════════════════ -->
<div class="page" id="page-t2">
  <div class="theme-cover tc-t2">
    <div class="tc-num">Thème 2</div>
    <h2>L'économie de marché</h2>
    <p>Dossiers 5 à 6 · Concurrence, modèles d'organisation, défaillances du marché</p>
  </div>

<div class="fiche d5" id="d5">
  <div class="fiche-header" onclick="openModal('d5')"><div class="num">Dossier 5 – Séquence 5</div><h2>L'économie de marché : fonctionnement, concurrence et modèles</h2></div>
  <div class="fiche-body">
    <div class="section-title teal">1. Le marché et la "main invisible" d'Adam Smith</div>
    <div class="def-box teal">Le <strong>marché</strong> est le lieu (réel ou virtuel) où se rencontrent l'offre et la demande pour fixer un <strong>prix d'équilibre</strong> et des quantités échangées.</div>
    <div class="auteur" style="display:block;background:#e8f8f5;padding:12px 16px;border-radius:6px;margin:12px 0;font-size:0.95em;color:#0e5940">
      <strong>Qui est Adam Smith ?</strong> Économiste et philosophe écossais (1723-1790). Son livre <em>La Richesse des Nations</em> (1776) est le texte fondateur de l'économie libérale. Il est le premier à expliquer comment le marché, sans intervention extérieure, peut organiser efficacement la production et la distribution des richesses.
    </div>
    <p>Sa grande idée : la <strong>"main invisible"</strong>. Chaque individu cherche son intérêt personnel (vendre au meilleur prix, acheter au moins cher) sans penser à l'intérêt collectif. Pourtant, le jeu de la concurrence fait que ces intérêts égoïstes convergent vers un équilibre bénéfique pour tous. Personne ne "dirige" le marché, il s'organise tout seul.</p>
    <div class="exemple">Le boulanger fait du pain pour gagner de l'argent, pas pour nourrir la population. Pourtant il nourrit la population. C'est la main invisible : l'intérêt privé sert l'intérêt général.</div>

    <div class="section-title teal">2. La Concurrence Pure et Parfaite (CPP) : le modèle idéal</div>
    <p>Les économistes néoclassiques (<span class="auteur">Walras, Pareto</span>) ont théorisé le marché idéal : la CPP. C'est un modèle théorique — il n'existe pas vraiment — mais il sert de référence.</p>
    <table class="mini-table teal">
      <tr><th>Condition</th><th>Ce que ça signifie concrètement</th></tr>
      <tr><td><strong>Atomicité</strong></td><td>Des milliers d'acheteurs et vendeurs, aucun ne peut influencer le prix à lui seul</td></tr>
      <tr><td><strong>Homogénéité</strong></td><td>Les produits sont strictement identiques d'un vendeur à l'autre (le blé d'un agriculteur = le blé d'un autre)</td></tr>
      <tr><td><strong>Libre entrée/sortie</strong></td><td>N'importe qui peut entrer ou quitter le marché sans barrière ni coût</td></tr>
      <tr><td><strong>Mobilité des facteurs</strong></td><td>Le travail et le capital peuvent se déplacer librement vers les secteurs les plus rentables</td></tr>
      <tr><td><strong>Transparence</strong></td><td>Tous les acteurs ont accès à la même information sur les prix et la qualité</td></tr>
    </table>
    <div class="highlight"><strong>Résultat de la CPP :</strong> l'optimum de Pareto (<span class="auteur">Vilfredo Pareto, 1896</span>) — on ne peut améliorer la situation de personne sans dégrader celle d'une autre. En CPP, les ressources sont allouées de façon optimale.</div>
    <div class="piege">La CPP est quasi-inexistante dans la vraie vie. Internet s'en approche parfois (comparateurs de prix), mais même là la transparence est imparfaite. En pratique → concurrence imparfaite (voir D6).</div>

    <div class="section-title teal">3. Les visions dynamiques de la concurrence : 3 auteurs essentiels</div>
    <table class="mini-table teal">
      <tr><th>Auteur</th><th>Sa vision</th><th>Exemple concret</th></tr>
      <tr><td><span class="auteur">Schumpeter</span> (1942)</td><td><strong>Destruction créatrice</strong> : l'innovation détruit les activités obsolètes et en crée de nouvelles. La croissance vient de l'instabilité, pas de l'équilibre.</td><td>Le smartphone a détruit l'industrie des appareils photo (Kodak faillite en 2012) et créé des millions d'emplois dans les apps mobiles</td></tr>
      <tr><td><span class="auteur">Hayek</span> (1945)</td><td><strong>Concurrence = processus de découverte</strong> : les prix transmettent une information dispersée que personne ne peut centraliser. Aucune autorité ne peut remplacer le marché.</td><td>Amazon ajuste 2,5 millions de prix par jour grâce aux signaux du marché — aucun planificateur central ne pourrait faire ça</td></tr>
      <tr><td><span class="auteur">Baumol</span> (1982)</td><td><strong>Marchés contestables</strong> : même avec peu d'acteurs, la simple <em>menace</em> d'entrée de nouveaux concurrents suffit à discipliner les prix, si les barrières à l'entrée sont faibles.</td><td>Sur les liaisons aériennes Paris-Toulouse, Air France baisse ses prix car easyJet ou Ryanair pourraient s'y installer facilement</td></tr>
    </table>

    <div class="section-title teal">4. Les 3 grands modèles d'organisation économique</div>
    <table class="mini-table teal">
      <tr><th>Modèle</th><th>Rôle du marché</th><th>Rôle de l'État</th><th>Exemple pays</th></tr>
      <tr><td><strong>Libéral</strong></td><td>Central, auto-régulateur</td><td>Minimal : sécurité, justice, respect des contrats</td><td>États-Unis, Royaume-Uni (avant Brexit)</td></tr>
      <tr><td><strong>Mixte</strong></td><td>Important mais régulé</td><td>Correcteur des défaillances, redistribution</td><td>France, Allemagne, Scandinavie</td></tr>
      <tr><td><strong>Dirigiste / planifié</strong></td><td>Limité ou inexistant</td><td>L'État décide de la production et des prix</td><td>URSS (1917-1991), Chine Mao (1949-1978)</td></tr>
    </table>
    <div class="exemple">La France est un modèle mixte : Carrefour et Total sont privés (marché), mais la SNCF, EDF et les hôpitaux sont publics ou régulés (État). L'État intervient là où le marché est défaillant.</div>
  </div>
</div>

<div class="fiche d6" id="d6">
  <div class="fiche-header" onclick="openModal('d6')"><div class="num">Dossier 6 – Séquence 6</div><h2>Pourquoi encadrer le fonctionnement du marché ?</h2></div>
  <div class="fiche-body">
    <div class="section-title darkred">1. La concurrence imparfaite : quand certains dominent le marché</div>
    <p>En pratique, la CPP (D5) n'existe presque jamais. Les marchés réels sont souvent dominés par quelques acteurs puissants :</p>
    <table class="mini-table darkred">
      <tr><th>Structure</th><th>Ce que c'est</th><th>Exemple concret</th></tr>
      <tr><td><strong>Monopole</strong></td><td>Une seule entreprise domine. Elle est "price maker" : elle fixe ses prix comme elle veut, sans craindre la concurrence.</td><td>Google = 90% du marché mondial de la recherche en ligne. SNCF sur de nombreuses lignes avant l'ouverture à la concurrence.</td></tr>
      <tr><td><strong>Oligopole</strong></td><td>Quelques grandes firmes se partagent le marché et s'influencent mutuellement. Si l'une baisse ses prix, les autres sont obligées de réagir.</td><td>Téléphonie mobile en France : Orange, SFR, Bouygues, Free. Streaming : Netflix, Disney+, Amazon Prime.</td></tr>
      <tr><td><strong>Concurrence monopolistique</strong></td><td>Nombreuses entreprises, mais chacune a une clientèle fidèle grâce à des produits différenciés (marque, design, réputation…).</td><td>Fast-food (McDonald's ≠ Burger King ≠ KFC), cosmétiques (L'Oréal ≠ Nivea), vêtements (Zara ≠ H&M).</td></tr>
    </table>

    <div class="section-title darkred">2. Les pratiques anticoncurrentielles : quand les entreprises trichent</div>
    <p>Certaines entreprises abusent de leur position ou s'entendent illégalement pour nuire à la concurrence et aux consommateurs :</p>
    <table class="mini-table darkred">
      <tr><th>Pratique</th><th>Ce que c'est</th><th>Sanction réelle</th></tr>
      <tr><td><strong>Abus de position dominante</strong></td><td>Une entreprise dominante écrase ses concurrents de façon déloyale (vente à perte, exclusivité forcée…)</td><td>Google condamné à 4,34 Mds€ par l'UE en 2018 (favorisait son propre comparateur de prix)</td></tr>
      <tr><td><strong>Entente illicite</strong></td><td>Des concurrents s'entendent secrètement pour fixer les prix ou se partager les marchés</td><td>Orange, SFR, Bouygues condamnés à 534 M€ en 2015 pour s'être partagé des clients pros</td></tr>
      <tr><td><strong>Auto-préférence</strong></td><td>Une plateforme favorise ses propres produits dans ses résultats au détriment des concurrents</td><td>Apple condamné à 1,8 Mds€ en 2024 par l'UE pour avoir favorisé Apple Music</td></tr>
    </table>
    <div class="actu"><strong>Digital Markets Act (DMA, 2023) :</strong> Nouveau règlement européen qui impose des obligations aux géants du numérique désignés comme "contrôleurs d'accès" (Google, Apple, Meta, Amazon, Microsoft, TikTok, Booking). Sanctions pouvant aller jusqu'à 10% du CA mondial — voire 20% en cas de récidive.</div>

    <div class="section-title darkred">3. Les biens publics : ce que le marché ne peut pas fournir</div>
    <div class="def-box darkred">Un <strong>bien public pur</strong> a deux propriétés selon <span class="auteur">Paul Samuelson (1954)</span> :<br>
    • <strong>Non-rivalité :</strong> je peux l'utiliser sans réduire la quantité disponible pour les autres (si je regarde le feu d'artifice du 14 juillet, ça n'empêche pas mon voisin de le regarder aussi)<br>
    • <strong>Non-exclusion :</strong> impossible d'empêcher quelqu'un d'en bénéficier, même s'il ne paie pas → <strong>passagers clandestins</strong></div>
    <div class="exemple">La défense nationale protège tous les Français, même ceux qui ne paient pas d'impôts. L'éclairage public illumine la rue pour tout le monde. Internet ne voudra jamais financer ça → c'est à l'État de le faire avec l'impôt.</div>
    <div class="auteur" style="display:block;background:#fdecea;padding:12px 16px;border-radius:6px;margin:12px 0;font-size:0.95em;color:#7b1818">
      <strong>Qui est Paul Samuelson ?</strong> Économiste américain (1915-2009), Prix Nobel 1970. Il est l'auteur du manuel d'économie le plus vendu de l'histoire. Il est le premier à avoir formalisé mathématiquement la théorie des biens publics, montrant pourquoi le marché ne peut pas les financer efficacement.
    </div>

    <div class="section-title darkred">4. Les externalités : quand une activité impacte des tiers</div>
    <div class="def-box darkred">Une <strong>externalité</strong> est l'effet (positif ou négatif) d'une activité économique sur un tiers qui n'est pas partie prenante de l'échange, sans compensation financière. <span class="auteur">Arthur Pigou (1877-1959)</span> est le premier à proposer une solution : faire payer le coût social.</div>
    <table class="mini-table darkred">
      <tr><th>Type</th><th>Exemple concret</th><th>Solution de l'État</th></tr>
      <tr><td><strong>Externalité négative</strong></td><td>Une usine rejette des polluants dans la rivière. Les pêcheurs en aval perdent leur activité mais ne sont pas dédommagés.</td><td>Taxe carbone, malus écologique, norme d'émission</td></tr>
      <tr><td><strong>Externalité positive</strong></td><td>Pfizer développe un vaccin contre la grippe. En vaccinant des gens, il protège aussi les personnes fragiles qui ne se sont pas vaccinées (immunité collective).</td><td>Subvention, remboursement Sécu, campagne gratuite</td></tr>
      <tr><td><strong>Externalité positive (entreprise)</strong></td><td>Google investit dans la recherche sur l'IA. Ses découvertes profitent à toute l'industrie via les publications scientifiques.</td><td>Crédit Impôt Recherche (CIR)</td></tr>
    </table>
    <div class="piege"><strong>Concurrence imparfaite ≠ défaillance pure :</strong> la concurrence imparfaite (monopole, oligopole) signifie que le marché fonctionne mais mal → régulation par les autorités de concurrence. Les biens publics et externalités sont des défaillances pures → le marché est structurellement incapable de les gérer correctement → intervention directe de l'État indispensable.</div>
  </div>
</div>

  <div class="page-footer">Thème 2 · DCG UE5 · <button onclick="goHome()" style="background:none;border:none;color:#0e6655;cursor:pointer;font-size:1em;">← Retour à l'accueil</button></div>
</div>


<!-- ══════════════════════════════════════════ -->
<!-- PAGE : THÈME 3 -->
<!-- ══════════════════════════════════════════ -->
<div class="page" id="page-t3">
  <div class="theme-cover tc-t3">
    <div class="tc-num">Thème 3</div>
    <h2>Le financement de l'économie</h2>
    <p>Dossiers 7 à 8 · Capacité/besoin de financement, banques, marchés financiers</p>
  </div>

<div class="fiche d7" id="d7">
  <div class="fiche-header" onclick="openModal('d7')"><div class="num">Dossier 7 – Séquence 7</div><h2>Quels agents ont un besoin ou une capacité de financement ?</h2></div>
  <div class="fiche-body">
    <div class="section-title navy">1. Capacité et besoin de financement</div>
    <div class="def-box navy">Un agent est en <strong>capacité de financement</strong> quand ses ressources (revenus, recettes) dépassent ses dépenses : il a de l'argent à placer. Un agent est en <strong>besoin de financement</strong> quand ses dépenses dépassent ses ressources : il doit emprunter pour financer ses projets.</div>
    <table class="mini-table navy">
      <tr><th>Agent</th><th>Situation habituelle</th><th>Pourquoi ?</th></tr>
      <tr><td><strong>Ménages</strong></td><td>Capacité de financement ✅</td><td>Ils gagnent plus qu'ils ne consomment. Taux d'épargne en France : ~17% du revenu disponible en 2024.</td></tr>
      <tr><td><strong>Entreprises (SNF)</strong></td><td>Besoin de financement ❌</td><td>Elles investissent plus qu'elles ne s'autofinancent. Renault doit emprunter pour construire une nouvelle usine.</td></tr>
      <tr><td><strong>État (APU)</strong></td><td>Besoin de financement structurel ❌</td><td>L'État dépense plus qu'il ne perçoit d'impôts depuis les années 1970. Déficit 2024 : −5,8% du PIB.</td></tr>
      <tr><td><strong>Sociétés financières</strong></td><td>Capacité de financement ✅</td><td>Leur rôle est justement de collecter l'épargne et de la prêter à ceux qui en ont besoin.</td></tr>
    </table>
    <div class="exemple">Les ménages épargnent à la BNP (capacité). La BNP prête cet argent à Airbus pour financer un nouvel avion (besoin). C'est la rencontre entre capacité et besoin de financement, le rôle central des banques.</div>

    <div class="section-title navy">2. Deux théories de l'épargne face à face</div>
    <p>Pourquoi les ménages épargnent-ils ? Deux économistes ont des réponses différentes :</p>
    <div class="def-box navy">
      <strong>Théorie du revenu permanent (<span class="auteur">Milton Friedman</span>, 1957) :</strong><br>
      Les ménages ne basent pas leur épargne sur leur revenu du moment, mais sur ce qu'ils espèrent gagner sur l'ensemble de leur vie (leur "revenu permanent"). Si tu reçois une prime exceptionnelle de 3 000€, tu ne la dépenses pas entièrement : tu sais que c'est temporaire et tu l'épargnes.
    </div>
    <div class="def-box navy">
      <strong>Théorie du cycle de vie (<span class="auteur">Ando & Modigliani</span>, 1963) :</strong><br>
      Le comportement d'épargne change au fil de la vie : endettement en début de vie active (crédit immobilier, études) → épargne pendant la vie active (retraite complémentaire, assurance-vie) → désépargne à la retraite (on vit sur son capital). C'est comme un camel : bosse d'épargne au milieu de la vie.
    </div>
    <div class="exemple">Un jeune cadre de 30 ans rembourse son crédit étudiant ET son prêt immobilier = désépargne. À 45 ans, il cotise à son PEA et son assurance-vie = épargne. À 70 ans, il retire ses placements pour voyager = désépargne. C'est exactement le cycle de vie de Modigliani.</div>

    <div class="section-title navy">3. Déficit vs dette : la confusion la plus courante à l'examen</div>
    <div class="def-box navy">
      <strong>DÉFICIT</strong> = FLUX = résultat d'UNE SEULE ANNÉE (recettes − dépenses). France 2024 : −5,8% du PIB.<br>
      <strong>DETTE</strong> = STOCK = accumulation de TOUS les déficits passés non remboursés depuis des décennies. France 2024 : 113% du PIB.
    </div>
    <div class="exemple">Imagine une baignoire avec un robinet (recettes fiscales) et un bouchon qui fuit (dépenses). Le déficit = la quantité d'eau qui s'échappe chaque année. La dette = toute l'eau qui s'est déjà échappée et qu'il faudrait remettre. Même si on réduisait le déficit à zéro demain, la dette resterait à 113% du PIB !</div>
    <p>Pour financer son déficit, l'État émet des <strong>OAT</strong> (Obligations Assimilables du Trésor), gérées par l'<strong>Agence France Trésor</strong>. En 2024, ~52% de la dette est détenue par des non-résidents (fonds d'investissement étrangers, banques centrales). Cela rend la France dépendante des marchés financiers internationaux.</p>
    <div class="actu">En 2024, la charge d'intérêts de la dette française dépasse <strong>56 milliards €/an</strong>, devenant le premier poste budgétaire de l'État devant l'Éducation nationale (57 Mds€). Chaque jour, la France paie ~150 millions d'euros d'intérêts sans rien rembourser du capital.</div>

    <div class="section-title navy">4. Les 6 modes de financement des entreprises</div>
    <table class="mini-table navy">
      <tr><th>Mode</th><th>Ce que c'est</th><th>Avantage / Inconvénient</th></tr>
      <tr><td><strong>Autofinancement</strong></td><td>L'entreprise utilise ses bénéfices mis en réserve</td><td>✅ Aucun remboursement ni intérêts ❌ Limité aux bénéfices passés</td></tr>
      <tr><td><strong>Emprunt bancaire</strong></td><td>La banque prête une somme remboursée avec intérêts</td><td>✅ Accessible ❌ Intérêts + garanties exigées</td></tr>
      <tr><td><strong>Augmentation de capital</strong></td><td>Émission de nouvelles actions vendues à des investisseurs</td><td>✅ Pas de remboursement ❌ Dilue le pouvoir des actionnaires</td></tr>
      <tr><td><strong>Emprunt obligataire</strong></td><td>L'entreprise émet des obligations sur les marchés</td><td>✅ Gros montants possibles ❌ Réservé aux grandes entreprises</td></tr>
      <tr><td><strong>Crédit-bail (leasing)</strong></td><td>Location d'un bien avec option d'achat en fin de contrat</td><td>✅ Utilise sans acheter ❌ Coût total plus élevé</td></tr>
      <tr><td><strong>Crowdfunding</strong></td><td>Levée de fonds via internet (Kickstarter, Ulule…)</td><td>✅ Accessible aux start-ups ❌ Montants souvent limités</td></tr>
    </table>
    <div class="piege">Le piège classique : confondre <strong>déficit</strong> (ce qu'on dépense EN PLUS chaque année) et <strong>dette</strong> (tout ce qu'on doit au total). Exemple : si le gouvernement réduit le déficit de 5,8% à 3%, la dette continue d'augmenter — elle augmente juste moins vite !</div>
  </div>
</div>

<div class="fiche d8" id="d8">
  <div class="fiche-header" onclick="openModal('d8')"><div class="num">Dossier 8 – Séquence 8</div><h2>Rôles des banques et des marchés financiers dans le financement de l'économie</h2></div>
  <div class="fiche-body">
    <div class="section-title gold">1. Finance directe vs finance indirecte</div>
    <div class="def-box gold">
      <strong>Finance indirecte (intermédiation bancaire) :</strong> tu déposes de l'argent à la BNP → la BNP le prête à une entreprise. La banque est l'intermédiaire entre épargnants et emprunteurs.<br><br>
      <strong>Finance directe (désintermédiation) :</strong> l'entreprise émet des actions ou des obligations directement sur les marchés financiers, et des investisseurs les achètent. La banque n'est plus nécessaire.
    </div>
    <div class="exemple">Tesla veut lever 2 milliards $ pour construire une nouvelle Gigafactory. Deux options : 1) Emprunter à une banque (finance indirecte) 2) Émettre de nouvelles actions en Bourse et des investisseurs du monde entier les achètent directement (finance directe). Tesla choisit souvent la 2e option car elle ne paie pas d'intérêts aux actionnaires si l'action monte.</div>

    <div class="section-title gold">2. Les 3 rôles essentiels des banques</div>
    <table class="mini-table gold">
      <tr><th>Rôle</th><th>Ce que la banque fait concrètement</th></tr>
      <tr><td><strong>1. Moyens de paiement</strong></td><td>Elle gère les comptes courants, cartes bancaires, virements, chèques. Sans banques, impossible d'acheter en ligne ou de recevoir ton salaire.</td></tr>
      <tr><td><strong>2. Transformation des échéances</strong></td><td>Elle collecte des dépôts à COURT terme (ton compte courant que tu peux vider demain) et prête à LONG terme (crédit immobilier sur 20 ans). C'est un risque : si tous les clients retirent leur argent en même temps → bank run (faillite de la banque).</td></tr>
      <tr><td><strong>3. Création monétaire</strong></td><td>Quand elle accorde un crédit, elle crée de la monnaie qui n'existait pas. Cette monnaie disparaît quand l'emprunteur rembourse.</td></tr>
    </table>
    <div class="def-box gold"><strong>Comment fonctionne la création monétaire ?</strong> Tu demandes un crédit de 10 000€ pour acheter une voiture. La banque inscrit 10 000€ sur ton compte → cet argent est créé à partir de rien (ex nihilo). Tu paies le concessionnaire → l'argent circule dans l'économie. Tu rembourses 500€/mois → cet argent est détruit progressivement. <strong>"Les crédits font les dépôts"</strong> (dicton des banquiers centraux).</div>
    <div class="piege">Une banque ne prête pas l'argent de ses déposants. Elle CRÉE l'argent qu'elle prête. Ce n'est donc pas ton dépôt de 1 000€ qui finance le crédit immobilier de ton voisin.</div>

    <div class="section-title gold">3. La réglementation prudentielle : Bâle III</div>
    <p>La crise des <strong>subprimes de 2008</strong> a montré que des banques mal régulées pouvaient prendre des risques excessifs et mettre en danger tout le système financier mondial. Pour éviter ça :</p>
    <div class="def-box gold">Les accords <strong>Bâle III</strong> (2010) imposent aux banques de détenir au minimum <strong>8% de fonds propres</strong> par rapport à leurs engagements. Si une banque prête 100€, elle doit avoir au moins 8€ de capital propre pour absorber les pertes potentielles.</div>
    <div class="exemple">En 2008, la banque américaine Lehman Brothers avait des fonds propres insuffisants face à ses engagements → quand les emprunteurs ont arrêté de rembourser (crise des subprimes), la banque s'est effondrée → panique mondiale → récession de −3,5% aux États-Unis en 2009.</div>

    <div class="section-title gold">4. Les 3D de Bourguignon : la révolution des marchés financiers depuis 1980</div>
    <p>Depuis les années 1980, le système financier mondial a été transformé par trois grandes évolutions simultanées :</p>
    <table class="mini-table gold">
      <tr><th>Le "D"</th><th>Ce qui a changé</th><th>Conséquence</th></tr>
      <tr><td><strong>Désintermédiation</strong></td><td>Les grandes entreprises se financent de moins en moins via les banques et de plus en plus directement sur les marchés (actions, obligations)</td><td>Les banques perdent des clients → elles prennent plus de risques pour compenser</td></tr>
      <tr><td><strong>Décloisonnement</strong></td><td>Les barrières entre les différents marchés financiers (actions, obligations, devises, matières premières) et entre les pays disparaissent</td><td>Les capitaux circulent librement au niveau mondial en quelques secondes</td></tr>
      <tr><td><strong>Déréglementation</strong></td><td>Les règles encadrant les activités financières sont allégées (lois Reagan aux États-Unis, loi bancaire 1984 en France)</td><td>Plus de liberté = plus de dynamisme + plus de risques systémiques</td></tr>
    </table>
    <div class="actu">Les 3D ont créé un système financier plus dynamique mais beaucoup plus fragile. C'est directement la déréglementation financière des années 1980-90 qui a rendu possible la crise de 2008 : les banques américaines avaient trop de liberté pour titriser des crédits immobiliers à risque.</div>
  </div>
</div>

  <div class="page-footer">Thème 3 · DCG UE5 · <button onclick="goHome()" style="background:none;border:none;color:#7d5a0a;cursor:pointer;font-size:1em;">← Retour à l'accueil</button></div>
</div>


<!-- ══════════════════════════════════════════ -->
<!-- PAGE : THÈME 4 -->
<!-- ══════════════════════════════════════════ -->
<div class="page" id="page-t4">
  <div class="theme-cover tc-t4">
    <div class="tc-num">Thème 4</div>
    <h2>La régulation publique dans une économie de marché</h2>
    <p>Dossiers 9 à 11 · Rôle de l'État, politiques économiques, appartenance à l'UE</p>
  </div>

<div class="fiche d9" id="d9">
  <div class="fiche-header" onclick="openModal('d9')"><div class="num">Dossier 9 – Séquence 9</div><h2>Quels sont la place et le rôle de l'État ?</h2></div>
  <div class="fiche-body">
    <div class="section-title forest">1. État-gendarme vs État-providence : deux visions opposées</div>
    <p>L'<strong>État-gendarme</strong> (vision libérale) se limite à ses fonctions <strong>régaliennes</strong> — ce que seul l'État peut faire : justice, police, défense nationale, diplomatie, monnaie. Il garantit le cadre légal sans interférer dans l'économie. Adam Smith en est le défenseur : moins l'État intervient, mieux le marché fonctionne.</p>
    <p>L'<strong>État-providence</strong> (vision keynésienne et social-démocrate) va beaucoup plus loin : il protège la population contre les grands risques sociaux de la vie (maladie, chômage, vieillesse, pauvreté, accident du travail). En France, il s'institutionnalise avec la création de la <strong>Sécurité sociale en 1945</strong> à l'initiative du Conseil National de la Résistance.</p>
    <div class="exemple">Avant 1945 en France : si tu tombais malade, tu payais le médecin de ta poche. Si tu perdais ton emploi, tu survivais grâce à la famille ou à la charité. Depuis 1945 : l'État te couvre. C'est ce passage à l'État-providence.</div>

    <div class="section-title forest">2. Les 3 fonctions de l'État selon Musgrave (1959)</div>
    <div class="auteur" style="display:block;background:#eafaf1;padding:12px 16px;border-radius:6px;margin:12px 0;font-size:0.95em;color:#145a32">
      <strong>Qui est Richard Musgrave ?</strong> Économiste américano-allemand (1910-2007). Il a systématisé les raisons pour lesquelles l'État doit intervenir dans l'économie. Son analyse en 3 fonctions est la base de toute la théorie des finances publiques.
    </div>
    <table class="mini-table forest">
      <tr><th>Fonction</th><th>L'État fait quoi ?</th><th>Exemples concrets</th></tr>
      <tr><td><strong>Allocation</strong></td><td>Corriger les défaillances du marché (D6) : produire ce que le marché ne peut pas fournir efficacement</td><td>Construction d'autoroutes, financement de l'école publique, de la recherche fondamentale (CNRS)</td></tr>
      <tr><td><strong>Redistribution</strong></td><td>Réduire les inégalités de revenus et de patrimoine</td><td>Impôt progressif sur le revenu (les riches paient plus), RSA, allocations familiales, SMIC (12,13€/h en 2024)</td></tr>
      <tr><td><strong>Stabilisation</strong></td><td>Réguler les cycles économiques (relancer en récession, freiner en surchauffe)</td><td>Plan de relance post-Covid (100 Mds€), politique monétaire de la BCE (monter les taux pour lutter contre l'inflation)</td></tr>
    </table>

    <div class="section-title forest">3. La triple crise de l'État-providence (Pierre Rosanvallon)</div>
    <div class="auteur" style="display:block;background:#eafaf1;padding:12px 16px;border-radius:6px;margin:12px 0;font-size:0.95em;color:#145a32">
      <strong>Qui est Pierre Rosanvallon ?</strong> Sociologue et historien français (né en 1948), professeur au Collège de France. Il analyse les tensions et contradictions de l'État-providence moderne. Sa théorie de la "triple crise" explique pourquoi il est difficile de le réformer sans le supprimer.
    </div>
    <table class="mini-table forest">
      <tr><th>Crise</th><th>Le problème</th><th>Exemple concret</th></tr>
      <tr><td><strong>Crise financière</strong></td><td>Les coûts de la protection sociale augmentent plus vite que les recettes : vieillissement de la population, chômage persistant, nouvelles maladies.</td><td>En 2024, le déficit de la Sécurité sociale française est de ~11 Mds€. La retraite à 64 ans est une réponse à cette crise financière.</td></tr>
      <tr><td><strong>Crise d'efficacité</strong></td><td>Les politiques publiques produisent-elles vraiment les résultats attendus ? Les aides semblent parfois créer des "trappes à pauvreté" ou "à inactivité".</td><td>Malgré des millions d'euros investis, le chômage des jeunes et l'échec scolaire persistent en France.</td></tr>
      <tr><td><strong>Crise de légitimité</strong></td><td>Les citoyens veulent plus de services publics de qualité (hôpitaux, école, retraites) MAIS refusent de payer davantage d'impôts. Paradoxe impossible.</td><td>Les Gilets Jaunes (2018-2019) : protestation contre la hausse de la taxe carbone, perçue comme injuste.</td></tr>
    </table>

    <div class="section-title forest">4. Les collectivités territoriales et la décentralisation</div>
    <p>La loi de décentralisation (<strong>lois Defferre, 1982</strong>) a transféré une partie des pouvoirs de l'État central vers les collectivités locales, pour rapprocher la prise de décision des citoyens :</p>
    <table class="mini-table forest">
      <tr><th>Collectivité</th><th>Compétences principales</th></tr>
      <tr><td><strong>Communes</strong> (36 000 en France)</td><td>Écoles maternelles et primaires, urbanisme, logement social, voirie locale</td></tr>
      <tr><td><strong>Départements</strong> (101)</td><td>Action sociale (RSA, aide aux personnes âgées), gestion des collèges, routes départementales</td></tr>
      <tr><td><strong>Régions</strong> (18)</td><td>Développement économique, lycées, transports régionaux (TER), formation professionnelle</td></tr>
    </table>

    <div class="section-title forest">5. La dette publique et la courbe de Laffer</div>
    <p>Fin 2025, la dette publique française atteint <strong>115,6% du PIB</strong>. Elle est détenue à ~55% par des non-résidents. Sa <strong>soutenabilité</strong> dépend de la relation entre croissance, taux d'intérêt et déficit :</p>
    <div class="formule forest">Si g (taux de croissance) > r (taux d'intérêt réel) + d (déficit primaire) → ratio dette/PIB baisse automatiquement</div>
    <div class="highlight"><strong>Courbe de Laffer (<span class="auteur">Arthur Laffer</span>, économiste américain) :</strong> "Trop d'impôt tue l'impôt." Au-delà d'un certain taux, toute hausse d'imposition décourage le travail et l'investissement et fait BAISSER les recettes fiscales. Courbe en forme de cloche. Cette idée a fondé les politiques de Reagan (réduction d'impôts aux États-Unis dans les années 1980).</div>
    <div class="piege">À l'examen, toujours citer les 3 fonctions de Musgrave (allocation, redistribution, stabilisation) ET la triple crise de Rosanvallon (financière, efficacité, légitimité). Ce sont des auteurs incontournables du programme.</div>
  </div>
</div>

<div class="fiche d10" id="d10">
  <div class="fiche-header" onclick="openModal('d10')"><div class="num">Dossier 10 – Séquence 10</div><h2>Quelles politiques économiques l'État peut-il mener ?</h2></div>
  <div class="fiche-body">
    <div class="section-title brown">1. Le carré magique de Kaldor : 4 objectifs contradictoires</div>
    <div class="auteur" style="display:block;background:#fdf2e9;padding:12px 16px;border-radius:6px;margin:12px 0;font-size:0.95em;color:#6e3b0a">
      <strong>Qui est Nicholas Kaldor ?</strong> Économiste britannique d'origine hongroise (1908-1986). Il a montré que les 4 grands objectifs économiques d'un gouvernement sont souvent incompatibles : les atteindre tous en même temps est si difficile qu'on parle de "carré magique".
    </div>
    <p>Les <strong>4 objectifs</strong> du carré magique sont souvent contradictoires :</p>
    <table class="mini-table brown">
      <tr><th>Objectif</th><th>Indicateur</th><th>Tension avec les autres</th></tr>
      <tr><td><strong>Croissance économique</strong></td><td>Taux de croissance du PIB</td><td>Forte croissance → risque d'inflation et de déséquilibre extérieur</td></tr>
      <tr><td><strong>Plein-emploi</strong></td><td>Taux de chômage &lt; 5%</td><td>Trop peu de chômage → hausse des salaires → inflation</td></tr>
      <tr><td><strong>Stabilité des prix</strong></td><td>Inflation ~2%</td><td>Lutter contre l'inflation par la hausse des taux → freine la croissance</td></tr>
      <tr><td><strong>Équilibre extérieur</strong></td><td>Balance commerciale équilibrée</td><td>Relancer la croissance → ↑ importations → déficit commercial</td></tr>
    </table>
    <div class="exemple">En France 2022 : la BCE a fortement monté ses taux pour lutter contre l'inflation (objectif 3 ✅) → ça a ralenti la croissance et augmenté le coût du crédit pour les entreprises (objectif 1 ❌). Impossible d'atteindre les deux en même temps.</div>

    <div class="section-title brown">2. Conjoncturelle vs structurelle</div>
    <table class="mini-table brown">
      <tr><th></th><th>Politique conjoncturelle</th><th>Politique structurelle</th></tr>
      <tr><td><strong>Horizon</strong></td><td>Court terme (quelques mois à 2 ans)</td><td>Long terme (5 à 20 ans)</td></tr>
      <tr><td><strong>Objectif</strong></td><td>Répondre à un choc immédiat (récession, inflation)</td><td>Transformer les fondations de l'économie</td></tr>
      <tr><td><strong>Instruments</strong></td><td>Politique budgétaire (État) + politique monétaire (BCE)</td><td>Réforme de l'éducation, du droit du travail, investissement en R&D</td></tr>
      <tr><td><strong>Exemple</strong></td><td>Plan de relance post-Covid (100 Mds€ en 2020)</td><td>Réforme des retraites (2023), investissement dans l'IA</td></tr>
    </table>

    <div class="section-title brown">3. Keynes vs les libéraux : le grand débat</div>
    <p>Que faire quand l'économie va mal ? Deux visions s'affrontent depuis les années 1930 :</p>
    <table class="mini-table brown">
      <tr><th></th><th>Politique de DEMANDE (Keynes)</th><th>Politique d'OFFRE (libéraux)</th></tr>
      <tr><td><strong>Diagnostic</strong></td><td>L'économie souffre d'un manque de demande : les gens n'achètent pas assez → les entreprises produisent moins → chômage</td><td>L'économie souffre de coûts de production trop élevés : charges trop lourdes, réglementation trop contraignante → les entreprises n'investissent pas</td></tr>
      <tr><td><strong>Remède</strong></td><td>↑ dépenses publiques, ↓ impôts sur les ménages pour soutenir la consommation</td><td>↓ charges patronales, ↓ impôts sur les entreprises, flexibilité du marché du travail</td></tr>
      <tr><td><strong>Théoriciens</strong></td><td><span class="auteur">Keynes</span>, Krugman, Stiglitz</td><td>Friedman, Reagan, Thatcher, Laffer</td></tr>
    </table>
    <div class="auteur" style="display:block;background:#fdf2e9;padding:12px 16px;border-radius:6px;margin:12px 0;font-size:0.95em;color:#6e3b0a">
      <strong>Qui est John Maynard Keynes ?</strong> Économiste britannique (1883-1946), considéré comme le plus influent du XXe siècle. Sa révolution : en cas de crise, les individus et entreprises n'investissent plus spontanément → l'État doit suppléer à leur carence. Ses idées ont guidé les politiques économiques occidentales de 1945 à 1975, puis ont été contestées par les libéraux (Friedman, Hayek) dans les années 1980.
    </div>

    <div class="section-title brown">4. Le multiplicateur keynésien en pratique</div>
    <div class="def-box brown">Le <strong>multiplicateur keynésien</strong> : quand l'État dépense 1€, le revenu total dans l'économie augmente de plus de 1€, car cet argent circule et crée des revenus à chaque étape.</div>
    <div class="exemple">
      L'État commande des trains à Alstom (1 Mds€). Alstom paie ses ouvriers (salaires) → les ouvriers consomment dans des commerces locaux → les commerçants paient leurs fournisseurs → etc. L'effet final dans l'économie peut atteindre 1,5 à 2 Mds€. C'est le multiplicateur.
    </div>

    <div class="section-title brown">5. Les limites de la relance keynésienne</div>
    <p>Deux arguments libéraux remettent en question l'efficacité de la relance par la dépense publique :</p>
    <div class="def-box brown">
      <strong>Équivalence ricardienne (<span class="auteur">David Ricardo</span> / <span class="auteur">Robert Lucas</span>) :</strong><br>
      Si l'État dépense plus aujourd'hui en s'endettant, les ménages savent qu'ils devront payer plus d'impôts demain. Ils épargnent donc davantage dès maintenant pour anticiper ces impôts futurs. Résultat : la relance est annulée par la hausse de l'épargne privée.
    </div>
    <div class="def-box brown">
      <strong>Effet d'éviction (<span class="auteur">Milton Friedman</span>) :</strong><br>
      Quand l'État emprunte massivement sur les marchés, il fait monter les taux d'intérêt → le crédit devient plus cher pour les entreprises → elles investissent moins → la relance publique est "évincée" par la réduction de l'investissement privé.
    </div>

    <div class="section-title brown">6. La croissance endogène : le rôle à long terme de l'État</div>
    <p>Même les libéraux reconnaissent que l'État a un rôle dans la croissance à long terme, via ce qu'on appelle la <strong>croissance endogène</strong> (la croissance vient de l'intérieur du système) :</p>
    <table class="mini-table brown">
      <tr><th>Auteur</th><th>Ce qui génère la croissance</th><th>Rôle de l'État</th></tr>
      <tr><td><span class="auteur">Robert Lucas</span></td><td>Capital humain : les compétences des travailleurs</td><td>Investir massivement dans l'éducation, la formation continue</td></tr>
      <tr><td><span class="auteur">Paul Romer</span></td><td>Innovation et connaissance (qui ne s'épuisent pas)</td><td>Financer la R&D publique, protéger les brevets</td></tr>
      <tr><td><span class="auteur">Robert Barro</span></td><td>Infrastructures productives (routes, numérique)</td><td>Investir dans les autoroutes, le très haut débit, l'énergie</td></tr>
    </table>
    <div class="exemple">Le plan France 2030 (54 Mds€ investis par l'État dans l'IA, la transition écologique, l'hydrogène) est une politique de croissance endogène typique : l'État crée les conditions d'une croissance future par l'innovation.</div>
    <div class="piege">Politique conjoncturelle (court terme) ≠ structurelle (long terme). Politique de demande (soutien à la conso) ≠ d'offre (compétitivité des entreprises). Ce sont 2 paires de distinctions différentes — ne pas les mélanger à l'examen !</div>
  </div>
</div>

<div class="fiche d11" id="d11">
  <div class="fiche-header" onclick="openModal('d11')"><div class="num">Dossier 11 – Séquence 11</div><h2>L'appartenance à l'UE influence-t-elle la politique économique des pays membres ?</h2></div>
  <div class="fiche-body">
    <div class="section-title indigo">1. La construction et l'élargissement de l'UE</div>
    <p>En <strong>1957</strong>, le <strong>Traité de Rome</strong> crée la CEE avec 6 pays fondateurs (France, Allemagne, Italie, Belgique, Pays-Bas, Luxembourg) pour créer un marché commun. Plusieurs vagues d'élargissement jusqu'à 28 membres. En 2020, le <strong>Brexit</strong> illustre qu'une intégration peut être réversible : le Royaume-Uni quitte l'UE après un référendum en 2016.</p>
    <div class="section-title indigo">2. Les niveaux d'intégration (Balassa, 1961)</div>
    <table class="mini-table indigo">
      <tr><th>Niveau</th><th>Ce que cela implique</th><th>Référence UE</th></tr>
      <tr><td>Zone de libre-échange</td><td>Suppression des droits de douane entre membres</td><td>Traité de Rome (1957)</td></tr>
      <tr><td>Union douanière</td><td>Tarif extérieur commun envers les pays tiers</td><td>Acte unique (1986)</td></tr>
      <tr><td>Marché commun</td><td>Libre circulation des facteurs (travail + capital)</td><td>Accords de Schengen</td></tr>
      <tr><td>Union économique</td><td>Coordination des politiques économiques</td><td>Traité de Maastricht (1992)</td></tr>
      <tr><td>Union économique et monétaire</td><td>Monnaie unique, politique monétaire commune</td><td>Euro (1999-2002)</td></tr>
    </table>
    <div class="section-title indigo">3. Subsidiarité et proportionnalité</div>
    <div class="def-box indigo"><strong>Subsidiarité :</strong> l'UE n'intervient que si son action est plus efficace que celle des États. L'éducation et la fiscalité restent nationales. <strong>Proportionnalité :</strong> même si l'UE est compétente, son action doit être strictement limitée au nécessaire.</div>
    <p><strong>Exception :</strong> la <strong>politique monétaire</strong> est exclusivement européenne pour la zone euro — la BCE fixe les taux pour tous, sans que chaque État puisse intervenir.</p>
    <div class="section-title indigo">4. La BCE et le Pacte de Stabilité et de Croissance</div>
    <p>La <strong>BCE</strong> (créée en 1998, indépendante des gouvernements) a pour objectif prioritaire la <strong>stabilité des prix</strong> (cible d'inflation : ~2%). Elle agit par <strong>politique monétaire conventionnelle</strong> (taux d'intérêt directeurs : baisser = relancer, monter = freiner l'inflation) et par <strong>politique non conventionnelle</strong> — le <strong>Quantitative Easing (QE)</strong> : achats massifs d'obligations d'État pour injecter des liquidités quand les taux sont déjà proches de zéro.</p>
    <p>Le <strong>Pacte de Stabilité et de Croissance (PSC, 1997)</strong> impose aux États membres : déficit public &lt; <strong>3% du PIB</strong> · dette publique &lt; <strong>60% du PIB</strong>.</p>
    <div class="actu">En 2024, la France est en procédure pour déficit excessif avec -5,8% du PIB, bien au-delà de la limite de -3%.</div>
    <div class="section-title indigo">5. Budget et politiques structurelles de l'UE</div>
    <p>Le budget de l'UE représente ~1% du PIB européen (contre 40-50% pour les budgets nationaux). Il est dominé par la <strong>PAC</strong> (~38%), la <strong>politique de cohésion</strong> (~34%), la recherche (~7%) et Erasmus (~1,5%). L'UE ne peut donc pas mener de politique budgétaire conjoncturelle. Le plan <strong>NextGenerationEU</strong> (750 Mds€ post-Covid) est une innovation : pour la première fois, l'UE a levé une dette commune.</p>
    <div class="piege">Politique monétaire = compétence exclusive de la BCE. Politique budgétaire = reste nationale mais encadrée par le PSC (-3% / 60%).</div>
  </div>
</div>

  <div class="page-footer">Thème 4 · DCG UE5 · <button onclick="goHome()" style="background:none;border:none;color:#4a1a6e;cursor:pointer;font-size:1em;">← Retour à l'accueil</button></div>
</div>


<!-- ══════════════════════════════════════════ -->
<!-- PAGE : THÈME 5 -->
<!-- ══════════════════════════════════════════ -->
<div class="page" id="page-t5">
  <div class="theme-cover tc-t5">
    <div class="tc-num">Thème 5</div>
    <h2>La croissance économique : origines et enjeux</h2>
    <p>Dossiers 12 à 13 · Cycles, développement, facteurs de production, progrès technique</p>
  </div>

<div class="fiche d12" id="d12">
  <div class="fiche-header" onclick="openModal('d12')"><div class="num">Dossier 12 – Séquence 12</div><h2>La croissance économique doit-elle être systématiquement recherchée ?</h2></div>
  <div class="fiche-body">
    <div class="section-title olive">1. Définir et mesurer la croissance</div>
    <div class="def-box olive">La <strong>croissance économique</strong> désigne l'augmentation soutenue et durable de la production (PIB réel) d'un pays sur une longue période. <span class="auteur">François Perroux</span> (économiste français) insiste sur le caractère "soutenu" (pas un simple rebond temporaire) et "durable" (sur plusieurs années).</div>
    <div class="formule olive">Taux de croissance du PIB réel = (PIB(année t) – PIB(année t-1)) / PIB(année t-1) × 100</div>
    <p>La <strong>croissance extensive</strong> = on utilise plus de facteurs (embauche de travailleurs supplémentaires, construction d'usines). La <strong>croissance intensive</strong> = on utilise mieux les facteurs (robots, formation, innovations). Les pays développés comme la France misent surtout sur la croissance intensive car leur population vieillit.</p>
    <p>La <strong>croissance potentielle</strong> est le niveau de croissance qu'on peut atteindre sans créer d'inflation (utilisation optimale des ressources sans tensions). La <strong>croissance effective</strong> est ce qu'on observe réellement. L'<strong>output gap</strong> = différence entre les deux.</p>
    <div class="exemple">En 2020, le PIB français a chuté de −7,8% à cause du Covid (croissance effective). La croissance potentielle était estimée à +1,1%. L'output gap était donc de −8,9% : des capacités de production énormes étaient inutilisées (usines à l'arrêt, travailleurs en chômage partiel).</div>

    <div class="section-title olive">2. Les cycles économiques : l'économie ne croît pas en ligne droite</div>
    <p>L'économie passe par des phases successives, comme des vagues :</p>
    <table class="mini-table olive">
      <tr><th>Phase</th><th>Ce qui se passe</th><th>Exemples historiques</th></tr>
      <tr><td><strong>Expansion</strong></td><td>Croissance ↑, chômage ↓, entreprises investissent</td><td>Trente Glorieuses (1945-1973), bulle internet (1995-2000)</td></tr>
      <tr><td><strong>Crise</strong></td><td>Retournement brutal : bulle qui éclate, choc extérieur</td><td>Krach de 1929, crise des subprimes 2008, Covid 2020</td></tr>
      <tr><td><strong>Récession</strong></td><td>PIB négatif pendant ≥ 2 trimestres consécutifs</td><td>−2,9% en France en 2009, −7,8% en 2020</td></tr>
      <tr><td><strong>Dépression</strong></td><td>Récession prolongée + déflation (prix qui baissent) + faillites en cascade</td><td>Grande Dépression 1929-1939 aux États-Unis</td></tr>
      <tr><td><strong>Reprise</strong></td><td>Croissance redevient positive, l'économie redémarre</td><td>+6,8% en France en 2021 (rebond post-Covid)</td></tr>
    </table>
    <p>Des économistes ont identifié des cycles réguliers selon leur durée : <strong>Kitchin</strong> (3-4 ans, lié aux variations de stocks), <strong>Juglar</strong> (8-10 ans, lié à l'investissement), <strong>Kuznets</strong> (15-25 ans, lié à la construction), <strong>Kondratiev</strong> (40-60 ans, lié aux grappes d'innovations technologiques — vapeur, électricité, informatique, IA ?).</p>
    <div class="def-box olive"><strong>Stagnation séculaire :</strong> certains économistes pensent que les pays développés sont entrés dans une période de faible croissance structurelle. <span class="auteur">Larry Summers</span> : insuffisance chronique de demande (les riches épargnent trop). <span class="auteur">Robert Gordon</span> : ralentissement de l'innovation (les grandes inventions du XXe siècle, eau courante, électricité, ne se reproduiront peut-être pas). <span class="auteur">Ben Bernanke</span> : excès mondial d'épargne des pays émergents qui maintient les taux d'intérêt très bas.</div>

    <div class="section-title olive">3. Croissance vs développement : deux notions à bien distinguer</div>
    <p>La <strong>croissance</strong> est purement quantitative : ↑ du PIB. Le <strong>développement</strong> est qualitatif : transformation structurelle durable de la société (meilleures infrastructures, éducation, santé, institutions).</p>
    <div class="exemple"><span class="auteur">Walt Rostow (1960)</span>, économiste américain, décrit 5 étapes universelles du développement : société traditionnelle (agriculture) → conditions préalables au décollage (infrastructures, alphabétisation) → décollage (<em>take-off</em>, industrialisation rapide) → marche vers la maturité → ère de la consommation de masse. La Corée du Sud a parcouru ces 5 étapes en 40 ans (1960-2000) — un record historique.</div>
    <div class="exemple"><span class="auteur">Akamatsu</span> (théorie du <strong>vol d'oies sauvages</strong>) : dans les années 1960, le Japon produisait des textiles bon marché exportés partout. Quand le Japon est monté en gamme vers l'électronique, la Corée a pris le relais pour les textiles. Quand la Corée est montée vers les semi-conducteurs, la Chine a pris le relais. Maintenant le Vietnam et le Bangladesh prennent le relais de la Chine. Les pays se passent le flambeau comme des oies qui volent en V.</div>

    <div class="section-title olive">4. Le développement humain : l'IDH d'Amartya Sen</div>
    <p><span class="auteur">Amartya Sen</span> (Prix Nobel 1998, D4) : le développement = "expansion des libertés réelles des individus" — pas juste des revenus. L'<strong>IDH</strong> (créé avec le PNUD en 1990) combine 3 dimensions :</p>
    <table class="mini-table olive">
      <tr><th>Dimension</th><th>Indicateur</th><th>Exemple : France vs Niger</th></tr>
      <tr><td>Santé</td><td>Espérance de vie à la naissance</td><td>France : 83 ans · Niger : 62 ans</td></tr>
      <tr><td>Éducation</td><td>Années de scolarisation moyennes</td><td>France : 11,4 ans · Niger : 2,3 ans</td></tr>
      <tr><td>Niveau de vie</td><td>RNB/hab en PPA (USD)</td><td>France : 43 510$ · Niger : 1 360$</td></tr>
    </table>
    <p>IDH de la France : <strong>0,910</strong> (rang 28 mondial, 2021). IDH du Niger : <strong>0,394</strong> (dernier rang). La courbe de <strong>Kuznets</strong> (économiste américain) montre que les inégalités augmentent au début du développement, puis baissent avec l'émergence d'une classe moyenne — comme un "U renversé".</p>

    <div class="section-title olive">5. Le développement durable : croître sans détruire la planète</div>
    <div class="def-box olive">« Un développement qui répond aux besoins du présent sans compromettre la capacité des générations futures à répondre aux leurs. » <span class="auteur">Rapport Brundtland, Commission des Nations Unies, 1987</span></div>
    <p>3 piliers interdépendants : économique (croître) + social (équité) + environnemental (préserver). <span class="auteur">John Elkington</span> les a formalisés dans la <strong>Triple Bottom Line (TBL)</strong> ou "People, Planet, Profit" — un cadre pour mesurer la performance durable d'une entreprise.</p>
    <table class="mini-table olive">
      <tr><th>Vision de la soutenabilité</th><th>Ce qu'elle dit</th><th>Représentant</th></tr>
      <tr><td><strong>Soutenabilité faible</strong></td><td>Le capital naturel (forêts, pétrole) peut être remplacé par du capital technologique (panneaux solaires, innovation). On peut détruire des ressources si on crée de la technologie en échange.</td><td><span class="auteur">Solow</span> (Prix Nobel 1987)</td></tr>
      <tr><td><strong>Soutenabilité forte</strong></td><td>Certaines ressources naturelles sont irremplaçables (biodiversité, eau douce, stabilité climatique). On ne peut PAS les substituer par la technologie. Il faut les préserver absolument.</td><td>Économistes écologiques (Daly, Costanza)</td></tr>
    </table>
    <div class="exemple">Le déforestation en Amazonie : vue sous l'angle de la soutenabilité faible, si les recettes des exportations de soja financent des innovations propres, c'est acceptable. Vue sous l'angle de la soutenabilité forte, détruire la forêt amazonienne (poumon de la planète) est irréversible — aucune technologie ne la remplacera.</div>
    <div class="piege">3 distinctions essentielles à l'examen : <strong>croissance</strong> (↑ quantitative du PIB) ≠ <strong>développement</strong> (transformation qualitative durable des sociétés) ≠ <strong>développement durable</strong> (qui ne compromet pas les générations futures). Et soutenabilité <strong>faible</strong> (capital naturel substituable) ≠ <strong>forte</strong> (capital naturel irremplaçable).</div>
  </div>
</div>

<div class="fiche d13" id="d13">
  <div class="fiche-header" onclick="openModal('d13')"><div class="num">Dossier 13 – Séquence 13</div><h2>Qu'est-ce qui détermine le potentiel de croissance ?</h2></div>
  <div class="fiche-body">
    <div class="section-title cerulean">1. Les facteurs classiques de production</div>
    <p>La croissance repose sur la combinaison de 3 facteurs de production classiques : le <strong>travail</strong> (la main-d'œuvre), le <strong>capital physique</strong> (machines, usines, infrastructures) et les <strong>ressources naturelles</strong>. Mais comment chaque pays les mobilise-t-il ?</p>
    <table class="mini-table cerulean">
      <tr><th>Pays</th><th>Stratégie de croissance</th><th>Résultat</th></tr>
      <tr><td><strong>Chine (1980-2010)</strong></td><td>Quantité : main-d'œuvre abondante et bon marché + accumulation massive de capital (usines partout)</td><td>Croissance extensive de +10%/an pendant 30 ans. Mais épuisement du modèle quand les salaires ont augmenté.</td></tr>
      <tr><td><strong>Allemagne</strong></td><td>Qualité : formation professionnelle en alternance (Ausbildung), capital technique de très haute qualité, innovation</td><td>Exportations de machines-outils et voitures premium qui résistent mieux à la concurrence des pays émergents.</td></tr>
      <tr><td><strong>Norvège</strong></td><td>Ressources naturelles + intelligence : revenus du pétrole versés dans un fonds souverain (1 600 Mds€), investis dans les énergies renouvelables</td><td>L'un des plus hauts niveaux de vie au monde, ET préparation à l'après-pétrole.</td></tr>
    </table>

    <div class="section-title cerulean">2. Le capital humain : l'éducation comme investissement</div>
    <div class="def-box cerulean">Le <strong>capital humain</strong> désigne l'ensemble des connaissances, compétences, qualifications et état de santé incorporés à un individu. Comme le capital physique (machines), il s'accumule par l'investissement (formation) et se déprécie (connaissances obsolètes).</div>
    <div class="auteur" style="display:block;background:#e8f5fd;padding:12px 16px;border-radius:6px;margin:12px 0;font-size:0.95em;color:#054a6e">
      <strong>Qui sont Schultz et Becker ?</strong> <span class="auteur">Theodore Schultz</span> (Prix Nobel 1979) a été le premier à théoriser l'éducation comme investissement productif en analysant l'agriculture américaine. <span class="auteur">Gary Becker</span> (Prix Nobel 1992) a généralisé l'idée : dans son livre <em>Human Capital</em> (1964), il montre que chaque individu arbitre entre les coûts de la formation (dépenses, années de salaire sacrifié) et les bénéfices attendus (salaires plus élevés tout au long de la vie).
    </div>
    <div class="exemple">Faire le DCG coûte entre 5 000 et 15 000€ en frais de formation, plus les années de revenus inférieurs à ce que tu gagnerais avec un emploi. Mais un cadre comptable gagne en moyenne 20-30% de plus qu'un employé sans qualification supérieure. En 10-15 ans, l'investissement formation est rentabilisé. C'est exactement le raisonnement de Becker.</div>

    <div class="section-title cerulean">3. Malthus et Ricardo : les pessimistes historiques</div>
    <p>Au XIXe siècle, deux économistes ont montré que la croissance se heurtait à des limites naturelles incontournables :</p>
    <div class="def-box cerulean">
      <strong><span class="auteur">Thomas Malthus</span> (1798, <em>Essai sur le principe de population</em>) :</strong><br>
      La population croît de façon <strong>géométrique</strong> (1, 2, 4, 8, 16…) car chaque couple peut avoir plusieurs enfants. Mais la production alimentaire ne croît qu'<strong>arithmétiquement</strong> (1, 2, 3, 4, 5…) car les terres cultivables sont limitées. Résultat inévitable : famines, épidémies ou guerres qui régulent la population. Malthus était profondément pessimiste sur l'avenir de l'humanité.
    </div>
    <div class="def-box cerulean">
      <strong><span class="auteur">David Ricardo</span> (1817, <em>Principes de l'économie politique et de l'impôt</em>) :</strong><br>
      Loi des <strong>rendements décroissants</strong> : les agriculteurs exploitent d'abord les meilleures terres. Quand la population augmente, ils sont obligés de cultiver des terres moins fertiles → chaque unité de travail supplémentaire produit moins → la <strong>rente foncière</strong> (revenus des propriétaires terriens) augmente et capte une part croissante de la richesse → les profits des entrepreneurs baissent → ils investissent moins → la croissance freine.
    </div>
    <div class="exemple">Malthus avait tort pour les pays développés (la révolution verte, les engrais et l'agriculture intensive ont multiplié les rendements par 5 au XXe siècle). Mais il a peut-être raison pour les ressources naturelles non alimentaires : le pétrole, les minerais rares (lithium, cobalt) suivent bien ses lois.</div>

    <div class="section-title cerulean">4. La PGF : la magie du progrès technique</div>
    <div class="def-box cerulean">La <strong>Productivité Globale des Facteurs (PGF)</strong> = la part de la croissance économique qui ne s'explique PAS par l'augmentation du travail ni du capital. C'est le "résidu de Solow" : ce qu'on ne sait pas expliquer, et qu'on attribue au progrès technique, à l'amélioration de l'organisation, à la diffusion des innovations.</div>
    <div class="auteur" style="display:block;background:#e8f5fd;padding:12px 16px;border-radius:6px;margin:12px 0;font-size:0.95em;color:#054a6e">
      <strong>Qui est Robert Solow ?</strong> Économiste américain (1924-2023), Prix Nobel 1987. Il a développé le modèle de croissance exogène le plus utilisé. En étudiant la croissance américaine 1909-1949, il a montré que seulement 1/8 de la croissance s'expliquait par l'augmentation des facteurs de production. Les 7/8 restants = le "résidu" = ce qu'il a attribué au progrès technique (mais sans expliquer d'où il venait — d'où le qualificatif "exogène" = tombé du ciel).
    </div>
    <div class="def-box cerulean"><strong>Paradoxe de Solow (1987) :</strong> Malgré les investissements massifs dans les ordinateurs et l'informatique depuis les années 1970, la productivité du travail a paradoxalement RALENTI dans les statistiques. Solow écrivait : "On voit des ordinateurs partout, sauf dans les statistiques de la productivité." Explication : les effets du PT sont différés — il faut du temps pour réorganiser les entreprises, former les salariés, et que les gains se matérialisent dans les chiffres. Les gains de productivité des TIC sont finalement apparus dans les années 1990.</div>

    <div class="section-title cerulean">5. Schumpeter vs Aghion : deux visions de l'innovation</div>
    <p>Comment le progrès technique génère-t-il de la croissance ? Deux grandes visions s'affrontent :</p>
    <table class="mini-table cerulean">
      <tr><th>Auteur</th><th>Sa vision de l'innovation</th><th>Exemple</th></tr>
      <tr><td><span class="auteur">Schumpeter</span> (1883-1950), autrichien</td><td>Innovation <strong>DISCONTINUE par grappes</strong> : une grande innovation (vapeur, électricité, internet) génère une grappe d'innovations complémentaires et tire la croissance pendant 40-60 ans. Puis ralentissement jusqu'à la prochaine vague.</td><td>Internet (1995) → e-commerce → smartphones → réseaux sociaux → IA. Toute une grappe d'innovations liées qui tire la croissance depuis 30 ans.</td></tr>
      <tr><td><span class="auteur">Aghion & Howitt</span> (1992), Aghion franco-américain</td><td>Innovation <strong>CONTINUE "étape par étape"</strong> : chaque innovation améliore progressivement la précédente. Pas de grandes ruptures, mais une amélioration graduelle permanente.</td><td>Chaque nouvel iPhone est une petite amélioration du précédent. Tesla améliore ses batteries de quelques % chaque année.</td></tr>
    </table>
    <p><strong>Ce qu'ils ont en commun :</strong> le progrès technique est <strong>endogène</strong> (il résulte de décisions économiques) et la <strong>concurrence est un moteur de l'innovation</strong> (les entreprises innovent pour conquérir ou protéger leur rente de monopole temporaire).</p>
    <div class="exemple">Nokia dominait le marché des téléphones (position de monopole). Apple a innové avec l'iPhone en 2007 → destruction créatrice : Nokia a perdu 90% de sa valeur en 5 ans, mais des millions de nouveaux emplois ont été créés dans l'écosystème des apps mobiles. À long terme, le niveau de vie a augmenté. C'est Schumpeter à l'état pur.</div>

    <div class="section-title cerulean">6. Synthèse : comment stimuler la croissance à long terme ?</div>
    <table class="mini-table cerulean">
      <tr><th>Théoricien</th><th>Moteur de croissance</th><th>Politique recommandée</th></tr>
      <tr><td><span class="auteur">Malthus / Ricardo</span></td><td>Pessimistes : limites naturelles insurmontables</td><td>Contrôle démographique, libre-échange pour accéder aux ressources</td></tr>
      <tr><td><span class="auteur">Solow</span></td><td>Progrès technique exogène (non expliqué)</td><td>Créer un environnement de marché favorable</td></tr>
      <tr><td><span class="auteur">Schumpeter</span></td><td>Destruction créatrice par grappes d'innovations</td><td>Protéger l'innovation via les brevets, financer les start-ups</td></tr>
      <tr><td><span class="auteur">Lucas / Romer / Barro</span></td><td>Capital humain, connaissance, infrastructures</td><td>Investir dans l'éducation (Lucas), la R&D (Romer), les autoroutes/numérique (Barro)</td></tr>
      <tr><td><span class="auteur">Aghion & Howitt</span></td><td>Innovation continue + concurrence</td><td>Maintenir la concurrence sur les marchés, financer la recherche</td></tr>
    </table>
    <div class="piege">Progrès technique ≠ Innovation au sens de Schumpeter. PT = toute amélioration des techniques (large). Innovation = application commerciale d'une invention qui se diffuse dans l'économie. Et <strong>résidu de Solow = PGF</strong> = part de la croissance non expliquée par travail + capital. Ces 3 termes sont souvent mélangés à l'examen.</div>
  </div>
</div>

  <div class="page-footer">Thème 5 · DCG UE5 · <button onclick="goHome()" style="background:none;border:none;color:#1e4a12;cursor:pointer;font-size:1em;">← Retour à l'accueil</button></div>
</div>


<!-- ══════════════════════════════════════════ -->
<!-- PAGE : MÉTHODE -->
<!-- ══════════════════════════════════════════ -->
<div class="page" id="page-tm">
  <div class="theme-cover tc-tm">
    <div class="tc-num">Méthode</div>
    <h2>Fiches Méthode</h2>
    <p>Analyser un graphique · Verbes directeurs · Repères historiques</p>
  </div>

<div class="fiche dm" id="methode">
  <div class="fiche-header"><div class="num">Fiches Méthode</div><h2>Analyser un graphique & Comprendre les verbes directeurs</h2></div>
  <div class="fiche-body">
    <div class="section-title red">Méthode : Analyser un graphique en 3 étapes</div>
    <p><strong>Étape 1 – Identifier l'environnement.</strong> Lisez le titre (c'est le sujet), la source et la date, repérez le type de graphique (courbe, histogramme, camembert) et notez les variables et leur unité de mesure (%, €, millions…).</p>
    <p><strong>Étape 2 – Analyser le graphique.</strong> Identifiez la tendance générale (ça monte ou ça descend ?) puis repérez les évolutions particulières importantes : ruptures, pics, creux.</p>
    <p><strong>Étape 3 – Rédiger la réponse.</strong> Présentez la tendance générale en citant source, date et variables. Puis approfondissez en expliquant les causes et mécanismes économiques avec vos connaissances de cours.</p>
    <div class="highlight"><strong>Vocabulaire essentiel :</strong> Une courbe croît / décroît / fluctue. Deux courbes sont <strong>corrélées positivement</strong> si elles évoluent dans le même sens, <strong>négativement</strong> si elles s'opposent. Si une donnée passe de 30% à 15%, elle diminue de <strong>15 points de pourcentage</strong> (pas de 15%). Ne jamais écrire qu'une donnée "évolue" sans préciser dans quel sens.</div>

    <div class="section-title red">Les verbes directeurs à l'examen</div>
    <table class="mini-table red">
      <tr><th>Verbe</th><th>Ce qu'on attend</th><th>Structure conseillée</th></tr>
      <tr><td>Repérer / Relever</td><td>Trouver une information dans les documents</td><td>Définir → Présenter l'info → Conclure</td></tr>
      <tr><td>Expliquer</td><td>Rendre clair un mécanisme</td><td>Définir → Décomposer → Illustrer → Conclure</td></tr>
      <tr><td>Caractériser</td><td>Donner les caractéristiques d'un phénomène</td><td>Définir → 1 caractéristique = 1 paragraphe → Conclure</td></tr>
      <tr><td>Montrer / Démontrer</td><td>Prouver une vérité</td><td>Définir → Expliquer → Illustrer avec preuves → Conclure</td></tr>
      <tr><td>Analyser</td><td>Étude approfondie (objectifs, résultats, limites)</td><td>Définir → Objectifs → Résultats → Limites → Conclure</td></tr>
      <tr><td>Comparer</td><td>Points communs ET différences</td><td>Définir les deux → Convergences → Divergences → Conclure</td></tr>
      <tr><td>Distinguer</td><td>Montrer les différences</td><td>Définir → Différence(s) → Illustrer → Conclure</td></tr>
      <tr><td>Justifier</td><td>Donner des arguments et preuves</td><td>Définir → Arguments illustrés → Conclure</td></tr>
      <tr><td>Apprécier / Évaluer</td><td>Porter un jugement fondé sur des critères</td><td>Critères → Évaluation structurée → Conclure</td></tr>
    </table>
    <div class="piege">Quel que soit le verbe directeur, commencez TOUJOURS par définir la notion clé. Une réponse sans définition est incomplète aux yeux du correcteur.</div>

    <div class="section-title red">Repères historiques utiles pour les graphiques</div>
    <table class="mini-table red">
      <tr><th>Événement</th><th>Ce qu'il faut savoir</th></tr>
      <tr><td>Crise de 1929</td><td>Krach de Wall Street → Grande Dépression → intervention forte de l'État</td></tr>
      <tr><td>Trente Glorieuses (1945-1973)</td><td>Forte croissance dans les pays développés, plein emploi, construction de l'État-providence</td></tr>
      <tr><td>Chocs pétroliers 1973 et 1979</td><td>Hausse du pétrole → baisse de la croissance → montée du chômage structurel</td></tr>
      <tr><td>Années 1980</td><td>Déréglementation financière, désintermédiation, montée des marchés financiers (3D)</td></tr>
      <tr><td>Traité de Maastricht 1992</td><td>UEM, critères de convergence (-3% déficit, 60% dette), préparation de l'euro</td></tr>
      <tr><td>Adoption de l'euro 1999-2002</td><td>Monnaie unique européenne, perte de la souveraineté monétaire nationale</td></tr>
      <tr><td>Crise des subprimes 2007-2008</td><td>Crise financière mondiale née aux États-Unis → récession mondiale → réforme Bâle III</td></tr>
      <tr><td>Crise des dettes souveraines 2010-12</td><td>Grèce, Espagne, Portugal en difficulté → austérité imposée par la Commission européenne</td></tr>
      <tr><td>Covid-19 2020</td><td>Paralysie économique mondiale, plan NextGenerationEU, première dette commune européenne</td></tr>
      <tr><td>Inflation 2021-2023</td><td>Reprise post-Covid + guerre Ukraine → hausse des prix de l'énergie → remontée des taux BCE</td></tr>
    </table>
  </div>
</div>

  <div class="page-footer">Méthode · DCG UE5 · <button onclick="goHome()" style="background:none;border:none;color:#922b21;cursor:pointer;font-size:1em;">← Retour à l'accueil</button></div>
</div>

<!-- ══════════════════════════════════════════ -->
<!-- JAVASCRIPT NAVIGATION -->
<!-- ══════════════════════════════════════════ -->
<script>
// ── MODAL DATA ──────────────────────────────
const DOSSIERS = {
  d1: {
    num: 'Dossier 1 · Thème 1', color: '#2d6a9f', bg: '#e8f4fd',
    title: "L'économie, science de la rareté",
    summary: "L'économie est la science qui étudie comment des ressources limitées sont utilisées pour satisfaire des besoins potentiellement illimités. Face à cette contrainte de rareté, chaque agent doit faire des choix : choisir une option, c'est renoncer à une autre (coût d'opportunité). Ce problème fondamental s'est accentué depuis la sortie de la Covid-19 avec le retour d'une économie de rareté (tensions sur l'énergie, les semi-conducteurs, les matières premières).",
    theories: [
      { name: "Malinvaud (1986)", desc: "Définition de l'économie comme science de l'allocation de ressources rares entre des besoins illimités." },
      { name: "Maslow", desc: "Pyramide des besoins en 5 niveaux : physiologiques → sécurité → appartenance → estime → accomplissement de soi." },
      { name: "Artus & Pastré", desc: "Concept d'économie de rareté : retour après 20 ans d'abondance, imposant sobriété et résilience." }
    ],
    keywords: ["Rareté","Besoins illimités","Ressources limitées","Coût d'opportunité","Allocation des ressources","Biens libres","Biens économiques","Arbitrage","Pyramide de Maslow"]
  },
  d2: {
    num: 'Dossier 2 · Thème 1', color: '#27ae60', bg: '#eaf7f0',
    title: "Qu'est-ce que l'activité économique ?",
    summary: "L'activité économique repose sur des échanges entre 6 agents économiques (ménages, SNF, SF, État, ISBLSM, reste du monde), chacun avec un rôle précis. Les ménages consomment (consommation finale vs effective) et épargnent selon leur revenu. L'investissement (FBCF) sert à maintenir ou développer la capacité de production. Tout ce qui est produit ou importé doit être utilisé : c'est l'équilibre ressources-emplois.",
    theories: [
      { name: "Keynes", desc: "La consommation dépend du revenu disponible courant. Une hausse de revenu entraîne une hausse de consommation, mais dans une moindre proportion (propension marginale à consommer < 1)." },
      { name: "Friedman", desc: "Théorie du revenu permanent : les ménages consomment selon ce qu'ils estiment gagner sur toute leur vie, pas selon leur revenu du moment." },
      { name: "Modigliani", desc: "Théorie du cycle de vie : on emprunte jeune, on épargne pendant la vie active, on désépargne à la retraite." },
      { name: "Loi d'Engel (1857)", desc: "Avec la hausse du revenu, la part des dépenses alimentaires diminue et celle des loisirs/transports augmente." },
      { name: "Paradoxe de l'épargne", desc: "Si tous les agents épargnent simultanément, la demande globale chute → récession → les revenus baissent → on épargne au final moins qu'avant." }
    ],
    keywords: ["Agents économiques","Consommation finale","Consommation effective","ISBLSM","Épargne","FBCF","Investissement de capacité","Investissement de remplacement","Revenu permanent","Cycle de vie","Paradoxe de l'épargne","Équilibre ressources-emplois"]
  },
  d3: {
    num: 'Dossier 3 · Thème 1', color: '#e67e22', bg: '#fdf3e8',
    title: "Comment l'activité économique crée-t-elle de la richesse ?",
    summary: "La richesse créée par une entreprise se mesure par la Valeur Ajoutée (VA = CA – CI). La VA est ensuite répartie entre les différents acteurs : salariés (~63%), actionnaires, banques, État, et l'entreprise elle-même. La somme des VA de toutes les entreprises permet d'obtenir le PIB. L'économie est divisée en 3 secteurs (primaire, secondaire, tertiaire) et inclut l'ESS qui vise une performance économique ET sociale.",
    theories: [
      { name: "Colin Clark (1947)", desc: "Découpage de l'économie en 3 secteurs : primaire (exploitation des ressources), secondaire (industrie, transformation), tertiaire (services). Le tertiaire représente aujourd'hui ~80% du PIB en France." },
      { name: "Répartition primaire / secondaire", desc: "Répartition primaire = partage de la VA avant intervention de l'État. Répartition secondaire = redistribution via impôts, cotisations et allocations." }
    ],
    keywords: ["Valeur Ajoutée (VA)","Consommations intermédiaires (CI)","Chiffre d'affaires","EBE","Répartition primaire","Répartition secondaire","Secteur primaire","Secteur secondaire","Secteur tertiaire","ESS","Coopérative","Mutuelle","Triple Bottom Line"]
  },
  d4: {
    num: 'Dossier 4 · Thème 1', color: '#8e44ad', bg: '#f3e8fd',
    title: "Comment rendre compte de la situation économique d'un pays ?",
    summary: "Le PIB est l'indicateur principal de la richesse créée sur un territoire. Il peut être calculé de 3 façons (par l'offre, la demande et les revenus). Mais le PIB a des limites importantes : il ne mesure pas le bien-être, ignore le travail domestique et le bénévolat, et comptabilise positivement des activités néfastes. Des indicateurs alternatifs comme l'IDH tentent de dépasser ces limites en intégrant des dimensions qualitatives.",
    theories: [
      { name: "PIB – 3 approches", desc: "Offre : Σ VA + TVA + droits de douane. Demande : C + I + ΔS + (X–M). Revenus : Salaires + (Impôts – Subventions) + EBE." },
      { name: "Amartya Sen / PNUD (1990)", desc: "Indice de Développement Humain (IDH) : combine espérance de vie, niveau d'éducation et PIB/hab en PPA. Dépasse la mesure purement monétaire du développement." },
      { name: "Paradoxe d'Easterlin", desc: "Au-delà d'un certain seuil de richesse, l'augmentation du PIB ne correspond plus à une augmentation du bonheur ressenti." },
      { name: "Commission Stiglitz-Sen-Fitoussi (2009)", desc: "Rapport recommandant d'aller au-delà du PIB pour mesurer le bien-être : qualité de vie, soutenabilité environnementale, inégalités." }
    ],
    keywords: ["PIB","PIB en volume","PIB en valeur","PPA","Taux de croissance","IDH","IDHP","Better Life Index","Épargne Nette Ajustée","Externalités","Paradoxe d'Easterlin","Travail domestique","Bénévolat"]
  },
  d5: {
    num: 'Dossier 5 · Thème 2', color: '#16a085', bg: '#e8f8f5',
    title: "L'économie de marché : fonctionnement, concurrence et modèles",
    summary: "Le marché est le mécanisme central de l'économie libérale : l'offre et la demande se confrontent pour aboutir à un prix d'équilibre. Le modèle théorique idéal est la Concurrence Pure et Parfaite (CPP) avec 5 conditions. En pratique, la concurrence est imparfaite. Les économistes proposent des visions dynamiques de la concurrence : la destruction créatrice (Schumpeter), la concurrence comme signal (Hayek) ou la menace d'entrée (Baumol).",
    theories: [
      { name: "Adam Smith (1776)", desc: "La 'main invisible' : chaque individu, en poursuivant son intérêt personnel, contribue involontairement au bien-être collectif via le mécanisme des prix." },
      { name: "CPP – Walras & Pareto", desc: "5 conditions : atomicité, homogénéité, libre entrée/sortie, mobilité des facteurs, transparence de l'information. Mène à un optimum de Pareto." },
      { name: "Schumpeter", desc: "Destruction créatrice : l'innovation rend obsolètes les activités existantes tout en créant de nouvelles activités plus productives. Moteur du capitalisme." },
      { name: "Hayek", desc: "La concurrence comme processus de découverte : les prix coordonnent des millions de décisions sans autorité centrale, révélant une information dispersée." },
      { name: "Baumol", desc: "Marchés contestables : même avec peu d'acteurs, la simple menace d'entrée de concurrents suffit à discipliner les comportements et les prix." }
    ],
    keywords: ["Marché","Prix d'équilibre","CPP","Atomicité","Homogénéité","Libre entrée","Mobilité des facteurs","Transparence","Optimum de Pareto","Main invisible","Destruction créatrice","Marchés contestables","Concurrence imparfaite"]
  },
  d6: {
    num: 'Dossier 6 · Thème 2', color: '#c0392b', bg: '#fdecea',
    title: "Pourquoi encadrer le fonctionnement du marché ?",
    summary: "Le marché peut défaillir de deux façons. D'abord par la concurrence imparfaite : certaines entreprises ont un pouvoir de marché (monopole, oligopole) qu'elles peuvent abuser (abus de position dominante, ententes). Ensuite par des défaillances structurelles : les biens publics (non-rivaux et non-excluables) et les externalités (effets sur des tiers non compensés) ne peuvent pas être correctement gérés par le marché seul. L'État et des autorités de régulation interviennent pour corriger ces situations.",
    theories: [
      { name: "Paul Samuelson (1954)", desc: "Définition des biens publics purs : non-rivalité (la conso par un agent n'empêche pas celle des autres) et non-exclusion (impossible d'empêcher quelqu'un d'en bénéficier)." },
      { name: "Arthur Pigou", desc: "Théorie des externalités : internalisation via taxes pigouviennes (externalités négatives) ou subventions (externalités positives) pour que les prix reflètent le coût social réel." },
      { name: "Digital Markets Act (DMA, 2023)", desc: "Règlement européen imposant des obligations aux géants du numérique (Google, Apple, Amazon, Meta, Microsoft, TikTok). Sanctions jusqu'à 10% du CA mondial." }
    ],
    keywords: ["Pouvoir de marché","Monopole","Oligopole","Concurrence monopolistique","Abus de position dominante","Entente","Auto-préférence","DMA","Autorité de la concurrence","Bien public","Non-rivalité","Non-exclusion","Passager clandestin","Externalité","Taxe pigouvienne"]
  },
  d7: {
    num: 'Dossier 7 · Thème 3', color: '#1a5276', bg: '#eaf2fb',
    title: "Quels agents ont un besoin ou une capacité de financement ?",
    summary: "Dans une économie, les agents qui épargnent plus qu'ils n'investissent (ménages, sociétés financières) financent ceux qui investissent plus qu'ils n'épargnent (entreprises, État). Le déficit public annuel (flux) s'accumule pour former la dette publique (stock). La France a une dette de 113% du PIB en 2024, bien au-dessus du seuil de Maastricht (60%). Les entreprises peuvent se financer de 6 façons : autofinancement, emprunt bancaire, augmentation de capital, obligations, crédit-bail, crowdfunding.",
    theories: [
      { name: "Friedman (1957) – Revenu permanent", desc: "Les ménages lissent leur consommation sur toute leur vie, pas seulement en fonction du revenu courant. Une hausse temporaire de revenu est surtout épargnée." },
      { name: "Ando & Modigliani (1963) – Cycle de vie", desc: "Le comportement d'épargne varie selon l'âge : endettement au début de la vie active, épargne en milieu de carrière, désépargne à la retraite." },
      { name: "Déficit ≠ Dette", desc: "Le déficit est un flux annuel (résultat d'une seule année). La dette est un stock qui accumule tous les déficits passés non remboursés." }
    ],
    keywords: ["Capacité de financement","Besoin de financement","Déficit public","Dette publique","OAT","Agence France Trésor","FBCF","Autofinancement","Emprunt bancaire","Augmentation de capital","Emprunt obligataire","Crédit-bail","Crowdfunding","Revenu permanent","Cycle de vie"]
  },
  d8: {
    num: 'Dossier 8 · Thème 3', color: '#b7770d', bg: '#fef9e7',
    title: "Rôles des banques et des marchés financiers dans le financement de l'économie",
    summary: "L'économie se finance par deux voies : la finance indirecte (les banques collectent l'épargne et accordent des crédits) et la finance directe (les entreprises émettent des titres sur les marchés). Les banques jouent 3 rôles essentiels : gestion des paiements, transformation des échéances et création monétaire. Depuis les années 1980, les 3D (désintermédiation, décloisonnement, déréglementation) ont renforcé les marchés financiers au détriment des banques, mais aussi fragilisé le système (crise 2008).",
    theories: [
      { name: "Création monétaire", desc: "Quand une banque accorde un crédit, elle crée de la monnaie scripturale ex nihilo. Cette monnaie disparaît quand l'emprunteur rembourse. 'Les crédits font les dépôts.'" },
      { name: "Bâle III", desc: "Accords internationaux imposant aux banques de détenir au minimum 8% de fonds propres par rapport à leurs engagements pour limiter la prise de risque excessive." },
      { name: "3D de Bourguignon", desc: "Désintermédiation (↓ rôle des banques), Décloisonnement (fusion des marchés financiers), Déréglementation (↓ contraintes sur les activités bancaires). Depuis les années 1980." }
    ],
    keywords: ["Finance directe","Finance indirecte","Intermédiation financière","Création monétaire","Monnaie scripturale","Transformation des échéances","Bâle III","Fonds propres","3D","Désintermédiation","Décloisonnement","Déréglementation","Liquidité","Bulle spéculative","Subprimes 2008"]
  },
  d9: {
    num: 'Dossier 9 · Thème 4', color: '#1e8449', bg: '#eafaf1',
    title: "Quels sont la place et le rôle de l'État ?",
    summary: "L'État a évolué de simple 'gendarme' (fonctions régaliennes) vers un 'État-providence' qui protège contre les risques sociaux. Musgrave identifie 3 fonctions : allocation des ressources, redistribution des richesses, stabilisation économique. Mais l'État-providence est en crise depuis les années 1980 : crise financière (coûts), crise d'efficacité (résultats) et crise de légitimité (confiance). La décentralisation (lois Defferre, 1982) a transféré des compétences vers les collectivités territoriales.",
    theories: [
      { name: "Richard Musgrave (1959)", desc: "3 fonctions de l'État : allocation (corriger les défaillances du marché), redistribution (réduire les inégalités via impôts et transferts), stabilisation (réguler les cycles économiques)." },
      { name: "Pierre Rosanvallon", desc: "Triple crise de l'État-providence : financière (coûts croissants), d'efficacité (résultats questionnés), de légitimité (perte de confiance des citoyens)." },
      { name: "Loi de Wagner", desc: "La part des dépenses publiques tend à augmenter avec le développement économique, en raison de la demande croissante de services collectifs." },
      { name: "Arthur Laffer", desc: "Courbe de Laffer en cloche : 'trop d'impôt tue l'impôt'. Au-delà d'un taux optimal, la hausse de la pression fiscale réduit les recettes." }
    ],
    keywords: ["Fonctions régaliennes","État-gendarme","État-providence","Sécurité sociale (1945)","Musgrave","Allocation","Redistribution","Stabilisation","Rosanvallon","Collectivités territoriales","Décentralisation","AAI","AMF","CNIL","Courbe de Laffer","Soutenabilité de la dette"]
  },
  d10: {
    num: 'Dossier 10 · Thème 4', color: '#ca6f1e', bg: '#fdf2e9',
    title: "Quelles politiques économiques l'État peut-il mener ?",
    summary: "L'État dispose de plusieurs leviers pour agir sur l'économie : la politique budgétaire (dépenses/recettes) et la politique monétaire (taux d'intérêt, via la BCE). Il choisit entre politiques conjoncturelles (court terme) et structurelles (long terme), entre politiques de demande (keynésiennes) et politiques d'offre (libérales). Chaque approche a ses avantages et ses limites : la relance keynésienne peut creuser le déficit, et les politiques d'offre ont des effets lents.",
    theories: [
      { name: "Nicholas Kaldor – Carré magique", desc: "4 objectifs souvent contradictoires : croissance, plein-emploi, stabilité des prix, équilibre extérieur. Plus le carré est grand, meilleure est la situation économique." },
      { name: "John Maynard Keynes", desc: "La demande effective détermine le niveau de production. En cas d'insuffisance de demande, l'État doit relancer par la dépense publique (multiplicateur keynésien)." },
      { name: "Multiplicateur keynésien", desc: "Un euro de dépense publique génère plus d'un euro de revenu supplémentaire dans l'économie, via les effets en chaîne de consommation." },
      { name: "Équivalence ricardienne (Lucas)", desc: "Si l'État s'endette, les ménages rationnels anticipent de futures hausses d'impôts et épargnent davantage, neutralisant l'effet de la relance." },
      { name: "Effet d'éviction (Friedman)", desc: "Les emprunts massifs de l'État sur les marchés font monter les taux d'intérêt, réduisant l'investissement privé." },
      { name: "Lucas, Romer, Barro – Croissance endogène", desc: "La croissance est auto-entretenue par le capital humain (Lucas), l'innovation (Romer) et les infrastructures productives (Barro)." }
    ],
    keywords: ["Carré magique","Politique conjoncturelle","Politique structurelle","Politique budgétaire","Politique monétaire","Politique de demande","Politique d'offre","Multiplicateur keynésien","Demande effective","Équivalence ricardienne","Effet d'éviction","Croissance endogène","Plan de relance","Austérité"]
  },
  d11: {
    num: 'Dossier 11 · Thème 4', color: '#5b4fcf', bg: '#eae8fd',
    title: "L'appartenance à l'UE influence-t-elle la politique économique des pays membres ?",
    summary: "L'intégration européenne est un processus progressif depuis le Traité de Rome (1957). Elle contraint les États membres en matière monétaire (la BCE gère la politique monétaire pour tous) et budgétaire (PSC : -3%/60%). En contrepartie, elle offre un marché unique de 450 millions de consommateurs, une stabilité monétaire et des mécanismes de solidarité. Le Brexit (2020) illustre les tensions entre intégration et souveraineté nationale.",
    theories: [
      { name: "Béla Balassa (1961)", desc: "Échelle de l'intégration régionale : zone de libre-échange → union douanière → marché commun → union économique → UEM → union politique." },
      { name: "Subsidiarité", desc: "L'UE n'intervient que si elle est plus efficace que les États membres. L'éducation, la fiscalité et la politique sociale restent nationales." },
      { name: "Proportionnalité", desc: "Même quand l'UE est compétente, elle doit limiter son action au strict nécessaire (directives-cadres plutôt que règlements uniformes)." },
      { name: "BCE & Quantitative Easing", desc: "Politique non conventionnelle : achats massifs d'obligations d'État pour injecter des liquidités quand les taux d'intérêt directeurs sont déjà proches de 0." },
      { name: "PSC (1997)", desc: "Pacte de Stabilité et de Croissance : déficit < 3% du PIB et dette < 60% du PIB. Règles souvent contournées (France en déficit > 3% depuis 2002)." }
    ],
    keywords: ["Traité de Rome (1957)","Balassa","Zone de libre-échange","Union douanière","Marché commun","UEM","BCE","Taux directeurs","QE","Quantitative Easing","PSC","Déficit < 3%","Dette < 60%","NextGenerationEU","Brexit","Subsidiarité","Proportionnalité","PAC","Fonds de cohésion"]
  },
  d12: {
    num: 'Dossier 12 · Thème 5', color: '#3a7d2c', bg: '#edf7e8',
    title: "La croissance économique doit-elle être systématiquement recherchée ?",
    summary: "La croissance économique désigne l'augmentation durable du PIB réel. Elle peut être extensive (plus de facteurs) ou intensive (meilleure productivité). L'écart entre croissance potentielle et effective (output gap) guide les politiques économiques. Mais la croissance soulève des questions : est-elle un bon indicateur de bien-être ? Est-elle compatible avec les limites planétaires ? La notion de développement durable tente de concilier croissance, équité sociale et préservation de l'environnement.",
    theories: [
      { name: "François Perroux", desc: "Définit la croissance comme une 'augmentation soutenue durant une ou plusieurs périodes longues' du PIB réel. La distingue du développement, plus qualitatif." },
      { name: "Rostow (1960) – Étapes du développement", desc: "5 étapes universelles : société traditionnelle → conditions préalables → décollage (take-off) → maturité → consommation de masse." },
      { name: "Akamatsu – Vol d'oies sauvages", desc: "Le développement suit un cycle : importer → produire → exporter. Quand un pays monte en gamme, un autre prend le relais dans les produits bas de gamme." },
      { name: "Amartya Sen – Développement humain", desc: "Le développement = expansion des libertés réelles. L'IDH (espérance de vie + éducation + niveau de vie) dépasse la seule mesure du PIB." },
      { name: "Rapport Brundtland (1987)", desc: "Développement durable : répondre aux besoins du présent sans compromettre ceux des générations futures. 3 piliers : économique, social, environnemental." },
      { name: "Stagnation séculaire (Summers/Gordon)", desc: "Théorie selon laquelle les économies avancées sont entrées dans une phase de faible croissance structurelle durable, liée à une insuffisance de demande ou au ralentissement de l'innovation." }
    ],
    keywords: ["Croissance économique","Croissance extensive","Croissance intensive","Croissance potentielle","Croissance effective","Output gap","Cycles économiques","Récession","Dépression","Kondratiev","Stagnation séculaire","Développement économique","IDH","Développement durable","TBL","Soutenabilité forte/faible","Rapport Brundtland"]
  },
  d13: {
    num: 'Dossier 13 · Thème 5', color: '#0b7aaa', bg: '#e8f5fd',
    title: "Qu'est-ce qui détermine le potentiel de croissance ?",
    summary: "La croissance économique repose sur les facteurs de production (travail, capital, ressources naturelles), mais aussi sur la façon dont ils sont mobilisés. Le capital humain (éducation, formation) est un investissement productif clé. Malthus et Ricardo ont montré les limites de la croissance fondée sur les seuls facteurs. La PGF mesure la part de la croissance inexpliquée par les facteurs : c'est essentiellement le progrès technique. Schumpeter et Aghion/Howitt montrent que l'innovation est le moteur principal de la croissance à long terme.",
    theories: [
      { name: "Theodore Schultz & Gary Becker", desc: "Capital humain : l'éducation et la formation sont des investissements productifs. Becker : l'individu arbitre coûts/bénéfices de la formation comme pour tout investissement." },
      { name: "Thomas Malthus (1798)", desc: "La population croît géométriquement, la production alimentaire arithmétiquement → pénuries inévitables si aucun frein. Vision pessimiste des limites de la croissance." },
      { name: "David Ricardo (1817)", desc: "Loi des rendements décroissants : chaque unité supplémentaire de facteur sur des terres moins fertiles produit de moins en moins. La rente foncière capte une part croissante de la VA." },
      { name: "Résidu de Solow / PGF", desc: "La part de la croissance non expliquée par l'augmentation du travail et du capital. Correspond essentiellement au progrès technique, difficile à mesurer directement." },
      { name: "Schumpeter – Destruction créatrice", desc: "L'innovation apparaît par grappes et remplace les activités obsolètes. Court terme : destructions d'emplois. Long terme : hausse de la productivité et du niveau de vie." },
      { name: "Aghion & Howitt – Croissance endogène", desc: "Le progrès technique est endogène (résulte des décisions de R&D). La concurrence pousse les entreprises à innover pour protéger leurs rentes. Innovation = processus continu étape par étape." }
    ],
    keywords: ["Facteurs de production","Capital humain","Schultz","Gary Becker","Rendements décroissants","Malthus","Ricardo","PGF","Résidu de Solow","Paradoxe de Solow","Progrès technique","Innovation","Destruction créatrice","Grappes d'innovations","Croissance endogène","Romer","Aghion","Malédiction des ressources","Acemoglu"]
  }
};

// colour overrides per dossier for theory badges
const THEORY_COLORS = {
  d1:'#2d6a9f',d2:'#27ae60',d3:'#e67e22',d4:'#8e44ad',
  d5:'#16a085',d6:'#c0392b',d7:'#1a5276',d8:'#b7770d',
  d9:'#1e8449',d10:'#ca6f1e',d11:'#5b4fcf',d12:'#3a7d2c',d13:'#0b7aaa'
};

// ── MODAL FUNCTIONS ──────────────────────────
function openModal(id) {
  const d = DOSSIERS[id];
  if (!d) return;
  const col = d.color;
  const header = document.getElementById('modalHeader');
  header.style.background = d.bg;
  header.style.borderColor = col;
  header.style.color = col;
  document.getElementById('modalDnum').textContent = d.num;
  document.getElementById('modalTitle').textContent = d.title;
  document.getElementById('modalSummary').style.borderLeftColor = col;
  document.getElementById('modalSummary').innerHTML = d.summary;

  // Theories
  const tc = THEORY_COLORS[id] || col;
  document.getElementById('modalTheories').innerHTML = d.theories.map(t =>
    `<div class="theory-item">
      <span class="theory-name" style="background:${tc}">${t.name}</span>
      <span class="theory-desc">${t.desc}</span>
    </div>`
  ).join('');

  // Keywords
  document.getElementById('modalKeywords').innerHTML = d.keywords.map(k =>
    `<span class="keyword" style="background:${col}18;border-color:${col}55;color:${col}">${k}</span>`
  ).join('');

  // Button
  const btn = document.getElementById('modalBtnFiche');
  btn.style.background = col;
  btn.onclick = () => { closeModal(); document.getElementById(id).scrollIntoView({ behavior:'smooth', block:'start' }); };

  document.getElementById('modalOverlay').classList.add('open');
  document.body.style.overflow = 'hidden';
}

function closeModal(e) {
  if (e && e.target !== document.getElementById('modalOverlay')) return;
  document.getElementById('modalOverlay').classList.remove('open');
  document.body.style.overflow = '';
}

document.addEventListener('keydown', e => { if (e.key === 'Escape') closeModal(); });


const navConfig = {
  't1': { title: 'Thème 1 – Fondements', links: [{href:'#d1',label:'D1'},{href:'#d2',label:'D2'},{href:'#d3',label:'D3'},{href:'#d4',label:'D4'}] },
  't2': { title: 'Thème 2 – Marché', links: [{href:'#d5',label:'D5'},{href:'#d6',label:'D6'}] },
  't3': { title: 'Thème 3 – Financement', links: [{href:'#d7',label:'D7'},{href:'#d8',label:'D8'}] },
  't4': { title: 'Thème 4 – Régulation publique', links: [{href:'#d9',label:'D9'},{href:'#d10',label:'D10'},{href:'#d11',label:'D11'}] },
  't5': { title: 'Thème 5 – Croissance', links: [{href:'#d12',label:'D12'},{href:'#d13',label:'D13'}] },
  'tm': { title: 'Fiches Méthode', links: [{href:'#methode',label:'Méthode'}] },
};

function showPage(pageId, title, key) {
  // Hide all pages
  document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
  // Show target page
  document.getElementById(pageId).classList.add('active');
  // Update & show navbar
  const nav = document.getElementById('mainNav');
  const navTitle = document.getElementById('navTitle');
  const navToc = document.getElementById('navToc');
  const cfg = navConfig[key.toLowerCase()];
  navTitle.textContent = cfg ? cfg.title : title;
  navToc.innerHTML = cfg ? cfg.links.map(l => `<a href="${l.href}" onclick="scrollToAnchor('${l.href}')">${l.label}</a>`).join('') : '';
  nav.classList.add('visible');
  // Scroll to top
  window.scrollTo({ top: 0, behavior: 'smooth' });
}

function goHome() {
  document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
  document.getElementById('page-home').classList.add('active');
  document.getElementById('mainNav').classList.remove('visible');
  window.scrollTo({ top: 0, behavior: 'smooth' });
}

function scrollToAnchor(href) {
  const id = href.replace('#', '');
  setTimeout(() => {
    const el = document.getElementById(id);
    if (el) el.scrollIntoView({ behavior: 'smooth', block: 'start' });
  }, 100);
}

// ══════════════════════════════════════════════
// MIND MAP ENGINE
// ══════════════════════════════════════════════
const MM = {
  t1: {
    title: "Thème 1 — Les fondements de l'activité économique",
    centerLabel: "Thème 1\nFondements", color: "#1e3a5f",
    angles: [220, 140, 320, 40],
    branches: [
      { label: "D1 · Rareté\n& Besoins", color: "#2d6a9f",
        items: ["Ressources rares\nvs besoins illimités","Coût d'opportunité","Pyramide de Maslow","Biens libres\nvs économiques"] },
      { label: "D2 · Activité\néconomique", color: "#27ae60",
        items: ["6 agents économiques","Conso finale\nvs effective","Épargne (Modigliani)","FBCF · Investissement"] },
      { label: "D3 · Création\nde richesse", color: "#e67e22",
        items: ["VA = CA – CI","Répartition VA\n(salariés ~63%)","3 secteurs (Clark)","ESS"] },
      { label: "D4 · PIB &\nIndicateurs", color: "#8e44ad",
        items: ["3 approches du PIB","PIB volume vs valeur","Limites du PIB","IDH (Sen / PNUD)"] }
    ]
  },
  t2: {
    title: "Thème 2 — L'économie de marché",
    centerLabel: "Thème 2\nMarché", color: "#0e6655",
    angles: [195, 355],
    branches: [
      { label: "D5 · Marché\n& Concurrence", color: "#16a085",
        items: ["Main invisible\n(Adam Smith)","CPP · 5 conditions","Destruction créatrice\n(Schumpeter)","Marchés contestables\n(Baumol)","Modèles libéral\nmixte · planifié"] },
      { label: "D6 · Encadrement\ndu marché", color: "#c0392b",
        items: ["Monopole · Oligopole","Pratiques\nanticoncurrentielles","DMA (2023)","Biens publics\n(Samuelson 1954)","Externalités (Pigou)"] }
    ]
  },
  t3: {
    title: "Thème 3 — Le financement de l'économie",
    centerLabel: "Thème 3\nFinancement", color: "#7d5a0a",
    angles: [195, 355],
    branches: [
      { label: "D7 · Besoin &\nCapacité finance.", color: "#1a5276",
        items: ["Ménages → capacité\n(épargne ~17%)","Entreprises → besoin","État → besoin\n(-5,8% PIB 2024)","Revenu permanent\n(Friedman)","6 modes de\nfinancement entreprises"] },
      { label: "D8 · Banques &\nMarchés financiers", color: "#b7770d",
        items: ["Finance directe\nvs indirecte","3 rôles des banques","Création monétaire\n(scripturale)","Bâle III (8% FP)","3D de Bourguignon"] }
    ]
  },
  t4: {
    title: "Thème 4 — La régulation publique",
    centerLabel: "Thème 4\nRégulation\npublique", color: "#4a1a6e",
    angles: [210, 150, 0],
    branches: [
      { label: "D9 · Rôle\nde l'État", color: "#1e8449",
        items: ["État-gendarme\nvs État-providence","3 fonctions Musgrave","Triple crise\n(Rosanvallon)","Collectivités\nterritoriales","Courbe de Laffer"] },
      { label: "D10 · Politiques\néconomiques", color: "#784212",
        items: ["Carré magique\n(Kaldor)","Conjoncturelle\nvs structurelle","Demande (Keynes)\nvs Offre","Multiplicateur\nkeynésien","Croissance endogène\n(Lucas, Romer, Barro)"] },
      { label: "D11 · Appartenance\nà l'UE", color: "#2d1b8e",
        items: ["Construction UE\n(Traité Rome 1957)","Niveaux intégration\n(Balassa)","Subsidiarité &\nproportionnalité","BCE & QE\n(objectif 2%)","PSC : -3% / 60%"] }
    ]
  },
  t5: {
    title: "Thème 5 — La croissance économique",
    centerLabel: "Thème 5\nCroissance", color: "#1e4a12",
    angles: [195, 355],
    branches: [
      { label: "D12 · Croissance\n& Développement", color: "#3a7d2c",
        items: ["Extensive vs intensive","Output gap","Cycles éco.\n(Kitchin, Kondratiev)","Stagnation séculaire\n(Summers, Gordon)","IDH (Sen / PNUD)","Dév. durable\n(Brundtland 1987)"] },
      { label: "D13 · Déterminants\ndu potentiel", color: "#0b7aaa",
        items: ["Capital humain\n(Schultz, Becker)","Malthus & Ricardo\n(limites)","PGF & paradoxe\nde Solow","Destruction créatrice\n(Schumpeter)","Croissance endogène\n(Romer, Aghion)"] }
    ]
  }
};

// ══════════════════════════════════════════════
// MIND MAP ENGINE — LIGHT THEME
// ══════════════════════════════════════════════

// Colors matching the site's fiche headers
const DM_BRANCH_COLORS = {
  d1:'#2d6a9f', d2:'#27ae60', d3:'#e67e22', d4:'#8e44ad',
  d5:'#16a085', d6:'#c0392b',
  d7:'#1a5276', d8:'#b7770d',
  d9:'#1e8449', d10:'#ca6f1e', d11:'#5b4fcf',
  d12:'#3a7d2c', d13:'#0b7aaa'
};

const DM_THEMES = {
  t1: {
    centerLabel:["THÈME 1","Fondements"], centerColor:'#1e3a5f',
    W:1100, H:580, CX:550, CY:285, R:215,
    branches:[
      { id:"d1", label:["D1","Rareté &","Besoins"], angle:235,
        detail:{ title:"D1 – L'économie, science de la rareté",
          chips:["Rareté","Besoins","Biens","Coût d'opportunité","Maslow"],
          points:[
            ["Définition (Malinvaud, 1986) :","L'économie est la science qui étudie comment des ressources limitées sont utilisées pour satisfaire des besoins illimités. C'est la tension fondamentale que toute la discipline cherche à résoudre."],
            ["La rareté :","les ressources de la société (naturelles, humaines, financières) ne permettent pas de produire tous les biens et services désirés. On distingue ressources renouvelables (eau, forêts), non renouvelables (pétrole, charbon) et intangibles (innovation, données)."],
            ["Pyramide de Maslow :","5 niveaux hiérarchiques de besoins — physiologiques → sécurité → appartenance → estime → accomplissement de soi. On satisfait les besoins inférieurs avant les supérieurs."],
            ["Biens libres vs économiques :","les biens libres sont illimités et gratuits (l'air). Les biens économiques sont rares et ont un coût : matériels (voiture, nourriture) ou immatériels (service d'un avocat, éducation publique)."],
            ["Coût d'opportunité :","choisir une option implique de renoncer à une autre. Le coût d'opportunité, c'est la valeur de la meilleure alternative non choisie. Ex : choisir d'étudier = renoncer à une soirée."],
            ["Retour de la rareté (Artus & Pastré) :","après 20 ans d'abondance (énergie bon marché, main-d'œuvre peu chère), la crise Covid-19 + la guerre en Ukraine ont créé des tensions sur l'énergie, les semi-conducteurs et les matières premières."],
          ],
          retenir:"L'économie résout un problème fondamental : des ressources LIMITÉES face à des besoins ILLIMITÉS. Chaque choix a un coût d'opportunité = la valeur de ce à quoi on renonce.",
          leaves:["Ressources limitées","Pyramide de Maslow","Coût d'opportunité"] }},
      { id:"d2", label:["D2","Activité","économique"], angle:145,
        detail:{ title:"D2 – Qu'est-ce que l'activité économique ?",
          chips:["6 Agents","Consommation","Épargne","Investissement","FBCF","Keynes","Friedman"],
          points:[
            ["6 agents économiques :","Ménages (consomment, travaillent) · Sociétés non financières (produisent) · Sociétés financières (banques, assurances) · État/APU (services non marchands) · ISBLSM (associations, ONG) · Reste du monde (partenaires étrangers)."],
            ["Consommation finale vs effective :","la consommation finale = ce que les ménages paient directement. La consommation effective = finale + les services collectifs gratuits fournis par l'État (éducation, santé). Toujours supérieure à la finale."],
            ["Théorie keynésienne de la conso. :","pour Keynes, la consommation dépend avant tout du revenu disponible courant. Quand le revenu augmente, la consommation augmente, mais dans une moindre proportion (propension marginale < 1)."],
            ["Revenu permanent (Friedman, 1957) :","les ménages ne basent pas leur consommation sur le revenu du moment, mais sur ce qu'ils espèrent gagner sur toute leur vie. Une prime exceptionnelle est surtout épargnée."],
            ["Paradoxe de l'épargne (Keynes) :","si TOUS les agents épargnent simultanément, la demande globale chute, la production baisse, les revenus diminuent, et on finit par épargner moins qu'avant. Ce qui est rationnel individuellement est néfaste collectivement."],
            ["FBCF et investissement :","la Formation Brute de Capital Fixe mesure l'investissement. 4 types : capacité (nouvelle usine), remplacement (machines usées), productivité (automatisation), immatériel (R&D, logiciels, formation)."],
          ],
          retenir:"Paradoxe de l'épargne : rationnel individuellement mais catastrophique collectivement. Conso effective > conso finale (inclut les services collectifs gratuits de l'État).",
          leaves:["Conso. finale vs effective","Revenu permanent Friedman","FBCF & investissement"] }},
      { id:"d3", label:["D3","Valeur","Ajoutée"], angle:325,
        detail:{ title:"D3 – Comment l'activité économique crée-t-elle de la richesse ?",
          chips:["VA","Consommations Intermédiaires","Répartition","3 Secteurs","ESS"],
          points:[
            ["Valeur Ajoutée (VA) :","richesse nouvelle créée lors de la production. VA = Chiffre d'affaires − Consommations Intermédiaires. Les CI sont les biens/services achetés à l'extérieur et DÉTRUITS dans la production. Attention : les machines (durée > 1 an) ne sont PAS des CI."],
            ["Exemple concret :","un jean vendu 60€. CI = tissu (10€) + boutons (2€) + fil (1€) = 13€. VA = 60 − 13 = 47€. Avec cette VA, l'entreprise doit payer ses salariés, ses impôts, sa banque et ses actionnaires."],
            ["Répartition primaire de la VA :","salariés (~63% en France selon l'INSEE 2024), actionnaires (dividendes), banques (intérêts), État (impôts sur la production), entreprise elle-même (EBE = autofinancement)."],
            ["Répartition secondaire :","après la répartition primaire, l'État intervient via les impôts, cotisations et allocations pour corriger les inégalités issues du marché."],
            ["3 secteurs économiques (Clark, 1947) :","primaire (exploitation des ressources naturelles : agriculture, pêche), secondaire (transformation et industrie), tertiaire (services). Le tertiaire représente ~80% du PIB et ~77% de l'emploi en France."],
            ["Économie Sociale et Solidaire (ESS) :","associations, coopératives, mutuelles, fondations. Objectif : performance économique ET utilité sociale. Pas de profit maximisé. ~10% de l'emploi et 200 000 structures en France."],
          ],
          retenir:"VA = CA − CI. Le PIB = somme des VA + TVA + droits de douane. Le secteur tertiaire domine l'économie française (~80% du PIB). L'ESS concilie performance économique et utilité sociale.",
          leaves:["VA = CA – CI","Répartition de la VA","ESS & 3 secteurs"] }},
      { id:"d4", label:["D4","PIB &","Indicateurs"], angle:45,
        detail:{ title:"D4 – Comment rendre compte de la situation économique d'un pays ?",
          chips:["PIB","3 Approches","PIB en volume","Limites","IDH","Alternatives"],
          points:[
            ["PIB – définition :","le Produit Intérieur Brut est la somme de toutes les valeurs ajoutées produites sur le territoire d'un pays en un an. C'est l'indicateur de référence pour mesurer la richesse créée et la croissance économique."],
            ["3 approches de calcul :","Offre : Σ VA + TVA + droits de douane · Demande : C + I + ΔStocks + (X − M) · Revenus : Salaires + (Impôts − Subventions) + EBE. Les 3 donnent le même résultat."],
            ["PIB en volume vs en valeur :","le PIB en valeur mélange évolution des quantités ET des prix. Le PIB en volume est corrigé de l'inflation : c'est lui qui mesure la vraie croissance. Le PIB par habitant en PPA permet de comparer les pays."],
            ["Limites du PIB :","il ne comptabilise pas le travail domestique ni le bénévolat (19-35% du PIB selon Stiglitz-Sen-Fitoussi). Il comptabilise positivement des activités néfastes (pollution + dépollution = 2 hausses du PIB). Il masque les inégalités."],
            ["Paradoxe d'Easterlin :","au-delà d'un certain seuil de richesse nationale, PIB par habitant et bonheur des citoyens ne sont plus corrélés. La croissance du PIB ne garantit pas le bien-être."],
            ["IDH (Sen / PNUD, 1990) :","l'Indice de Développement Humain combine espérance de vie (santé) + années de scolarisation (éducation) + RNB par habitant en PPA (niveau de vie). IDH mondial : 0,601 en 1990 → 0,732 en 2021."],
            ["Autres indicateurs alternatifs :","Better Life Index (OCDE, 11 dimensions), Épargne Nette Ajustée (Banque mondiale, préservation du capital pour les générations futures), IDHP (ajusté aux pressions environnementales)."],
          ],
          retenir:"PIB = indicateur QUANTITATIF. Il mesure la taille de l'économie, pas le bien-être. IDH = 3 dimensions (santé + éducation + niveau de vie). Toujours distinguer PIB en valeur (inclut l'inflation) et PIB en volume (croissance réelle).",
          leaves:["PIB – 3 approches","Limites du PIB","IDH & alternatives"] }},
    ]
  },
  t2: {
    centerLabel:["THÈME 2","Marché"], centerColor:'#0e6655',
    W:1000, H:510, CX:500, CY:255, R:210,
    branches:[
      { id:"d5", label:["D5","Marché &","Concurrence"], angle:205,
        detail:{ title:"D5 – L'économie de marché : fonctionnement, concurrence et modèles",
          chips:["Marché","CPP","Adam Smith","Main invisible","Schumpeter","Hayek","Baumol"],
          points:[
            ["Le marché :","lieu réel ou virtuel où l'offre et la demande se rencontrent pour former un prix d'équilibre et des quantités échangées. Peut être un marché de biens, de travail, de capitaux ou de devises."],
            ["Main invisible (Adam Smith, 1776) :","chaque individu, en cherchant son intérêt personnel, contribue involontairement au bien-être collectif grâce à la concurrence. C'est le principe fondateur du libéralisme économique."],
            ["CPP – 5 conditions :","atomicité (nombreux acteurs sans pouvoir de marché), homogénéité (produits identiques), libre entrée/sortie (pas de barrières), mobilité des facteurs (travail et capital circulent librement), transparence (information parfaite sur les prix)."],
            ["Optimum de Pareto :","état où on ne peut améliorer la situation de personne sans dégrader celle d'une autre. Atteint en CPP. En pratique, presque jamais réalisé."],
            ["Destruction créatrice (Schumpeter) :","l'innovation apparaît par 'grappes' et rend obsolètes les activités existantes tout en créant de nouvelles plus productives. À court terme = destructions d'emplois. À long terme = hausse du niveau de vie. Moteur du capitalisme."],
            ["Concurrence comme signal (Hayek) :","les prix ne sont pas seulement un signal de rareté, mais un mécanisme de transmission d'information dispersée entre des millions d'agents. Aucune autorité centrale ne peut remplacer ce processus."],
            ["Marchés contestables (Baumol) :","même si un marché est dominé par peu d'entreprises, la simple menace d'entrée de nouveaux concurrents (si pas de barrières à l'entrée) suffit à discipliner les prix et le comportement des firmes."],
          ],
          retenir:"La CPP est un modèle THÉORIQUE idéal. En pratique → concurrence imparfaite. Schumpeter : la vraie croissance vient de la destruction créatrice, pas de l'équilibre statique.",
          leaves:["CPP – 5 conditions","Destruction créatrice","Marchés contestables"] }},
      { id:"d6", label:["D6","Encadrement","du marché"], angle:340,
        detail:{ title:"D6 – Pourquoi encadrer le fonctionnement du marché ?",
          chips:["Monopole","Oligopole","Pratiques anticoncurrentielles","Biens publics","Externalités","DMA","Pigou"],
          points:[
            ["Concurrence imparfaite :","monopole (1 seule entreprise, 'price maker' — ex. Google avec 90% du marché de recherche mondial), oligopole (quelques grandes firmes — ex. téléphonie : Orange/SFR/Bouygues), concurrence monopolistique (nombreuses entreprises mais produits différenciés — ex. fast food)."],
            ["Pratiques anticoncurrentielles :","abus de position dominante (Google condamné à 4,34 Mds€ en 2018), entente illicite (Orange/SFR/Bouygues condamnés à 534 M€), auto-préférence (Apple condamné à 1,8 Mds€ en 2024). L'Autorité de la concurrence et la Commission européenne sanctionnent ces pratiques."],
            ["Digital Markets Act (DMA, 2023) :","règlement européen s'appliquant aux géants du numérique (Google, Apple, Amazon, Meta, Microsoft, TikTok). Leur impose des obligations spécifiques. Sanctions pouvant atteindre 10% du CA mondial en cas de violation."],
            ["Biens publics purs (Samuelson, 1954) :","deux propriétés : non-rivalité (ma consommation n'empêche pas la tienne) et non-exclusion (impossible d'empêcher quelqu'un d'en bénéficier). Exemple : éclairage public, défense nationale, justice. → passagers clandestins → seul l'État peut les financer."],
            ["Externalités (Pigou) :","effet d'une activité sur un tiers non compensé financièrement. Négative : pollution automobile (taxe carbone, malus) → l'État internalise le coût social. Positive : vaccination (subvention, gratuité), R&D (crédit impôt recherche)."],
          ],
          retenir:"2 types de défaillances : concurrence imparfaite (marché fonctionne mais mal → régulation) et défaillances pures (biens publics, externalités → le marché ne peut pas fonctionner seul).",
          leaves:["Biens publics & passagers","Externalités – Pigou","DMA & régulation"] }},
    ]
  },
  t3: {
    centerLabel:["THÈME 3","Financement"], centerColor:'#7d5a0a',
    W:1000, H:510, CX:500, CY:255, R:210,
    branches:[
      { id:"d7", label:["D7","Besoin &","Capacité"], angle:205,
        detail:{ title:"D7 – Quels agents ont un besoin ou une capacité de financement ?",
          chips:["Capacité","Besoin","Déficit","Dette","6 modes de financement","Friedman","Modigliani"],
          points:[
            ["Capacité vs besoin de financement :","un agent est en capacité si ses ressources > ses dépenses. En besoin si ses dépenses > ses ressources → doit emprunter. Ménages = structurellement en capacité (~17% d'épargne en 2024). Entreprises et État = structurellement en besoin."],
            ["Déficit public ≠ dette publique :","le déficit est un FLUX annuel (résultat d'une seule année : dépenses − recettes). La dette est un STOCK = accumulation de TOUS les déficits passés non encore remboursés. France 2024 : déficit = −5,8% du PIB ; dette = 113% du PIB."],
            ["Financement de l'État :","pour financer son déficit, l'État émet des OAT (Obligations Assimilables du Trésor) gérées par l'Agence France Trésor. ~52% de la dette est détenue par des non-résidents → vulnérabilité aux marchés internationaux. En 2024, la charge d'intérêts (56 Mds€) est le 1er poste budgétaire, devant l'Éducation nationale."],
            ["Théorie du revenu permanent (Friedman, 1957) :","les ménages lissent leur consommation sur toute leur vie selon ce qu'ils estiment gagner durablement. Une prime exceptionnelle est surtout épargnée, pas consommée. À l'opposé de Keynes qui pense que tout revenu supplémentaire est en partie consommé."],
            ["Cycle de vie (Ando & Modigliani, 1963) :","le comportement d'épargne varie selon l'âge. Phase 1 : endettement en début de vie active (revenus faibles, dépenses élevées). Phase 2 : épargne pendant la vie active. Phase 3 : désépargne à la retraite pour maintenir son niveau de vie."],
            ["6 modes de financement des entreprises :","autofinancement (bénéfices mis en réserve, sans coût), emprunt bancaire (crédit à moyen/long terme), augmentation de capital (émission de nouvelles actions), emprunt obligataire (pour grandes entreprises), crédit-bail (location avec option d'achat), crowdfunding (levée de fonds en ligne)."],
          ],
          retenir:"Déficit = FLUX (1 an). Dette = STOCK (cumulé). La charge d'intérêts (56 Mds€ en 2024) = 1er poste budgétaire de l'État français. Retenir les 6 modes de financement des entreprises.",
          leaves:["Déficit (flux) vs dette (stock)","6 modes de financement","Revenu permanent – Friedman"] }},
      { id:"d8", label:["D8","Banques &","Marchés"], angle:340,
        detail:{ title:"D8 – Rôles des banques et des marchés financiers dans le financement de l'économie",
          chips:["Finance directe","Finance indirecte","Création monétaire","Bâle III","3D – Bourguignon","Spéculation","Fintechs"],
          points:[
            ["Finance indirecte (intermédiation) :","les banques collectent l'épargne des ménages (dépôts à court terme) et accordent des crédits aux emprunteurs (prêts à long terme). C'est la transformation des échéances."],
            ["Finance directe :","les entreprises se financent directement auprès des épargnants en émettant des titres (actions, obligations) sur les marchés de capitaux, sans passer par une banque comme intermédiaire."],
            ["Création monétaire :","quand une banque accorde un crédit, elle crée de la monnaie scripturale ex nihilo en inscrivant le montant sur le compte de l'emprunteur. 'Les crédits font les dépôts.' Cette monnaie disparaît quand l'emprunteur rembourse."],
            ["Bâle III (réforme post-2008) :","les accords imposent aux banques de détenir au minimum 8% de fonds propres par rapport à leurs engagements. Si trop de clients ne remboursent pas, la banque peut faire faillite et entraîner d'autres banques dans sa chute (risque systémique — crise des subprimes 2008)."],
            ["3D de Bourguignon (depuis 1980) :","Désintermédiation (les entreprises se financent de moins en moins via les banques), Décloisonnement (disparition des barrières entre les différents marchés financiers), Déréglementation (allègement des règles encadrant les activités bancaires). Résultat : système plus dynamique mais plus fragile."],
            ["Spéculation et bulles :","la forte liquidité des marchés financiers favorise la spéculation (achat/vente rapide sans lien avec la valeur fondamentale) et crée des bulles spéculatives (ex. valeurs Internet 2000, immobilier USA 2007, crypto-monnaies 2021). La Bourse offre aussi des instruments de couverture (produits dérivés) pour se protéger contre les risques de change ou de taux."],
          ],
          retenir:"Les 3D de Bourguignon expliquent la montée des marchés financiers depuis 1980. Crise 2008 = conséquence directe de la déréglementation excessive. Création monétaire = 'les crédits font les dépôts'.",
          leaves:["Finance directe/indirecte","Création monétaire","3D – Bourguignon"] }},
    ]
  },
  t4: {
    centerLabel:["THÈME 4","Régulation","publique"], centerColor:'#4a1a6e',
    W:1100, H:570, CX:550, CY:275, R:215,
    branches:[
      { id:"d9", label:["D9","Rôle de","l'État"], angle:215,
        detail:{ title:"D9 – Quels sont la place et le rôle de l'État ?",
          chips:["État-gendarme","État-providence","3 fonctions Musgrave","Triple crise Rosanvallon","Collectivités","Courbe Laffer"],
          points:[
            ["État-gendarme vs État-providence :","l'État-gendarme se limite aux fonctions régaliennes (justice, police, défense, diplomatie, monnaie) sans interférer dans l'économie. L'État-providence, développé au XXe siècle, protège contre les risques sociaux (maladie, chômage, vieillesse, pauvreté). En France, il s'institutionnalise en 1945 avec la création de la Sécurité sociale."],
            ["3 fonctions de l'État (Musgrave, 1959) :","allocation des ressources (corriger les défaillances du marché : produire ce que le marché ne peut pas fournir efficacement — biens publics, externalités), redistribution des richesses (impôt progressif, allocations, SMIC), stabilisation économique (réguler les cycles via les politiques budgétaires et monétaires)."],
            ["Triple crise de l'État-providence (Rosanvallon) :","crise financière (coûts croissants liés au vieillissement de la population), crise d'efficacité (les politiques produisent-elles les résultats attendus ? chômage structurel, échec scolaire), crise de légitimité (les citoyens veulent plus de services mais refusent de payer plus d'impôts → méfiance envers les institutions)."],
            ["Collectivités territoriales :","communes (écoles primaires, urbanisme), départements (RSA, collèges), régions (lycées, développement économique, transports). La décentralisation (lois Defferre, 1982) a transféré des compétences de l'État vers ces collectivités pour rapprocher l'action publique des citoyens."],
            ["Courbe de Laffer :","'trop d'impôt tue l'impôt'. Au-delà d'un taux optimal, toute hausse d'imposition décourage le travail et l'investissement et finit par RÉDUIRE les recettes fiscales. Courbe en forme de cloche, fondement des politiques libérales des années 1980 (Reagan, Thatcher)."],
            ["Soutenabilité de la dette :","si g (taux de croissance) > r (taux d'intérêt) + d (déficit), le ratio dette/PIB baisse mécaniquement. Dans le cas contraire, il explose. Fin 2025 : dette française = 115,6% du PIB, charge d'intérêts = 56 Mds€/an."],
          ],
          retenir:"3 fonctions de Musgrave : allocation · redistribution · stabilisation. Triple crise de Rosanvallon : financière · efficacité · légitimité. Toujours distinguer fonctions régaliennes (État-gendarme) et protection sociale (État-providence).",
          leaves:["3 fonctions Musgrave","Triple crise Rosanvallon","Courbe de Laffer"] }},
      { id:"d10", label:["D10","Politiques","économiques"], angle:335,
        detail:{ title:"D10 – Quelles politiques économiques l'État peut-il mener ?",
          chips:["Carré magique Kaldor","Conjoncturelle vs Structurelle","Demande vs Offre","Multiplicateur Keynes","Équivalence ricardienne","Croissance endogène"],
          points:[
            ["Carré magique de Kaldor :","4 objectifs souvent contradictoires : croissance économique (↑PIB), plein-emploi (↓chômage), stabilité des prix (inflation ~2%), équilibre extérieur (exports ≈ imports). Plus le carré est grand, meilleure est la situation. En France 2019 : croissance 1,2%, chômage 8,1%, inflation 1,1% → aucun objectif pleinement atteint."],
            ["Politique conjoncturelle vs structurelle :","conjoncturelle = court terme, répond aux chocs immédiats (relance ou freinage). Structurelle = long terme, transforme les fondations de l'économie (réforme du marché du travail, éducation, innovation). Effets lents mais durables."],
            ["Politique de demande (Keynes) vs d'offre :","demande = soutenir la consommation par la dépense publique et les baisses d'impôts sur les ménages. Offre = améliorer les conditions de production (baisse charges patronales, flexibilité du travail, R&D). La demande est efficace à court terme mais creuse le déficit. L'offre a des effets plus durables mais lents."],
            ["Multiplicateur keynésien :","1€ de dépense publique génère plus d'1€ de revenu dans l'économie par effets en chaîne : l'État paie des ouvriers → ils consomment → les commerçants embauchent → etc. L'effet final est supérieur à la dépense initiale."],
            ["Équivalence ricardienne (Lucas) :","si l'État s'endette pour financer des dépenses, les ménages rationnels anticipent des hausses d'impôts futures et épargnent immédiatement → l'effet de relance est annulé. L'effet d'éviction (Friedman) : l'État emprunte massivement → hausse des taux → baisse de l'investissement privé."],
            ["Croissance endogène (Lucas, Romer, Barro) :","la croissance est générée de l'intérieur du système par le capital humain (Lucas : investir dans la formation), l'innovation et la connaissance (Romer : financer la R&D et protéger les brevets), les infrastructures productives (Barro : transports, numérique, énergie)."],
          ],
          retenir:"Carré magique = 4 objectifs CONTRADICTOIRES. Multiplicateur amplifie la relance, mais équivalence ricardienne + effet d'éviction peuvent l'annuler. Croissance endogène : l'État doit créer les conditions structurelles (éducation, R&D, infrastructures).",
          leaves:["Carré magique – Kaldor","Multiplicateur keynésien","Croissance endogène"] }},
      { id:"d11", label:["D11","UE &","Politique"], angle:85,
        detail:{ title:"D11 – L'appartenance à l'UE influence-t-elle la politique économique des pays membres ?",
          chips:["Balassa","Subsidiarité","Proportionnalité","BCE","QE","PSC","NextGenerationEU","Brexit"],
          points:[
            ["Construction de l'UE :","le Traité de Rome (1957) crée la CEE avec 6 pays fondateurs. Plusieurs vagues d'élargissement jusqu'à 27 États membres. En 2020, le Brexit illustre que l'intégration peut être réversible : le Royaume-Uni quitte l'UE après 47 ans de membership."],
            ["Niveaux d'intégration (Balassa, 1961) :","zone de libre-échange (fin des droits de douane internes) → union douanière (tarif extérieur commun) → marché commun (libre circulation des facteurs) → union économique (coordination des politiques) → UEM (monnaie unique) → union politique (non encore atteinte)."],
            ["Subsidiarité & proportionnalité :","subsidiarité = l'UE n'intervient que si elle est plus efficace que les États (l'éducation et la fiscalité restent nationales). Proportionnalité = même si l'UE est compétente, elle ne doit agir qu'à la mesure strictement nécessaire (directives-cadres > règlements uniformes)."],
            ["BCE et politique monétaire :","créée en 1998, indépendante des gouvernements. Objectif prioritaire : stabilité des prix (inflation ~2%). Politique conventionnelle : taux directeurs. QE (Quantitative Easing) : achats massifs d'obligations d'État quand les taux sont déjà proches de 0, pour injecter des liquidités directement."],
            ["PSC et budget européen :","Pacte de Stabilité et de Croissance (1997) : déficit public < 3% du PIB · dette publique < 60% du PIB. La France ne respecte plus ces critères depuis 2002. Le budget de l'UE représente ~1% du PIB européen (vs 40-50% pour les budgets nationaux) : il ne peut pas servir d'outil de relance macroéconomique."],
            ["NextGenerationEU :","750 Mds€ post-Covid, financés par une dette commune européenne (une première). Objectif : financer la transition écologique et numérique. Illustre une évolution vers plus d'intégration budgétaire."],
          ],
          retenir:"Politique monétaire = compétence EXCLUSIVE de la BCE pour la zone euro. Politique budgétaire = nationale mais encadrée par le PSC (−3% / 60%). Brexit = preuve que l'intégration est réversible si le coût en souveraineté est perçu comme trop élevé.",
          leaves:["BCE & QE","PSC : −3% / 60%","Subsidiarité & Brexit"] }},
    ]
  },
  t5: {
    centerLabel:["THÈME 5","Croissance"], centerColor:'#1e4a12',
    W:1000, H:510, CX:500, CY:255, R:210,
    branches:[
      { id:"d12", label:["D12","Croissance &","Développement"], angle:200,
        detail:{ title:"D12 – La croissance économique doit-elle être systématiquement recherchée ?",
          chips:["Croissance extensive/intensive","Output gap","Cycles","IDH","Dév. durable","Soutenabilité","Kuznets","Rostow"],
          points:[
            ["Définition et mesure (Perroux) :","la croissance économique = augmentation soutenue et durable du PIB réel. Extensive = ↑ quantité de facteurs de production (plus de travailleurs, plus de capital). Intensive = ↑ productivité des facteurs (on produit plus avec les mêmes ressources, grâce à l'innovation)."],
            ["Croissance potentielle vs output gap :","la croissance potentielle est le niveau de production sans tensions inflationnistes (le 'trend'). L'output gap = écart entre croissance effective et potentielle. Négatif → capacités inutilisées → politique de relance utile. Positif → économie en surchauffe → risque d'inflation."],
            ["Cycles économiques :","expansion (↑ croissance, ↓ chômage), crise (retournement), récession (PIB négatif ≥ 2 trimestres), dépression (contraction durable + faillites + déflation), reprise. Cycles de Kitchin (3-4 ans, stocks), Juglar (8-10 ans, investissement), Kondratiev (40-60 ans, grappes d'innovations)."],
            ["Stagnation séculaire :","Summers : insuffisance structurelle de la demande, masquée avant 2008 par des bulles immobilières. Gordon : ralentissement de l'innovation comme frein à la croissance potentielle. Bernanke : excès mondial d'épargne des pays émergents qui maintient les taux bas et décourage l'investissement productif."],
            ["Développement humain (Amartya Sen) :","le développement = 'processus d'expansion des libertés réelles'. L'IDH (PNUD, 1990) combine santé (espérance de vie) + éducation (années de scolarisation) + niveau de vie (RNB/hab en PPA). IDH mondial : 0,601 (1990) → 0,732 (2021). Courbe de Kuznets : les inégalités augmentent au début du développement, puis baissent avec l'émergence d'une classe moyenne."],
            ["Développement durable (Brundtland, 1987) :","'répondre aux besoins du présent sans compromettre ceux des générations futures'. 3 piliers : économique + social + environnemental. Triple Bottom Line (Elkington) = 'People, Planet, Profit'. Soutenabilité faible (Solow) : le capital naturel est substituable par la technologie. Soutenabilité forte : le capital naturel est irremplaçable, il faut le préserver absolument."],
          ],
          retenir:"Croissance (↑ PIB, quantitatif) ≠ Développement (transformation qualitative) ≠ Développement durable (ne compromet pas les générations futures). L'output gap guide les politiques conjoncturelles.",
          leaves:["Output gap & cycles","IDH – Amartya Sen","Dév. durable & soutenabilité"] }},
      { id:"d13", label:["D13","Déterminants","de la croissance"], angle:340,
        detail:{ title:"D13 – Qu'est-ce qui détermine le potentiel de croissance ?",
          chips:["Capital humain","PGF","Paradoxe Solow","Schumpeter","Romer","Aghion","Malthus","Ricardo"],
          points:[
            ["Facteurs de production :","travail, capital physique, ressources naturelles. Mais leur simple accumulation ne garantit pas la croissance durable : la Chine a misé sur la quantité (main-d'œuvre + investissement massif), l'Allemagne sur la qualité (formation Ausbildung + capital de haute qualité), la Norvège sur ses ressources (pétrole → fonds souverain)."],
            ["Capital humain (Schultz & Becker) :","l'éducation, la formation et la santé sont des INVESTISSEMENTS productifs à rendement mesurable. Becker (Human Capital, 1964) : l'individu arbitre coûts (études, temps, salaire sacrifié) vs bénéfices (salaires plus élevés, emploi stable). Investir dans la formation = augmenter la productivité du travail."],
            ["Malthus (1798) & Ricardo (1817) :","Malthus : population croît géométriquement (1,2,4,8) mais production alimentaire arithmétiquement (1,2,3,4) → pénuries inévitables. Ricardo : loi des rendements décroissants — exploitation progressive de terres moins fertiles → chaque unité supplémentaire produit moins. La rente foncière capte une part croissante de la VA → freine l'investissement."],
            ["PGF et résidu de Solow :","la Productivité Globale des Facteurs mesure la part de la croissance NON expliquée par l'augmentation du travail et du capital. Aux États-Unis, Denison (1962) : sur 2,9% de croissance, 0,9 point inexpliqué. En France : 2 points inexpliqués sur 5%. Ce 'résidu' = progrès technique non mesurable directement."],
            ["Paradoxe de Solow :","'On voit des ordinateurs partout, sauf dans les statistiques de la productivité.' Malgré les investissements massifs dans les TIC, la productivité a ralenti dans les années 1970-80. Explication : les effets du PT sont différés (réorganisation des entreprises, formation des salariés). Résolution dans les années 1990 quand les gains de productivité ont finalement émergé."],
            ["Destruction créatrice (Schumpeter) vs croissance endogène :","Schumpeter : l'innovation apparaît par GRAPPES (discontinue), remplace les activités obsolètes. Aghion & Howitt : l'innovation est CONTINUE 'étape par étape', chaque innovation améliore la précédente. Point commun : le progrès technique est ENDOGÈNE (résulte des décisions de R&D). La concurrence pousse les entreprises à innover pour protéger ou conquérir leur rente de monopole."],
          ],
          retenir:"PGF = résidu de Solow = ce que travail et capital n'expliquent pas. Schumpeter : innovation DISCONTINUE (grappes). Aghion : innovation CONTINUE (étape par étape). Les deux : la concurrence est un moteur d'innovation.",
          leaves:["PGF & paradoxe Solow","Destruction créatrice","Croissance endogène"] }},
    ]
  }
};

// per-page selected state
const dmSelected = { t1:null, t2:null, t3:null, t4:null, t5:null };

function dmPolar(cx, cy, r, deg) {
  const rad = deg * Math.PI / 180;
  return { x: cx + r * Math.cos(rad), y: cy + r * Math.sin(rad) };
}

function dmRenderMap(key) {
  const theme = DM_THEMES[key];
  const sel = dmSelected[key];
  const { W, H, CX, CY, centerColor } = theme;
  const gid = `shd_${key}`;

  let svg = `<defs>
    <filter id="${gid}" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="0" dy="2" stdDeviation="4" flood-color="#000" flood-opacity="0.12"/>
    </filter>
  </defs>
  <rect width="${W}" height="${H}" fill="#f8fafd"/>`;

  // center node
  svg += `<circle cx="${CX}" cy="${CY}" r="64" fill="${centerColor}" filter="url(#${gid})"/>`;
  theme.centerLabel.forEach((line, i) => {
    const y = CY - (theme.centerLabel.length-1)*10 + i*20;
    svg += `<text x="${CX}" y="${y}" text-anchor="middle" dominant-baseline="central"
      fill="white" font-size="${i===0?13:12}" font-weight="700"
      font-family="Segoe UI,sans-serif">${line}</text>`;
  });

  theme.branches.forEach(branch => {
    const col = DM_BRANCH_COLORS[branch.id] || '#2d6a9f';
    const bp = dmPolar(CX, CY, theme.R, branch.angle);
    const isSel = sel === branch.id;
    const isLeft = bp.x < CX;

    // center → branch connector
    svg += `<line x1="${CX}" y1="${CY}" x2="${bp.x.toFixed(1)}" y2="${bp.y.toFixed(1)}"
      stroke="${col}" stroke-width="2" opacity="0.3"/>`;

    // leaf config
    const leaves = branch.detail.leaves;
    const lw = 148, lh = 34, gap = 8;
    const totalH = leaves.length * (lh + gap) - gap;
    const startY = bp.y - totalH / 2;
    const leafX = isLeft ? bp.x - 26 - lw : bp.x + 26;
    const connX = isLeft ? leafX + lw : leafX;

    // bracket: branch → vertical bar
    svg += `<line x1="${isLeft ? bp.x-58 : bp.x+58}" y1="${bp.y}"
      x2="${connX}" y2="${bp.y}"
      stroke="${col}" stroke-width="1.8" opacity="0.35"/>`;
    svg += `<line x1="${connX}" y1="${startY + lh/2}"
      x2="${connX}" y2="${startY + totalH - lh/2}"
      stroke="${col}" stroke-width="1.8" opacity="0.35"/>`;

    // leaf cards
    leaves.forEach((leaf, i) => {
      const ly = startY + i * (lh + gap);
      const midY = ly + lh / 2;
      svg += `<line x1="${connX}" y1="${midY}" x2="${isLeft ? leafX+lw : leafX}" y2="${midY}"
        stroke="${col}" stroke-width="1.2" opacity="0.25"/>`;
      svg += `<rect x="${leafX}" y="${ly}" width="${lw}" height="${lh}" rx="8"
        fill="white" stroke="${col}" stroke-width="1.4"
        style="cursor:pointer" filter="url(#${gid})"
        onclick="dmSelectBranch('${key}','${branch.id}')"/>`;
      svg += `<text x="${leafX + lw/2}" y="${ly + lh/2}"
        text-anchor="middle" dominant-baseline="central"
        fill="#1a1a2e" font-size="10.5" font-family="Segoe UI,sans-serif"
        pointer-events="none">${leaf}</text>`;
    });

    // branch node
    const bw = 114, bh = 64;
    svg += `<rect x="${(bp.x-bw/2).toFixed(1)}" y="${(bp.y-bh/2).toFixed(1)}"
      width="${bw}" height="${bh}" rx="12"
      fill="${isSel ? col : 'white'}" stroke="${col}"
      stroke-width="${isSel ? 2.5 : 2}"
      filter="url(#${gid})"
      style="cursor:pointer"
      onclick="dmSelectBranch('${key}','${branch.id}')"/>`;
    branch.label.forEach((line, i) => {
      const y = bp.y - (branch.label.length-1)*8.5 + i*17;
      svg += `<text x="${bp.x.toFixed(1)}" y="${y.toFixed(1)}"
        text-anchor="middle" dominant-baseline="central"
        fill="${isSel ? 'white' : '#1a1a2e'}"
        font-size="${i===0?12:10}" font-weight="700"
        font-family="Segoe UI,sans-serif" pointer-events="none">${line}</text>`;
    });
  });

  const el = document.getElementById(`dm-map-${key}`);
  if (el) el.innerHTML = svg;
}

function dmRenderDetail(key) {
  const el = document.getElementById(`dm-detail-${key}`);
  if (!el) return;
  const sel = dmSelected[key];
  if (!sel) {
    el.innerHTML = `<div style="text-align:center;color:#aaa;padding:28px 0;font-size:14px;font-style:italic">
      👆 Clique sur un nœud de la carte pour afficher le résumé détaillé
    </div>`;
    return;
  }
  const theme = DM_THEMES[key];
  const branch = theme.branches.find(b => b.id === sel);
  if (!branch) return;
  const d = branch.detail;
  const col = DM_BRANCH_COLORS[branch.id] || '#2d6a9f';

  el.innerHTML = `
    <div style="border-left:4px solid ${col};padding-left:16px;margin-bottom:16px">
      <div style="font-size:0.75em;font-weight:700;text-transform:uppercase;letter-spacing:1px;color:${col};margin-bottom:4px">
        ${branch.label.join(' ')}
      </div>
      <h3 style="font-size:1.08em;font-weight:700;color:#1a1a2e;line-height:1.35">${d.title}</h3>
    </div>
    <div style="display:flex;flex-wrap:wrap;gap:6px;margin-bottom:16px">
      ${d.chips.map(c=>`<span style="padding:3px 11px;border-radius:20px;font-size:0.8em;font-weight:600;
        background:${col}18;color:${col};border:1px solid ${col}44">${c}</span>`).join('')}
    </div>
    <ul style="list-style:none;padding:0;margin-bottom:14px">
      ${d.points.map(([label,text])=>`<li style="padding:8px 0 8px 18px;border-bottom:1px solid #f0f4f8;
        font-size:0.9em;color:#333;line-height:1.65;position:relative">
        <span style="position:absolute;left:0;color:${col};font-weight:bold">→</span>
        <strong style="color:#1a1a2e">${label}</strong> ${text}
      </li>`).join('')}
    </ul>
    ${d.retenir?`<div style="background:#fff8e1;border:1px solid #f9c740;border-radius:6px;padding:11px 14px;font-size:0.88em;line-height:1.65;color:#333">
      <strong style="color:#7a5800">⭐ À retenir — </strong>${d.retenir}
    </div>`:''}
  `;
  el.style.animation='none';
  requestAnimationFrame(()=>{ el.style.animation='fadeIn .22s ease'; });
}

function dmSelectBranch(key, id) {
  dmSelected[key] = dmSelected[key] === id ? null : id;
  dmRenderMap(key);
  dmRenderDetail(key);
}

function showMM(pageId) {
  document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
  document.getElementById(pageId).classList.add('active');
  const nav = document.getElementById('mainNav');
  document.getElementById('navTitle').textContent = '🧠 Carte Mentale';
  document.getElementById('navToc').innerHTML = '';
  nav.classList.add('visible');
  window.scrollTo({ top: 0, behavior: 'smooth' });
  const key = pageId.replace('mm-', '');
  setTimeout(() => { dmRenderMap(key); dmRenderDetail(key); }, 80);
}
</script>

<!-- ══════════════════════════════════════════ -->
<!-- PAGES CARTES MENTALES -->
<!-- ══════════════════════════════════════════ -->

<div class="page" id="mm-t1">
  <div class="theme-cover tc-t1">
    <div class="tc-num">🧠 Carte Mentale · Thème 1</div>
    <h2>Les fondements de l'activité économique</h2>
    <p>D1 Rareté · D2 Activité économique · D3 Création de richesse · D4 PIB & Indicateurs</p>
  </div>
  <div style="max-width:1100px;margin:24px auto 30px;padding:0 16px">
    <div style="background:white;border-radius:12px;box-shadow:0 2px 10px rgba(0,0,0,.09);padding:12px;margin-bottom:16px;overflow-x:auto">
      <svg id="dm-map-t1" viewBox="0 0 1100 580" style="width:100%;display:block;min-width:600px"></svg>
    </div>
    <div id="dm-detail-t1" style="background:white;border-radius:12px;box-shadow:0 2px 10px rgba(0,0,0,.09);padding:24px 28px;min-height:80px">
      <div style="text-align:center;color:#aaa;padding:22px 0;font-size:14px;font-style:italic">👆 Clique sur un nœud de la carte pour afficher le résumé détaillé</div>
    </div>
  </div>
  <div class="page-footer">🧠 Thème 1 ·
    <button onclick="goHome()" style="background:none;border:none;color:#2d6a9f;cursor:pointer;font-size:1em">← Accueil</button> ·
    <button onclick="showPage('page-t1','Thème 1','T1')" style="background:none;border:none;color:#2d6a9f;cursor:pointer;font-size:1em">📖 Voir les fiches →</button>
  </div>
</div>

<div class="page" id="mm-t2">
  <div class="theme-cover tc-t2">
    <div class="tc-num">🧠 Carte Mentale · Thème 2</div>
    <h2>L'économie de marché</h2>
    <p>D5 Marché & concurrence · D6 Encadrement du marché</p>
  </div>
  <div style="max-width:1000px;margin:24px auto 30px;padding:0 16px">
    <div style="background:white;border-radius:12px;box-shadow:0 2px 10px rgba(0,0,0,.09);padding:12px;margin-bottom:16px;overflow-x:auto">
      <svg id="dm-map-t2" viewBox="0 0 1000 510" style="width:100%;display:block;min-width:560px"></svg>
    </div>
    <div id="dm-detail-t2" style="background:white;border-radius:12px;box-shadow:0 2px 10px rgba(0,0,0,.09);padding:24px 28px;min-height:80px">
      <div style="text-align:center;color:#aaa;padding:22px 0;font-size:14px;font-style:italic">👆 Clique sur un nœud de la carte pour afficher le résumé détaillé</div>
    </div>
  </div>
  <div class="page-footer">🧠 Thème 2 ·
    <button onclick="goHome()" style="background:none;border:none;color:#0e6655;cursor:pointer;font-size:1em">← Accueil</button> ·
    <button onclick="showPage('page-t2','Thème 2','T2')" style="background:none;border:none;color:#0e6655;cursor:pointer;font-size:1em">📖 Voir les fiches →</button>
  </div>
</div>

<div class="page" id="mm-t3">
  <div class="theme-cover tc-t3">
    <div class="tc-num">🧠 Carte Mentale · Thème 3</div>
    <h2>Le financement de l'économie</h2>
    <p>D7 Besoin & capacité de financement · D8 Banques & marchés financiers</p>
  </div>
  <div style="max-width:1000px;margin:24px auto 30px;padding:0 16px">
    <div style="background:white;border-radius:12px;box-shadow:0 2px 10px rgba(0,0,0,.09);padding:12px;margin-bottom:16px;overflow-x:auto">
      <svg id="dm-map-t3" viewBox="0 0 1000 510" style="width:100%;display:block;min-width:560px"></svg>
    </div>
    <div id="dm-detail-t3" style="background:white;border-radius:12px;box-shadow:0 2px 10px rgba(0,0,0,.09);padding:24px 28px;min-height:80px">
      <div style="text-align:center;color:#aaa;padding:22px 0;font-size:14px;font-style:italic">👆 Clique sur un nœud de la carte pour afficher le résumé détaillé</div>
    </div>
  </div>
  <div class="page-footer">🧠 Thème 3 ·
    <button onclick="goHome()" style="background:none;border:none;color:#7d5a0a;cursor:pointer;font-size:1em">← Accueil</button> ·
    <button onclick="showPage('page-t3','Thème 3','T3')" style="background:none;border:none;color:#7d5a0a;cursor:pointer;font-size:1em">📖 Voir les fiches →</button>
  </div>
</div>

<div class="page" id="mm-t4">
  <div class="theme-cover tc-t4">
    <div class="tc-num">🧠 Carte Mentale · Thème 4</div>
    <h2>La régulation publique dans une économie de marché</h2>
    <p>D9 Rôle de l'État · D10 Politiques économiques · D11 Appartenance à l'UE</p>
  </div>
  <div style="max-width:1100px;margin:24px auto 30px;padding:0 16px">
    <div style="background:white;border-radius:12px;box-shadow:0 2px 10px rgba(0,0,0,.09);padding:12px;margin-bottom:16px;overflow-x:auto">
      <svg id="dm-map-t4" viewBox="0 0 1100 570" style="width:100%;display:block;min-width:600px"></svg>
    </div>
    <div id="dm-detail-t4" style="background:white;border-radius:12px;box-shadow:0 2px 10px rgba(0,0,0,.09);padding:24px 28px;min-height:80px">
      <div style="text-align:center;color:#aaa;padding:22px 0;font-size:14px;font-style:italic">👆 Clique sur un nœud de la carte pour afficher le résumé détaillé</div>
    </div>
  </div>
  <div class="page-footer">🧠 Thème 4 ·
    <button onclick="goHome()" style="background:none;border:none;color:#4a1a6e;cursor:pointer;font-size:1em">← Accueil</button> ·
    <button onclick="showPage('page-t4','Thème 4','T4')" style="background:none;border:none;color:#4a1a6e;cursor:pointer;font-size:1em">📖 Voir les fiches →</button>
  </div>
</div>

<div class="page" id="mm-t5">
  <div class="theme-cover tc-t5">
    <div class="tc-num">🧠 Carte Mentale · Thème 5</div>
    <h2>La croissance économique : origines et enjeux</h2>
    <p>D12 Croissance & développement · D13 Déterminants du potentiel de croissance</p>
  </div>
  <div style="max-width:1000px;margin:24px auto 30px;padding:0 16px">
    <div style="background:white;border-radius:12px;box-shadow:0 2px 10px rgba(0,0,0,.09);padding:12px;margin-bottom:16px;overflow-x:auto">
      <svg id="dm-map-t5" viewBox="0 0 1000 510" style="width:100%;display:block;min-width:560px"></svg>
    </div>
    <div id="dm-detail-t5" style="background:white;border-radius:12px;box-shadow:0 2px 10px rgba(0,0,0,.09);padding:24px 28px;min-height:80px">
      <div style="text-align:center;color:#aaa;padding:22px 0;font-size:14px;font-style:italic">👆 Clique sur un nœud de la carte pour afficher le résumé détaillé</div>
    </div>
  </div>
  <div class="page-footer">🧠 Thème 5 ·
    <button onclick="goHome()" style="background:none;border:none;color:#1e4a12;cursor:pointer;font-size:1em">← Accueil</button> ·
    <button onclick="showPage('page-t5','Thème 5','T5')" style="background:none;border:none;color:#1e4a12;cursor:pointer;font-size:1em">📖 Voir les fiches →</button>
  </div>
</div>

</body>
</html>

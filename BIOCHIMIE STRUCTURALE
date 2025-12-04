<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>QCM Biochimie Pro — Glucides, Lipides & Acides aminés</title>
  <meta name="description" content="Plateforme QCM — accès 1 an pour 500 F." />
  <style>
    :root{
      --bg1:#f7fafc; --bg2:#eef2f7; --card:#ffffff; --accent:#0f172a; --muted:#64748b;
      --primary:#0ea5a4; --primary-600:#06b6d4; --danger:#ef4444;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans";
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{margin:0; background: linear-gradient(160deg,var(--bg1),var(--bg2)); color:var(--accent); min-height:100vh; -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale}
    .container{max-width:1100px;margin:30px auto;padding:20px}
    header{
      display:flex;align-items:center;justify-content:space-between;padding:16px 20px;background:linear-gradient(180deg,#ffffff,#fbfdff);
      border-radius:14px;border:1px solid rgba(2,6,23,0.04);box-shadow:0 6px 30px rgba(2,6,23,0.04);
    }
    .brand{font-weight:800;font-size:18px;cursor:pointer;display:flex;gap:10px;align-items:center}
    .brand .logo{width:42px;height:42px;border-radius:10px;background:linear-gradient(135deg,var(--primary),var(--primary-600));display:flex;align-items:center;justify-content:center;color:#fff;font-weight:800}
    .nav-actions{display:flex;gap:10px;align-items:center}
    button, .btn, a.btn {border:0;cursor:pointer;padding:10px 14px;border-radius:10px;font-weight:700;font-size:14px;text-decoration:none;display:inline-flex;align-items:center;gap:8px}
    .btn-primary{background:linear-gradient(90deg,var(--primary),var(--primary-600));color:white;box-shadow:0 6px 18px rgba(14,165,164,0.12)}
    .btn-ghost{background:transparent;border:1px solid rgba(2,6,23,0.06);color:var(--accent)}
    .btn-danger{background:var(--danger);color:white}
    .card{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 8px 30px rgba(2,6,23,0.04)}
    .grid{display:grid;gap:14px}
    .grid.cols-2{grid-template-columns:1fr 380px}
    h1{margin:0 0 8px 0;font-size:24px}
    p.lead{margin:0;color:var(--muted);font-size:15px}
    .form-row{display:flex;gap:12px;flex-wrap:wrap;margin-top:10px}
    input[type="text"], input[type="password"], select, textarea{padding:10px;border-radius:10px;border:1px solid #e6eef8;background:transparent;width:100%;font-size:14px}
    label{font-size:13px;color:var(--muted)}
    .small{font-size:13px;color:var(--muted)}
    .sidebar{position:sticky;top:22px}
    .muted{color:var(--muted);font-size:13px}
    .chip{display:inline-block;padding:6px 10px;border-radius:999px;background:#eef2ff;font-size:12px;color:#3730a3}
    .chapter{padding:12px;border-radius:10px;border:1px solid rgba(2,6,23,0.04);display:flex;justify-content:space-between;align-items:center}
    .qcm-item{padding:12px;border-radius:8px;border:1px dashed rgba(2,6,23,0.04);margin-top:8px;background:#fcfdff}
    footer{margin-top:24px;text-align:center;color:var(--muted);font-size:13px}
    .top-line{display:flex;justify-content:space-between;gap:12px;align-items:center;margin-bottom:12px}
    .badge-green{background:#ecfdf5;color:#065f46;padding:6px 8px;border-radius:999px;font-weight:700}
    .hidden{display:none}
    .spaced{margin-top:12px}
    .small-muted{font-size:13px;color:var(--muted)}
    .qcm-box{margin-bottom:12px;padding:14px;border-radius:12px;background:#fff;border:1px solid #eef2f7}
    .qcm-box h3{margin:0 0 10px 0;font-size:16px}
    .result { margin-top:10px; color:#475569; font-weight:700; }
    .correct { color: #065f46; }
    .incorrect { color: #b91c1c; }
    label { display:block; margin-bottom:8px; cursor:pointer; color:var(--accent) }
    input[type="checkbox"]{transform:scale(1.05);margin-right:8px}
    .muted-note{font-size:13px;color:var(--muted);margin-top:8px}
    @media (max-width:900px){ .grid.cols-2{grid-template-columns:1fr} .sidebar{position:static} header{flex-direction:column;gap:12px} .brand{width:100%;justify-content:space-between} .nav-actions{width:100%;justify-content:flex-end} }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand" id="brand">
        <div class="logo">QB</div>
        <div>
          <div style="font-size:15px">QCM Biochimie Pro</div>
          <div style="font-size:12px;color:var(--muted)">Révision — Glucides, Lipides, AA & plus</div>
        </div>
      </div>
      <div class="nav-actions" id="navActions"></div>
    </header>

    <main class="spaced">
      <div id="pageHome" class="card">
        <div class="top-line">
          <div style="flex:1">
            <h1>Plateforme professionnelle de QCM — Biochimie structurale</h1>
            <p class="lead">Révise par chapitre, corrige automatiquement, et suis ta progression. Accès complet pendant 1 an pour <strong>500 F</strong>.</p>
            <div class="spaced">
              <button class="btn btn-primary" id="ctaRegister">Commencer — Créer un compte</button>
              <button class="btn btn-ghost" id="ctaLogin">J'ai déjà un compte — Me connecter</button>
            </div>
            <div class="muted-note">Le paiement s'effectue via un USSD : appuie sur "Composer le paiement" depuis ton tableau de bord pour lancer l'appel. Le numéro est masqué pour des raisons de confidentialité.</div>
          </div>
          <div class="sidebar" style="width:320px">
            <div class="card" style="padding:14px;margin-bottom:12px">
              <div style="display:flex;justify-content:space-between;align-items:center">
                <div><strong>Paiement</strong><div class="small-muted">Connecte-toi pour composer le paiement</div></div>
                <div class="chip">500 F</div>
              </div>
              <div class="spaced small-muted">Le numéro de réception est masqué ici ; tu pourras composer directement depuis ton tableau de bord.</div>
            </div>

            <div class="card" style="padding:14px;margin-bottom:12px">
              <div class="muted">Fonctionnalités</div>
              <ul class="small-muted" style="padding-left:18px;margin-top:8px">
                <li>100 QCM / chapitre</li>
                <li>Accès : 1 an après paiement</li>
                <li>Panneau admin pour importer chapitres et QCM (côté serveur)</li>
                <li>Correction automatique et historique de réponses</li>
              </ul>
            </div>

            <div class="card" style="padding:14px">
              <div style="display:flex;justify-content:space-between;align-items:center">
                <div><strong>Chaîne WhatsApp</strong><div class="small-muted">Rejoins la chaîne pour recevoir les nouveautés</div></div>
              </div>
              <div class="spaced small-muted">Notre chaîne WhatsApp publie les nouvelles fonctionnalités et mises à jour.</div>
              <div class="spaced"><a class="btn btn-primary" href="https://whatsapp.com/channel/0029VbBoaZhHFxOw17OfXF2E" target="_blank" rel="noopener noreferrer">Rejoindre la chaîne WhatsApp</a></div>
            </div>
          </div>
        </div>
      </div>

      <div id="pageRegister" class="card hidden">
        <h2>Créer un compte</h2>
        <div class="form-row">
          <div style="flex:1"><label>Email</label><input type="text" id="regEmail" placeholder="ex: etudiant@univ.bj" /></div>
          <div style="width:240px"><label>Mot de passe</label><input type="password" id="regPass" placeholder="••••••••" /></div>
        </div>
        <div class="form-row spaced">
          <label style="display:flex;align-items:center;gap:8px"><input type="checkbox" id="regRemember" /> <span class="small-muted">Se souvenir de moi</span></label>
        </div>
        <div class="form-row spaced">
          <button class="btn btn-primary" id="btnRegister">S'inscrire et continuer</button>
          <button class="btn btn-ghost" id="btnBackFromRegister">Retour</button>
        </div>
        <div class="small-muted spaced">Après inscription, tu pourras payer via le bouton « Composer le paiement » depuis ton tableau de bord.</div>
      </div>

      <div id="pageLogin" class="card hidden">
        <h2>Connexion</h2>
        <div class="form-row">
          <div style="flex:1"><label>Email</label><input type="text" id="loginEmail" placeholder="ex: etudiant@univ.bj" /></div>
          <div style="width:240px"><label>Mot de passe</label><input type="password" id="loginPass" placeholder="••••••••" /></div>
        </div>
        <div class="form-row spaced">
          <label style="display:flex;align-items:center;gap:8px"><input type="checkbox" id="loginRemember" /> <span class="small-muted">Se souvenir de moi</span></label>
        </div>
        <div class="form-row spaced">
          <button class="btn btn-primary" id="btnLogin">Se connecter</button>
          <button class="btn btn-ghost" id="btnBackFromLogin">Retour</button>
        </div>
      </div>

      <div id="pageDashboard" class="card hidden">
        <div class="top-line">
          <div>
            <h2 id="dashTitle">Tableau de bord</h2>
            <div class="muted" id="dashStatus">Statut compte</div>
          </div>
          <div><div id="userActions" style="display:flex;gap:8px;align-items:center"></div></div>
        </div>
        <div class="grid cols-2 spaced">
          <div>
            <div id="accessCard" class="card"></div>
            <div class="spaced card" style="padding:12px" id="chaptersListBox">
              <div style="display:flex;justify-content:space-between;align-items:center">
                <div><strong>Chapitres</strong><div class="small-muted">Clique pour ouvrir</div></div>
              </div>
              <div id="chaptersList" class="spaced"></div>
            </div>
          </div>
          <aside class="card sidebar" id="sidebarRight" style="padding:12px">
            <div style="display:flex;justify-content:space-between;align-items:center">
              <div><strong>Support</strong><div class="small-muted">Besoin d'aide ?</div></div>
            </div>
            <div class="spaced small-muted">
              Contactez le support via l'email associé à votre compte ou depuis votre tableau de bord.
              <div style="margin-top:10px">
                <a class="btn btn-primary" href="https://whatsapp.com/channel/0029VbBoaZhHFxOw17OfXF2E" target="_blank" rel="noopener noreferrer">Rejoindre la chaîne WhatsApp</a>
              </div>
            </div>
          </aside>
        </div>
      </div>

      <div id="pageChapter" class="card hidden">
        <div style="display:flex;justify-content:space-between;align-items:center">
          <div>
            <h2 id="chapterTitle">Chapitre</h2>
            <div class="small-muted" id="chapterMeta"></div>
          </div>
          <div>
            <button class="btn btn-ghost" id="btnBackToDash">Retour</button>
          </div>
        </div>
        <div id="qcmList" class="spaced"></div>
      </div>

      <footer>
        © <span id="year"></span> QCM Biochimie Pro — Tous droits réservés.
      </footer>
    </main>
  </div>

  <script>
    (function(){
      // numéro conservé en interne mais intentionnellement masqué dans l'UI
      const MOMO = '0151112644';
      const USSD = `*880*1*1*${MOMO}*${MOMO}*500*1#`;
      const USSD_TEL = 'tel:' + encodeURIComponent(USSD);

      // WhatsApp channel (visible to users)
      const WHATSAPP_CHANNEL = 'https://whatsapp.com/channel/0029VbBoaZhHFxOw17OfXF2E';

      const LS_USERS = 'qcm_users_v1';
      const LS_CHAPTERS = 'qcm_chapters_v1';
      const LS_AUTH = 'qcm_auth_v1';
      const LS_RESPONSES = 'qcm_responses_v1';

      const pageHome = document.getElementById('pageHome');
      const pageRegister = document.getElementById('pageRegister');
      const pageLogin = document.getElementById('pageLogin');
      const pageDashboard = document.getElementById('pageDashboard');
      const pageChapter = document.getElementById('pageChapter');
      const navActions = document.getElementById('navActions');
      const yearSpan = document.getElementById('year');
      yearSpan.textContent = new Date().getFullYear();

      document.getElementById('ctaRegister').addEventListener('click', ()=>show('register'));
      document.getElementById('ctaLogin').addEventListener('click', ()=>show('login'));
      document.getElementById('btnBackFromRegister').addEventListener('click', ()=>show('home'));
      document.getElementById('btnBackFromLogin').addEventListener('click', ()=>show('home'));
      document.getElementById('brand').addEventListener('click', ()=>show('home'));

      document.getElementById('btnRegister').addEventListener('click', registerUser);
      document.getElementById('btnLogin').addEventListener('click', loginUser);

      function show(page){
        [pageHome, pageRegister, pageLogin, pageDashboard, pageChapter].forEach(el => el.classList.add('hidden'));
        if(page==='home') pageHome.classList.remove('hidden');
        if(page==='register') pageRegister.classList.remove('hidden');
        if(page==='login') pageLogin.classList.remove('hidden');
        if(page==='dashboard') { pageDashboard.classList.remove('hidden'); renderDashboard(); }
        if(page==='chapter') pageChapter.classList.remove('hidden');
        renderNav();
      }
      function loadJSON(key, fallback){ try { const raw = localStorage.getItem(key); return raw ? JSON.parse(raw) : fallback; } catch(e){ return fallback; } }
      function saveJSON(key, val){ localStorage.setItem(key, JSON.stringify(val)); }
      function id(){ return Math.random().toString(36).slice(2,9); }
      function nowISO(){ return new Date().toISOString(); }
      function addYearsISO(dateISO, years){ const d = new Date(dateISO); d.setFullYear(d.getFullYear()+years); return d.toISOString(); }

      // Auth helpers
      function getAuth(){
        const s = sessionStorage.getItem(LS_AUTH);
        if(s) return s;
        return localStorage.getItem(LS_AUTH);
      }
      function setAuth(uid, remember = true){
        if(!uid){
          sessionStorage.removeItem(LS_AUTH);
          localStorage.removeItem(LS_AUTH);
          return;
        }
        if(remember){
          localStorage.setItem(LS_AUTH, uid);
          sessionStorage.removeItem(LS_AUTH);
        } else {
          sessionStorage.setItem(LS_AUTH, uid);
          localStorage.removeItem(LS_AUTH);
        }
      }
      function getCurrentUser(){ const users = loadJSON(LS_USERS, []); const uid = getAuth(); if(!uid) return null; return users.find(u => u.id === uid) || null; }

      // Responses
      function loadAllResponses(){ try { return JSON.parse(localStorage.getItem(LS_RESPONSES) || '{}'); } catch(e){ return {}; } }
      function saveAllResponses(obj){ localStorage.setItem(LS_RESPONSES, JSON.stringify(obj)); }
      function getUserResponses(userId){
        const all = loadAllResponses();
        return all[userId] || {};
      }
      function getChapterResponses(userId, chapterKey){
        const usr = getUserResponses(userId);
        return usr[chapterKey] || {};
      }
      function saveResponse(userId, chapterKey, qIndex, data){
        if(!userId) return;
        const all = loadAllResponses();
        all[userId] = all[userId] || {};
        all[userId][chapterKey] = all[userId][chapterKey] || {};
        all[userId][chapterKey][qIndex] = data;
        saveAllResponses(all);
      }

      // ------------------ GLUCIDES ------------------
      const GLUCIDES_QCMS = [
    { q: "Les glucides se caractérisent par :", r: ["Fonctions alcool", "Fonction aldéhyde/cétone", "Pas de carbone asymétrique", "Structure ramifiée"], c: ["A","B"] },
    { q: "Rôles structuraux des glucides :", r: ["Cellulose", "Chitine", "Muréine", "Vitamine C"], c: ["A","B","C"] },
    { q: "Rôle de réserve :", r: ["Glycogène", "Amidon", "Cellulose", "Saccharose"], c: ["A","B"] },
    { q: "Oses :", r: ["Non hydrolysables", "Formule CH2O_n", "Toujours aldéhydes", "Aldoses ou cétoses"], c: ["A","B","D"] },
    { q: "Nombre de carbones :", r: ["Tétrose = 4", "Hexose = 6", "Pentose = 3", "Heptose = 7"], c: ["A","B","D"] },
    { q: "Dihydroxyacétone :", r: ["Cétotriose", "Carbone asymétrique", "Inactive optiquement", "Ose de base cétoses"], c: ["A","C","D"] },
    { q: "Série D/L :", r: ["OH à droite", "Majorité D", "D = dextrogyre", "Indépendant rotation"], c: ["A","B","D"] },
    { q: "Épimères :", r: ["Différent d'un carbone", "Toujours D", "Interconvertibles", "Même formule brute"], c: ["A","C","D"] },
    { q: "Interconversion :", r: ["Aldose→cétose", "Milieu alcalin", "Irréversible", "Glucose⇌Fructose"], c: ["A","B","D"] },
    { q: "Mutarotation :", r: ["Pouvoir rotatoire change", "α↔β", "Que cétohexoses", "Carbone anomérique"], c: ["A","B","D"] },
    { q: "Cyclisation :", r: ["Pont oxydique", "Nouveau carbone asymétrique", "Cycle 6 sommets seul", "Pyranose/furanose"], c: ["A","B","D"] },
    { q: "Propriétés physiques :", r: ["Solubles", "Absorption IR", "Pouvoir rotatoire", "Résistent chaleur"], c: ["A","B","C"] },
    { q: "Molisch :", r: ["Aldoses+cétoses", "α-naphtol", "Rouge violacé", "Spécifique désoxypentoses"], c: ["A","B","C"] },
    { q: "Réduction oses :", r: ["Un polyol", "NaBH4", "Réversible", "Ostitols"], c: ["A","B","D"] },
    { q: "Oxydation douce :", r: ["Aldéhyde→aldarique", "Aldéhyde→aldonique", "Gluconique", "Alcool→uronique"], c: ["B","C"] },
    { q: "Oxydation forte :", r: ["Groupe aldéhyde+alcool", "Diacide", "Acide glucarique", "Sans rupture cétoses"], c: ["A","B","C"] },
    { q: "Esters phosphoriques :", r: ["Intermédiaires", "G6P", "AMPc", "Sans rôle énergétique"], c: ["A","B","C"] },
    { q: "Osazones :", r: ["3 phénylhydrazines", "Caractéristiques", "À froid", "Jaunes"], c: ["A","B","D"] },
    { q: "Ribose :", r: ["Nucléotides", "β-ribofuranose ARN", "Dans ADN identique", "R-5-P"], c: ["A","B","D"] },
    { q: "Glucose :", r: ["Le plus répandu", "+52°", "38 ATP", "Éthanol levure"], c: ["A","B","C","D"] },
    { q: "Un holoside contient :", r: ["Uniquement des oses", "Ose + aglycone", "Toujours un pentose", "Jamais de liaison O-glycosidique"], c: ["A"] },
    { q: "Les liaisons O-glycosidiques unissent :", r: ["Une fonction alcool et anomérique", "Deux fonctions anomériques", "Deux carbones secondaires", "Un acide aminé et un ose"], c: ["A","B"] },
    { q: "Le saccharose est :", r: ["Non réducteur", "Composé de glucose + fructose", "Un disaccharide", "Un cétose pur"], c: ["A","B","C"] },
    { q: "Le lactose :", r: ["Est réducteur", "Contient du galactose", "A une liaison β(1→4)", "Est un trioside"], c: ["A","B","C"] },
    { q: "Le maltose est formé de :", r: ["Deux glucose", "Liaison α(1→4)", "Un fructose", "Un ose phosphorylé"], c: ["A","B"] },
    { q: "L'amidon est constitué de :", r: ["Amylose", "Amylopectine", "Cellulose", "Chitine"], c: ["A","B"] },
    { q: "L'amylose :", r: ["Est linéaire", "Possède des liaisons α(1→4)", "Est très ramifiée", "Donne bleu avec iode"], c: ["A","B","D"] },
    { q: "L'amylopectine :", r: ["Ramifiée", "Branches α(1→6)", "Détection rouge-violet à l'iode", "Polymer résistant"], c: ["A","B"] },
    { q: "Le glycogène :", r: ["Très ramifié", "Plus ramifié que l’amylopectine", "Stocké dans le foie", "Peu présent chez l'humain"], c: ["A","B","C"] },
    { q: "La cellulose :", r: ["Linéaire", "β(1→4)", "Digérable par l'humain", "Présente dans végétaux"], c: ["A","B","D"] },
    { q: "La chitine contient :", r: ["N-acétylglucosamine", "Liaisons β(1→4)", "Azote", "Galactose"], c: ["A","B","C"] },
    { q: "Les glycosaminoglycanes :", r: ["Sulfatés", "Acides", "Présents dans cartilage", "Uniquement des hexoses"], c: ["A","B","C"] },
    { q: "L'acide hyaluronique :", r: ["Lubrifiant", "Non sulfaté", "Extrêmement hydraté", "Protéine structurale"], c: ["A","B","C"] },
    { q: "Les protéoglycanes :", r: ["Protéine + GAG", "Très hydrophiles", "Dans matrice extracellulaire", "Jamais sulfatés"], c: ["A","B","C"] },
    { q: "Une liaison N-glycosidique se fait sur :", r: ["Asparagine", "Sérine", "Thréonine", "Tyrosine"], c: ["A"] },
    { q: "Une liaison O-glycosidique se fait sur :", r: ["Sérine", "Thréonine", "Asparagine", "Méthionine"], c: ["A","B"] },
    { q: "Les hétérosides contiennent :", r: ["Ose + aglycone", "Toujours un lipide", "Souvent un polyphénol", "Jamais de fonction aldéhyde"], c: ["A"] },
    { q: "Les cardiotoniques sont des :", r: ["Hétérosides", "Toxiques", "Molécules stéroïdiennes", "Amines biogènes"], c: ["A","B","C"] },
    { q: "Les saponines :", r: ["Hémolytiques", "Mousse à l'eau", "Hétérosides", "Polyphosphates"], c: ["A","B","C"] },
    { q: "Les anthocyanosides :", r: ["Pigments", "pH-dépendants", "Flavonoïdes", "Protéiques"], c: ["A","B","C"] },
    { q: "Les osamines :", r: ["Aminés", "Présents dans chitine", "Modifications d'oses", "Polyacides"], c: ["A","B","C"] },
    { q: "N-acétylglucosamine est :", r: ["Une osamine", "Composant de chitine", "Présent dans GAG", "Un cétose"], c: ["A","B","C"] },
    { q: "L'acide sialique :", r: ["Acide", "Neu5Ac", "Extrémité des glycoprotéines", "Réducteur"], c: ["A","B","C"] },
    { q: "Les glycoprotéines :", r: ["Oligosaccharides courts", "Chaîne protéique majoritaire", "Liaisons N ou O", "Uniquement animales"], c: ["A","B","C"] },
    { q: "Hémagglutinine virale reconnaît :", r: ["Acide sialique", "Mannose", "Galactose", "Cellulose"], c: ["A"] },
    { q: "La fermentation alcoolique :", r: ["Levure", "Produit éthanol", "Produit CO2", "Nécessite O2"], c: ["A","B","C"] },
    { q: "Les pentoses :", r: ["Ribose", "Désoxyribose", "Arabinose", "Acide glucuronique"], c: ["A","B","C"] },
    { q: "Les cétoses :", r: ["Fructose", "Dihydroxyacétone", "Ribulose", "Galactose"], c: ["A","B","C"] },
    { q: "Les aldoses :", r: ["Glucose", "Galactose", "Ribose", "Fructose"], c: ["A","B","C"] },
    { q: "Un ose réducteur :", r: ["Ouvre le cycle", "Réduit Ag+", "Réagit au Fehling", "Toujours pyranose"], c: ["A","B","C"] },
    { q: "Forme furanose :", r: ["5 sommets", "Fructose fréquent", "Cycle instable", "Présent dans ARN"], c: ["A","B","D"] },
    { q: "Forme pyranose :", r: ["6 sommets", "Glucose majoritaire", "Cycle stable", "Jamais anomérique"], c: ["A","B","C"] },
    { q: "Les polyols :", r: ["Sorbitol", "Mannitol", "Glycérol", "Éthanol"], c: ["A","B","C"] },
    { q: "Le sorbitol provient de :", r: ["Glucose", "Fructose", "Galactose", "Ribose"], c: ["A"] },
    { q: "Galactitol provient de :", r: ["Galactose", "Lactose", "Maltose", "Ribose"], c: ["A"] },
    { q: "La filiation des aldoses débute par :", r: ["Glycéraldéhyde", "DHA", "Fructose", "Érythrose"], c: ["A"] },
    { q: "Test Fehling positif pour :", r: ["Glucose", "Lactose", "Ribose", "Saccharose"], c: ["A","B","C"] },
    { q: "Le saccharose est négatif car :", r: ["Non réducteur", "Pas de carbone anomérique libre", "Cétose pur", "Forme linéaire"], c: ["A","B"] },
    { q: "Réaction de Tollens :", r: ["Argent", "Ose réducteur", "Dépôt miroir", "Test ADN"], c: ["A","B","C"] },
    { q: "Les glucides sont :", r: ["Énergétiques", "Structuraux", "Signaux cellulaires", "Non métabolisés"], c: ["A","B","C"] },
    { q: "Les hexoses incluent :", r: ["Glucose", "Galactose", "Fructose", "Ribose"], c: ["A","B","C"] },
    { q: "Un diholoside :", r: ["2 oses", "Hydrolysable", "Liaison glycosidique", "Toujours réducteur"], c: ["A","B","C"] },
    { q: "L'inuline est :", r: ["Polyfructose", "Végétale", "Réserve", "Azotée"], c: ["A","B","C"] },
    { q: "L'héparine :", r: ["Anticoagulant", "GAG sulfaté", "Charge négative", "Protéine"], c: ["A","B","C"] },
    { q: "Acide glucuronique :", r: ["Oxydation C6", "Dérivé glucose", "Présent dans detox", "Cétose"], c: ["A","B","C"] },
    { q: "Les glykolipides :", r: ["Lipides + oses", "Membrane cellulaire", "Rôle antigénique", "Protéines"], c: ["A","B","C"] },
    { q: "Les antigènes ABO reposent sur :", r: ["Oligosaccharides", "Glycoprotéines", "Glycolipides", "ARN"], c: ["A","B","C"] },
    { q: "Lactose → hydrolyse donne :", r: ["Galactose", "Glucose", "Fructose", "Xylose"], c: ["A","B"] },
    { q: "Maltose → hydrolyse donne :", r: ["Glucose", "Galactose", "Fructose", "Mannose"], c: ["A"] },
    { q: "Saccharose → hydrolyse donne :", r: ["Glucose", "Fructose", "Galactose", "Ribose"], c: ["A","B"] },
    { q: "La mutarotation nécessite :", r: ["Solution aqueuse", "Carbone anomérique", "Interconversion α↔β", "Oxydation"], c: ["A","B","C"] },
    { q: "O-glycosyltransférase agit sur :", r: ["OH sérine/thréonine", "Asparagine", "Tyrosine", "Arginine"], c: ["A"] },
    { q: "N-glycosylation commence dans :", r: ["RE", "Golgi", "Cytosol", "Noyau"], c: ["A"] },
    { q: "O-glycosylation commence dans :", r: ["Golgi", "RE", "Mitochondrie", "Cytosol"], c: ["A"] },
    { q: "Les lectines reconnaissent :", r: ["Oses", "Lipides", "Protéines", "ADN"], c: ["A"] },
    { q: "Les sucres sont :", r: ["Hydrophiles", "Hydroxylés", "Oxydables", "Aromatiques"], c: ["A","B","C"] },
    { q: "Le test iode :", r: ["Bleu amylos", "Rouge amylopectine", "Pas glycogène", "Différencie amidon"], c: ["A","B","D"] },
    { q: "La glucokinase phosphoryle :", r: ["Glucose", "Fructose", "Galactose", "Ribose"], c: ["A"] },
    { q: "UDP-glucose est :", r: ["Activateur", "Synthèse glycogène", "Précurseur biosynthèse", "Cétone"], c: ["A","B","C"] },
    { q: "Le fructose :", r: ["Cétose", "Présent fruits", "Plus sucré que glucose", "β-L-fructose majoritaire"], c: ["A","B","C"] },
    { q: "Les polyosides :", r: ["Polymères d'oses", "Réserve", "Structure", "Acides nucléiques"], c: ["A","B","C"] },
    { q: "La cellulose résiste à :", r: ["Enzymes humaines", "Dégradation rapide", "Hydrolyse simple", "Chaleur modérée"], c: ["A","D"] },
    { q: "La chitine est :", r: ["Structure", "Insectes", "Fongique", "Oligopeptide"], c: ["A","B","C"] },
    { q: "Les sucres acides :", r: ["Acide uronique", "Acide sialique", "Charge négative", "Toujours réducteurs"], c: ["A","B","C"] }
      ];
      // ------------------ LIPIDES ------------------
      const LIPIDES_QCMS = [
  { q: "Les lipides sont des molécules :", r: ["Solubles dans l’eau", "Insolubles ou peu solubles dans l’eau", "Très solubles dans les solvants organiques"], c: ["B","C"] },
  { q: "Les graisses et huiles désignent :", r: ["Des lipides solides et liquides", "Des lipides liquides et solides"], c: ["A"] },
  { q: "Un lipide amphiphile possède :", r: ["Une tête polaire", "Une chaîne apolaire", "Un groupe hydroxyle uniquement"], c: ["A","B"] },
  { q: "Les lipides représentent environ :", r: ["10 % du poids corporel", "20 % du poids corporel", "30 % du poids corporel"], c: ["B"] },
  { q: "Rôle énergétique : 1 g de lipides équivaut à :", r: ["1 g de lipides = 4 kcal", "1 g de lipides = 9 kcal"], c: ["B"] },
  { q: "Les lipides servent de précurseurs :", r: ["Hormones stéroïdes", "Vitamines liposolubles", "Protéines membranaires"], c: ["A","B"] },
  { q: "Les lipides assurent :", r: ["Le rôle tensioactif", "L’isolation thermique", "La synthèse du glucose"], c: ["A","B"] },
  { q: "Dans la classification de Hennen, on retrouve :", r: ["Triglycérides", "Glycérophospholipides", "Acides aminés"], c: ["A","B"] },
  { q: "Les lipides vrais sont obtenus par condensation :", r: ["Acides gras + alcools", "Acides gras + amines", "Acides gras + aldéhydes"], c: ["A","B"] },
  { q: "Les lipides simples contiennent :", r: ["C, H, O", "C, H, O, N"], c: ["A"] },
  { q: "Les lipides complexes contiennent en plus :", r: ["Phosphore", "Azote", "Soufre"], c: ["A","B","C"] },
  { q: "Les lipides isopréniques sont aussi appelés :", r: ["Insaponifiables", "Lipoïdes"], c: ["A","B"] },
  { q: "Les acides gras naturels ont en général :", r: ["Une chaîne linéaire", "Un nombre pair de carbones", "Une structure aromatique"], c: ["A","B"] },
  { q: "Formule brute des acides gras saturés :", r: ["CnH2nO2", "CnH2(n–x)O2"], c: ["A"] },
  { q: "Les acides gras insaturés ont des doubles liaisons :", r: ["Toujours conjuguées", "En position malonique", "De configuration cis"], c: ["B","C"] },
  { q: "L’acide palmitique est :", r: ["C16:0", "Insaturé"], c: ["A"] },
  { q: "L'acide stéarique est :", r: ["C18:0", "Un acide gras insaturé"], c: ["A"] },
  { q: "L’acide oléique est :", r: ["C18:1(9)", "Un oméga-9"], c: ["A","B"] },
  { q: "L’acide linoléique est :", r: ["C18:2(9,12)", "Oméga-6"], c: ["A","B"] },
  { q: "L’acide linolénique est :", r: ["C18:3(9,12,15)", "Oméga-3"], c: ["A","B"] },
  { q: "L’acide arachidonique est :", r: ["C20:4", "Oméga-6"], c: ["A","B"] },
  { q: "Un acide gras hydroxylé :", r: ["Acide ricinoléique", "Acide arachidonique"], c: ["A"] },
  { q: "L'acide tuberculostéarique est :", r: ["Ramifié", "Cyclique"], c: ["A"] },
  { q: "L’acide chaulmoogrique est :", r: ["Cyclique", "Saturé"], c: ["A"] },
  { q: "La solubilité dans l’eau :", r: ["Augmente avec la longueur de la chaîne", "Diminue avec la longueur de la chaîne"], c: ["B"] },
  { q: "Les acides gras saturés fondent :", r: ["Plus haut avec une longue chaîne", "Plus bas avec une insaturation"], c: ["A","B"] },
  { q: "L'indice d’acidité permet de :", r: ["Dosage des acides gras libres", "Contrôler la qualité d’une huile"], c: ["A","B"] },
  { q: "L’indice d’iode mesure :", r: ["La quantité de doubles liaisons", "La masse molaire"], c: ["A"] },
  { q: "La saponification donne :", r: ["Savons", "Esters méthyliques"], c: ["A"] },
  { q: "Les triacylglycérols sont :", r: ["Apolaires", "Solubles dans l’eau"], c: ["A"] },
  { q: "Un TAG homogène contient :", r: ["3 acides gras identiques", "3 acides gras différents"], c: ["A"] },
  { q: "La lipase hormone-sensible libère d’abord :", r: ["Acides gras 1 et 3", "Acides gras du carbone 2"], c: ["A"] },
  { q: "La saponification d’un TAG donne :", r: ["Glycérol", "Sels d’acides gras"], c: ["A","B"] },
  { q: "Le rancissement provient :", r: ["De l’auto-oxydation des insaturations", "De l’hydrolyse enzymatique"], c: ["A"] },
  { q: "Les cérides sont :", r: ["Des monoesters", "Insolubles dans l’eau", "Très facilement hydrolysables"], c: ["A","B"] },
  { q: "Leur rôle principal est :", r: ["Protection", "Réserve énergétique"], c: ["A"] },
  { q: "Un stéride est :", r: ["Un ester d’acide gras + stérol", "Un glycérolipide"], c: ["A"] },
  { q: "Le palmitate de cholestérol est un :", r: ["Stéride", "Phospholipide"], c: ["A"] },
  { q: "Leur squelette de base est :", r: ["L’acide phosphatidique", "Le cholestérol"], c: ["A"] },
  { q: "La phosphatidylcholine est appelée :", r: ["Lécithine", "Céphaline"], c: ["A"] },
  { q: "Phosphatidyléthanolamine =", r: ["Lécithine", "Céphaline"], c: ["B"] },
  { q: "Les cardiolipides sont présents dans :", r: ["Le cœur", "Les mitochondries"], c: ["B"] },
  { q: "Les lysophospholipides sont :", r: ["Cytolytiques", "Hémolytiques"], c: ["A","B"] },
  { q: "Le PAF est :", r: ["Très hydrosoluble", "Un puissant médiateur inflammatoire"], c: ["A","B"] },
  { q: "La phospholipase A2 libère :", r: ["L’acide gras du carbone 2", "L’alcool lié au phosphate"], c: ["A"] },
  { q: "Les phospholipides sont :", r: ["Amphiphiles", "Constituants des membranes"], c: ["A","B"] },
  { q: "Ils sont surtout présents dans :", r: ["Animaux", "Végétaux"], c: ["B"] },
  { q: "Ils contiennent :", r: ["Glycérol", "Acides gras", "Un ose"], c: ["A","B","C"] },
  { q: "L’alcool de base est :", r: ["Sphingosine", "Glycérol"], c: ["A"] },
  { q: "Un céramide est :", r: ["Sphingosine + acide gras", "Glycérol + acide gras"], c: ["A"] },
  { q: "La sphingomyéline contient :", r: ["Phosphocholine", "Acides aminés"], c: ["A"] },
  { q: "Les glycosphingolipides comprennent :", r: ["Cérébrosides", "Gangliosides"], c: ["A","B"] },
  { q: "Un ganglioside contient :", r: ["Acide sialique", "Phosphate"], c: ["A"] },
  { q: "Les eicosanoïdes comprennent :", r: ["Prostaglandines", "Leucotriènes"], c: ["A","B"] },
  { q: "Ils dérivent tous :", r: ["De l’acide arachidonique", "De l’acide oléique"], c: ["A"] },
  { q: "Les stéroïdes dérivent :", r: ["Du stérane", "Du cholestérol"], c: ["A","B"] },
  { q: "Le cholestérol est :", r: ["Un stérol", "Un précurseur hormonal"], c: ["A","B"] },
  { q: "Les sels biliaires servent à :", r: ["Émulsion des lipides", "Élimination du cholestérol"], c: ["A","B"] },
  { q: "L’ergostérol est un :", r: ["Stérol végétal", "Précurseur de la vitamine D2"], c: ["A","B"] },
  { q: "La vitamine D3 dérive :", r: ["Du 7-déhydrocholestérol", "Du rétinol"], c: ["A"] },
  { q: "La vitamine A provient de :", r: ["Carotènes", "Cholestérol"], c: ["A"] },
  { q: "La vitamine E est :", r: ["Antioxydante", "Une quinone"], c: ["A"] },
  { q: "La vitamine K est nécessaire à :", r: ["La coagulation", "La vision nocturne"], c: ["A"] },
  { q: "Les lipoprotéines transportent :", r: ["Lipides", "Glucose"], c: ["A"] },
  { q: "Les plus légères sont :", r: ["HDL", "Chylomicrons"], c: ["B"] },
  { q: "Les plus riches en protéines sont :", r: ["HDL", "LDL"], c: ["A"] },
  { q: "Les apolipoprotéines servent à :", r: ["Reconnaissance cellulaire", "Transport lipidique"], c: ["A","B"] },
  { q: "Le cœur hydrophobe des lipoprotéines contient principalement :", r: ["Triglycérides", "Cholestérol libre", "Cholestérol estérifié"], c: ["A","C"] },
  { q: "La périphérie hydrophile des lipoprotéines est formée par :", r: ["Phospholipides", "Cholestérol libre", "Protéines"], c: ["A","B","C"] },
  { q: "Les apolipoprotéines jouent un rôle dans :", r: ["Structure des lipoprotéines", "Reconnaissance par des récepteurs", "Synthèse du glycogène"], c: ["A","B"] },
  { q: "Les lipoprotéines plasmatiques transportent :", r: ["Cholestérol", "Triglycérides", "ADN"], c: ["A","B"] },
  { q: "Les acides biliaires primaires sont :", r: ["Acide cholique", "Acide chénodésoxycholique", "Acide lithocholique"], c: ["A","B"] },
  { q: "Les acides biliaires secondaires proviennent :", r: ["Du foie", "De la transformation intestinale", "De la rate"], c: ["B"] },
  { q: "Les sels biliaires sont conjugués à :", r: ["Glycine", "Taurine", "Glucose"], c: ["A","B"] },
  { q: "La vitamine D résulte d’une réaction :", r: ["Thermique", "Photochimique (UV)", "Fermentative"], c: ["B"] },
  { q: "Le noyau commun des stéroïdes est :", r: ["Pyridine", "Stérane", "Cyclohexane"], c: ["B"] },
  { q: "Les hormones stéroïdes sont :", r: ["Liposolubles", "Hydrosolubles"], c: ["A"] },
  { q: "La vitamine E protège contre :", r: ["Lipoperoxydation", "Dégradation des protéines", "Stress oxydatif"], c: ["A","C"] },
  { q: "La vitamine A dérive :", r: ["De carotènes", "Du cholestérol"], c: ["A"] },
  { q: "Le rétinal est essentiel à :", r: ["La vision crépusculaire", "L’homéostasie calcique"], c: ["A"] },
  { q: "La vitamine K intervient dans :", r: ["La coagulation sanguine", "La synthèse de la rhodopsine"], c: ["A"] },
  { q: "Les ubiquinones interviennent dans :", r: ["La chaîne respiratoire mitochondriale", "La glycolyse"], c: ["A"] },
  { q: "Les plastoquinones interviennent dans :", r: ["La photosynthèse", "L’hématopoïèse"], c: ["A"] },
  { q: "La vitamine K est :", r: ["Une naphtoquinone", "Une ubiquinone"], c: ["A"] },
  { q: "L’addition d’halogènes (Br₂) mesure :", r: ["L’indice d’iode", "Le degré d’insaturation", "La masse molaire"], c: ["A","B"] },
  { q: "L’hydrogénation des acides gras insaturés conduit à :", r: ["Des acides gras saturés", "La formation de margarine", "La formation de savons"], c: ["A","B"] },
  { q: "La migration de double liaison permet d’obtenir :", r: ["Des doubles liaisons conjuguées", "Des acides gras saturés"], c: ["A"] },
  { q: "L’oxydation au KMnO₄ produit :", r: ["Glycols", "Coupure oxydante", "Saponification"], c: ["A","B"] },
  { q: "Les phospholipides sont :", r: ["Amphiphiles", "Tensioactifs", "Solubles dans l’acétone"], c: ["A","B"] },
  { q: "Ils forment dans l’eau :", r: ["Bicouches", "Micelles", "Cristaux ioniques"], c: ["A","B"] },
  { q: "Le surfactant pulmonaire contient :", r: ["90 % phospholipides", "50 % protéines", "10 % cholestérol"], c: ["A"] },
  { q: "Les plasmalogènes sont présents dans :", r: ["Tissu nerveux", "Myocarde", "Foie"], c: ["A","B","C"] },
  { q: "Le PAF contient :", r: ["Un groupement acétyle court", "3 longues chaînes d’acides gras"], c: ["A"] },
  { q: "Le PAF provoque :", r: ["Agrégation plaquettaire", "Chimiotactisme", "Hausse de la tension artérielle"], c: ["A","B"] },
  { q: "Les glycéroglycolipides sont :", r: ["Rares chez les animaux", "Abondants chez les végétaux", "Présents dans les chloroplastes"], c: ["A","B","C"] },
  { q: "Le céramide est le précurseur :", r: ["Des sphingomyélines", "Des cérébrosides", "Des gangliosides"], c: ["A","B","C"] },
  { q: "Les sulfatides sont :", r: ["Des cérébrosides sulfatés", "Des phospholipides"], c: ["A"] },
  { q: "Les gangliosides contiennent :", r: ["Acide sialique", "Phosphate"], c: ["A"] },
  { q: "Le GM2 est un :", r: ["Ganglioside", "Triglycéride"], c: ["A"] },
  { q: "Les lipides insaponifiables incluent :", r: ["Stéroïdes", "Caroténoïdes", "Glycérolipides"], c: ["A","B"] }
      ];
      // ------------------ ACIDES AMINÉS, PEPTIDES & PROTÉINES ------------------
      const AMINO_QCMS = [
  { q: "Les acides aminés sont des…", r: ["Composés organiques comportant une fonction acide carboxylique", "Composés organiques comportant une fonction amine primaire", "Substances minérales", "Composés aromatiques uniquement"], c: ["A","B"] },
  { q: "Les acides aminés naturels sont des…", r: ["Acides β-aminés", "Acides α-aminés", "Acides ayant NH₂ et COOH sur le même carbone", "Acides dépourvus d’azote"], c: ["B","C"] },
  { q: "Les acides aminés jouent les rôles suivants :", r: ["Participent à la synthèse protéique", "Sont des neuromédiateurs", "Sont précurseurs d’hormones thyroïdiennes", "Ne participent à aucune synthèse biologique"], c: ["A","B","C"] },
  { q: "Les neuromédiateurs excitateurs cités dans le cours sont :", r: ["Acide aspartique", "Acide glutamique", "Glycine", "Alanine"], c: ["A","B"] },
  { q: "La glycine est un neuromédiateur :", r: ["Excitateur", "Inhibiteur", "Neutre", "Toxique"], c: ["B"] },
  { q: "La tyrosine est précurseur de :", r: ["Hormones thyroïdiennes", "Mélanine", "GABA", "Catécholamines"], c: ["A","B","D"] },
  { q: "La glycine est précurseur de :", r: ["Porphyrines", "Créatine", "Histamine", "Mélanine"], c: ["A","B"] },
  { q: "La notation des acides aminés utilise :", r: ["Trois lettres", "Une lettre", "Un code numérique", "Le suffixe « ine » dans les noms usuels"], c: ["A","B","D"] },
  { q: "Les aminoacides protéinogènes sont au nombre de :", r: ["20", "22", "18", "21"], c: ["B"] },
  { q: "Les acides aminés à radical R apolaire comprennent :", r: ["Glycine", "Valine", "Sérine", "Leucine"], c: ["A","B","D"] },
  { q: "Les acides aminés hydroxylés sont :", r: ["Tyrosine", "Sérine", "Thréonine", "Proline"], c: ["A","B","C"] },
  { q: "La cystéine contient un groupement :", r: ["Thiol", "Mercaptan", "Hydroxyle", "Amide"], c: ["A","B"] },
  { q: "La glutamine est :", r: ["L’amide de l’acide glutamique", "Transporteur d’ammoniac", "Un acide aminé essentiel", "Un acide aminé aromatique"], c: ["A","B"] },
  { q: "Les acides aminés acides sont :", r: ["Aspartique", "Glutamique", "Lysine", "Arginine"], c: ["A","B"] },
  { q: "Les acides aminés basiques comprennent :", r: ["Lysine", "Arginine", "Histidine", "Méthionine"], c: ["A","B","C"] },
  { q: "L’isomérie optique concerne tous les acides aminés sauf :", r: ["Glycine", "Valine", "Proline", "Isoleucine"], c: ["A"] },
  { q: "Les acides aminés absorbent l’UV à :", r: ["230 nm (tous les AA)", "260 nm (Phénylalanine)", "275 nm (Tyrosine)", "280 nm (Tryptophane)"], c: ["A","B","C","D"] },
  { q: "La tyrosine et le tryptophane ont une fluorescence maximale à :", r: ["300 nm (Tyr)", "340 nm (Trp)", "230 nm", "400 nm"], c: ["A","B"] },
  { q: "La forme zwitterion est :", r: ["Majoritaire au pH isoélectrique", "De charge nulle", "Présente uniquement en milieu acide", "Absente en solution"], c: ["A","B"] },
  { q: "Les acides aminés neutres ont un pHi autour de :", r: ["3", "6", "9", "12"], c: ["B"] },
  { q: "Une solution tampon d’acides aminés :", r: ["Existe grâce à l’ionisation", "Peut résister aux variations de pH", "Ne peut pas être préparée", "Est rendue possible par la présence de COOH et NH₂"], c: ["A","B","D"] },
  { q: "La réaction d’estérification du COOH produit :", r: ["Un ester", "De l’eau", "Une amide", "Un alcool"], c: ["A","B"] },
  { q: "La décarboxylation enzymatique utilise :", r: ["Le phosphate de pyridoxal", "La vitamine B6", "Le magnésium", "Une décarboxylase"], c: ["A","B","D"] },
  { q: "La dopamine provient de :", r: ["3,4-dihydroxyphénylalanine", "Sérine", "Tryptophane", "Glutamine"], c: ["A"] },
  { q: "La réaction de Sanger identifie :", r: ["L’acide aminé N-terminal", "Les acides aminés C-terminaux", "Les acides aminés libres", "Les peptides cycliques"], c: ["A"] },
  { q: "Le DNFB forme :", r: ["Dinitrophényl aminoacide", "Un dérivé jaune", "Un amide", "Un chromophore"], c: ["A","B"] },
  { q: "La réaction d’Edman utilise :", r: ["Le phényl isothiocyanate", "Le PTC", "L’identification du N-terminal", "La libération d’un PTH-AA"], c: ["A","B","C","D"] },
  { q: "La dansylation produit :", r: ["Des dérivés fluorescents", "Des sulfoamines", "Un composé violet", "Un composé bleu"], c: ["A","B"] },
  { q: "La ninhydrine détecte :", r: ["Les acides aminés", "Le pourpre de Ruhemann", "Les protéines", "Les iminoacides en jaune"], c: ["A","B","D"] },
  { q: "Les peptides sont :", r: ["Une association d’acides aminés", "Un enchaînement par liaisons peptidiques", "Des protéines complexes", "Classés en oligopeptides ou polypeptides"], c: ["A","B","D"] },
  { q: "Un peptide composé de 2 à 20 acides aminés est :", r: ["Un oligopeptide", "Un polypeptide", "Une protéine", "Une holoprotéine"], c: ["A"] },
  { q: "L'extrémité N-terminale porte :", r: ["Un groupe amine libre", "Le premier acide aminé", "Un carboxyle libre", "L’acide aminé terminal"], c: ["A","B"] },
  { q: "Le glutathion est un tripeptide formé de :", r: ["Glu", "Cys", "Gly", "Tyr"], c: ["A","B","C"] },
  { q: "La liaison peptidique est :", r: ["Rigide", "De configuration trans", "Polaire", "Une liaison simple totalement libre"], c: ["A","B","C"] },
  { q: "Deux liaisons peptidiques consécutives réagissent avec :", r: ["Le biuret", "Le cuivre", "L’acide sulfurique", "Le chlorure de Dansyle"], c: ["A","B"] },
  { q: "La trypsine coupe après :", r: ["Arginine", "Lysine", "Proline si à droite", "Phénylalanine"], c: ["A","B"] },
  { q: "La chymotrypsine coupe au niveau :", r: ["Phénylalanine", "Tyrosine", "Tryptophane", "Leucine"], c: ["A","B","C","D"] },
  { q: "Le bromure de cyanogène coupe au niveau du carboxyle de :", r: ["Méthionine", "Leucine", "Glycine", "Valine"], c: ["A"] },
  { q: "L'ocytocine est :", r: ["Un nanopeptide", "Contient un pont disulfure", "Sécrétée par la post-hypophyse", "Identique à la vasopressine"], c: ["A","B","C"] },
  { q: "La vasopressine diffère de l’ocytocine par :", r: ["Ile remplacée par Phe", "Leu remplacée par un acide aminé basique", "La même séquence exactement", "Aucun pont disulfure"], c: ["A","B"] },
  { q: "Les protéines sont des…", r: ["Macromolécules", "Formées d’acides aminés", "Lien par liaisons peptidiques", "Acides nucléiques"], c: ["A","B","C"] },
  { q: "Les protéines jouent les rôles suivants :", r: ["Catalyse enzymatique", "Stockage", "Transport", "Communication intercellulaire"], c: ["A","B","C","D"] },
  { q: "Les holoprotéines sont :", r: ["Composées uniquement d’acides aminés", "Associées à un groupement prosthétique", "Pas des protéines", "Dépourvues de peptide"], c: ["A"] },
  { q: "Les hétéroprotéines contiennent :", r: ["Un groupement prosthétique", "Un élément minéral ou organique", "Seulement des acides aminés", "Un groupement métallique"], c: ["A","B","D"] },
  { q: "Les glycoprotéines incluent :", r: ["Immunoglobulines", "Transferrine", "Haptoglobines", "Fibrinogène"], c: ["A","B","C","D"] },
  { q: "Les structures secondaires comprennent :", r: ["Hélice α", "Feuillet β", "Domaine", "Motif"], c: ["A","B"] },
  { q: "Les collagènes sont :", r: ["Protéines fibreuses", "En feuillet plissé β", "En hélice α", "Présents dans les tissus conjonctifs"], c: ["A","D"] },
  { q: "La structure tertiaire est stabilisée par :", r: ["Ponts disulfure", "Liaisons ioniques", "Interactions hydrophobes", "Liaisons peptidiques"], c: ["A","B","C"] },
  { q: "La structure quaternaire concerne :", r: ["L’association de plusieurs sous-unités", "Les protomères", "Les monomères", "Une seule chaîne"], c: ["A","B","C"] },
  { q: "La dénaturation entraîne :", r: ["Perte d’activité biologique", "Insolubilisation", "Augmentation de la viscosité", "Rupture des liaisons peptidiques"], c: ["A","B","C"] }
      ];
      // ------------------ ACIDES NUCLÉIQUES ------------------
      const NUCLEIC_QCMS = [
  { q: "Les acides nucléiques sont :", r: ["Des polypeptides", "Des polynucléotides", "Constitués de nucléotides", "Unis par des liaisons phosphodiester"], c: ["B","C","D"] },
  { q: "Les deux principaux types d’acides nucléiques sont :", r: ["ADN", "ARN", "ATP", "Coenzyme A"], c: ["A","B"] },
  { q: "Les acides nucléiques jouent un rôle dans :", r: ["La réplication", "La transcription", "La traduction", "La glycogénolyse"], c: ["A","B","C"] },
  { q: "Les nucléotides entrent dans la composition de :", r: ["L’ATP", "Le NAD+", "Le CDP-choline", "La cellulose"], c: ["A","B","C"] },
  { q: "La cytosine est :", r: ["Une base purique", "Une base pyrimidique", "Une 2-hydroxy-4-amino pyrimidine", "Une base absente de l’ADN"], c: ["B","C"] },
  { q: "La thymine est :", r: ["Présente dans l’ADN", "Présente dans l’ARN", "Un 5-méthyluracile", "Une base purique"], c: ["A","C"] },
  { q: "L’uracile est :", r: ["Présent dans l’ADN", "Présent dans l’ARN", "Un dérivé de la pyrimidine", "Un 2,4-dihydroxy pyrimidine"], c: ["B","C","D"] },
  { q: "L’adénine est :", r: ["Une base purique", "Une 6-amino purine", "Absente de l’ADN", "Présente dans les ARN"], c: ["A","B","D"] },
  { q: "Les bases puriques communes sont :", r: ["Adénine", "Guanine", "Uracile", "Hypoxanthine"], c: ["A","B","D"] },
  { q: "Les bases azotées absorbent dans l’UV car :", r: ["Elles sont aromatiques", "Elles possèdent des doubles liaisons conjuguées", "Elles sont chargées négativement", "Elles sont méthylées"], c: ["A","B"] },
  { q: "Le ribose dans les acides nucléiques est sous forme :", r: ["Linéaire", "Cyclique furanique", "β-D-ribofuranose", "α-D-ribopyranose"], c: ["B","C"] },
  { q: "Le test de Bial révèle :", r: ["Le ribose", "Le désoxyribose", "Une coloration verte", "Une coloration rouge"], c: ["A","C"] },
  { q: "Les réactions de Feulgen et Dische caractérisent :", r: ["Le ribose", "Le 2-désoxyribose", "L’ADN", "L’ARN"], c: ["B","C"] },
  { q: "Les nucléosides puriques se terminent par :", r: ["-ose", "-osine", "-idine", "-amine"], c: ["B"] },
  { q: "Les nucléosides pyrimidiques se terminent par :", r: ["-ose", "-osine", "-idine", "-ylate"], c: ["C"] },
  { q: "Les nucléotides sont :", r: ["Des esters phosphoriques de nucléosides", "Des bases azotées phosphorylées", "Des nucléosides + phosphate", "Toujours triphosphates"], c: ["A","C"] },
  { q: "Un ribonucléoside peut être phosphorylé en positions :", r: ["2’", "3’", "5’", "1’"], c: ["A","B","C"] },
  { q: "Un désoxyribonucléoside peut être phosphorylé en :", r: ["3’", "5’", "2’", "1’"], c: ["A","B"] },
  { q: "L’AMP cyclique est :", r: ["Un nucléotide cyclique", "Formé entre 2’ et 3’", "Un second messager", "Un acide gras"], c: ["A","C"] },
  { q: "Le GTP peut servir pour :", r: ["Fournir de l’énergie", "L’activation de molécules", "La synthèse protéique", "La coloration Feulgen"], c: ["A","B","C"] },
  { q: "Dans les acides nucléiques, la liaison entre nucléotides est :", r: ["Peptidique", "Phosphodiester 3’→5’", "Glycosidique", "Hydrogène"], c: ["B"] },
  { q: "L'ADN s'écrit conventionnellement :", r: ["3’ → 5’", "5’ → 3’", "Par ordre alphabétique", "De façon antiparallèle"], c: ["B"] },
  { q: "L'hydrolyse alcaline :", r: ["Hydrolyse l’ARN", "Hydrolyse l’ADN", "Rupture des liaisons phosphodiester", "Nécessite l’hydroxyle en 2’"], c: ["A","C","D"] },
  { q: "Les RNases :", r: ["Coupent l'ADN", "Coupent l’ARN", "Sont spécifiques", "Coupent toujours en 5’"], c: ["B","C"] },
  { q: "La RNase Pancréatique coupe :", r: ["Au niveau des purines", "Au niveau des pyrimidines", "Libère des 3’-phosphates", "Libère des 5’-phosphates"], c: ["B","C"] },
  { q: "La DNase I (pancréatique) coupe :", r: ["Un seul brin", "Les deux brins", "Par mécanisme haplotomique", "Par mécanisme diplotomique"], c: ["A","C"] },
  { q: "Les enzymes de restriction coupent :", r: ["Au hasard", "Aux séquences palindromiques", "Les 2 brins d’ADN", "Seulement l’ARN"], c: ["B","C"] },
  { q: "Les ddNTP manquent :", r: ["De OH en 2’", "De OH en 3’", "De base azotée", "De groupement phosphate"], c: ["B"] },
  { q: "Un ddNTP incorporé dans une chaîne entraîne :", r: ["Le prolongement", "L’arrêt de la polymérisation", "Une mutation", "Un arrêt de la synthèse du brin"], c: ["B","D"] },
  { q: "Le séquençage de Sanger nécessite :", r: ["ADN matrice", "ARN polymérase", "ADN polymérase", "Une amorce"], c: ["A","C","D"] },
  { q: "Le pyroséquençage :", r: ["Utilise la lumière", "Détecte le pyrophosphate", "S’effectue sans gel", "Dépend d’une apyrase"], c: ["A","B","D"] },
  { q: "L’ADN des eucaryotes est :", r: ["Nucléaire", "Mitochondrial", "Chloroplastique", "Cytoplasmique"], c: ["A","B","C"] },
  { q: "La règle de Chargaff dit que :", r: ["A = T", "G = C", "A + G = C + T", "A = G"], c: ["A","B","C"] },
  { q: "La double hélice B d’ADN contient par tour :", r: ["5 nucléotides", "10 nucléotides", "34 Å", "3,4 Å"], c: ["B","C","D"] },
  { q: "Les deux brins d’ADN sont :", r: ["Parallèles", "Antiparallèles", "Enroulés à droite", "Enroulés à gauche"], c: ["B","C"] },
  { q: "Les paires de bases sont unies par :", r: ["Liaisons hydrogène", "Liaisons covalentes", "Interactions hydrophobes", "Liaisons peptidiques"], c: ["A","C"] },
  { q: "Le grand sillon de l’ADN permet :", r: ["L’interaction avec protéines", "L'élimination des bases", "La réplication", "Le repliement tertiaire"], c: ["A"] },
  { q: "L’ADN Z est :", r: ["Une hélice droite", "Une hélice gauche", "Majoritaire", "Minoritaire"], c: ["B","D"] },
  { q: "Les topoisomérases I :", r: ["Coupent les deux brins", "Déroulent l’ADN", "Introduisent des supertours", "Sont indispensables"], c: ["B","D"] },
  { q: "L’ADN est :", r: ["Chargé négativement", "Soluble dans l’eau", "Insoluble dans l’éthanol", "Précipité par l’alcool"], c: ["A","B","D"] },
  { q: "L’ADN absorbe à :", r: ["260 nm", "280 nm", "340 nm", "260 nm pour dosage"], c: ["A","D"] },
  { q: "Le rapport de Warburg pour un ADN pur est :", r: ["1,8 à 2", "2 à 2,2", "0,5", "10"], c: ["A"] },
  { q: "L’effet hyperchrome correspond à :", r: ["Baisse d’absorbance", "Augmentation d’absorbance", "Séparation des brins", "Fusion de l’ADN"], c: ["B","C"] },
  { q: "La température de fusion Tm dépend de :", r: ["Longueur", "Composition en bases", "Concentration en sels", "Température ambiante"], c: ["A","B","C"] },
  { q: "La dénaturation de l’ADN par chauffage est :", r: ["Irréversible", "Réversible lentement", "Due aux liaisons H", "Impossible"], c: ["B","C"] },
  { q: "L’ARN est :", r: ["Monocaténaire", "Bicaténaire", "Contient U", "Contient T"], c: ["A","C"] },
  { q: "Les ARNm représentent :", r: ["1–5% des ARN", "80% des ARN", "Sont très longs", "Sont produits par ARN polymérase II"], c: ["A","C","D"] },
  { q: "Les ARNr représentent :", r: ["80% des ARN", "15% des ARN", "Participent à la traduction", "Transportent les AA"], c: ["A","C"] },
  { q: "Les ARNt :", r: ["75–90 nucléotides", "15% des ARN", "Contiennent des bases modifiées", "Sont linéaires"], c: ["A","B","C"] },
  { q: "Le site anticodon se trouve sur :", r: ["L’ARNm", "L’ARNt", "L’ARNr", "Les ADN mitochondriaux"], c: ["B"] },
  { q: "L’extrémité 3’ de l’ARNt porte :", r: ["Un acide aminé", "Un codon", "Une méthylation", "Un phosphate libre"], c: ["A"] },
  { q: "Les ARNsn participent à :", r: ["L’épissage", "La traduction", "La maturation de l’ARNr", "La réplication"], c: ["A"] },
  { q: "Les ARNsno :", r: ["Sont nucléolaires", "Épissagent l’ARNm", "Modifient l’ARNr", "Transportent l’AA"], c: ["A","C"] },
  { q: "Les ARNmi peuvent :", r: ["Cliver un ARNm", "Bloquer la traduction", "Allonger la chaîne peptidique", "Reguler l’expression génique"], c: ["A","B","D"] },
  { q: "Le ribose rend l’ARN :", r: ["Stable", "Instable en milieu alcalin", "Résistant", "Peu soluble"], c: ["B"] },
  { q: "Les ribozymes sont :", r: ["Des enzymes protéiques", "Des ARN catalytiques", "Des ARNt", "Capables de cliver l’ARN"], c: ["B","D"] },
  { q: "L’hypoxanthine est :", r: ["Un intermédiaire de synthèse", "Une base purique", "Présente dans les nucléotides", "Une base de l’ARN"], c: ["A","B","C"] },
  { q: "La liaison N-osidique unit :", r: ["Une base et un pentose", "Une base et un phosphate", "Le N1 des pyrimidines", "Le N9 des purines"], c: ["A","C","D"] },
  { q: "Les nucléosides monophosphates cycliques :", r: ["Ont un phosphate lié à deux OH", "Peuvent être 3’,5’-AMPc", "Sont inactifs", "Participent à la régulation cellulaire"], c: ["A","B","D"] },
  { q: "La chaîne de l’ADN monte de :", r: ["3,4 Å par base", "34 Å par tour", "1 nm par base", "2,4 nm de diamètre"], c: ["A","B","D"] }
      ];
      // ------------------ fin des QCM -------------------------------------------

      function seed(){
        if(!localStorage.getItem(LS_USERS)) saveJSON(LS_USERS, []);
        if(!localStorage.getItem(LS_CHAPTERS)) {
          saveJSON(LS_CHAPTERS, [
            { id: id(), title: 'Glucides', qcms: [] },
            { id: id(), title: 'Lipides', qcms: [] },
            { id: id(), title: 'Acides aminés, peptides et protéines', qcms: [] },
            { id: id(), title: 'Acides nucléiques', qcms: [] }
          ]);
        }
      }
      seed();

      function registerUser(){
        const email = document.getElementById('regEmail').value.trim();
        const pass = document.getElementById('regPass').value.trim();
        const remember = !!document.getElementById('regRemember').checked;
        if(!email || !pass) return alert('Tous les champs sont requis.');
        const users = loadJSON(LS_USERS, []);
        if(users.some(u=>u.email===email)) return alert('Email déjà utilisé.');
        const u = { id: id(), email, password: pass, paid:false, pending:false, paymentDate:null, expiresAt:null, paymentTimer:null };
        users.push(u); saveJSON(LS_USERS, users); setAuth(u.id, remember);
        alert('Compte créé. Tu peux procéder au paiement depuis le tableau de bord.');
        show('dashboard');
      }
      function loginUser(){
        const email = document.getElementById('loginEmail').value.trim();
        const pass = document.getElementById('loginPass').value.trim();
        const remember = !!document.getElementById('loginRemember').checked;
        const users = loadJSON(LS_USERS, []);
        const u = users.find(x=>x.email===email && x.password===pass);
        if(!u) return alert('Identifiants incorrects.');
        setAuth(u.id, remember); show('dashboard');
      }
      function renderNav(){
        const cur = getCurrentUser();
        navActions.innerHTML = '';
        if(!cur){
          const btn1 = el('button','Connexion', { class:'btn btn-ghost', onclick:()=>show('login') });
          const btn2 = el('button','Inscription', { class:'btn btn-primary', onclick:()=>show('register') });
          navActions.appendChild(btn1); navActions.appendChild(btn2);
        } else {
          const userLabel = el('div', cur.email, { class:'small-muted' });
          const dashBtn = el('button', 'Tableau', { class:'btn btn-ghost', onclick:()=>show('dashboard') });
          const logoutBtn = el('button','Déconnexion',{ class:'btn btn-danger', onclick: ()=>{ setAuth(null); show('home'); }});
          navActions.appendChild(userLabel); navActions.appendChild(dashBtn); navActions.appendChild(logoutBtn);
        }

        // Always expose the WhatsApp channel join link in the top-right nav
        const waLink = el('a', 'Chaîne WhatsApp', { class: 'btn btn-ghost', href: WHATSAPP_CHANNEL, target: '_blank', rel: 'noopener noreferrer' });
        navActions.appendChild(waLink);
      }
      function el(tag, text, attrs){
        const e = document.createElement(tag);
        if(text && typeof text === 'string') e.textContent = text;
        if(attrs) Object.keys(attrs).forEach(k=> {
          const val = attrs[k];
          if(k === 'class') {
            e.className = val;
          } else if(k === 'id') {
            e.id = val;
          } else if(typeof val === 'function' && k.startsWith('on')) {
            const ev = k.slice(2);
            e.addEventListener(ev, val);
          } else {
            try { e.setAttribute(k, val); } catch(e) { /* ignore invalid attrs */ }
          }
        });
        return e;
      }
      function updateUserTimer(userId, timeLeft) {
        const users = loadJSON(LS_USERS, []);
        const idx = users.findIndex(u => u.id === userId);
        if(idx !== -1) {
          users[idx].paymentTimer = timeLeft;
          saveJSON(LS_USERS, users);
        }
      }
      function intervalRenderTimer(user){
        const payRow = document.getElementById('payTimerRow');
        if(!payRow) return;
        if(user.paymentTimer > 0) {
          payRow.querySelector("#payCountdown").textContent = user.paymentTimer;
        } else {
          payRow.querySelector("#payCountdown").textContent = '0';
        }
      }
      function renderDashboard(){
        renderNav();
        const user = getCurrentUser();
        const dashStatus = document.getElementById('dashStatus');
        const userActions = document.getElementById('userActions');
        const accessCard = document.getElementById('accessCard');
        const chaptersList = document.getElementById('chaptersList');

        if(!user) { accessCard.innerHTML = '<div class="muted">Connecte-toi pour voir ton tableau de bord.</div>'; return; }
        if(user.paymentTimer !== null && user.paymentTimer > 0 && !user.paid) {
          dashStatus.textContent = 'Paiement en attente de validation automatique';
        } else if(user.paid && user.expiresAt && new Date(user.expiresAt) > new Date()){
          dashStatus.textContent = 'Accès actif — expire le ' + new Date(user.expiresAt).toLocaleDateString();
        } else {
          dashStatus.textContent = 'Accès verrouillé — non payé';
        }
        userActions.innerHTML = '';
        const btnProfile = el('button','Mon profil', { class:'btn btn-ghost', onclick: ()=>alert('Profil : ' + user.email) });
        userActions.appendChild(btnProfile);
        accessCard.innerHTML = '';
        const acTop = el('div','',{}); acTop.style.display='flex'; acTop.style.justifyContent='space-between';
        const left = el('div','',{}); left.innerHTML = '<strong>Accès aux QCM</strong><div class="small-muted">500 F — accès 1 an</div>';
        const right = el('div','',{}); right.innerHTML = user.paid ? '<span class="badge-green">Actif</span>' : '<span class="chip">500 F</span>';
        acTop.appendChild(left); acTop.appendChild(right);
        accessCard.appendChild(acTop);

        // show payment info: masked (no number displayed) but keep Composer le paiement active
        if(!user.paid){
          const payInfo = el('div','',{}); payInfo.className = 'spaced';
          payInfo.innerHTML = `<div class="small-muted">Numéro masqué pour confidentialité. Appuyez sur <strong>Composer le paiement</strong> pour lancer l'appel et effectuer le paiement.</div>`;
          accessCard.appendChild(payInfo);

          if(user.paymentTimer !== null && user.paymentTimer > 0) {
            const payRow = el('div','',{}); payRow.className='spaced'; payRow.id = 'payTimerRow';
            payRow.innerHTML = '<div class="small-muted"><strong>Paiement détecté.</strong> Activation du compte dans <span id="payCountdown">'+user.paymentTimer+'</span> secondes...</div>';
            accessCard.appendChild(payRow);
            clearInterval(window._payTimerInterval);
            window._payTimerInterval = setInterval(function(){
              let curUser = getCurrentUser();
              if(!curUser) return;
              if(curUser.paymentTimer > 0) {
                updateUserTimer(curUser.id, curUser.paymentTimer - 1);
                intervalRenderTimer(curUser);
                if(curUser.paymentTimer - 1 <= 0) {
                  const users = loadJSON(LS_USERS, []);
                  const idx = users.findIndex(u => u.id===curUser.id);
                  if(idx !== -1) {
                    users[idx].paid = true;
                    users[idx].pending = false;
                    users[idx].paymentTimer = null;
                    users[idx].paymentDate = nowISO();
                    users[idx].expiresAt = addYearsISO(nowISO(), 1);
                    saveJSON(LS_USERS, users);
                    clearInterval(window._payTimerInterval);
                    alert('Paiement validé automatiquement. Accès activé pour 1 an.');
                    renderDashboard();
                    return;
                  }
                }
              }
            }, 1000);
          } else {
            const payRow = el('div','',{}); payRow.className='spaced';
            // Composer le paiement -> launches USSD call (number kept internally)
            const payBtn = document.createElement('a');
            payBtn.className = 'btn btn-primary';
            payBtn.href = USSD_TEL;
            payBtn.textContent = 'Composer le paiement';
            payBtn.setAttribute('aria-label', 'Composer le paiement (ouvre l’application téléphone)');

            const doPayBtn = el('button',"J'ai payé",{ class:'btn btn-ghost' });
            doPayBtn.addEventListener('click', ()=> {
              const users = loadJSON(LS_USERS, []);
              const next = users.map(u => u.id===user.id ? {...u, paymentTimer:180} : u );
              saveJSON(LS_USERS, next);
              alert('Merci ! Validation automatique dans 3 minutes...');
              renderDashboard();
            });
            payRow.appendChild(payBtn); payRow.appendChild(doPayBtn);
            accessCard.appendChild(payRow);
            accessCard.appendChild(el('div','Après paiement, attends 3 minutes pour que ton accès soit automatiquement débloqué.','class=small-muted spaced'));
          }
        } else {
          accessCard.appendChild(el('div','Accès complet activé — profite des chapitres et QCM.','class=small-muted spaced'));
        }
        chaptersList.innerHTML = '';
        const chapters = loadJSON(LS_CHAPTERS, []);
        if(chapters.length===0) chaptersList.appendChild(el('div','Aucun chapitre pour le moment.','class=small-muted'));
        chapters.forEach(ch=> {
          const box = el('div','', { class:'chapter' });
          const left = el('div', ch.title );
          left.style.fontWeight = '600';
          const right = el('div','', {});
          const tl = ch.title.toLowerCase().trim();
          const qcount = (ch.qcms && ch.qcms.length) || (tl==='glucides' ? GLUCIDES_QCMS.length : (tl==='lipides' ? LIPIDES_QCMS.length : (tl.startsWith('acides amin') ? AMINO_QCMS.length : (tl.includes('nucl') ? NUCLEIC_QCMS.length : 0))));
          right.innerHTML = `<div class="small-muted">${qcount} QCM</div>`;
          const openBtn = el('button','Ouvrir',{ class:'btn btn-ghost' });
          openBtn.addEventListener('click', ()=> openChapter(ch.id));
          right.appendChild(openBtn);
          box.appendChild(left); box.appendChild(right);
          chaptersList.appendChild(box);
        });
      }

      // openChapter: handle Glucides, Lipides, Acides aminés, Acides nucléiques
      function openChapter(chId){
        const chapters = loadJSON(LS_CHAPTERS, []);
        const ch = chapters.find(c=>c.id===chId);
        if(!ch) return alert('Chapitre introuvable.');
        const user = getCurrentUser();
        const allowed = user && user.paid && user.expiresAt && new Date(user.expiresAt) > new Date();
        document.getElementById('chapterTitle').textContent = ch.title;
        const tl = ch.title.toLowerCase().trim();

        if(tl === 'glucides') {
          if(!allowed){
            document.getElementById('chapterMeta').textContent = 'Accès restreint — payez 500 F pour accéder';
            const qcmList = document.getElementById('qcmList'); qcmList.innerHTML = '';
            qcmList.appendChild(el('div','Accès restreint — payez 500 F pour accéder au chapitre Glucides.','class=small-muted'));
            show('chapter'); return;
          }
          renderEmbeddedGlucides(); return;
        }

        if(tl === 'lipides') {
          if(!allowed){
            document.getElementById('chapterMeta').textContent = 'Accès restreint — payez 500 F pour accéder';
            const qcmList = document.getElementById('qcmList'); qcmList.innerHTML = '';
            qcmList.appendChild(el('div','Accès restreint — payez 500 F pour accéder au chapitre Lipides.','class=small-muted'));
            show('chapter'); return;
          }
          renderEmbeddedLipides(); return;
        }

        // detect acides aminés chapter (accept common title variants)
        if(tl === 'acides aminés, peptides et protéines' || tl.startsWith('acides amin')) {
          if(!allowed){
            document.getElementById('chapterMeta').textContent = 'Accès restreint — payez 500 F pour accéder';
            const qcmList = document.getElementById('qcmList'); qcmList.innerHTML = '';
            qcmList.appendChild(el('div','Accès restreint — payez 500 F pour accéder au chapitre Acides aminés, peptides et protéines.','class=small-muted'));
            show('chapter'); return;
          }
          renderEmbeddedAmino(); return;
        }

        // detect acides nucléiques chapter
        if(tl.includes('nucl') || tl.startsWith('acides nuclé')) {
          if(!allowed){
            document.getElementById('chapterMeta').textContent = 'Accès restreint — payez 500 F pour accéder';
            const qcmList = document.getElementById('qcmList'); qcmList.innerHTML = '';
            qcmList.appendChild(el('div','Accès restreint — payez 500 F pour accéder au chapitre Acides nucléiques.','class=small-muted'));
            show('chapter'); return;
          }
          renderEmbeddedNucleic(); return;
        }

        // fallback for server-managed chapters
        document.getElementById('chapterMeta').textContent = (ch.qcms||[]).length + ' QCM';
        const qcmList = document.getElementById('qcmList'); qcmList.innerHTML = '';
        if((ch.qcms||[]).length===0) qcmList.appendChild(el('div','Aucun QCM pour l\'instant.','class=small-muted'));
        const chapterKey = ch.title.toLowerCase().trim();
        ch.qcms.forEach((q, qidx)=> {
          const qbox = el('div','', { class:'qcm-item' });
          const qtitle = el('div', q.question, {}); qtitle.style.fontWeight='700';
          qbox.appendChild(qtitle);
          if(!allowed){
            qbox.appendChild(el('div','Accès restreint — payez 500 F pour accéder.','class=small-muted spaced'));
          } else {
            const choicesBox = el('div','',{}); choicesBox.style.marginTop='8px';
            const userRes = getChapterResponses(getCurrentUser().id, chapterKey);
            const saved = userRes[qidx];
            q.choices.forEach((c)=> {
              const label = document.createElement('label');
              label.style.display='flex'; label.style.gap='8px'; label.style.alignItems='center';
              const input = document.createElement('input'); input.type='checkbox'; input.dataset.choiceId = c.id;
              input.style.width='16px'; input.style.height='16px';
              if(saved && saved.selected && saved.selected.includes(c.id)){
                input.checked = true; input.disabled = true;
              }
              const txt = document.createElement('div'); txt.textContent = c.text || '(vide)';
              label.appendChild(input); label.appendChild(txt);
              choicesBox.appendChild(label);
            });
            const submit = el('button','Soumettre',{ class:'btn btn-primary spaced' });
            const result = el('div','',{}); result.className='small-muted spaced';
            let answered = !!saved;
            if(saved){
              if(saved.score > 0) result.innerHTML = `<span class="correct">Bonne réponse ! (+${saved.score})</span>`;
              else result.innerHTML = `<span class="incorrect">Mauvaise réponse (${saved.score}). Bonnes réponses : ${saved.goodTexts || ''}</span>`;
              submit.disabled = true;
            }
            submit.addEventListener('click', ()=> {
              if(answered) return;
              const checks = choicesBox.querySelectorAll('input[type=checkbox]');
              const selected = [];
              checks.forEach(cb=>{
                const c = q.choices.find(x=>x.id===cb.dataset.choiceId);
                if(cb.checked) selected.push(c);
              });
              const nbCorrect = q.choices.filter(c=>c.correct).length;
              const nbSelectedCorrect = selected.filter(c=>c.correct).length;
              const nbSelectedWrong = selected.filter(c=>!c.correct).length;
              let outText = '';
              let score = 0;
              if(nbSelectedCorrect === nbCorrect && nbSelectedWrong === 0 && selected.length===nbCorrect) {
                outText = "Bravo ! Bonne réponse. (+5 points)"; score = 5;
              } else {
                const goodTxts = q.choices.filter(c=>c.correct).map(c=>c.text).join(", ");
                outText = "Mauvaise réponse (-5). Les bonnes réponses étaient : " + goodTxts; score = -5;
              }
              result.textContent = outText;
              const selectedIds = [];
              checks.forEach(cb=>{
                if(cb.checked) selectedIds.push(cb.dataset.choiceId);
                cb.disabled = true;
              });
              submit.disabled = true; answered = true;
              saveResponse(getCurrentUser().id, chapterKey, qidx, { selected: selectedIds, score: score, goodTexts: (score>0?undefined: q.choices.filter(c=>c.correct).map(c=>c.text).join(", ")) });
            });
            qbox.appendChild(choicesBox);
            qbox.appendChild(submit);
            qbox.appendChild(result);
          }
          qcmList.appendChild(qbox);
        });
        show('chapter');
      }

      // renderEmbeddedGlucides
      function renderEmbeddedGlucides(){
        const qcmList = document.getElementById('qcmList'); qcmList.innerHTML = '';
        document.getElementById('chapterMeta').textContent = `${GLUCIDES_QCMS.length} QCM — Correction automatique (+5 / -5)`;
        let totalScore = 0; const scoreArr = new Array(GLUCIDES_QCMS.length).fill(0);
        const user = getCurrentUser(); const chapterKey = 'glucides';
        const savedChapter = user ? getChapterResponses(user.id, chapterKey) : {};
        GLUCIDES_QCMS.forEach((item, idx) => {
          const qi = idx; const qbox = document.createElement('div'); qbox.className = 'qcm-box';
          const title = document.createElement('h3'); title.textContent = `QCM ${idx+1}. ${item.q}`; qbox.appendChild(title);
          const choicesContainer = document.createElement('div');
          item.r.forEach((choiceText, j) => {
            const letter = String.fromCharCode(65+j);
            const label = document.createElement('label');
            const input = document.createElement('input'); input.type = 'checkbox'; input.dataset.letter = letter; input.style.marginRight='8px';
            label.appendChild(input);
            const span = document.createElement('span'); span.textContent = `${letter}. ${choiceText}`; label.appendChild(span);
            choicesContainer.appendChild(label);
          });
          const controls = document.createElement('div'); controls.style.marginTop='8px';
          const btn = document.createElement('button'); btn.className='btn btn-primary'; btn.textContent = 'Valider';
          const res = document.createElement('div'); res.className='result';
          controls.appendChild(btn); controls.appendChild(res);
          let submitted = false; const saved = savedChapter && savedChapter[idx];
          if(saved){
            const checks = choicesContainer.querySelectorAll('input[type=checkbox]');
            checks.forEach(cb=> { if(saved.selected && saved.selected.includes(cb.dataset.letter)) cb.checked = true; cb.disabled = true; });
            btn.disabled = true; submitted = true; scoreArr[qi] = saved.score || 0;
            if(saved.score > 0) res.innerHTML = `<span class="correct">Bonne réponse ! (+${saved.score})</span>`;
            else res.innerHTML = `<span class="incorrect">Mauvaise réponse (${saved.score}). Bonnes réponses : ${saved.goodTexts || ''}</span>`;
          }
          btn.addEventListener('click', ()=> {
            if(submitted) return;
            const checks = choicesContainer.querySelectorAll('input[type=checkbox]');
            const selected = []; checks.forEach(cb => { if(cb.checked) selected.push(cb.dataset.letter); });
            const correct = Array.from(item.c);
            const nbSelectedCorrect = selected.filter(s => correct.includes(s)).length;
            const nbSelectedWrong = selected.filter(s => !correct.includes(s)).length;
            let local = 0;
            if(selected.length === 0){ res.innerHTML = `<span class="incorrect">Aucune réponse sélectionnée (-5)</span>`; local = -5; }
            else if(nbSelectedCorrect === correct.length && nbSelectedWrong === 0 && selected.length === correct.length){ res.innerHTML = `<span class="correct">Bonne réponse ! (+5)</span>`; local = 5; }
            else {
              const goodTexts = []; const labels = choicesContainer.querySelectorAll('label');
              labels.forEach(lbl => { const input = lbl.querySelector('input'); if(input && correct.includes(input.dataset.letter)){ goodTexts.push(lbl.textContent.replace(/^[A-Z]\.\s*/, '')); } });
              res.innerHTML = `<span class="incorrect">Mauvaise réponse (-5). Bonnes réponses : ${goodTexts.join(', ')}</span>`; local = -5;
            }
            checks.forEach(cb => cb.disabled = true); btn.disabled = true; submitted = true;
            scoreArr[qi] = local; totalScore = scoreArr.reduce((a,b)=>a+b,0) || 0;
            if(user){
              const goodTexts = local>0 ? undefined : (()=> { const labels = choicesContainer.querySelectorAll('label'); const arr=[]; labels.forEach(lbl=>{ const input = lbl.querySelector('input'); if(input && item.c.includes(input.dataset.letter)){ arr.push(lbl.textContent.replace(/^[A-Z]\.\s*/, '').trim()); } }); return arr.join(', '); })();
              saveResponse(user.id, chapterKey, qi, { selected: selected, score: local, goodTexts: goodTexts });
            }
            let totalEl = document.getElementById('chapterTotalScore');
            if(!totalEl){ totalEl = document.createElement('div'); totalEl.id = 'chapterTotalScore'; totalEl.style.fontWeight = 'bold'; totalEl.style.marginTop = '18px'; document.getElementById('qcmList').appendChild(totalEl); }
            totalEl.textContent = `Score total pour ce chapitre : ${totalScore} points`;
          });
          qbox.appendChild(choicesContainer); qbox.appendChild(controls); qcmList.appendChild(qbox);
        });
        let totalEl = document.getElementById('chapterTotalScore');
        if(!totalEl){ totalEl = document.createElement('div'); totalEl.id = 'chapterTotalScore'; totalEl.style.fontWeight = 'bold'; totalEl.style.marginTop = '18px'; totalEl.textContent = `Score total pour ce chapitre : ${scoreArr.reduce((a,b)=>a+b,0) || 0} points`; qcmList.appendChild(totalEl); }
        else totalEl.textContent = `Score total pour ce chapitre : ${scoreArr.reduce((a,b)=>a+b,0) || 0} points`;
        show('chapter');
      }

      // renderEmbeddedLipides
      function renderEmbeddedLipides(){
        const qcmList = document.getElementById('qcmList'); qcmList.innerHTML = '';
        document.getElementById('chapterMeta').textContent = `${LIPIDES_QCMS.length} QCM — Correction automatique (+5 / -5)`;
        let totalScore = 0; const scoreArr = new Array(LIPIDES_QCMS.length).fill(0);
        const user = getCurrentUser(); const chapterKey = 'lipides';
        const savedChapter = user ? getChapterResponses(user.id, chapterKey) : {};
        LIPIDES_QCMS.forEach((item, idx) => {
          const qi = idx; const qbox = document.createElement('div'); qbox.className = 'qcm-box';
          const title = document.createElement('h3'); title.textContent = `QCM ${idx+1}. ${item.q}`; qbox.appendChild(title);
          const choicesContainer = document.createElement('div');
          item.r.forEach((choiceText, j) => {
            const letter = String.fromCharCode(65+j);
            const label = document.createElement('label');
            const input = document.createElement('input'); input.type = 'checkbox'; input.dataset.letter = letter; input.style.marginRight='8px';
            label.appendChild(input);
            const span = document.createElement('span'); span.textContent = `${letter}. ${choiceText}`; label.appendChild(span);
            choicesContainer.appendChild(label);
          });
          const controls = document.createElement('div'); controls.style.marginTop='8px';
          const btn = document.createElement('button'); btn.className='btn btn-primary'; btn.textContent = 'Valider';
          const res = document.createElement('div'); res.className='result';
          controls.appendChild(btn); controls.appendChild(res);
          let submitted = false; const saved = savedChapter && savedChapter[idx];
          if(saved){
            const checks = choicesContainer.querySelectorAll('input[type=checkbox]');
            checks.forEach(cb=> { if(saved.selected && saved.selected.includes(cb.dataset.letter)) cb.checked = true; cb.disabled = true; });
            btn.disabled = true; submitted = true; scoreArr[qi] = saved.score || 0;
            if(saved.score > 0) res.innerHTML = `<span class="correct">Bonne réponse ! (+${saved.score})</span>`;
            else res.innerHTML = `<span class="incorrect">Mauvaise réponse (${saved.score}). Bonnes réponses : ${saved.goodTexts || ''}</span>`;
          }
          btn.addEventListener('click', ()=>{
            if(submitted) return;
            const checks = choicesContainer.querySelectorAll('input[type=checkbox]'); const selected=[];
            checks.forEach(cb => { if(cb.checked) selected.push(cb.dataset.letter); });
            const correct = Array.from(item.c);
            const nbSelectedCorrect = selected.filter(s => correct.includes(s)).length;
            const nbSelectedWrong = selected.filter(s => !correct.includes(s)).length;
            let local = 0;
            if(selected.length === 0){ res.innerHTML = `<span class="incorrect">Aucune réponse sélectionnée (-5)</span>`; local = -5; }
            else if(nbSelectedCorrect === correct.length && nbSelectedWrong === 0 && selected.length === correct.length){ res.innerHTML = `<span class="correct">Bonne réponse ! (+5)</span>`; local = 5; }
            else {
              const goodTexts = []; const labels = choicesContainer.querySelectorAll('label');
              labels.forEach(lbl => { const input = lbl.querySelector('input'); if(input && correct.includes(input.dataset.letter)){ goodTexts.push(lbl.textContent.replace(/^[A-Z]\.\s*/, '')); } });
              res.innerHTML = `<span class="incorrect">Mauvaise réponse (-5). Bonnes réponses : ${goodTexts.join(', ')}</span>`; local = -5;
            }
            checks.forEach(cb=>cb.disabled=true); btn.disabled=true; submitted=true; scoreArr[qi]=local; totalScore = scoreArr.reduce((a,b)=>a+b,0) || 0;
            if(user){
              const goodTexts = local>0 ? undefined : (()=>{ const labels = choicesContainer.querySelectorAll('label'); const arr=[]; labels.forEach(lbl=>{ const input = lbl.querySelector('input'); if(input && item.c.includes(input.dataset.letter)){ arr.push(lbl.textContent.replace(/^[A-Z]\.\s*/, '').trim()); } }); return arr.join(', '); })();
              saveResponse(user.id, chapterKey, qi, { selected: selected, score: local, goodTexts: goodTexts });
            }
            let totalEl = document.getElementById('chapterTotalScore');
            if(!totalEl){ totalEl = document.createElement('div'); totalEl.id = 'chapterTotalScore'; totalEl.style.fontWeight = 'bold'; totalEl.style.marginTop = '18px'; document.getElementById('qcmList').appendChild(totalEl); }
            totalEl.textContent = `Score total pour ce chapitre : ${totalScore} points`;
          });
          qbox.appendChild(choicesContainer); qbox.appendChild(controls); qcmList.appendChild(qbox);
        });
        let totalEl = document.getElementById('chapterTotalScore');
        if(!totalEl){ totalEl = document.createElement('div'); totalEl.id = 'chapterTotalScore'; totalEl.style.fontWeight = 'bold'; totalEl.style.marginTop = '18px'; totalEl.textContent = `Score total pour ce chapitre : ${scoreArr.reduce((a,b)=>a+b,0) || 0} points`; qcmList.appendChild(totalEl); }
        else totalEl.textContent = `Score total pour ce chapitre : ${scoreArr.reduce((a,b)=>a+b,0) || 0} points`;
        show('chapter');
      }

      // renderEmbeddedAmino
      function renderEmbeddedAmino(){
        const qcmList = document.getElementById('qcmList'); qcmList.innerHTML = '';
        document.getElementById('chapterMeta').textContent = `${AMINO_QCMS.length} QCM — Correction automatique (+5 / -5)`;
        let totalScore = 0; const scoreArr = new Array(AMINO_QCMS.length).fill(0);
        const user = getCurrentUser(); const chapterKey = 'acides-aminés';
        const savedChapter = user ? getChapterResponses(user.id, chapterKey) : {};
        AMINO_QCMS.forEach((item, idx) => {
          const qi = idx; const qbox = document.createElement('div'); qbox.className = 'qcm-box';
          const title = document.createElement('h3'); title.textContent = `QCM ${idx+1}. ${item.q}`; qbox.appendChild(title);
          const choicesContainer = document.createElement('div');
          item.r.forEach((choiceText, j) => {
            const letter = String.fromCharCode(65+j);
            const label = document.createElement('label');
            const input = document.createElement('input'); input.type = 'checkbox'; input.dataset.letter = letter; input.style.marginRight='8px';
            label.appendChild(input);
            const span = document.createElement('span'); span.textContent = `${letter}. ${choiceText}`; label.appendChild(span);
            choicesContainer.appendChild(label);
          });
          const controls = document.createElement('div'); controls.style.marginTop='8px';
          const btn = document.createElement('button'); btn.className='btn btn-primary'; btn.textContent = 'Valider';
          const res = document.createElement('div'); res.className='result';
          controls.appendChild(btn); controls.appendChild(res);
          let submitted = false; const saved = savedChapter && savedChapter[idx];
          if(saved){
            const checks = choicesContainer.querySelectorAll('input[type=checkbox]');
            checks.forEach(cb=> { if(saved.selected && saved.selected.includes(cb.dataset.letter)) cb.checked = true; cb.disabled = true; });
            btn.disabled = true; submitted = true; scoreArr[qi] = saved.score || 0;
            if(saved.score > 0) res.innerHTML = `<span class="correct">Bonne réponse ! (+${saved.score})</span>`;
            else res.innerHTML = `<span class="incorrect">Mauvaise réponse (${saved.score}). Bonnes réponses : ${saved.goodTexts || ''}</span>`;
          }
          btn.addEventListener('click', ()=>{
            if(submitted) return;
            const checks = choicesContainer.querySelectorAll('input[type=checkbox]'); const selected=[];
            checks.forEach(cb => { if(cb.checked) selected.push(cb.dataset.letter); });
            const correct = Array.from(item.c);
            const nbSelectedCorrect = selected.filter(s => correct.includes(s)).length;
            const nbSelectedWrong = selected.filter(s => !correct.includes(s)).length;
            let local = 0;
            if(selected.length === 0){ res.innerHTML = `<span class="incorrect">Aucune réponse sélectionnée (-5)</span>`; local = -5; }
            else if(nbSelectedCorrect === correct.length && nbSelectedWrong === 0 && selected.length === correct.length){ res.innerHTML = `<span class="correct">Bonne réponse ! (+5)</span>`; local = 5; }
            else {
              const goodTexts = []; const labels = choicesContainer.querySelectorAll('label');
              labels.forEach(lbl => { const input = lbl.querySelector('input'); if(input && correct.includes(input.dataset.letter)){ goodTexts.push(lbl.textContent.replace(/^[A-Z]\.\s*/, '')); } });
              res.innerHTML = `<span class="incorrect">Mauvaise réponse (-5). Bonnes réponses : ${goodTexts.join(', ')}</span>`; local = -5;
            }
            checks.forEach(cb=>cb.disabled=true); btn.disabled=true; submitted=true; scoreArr[qi]=local; totalScore = scoreArr.reduce((a,b)=>a+b,0) || 0;
            if(user){
              const goodTexts = local>0 ? undefined : (()=>{ const labels = choicesContainer.querySelectorAll('label'); const arr=[]; labels.forEach(lbl=>{ const input = lbl.querySelector('input'); if(input && item.c.includes(input.dataset.letter)){ arr.push(lbl.textContent.replace(/^[A-Z]\.\s*/, '').trim()); } }); return arr.join(', '); })();
              saveResponse(user.id, chapterKey, qi, { selected: selected, score: local, goodTexts: goodTexts });
            }
            let totalEl = document.getElementById('chapterTotalScore');
            if(!totalEl){ totalEl = document.createElement('div'); totalEl.id = 'chapterTotalScore'; totalEl.style.fontWeight = 'bold'; totalEl.style.marginTop = '18px'; document.getElementById('qcmList').appendChild(totalEl); }
            totalEl.textContent = `Score total pour ce chapitre : ${totalScore} points`;
          });
          qbox.appendChild(choicesContainer); qbox.appendChild(controls); qcmList.appendChild(qbox);
        });
        let totalEl = document.getElementById('chapterTotalScore');
        if(!totalEl){ totalEl = document.createElement('div'); totalEl.id = 'chapterTotalScore'; totalEl.style.fontWeight = 'bold'; totalEl.style.marginTop = '18px'; totalEl.textContent = `Score total pour ce chapitre : ${scoreArr.reduce((a,b)=>a+b,0) || 0} points`; qcmList.appendChild(totalEl); }
        else totalEl.textContent = `Score total pour ce chapitre : ${scoreArr.reduce((a,b)=>a+b,0) || 0} points`;
        show('chapter');
      }

      // renderEmbeddedNucleic
      function renderEmbeddedNucleic(){
        const qcmList = document.getElementById('qcmList'); qcmList.innerHTML = '';
        document.getElementById('chapterMeta').textContent = `${NUCLEIC_QCMS.length} QCM — Correction automatique (+5 / -5)`;
        let totalScore = 0; const scoreArr = new Array(NUCLEIC_QCMS.length).fill(0);
        const user = getCurrentUser(); const chapterKey = 'acides-nucleiques';
        const savedChapter = user ? getChapterResponses(user.id, chapterKey) : {};
        NUCLEIC_QCMS.forEach((item, idx) => {
          const qi = idx; const qbox = document.createElement('div'); qbox.className = 'qcm-box';
          const title = document.createElement('h3'); title.textContent = `QCM ${idx+1}. ${item.q}`; qbox.appendChild(title);
          const choicesContainer = document.createElement('div');
          item.r.forEach((choiceText, j) => {
            const letter = String.fromCharCode(65+j);
            const label = document.createElement('label');
            const input = document.createElement('input'); input.type = 'checkbox'; input.dataset.letter = letter; input.style.marginRight='8px';
            label.appendChild(input);
            const span = document.createElement('span'); span.textContent = `${letter}. ${choiceText}`; label.appendChild(span);
            choicesContainer.appendChild(label);
          });
          const controls = document.createElement('div'); controls.style.marginTop='8px';
          const btn = document.createElement('button'); btn.className='btn btn-primary'; btn.textContent = 'Valider';
          const res = document.createElement('div'); res.className='result';
          controls.appendChild(btn); controls.appendChild(res);
          let submitted = false; const saved = savedChapter && savedChapter[idx];
          if(saved){
            const checks = choicesContainer.querySelectorAll('input[type=checkbox]');
            checks.forEach(cb=> { if(saved.selected && saved.selected.includes(cb.dataset.letter)) cb.checked = true; cb.disabled = true; });
            btn.disabled = true; submitted = true; scoreArr[qi] = saved.score || 0;
            if(saved.score > 0) res.innerHTML = `<span class="correct">Bonne réponse ! (+${saved.score})</span>`;
            else res.innerHTML = `<span class="incorrect">Mauvaise réponse (${saved.score}). Bonnes réponses : ${saved.goodTexts || ''}</span>`;
          }
          btn.addEventListener('click', ()=>{
            if(submitted) return;
            const checks = choicesContainer.querySelectorAll('input[type=checkbox]'); const selected=[];
            checks.forEach(cb => { if(cb.checked) selected.push(cb.dataset.letter); });
            const correct = Array.from(item.c);
            const nbSelectedCorrect = selected.filter(s => correct.includes(s)).length;
            const nbSelectedWrong = selected.filter(s => !correct.includes(s)).length;
            let local = 0;
            if(selected.length === 0){ res.innerHTML = `<span class="incorrect">Aucune réponse sélectionnée (-5)</span>`; local = -5; }
            else if(nbSelectedCorrect === correct.length && nbSelectedWrong === 0 && selected.length === correct.length){ res.innerHTML = `<span class="correct">Bonne réponse ! (+5)</span>`; local = 5; }
            else {
              const goodTexts = []; const labels = choicesContainer.querySelectorAll('label');
              labels.forEach(lbl => { const input = lbl.querySelector('input'); if(input && correct.includes(input.dataset.letter)){ goodTexts.push(lbl.textContent.replace(/^[A-Z]\.\s*/, '')); } });
              res.innerHTML = `<span class="incorrect">Mauvaise réponse (-5). Bonnes réponses : ${goodTexts.join(', ')}</span>`; local = -5;
            }
            checks.forEach(cb=>cb.disabled=true); btn.disabled=true; submitted=true; scoreArr[qi]=local; totalScore = scoreArr.reduce((a,b)=>a+b,0) || 0;
            if(user){
              const goodTexts = local>0 ? undefined : (()=>{ const labels = choicesContainer.querySelectorAll('label'); const arr=[]; labels.forEach(lbl=>{ const input = lbl.querySelector('input'); if(input && item.c.includes(input.dataset.letter)){ arr.push(lbl.textContent.replace(/^[A-Z]\.\s*/, '').trim()); } }); return arr.join(', '); })();
              saveResponse(user.id, chapterKey, qi, { selected: selected, score: local, goodTexts: goodTexts });
            }
            let totalEl = document.getElementById('chapterTotalScore');
            if(!totalEl){ totalEl = document.createElement('div'); totalEl.id = 'chapterTotalScore'; totalEl.style.fontWeight = 'bold'; totalEl.style.marginTop = '18px'; document.getElementById('qcmList').appendChild(totalEl); }
            totalEl.textContent = `Score total pour ce chapitre : ${totalScore} points`;
          });
          qbox.appendChild(choicesContainer); qbox.appendChild(controls); qcmList.appendChild(qbox);
        });
        let totalEl = document.getElementById('chapterTotalScore');
        if(!totalEl){ totalEl = document.createElement('div'); totalEl.id = 'chapterTotalScore'; totalEl.style.fontWeight = 'bold'; totalEl.style.marginTop = '18px'; totalEl.textContent = `Score total pour ce chapitre : ${scoreArr.reduce((a,b)=>a+b,0) || 0} points`; qcmList.appendChild(totalEl); }
        else totalEl.textContent = `Score total pour ce chapitre : ${scoreArr.reduce((a,b)=>a+b,0) || 0} points`;
        show('chapter');
      }

      renderNav(); show('home'); if(getCurrentUser()) show('dashboard');
      document.getElementById('btnBackToDash').addEventListener('click', ()=> show('dashboard'));
    })();
  </script>
</body>
</html>

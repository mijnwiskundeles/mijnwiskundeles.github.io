<html lang="nl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>mijnwiskundeles – Persoonlijke bijles rekenen & wiskunde</title>
  <style>
    body { font-family: 'Segoe UI', sans-serif; margin:0; color:#1f2937; line-height:1.6; }
    header {
		background: linear-gradient(
			135deg,
			#0b132b 0%,
			#0b132b 50%,
			#0b132b 100%
  );
		color:white;
		padding:3rem 1.5rem;
		position: relative;   /* heel belangrijk voor absolute logo */
	}
    header h1 { font-size:2.2rem; margin-bottom:1rem; }
    header p { font-size:1.1rem; max-width:700px; }
    .btn { background:#20c9dc; color:#022; padding:0.75rem 1.5rem; border-radius:6px; text-decoration:none; display:inline-block; margin-top:1.5rem; }
    section { padding:3rem 1.5rem; max-width:1000px; margin:auto; }
    h2 { font-size:1.8rem; margin-bottom:1rem; }
    .grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:2rem; }
    .card { background:#f8fafc; padding:1.5rem; border-radius:10px; }
    footer { background:#f1f5f9; padding:2rem 1.5rem; font-size:0.9rem; }
    label { display:block; margin-top:1rem; font-weight:600; }
    input, select, textarea { width:100%; padding:0.5rem; margin-top:0.25rem; }
    button { margin-top:1.5rem; padding:0.75rem 1.5rem; background:#2563eb; color:white; border:none; border-radius:6px; cursor:pointer; }
    .note { font-size:0.9rem; color:#475569; margin-top:0.5rem; }
	
	.header-inner {
		max-width: 1100px;
		margin: 0 auto;
		text-align: center; /* header tekst blijft gecentreerd */
	}

	.logo {
		max-height: 40px;
		width: auto;
	}
	
	.logo-block {
		position: absolute;
		top: 80px;   /* afstand vanaf de bovenkant */
		left: 20px;  /* afstand vanaf de linkerkant */
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	.company-name {
		margin-top: 0.4rem;
		font-size: 1.1rem;
		font-weight: 500;
		color: rgba(210, 235, 255, 0.94);
		letter-spacing: 0.04em;
	}

	.header-text {
		flex: 1;
		max-width: 1000px;      /* bepaalt de breedte van beide regels */
		margin: 0 auto;         /* centreert de container */
		padding-left: 140px;    /* ruimte voor logo */
		text-align: left;
	}

	/* Mobiel */
	@media (max-width: 768px) {
		.logo-block {
			position: static;
			margin: 0 auto 1rem auto;
		}

		.header-text {
			padding-left: 0;
			text-align: center;
		}
	}

	
	footer {
		background:#f1f5f9;
		padding:2rem 1.5rem;
		font-size:0.9rem;
	}

	.footer-logo {
		max-height: 10px;
		width: auto;
		vertical-align: middle;
		margin-right: 0.5rem;
	}

	.header-text h1,
	.header-text p {
		margin: 0;
	}
	
	.grid {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
		gap: 1.5rem;
		margin-top: 2rem;
	}

	.card {
		background: white;
		border-radius: 12px;
		padding: 1.5rem;
		box-shadow: 0 8px 20px rgba(0,0,0,0.06);
	}

	.card h3 {
		margin-top: 0;
		margin-bottom: 0.6rem;
		font-size: 1.1rem;
		color: #0b132b;
	}
	
	.card-icon {
		margin-bottom: 0.6rem;
	}

	.card-icon svg {
		width: 22px;
		height: 22px;
		stroke: #20c9dc; /* accentkleur uit je logo */
		stroke-width: 1.8;
	}
	
	.btw-note {
		margin-top: 1rem;
		font-size: 0.85rem;
		color: #64748b; /* zacht grijs-blauw */
	}
	
	.background-box {
		margin-top: 1.5rem;
		padding-left: 1rem;
		border-left: 3px solid #20c9dc; /* accentkleur uit je logo */
	}

	.background-box h3 {
		margin: 0 0 0.4rem 0;
		font-size: 1rem;
		color: #0f172a;
	}

	.background-box ul {
		margin: 0;
		padding-left: 1.2rem;
		font-size: 0.9rem;
		color: #334155;
	}

	.background-box li {
		margin-bottom: 0.3rem;
	}

	.profile-photo {
		float: left;
		width: 180px;        /* Change size here */
		height: auto;
		border-radius: 50%; /* Optional: gives soft corners */
		display: block;
	}
	
	.download-box {
		margin-top: 1.5rem;
		text-align: left;
	}

	.small-note {
		margin-top: 0.5rem;
		font-size: 0.9rem;
		color: #64748b;
	}

  </style>
  <script src="https://unpkg.com/lucide@latest"></script>
</head>
<body>

<header>
  <div class="header-inner">
    <div class="logo-block">
      <img src="images/bedrijfslogo_backgr_0b132bf0.PNG" alt="mijnwiskundeles logo" class="logo" />
      <div class="company-name">mijnwiskundeles</div>
    </div>

    <div class="header-text">
      <h1>Persoonlijke rekenen- en wiskundebijles in Valkenswaard</h1>
      <p>Sessies van 2 uur • Eerste les gratis • Basisschool & voortgezet onderwijs</p>
      <a href="#boeken" class="btn">Boek een proefles</a>
    </div>
  </div>
</header>

<section>
  <h2>Over mij</h2>
  <div class="grid">
    <div>
      <p>Hi, ik ben Norbert. Ik help leerlingen uit het basis- en voortgezet onderwijs om rekenen en wiskunde te begrijpen door samen helderheid en vertrouwen op te bouwen.</p>
      <p>Van oorsprong ben ik ingenieur en jarenlang heb ik gewerkt aan complexe technische systemen, waar precisie, logisch denken en zorgvuldigheid essentieel zijn. Die manier van denken neem ik mee in mijn bijlessen, ingewikkelde problemen terugbrengen tot iets dat overzichtelijk en begrijpelijk wordt.</p>
	  <p>Wat mij onderscheidt, is rust en aandacht. Ik neem de tijd om te begrijpen waar een leerling vastloopt. Dat kan inhoudelijk zijn, maar vaak ook in onzekerheid, tempo of eerdere negatieve ervaringen met het vak. Ik geloof niet in labels of snelle conclusies. Elk kind leert anders, en daar stem ik mijn begeleiding op af.</p>
	  <p>Mijnwiskundeles is ontstaan vanuit de overtuiging dat goede begeleiding begint bij serieus kijken, luisteren en uitleggen, zonder druk, maar met duidelijke structuur en heldere stappen.</p>
	  <div class="background-box">
		<h3>Achtergrond</h3>
		<ul>
			<li>Ingenieursopleiding Systeem- en Computertechniek</li>
			<li>Master Besturingssystemen</li>
			<li>Ruim 14,5 jaar ervaring als embedded software engineer</li>
			<li>12,5 jaar werkzaam geweest bij DAF Trucks (Eindhoven)</li>
		</ul>
	  </div>

    </div>
    <div>
      <!-- Eigen foto toevoegen -->
      <img src="images/portrait.png" alt="Norbert" class="profile-photo" />
    </div>
  </div>
</section>

<section>
  <h2>Mijn aanpak</h2>
    <div class="grid">

      <div class="card">
		<div class="card-icon">
			<i data-lucide="user"></i>
		</div>
        <h3>Persoonlijke aandacht</h3>
        <p>Elk kind verdient persoonlijke aandacht. Ik stem het tempo, de uitleg en de oefeningen af op het niveau, de leerstijl en het karakter van de leerling.</p>
      </div>

      <div class="card">
		<div class="card-icon">
			<i data-lucide="book-open"></i>
		</div>
        <h3>Kennis van de theorie is essentieel</h3>
        <p>Een heldere uitleg van de theorie is de basis. Met duidelijke voorbeelden zorgen we eerst dat de fundamenten stevig zijn, voordat we werken aan complexere opgaven.</p>
      </div>

      <div class="card">
		<div class="card-icon">
			<i data-lucide="pen-tool"></i>
		</div>
        <h3>Lead by example</h3>
        <p>Ik laat zien hoe je een wiskundig probleem aanpakt. We beginnen altijd met orde scheppen: wat is precies de opdracht, welke stappen horen daarbij en welke regels gelden?</p>
      </div>

      <div class="card">
		<div class="card-icon">
			<i data-lucide="check-circle"></i>
		</div>
        <h3>Realistische verwachtingen</h3>
        <p>Ik verwacht niet dat een leerling iets weet als dit nog niet is uitgelegd. Nieuwe stof bouwen we logisch en stap voor stap op.</p>
      </div>

      <div class="card">
		<div class="card-icon">
			<i data-lucide="focus"></i>
		</div>
        <h3>Rust en focus</h3>
        <p>Tijdens de les werken we in een rustige omgeving met aandacht voor concentratie, overzicht en logisch redeneren.</p>
      </div>

      <div class="card">
		<div class="card-icon">
			<i data-lucide="brain"></i>
		</div>
        <h3>Begrip vóór snelheid</h3>
        <p>Snelheid is niet het doel. Ik controleer of een leerling kan uitleggen waarom een oplossing werkt.</p>
      </div>

      <div class="card">
		<div class="card-icon">
			<i data-lucide="repeat"></i>
		</div>
        <h3>Consistency is key</h3>
        <p>Door te oefenen, fouten te maken en te verbeteren wordt kennis duurzaam opgebouwd.</p>
      </div>

      <div class="card">
		<div class="card-icon">
			<i data-lucide="layers"></i>
		</div>
        <h3>Alle vereiste onderwerpen</h3>
        <p>We behandelen alle onderwerpen die bij het niveau horen, zonder te blijven hangen in één onderdeel.</p>
      </div>

      <div class="card">
		<div class="card-icon">
			<i data-lucide="shield-check"></i>
		</div>
        <h3>Zelfvertrouwen</h3>
        <p>In een veilige en ontspannen sfeer groeit zelfvertrouwen vanzelf door begrip en succeservaringen.</p>
      </div>

    </div>
  </div>
</section>

<section>
  <h2>Voor wie?</h2>
  <ul>
    <li>Basisschool: groep 5 t/m 8.</li>
    <li>Voortgezet onderwijs: vmbo, havo, vwo (incl. gymnasium).</li>
    <li>Wiskunde A, B, C en D.</li>
    <li>Taal: Nederlands (B2) en Engels.</li>
  </ul>
</section>

<section>
  <h2>Lesopzet & locatie</h2>
  <p>Elke sessie duurt 2 uur (twee blokken van 50 minuten met pauze). Wekelijkse lessen zijn standaard, tweewekelijkse lessen zijn beperkt beschikbaar (in de oneven weken, op vrijdag en zaterdag).</p>
  <p>Locatie: Dommelseweg 26, Kamer 7, 5554 NR Valkenswaard.</p>
  <div class="grid">
    <img src="images/Kantoor 1.png" alt="Kantoor buiten" style="width:100%; border-radius:10px;" />
    <img src="images/Kantoor 2.png" alt="Kantoor binnen" style="width:100%; border-radius:10px;" />
  </div>
</section>

<section>
  <h2>Tarieven & voorwaarden</h2>
  <p><strong>€35 per uur</strong> • €70 per sessie van 2 uur • Eerste les gratis</p>
  <ul>
    <li>Maandelijkse factuur per e-mail.</li>
	<li>De dag na de proefles sturen we een korte e-mail om te vragen hoe het is gegaan en of je verder wilt met de lessen.</li>
    <li>Dag en tijd blijven vast na de proefles.</li>
    <li>Wekelijks opzegbaar.</li>
  </ul>

  <p class="btw-note">
  Alle genoemde tarieven zijn vrijgesteld van btw.
</p>
</section>

<section>
  <h2>Jaarrooster</h2>
  <div class="download-box">
	<a href="docs/Jaarrooster 2026.pdf" class="btn" download>
		Download jaarrooster (PDF)
	</a>
	<p class="small-note">Het jaarrooster bevat alle lesvrije periodes en vakanties.</p>
  </div>
</section>

<section id="boeken">
  <h2>Les boeken</h2>
  <p class="note">Let op: de gekozen dag en tijd blijven vast voor volgende lessen.</p>

  <form action="https://example-mail-server.com/send" method="post">
    <label>Frequentie</label>
    <select name="frequentie" required>
      <option value="wekelijks">Wekelijks</option>
      <option value="tweewekelijks">Tweewekelijks (oneven weken)</option>
    </select>

    <label>Datum proefles</label>
    <input type="date" name="datum" required />

    <label>Tijd</label>
    <select name="tijd" id="tijdSelect" required></select>

    <label>Naam ouder</label>
    <input type="text" name="ouder" required />

    <label>E-mail ouder</label>
    <input type="email" name="email" required />

    <label>Naam leerling</label>
    <input type="text" name="leerling" required />

    <label>School</label>
    <select name="school">
      <option>Basisschool</option>
      <option>Voortgezet onderwijs</option>
    </select>

    <label>Groep / Niveau</label>
    <input type="text" name="niveau" />

    <label>Wiskundevak</label>
    <select name="vak">
      <option>n.v.t.</option>
      <option>A</option><option>B</option><option>C</option><option>D</option>
    </select>

    <label>Voorkeur taal</label>
    <select name="taal"><option>Nederlands</option><option>Engels</option></select>

    <label>Opmerkingen</label>
    <textarea name="opmerkingen"></textarea>

    <button type="submit" class="btn">Verstuur aanvraag</button>
  </form>
</section>

<footer>
  <p>
  <img src="images/bedrijfslogo.png" alt="logo" class="footer-logo" />
  <strong>mijnwiskundeles</strong> • KvK 99006049
  </p>
  <p>Dommelseweg 26, Kamer 7, 5554 NR Valkenswaard</p>
  <p>E-mail: mijnwiskundeles@gmail.com • Tel: 06 34174213</p>
</footer>

<script>
// === Boekingssysteem logica ===
const dateInput = document.querySelector('input[name="datum"]');
const freqSelect = document.querySelector('select[name="frequentie"]');

// vandaag: 26-01-2026
const today = new Date();

// lesvrije weken (vereenvoudigd, start)
const lesvrijeWeken = [1,8,18,32,33,34,53];

function getWeekNumber(d) {
  d = new Date(Date.UTC(d.getFullYear(), d.getMonth(), d.getDate()));
  const dayNum = d.getUTCDay() || 7;
  d.setUTCDate(d.getUTCDate() + 4 - dayNum);
  const yearStart = new Date(Date.UTC(d.getUTCFullYear(),0,1));
  return Math.ceil((((d - yearStart) / 86400000) + 1)/7);
}

function isDisabled(date) {
  if (date <= today) return true;
  if (date.getDay() === 0) return true; // zondag

  const week = getWeekNumber(date);
  if (lesvrijeWeken.includes(week)) return true;

  // Tweewekelijks: alleen oneven weken EN alleen vrijdag/zaterdag
  if (freqSelect.value === 'tweewekelijks') {
    if (week % 2 === 0) return true; // geen even weken
    const day = date.getDay();
    if (!(day === 5 || day === 6)) return true; // alleen vr (5) en za (6)
  }

  return false;
}

// HTML date picker workaround
// validatie bij wijziging
dateInput.addEventListener('change', () => {
  const selected = new Date(dateInput.value);
  if (isDisabled(selected)) {
    alert('Deze datum is niet beschikbaar.');
    dateInput.value = '';
  }
});

// === Tijden per dag ===
const tijdSelect = document.getElementById('tijdSelect');

const tijdenWekelijks = {
  1: ['10:00','13:00','15:00','17:00','19:00'], // ma
  2: ['10:00','13:00','15:00','17:00','19:00'], // di
  3: ['09:30','15:00','17:00'],                 // wo
  4: ['10:00','13:00','15:00'],                 // do
  5: ['10:00','13:00','15:00'],                 // vr
  6: ['10:00']                                  // za
};

const tijdenTweewekelijks = {
  5: ['17:00','19:00'], // vrijdag
  6: ['13:00','15:00']  // zaterdag
};

function updateTijden() {
  tijdSelect.innerHTML = '';
  if (!dateInput.value) return;

  const date = new Date(dateInput.value);
  const day = date.getDay();

  let tijden = [];
  if (freqSelect.value === 'wekelijks') {
    tijden = tijdenWekelijks[day] || [];
  } else {
    tijden = tijdenTweewekelijks[day] || [];
  }

  if (tijden.length === 0) {
    const opt = document.createElement('option');
    opt.textContent = 'Geen tijden beschikbaar';
    opt.disabled = true;
    opt.selected = true;
    tijdSelect.appendChild(opt);
    return;
  }

  tijden.forEach(t => {
    const opt = document.createElement('option');
    opt.value = t;
    opt.textContent = t;
    tijdSelect.appendChild(opt);
  });
}

freqSelect.addEventListener('change', () => {
  dateInput.value = '';
  updateTijden();
});

dateInput.addEventListener('change', updateTijden);

lucide.createIcons();
</script>
</body>
</html>
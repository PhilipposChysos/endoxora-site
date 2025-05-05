<!DOCTYPE html>
<html lang="el">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ΕΝΔΟΧΩΡΑ - Συμβουλευτική Μελετητική</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Montserrat', sans-serif;
      margin: 0;
      padding: 0;
      background: #f7f7f7;
      color: #333;
    }
    header {
      background-color: #1c3d5a;
      color: white;
      padding: 1.5rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #133049;
      padding: 0.5rem;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
    }
    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #1c3d5a;
    }
    .services ul {
      list-style: none;
      padding: 0;
    }
    .services li {
      padding: 0.5rem 0;
    }
    footer {
      text-align: center;
      background: #1c3d5a;
      color: white;
      padding: 1rem;
    }
    .lang-switch {
      position: absolute;
      right: 1rem;
      top: 1rem;
    }
    .en {
      display: none;
    }
    .file-link {
      margin: 1rem 0;
      display: block;
    }
  </style>
  <script>
    function switchLang() {
      const el = document.documentElement;
      const elLang = el.lang;
      if (elLang === 'el') {
        el.lang = 'en';
        document.querySelectorAll('.el').forEach(e => e.style.display = 'none');
        document.querySelectorAll('.en').forEach(e => e.style.display = 'block');
      } else {
        el.lang = 'el';
        document.querySelectorAll('.el').forEach(e => e.style.display = 'block');
        document.querySelectorAll('.en').forEach(e => e.style.display = 'none');
      }
    }
  </script>
</head>
<body>
  <header>
    <div class="el">
      <h1>ΕΝΔΟΧΩΡΑ ΣΥΜΒΟΥΛΕΥΤΙΚΗ - ΜΕΛΕΤΗΤΙΚΗ ΙΚΕ</h1>
      <p>Στρατηγικός πολεοδομικός σχεδιασμός για βιώσιμες πόλεις</p>
    </div>
    <div class="en">
      <h1>ENDOXORA CONSULTING - PLANNING IKE</h1>
      <p>Strategic urban planning for sustainable cities</p>
    </div>
  </header>

  <div class="lang-switch">
    <button onclick="switchLang()">🌐</button>
  </div>

  <nav>
    <a href="#about">Σχετικά / About</a>
    <a href="#services">Υπηρεσίες / Services</a>
    <a href="#projects">Έργα / Projects</a>
    <a href="#financials">Ισολογισμοί / Financials</a>
    <a href="#contact">Επικοινωνία / Contact</a>
  </nav>

  <section id="about">
    <div class="el">
      <h2>Σχετικά με εμάς</h2>
      <p>Ο Ευστράτιος Μάνος είναι Πολεοδόμος - Χωροτάκτης, MSc Περιβαλλοντικού Σχεδιασμού και Σύμβουλος Αστικής και Τοπικής Ανάπτυξης. Με πολυετή εμπειρία, η εταιρεία μας δραστηριοποιείται σε πολυεπίπεδα έργα χωρικού σχεδιασμού και συμβουλευτικής υποστήριξης.</p>
    </div>
    <div class="en">
      <h2>About Us</h2>
      <p>Efstratios Manos is an Urban and Spatial Planner, MSc in Environmental Design, and Advisor for Urban and Local Development. With extensive experience, our company engages in multi-level spatial planning and consulting projects.</p>
    </div>
  </section>

  <section id="services" class="services">
    <div class="el">
      <h2>Υπηρεσίες</h2>
      <ul>
        <li>Υπηρεσίες Πολεοδομίας</li>
        <li>Αρχιτεκτονικές Συμβουλές</li>
        <li>Αστικός και Χωροταξικός Σχεδιασμός</li>
        <li>Περιβαλλοντική Έρευνα και Ανάπτυξη</li>
        <li>Διαχείριση και Εκμίσθωση Ακινήτων</li>
        <li>Βραχυχρόνια Μίσθωση (Airbnb και άλλες πλατφόρμες)</li>
      </ul>
    </div>
    <div class="en">
      <h2>Services</h2>
      <ul>
        <li>Urban Planning Services</li>
        <li>Architectural Consulting</li>
        <li>Urban and Spatial Development</li>
        <li>Environmental Research and Development</li>
        <li>Property Leasing and Management</li>
        <li>Short-Term Rentals (Airbnb and other platforms)</li>
      </ul>
    </div>
  </section>

  <section id="projects">
    <div class="el">
      <h2>Έργα</h2>
      <p>Ενδεικτικά έργα και μελέτες θα προστεθούν εδώ με φωτογραφίες, χάρτες και περιγραφές.</p>
    </div>
    <div class="en">
      <h2>Projects</h2>
      <p>Sample projects and studies will be added here with photos, maps, and descriptions.</p>
    </div>
  </section>

  <section id="financials">
    <div class="el">
      <h2>Ισολογισμοί</h2>
      <p>Εδώ θα εμφανίζονται οι ετήσιοι ισολογισμοί της εταιρείας. Μπορείτε να κατεβάσετε τα έγγραφα παρακάτω.</p>
      <a class="file-link" href="#" download>Ισολογισμός 2024 (PDF)</a>
    </div>
    <div class="en">
      <h2>Financials</h2>
      <p>Here you can find the company's annual financial statements. Download the documents below.</p>
      <a class="file-link" href="#" download>Financial Statement 2024 (PDF)</a>
    </div>
  </section>

  <section id="contact">
    <div class="el">
      <h2>Επικοινωνία</h2>
      <p><strong>Ευστράτιος Μάνος</strong><br>
      Πολεοδόμος-Χωροτάκτης, MSc Περιβαλλοντικού Σχεδιασμού<br>
      Σύμβουλος Αστικής και Τοπικής Ανάπτυξης</p>
      <p>
        Διεύθυνση: Φυλής 132, 11251 Αθήνα<br>
        Τηλέφωνο: +30 6932 357892<br>
        Email: efmanos1@yahoo.gr
      </p>
    </div>
    <div class="en">
      <h2>Contact</h2>
      <p><strong>Efstratios Manos</strong><br>
      Urban & Regional Planner, MSc Environmental Design<br>
      Advisor in Urban and Local Development</p>
      <p>
        Address: 132 Filis Str., 11251 Athens, Greece<br>
        Phone: +30 6932 357892<br>
        Email: efmanos1@yahoo.gr
      </p>
    </div>
  </section>

  <footer>
    <div class="el">&copy; 2025 ΕΝΔΟΧΩΡΑ ΙΚΕ</div>
    <div class="en">&copy; 2025 ENDOXORA IKE</div>
  </footer>
</body>
</html>

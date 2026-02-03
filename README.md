<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Flag City Piano Care | Piano Tuning in Findlay, Ohio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Premium piano tuning, cleaning, and maintenance for upright and grand pianos in Findlay, Ohio." />
  <style>
    :root {
      --bg: #0f172a;
      --bg-alt: #111827;
      --accent: #eab308;
      --accent-soft: #facc15;
      --text: #f9fafb;
      --muted: #9ca3af;
      --card: #020617;
      --border: #1f2937;
      --font-sans: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: var(--font-sans);
      background: radial-gradient(circle at top, #1f2937 0, #020617 55%, #000 100%);
      color: var(--text);
      line-height: 1.6;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    header {
      position: sticky;
      top: 0;
      z-index: 50;
      backdrop-filter: blur(14px);
      background: linear-gradient(to bottom, rgba(15,23,42,0.95), rgba(15,23,42,0.7), transparent);
      border-bottom: 1px solid rgba(148,163,184,0.2);
    }

    .nav {
      max-width: 1100px;
      margin: 0 auto;
      padding: 0.75rem 1.25rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 0.5rem;
      font-weight: 600;
      letter-spacing: 0.06em;
      text-transform: uppercase;
      font-size: 0.9rem;
    }

    .logo-mark {
      width: 28px;
      height: 28px;
      border-radius: 999px;
      border: 1px solid rgba(250, 204, 21, 0.7);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 0.8rem;
      background: radial-gradient(circle at 30% 0, #facc15 0, #f97316 40%, #0f172a 100%);
      box-shadow: 0 0 18px rgba(250, 204, 21, 0.5);
    }

    .nav-links {
      display: flex;
      gap: 1.25rem;
      font-size: 0.9rem;
    }

    .nav-links a {
      color: var(--muted);
      padding-bottom: 0.15rem;
      border-bottom: 1px solid transparent;
    }

    .nav-links a:hover {
      color: var(--text);
      border-bottom-color: rgba(250, 204, 21, 0.7);
    }

    .nav-cta {
      padding: 0.45rem 0.9rem;
      border-radius: 999px;
      border: 1px solid rgba(250, 204, 21, 0.7);
      background: radial-gradient(circle at 0 0, rgba(250, 204, 21, 0.18), transparent 55%);
      font-size: 0.85rem;
      font-weight: 500;
      color: var(--accent-soft);
      display: none;
    }

    @media (min-width: 768px) {
      .nav-cta {
        display: inline-flex;
      }
    }

    main {
      max-width: 1100px;
      margin: 0 auto;
      padding: 1.5rem 1.25rem 3rem;
    }

    section {
      padding: 3.5rem 0;
      border-bottom: 1px solid rgba(15,23,42,0.8);
    }

    /* Hero */
    .hero {
      min-height: 70vh;
      display: grid;
      grid-template-columns: 1.2fr 1fr;
      gap: 2.5rem;
      align-items: center;
    }

    @media (max-width: 900px) {
      .hero {
        grid-template-columns: 1fr;
      }
    }

    .hero-kicker {
      font-size: 0.8rem;
      text-transform: uppercase;
      letter-spacing: 0.18em;
      color: var(--accent-soft);
      margin-bottom: 0.75rem;
    }

    .hero-title {
      font-size: clamp(2.2rem, 4vw, 3rem);
      font-weight: 700;
      line-height: 1.1;
      margin-bottom: 0.75rem;
    }

    .hero-subtitle {
      color: var(--muted);
      max-width: 32rem;
      margin-bottom: 1.5rem;
      font-size: 0.98rem;
    }

    .hero-cta-row {
      display: flex;
      flex-wrap: wrap;
      gap: 0.75rem;
      align-items: center;
      margin-bottom: 1.75rem;
    }

    .btn-primary {
      padding: 0.7rem 1.4rem;
      border-radius: 999px;
      border: none;
      background: linear-gradient(135deg, #facc15, #f97316);
      color: #111827;
      font-weight: 600;
      font-size: 0.95rem;
      cursor: pointer;
      box-shadow: 0 10px 30px rgba(15,23,42,0.7);
    }

    .btn-outline {
      padding: 0.65rem 1.3rem;
      border-radius: 999px;
      border: 1px solid rgba(148,163,184,0.6);
      background: transparent;
      color: var(--muted);
      font-size: 0.9rem;
      cursor: pointer;
    }

    .hero-meta {
      display: flex;
      flex-wrap: wrap;
      gap: 1.5rem;
      font-size: 0.8rem;
      color: var(--muted);
    }

    .hero-meta span {
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
    }

    .hero-meta-dot {
      width: 6px;
      height: 6px;
      border-radius: 999px;
      background: var(--accent-soft);
      box-shadow: 0 0 10px rgba(250, 204, 21, 0.8);
    }

    .hero-card {
      border-radius: 1.25rem;
      border: 1px solid rgba(148,163,184,0.25);
      background: radial-gradient(circle at top, rgba(15,23,42,0.9), #020617 60%, #000 100%);
      padding: 1.5rem 1.4rem;
      box-shadow: 0 20px 60px rgba(0,0,0,0.7);
      position: relative;
      overflow: hidden;
    }

    .hero-card::before {
      content: "";
      position: absolute;
      inset: -40%;
      background: radial-gradient(circle at 0 0, rgba(250, 204, 21, 0.12), transparent 55%);
      opacity: 0.9;
      pointer-events: none;
    }

    .hero-card-inner {
      position: relative;
      z-index: 1;
    }

    .hero-card-title {
      font-size: 0.9rem;
      text-transform: uppercase;
      letter-spacing: 0.18em;
      color: var(--muted);
      margin-bottom: 0.75rem;
    }

    .hero-card-main {
      font-size: 1.1rem;
      font-weight: 600;
      margin-bottom: 1.25rem;
    }

    .hero-card-list {
      list-style: none;
      font-size: 0.85rem;
      color: var(--muted);
      margin-bottom: 1.25rem;
    }

    .hero-card-list li {
      margin-bottom: 0.4rem;
      display: flex;
      align-items: center;
      gap: 0.4rem;
    }

    .hero-badge {
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
      font-size: 0.75rem;
      padding: 0.35rem 0.7rem;
      border-radius: 999px;
      border: 1px solid rgba(250, 204, 21, 0.6);
      color: var(--accent-soft);
      background: rgba(15,23,42,0.8);
    }

    /* Section headings */
    .section-heading {
      font-size: 1.6rem;
      margin-bottom: 0.4rem;
    }

    .section-subtitle {
      color: var(--muted);
      font-size: 0.95rem;
      max-width: 34rem;
      margin-bottom: 1.8rem;
    }

    /* Services */
    .services-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 1.5rem;
    }

    .card {
      border-radius: 1rem;
      border: 1px solid var(--border);
      background: linear-gradient(145deg, rgba(15,23,42,0.9), rgba(15,23,42,0.7));
      padding: 1.25rem 1.3rem;
    }

    .card h3 {
      font-size: 1rem;
      margin-bottom: 0.4rem;
    }

    .card p {
      font-size: 0.9rem;
      color: var(--muted);
      margin-bottom: 0.5rem;
    }

    .pill {
      display: inline-flex;
      align-items: center;
      gap: 0.35rem;
      font-size: 0.75rem;
      padding: 0.25rem 0.6rem;
      border-radius: 999px;
      border: 1px solid rgba(148,163,184,0.5);
      color: var(--muted);
      margin-top: 0.25rem;
    }

    /* Pricing */
    .pricing-grid {
      display: grid;
      grid-template-columns: 1.4fr 1fr;
      gap: 1.75rem;
    }

    @media (max-width: 900px) {
      .pricing-grid {
        grid-template-columns: 1fr;
      }
    }

    table {
      width: 100%;
      border-collapse: collapse;
      font-size: 0.9rem;
      margin-bottom: 1rem;
    }

    th, td {
      padding: 0.6rem 0.4rem;
      border-bottom: 1px solid rgba(31,41,55,0.9);
      text-align: left;
    }

    th {
      font-size: 0.8rem;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      color: var(--muted);
    }

    tbody tr:last-child td {
      border-bottom: none;
    }

    .price {
      font-weight: 600;
      color: var(--accent-soft);
    }

    .note {
      font-size: 0.8rem;
      color: var(--muted);
    }

    /* Contact */
    .contact-grid {
      display: grid;
      grid-template-columns: 1.1fr 1fr;
      gap: 1.75rem;
    }

    @media (max-width: 900px) {
      .contact-grid {
        grid-template-columns: 1fr;
      }
    }

    form {
      display: grid;
      gap: 0.75rem;
    }

    label {
      font-size: 0.8rem;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      color: var(--muted);
    }

    input, select, textarea {
      width: 100%;
      padding: 0.55rem 0.6rem;
      border-radius: 0.5rem;
      border: 1px solid rgba(31,41,55,0.9);
      background: rgba(15,23,42,0.9);
      color: var(--text);
      font-size: 0.9rem;
    }

    textarea {
      min-height: 90px;
      resize: vertical;
    }

    input:focus, select:focus, textarea:focus {
      outline: 1px solid rgba(250, 204, 21, 0.7);
      border-color: rgba(250, 204, 21, 0.7);
    }

    footer {
      border-top: 1px solid rgba(15,23,42,0.9);
      padding: 1.5rem 1.25rem 2rem;
      font-size: 0.8rem;
      color: var(--muted);
      max-width: 1100px;
      margin: 0 auto;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      gap: 0.75rem;
    }
  </style>
</head>
<body>
  <header>
    <nav class="nav">
      <div class="logo">
        <div class="logo-mark">FC</div>
        <span>Flag City Piano Care</span>
      </div>
      <div class="nav-links">
        <a href="#services">Services</a>
        <a href="#pricing">Pricing</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </div>
      <a href="#contact" class="nav-cta">Book a Tuning</a>
    </nav>
  </header>

  <main>
    <!-- Hero -->
    <section class="hero" id="top">
      <div>
        <div class="hero-kicker">Piano tuning & care • Findlay, Ohio</div>
        <h1 class="hero-title">Premium piano tuning for upright and grand pianos.</h1>
        <p class="hero-subtitle">
          Flag City Piano Care provides precise, reliable tuning, cleaning, and maintenance for acoustic pianos in homes, schools, and churches—helping your instrument sound its best all year long.
        </p>
        <div class="hero-cta-row">
          <a href="#contact"><button class="btn-primary">Schedule a Tuning</button></a>
          <a href="#pricing"><button class="btn-outline">View Pricing</button></a>
        </div>
        <div class="hero-meta">
          <span><span class="hero-meta-dot"></span> Serving Findlay and surrounding communities</span>
          <span><span class="hero-meta-dot"></span> Recommended every 6–12 months</span>
        </div>
      </div>
      <div class="hero-card">
        <div class="hero-card-inner">
          <div class="hero-card-title">Service snapshot</div>
          <div class="hero-card-main">Professional care for upright & grand acoustic pianos.</div>
          <ul class="hero-card-list">
            <li>• Standard and advanced tuning</li>
            <li>• Pitch correction for neglected instruments</li>
            <li>• Interior cleaning and detailing</li>
            <li>• Expanding voicing, regulation, and repair services</li>
          </ul>
          <div class="hero-badge">
            <span>Flag City • Piano Care</span>
          </div>
        </div>
      </div>
    </section>

    <!-- Services -->
    <section id="services">
      <h2 class="section-heading">Services</h2>
      <p class="section-subtitle">
        Comprehensive care for upright and grand pianos, with a focus on long‑term performance, stability, and tone.
      </p>
      <div class="services-grid">
        <div class="card">
          <h3>Piano Tuning</h3>
          <p>
            Professional tuning for upright and grand acoustic pianos using a thorough, systematic process to ensure stable pitch and musical clarity.
          </p>
          <div class="pill">Recommended every 6–12 months</div>
        </div>
        <div class="card">
          <h3>Pitch Correction</h3>
          <p>
            For pianos that have fallen significantly below standard pitch. Includes pitch raising and fine tuning to bring the instrument back into alignment.
          </p>
          <div class="pill">Ideal for long‑neglected pianos</div>
        </div>
        <div class="card">
          <h3>Neglected Piano Tuning</h3>
          <p>
            Multi‑step tuning and stabilization for older or severely out‑of‑tune instruments that require extra time and care.
          </p>
          <div class="pill">Extended appointment time</div>
        </div>
        <div class="card">
          <h3>Deep Cleaning & Detailing</h3>
          <p>
            Interior cleaning of the soundboard, action cavity, and keybed, along with keytop and case cleaning to remove dust and debris.
          </p>
          <div class="pill">Upright & grand options</div>
        </div>
        <div class="card">
          <h3>Developing Services</h3>
          <p>
            Voicing, regulation, and light repairs are actively being added to provide full‑service piano care for demanding players and institutions.
          </p>
          <div class="pill">Growing capabilities</div>
        </div>
        <div class="card">
          <h3>Institutional Service</h3>
          <p>
            Flexible scheduling and discounted rates for schools, churches, and organizations with multiple instruments needing regular care.
          </p>
          <div class="pill">Multi‑piano plans available</div>
        </div>
      </div>
    </section>

    <!-- Pricing -->
    <section id="pricing">
      <h2 class="section-heading">Pricing</h2>
      <p class="section-subtitle">
        Pricing reflects a careful, methodical approach to each instrument while remaining competitive within the regional market.
      </p>
      <div class="pricing-grid">
        <div>
          <table>
            <thead>
              <tr>
                <th>Service</th>
                <th>Details</th>
                <th>Price</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>Basic Tuning</td>
                <td>Standard tuning for upright or grand acoustic pianos.</td>
                <td class="price">$150</td>
              </tr>
              <tr>
                <td>Pitch Correction + Tuning</td>
                <td>For pianos significantly below pitch; includes pitch raise and fine tuning.</td>
                <td class="price">$250</td>
              </tr>
              <tr>
                <td>Neglected Piano Tuning</td>
                <td>For long‑neglected instruments requiring multiple passes and stabilization.</td>
                <td class="price">$300+</td>
              </tr>
              <tr>
                <td>Deep Cleaning (Upright)</td>
                <td>Interior cleaning and detailing for upright pianos.</td>
                <td class="price">$125</td>
              </tr>
              <tr>
                <td>Deep Cleaning (Grand)</td>
                <td>Interior cleaning and detailing for grand pianos.</td>
                <td class="price">$200</td>
              </tr>
            </tbody>
          </table>
          <p class="note">
            Discounts are available for institutions with multiple instruments and for clients who schedule regular 6‑ or 12‑month tunings.
          </p>
        </div>
        <div class="card">
          <h3>How pricing works</h3>
          <p>
            Each appointment is scheduled with enough time to properly assess, tune, and care for your instrument. Older or severely neglected pianos may require additional work, which will be discussed clearly before service begins.
          </p>
          <p class="note">
            Final quotes can be provided after a brief conversation about your piano’s age, condition, and last tuning date.
          </p>
        </div>
      </div>
    </section>

    <!-- About -->
    <section id="about">
      <h2 class="section-heading">About Flag City Piano Care</h2>
      <p class="section-subtitle">
        A locally rooted piano service dedicated to precision, reliability, and long‑term care for the instruments that matter most.
      </p>
      <div class="services-grid">
        <div class="card">
          <h3>Our Focus</h3>
          <p>
            Flag City Piano Care specializes in acoustic piano tuning, cleaning, and developing maintenance services for upright and grand pianos in the Findlay area.
          </p>
          <p>
            The goal is simple: keep your piano sounding and feeling its best, year after year.
          </p>
        </div>
        <div class="card">
          <h3>Who We Serve</h3>
          <p>
            Families with young students, older adult pianists, hobbyists, schools, churches, and community organizations who value consistent, professional piano care.
          </p>
        </div>
        <div class="card">
          <h3>What Sets Us Apart</h3>
          <p>
            A thorough, systematic tuning process, local flexibility for scheduling, and a strong emphasis on customer satisfaction and long‑term relationships.
          </p>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact">
      <h2 class="section-heading">Schedule a Tuning</h2>
      <p class="section-subtitle">
        Share a few details about your piano and preferred timing, and you’ll receive a follow‑up to confirm your appointment.
      </p>
      <div class="contact-grid">
        <div>
          <form>
            <div>
              <label for="name">Name</label>
              <input id="name" type="text" placeholder="Your name" />
            </div>
            <div>
              <label for="email">Email</label>
              <input id="email" type="email" placeholder="you@example.com" />
            </div>
            <div>
              <label for="phone">Phone</label>
              <input id="phone" type="tel" placeholder="(555) 555‑5555" />
            </div>
            <div>
              <label for="piano">Piano Type</label>
              <select id="piano">
                <option value="">Select one</option>
                <option>Upright</option>
                <option>Grand</option>
                <option>Not sure</option>
              </select>
            </div>
            <div>
              <label for="service">Service Requested</label>
              <select id="service">
                <option value="">Select one</option>
                <option>Basic Tuning</option>
                <option>Pitch Correction + Tuning</option>
                <option>Neglected Piano Tuning</option>
                <option>Deep Cleaning</option>
                <option>Multiple / Institutional</option>
              </select>
            </div>
            <div>
              <label for="message">Notes</label>
              <textarea id="message" placeholder="Tell us about your piano, last tuning date, and preferred days/times."></textarea>
            </div>
            <div>
              <button type="submit" class="btn-primary">Submit Request</button>
            </div>
          </form>
        </div>
        <div class="card">
          <h3>Contact & Service Area</h3>
          <p>
            <strong>Email:</strong> info@flagcitypianocare.com<br />
            <strong>Phone:</strong> (555) 555‑5555
          </p>
          <p>
            Based in Findlay, Ohio and serving Flag City and surrounding communities.
          </p>
          <p class="note">
            After you submit your request, you’ll receive a follow‑up to confirm availability, pricing, and appointment details.
          </p>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <span>© <span id="year"></span> Flag City Piano Care. All rights reserved.</span>
    <span>Findlay, Ohio • Upright & Grand Piano Tuning</span>
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
# Flag-City-Piano-Care

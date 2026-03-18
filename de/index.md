---
layout: default
title: Startseite
description: "Portfolio Startseite von Michael Berthold"
lang: de
ref: home
contact_overline: "Kontakt"
contact_title: "Kontakt"
footer_name: "Michael R. Berthold"
address_line: "123 Anywhere St., Beliebige Stadt, Deutschland"
phone_line: "Tel: +49 123 456 789"
email_line: "E-Mail: hello@example.com"
---

<section class="hero">
  <div class="container hero-grid">
    <div class="hero-copy">
      <p class="overline">Über mich</p>
      <h1>Hallo</h1>
      <p class="hero-subtitle">Ich bin Michael Berthold, Informatiker.</p>
      <a class="button button--accent" href="#contact">Kontakt</a>
    </div>
    <div class="hero-media">
      <img class="hero-portrait" src="{{ '/assets/img/portrait.svg' | relative_url }}" alt="Porträtillustration von Michael Berthold" width="820" height="980">
    </div>
  </div>
</section>

<section class="stats" aria-label="Kennzahlen">
  <div class="container stats-grid">
    <article class="stat-card stat-card--accent"><strong>250+</strong><span>Wissenschaftliche Publikationen</span></article>
    <article class="stat-card"><strong>3+</strong><span>Bücher und Lehrbücher</span></article>
    <article class="stat-card stat-card--dark"><strong>30+</strong><span>Jahre in Data Science &amp; KI</span></article>
    <article class="stat-card stat-card--mid"><strong>4+</strong><span>Auszeichnungen und Ehrungen</span></article>
  </div>
</section>

<section class="section about" id="about">
  <div class="container about-grid">
    <div class="about-copy">
      <h2 class="section-title">Über mich</h2>
      <p>Michael Berthold arbeitet an der Schnittstelle von Data Science, künstlicher Intelligenz, Forschung, Lehre und wissenschaftlicher Kommunikation. Die Gestaltung dieses Portfolios folgt einer klaren, editoriellen Struktur mit Monospace-Überschriften, reduzierter Bildsprache und markanten Kartenflächen.</p>
      <p>Dieses Starter-Setup ist für GitHub Pages mit Jekyll gebaut. Navigation und Footer werden zentral gepflegt, während die veröffentlichte Seite weiterhin sauberes, suchmaschinenfreundliches statisches HTML ausliefert.</p>
    </div>
    <div class="role-cards">
      <a class="role-card" href="#talks"><span class="role-card__title">Speaker</span><span class="role-card__meta">mehr erfahren</span></a>
      <a class="role-card" href="{{ '/de/publications/' | relative_url }}"><span class="role-card__title">Publizist</span><span class="role-card__meta">mehr erfahren</span></a>
      <a class="role-card" href="#about"><span class="role-card__title">Pionier für KI &amp; Data Science</span><span class="role-card__meta">mehr erfahren</span></a>
    </div>
  </div>
</section>

<section class="research">
  <div class="container research-grid">
    <div class="research-copy">
      <h2 class="section-title">Fortschritt in Data Science durch Forschung</h2>
      <a class="button button--dark" href="{{ '/de/publications/' | relative_url }}">Publikationen</a>
    </div>
    <div class="quote-list">
      <blockquote class="quote"><p>Lorem ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type specimen book.</p><footer>Kyle D.</footer></blockquote>
      <blockquote class="quote"><p>Lorem ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p><footer>Sofia M.</footer></blockquote>
      <blockquote class="quote"><p>Lorem ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p><footer>Liam W.</footer></blockquote>
    </div>
  </div>
</section>

<section class="books">
  <div class="container">
    <h2 class="section-title">Herausgeber und Mitautor von Lehrbüchern:</h2>
    <div class="books-grid">
      <article class="book-card">
        <div class="book-card__image"><img src="{{ '/assets/img/book-1.svg' | relative_url }}" alt="Buchplatzhalter 1" width="520" height="360"></div>
        <div class="book-card__body"><h3>Advances in Intelligent Data Analysis V</h3><p>Reasoning about Data (1997)</p></div>
      </article>
      <article class="book-card">
        <div class="book-card__image"><img src="{{ '/assets/img/book-2.svg' | relative_url }}" alt="Buchplatzhalter 2" width="520" height="360"></div>
        <div class="book-card__body"><h3>Intelligent Data Analysis 2nd Edition</h3><p>(2007)</p></div>
      </article>
      <article class="book-card">
        <div class="book-card__image"><img src="{{ '/assets/img/book-3.svg' | relative_url }}" alt="Buchplatzhalter 3" width="520" height="360"></div>
        <div class="book-card__body"><h3>Bisociative Knowledge Discovery</h3><p>(2012)</p></div>
      </article>
    </div>
  </div>
</section>

<section class="talks" id="talks">
  <div class="container talks-shell talks-grid">
    <div class="talks-copy">
      <h2 class="section-title">Konferenzvorträge &amp; Präsentationen</h2>
      <p>Eine Auswahl aktueller Vorträge und Videos.</p>
      <a class="button button--accent" href="#">Mehr sehen</a>
    </div>
    <div><img class="talks-photo" src="{{ '/assets/img/talks.svg' | relative_url }}" alt="Illustration eines Konferenzvortrags" width="900" height="620"></div>
  </div>
</section>

<section class="interests">
  <div class="container interests-grid">
    <div class="interests-copy">
      <h2 class="section-title">Interessen</h2>
      <p>Lorem ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting.</p>
    </div>
    <div><img class="interest-portrait" src="{{ '/assets/img/speaker.svg' | relative_url }}" alt="Illustration einer Vortragsszene" width="760" height="760"></div>
  </div>
</section>

<section class="musings" id="musings">
  <div class="container musings-grid">
    <div class="musings-copy">
      <h2 class="section-title">Aktuelle Gedanken</h2>
      <div class="rule"></div>
      <p>Gedanken und Reflexionen zu Technologie, Innovation und Forschung.</p>
      <a class="button button--dark" href="#">Mehr lesen</a>
    </div>
    <div class="musings-cards">
      <article class="musing-card musing-card--accent"><div class="musing-card__index">01</div><h3>Bias in AI is bad – but is it really?</h3></article>
      <article class="musing-card musing-card--dark"><div class="musing-card__index">02</div><h3>Bias in AI is bad – but is it really?</h3></article>
      <article class="musing-card"><div class="musing-card__index">03</div><h3>Bias in AI is bad – but is it really?</h3></article>
      <article class="musing-card musing-card--accent"><div class="musing-card__index">04</div><h3>Bias in AI is bad – but is it really?</h3></article>
    </div>
  </div>
</section>

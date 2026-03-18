---
layout: default
title: Home
description: "Portfolio homepage of Michael Berthold"
lang: en
ref: home
contact_overline: "Get in touch"
contact_title: "Get in touch"
footer_name: "Michael R. Berthold"
address_line: "123 Anywhere St., Any City, Germany"
phone_line: "Tel: +49 123 456 789"
email_line: "Email: hello@example.com"
---

<section class="hero">
  <div class="container hero-grid">
    <div class="hero-copy">
      <p class="overline">About me</p>
      <h1>Hello</h1>
      <p class="hero-subtitle">I’m Michael Berthold, computer scientist.</p>
      <a class="button button--accent" href="#contact">Get in touch</a>
    </div>
    <div class="hero-media">
      <img class="hero-portrait" 
     src="{{ '/assets/img/portrait1.png' | relative_url }}" 
     alt="Portrait illustration of Michael Berthold" 
     width="820" 
     height="980">
    </div>
  </div>
</section>

<section class="stats" aria-label="Highlights">
  <div class="container stats-grid">
    <article class="stat-card stat-card--accent"><strong>250+</strong><span>Scientific Publications</span></article>
    <article class="stat-card"><strong>3+</strong><span>Books and textbooks</span></article>
    <article class="stat-card stat-card--dark"><strong>30+</strong><span>Years in Data Science &amp; AI</span></article>
    <article class="stat-card stat-card--mid"><strong>4+</strong><span>Awards and honors</span></article>
  </div>
</section>

<section class="section about" id="about">
  <div class="container about-grid">
    <div class="about-copy">
      <h2 class="section-title">About Me</h2>
      <p>Michael Berthold works at the intersection of data science, artificial intelligence, research, teaching, and scientific communication. The visual direction of this portfolio follows an editorial layout: large monospace headlines, restrained grayscale imagery, strong card blocks, and generous spacing.</p>
      <p>This starter is built for GitHub Pages with Jekyll, so the navigation and footer remain centrally editable while the published site still outputs clean, crawlable static HTML.</p>
    </div>
    <div class="role-cards">
      <a class="role-card" href="#talks"><span class="role-card__title">Speaker</span><span class="role-card__meta">learn more</span></a>
      <a class="role-card" href="{{ '/en/publications/' | relative_url }}"><span class="role-card__title">Publicist</span><span class="role-card__meta">learn more</span></a>
      <a class="role-card" href="#about"><span class="role-card__title">AI &amp; Data Science Pioneer</span><span class="role-card__meta">learn more</span></a>
    </div>
  </div>
</section>

<section class="research">
  <div class="container research-grid">
    <div class="research-copy">
      <h2 class="section-title">Advancing Data Science Through Research</h2>
      <a class="button button--dark" href="{{ '/en/publications/' | relative_url }}">Publications</a>
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
    <h2 class="section-title">Editor and co-author of textbooks:</h2>
    <div class="books-grid">
      <article class="book-card">
        <div class="book-card__image"><img src="{{ '/assets/img/book-1.svg' | relative_url }}" alt="Book placeholder cover 1" width="520" height="360"></div>
        <div class="book-card__body"><h3>Advances in Intelligent Data Analysis V</h3><p>Reasoning about Data (1997)</p></div>
      </article>
      <article class="book-card">
        <div class="book-card__image"><img src="{{ '/assets/img/book-2.svg' | relative_url }}" alt="Book placeholder cover 2" width="520" height="360"></div>
        <div class="book-card__body"><h3>Intelligent Data Analysis 2nd Edition</h3><p>(2007)</p></div>
      </article>
      <article class="book-card">
        <div class="book-card__image"><img src="{{ '/assets/img/book-3.svg' | relative_url }}" alt="Book placeholder cover 3" width="520" height="360"></div>
        <div class="book-card__body"><h3>Bisociative Knowledge Discovery</h3><p>(2012)</p></div>
      </article>
    </div>
  </div>
</section>

<section class="talks" id="talks">
  <div class="container talks-shell talks-grid">
    <div class="talks-copy">
      <h2 class="section-title">Conference Talks &amp; Presentations</h2>
      <p>A selection of recent presentations and videos.</p>
      <a class="button button--accent" href="#">See more</a>
    </div>
    <div><img class="talks-photo" src="{{ '/assets/img/talks.svg' | relative_url }}" alt="Conference presentation illustration" width="900" height="620"></div>
  </div>
</section>

<section class="interests">
  <div class="container interests-grid">
    <div class="interests-copy">
      <h2 class="section-title">Interests</h2>
      <p>Lorem ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting.</p>
    </div>
    <div><img class="interest-portrait" src="{{ '/assets/img/speaker.svg' | relative_url }}" alt="Speaking pose illustration" width="760" height="760"></div>
  </div>
</section>

<section class="musings" id="musings">
  <div class="container musings-grid">
    <div class="musings-copy">
      <h2 class="section-title">Recent musings</h2>
      <div class="rule"></div>
      <p>Thoughts and reflections on technology, innovation, and research.</p>
      <a class="button button--dark" href="#">Read more</a>
    </div>
    <div class="musings-cards">
      <article class="musing-card musing-card--accent"><div class="musing-card__index">01</div><h3>Bias in AI is bad – but is it really?</h3></article>
      <article class="musing-card musing-card--dark"><div class="musing-card__index">02</div><h3>Bias in AI is bad – but is it really?</h3></article>
      <article class="musing-card"><div class="musing-card__index">03</div><h3>Bias in AI is bad – but is it really?</h3></article>
      <article class="musing-card musing-card--accent"><div class="musing-card__index">04</div><h3>Bias in AI is bad – but is it really?</h3></article>
    </div>
  </div>
</section>

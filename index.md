---
layout: default
title: Home
---

<div class="home-layout">
  <aside class="home-sidebar">
    <figure class="profile-photo">
      <img src="{{ '/assets/images/profile.jpeg' | relative_url }}" alt="Portrait of Noé Lallouet">
    </figure>
    <h2>Noé Lallouet</h2>
    <p class="title">PhD Student</p>
    <p class="affiliation">LAMSADE<br>Paris Dauphine - PSL University</p>
    <nav class="social-links">
      <a href="mailto:noe.lallouet@gmail.com" title="Email">
        <img src="{{ '/assets/icons/envelope.svg' | relative_url }}" alt="Email">
      </a>
      <a href="https://github.com/noual" title="GitHub">
        <img src="{{ '/assets/icons/github.svg' | relative_url }}" alt="GitHub">
      </a>
      <a href="https://linkedin.com/in/noe-lallouet" title="LinkedIn">
        <img src="{{ '/assets/icons/linkedin.svg' | relative_url }}" alt="LinkedIn">
      </a>
    </nav>
  </aside>

  <section class="home-main">
    <section class="biography">
      <h3>About Me</h3>
      <p>I am a researcher in artificial intelligence, specializing in the development of novel learning algorithms for multi-objective optimization and combinatorial optimization.</p>
      <p>I am currently a PhD student at LAMSADE, Paris Dauphine - PSL University, under the supervision of Prof. Tristan Cazenave. My research is centered around the development of efficient neural networks for radar target detection and the characterization of the performance / computational complexity trade-off in neural network design.</p>
    </section>

    <div class="home-grid">
      <section class="interests">
        <h3>Research Interests</h3>
        <ul>
          <li>Multi-objective optimization</li>
		  <li>Deep learning</li>
		  <li>Monte Carlo search</li>
		  <li>Computer vision</li>
        </ul>
      </section>

      <section class="education">
        <h3>Education</h3>
        <ul>
		<li>
			<strong>Ph.D in Artificial Intelligence</strong> <br>
			<span class="edu-date">2023 - 2026</span><br>
			LAMSADE, PSL University
		</li>
		<li>
			<strong>MSc in Artificial Intelligence, Systems, Data</strong> <br>
			<span class="edu-date">2020 - 2022</span><br>
			Paris Dauphine - PSL University
		</li>
		</ul>
      </section>
    </div>
  </section>
</div>

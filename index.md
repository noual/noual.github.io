---
layout: default
description: Noé Lallouet - PhD student in AI at LAMSADE, Paris Dauphine - PSL University. Research in multi-objective optimization, combinatorial optimization, and deep learning.
---

<div class="home-layout">
  <aside class="home-sidebar">
    <figure class="profile-photo">
      <img src="{{ '/assets/images/profile.jpeg' | relative_url }}" alt="Portrait of Noé Lallouet">
    </figure>
    <h2>Noé Lallouet</h2>
    <p class="title">PhD Student</p>
    <p class="affiliation">LAMSADE<br>Paris Dauphine — PSL University</p>
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
      <a href="https://scholar.google.com/citations?user=hRBgf6gAAAAJ&hl=en" title="Google Scholar">
        <img src="{{ '/assets/icons/scholar.svg' | relative_url }}" alt="Google Scholar">
      </a>
    </nav>
  </aside>

  <section class="home-main">
    <section class="biography">
      <p class="intro" data-lettrine="2">I am currently a PhD student at LAMSADE, Paris Dauphine — PSL University, under the supervision of Prof. Tristan Cazenave. My research interests focus on characterising and improving the efficiency of neural methods for perception. To this day, my work has spanned neural architecture search, multi-objective optimisation and post-training, with applications to radar signal processing and 3D Gaussian splatting.</p>
      <script>
        (function () {
          const intro = document.querySelector('.home-main .biography .intro[data-lettrine]');

          if (!intro) {
            return;
          }

          intro.setAttribute('data-lettrine', String(Math.floor(Math.random() * 5) + 1));
        }());
      </script>
    </section>

    <div class="home-grid">
      <section class="education">
        <h3>Education</h3>
        <ul>
		<li>
			<strong>Ph.D in Artificial Intelligence</strong>
      <span class="edu-date">2023 - 2026</span><br>
			LAMSADE, PSL University
		</li>
		<li>
			<strong>MSc in Artificial Intelligence, Systems, Data</strong>
			<span class="edu-date">2020 - 2022</span><br>
			Paris Dauphine - PSL University
		</li>
		</ul>
      </section>

	      <section class="interests">
	        <h3>Research Interests</h3>
	        <ul>
	          <li>
	            <strong>Optimisation &amp; search</strong>
	            <ul>
	              <li>Neural combinatorial optimisation</li>
	              <li>Neural architecture search</li>
	              <li>Multi-objective optimisation</li>
	            </ul>
	          </li>
	          <li>
	            <strong>Computer Vision</strong>
	            <ul>
	              <li>3D Gaussian splatting</li>
	              <li>3D representation learning</li>
	            </ul>
	          </li>
	        </ul>
	      </section>
    </div>
  </section>
</div>

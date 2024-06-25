---
# Feel free to add content and custom Front Matter to this file.

layout: default
---

<div class="hero">
  <h2><span>Build a healthy, sustainable engineering organization</span></h2>
</div>

<div class="services">
  <h2>Services</h2>
    <div class="tiles">
    <div>
      <h3>Culture</h3>
      <p>10x more important than compensation.</p>
      <cite>(Source: <a href="https://sloanreview.mit.edu/article/toxic-culture-is-driving-the-great-resignation/">MIT/Sloan</a>)</cite>
    </div>
    <div>
      <h3>Coaching</h3>
      <p>From C-level to individual contributor, everyone needs a coach sometimes.</p>
    </div>
    <div>
      <h3>Coding</h3>
      <p>Looking for a little extra help?</p>
    </div>
  </div>
</div>

<div class="focus">
  <h2>My Focus</h2>
  <p>
    I have reset the sensors to scan for frequencies outside the usual range. By emitting harmonic vibrations to shatter the lattices. We will monitor and adjust the frequency of the resonators. He has this ability of instantly interpreting and extrapolating any verbal communication he hears. It may be due to the envelope over the structure, causing hydrogen-carbon helix patterns throughout. I'm comparing the molecular integrity of that bubble against our phasers.
  </p>

  <p>
    Shields up. I recommend we transfer power to phasers and arm the photon torpedoes. Something strange on the detector circuit. The weapons must have disrupted our communicators. You saw something as tasty as meat, but inorganically materialized out of patterns used by our transporters. Captain, the most elementary and valuable statement in science, the beginning of wisdom, is 'I do not know.' All transporters off.
  </p>

  <p>
    Deflector power at maximum. Energy discharge in six seconds. Warp reactor core primary coolant failure. Fluctuate phaser resonance frequencies. Resistance is futile. Recommend we adjust shield harmonics to the upper EM band when proceeding. These appear to be some kind of power-wave-guide conduits which allow them to work collectively as they perform ship functions. Increase deflector modulation to upper frequency band.
  </p>

  <p>
    Run a manual sweep of anomalous airborne or electromagnetic readings. Radiation levels in our atmosphere have increased by 3,000 percent. Electromagnetic and subspace wave fronts approaching synchronization. What is the strength of the ship's deflector shields at maximum output? The wormhole's size and short period would make this a local phenomenon. Do you have sufficient data to compile a holographic simulation?
  </p>
</div>

<div class="latest-posts">
  <h2>Latest Posts</h2>
  <ul>
  {% for post in collections.posts.resources %}
    <li>
      <a href="{{ post.relative_url }}">{{ post.data.title }}</a>
    </li>
  {% endfor %}
</ul>
</div>

{% render "contact_form" %}

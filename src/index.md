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
        <a href="{{ '/services#culture' | relative_url }}">
          <h3>Culture</h3>
          <p>10x more important than compensation.</p>
        </a>
      </div>
      <div>
        <a href="{{ '/services#coaching' | relative_url }}">
        <h3>Coaching</h3>
        <p>From C-level to individual contributor, everyone needs a coach sometimes.</p>
        </a>
      </div>
  </div>
</div>

<div class="values">
  <div>
    <h2>My Values</h2>
    <p>
      WIP - Something about living your values and how humans need to do that in all facets of life including work.
    </p>
  </div>
  <div>
    <h3>Equity</h3>
    <p>
      We don't need to settle for a world that is unfair.  We can be the source of that change.  <b>You</b> can be the source of that change.
    </p>
  </div>
  <div>
    <h3>Transparency</h3>
    <p>
      Transparency enhances your company’s credibility and reputation, making it more attractive to investors, partners, and candidates who value integrity and openness. Transparent practices contribute to smoother operations, reduced conflicts, and stronger relationships, driving sustainable growth and resilience. If you don't trust your employees with information, <i>why did you hire them?</i>
    </p>
  </div>
  <div>
    <h3>Autonomy</h3>
    <p>
      WIP - Autonomous employees tend to be more productive as they can tailor their workflows to suit their strengths and preferences, ultimately driving better outcomes for the organization as a whole. Thus, valuing autonomy not only cultivates a positive work culture but also enhances overall performance and competitiveness in the market.
    </p>
  </div>
  <div>
    <h3>Empowerment</h3>
    <p>
      When employees feel empowered to make decisions and take ownership of their work, they become more engaged and committed to achieving company goals. This results in higher productivity, faster problem-solving, and a culture of continuous improvement. Empowerment also cultivates leadership potential at all levels of your organization, fostering a pipeline of capable leaders who can drive future growth and adaptability in a dynamic business environment.
    </p>
  </div>
  <div>
    <h3>Compassion</h3>
    <p>
      WIP - I want to put something in here about how companies owe the community in which they operate positive contributions, as the community in which they operate make it possible for them to exist in the first place.  Showing compassion to employees and customers alike is a way to put positive contributions into the community.  But I need better words.
    </p>
  </div>
  <div>
    <h3>Servant Leadership</h3>
    <p>
      Servant leaders prioritize the needs of their employees and strive to empower them to achieve their full potential. This approach fosters a culture of trust, respect, and mutual support, where leaders serve as mentors and facilitators of growth rather than authoritative figures. Servant leadership promotes a cohesive and motivated workforce, resulting in higher employee satisfaction, stronger team dynamics, and improved organizational performance.
    </p>
  </div>
</div>

<div class="latest-posts">
  <h2>Latest Posts</h2>
  <div class="tiles">
  {% for post in collections.posts.resources limit:3 %}
    <div>
      <a href="{{ post.relative_url }}">
        <h3>{{ post.data.title }}</h3>
        <p>{{post.data.date}}</p>
      </a>
    </div>
  {% endfor %}
  </div>
</div>

{% render "contact_form" %}

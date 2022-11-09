---
layout: default
---
<div class="front-page">
  <div class="dots-box">
    <div class="profile-section" id="profile">
      <img align="left" class="bigdot left" alt="Me" src="/assets/profile-circle.png">
      <div class="social-refs">
        <a rel="me" href="https://github.com/{{ site.github_username }}" class="github" title="GitHub">
          <span class="fa-stack fa-3x">
            <i class="fa-brands fa-stack-2x fa-github"></i>
          </span>
        </a>

        <a rel="me" href="https://linkedin.com/in/{{ site.linkedin_username }}" class="linkedin" title="LinkedIn">
          <span class="fa-stack fa-3x">
            <i class="fa fa-circle fa-stack-2x"></i>
            <i class="fa-brands fa-linkedin fa-stack-1x fa-inverse"></i>
          </span>
        </a>
        
        <a rel="me" href="{{ site.personal_mastodon_url }}" class="mastodon" title="Mastodon">
          <span class="fa-stack fa-3x">
            <i class="fa fa-circle fa-stack-2x"></i>
            <i class="fa-brands fa-mastodon fa-stack-1x fa-inverse"></i>
          </span>
        </a>
      </div>
    </div>

    <div style="clear: both;"></div>

    <div class="profile-section" id="furry">
      <div class="social-refs">
        <a rel="me" href="{{ site.furry_mastodon_url }}" class="mastodon" title="Mastodon">
          <span class="fa-stack fa-3x">
            <i class="fa fa-circle fa-stack-2x"></i>
            <i class="fa-brands fa-mastodon fa-stack-1x fa-inverse"></i>
          </span>
        </a>

        <a rel="me" href="https://www.facebook.com/{{ site.facebook_username }}" class="facebook" title="Facebook">
          <span class="fa-stack fa-3x">
            <i class="fa-brands fa-facebook fa-stack-2x"></i>
          </span>
        </a>
      </div>

      <img align="right" class="bigdot right" title="Photo &copy; 2013 Anthony Stewart" alt="Fursuit" src="/assets/fursuit-circle.png">
    </div>
  </div>
</div>

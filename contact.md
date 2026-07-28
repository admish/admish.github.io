---
title: Contact
heading: Contact
layout: page
permalink: /contact/
menu:
  footer:
    identifier: _contact
    url: "/contact/"
---

<form action="https://api.web3forms.com/submit" method="POST">
  <input type="hidden" name="access_key" value="a1c6b4f1-0bce-47f8-9ab0-98dc56dd5817">
  <input type="hidden" name="subject" value="Contact form: adium.me">

  <!-- honeypot: bots fill this, humans never see it -->
  <input type="checkbox" name="botcheck" class="hidden" style="display:none;" tabindex="-1" autocomplete="off">

  <p>
    <label for="name">Name</label><br>
    <input type="text" id="name" name="name" required style="width:100%;max-width:28rem;">
  </p>
  <p>
    <label for="email">Your email</label><br>
    <input type="email" id="email" name="email" required style="width:100%;max-width:28rem;">
  </p>
  <p>
    <label for="message">Message</label><br>
    <textarea id="message" name="message" rows="6" required style="width:100%;max-width:28rem;"></textarea>
  </p>
  <p><button type="submit">Send</button></p>
</form>

<p><em>Or reach me on <a href="https://www.linkedin.com/in/adium/">LinkedIn</a>.</em></p>

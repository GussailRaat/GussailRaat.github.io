---
layout: page
title: Contact
permalink: /contact/
nav: true
nav_order: 4
---

<style>
.contact-info p { margin-bottom: 0.3rem; }
.contact-form { max-width: 600px; margin-top: 1rem; }
.contact-form .form-row { display: flex; gap: 1rem; margin-bottom: 0.8rem; }
.contact-form .form-row > div { flex: 1; }
.contact-form label { display: block; font-weight: 600; margin-bottom: 0.2rem; font-size: 0.9rem; }
.contact-form input,
.contact-form textarea {
  width: 100%;
  padding: 0.5rem 0.7rem;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-size: 0.95rem;
  font-family: inherit;
  background: var(--global-bg-color);
  color: var(--global-text-color);
}
.contact-form textarea { min-height: 120px; resize: vertical; }
.contact-form .submit-btn {
  background: var(--global-theme-color, #4285f4);
  color: white;
  border: none;
  padding: 0.6rem 1.5rem;
  border-radius: 4px;
  font-size: 0.95rem;
  cursor: pointer;
  margin-top: 0.5rem;
}
.contact-form .submit-btn:hover { opacity: 0.9; }
.contact-icons-bottom { text-align: center; margin-top: 2.5rem; padding-top: 1.5rem; border-top: 1px solid #eee; }
.contact-icons-bottom .contact-icons { font-size: 2rem !important; }
.contact-icons-bottom .contact-icons a img,
.contact-icons-bottom .contact-icons a svg { width: 1.8rem !important; height: 1.8rem !important; }
</style>

<div class="contact-info">
<h3>Email</h3>
<p>📧 <a href="mailto:Dushyant.Chauhan@mbzuai.ac.ae">Dushyant.Chauhan@mbzuai.ac.ae</a></p>

<h3>Address</h3>
<p>🏫 Mohamed bin Zayed University of Artificial Intelligence (MBZUAI)<br>
Masdar City, Abu Dhabi, United Arab Emirates</p>
</div>

<hr>

<h3>Contact Me</h3>
<p>If you'd like to connect, please use the form below.</p>

<form class="contact-form" action="https://formspree.io/f/YOUR_FORMSPREE_ID" method="POST">
  <div class="form-row">
    <div>
      <label for="first_name">First Name *</label>
      <input type="text" id="first_name" name="first_name" required>
    </div>
    <div>
      <label for="last_name">Last Name</label>
      <input type="text" id="last_name" name="last_name">
    </div>
  </div>
  <div class="form-row">
    <div>
      <label for="email">Email *</label>
      <input type="email" id="email" name="email" required>
    </div>
    <div>
      <label for="phone">Phone</label>
      <input type="tel" id="phone" name="phone">
    </div>
  </div>
  <div>
    <label for="message">Message</label>
    <textarea id="message" name="message"></textarea>
  </div>
  <button type="submit" class="submit-btn">Submit</button>
</form>

<div class="contact-icons-bottom">
  <div class="contact-icons">{% social_links %}</div>
</div>

---
layout: page
title: Contact
permalink: /contact/
nav: true
nav_order: 4
---

<style>
.contact-wrapper { max-width: 700px; margin: 0 auto; }
.contact-card {
  background: var(--global-card-bg-color, #f8f9fa);
  border-radius: 8px;
  padding: 1.5rem 2rem;
  margin-bottom: 1.5rem;
  box-shadow: 0 1px 3px rgba(0,0,0,0.06);
}
.contact-card h3 { margin-top: 0; margin-bottom: 0.8rem; font-size: 1.2rem; }
.contact-card p { margin-bottom: 0.4rem; }

.contact-form {
  background: var(--global-card-bg-color, #f8f9fa);
  border-radius: 8px;
  padding: 1.5rem 2rem;
  box-shadow: 0 1px 3px rgba(0,0,0,0.06);
}
.contact-form h3 { margin-top: 0; margin-bottom: 0.5rem; font-size: 1.2rem; }
.contact-form .intro { color: gray; font-size: 0.9rem; margin-bottom: 1.2rem; }
.contact-form .form-row { display: flex; gap: 1rem; margin-bottom: 0.9rem; }
.contact-form .form-row > div { flex: 1; }
.contact-form label {
  display: block;
  font-weight: 500;
  margin-bottom: 0.3rem;
  font-size: 0.85rem;
  color: var(--global-text-color);
}
.contact-form input,
.contact-form textarea {
  width: 100%;
  padding: 0.55rem 0.8rem;
  border: 1px solid #ddd;
  border-radius: 5px;
  font-size: 0.95rem;
  font-family: inherit;
  background: var(--global-bg-color);
  color: var(--global-text-color);
  box-sizing: border-box;
}
.contact-form input:focus,
.contact-form textarea:focus { outline: none; border-color: var(--global-theme-color, #4285f4); }
.contact-form textarea { min-height: 130px; resize: vertical; }
.contact-form .field { margin-bottom: 0.9rem; }
.contact-form .submit-row { text-align: center; margin-top: 1.2rem; }
.contact-form .submit-btn {
  background: var(--global-theme-color, #4285f4);
  color: white;
  border: none;
  padding: 0.65rem 2.2rem;
  border-radius: 5px;
  font-size: 0.95rem;
  font-weight: 500;
  cursor: pointer;
  transition: opacity 0.2s;
}
.contact-form .submit-btn:hover { opacity: 0.85; }

.contact-icons-bottom { text-align: center; margin-top: 2rem; padding-top: 1.5rem; border-top: 1px solid #eee; }
</style>

<div class="contact-wrapper">

<div class="contact-card">
  <h3>📧 Email</h3>
  <p><a href="mailto:Dushyant.Chauhan@mbzuai.ac.ae">Dushyant.Chauhan@mbzuai.ac.ae</a> <span style="color: gray; font-size: 0.85em;">(primary)</span></p>
  <p><a href="mailto:dushyantchauhan27@gmail.com">dushyantchauhan27@gmail.com</a></p>
  <hr style="margin: 1rem 0;">
  <h3>🏫 Address</h3>
  <p><a href="https://mbzuai.ac.ae/">Mohamed bin Zayed University of Artificial Intelligence (MBZUAI)</a><br>
  Masdar City, Abu Dhabi, United Arab Emirates</p>
</div>

<form class="contact-form" action="https://formspree.io/f/YOUR_FORMSPREE_ID" method="POST">
  <h3>Contact Me</h3>
  <p class="intro">Have a question or want to collaborate? Fill out the form below.</p>

  <div class="form-row">
    <div>
      <label for="first_name">First Name <span style="color: red;">*</span></label>
      <input type="text" id="first_name" name="first_name" required>
    </div>
    <div>
      <label for="last_name">Last Name</label>
      <input type="text" id="last_name" name="last_name">
    </div>
  </div>

  <div class="form-row">
    <div>
      <label for="email">Email <span style="color: red;">*</span></label>
      <input type="email" id="email" name="email" required>
    </div>
    <div>
      <label for="phone">Phone</label>
      <input type="tel" id="phone" name="phone">
    </div>
  </div>

  <div class="field">
    <label for="message">Message</label>
    <textarea id="message" name="message"></textarea>
  </div>

  <div class="submit-row">
    <button type="submit" class="submit-btn">Submit</button>
  </div>
</form>

</div>

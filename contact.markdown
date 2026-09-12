---
title: CONTACT
date: 2026-09-11 12:10:00 -04:00
permalink: "/contact.html"
layout: default
---

<style>
  body {
    background-color: #050505 !important;
    color: #f1f1f1 !important;
  }
  
  .entry-title, .page-title, h1, h2, h3 {
    color: #fff !important;
  }

  .contact-container img {
    max-width: 100%;
    height: auto;
    border-radius: 4px;
  }
</style>
<div class="contact-container" style="max-width: 900px; margin: 0 auto; padding: 0 20px;" markdown="1">

.contact-container {
  max-width: 600px;
  margin: 0 auto 50px auto;
  background: #111;
  padding: 40px;
  border: 1px solid #222;
  border-radius: 4px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.5);
}

.contact-info {
  text-align: center;
  margin-bottom: 30px;
  padding-bottom: 30px;
  border-bottom: 1px solid #333;
}

.form-group {
  margin-bottom: 20px;
}

.form-group label {
  display: block;
  margin-bottom: 8px;
  font-weight: 600;
  color: #ccc;
  font-size: 0.9em;
  letter-spacing: 1px;
  text-transform: uppercase;
}

.form-group input, .form-group textarea {
  width: 100%;
  padding: 12px;
  background: #000;
  border: 1px solid #333;
  color: #fff;
  border-radius: 3px;
  font-family: inherit;
}

.form-group input:focus, .form-group textarea:focus {
  outline: none;
  border-color: #666;
}

.submit-btn {
  display: block;
  width: 100%;
  background-color: #fff;
  color: #000;
  text-align: center;
  padding: 15px;
  border: none;
  border-radius: 3px;
  font-size: 1em;
  font-weight: bold;
  letter-spacing: 1px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.submit-btn:hover {
  background-color: #ccc;
}

/* Formspree Success/Error Styling */
.success-msg {
  background-color: #1a1a1a;
  border: 1px solid #333;
  color: #fff;
  padding: 20px;
  text-align: center;
  border-radius: 3px;
  font-weight: bold;
  letter-spacing: 1px;
}

.error-text {
  color: #ff6b6b;
  font-size: 0.85em;
  display: block;
  margin-top: 5px;
}
</style>

<div class="contact-container">
  <div class="contact-info">
    <h3 style="margin-top: 0;">Licensing, Development & Inquiries</h3>
    <p style="color: #999; line-height: 1.6; margin-bottom: 15px;">
      Our catalog is tailored for both the academic market and the entertainment industry. 
      Whether you are a university librarian or professor requiring an institutional streaming license or expedited DVD, or an industry professional requesting private screeners and development slates, our team is here to assist.
    </p>
    <p style="color: #bbb; line-height: 1.6; font-size: 0.9em; font-style: italic;">
      Note: We gladly accommodate purchase orders and custom invoices for educational institutions.
    </p>
    <p style="color: #fff; font-weight: bold; margin-top: 25px;">
      Direct: (917) 664-0507
    </p>
  </div>

  <!-- Formspree Vanilla JS Form Integration -->
  <form id="studio-contact-form" action="https://formspree.io/f/mdeojyvg" method="POST">

    <div class="form-group">
      <label for="name">Name</label>
      <input type="text" id="name" name="name" data-fs-field required>
    </div>
    
    <div class="form-group">
      <label for="company">Company / Agency</label>
      <input type="text" id="company" name="company" data-fs-field>
    </div>
    
    <div class="form-group">
      <label for="email">Email Address</label>
      <input type="email" id="email" name="email" data-fs-field required>
      <span data-fs-error="email" class="error-text"></span>
    </div>
    
    <div class="form-group">
      <label for="message">Message</label>
      <textarea id="message" name="message" rows="5" data-fs-field required></textarea>
      <span data-fs-error="message" class="error-text"></span>
    </div>
    
    <button type="submit" class="submit-btn" data-fs-submit-btn>SEND MESSAGE</button>

  </form>

  <!-- Success Message (Hidden by default) -->
  <div data-fs-success class="success-msg" style="display: none;">
    Thank you. Your message has been sent to our development team.
  </div>

  <!-- Form-level Error Message (Hidden by default) -->
  <div data-fs-error style="display: none; color: #ff6b6b; text-align: center; margin-top: 15px;"></div>

</div>

<!-- Formspree AJAX Scripts -->
<script>
  window.formspree = window.formspree || function () { (formspree.q = formspree.q || []).push(arguments); };
  formspree('initForm', { formElement: '#studio-contact-form', formId: 'mdeojyvg' });
</script>
<script src="https://unpkg.com/@formspree/ajax@1" defer></script>
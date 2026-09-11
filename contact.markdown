---
title: CONTACT
date: 2026-09-11 12:10:00 -04:00
layout: default
---

---
layout: page
title: CONTACT
permalink: /contact/
---

<style>
  body {
    background-color: #050505 !important;
    color: #f1f1f1 !important;
  }
  
  .entry-title, .page-title, h1, h2, h3 {
    color: #fff !important;
  }

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
</style>

<div class="contact-container">
  <div class="contact-info">
    <h3 style="margin-top: 0;">Development & Inquiries</h3>
    <p style="color: #999; line-height: 1.6;">
      For private screeners, script requests, or to discuss projects in development, please reach out to our team below.
    </p>
    <p style="color: #fff; font-weight: bold; margin-top: 20px;">
      Direct: (917) 664-0507
    </p>
  </div>

  <!-- Replace the ACTION URL below once you have your Formspree link -->
  <form action="https://formspree.io/f/YOUR_FORM_ID_HERE" method="POST">
    
    <div class="form-group">
      <label for="name">Name</label>
      <input type="text" id="name" name="name" required>
    </div>

    <div class="form-group">
      <label for="company">Company / Agency</label>
      <input type="text" id="company" name="company">
    </div>

    <div class="form-group">
      <label for="email">Email Address</label>
      <input type="email" id="email" name="_replyto" required>
    </div>

    <div class="form-group">
      <label for="message">Message</label>
      <textarea id="message" name="message" rows="5" required></textarea>
    </div>

    <button type="submit" class="submit-btn">SEND MESSAGE</button>
  </form>
</div>
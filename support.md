---
layout: default
title: Maison Editorial Support
permalink: /support/
---

<style>
.support-wrap{max-width:760px;margin:3rem auto;padding:0 1.25rem;color:#25231f}
.support-wrap h1{font-family:Georgia,serif;font-size:clamp(2.5rem,6vw,4rem);font-weight:400;line-height:1.05}
.support-intro{max-width:620px;color:#625e57;line-height:1.7}
.support-form{display:grid;gap:1.15rem;margin-top:2rem}
.support-field{display:grid;gap:.45rem}
.support-field label{font-size:.9rem;font-weight:600}
.support-field input,.support-field select,.support-field textarea{width:100%;padding:.9rem;border:1px solid #c9c4ba;border-radius:0;background:#fff;color:#25231f;font:inherit}
.support-field textarea{min-height:170px;resize:vertical}
.support-field small{color:#716d65}
.support-submit{justify-self:start;padding:.95rem 1.5rem;border:1px solid #25231f;background:#25231f;color:#fff;font:inherit;letter-spacing:.08em;text-transform:uppercase;cursor:pointer}
.support-note{font-size:.85rem;line-height:1.6;color:#716d65}
.support-field input:focus-visible,.support-field select:focus-visible,.support-field textarea:focus-visible,.support-submit:focus-visible{outline:3px solid #9a8058;outline-offset:2px}
</style>

<main class="support-wrap">
  <p class="eyebrow">MAISON EDITORIAL</p>
  <h1>How can we help?</h1>
  <p class="support-intro">Contact the Maison Editorial theme support team about installation, theme settings, or a defect in the theme's shipped functionality. We aim to acknowledge requests within two business days.</p>

  <form class="support-form" action="https://formsubmit.co/khingsmhart45@gmail.com" method="POST" enctype="multipart/form-data">
    <input type="hidden" name="_subject" value="Maison Editorial theme support request">
    <input type="hidden" name="_autoresponse" value="Thank you for contacting Maison Editorial support. We have received your request and aim to respond within two business days. Please keep your support reference and reply to this email if you need to add information. For your security, never send passwords, payment card details, API keys, or other sensitive account credentials.">
    <input type="hidden" name="_template" value="table">
    <input type="hidden" name="_next" value="https://khingsmhart4.github.io/maison-editorial-documentation/support-thanks.html">
    <input type="hidden" name="_url" value="https://khingsmhart4.github.io/maison-editorial-documentation/support/">
    <input type="text" name="_honey" tabindex="-1" autocomplete="off" aria-hidden="true" style="position:absolute;left:-10000px;width:1px;height:1px">

    <div class="support-field">
      <label for="support-name">Your name *</label>
      <input id="support-name" name="name" autocomplete="name" required>
    </div>
    <div class="support-field">
      <label for="support-email">Email address *</label>
      <input id="support-email" type="email" name="email" autocomplete="email" required>
      <small>We'll use this address to reply and send an acknowledgement.</small>
    </div>
    <div class="support-field">
      <label for="support-store">Shopify store URL *</label>
      <input id="support-store" type="url" name="store_url" placeholder="https://your-store.myshopify.com" required>
    </div>
    <div class="support-field">
      <label for="support-version">Theme version</label>
      <input id="support-version" name="theme_version" value="0.3.0">
    </div>
    <div class="support-field">
      <label for="support-type">What do you need help with? *</label>
      <select id="support-type" name="issue_type" required>
        <option value="">Choose a topic</option>
        <option>Installation or setup</option>
        <option>Theme editor or section settings</option>
        <option>Product, collection, search or cart functionality</option>
        <option>Mobile or browser display issue</option>
        <option>Accessibility issue</option>
        <option>Bug or unexpected behavior</option>
        <option>Other theme support question</option>
      </select>
    </div>
    <div class="support-field">
      <label for="support-subject">Subject *</label>
      <input id="support-subject" name="subject" required>
    </div>
    <div class="support-field">
      <label for="support-message">Describe the issue *</label>
      <textarea id="support-message" name="message" placeholder="Tell us what you expected, what happened, and the steps to reproduce it." required></textarea>
    </div>
    <div class="support-field">
      <label for="support-attachment">Screenshot or file (optional)</label>
      <input id="support-attachment" type="file" name="attachment" accept=".png,.jpg,.jpeg,.webp,.pdf,.txt">
      <small>One file, maximum 10 MB. Do not attach passwords, payment information, API keys, or customer personal data.</small>
    </div>
    <button class="support-submit" type="submit">Send support request</button>
    <p class="support-note">Submitting this form sends your message and any attachment through FormSubmit.co, a third-party form delivery service, to our support inbox. FormSubmit's <a href="https://formsubmit.co/privacy.pdf" rel="noopener noreferrer">privacy information</a> explains its handling of submissions. By submitting, you acknowledge this processing. Do not include sensitive credentials or payment details.</p>
  </form>
</main>

<script>
document.querySelector('.support-form')?.addEventListener('submit', function(event) {
  const file = document.getElementById('support-attachment')?.files?.[0];
  if (file && file.size > 10 * 1024 * 1024) {
    event.preventDefault();
    window.alert('Please choose a file smaller than 10 MB.');
  }
});
</script>

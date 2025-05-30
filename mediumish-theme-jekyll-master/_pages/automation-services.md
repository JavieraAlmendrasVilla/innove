---
layout: default
title: Automation Services
permalink: /automation-services/
---

<section class="automation-landing" style="text-align:center; padding:2rem 1rem; max-width: 768px; margin:auto;">

  <h1>🤖 Automate Your Dental Clinic</h1>
  <p><em>English / Español</em></p>

  <p>
    ✅ Reduce no-shows<br>
    ✅ Automate patient communication<br>
    ✅ Chatbot answers FAQs 24/7<br>
    ✅ Recordatorios y reservas en WhatsApp
  </p>

  <a href="#calendly" class="btn btn-primary" style="margin-top:1rem;">📅 Schedule a Free Demo</a>

  <hr>

  <h2>How It Works / Cómo Funciona</h2>
  <ol style="text-align:left;">
    <li>Embed the chatbot on your site</li>
    <li>Connect your Calendly</li>
    <li>Automate WhatsApp messages for reminders</li>
  </ol>

  <div id="calendly" style="margin-top:2rem;">
    <div class="calendly-inline-widget" data-url="https://calendly.com/YOUR_USER/demo" style="min-width:320px; height:630px;"></div>
    <script type="text/javascript" src="https://assets.calendly.com/assets/external/widget.js" async></script>
  </div>

  <a href="https://wa.me/YOUR_PHONE" class="btn btn-success" style="margin-top:1rem;">💬 Contactar por WhatsApp</a>

</section>

<script src="https://cdn.botpress.cloud/webchat/v0/inject.js"></script>
<script>
  window.botpressWebChat.init({
    "composerPlaceholder": "¿Cómo puedo ayudarte? / How can I help you?",
    "botId": "REPLACE_WITH_BOTPRESS_ID",
    "hostUrl": "https://cdn.botpress.cloud/webchat/v0",
    "messagingUrl": "https://messaging.botpress.cloud",
    "clientId": "REPLACE_WITH_BOTPRESS_ID",
    "lazySocket": true,
    "themeName": "prism",
    "stylesheet": "https://cdn.botpress.cloud/webchat/v0/themes/prism.css",
    "showPoweredBy": false
  });
</script>

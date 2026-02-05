---
title: Terminbuchung
description: Buchen Sie hier Ihren Termin!
author_profile: false
layout: single
canonical_url: 'https://tierarzt.cc/'
permalink: /buchungstool/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: "/assets/images/termin.jpg"
excerpt: "Ihr Termin bei uns in 1220 Wien"
---

**Willkommen bei unserem Buchungssystem!**

<div class="gcal-2click"
     data-gcal-src="https://calendar.google.com/calendar/appointments/schedules/AcZssZ2t375kzHzVSuROY7an2pDtjuOuEIU_1pjczjm5DAdvflV_9SF3YjkivJ_n1gbTgO-huoMgtEyr?gv=true"
     data-gcal-height="600"
     style="margin: 1rem 0;">

  <div class="notice notice--warning" style="padding: 1rem; border-radius: .75rem;">
    <p style="margin: 0 0 .75rem 0;">
      <strong>Online-Terminbuchung laden</strong><br>
      Beim Laden werden Inhalte von Google (Google Kalender) eingebunden. Dabei können Daten (z.B. IP-Adresse)
      an Google übertragen und Cookies/ähnliche Technologien verwendet werden.
    </p>

    <button type="button" class="btn btn--primary gcal-2click__btn">
      Buchungstool laden
    </button>

    <a class="btn btn--inverse"
       href="https://calendar.google.com/calendar/appointments/schedules/AcZssZ2t375kzHzVSuROY7an2pDtjuOuEIU_1pjczjm5DAdvflV_9SF3YjkivJ_n1gbTgO-huoMgtEyr?gv=true"
       target="_blank"
       rel="noopener noreferrer">
      In neuem Tab öffnen
    </a>

    <p style="margin: .75rem 0 0 0; font-size: .9em;">
      Mehr Infos in der <a href="/datenschutz/">Datenschutzerklärung</a>.
    </p>
  </div>

  <noscript>
    <p>
      JavaScript ist deaktiviert. Bitte öffnen Sie die Terminbuchung hier:
      <a href="https://calendar.google.com/calendar/appointments/schedules/AcZssZ2t375kzHzVSuROY7an2pDtjuOuEIU_1pjczjm5DAdvflV_9SF3YjkivJ_n1gbTgO-huoMgtEyr?gv=true"
         target="_blank" rel="noopener noreferrer">Buchungstool öffnen</a>
    </p>
  </noscript>
</div>

<script>
(function () {
  function init(el) {
    if (el.dataset.gcalInit === "1") return;
    el.dataset.gcalInit = "1";

    var btn = el.querySelector(".gcal-2click__btn");
    if (!btn) return;

    btn.addEventListener("click", function () {
      var src = el.getAttribute("data-gcal-src");
      var h = el.getAttribute("data-gcal-height") || "600";
      if (!src) return;

      var iframe = document.createElement("iframe");
      iframe.src = src; // <-- erst jetzt wird Google geladen
      iframe.style.border = "0";
      iframe.width = "100%";
      iframe.height = h;
      iframe.loading = "lazy";
      iframe.referrerPolicy = "no-referrer-when-downgrade";
      iframe.setAttribute("frameborder", "0");
      iframe.setAttribute("title", "Online Terminbuchung");

      el.innerHTML = "";
      el.appendChild(iframe);
    });
  }

  document.addEventListener("DOMContentLoaded", function () {
    document.querySelectorAll(".gcal-2click").forEach(init);
  });
})();
</script>

### Buchen Sie Ihren Tierarzttermin gleich online...
...oder rufen Sie unter <a href="tel:+43 1 28 32 779">+43 1 28 32 779</a> in unserer Ordination an. Wir beraten Sie gerne.

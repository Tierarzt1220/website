---
title: "Online-Terminbuchung"
description: "Tierarzttermin online buchen in Wien 1220 (Donaustadt) – schnell & bequem. Alternativ telefonisch: +43 1 28 32 779."
excerpt: "Tierarzttermin online buchen in Wien 1220 (Donaustadt)."
layout: single
author_profile: false
permalink: /buchungstool/
canonical_url: "https://tierarzt.cc/buchungstool/"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: "/assets/images/termin.jpg"
  og_image: "/assets/images/termin.jpg"
  teaser: "/assets/images/termin.jpg"
---

**Willkommen bei unserem Buchungssystem!**

<div class="gcal-2click"
     data-gcal-src="https://calendar.google.com/calendar/appointments/schedules/AcZssZ2t375kzHzVSuROY7an2pDtjuOuEIU_1pjczjm5DAdvflV_9SF3YjkivJ_n1gbTgO-huoMgtEyr?gv=true"
     data-gcal-height="600">

  <div class="gcal-consent-card" role="group" aria-label="Online Terminbuchung">
    <div class="gcal-consent-card__badge">
      <span class="gcal-consent-card__dot" aria-hidden="true"></span>
      Externer Inhalt (Google Kalender)
    </div>

    <h3 class="gcal-consent-card__title">Online-Terminbuchung</h3>
    <p class="gcal-consent-card__subtitle">
      Zum Laden der Terminbuchung werden Inhalte von Google (Google Kalender) eingebunden.
      Dabei können Daten übertragen und Cookies/ähnliche Technologien genutzt werden.
    </p>

    <div class="gcal-consent-card__actions">
      <button
        type="button"
        class="btn btn--primary gcal-2click__btn"
        style="font-size: 1.05rem; padding: .9rem 1.2rem; border-radius: .9rem;"
      >
        Zustimmen und Terminbuchung laden
      </button>
    </div>

    <p class="gcal-consent-card__fineprint">
      Mehr Infos in der <a href="/datenschutz/">Datenschutzerklärung</a>.
    </p>
  </div>

  <noscript>
    <p>
      JavaScript ist deaktiviert. Bitte rufen Sie uns für eine Terminvereinbarung an:
      <a href="tel:+43 1 28 32 779">+43 1 28 32 779</a>.
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
      iframe.src = src; // Google wird erst jetzt geladen
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

---
title: "Praxis-Webshop für Tierbedarf"
description: "Diätfutter und Ergänzungsfuttermittel für Ihr Tier nachbestellen: Die Beratung erfolgt in 1220 Wien, die Bestellung über den VetNative-Shop der Praxis am Bacherplatz."
image: /assets/images/service-review/ernaehrungsberatung.jpg
permalink: /shop/
layout: single
classes: wide
---

<style>
  .shop-intro {
    display: flex;
    align-items: center;
    gap: 1rem;
    max-width: 74ch;
    margin: 0 0 1.25rem;
  }

  .shop-intro p { margin: 0; }
  .shop-intro img {
    width: clamp(4.5rem, 16vw, 8rem);
    height: auto;
    flex-shrink: 0;
    border-radius: 0.35rem;
  }

  /* Inhaltsbereich möglichst breit machen */
  .page {
    width: 100% !important;
    padding-right: 0 !important;
  }

  .page__inner-wrap,
  .page__content {
    width: 100% !important;
    max-width: none !important;
  }

  .shop-wrapper {
    width: 100%;
    margin: 0;
    padding: 0;
  }

  /* Hinweisbanner */
  .shop-notice {
    position: sticky;
    top: 0;
    z-index: 1000;

    margin: 0;
    padding: 0;

    background: #eef7ff;
    border-bottom: 1px solid #c9e4f7;

    font-size: 0.95rem;
    line-height: 1.5;
  }

  .shop-notice summary {
    padding: 12px 20px;
    cursor: pointer;
    user-select: none;
  }

  .shop-notice summary strong {
    font-weight: 700;
  }

  .shop-notice-content {
    padding: 0 20px 14px 20px;
  }

  /* Shop-Frame */
  .shop-frame {
    display: block;
    width: 100%;
    height: calc(100vh - 120px);
    min-height: 750px;

    border: 0;
    background: #fff;
  }

  /* Mobile */
  @media (max-width: 768px) {
    .shop-notice {
      font-size: 0.88rem;
    }

    .shop-notice summary {
      padding: 10px 14px;
    }

    .shop-notice-content {
      padding: 0 14px 12px 14px;
    }

    .shop-frame {
      height: calc(100vh - 140px);
      min-height: 650px;
    }
  }
</style>

<div class="shop-wrapper">
  <div class="shop-intro">
    <p>Hier können Sie das empfohlene Diätfutter oder ein Ergänzungsfuttermittel nachbestellen. Ihre Bestellung läuft über den VetNative-Webshop der Tierarztpraxis am Bacherplatz. Bei Fragen zur Fütterung berät Sie <a href="/ernaehrungsberatung/">unser Team in 1220 Wien</a>.</p>
    <img src="/assets/images/service-review/ernaehrungsberatung.jpg" alt="Tierärztliche Ernährungsberatung für einen Hund" width="1200" height="800" decoding="async">
  </div>

  <details class="shop-notice" open>
    <summary>
      <strong>Hinweis zu unserem Webshop</strong>
    </summary>

    <div class="shop-notice-content">
      In unserem Webshop in Kooperation mit VetNative und Tierarztpraxis am Bacherplatz finden Sie ein umfangreiches Sortiment.

      <strong>Bitte beachten Sie:</strong> Einige der angebotenen Produkte sind für besondere
      medizinische oder ernährungsphysiologische Bedürfnisse bestimmt. Diätfuttermittel und
      Nahrungsergänzungsmittel dürfen daher nur nach tierärztlicher Beratung verwendet werden,
      da sie Teil der Therapie sind.
    </div>
  </details>

  <iframe
    class="shop-frame"
    src="https://eltiga.vetnative.com/shop/landing?code=TVRFMU9BLjN4bm42X1ZsVGNRM2cyS1BNNDZfRm1CS1UwdjRBYzk0NkxQbG1hbUlvVzQ"
    title="Tierarztpraxis am Mühlgrund Online-Shop"
    loading="eager"
    allow="payment *"
    referrerpolicy="strict-origin-when-cross-origin">
  </iframe>

</div>

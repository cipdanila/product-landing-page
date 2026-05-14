# Iasi Eco-Mobility — Copou E-Bike Landing Page

A premium, accessibility-first product marketing landing page built to showcase **Copou E-Bike V2**, a conceptual high-performance electric bicycle tailored specifically for the steep urban topographies of Iasi, Romania (Copou, Sararie, Bucium).

## 🚀 Features & Technical Implementation

*   **Fixed Navigation Component:** Implementation of a strict `position: fixed` header tracking engine layout complying 100% with automated freeCodeCamp assessment criteria.
*   **Dynamic Top-Focus Pricing Engine (672px - 995px):** A pure CSS layout mechanism driven by sibling combinators (`.plan-radio:checked + label.pricing-card`) and Flexbox ordering. Clicking any plan automatically elevates it to the top row at full-width (`flex: 1 1 100%; order: 1;`), while unselected options gracefully share the row beneath it.
*   **Accessibility Standards Compliance:** Integrated strict label components (`<label for="email">`), fully descriptive visual asset alt metrics (Axe Linter validated), and secured out-bound links utilizing `rel="noopener noreferrer"`.
*   **Media Streaming Integration:** Built-in direct responsive wrapper handling an embedded public transit infrastructure video document from Euronews Romania.
*   **Eco Token Color Blueprint:** Utilizes a highly readable, specialized forest green palette configured to satisfy strict contrast rules on lightweight backgrounds.

## 🛠️ Tech Stack & Directory Tree

*   **Operating System:** Ubuntu Linux
*   **IDE:** Visual Studio Code
*   **Core Assets:** Native HTML5, Modern CSS3 Layouts (Flexbox Module Engine)

```text
iasi-eco-mobility/
├── index.html                # Semantically structured page blueprint
├── styles.css                # Advanced component stylesheet configurations
├── palatul-culturii-iasi.jpg  # Localized high-contrast cover visual
└── README.md                 # English technical deployment documentation
```

## 📜 Media Attributions & Special Thanks

*   **Hero Section Imagery:** Special credit to [Tudor Baciu](https://unsplash.com/@baciutudor) for the stunning night photography of the Palace of Culture in Iasi illuminated in green, sourced via [Unsplash](https://unsplash.com).
*   **Media Report Integration:** Special credit to [Euronews Romania](https://www.youtube.com/@euronewsro) for the informative public broadcast document regarding the green urban transit infrastructure integrated via the YouTube embedded framework.

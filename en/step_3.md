<h2 class="c-project-heading--task">Give it terminally bad taste</h2>

Change the custom properties at the top of `style.css` so the popup artefact gets darker, louder, and more dramatic.

<h2 class="c-project-heading--explainer">Make this change</h2>

Open `style.css` and edit the values inside `:root`. These custom properties control the page background, the panel colours, the accent colours, the border size, the font, and the panel width.

<div class="c-project-tip">

<h3>Tip</h3>

<p>Pick colours that feel like a cursed browser warning, a fake software installer, or a popup that absolutely should not be trusted.</p>

<p>Small value changes can make the page feel more sugary, more chaotic, or more fake-dangerous.</p>

<p><a href="https://www.google.com/search?q=web+colour+picker" target="_blank" rel="noopener noreferrer">Open the Google web colour picker in a new tab</a> if you want help choosing colours.</p>

</div>

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 2-13
---
/* Build a cursed popup artefact with one suspicious browser button. */
:root {
  --page-bg: #120014;
  --ink: #26001b;
  --panel-bg: #ffd8f2;
  --accent: #ff73c6;
  --accent-hot: #7eeeff;
  --accent-warning: #ffe45a;
  --shadow-color: #170011;
  --border-size: 5px;
  --corner-size: 20px;
  --body-font: Verdana, Geneva, sans-serif;
  --panel-width: 35rem;
}
--- /code ---

</div>

## Now run your code

The page should still work the same way, but the popup artefact should feel much more cursed.

<div class="c-project-output">
  <img src="images/step_3_output.png" alt="Expected project output after step 3 showing darker colours and louder popup styling.">
</div>

<h2 class="c-project-heading--task">Add the evidence box</h2>

Add one result paragraph so the page has somewhere to show an answer later.

<h2 class="c-project-heading--explainer">Make this change</h2>

Stay in `index.html` and put the new paragraph underneath the button inside `<main class="popup-panel">`.

<div class="c-project-tip">

<h3>Tip</h3>

<p>The `#result` style is already waiting in `style.css`, so the box will appear as soon as you add the HTML.</p>

</div>

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 11
line_highlights: 17
---
    <main class="popup-panel">
      <p class="eyebrow">Recovered popup artefact // triggered at 1:43am</p>
      <h1>warning_popup_FINAL-final.exe</h1>
      <p class="status">mood: screenshot under review</p>
      <p>Press the button if you enjoy suspicious popups and fake browser warnings from a profile nobody can trace back to you.</p>
      <button type="button" class="panic-button">press if you read the tiny cursed text</button>
      <p id="result" aria-live="polite"></p>
    </main>
--- /code ---

</div>

## Now run your code

You should now see an empty evidence box underneath the button.

<div class="c-project-output">
  <img src="images/step_5_output.png" alt="Expected project output after step 5 showing the empty evidence box under the button.">
</div>

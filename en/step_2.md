<h2 class="c-project-heading--task">Add the suspicious button</h2>

Add the warning paragraph and the button underneath the header so the page has something dangerous-looking to press.

<h2 class="c-project-heading--explainer">Make this change</h2>

Add the warning paragraph and button inside the tags, underneath the status:

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 9
line_highlights: 13-14
---
    <main class="popup-panel">
      <p class="eyebrow">Recovered popup artefact // triggered at 1:43am</p>
      <h1>warning_popup_FINAL-final.exe</h1>
      <p class="status">mood: screenshot under review</p>
      <p>Press the button if you enjoy suspicious popups and fake browser warnings from a profile nobody can trace back to you.</p>
      <button type="button" class="panic-button">press if you read the tiny cursed text</button>
    </main>
--- /code ---

</div>

## Now run your code

You should now see the warning text and one large suspicious button.

<div class="c-project-output">
  <img src="images/step_2_output.png" alt="Expected project output after step 2 showing the warning text and the suspicious button.">
</div>

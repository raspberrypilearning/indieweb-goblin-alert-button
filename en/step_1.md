<h2 class="c-project-heading--task">Add the popup artefact header</h2>

Add the visible header inside `<main class="popup-panel">` so the page stops looking empty.

## Step 1
Run the code to see the unstyled page.

## Step 2
The starter file has an empty `<main>` element, so add the top box content, the main heading, and the mood line inside it.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 1
line_highlights: 10-14
---
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>warning_popup_FINAL-final.exe</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <main class="popup-panel">
      <p class="eyebrow">Recovered popup artefact // triggered at 1:43am</p>
      <h1>warning_popup_FINAL-final.exe</h1>
      <p class="status">mood: screenshot under review</p>
    </main>
  </body>
</html>
--- /code ---

</div>

## Now run your code

You should see the popup artefact header inside the panel instead of an empty box.

<div class="c-project-output">
  <img src="images/step_1_output.png" alt="Expected project output after step 1 showing the popup artefact header inside the panel.">
</div>

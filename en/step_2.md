<h2 class="c-project-heading--task">Add the page background</h2>

You will centre the page on a bright background so the button has room to stand out.

### Step 1

Stay in `index.html` and add the start of your `<style>` block inside the `<head>`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 1
line_highlights: 6-22
---
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Goblin Alert Button</title>
    <style>
      * {
        box-sizing: border-box;
      }

      body {
        margin: 0;
        min-height: 100vh;
        display: grid;
        place-items: center;
        padding: 24px;
        font-family: "Trebuchet MS", Verdana, sans-serif;
        color: #1e1234;
        background: linear-gradient(180deg, #fff09c, #ffb0df 55%, #90f8ff 100%);
      }
    </style>
  </head>
</html>
--- /code ---

</div>

<h2 class="c-project-heading--task">Test</h2>

**Run your code:** You should now see the page centred on a loud background, even though the content still looks plain.

<div class="c-project-output">
  <img src="images/step_2_output.png" alt="Observed project output after this step.">
</div>

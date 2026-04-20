<h2 class="c-project-heading--task">Make the browser react</h2>

You will add one inline script that makes the button open a browser-owned alert when it is clicked.

### Step 1

Add this `<script>` block near the bottom of `index.html`, then change the text inside the quoted alert message to any harmless silly warning you like.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 57
line_highlights: 64-69

---
  <body>
    <main>
      <h1>One rude little browser alert</h1>
      <p>Press the button if you would like the browser to announce something completely harmless.</p>
      <button type="button">Press for goblin news</button>
    </main>

    <script>
      document.querySelector("button").setAttribute(
        "onclick",
        "alert('Warning: you have entered goblin territory.')"
      );
    </script>
  </body>
</html>
--- /code ---

</div>

The popup belongs to the browser, so you do not style it with CSS. If you test it, keep the page tab active because browsers can behave differently when a page is in the background.

<h2 class="c-project-heading--task">Test</h2>

**Run your code:** When you click the button, the browser should show your silly alert message.

<div class="c-project-output">
  <img src="images/step_5_output.png" alt="Observed project output after this step.">
</div>

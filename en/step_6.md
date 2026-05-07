<h2 class="c-project-heading--task">Make the page choose an outcome</h2>

Replace the alert script so the browser asks a yes-or-no question and the page shows one result for OK and another for Cancel.

<h2 class="c-project-heading--explainer">Make this change</h2>

Replace the old script with this version.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 18
line_highlights: 19-22
---
    <script>
      document.querySelector(".panic-button").setAttribute(
        "onclick",
        "document.querySelector('#result').textContent = window.confirm('Do you accept the terms of this extremely bad popup?') ? 'Noted. Your desktop has been added to the watchlist.' : 'Too late. The popup log still says you hovered here at 1:43am.'"
      );
    </script>
  </body>
</html>
--- /code ---

</div>

The confirm box belongs to the browser, so you do not style it with CSS. Browsers treat ignored dialogs like Cancel, so the page should still show one sensible result.

## Now run your code

Click the button and the page should show one outcome for OK and a different outcome for Cancel.

<div class="c-project-output">
  <img src="images/step_6_output.png" alt="Expected project output after step 6 showing the page result after the browser confirm choice.">
</div>

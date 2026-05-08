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

The confirm box belongs to the browser, so you do not style it with CSS. The screenshot below shows one example of how the confirm box might look, and browsers treat ignored dialogs like Cancel.

## Now run your code

Click the button and the browser should show the confirm box. Choose OK or Cancel and the page should then show the matching outcome.

<div class="c-project-output">
  <img src="images/popup2.png" alt="Expected browser confirm popup after clicking the button in step 6.">
</div>

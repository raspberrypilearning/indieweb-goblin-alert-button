<h2 class="c-project-heading--task">Make the browser shout</h2>

Add one small script so clicking the button makes the browser show a popup alert.

<h2 class="c-project-heading--explainer">Make this change</h2>

Go back to `index.html` and put this `<script>` block underneath `</main>`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 18
line_highlights: 20-24
---
    </main>

    <script>
      document.querySelector(".panic-button").setAttribute(
        "onclick",
        "alert('Warning: this profile has attempted to install glitter.exe.')"
      );
    </script>
  </body>
</html>
--- /code ---

</div>

The popup belongs to the browser, so you do not style it with CSS.

## Now run your code

Click the button and the browser should show your warning popup.

<div class="c-project-output">
  <img src="images/step_4_output.png" alt="Expected project output after step 4 showing the popup page before the browser alert appears.">
</div>

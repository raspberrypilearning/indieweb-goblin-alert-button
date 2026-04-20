<h2 class="c-project-heading--task">Style the panel</h2>

You will turn the plain content into a small bright panel with a bold heading and readable text.

### Step 1

Stay in the same `<style>` block and add styles for `main`, `h1`, and `p`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 23
line_highlights: 23-42
---
      main {
        width: min(420px, 100%);
        padding: 28px;
        text-align: center;
        border: 5px solid #1e1234;
        border-radius: 24px;
        background: rgba(255, 255, 255, 0.9);
        box-shadow:
          0 0 0 6px #ffffff,
          0 16px 0 #1e1234;
      }

      h1 {
        margin: 0;
        font-size: clamp(2rem, 8vw, 3rem);
        line-height: 0.95;
        text-transform: uppercase;
      }

      p {
        margin: 14px 0 0;
        line-height: 1.5;
      }
--- /code ---

</div>

<h2 class="c-project-heading--task">Test</h2>

**Run your code:** You should now see the heading and text sitting inside a bright little panel.

Try changing the colour values and the `border` or `box-shadow` values to make the panel feel more like your own weird little web toy. If you want help picking colours, open the <a href="https://www.google.com/search?q=color+picker" target="_blank" rel="noopener noreferrer">Google colour picker</a> in a new tab.

<div class="c-project-output">
  <img src="images/step_3_output.png" alt="Observed project output after this step.">
</div>

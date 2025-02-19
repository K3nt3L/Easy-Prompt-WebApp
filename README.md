# Easy-Prompt-WebApp
<H1>A simple HTML/JS application to visually manipulate your SDXL prompt.</H1>

The application is just a simple HTML file with JS to manage the interface.

*Une version française est disponible dans le repo.*

As I was tired of copying and pasting while editing my prompts, I decided to create a small visual tool that allows me to color certain parts of the prompt, change the position of tokens by dragging and dropping, delete them, etc.
For example, I use one color for everything related to the main subject, another for the style or medium, and another for the details. 

Do as you feel :)

Simply download the HTML file and open it with your preferred web browser.

There are two versions: one in English, the other in French.


<ol>
<li>Enter your text in the provided area using commas or periods to separate tokens.</li>
<li>Choose the font size for the text area using the dropdown menu.</li>
<li>Click on "Load Tokens" to convert the text into tokens.</li>
<li>You can move tokens by dragging and dropping or edit them by double-clicking.</li>
<li>To change a token's color, right-click to open the context menu and select one of the available colors.</li>
<li>The "Split words" option splits a token into multiple tokens while retaining its color.</li>
<li>Hold the Ctrl key and click on adjacent tokens to select multiple tokens. A "Merge tokens" option will appear in the context menu to merge them.</li>
<li>After editing, click on "Validate" to obtain the final text with commas as the only separators, along with the total number of words displayed below.</li>
<li>Double click on a box for editing content</li>
</ol>


![screenshot](https://github.com/K3nt3L/Easy-Prompt-WebApp/blob/main/easy_prompt_screenshot.jpg)


<H3>New in Update 1.3</H3>

<ol>
 <li>There are now two text input fields: one for the positive prompt, the other for the negative prompt.</li> 
  <li>The context menu has been fixed to add the ability to delete a token.</li>
  <li>After editing and validating both prompts, it is possible to export the entire set into a text file compatible with Inspire Pack.</li>
</ol>

What's the Inspire pack format : 

It is a plain text file that combines the positive prompt and the negative prompt in the following format:

---

positive:token1, token2

negative:token_n1, token_n2

---

You can find the nodes here :

[Inspire Pack for ComfyUI] (https://github.com/ltdrdata/ComfyUI-Inspire-Pack "by Dr.Lt.Data")




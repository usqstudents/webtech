<h3>Practicals</h3>

---

<details>    
<summary><b>Week 3: HTML</b></summary>
     
<h5>Exercise 1</h5>
<p>If you did not complete the exercises from last week, do so.</p>
<p>If you have not read Modules 1 and 2 of the Study Book, do so.</p>
	   
<h5>Exercise 2</h5>
<p>The HTML used in last week’s practical is written in XHTML.
The same code in HTML is:</p>

```
<!DOCTYPE html>
<html lang="en">
  <head>
  <title>
     A simple HTML document
  </title>
  </head>

  <body>
     <section>
       <h1>HTML Test Page</h1>
       <p>This is the first paragraph on the page!</p>
       <section>
         <h2>A Subsection Heading</h2>
         <p>This is the second paragraph on the page!</p>
       </section>
     </section>
  </body>
</html>
```

<p>There is little difference between this HTML and the HTML of
last week. But there is a big difference how a browser deals
with an error.</p>

<p>Using last week's XHTML code, create a file
<kbd>test.xhtml</kbd> and using the code above create another
file <kbd>test.html</kbd></p>

<p>Test that both files are parsed correctly by the Web
browser.</p>

<p>Now introduce an error in both files—delete one of the		
</p> tags. Now how are they displayed by the Web browser?</p>

<p>Copy <kbd>test.xhtml</kbd> to <kbd>alt.html</kbd> and copy
<kbd>test.html</kbd> to <kbd>alt.xhtml</kbd>. Now display the
alternate files in the Web browser. What has happened?</p>

<p>How important are the file extensions to the browser?
How important the first line of each file to the browser?</p>

<p>Notice how <kbd>alt.xhtml</kbd> (the HTML document
masquerading as an XHTML document) is displayed. Remove the
error from <kbd>alt.xhtml</kbd> and display it again—what is
the browser’s responce</p>

<p>XHTML, being XML documents are more restrictive with errors
and the browser will warn you if there is an error in your
document. The advantage (and frustration) of XHTML documents
is that the browser will error check your HTML document.</p>

<h5>Exercise 3</h5>
<p>Structure the text file <a href="../master/prac/p03/Poets.txt">Poets.txt</a>
using XHTML markup. The file contains three poems about the
First World War, by poets that participated in the conflict.
Structure the file using markup so the text is sectioned
logically by using headings, sections, paragraphs, &amp;c.</p>

Remember, HTML markup is used to logically
structure the source file it is not used to format the
browser's output.

<h5>Exercise 4</h5>
Format the text file <a href="../master/prac/p03/Heracles.txt">Heracles.txt</a>
using XHTML markup. The file contains the opening scene of Euripides'
play Heracles. To format the file make use of Emphasised, Italic
and Bold text, headings, a Descriptive List, &amp;c.</p>

<h5>Exercise 5</h5>
<p>
Structure the text file <a href="../master/prac/p03/TheLongShips.txt">TheLongShips.txt</a>
using XHTML markup. The file contains the opening paragraph of 
Frans Bengtsson’s book “The Long Ships”. Use the 
<code>id</code> attribute to correctly setup links to the footnotes 
and from the footnotes backto the text.
</p>
       
<h5>Exercise 6</h5>    
Structure the following Body Mass Index table 
from the World Health Organisation using the <kbd>table</kbd> element.
<pre>
Classification                           BMI(kg/m<sup>2</sup>)
<strong>Underweight</strong>                               <18.50
    Severe thinness                        <16.00 
    Moderate thinness                   16.00 - 16.99
    Mild thinness                       17.00 - 18.49
<strong>Normal Range</strong>                           18.50 - 24.99
<strong>Overweight</strong>                                &#x2265;25.00
     Pre-obese                          25.00 - 29.99
     <strong>Obese</strong>                                &#x2265;30.00
          Obese class I                 30.00 - 34-99
          Obese class II                35.00 - 39.99
          Obese class III                  &#x2265;40.00 
</pre>
</details>

---

<details>
<summary><b>Week 4: CSS Intro</b></summary>
<h5>Exercise 1</h5>
<p>
If you did not complete the exercises from last week, do so.
If you have not read Chapters 1 to 3 of the Study Book, do so.
</p>
<h5>Exercise 2</h5>
<p>
Add style to the HTML file created from the text file Poets.txt. Add the style using the style element in the HTML document header.
Experiment with the different forms of white-space, font-style, font-size, &c. for different sections of the document. 
</p>
<h5>Exercise 3</h5>
<p>
Add style to the structured file created from the text file Heracles.txt. Add the style using a separate style file and use the link element to tie th style file to the HTML document.
Experiment with the different forms of font-style, font-size, text-align, color &c. for different sections of the document.
</p>
<h5>Exercise 4</h5>
<p>
Add style to the structured file created from the text file TheLongShips.txt
Experiment with changing the style of the footnotes, study the footnotes used in the StudyBook. How is the selected footnote highlighted?
</p>
</details>

---

<details>
<summary><b>Week 5: Advanced CSS</b></summary>

<h5>Exercise 1</h5>
<p>
The Web site
<a href="http://www.csszengarden.com">http://www.csszengarden.com</a>
has been around for many years and though it is specifically
aimed at graphic artists it does show what is possible with
CSS</p>
<p>This site has only one page in which the HTML “content” is
fixed - only the presentation of the HTML elements can be
altered by the “style” author through CSS commands.
The CSS commands used are straight forward —
the effects can dramatic. For example,
consider the wide-screen version of
“<a href="http://www.csszengarden.com/219/">Steel</a>” by
Steffen Knoeller. This design uses CSS3 features for a
dramatic effect and has different style sheets for different
wih5h displays. Experiment by changing the wih5h of the Web
browser window.</p>


<h5>Exercise 2</h5>
<p>Use Google Chrome's inbuilt <em>Developer Tools</em> interface
(press <kbd>ctrl+shift+i</kbd>) to explore the CSS boxes that exist
in a web page.  Load a variety of websites (start with something simple,
like the CSC2406 course page, and graduate to more complex sites) to
learn how they are structured.</p>
<p>Simply hover your mouse over an element in the Document Tree as 
displayed in the <em>Elements</em> tab in the Developer Tools interface.
You will see the corresponding box being highlighted in the website page
itself. Start with the <kbd>body</kbd> element and work your way down
in the element tree.</p>
<p><em>Note:</em> the World Wide Web contains many sites/pages that are
<em>not</em> good examplars for how things should be done. Always be
mindful of the possibility of an example not representing good practice. Where
possible, look for sites that make a statement about wanting to use
CSS3 (and HTML5) correctly. The above CSS Zen Garden site is an example.</p>


<h5>Exercise 3</h5>
<p>Study the
<a href="https://tau.usq.edu.au/courses/CSC2406/StudyBook/examples/CSS/beowulf.xhtml">Beowulf</a> example of
using floating blocks to create a
two column display on a Web page.</p>
<p>Also note the small design change if the Web browser’s window
becomes narrow.</p>
<p>At the bottom of the <a href="https://tau.usq.edu.au/courses/CSC2406/StudyBook/examples/CSS/beowulf.xhtml">Beowulf</a>
HTML page there is the line:</p>
<p><kbd>&lt;div style="clear:
left"&gt;&amp;#160;&lt;/div&gt;</kbd></p>
<p>What is its purpose? What happens if the line is
removed?</p>
<p>When an element is positioned using the <kbd>float</kbd>
property or positioned absolutely  with <kbd>position:
absolute;</kbd> it is said to “be removed from the
normal flow” What does that mean?</p>
<p>When is a positioned element not removed from the normal flow?</p>

<h5>Exercise 4</h5>
Convert the  the HTML file created from the text
file <a href="../master/prac/p03/Poets.txt">Poets.txt</a> into a multicolumn
document using the <kbd>float</kbd> property. What happens as
the wih5h of the Web browser’s window is changed? 

<h5>Exercise 5</h5>
<p>Study the  <a href="https://tau.usq.edu.au/courses/CSC2406/StudyBook/examples/CSS/menus.xhtml">CSS menu</a>
example which uses absolutely positioning elements.</p>
<p>Why is there a small (1 pixel?) transparent gap between the
menu elements? This is a mistake since as the cursor moves
between menu elements the menu can irritatingly collapse
as the cursor has moved outside the menu
— this is very much browser dependent.
Can you see what needs to be done to remove the transparent border?</p>
<p>When an element is positioned using the <kbd>float</kbd>
property or positioned absolutely  with <kbd>position:
absolute;</kbd> it is said to “be removed from the
normal flow” What does that mean?</p>
<p>When is a positioned element not removed from the normal
flow?</p>

<h5>Exercise 6</h5>
<p>Consider the following HTML file of
<a href="https://tau.usq.edu.au/courses/CSC2406/Practicals/HenryV_IV_III.xhtml">Act IV, Scene III</a> of
William Shakespeare’s play, King Henry V. The dialog is
structured using a descriptive list. Change the style of the
<kbd>h5</kbd> element so that it is inline with the characters
dialog. (cf. The exercises on this page).</p>
<p>Add CSS commands so that if the browser's window is narrow
(500px, say) the <kbd>h5</kbd> element is on a line of its own
(that is the default style of a descriptive list).</p> 

<h5>Exercise 7</h5>
Why in the original HTML file  of
<a href="https://tau.usq.edu.au/courses/CSC2406/Practicals/HenryV_IV_III.xhtml">Act IV, Scene III</a> of
William Shakespeare’s play, King Henry V the HTML line break
element was used to break lines not the CSS
white-space property?      
</details>

---

<details>
	<summary><b>Week 6: Design</b></summary>
<h5>Exercise 1</h5>
<p>Read the Chapter on <a href="https://tau.usq.edu.au/courses/CSC2406/StudyBook/04Design.xhtml">Web Design</a></p>

<h5>Exercise 2</h5>
<p>Complete all previous practical exercises</p>

<h5>Exercise 3</h5>
<p>Attempt the questions at the end of the Web Design chapter</p>

<h5>Exercise 4</h5>
<p>Go back to the pages you created in earlier practicals. Review your pages — are they User Centred Design?</p>

<h5>Exercise 5</h5>
<p>Study the Web site  <a href="http://www.usq.edu.au">www.usq.edu.au</a>. Using the 4.4 Usability Guidelines section — what are the good design points of the site? What are the bad? Try not to be influenced by whether you like the site or not (I know it is difficult.)</p>

<h5>Exercise 6</h5>

<p>You have been approached to design a Web site for a retail company that wants to sell tropical fish, aquarium equipment, and also provide a cleaning amd maintenence service in a major city. It delivers to the door.</p>

<p>Think about the site design: what major sections should be incorporated? What parts are critical for the retail business and what is eye candy? What is a visitor’s primary objective?</p>

<p>Think about the page design: Structure of a page? Positioning of the major parts of the page? Colours? Font?</p>

<p>Responsive design? If it is going to be responsive then this will effect the basic design.</p>

<p>Suggested tasks:</p>

<ul>
	<li>Suggest the major sections of the site.</li>
	<li>Draw the base design of the page. and how each section should look</li>
	<li>Map the paths to key pages a user must visit to order services.</li>
	<li>Justify all design decisions made</li>
</ul>
</details>

---

<details>
	<summary><b>Week 7: The DOM</b></summary>
<h5>Exercise 1</h5>
<p>Read Section 5.2 Scripting of the Study Book and study the examples.</p>

<h5>Exercise 2</h5>
<p>Using the source of this <a href="prac07.html">linked HTML page</a> draw a representative tree structure</p>

<h5>Exercise 3</h5>
<p>Using the Chrome Developer Tools compare your tree to the DOM tree that Chrome creates.</p>

<h5>Exercise 4</h5>
<p>Using the DOM function—<br/><kbd>document.getElementsByTagName('p')</kbd><br/>count the number of paragraphs in the document. Display the answer by using the DOM function-<br/><kbd>window.alert()</kbd></p>

<h5>Exercise 5</h5>
<p>Using the DOM function—<br/><kbd>document.getElementsByClassName('second')</kbd><br/>count the number of list items in the second list. Display the answer by using the DOM function-<br/><kbd>window.alert()</kbd></p>

<h5>Exercise 6</h5>
<p>Using the DOM function—<br/>
<kbd>document.querySelector('…')</kbd><br/> get the contents of the last list item of the first unordered list. Display the answer by using the DOM function-<br/><kbd>window.alert()</kbd></p>

<h5>Exercise 7</h5>
<p>Repeat the exercises above but instead of displaying the
result in an alert popup display the result in a newly created
paragraph element and added to the <kbd>div id="DOM"</kbd>
element.</p>
<p>The steps to create a new node are:</p>
<ol>
<li>Use <kbd>document.createElement('p')</kbd> to create a
new paragraph.</li>
<li>Use <kbd>document.createTextNode('…')</kbd> to create a
new text node.</li>
<li>Attach the text node to the paragraph node with
the <kbd>appendChild()</kbd> method.</li>
<li>Attach the paragraph node to the <kbd>div id="DOM"</kbd> node with
the <kbd>appendChild()</kbd> method.</li>
</ol>
</dl>

</details>
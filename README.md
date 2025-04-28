# csci111-lab-3-solved
**TO GET THIS SOLUTION VISIT:** [CSCI111 Lab 3 Solved](https://www.ankitcodinghub.com/product/csci-111-lab-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116900&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI111 Lab 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
File names: Names of files and variables, when specified, must be EXACTLY as specified. This includes simple mistakes such as capitalization.

Modify each of these files so that they make a 4×4 grid of squares instead of a 2×2 grid. Make as few changes to the files as you can.

Each line that is modified from the original should have a comment at the end of the line like this:

x = func(y) # CHANGED

Each line that is new and not in the original should have a comment at the end of the line like this:

x = func(y) # NEW

Leave the filenames as grid00.py, etc.

Minkowski islands: Do Exercise 6, Chapter 5, in the textbook on the Koch curve and the Koch snowflake. Feel free to look at the author’s solutions after you have done it yourself. You do NOT have to turn in your snowflake.

Look up Minkowski sausage in Wikipedia. There you will find three generators for Minkowski sausages, illustrated in Figures 1, 2, and 3.

Each of these can be used to make a Minkowski Island by drawing four of them around a square.

Write a function for each of these generators, and place each in its own file:

koch1 in koch1.py koch2 in koch2.py koch15 in koch16.py

Each function will take as arguments a turtle and a distance, as in the snowflake solution accompanying the textbook.

The recursion is stopped when the distance is less than 10.

Each generator uses a different reduction in size for the distance in the recursive calls. Figure out which distance will preserve the total length, regardless of how big it is.

Write a single function island, that takes a turtle and a generator as arguments, and makes the turtle draw the generator around all four sides of a square. Islands look like Figures 4, 5, and 6.

In each of your three files, define a turtle bob, set its speed to 0, and call island(bob, 200, generator) so that the island will be drawn when the module is run.

Replace generator in each case with koch1, koch2 or koch16, accordingly.

Figure 1: Koch type 1 generator

Figure 2: Koch type 2 generator

Figure 3: Koch type 1.6 generator

Figure 4: Koch type 1 island

Figure 5: Koch type 2 island

Figure 6: Koch type 1.6 island

# comp340-homework-5--lexer-solved
**TO GET THIS SOLUTION VISIT:** [COMP340 Homework 5- Lexer Solved](https://www.ankitcodinghub.com/product/comp340-homework-5-lexer-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91129&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP340 Homework 5- Lexer Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
Homework Description

In this homework, you need to complete lexer.py that we’ve worked on during the class. In our interpreter, a lexer needs to handle seven tokens as shown below.

</div>
</div>
<div class="layoutArea">
<div class="column">
COMP 340 – HW 5 Due date: 04/20/2020 11:59 pm Total Points: 20 pts

</div>
</div>
<div class="layoutArea">
<div class="column">
Token Type

NUMBER

PLUS

MINUS MULTIPLICATION DIVISION LPAREN

RPAREN

</div>
<div class="column">
Token Value

0,1,2,3,….,9 +

–

*

/ ( )

</div>
</div>
<div class="layoutArea">
<div class="column">
Currently, our lexer produces NUMBER token and PLUS token. Complete lexer.py so that our lexer also produces other tokens (MINUS, MULTIPLICATION, DIVISION, LPAREN, RPAREN).

Assume that we run main.py with srcCode=“((12+3*5)+5/4)” with the completed lexer.py like the below.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
import lexer

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
srcCode = “((12+3*5)+5/4)” tokSeq = lexer.tokenize(srcCode)

for i in tokSeq: print(i.type, i.value)

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
main.py

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 1 of 3

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Then, it should print a sequence of tokens:

<pre>LPAREN (
LPAREN (
NUMBER 12
PLUS +
NUMBER 3
MULTIPLICATION *
NUMBER 5
</pre>
<pre>RPAREN )
PLUS +
NUMBER 5
DIVISION /
NUMBER 4
RPAREN )
</pre>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>

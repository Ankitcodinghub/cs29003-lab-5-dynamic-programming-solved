# cs29003-lab-5-dynamic-programming-solved
**TO GET THIS SOLUTION VISIT:** [CS29003 Lab 5-Dynamic Programming Solved](https://www.ankitcodinghub.com/product/cs29003-lab-5-dynamic-programming-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92905&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS29003 Lab 5-Dynamic Programming Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

Problem Statement

Recently you have joined a chemistry lab and they are leading a research on a system which consists of a sequence of independent and essential chemical reactions. Surprisingly the researchers of the lab have discovered a unique catalyst and it can be included in any of the reactions of the system. The use of the catalyst enhances the rate of the reaction and hence its probability of success also. Also they have proven that the probability of success of the reactions depends on the usage of the catalyst, typically expressed in terms of number of units involved in the reaction. The more the quantity (units) of catalyst is used in a reaction, the probability of success increases or remains the same, but never decreases. The probability of success of the entire system is the product of the probability of success of each of the individual reactions. Given the limited quantity (units) of the catalyst, the researchers want to gain the maximum success of the system. As an expert in algorithms, you are given the task of maximizing the success probability of the system with the constrained amount of the catalyst. You have to formulate a Dynamic Programming solution for the problem (use of memoization is NOT allowed).

You are given N reactions, numbered from 1 to N, all of which must be completed for the successful completion of reactions of the system. The system has a total of C units of catalyst (C ≥ N) that can be used in different reactions. Let e(k,p) denote the probability of success of the reaction k if p units of catalyst are used in the reaction. It is given that e(k, 0) = 0 for all k, so at least one unit of catalyst must be used by each of the reaction. Also, for a reaction k, e(k, p) values are non-decreasing with increasing values of p (i.e., the chance of success never decreases if more units of catalyst are assigned to the reactions). You need to assign the C units of the catalyst to the N reactions so that the probability of success of the system is maximized.

You are required to design an efficient dynamic programming algorithm for the problem.

Part I

Write as comments at the very beginning in your program, the following clearly

<ol>
<li>The definition of the subproblem that you choose.</li>
<li>The recursive formulation used in the DP solution, including the base case. Write using notations as you have seen in text, do not write long sentences.</li>
</ol>
Partial marks will be awarded if you can figure out the recurrence.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Part II

Write a main() function to implement the dynamic programming. Read the input file as follows

1. The first line contains the number of reactions N (assume N &lt; 10)

2. Read in C (assume C &lt; 30. You can also assume C will be entered as ≥ N, no need to check).

3. Read in the e(k, p) values for each reaction exactly in this order in a 2-d array (enter the values in each row in non-decreasing order):

e(1, 1), e(1, 2), …., e(1, C )

e(2, 1), e(2, 2), …., e(2, C )

….

e(N, 1), e(N, 2), …., e(N, C)

Sample input file

File: input.txt

<pre>  3
  5
  0.1 0.3 0.5 0.6 0.6
  0.1 0.2 0.4 0.6 0.8
  0.2 0.4 0.4 0.7 0.9
</pre>
You have to print the followings exactly same as shown in the sample output file

<ol>
<li>The maximum probability of success, of the system.</li>
<li>The assignment of the catalyst in units to each of the reaction that gives the maximum success probability of the system.</li>
</ol>
Sample output file

File: output.txt

<pre>  0.012
  reaction 1 : 2
  reaction 2 : 2
  reaction 3 : 1
</pre>
Notes

<ol>
<li>There may be more than one assignment that gives the same maximum success probability; in such cases, you can print any one assignment that gives the maximum success probability.</li>
<li>You have to code directly in main(), no separate function is allowed to use.</li>
<li>You are not allowed to use Memoization</li>
<li>Make sure to read inputs from a file named “input.txt”. At the time of evaluation, the input data might be different from the one given here.</li>
<li>You need not to submit “output.txt”, but your code should write the output in the given format in a file named “output.txt”</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>

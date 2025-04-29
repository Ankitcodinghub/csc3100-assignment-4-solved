# csc3100-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [CSC3100 Assignment 4 Solved](https://www.ankitcodinghub.com/product/csc3100-programming-assignment-ii-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116266&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC3100 Assignment 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
1 Problem 1: Special Shortest Path

1.1 Statement

City C consists of n nodes, representing different places. There are m edges between these nodes. For the edge ei = (ui,vi,wi), there is a bidirectional(undirected) trail connecting ui and vi with length of wi.

For a path P = {pi}, consisting of edges p1,p2,p3,··· ,pk, the length of each edge is li = wpi. Normally, passing the edge pi with length li will cost li units of energy. Specially, if li = K · li−1, then passing this edge will only cost (K − 1) · li−1 units of energy.

Alice is starting from the node 1. Alice wants to know how many units of energy it will take at least to visit the node x, for any x. If x is unreachable from the start point(node 1), you should output −1 as the result.

1.2 Input Format

The first line consists of three integer numbers n,m,K. The following m lines each consists of three integer numbers u,v,w to describe a bidirectional trail.

1.3 Output Format

You need to output a line consisting of n integers, each representing the minimum units of energy to reach node i from node 1.

1.4 Example

1.5 Constraints

1 ∼ 3 30 pts n ≤ 105 m ≤ 2 × 105 K = 0

4 ∼ 5 20 pts n ≤ 103 m ≤ 2 × 105 K = 1

6 ∼ 7 20 pts n ≤ 105 m ≤ 2 × 105 K = 2

8 ∼ 10 30 pts n ≤ 105 m ≤ 2 × 105 K ≤ 105

1 ≤ wi ≤ 104

1.6 Hints

• Hint: You can modify(or add) some edges to the original graph to fit this problem into the algorithm you know.

2 Problem 2: Median Search Tree

2.1 Statement

If the sorted array of all the values in the set is , let t = ⌈n/2⌉, then the median 2k values are {at−k+1,··· ,at+k}.

Barbara has got a set of values with size of 2k initially. Barbara wants to do m operations on it. Each operation belongs to the following 3 types:

• 1 w: insert a value w.

• 2: output all the median 2k values, i.e. at−k+p,∀1 ≤ p ≤ 2k.

• 3 p: delete the p-th value among median 2k values, i.e. at−k+p.

We guarantee that all the values will be distinct and the size of the set is always at least 2k.

2.2 Input Format

The first line consists of two integer numbers m,k. The second line consists of the 2k values in the initial set. Then, the following m lines each consists of the command of an operation.

2.3 Output Format

You need to output one line for each query(operation 2). Each line consists of 2k positive integers, the median 2k values of the set at that time in ascending order.

2.4 Example

2.5 Constraints

1 ∼ 3 30 pts n ≤ × 103 k ≤ 25

4 ∼ 5 20 pts n ≤ 105 k ≤ 25 no operation 3

6 ∼ 7 20 pts n ≤ 105 k = 1

8 ∼ 10 30 pts n ≤ 105 k ≤ 25

1 ≤ w ≤ 106

3 Problem 3: Football Match

3.1 Statement

While the FIFA World Cup is being held in Qatar, BLGG is organizing a football tournament in LGU, too.

There are n teams in this tournament, numbered from 1 to n. Each team has its popularity, and the popularity of team i is ai. A match between i and j will gain ai × aj MOD M attractions.

When a football team loses a match, it will be eliminated from the tournament. At the end, the team left standing will be the champion of this tournament.

BLGG is wondering that what the maximum sum of the attractions of the (n − 1) matches.

3.2 Input Format

The first line contains two integers n and M.

The second line contains n integers a1,··· ,an.

3.3 Output Format

Output one integer representing the maximum sum of the attractions of the (n − 1) matches.

3.4 Sample Input/Output

3.5 Constraints

3.6 Hints

You can try to solve this problem using the graph algorithms we learn in classes.

4 Problem 4: Prefix

4.1 Statement

You are given n strings s1,s2,··· ,sn and q queries. In ith query, you are given a string ti, please find out how many strings in s1,s2,··· ,sn begins with ti.

4.2 Input Format

The first line is an integer n.

Each of the next n lines contains a string, respectively. The (i + 1)th line of input is si. The (n + 2)th line of input is an integer q.

Each of the next q lines contains a string, respectively. The (n + 2 + i)th line of input is ti.

4.3 Output Format

Output q lines. The ith line contains the answer of ith query.

4.4 Sample Input/Output

4.5 Constraints

All strings only contain lowercase letters.

Case Score Constraints

1 ∼ 4 40 pts n,q ≤ 103 Pni=1 |si|,Piq=1 |ti| ≤ 103

5 ∼ 10 60 pts n,q ≤ 106 Pni=1 |si|,Piq=1 |ti| ≤ 106

4.6 Hints

You can try to store s1,s2,··· ,sn in a tree.

Since the input might be very large, fast input method such as BufferedReader in Java is required.

A. Requirements

Code (90%)

The distribution of programming grade is 20%, 20%, 25%, 25% for the four problems respectively.

We provide a example problem to better illustrate the information above.

Report (10%)

You also need to write a report to explain the following:

• What are the possible solutions for the problem?

• How do you solve this problem?

• Why is your solution better than others?

Remember that the report is to illustrate your thinking process. Keep in mind that your report is supposed to show your ideas and thinking process. We expect clear and precise textual descriptions in your report, and we do not recommend that you over-format your report.

B. Example Problem: A + B Problem

Description

Given 2 integers A and B, compute and print A + B

Input

Two integers in one line: A, and B

Output

One integer: A + B

Sample Input I Sample Output I

1 2 3

Problem Scale &amp; Subtasks

For 100% of the test cases, 0 ≤ A,B ≤ 106

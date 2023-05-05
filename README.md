Download Link: https://assignmentchef.com/product/solved-cst370-homework-6
<br>
<h1>Problems</h1>

<table width="363">

 <tbody>

  <tr>

   <td width="300">1    Earthquake Recovery</td>

   <td width="63">10 points</td>

  </tr>

  <tr>

   <td width="300">2    Coin change</td>

   <td width="63">10 points</td>

  </tr>

  <tr>

   <td width="300">3    Leap Frog</td>

   <td width="63">10 points</td>

  </tr>

  <tr>

   <td width="300">4    Maximum Sub-Square</td>

   <td width="63">10 points</td>

  </tr>

  <tr>

   <td width="300">5    Climbing Stairs</td>

   <td width="63">10 points</td>

  </tr>

  <tr>

   <td width="300">6    Meeting Scheduling</td>

   <td width="63">10 points</td>

  </tr>

 </tbody>

</table>




<h1>1.       Earthquake Recovery (10 <sub>points)</sub></h1>

<a href="https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-earthquake"><strong>https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-earthquake</strong></a>

An Earthquake has knocked out a lot of roads in a county so citizens are cut off from essential resources. The county’s repair crews are working overtime to get everyone reconnected to the road network. You are given the towns and roads in the county, as well as the amount of time it will take to repair damaged roads. You wil find the minimum amount of time it will take to get everyone reconnected?

<h2>Input</h2>

<ul>

 <li>The first line will contain an integer <em>n</em>, the number of towns that are stranded.</li>

 <li>The next <em>n </em>lines will contain those towns.</li>

 <li>The next line will contain an integer <em>r</em>, the number of roads in need of repair.</li>

 <li>The next <em>r </em>lines will contain the roads in the format of comma-separated endpoints, followed by an integer, the amount of time required to repair it.</li>

</ul>

All towns must be reachable after repairing the roads. Any town that is not unconnected is a valid reconnection point. This input is very similar to the input for homework 5’s Essential Services problem. You can reuse your input handling code that problem on this problem.

<h2>Constraints</h2>

You can assume all the weights are positive (it takes time to repair a road) and that all towns have unique names.

<h2>Output</h2>

A single line containing an integer, the amount of time it will take to get everyone reconnected.

Sample Input 1                                                            Sample Output 1

<table width="622">

 <tbody>

  <tr>

   <td width="321">6Pacific GroveSalinasMontereySeaside Marina CSUMB9Pacific Grove, Monterey, 80Pacific Grove, Pebble Beach, 10 Pacific Grove, CSUMB, 20Monterey, Marina, 15Monterey, Salinas, 30Marina, Salinas, 45 Seaside, CSUMB, 25Seaside, Marina, 15CSUMB, Marina, 10</td>

   <td width="301">100</td>

  </tr>

 </tbody>

</table>

<h1>2.       Coin change (10 points)</h1>

You will be given the denominations of coins in a monetary system and a required sum. Your job is to find the number of ways you can make change for that sum assuming order of coins does not matter.

<h2>Submission</h2>

<ul>

 <li>Use this link to submit a <strong>iterative </strong>dynamic programming solution to this problem: <a href="https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-coinchange-iterative">https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-coinchange-iterative</a></li>

 <li>Use this link to submit a <strong>recursive </strong>dynamic programming solution to this problem: <a href="https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-coinchange-recursive">https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-coinchange-recursive</a></li>

</ul>

<h2>Input</h2>

<ul>

 <li>The first line will contain an integer, <em>n</em>, the required sum.</li>

 <li>The second line will contain an integer, <em>c</em>, the number of coins in the monetary system.</li>

 <li>The third and final line will contain <em>c </em>space-separated integers, the denominations of those coins.</li>

</ul>

<strong>Constraints</strong>

For simplicity, you can assume the required sum and all coin denominations are integers.

<h2>Output</h2>

The output will consist of a single line containing an integer, the number of ways to make the required sum.

Sample Input 1                                                          Sample Output 1

<table width="622">

 <tbody>

  <tr>

   <td width="311">25410 5 25 1</td>

   <td width="311">13</td>

  </tr>

  <tr>

   <td width="311">Sample Input 2</td>

   <td width="311">Sample Output 2</td>

  </tr>

  <tr>

   <td width="311">100410 5 25 1</td>

   <td width="311">242</td>

  </tr>

 </tbody>

</table>




This page is intentionally left blank.

<h1>3.       Leap Frog (10 points)</h1>

You will be given an array of integers representing the lily pads. Each integer indicats how many lily pads forward the frog can jump in a single leap from that lily pad. Find the minimum number of jumps the frog needs to reach shore (past the lily pads, i.e., the end of the array).

<h2>Submission</h2>

<ul>

 <li>Use this link to submit a <strong>iterative </strong>dynamic programming solution to this problem:</li>

</ul>

<a href="https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-leapfrog-iterative">https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-leapfrog-iterative</a>

<ul>

 <li>Use this link to submit a <strong>recursive </strong>dynamic programming solution to this problem:</li>

</ul>

<a href="https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-learfrog-recursive">https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-learfrog-recursive</a>

<h2>Input</h2>

<ul>

 <li>The first line will contain a single integer <em>n</em>, the number of lily pads.</li>

 <li>The second line contains <em>n </em>space-separated integers, the lily pads in order across the pond.</li>

</ul>

<h2>Constraints</h2>

You can assume the frog starts on lily pad 0 (the first in the array). You can also assume there are no negative numbers in the array.

<h2>Output</h2>

A single line consisting of either

<ul>

 <li>a single integer, the minimum number of jumps.</li>

 <li>−1 if the Frog can’t reach shore and should turn back.</li>

</ul>

Sample Input 1                   Sample Output 1

<table width="622">

 <tbody>

  <tr>

   <td width="311">111 3 5 8 9 2 6 7 6 8 9</td>

   <td width="311">3</td>

  </tr>

  <tr>

   <td width="311">Sample Input 2</td>

   <td width="311">Sample Output 2</td>

  </tr>

  <tr>

   <td width="311">61 0 10 5 11 3</td>

   <td width="311">-1</td>

  </tr>

 </tbody>

</table>

This page is intentionally left blank.

<h1>4.       Maximum Sub-Square (10 <sub>points)</sub></h1>

You will receive a square binary matrix representing unoccupied and occupied space in a park.

You are trying to install a square garden and would like it to be as large as possible. Find the dimension of the largest possible garden (i.e., the largest sub-square of just 0s, vacant space).

<h2>Submission</h2>

<ul>

 <li>Use this link to submit a <strong>iterative </strong>dynamic programming solution to this problem: <a href="https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-subsquares-iterative">https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-subsquares-iterative</a></li>

 <li>Use this link to submit a <strong>recursive </strong>dynamic programming solution to this problem: <a href="https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-subsquares-recursive">https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-subsquares-recursive</a></li>

</ul>

<h2>Input</h2>

<table width="622">

 <tbody>

  <tr>

   <td width="311">30      1 01      0 00 0 1</td>

   <td width="311">1</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>The first line will contain an integer, <em>n</em>, the dimension of the park.</li>

 <li>The next <em>n </em>lines will contain <em>n </em>space-separated bits (0 or 1), indicating whether that part of the park is vacant or occupied.</li>

</ul>

<strong>Constraints</strong>

You can assume <em>n </em>is positive.

<h2>Output</h2>

A single line containing an integer, the maximum dimension for the garden.

Sample Input 1                   Sample Output 1

<table width="622">

 <tbody>

  <tr>

   <td width="311">40      1 0 01      0 0 00 0 0 00 0 1 0</td>

   <td width="311">2</td>

  </tr>

 </tbody>

</table>

Sample Input 2                   Sample Output 2

This page is intentionally left blank.

<h1>5.       Climbing Stairs (10 points)</h1>

You have to climb a special staircase. It costs money to stand on each step so you want to minimize the cost incurred by climbing the stairs. You are given an array of integers representing the cost to stand on the <em>i<sup>th </sup></em>step where <em>i </em>is the index. You may start on either step 0 or 1 and you can go up 1 or 2 steps each time. You must end on the last step.

<h2>Submission</h2>

<ul>

 <li>Use this link to submit a <strong>iterative </strong>dynamic programming solution to this problem:</li>

</ul>

<a href="https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-stairs-iterative">https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-stairs-iterative</a>

<ul>

 <li>Use this link to submit a <strong>recursive </strong>dynamic programming solution to this problem:</li>

</ul>

<a href="https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-stairs-recursive">https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-stairs-recursive</a>

<h2>Input</h2>

<ul>

 <li>The first line will contain an integer <em>n</em>, the number of steps.</li>

 <li>The second and final line will contain <em>n </em>space-separated integers, the cost of stepping on each step.</li>

</ul>

<strong>Constraints</strong>

You can assume the cost of a step is non-negative.

<h2>Output</h2>

The output will consist of a single integer, <em>n</em>, the cheapest cost you can climb the stairs for.

Sample Input 1                   Sample Output 1

<table width="622">

 <tbody>

  <tr>

   <td width="311">57 10 15 3 11</td>

   <td width="311">24</td>

  </tr>

  <tr>

   <td width="311">Sample Input 2</td>

   <td width="311">Sample Output 2</td>

  </tr>

  <tr>

   <td width="311">1211 9 2 4 15 19 3 25 18 8 0 1</td>

   <td width="311">48</td>

  </tr>

 </tbody>

</table>

This page is intentionally left blank.

<h1>6.       Meeting Scheduling (10 <sub>points)</sub></h1>

My company is perptually short on meeting rooms. A number of meetings have been scheduled for the same room but unfortunately they overlap in time so not all of them can occur. Each meeting has a start and end time and a priority (importance). Find the maximum cumulative priority we can accomplish with non-overlapping meetings.

<h2>Submission</h2>

<ul>

 <li>Use this link to submit a <strong>iterative </strong>dynamic programming solution to this problem:</li>

</ul>

<a href="https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-meetings-iterative">https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-meetings-iterative</a>

<ul>

 <li>Use this link to submit a <strong>recursive </strong>dynamic programming solution to this problem: <a href="https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-meetings-recursive">https://www.hackerrank.com/contests/cst370-s19-hw6/challenges/hw6-meetings-recursive</a></li>

</ul>

<h2>Input</h2>

<ul>

 <li>The first line of the input will be an integer, <em>n</em>, the number of meetings.</li>

 <li>The next <em>n </em>lines will consist of three space separated integers: the start time, the end time, and the priority, in that order.</li>

</ul>

<strong>Constraints</strong>

You can assume all the priorties are positive.

<h2>Output</h2>

The output will consist of a single line containing an integer, the maximum cumulative priority we can get scheduled.

Sample Input 1                   Sample Output 1

<table width="622">

 <tbody>

  <tr>

   <td width="311">78 9 511 13 410       13 211       15 615 16 813 14 38 11 7</td>

   <td width="311">22</td>

  </tr>

 </tbody>

</table>

This page is intentionally left blank.
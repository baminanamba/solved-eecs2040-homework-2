Download Link: https://assignmentchef.com/product/solved-eecs2040-homework-2
<br>
<strong>Part 1 </strong>

<ol>

 <li> A linear list is being maintained circularly in an array with front and rear set up as for circular queues.

  <ul>

   <li>Obtain a formula in terms of the array capacity, front, and rear, for the number of elements in the list.</li>

   <li>Assume the kth element in the list is to be deleted, the elements after it should be moved up one position. Give a formula describing the positions of those elements to be moved up one position, i.e., from ??? to ???.</li>

   <li>Assume that we want to insert an element y immediately after the kth element and array doubling is needed (as <strong>Program 3.11</strong> shows or pptx page 83 <strong>void</strong> <strong>Queue&lt;T&gt;::</strong>Push(<strong>const</strong> <strong>T&amp; </strong>x) shows), please explain the code using a graphical illustration and explanation.</li>

  </ul></li>

</ol>




<ol start="2">

 <li>Using the operator priorities of Figure 3.15 (or pptx page 130 <strong>Parentheses Handling) </strong>together with those for ‘(‘ and ‘#’ to answer the following:

  <ul>

   <li>In function Postfix (Program 3.19, pptx <strong>Infix to Postfix Algorithm</strong>), what is the maximum number of elements that can be on the stack at any time if the input expression has n operators and delimiters?</li>

   <li>What is the answer to (a) if the input expression e has n operators and the depth of nesting of parentheses is at most 6?</li>

  </ul></li>

</ol>




<ol start="3">

 <li> Write the postfix form and prefix form of the following infix expressions:

  <ul>

   <li>–A + B – C + D</li>

   <li>A * -B + C</li>

   <li>(A + B) * D + E / (F + A * D) + C (d) A &amp;&amp; B || C || !(E &gt; F)</li>

  </ul></li>

</ol>

(e) !(A &amp;&amp; !((B &lt; C) || (C &gt; D))) || (C &lt; E)




<strong>Part 2 Coding </strong>You should submit:

<ul>

 <li>All your source codes (C++ file).</li>

 <li>Show the execution trace of your program.</li>

</ul>




<ol>

 <li>(30%) Based on the circular queue and template queue ADT in <strong>ADT 3.2</strong> in textbook (or pptx pp.79), write a C++ program to implement the queue ADT<strong>. </strong></li>

</ol>

Then add two more functions to

<ul>

 <li>Return the size and capacity of a queue.</li>

 <li>Merge two queues into a one by alternately taking elements from each queue. Te relative order of queue elements is unchanged. What is the complexity of your function?</li>

</ul>

You should <strong>demonstrate all the functions</strong> using at least one example.




<ol start="2">

 <li>(35%) Referring to <strong>Program 3.13</strong> in textbook (pptx pp.94),

  <ul>

   <li>Implement Stack as a publicly derived class of Bag using template. <strong>Demonstrate</strong> your C++ code using at least two element types (e.g., int, float,…). <strong>Show results</strong> of a series of Pushes and Pops and Size functions.</li>

   <li>Implement Queue as a publicly derived class of Bag using template. <strong>Demonstrate</strong> your C++ code using at least two element types (e.g., int, float,…). <strong>Show results</strong> of a series of Pushes and Pops and Size functions.</li>

   <li>A template double-ended queue (deque) is a linear list in which additions and deletions may be made at either end. Implement the class Deque as a publicly derived templated class of Queue. The class Deque must have public functions (either via inheritance from Queue or by direct implementation in Deque) to add and delete elements from either end of the deque and also to return an element from either end. The complexity of each function (excluding array doubling) should be Θ(1).</li>

  </ul></li>

</ol>

<strong>Demonstrate</strong> your C++ code using at least two element types (e.g., int, float,…). <strong>Show results</strong> of a series of two types of Pushes and Pops and Size functions to illustrate your code is working.




<ol start="3">

 <li>(35%) Write a C++ program to implement the maze in textbook using the example codes of <strong>Program 3.15</strong> (pptx pp.106 Algorithm()) and <strong>16 (pptx void Path(const int m, const int p)</strong>. You should use a text editor to edit a file containing the maze matrix and then read in the file to establish the maze matrix in your program. The default entrance and exit are located in the upper left corner and lower right corner, respectively as shown in textbook.

  <ul>

   <li>Demonstrate your maze program using the maze shown in <strong>Figure 3.11</strong> in textbook.</li>

   <li>Find a path through the maze shown <strong>Figure 3.14</strong> in textbook.</li>

   <li>Trace out the action of function path (<strong>Program 3.16</strong>) on the maze shown.</li>

  </ul></li>

</ol>

Compare this to your own attempt in (b).




<strong>Figure 3.11</strong><strong>：</strong>一個迷宮的例子（你能找出一條路徑嗎？）




<table>

 <tbody>

  <tr>

   <td width="120"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<strong>Figure 3.14</strong><strong>：</strong>唯一路徑的迷宮圖



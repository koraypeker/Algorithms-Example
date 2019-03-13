<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><h1 id="algorithms--square-root-operation">Algorithms : Square Root Operation</h1>
<h2 id="goal">Goal</h2>
<p>Write a function solution that, given two integers A and B, returns the maximum number of repeated square root operations that can be performed using the numbers from the interval [A…B] <strong>(both end included)</strong> as starting points. Square root operations can be performed as long as the result is still an integer.</p>
<h1 id="test-cases">Test Cases</h1>
<h2 id="case-1-">Case 1 :</h2>
<p>A = 10 and B = 20, the function should return <strong>2</strong>.<br>
Starting with the integer 16, two square root operations can be performed <code>sqrt(16)=4</code> and then <code>sqrt(4)=2</code> .</p>
<h2 id="case--2-">Case  2 :</h2>
<p>A = 6000 and B = 7000, the function should return <strong>3</strong>.<br>
Starting with integer 6561, three square root operations can be performed <code>sqrt(6561)=81</code> , <code>sqrt(81)=9</code> and <code>sqrt(9)=3</code>.</p>
<h1 id="task">Task</h1>
<p>Write an efficient algorithm.</p>
</div>
</body>

</html>

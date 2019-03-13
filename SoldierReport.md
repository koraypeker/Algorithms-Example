<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><h1 id="algorithms--soldier-report">Algorithms : Soldier Report</h1>
<h2 id="goal">Goal</h2>
<p>In the army, each soldier has an assigned rank. A soldier of rank X has to report to (any) soldier of rank X + 1. Many soldiers can report to the same superior. Given an array ranks consisting of soldiers ranks, returns the number of soldiers who can report to some superior.</p>
<h1 id="test-cases">Test Cases</h1>
<h2 id="case-1">Case 1</h2>
<p>Given <code>ranks[3,4,3,0,2,2,3,0,0]</code>, your function should return 5, because</p>
<ul>
<li>Three soldiers of rank 3 (ranks[0], ranks[2], ranks[6]) may report to a soldier of rank 4 (ranks[1])</li>
<li>Two soldiers of rank 2 may report to any soldier of rank 3</li>
</ul>
<h2 id="case-2">Case 2</h2>
<p>Given <code>ranks[4,2,0]</code>, your function should return 0.</p>
<h2 id="case-3">Case 3</h2>
<p>Given <code>ranks[4,4,3,3,1,0]</code>, your function should return 3, because</p>
<ul>
<li>A soldier of rank 0 can report to a soldier of rank 1</li>
<li>Two soldiers of rank 3 can report to any soldier of rank 4</li>
</ul>
<h1 id="task">Task</h1>
<p>Write an efficient algorithm.</p>
</div>
</body>

</html>

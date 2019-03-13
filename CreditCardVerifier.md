<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><h1 id="algorithms--credit-card-verifier">Algorithms : Credit Card Verifier</h1>
<h2 id="goal">Goal</h2>
<p>Most payment card numbers are <strong>16 digits</strong> long. <strong>The leftmost 6 digits</strong> represent a unique identification number for the bank who has issued the card. <strong>The next 2 digits</strong> determine the type of the card (e.g., debit, credit, gift). <strong>Digits 9 to 15</strong> are the serial number of the card, and the last digit is used as a control digit to verify whether the card number is valid.</p>
<p>Hence, if somebody enters the card number incorrectly, there is a high chance that a payment software can easily determine it.</p>
<h2 id="algorithm">Algorithm</h2>
<ol>
<li>Double every second digit from right to left. If this “doubling” results in a two-digit number, subtract 9 from it get a single digit.</li>
<li>Now add all single digit numbers from step 1.</li>
<li>Add all digits in the odd places from right to left in the credit card number.</li>
<li>Sum the results from steps 2 &amp; 3.</li>
<li>If the result from step 4 is divisible by 10, the card number is valid; otherwise, it is invalid.</li>
</ol>
<h2 id="test-cases">Test Cases</h2>
<p><strong>CASE 1 :</strong></p>
<p>Credit Card Number : <code>4556 7375 8689 9855</code></p>
<ol>
<li></li>
</ol>
<p>5*2 9*2 8*2 8*2 7*2 7*2 5*2 4*2</p>
<p>10 18 16 16 14 14 10 8</p>
<p>1 9 7 7 5 5 1 8</p>
<ol start="2">
<li></li>
</ol>
<p>1+9+7+7+5+5+1+8=43</p>
<ol start="3">
<li></li>
</ol>
<p>5+8+9+6+5+3+6+5=47</p>
<ol start="4">
<li></li>
</ol>
<p>43+47=90</p>
<p>The number is valid</p>
<p><strong>CASE 2 :</strong></p>
<p>Credit Card Number : <code>4024 0071 0902 2143</code></p>
<ol>
<li></li>
</ol>
<p>4*2 2*2 0*2 0*2 7*2 0*2 2*2 4*2</p>
<p>8 4 0 0 14 0 4 8</p>
<p>8 4 0 0 5 0 4 8</p>
<ol start="2">
<li></li>
</ol>
<p>8+4+0+0+5+0+4+8=29</p>
<ol start="3">
<li></li>
</ol>
<p>3+1+2+9+1+0+4+0=20</p>
<ol start="4">
<li></li>
</ol>
<p>20+29=49</p>
<p>Therefore the number not valid.</p>
<h2 id="task">Task</h2>
<p>Your task is to read several card numbers from the input, and determine whether each one is a valid card number or not.</p>
</div>
</body>

</html>

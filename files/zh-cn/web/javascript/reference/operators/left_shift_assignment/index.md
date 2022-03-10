---
title: Left shift assignment (<<=)
slug: Web/JavaScript/Reference/Operators/Left_shift_assignment
translation_of: Web/JavaScript/Reference/Operators/Left_shift_assignment
---
<div>{{jsSidebar("Operators")}}</div>

<p>The left shift assignment operator (<code>&lt;&lt;=</code>) moves the specified amount of bits to the left and assigns the result to the variable.</p>

<div>{{EmbedInteractiveExample("pages/js/expressions-left-shift-assignment.html")}}</div>





<h2 id="语法">语法</h2>

<pre class="syntaxbox"><strong>Operator:</strong> x &lt;&lt;= y
<strong>Meaning:</strong>  x   = x &lt;&lt; y</pre>

<h2 id="Examples">Examples</h2>

<h3 id="Using_left_shift_assignment">Using left shift assignment</h3>

<pre class="brush: js">let a = 5;
// 00000000000000000000000000000101

a &lt;&lt;= 2; // 20
// 00000000000000000000000000010100</pre>

<h2 id="Specifications">Specifications</h2>

<table class="standard-table">
 <tbody>
  <tr>
   <th scope="col">Specification</th>
  </tr>
  <tr>
   <td>{{SpecName('ESDraft', '#sec-assignment-operators', 'Assignment operators')}}</td>
  </tr>
 </tbody>
</table>

<h2 id="Browser_compatibility">Browser compatibility</h2>



<p>{{Compat("javascript.operators.left_shift_assignment")}}</p>

<h2 id="See_also">See also</h2>

<ul>
 <li><a href="/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#Assignment">Assignment operators in the JS guide</a></li>
 <li><a href="/en-US/docs/Web/JavaScript/Reference/Operators/Left_shift">Left shift operator</a></li>
</ul>
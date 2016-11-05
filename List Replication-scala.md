<p>Given a list, repeat each element in the list&nbsp;&nbsp;amount of times. The input and output portions will be handled automatically by the grader. You need to write a function with the recommended method signature.</p>

<p><strong>Input Format</strong></p>

<p>The first line contains the integer&nbsp;&nbsp;where&nbsp;&nbsp;is the number of times you need to repeat the elements.&nbsp;<br />
The next&nbsp;&nbsp;lines each contain an integer. These are the&nbsp;&nbsp;elements in the array.</p>

<p><strong>Output Format</strong></p>

<p>Output each element of the original list&nbsp;&nbsp;times, each on a separate line. You have to return the list/vector/array of&nbsp;&nbsp;integers. The relative positions of the values should be the same as the original list provided in the input.</p>

<p><strong>Constraints</strong></p>

<p>&nbsp;</p>

<p><strong>Sample Input</strong></p>

<pre>
<code>3
1
2
3
4
</code></pre>

<p><strong>Sample Output</strong></p>

<pre>
<code>1
1
1
2
2
2
3
3
3
4
4
4
</code></pre>

<p><strong>Recommended Method Signature</strong></p>

<pre>
<code>Number Of Parameters: 2
Parameters: [number of times to replicate elements, list]
Returns: List or Vector
</code></pre>

<p><strong>For Hackers Using Clojure</strong></p>

<p>This will be the outline of your function body (fill in the blank portion marked by underscores):</p>

<pre>
<code> (fn[num lst]___________________________)
</code></pre>

<p><strong>For Hackers Using Scala</strong></p>

<p>This will be the outline of your function body (fill in the blank portion marked by underscores):</p>

<pre>
<code> def f(num:Int,arr:List[Int]):List[Int] = __________________
</code></pre>

<p><strong>For Hackers Using Haskell</strong></p>

<p>This will be the outline of your function body (fill in the blank portion marked by underscores):</p>

<pre>
<code> f n arr = ___________________
</code></pre>

<p><strong>For Hackers Using OCaml</strong></p>

<p>This will be the outline of your function body (fill in the blank portion marked by underscores):</p>

<pre>
<code> let f n arr = (*Complete this function*)
</code></pre>

<p><strong>For Hackers Using other Languages</strong></p>

<p>You have to read input from standard input and write output to standard output. Please follow the input/output format mentioned above.</p>

<p><strong>NOTE</strong>: You only need to submit the code above after filling in the blanks appropriately. The input and output section will be handled by us. The focus is on writing the correct function.</p>

<h1>SOLUTIONS</h1>

<p>def f(num:Int,arr:List[Int]):List[Int] = {<br />
&nbsp; &nbsp;var res = List[Int]()<br />
&nbsp; &nbsp; for(i &lt;- arr){<br />
&nbsp; &nbsp; &nbsp; &nbsp; res = res:::List.fill(num)(i)<br />
&nbsp; &nbsp;&nbsp;<br />
}<br />
&nbsp; &nbsp; res<br />
}</p>

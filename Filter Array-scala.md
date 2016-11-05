<p>Filter a given array of integers and output only those values that are less than a specified value&nbsp;. The output integers should be in the same sequence as they were in the input. You need to write a function with the recommended method signature for the languages mentioned below. For the rest of the languages, you have to write a complete code.</p>

<p><strong>Input Format</strong></p>

<p>The first line contains the delimiter&nbsp;.&nbsp;<br />
The next&nbsp;&nbsp;lines each contain an integer, which represents the elements of the list/array. You have to read the input to the&nbsp;<em>End-Of-File</em>.</p>

<p><strong>Output Format</strong></p>

<p>Print all the integers from the array that are less than the given upper limit&nbsp;&nbsp;in value on separate lines. The sequence should be the same as it was in the original array.</p>

<p><strong>Constraints</strong></p>

<p>&nbsp;<br />
For any element,&nbsp;&nbsp;in the array,&nbsp;&nbsp;</p>

<p><strong>Note</strong></p>

<p>The purpose of this challenge is to learn how to write your own implementation of a&nbsp;<em>filter</em>&nbsp;function. We recommend not using the inbuilt library function.</p>

<p><strong>Sample Input</strong></p>

<pre>
<code>3
10
9
8
2
7
5
1
3
0
</code></pre>

<p><strong>Sample Output</strong></p>

<pre>
<code>2
1
0
</code></pre>

<p><strong>Explanation</strong></p>

<p>&nbsp;and&nbsp;&nbsp;are the list elements that are less than the&nbsp;&nbsp;delimiter,&nbsp;. They are displayed in the same order as they were in the original list.</p>

<p><strong>Recommended Method Signature</strong></p>

<pre>
<code>Number Of Parameters: 2
Parameters: [upper-limit(X) list]
Returns: List or Vector
</code></pre>

<p><strong>For Hackers Using Clojure</strong></p>

<p>This will be the outline of your function body (fill in the blank portion marked by underscores):</p>

<pre>
<code> (fn[delim lst]___________________________)
</code></pre>

<p><strong>For Hackers Using Scala</strong></p>

<p>This will be the outline of your function body (fill in the blank portion marked by underscores):</p>

<pre>
<code> def f(delim:Int,arr:List[Int]):List[Int] = __________________
</code></pre>

<p><strong>For Hackers Using Haskell</strong></p>

<p>This will be the outline of your function body (fill in the blank portion marked by underscores):</p>

<pre>
<code>f n arr = _____________________
</code></pre>

<p><strong>For Hackers Using other Languages</strong></p>

<p>You have to read input from standard input and write output to standard output. Please follow the input/output format mentioned above.</p>

<p><strong>NOTE</strong>: You only need to submit the code above after filling in the blanks appropriately. The input and output section will be handled by us. The focus is on writing the correct function.</p>

<h1>SOLUTIONS</h1>

<p>&nbsp;def f(delim:Int,arr:List[Int]):List[Int] = arr.filter(x =&gt; x&lt;delim)</p>

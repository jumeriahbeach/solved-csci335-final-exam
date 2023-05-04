Download Link: https://assignmentchef.com/product/solved-csci335-final-exam
<br>
<h1>Programming Q1:  – Longest Common Subsequence</h1>

<strong>Attachments provided: subsequence.cc </strong>

<strong>Subsequences</strong> are sequences within a string that appear in the same relative order but are not necessarily contiguous. For example, if given a string “123456”, then some potential subsequences are, “123”, “12”, “456”, “14”, “236”, “46”, etc.

<strong><em>The longest common subsequence problem is as follows:  </em></strong>

Given two sequences <strong>A= a<sub>1</sub>,a<sub>2</sub>,…a<sub>m</sub></strong>  and  <strong>B= b<sub>1</sub>,b<sub>2</sub>,…b<sub>N</sub></strong>  find the length, <strong>k</strong>, of the longest subsequence <strong>C= c<sub>1</sub>,c<sub>2</sub>,…c<sub>m</sub></strong>  such that <strong>C</strong> is a subsequence (not necessarily contiguous) of both <strong>A</strong> and <strong>B.</strong>

Example 1: If<strong>  </strong><strong>A = dynamic</strong> and<strong>  </strong><strong>B = programming</strong>  then the longest common subsequence is <strong>ami</strong> and has a length of <strong>3</strong>.

Example 2: If  <strong>A = apples</strong>   and  <strong>B = oranges</strong>  then the longest common subsequence is  <strong>aes</strong> and has a length of <strong>3</strong>.

<strong>Write an algorithm to solve the longest common subsequence problem in O(MN) time. </strong>

Your program should take two arguments, word_a and word_b.

Given a call, <strong>./subsequence &lt;word_a&gt; &lt;word_b&gt;</strong>, your program should output in the following format.

&lt;length_of_longest_subsequence&gt;

&lt;longest_subsequence&gt;




Example: Given, <strong>./subsequence apples oranges </strong>your program should return:

3 aes

<strong> </strong>

<strong><u>Q1 Deliverables:</u></strong>

<ul>

 <li>cc (modified) o subsequence_driver()</li>

 <li>README file (one comprehensive README about all Q’s)</li>

</ul>




<h1>Programming Q2: – Optimal Matrix Multiplication</h1>

<strong>Attachments provided:  optimal_multiplications.cc, optimal_ordering.cc, dimension_file.txt, dimension_file2.txt </strong>

Given the sizes of several matrices, calculate the optimal multiplication ordering using dynamic programming. The sizes will be presented in a file containing dimensions in a sequence: For example, dimensions_file.txt can be

50

10

40

30

5

That means that c0 = 50, c1 = 10, c2 = 40, c3 = 30, and c4 = 5. Therefore. the matrices to be multiplied have sizes:




Matrix 1: 50 x 10

Matrix 2: 10 x 40

Matrix 3: 40 x 30

Matrix 4: 30 x 5




Obviously when the dimensions_file.txt contains N numbers, then the matrices to be multiplied are N – 1.

Write a program that runs as follows:

<strong>./optimal_multiplications &lt;dimensions_file&gt; </strong>

The program should produce the optimal number of multiplications.

<strong>./optimal_multiplications dimensions_file.txt, </strong>should output a single number.

<strong> </strong>

10500

<strong> </strong>

<strong><em>Note: This output is not necessarily representative of any particular input. </em></strong>

<strong><em> </em></strong>

<strong><em> </em></strong>

<strong><em><u>Q2 deliverables:</u></em></strong>

<strong><em> </em></strong>

<ul>

 <li>cc (modified) o multiplication_driver()</li>

 <li>README file. (one comprehensive README about all Q’s)</li>

</ul>




<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<h1>Programming Q2 Extra Credit (– Optimal Matrix Multiplication Ordering</h1>

<strong> </strong>

For 10 points of extra credit, submit <strong>optimal_ordering.cc</strong>, that upon the input:

<strong>./optimal_ordering &lt;dimensions_filename&gt; </strong>outputs the correct optimal matrix multiplication order.




You should use parentheses, and the matrices should be named A through Z, in order, left to right. You can and should use your work in Q2.

<strong> </strong>

<strong>For example: </strong>

<strong> </strong>

<strong>./optimal_ordering dimensions_file.txt   </strong>should print:

<strong> </strong>

(A(B(CD)))




<strong><em>Note: This output is not necessarily representative of any particular file. </em></strong>

<strong><em> </em></strong>

More potential output examples: (not necessarily representative of any files)




((AB)((CD)E))

((A(BC))D)




Your output should be of this form, with parentheses surrounding every grouping, including the outermost. You can assume that there will not be more than 26 matrices in a given dimensions file.




Please make sure that all functionality is called from the function <strong>ordering_driver().</strong>

<strong> </strong>

<strong><u>Q2 EC deliverables</u></strong>

<strong> </strong>

<ul>

 <li>cc (modified) o ordering_driver()</li>

 <li>Readme file. (one comprehensive README about all Q’s)</li>

</ul>







<strong> </strong>



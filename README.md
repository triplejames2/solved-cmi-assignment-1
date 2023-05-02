Download Link: https://assignmentchef.com/product/solved-cmi-assignment-1
<br>
Create an ARMv8 A64 assembly language program that finds the maximum of  <em>y</em> = -2<em>x</em><sup>3</sup> – 22<em>x</em><sup>2</sup> + 11<em>x</em> + 57 in the range -10 £ <em>x</em> £ 4, by stepping through the range one by one in a loop and testing. Use only long integers for <em>x</em>, and do not factor the expression. Use the printf() function to display to the screen the values of <em>x</em>, <em>y</em> and the current <em>maximum</em> on each iteration of your loop.

You are to create 2 versions of your program:

<ol>

 <li>Write the program without macros (i.e. don’t use <em>m4</em>), and use only the <em>mul</em>, <em>add</em>, and <em>mov</em> instructions to do your calculations. Use a pre-test loop, where the test is at the top of the loop.</li>

 <li>Optimize the above program by putting the loop test at the bottom of the loop (make sure it is still a pre-test loop), and by making use of the <em>madd</em> Also, add macros to the above program to make it more readable (use <em>m4</em>). In particular, provide macros for heavily used registers.</li>

</ol>




<strong>Running Your Program</strong>




To verify that your assembly language program works, run both versions under <em>gdb</em>, capturing output from each session using the <em>script </em>UNIX command. For version 1, single step through the program (use ni) for at least one iteration of your loop, displaying the instruction being executed (use display/i $pc). Also print out the contents of particular registers (use p) at key points in your program to show that it is working as expected. For version 2, set a breakpoint just after the place where the final result is calculated, and then print out the <em>maximum</em>. Do not single step through this version.




<strong>Other Requirements</strong>




Make sure your code is properly formatted into columns, is readable and fully documented, and includes identifying information at the top of each file. You must comment each line of assembly code. Your code should also be well designed: make sure it is well organized, clear, and concise.




<strong>New Skills Needed for this Assignment:</strong>




<ul>

 <li>Ability to work with basic arithmetic, loops, and if-else constructs in assembly</li>

 <li>Ability to print to standard output using the printf() function</li>

 <li>Ability to optimize assembly code by rearranging loops and using alternate instructions</li>

 <li>Ability to use macros in assembly code</li>

 <li>Ability to assemble programs using <em>gcc </em>and use <em>m4</em> to process macros</li>

 <li>Ability to use <em>gdb</em> to debug and display assembly language programs</li>

</ul>



# Cycle Detection
<div class="challenge_problem_statement"><div class="msB challenge_problem_statement_body"><div class="hackdown-content"><p>A linked list is said to contain a <em>cycle</em> if any node is visited more than once while traversing the list.  Given a pointer to the head of a linked list, determine if it contains a cycle.  If it does, return <span style="font-size: 100%; display: inline-block;" class="MathJax_SVG" id="MathJax-Element-1-Frame"><img src="./assets/svg-0.svg" /></span>.  Otherwise, return <span style="font-size: 100%; display: inline-block;" class="MathJax_SVG" id="MathJax-Element-2-Frame"><img src="./assets/svg-1.svg" /></span>.  </p>

<p><strong>Example</strong>  </p>

<p><span style="font-size: 100%; display: inline-block;" class="MathJax_SVG" id="MathJax-Element-3-Frame"><img src="./assets/svg-2.svg" /></span> refers to the list of nodes <span style="font-size: 100%; display: inline-block;" class="MathJax_SVG" id="MathJax-Element-4-Frame"><img src="./assets/svg-3.svg" /></span>  </p>

<p>The numbers shown are the node numbers, not their data values.  There is no cycle in this list so return <span style="font-size: 100%; display: inline-block;" class="MathJax_SVG" id="MathJax-Element-5-Frame"><img src="./assets/svg-4.svg" /></span>.  </p>

<p><span style="font-size: 100%; display: inline-block;" class="MathJax_SVG" id="MathJax-Element-6-Frame"><img src="./assets/svg-5.svg" /></span> refers to the list of nodes <span style="font-size: 100%; display: inline-block;" class="MathJax_SVG" id="MathJax-Element-7-Frame"><img src="./assets/svg-6.svg" /></span>  </p>

<p>There is a cycle where node 3 points back to node 1, so return <span style="font-size: 100%; display: inline-block;" class="MathJax_SVG" id="MathJax-Element-8-Frame"><img src="./assets/svg-7.svg" /></span>.  </p>

<p><strong>Function Description</strong>  </p>

<p>Complete the <em>has_cycle</em> function in the editor below.  </p>

<p>It has the following parameter:  </p>

<ul>
<li><em>SinglyLinkedListNode pointer head:</em>  a reference to the head of the list  </li>
</ul>

<p><strong>Returns</strong>  </p>

<ul>
<li><em>int:</em>  <span style="font-size: 100%; display: inline-block;" class="MathJax_SVG" id="MathJax-Element-9-Frame"><img src="./assets/svg-8.svg" /></span> if there is a cycle or <span style="font-size: 100%; display: inline-block;" class="MathJax_SVG" id="MathJax-Element-10-Frame"><img src="./assets/svg-9.svg" /></span> if there is not  </li>
</ul>

<p><strong>Note:</strong> If the list is empty, <span style="font-size: 100%; display: inline-block;" class="MathJax_SVG" id="MathJax-Element-11-Frame"><img src="./assets/svg-10.svg" /></span> will be <em>null</em>.</p></div></div></div><div class="challenge_input_format"><div class="msB challenge_input_format_title"><p><strong>Input Format</strong></p></div><div class="msB challenge_input_format_body"><div class="hackdown-content"><p>The code stub reads from stdin and passes the appropriate argument to your function. The custom test cases format will not be described for this question due to its complexity.  Expand the section for the main function and review the code if you would like to figure out how to create a custom case.  </p></div></div></div><div class="challenge_constraints"><div class="msB challenge_constraints_title"><p><strong>Constraints</strong></p></div><div class="msB challenge_constraints_body"><div class="hackdown-content"><ul>
<li><span style="font-size: 100%; display: inline-block;" class="MathJax_SVG" id="MathJax-Element-1-Frame"><img src="./assets/svg-11.svg" /></span></li>
</ul></div></div></div><div class="challenge_sample_input"><div class="msB challenge_sample_input_title"><p><strong>Sample Input</strong></p></div><div class="msB challenge_sample_input_body"><div class="hackdown-content"><p>References to each of the following linked lists are passed as arguments to your function:  </p>

<p><img src="https://s3.amazonaws.com/hr-challenge-images/1163/1463778594-900a0ae522-inputs.png" alt="Sample Inputs" title="">    </p></div></div></div><div class="challenge_sample_output"><div class="msB challenge_sample_output_title"><p><strong>Sample Output</strong></p></div><div class="msB challenge_sample_output_body"><div class="hackdown-content"><pre><code>0
1
</code></pre></div></div></div><div class="challenge_explanation"><div class="msB challenge_explanation_title"><p><strong>Explanation</strong></p></div><div class="msB challenge_explanation_body"><div class="hackdown-content"><ol>
<li>The first list has no cycle, so return <span style="font-size: 100%; display: inline-block;" class="MathJax_SVG" id="MathJax-Element-1-Frame"><img src="./assets/svg-12.svg" /></span>.  </li>
<li>The second list has a cycle, so return <span style="font-size: 100%; display: inline-block;" class="MathJax_SVG" id="MathJax-Element-2-Frame"><img src="./assets/svg-13.svg" /></span>.</li>
</ol></div></div></div>
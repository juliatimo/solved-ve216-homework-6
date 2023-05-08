Download Link: https://assignmentchef.com/product/solved-ve216-homework-6
<br>
<strong>Problems:</strong>

<ol>

 <li>[5] Is this system stable? Explain. (Note: the system is causal.)</li>

 <li>[5] How many signals have a Laplace transform that may be experessed as</li>

</ol>

in its region of convergence?

<ol start="3">

 <li>[5] Use geometric evaluation from the pole-zero plot to determine the magnitude of the Fourier transform of the signal whose Laplace transform is specified as</li>

 <li>[5] Consider two right-sided signals x(t) and y(t) related through the differential equations</li>

</ol>

and

Determine Y(S) and X(S), along with their regions of convergence.

<ol start="5">

 <li>[10] A causal LTI system S with impluse response h(t) has its input x(t) and output y(t) related through a linear constant-coefficient differential equation of the form

  <ul>

   <li>If</li>

  </ul></li>

</ol>

,

how many poles does G(s) have?

<ul>

 <li>For what real values of the parameter <em>α </em>is S guaranteed to be stable?</li>

</ul>

<ol start="6">

 <li>[10] Draw a direct-form representation for the causal LTI systems with the following system fuctions:

  <ul>

   <li>(b)</li>

  </ul></li>

</ol>

(c)

<ol start="7">

 <li>[10] A causal LTI system with impulse response h(t) has the following properties:1.When the input to the system is <em>x</em>(<em>t</em>) = <em>e</em><sup>2<em>t </em></sup>for all t, the output is for all t. 2.The impulse respose h(t) satisfies the differential equation ), where b is an unkhown constant.</li>

</ol>

Determine the system function H(s) of the system, consistent with information above. There should be no unkhowm constants in your answer, that is, the constant b should not appear in the answer.

<ol start="8">

 <li>[10] A unit step signal is applied to a system consisting of two LTI system connected in parallel. The pole-zero plots of each of the system are shown below. Determine the output signal. Assume that each of the system has unit gain at DC.</li>

</ol>

Hint: first find the Laplace transform <em>Y </em>(<em>s</em>) of the output signal using the convolution and linearity properties of the Laplace transform, Then take the inverse Laplace transform to get <em>y</em>(<em>t</em>) using PFE. The “unit gain at DC” specifies <em>H</em><sub>1</sub>(0) and <em>H</em><sub>2</sub>(0), which you can use to determine the scaling factor.

<ol start="9">

 <li>[10] Consider an LTI system with input <em>x</em>(<em>t</em>) = <em>e</em><sup>−<em>t</em></sup><em>u</em>(<em>t</em>) and impulse response <em>h</em>(<em>t</em>) = <em>e</em><sup>−2<em>t</em></sup><em>u</em>(<em>t</em>).

  <ul>

   <li>Determine the Laplace transform of <em>x</em>(<em>t</em>) and <em>h</em>(<em>t</em>).</li>

   <li>Using the convolution property, determine the Laplace transform <em>Y </em>(<em>s</em>) of the output <em>y</em>(<em>t</em>).</li>

   <li>From the Laplace transform of <em>y</em>(<em>t</em>) as obtained in part(b), determine <em>y</em>(<em>t</em>).</li>

   <li>Verify your result in part (c) by explicitly convolving <em>x</em>(<em>t</em>) and <em>h</em>(<em>t</em>).</li>

  </ul></li>

 <li>[10] The system function of a causal LTI system is</li>

</ol>

Determine and sketch the response <em>y</em>(<em>t</em>) when the input is

<ol start="11">

 <li>[20] In this problem, we consider the construction of various type of block diagram representations for a causal LTI system <em>S </em>with input <em>x</em>(<em>t</em>), output <em>y</em>(<em>t</em>), and system function</li>

</ol>

To derive the direct-diagram representation of S, we first consider a causal LTI system <em>S</em><sub>1 </sub>that has the same input <em>x</em>(<em>t</em>) as <em>S</em>, but whose system function is

With the output of <em>S</em><sub>1 </sub>denoted by <em>y</em><sub>1</sub>(<em>t</em>), the direct-form diagram representation of <em>S</em><sub>1 </sub>is shown in Figure

<ol>

 <li>The signals <em>e</em>(<em>t</em>) and <em>f</em>(<em>t</em>) indicates in the figure represent respective inputs into the two integrators.</li>

</ol>

<ul>

 <li>Express <em>y</em>(<em>t</em>) (the output of <em>S</em>) as a linear combination of <em>y</em><sub>1</sub>(<em>t</em>), <em>dy</em><sub>1</sub>(<em>t</em>)<em>/dt</em>, and <em>d</em><sup>2</sup><em>y</em><sub>1</sub>(<em>t</em>)<em>/dt</em><sup>2</sup>.</li>

 <li>How is <em>dy</em><sub>1</sub>(<em>t</em>)<em>/dt </em>related to <em>f</em>(<em>t</em>).</li>

 <li>How is <em>d</em><sup>2</sup><em>y</em><sub>1</sub>(<em>t</em>)<em>/dt</em><sup>2 </sup>related to <em>e</em>(<em>t</em>).</li>

 <li>Express <em>y</em>(<em>t</em>) as a linear combination of <em>e</em>(<em>t</em>), <em>f</em>(<em>t</em>), <em>y</em><sub>1</sub>(<em>t</em>).</li>

 <li>Use the result from the previous part to extend the direct-form block diagram representation of <em>S</em><sub>1 </sub>and create a block diagram representation of <em>S</em>.</li>

 <li>Observing that</li>

</ul>

draw a block diagram representation for <em>S </em>as a cascade combination of two subsystems.

<ul>

 <li>Observing that</li>

</ul>

draw a block-diagram representation for S as parallel combination of three subsystems.
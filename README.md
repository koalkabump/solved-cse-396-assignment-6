Download Link: https://assignmentchef.com/product/solved-cse-396-assignment-6
<br>
In lecture we have concluded our discussion on computability and with it have moved into the realm of problems that are always decidable. This assignment touches on a number of the bits we saw during the exploration of the computability theory with a focus on some of the main theorems that tied everything together. Many-one reductions were a big part of our discussion and enabled us to show that many of the problems we were studying that asked about the behavior of a TM algorithm were undecdiable problems [of varying degrees].

Problem 1.  Complete the TopHat worksheet

2 Consider the following algorithm describing the TM <em>M</em><sub>1</sub>:

Input: h<em>D</em>i<em>, </em>the encoding of a DFA <em>D.</em>

<ol>

 <li>Simulate <em>D </em>on input <em>ε.</em></li>

 <li>if(<em>D </em>accepts input <em>ε</em>)</li>

 <li>Accept h<em>D</em>i<em>.</em></li>

 <li>else</li>

 <li>Reject h<em>D</em>i<em>.</em></li>

</ol>

Using <em>M</em><sub>1</sub>, prove that <em>L</em><sub>1 </sub>= {h<em>D</em>i | h<em>D</em>i is the encoding of a DFAis Turing decidable.

Problem 3.

Prove the following theorem:

If language <em>L </em>is undecidable and Turing recognizable, then <em>L </em>6≡<em><sub>m </sub>L.</em>

Problem 4.

Recall the following decision problem <em>ALL</em><sub>TM</sub>:

<em>ALL</em><sub>TM</sub>:

INSTANCE: h<em>M</em>i, the encoding of a Turing machine.

QUESTION: Is <em>L</em>(<em>M</em>) = Σ<sup>∗</sup>? (i.e., does <em>M </em>accept every input?)

Consider the function: <em>f</em><sub>1</sub>(h<em>M,w</em>i) = h<em>AoN<sub>M,w</sub></em>i

where <em>AoN<sub>M,w </sub></em>is the All-or-Nothing machine as defined in lecture. Prove that <em>A</em><sub>TM </sub>≤<em><sub>m </sub>ALL</em><sub>TM </sub>via this function <em>f</em><sub>1</sub>. Conclude that <em>ALL</em><sub>TM </sub>is undecidable.



# ve370-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [VE370 Homework 1 Solved](https://www.ankitcodinghub.com/product/ve370-homework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99093&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;VE370  Homework 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
<ol>
<li>For the following C statement, write the corresponding RISC-V assembly code. Assume that the C variables f, g, and h, have already been placed in registers x28, x29, and x30 respectively. Use a minimal number of RISC-V assembly instructions.f = g + (h − 9);</li>
<li>&nbsp;Translate the following C code to RISC-V. Assume that the variables f, g, h, i, and j are assigned to registers x5, x6, x7, x28, and x29, respectively. Assume that the base address of the arrays A and B are in registers x10 and x11, respectively. Assume that the elements of the arrays A and B are 4-byte words:
<pre>     B[8] = A[i] + A[j];
</pre>
</li>
<li>&nbsp;Translate the following loop into C. Assume that the C-level integer i is held in register x5, x6 holds the C-level integer called result, and x10 holds the base address of the integer MemArray.addi x6, x0, 0
<pre>           addi x29, x0, 100
     LOOP: lw   x7, 0(x10)
           add  x5, x5, x7
</pre>
<pre>           addi x10, x10, 4
           addi x6, x6, 1
           blt  x6, x29, LOOP
</pre>
</li>
<li>&nbsp;Show how the value 0x12345678 would be arranged in memory of a little- endian and a big-endian machine. Assume the data are stored starting at word address 0.</li>
<li>&nbsp;Assume the following register contents:
<pre>     x5 = 0x0000AAAA, x6 = 0x12345678
</pre>
</li>
</ol>
a. For the register values shown above, what is the value of x7 for the following sequence of instructions?

slli x7, x5, 4

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
or x7, x7, x6

b. For the register values shown above, what is the value of x7 for the following sequence of instructions?

<pre>     srli   x7, x5, 3
     andi   x7, x7, 0xFEF
</pre>
<ol start="6">
<li>&nbsp;Assume x5 holds the value 0x01010000. What is the value of x6 after the following instructions?
<pre>         bge x5, x0, ELSE
</pre>
<pre>         jal x0, DONE
  ELSE: ori x6, x0, 2
</pre>
DONE: ……
</li>
<li>Consider the following RISC-V loop:
<pre>  LOOP: beq x6, x0, DONE
        addi x6, x6, -1
</pre>
addi x5, x5, 2

<pre>        jal x0, LOOP
  DONE: ......
</pre>
<ol>
<li>(1)&nbsp; &nbsp;Assume that the register x6 is initialized to the value 10. What is the final value in register x5 assuming the x5 is initially zero?</li>
<li>(2)&nbsp; &nbsp;For the loop above, write the equivalent C code. Assume that the registers x5 and x6 are integers acc and i, respectively.</li>
<li>(3)&nbsp; For the loop written in RISC-V assembly above, assume that the register x6 is initialized to the value N. How many RISC-V instructions are executed?</li>
<li>(4)&nbsp; For the loop written in RISC-V assembly above, replace the instruction “beq x6, x0, DONE” with the instruction “blt x6, x0, DONE” and write the equivalent C code.</li>
</ol>
</li>
<li>Translate the following C code to RISC-V assembly code. Use a minimum number of instructions. Assume that the values of a, b, i, and j are in registers x5, x6, x7, and x29, respectively. Also, assume that register x10 holds the base address of the array D.
<pre>      for(i=0; i&lt;a; i++)
         for(j=0; j&lt;b; j++)
</pre>
D[4∗j] = i + j;
</li>
</ol>
</div>
</div>
</div>

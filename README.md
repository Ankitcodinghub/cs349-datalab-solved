# cs349-datalab-solved
**TO GET THIS SOLUTION VISIT:** [CS349 Datalab Solved](https://www.ankitcodinghub.com/product/cs349-datalab-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100100&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS349 Datalab Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
– Datalab

</div>
</div>
<div class="layoutArea">
<div class="column">
In this activity you will review the material on integers, binary, and floating-point necessary for datalab. This activity was based on material developed by Professor Saturnino Garcia of the University of San Diego. It is used here with permission.

Each activity is designed to be solved in groups and take approximately 10 minutes.

Activity 1: Bit-level and Logical

1. De Morgan’s Law enables one to distribute negation over AND and OR. Given the following expression, complete the following table to verify for the 4-bit inputs. ~(x &amp; y) == (~x) | (~y)

x y ~(x &amp; y) (~x) | (~y) 0xF 0x1

0x5 0x7 0x3 0xC

This section will explore logical operations. These operations contrast with bit-level in that they treat the entire value as a single element. In other languages, the type of these values would be termed, “bool” or “boolean”. C does not have any such type. Instead, the value of 0 is false and all other values are true.

The three operators are AND (&amp;&amp;), OR (||), and NOT (!). “!” is commonly termed “bang”.

2. Evaluate the following expression: (0x3 &amp;&amp; 0xC) == (0x3 &amp; 0xC)

3. Test whether (!!X) == X holds across different values of X. Do the same for bitwise complement.

X !X !!X ~X ~~X -1

0 1 2

Activity 2: Shifts, Negation and Conditional

1. Suppose we right shift the value of “-2” by 1. What value do we expect?

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2. With 4-bit integers, what is the binary for -2? After right shifting by 1, what value(s) might we have?

3. Fill in the following table, assuming you only have 4 bits to represent the 2s complement integer.

</div>
</div>
<div class="layoutArea">
<div class="column">
4. Find an algorithm for computing the expression (cond) ? 1 and f if cond is 0.

<pre>int conditional(int cond, int t, int f) {
 /* Compute a mask that equals 0x00000000 or
 0xFFFFFFFF depending on the value of cond */
</pre>
<pre> int mask = ______________________________________;
</pre>
</div>
<div class="column">
t :

</div>
<div class="column">
f, which equals t if cond is

</div>
</div>
<div class="layoutArea">
<div class="column">
x x in binary 1

2

7

-8

</div>
<div class="column">
-x in binary

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre> /* Use the mask to toggle between returning t or returning f */
</pre>
<pre> return __________________________________________;
}
</pre>
Activity 3: Floating-point

<ol>
<li>How many representations for zero are there with denormalized floats? Are any of these representations the same for zero as an integer?</li>
<li>Which is larger, 2127 or +inf? Does this ordering hold when these numbers are floats (i.e., if just the bit patterns are compared)?</li>
<li>There are several possible rounding schemes for floating point values. There are two components of rounding. First, is what to do in general? Should the float be rounded up, down, to zero, or to nearest? The second component is what to do about ties with round to nearest. So should 9/2.0 be 4 or 5? The default IEEE scheme is round to nearest even. Apply it to the following values for a system that only has three bits for the fractional component of the final value, so final binary value should be 1.xyz.
Value Binary Rounded Final 1 3/32

1 5/32

1 7/8

1 5/8
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Activity 4: Divide and Conquer (Bit Parity)

Let’s determine whether a number has an even number of 1-bits or an odd number. You can use any operator allowed in datalab. Return a 0 if there’s an even number and 1 if odd. Using 1 op, you can return the parity of a 1-bit number. int bitParity1bit(int x) {return x;}

1. How about if there are two bits in the input?

<pre>     int bitParity2bit(int x)
     {
</pre>
<pre>       int bit1 = ___________;
       int bit2 = ___________;
       return ___________ ^ ___________;
</pre>
}

2. How about if there are four bits?

<pre>int bitParity4bit(int x)
{
</pre>
<pre>  int mask = ___________;
</pre>
<pre>  int halfParity = ___________;
</pre>
<pre>  int mask2 = ___________;
</pre>
<pre>  return ___________ ^ ___________;
}
</pre>
3. How about if there are eight bits? (12 ops max)

<pre>int bitParity8bit(int x)
{
</pre>
<pre>  int mask = ___________;
</pre>
<pre>  int quarterParity = ___________;
</pre>
<pre>  int mask2 = ___________;
</pre>
<pre>  int halfParity = ___________;
</pre>
<pre>  int mask3 = ___________;
</pre>
<pre>  return ___________ ^ ___________ ;
}
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Activity 5: Divide and Conquer (Bit Count)

Let’s count how many bits are set in a number. For each challenge, you can use any allowed operator allowed in the integer problems in datalab. Using 1 op, return the number of bits set in a 1-bit number. int bitCount1bit(int x) {return x;}

1. How about if there are two bits in the input? (4 ops max)

<pre>int bitCount2bit(int x)
{
</pre>
<pre>  int bit1 = ___________;
  int bit2 = ___________;
  return ___________ + ___________ ;
</pre>
}

<pre>int bitCount4bit(int x)
{
</pre>
<pre>  int mask = ___________;
</pre>
<pre>  int halfSum = ___________;
</pre>
<pre>  int mask2 = ___________;
</pre>
<pre>  return ___________ + ___________ ;
}
</pre>
3. How about if there are eight bits? (12 ops max)

<pre>int bitCount8bit(int x)
{
</pre>
<pre>  int mask = ___________;
</pre>
<pre>  int quarterSum = ___________;
</pre>
<pre>  int mask2 = ___________;
</pre>
<pre>  int halfSum = ___________;
</pre>
<pre>  int mask3 = ___________;
</pre>
<pre>  return ___________ + ___________ ;
}
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
2. How about if there are four bits? (8 ops max)

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>

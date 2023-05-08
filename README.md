Download Link: https://assignmentchef.com/product/solved-project-1-cs471-optimization
<br>
Eighteen selected problems are standard benchmark functions of different properties: Schwefel, De Jong 1, Rosenbrock’s Saddle, Rastrigin, Griewangk, Sine Envelope Sine Wave, Stretch V Sine Wave, Ackley One, Ackley Two, Egg Holder, Rana, Pathological, Michalewicz, Master’s Cosine Wave, Quartic, Levy, Step and Alpine. All of the functions are dimension-wise scalable.

Table 1 presents functions together with optimal values, in cases where global optima is known and can be reasonably expressed independent of dimension. The third column gives dimensions used in the experimentation for each function. The last column is the search and initialization range used in the experimentation.

<ol>

 <li>Schwefel’s function:</li>

</ol>

(1)

<ol start="2">

 <li>1st De Jong’s function:</li>

</ol>

<em>n</em>

<em>f</em>2 (<em>x</em>) = X<em>x</em>2<em>i                                                                                                                         </em>(2)

<em>i</em>=1

<ol start="3">

 <li>Rosenbrock</li>

</ol>

(3)

<ol start="4">

 <li>Rastrigin</li>

</ol>

(4)

<ol start="5">

 <li>Griewangk</li>

</ol>

(5)

<ol start="6">

 <li>Sine Envelope Sine Wave</li>

</ol>

(6)

<ol start="7">

 <li>Stretched V Sine Wave</li>

</ol>

!

(7) 8. Ackley’s One

))                       (8)

<ol start="9">

 <li>Ackley’s Two</li>

</ol>

(9)

<ol start="10">

 <li>Egg Holder</li>

</ol>

(10)

<ol start="11">

 <li>Rana</li>

</ol>

(11)

<ol start="12">

 <li>Pathological</li>

</ol>

(12)

<ol start="13">

 <li>Michalewicz</li>

</ol>

(13)

<ol start="14">

 <li>Masters Cosine Wave</li>

</ol>

(14)

<ol start="15">

 <li>Quartic</li>

</ol>

(15) 16. Levy

where: 17. Step

<em>n</em>−1

<em>f</em><sub>17 </sub>(<em>x</em>) = <sup>X</sup>(|<em>x<sub>i</sub></em>| + 0<em>.</em>5)<sup>2                                                                                                    </sup>(17)

<em>i</em>=0

<ol start="18">

 <li>Alpine</li>

</ol>

<em>n</em>−1

<em>f</em><sub>18 </sub>(<em>x</em>) = <sup>X</sup>|<em>x<sub>i </sub></em>· <em>sin</em>(<em>x<sub>i</sub></em>) + 0<em>.</em>1 · <em>x<sub>i</sub></em>|                                           (18)

<em>i</em>=0

Table 1: Experiments

<em>f</em><sub>1 </sub>Schwefel    0                     10,20,30    [ <em>f</em><sub>2                  </sub>De Jong 1   0                     10,20,30    [ <em>f</em><sub>3                  </sub>Rosenbrock’s Saddle             0                     10,20,30    [ <em>f</em><sub>4                  </sub>Rastrigin   0                     10,20,30    [ <em>f</em><sub>5                  </sub>Griewangk    0                     10,20,30    [ <em>f</em><sub>6                  </sub>−1<em>.</em>4915(<em>n </em>− 1)              10,20,30    [ <em>f</em><sub>7                  </sub>Stretch V Sine Wave  0    10,20,30    [ <em>f</em><sub>8                  </sub>−7<em>.</em>54276 − 2<em>.</em>91867(<em>n </em>− 3)           10,20,30    [ <em>f</em><sub>9                  </sub>Ackley Two                    0    10,20,30    [

<table width="452">

 <tbody>

  <tr>

   <td width="32"><em>f</em>10</td>

   <td width="140">Egg Holder</td>

   <td width="148">−</td>

   <td width="72">10,20,30</td>

   <td width="60">[−500<em>,</em>500]<em><sup>n</sup></em></td>

  </tr>

  <tr>

   <td width="32"><em>f</em>11</td>

   <td width="140">Rana</td>

   <td width="148">−</td>

   <td width="72">10,20,30</td>

   <td width="60">[−500<em>,</em>500]<em><sup>n</sup></em></td>

  </tr>

  <tr>

   <td width="32"><em>f</em>12</td>

   <td width="140">Pathological</td>

   <td width="148">−</td>

   <td width="72">10,20,30</td>

   <td width="60">[−100<em>,</em>100]<em><sup>n</sup></em></td>

  </tr>

  <tr>

   <td width="32"><em>f</em>13</td>

   <td width="140">Michalewicz</td>

   <td width="148">0<em>.</em>966<em>n</em></td>

   <td width="72">10,20,30</td>

   <td width="60">[0<em>,π</em>]<em><sup>n</sup></em></td>

  </tr>

  <tr>

   <td width="32"><em>f</em>14</td>

   <td width="140">Masters’ Cosine Wave</td>

   <td width="148">1 − <em>n</em></td>

   <td width="72">10,20,30</td>

   <td width="60">[−30<em>,</em>30]<em><sup>n</sup></em></td>

  </tr>

  <tr>

   <td width="32"><em>f</em>15</td>

   <td width="140">Quartic</td>

   <td width="148">0</td>

   <td width="72">10,20,30</td>

   <td width="60">[−100<em>,</em>100]<em><sup>n</sup></em></td>

  </tr>

  <tr>

   <td width="32"><em>f</em>16</td>

   <td width="140">Levy</td>

   <td width="148">0</td>

   <td width="72">10,20,30</td>

   <td width="60">[−10<em>,</em>100]<em><sup>n</sup></em></td>

  </tr>

  <tr>

   <td width="32"><em>f</em>17</td>

   <td width="140">Step</td>

   <td width="148">0</td>

   <td width="72">10,20,30</td>

   <td width="60">[−100<em>,</em>100]<em><sup>n</sup></em></td>

  </tr>

  <tr>

   <td width="32"><em>f</em>18</td>

   <td width="140">Alpine</td>

   <td width="148">0</td>

   <td width="72">10,20,30</td>

   <td width="60">[−100<em>,</em>100]<em><sup>n</sup></em></td>

  </tr>

 </tbody>

</table>

<h1>Pseudo-random number generator</h1>

Use the <strong>Mersenne Twister </strong>(MT) pseudo-random number generator in your code. The MT webpage is at (<a href="http://www.math.sci.hiroshima-u.ac.jp/~m-mat/MT/emt.html">http://www.math.sci.hiroshima-u.ac.jp/</a><a href="http://www.math.sci.hiroshima-u.ac.jp/~m-mat/MT/emt.html">~</a><a href="http://www.math.sci.hiroshima-u.ac.jp/~m-mat/MT/emt.html">m-mat/MT/emt.html</a><a href="http://www.math.sci.hiroshima-u.ac.jp/~m-mat/MT/emt.html">)</a> and the different programming language codes are available at (<a href="http://www.math.sci.hiroshima-u.ac.jp/~m-mat/MT/VERSIONS/eversions.html">http://www.math.sci.hiroshima-u. </a><a href="http://www.math.sci.hiroshima-u.ac.jp/~m-mat/MT/VERSIONS/eversions.html">ac.jp/</a><a href="http://www.math.sci.hiroshima-u.ac.jp/~m-mat/MT/VERSIONS/eversions.html">~</a><a href="http://www.math.sci.hiroshima-u.ac.jp/~m-mat/MT/VERSIONS/eversions.html">m-mat/MT/VERSIONS/eversions.html</a><a href="http://www.math.sci.hiroshima-u.ac.jp/~m-mat/MT/VERSIONS/eversions.html">)</a>.

<h1>Experiment</h1>

Generate at least 30 pseudo-random solution vectors and solve for all functions in given dimensions of 10, 20 and 30. Compute statistical analysis on the obtained results for average, standard deviation, range, median and time (in millisecond).

<h1>Submission</h1>

The student must submit the following separate files to canvas:

<ol>

 <li>source codes</li>

 <li>a L<sup>A</sup>TEX typeset report on the results and its analysis</li>

</ol>

The report must contain an introduction in the problems, the full experimentation results in tabular format and condensed results with statistical analysis.

The files must be submitted through Canvas by 5PM April 5, 2019. The grading rubric is given in Table 2.

Table 2: Grading rubric
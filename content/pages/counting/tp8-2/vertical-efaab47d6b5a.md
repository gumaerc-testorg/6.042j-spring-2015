---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 3.1 Sums & Products
parent_type: CourseSection
parent_uid: 93998ab0-0443-52e8-5efc-b877380e8e28
title: 3.1 Sums & Products
uid: 5d280af9-7292-c65b-978c-b823914e77ed
---
<ul class="navigation pagination"><li id="top_bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/vertical-65e8069d3ac4';><<span>Integral Method: Video</span></a></li><li id="flp_btn_1" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2'>3.1.1<span>Arithmetic Sums: Video</span></a></li><li id="flp_btn_2" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/vertical-56598c481e1a'>3.1.2<span>Perturbation by Young Gauss</span></a></li><li id="flp_btn_3" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/vertical-46a80f3884d6'>3.1.3<span>Geometric Sums: Video</span></a></li><li id="flp_btn_4" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/vertical-7019fdda010c'>3.1.4<span>Annuities</span></a></li><li id="flp_btn_5" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/vertical-d3f74a0ca5a8'>3.1.5<span>Book Stacking: Video</span></a></li><li id="flp_btn_6" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/vertical-c496866a2419'>3.1.6<span>Harmonic Numbers</span></a></li><li id="flp_btn_7" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/vertical-65e8069d3ac4'>3.1.7<span>Integral Method: Video</span></a></li><li id="flp_btn_8" class="button_selected"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/vertical-efaab47d6b5a'>3.1.8<span>Integral Method Demystified</span></a></li><li id="flp_btn_9" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/vertical-356e14210c43'>3.1.9<span>Stirling's Formula: Video</span></a></li><li id="flp_btn_10" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/vertical-109177f07958'>3.1.10<span>Applying Stirling's Formula</span></a></li><li id="flp_btn_11" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/convergence-of-geometric-series'>3.1.11<span>Convergence of Geometric Series</span></a></li><li id="flp_btn_12" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/vertical-a64ff304ccd5'>3.1.12<span>Summation</span></a></li><li id="flp_btn_13" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/vertical-9f131aae203e'>3.1.13<span>Sum's Upper Lower Bounds</span></a></li><li id="top_continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/vertical-356e14210c43';>><span>Stirling's Formula: Video</span></a></li></ul><h2 class="subhead">Integral Method Demystified</h2><div class="self_assessment">
<br display_name="Integral Method Demystified" url_name="Integral_Method_Demystified_1" />
<p display_name="Integral Method Demystified" url_name="Integral_Method_Demystified_2">Let \(f: \mathbb{R}^{+} \rightarrow \mathbb{R}^{+} \),   \(S ::= \sum\limits_{i=1}^{n} f(i) \),   \(I ::= \int\limits_{1}^{n} f(x) dx \).</p>
<ol display_name="Integral Method Demystified" url_name="Integral_Method_Demystified_3">
<li>
<div id="Q1_div" class="problem_question"><p>What is the upper bound for \(S \) when \(f \) is weakly increasing?</p><fieldset><legend class="visually-hidden">Exercise 1</legend><div class="choice"><label id="Q1_label"><span id="Q1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(1)" id="Q1_select" class="problem_text_input"><option correct="false"></option><option correct="false">\(I \)</option><option correct="false">\(I + f(1) \)</option><option correct="true">\(I + f(n) \)</option><option correct="false">\(ln(n) \)</option><option correct="false">\(I + (1/2)f(n) \)</option></select><span style="display:none;" id="Q1_ans_span" tabindex="-1">  \(I + f(n) \)</span><span id="Q1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div></fieldset></div></li>
<li>
<div id="Q2_div" class="problem_question"><p>What is the upper bound for \(S \) when \(f \) is weakly decreasing?</p><fieldset><legend class="visually-hidden">Exercise 2</legend><div class="choice"><label id="Q2_label"><span id="Q2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(2)" id="Q2_select" class="problem_text_input"><option correct="false"></option><option correct="false">\(I \)</option><option correct="true">\(I + f(1) \)</option><option correct="false">\(I + f(n) \)</option><option correct="false">\(ln(n) \)</option><option correct="false">\(I + (1/2)f(n) \)</option></select><span style="display:none;" id="Q2_ans_span" tabindex="-1">  \(I + f(1) \)</span><span id="Q2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div></fieldset></div></li>
<li>
<div id="Q3_div" class="problem_question"><p>What is the lower bound for \(S \) when \(f \) is weakly increasing?</p><fieldset><legend class="visually-hidden">Exercise 3</legend><div class="choice"><label id="Q3_label"><span id="Q3_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(3)" id="Q3_select" class="problem_text_input"><option correct="false"></option><option correct="false">\(I \)</option><option correct="true">\(I + f(1) \)</option><option correct="false">\(I + f(n) \)</option><option correct="false">\(ln(n) \)</option><option correct="false">\(I + (1/2)f(n) \)</option></select><span style="display:none;" id="Q3_ans_span" tabindex="-1">  \(I + f(1) \)</span><span id="Q3_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div></fieldset></div></li>
<li>
<div id="Q4_div" class="problem_question"><p>What is the lower bound for \(S \) when \(f \) is weakly decreasing?</p><fieldset><legend class="visually-hidden">Exercise 4</legend><div class="choice"><label id="Q4_label"><span id="Q4_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(4)" id="Q4_select" class="problem_text_input"><option correct="false"></option><option correct="false">\(I \)</option><option correct="false">\(I + f(1) \)</option><option correct="true">\(I + f(n) \)</option><option correct="false">\(ln(n) \)</option><option correct="false">\(I + (1/2)f(n) \)</option></select><span style="display:none;" id="Q4_ans_span" tabindex="-1">  \(I + f(n) \)</span><span id="Q4_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div></fieldset></div></li>
<li>
<div id="Q5_div" class="problem_question"><p>Do the upper bounds and lower bounds for \(f \) change if it is strictly increasing/decreasing instead of weakly increasing/decreasing?</p><fieldset><legend class="visually-hidden">Exercise 5</legend><div class="choice"><label id="Q5_label"><span id="Q5_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(5)" id="Q5_select" class="problem_text_input"><option correct="false"></option><option correct="false">yes</option><option correct="true">no</option><option correct="false">it depends</option></select><span style="display:none;" id="Q5_ans_span" tabindex="-1">  no</span><span id="Q5_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div></fieldset></div><div id="S1_div" class="problem_solution" tabindex="-1">From weakly increasing/decreasing to strictly increasing/decreasing, simply change the inequality sign from \(\le \) to &lt;.</div></li>
<li>
<div id="Q6_div" class="problem_question"><p>What is the upper bound for \(H_n \)?</p><fieldset><legend class="visually-hidden">Exercise 6</legend><div class="choice"><label id="Q6_label"><span id="Q6_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(6)" id="Q6_select" class="problem_text_input"><option correct="false"></option><option correct="true">\(1 + ln(n) \)</option><option correct="false">\(ln(n+1) \)</option><option correct="false">\(ln(n) \)</option></select><span style="display:none;" id="Q6_ans_span" tabindex="-1">  \(1 + ln(n) \)</span><span id="Q6_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div></fieldset></div></li>
<li>
<div id="Q7_div" class="problem_question"><p>What is the lower bound for \(H_n \)?</p><fieldset><legend class="visually-hidden">Exercise 7</legend><div class="choice"><label id="Q7_label"><span id="Q7_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(7)" id="Q7_select" class="problem_text_input"><option correct="false"></option><option correct="false">\(1 + ln(n) \)</option><option correct="true">\(ln(n+1) \)</option><option correct="false">\(ln(n) \)</option></select><span style="display:none;" id="Q7_ans_span" tabindex="-1">  \(ln(n+1) \)</span><span id="Q7_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div></fieldset></div></li>
<li>
<div id="Q8_div" class="problem_question"><p>What is the asymptotic bound for \(H_n \)?</p><fieldset><legend class="visually-hidden">Exercise 8</legend><div class="choice"><label id="Q8_label"><span id="Q8_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(8)" id="Q8_select" class="problem_text_input"><option correct="false"></option><option correct="false">\(1 + ln(n) \)</option><option correct="false">\(ln(n+1) \)</option><option correct="true">\(ln(n) \)</option></select><span style="display:none;" id="Q8_ans_span" tabindex="-1">  \(ln(n) \)</span><span id="Q8_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div></fieldset></div><div id="S2_div" class="problem_solution" tabindex="-1">The integral method is for finding the upper and lower bounds of a sum, but it is also helpful in obtaining the asymptotic bound / asymptotic equivalence / asymptotic equality of the sum.  Once we have the upper and lower bounds, we take the limit on these bounds as \(n \rightarrow \infty \).</div><div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'optionresponse', 2: 'optionresponse', 3: 'optionresponse', 4: 'optionresponse', 5: 'optionresponse', 6: 'optionresponse', 7: 'optionresponse', 8: 'optionresponse'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'optionresponse', 2: 'optionresponse', 3: 'optionresponse', 4: 'optionresponse', 5: 'optionresponse', 6: 'optionresponse', 7: 'optionresponse', 8: 'optionresponse'}, 1, [1, 2])" class="problem_mo_button">Show Answer</button></div></li>
</ol>
</div><ul class="navigation progress"><li id="bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/vertical-65e8069d3ac4';>Back<span>Integral Method: Video</span></a></li><li id="continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp8-2/vertical-356e14210c43';>Continue<span>Stirling's Formula: Video</span></a></li></ul>
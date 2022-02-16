---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 2.3  Euler's Theorem
parent_type: CourseSection
parent_uid: 8083cb55-8a36-eb8d-ad32-920ceb95cfdb
title: 2.3  Euler's Theorem
uid: e4755cd4-59fa-090f-fe97-18a5211a4775
---
<ul class="navigation pagination"><li id="top_bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-1/vertical-96037fd2d933';><<span>The Ring Z: Video</span></a></li><li id="flp_btn_1" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-1'>2.3.1<span>Modular Exponentiation Euler's Function: Video</span></a></li><li id="flp_btn_2" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-1/vertical-62a25d1dd25f'>2.3.2<span>Euler's Totient Function</span></a></li><li id="flp_btn_3" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-1/vertical-96037fd2d933'>2.3.3<span>The Ring Z: Video</span></a></li><li id="flp_btn_4" class="button_selected"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-1/vertical-cad174bba3a3'>2.3.4<span>The Ring</span></a></li><li id="flp_btn_5" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-1/vertical-ad604933e05b'>2.3.5<span>Z mod n</span></a></li><li id="flp_btn_6" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-1/vertical-0be4c94c5864'>2.3.6<span>Fermat's Little Theorem</span></a></li><li id="flp_btn_7" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-1/vertical-f4e414f3a824'>2.3.7<span>Euler's Theorem</span></a></li><li id="top_continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-1/vertical-ad604933e05b';>><span>Z mod n</span></a></li></ul><h2 class="subhead">The Ring</h2><div class="self_assessment">
<br display_name="The Ring" url_name="The_Ring_0" />
<ol display_name="The Ring" url_name="The_Ring_1">
<li>
<div id="Q1_div" class="problem_question">
<p>Which of the following ALWAYS hold in \(Z_n\)?</p><fieldset><legend class="visually-hidden">Exercise 1</legend><div class="choice"><label id="Q1_input_1_label"><span id="Q1_input_1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q1_input_1" onclick="optionSelected(1)" name="Q1_input" class="problem_radio_input" correct="true"><span class="choice">
            \(a+b=b+a\)
          </span><span id="Q1_input_1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><div class="choice"><label id="Q1_input_2_label"><span id="Q1_input_2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q1_input_2" onclick="optionSelected(1)" name="Q1_input" class="problem_radio_input" correct="false"><span class="choice">
            \(ab=bc \implies a=c\)
          </span><span id="Q1_input_2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><div class="choice"><label id="Q1_input_3_label"><span id="Q1_input_3_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q1_input_3" onclick="optionSelected(1)" name="Q1_input" class="problem_radio_input" correct="true"><span class="choice">
            \((ab)c=a(bc)\)
          </span><span id="Q1_input_3_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><div class="choice"><label id="Q1_input_4_label"><span id="Q1_input_4_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q1_input_4" onclick="optionSelected(1)" name="Q1_input" class="problem_radio_input" correct="true"><span class="choice">
            \(a(b+c) = ab+ac\)
          </span><span id="Q1_input_4_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="Q1_status_combined" tabindex="-1" class="nostatus"></p></fieldset></div></li>
<br />
<li>
<div id="Q2_div" class="problem_question"><p>What are the elements of \(Z_7^{*}\)? <br /> Enter your answer as series of numbers in INCREASING order, separated by spaces (e.g. "2 4 6 8")</p><fieldset><legend class="visually-hidden">Exercise 2</legend><div class="choice"><label id="Q2_label"><span id="Q2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Text Response</span><input ckecktype="ci" onkeypress="numericTypedOrDropDownSelected(2)" value="" answer="1 2 3 4 5 6" type="text" id="Q2_input" class="problem_text_input"><span id="Q2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span><span style="display:none;" id="Q2_ans_span" tabindex="-1">  Answer:1 2 3 4 5 6</span></label></div></fieldset></div><div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'choiceresponse', 2: 'stringresponse'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'choiceresponse', 2: 'stringresponse'}, 1, [])" class="problem_mo_button">Show Answer</button></div></li>
</ol>
</div><ul class="navigation progress"><li id="bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-1/vertical-96037fd2d933';>Back<span>The Ring Z: Video</span></a></li><li id="continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-1/vertical-ad604933e05b';>Continue<span>Z mod n</span></a></li></ul>
---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 2.9 Coloring & Connectivity
parent_type: CourseSection
parent_uid: 109f4d41-cb88-fdaa-de16-336e6c117167
title: 2.9 Coloring & Connectivity
uid: 82f33672-223d-e835-7b0e-01944b79495e
---
<ul class="navigation pagination"><li id="top_bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-3/vertical-c79a8bf5b197';><<span>Graph Coloring I</span></a></li><li id="flp_btn_1" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-3'>2.9.1<span>Coloring: Video</span></a></li><li id="flp_btn_2" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-3/vertical-312af3a98ad1'>2.9.2<span>Chromatic Number</span></a></li><li id="flp_btn_3" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-3/vertical-857c6f8a582c'>2.9.3<span>Connectivity: Video</span></a></li><li id="flp_btn_4" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-3/vertical-a730aa2d96d6'>2.9.4<span>k-Connectivity: Video</span></a></li><li id="flp_btn_5" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-3/vertical-7dbbc5839c46'>2.9.5<span>k-Connected [optional]</span></a></li><li id="flp_btn_6" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-3/vertical-c79a8bf5b197'>2.9.6<span>Graph Coloring I</span></a></li><li id="flp_btn_7" class="button_selected"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-3/vertical-5c29d46d85ff'>2.9.7<span>Graph Coloring II</span></a></li><li id="flp_btn_8" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-3/vertical-fef93eac28bc'>2.9.8<span>Connected Components in Integers</span></a></li><li id="top_continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-3/vertical-fef93eac28bc';>><span>Connected Components in Integers</span></a></li></ul><h2 class="subhead">Graph Coloring II</h2><div class="self_assessment">
<br display_name="Graph Coloring II" url_name="Graph_Coloring_II_0" />
<div id="Q1_div" class="problem_question"><p display_name="Graph Coloring II" url_name="Graph_Coloring_II_1">
  What is the chromatic number of an acyclic graph?
  </p><fieldset><legend class="visually-hidden">Exercise 1</legend><div class="choice"><label id="Q1_label"><span id="Q1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Text Response</span><input ckecktype="ci" onkeypress="numericTypedOrDropDownSelected(1)" value="" answer="2" type="text" id="Q1_input" class="problem_text_input"><span id="Q1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span><span style="display:none;" id="Q1_ans_span" tabindex="-1">  Answer:2</span></label></div></fieldset></div><div id="S1_div" class="problem_solution" tabindex="-1" display_name="Graph Coloring II" url_name="Graph_Coloring_II_3">
<p>
      By definition, an acyclic graph contains no cycles (and in particular, no cycles of odd length). Therefore it is bipartite. This means 2 colors are <em>sufficient</em>.
      Moreover, if the graph has at least one edge, 2 colors are also
      <em>necessary</em>. Therefore, the chromatic number of any
      acyclic graph is 2.
    </p>
<p>
          Note that the answer assumes the non-trivial case, where the graph contains at least one edge.
          In the trivial case where the graph contains no edges, it only has disjoint vertices and its chromatic number is 1.
    </p>
</div><div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'stringresponse'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'stringresponse'}, 1, [1])" class="problem_mo_button">Show Answer</button></div></div><ul class="navigation progress"><li id="bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-3/vertical-c79a8bf5b197';>Back<span>Graph Coloring I</span></a></li><li id="continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-3/vertical-fef93eac28bc';>Continue<span>Connected Components in Integers</span></a></li></ul>
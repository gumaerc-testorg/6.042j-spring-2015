---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 1.9  State Machines - Invariants
parent_type: CourseSection
parent_uid: 470546ac-8124-6c93-8505-a0f7571765aa
title: 1.9  State Machines - Invariants
uid: c9c18fad-0944-7554-62d1-010531375954
---

*   [\< State Machines - Invariants]({{< baseurl >}}/pages/proofs/tp4-2)
*   [1.9.1State Machines Invariants: Video]({{< baseurl >}}/pages/proofs/tp4-2)
*   [1.9.2State Machine Invariants]({{< baseurl >}}/pages/proofs/tp4-2/vertical-ee3144f200f1)
*   [1.9.3Derived Variables: Video]({{< baseurl >}}/pages/proofs/tp4-2/vertical-ef00ae29a8ca)
*   [1.9.4Derived Variables and Termination]({{< baseurl >}}/pages/proofs/tp4-2/vertical-5bf3bfde6f69)
*   [1.9.5Integer Multiplication]({{< baseurl >}}/pages/proofs/tp4-2/vertical-85cff195fae3)
*   [1.9.6Chocolate Bars]({{< baseurl >}}/pages/proofs/tp4-2/vertical-ffd6266c03ec)
*   [\>Derived Variables: Video]({{< baseurl >}}/pages/proofs/tp4-2/vertical-ef00ae29a8ca)

State Machine Invariants
------------------------

  

1.  What are the states in the _Die Hard_ example?
    
    Exercise 1
    
    &nbsp;the total amount of water in the two jugsthe amount of water in jugs: \\((b, l) \\), where \\(b \\) is the amount in the big jug, \\(l \\) is the amount in the small jugthe difference in the amount of water in the two jubsnone of the above the amount of water in jugs: \\((b, l) \\), where \\(b \\) is the amount in the big jug, \\(l \\) is the amount in the small jug&nbsp;
    
2.  The preserved invariant for the state machine in the _Die Hard Once For All_ example is:
    
    Exercise 2
    
    &nbsp;The total amount of water must increase or decrease by exactly three gallons.The total amount of water must be preserved.The number of gallons in each jug is never divisible by the difference of the jugs.The number of gallons in each jug is always divisible by three.The number of gallons in each jug can be any integer value. The number of gallons in each jug is always divisible by three.&nbsp;
    
3.  {{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;(-11, 3)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;(3, 7)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;(5, 4)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;(2, 1)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}
4.  {{< quiz_multiple_choice questionId="Q4_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;It is induction reformulated for state machines.&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;For a preserved invariant \\(P(\\text{state}) \\), if \\(P(\\text{start state}) \\), then \\(P(r) \\), for all reachable states \\(r \\) .&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;Preserved invariants are the same as invariants.&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;Any preserved invariant of a state machine is a property of the states, including the final state, if any.&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}

*   [Back State Machines - Invariants]({{< baseurl >}}/pages/proofs/tp4-2)
*   [ContinueDerived Variables: Video]({{< baseurl >}}/pages/proofs/tp4-2/vertical-ef00ae29a8ca)
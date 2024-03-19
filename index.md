---
layout: default
random_list: true
---

Welcome to the Princeton Alg-ML Seminar Page! 

Alg-ML is a weekly ML theory seminar primarily attended by the research groups of Prof. Sanjeev Arora, Prof. Elad Hazan, Prof. Jason Lee, and Prof. Chi Jin. 
We discuss exciting recent advancements in the areas of algorithm design and theoretical machine learning. 

Talks are held **every Monday from 12:15 pm ET to 1:15 pm ET**, with food usually served at 12:00 pm ET. It is open to all members of the Princeton community. 

For the 2023-2024 academic year, this seminar is organized by[^1]:
<ul id="namesList">
    <li>Simran Kaur</li>
    <li>Eshaan Nichani</li>
    <li>Jennifer Sun</li>
</ul>


If you would like to be notified about future Alg-ML talks, please subscribe to the [alg-ml mailing list](https://lists.cs.princeton.edu/mailman/listinfo/alg-ml-reading-group) and [google calendar](https://calendar.google.com/calendar/u/1?cid=Y185ZWQxMzVmOGMxN2JjZmNhYjAyOTk3ZGU0YTg0YzRhZDkyMjE1NTcwMGRhZjg1YjgzODJjZmUzNTBhNTk0MTQ3QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20).

# This week's talk
## March 20, 2024 | Computer Science 402

> **Annie Mardsen** 
>
> **Efficient Convex Optimization Requires Superlinear Memory**
>
> Despite convex optimization’s long history of study and despite the importance of designing algorithms which have limited memory footprints, the tradeoff between an optimization algorithm’s use of memory and its performance has remained largely elusive. To what extent do restrictions on the available memory imply worsened performance? In this talk I will discuss some of the first major progress made towards understanding the answer to this question. We will consider the problem of optimizing a convex, d-dimensional, 1-Lipschitz  function to epsilon accuracy, given the ability to query the function value and its sub-gradient at any point in the domain. There are algorithms which can optimize with only d*log(1/epsilon) queries, but require Ω(d^2) bits of memory. On the other hand, gradient descent only needs O(d) bits of memory but requires 1/epsilon^2 queries. This begs the following very fundamental question: To what extent must an algorithm use memory if it hopes to achieve optimal query complexity?  I will discuss my joint work with Vatsal Sharan, Aaron Sidford, and Greg Valiant, which made the first ever progress towards understanding this question by showing a negative result that any algorithm using at most d^(1.25−δ) bits of memory must make at least Ω(d^(1+(4/3)δ )) first-order queries. This work was awarded the COLT 2022 Best Paper Award. 

# Calendar
<!--<div class="responsive-iframe-container">
    <iframe src="https://calendar.google.com/calendar/embed?src=c_9ed135f8c17bcfcab02997de4a84c4ad922155700daf85b8382cfe350a594147%40group.calendar.google.com&ctz=America%2FNew_York" allowfullscreen></iframe>
</div>-->

<div style="position: relative; overflow: hidden; width: 100%; padding-top: 56.25%;">
    <iframe src="https://calendar.google.com/calendar/embed?src=c_9ed135f8c17bcfcab02997de4a84c4ad922155700daf85b8382cfe350a594147%40group.calendar.google.com&ctz=America%2FNew_York" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none;" allowfullscreen></iframe>
</div>
<!-- <iframe src="https://calendar.google.com/calendar/embed?src=c_9ed135f8c17bcfcab02997de4a84c4ad922155700daf85b8382cfe350a594147%40group.calendar.google.com&ctz=America%2FNew_York" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>
width=device-width -->


[^1]: The ordering on this page is randomized (as opposed to ordering alphabetically).  

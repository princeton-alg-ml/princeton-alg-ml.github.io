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
## March 4, 2024 | Computer Science 302

> **Ahmed Khaled** 
>
> **Tuning-free stochastic optimization**
>
> Hyperparameter tuning is too costly to use in today's large-scale machine learning problems. This creates a need for algorithms that can tune themselves on-the-fly. We formalize the notion of "tuning-free" algorithms that can match the performance of optimally-tuned optimization algorithms up to polylogarithmic factors given only loose hints on the relevant problem parameters. We consider in particular algorithms that can match optimally-tuned Stochastic Gradient Descent (SGD). When the domain of optimization is bounded, we show tuning-free matching of SGD is possible and achieved by several existing algorithms. We prove that for the task of minimizing a convex and smooth or Lipschitz function over an unbounded domain, tuning-free optimization is impossible. We discuss conditions under which tuning-free optimization is possible even over unbounded domains. In particular, we show that the recently proposed DoG and DoWG algorithms are tuning-free when the noise distribution is sufficiently well-behaved. For the task of finding a stationary point of a smooth and potentially nonconvex function, we give a variant of SGD that matches the best-known high-probability convergence rate for tuned SGD at only an additional polylogarithmic cost. However, we also give an impossibility result that shows no algorithm can hope to match the optimal expected convergence rate for tuned SGD with high probability. 

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

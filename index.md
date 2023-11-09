---
layout: default
random_list: true
---

Welcome to the Princeton Alg-ML Seminar Page! 

Alg-ML is a weekly ML theory seminar primarily attended by the research groups of Prof. Sanjeev Arora, Prof. Elad Hazan, Prof. Jason Lee, and Prof. Chi Jin. 
We discuss exciting recent advancements in the areas of algorithm design and theoretical machine learning. 

Talks are held **every Monday from 12:30 pm ET to 1:30 pm ET**, with food usually served at 12:15 pm ET. It is open to all members of the Princeton community. 

For the 2023-2024 academic year, this seminar is organized by[^1]:
<ul id="namesList">
    <li>Simran Kaur</li>
    <li>Eshaan Nichani</li>
    <li>Jennifer Sun</li>
</ul>


If you would like to be notified about future Alg-ML talks, please subscribe to the [alg-ml mailing list](https://lists.cs.princeton.edu/mailman/listinfo/alg-ml-reading-group) and [google calendar](https://calendar.google.com/calendar/u/1?cid=Y185ZWQxMzVmOGMxN2JjZmNhYjAyOTk3ZGU0YTg0YzRhZDkyMjE1NTcwMGRhZjg1YjgzODJjZmUzNTBhNTk0MTQ3QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20).

# This week's talk
## November 13, 2023 | Computer Science 302

> **Jason Altschuler** from UPenn
>
> **Acceleration by Stepsize Hedging**
>
> Can we accelerate convergence of gradient descent without changing the algorithm — just by optimizing stepsizes? Surprisingly, we show that the answer is yes. Our proposed Silver Stepsize Schedule optimizes strongly convex functions in $k^{\log_p 2} = k^{0.7864}$ iterations, where $p=1+\sqrt{2}$ is the silver ratio and $k$ is the condition number. This is intermediate between the textbook unaccelerated rate $k$ and the accelerated rate $\sqrt{k}$ due to Nesterov in 1983. The non-strongly convex setting is conceptually identical and leads to an analogously accelerated rate $\epsilon^{-\log_p 2} = \epsilon^{-0.7864}$. We conjecture and provide partial evidence that these rates are optimal among all possible stepsize schedules.
> 
> The Silver Stepsize Schedule is an explicit non-monotonic fractal. Why should such stepsizes help? The core intuition is “hedging” between individually suboptimal strategies — short steps and long steps — since bad cases for the former are good cases for the latter, and vice versa. Properly combining these stepsizes yields faster convergence due to the misalignment of worst-case functions. This talk is based on a line of work with Pablo Parrilo that originates from my 2018 Master’s Thesis — which established for the first time that judiciously chosen stepsizes can enable accelerated convex optimization. Prior to this thesis, the only such result was for the special case of quadratics, due to Young in 1953.


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

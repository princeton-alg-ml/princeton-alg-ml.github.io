---
layout: default
random_list: true
---

Welcome to the Princeton Alg-ML Seminar Page! 

Alg-ML is a weekly ML theory seminar primarily attended by the research groups of Prof. Sanjeev Arora, Prof. Elad Hazan, Prof. Jason Lee, and Prof. Chi Jin. 
We discuss exciting recent advancements in the areas of algorithm design and theoretical machine learning. 

Talks are held **every Monday from 12:30 pm ET to 1:30 pm ET**, with food usually served at 12:00 pm ET. It is open to all members of the Princeton community. 

For the 2024-2025 academic year, this seminar is organized by[^1]:
<ul id="namesList">
    <li>Jennifer Sun</li>
    <li>Catherine Cheng</li>
    <li>Zixuan Wang</li>
</ul>


If you would like to be notified about future Alg-ML talks, please subscribe to the [alg-ml mailing list](https://lists.cs.princeton.edu/mailman/listinfo/alg-ml-reading-group) and [google calendar](https://calendar.google.com/calendar/u/1?cid=Y185ZWQxMzVmOGMxN2JjZmNhYjAyOTk3ZGU0YTg0YzRhZDkyMjE1NTcwMGRhZjg1YjgzODJjZmUzNTBhNTk0MTQ3QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20).

# This week's talk
## Nov 11, 2024 | Computer Science 302

> **Eshaan Nichani** 
>
> **How Transformers Learn Causal Structure with Gradient Descent**
>
> **Abstract**: The incredible success of transformers on sequence modeling tasks can be largely attributed to the self-attention mechanism, which allows information to be transferred between different parts of a sequence. Self-attention allows transformers to encode causal structure, which makes them particularly suitable for sequence modeling. However, the process by which transformers learn such causal structures via gradient-based training algorithms remains poorly understood. To better understand this process, we introduce an in-context learning task that requires learning latent causal structure. We prove that gradient descent on a simplified two-layer transformer learns to solve this task by encoding the latent causal graph in the first attention layer. The key insight of our proof is that the gradient of the attention matrix encodes the mutual information between tokens. As a consequence of the data processing inequality, the largest entries of this gradient correspond to edges in the latent causal graph. As a special case, when the sequences are generated from in-context Markov chains, we prove that transformers learn an induction head (Olsson et al., 2022). We confirm our theoretical findings by showing that transformers trained on our in-context learning task are able to recover a wide variety of causal structures. This is joint work with Alex Damian and Jason D. Lee.

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

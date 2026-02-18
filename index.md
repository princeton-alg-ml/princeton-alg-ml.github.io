# Princeton Alg-ML Seminar

Alg-ML is a weekly machine learning theory seminar primarily attended by the research groups of  
Prof. Sanjeev Arora, Prof. Elad Hazan, and Prof. Boris Hanin.

We discuss recent advances in algorithm design and theoretical machine learning.

**Time:** Tuesdays, 12:15–1:15 pm ET  
**Lunch:** Usually at 12:00 pm  
**Location:** CS 402

Open to all members of the Princeton community!

For spring 2026, the seminar is organized by [Gon Buzaglo](https://www.buzaglo.me) and [Anand Brahmbhatt](https://anand-10-prog.github.io).

Subscribe to the [alg-ml mailing list](https://lists.cs.princeton.edu/mailman/listinfo/alg-ml-reading-group) and the [Google calendar](https://calendar.google.com/calendar/u/1?cid=Y185ZWQxMzVmOGMxN2JjZmNhYjAyOTk3ZGU0YTg0YzRhZDkyMjE1NTcwMGRhZjg1YjgzODJjZmUzNTBhNTk0MTQ3QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20).

---

## Spring 2026 Schedule

<div class="talk-list">

<div class="talk">
  <div class="talk-date">February 10, 2026</div>

  <div class="talk-speaker">
    <strong>Abhishek Panigrahi</strong>
    <span class="affiliation">Princeton University</span>
  </div>

  <div class="talk-meta">
    CS 402 · 12:15–1:15 pm
  </div>

  <details class="talk-abstract">
  <summary>See abstract</summary>
  <div class="abstract-content">
    <div class="talk-title">
      <strong>Title:</strong> Making LLMs better teachers
    </div>
    <p> <strong>Abstract:</strong>
      Training capable small language models is a central challenge, yet existing
      distillation methods treat teachers as static supervision sources. I argue
      that effective learning depends on how a small model learns from a bigger
      one and when it learns it. I show that intermediate teacher checkpoints
      reveal implicit learning trajectories, and that aligning students to these
      trajectories yields provable sample-complexity benefits.
    </p>
  </div>
</details>
<div class="talk">
  <div class="talk-date">February 17, 2026</div>
  <div class="talk-speaker">
    <strong>Yotam Alexander</strong>
    <span class="affiliation">Tel Aviv University</span>
  </div>
  <div class="talk-meta">
    CS 402 · 12:15–1:15 pm
  </div>
  <details class="talk-abstract">
    <summary>See abstract</summary>
    <div class="abstract-content">
      <div class="talk-title"><strong>Title:</strong> Implicit Biases in Transformers and SSMs: Distribution Shifts Can Improve Generalization.</div>
      <p><strong>Abstract:</strong> Modern Large Language Models (LLMs) are typically based on Transformers and/or Structured State Space Models (SSMs), and tend to generalize well even under a distribution shift between training and test data. Conventional wisdom attributes this generalization to implicit biases induced by architectures and the gradient-based algorithms that train them. This talk will describe a series of works theoretically analyzing and empirically evaluating implicit biases in Transformers and SSMs. Beginning with Transformers, I will consider Reinforcement Learning with outcome-based supervision (as in, e.g., DeepSeek-R1), and show that on a graph traversal task, if training data includes simple examples then an implicit bias admits generalization via step-by-step reasoning (Chain-of-Thought), whereas if training data does not include simple examples then learning is intractable. Continuing to SSMs, I will consider a teacher-student setting, and show that if training data is generic then an implicit bias admits generalization, yet there are cleanly labeled examples whose inclusion in training entirely disrupts generalization. These findings carry a counterintuitive message: for both Transformers and SSMs, it is sometimes beneficial to deliberately introduce a distribution shift to training data. Further research into the potential benefits of distribution shifts for Transformers and SSMs may pave the way to more effective curricula for training modern LLMs.</p>
    </div>
  </details>
</div>

<div class="talk">
  <div class="talk-date">February 24, 2026</div>
  <div class="talk-speaker">
    <strong>Alessandro Achille</strong>
    <span class="affiliation">AWS / Caltech</span>
  </div>
  <div class="talk-meta">
    CS 402 · 12:15–1:15 pm
  </div>
  <details class="talk-abstract">
    <summary>See abstract</summary>
    <div class="abstract-content">
      <div class="talk-title"><strong>Title:</strong> TBD</div>
      <p><strong>Abstract:</strong> TBD</p>
    </div>
  </details>
</div>

<div class="talk">
  <div class="talk-date">March 3, 2026</div>
  <div class="talk-speaker">
    <strong>Zak Mhammedi</strong>
    <span class="affiliation">Google</span>
  </div>
  <div class="talk-meta">
    CS 402 · 12:15–1:15 pm
  </div>
  <details class="talk-abstract">
    <summary>See abstract</summary>
    <div class="abstract-content">
      <div class="talk-title"><strong>Title:</strong> TBD</div>
      <p><strong>Abstract:</strong> TBD</p>
    </div>
  </details>
</div>

<div class="talk">
  <div class="talk-date">March 17, 2026</div>
  <div class="talk-speaker">
    <strong>Aaron Roth</strong>
    <span class="affiliation">University of Pennsylvania</span>
  </div>
  <div class="talk-meta">
    CS 402 · 12:15–1:15 pm
  </div>
  <details class="talk-abstract">
    <summary>See abstract</summary>
    <div class="abstract-content">
      <div class="talk-title"><strong>Title:</strong> TBD</div>
      <p><strong>Abstract:</strong> TBD</p>
    </div>
  </details>
</div>

<div class="talk">
  <div class="talk-date">March 24, 2026</div>
  <div class="talk-speaker">
    <strong>Surbhi Goel</strong>
    <span class="affiliation">University of Pennsylvania</span>
  </div>
  <div class="talk-meta">
    CS 402 · 12:15–1:15 pm
  </div>
  <details class="talk-abstract">
    <summary>See abstract</summary>
    <div class="abstract-content">
      <div class="talk-title"><strong>Title:</strong> TBD</div>
      <p><strong>Abstract:</strong> TBD</p>
    </div>
  </details>
</div>

<div class="talk">
  <div class="talk-date">March 31, 2026</div>
  <div class="talk-speaker">
    <strong>Matus Telgarski</strong>
    <span class="affiliation">New York University</span>
  </div>
  <div class="talk-meta">
    CS 402 · 12:15–1:15 pm
  </div>
  <details class="talk-abstract">
    <summary>See abstract</summary>
    <div class="abstract-content">
      <div class="talk-title"><strong>Title:</strong> TBD</div>
      <p><strong>Abstract:</strong> TBD</p>
    </div>
  </details>
</div>

<div class="talk">
  <div class="talk-date">April 7, 2026</div>
  <div class="talk-speaker">
    <strong>Philippe Rigollet</strong>
    <span class="affiliation">MIT</span>
  </div>
  <div class="talk-meta">
    CS 402 · 12:15–1:15 pm
  </div>
  <details class="talk-abstract">
    <summary>See abstract</summary>
    <div class="abstract-content">
      <div class="talk-title"><strong>Title:</strong> TBD</div>
      <p><strong>Abstract:</strong> TBD</p>
    </div>
  </details>
</div>

<div class="talk">
  <div class="talk-date">April 14, 2026</div>
  <div class="talk-speaker">
    <strong>Alex Meterez</strong>
    <span class="affiliation">Harvard University</span>
  </div>
  <div class="talk-meta">
    CS 402 · 12:15–1:15 pm
  </div>
  <details class="talk-abstract">
    <summary>See abstract</summary>
    <div class="abstract-content">
      <div class="talk-title"><strong>Title:</strong> TBD</div>
      <p><strong>Abstract:</strong> TBD</p>
    </div>
  </details>
</div>

<div class="talk">
  <div class="talk-date">April 21, 2026</div>
  <div class="talk-speaker">
    <strong>Dylan Foster</strong>
    <span class="affiliation">Microsoft Research (NYC)</span>
  </div>
  <div class="talk-meta">
    CS 402 · 12:15–1:15 pm
  </div>
  <details class="talk-abstract">
    <summary>See abstract</summary>
    <div class="abstract-content">
      <div class="talk-title"><strong>Title:</strong> TBD</div>
      <p><strong>Abstract:</strong> TBD</p>
    </div>
  </details>
</div>

</div>


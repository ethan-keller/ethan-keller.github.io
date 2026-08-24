---
layout: default
---

<div class="intro">
  <img src="{{ '/assets/img/pp.png' | relative_url }}" alt="Ethan Keller">
  <div>
    <h1>Ethan Keller</h1>
    <p class="links">
      <a href="https://www.linkedin.com/in/ethkeller/" target="_blank">linkedin</a>
      <a href="https://github.com/ethan-keller" target="_blank">github</a>
      <a id="mail" href="#" data-r="moc.liamg#2002rellek.nahte">email</a>
      <span id="out"></span>
    </p>
  </div>
</div>

I'm an AI researcher at [Amazon AGI](https://www.amazon.science/) where I focus on LLMs for speech generation. Before that, I worked on reinforcement learning and federated learning at [Imperial College London](https://www.imperial.ac.uk/) for sepsis treatment prediction.

My research interests include synthetic data, post-training, multimodality, interpretability, and automated research.

## Journey

<div class="journey">
  <span class="year">2024 - now</span>
  <img class="logo" src="{{ '/assets/img/logos/amazon.png' | relative_url }}" alt="">
  <div class="body" markdown="span">I joined the AGI team at [Amazon](https://www.amazon.science/) to work on speech generation.</div>

  <span class="year">2022 - 2024</span>
  <img class="logo" src="{{ '/assets/img/logos/imperial.png' | relative_url }}" alt="">
  <div class="body" markdown="1">
MSc Computing (AI &amp; ML) at [Imperial College London](https://www.imperial.ac.uk/), where I worked with [Aldo Faisal](https://profiles.imperial.ac.uk/a.faisal) on federated reinforcement learning to predict treatments for [sepsis](https://www.nhs.uk/conditions/sepsis/) patients.

After graduating, I joined the [Brain &amp; Behaviour Lab](https://faisallab.org/) for about a year to work on the next generation of the [AI Clinician](https://www.nature.com/articles/s41591-018-0213-5).
  </div>

  <span class="year">2019 - 2022</span>
  <img class="logo" src="{{ '/assets/img/logos/tudelft.png' | relative_url }}" alt="">
  <div class="body" markdown="1">
BSc Computer Science and Engineering. My thesis focused on synthetic tabular data generation ([FCT-GAN](https://repository.tudelft.nl/record/uuid:4660ac7d-9abc-424c-8c66-070324f93d8e)). I was head teaching assistant and taught 1000+ students in machine learning, data mining and programming courses.

Along the way I completed 2 internships. First at [Jetbrains Research](https://www.jetbrains.com/research/) (2021) researching lightweight messaging systems for robotics and IoT devices, and later at [Amazon](https://read.amazon.com/) (2022) building web-based reading products in the Kindle team.
  </div>
</div>

## Languages

<dl class="levels">
  <dt>Proficient</dt><dd>English, French, Dutch</dd>
  <dt>Intermediate</dt><dd>Hebrew, Spanish, German</dd>
</dl>

## Personal

Besides research, I like going to the gym, swimming, playing tennis and hanging out with friends. I also enjoy exploring topics in medicine and health or philosophizing about concepts like superintelligence, psychological biases, determinism or self-improvement (obviously without ever reaching a conclusion).

<script>
mail.onclick = function (e) {
  e.preventDefault();
  out.textContent = mail.dataset.r.split('').reverse().join('').replace('#', '@');
};
</script>

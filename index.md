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

<script>
mail.onclick = function (e) {
  e.preventDefault();
  out.textContent = mail.dataset.r.split('').reverse().join('').replace('#', '@');
};
</script>
I'm an AI scientist at **Amazon AGI**.

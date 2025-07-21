---
layout: archive
#title: "Publications"
title: "Research"
permalink: /publications/
author_profile: true
---

<style>
    .btn {
    display: inline-block;
    background-color: #007bff;
    color: white;
    padding: 0.375rem 0.75rem;
    margin-right: 5px;
    text-align: center;
    text-decoration: none;
    border: none;
    border-radius: 0.25rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  
  .btn:hover {
    background-color: #0056b3;
  }
  
  .link-btn {
    background: none;
    border: none;
    color: #007bff;
    text-decoration: underline;
    cursor: pointer;
    font: inherit;
    margin-right: 5px;
  }
  
  .link-btn:hover {
    color: #0056b3;
    text-decoration: underline;
  }
</style>

  

<!-- ## Social Science -->
___
* **Universal Basic Income for Developing Economies** ***(Job Market Paper)*** <br>
<button class="link-btn" onclick="toggleAbstract('abstract1')">[abstract]</button>
<a href="https://kuldeepsingh-econ.github.io/files/JMP.pdf" target="_blank" rel="noopener">[pdf]</a> <a href="https://blogs.worldbank.org/impactevaluations/ubi-financing-and-its-long-term-impacts-economies-large-informal-sector-guest" target="_blank" rel="noopener"> [World Bank Blog] </a> <br>
<div id="abstract1" style="display:none;">
Universal Basic Income has gained traction as an anti-poverty policy for developing economies, but financing it poses challenges due to the vast informal sector that remains outside the income tax net. This paper analyzes the feasibility of financing UBI under alternative financing schemes and studies the long-term aggregate and distributional effects of UBI in developing countries. I build a general equilibrium life cycle model with incomplete markets that incorporates the decision to work in either the formal or informal sector. After calibrating it to Indian data, I find that a UBI equal to half the international poverty line cannot be financed through labor income taxes. An increase in labor income tax shrinks the formal sector, decreases labor supply and reduces human capital accumulation, ultimately leading to reduced tax revenues. Financing UBI via consumption taxes is feasible but results in lower output, capital, and aggregate labor, as well as an increase in income and wealth inequality. Furthermore, I highlight that UBI and taxes have opposing effects on the size of the formal sector.
</div>

* **Risky Business and the Process of Development** _(with Paco Buera, Jeremy Majerovitz, Yongseok Shin)_ <br>
<button class="link-btn" onclick="toggleAbstract('abstract2')">[abstract]</button>
<span>Updated draft coming soon!</span> <br>
<div id="abstract2" style="display:none;">
Risk is an important factor that affects investment decisions, especially for undiversified entrepreneurs in less developed economies. Yet standard macro models of financial frictions do not incorporate risk: short-term returns are known in advance, and investment is fully reversible. Thus, even if entrepreneurs are risk averse and credit constrained, they will invest all of their assets in the firm, until the marginal product of capital equals the interest rate. As a result, standard models often find that productive entrepreneurs quickly save their way out of credit constraints, limiting the effect of financial frictions on output and aggregate productivity. We incorporate risk into a model of financial frictions, by making investment partially irreversible. Productive entrepreneurs accumulate capital substantially more slowly than in the first-best, leading to a reduction in aggregate productivity. Credit can play a role in undoing these frictions if firms have an option to default. Default creates a state-contingent contract, in which the entrepreneur repays if productivity stays high and defaults if productivity falls; this encourages investment and improves welfare through risk-sharing with the bank.
</div>

<script>
function toggleAbstract(id) {
  var abstract = document.getElementById(id);
  if (abstract.style.display === "none") {
    abstract.style.display = "block";
  } else {
    abstract.style.display = "none";
  }
}
</script>

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

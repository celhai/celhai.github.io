---
layout: page
title: Research
permalink: /research/
---

## Working papers

---

<div class="pub">
  <div class="pub-title">
    <strong>Incentives to Emit in Upstream Oil and Gas: Theory, Evidence, and Policy Implications</strong>
    <span class="pub-authors"> (with Toren Fronsdal)</span>
  </div>

  <div class="pub-links">
  [ <a href="#" class="abstract-toggle"
      data-target="abs-methane"
      aria-controls="abs-methane"
      aria-expanded="false">Abstract</a>
    | <a href="/pdfs/methane_draft_current.pdf">Draft</a> ]
  </div>

  <div class="pub-abstract-text" id="abs-methane" hidden>
    <p>
      We study how market incentives and infrastructure constraints shape oil and gas industry methane emissions. We develop a model in which producers make drilling and emissions decisions and face transmission costs that depend on aggregate pipeline utilization. Leveraging novel emissions data for the Permian Basin, we show that emissions respond to high-frequency price variation as predicted by the model. We use our estimated model to evaluate policies. A methane tax reduces emissions by up to 14 percent, but pipeline congestion significantly attenuates its effectiveness. Expanding gas pipeline infrastructure yields net emission reductions and generates social returns substantially exceeding construction costs.
    </p>
  </div>
</div>

## Work in progress

---

<div class="pub">
  <div class="pub-title">
    <strong>Regulating Emissions: The Impact of New Mexico’s Flaring Rules</strong>
    <span class="pub-authors"> (with Toren Fronsdal)</span>
  </div>

  <div class="pub-links">
  [ <a href="#" class="abstract-toggle"
      data-target="abs-nmflaring"
      aria-controls="abs-nmflaring"
      aria-expanded="false">Abstract</a> ]
  </div>

  <div class="pub-abstract-text" id="abs-nmflaring" hidden>
    <p>
      Methane emissions from oil and gas production are a prime target for emissions mitigation efforts worldwide. However, there is limited evidence on which policies are actually effective at reducing methane emissions from this industry.  We evaluate the impact of rules adopted in New Mexico in 2021 that, among other things, impose strict limits on the flaring of natural gas. We compare flaring and methane emissions before and after the policy change to show that the policy had no discernible effect on either outcome. We rationalize this null result using a model of producer decision making from Elhai and Fronsdal (2026), showing that the policy was not accompanied by sufficient enforcement to overcome the private benefits of flaring. We quantify the penalties New Mexico would have needed to levy to achieve their flaring reduction targets. We then compare the cost of hitting these targets using penalties versus with Pigouvian taxation.
    </p>
  </div>
</div>

<div class="pub">
  <div class="pub-title">
    <strong>Data Centers: Location Choice and Grid Externalities</strong>
    <span class="pub-authors"> (with Yixin Zhou)</span>
  </div>
</div>

<div class="pub">
  <div class="pub-title">
    <strong>Market Power, Rate Regulation, and Quality: Evidence from Natural Gas Pipelines</strong>
    <span class="pub-authors"> (with Toren Fronsdal)</span>
  </div>
</div>

<script>
  document.addEventListener('DOMContentLoaded', () => {
    document.querySelectorAll('.abstract-toggle').forEach(link => {
      link.addEventListener('click', (e) => {
        e.preventDefault();

        const id = link.dataset.target;
        const box = document.getElementById(id);
        if (!box) return;

        const isHidden = box.hasAttribute('hidden');
        if (isHidden) box.removeAttribute('hidden');
        else box.setAttribute('hidden', '');

        link.setAttribute('aria-expanded', String(isHidden));
      });
    });
  });
</script>
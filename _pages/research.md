---
title: "Ghent Neutrino Interactions Group"
layout: textlay
excerpt: "Ghent Neutrino Interactions Group"
sitemap: false
permalink: /research/
---

<style>
.research-img-box {
  float: right;
  margin: 0 0 1.2em 1.8em;
  max-width: 260px;
  background: #f8f9fa;
  border: 1px solid #dee2e6;
  border-radius: 6px;
  padding: 10px;
  text-align: center;
  font-size: 0.82em;
  color: #555;
  line-height: 1.4;
}
.research-img-box img {
  width: 100%;
  height: auto;
  border-radius: 4px;
  display: block;
  margin-bottom: 6px;
}
.clearfix::after {
  content: "";
  display: table;
  clear: both;
}
.research-box {
  background: #f8f9fa;
  border: 1px solid #dee2e6;
  border-radius: 6px;
  padding: 16px 18px;
  margin: 1.5em 0;
}
</style>

# Research

## Reaction Mechanisms

<!-- <div class="research-img-box">
  <img src="/images/research_page/mechs.png" alt="Reaction mechanisms diagram">
  Reaction mechanisms overview.
</div> -->

<!-- <div class="clearfix"> -->
  
<div style="text-align: center;">
<img src="/images/research_page/mechs.png" 
alt="Reaction mechanisms diagram"
style="max-width: 60%;">
<p><small> Reaction mechanisms overview. </small></p>
</div>

<div class="research-box clearfix">
Neutrinos interact with matter only through the weak interaction. Consequently, they are incredibly difficult to detect. Currently, there are only a few ways to observe them, and our group focuses on building models for accelerator-based neutrino oscillation experiments. These experiments require two conditions: a high-intensity neutrino beam and massive targets for the neutrinos to interact with. Both requirements present unique challenges.

<ul>
  <li>To create a high-intensity neutrino beam, protons are accelerated to very high kinetic energies and directed toward a target block. The resulting collisions produce a variety of particles, including a large number of pions. These pions are redirected using magnetic fields and subsequently decay into muons and muon-neutrinos. A downside of this method is that the resulting beam is not mono-energetic. Instead, a wide spectrum of energies is directed toward the detector.</li>
  <li>Because neutrinos interact so rarely, we use heavy atomic nuclei such as <sup>12</sup>C, <sup>16</sup>O, and <sup>40</sup>Ar as targets to increase the probability of an interaction. However, using nuclei introduces significant theoretical challenges. Nuclei cannot be described purely by fundamental Quantum Field Theory (QFT). Because the energies of nucleons are relatively small, standard perturbation theory fails. This necessitates phenomenological models that rely on effective parameters fitted to experimental data. Because the neutrino beam is not mono-energetic, the neutrinos trigger many different types of interactions, producing a wide variety of outgoing particles. This makes it incredibly hard to reconstruct the neutrino energy from the detected final particles.</li>
</ul>

To guide these analyses, we need robust theoretical models for every possible interaction. This is where the Ghent group contributes. We develop models for the cross sections of all possible neutrino-nucleus interactions. These models are integrated into "event generators" which are simulations that determine the probability of specific interactions based on the observed final-state particles. By using these simulations, researchers can reconstruct the energy of the initial neutrino. By comparing the interaction rates at two different locations (a near detector close to the beam source and a far detector hundreds of kilometers away) the neutrino oscillation parameters can be extracted and unlock the secrets of these elusive particles.

</div>

---

## Quasi-elastic scattering

<div class="research-img-box">
  <img src="/images/research_page/diagram_QE.png" alt="Quasi-elastic scattering diagram">
  Quasi-elastic scattering: a $\nu_\mu$ strikes an <strong>individual nucleon</strong> within a nucleus, providing enough energy to knock it out.
</div>

<div class="clearfix">

Quasi-elastic scattering occurs when a $\nu_\mu$ interacts with a single nucleon bound inside the nucleus and transfers enough momentum to eject it. It is one of the dominant interaction channels at intermediate neutrino energies and serves as a key signal process in oscillation experiments. Accurate modelling of this process, including nuclear structure effects such as Pauli blocking, short-range correlations, and collective excitations through the Random Phase Approximation (RPA), is essential for reliable neutrino energy reconstruction.

</div>

---

## Pion production

<div class="research-img-box">
  <img src="/images/research_page/diagram_SPP.png" alt="Pion production diagram">
  A $\nu_\mu$ excites a <strong>nucleon</strong> into a <strong>$\Delta$-resonance</strong> that decays into a <strong>nucleon</strong> and a <strong>pion</strong>.
</div>

<div class="clearfix">

Single-pion production is a key interaction channel in neutrino–nucleus scattering and plays an essential role in the interpretation of accelerator-based neutrino experiments. In high-energy experiments like DUNE [^DUNE] and NO$\nu$A [^NOVA1] $^,$[^NOVA2], inelastic interactions that produce pions constitute a major contribution to the total neutrino–nucleus cross section. In experiments such as T2K [^T2K], Hyper-Kamiokande, and the Short-Baseline Neutrino Program, single-pion production (SPP), dominated by the $\Delta$-resonance region, accounts for roughly 20% of all neutrino interactions [^Katori_Martini]$^,$[^Isaacson_Jay]$^,$[^NEUT]. In this process, a neutrino interacts with a nucleon inside a nucleus, produces a resonance and subsequently decays into a nucleon and a pion. In addition, SPP can also contribute to "0-pion" final states when a pion is absorbed or inelastically rescattered. This leads to an important background in the oscillation analyses. A precise description of pion production and nuclear effects is therefore essential to reduce systematic uncertainties in the reconstructed neutrino energy.

<!-- <div style="display:flex; gap:1.5em; margin: 1.2em 0; justify-content: center;">
  <div style="text-align:center; max-width:200px; background:#f8f9fa; border:1px solid #dee2e6; border-radius:6px; padding:10px; font-size:0.82em; color:#555;">
    <img src="/images/research_page/resonances-1.png" style="height:130px; object-fit:contain; width:100%; border-radius:4px; margin-bottom:6px;">
    <p><small>s-channel resonance diagram.</small></p>
  </div>
  <div style="text-align:center; max-width:200px; background:#f8f9fa; border:1px solid #dee2e6; border-radius:6px; padding:10px; font-size:0.82em; color:#555;">
    <img src="/images/research_page/cross_resonances-1.png" style="height:130px; object-fit:contain; width:100%; border-radius:4px; margin-bottom:6px;">
    <p><small>u-channel cross-resonance.</small></p>
  </div>
</div> -->

<div style="display: flex; gap: 20px; justify-content: center; align-items: flex-end;">
  
<div style="text-align: center; width: 300px;">
<img src="/images/research_page/resonances-1.png"
     style="height: 200px; object-fit: contain;">
<p style="min-height: 40px;"><small>s-channel resonance diagram.</small></p>
</div>

<div style="text-align: center; width: 300px;">
<img src="/images/research_page/cross_resonances-1.png"
     style="height: 200px; object-fit: contain;">
<p style="min-height: 40px;"><small>u-channel cross-resonance.</small></p>
</div>

</div>

Our work focuses on the development of the Ghent hybrid model [^GHENT] for pion production, which combines a resonance description with a tree-level background from chiral perturbation theory [^HNV]. The original low-energy model including the $\Delta$(1232)-resonance is further extended with higher-energy resonances $P_{11}$(1440), $D_{13}$(1520), $S_{11}$(1535) [^DSD1]$^,$[^DSD2]$^,$[^DSD3]$^,$[^DSD4] and the model is partially unitarized in the $\Delta$-region through Olsson phases [^Olsson]. The tree-level background diagrams are extended to higher energies using Regge theory [^Regge1]$^,$[^Regge2]$^,$[^Regge3]$^,$[^Regge4]. Recent efforts aim to improve the theoretical consistency of the model by unitarizing all contributions using Watson's theorem [^Matthias]. This is achieved by redefining the model in a multipole decomposition, and unitarizing the amplitudes through K-matrix theory.

In addition, we investigate the role of nuclear effects, in particular final-state interactions of the produced pions and nucleons [^Javi]. Inside the nucleus, produced particles like the nucleon and pion can be absorbed, elastically and inelastically rescattered, which modifies the final-state particles. These effects are crucial for reducing systematic uncertainties in neutrino oscillation experiments.

</div>

---

## Two-nucleon knockout

<div class="research-img-box">
  <img src="/images/research_page/diagram_2p2h.png" alt="Two-nucleon knockout diagram">
  A $\nu_\mu$ ejects two nucleons from a <strong>correlated pair</strong>, transferring enough momentum to liberate both simultaneously.
</div>

<div class="clearfix">

In two-nucleon knockout, a $\nu_\mu$ ejects not one, but two nucleons from the nucleus. This occurs when the nucleons form a correlated pair, transferring enough momentum to liberate both particles from the nucleus simultaneously. This process, often referred to as 2p2h or meson-exchange current (MEC) contributions, constitutes an important part of the total cross section in the region between the quasi-elastic peak and the $\Delta$-resonance, and is a significant source of systematic uncertainty in neutrino energy reconstruction.

</div>

---

## Nuclear effects

<div class="clearfix">

Nuclear effects encompass a broad range of phenomena that modify the interaction of neutrinos with nucleons bound inside a nucleus. These include Pauli blocking, Fermi motion, short- and long-range nucleon–nucleon correlations, and final-state interactions (FSI) of outgoing particles. A reliable description of these effects is indispensable for correctly interpreting experimental cross-section measurements and reducing systematic uncertainties in oscillation analyses.

</div>

---

## Monte Carlo simulations

<!-- <div class="research-img-box">
  <img src="/images/research_page/MC_diagram.png" alt="Monte Carlo simulation diagram">
  Schematic of Monte Carlo neutrino event simulation.
</div> -->
<div style="text-align: center;">
  <img src="/images/research_page/MC_diagram.png"
       alt="Event generator logos"
       style="max-width: 60%;">
  <p><small>Schematic of Monte Carlo neutrino event simulation.</small></p>
</div>

<div class="clearfix">

Monte Carlo (MC) simulations are the backbone of neutrino experiment analyses, linking theoretical cross-section models to detector-level observables. Our group works on implementing and validating our theoretical models within widely used neutrino event generators.
<div style="text-align: center;">
  <img src="/images/research_page/logos_event_generators.png"
       alt="Event generator logos"
       style="max-width: 60%;">
  <p><small>Neutrino event generators.</small></p>
</div>

<!-- <div style="text-align:center; margin-top: 1em;">
  <div style="display:inline-block; background:#f8f9fa; border:1px solid #dee2e6; border-radius:6px; padding:10px;">
    <img src="/images/research_page/logos_event_generators.png" alt="Event generator logos" style="max-width:280px; height:auto;">
    <div style="font-size:0.82em; color:#555; margin-top:6px;">Neutrino event generators.</div>
  </div>
</div> -->

</div>

---
## References

[^DUNE]: R. Acciarri et al. (DUNE), (2016).
[^NOVA1]: M. A. Acero et al. (NOvA, R. Group), *[Eur. Phys. J. C 80, 1119 (2020)](https://doi.org/10.1140/epjc/s10052-020-08577-5)*.
[^NOVA2]: M. A. Acero et al. (NOvA), *[Phys. Rev. D 107, 052011 (2023)](https://doi.org/10.1103/PhysRevD.107.052011)*.
[^T2K]: K. Abe et al. (T2K), *[Nucl. Instrum. Meth. A 659, 106 (2011)](https://doi.org/10.1016/j.nima.2011.06.067)*.
[^Katori_Martini]: T. Katori and M. Martini, *[J. Phys. G 45, 013001 (2018)](https://doi.org/10.1088/1361-6471/aa8bf7)*.
[^Isaacson_Jay]: J. Isaacson, W. Jay, A. Lovato, P. Machado, A. Nikolakopoulos, N. Rocco, and N. Steinberg, (2026), *[Single pion production and pion propagation in ACHILLES. Physical Review D, 113(3), 036005.](https://doi.org/10.1103/13bh-22lm)*.
[^NEUT]: Hayato, Y., Pickering, L. The NEUT neutrino interaction simulation program library. *[Eur. Phys. J. Spec. Top. 230, 4469–4481 (2021).](https://doi.org/10.1140/epjs/s11734-021-00287-7)*
[^GHENT]: González-Jiménez, R., Jachowicz, N., Niewczas, K., Nys, J., Pandey, V., Van Cuyck, T., & Van Dessel, N. (2017). Electroweak single-pion production off the nucleon: From threshold to high invariant masses. *[Physical Review D, 95(11), 113007.](https://doi.org/10.1103/PhysRevD.95.113007)*
[^HNV]: Hernández, E., Nieves, J., & Valverde, M. (2007). Weak pion production off the nucleon. *[Physical Review D, 76(3), 033005.](https://doi.org/10.1103/PhysRevD.76.033005)*
[^DSD1]: Hernández, E., Nieves, J., Singh, S. K., Valverde, M., & Vicente Vacas, M. J. (2008). ν induced threshold production of two pions and N(1440) electroweak form factors. *[Physical Review D, 77(5), 053009.](https://doi.org/10.1103/PhysRevD.77.053009)*
[^DSD2]: Hernández, E., Nieves, J., Valverde, M., & Vicente Vacas, M. J. (2010). N–Δ(1232) axial form factors from weak pion production. *[Physical Review D, 81(8), 085046.](https://doi.org/10.1103/PhysRevD.81.085046)*
[^DSD3]: Hernández, E., Nieves, J., & Vicente Vacas, M. J. (2013). Single π production in neutrino–nucleus scattering. *[Physical Review D, 87(11), 113009.](https://doi.org/10.1103/PhysRevD.87.113009)*
[^DSD4]: Alvarez-Ruso, L., Hernández, E., Nieves, J., & Vicente Vacas, M. J. (2016). Watson's theorem and the N–Δ(1232) axial transition. *[Physical Review D, 93(1), 014016.](https://doi.org/10.1103/PhysRevD.93.014016)*
[^Olsson]: Olsson, M. G. (1974). Solutions of the multichannel unitarity equations describing the addition of a resonance and background. *[Nuclear Physics B, 74, 90–115.](https://doi.org/10.1016/0550-3213(74)90115-1)*
[^Regge1]: Aznauryan, I. G. (2003). Multipole amplitudes of pion photoproduction on nucleons up to 2 GeV. *[Physical Review C, 67(1), 015209.](https://doi.org/10.1103/PhysRevC.67.015209)*
[^Regge2]: Aznauryan, I. G., Burkert, V. D., et al. (2005). Electroexcitation of the P33(1232), P11(1440), D13(1520), and S11(1535). *[Physical Review C, 71(1), 015201.](https://doi.org/10.1103/PhysRevC.71.015201)*
[^Regge3]: Vrancx, T., De Cruz, L., Ryckebusch, J., & Vancraeyveld, P. (2013). *[Nuclear Physics A, 914, 74–78.](https://doi.org/10.1016/j.nuclphysa.2012.12.075)*
[^Regge4]: T. Corthals, J. Ryckebusch, and T. Van Cauteren, *[Phys. Rev. C73, 045207 (2006)](https://doi.org/10.1103/PhysRevC.73.045207)*
[^Matthias]: M. Hooft et al. (2026). Optimizing the description of the Delta region in the Ghent Hybrid model. *[arXiv:2603.29486](https://arxiv.org/abs/2603.29486)*
[^Javi]: J. García-Marcos et al. (2024). Towards a more complete description of nucleon distortion in lepton-induced single-pion production. *[Physical Review C, 109(2), 024608.](https://doi.org/10.1103/PhysRevC.109.024608)*

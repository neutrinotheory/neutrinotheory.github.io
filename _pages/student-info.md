---
title: "Student-Info"
layout: textlay
excerpt: "Master Thesis topics"
sitemap: false
permalink: /student-info/
---

<style>
/* ── Container ───────────────────────────────────────── */
.thesis-container {
  margin-bottom: 32px;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  border: 1px solid #d6d6d6;
}

/* ── Header (darker grey) ────────────────────────────── */
.thesis-header {
  background-color: #cfcfcf;
  padding: 16px 24px;
  border-bottom: 3px solid #b3b3b3;
}

.thesis-header h2 {
  margin: 0 0 10px 0;
  font-size: 1.15rem;
  color: #1a1a1a;
  line-height: 1.4;
}

.supervisor-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
}

.supervisor-tag {
  background: #b8b8b8;
  color: #2c2c2c;
  font-size: 0.76rem;
  font-weight: 600;
  padding: 3px 10px;
  border-radius: 20px;
}

/* ── Content (lighter grey) ──────────────────────────── */
.thesis-content {
  background-color: #efefef;
  padding: 22px 24px;
  line-height: 1.75;
}

/* ── Section blocks ──────────────────────────────────── */
.thesis-section {
  background: #e4e4e4;
  border-left: 3px solid #a8a8a8;
  border-radius: 0 6px 6px 0;
  padding: 13px 16px;
  margin-bottom: 12px;
}

.thesis-section:last-child {
  margin-bottom: 0;
}

.section-label {
  font-size: 0.7rem;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #777;
  margin-bottom: 8px;
}

.thesis-section p {
  margin: 0 0 10px 0;
  font-size: 0.93rem;
  color: #333;
}

.thesis-section p:last-child {
  margin-bottom: 0;
}
</style>

# Thesis Topics

<div class="thesis-container">
  <div class="thesis-header">
    <h2>Advancing the Ghent Hybrid Model for Neutrino-induced Pion Production</h2>
    <div class="supervisor-tags">
      <span class="supervisor-tag">Natalie Jachowicz</span>
      <span class="supervisor-tag">Yari De Backer</span>
      <span class="supervisor-tag">Matthias Hooft</span>
    </div>
  </div>
  <div class="thesis-content">
    <div class="thesis-section">
      <div class="section-label">Problem</div>
      <p>Depending on the energy of the incoming neutrino, different reaction mechanisms in neutrino-nucleus scattering can occur. In accelerator-based neutrino-oscillations experiments, neutrinos are produced with a broad energy range. Consequently, a comprehensive theoretical understanding of all relevant reaction mechanisms is essential to interpret the experimental results. For present and future experiments like T2K, Hyper-K and DUNE, single pion production constitutes a significant part of the signal.</p>
      <p>The Ghent Hybrid model for single-pion production on the nucleon consists of two components. At low energies, it incorporates background diagrams for the pion-nucleon system (originating from a chiral perturbation theory Lagrangian) and a subsequent decay of nucleon resonances like the delta resonance. At higher energies, the description of single pion production based solely on three-level diagrams becomes insufficient and Regge theory is used.</p>
      <p>All these models contain a lot of phenomenology, including form factors and decay widths, which require complex fits with experimental data. The quality of neutrino-nucleus data is limited which makes it very hard to build models that describe the data in all parts of phase-space. Implementing as many physics-driven constraints as possible will reduce the amount of phenomenological parameters and make the theory more reliable. Recently the Ghent model for pion production was modified by implementing unitarity below the two pion threshold.</p>
    </div>
    <div class="thesis-section">
      <div class="section-label">Goal</div>
      <p>The goal of this project is to extend the Ghent model for single pion production. The model now only contains resonances up to the 'second resonance region' whereas the third resonance region remains to be implemented. To unitarize the model at energies beyond the two-pion threshold, other decay channels like the decay into two pions or to eta mesons must be incorporated. Furthermore, these modifications should be tested in the nuclear framework to investigate the effect of final state interactions.</p>
    </div>
  </div>
</div>

<div class="thesis-container">
  <div class="thesis-header">
    <h2>Decoding the Quasi-Elastic Signal in Future Neutrino Oscillation Experiments</h2>
    <div class="supervisor-tags">
      <span class="supervisor-tag">Natalie Jachowicz</span>
      <span class="supervisor-tag">Marco Vanderpoorten</span>
      <span class="supervisor-tag">Matthias Hooft</span>
      <span class="supervisor-tag">Ashish Kumar Jha</span>
    </div>
  </div>
  <div class="thesis-content">
    <div class="thesis-section">
      <div class="section-label">Problem</div>
      <p>The discovery of neutrino oscillations has driven significant investment into our understanding of the properties of this phenomenon. Current and future experiments, such as T2K and HyperKamiokande in Japan and the SBND and DUNE programs in the US, aim to improve our knowledge of mixing angles, mass hierarchy, and CP violation. These experiments measure the interaction rate of neutrinos with a target at different distances: one near the source (near detector) and one far away (far detector).</p>
      <p>A major challenge in analyzing the results of these experiments is the systematic uncertainty in neutrino interaction modeling across different energy ranges. In the quasi-elastic (QE) region, where a single nucleon is ejected from the nucleus, several competing models exist, ranging from simple to highly complex descriptions of nuclear effects. Both the initial vertex (i.e. the interaction of the incoming neutrino with a bound nucleon) as well as final-state interactions (i.e. the secondary interactions the hit nucleon experiences while propagating outwards) are important and need to be modeled with high precision. For the oscillation analyses, that rely on a comparison of the interaction rate between the near and the far detector, sound estimates of the uncertainties in the predictions for these models is essential. A comprehensive study of these models is hence necessary to assess their strengths and weaknesses.</p>
    </div>
    <div class="thesis-section">
      <div class="section-label">Goal</div>
      <p>This project aims to investigate the impact of different quasi-elastic models on various observable kinematic quantities in neutrino-nucleus scattering. The student will start by comparing the results of the relatively simple (but often used in experimental analyses) Relativistic Fermi Gas (RFG) with the results of more advanced microscopic descriptions of the process like the Mean Field (MF) and the Continuum Random Phase Approximation (CRPA) approaches. Building on this first milestone, one of the main goals of this project will be to develop an improved understanding of final-state interactions (FSI) in the nucleus. To this end, the student will build a toy model for the description of the final state interactions of the nucleon, to study the influence of assumptions and parameters that are traditionally built-in by the semi-classical description instrumented by event generators. Additionally, a comparison with Monte Carlo generators like NuWro, which form the bridge between theory and experiment, can be performed. Ultimately, the goal is to develop a better understanding of these models, assess their strengths and weaknesses, and demonstrate a path forward for building an improved FSI model.</p>
    </div>
  </div>
</div>

<div class="thesis-container">
  <div class="thesis-header">
    <h2>Final State Interactions in Coherent Pion Production</h2>
    <div class="supervisor-tags">
      <span class="supervisor-tag">Natalie Jachowicz</span>
      <span class="supervisor-tag">Javier Garcia Marcos</span>
      <span class="supervisor-tag">Matthias Hooft</span>
    </div>
  </div>
  <div class="thesis-content">
    <div class="thesis-section">
      <div class="section-label">Problem</div>
      <p>Coherent pion production refers to pion-nucleus scattering that leaves the nucleus intact. Coherent pion production in neutrino experiments is relatively rare, but neutral-current coherent interactions contribute to one of the main backgrounds in oscillation analyses, for example, at the T2K experiment. The identification of these processes is carried out through measuring the pion decay into two photons, which can mimic the electron neutrino appearance signal. This motivates the development of a realistic and sophisticated treatment of coherent pion production on nuclei. In general, two methods are used to model this interaction. The first one involves making use of the partially conserved axial vector current (PCAC) principle to relate neutrino-induced coherent pion production to elastic pion-nucleus scattering amplitudes. The second one is to adopt a fully relativistic and quantum mechanical point of view, making a nuclear description identical to the one used for incoherent pion production.</p>
    </div>
    <div class="thesis-section">
      <div class="section-label">Goal</div>
      <p>In this project, we aim to model coherent pion production following the second method, based on the Gent model for pion production with a relativistic mean field (RMF) model for the bound nucleon states, which has proven to be successful in reproducing lepton-induced single pion production on nuclei. The impact of final state interactions (FSI) between the pion and the nucleus after the interaction, and medium modifications must be studied in order to develop a full coherent pion production model. This thesis subject offers the opportunity to spend a research stay in the neutrino research group of Complutense University of Madrid or University of Seville.</p>
    </div>
  </div>
</div>

<div class="thesis-container">
  <div class="thesis-header">
    <h2>Detecting Astrophysical Neutrinos on Earth</h2>
    <div class="supervisor-tags">
      <span class="supervisor-tag">Natalie Jachowicz</span>
      <span class="supervisor-tag">Marco Vanderpoorten</span>
      <span class="supervisor-tag">Ashish Kumar Jha</span>
    </div>
  </div>
  <div class="thesis-content">
    <div class="thesis-section">
      <div class="section-label">Problem</div>
      <p>While the future generation of accelerator-based neutrino experiments are built with the primary aim of enhancing our knowledge on neutrino oscillations and determining the CP violating phase in the weak sector, the detectors that are constructed are also able to observe the low-energy neutrinos reaching the Earth from a galactic supernova. These neutrinos are produced in enormous amounts at the end of the life of a massive star when the center of the star implodes and neutronization processes take place. When the central density of the star reaches and exceeds nuclear density values, the star core bounces and a shock wave sets off. Densities drop, the neutrinos produced during the neutronization processes are released and can reach detectors on Earth, carrying with them precious information about the processes going on in the very center of the supernova event, information that is not accessible with optical observations. In 1987, the handful of neutrinos from supernova 1987A that were observed showed these basic ideas to be correct and proved that it is indeed possible to detect these neutrinos. Nowadays, several experiments (e.g. DUNE) are planning for a much more detailed study of these neutrinos, their flavor, energy, arrival time, etc.</p>
    </div>
    <div class="thesis-section">
      <div class="section-label">Goal</div>
      <p>For the detection of supernova neutrinos one often relies on their interaction with atomic nuclei. Recent measurements of low energy neutrino cross sections (e.g. by the COHERENT collaboration) however show strong discrepancies between predictions and data for these reactions, indicating that in this energy regime, the interaction and the influence of nuclear effects is only poorly understood. Within the nuclear framework used in our research group, the role of transitions to discrete nuclear states has not been studied yet. The aim of this master thesis is to study these low energy neutrino-nucleus cross sections and investigate the role of nuclear effects and uncertainties for supernova neutrino detection using a consistent framework over the whole energy range relevant for supernova neutrinos.</p>
    </div>
  </div>
</div>

<div class="thesis-container">
  <div class="thesis-header">
    <h2>Modeling Kaon Production for Neutrino Oscillation Experiments</h2>
    <div class="supervisor-tags">
      <span class="supervisor-tag">Natalie Jachowicz</span>
      <span class="supervisor-tag">Javier Garcia Marcos</span>
      <span class="supervisor-tag">Tania Franco Munoz</span>
    </div>
  </div>
  <div class="thesis-content">
    <div class="thesis-section">
      <div class="section-label">Problem</div>
      <p>In long-baseline neutrino oscillation experiments, neutrinos are produced with a broad energy range. This results in several competing reaction mechanisms for the neutrino-nucleus interaction used for detecting the neutrino, that all need to be modeled in order to fully understand the oscillation signal. At sufficiently high neutrino energies, mesons begin to be created in the neutrino-nucleon interaction. The most common interaction mechanism of this type is pion production. Alternatively, kaons (mesons containing a strange quark) can be produced. The kaon production signal is usually small compared to the more common pion production, as it is Cabibbo suppressed, but it will provide an important contribution to the signal in the detector. In the detectors of the <a href="https://sbn.fnal.gov/">short-baseline neutrino (SBN) program</a> and in the future <a href="https://www.dunescience.org">Deep Underground Neutrino Experiment (DUNE)</a>, kaon production is expected to be an important interaction mechanism. A proper modeling of the process will hence be important to reduce systematic errors in the neutrino energy reconstruction and the oscillation analysis.</p>
    </div>
    <div class="thesis-section">
      <div class="section-label">Goal</div>
      <p>The goal of this project is to explore the development of a kaon production model for lepton-induced charged-current kaon production. Firstly, modeling the vertex in which the kaon is produced and then applying final state interactions to model the propagation of the kaon through the nuclear medium.</p>
    </div>
  </div>
</div>

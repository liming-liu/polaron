# Carrier Dynamics of TiO~2~ (110) surface with BBOV

## Abstract

The carrier dynamics coupled with quasi-particles is the challenging filed for solid state physics. Here we investigate the polaronic carrier dynamics in TiO~2~ using state-of-art NAMD method. We report that the polaronic states alters the carrier re-combination pathway through e-h coupling. 

---

## Motivation

TiO~2~ as the most important photo-catalytic material, the mechanism of its carrier dynamics is still not clear. We adopted NAMD methods to investigate electron and hole dynamics in the presence of O~v~.  O~v~ would bring un-paired electrons into the system, the two excess electrons would induce local lattice distortion and localize on Ti atom forming so called small polaron. In the presence localized polaron states, the carrier dynamics revealed sensible dependence on temperature. 

---

## Results and discussion

To elucidate the non-adiabatic effect of carrier dynamics on TiO~2~ (110) surface with O~v~, three typical T were chosen to test the e-p coupling. 

---

### Energy levels evolution

>Be cautious, the range of time is not in accordance at different T, specifically, at T=100K: [0-1000]; at T=300K:[0-1000]; at T=1000K:[0-500]

<center><img src="http://wx1.sinaimg.cn/mw690/006VaKryly1g1ik8vpth2j31400u077e.jpg" width="33%" /><img src="http://wx2.sinaimg.cn/mw690/006VaKrygy1g1afjqsosfj31400u0ads.jpg" width="33%" /><img src="http://wx4.sinaimg.cn/mw690/006VaKryly1g1ikf4pwj6j31400u00vy.jpg" width="33%" /></center>

From left to right, the frontier orbitals (To investigate the carrier re-combination time scale, only 4 frontier orbitals were chosen as the NAMD basis. VBM, LPS, HPS and CBM from bottom to top) evolution at 100K, 300K, and 1000K were showed. The energy levels oscillation differs in frequency and magnitude from 100K to 1000K. Be specific, more high frequency were activated as T increased.

+++

### Fourier Transform of ELE

To analyze the periodicity of a time dependent signal, the Fourier transform could be adopted:

$$
f(\omega) = \int_{-\infty}^{\infty} dt \  g(t) e^{-i\omega t} 
$$

To numerically proceed Fourier transformation, how?

+++

#### Improvements

1. Using FFT get frequency spectrum
2. Recognize key mode responsible for carrier hopping. (Frozen phonon method)

+++

### Carrier relaxation

---

#### Electron

>Again, the range of time is not in accordance at different T. Specifically, at T=100K: [0-500]; at T=300K:[0-800]; at T=1000K:[0-300]


<center><img src="http://wx1.sinaimg.cn/mw690/006VaKrygy1fzh9xh1oytj31400u0dla.jpg" width="33%" /><img src="http://wx3.sinaimg.cn/mw690/006VaKrygy1g1bjryo398j31400u043x.jpg" width="33%" /><img src="http://wx3.sinaimg.cn/mw690/006VaKryly1g1ibyb889cj31400u0grn.jpg" width="33%" /></center>

Electron initially occupied CBM to evolve. 

1. For T=100K, no sign of decaying in the range of 500fs;
2. For T=300K, electron decay to LPS after 700fs;
3. For T=1000K, electron decay to VBM after 200fs.

+++

#### Hole
<center><img src="http://wx4.sinaimg.cn/mw690/006VaKrygy1fzh9xvmi2zj31400u00yh.jpg" width="33%" /><img src="http://wx4.sinaimg.cn/mw690/006VaKrygy1g1bba43n6kj31400u0n4d.jpg" width="33%" /><img src="http://wx3.sinaimg.cn/mw690/006VaKryly1g1ibygeqq6j31400u0dof.jpg" width="33%" /></center>

While for hole, the decay seems much faster than that of electron.

1. T=100K, no sign of decay in 500fs;
2. T=300K, hole decay from VBM to HPS after 500fs;
3. T=1000K, hole decay from VBM to HPS after 100fs;

==What is the reason for the fastening decay?==

Several assumptions rised to explain this difference:

1. After 700 fs, electron populated on lower polaron state, hole populated on higher polaron state, each carrier experienced different relaxation path. So if the coupling between VBM and lower polaron state is stronger than the coupling between CBM with higher polaron state, the faster decay of hole is expected.
2. It reflects the difference between hole polaron and electron polaron. Since in TiO2, hole polaron is more delocalized than electron polaron, then hole decay faster from LPS to HPS than electron from HPS to LPS.

> Still I got no much clue on how to push the project forward. May be I should prepare discuss with colleagues in near future after gaining more data.


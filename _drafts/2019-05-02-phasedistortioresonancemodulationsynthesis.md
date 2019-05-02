---
layout: post
title:  "phase distortion resonance modulation synthesis"
date:   2019-05-02 01:23:08 -0700
categories: synthesis
permalink: /synth/pdrms/
---
<style>
section {
  margin-bottom: 1em;
     box-shadow: 1pt 2pt 6pt inset rgba(0,0,0,.25);
     background: #eee;
        padding: 0pt 2em 1em;
	 border: 1px solid #eff;
}
section > *:not(h2){
}
section > h2{
  border-bottom: 8pt solid #fcf;
    margin-left: -1em;
    text-indent: 10pt;
    text-shadow:  1pt  1pt 0pt      rgba(0,0,0,.5),
                  2pt  4pt 6pt      rgba(0,0,0,.3);
     box-shadow:  2pt  6pt 6pt -6pt rgba(0,0,0,.5);
     background: rgba(0,255,255,.5);
          color: #fff;
	  width: calc(100% + 2em);
}
</style>
<section markdown="1">
## phase distortion resonance modulation synthesis

What about modulating step c?

![wikipedia screenshot](/assets/img/screenshots/20190502-1.png)
</section>

<section markdown="1">
<details markdown="1">
<summary>from wikipedia:</summary>

As well as being more capable of generating traditional linear spectra, the CZ synthesizers can also emulate resonant filter sweeps. This was done using sine waves at the resonant frequency, synchronised and windowed at the fundamental frequency. Frequencies could be controlled but not resonance amount.

Figure 19 from the 1985 CZ-series patent shows how to emulate the variable resonance found in analogue voltage-controlled filters:

(a) The base frequency counter, wrapping around every period.
(b) The resonance frequency counter at a slightly higher frequency, being reset (or "synced") when the base counter wraps around.
(c) The resonance frequency counter used as a sine wave readout. Note the nasty sudden jump at the reset!
(d) The inverted base frequency counter.
(e) Multiplying c by d. The sudden jump in c is now leveled out.
To summarize in other terms: The resonance is a form of digital hard sync, composed of a sine wave at the resonant frequency, amplitude enveloped by and hard-synced to a window function at the fundamental frequency. The window function can take various shapes, including sawtooth and triangle, thus determining the 'basal' spectrum upon which the resonant effect is superimposed. Since the amplitude of all available window functions ends at zero, this removes sharp discontinuities in the synced sine wave, which is a well-known way to reduce aliasing in digital sync. However, some aliasing is still present due to discontinuities in the function's derivatives[clarification needed]. Thus, filter sweep effects are generated the same way as sync effects: by modulating the frequency of the resonance (DCW envelope), the timbre changes, adding and subtracting harmonics to/from the chosen fundamental spectrum around the chosen resonant frequency.
</details>
</section>

# pll
pll vco design using sky130nm library on magic and ngspice 
# PLL VCO using 130nm PDK

# Table of Contents
- [Abstract](https://github.com/anandr16910/pll/edit/main/README.md#abstract)
- [INTRODUCTION](https://github.com/anandr16910/pll/edit/main/README.md#introduction)
- [Truth Table of 3:8 Decoder](https://github.com/anandr16910/pll/edit/main/README.md#truth-table-of-38-decoder)
- [Circuits and Waveforms](https://github.com/laptopcomputermistri/Nikhil/blob/main/README.md#circuits-and-waveforms)
  1. [Inverter](https://github.com/laptopcomputermistri/Nikhil#inveter)
  2. [3 input AND](https://github.com/laptopcomputermistri/Nikhil#3-input-and)
  3. [3-8 Decoder waveform (NOTE : Active LOW)](https://github.com/laptopcomputermistri/Nikhil#3-8-decoder-waveform)
  4. [4-16 bit decoder using 3-8 Decoder](https://github.com/laptopcomputermistri/Nikhil#4-16-bit-decoder-using-3-8-decoder)
  5. [5-32 Decoder using 3-8 Decoder](https://github.com/laptopcomputermistri/Nikhil#5-32-decoder-using-3-8-decoder)
  6. [Simulation/Testbench Circuit](https://github.com/laptopcomputermistri/Nikhil#simulationtestbench-circuit)
  7. [Output Waveform of 5-32 bit Decoder (NOTE : Active LOW)](https://github.com/laptopcomputermistri/Nikhil#output-waveform-of-5-32-bit-decoder-note--active-low)
- [References](https://github.com/laptopcomputermistri/Nikhil#references)
- [Acknowledgements](https://github.com/laptopcomputermistri/Nikhil/blob/main/README.md#acknowledgements)
- [Author](https://github.com/laptopcomputermistri/Nikhil#author)
# Abstract
The circuit is designed to be used in high performance memory-decoding or data-routing applications
requiring very short propagation delay times. In highperformance memory systems, this decoder can be used to
minimize the effects of system decoding. When employed with
high-speed memories utilizing a fast enable circuit, the delay
times of this decoder and the enable time of the memory are
usually less than the typical access time of the memory. This
means that the effective system delay introduced by the
decoder is negligible.

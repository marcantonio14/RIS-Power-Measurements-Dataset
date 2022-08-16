# RIS-Power-Measurements-Dataset
***
#### Here we provide the dataset containing the power measurements carried out in the anechoic chamber of TU Darmstadt. 
The test was performed under the following conditions:
* TX at 1.1m away from RIS with -3° elevation angle and AoA θ<sub>t</sub> = [20°,90°] 
* RX at 6.3m away from RIS with 33°
* Horn antennas gain = 13.5 dBi 
* OFDM QPSK-modulated symbols with 5 MHz of bandwidth, numerology that meets LTE requirements. 
* TX power per subcarrier = -30 dBm
* Reference signal received power (RSRP) sampling at RX
* Noise floor = -90dBm

For more details, please refer to sec. 5 of our paper.

In the CSV file, the pair (θ<sub>n</sub>, Φ<sub>n</sub>) defines the RIS main beam location: θ<sub>n</sub> for the azimuth and Φ<sub>n</sub> for the elevation.
Instead, θ<sub>r</sub> indicates the angle for the radiation pattern varying with a step of 3° on the azimuth.

***

### The use of data here contained is intended only for research purposes. Any use of it has to be acknowledged by citing the following:
---
```
@article{rossanese2022designing,
  title={Designing, Building, and Characterizing RF Switch-based Reconfigurable Intelligent Surfaces},
  author={Rossanese, Marco and Mursia, Placido and Garcia-Saavedra, Andres and Sciancalepore, Vincenzo and Asadi, Arash and Costa-Perez, Xavier},
  journal={arXiv preprint arXiv:2207.07121},
  year={2022}
}
```
---

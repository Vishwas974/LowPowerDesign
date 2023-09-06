# Power and Energy Consumption of Digital Systems

## Design of Low Power and Low Energy VLSI Domino Logic OR Gate Circuit

### Introduction

The power dissipation of a circuit is reduced in normal mode of operation compared to test mode for any low-power VLSI designs. This reduction in power dissipation during normal operation is critical for maximizing the battery life of devices. Power dissipation can be reduced at different stages of the circuit design. In CMOS circuits, power dissipation can be categorized as dynamic or static. Dynamic power dissipation arises from switching activities during test patterns, while static power dissipation is due to leakage current in the device.

This project focuses on the design of a low-power and low-energy VLSI Domino Logic OR gate circuit. The proposed design uses a smaller number of clocked transistors to reduce dynamic power consumption and leakage current. The project involves designing and simulating the circuit using Cadence tools in 180nm technology.

### Project Details

#### A) Conventional Diode Footed Domino Logic OR Gate
![image](https://github.com/Vishwas974/LowPowerDesign/assets/144245060/3f7eb301-882b-4e97-94f7-47d4fd537510)


- The Conventional Diode Footed Domino Logic OR gate includes an NMOS transistor in a diode configuration in series with the evaluation network.
- The diode footer (M1) reduces sub-threshold leakage due to stacking effects, but it can lead to performance degradation.
- A mirror transistor (M2) is employed to enhance performance characteristics.

##### Implementation
![image](https://github.com/Vishwas974/LowPowerDesign/assets/144245060/79b04585-345f-466d-83b8-941e8c9ea207)


- Circuit design of the Diode Footed Domino Logic OR gate using Cadence platform for 180nm technology with a supply voltage of 1.8V and 100 MHz frequency.
- Characterization of transistors in saturation region.
- Analysis of power, area, and delay for the design.
- Proposed changes in structural and logical implementation to further reduce power, area, and delay.
- Comparison of the proposed technique with existing conventional techniques in terms of power, area, and delay.

#### B) Modified Conventional Design Proposed Circuit for Domino Logic OR Gate
![image](https://github.com/Vishwas974/LowPowerDesign/assets/144245060/e931e1cf-2450-4bdd-beab-2053de8bda24)


- The Modified Conventional Design Proposed Circuit includes an extra enable signal to ensure a static output even in the pre-charge phase.
- Circuit operation involves dynamic node charging and discharging based on input logic.
- An external enable signal ensures proper functioning and allows multiple transitions.

##### Implementation
![image](https://github.com/Vishwas974/LowPowerDesign/assets/144245060/cfda3f9b-edde-493e-9133-812e6822f2a5)


- Circuit design of the Modified Conventional Design Proposed Circuit for Domino Logic OR gate using Cadence platform for 180nm technology with a supply voltage of 1.8V and 100 MHz frequency.
- Characterization of transistors in saturation region.
- Analysis of power, area, and delay for the design.

### Simulated Outputs

The simulated outcomes of the Domino Logic OR gate are obtained using Cadence Virtuoso with 180nm CMOS technology and a supply voltage of 1.8V. The Diode Footed technique optimizes power dissipation and energy consumption. The proposed circuit method for Domino Logic OR gate design yields better results in terms of power dissipation and static power.

![image](https://github.com/Vishwas974/LowPowerDesign/assets/144245060/2f361da4-8595-4b94-915d-b3599fe458ce)

![image](https://github.com/Vishwas974/LowPowerDesign/assets/144245060/0d0e3887-44b7-497a-8a92-fa182f085978)


#### Table: Comparison of Domino Logic OR gate using different methods

| Performance Parameter | Conventional Diode Footed Domino Logic OR Gate | Modified Proposed Circuit Domino Logic OR Gate |
|-----------------------|--------------------------------------------------|--------------------------------------------------|
| Technology Used       | 180nm                                            | 180nm                                            |
| Supply Voltage        | 1.8V                                             | 1.8V                                             |
| Power Dissipation     | 406.7E-6                                         | 1.344E-6                                         |
| Energy                | 425.0E-15                                        | 136.1E-15                                        |
| Static Power          | 68.27E-12                                        | 48.73E-12                                        |

### Conclusion

In this project, we calculated power and energy for both the conventional Diode Footed Domino Logic OR gate and the modified proposed circuit Domino Logic OR gate, designed for 180nm technology with a 1.8V supply voltage using Cadence Virtuoso. The modified design yields better power dissipation and energy efficiency compared to conventional designs.



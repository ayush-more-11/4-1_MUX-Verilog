# 4-1_MUX-Verilog
Verilog Code and Testbench for implementation of 4:1 Multiplexer using Gate, Dataflow, Behavioral Level Modelling.

| S1 | S0 | Y |
| -- | -- | ---------- |
| 0  | 0  | I0         |
| 0  | 1  | I1         |
| 1  | 0  | I2         |
| 1  | 1  | I3         |

 y = (i0 & ~s1 & ~s0 )  |  (i1 & ~s1 & s0 )  |  (i2 & s1 & ~s0 )  |  (i3 & s1 & s0 );

# How it works

This project implements a simple two-input AND gate using Verilog. It takes two digital inputs, A and B, and produces one output.

The output is HIGH (1) only when both inputs are HIGH (1). Otherwise, the output is LOW (0).

The inputs are connected to `ui_in[0]` and `ui_in[1]`, and the result is sent to `uo_out[0]`. The remaining output pins are set to zero.

# How to test

To test the AND gate, apply the following input combinations:

| Input A | Input B | Expected Output |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

The circuit is working correctly if the output is 1 only when both inputs are 1.

# External hardware

No external hardware is required for simulation. The circuit can be tested using the Tiny Tapeout simulation environment.

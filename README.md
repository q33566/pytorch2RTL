# Objective: Turning pytorch model into RTL code
## Overview
1. Create a model using pytorch
2. Export a model to ONNX (Open Neural Network Exchange)
3. Convert ONNX → Vitis HLS Project
4. Synthesize HLS C++ → RTL Verilog
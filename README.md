## Online Evaluation
Our online implementation is based on pure python code with some optimization of the streaming convolutions and transposed convolutions.
We benchmark this implementation on a quad-core Intel i5 CPU at 2 GHz.
The Real-Time Factor (RTF) of the proposed models are:

| Model | Threads | RTF  |
|-------|---------|------|
| H=48  | 1       | 0.8  |
| H=64  | 1       | 1.2  |
| H=48  | 4       | 0.6  |
| H=64  | 4       | 1.0  |


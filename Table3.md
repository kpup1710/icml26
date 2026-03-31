**Table 3**: Throughput analysis of generations during inference with precomputed steering vectors from Momentum Steering, under sequential and non-sequential steering respectively. Non-sequential steering acts as the baseline for comparison.

| Model | Sequential| Total time (s) |Input Throughput (tok/s) | Output Throughput (tok/s)| Throughput (tok/s) |
|:--------------|:---:|:----:|:--------:|:-----:|:-----:|
| Qwen2.5-7B-Instruct | | 6.72| 641.2| 7586.7  | 8227.8
| Qwen2.5-7B-Instruct | $\checkmark$ | 6.62| 650.8 | 7775.5  | 8426.3 |
| Qwen2.5-32B-Instruct | | 22.43  | 192.0  | 2304.0 | 2496.0
| Qwen2.5-32B-Instruct | $\checkmark$| 22.38 | 192.4 | 2323.3 | 2515.7
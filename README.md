# Gaia

Gaia turns CPU/GPU selection into a platform decision for serverless AI across the Edge–Cloud–Space 3D Compute Continuum. At deploy time, an Execution Mode Identifier classifies each function into cpu, cpu_preferred, gpu_preferred, or gpu based on DL imports, explicit device calls, and tensor ops. At runtime, a Dynamic Function Runtime monitors SLOs (latency, throughput) and promotes/demotes functions between CPU and GPU with cold-start and hysteresis guards to avoid thrashing.
Across representative workloads (matrix multiply, ResNet-18, TinyLlama, idle), Gaia reduces end-to-end latency by up to 95% on accelerable tasks while avoiding unnecessary GPU usage on non-accelerable ones—delivering SLO-aware, cost-efficient acceleration suitable for heterogeneous, resource-constrained environments, including LEO satellites.

## Citation

Plain Text

> M. Reisecker, C. Marcelino, T. Pusztai, and S. Nastic, “Gaia: Hybrid Hardware Acceleration for Serverless AI in the 3D Compute Continuum,” in IEEE/ACM 12th International Conference on Big Data Computing, Applications and Technologies (BDCAT ’25), Nantes, France, 2025. https://doi.org/10.1145/3773276.3774299

BibTex
```
@inproceedings{GaiaBDCAT2025,
  author    = {Reisecker, Maximilian and Marcelino, Cynthia and Pusztai, Thomas and Nastic, Stefan},
  title     = {Gaia: Hybrid Hardware Acceleration for Serverless AI in the 3D Compute Continuum},
  booktitle = {IEEE/ACM 12th International Conference on Big Data Computing, Applications and Technologies (BDCAT '25)},
  year      = {2025},
  address   = {Nantes, France},
  doi       = {10.1145/3773276.3774299}
}
```

# GPUProgramming-and-ProgrammingModels
This repository contains technical resources about the GPU programming and various programming models like CUDA, OpenACC, Standard Languages, CUDA Fortran, Python, Kokkos, RAJA, and Multi-GPU.

## Introduction to GPU Programming
1. Video: [Introduction to NVIDIA GPU Programming](https://www.youtube.com/watch?v=E7xLxkOm904)
2. Presentation: [Present and Future of Accelerated Computing Programming Approaches](https://www.nvidia.com/en-us/on-demand/session/gtcspring21-s31146/)
3. Video: [ACM Winter School 2019 on HPC IIT Kanpur](https://nptel.ac.in/courses/128/106/128106014/)

## Libraries
1. Documentation: [Mathematics and Communication libraries](https://docs.nvidia.com/hpc-sdk/index.html#math-libraries)
2. Presentation: [How CUDA Math Libraries Can Help You Unleash the Power of the New NVIDIA A100 GPU](https://www.nvidia.com/en-us/on-demand/session/gtcsj20-s21681/)
3. Video: [Recent Developments in NVIDIA Math Library](https://www.nvidia.com/en-us/on-demand/session/gtcspring22-s41491/)
4. Presentation: [High-Performance Sparse Linear Algebra on NVIDIA GPUs with cuSPARSE](https://drive.google.com/file/d/1EgUYtgpqCr51jC9WWUz2W5wqx-k3aS0s/view?usp=sharing)

## ARM
1. Presentation: [Port, Profile, and Tune HPC Applications for Arm-based Supercomputers](https://www.nvidia.com/en-us/on-demand/session/gtcspring22-s41788/)
2. Presentation: [Port, Profile, and Tune HPC Applications for Arm-based Supercomputers](https://www.nvidia.com/en-us/on-demand/session/gtcspring22-s41788/)
3. Web Page: [NVIDIA Arm HPC Developer Kit](https://developer.nvidia.com/arm-hpc-devkit)

## Programming Models
### OpenACC
1. Web Page: [OpenACC.org Resources](http://www.openacc.org/resources)
2. Forum: [OpenACC Slack Channel](http://www.openacc.org/community#slack)
3. Presentation: [Zero to GPU Hero with OpenACC](https://www.nvidia.com/en-us/on-demand/session/gtcspring21-s31816/)
4. Presentation: [Directive-Based Programming with OpenACC](https://www.nvidia.com/en-us/on-demand/session/gtcspring21-cwes1738/)
5. Training Series: [OpenACC Training Series](https://www.olcf.ornl.gov/openacc-training-series/)
6. Videos: [Directive Based GPU Programming](https://www.cscs.ch/publications/tutorials/2018/directive-based-gpu-programming/)
7. GitHub: [OpenACC Training Materials](https://github.com/OpenACC/openacc-training-materials)
8. Docker Container: [OpenACC Training Materials](https://ngc.nvidia.com/catalog/containers/hpc:openacc-training-materials)
9. Online Course: [Fundamentals of Accelerated Computing with OpenACC (Fee-based)](https://courses.nvidia.com/courses/course-v1:DLI+C-AC-03+V1/about)
10. Video: [OpenACC Multi-GPU](https://www.nvidia.com/en-us/on-demand/session/gtcsiliconvalley2019-s9263/)

### Standard Languages
1. Presentation: [Standard Language Parallelism](https://drive.google.com/file/d/1phZGnFnss6iYtJrHYUsKRpwQNB63mLAU/view?usp=sharing)
2. Presentation: [Developing HPC Applications with Standard C++, Fortran, and Python](https://www.nvidia.com/en-us/on-demand/session/gtcfall22-a41087/)
3. Presentation: [The NVIDIA C++ Standard Library](https://www.nvidia.com/en-us/on-demand/session/gtcspring21-s31359/)
4. Presentation: [Shifting through the Gears of GPU Programming: Understanding Performance and Portability Trade-offs](https://www.nvidia.com/en-us/on-demand/session/gtcfall21-a31156/)

### CUDA
1. Training Series: [CUDA Training Series](https://www.olcf.ornl.gov/cuda-training-series/)
2. Presentation: [CUDA on NVIDIA Ampere GPU Architecture: Taking Your Algorithms to the Next Level of Performance](https://www.nvidia.com/en-us/on-demand/session/gtcsj20-s21170/)
3. Presentation: [CUDA: New Features And Beyond](https://www.nvidia.com/en-us/on-demand/session/gtcfall22-a41100/)
4. Presentation: [Developing CUDA Kernels to Push Tensor Cores to the Absolute Limit on NVIDIA A100](https://www.nvidia.com/en-us/on-demand/session/gtcsj20-s21745/)
5. Online Course: [Fundamentals of Accelerated Computing with CUDA C/C++ (Fee-based)](https://courses.nvidia.com/courses/course-v1:DLI+C-AC-01+V1/about)
6. Presentation: [How CUDA Programming Works (GTC Fall '22)](https://www.nvidia.com/en-us/on-demand/session/gtcfall22-a41101/)
7. Presentation: [How CUDA Programming Works (GTC Spring '22)](https://www.nvidia.com/en-us/on-demand/session/gtcspring22-s41487/)
8. Presentation: [CUDA Programming Model for Hopper Architecture](https://www.nvidia.com/en-us/on-demand/session/gtcfall22-a41095/)
9. Presentation: [Optimizing CUDA Applications for NVIDIA Hopper Architecture](https://www.nvidia.com/en-us/on-demand/session/gtcspring22-s41489/)
10. Presentation: [Enabling Hopper-Specific Optimizations in CUDA Applications](https://www.nvidia.com/en-us/on-demand/session/gtcfall22-a41147/)
11. Presentation: [Performance Optimization with Modern CUDA Programming Techniques](https://www.nvidia.com/en-us/on-demand/session/gtcfall21-a31115/)

### CUDA Fortran
1. Documentation: [Programming Guide](https://docs.nvidia.com/hpc-sdk/compilers/cuda-fortran-prog-guide/index.html)

### Python
1. Presentation: [CuPy Overview: NumPy Syntax Computation with Advanced CUDA Features](https://www.nvidia.com/en-us/on-demand/session/gtcsj20-s22471/)
2. Presentation: [Accelerating Python with CUDA](https://www.nvidia.com/en-us/on-demand/session/gtcsj20-cwe21742/)
3. Online Course: [Fundamentals of Accelerated Computing with CUDA Python (Fee-based)](https://courses.nvidia.com/courses/course-v1:DLI+C-AC-02+V1/about)
4. Tutorial: [Python Profiling](https://docs.python.org/3/library/profile.html)
5. Presentation: [GPU Acceleration in Python](https://www.nvidia.com/en-us/on-demand/session/gtcfall20-a21118/)
6. Presentation: [Legate: Scaling the Python Ecosystem](https://www.nvidia.com/en-us/on-demand/session/gtcfall21-a31168/)
7. Presentation: [Scale Python and NumPy Performance with Legate](https://www.nvidia.com/en-us/on-demand/session/gtcfall21-d31036/)
8. Presentation: [GPU Acceleration in Python using CuPy and Numba](https://www.nvidia.com/en-us/on-demand/session/gtcfall21-a31149/)
9. Presentation: [Accelerate Computing with CUDA Python](https://www.nvidia.com/en-us/on-demand/session/gtcfall21-a31138/)

### Kokkos
1. GitHub: [Kokkos Repository](https://github.com/kokkos/kokkos)
2. GitHub: [Kokkos Tutorial](https://github.com/kokkos/kokkos-tutorials)
3. Forum: [Kokkos Slack Channel](https://kokkosteam.slack.com/)
4. Video: [Kokkos: C++ Performance Portability for Production](https://www.youtube.com/watch?v=PjWwith05oA)

### RAJA
1. GitHub: [RAJA Repository](https://github.com/LLNL/RAJA)
2. Video: [A Tutorial Introduction to RAJA](https://www.youtube.com/watch?v=UTtARI-Jsyw)

### Multi-GPU
1. Presentation: [Multi-GPU Programming with MPI (a Magnum IO Session)](https://www.nvidia.com/en-us/on-demand/session/gtcspring22-s41018/)
2. Presentation: [Multi-GPU Programming Models](https://www.nvidia.com/en-us/on-demand/session/gtcfall21-a31140/)
3. Presentation: [A Partitioned Global Address Space Library for Large GPU Clusters](https://www.nvidia.com/en-us/on-demand/session/gtcsj20-s22093/)
4. Presentation: [NVSHMEM: CUDA-Integrated Communication for NVIDIA GPUs (a Magnum IO session)](https://www.nvidia.com/en-us/on-demand/session/gtcspring22-s41044/)
5. Presentation: [NVSHMEM: GPU-Integrated Communication for NVIDIA GPU Clusters](https://www.nvidia.com/en-us/on-demand/session/gtcspring21-s32515/)
6. Presentation: [NCCL: High-Speed Inter-GPU Communication for Large-Scale Training](https://www.nvidia.com/en-us/on-demand/session/gtcspring21-s31880/)
7. GitHub: [Multi-GPU Programming Models](https://github.com/NVIDIA/multi-gpu-programming-models)

### Tools
1. Download: [NVIDIA Nsight™ Systems](https://developer.nvidia.com/gameworksdownload#?dn=nsight-systems-2021-4-1-73)
2. Download: [NVIDIA Nsight Compute](https://developer.nvidia.com/gameworksdownload#?dn=nsight-compute-2021-2-2)
3. Download: [NVIDIA Nsight Graphics](https://developer.nvidia.com/gameworksdownload#?dn=nvidia-nsight-graphics-2021-4)
4. Download: [NVIDIA Nsight Visual Studio Code Edition](https://marketplace.visualstudio.com/items?itemName=NVIDIA.nsight-vscode-edition)
5. Download: [NVIDIA Deep Learning Designer](https://developer.nvidia.com/nsight-dl-designer)
6. Documentation: [Nsight Systems](https://docs.nvidia.com/nsight-systems/index.html)
7. Documentation: [Nsight Compute](https://docs.nvidia.com/nsight-compute/2021.2/index.html)
8. Documentation: [Nsight Graphics](https://developer.nvidia.com/nsight-graphics-documentation-and-support)
9. Documentation: [CUPTI](https://docs.nvidia.com/cuda/cupti/index.html)
10. Documentation: [ NVIDIA Tools Extension SDK (Nvtx)](https://docs.nvidia.com/gameworks/content/gameworkslibrary/nvtx/nvidia_tools_extension_library_nvtx.htm)
11. Documentation: [Compute Sanitizer](https://docs.nvidia.com/cuda/compute-sanitizer/index.html)
12. Documentation: [CUDA-memcheck](https://docs.nvidia.com/cuda/cuda-gdb/index.html)
13. Documentation: [CUDA-GDB](https://docs.nvidia.com/cuda/cuda-gdb/index.html)
14. Documentation: [Nsight Visual Studio Code Edition](https://docs.nvidia.com/nsight-visual-studio-code-edition/)
15. Documentation: [Nsight Deep Learning Designer](https://docs.nvidia.com/nsight-dl-designer/)
16. Video: [NVIDIA Nsight Systems "Profiling GPU Applications with NVIDIA NSight Systems"](https://www.youtube.com/watch?v=kKANP0kL_hk)
17. Video: [NVIDIA Nsight Compute "Introduction to NVIDIA Nsight Compute"](https://www.youtube.com/watch?v=nYSdsJE2zMs)
18. Technical Session: [CUDA is Evolving, and the Latest Developer Tools are Adapting to Keep Up](https://www.nvidia.com/en-us/on-demand/session/gtcspring21-s31747/?playlistId=playList-d59c3dc3-9e5a-404d-8725-4b567f4dfe77)
19. Technical Session: [It's Alive: CUDA in Visual Studio Code](https://www.nvidia.com/en-us/on-demand/session/gtcspring21-s31884/)
20. Technical Session: [Optimizing CUDA Kernels in HPC Simulation and Visualization Codes Using NVIDIA Nsight Compute](https://www.nvidia.com/en-us/on-demand/session/gtcsj20-s21771/)
21. Technical Session: [What the Profiler is Telling You: How to Get the Most Performance out of Your Hardware](https://www.nvidia.com/en-us/on-demand/session/gtcsj20-s22141/)
22. Technical Session: [Performance Tuning CUDA Applications with the Roofline Model](https://www.nvidia.com/en-us/on-demand/session/gtcspring21-s32062/)
23. Technical Session: [Roofline and NVIDIA Ampere GPU Architecture Analysis](https://www.nvidia.com/en-us/on-demand/session/supercomputing2020-sc2022/)
24. GitHub: [Nsight Developer Tools Training](https://github.com/NVIDIA/nsight-training)
25. Technical Blog: [Analysis-Driven Optimization: Analyzing and Improving Performance with NVIDIA Nsight Compute](https://developer.nvidia.com/blog/analysis-driven-optimization-preparing-for-analysis-with-nvidia-nsight-compute-part-1/)
26. Technical Blog: [Custom Application Profile Timelines with NVTX](https://developer.nvidia.com/blog/cuda-pro-tip-generate-custom-application-profile-timelines-nvtx/)
27. Demo: [NVIDIA Nsight-Developer Tools](https://drive.google.com/file/d/1TEPiRpxqZXK2iqzy1uAQoAlrH3u7z-iX/view?usp=sharing)
28. Blog: [Debugging CUDA More Efficiently with NVIDIA Compute Sanitizer](https://developer.nvidia.com/blog/debugging-cuda-more-efficiently-with-nvidia-compute-sanitizer/)
29. Technical Session: [How to Understand and Optimize Shared Memory Accesses using Nsight Compute](https://www.nvidia.com/en-us/on-demand/session/gtcspring22-s41723/)
30. Technical Session: [Requests, Wavefronts, Sectors Metrics: Understanding and Optimizing Memory-Bound Kernels with Nsight Compute](https://www.nvidia.com/en-us/on-demand/session/gtcspring21-s32089/)

### Data Science
1. Web Page: [RAPIDS overview](https://rapids.ai/about.html)
2. Web Page: [RAPIDS-Getting Started (Hands-on labs and other materials)](https://rapids.ai/#getstarted)
3. Forum: [RAPIDS Community](https://rapids.ai/community.html)
4. Presentations: [Collection of RAPIDS Talks](https://www.nvidia.com/en-us/on-demand/search/?facet.mimetype[]=event%20session&layout=list&page=1&q=RAPIDS&sort=relevance)
5. Online Course: [Fundamentals of Accelerated Data Science with RAPIDS(Fee-Based)](https://courses.nvidia.com/courses/course-v1:DLI+C-DS-02+V1/about)
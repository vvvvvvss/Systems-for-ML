# Systems for Machine Learning
On the 13th, 14th and 15th of June, 2025, we had an exceptional experience at the Systems for Machine Learning workshop conducted by the ACM student chapter of IISc Bengaluru. With an overhwelming inflow of Machine Learning and Deep learning models we often forget to learn or understand what's under the hood. This workshop explored exactly that. Nine sessions, one panel discussion, one live demo and one hands-on project across three days and here's what was covered.

## Session 1 : Edge AI for Advanced Automobile In-Cabin Experience
**Keynote speaker - Dr. Amod Anandkumar, HARMAN Automotive**  
This session explored how megatrends like connectivity, autonomy, and electric mobility are reshaping the automotive industry. Focused on in-cabin experiences, the talk highlighted how AI-powered screens, passenger displays, and rearview systems enhance user interaction through continuous updates and upgrades. It introduced the concept of the *Software Defined Vehicle (SDV)*, where applications run over middleware, hardware abstraction layers, and hardware. The session also traced the evolution from distributed controllers to domain and zonal controllers. Challenges like brand consistency and opportunities for AI-driven personalization in multi-screen environments were emphasized.

## Session 2 : Introduction & Overview: Systems in ML
**Speaker - Divij Ghose**  
Session 2 focused on the TensorFlow ecosystem and hardware accelerators for ML. It began with TensorFlow Lite, a lightweight ML framework for mobile and embedded devices, and TensorFlow Serving for production deployment. The session covered transfer learning techniques and model optimization strategies for efficient inference. Specialized hardware like GPUs and TPUs was introduced, emphasizing their parallelism and architecture suited for ML workloads. TPUs, developed by Google, were highlighted for their speed, integration, and limitations like high cost and limited scalability. Key challenges discussed included latency, energy efficiency, and the need for accessible, distributed frameworks for large-scale parallelism.

## Session 3 : Edge Computing - Deploying ML on the Go
**Keynote speakers - Alka and Anusha, Harman** 
Session 3 focuses on model conversion and deployment for edge computing environments. The presentation showcases various deployment format examples including framework-specific tools like LiteRT (TensorFlow Lite) for ARM processors and mobile acceleration, ONNX Runtime for cross-platform deployment, and hardware-specific SDKs like Qualcomm Neural Processing SDK for optimized inference. Additional tools covered include PyTorch ExecutorTorch for mobile deployment, TVM for tensor compilation, and OpenVINO for Intel hardware optimization. The session emphasizes converting trained models into efficient formats suitable for resource-constrained edge devices while maintaining performance across different hardware platforms and architectures. 

## Session 4 : Spiking Neural Networks For Engergy Efficient And Fault Tolerant Neuromorphic Computing
**Keynote speaker - Dr. Gopalakrishnan Srinivasan, IIT Madras**  
Spiking Neural Networks (SNNs) are biologically-inspired computing models that offer energy-efficient and fault-tolerant neuromorphic systems. Unlike traditional ANNs that continuously process data, SNNs generate spikes when neurons are excited, enabling energy efficiency through rate encoding or temporal coding. Their biological design eliminates multipliers, using binary accumulators instead. Key research areas include ANN-to-SNN conversion by replacing activation functions like ReLU with spiking equivalents, and knowledge distillation to transfer complex ANN knowledge to efficient SNNs. Emerging directions encompass federated learning, hardware-aware compression, on-device learning, and adversarial security, aiming to develop robust neuromorphic frameworks for resource-constrained edge devices.

## Session 5 : Software & Profiler Basics for ML 
**Keynote speaker - Sunny Manchanda, DRDO**
Sunny Manchnada (Director of Young Scientist Laboratory, DRDO) on this session of Day 2 of the workshop, started the session by giving real life scenarios of an ML model deployment and letting the audience come up with probable answers. He later asked the simplest questions, like difference between Numpy Array and Pytorch tensors. He taught us the basics of using Pytorch functions the right way and gave a great perspective on how deploying a model is more difficult than it looks and counterintuitive ideas to overcome some problems.

## Session 6 : Case Study & Lab: Accelerating ML Workloads 
**Speaker - Kautuk Astu and Mayank Arya, IISc**
During this session, Mayank and Kautuk helped students understand the architecture and run RESNET-50 CNN model. They explained the forward pass and backward pass process and went on to explain how GPU is better at ML computation workload over CPU. They explained the whys and hows as well and how Python control flow, funtion calls and lack of graph level optimisation could be the cause. They also talked about ways of optimising your model by faster data loading, mixed precision training and compiling the model the right way.

## Session 7 : Foundational Models as OS
**Keynote speaker - Dr. Suparna Bhattacharya, HPE**
Session 7 explores the concept of treating foundational models as operating systems, featuring research on AIOS (LLM Agent Operating System). The presentation covers OS-inspired techniques including context switching across LLM agents, privilege modes for security with hierarchical instruction levels, and circuit breaking mechanisms for alignment and robustness. Key components include the AIOS agent ecosystem with SDK integration, agentic memory (A-Mem) for dynamic long-term memory organization, and drawing inspiration from traditional operating systems to design foundation model systems. The session demonstrates how OS principles can enhance LLM agent management and operational efficiency.

## Session 8 : Distributed ML - Getting Started 
*Speaker - *Dhruv Garg (Georgia Tech)**
Dhruv started the session with making the audience understand how a typical DL model works, followed by what distributed ML means. He expained about the key components in Distributed ML and the current challenges in the same. He went on to talk about the different frameworks like vLLM, DeepSpeed, Inference, Triton, RayServe, etc. and inference strategies like model sharding, batching, smart routing, etc.

## Session 9 : Ensuring Reliability – Scalability & Fault Tolerance
**Keynote speaker - Dibjajyoti Nayak (John Hopkins Research Centre) & Dhaniya Mathews (IBM)**
The session started with Dibyajyoti talking about basics of Federated Learning and about data and model parallelism. He also talked Distributed Systems. He proceeded to talk about scaling ML Systems in real world efficiently. He also explained about Horizontal and Vertical Scaling.
Dhaniya Mathews talked about Reliability and went on to explain the difference between fault, error and failure and their different types. She also talked about common systems failure causes, standby systems, failure handling and disaster recovery plan. 

## Panel Discussion
*Topic: Do We Need More Models or Better Systems for AI Breakthroughs?*
**Moderator: Dr. Kalapriya Kannan (Intuit)**
**Speakers: Dr. Anjaly Parayil (Microsoft), Dr. Sriparna Saha (IIT Patna), Anchal Gupta(NVIDIA), Dr. Sumit Kumar Mandal (IISc Bangalore), Dr. Praveen Jayachandran (IBM Research)**
This was one of the most interesting parts of the workshop. We got a very unique perspective on an array of topics that were brought up during the panel discussion, like- AI based learning, Mastering fundamentals in the AI age, future of AI, sustainibilty, etc. Later the panel even  allowed the audience to ask questions, making the entire session extremely interactive and insightful.

## Live Demo : NVIDIA Autonomous Vehicles demo
**Anchal Gupta**
This was an informative introduction to the NVIDIA Orin platform and its comprehensive capabilities for autonomous systems. The session covered Orin's dual focus areas: perception functionalities including weather detection, object presence recognition, static dynamics, and advanced detection/segmentation capabilities; and planning systems with multiple automation levels from basic netting (L1) through legacy handoffs (L2), combined legacy handoffs with eyes open (L3), eyes closed with brain open (L4), to full brain-off automation (L5). Anchal Gupta demonstrated Orin's versatility in handling complex spatial movements including roll, pitch, and yaw for any free-moving objects, along with sophisticated tracking logic that enables fps-based movement calculations at specified speeds and IoU (Intersection over Union) computations. The technical presentation also covered practical implementation aspects such as release check-outs for simulators and driver SDK integration, showcasing how NVIDIA DriveWorks serves as the comprehensive development framework that leverages Orin's processing power for building robust autonomous vehicle systems.
 
## Hands-on Project
**Topic : Federated Learning**
We tried to learn as much as possible about Federated Learning and understand and solve the problem statement. Our team made a technical report, which we ended up presenting during our presentation.
[Problem Staement Github Repo](https://github.com/roopkathaB/ACM_Workshop_SYSML)
[Our Technical Report](https://docs.google.com/document/d/1Ou7unHEdZxqF6XTA-QaIv2irHst-Bit0wvJlQj02lRQ/edit?usp=sharing)

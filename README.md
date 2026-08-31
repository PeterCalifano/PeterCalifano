# Hello! Here is Pietro Califano - aka "PC"

## Research, software and a bit about me

## Research and development

I'm a PhD student in Aerospace Engineering at **DART Lab, Politecnico di Milano**.

My research primarily focuses on **visual navigation, SLAM, computer vision and multi-sensor state estimation**, with particular interest in factor-graph methods and integrated navigation architectures. I primarily develop these methods for autonomous spacecraft navigation, especially for the exploration and characterization of small bodies and other poorly known environments, where no GNSS is available.

My work spans different parts of the navigation stack, from visual frontends and geometric vision to nonlinear estimation, simulation, validation and algorithm deployment.

Secondary research interests include **event-based vision**, **machine learning for navigation and perception**, and **physically based rendering and sensor simulation**. I usually spend considerable effort developing reusable and well designed software around these topics, beyond just writing papers.

### Research profiles & links

- [Google Scholar](https://scholar.google.com/citations?user=Yvol8yQAAAAJ&hl=en)
- [ORCID](https://orcid.org/0009-0003-6157-3515)
- [LinkedIn](https://www.linkedin.com/in/pietro-califano-a46b7b199/)
- Personal website (WIP)

### Research interests

- Visual navigation, SLAM and structure from motion
- Factor-graph estimation and multi-sensor fusion
- Autonomous spacecraft navigation and exploration
- Event-based vision in SLAM, visual odometry and localization
- Machine learning applied to computer vision and estimation problems
- High fidelity physically based rendering and spectral rendering

---

## Selected software & projects

> Some active research repositories remain private while the corresponding work is in development or publication. Reusable components are released publicly whenever possible, and I am open to sharing work in the context of research collaborations, projects and reviews.

### Computer vision, SLAM & robotics

**[slam-primitives](https://github.com/PeterCalifano/slam-primitives)**

Header-only C++20 library providing reusable data structures and components for visual-SLAM frontends, including feature tracks, bundles and covisibility structures. Designed as an installable, dependency-light package with optional CUDA, ROS 2 and language bindings.

**pyramidal-klt-for-space-nav** (Private repository)

C++20 pyramidal KLT feature-tracking library for visual navigation, with MATLAB-codegen KLT/MSAC kernels, an OpenCV-based tracking pipeline, Python/MATLAB bindings and an optional ROS 2 overlay. It also includes reproducible demos on lunar imagery for end-to-end evaluation of the frontend pipeline.

**space-nav-frontend** (Private repository)

Visual-navigation frontend used to develop and integrate feature tracking, geometric vision and related perception components for the broader spacecraft navigation architecture.

### Spacecraft navigation and estimation

**gtsam-space-nav** (Private repository)

C++20 extension library for spacecraft navigation on top of GTSAM, including dynamics and propagation utilities, process-noise handling, measurement and maneuver factors, and optional Python/MATLAB wrappers.

**[EstimationGears for SpaceNav](https://github.com/PeterCalifano/EstimationGears_for_SpaceNav)**

Collection of reusable MATLAB and C++ building blocks for spacecraft navigation estimators, progressively organized and refactored from research code developed across different projects.

**space-nav-backend** (Private repository)

Navigation backend combining MATLAB algorithms with a standalone C++/CUDA library, wrapper infrastructure and an optional ROS 2 overlay.

**space-nav-loop-closures** (Private repository)

Research repository for loop-closure detection and geometric validation in visual SLAM for small-body navigation.

### Space environment and models simulation

**[SimulationGears for SpaceNav](https://github.com/PeterCalifano/SimulationGears_for_SpaceNav)**

Simulation infrastructure for spacecraft navigation research, combining a MATLAB-based simulation environment with a growing native C++20, CUDA and ROS 2 software stack.

**space-nav-shape-reconstruction** (Private repository)

Research and software for shape reconstruction and mapping of poorly characterized bodies, intended for integration with navigation and SLAM pipelines.

### Event-based vision

**event-based-centroiding** (Private repository)

C++20 and Python project for event-based centroid estimation, with optional CUDA and oneTBB support and installable C++ and Python package structures.

**EventDataGenerationLib** (Private repository)

Utilities and experiments for generating event-camera data and synthetic event streams for algorithm development and evaluation.

**[event-cameras-primitives](https://github.com/PeterCalifano/event-cameras-primitives)** (WIP)

Early-stage C++/CUDA foundation for reusable event-camera processing components. The public repository is still being reorganized from the common project template.

### Machine learning & deployment

**[pyTorchAutoForge](https://github.com/PeterCalifano/pyTorchAutoForge)**

Tools for PyTorch model development, experiment tracking, optimization and deployment. Includes integration with MLflow and Optuna together with ONNX, TensorRT and embedded/Jetson-oriented workflows.

**[torchAutoForge-deploy](https://github.com/PeterCalifano/torchAutoForge-deploy)** (WIP)

Companion deployment library for pyTorchAutoForge, separating inference and runtime integration from the model-development stack. Current work focuses on C++ ONNX Runtime inference, installable CMake packaging and Python/MATLAB binding support.

### Rendering & sensor simulation

**[computer-graphics-primitives](https://github.com/PeterCalifano/computer-graphics-primitives)**

Dependency-light C++20 foundation for reusable computer-graphics, rendering and physically based sensor-simulation components.

**spectra-rt** (Private repository)

GPU-accelerated rendering framework for physically based and radiometric simulation of space scenes, developed with C++, CUDA and NVIDIA OptiX.

### Development tools

**[cpp_cuda_template_project](https://github.com/PeterCalifano/cpp_cuda_template_project)**

Reusable CMake project template for modern C++20 and GPU-accelerated libraries, with optional CUDA, OptiX, TensorRT, Python/MATLAB bindings, testing, documentation, profiling and CI support.

**[AutoCodegenTools4MATLAB](https://github.com/PeterCalifano/AutoCodegenTools4MATLAB)**

Utilities for streamlining MATLAB and Simulink code generation workflows, including automated generation of Interface Control Documents.

I also maintain a number of smaller utilities and templates for MATLAB/C++, code generation, testing and general software workflows. The list above is intentionally selective and reflects the projects I currently maintain or develop most actively. This changes over time with the needs of ongoing research and software work.

---

## A bit about me

Curiosity is my greatest strength. No matter the subject, I approach everything with awe and enthusiasm ✨.

**Motto** 🔥: *“Wonder is anywhere, if you are curious enough to discover it.”*

**Coding-related motto** 🤖: *“Give me a task and I will code a SW library to automate it.”*

## Contacts 📡

- Email: [petercalifano.gs@gmail.com](mailto:petercalifano.gs@gmail.com) or [pietro.califano@polimi.it](mailto:pietro.califano@polimi.it)
- Telegram: @peter_califano
- [LinkedIn](https://www.linkedin.com/in/pietro-califano-a46b7b199/)

Feel free to get in touch if you are interested in my work, curious to learn more, or considering a collaboration! 🚀

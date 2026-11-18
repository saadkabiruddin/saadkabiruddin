# Hi, I'm Saad Kabir Uddin 👋

**Software Engineer | Embedded and Software Security | Cyber-Physical Systems**

I’m a software engineer at The Dhaka Mercantile Co-operative Bank Ltd., where I build and support enterprise financial systems. My work includes backend services, secure access controls, data reconciliation, case management, and integrations.

My technical interests include embedded and wireless firmware security, network and protocol security, cyber-physical and real-time systems, and program analysis.

## Research Interests

- Embedded and wireless firmware security
- Network and protocol security
- Cyber-physical and real-time systems security
- Program analysis

## What I Work On

- Enterprise banking applications and workflows
- Backend services and REST APIs
- Authentication, authorization, and access control
- Reconciliation and data processing
- Case management and system integration
- Embedded security experiments and protocol defenses
- Static analysis for application security

## Technical Skills

**Systems Programming:** C, C++, Rust  
**Programming Languages:** C#, Python, TypeScript, JavaScript  
**Embedded:** ESP-IDF, FreeRTOS, MQTT, Wokwi  
**Software and Data:** ASP.NET Core, FastAPI, Angular, EF Core, CQRS, JWT, SQL Server, PostgreSQL  
**Tools and Platforms:** Git, Linux, AWS  
**Machine Learning:** PyTorch, OpenCV, scikit-learn, Albumentations, Matplotlib, Pandas, NumPy

## Selected Projects

### Replay Lock — Replay Protection as a Protocol-State Problem Across Restarts

Compared unprotected, RAM-counter, and persistent-counter receivers under replay, modification, and restart scenarios. Identified that a RAM-held replay counter resets on restart, allowing previously captured messages to be accepted again when the receiver returns to an earlier state.

- Only persistent counters rejected replay after restart in all 20 host trials.
- Python and ESP32 firmware agreed on all 49 test inputs.
- Hardware validation is pending.

### LoopShield — Sensor Spoofing Detection for Networked Control Systems

Built an MQTT attack proxy that injects bias, ramp, and forged messages into a simulated control loop, alongside a C# temperature-control simulation and local MQTT broker.

- Implemented portable C defenses using HMAC authentication, replay protection, a model observer, and CUSUM.
- Evaluated four defense configurations across seven scenarios.
- Combined defenses detected bias, ramp, and forgery within 0.2 seconds in preliminary host-based trials.

### ESP32 FreeRTOS Priority Inversion Experiment

Built a C and ESP-IDF experiment in Wokwi to study priority inversion under task interference.

- Mutex priority inheritance reduced lock wait from 339.3 ms to 89.7 ms.
- Deadline misses dropped from 95/95 to 0/95 in the simulation.
- Hardware validation is pending.

### Roslyn Security Analyzer

Built a C# Roslyn analyzer for ASP.NET Core Web APIs to detect SQL command text assembled through string concatenation or interpolation.

- Detected 2 of 2 planted SQL injection cases.
- Produced no warnings on three parameterized-query controls in a banking API benchmark.

### LLM Agent Security Gateway — AgentGuard

Built an ASP.NET Core gateway for an Ollama banking agent, with role, scope, and provenance checks, deny-by-default policies, and audit logging.

- In a simulated benchmark, blocked 8 of 8 unauthorized calls, compared with 3 of 8 using role-only checks.
- Allowed all 3 legitimate calls.

### ML Backdoor Security Lab

Reproduced BadNets-style poisoning on MNIST and evaluated fine-pruning as a mitigation.

- Baseline results were 100% attack success and 99.00% clean accuracy.
- Fine-pruning 90% of the final convolutional layer reduced attack success to 50.06%, with 97.90% clean accuracy.

## Research Experience

### Undergraduate Researcher — Universiti Teknologi Malaysia  
**September 2022 – September 2023**

Researched iris recognition in less cooperative environments, including blur, off-angle gaze, uneven lighting, occlusion, and half-open eyes.

- Implemented a 1.9-million-parameter U-Net for iris segmentation using PyTorch.
- Worked with the CASIA-Iris-Degradation database, Albumentations, and OpenCV.
- Evaluated segmentation using IoU, loss, and visual comparisons.

## Publications

- Uddin, Saad Kabir, and Sim Hiew Moi. “Improving the Methods of Iris Recognition in Less Cooperative Environments.” *UTM Computing Proceedings: Innovations in Computing Technology and Applications*, vol. 6, 2024, pp. 71–76.
- Yong, Pang Yee, Saad Kabir Uddin, and Sim Hiew Moi. “Enhancing Iris Recognition in Less Cooperative Environments.” In *Frontiers in Image Processing and Computer Vision*, chapter 4, pp. 47–60. UTM Press, 2025.

## Professional Experience

### Software Engineer (Senior Technical Officer) — The Dhaka Mercantile Co-operative Bank Ltd.  
**November 2024 – Present**

Work on enterprise banking applications, including secure access control, case management, reconciliation, core banking modules, and internal service integrations.

### Software Developer Intern — BigLedger Sdn Bhd (Cloud App Software Solutions)  
**September 2023 – February 2024**

Developed ERP functionality with Java, Spring Boot, and Angular. Investigated PostgreSQL data issues, supported AWS operations, and troubleshot production problems.

## Awards and Achievements

- Dean’s List, Semester II 2019/2020 and Semester I 2022/2023 — School of Computing, Universiti Teknologi Malaysia.
- International Assessments for Schools, Science — High Distinction, Class 9, 2013.
- International Assessments for Schools, Mathematics — Distinction, Class 9, 2013.
- 3rd Place, Rubik’s Cube Competition — Citycell–SGHS Knowledge Fiesta 2014.
- Medalist in 400 m relay and football competitions.

## Links

- [Portfolio](https://saadkabiruddin.github.io/)
- [GitHub](https://github.com/saadkabiruddin)
- [LinkedIn](https://www.linkedin.com/in/saadkabiruddin/)
- [Google Scholar](https://scholar.google.com/citations?user=wttp814AAAAJ&hl=en&authuser=1)
- [ORCID](https://orcid.org/0009-0005-3966-5020)

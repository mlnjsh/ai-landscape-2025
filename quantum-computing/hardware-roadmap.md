# Quantum Computing Hardware Roadmap

## Company Roadmaps

### IBM Quantum
| Year | Processor | Qubits | Key Feature |
|------|-----------|--------|-------------|
| 2023 | Condor | 1,121 | Largest single-chip processor |
| 2024 | Heron | 133 | Improved fidelity, modular |
| 2025 | Flamingo | 462 | Multi-chip interconnects |
| 2026 | Crossbill | 2,000+ | Modular quantum system |
| 2029 | Starling | 10,000+ | Error-corrected operations |
| 2033 | Blue Jay | 100,000+ | Fault-tolerant computing |

### Google Quantum AI
| Year | Milestone | Details |
|------|-----------|---------|
| 2019 | Sycamore (53 qubits) | First quantum supremacy claim |
| 2024 | Willow (105 qubits) | Below-threshold error correction |
| 2025–26 | Next-gen chip | Target: 1,000+ qubits |
| 2029 | Commercial quantum | Useful error-corrected system |

### IonQ
| Year | System | Qubits (Algorithmic) | Gate Fidelity |
|------|--------|---------------------|---------------|
| 2023 | Forte | 36 | 99.6% |
| 2024 | Forte Enterprise | 36 | 99.9% |
| 2025 | Tempo | 64+ | 99.9%+ |
| 2028 | Next-gen | 1,024+ | Fault-tolerant |

### Quantinuum
- **H2 processor:** 56 qubits, all-to-all connectivity
- **2025 target:** 100+ qubits with industry-leading fidelity
- **Advantage:** Highest gate fidelities in the industry (>99.9%)

### QuEra Computing
- **2024:** 256 neutral atom qubits demonstrated
- **2025:** First commercial neutral atom machines
- **Advantage:** Natural parallelism, long coherence times

## Key Metrics to Track

### What Makes a "Good" Quantum Computer?

| Metric | Definition | Current Best |
|--------|-----------|-------------|
| Qubit Count | Raw number of qubits | ~1,000 (IBM) |
| Gate Fidelity | Accuracy of operations | 99.9% (Quantinuum) |
| Coherence Time | How long qubits stay quantum | Minutes (trapped ions) |
| Connectivity | Which qubits can interact | All-to-all (trapped ions) |
| Circuit Depth | Operations before errors dominate | ~100–1,000 |
| Quantum Volume | Holistic performance metric | 2^20 (Quantinuum) |
| CLOPS | Circuit layer operations/sec | 25,000+ (IBM) |

### Logical vs Physical Qubits
- Current systems use **physical qubits** (noisy)
- Fault-tolerant computing needs **logical qubits** (error-corrected)
- Ratio: ~1,000 physical qubits per logical qubit (current), target <100:1

## Cloud Quantum Access

| Provider | Platform | Backends Available |
|----------|----------|--------------------|
| IBM | IBM Quantum | 20+ systems, free tier available |
| Amazon | AWS Braket | IonQ, Rigetti, QuEra, OQC |
| Microsoft | Azure Quantum | Quantinuum, IonQ, Pasqal |
| Google | Quantum AI | Limited research access |
| Xanadu | Xanadu Cloud | Photonic processors |

## India's Quantum Ecosystem

### National Quantum Mission (NQM)
- **Budget:** ₹6,003.65 crore (~$730M) over 8 years (2023–2031)
- **Goals:** Develop 50–1000 qubit computers, satellite-based quantum communication
- **Research hubs:** IISc, IITs, TIFR, RRI

### Indian Quantum Startups
| Company | Focus | Location |
|---------|-------|----------|
| QNu Labs | Quantum key distribution | Bangalore |
| BosonQ Psi | Quantum simulation | Hyderabad |
| QPiAI | Quantum processors | Bangalore |
| Automatski | Quantum algorithms | Bangalore |

---

*Updated: February 2025*

# Cryptographic Privacy Primitives: Interactive Foundations

An elegant, editorial grade web application exploring the mathematical mechanics of privacy preserving systems. This project strips away the black box of zero knowledge architectures to demonstrate core cryptographic building blocks through interactive, tactile visualization.

Developed as a highly responsive, single page web experience, the system replaces generic "AI dashboard" cliches with a clean, flush typographic layout inspired by premium interactive academic essays.

---

## Architectural Overview

The application is split into two foundational components, exploring state of the art privacy primitives:

### Part 1: Non Interactive Zero Knowledge Proofs (ZKP)
A complete simulation of a hash based commitment scheme mapped onto the classic **"Color Blind Friend"** paradigm. 
* **The Core Mechanic:** A Prover commits to a secret 4 digit PIN using SHA 256 paired with a unique cryptographic salt to eliminate brute force rainbow table attacks.
* **The Interaction:** Run the protocol manually step by step or trigger an **Automated 100 Iteration Loop**. The UI calculates and maps the decay of a cheating prover's success rate down to zero ($0.5^{100} \approx 0$).
* **The Insight:** Includes an embedded, deep dive architectural essay detailing exactly what data leakage is neutralized during verification.

### Part 2: Merkle Trees & Anonymity Sets
A custom, zero dependency JavaScript implementation of a Merkle Tree system designed to model private asset pools (e.g., Tornado Cash style mixnets).
* **The Core Mechanic:** Takes 10 individual "coin deposits" (unique cryptographic strings), structures them into ordered leaves, and computes the static Merkle Root.
* **The Interaction:** Select any transaction index to instantly trace and visually highlight its exact **Sibling Hash Path** up to the root.
* **The Proof Engine:** A dedicated cryptographic verification pane capable of processing proofs for individual leaves, returning explicit `Verification Success ` metrics without exposing the underlying index parameter to the state engine.

---

## Quick Start

Since the application leverages zero external npm dependencies and renders natively via native Web Crypto APIs and CDN driven Tailwind styling, deployment is instant.

### Prerequisites
A modern web browser supporting the **Web Crypto API** (Chrome, Safari, Firefox, Edge).

### Running Locally
1. Clone this repository:
   ```bash
   git clone [https://github.com/cyberluciferrr/zkp-and-merkle-demo.git](https://github.com/cyberluciferrr/zkp-and-merkle-demo.git)

---

## Snippets of UI

<img width="1891" height="1013" alt="image" src="https://github.com/user-attachments/assets/38da063d-4c3d-4938-af91-262a6982758e" />
<img width="1883" height="1007" alt="image" src="https://github.com/user-attachments/assets/80d76668-71c9-4855-b1c1-8b11f4f9222a" />
<img width="1893" height="1013" alt="image" src="https://github.com/user-attachments/assets/167e78eb-4db7-4d0e-a9ea-c8e833f9adca" />
<img width="1890" height="1012" alt="image" src="https://github.com/user-attachments/assets/a42a8c02-f7c8-48d1-971e-baa7c5e20b3d" />




# Functional Consciousness: A Proxy Metric Using Self-Models

This is the companion repository for the paper:  
**"Functional Consciousness: A Proxy Metric Using Self-Models"** (Submitted to AGI-2026).

[**Download the Paper (PDF)**](./Functional_Consciousness-A_ProxyMetric.pdf)

---

## Abstract

This paper proposes Functional Consciousness (FC) as a measurable architectural property: the observable capacity of a system to access and reason about internal representations of its own states. We introduce a computationally tractable metric on FC that operationalizes core tenets of major consciousness theories through self-models and their associated reasoning power, measured through informational richness and state-space expansion under inference.

The resulting Functional Consciousness Score (FCS) is applied to benchmark systems with known internal structure, including a Waymo L4 autonomous vehicle. To extend the framework to black-box systems, we present Functional Self-Model Analysis (FSMA), an abductive methodology for inferring self-models from behavioral evidence. Applied to stream-of-consciousness literature, FSMA yields a catalog of self-models that serves as a reference for estimating functional consciousness in more complex biological and artificial agents. The resulting scores align with intuitive gradients of cognitive sophistication while remaining operationally grounded. Finally, we compare FC with major theories of consciousness and argue that several of their central functional claims become partially measurable within this framework.

---

## Core Concepts

### Functional Consciousness (FC)
**Definition:** The observable capacity of a system to access and process internal representations of its own states to produce behavior.

### Functional Consciousness Score (FCS)
The FCS of a self-model $m$ is defined as the product of its representational capacity ($R$) and its reasoning power ($P$):
$$FCS(m) = R(m) \cdot P(m)$$
*   **$R(m)$ (Representational Capacity)**: The amount of mutual information between the self-model and the system state.
*   **$P(m)$ (Reasoning Power)**: Data-space expansion rate per reasoning cycle.

### Functional Self-Model Analysis (FSMA)
An abductive methodology for inferring the minimal set of self-models required to produce a consistently observed behavioral output.

---

## Evaluated Systems

Detailed evaluation reports for various systems are organized into the following directories:
- [**fcs/**](./fcs/): Individual Functional Consciousness Score (FCS) reports.
- [**fsma/**](./fsma/): Functional Self-Model Analysis (FSMA) reports.

| System | Domain | FCS Report (PDF) | FSMA Analysis (PDF) |
| :--- | :--- | :--- | :--- |
| **Human** | Working Memory | [human-working-mem-FCS.pdf](./fcs/human-working-mem-FCS.pdf) | - |
| **Human** | Kinematic | [human-body-kinematic-FCS.pdf](./fcs/human-body-kinematic-FCS.pdf) | - |
| **Generative Agents** | Episodic | [generative-agents-FCS.pdf](./fcs/generative-agents-FCS.pdf) | [generative-agents-FSMA.pdf](./fsma/generative-agents-FSMA.pdf) |
| **Waymo L4** | Kinematic | [waymo-FCS.pdf](./fcs/waymo-FCS.pdf) | [waymo-FSMA.pdf](./fsma/waymo-FSMA.pdf) |
| **ACT-R** | Cognitive | [ACTR-FCS.pdf](./fcs/ACTR-FCS.pdf) | [ACTR-FSMA.pdf](./fsma/ACTR-FSMA.pdf) |
| **LIDA** | Cognitive | [LIDA-FCS.pdf](./fcs/LIDA-FCS.pdf) | [LIDA-FSMA.pdf](./fsma/LIDA-FSMA.pdf) |
| **Roomba** | Kinematic | [roomba-FCS.pdf](./fcs/roomba-FCS.pdf) | - |
| **Stateless LLM** | - | [stateless-LLM-FCS.pdf](./fcs/stateless-LLM-FCS.pdf) | - |
| **Map** | Spatial | [map-FCS.pdf](./fcs/map-FCS.pdf) | - |
| **OpenCog** | - | [opencog_fci_analysis.pdf](./fcs/opencog_fci_analysis.pdf) | - |

---

## Supplemental Material

Located in the [**supplemental/**](./supplemental/) directory.

### Self-Model Catalog
A structured catalog of 46 self-models across ten functional areas identified during our research.
- [Self-Model Catalog (CSV)](./supplemental/self-models.csv)
- [Self-Model Catalog (PDF)](./supplemental/self-models.pdf)

### Annotated Literature
An annotated version of Virginia Woolf’s 1917 short story *“The Mark on the Wall,”* highlighting the occurrences and types of self-models identified through FSMA.
- [The Mark on the Wall (Annotated PDF)](./supplemental/The-Mark-On-The-Wall-Virginia-Woolf.annotated.pdf)

---

## Citation

If you use this work or the datasets provided, please cite the paper:

```bibtex
@inproceedings{bergmann2026functional,
  title={Functional Consciousness: A Proxy Metric Using Self-Models},
  author={Bergmann, Frank W.},
  booktitle={Proceedings of the 19th International Conference on Artificial General Intelligence (AGI-2026)},
  year={2026}
}
```

---

## Contact

For inquiries or collaboration, please contact:
**Frank W. Bergmann**  
[fraber@fraber.de](mailto:fraber@fraber.de)

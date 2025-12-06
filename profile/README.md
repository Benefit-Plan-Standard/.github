# 🏛️ Benefit Plan Standard  
### An open, vendor-neutral data standard for normalizing and exchanging U.S. health insurance benefit plan information.

<p align="left">
  <a href="https://benefitplanstandard.org">
    <img src="https://img.shields.io/badge/Documentation-Live-blue?style=flat-square" />
  </a>
  <a href="https://github.com/Benefit-Plan-Standard/benefit-plan-schema">
    <img src="https://img.shields.io/badge/Schema-v1.0.0-green?style=flat-square" />
  </a>
  <img src="https://img.shields.io/badge/Status-Active_Development-purple?style=flat-square" />
</p>

---

## 📘 What Is the Benefit Plan Standard?

The **Benefit Plan Standard (BPS)** is a unified, open, machine-readable schema for representing U.S. health insurance benefit plan information across carriers.  
It provides:

- A **canonical JSON schema** for health plan normalization  
- Standard terminology and field definitions  
- Carrier crosswalk tables  
- Compliance & validation guidance (schema-level only)  
- Extensible modules (pharmacy, behavioral health, dental/vision, supplemental)  
- A structure designed for interoperability, analytics, and automation  

**Goal:**  
A single, consistent representation of health plan benefits — independent of carrier formatting, terminology, or document structure.

---

## 📂 Repositories

### 🔹 benefit-plan-docs  
Documentation site containing:
- Specification overview  
- Field definitions  
- Versioning & governance  
- Crosswalk tables  
- Compliance guidelines  
- Examples  
- Roadmap  

📘 Live Documentation: https://benefitplanstandard.org  
Repo: https://github.com/Benefit-Plan-Standard/benefit-plan-docs

---

### 🔹 benefit-plan-schema  
The official JSON Schema for the Benefit Plan Standard (v1.0.0), including:
- Core schema  
- Modules  
- Example normalized plans  
- Versioning rules  
- Schema change process  

Repo: https://github.com/Benefit-Plan-Standard/benefit-plan-schema

---

## 📐 What This Organization Provides

This GitHub organization maintains the **open, vendor-neutral artifacts** of the standard:

- 📄 JSON Schema (v1.0.0 + future modules)  
- 🧭 Carrier crosswalk mappings  
- 📚 Documentation & governance  
- ✔ Compliance expectations relevant to the schema  
- 🗺 Roadmap for the evolution of the standard  

These resources enable:
- Carriers  
- Brokers & TPAs  
- Health tech vendors  
- Researchers  
- Regulators  

…to align around a shared, interoperable model.

---

## 🔒 What Is *Not* Included (Proprietary)

To maintain neutrality, **this organization does not** include:

- PDF/SBC/EOC ingestion pipelines  
- AI extraction tooling  
- Proprietary validation logic  
- Confidence scoring engines  
- Carrier-specific rule packs  
- Commercial APIs  
- Customer dashboards or authentication systems  

These are **not** part of the open standard and remain private.

A separate project — **[HealthPlanAPI.com](https://HealthPlanAPI.com)** — implements ingestion and validation pipelines *using* the standard.  
It is an **implementer**, not the owner of this organization or standard.

This preserves neutrality while demonstrating real-world adoption.

---

## 🌱 Why This Standard Exists

Carriers describe plans differently — cost-sharing, accumulators, network tiers, benefits, and conditions vary wildly.  
This fragmentation makes it difficult to:

- Compare health plans  
- Build transparency tools  
- Automate underwriting  
- Train ML/AI models  
- Normalize data across carriers  
- Streamline broker and TPA workflows  

The Benefit Plan Standard addresses this by creating a stable, unified representation — similar to how:

- **FHIR** standardized clinical data  
- **EDI** standardized claims  
- **HL7** standardized healthcare messaging  

BPS is the foundation for **interoperable benefit plan data**.

---

## 🧭 Governance

The standard follows a transparent governance model:

- Public roadmap  
- Structured versioning  
- RFC process for changes  
- Backwards-compatibility rules  
- Industry collaboration  
- Community participation  

Governance documentation:  
https://benefitplanstandard.org/docs/governance/governance-overview

---

## 🤝 Contributing

We welcome participation from:

- Carriers  
- Brokers / TPAs  
- Healthcare technology vendors  
- Data engineers & architects  
- Researchers  
- Standards organizations  

Discussion Board:  
https://github.com/Benefit-Plan-Standard/benefit-plan-docs/discussions

Issues (schema):  
https://github.com/Benefit-Plan-Standard/benefit-plan-schema/issues

Contribution guidelines:  
https://benefitplanstandard.org/docs/compliance/compliance-overview

---

## 🗺 Roadmap Highlights (Public Standard Only)

- v1.1.0 modules:
  - Pharmacy  
  - Behavioral Health  
  - Supplemental Benefits  
- Expanded carrier crosswalks  
- Improved consistency rules  
- More examples + test plans  
- Schema refinement  

Full Roadmap:  
https://benefitplanstandard.org/docs/specification/roadmap-v1.1

---

## 🌐 Related Project (Private & Independent)

**[HealthPlanAPI.com](https://HealthPlanAPI.com)**  
A commercial implementation of the standard providing ingestion, validation, and API distribution of normalized benefit plans.

It operates **separately** and does **not** influence the neutrality of the open standard.

---

## 📬 Contact

📧 contact@benefitplanstandard.org  
🔗 https://benefitplanstandard.org  

---

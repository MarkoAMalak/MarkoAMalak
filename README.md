## Marko A. Malak

M.Sc. student, School of Computing, Queen's University. I work on machine learning for security:
anomaly detection for industrial control systems and cloud logs, and on making ML results honest
and reproducible, then shipping them as hardened, tested services.

### Selected projects

| Project | What it is | Stack |
|---|---|---|
| [**ics-guardian**](https://github.com/MarkoAMalak/ics-guardian) | Unsupervised process + network anomaly detection for water-chlorination ICS (SWaT/WADI), served as a hardened cloud-native service. Fusion lifts PR-AUC from 0.39 to 0.47 on the SWaT A6 campaign. | PyTorch · FastAPI · Kubernetes/Helm · Prometheus · 6-gate DevSecOps CI |
| [**apple-leaf-disease-framework**](https://github.com/MarkoAMalak/apple-leaf-disease-framework) | Leakage-free deep-learning framework for apple-leaf disease detection with honest cross-dataset evaluation, YOLO11 detection and domain adaptation. Archived on Zenodo ([DOI](https://doi.org/10.5281/zenodo.21336556)). | PyTorch · YOLO11 · DANN |
| [**cloud-threat-detection**](https://github.com/MarkoAMalak/cloud-threat-detection) | Behavior-based threat detection on AWS CloudTrail logs with refined, human-focused alerts and an investigation dashboard. | scikit-learn · Streamlit · Docker · Trivy |
| [**cloud-llm-deployment-cisc886**](https://github.com/MarkoAMalak/cloud-llm-deployment-cisc886) | End-to-end LLM pipeline on AWS: PySpark on EMR, QLoRA fine-tuning of Llama 3.2 1B, Terraform infrastructure, Ollama + OpenWebUI serving. | AWS · Terraform · PySpark · QLoRA |
| [**infosec-rag-chatbot**](https://github.com/MarkoAMalak/infosec-rag-chatbot) | Retrieval-augmented Q&A over a curated information-security knowledge base. | FAISS · Sentence-Transformers · FLAN-T5 · Gradio |
| [**ADDC-pytorch**](https://github.com/MarkoAMalak/ADDC-pytorch) | Apple-leaf disease segmentation, classification and severity estimation in one pipeline. | PyTorch · U-Net · DeepLabV3+ |

### Focus areas

- Anomaly detection for OT/ICS and cloud security
- Reproducible ML evaluation (leakage-free splits, threshold-free metrics)
- DevSecOps: CI security gates, container hardening, Kubernetes

### Contact

Queen's University · [GitHub](https://github.com/MarkoAMalak)

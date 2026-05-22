# ct_scan_clinical_reports_without_findings_medical_nlp
**Dataset Description:**


This dataset is a large-scale collection of **CT (Computed Tomography) scan reports without clinical findings**, designed to support the development of robust medical imaging and AI systems focused on normal baseline learning.

The dataset captures authentic imaging characteristics such as scanner variability, acquisition protocols, and patient positioning, along with structured and unstructured clinical narratives. This makes it highly valuable for building accurate, scalable, and production-ready AI systems.
Additionally, this dataset can be used in pipelines for **Supervised Fine-Tuning (SFT) and Reinforcement Learning with Human Feedback (RLHF) workflows**, especially for enhancing model sensitivity and calibration.


![Screenshot 2026-04-13 152720](https://cdn-uploads.huggingface.co/production/uploads/693ab313ff1770594f99afee/6fpMz5q-jq14aMFikl9Un.png)

**Key Use Cases**

    -Baseline learning for diagnostic AI models
    -False positive reduction
    -Medical image segmentation 
    -Radiology report generation 
    -Model validation and calibration

**Dataset Specification**

    -Modality: CT (Computed Tomography)
    -Type: Medical images without clinical findings 
    -Data Source: Clinical CT scan reports
    -Body Regions: Brain, Chest, Abdomen, Spine, etc.
    -Data Nature: Real-world clinical data
    -Patients: 14,264
    -Images: 2,602,829

**Value of This Dataset**

    -Enables learning of normal anatomical structures
    -Improves model specificity and reduces false alarms
    -Supports binary and multi-class classification tasks
    -Essential for anomaly detection systems
    -Helps build clinically safe and reliable AI solutions
    -Supports real-world healthcare deployment

**Basic JSON Schema**
```json
{
  "patient_id": "string",
  "image": "image",
  "series_number": "string",
  "study_uid": "string",
  "series_uid": "string",
  "instance_number": "int32",
}
```
**Data Creation**

  Procured through formal agreements and generated in the ordinary course of business.

**Considerations**

  This dataset is provided for research and educational purposes only. It contains only sample data. For access to the full dataset and enterprise licensing options, please visit our website [InfoBay AI](https://infobay.ai/) or contact us directly.

    -Ph: (91) 8303174762
    -Email: datareq@infobay.ai

# NeuroLog — Symptom Detective (v1.0-alpha)

A local-first digital phenotyping tool for tracking mechanical neurological triggers (IIH/Chiari) and clinical resilience metrics. Developed for patient-led research. Copyright 2026 PJZB.

## Core Features

### 1. Clinical Instruments (Scales Tab)
NeuroLog incorporates a suite of validated clinical scales to provide a multi-dimensional view of neurological health and patient resilience:

* **HIT-6 (Headache Impact Test):** Measures functional impact on daily life.
* **PASS-20 (Pain Anxiety Symptoms Scale):** Assesses pain-related anxiety and cognitive factors across four subscales.
* **BPI-SF (Brief Pain Inventory):** Assesses pain severity and interference with activities.
* **PCS-12 (Physical Component Summary):** Monitors overall physical functional status.

**The Resilience Gap:** The application calculates a "Resilience Gap" by comparing objective **functional impact** (HIT-6/BPI-SF) against **psychological magnification** (PASS-20/PCS-12) to identify where perceived pain may be out of sync with physical triggers.

### 2. Digital Phenotyping (Synapse & Tempo)
The app uses two interactive indicators to track adherence and safety:

* **Synapse (The Neuron):** Tracks **preventive medication** adherence.
    * **Evolution:** Synapse gains XP and evolves (Neuron → Spark → Pulse → Signal → Guardian) based on consistency.
    * **Mood:** Its state reflects the last 7 days of adherence and symptom stability.
* **Tempo (The Monitor):** Tracks **abortive medication** frequency.
    * **MOH Prevention:** Monitors usage within a monthly cycle (20th to 20th) to prevent Medication Overuse Headache.
    * **Visual Warning:** The "mercury" rises as you approach your monthly limit, "overheating" if limits are exceeded.

## Extensibility & Iteration

While optimized for mechanical neurological triggers (IIH/Chiari), the architecture is designed to be iterated for any chronic condition. By adjusting weighted attribution models and clinical scales, it can be customized for:
* **Autoimmune Disorders:** Correlating triggers with inflammatory markers.
* **Vestibular Disorders:** Tracking movement-based triggers and balance.
* **Mental Health:** Monitoring therapeutic efficacy through the Resilience Gap logic.

---
**DISCLAIMER:** NeuroLog is a personal data-tracking instrument and not a medical device. It is not intended for diagnosis or treatment. Always review data with a medical professional.

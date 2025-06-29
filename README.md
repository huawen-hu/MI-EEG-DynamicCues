# MI-EEG-DynamicCues
# 📊 Dataset Description

This dataset accompanies the MICCAI 2025 paper:

> *"Improving Motor Imagery EEG Signal Quality with Dynamic Visual Cues: An Innovative Paradigm and Dataset"*

---

## 👤 Participants

- **Subjects**: 5 healthy participants
- **Paradigm**: Four-class Motor Imagery (MI) tasks:
  - Left Hand
  - Right Hand
  - Both Hands
  - Both Feet

Each subject performs tasks under both **Dynamic Visual Cueing (DVC)** and **Static Cueing (SC)** paradigms.

---

## 🧪 Experimental Protocol

- **Sessions**: 2 per subject
  - One in the **morning**
  - One in the **evening**
  - Sessions are separated by **one week**
- **Runs**: 6 runs per session
- **Trials**: 48 trials per run
- **Paradigms**: Each run belongs to either DVC or SC condition

---

## 🧠 EEG Recording Details

- **Device**: Biosemi ActiveTwo
- **Channels**: 64 EEG electrodes
- **Montage**: International 10-10 system
- **Sampling Rate**: 2048 Hz
- **Format**: `.bdf` / `.mat` (depending on release)

---

## ✅ Ethics Approval

- The study protocol was reviewed and approved by the institutional ethics committee.
- **Approval Number**: 202402041
- The experiment was conducted in accordance with the Declaration of Helsinki.

---

## 📂 Data Structure

```bash
data/
├── subject01/
│   ├── session1/
│   │   ├── run1_dynamic.mat
│   │   ├── run2_static.mat
│   │   └── ...
│   └── session2/
│       ├── run1_dynamic.mat
│       └── ...
├── subject02/
└── ...
```

## 📥 Download

We will provide a download link soon after anonymization and hosting.

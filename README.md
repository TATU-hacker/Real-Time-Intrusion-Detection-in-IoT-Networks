# Real-time intrusion detection in IoT networks: A hybrid framework of offline ML and online DL

**Highlights**

• A label-free RF–LSTM IDS is developed for streaming IoT traffic.

• Drift is monitored using Mahalanobis distance and Page–Hinkley testing.

• Entropy-based switching selects between offline and online predictions.

• Confidence-gated pseudo-labels enable controlled LSTM adaptation.

• The framework achieves strong detection with real-time performance.

#
Internet of Things (IoT) intrusion detection must adapt to evolving traffic without relying on immediate ground-truth labels. This study proposes a label-free hybrid intrusion detection framework that integrates an offline RF teacher with an online Long Short-Term Memory student. The framework combines probability calibration, Mahalanobis-distance-based distribution monitoring, Page–Hinkley drift detection, entropy-based model selection, and confidence-gated pseudo-label adaptation. A leakage-resistant three-way protocol separates offline training, validation-time adaptation, and held-out testing, with labels used only for post-hoc evaluation. Experiments on CICIoMT2024 show that the proposed framework achieves 0.9893 accuracy, 0.8823 macro F1, and 0.9889 weighted F1 on the held-out multiclass stream. Under binary Benign-versus-Attack evaluation, it attains 0.9937 accuracy and 0.9257 macro F1, while attack recall reaches 0.9987. The framework also maintains strong ranking performance, low calibration error, and real-time processing, with a mean latency of 12.97 ms per sample and throughput of 77.13 samples per second. These results show that a strong offline detector can be extended with controlled online adaptation and label-free drift awareness while preserving high operational performance for gateway- and edge-level IoT monitoring.

https://www.sciencedirect.com/science/article/pii/S2542660526001691?via%3Dihub

Dusmurod Kilichev, Wooseong Kim,
Real-time intrusion detection in IoT networks: A hybrid framework of offline ML and online DL,
Internet of Things,
Volume 39,
2026,
102039,
ISSN 2542-6605,
https://doi.org/10.1016/j.iot.2026.102039.
(https://www.sciencedirect.com/science/article/pii/S2542660526001691)

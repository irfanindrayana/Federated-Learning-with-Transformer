# Federated-Learning-with-Transformer
Proyek ini bertujuan untuk mengembangkan kerangka kerja deteksi ransomware yang menjaga privasi menggunakan paradigma Federated Learning (FL) dan membandingkan efektivitas tiga arsitektur Transformer yang berbeda.

## Fokus Penelitian
Evaluasi akurasi deteksi dan efisiensi komunikasi dari model berbasis Transformer dalam lingkungan terdistribusi (Cross-Silo).

## Model Transformer
1. Informer
2. Time Series Transformer
3. Tabular Transformer

## Dataset
Menggunakan dataset Malware Memory Analysis (CIC-MalMem-2022)

## Hasil Penelitian
### Performa
| Arsitektur Model | Average Accuracy (%) | Average F1-Score (%) | Average Loss |
| :--- | :--- | :--- | :--- |
| **Informer** | 90,72% | 88,51% | 0,2132 |
| **Time Series Transformer** | 89,69% | 85,69% | 0,2436 |
| **Tabular Transformer** | 89,51% | 85,71% | 0,3224 |
Note: Penggunaan titik dan koma mengikuti aturan Indonesia

### Efisiensi
| Metrik Efisiensi | Informer | Tabular Transformer | Time Series Transformer |
| :--- | :--- | :--- | :--- |
| **Total Parameters** | 826.118 | 315.465.222 | 6.056.710 |
| **Model Size (MB)** | 3,15139 | 1203,4 | 23,1 |
| **Peak VRAM (MB)** | 61,17 | 8441,09 | 137,67 |
| **Training Throughput (samples/sec)** | 1081,7 | 263,52 | 2880,97 |
| **Inference Latency (ms/sample)** | 0,12 | 0,337 | 0,053 |
Note: Penggunaan titik dan koma mengikuti aturan Indonesia
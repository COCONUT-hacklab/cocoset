# Dataset Sektor Keamanan

Folder ini menampung dataset-dataset yang berfokus pada keamanan siber, deteksi intrusi, analisis kerentanan, dan topik keamanan informasi lainnya. Dataset ini relevan untuk penelitian di bidang [sebutkan area spesifik, misal: deteksi serangan jaringan, analisis malware, forensik digital].

## Daftar Dataset

* **`HIDS-Set.csv`**: Dataset Sistem Deteksi Intrusi Berbasis Host (HIDS) yang berisi data log dan traffic jenis serangan dari sistem untuk identifikasi aktivitas mencurigakan.
* **`wazuh_rules_dataset.csv`**: Kumpulan aturan Wazuh yang telah diproses, serverity, kategori aturan, description.
* **`wazuh_preprocessed_rules.csv`**: Versi pra-proses dari aturan Wazuh, telah melalui tahap pembersihan dan normalisasi.
* **`wazuh_rule_embeddings.csv`**: Representasi vektor (embeddings) dari aturan Wazuh, berguna untuk analisis semantik atau clustering.
* **`ET_parsed_rules.csv`**: Aturan Emerging Threats (ET) yang telah diurai dengan ekstraksi fitur tertentu.
* **`ET_processed_rules_with_embeddings.csv`**: Aturan ET yang telah diproses dan dilengkapi dengan representasi embeddings.
* **`ET_clustered_dataset.csv`**: Dataset yang berisi hasil clustering dari aturan ET, mengelompokkan aturan serupa.
* **`ET_dataset_with_relations.csv`**: Dataset ET yang mencakup hubungan antar aturan atau entitas terkait.

## Penggunaan

Dataset ini dapat digunakan untuk berbagai tujuan penelitian, termasuk:
* Pengembangan model deteksi intrusi
* Analisis perilaku jaringan dan sistem
* Klasifikasi serangan siber
* Pengembangan model keamanan
* Penelitian kerentanan, etc

## Sumber Data

Dataset ini dikembangkan secara internal dari [https://coconut.or.id].

## Catatan

Pastikan untuk membaca dokumentasi atau deskripsi individual untuk setiap dataset jika tersedia untuk informasi lebih lanjut mengenai struktur, kolom, dan metodologi pengumpulan data.

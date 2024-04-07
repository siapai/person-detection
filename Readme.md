# Daftar Isi
- [Deskripsi Proyek](#deskripsi-proyek)
- [Dataset](#dataset)
- [Model FASTER RCNN Restnet50 Backbone](#model-faster-rcnn-restnet50)
- [Implementasi](#implementasi)


## Deskripsi Proyek
Proyek ini bertujuan untuk melatih model deteksi objek menggunakan dataset COCO (Common Objects in Context) untuk mendeteksi manusia dalam gambar. Subset class yang digunakan hanya "person" untuk fokus pada deteksi manusia. Model yang digunakan adalah Faster R-CNN dengan backbone ResNet50. Proyek ini akan mencakup proses pengolahan data, pelatihan model, evaluasi performa, dan implementasi model untuk deteksi manusia dalam gambar. Dengan menggunakan subset class "person," diharapkan model dapat mempelajari fitur-fitur yang khusus untuk mendeteksi manusia dengan lebih baik.

## Dataset
Dataset COCO (Common Objects in Context) digunakan dalam proyek ini untuk melatih model deteksi objek, khususnya untuk mendeteksi manusia dalam gambar. Subset class yang digunakan hanya "person," memungkinkan model untuk fokus pada deteksi manusia dengan lebih baik. COCO dataset dikenal karena keberagaman visualnya dan anotasi yang detail, termasuk informasi tentang lokasi dan kelas objek. Penggunaan subset class "person" memungkinkan model untuk belajar fitur-fitur yang khusus untuk mendeteksi manusia, sehingga diharapkan dapat meningkatkan performa deteksi manusia dalam gambar.

## Model Faster RCNN Restnet50
Model yang digunakan dalam proyek ini adalah Faster R-CNN dengan backbone ResNet50 yang telah di-pretrain menggunakan dataset COCO. Faster R-CNN merupakan salah satu model populer untuk deteksi objek yang menggabungkan kecepatan dan akurasi yang baik. Sementara itu, ResNet50 adalah versi dari jaringan ResNet yang lebih dalam dengan 50 layer, yang telah terbukti efektif dalam berbagai tugas visi komputer. Dengan menggunakan model yang telah di-pretrain dengan dataset COCO, diharapkan model dapat mempelajari representasi yang baik untuk mendeteksi manusia dalam gambar.

## Implementasi
- [Link github backend](https://github.com/siapai/krowd-api.git)
- [Link github frontend](https://github.com/siapai/krowd.git)
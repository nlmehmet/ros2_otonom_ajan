# 🤖 Autonomous Systems AI Agency

Bulut tabanlı, robotik ve otonom sistemler geliştirmeye özel olarak tasarlanmış Yapay Zeka Ajanları çalışma alanı.

## 🚀 Proje Hakkında
Bu proje, otonom mobil robot (AMR) navigasyonu, sensör veri işleme ve simülasyon ortamları gibi spesifik mühendislik alanlarında teknik destek sağlaması amacıyla özelleştirilmiş yapay zeka ajanlarını barındırır. Donanım kısıtlamalarını aşmak ve yüksek işlem gücü gerektiren AI modellerini kesintisiz çalıştırmak için tamamen bulut altyapısı (Google Colab) ve **Gemini API** entegrasyonu üzerine inşa edilmiştir.

## ⚙️ Teknoloji Yığını (Tech Stack)
*   **Yapay Zeka:** Google Gemini 2.5 Flash API, Prompt Engineering
*   **Altyapı:** Google Colab, Jupyter Notebook, Python
*   **Ajan Odak Alanları:** ROS 2 (Humble/Iron), Nav2, Gazebo, C++/Python Düğüm (Node) Geliştirme

## 🧠 Mevcut Ajanlar
### 1. ROS 2 Navigasyon & Otonomi Uzmanı
Genel geçer AI asistanlarından farklı olarak, otonom sistem mimarileri için özel sistem komutlarıyla (system prompt) kısıtlandırılmış ve yapılandırılmıştır.
*   **Yetenekleri:** LIDAR/derinlik kamerası verilerini işleyen filtreler tasarlamak, Nav2 costmap konfigürasyonlarındaki gürültüleri gidermek ve bağımlılık (`package.xml`, `CMakeLists.txt`) optimizasyonu yapmak.

## 🛠️ Nasıl Çalıştırılır?
Proje, hiçbir lokal kurulum gerektirmeden tarayıcı üzerinden saniyeler içinde çalıştırılabilecek şekilde tasarlanmıştır:
1. Depodaki `.ipynb` uzantılı dosyayı Google Colab'da açın.
2. `GEMINI_API_KEY` bilginizi Colab'ın *Secrets* (Gizli Anahtarlar) bölümüne ekleyin.
3. Kod hücrelerini sırasıyla çalıştırarak ajana ROS 2 mimarisiyle ilgili teknik senaryolarınızı yöneltin.

## 🎯 Gelecek Hedefleri (Roadmap)
*   [ ] OpenCV ve PyTorch algoritmaları üretebilen Bilgisayarlı Görü (Computer Vision) ajanı eklenmesi.
*   [ ] Mekanik montaj, tolerans hesaplamaları ve CAD otomasyon senaryoları için özelleştirilmiş 3B Tasarım ajanı profilinin oluşturulması.

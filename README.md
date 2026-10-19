# 🤖 Autonomous Systems AI Agency

Bulut tabanlı, robotik ve mekanik sistemler geliştirmeye özel olarak tasarlanmış Yapay Zeka Ajanları çalışma alanı. Bir Robotik ve Yapay Zeka perspektifiyle, donanım ve yazılım entegrasyonu süreçlerini otomatize etmek için geliştirilmiştir.

## 🚀 Proje Hakkında
Bu proje, otonom mobil robot (AMR) navigasyonu, bilgisayarlı görü (computer vision) ve karmaşık mekanik CAD otomasyonları gibi spesifik mühendislik alanlarında teknik destek sağlaması amacıyla özelleştirilmiş yapay zeka ajanlarını barındırır. Donanım kısıtlamalarını aşmak ve yüksek işlem gücü gerektiren AI modellerini kesintisiz çalıştırmak için tamamen bulut altyapısı (Google Colab) ve **Gemini API** entegrasyonu üzerine inşa edilmiştir.

## ⚙️ Teknoloji Yığını (Tech Stack)
*   **Yapay Zeka:** Google Gemini 2.5 Flash API, Prompt Engineering
*   **Altyapı:** Google Colab, Jupyter Notebook, Python
*   **Ajan Odak Alanları:** ROS 2 (Humble/Iron), OpenCV/PyTorch, Autodesk Inventor API (win32com)

## 🧠 Mevcut Ajanlar

### 1. ROS 2 Navigasyon & Bilgisayarlı Görü Uzmanı
Otonom sistem mimarileri ve yapay zeka destekli görüntü işleme için yapılandırılmıştır.
*   **Yetenekleri:** LIDAR verilerini işlemek, Nav2 costmap optimizasyonu yapmak ve kameradan alınan anlık görüntülerle (`cv_bridge`) PyTorch/OpenCV tabanlı otonom nesne tespiti algoritmaları yazmak.

### 2. CAD Otomasyon & 3B Tasarım Uzmanı
Mekanik tasarım süreçlerini kodla otomatize etmek için tasarlanmış endüstriyel otomasyon profili.
*   **Yetenekleri:** Autodesk Inventor API kullanarak parametrik 3B montajlar (assembly) oluşturmak, parçalar arası mafsal (joint) ve kısıtları (constraint) otomatik atamak.
*   **Örnek Senaryo:** 3 eksenli (Pan-Tilt-Roll) kamera gimbal mekanizmalarının kod üzerinden kinematik kısıtlarının verilmesi gibi zorlu mekanik tasarım ve bitirme projelerinin algoritmik çözümü.

## 🛠️ Nasıl Çalıştırılır?
Proje, hiçbir lokal kurulum gerektirmeden tarayıcı üzerinden saniyeler içinde çalıştırılabilecek şekilde tasarlanmıştır:
1. Depodaki `.ipynb` uzantılı dosyayı Google Colab'da açın.
2. `GEMINI_API_KEY` bilginizi Colab'ın *Secrets* bölümüne ekleyin.
3. Kod hücrelerini sırasıyla çalıştırarak ajanlara teknik senaryolarınızı yöneltin.

## 🎯 Gelecek Hedefleri (Roadmap)
*   [ ] Ajanların kendi aralarında iletişim kurmasını sağlayan çoklu ajan (Multi-Agent) haberleşme altyapısının kurulması.
*   [ ] Robotik sistemler için Python Tkinter ile masaüstü kontrol arayüzü yazabilen UI/UX ajanının sisteme dahil edilmesi.

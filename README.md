# 🤖 Autonomous Systems AI Agency

Bulut tabanlı, robotik, mekanik tasarım ve kontrol arayüzleri geliştirmeye özel olarak tasarlanmış **Çoklu Yapay Zeka Ajanları (Multi-Agent)** çalışma alanı. 

Bu proje, donanım ve yazılım entegrasyonu süreçlerini otomatize etmek, düşük donanım kısıtlamalarını bulut mimarisiyle aşmak ve yapay zeka ajanlarını birbiriyle konuşturarak uçtan uca mühendislik çözümleri üretmek için geliştirilmiştir.

## 🚀 Proje Mimarisi ve Vizyon
Genel geçer AI asistanları yerine, her biri kendi alanında uzmanlaşmış "AI Çalışanları" tasarlanmıştır. Proje tamamen bulut altyapısı (Google Colab) ve **Gemini API** entegrasyonu üzerine inşa edilerek donanımdan bağımsız hale getirilmiştir.

## ⚙️ Teknoloji Yığını (Tech Stack)
*   **Yapay Zeka Mimarisi:** Google Gemini 2.5 Flash API, Prompt Chaining (İstem Zincirleme), Multi-Agent Workflow
*   **Altyapı & Geliştirme:** Google Colab, Python, Jupyter Notebook
*   **Mühendislik Araçları:** ROS 2 (Humble/Iron), OpenCV/PyTorch, Autodesk Inventor API (win32com), Python Tkinter / CustomTkinter

---

## 🧠 Ajan Kadrosu (The Roster)

### 1. 🤖 ROS 2 Navigasyon & Bilgisayarlı Görü Uzmanı
Otonom sistem mimarileri ve yapay zeka destekli görüntü işleme için yapılandırılmıştır.
*   **Uzmanlık:** LIDAR sensör verilerini işlemek, Nav2 costmap optimizasyonu ve `cv_bridge` üzerinden PyTorch/OpenCV tabanlı otonom nesne tespiti (Computer Vision) algoritmaları yazmak.

### 2. ⚙️ CAD Otomasyon & 3B Tasarım Uzmanı
Mekanik tasarım süreçlerini kodla otomatize etmek için tasarlanmış endüstriyel otomasyon profili.
*   **Uzmanlık:** Autodesk Inventor API kullanarak parametrik 3B montajlar (assembly) oluşturmak, kinematik mafsal (joint) ve kısıtları (constraint) Python üzerinden otomatize etmek.

### 3. 🖥️ Masaüstü Arayüz (UI/UX) Uzmanı
Robotik donanımların operatörler tarafından kontrol edilebilmesi için görsel arayüzler tasarlar.
*   **Uzmanlık:** Python Tkinter ve nesne yönelimli programlama (OOP) kullanarak, sensör akışlarını ve kamera görüntülerini anlık gösteren modern, duyarlı kontrol panelleri (Dashboard) kodlamak.

---

## 🔗 İleri Seviye Özellik: Çoklu Ajan İş Akışı (Multi-Agent Pipeline)
Bu projenin en güçlü yanı, ajanların birbiriyle iletişim kurabilmesidir.
*   **Örnek Senaryo (Pan-Tilt-Roll Gimbal):** Sisteme bir kamera gimbal'ı yapma görevi verildiğinde; **CAD Ajanı** 3 eksenli mekanik hiyerarşiyi ve fiziksel montaj kısıtlarını tasarlar. Ürettiği mekanik rapor, anında **ROS 2 Ajanı'na** aktarılır. ROS 2 Ajanı havadan kod yazmak yerine, birebir bu mekanik kısıtlara uyarak yazılım düğümlerini (nodes) oluşturur. Son olarak **UI/UX Ajanı**, bu eksenleri kontrol edecek kaydırma çubuklarına (slider) sahip masaüstü programını çizer.

## 🛠️ Nasıl Çalıştırılır?
Hiçbir lokal kurulum (IDE, kütüphane, GPU) gerektirmez.
1. Depodaki `.ipynb` uzantılı dosyayı Google Colab'da açın.
2. `GEMINI_API_KEY` bilginizi Colab'ın *Secrets* bölümüne ekleyin.
3. Kod hücrelerini sırasıyla çalıştırarak departmanları başlatın ve ajanların birbirleriyle olan etkileşimini izleyin.

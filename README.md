# 🏛️ Premium Personal Portfolio

Yazılım ve donanımın kesişim kümesinde geliştirilen mühendislik çözümlerini, yüksek estetik standartlar ve optimize edilmiş performansla sunan kişisel vitrin projesi. 

Bu site; ham verilerin, algoritmaların ve kullanıcı arayüzlerinin aynı ritimde buluştuğunda teknik bir çözümün nasıl sürdürülebilir bir deneyime dönüştüğünü göstermek amacıyla **"Mobile-First"** ve **"GPU-Optimized"** mimari prensipleriyle sıfırdan inşa edilmiştir.

---

## 🛠️ Teknoloji Yığını (Tech Stack)

Sitenin sinir sistemini, harici hantal framework'lerin (React, Vue vb.) getirdiği sanal yükleri (Virtual DOM) eleyerek doğrudan tarayıcı donanımıyla konuşan saf ve güçlü teknolojiler oluşturur:

* **İskelet:** Semantik HTML5 mimarisi (SEO ve erişilebilirlik odaklı)
* **Estetik & Stil:** Tailwind CSS (Utility-First, özel lüks renk paleti ve fluid tipografi)
* **Sinir Sistemi (Beyin):** Vanilla JavaScript (Saf JS - Sıfır bağımlılık, maksimum execution hızı)
* **Animasyon Motoru:** GSAP (GreenSock Animation Platform) & ScrollTrigger API
* **Grafik & Simülasyon:** HTML5 Canvas API (Object-Oriented JavaScript)

---

## 💎 Öne Çıkan Mühendislik Çözümleri & Özellikler

### 1. Kinetik Görüntü Nehri (GSAP & ScrollTrigger)
* Kullanıcının dikey kaydırma (scroll) gücünü ele geçirerek (`Scroll Hijacking`), ekranı dikey eksende kilitler (`pin: true`).
* Fare tekerleğinin kinetik enerjisini, çoklu sütunlardaki proje görsellerini zıt yönlerde akıtan bir motora dönüştürür (`scrub: 1`).
* Sayfa kaydırma yüzdesine bağlı olarak arka plandaki devasa tipografik katmanı dinamik olarak manipüle eder.

### 2. Matematiksel Parçacık Simülasyonu (Canvas API)
* Yaklaşım bölümünde yer alan interaktif arka plan, harici bir görsel veya video değil; tamamen JavaScript ile yazılmış bir fizik motorudur.
* Trigonometrik formüller (Sinüs/Kosinüs) ve yay fiziği (Spring Physics) kullanılarak binlerce parçacığın X ve Y koordinatları tarayıcı üzerinde anlık hesaplanır.
* Fare hareketlerini algılayan vektörel itme kuvveti algoritması entegre edilmiştir.

### 3. Donanım Hızlandırma (GPU Acceleration) & Mobil Optimizasyon
* Camsı katmanların (`Glassmorphism`) ve yoğun animasyonların Windows tabanlı tarayıcılarda ve mobil GPU'larda kasmasını engellemek için `transform-gpu` ve `will-change-transform` katmanları kullanılmıştır. Hesaplama yükü CPU'dan alınarak doğrudan grafik kartına (GPU) devredilmiştir.
* Ekran çözünürlüğüne göre parçacık sayısını dinamik olarak sınırlayan optimizasyon algoritması içerir.

### 4. Durum Korumalı Dil & Tema Yönetimi (State & LocalStorage)
* Gelişmiş `Intersection Observer API` ile elementlerin ekrana giriş anları izlenirken, asimetrik dil geçişleri (TR/EN) ve Karanlık Mod (Dark Mode) tercihleri HTML5 `localStorage` üzerinde durum korumalı (persistent state) olarak saklanır.

---

## 📁 Proje Yapısı

```text
my_website1/
├── assets/               # Yerel mühendislik laboratuvarı görselleri (MATLAB, ESP32, UI/UX)
├── index.html            # Ana semantik iskelet ve JavaScript mimarisi
└── README.md             # Proje dokümantasyonu

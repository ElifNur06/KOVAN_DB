# KOVAN_DB // Bilişsel Uç Veritabanı (Cognitive Edge Database)

![Version](https://img.shields.io/badge/Version-2.0_Synergy-blueviolet?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Private_Core-success?style=for-the-badge)
![Architecture](https://img.shields.io/badge/Architecture-P2P_Mesh-orange?style=for-the-badge)
![AI](https://img.shields.io/badge/AI-LLM_Semantic_Routing-yellow?style=for-the-badge)

KovanDB, geleneksel merkezi bulut (Cloud-Central) veritabanlarına meydan okuyan; yapay zeka destekli, tamamen çevrimdışı (offline-first) çalışabilen ve kendi kendine karar verebilen dağıtık bir **Uç Bilişim (Edge Computing)** veritabanı motorudur.

Merkezi sunucuların yüksek API maliyetlerini, gecikme (latency) sorunlarını ve tek nokta hatalarını (SPOF) ortadan kaldırmak üzere tasarlanmıştır. Sistem, ağdaki cihazların (düğümlerin) donanım kapasitelerini ve gelen verinin anlamsal içeriğini analiz ederek, veriyi ağ üzerinde **otonom bir karınca kolonisi (Swarm Intelligence)** gibi yönetir.

---

## 🚀 Çığır Açan Mimari Özellikler

Bu depo, KovanDB'nin kavramsal mimarisini ve arayüz yeteneklerini sergilemektedir. Çekirdek motor (Core Engine) fikri mülkiyet koruması altında gizli (private) tutulmaktadır. Sistemin temel yetenekleri şunlardır:

### 1. Bilişsel Replikasyon (Semantic Swarm)
Sistem verileri sadece ID'sine göre değil, **anlamsal bağına göre** ağda yönlendirir. Hafif bir yerel/bulut LLM (Büyük Dil Modeli) motoru, ağa giren veriyi anında analiz eder:
* **[HASSAS] Veriler** (Örn: Şifreler, cüzdan anahtarları) -> Sadece kapasite skoru ve güvenlik metrikleri en yüksek (güvenli) cihazlara şifrelenerek gönderilir.
* **[MEDYA] Verileri** (Örn: Oyun assetleri, ses dosyaları) -> Sadece boş depolama alanı en yüksek olan cihazlara yönlendirilir.
* API kotası dolduğunda veya internet kesildiğinde, sistem çökmez; saniyeler içinde **Çevrimdışı (Offline) Kelime Analiz Motoruna** geçiş yaparak otonom ayrıştırmaya kesintisiz devam eder.

### 2. Kırılmaz İletişim (Mesh Survival Mode)
KovanDB, tam bir felaket senaryosu (internetin veya ana yönlendiricinin çökmesi) durumunda hayatta kalmak üzere kodlanmıştır.
Sistem dış dünyadan yalıtıldığını fark ettiği an paniğe kapılmaz. Otomatik olarak **Hayatta Kalma Modunu (Survival Mode)** tetikler ve alternatif protokoller (Örn: Bluetooth Low Energy / Wi-Fi Direct simülasyonu) üzerinden yan yana duran cihazlar arasında kendi acil durum ağını (Mesh) kurarak veri eşitlemeyi sürdürür.

### 3. Kendi Kendini Optimize Eden Çekirdek (JIT Compressor)
Cihazların hafızası dolduğunda KovanDB'nin "Otonom Yük Dengeleyicisi" (Balancer) soğuk verileri ağdaki boş cihazlara göç ettirir (Migration). Ancak ağda hiç boş yer kalmadıysa?
KovanDB veri silmez. Çalışma zamanında devreye giren **JIT (Just-In-Time) Sıkıştırma Motoru**, verileri agresif bir şekilde analiz eder, gereksiz boşlukları siler ve `zlib/base64` mimarisiyle veriyi veri kaybı yaşamadan (lossless) **dondurur**.

### 4. Ekosistem Entegrasyonu (Flutter / BaaS Uyumu)
KovanDB, sadece arka planda çalışan teorik bir algoritma değildir; aynı zamanda geliştiriciler için hazır bir **Backend-as-a-Service (BaaS)** platformudur. Çapraz platform uygulama (Flutter/React Native) ve bağımsız oyun geliştiricileri, yüksek sunucu maliyetleri ödemeden projelerine KovanDB'yi entegre edebilirler. Sistem, standart bir REST API üzerinden veri kabul eder ve bunu oyuncuların cihazları arasında (merkeziyetsiz) dağıtır.

---

## 👁️ Nöral Ağ Monitörü (Neural Swarm Dashboard)

KovanDB'nin otonom kararları, siberpunk ve minimalist bir tasarıma sahip olan **Nöral Ağ Monitörü** üzerinden gerçek zamanlı, 60 FPS hızında izlenebilir. Merkez Kovan'ın etrafında dinamik bir yörüngeye oturan cihazlar, birbirleriyle yüksek hızlı lazer bağları kurarlar.

> **Sistem Metrikleri:**
> * <span style="color:#FF00FF;">**Fuşya (Magenta) İzler:**</span> Popüler verilerin ağ üzerindeki anlamsal replikasyonunu (Swarm) temsil eder.
> * <span style="color:#FFF44F;">**Limon Sarısı İzler:**</span> Doluluk oranına göre sistemin kendi kendine aldığı göç (Migration) kararlarını temsil eder.

## Görseller
<img width="1385" height="762" alt="image" src="https://github.com/user-attachments/assets/fda0df56-af18-499d-8843-46c71a2636b6" />
<img width="1382" height="761" alt="image" src="https://github.com/user-attachments/assets/ddd487ed-d88e-4046-a67e-330ac2705ebb" />
<img width="1388" height="776" alt="image" src="https://github.com/user-attachments/assets/285d9ab4-ce0d-4786-8222-fb20d7acfa1b" />
<img width="1386" height="739" alt="image" src="https://github.com/user-attachments/assets/ee8991fe-f792-4f22-a919-da37828e5061" />
<img width="1382" height="768" alt="image" src="https://github.com/user-attachments/assets/ff90259e-9b4d-4cb5-8f2f-975b12376ec0" />
<img width="1384" height="759" alt="image" src="https://github.com/user-attachments/assets/d863da11-e5ed-44fc-937e-e8f0b381b4b8" />
<img width="1384" height="763" alt="image" src="https://github.com/user-attachments/assets/ab95e35d-1a91-4764-8f0f-018ad4ee309d" />
<img width="1382" height="751" alt="image" src="https://github.com/user-attachments/assets/7b170e7d-347f-4674-96d1-004feb54e768" />
<img width="1382" height="775" alt="image" src="https://github.com/user-attachments/assets/947fee97-83ec-475c-85b4-741c43d00f07" />

### 🧠 KovanDB'nin Tepkisi: Otonom İş Akışı

Geliştiricinin veri yazma isteği sisteme girdiği anda; veriler yerel şifreli depoya yazılır, **Bilişsel (Cognitive) Motor** tarafından anlamsal içeriği analiz edilir ve sistem saniyeler içinde veriyi (örneğin `node-kayseri-1` gibi) donanım metriklerine göre en uygun cihazın belleğine otonom olarak taşır (Migration). Dışarıdaki geliştirici sadece `status: success` yanıtını alır; arka plandaki tüm bu sofistike "Swarm" yönetimi tamamen şeffaf ve otonomdur.

---


## ⚙️ Kaputun Altındaki Teknolojiler

KovanDB, yüksek performans ve düşük gecikme için modern, asenkron bir teknoloji yığını üzerine inşa edilmiştir:

* **Çekirdek:** Python 3.11+, `asyncio` (Tamamen Asenkron Mimarisi)
* **Ağ & İletişim:** WebSockets, `aiohttp`, UDP tabanlı Gossip Protokolü (Cihaz keşfi)
* **Anlamsal Zeka:** Google Gemini API (Fallback: On-Device Heuristic Engine)
* **Görselleştirme:** HTML5 Canvas, Vanilla JavaScript (Motion Blur & Particle Physics)
* **Veri Sıkıştırma:** `zlib`, JIT (Just-In-Time) tabanlı otonom veri dondurma (Freeze)

---


## 🔒 Lisans ve Fikri Mülkiyet

**KovanDB'nin çekirdek motoru (Core Engine), Bilişsel Yönlendirme (Semantic Routing) ve JIT dondurma algoritmaları fikri mülkiyet hakları kapsamında kapalı kaynaklıdır (Private Source).** Bu depo, KovanDB'nin vizyonunu, teknik mimarisini ve görsel kanıtlarını sunmak amacıyla hazırlanmış bir "Proof of Technology" dokümantasyonudur. Ticari kullanım, lisanslama ve kurumsal entegrasyon talepleri için bizimle iletişime geçebilirsiniz.

*© 2026 KovanDB Cognitive Systems. All Rights Reserved.*

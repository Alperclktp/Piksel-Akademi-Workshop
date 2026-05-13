# 🎮 Piksel Akademi - Unity 3D Runner Workshop Başlangıç Projesi

Bu depo, Piksel Akademi'de gerçekleştirilecek olan **Unity ile 3D Runner Oyunu Geliştirme** atölyesi için hazırlanmış temel (starter) projedir. Etkinlik boyunca zaman kaybetmeden doğrudan kodlamaya ve oyun mekaniklerine odaklanabilmemiz için gerekli olan karakter modelleri, animasyonlar ve temel çevre tasarımları bu projenin içine dahil edilmiştir.

## ⚠️ Workshop Öncesi Hazırlıklar (Gereksinimler)

Atölye çalışmalarına sorunsuz bir şekilde katılabilmek için bilgisayarınızda aşağıdaki yazılımların kurulu olduğundan emin olmalısınız.

### 1. Unity Kurulumu
* **Unity Hub:** [Buradan indirin ve kurun.](https://unity.com/download)
* **Unity Versiyonu:** Unity Hub üzerinden **`6000.2.9f1`** sürümünü yükleyin. Farklı bir sürüm kullanmak, projede uyumsuzluklara veya paket hatalarına yol açabilir.

### 2. Kod Editörü (Visual Studio)
* C# kodlarımızı yazmak için **Visual Studio IDE**'sini kurmanız gerekmektedir (Topluluk/Community sürümü ücretsizdir).
* **Önemli Adım:** Visual Studio Installer kurulumu sırasında, iş yükleri (workloads) ekranında mutlaka **"Unity ile Oyun Geliştirme" (Game development with Unity)** seçeneğinin işaretli olduğundan emin olun. Aksi takdirde Unity kütüphanelerini kod yazarken göremezsiniz.

### 3. Versiyon Kontrolü (GitHub)
* Bir [GitHub Hesabı](https://github.com/) oluşturun.
* Repoyu bilgisayarınıza kolayca indirebilmek ve yönetebilmek için [GitHub Desktop](https://desktop.github.com/) uygulamasını indirip kurun ve hesabınızla giriş yapın.

---

## 🚀 Projeyi Bilgisayarınıza İndirme ve Açma

Etkinlik başladığında projeyi kendi bilgisayarınıza almak için aşağıdaki adımları izleyin:

### Seçenek A: GitHub Desktop İle (Önerilen)
1. Bu sayfanın sağ üst köşesindeki yeşil **`<> Code`** butonuna tıklayın.
2. Açılan menüden **`Open with GitHub Desktop`** seçeneğine tıklayın.
3. GitHub Desktop uygulaması açılacak, projenin bilgisayarınızda kaydedileceği yeri seçin ve **Clone** (Klonla) butonuna basın.

### Seçenek B: ZIP Olarak İndirme
1. Yeşil **`<> Code`** butonuna tıklayın.
2. **`Download ZIP`** seçeneğini seçin.
3. İnen ZIP dosyasını bilgisayarınızda uygun bir klasöre çıkartın (Masaüstü vb.).

### Unity Hub'da Projeyi Açma
1. **Unity Hub**'ı açın.
2. **Projects** sekmesindeyken sağ üstteki **Add** butonuna tıklayın.
3. Projeyi klonladığınız (veya ZIP'ten çıkardığınız) `Piksel-Akademi-Workshop` ana klasörünü seçin.
4. Listeye eklenen projeye tıklayarak Unity editöründe açın. *(İlk açılış projenin derlenmesinden dolayı birkaç dakika sürebilir).*

---

## 📂 Proje İçeriği

Bu projede kodlamaya başlamadan önce sizin için hazır olanlar:
* **Hazır Sahneler (Scenes):** Aydınlatması ve kamerası ayarlanmış temel test sahnesi.
* **Karakter Modeli & Animasyonlar:** Koşma ve bekleme animasyonlarına sahip optimize edilmiş 3D karakter (Mixamo).
* **Temel Objeler (Prefabs):** Toplanabilir paralar (Coin), engeller (Obstacles) ve UI arayüzü bileşenleri.

Atölye boyunca bu temeli kullanarak kendi hareket sistemimizi (Movement), çarpışma kontrollerimizi (Collision), skor yönetimini ve oyun döngüsünü (Game Loop) kodlayacağız.

Şimdiden iyi eğlenceler, atölyede görüşmek üzere! 👨‍💻👩‍💻

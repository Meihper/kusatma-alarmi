# 🏰 Kuşatma Alarmı - Android APK Oluşturma Rehberi

Bu proje, **Aysel & Erdem** için hazırlanan **Kuşatma Alarmı (Sabah Savunması & Kahvaltı Kalesi)** mobil uygulamasının GitHub Actions üzerinden otomatik Android APK çıktısı veren paketidir.

---

## 🚀 GitHub'a Yükleyip APK İndirme (3 Basit Adım)

Bilgisayarında Android Studio veya herhangi bir ek programa gerek **yoktur**! GitHub'ın ücretsiz sunucuları APK'yı senin için otomatik derler.

### 1. Adım: GitHub'da Repo Oluştur
1. [GitHub](https://github.com/) hesabına giriş yap ve sağ üstteki **+** simgesinden **New repository** seç.
2. Repository name kısmına: `kusatma-alarmi` yaz.
3. **Public** seç ve **Create repository** butonuna bas.

### 2. Adım: Bu Dosyaları GitHub'a Yükle
* Açılan boş repo sayfasındaki **uploading an existing file** linkine tıkla.
* İndirdiğin `kusatma-alarmi-github-apk.zip` arşivini aç ve içindeki tüm dosyaları (`index.html`, `package.json`, `capacitor.config.json`, `manifest.json`, `www` klasörü ve `.github` klasörü) GitHub sayfasına sürükleyip bırak.
* Alttaki yeşil **Commit changes** butonuna bas.

### 3. Adım: APK Dosyasını İndir
1. Dosyaları yüklediğin an GitHub Actions otomatik olarak APK'yı derlemeye başlar.
2. Repo sayfasının üst menüsündeki **Actions** sekmesine tıkla.
3. Çalışan **Android APK Oluşturucu (Build APK)** işine tıkla (yaklaşık 2-3 dakika sürer).
4. İşlem tamamlandığında sayfanın en altındaki **Artifacts** bölümünde **`Kusatma-Alarmi-Android-APK`** belirecektir.
5. Tıkla ve hazır `.apk` dosyasını telefonuna indirip hemen kur!

---

## ⚡ Alternatif Hızlı Yol: PWABuilder (1 Tıkla APK)
Repo ayarlarından (Settings > Pages) GitHub Pages'i açtıktan sonra, sitenin linkini [PWABuilder.com](https://www.pwabuilder.com/) sitesine yapıştırıp **Generate Android Package (APK)** diyerek de 10 saniyede hazır APK alabilirsin!

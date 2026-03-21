# GitHub Pages Setup - WordMaster

## 🚀 Hızlı Başlangıç

### Adım 1: GitHub Repository Oluştur

1. GitHub.com'a git → **New Repository**
2. **Repository name:** `wordmasterapps`
3. **Public** seç (GitHub Pages için gerekli)
4. **Create repository**

---

### Adım 2: Dosyaları Push Et

```bash
# wordmasterapps-web klasörüne git
cd m:\Software\proje\english_master\wordmasterapps-web

# Git başlat (eğer başlatmadıysan)
git init

# Dosyaları ekle
git add .

# İlk commit
git commit -m "Initial commit: WordMaster website"

# GitHub'a bağlan (username yerine kendi kullanıcı adını yaz)
git remote add origin https://github.com/USERNAME/wordmasterapps.git

# Push et
git push -u origin main
```

**Not:** Eğer `main` yerine `master` branch'i kullanıyorsan:
```bash
git branch -M main
git push -u origin main
```

---

### Adım 3: GitHub Pages Aktif Et

1. GitHub repository'ne git
2. **Settings** → **Pages** (sol menüden)
3. **Source** bölümünde:
   - Branch: `main`
   - Folder: `/ (root)`
4. **Save** tıkla

**5-10 dakika içinde siteniz canlıya çıkacak!** 🎉

---

## 🌐 Site URL'leri

**Ana Sayfa:**
```
https://wordmasterapps.github.io
```

**Privacy Policy:**
```
https://wordmasterapps.github.io/privacy.html
```

**Terms of Service:**
```
https://wordmasterapps.github.io/terms.html
```

---

## ✅ Test Et

### Tarayıcıda:
1. `https://wordmasterapps.github.io` aç
2. Landing page görünmeli
3. Privacy ve Terms linklerini test et

### Uygulamada:
```bash
cd m:\Software\proje\english_master
flutter run
```

1. Profile → Settings git
2. Privacy Policy → Tıkla → GitHub Pages açılmalı ✅
3. Terms of Service → Tıkla → GitHub Pages açılmalı ✅

---

## 🔧 Güncelleme Yapmak İçin

```bash
# Dosyaları düzenle (index.html, privacy.html, terms.html)

# Değişiklikleri commit et
git add .
git commit -m "Update: Privacy policy"

# Push et
git push origin main

# 1-2 dakika içinde canlı olur!
```

---

## 🎨 Custom Domain Eklemek (İleride)

Eğer ileride domain alırsan (örn: wordmasterapps.com):

1. GitHub Pages → Settings → Custom domain
2. `wordmasterapps.com` yaz
3. Domain DNS ayarlarına:
```
CNAME @ wordmasterapps.github.io
```

---

## 📧 E-posta (Ücretsiz)

### ImprovMX ile:

**Şimdilik kullan:**
```
support@wordmasterapps.com → Senin Gmail'in
```

**Nasıl?**
1. improvmx.com → Domain ekle
2. MX kayıtlarını ekle (domain aldığında)

---

## ✨ Avantajlar

- ✅ Tamamen ücretsiz
- ✅ HTTPS otomatik
- ✅ Hızlı ve güvenilir
- ✅ Git ile versiyon kontrolü
- ✅ Custom domain ekleyebilirsin
- ✅ Google/App Store tarafından kabul edilir

---

## 📱 App Store Bilgileri

### Google Play Console:
```
Privacy Policy URL: https://wordmasterapps.github.io/privacy.html
Support Email: support@wordmasterapps.com
Website: https://wordmasterapps.github.io
```

### App Store Connect:
```
Privacy Policy URL: https://wordmasterapps.github.io/privacy.html
Support URL: https://wordmasterapps.github.io
Marketing URL: https://wordmasterapps.github.io
```

---

## 🎉 Tamamdır!

Artık profesyonel bir web siteniz var - **₺0 maliyetle!** 🚀

**Sorular için:** support@wordmasterapps.com

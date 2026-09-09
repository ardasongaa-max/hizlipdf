# HızlıPDF

Minimalist kitap arama uygulaması. GitHub Pages + Actions ile çalışır.

## Özellikler

- Kitap arama (LibGen üzerinden)
- Skeleton loader ile hızlı geri bildirim
- Doğrudan indirme linkleri
- Tamamen istemci tarafı, sunucu yok

## Kurulum

1. Bu repoyu klonla:
   ```bash
   git clone <repo-url>
   cd hızlıpdf
   ```

2. `main` branch'ine push et:
   ```bash
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git push -u origin main
   ```

3. GitHub Pages'i aktifleştir:
   - Repo ayarlarına git → **Settings** → **Pages**
   - **Source** bölümünde **GitHub Actions** seçeneğini seç
   - Workflow otomatik olarak çalışacak ve siteni yayınlayacak

4. Site URL'i: `https://<kullanıcıadi>.github.io/hızlıpdf`

## Teknolojiler

- HTML5, Tailwind CSS CDN, Lucide Icons
- Vanilla ES6+ JavaScript
- AllOrigins proxy + LibGen API
- GitHub Actions otomatik deploy

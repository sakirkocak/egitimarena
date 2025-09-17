# Eğitim Arena 🌐

Bu repo, **sakirkocak.com** için Firebase Studio + App Hosting üzerinde geliştirdiğim  
**“Eğitim Arena”** web projesinin kaynak kodlarını içerir.  

---

## 🚀 macOS Kurulum Adımları  

Aşağıdaki komutlar **Terminal.app** veya **iTerm2**’de çalıştırılmalıdır.  

### 1. Xcode Command Line Tools  
```bash
xcode-select --install
2. Homebrew
bash
Kodu kopyala
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew update
3. Node.js & pnpm
bash
Kodu kopyala
brew install node
npm install -g pnpm
4. Projeyi Çalıştır
bash
Kodu kopyala
# Depoyu klonla
git clone https://github.com/sakirkocak/egitimarena.git
cd egitimarena

# Bağımlılıkları kur ve development sunucusunu başlat
pnpm install
pnpm dev   # http://localhost:3000
Not: pnpm dev yerine npm run dev de kullanabilirsiniz. Proje Next.js 14 ile derlenir.

🔧 Deploy
main dalına push yaptığınızda Firebase App Hosting CI/CD boru hattı otomatik olarak:

pnpm install && pnpm build çalıştırır

Build çıktısını CDN’e yükler

SSL sertifikasını yeniler ve küresel olarak yayar

bash
Kodu kopyala
git add .
git commit -m "Update"
git push origin main
“Bilgiyi paylaş, geleceği kur!” 🚀

css
Kodu kopyala

👉 Bunu `README.md` dosyanın içine yapıştırıp commit + push ettiğinde branch referansların **main** olacak.

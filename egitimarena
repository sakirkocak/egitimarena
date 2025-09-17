# Akademi Merkezi 🌐

Bu repo, **sakirkocak.com** için Firebase Studio + App Hosting üzerinde geliştirdiğim  
“Akademi Merkezi” web projesinin kaynak kodlarını içerir.

## macOS Kurulum Adımları

> Aşağıdaki komutlar **Terminal.app** veya iTerm2’de çalıştırılmalıdır.

### 1. Xcode Command Line Tools
```bash
xcode-select --install
```

### 2. Homebrew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew update
```

### 3. Node.js & pnpm
```bash
brew install node
npm install -g pnpm
```

### 4. Projeyi Çalıştır
```bash
# Depoyu klonla
git clone https://github.com/sakirkocak/akademi.git
cd akademi

# Bağımlılıkları kur ve development sunucusunu başlat
pnpm install
pnpm dev   # http://localhost:3000
```

> **Not:** `pnpm dev` yerine `npm run dev` de kullanabilirsiniz. Proje Next.js 14 ile derlenir.

## Deploy

`main` dalına *push* yaptığınızda **Firebase App Hosting** CI/CD boru hattı otomatik olarak:
1. `pnpm install && pnpm build` çalıştırır  
2. Build çıktısını CDN'e yükler  
3. SSL sertifikasını yeniler ve küresel olarak yayar

```
git add .
git commit -m "Update"
git push origin main
```

---

“Bilgiyi paylaş, geleceği kur!” 🚀

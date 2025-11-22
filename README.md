# 🌌 Ultimate GNOME Setup — Gnome-Customization

![Made with Love](https://img.shields.io/badge/Made%20with-Linux-1793D1?logo=linux&logoColor=white)
![GNOME](https://img.shields.io/badge/GNOME-45%2B-blue?logo=gnome&logoColor=white)
![GTK](https://img.shields.io/badge/GTK-3%20%7C%204-4A90E2)
![Zsh](https://img.shields.io/badge/Zsh-OhMyZsh-FFD700)
![Fastfetch](https://img.shields.io/badge/Fastfetch-config-green)

Repositori ini berisi kumpulan tema, aset, konfigurasi, dan skrip untuk membuat pengalaman GNOME Anda menjadi **ultimate**, **estetis**, dan **konsisten**.  
Mulai dari GTK theme, GNOME Shell theme, GRUB theme, wallpaper, sampai setup Zsh dan fastfetch—semuanya ada dalam satu tempat.

---

## 🌈 Apa Saja yang Termasuk?

### 🎨 **Tahoe-gtk-theme**
Tema lengkap untuk:
- GTK 3 & GTK 4  
- GNOME Shell  
- Metacity  
- XFWM4  

Termasuk:
- `userChrome.css` untuk Firefox  
- Tema Plank  
- Wallpaper pack  
- Skrip build & instalasi (`install.sh`)

---

### 🖥️ **grub-themes**
Koleksi tema GRUB berbagai resolusi + skrip instalasi otomatis.

---

### ⚡ **fastfetch**
- Konfigurasi (`config.jsonc`) untuk tampilan informasi sistem yang rapi dan minimalis.

---

### 🧩 **OhMyZsh_Setup**
- Skrip untuk setup Zsh dan Oh My Zsh  
- Cocok untuk terminal Linux & Termux  
- Termasuk tema dan plugin dasar

---

### 🖼️ **Wallpapers**
- Wallpaper curated  
- Skrip pemasangan untuk GNOME dan GRUB backgrounds

---

### 📁 **src / release**
- Sumber dan mekanisme build untuk tema dan paket rilis.

---

## 🌟 Fitur Utama

- Tema desktop lengkap (GTK3/4, Shell, Metacity, XFWM4)
- Tema bootloader GRUB
- Setup terminal otomatis untuk Zsh/Oh My Zsh
- Fastfetch config siap pakai
- Wallpaper terintegrasi
- Skrip instalasi yang mempermudah setup

---

## 🧩 Rekomendasi Ekstensi GNOME

Direkomendasikan untuk pengalaman GNOME terbaik:

- AppIndicator / KStatusNotifier  
- Blur my Shell  
- Burn My Windows  
- Caffeine  
- Compiz Magic Lamp  
- Coverflow Alt-Tab  
- Dash2Dock Animated  
- ESP (Extension Search Provider)  
- Folder Search Provider  
- GNOME 4.x UI Improvements  
- GSConnect  
- In Picture  
- Just Perfection  
- Logo Menu  
- Media Controls  
- SSH Search Provider Reborn  
- User Themes  
- Vitals  
- VSCode Search Provider  
- Windows Search Provider (WSP)

Instalasi via:
- GNOME Extensions App  
- CLI: `gnome-extensions`  
- Website: extensions.gnome.org

---

## 🚀 Quick Start

### 1️⃣ Clone repo  
```bash
git clone https://github.com/SamVivan1/Gnome-Custimization.git
```

### 2️⃣ Install tema GTK/GNOME Shell  
```bash
cd Tahoe-gtk-theme
./install.sh
```

### 3️⃣ Install Tema GRUB (opsional)
```bash
cd grub-themes
./install.sh
```

### 4️⃣ Install Wallpaper GNOME  
```bash
cd Tahoe-gtk-theme/wallpaper
./install-gnome-backgrounds.sh
```

### 5️⃣ Setup Zsh / Oh My Zsh  
```bash
cd OhMyZsh_Setup
./Setup_Terminal.sh
```

### 6️⃣ Fastfetch  
Salin:
```
fastfetch/config.jsonc → ~/.config/fastfetch/config.jsonc
```

---

## 🛠️ Kustomisasi

- Baca skrip sebelum menjalankan (beberapa membutuhkan `sudo`).
- Gunakan ekstensi **User Themes** untuk memuat tema GNOME Shell.
- Modifikasi wallpaper & tema GRUB sesuai preferensi Anda.

---

## 🙏 Kredit

Sebagian tema GTK & GRUB pada repositori ini **berasal atau terinspirasi oleh karya luar biasa dari:**

👉 **VinceliuIce**  
https://github.com/vinceliuice?tab=repositories  

Pastikan untuk mengecek repository beliau untuk koleksi tema Linux lainnya!

---

### 🎉 Nikmati pengalaman GNOME yang lebih indah, modern, dan konsisten!

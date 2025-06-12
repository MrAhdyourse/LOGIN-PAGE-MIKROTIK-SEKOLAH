<!--
██╗      ██████╗  ██████╗ ██╗███╗   ██╗
██║     ██╔═══██╗██╔════╝ ██║████╗  ██║
██║     ██║   ██║██║  ███╗██║██╔██╗ ██║
██║     ██║   ██║██║   ██║██║██║╚██╗██║
███████╗╚██████╔╝╚██████╔╝██║██║ ╚████║
╚══════╝ ╚═════╝  ╚═════╝ ╚═╝╚═╝  ╚═══╝
-->
<p align="center">
  <img src="https://media.giphy.com/media/3o7TKtnuHOHHUjR38Y/giphy.gif" width="300" alt="Deepweb Hacker Vibes"/>
</p>

<h1 align="center"><span style="color:#39ff14;">Loginpage Hotspot</span> <br> <span style="color:#ff0055;">SMK Nahdlatu Ulama Indramayu</span></h1>

---

> **"Access is a privilege, not a right."**

---

## 🕸️ Overview

Selamat datang di **Loginpage Hotspot** SMK Nahdlatu Ulama Indramayu.  
Proyek ini adalah halaman login hotspot dengan desain modern, efek visual misterius, dan keamanan tingkat lanjut.  
Dibuat untuk memberikan pengalaman autentik dan profesional bagi pengguna hotspot sekolah.

---

## 🧬 Fitur Utama

- 🔒 **Keamanan Tinggi**: Enkripsi password, validasi input, dan proteksi brute-force.
- 🕶️ **Tampilan Deepweb**: Efek glitch, animasi terminal, dan nuansa gelap.
- 🖥️ **Responsive**: Desain adaptif untuk desktop & mobile.
- ⚡ **Integrasi Mikrotik**: Otentikasi langsung ke router hotspot.
- 🧑‍💻 **Customizable**: Mudah diubah sesuai kebutuhan sekolah.

---

## 🌑 Demo Visual

```html
<!-- Simulasi efek terminal -->
<div style="background:#111;color:#39ff14;padding:20px;font-family:monospace;">
  <span style="color:#ff0055;">root@hotspot</span>:<span style="color:#00ffff;">~</span>$ <span style="animation:blink 1s infinite;">_</span>
  <br>
  <span style="color:#39ff14;">Authenticating...</span>
  <br>
  <span style="color:#ff0055;">Access Granted</span>
</div>
```

---

## 🛠️ Instalasi

1. **Clone Repository**
   ```bash
   git clone https://github.com/username/loginpage-hotspot-smknu.git
   cd loginpage-hotspot-smknu
   ```

2. **Konfigurasi Mikrotik**
   - Masukkan IP router dan secret API di file `.env`.

3. **Jalankan Server**
   ```bash
   npm install
   npm start
   ```

---

## 🧩 Struktur Proyek

```plaintext
loginpage-hotspot-smknu/
├── public/
│   ├── css/
│   ├── js/
│   └── index.html
├── src/
│   ├── components/
│   ├── utils/
│   └── App.js
├── .env
├── package.json
└── README.md
```

---

## 🧙‍♂️ Kode Contoh (Level Tinggi)

```python
# login_security.py
import hashlib, secrets

def hash_password(password):
    salt = secrets.token_hex(16)
    return salt + hashlib.sha256((salt + password).encode()).hexdigest()

def verify_password(stored, provided):
    salt = stored[:32]
    return stored == salt + hashlib.sha256((salt + provided).encode()).hexdigest()
```

```javascript
// terminalEffect.js
const terminal = document.getElementById('terminal');
let i = 0, txt = 'Accessing Hotspot...';
function typeWriter() {
  if (i < txt.length) {
    terminal.innerHTML += txt.charAt(i);
    i++;
    setTimeout(typeWriter, 50);
  }
}
typeWriter();
```

---

## 🧑‍💻 Kontribusi

1. Fork repo ini
2. Buat branch fitur: `git checkout -b fitur-baru`
3. Commit perubahan: `git commit -m 'Tambah fitur baru'`
4. Push ke branch: `git push origin fitur-baru`
5. Buat Pull Request

---

## 🕵️‍♂️ Efek Visual Markdown

```css
/* Efek glitch */
@keyframes glitch {
  0% { text-shadow: 2px 0 red; }
  20% { text-shadow: -2px 0 blue; }
  40% { text-shadow: 2px 2px green; }
  60% { text-shadow: -2px -2px yellow; }
  80% { text-shadow: 2px 0 purple; }
  100% { text-shadow: 0 0 white; }
}
.glitch {
  animation: glitch 1s infinite;
}
```

---

## 🧠 FAQ

**Q:** Apakah loginpage ini aman?  
**A:** Ya, menggunakan enkripsi dan validasi input.

**Q:** Bisa diintegrasikan dengan sistem lain?  
**A:** Bisa, silakan modifikasi API sesuai kebutuhan.

---

## 📜 Lisensi

MIT License © 2025 SMK Nahdlatu Ulama Indramayu

---

<p align="center">
  <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" width="200"/>
</p>

---

> _"We are not hackers. We are guardians of the network."_  
> — Admin Hotspot SMK NU Indramayu

---

<!--
███╗   ██╗██╗   ██╗
████╗  ██║██║   ██║
██╔██╗ ██║██║   ██║
██║╚██╗██║██║   ██║
██║ ╚████║╚██████╔╝
╚═╝  ╚═══╝ ╚═════╝
-->

# Apple Clone Website

Latihan mengikuti tutorial — membangun ulang landing page Apple untuk mendalami
**GSAP ScrollTrigger** dan **React Three Fiber**. Desain, copy, dan aset visualnya
milik Apple; yang saya kerjakan implementasi animasi, scroll behavior, dan
integrasi model 3D-nya.

**Stack:** React · Vite · GSAP + @gsap/react · Three.js (@react-three/fiber, drei) · Tailwind CSS

## Kenapa repo ini ada di sini

Ini bukan karya orisinal dan tidak saya ajukan sebagai portofolio. Repo ini saya
biarkan publik karena inilah tempat saya belajar hal-hal yang kemudian dipakai
di project lain: scroll-driven animation, pinned section, dan memuat model `.glb`
di React.

Yang paling sulit bukan animasinya, tapi **performa** — model `.glb` mentah
membuat halaman berat, dan versi `-transformed` di `public/models/` adalah hasil
kompresi supaya scroll tetap mulus.

Untuk melihat kode yang benar-benar saya rancang sendiri, lihat repo lain di
profil saya.

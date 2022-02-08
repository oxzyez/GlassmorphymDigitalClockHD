# Glassmorphym Digital Clock HD
membuat jam digital lagi tetapi ingin mencoba dengan versi glassmorphym atau kaca, biasanya di sebut kaca

using:
<br>HTML, CSS, JS</br>

## Mengedit / Coding

### 1. color
jadi di codingan ini gw mau kasih tau, kl cuma color yang bisa lu ubah

untuk ini bagian backgroundnya gw pake color ini dan lu bisa ganti warnanya dengan code ini di section
```html
    section {
    position: relative;
    width: 100%;
    height: 100vh;
    background: #041C32;
    display: flex;
    justify-content: center;
    align-items: center;
}
```

kl untuk bagian yang gerak yang pertama itu gw pake warna ungu gradient, dan lu bisa ganti di backgroundnya
```html
section::before {
    content: '';
    position: absolute;
    top: 10%;
    right: 20%;
    width: 300px;
    height: 300px;
    border-radius: 10px;
    background: linear-gradient(#9A0680,#160040);
    animation: animate 5s ease-in-out infinite;
}
```

untuk yang satunya lagi yang pake animation itu kan gw pake warna blue sea, lu bisa ganti warnanya di backgroundnya juga

section::after {
    content: '';
    position: absolute;
    bottom: 10%;
    left: 20%;
    width: 250px;
    height: 250px;
    border-radius: 10px;
    background: linear-gradient(#01d6ff,#0f24f9);
    animation: animate 5s ease-in-out infinite;
    animation-delay: -2.5s;
}

mau milih warna yang cocok dan keren, lu bisa ke https://colorhunt.co/

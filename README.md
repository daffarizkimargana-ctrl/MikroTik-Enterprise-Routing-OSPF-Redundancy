# 🚀 MikroTik Enterprise Routing – OSPF Redundancy
project akhir semester untuk nilai
<p align="center">

**Building Reliable, Scalable, and Resilient Enterprise Networks**

</p>

---

## 📌 Project Overview

**MikroTik Enterprise Routing – OSPF Redundancy** merupakan project simulasi jaringan enterprise yang berfokus pada implementasi dynamic routing menggunakan **OSPF (Open Shortest Path First)** serta mekanisme redundansi jaringan untuk meningkatkan keandalan komunikasi antarperangkat.

Project ini dirancang untuk memahami bagaimana sebuah infrastruktur jaringan dapat mempertahankan konektivitas ketika terjadi gangguan pada salah satu jalur komunikasi.

Dengan memanfaatkan MikroTik RouterOS, project ini mengeksplorasi konsep routing dinamis, pertukaran informasi routing, dan mekanisme pemulihan koneksi dalam lingkungan jaringan enterprise.

## 🎯 Project Objectives

- Mengimplementasikan dynamic routing menggunakan OSPF.
- Memahami proses pertukaran routing information antar-router.
- Membangun jalur komunikasi alternatif melalui redundansi.
- Memahami proses convergence ketika terjadi perubahan jaringan.
- Menguji stabilitas konektivitas ketika salah satu jalur mengalami gangguan.
- Memahami konsep high availability pada infrastruktur jaringan.

## 🛠️ Technologies & Tools

| Technology | Description |
|---|---|
| MikroTik CHR | Virtual Router |
| RouterOS | Network Operating System |
| GNS3 | Network Simulation Platform |
| OSPF | Dynamic Routing Protocol |
| Cisco IOSvL2 | Layer 2 Switching |

## ⚙️ Key Implementations

### 1. OSPF Dynamic Routing
Implementasi OSPF untuk memungkinkan router bertukar informasi routing secara otomatis tanpa harus melakukan konfigurasi static route satu per satu.

### 2. Router Identification
Konfigurasi Router ID sebagai identitas unik setiap router dalam domain OSPF.

### 3. OSPF Neighbor Relationship
Membangun hubungan adjacency antar-router agar proses pertukaran informasi routing dapat berjalan dengan baik.

### 4. Network Redundancy
Menerapkan jalur komunikasi alternatif untuk mengurangi risiko terputusnya konektivitas akibat kegagalan salah satu jalur.

### 5. Failover & Convergence Testing
Melakukan pengujian dengan memutus salah satu jalur komunikasi untuk mengamati perubahan rute dan proses pemulihan konektivitas.

## 🧪 Testing & Verification

Beberapa pengujian yang menjadi fokus project:

- Memastikan OSPF neighbor terbentuk.
- Memastikan routing table menerima rute OSPF.
- Melakukan pengujian konektivitas antarjaringan.
- Melakukan simulasi link failure.
- Mengamati perubahan jalur routing.
- Memastikan komunikasi kembali berjalan melalui jalur alternatif.

## 📚 Learning Outcomes

Melalui project ini, saya mempelajari beberapa konsep penting dalam administrasi jaringan:

- Dynamic Routing menggunakan OSPF.
- OSPF Neighbor dan Adjacency.
- Routing Table Management.
- Network Redundancy.
- Failover Mechanism.
- OSPF Convergence.
- Troubleshooting jaringan enterprise.

## 👨‍💻 Project Information

| Information | Details |
|---|---|
| Project Name | MikroTik Enterprise Routing – OSPF Redundancy |
| Platform | GNS3 |
| Router | MikroTik CHR |
| OS | RouterOS v7 |
| Switching | Cisco IOSvL2 |
| Routing Protocol | OSPF |
| Difficulty | Intermediate |
| Category | Network Engineering |

## 📝 Conclusion

Project ini merupakan salah satu bentuk implementasi pembelajaran mengenai bagaimana membangun jaringan enterprise yang lebih andal menggunakan dynamic routing dan network redundancy.

Fokus utama bukan hanya membuat perangkat saling terhubung, tetapi juga memastikan jaringan mampu beradaptasi ketika terjadi kegagalan pada jalur komunikasi.

**A network is not truly reliable just because it works, but because it can keep working when something fails.**

---

⭐ *This project is developed for educational purposes and practical network engineering experience.*

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0:090d16,20:1e1035,45:3b1d6e,75:6d28d9,100:090d16&height=260&section=header&text=Felix%20Ferdinand&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Systems%20Architecture%20%7C%20Distributed%20Platforms%20%7C%20Applied%20AI&descFontSize=18&descAlignY=60" width="100%" alt="Header Banner" />
</div>

<div align="center">
  <a href="https://github.com/felixxferdinandd">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=1000&color=C084FC&center=true&vCenter=true&width=750&height=45&lines=Low-Level+Linux+Kernel+Optimization+%26+ARM64+GKI+Builds;Distributed+Systems+Architecture+%26+High-Concurrency+Backends;Enterprise+Transactional+Engines+%26+Distributed+Locking;Applied+Edge+Machine+Learning+%26+Autonomous+Pipelines" alt="Typing Banner" />
  </a>
</div>

<div align="center">

  ![Specialization](https://img.shields.io/badge/Specialization-Digital_Business_%26_Systems_Engineering-581c87?style=flat-square)
  ![Institution](https://img.shields.io/badge/Institution-SMKN_1_Yogyakarta-3b0764?style=flat-square)
  ![Base](https://img.shields.io/badge/Base-Yogyakarta%2C_Indonesia-1e1b4b?style=flat-square)
  ![Status](https://img.shields.io/badge/Status-Active_Engineering-1e1035?style=flat-square)

  <br />

  [![Profile Views](https://komarev.com/ghpvc/?username=felixxferdinandd&label=Profile_Views&style=flat-square&color=6d28d9)](https://github.com/felixxferdinandd)
  [![Repositories](https://img.shields.io/badge/GitHub-Repositories-4338ca?style=flat-square)](https://github.com/felixxferdinandd?tab=repositories)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-3730a3?style=flat-square)](https://linkedin.com/in/felixxferdinandd)
  [![Email](https://img.shields.io/badge/Direct-Contact-1e1b4b?style=flat-square)](mailto:contact@felixferdinand.dev)

</div>

---

## 01. Professional Overview

Software Engineer dan Systems Architect dengan fokus mendalam pada bridging antara komputasi sistem tingkat rendah (*low-level bare-metal/kernel systems*) dan aplikasi backend terdistribusi berkinerja tinggi. Memiliki rekam jejak praktis dalam memodifikasi kernel Linux generic (GKI), mengelola pipeline kompilasi silang (*cross-compilation*) berbasis LLVM/Clang, serta membangun sistem digital berkonkurensi tinggi dengan jaminan integritas data ACID mutlak.

Menerapkan disiplin rekayasa berstandar enterprise:
* **Separation of Concerns:** Memisahkan logika domain inti dari adapter eksternal untuk portabilitas maksimal.
* **Deterministic Execution:** Menghindari efek samping tersembunyi (*side-effects*) dalam penjadwalan proses maupun eksekusi transaksi database.
* **Observability by Design:** Setiap modul dibangun dengan audit tracing dan metrik performa terukur sejak perancangan awal.

---

## 02. Technical Competency Matrix

| Kategori Rekayasa | Bahasa & Framework | Metodologi & Spesialisasi |
| :--- | :--- | :--- |
| **Low-Level & Subsystems** | C, C++, POSIX Shell Scripting, GNU Make | ARM64 Linux Kernel, ThinLTO, KernelSU Modules, I/O Schedulers, CPU Governor Tuning |
| **Backend Engineering** | PHP (Laravel Core), Node.js, TypeScript, Python | Asynchronous Event Loops, REST APIs, Microservices, Worker Daemons |
| **Data Stores & Caching** | MySQL, PostgreSQL, Redis, Firebase Realtime DB | Distributed Locks, Transaction Isolation Levels, Query Execution Plans, B-Tree Indexing |
| **Platform & DevOps** | Linux, Docker, Cloudflare R2 & Workers, Nginx, Git | Multi-Stage Builds, CI/CD Pipeline Automation, Reverse Proxy, Edge Metadata Caching |
| **Applied Intelligence** | Python (NumPy, Pandas), OpenCV, Edge Runtimes | Retrieval-Augmented Generation (RAG), Model Quantization, Real-Time Video Inference |

---

## 03. Core Languages & Proficiency Breakdown

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>Bahasa Pemrograman Utama</h3>
      <p><b>C / C++</b> | <i>Systems, Subsystem Modules, Kernel Architecture</i><br />
      Tingkat: Ahli / Tingkat Lanjut<br />
      Fokus: Alokasi memori manual, driver hooks, pencegahan memory leak, optimalisasi instruksi CPU.</p>
      <br />
      <p><b>PHP / Laravel</b> | <i>Enterprise Backend & Transaction Management</i><br />
      Tingkat: Ahli / Tingkat Lanjut<br />
      Fokus: Pola Dependency Injection, ORM optimization, job queue workers, otentikasi multi-tenant.</p>
      <br />
      <p><b>TypeScript / JavaScript</b> | <i>Full-Stack & Asynchronous Workers</i><br />
      Tingkat: Tingkat Lanjut<br />
      Fokus: Non-blocking I/O runtime, event-driven engines, promise orchestration, API clients.</p>
      <br />
      <p><b>POSIX Shell & Python</b> | <i>Automation, Toolchains, Data Processing</i><br />
      Tingkat: Tingkat Lanjut<br />
      Fokus: Shell deployment scripting, automasi sanitasi dataset, skrip testing regresi.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Prinsip Desain & Pola Arsitektur</h3>
      <ul>
        <li><b>High-Throughput Concurrency:</b> Mitigasi race-condition dengan distributed lock dan redis memory primitives.</li>
        <li><b>Zero-Trust Storage:</b> Verifikasi kriptografi SHA-256 pada seluruh artifak rilis biner sebelum persistensi.</li>
        <li><b>Memory Optimization:</b> Reduksi ukuran binary menggunakan compiler flag ThinLTO dan penghapusan dead-code.</li>
        <li><b>Fail-Safe Degradation:</b> Mekanisme graceful fallback ketika salah satu modul data upstream mengalami lonjakan beban.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 04. Flagship Projects & Architecture Breakdown

<details open>
<summary><b>Project 01: ForgeOTA — Enterprise Artifact & Firmware Delivery Engine</b></summary>
<br />

Infrastruktur backend otomatisasi untuk validasi, katalogisasi, dan distribusi artifak rilis custom OS dan kernel Linux tanpa intervensi manual.

| Parameter Sistem | Spesifikasi Rekayasa |
| :--- | :--- |
| **Arsitektur Utama** | Asynchronous Streaming Ingestion, Edge Storage, Event-Driven Manifest Compiler |
| **Teknologi Backend** | Node.js, TypeScript, Cloudflare R2, Redis, Docker, Tailwind CSS |
| **Throughput Latency** | Sub-40ms respon manifest parsing di seluruh jaringan edge node global |
| **Protokol Integritas** | Hash auditing SHA-256 secara streaming sebelum file disimpan permanen |
| **Repositori Kode** | [felixxferdinandd/forgeota-engine](https://github.com/felixxferdinandd) |

**Sorotan Teknis:**
* Mengatasi bottleneck upload file biner besar (>1 GB) dengan memisahkan channel data transfer langsung ke bucket storage berbasis presigned URL bertarget pendek.
* Mengurangi waktu siklus pengujian dari kompilasi lokal hingga distribusi end-user dari semula beberapa jam menjadi di bawah 45 detik.

</details>

<details open>
<summary><b>Project 02: Anxinity Kernel — Optimized Linux Subsystem for ARM64</b></summary>
<br />

Modifikasi dan perakitan distribusi kernel Linux Generic Kernel Image (GKI) yang berfokus pada stabilitas thread scheduler, efisiensi energi, dan integrasi subsistem modern.

| Parameter Sistem | Spesifikasi Rekayasa |
| :--- | :--- |
| **Basis Kode** | Linux Kernel Source Tree (ARM64 Architecture) |
| **Toolchain Kompilasi** | Android NDK Clang/LLVM, GNU Make, AnyKernel3 Packaging |
| **Penyebaran Produksi** | Berjalan aktif pada 10,000+ perangkat bergerak produksi di berbagai belahan dunia |
| **Hasil Benchmarking** | Penurunan frame drop sebesar 18% dan perbaikan kurva thermal throttling hingga 14% |
| **Repositori Kode** | [felixxferdinandd/kernel_infinix_mt6789](https://github.com/felixxferdinandd) |

**Sorotan Teknis:**
* Mengintegrasikan subsistem KernelSU Next secara inline langsung ke dalam image kernel biner tanpa merusak verifikasi integritas runtime bawaan sistem operasi.
* Menerapkan backport patch scheduler upstream untuk memastikan alokasi proses foreground mendapatkan prioritas core CPU tertinggi saat beban komputasi memuncak.

</details>

<details>
<summary><b>Project 03: High-Concurrency Event Ticketing & Matrix Allocation Core</b></summary>
<br />

Sistem reservasi berbasis cloud yang dirancang untuk mengeliminasi benturan pemilihan kursi (*seat-locking conflict*) saat terjadi lonjakan traffic massal.

| Parameter Sistem | Spesifikasi Rekayasa |
| :--- | :--- |
| **Arsitektur Utama** | Two-Phase Commit Lock, In-Memory Realtime Buffer, Master SQL Store |
| **Teknologi Backend** | PHP, Laravel Framework, MySQL, Firebase Realtime Database, Redis |
| **Skala Beban** | Menangani ribuan pemilihan slot kursi paralel dalam interval jendela satu detik |
| **Integritas Data** | Garansi 100% konsistensi kursi tanpa insiden duplicate-booking |
| **Repositori Kode** | [felixxferdinandd/ticket-reservation-core](https://github.com/felixxferdinandd) |

**Sorotan Teknis:**
* Pemisahan state lock visual (disajikan melalui memory store real-time berlatensi ultra-rendah) dengan status transaksi final (diproses oleh transaksi ACID SQL).
* Otomasi pembatalan reservasi jika pengguna gagal menyelesaikan transaksi pembayaran dalam batas waktu window yang ditentukan.

</details>

---

## 05. Artificial Intelligence & Computational Engineering

<table width="100%">
  <thead>
    <tr>
      <th align="left">Bidang AI</th>
      <th align="left">Fokus Implementasi</th>
      <th align="left">Teknologi Terkait</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Retrieval-Augmented Generation (RAG)</b></td>
      <td>Perancangan pipeline pencarian dokumen semantik, vektorisasi teks terstruktur, dan integrasi agen LLM enterprise untuk ekstraksi wawasan kontekstual.</td>
      <td>Vector Stores, Python, REST Gateways</td>
    </tr>
    <tr>
      <td><b>Computer Vision Edge Inference</b></td>
      <td>Optimasi pipeline pemrosesan frame video real-time, segmentasi bounding-box objek deterministik, dan reduksi komputasi per-frame.</td>
      <td>OpenCV, ONNX Runtimes, C++ Bindings</td>
    </tr>
    <tr>
      <td><b>Automated Data Pipelines</b></td>
      <td>Sanitasi data tabular massal, deteksi anomali deret waktu (*time-series*), dan normalisasi metrik analitik kompetitif.</td>
      <td>Pandas, NumPy, Automated Workers</td>
    </tr>
  </tbody>
</table>

---

## 06. Professional Experience & Leadership

### Systems Architect & Core Maintainer
**Project Anxinity** | *2024 — Sekarang*
* Mengelola arsitektur toolchain kompilasi biner Linux ARM64 dengan integrasi ThinLTO.
* Mengawasi siklus rilis kernel untuk ribuan pengguna global, mencakup troubleshooting bug kernel-panic, patch scheduling, dan memory tuning.
* Mengotomatiskan alur kerja pengujian biner menggunakan skrip POSIX Shell dan pipeline GitHub Actions.

### Backend Infrastructure Specialist
**Widyaprasthiekatama Tech Hub** | *2025 — Sekarang*
* Merancang skema basis data relasional untuk sistem manajemen operasional institusi skala besar.
* Membangun modul API berkecepatan tinggi dengan autentikasi berbasis role dan isolasi hak akses data yang ketat.
* Mengawal stabilitas server pada saat event-event besar dengan beban konkurensi traffic puncak.

---

## 07. Honors, Achievements & Milestones

| Pengakuan / Pencapaian | Lingkup & Dampak |
| :--- | :--- |
| **Director of Digital Infrastructure** | Memimpin perancangan dan operasional sistem ticketing terintegrasi untuk event SKAONEFEST 2026. |
| **Kernel Distribution Milestone** | Menembus batas 10,000+ perangkat aktif untuk distribusi kernel custom open-source berbasis ARM64. |
| **Esports Quantitative Strategist** | Merancang model kalkulasi data performa makro dan mikro untuk divisi Mobile Legends: Bang Bang kompetitif. |
| **Top Academic Standing** | Meraih pengakuan akademis tertinggi dalam konsentrasi Bisnis Digital & Rekayasa Sistem di SMKN 1 Yogyakarta. |

---

## 08. Verified Certifications & Continuous Learning

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>Cloud & Infrastruktur Terdistribusi</h3>
      <ul>
        <li><b>AWS Certified Solutions Architect – Associate</b><br />Desain sistem high-availability, redundansi multi-region, dan mitigasi disaster recovery.</li>
        <li><b>AWS Certified Cloud Practitioner</b><br />Prinsip dasar keamanan IAM, arsitektur serverless, dan tata kelola biaya cloud.</li>
        <li><b>Oracle Cloud Infrastructure Foundations</b><br />Topologi komputasi cloud korporat, virtual cloud network, dan block volumes.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>Jaringan, Database & Algoritma</h3>
      <ul>
        <li><b>Oracle Certified Professional: MySQL Developer</b><br />Optimasi query indexing, isolasi transaksi, dan arsitektur basis data relasional.</li>
        <li><b>Cisco CCNA: Enterprise Networking</b><br />Perutean paket IPv4/IPv6, segmentasi VLAN, dan troubleshooting topologi jaringan.</li>
        <li><b>NPTEL: Data Structures & Algorithms</b><br />Analisis kompleksitas asimtotik, graf, pohon biner, dan pemrograman dinamis.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 09. Coding Profiles & Evaluation Platforms

<div align="center">

| Platform Evaluasi | Fokus Teknis Utama | Akses Tautan |
| :--- | :--- | :---: |
| **LeetCode** | Algoritma, Optimasi Kompleksitas Ruang & Waktu | [Profil LeetCode](https://leetcode.com) |
| **HackerRank** | Sintaksis Lanjut, Rekayasa Kueri SQL Kompleks | [Profil HackerRank](https://hackerrank.com) |
| **GeeksforGeeks** | Implementasi Struktur Data & Prinsip Sistem Inti | [Profil GeeksforGeeks](https://geeksforgeeks.org) |
| **CodeChef** | Logika Komputasi Tingkat Tinggi & Matematika Diskrit | [Profil CodeChef](https://codechef.com) |

</div>

---

## 10. Active Engineering Telemetry

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>Riset yang Sedang Berjalan</h3>
      <ul>
        <li>
          <b>eBPF Kernel Instrumentation:</b><br />
          Analisis alur system calls secara real-time langsung dari dalam ring-0 tanpa overhead context-switch tambahan.
        </li>
        <br />
        <li>
          <b>Distributed Consensus Mechanics:</b><br />
          Pengujian toleransi kesalahan data antara algoritma Raft dan Paxos pada skenario latensi jaringan yang tidak stabil.
        </li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>Fokus Pembangunan Aktif</h3>
      <ul>
        <li>
          <b>ForgeOTA Engine v2:</b><br />
          Implementasi direct edge workers untuk eliminasi server origin saat proses parsing metadata artifak.
        </li>
        <br />
        <li>
          <b>Zero-Copy Message Ledger:</b><br />
          Eksperimen buffer pertukaran data antrean pesan menggunakan memory-mapped files di level subsistem operasi.
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <b>Filosofi Rekayasa:</b> <code>Determinism Over Assumptions</code> • <code>Zero-Trust Security</code> • <code>Explicit Auditing</code> • <code>Graceful Failure</code>
    </td>
  </tr>
</table>

---

## 11. Professional Inquiries & Collaboration

<div align="center">

  [![Status](https://img.shields.io/badge/STATUS-OPEN_FOR_COLLABORATION-581c87?style=for-the-badge)](https://github.com/felixxferdinandd)
  [![Focus](https://img.shields.io/badge/FOCUS-SYSTEMS_%26_BACKEND-3b0764?style=for-the-badge)](https://github.com/felixxferdinandd)
  [![Location](https://img.shields.io/badge/LOCATION-YOGYAKARTA%2C_INDONESIA-1e1b4b?style=for-the-badge)](https://github.com/felixxferdinandd)

  <br /><br />

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-4338ca?style=flat-square)](https://linkedin.com/in/felixxferdinandd)
  [![Email](https://img.shields.io/badge/Email-Direct_Message-3730a3?style=flat-square)](mailto:contact@felixferdinand.dev)
  [![GitHub](https://img.shields.io/badge/GitHub-felixxferdinandd-1e1b4b?style=flat-square)](https://github.com/felixxferdinandd)

  <br /><br />
  <p><i>"Simplicity is prerequisite for reliability; elegance is the consequence of disciplined systems engineering."</i></p>

  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0:090d16,25:1e1035,50:3b1d6e,75:5b21b6,100:090d16&height=120&section=footer" width="100%" alt="Footer Banner" />

</div>

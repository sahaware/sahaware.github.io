---
name: 🚀 Feature / Task Request (AI-Friendly)
about: Deskripsi terstruktur untuk perencanaan dan pengembangan fitur
title: '[FEAT/TASK]: '
labels: 'enhancement, roadmap'
assignees: ''
---

## 📌 Deskripsi Ringkas
<!-- Berikan 1-2 kalimat ringkasan tentang apa yang ingin dicapai -->
**Tujuan:** [Contoh: Implementasi sistem autentikasi OAuth2 dengan Google]

## 🎯 Mengapa Ini Penting? (Context & Value)
<!-- Jelaskan masalah yang diselesaikan atau nilai tambahnya bagi pengguna/sistem -->
- **Masalah/Kebutuhan:** [Contoh: Pengguna kesulitan login manual]
- **Value:** [Contoh: Meningkatkan retensi user hingga 20%]

## 📝 Detail Teknis & Kriteria Penerimaan (Acceptance Criteria)
<!-- AI membutuhkan poin-poin spesifik untuk memecah tugas menjadi sub-task -->
- [ ] 1. [Deskripsi teknis spesifik]
- [ ] 2. [Deskripsi teknis spesifik]
- [ ] 3. [Kriteria keberhasilan/testing]

## 🛠️ Komponen/Area Terdampak
<!-- Sebutkan file, modul, atau API yang relevan agar AI paham konteks kode -->
- **Frontend:** [Contoh: `src/components/LoginButton.js`]
- **Backend:** [Contoh: `src/auth/oauth.py`]
- **Database:** [Contoh: Update tabel `users`]

## 📋 Referensi / Sumber Daya
<!-- Link ke dokumen teknis, desain, atau contoh API -->
- Dokumen API: [Link]
- Desain UI/UX: [Link]

## ⏱️ Estimasi Waktu (Opsional)
- [Contoh: 2-3 Hari]

## Mengapa Template Ini Efektif untuk AI?
- Struktur Terpisah (Separation of Concerns): AI lebih mudah memproses informasi yang dibagi menjadi konteks, kebutuhan teknis, dan komponen terdampak.
- Kriteria Penerimaan (Checklist): Menggunakan format [ ] (Markdown checklist) memungkinkan AI memecah tugas besar menjadi unit kerja terkecil yang bisa dikerjakan (atomic tasks)
- Konteks ## 🛠️ Komponen/Area Terdampak: Dengan menyebutkan file atau modul tertentu, AI dapat melakukan pemindaian (scanning) kode yang relevan dengan lebih cepat, mengurangi halusinasi.
- Judul Spesifik: Judul yang diawali dengan tipe issue ([FEAT], [BUG], [DOCS]) mempermudah AI dalam triase otomatis.

## Tips Tambahan agar AI Lebih Maksimal 
- Gunakan Bahasa Inggris: Meskipun AI paham bahasa Indonesia, instruksi teknis dalam bahasa Inggris umumnya memberikan hasil yang lebih akurat.
- Gunakan Label: Gunakan label ai-triage atau needs-review untuk memicu agent AI di GitHub Actions.
- CLAUDE.md: Buat file CLAUDE.md di root repositori untuk memberikan panduan coding style dan aturan main kepada AI agar issue yang diselesaikan sesuai dengan standar proyek Anda

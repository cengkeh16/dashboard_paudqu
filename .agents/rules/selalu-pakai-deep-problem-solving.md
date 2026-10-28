---
name: selalu-pakai-deep-problem-solving
description: Wajibkan metodologi 6 tahap skill deep-problem-solving untuk setiap investigasi, debugging, dan perbaikan di proyek ini. Selalu aktif tanpa perlu dipanggil.
trigger: model_decision
---

# Selalu Pakai Deep Problem Solving

Setiap tugas yang menyangkut **pencarian masalah, error, perilaku aneh, atau perbaikan sistem** di proyek ini (dashboard, workflow n8n, API, Google Sheets, data santri/nilai) **WAJIB** mengikuti metodologi 6 tahap dari skill `deep-problem-solving` (.agents/skills/deep-problem-solving/SKILL.md):

1. **Understand** — pahami tujuan dan fakta vs asumsi
2. **Investigate** — temukan akar masalah dari bukti nyata (sheet, log, eksekusi n8n, API) SEBELUM mengubah kode
3. **Plan** — rencanakan perubahan terkecil yang mungkin, jelaskan risikonya
4. **Execute** — lakukan perubahan minimal, jangan hapus fitur yang berjalan
5. **Verify** — uji hasilnya, jangan klaim sukses tanpa bukti
6. **Report** — laporkan akar masalah + perubahan + hasil uji dalam Bahasa Indonesia

## Pemicu (kapan rule ini berlaku)

- User melaporkan error, kegagalan, atau hasil yang tidak sesuai harapan
- Task mengandung kata: kenapa, gagal, error, rusak, salah, tidak berfungsi, periksa, cek, investigasi, debugging
- Perubahan pada workflow n8n (WF-01 s.d. WF-04), webhook, sheet, atau kode dashboard

## Larangan

- ❌ Mengubah kode/config sebelum akar masalah teridentifikasi dari bukti
- ❌ Menebak penyebab tanpa membaca data nyata (sheet, eksekusi, log)
- ❌ Mengulang pendekatan yang sudah terbukti gagal tanpa bukti baru
- ❌ Mengklaim "sudah diperbaiki" tanpa verifikasi
- ❌ Menghapus fitur atau mengubah perilaku yang sudah berjalan baik

## Pengecualian

Untuk pertanyaan ringan (bukan debugging) — misalnya menjelaskan konsep, tanya cara pakai, atau tugas tulis-menulis — cukup jawab langsung tanpa 6 tahap.

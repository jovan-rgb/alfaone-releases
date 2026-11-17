# AlfaOne — Download IPA

Halaman distribusi publik untuk build IPA **AlfaOne untuk iPhone**.

- **Download:** https://github.com/jovan-rgb/alfaone-releases/releases/latest/download/AlfaOneRebuild-unsigned.ipa
- **Landing page:** https://jovan-rgb.github.io/alfaone-releases/
- **Checksum:** `AlfaOneRebuild-unsigned.ipa.sha256` di halaman rilis

## Status build

| Item | Nilai |
| --- | --- |
| Versi | 0.1.1 (2) — build terbaru |
| Minimum iOS | 15.0 |
| Arsitektur | arm64 (iPhone) |
| Ukuran | ± 217 KB |
| Status | **unsigned** — perlu di-sign sebelum install |
| Bundle ID | `com.ric.alfaone.rebuild` |

> Checksum tersedia sebagai asset `AlfaOneRebuild-unsigned.ipa.sha256` di setiap rilis dan
> diperbarui otomatis oleh workflow build.

## Cara install

1. Download file `.ipa`.
2. Pasang **Sideloadly** (Windows/macOS) atau **AltStore**.
3. Hubungkan iPhone, login Apple ID, pilih IPA, lalu mulai signing/install.
4. Di iPhone: **Settings → General → VPN & Device Management** → Trust developer.
5. Buka app **AlfaOne**.

Apple ID gratis: berlaku **7 hari**, perlu re-sign. Apple Developer berbayar: **1 tahun**.

## Catatan

- File ini **unsigned** dan tidak berasal dari App Store.
- Aplikasi membungkus situs intranet AlfaOne; login/SSO dan hak akses tetap mengikuti sistem resmi SAT.
- Fitur native (push notification, biometric login, bridge absensi) belum diport.
- Source code berada di repo privat `jovan-rgb/alfaone-api`.
- Gunakan hanya untuk sistem yang memang berhak kamu akses.

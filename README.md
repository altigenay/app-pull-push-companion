# Basic File Manager · Basit Dosya Yöneticisi

A file manager for Android phones, tablets and TVs. The app shows Turkish on a Turkish device and English everywhere else.

| Build | File | For |
|---|---|---|
| Phone / tablet, 64-bit ARM | `basic-file-manager-phone.apk` | Most phones and tablets; includes online storage |
| Phone / tablet, 32-bit ARM | `basic-file-manager-phone-arm32.apk` | Older or budget devices; includes online storage |
| TV | `basic-file-manager-tv.apk` | Android TV / Google TV / Fire TV, remote control, two panes; small, no online storage |

Every release has `latest.json`: version, file names, SHA-256 digests and sizes. The app checks it for updates (at most every 12 hours, can be turned off in ⋮). On Wi-Fi it downloads the update, checks the SHA-256, and opens Android's installer.

## Features

- Browse, copy, move, delete, rename, new folder, zip and unzip, search, sort, hidden files, bookmarks, library (images, videos, audio, documents, archives, APKs, recent, large files), storage analysis, text editor.
- Internal storage, SD cards and USB drives. Open with other apps, share, install APKs.
- App manager: uninstall, APK backup, close in background, sleep list (apps closed again after every start).
- Network: share files with a browser or FTP on the same Wi-Fi; open FTP servers in a pane.
- **Online storage** (phone/tablet): Google Drive, OneDrive, Dropbox, pCloud, Box, Yandex Disk, MEGA, WebDAV (Nextcloud, ownCloud), SFTP, SMB, through [rclone](https://rclone.org) (MIT). You sign in on the service's own page in the browser.
- **Root** (rooted devices): browse and edit /data, /system and the rest of the file system through `su`.
- Answers ADB-only queries (app names and icons, storage, battery); other apps on the device cannot use that channel.

No ads, no trackers.

---

# Basit Dosya Yöneticisi

Android telefon, tablet ve TV için dosya yöneticisi. Cihaz Türkçe ise Türkçe, değilse İngilizce görünür.

- **Telefon/tablet:** 64-bit ARM için `basic-file-manager-phone.apk`, 32-bit ARM için `basic-file-manager-phone-arm32.apk`. İkisinde de çevrimiçi depolama var.
- **TV:** `basic-file-manager-tv.apk`. Küçüktür, kumandayla iki panel kullanılır, çevrimiçi depolama yoktur.

Uygulama `latest.json` ile en fazla 12 saatte bir güncelleme denetler; bu ⋮ menüsünden kapatılabilir. Wi-Fi'deyken güncellemeyi indirir, SHA-256 özetini doğrular ve Android'in yükleyicisini açar.

## Özellikler

- **Dosyalar:** gezme, kopyalama, taşıma, silme, zip, arama, kütüphane, yer imleri, bellek analizi ve metin düzenleyici.
- **Uygulama yöneticisi:** APK yedeği, arka planda kapatma ve uyutma.
- **Ağ:** tarayıcıdan ya da FTP ile paylaşım; FTP sunucularını panelde açma.
- **Çevrimiçi depolama:** Google Drive, OneDrive, Dropbox, pCloud, Box, Yandex, MEGA, WebDAV, SFTP ve SMB. Bu özellik rclone ile çalışır; giriş hizmetin kendi sayfasında yapılır.
- **Root:** rootlu cihazda /data, /system gibi klasörleri gezme ve düzenleme.

Reklam ve izleyici yoktur.

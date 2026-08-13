# GeoManager Pro — downloads

Official installer downloads for **GeoManager Pro**, a Windows desktop app that
pins any location on a map and makes every site in your browser report that
exact location and timezone.

**Product page & documentation:** https://themetechofficial.web.app/product/geomanager-pro

## Download

Get the latest installer from the [**Releases**](../../releases/latest) page.

| File | Notes |
| ---- | ----- |
| `GeoManagerPro-<version>-x64-setup.exe` | Standard installer — use this one |
| `GeoManagerPro-<version>-x64.msi` | For managed / silent deployment |

Windows 10 or 11, 64-bit.

## A licence key is required

The installer is a free download, but the app opens on an activation screen and
stays locked until a valid licence key is entered. There is no trial or limited
mode. Buy a key on Telegram: [@osopvdeveloper](https://t.me/osopvdeveloper)

## Verifying your download

Each release lists a SHA-256 checksum. Check the file you downloaded matches:

```powershell
certutil -hashfile GeoManagerPro-1.1.16-x64-setup.exe SHA256
```

The build is not code-signed yet, so Windows SmartScreen shows “Windows
protected your PC”. Click **More info → Run anyway**. Verifying the checksum
above confirms the file is the one we published.

---

This repository hosts release binaries only; the application source is not public.

© ThemeTech Official

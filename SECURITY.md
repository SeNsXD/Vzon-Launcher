# Security Policy & Privacy Architecture

## Our Security Commitment

At **xdNOT Labs**, security and user privacy are foundational pillars of **Vzon Launcher**. We believe that your home screen launcher—the software interface you touch dozens of times every single day—must adhere to the highest standards of data isolation, local-only processing, and transparency.

---

## 🛡️ The Zero-Telemetry Guarantee

Vzon Launcher is architected from the ground up to respect your digital sovereignty:

1. **Zero Tracking SDKs:** Vzon contains **no** third-party analytics (no Google Analytics, Firebase Analytics, Adjust, AppsFlyer, or telemetry frameworks).
2. **Zero Advertising:** Absolutely no ad networks, tracking beacons, or monetized data harvesting SDKs are present in any build.
3. **100% On-Device Processing:** App search ranking, suggested app algorithms, layout management, and icon indexing execute entirely on your device hardware.
4. **Coarse-Only Location Access:** Weather data is fetched directly from [Open-Meteo](https://open-meteo.com/) using coarse coordinates. Exact GPS coordinates are never stored, logged, or transmitted.
5. **No Notification Content Reading:** Notification listener permissions are utilized solely to observe active media session playback (title, artist, album art) and provide notification history count. The textual content of incoming private chat messages is never saved, read, or sent off-device.
6. **Encrypted Cloud Backup Exclusion:** Sensitive cached weather coordinates and private token states are excluded from Android OS cloud backup archives via `data_extraction_rules.xml`.

---

## Supported Versions

Security and stability patches are provided for the following releases:

| Version | Status | Supported |
|---|---|---|
| `v1.x` (Current Release / Beta) | Active Development | ✅ Yes |
| Pre-release APK Betas | Active Testing | ✅ Yes |
| Legacy Builds (< 1.0) | Deprecated | ❌ No |

---

## Reporting a Security Vulnerability

If you believe you have discovered a security vulnerability or privacy concern within Vzon Launcher, please notify us responsibly:

1. **Email:** Contact the core developer directly at `75002933+SeNsXD@users.noreply.github.com` with the subject line `[SECURITY] Vzon Launcher Vulnerability Report`.
2. **Details to Include:**
   - Detailed summary of the potential vulnerability.
   - Exact APK version and build number.
   - Proof-of-concept steps or ADB logs demonstrating the vulnerability.
   - Impact assessment on user privacy or system security.
3. **Response Timeline:** We commit to acknowledging receipt of your report within **48 hours** and will provide regular updates regarding our triage and remediation timeline.

Please do **not** file public GitHub issues for unresolved security vulnerabilities.

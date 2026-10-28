# Privacy Policy — VaultLink

**Last updated:** October 28, 2026

Kenny Lee ("we", "us") operates the mobile application **VaultLink**. This page explains how we handle information when you use the app.

## Summary

VaultLink is an account and sign-in vault. Your vault is encrypted on your device with a master password that we never receive. If you sign in with Google, a copy of that ciphertext can sync so your other devices can download it. We cannot read your passwords, names, or other vault contents.

There are no ads, no analytics, and no telemetry. The encryption has not been independently audited.

## Information we handle

### Google account

If you sign in with Google, authentication is handled by Supabase. We receive the email address and user id that Google and Supabase provide, and we use them only to know which encrypted vault belongs to you.

The master password is entered only on the device. It is not sent to us, to Google, or to Supabase.

### Vault contents

Sign-in details, passwords, personal details, profiles, relationships, trash, and previous passwords are encrypted on the device before they are saved (Argon2id and XChaCha20-Poly1305). The cloud row stores only that ciphertext, a revision number, and the time it was updated. A copy of the database does not reveal the vault contents.

An extra device-bound Android Keystore layer protects the local file. That layer is not uploaded.

### Biometrics

Optional fingerprint or face unlock wraps the vault key in the Android Keystore on the device. Biometric templates stay with the operating system. We do not receive them. After a reboot, or after biometric enrollment changes, the app asks for the master password again.

### Autofill

If you set VaultLink as Android's autofill service, the app can fill sign-in fields in other apps and browsers after you unlock or confirm. Filling does not upload those credentials.

The app declares Android's user-dictionary permission because of autofill integration. Our code does not read or upload your dictionary.

## Permissions

| Permission | Purpose |
|------------|---------|
| Internet | Google sign-in and encrypted sync |
| Biometric | Optional unlock on this device |
| User dictionary | Declared for Android autofill compatibility; not read by our code |

## Sharing

We do not sell personal data.

Google processes sign-in under [Google's Privacy Policy](https://policies.google.com/privacy). Supabase hosts the authentication account and the encrypted vault row. We do not share vault contents with anyone else, because we cannot read them.

## Retention and deletion

Local vault files stay on the device until you clear the app's storage or uninstall it. Signing out removes the session on that device and leaves the local ciphertext in place.

To delete the cloud account and the encrypted vault row, email [lee.mh.kenny@gmail.com](mailto:lee.mh.kenny@gmail.com?subject=Delete%20my%20VaultLink%20account) from the Google account you use in the app and ask us to delete your VaultLink account. We delete the Supabase user and the ciphertext row. A device that still has a local copy keeps that copy until you clear app data or uninstall.

Inside the app, open the account screen and choose **Request cloud account deletion**. That opens this request. It does not erase a local copy by itself.

## Children

VaultLink is not directed at children under 13. We do not knowingly collect personal information from children.

## Changes

We may update this policy. The "Last updated" date at the top will change when we do.

## Contact

**Email:** [lee.mh.kenny@gmail.com](mailto:lee.mh.kenny@gmail.com)

---

## 隱私權政策 — VaultLink（繁體中文）

**最後更新：** 2026 年 10 月 28 日

Kenny Lee（「我們」）營運 **VaultLink**。本頁說明使用這個應用程式時，資料如何被處理。

### 摘要

VaultLink 是帳號與登入資料保險庫。保險庫在你的裝置上以主密碼加密，我們收不到這組主密碼。若你使用 Google 登入，加密後的副本可以同步，讓其他裝置下載。我們讀不到你的密碼、姓名或其他保險庫內容。

沒有廣告、沒有分析、沒有遙測。加密尚未經過獨立稽核。

### 我們處理的資料

- **Google 帳號：** 登入由 Supabase 處理。我們收到 Google 與 Supabase 提供的電子郵件與使用者識別碼，只用來對應哪一份加密保險庫屬於你。主密碼只在裝置上輸入，不會送到我們、Google 或 Supabase。
- **保險庫內容：** 登入資料、密碼、個人資料、設定檔、關係、垃圾桶與先前的密碼，都先在裝置上加密再儲存。雲端只保存密文、版本號與更新時間。資料庫副本無法還原保險庫內容。本機檔案另有一層裝置綁定的 Android Keystore，這一層不會上傳。
- **生物辨識：** 指紋或臉部解鎖把金鑰包在裝置上的 Android Keystore。生物辨識範本留在作業系統，我們收不到。重新開機或變更生物辨識登錄後，應用程式會再要求主密碼。
- **自動填入：** 若你把 VaultLink 設為 Android 自動填入服務，解鎖或確認後可以填入其他應用程式與瀏覽器的登入欄位。填入不會上傳那些憑證。應用程式因自動填入整合而宣告使用者字典權限；我們的程式不會讀取或上傳字典。

### 權限

| 權限 | 用途 |
|------|------|
| 網際網路 | Google 登入與加密同步 |
| 生物辨識 | 在這部裝置上選擇性解鎖 |
| 使用者字典 | 為 Android 自動填入相容性而宣告；我們的程式不會讀取 |

### 分享

我們不出售個人資料。Google 依其隱私權政策處理登入。Supabase 代管驗證帳號與加密保險庫資料列。我們無法閱讀保險庫內容，也不會把內容分享給其他人。

### 保留與刪除

本機保險庫會留在裝置上，直到你清除應用程式儲存空間或解除安裝。登出只會移除這部裝置上的工作階段，本機密文仍會留下。

若要刪除雲端帳號與加密保險庫資料列，請用你在應用程式裡使用的 Google 帳號寄信到 [lee.mh.kenny@gmail.com](mailto:lee.mh.kenny@gmail.com?subject=Delete%20my%20VaultLink%20account)，要求刪除 VaultLink 帳號。我們會刪除 Supabase 使用者與密文資料列。裝置上仍留著的本機副本，要等你清除應用程式資料或解除安裝才會消失。

在應用程式裡開啟帳號畫面，點 **要求刪除雲端帳號**，就會開啟這項請求。這個動作本身不會清除本機副本。

### 兒童

VaultLink 不以 13 歲以下兒童為對象。

### 聯絡

**電子郵件：** [lee.mh.kenny@gmail.com](mailto:lee.mh.kenny@gmail.com)

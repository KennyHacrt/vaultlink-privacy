# Privacy Policy — VaultLink

**Last updated: November 12, 2026**

Kenny Lee operates VaultLink. This policy covers our Android application and planned iOS release.

VaultLink encrypts vault contents on your device before local storage or cloud sync. The master password and recovery key are not sent to us or Supabase. Encryption has not been independently audited.

## Accounts and sync

Google or Apple sign-in identifies the owner of an encrypted vault through Supabase. We process the provider identity, email when supplied, user ID, authentication tokens and encrypted vault revision metadata. Apple may provide a private relay email. Account login does not replace the separate master password. Supabase holds the authentication account and ciphertext; the app does not send readable vault contents to that service.

## Device protection

Android uses Keystore and iOS uses device-only Keychain protection. Biometric templates remain with the operating system. iOS AutoFill shares only a short-lived encrypted snapshot between VaultLink and its credential provider extension, protected by a separate biometric key. Passwords are released to the selected login field only after authorization and selection. It does not send those passwords to advertising or subscription providers. Sensitive iOS clipboard copies expire after 30 seconds and are restricted to the local device; another app may already have read a copied value.

## Advertising

The current release is free and contains no advertising, tracking, in-app purchases, AdMob SDK or RevenueCat SDK. We do not collect advertising identifiers, ad interactions or purchase history. Future paid features will require a separate release and updated disclosures before activation.

## Retention and deletion

When signed in, Account → Delete cloud account asks for confirmation. Apple-linked accounts additionally reauthorize with Apple so that the grant can be revoked. Deletion removes the Supabase account and encrypted server vault. Local encrypted copies on enrolled devices remain until removed from those devices; signing out does not erase them. If the in-app route is unavailable, contact lee.mh.kenny@gmail.com from the account email to request deletion.

We do not sell vault contents. Providers process service data under their policies: [Apple](https://www.apple.com/legal/privacy/), [Google](https://policies.google.com/privacy), [Supabase](https://supabase.com/privacy). Contact: lee.mh.kenny@gmail.com. VaultLink is not directed at children under 13.

---

## 隱私權政策 — VaultLink（繁體中文）

**最後更新：2026 年 11 月 12 日**

Kenny Lee 營運 VaultLink。本政策涵蓋 Android 應用程式及準備發佈的 iOS 版本。

VaultLink 先在裝置上加密保險庫，再儲存或同步。主密碼與復原金鑰不會傳送給我們或 Supabase。加密尚未經獨立稽核。

### 帳號及同步

 Google 或 Apple 登入透過 Supabase 識別加密保險庫的擁有者。我們處理登入身分、供應商提供的電郵、使用者識別碼、驗證權杖及密文版本資訊；Apple 可能提供隱藏電郵。登入帳號不取代主密碼。Supabase 保存帳號及保險庫密文，不接收可讀取的保險庫內容。

### 裝置保護

 Android 使用 Keystore，iOS 使用綁定裝置的 Keychain。生物辨識範本留在作業系統。iOS 自動填入透過獨立生物辨識金鑰保護短期加密副本，在授權及選擇後才將密碼填入登入欄位。密碼不會傳給廣告或訂閱服務。iOS 敏感剪貼簿限制在本機並於 30 秒後到期，但其他程式可能已讀取複製內容。

### 廣告與購買

目前版本免費，沒有廣告、追蹤、應用程式內購買、AdMob SDK 或 RevenueCat SDK。我們不收集廣告識別碼、廣告互動或購買紀錄。未來付費功能將在另一版本實作並更新相關聲明後才啟用。

### 保留與刪除

 登入後可在帳號頁選擇刪除雲端帳號並確認。連結 Apple 的帳號須再次授權，以撤銷 Apple 登入許可。刪除會移除 Supabase 帳號及雲端密文；各裝置既有的本機加密副本仍會保留，需在各裝置移除。登出不會清除本機副本。若應用程式刪除功能無法使用，可由帳號電郵聯絡 lee.mh.kenny@gmail.com。

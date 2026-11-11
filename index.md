# Privacy Policy — VaultLink

**Last updated: November 12, 2026**

Kenny Lee operates VaultLink. This policy covers our Android application and planned iOS release.

VaultLink encrypts vault contents on your device before local storage or cloud sync. The master password and recovery key are not sent to us, Supabase, RevenueCat or AdMob. Encryption has not been independently audited.

## Accounts and sync

Google or Apple sign-in identifies the owner of an encrypted vault through Supabase. We process the provider identity, email when supplied, user ID, authentication tokens and encrypted vault revision metadata. Apple may provide a private relay email. Account login does not replace the separate master password. Supabase holds the authentication account and ciphertext; the app does not send readable vault contents to that service.

## Device protection

Android uses Keystore and iOS uses device-only Keychain protection. Biometric templates remain with the operating system. iOS AutoFill shares only a short-lived encrypted snapshot between VaultLink and its credential provider extension, protected by a separate biometric key. Passwords are released to the selected login field only after authorization and selection. It does not send those passwords to advertising or subscription providers. Sensitive iOS clipboard copies expire after 30 seconds and are restricted to the local device; another app may already have read a copied value.

## Premium subscriptions

Apple handles payment. RevenueCat checks purchase receipts, product and transaction information, entitlement status, an automatically generated app user identifier, and associated technical metadata to provide purchase and restore functionality. We do not send your vault or Supabase account identity to RevenueCat. We do not receive your payment card details. Cancelling a subscription is managed in the App Store and is separate from deleting a VaultLink cloud account. Vault access and autofill remain free.

## Advertising

The free iOS edition can display one Google AdMob banner on Settings. Premium removes it. No advertisements appear in vault lists, item details or the autofill extension. The app requests non-personalized ads after the applicable consent check. Google may process IP-derived approximate location, device/app identifiers and technical data, ad interactions and performance data for ad delivery, measurement and fraud prevention. Non-personalized advertising still involves data processing. The app does not supply vault contents, names, emails, search terms or saved website addresses to AdMob, and it does not request Apple's advertising tracking permission. Where required, Settings provides advertising privacy choices so users can revisit their decision. There is no separate app analytics service; advertising and subscription SDK processing is described here.

## Retention and deletion

When signed in, Account → Delete cloud account asks for confirmation. Apple-linked accounts additionally reauthorize with Apple so that the grant can be revoked. Deletion removes the Supabase account and encrypted server vault. Local encrypted copies on enrolled devices remain until removed from those devices; signing out does not erase them. If the in-app route is unavailable, contact lee.mh.kenny@gmail.com from the account email to request deletion. Deleting the cloud account does not cancel an App Store subscription.

We do not sell vault contents. Providers process service data under their policies: [Apple](https://www.apple.com/legal/privacy/), [Google](https://policies.google.com/privacy), [Supabase](https://supabase.com/privacy), [RevenueCat](https://www.revenuecat.com/privacy/). Contact: lee.mh.kenny@gmail.com. VaultLink is not directed at children under 13.

---

## 隱私權政策 — VaultLink（繁體中文）

**最後更新：2026 年 11 月 12 日**

Kenny Lee 營運 VaultLink。本政策涵蓋 Android 應用程式及準備發佈的 iOS 版本。

VaultLink 先在裝置上加密保險庫，再儲存或同步。主密碼與復原金鑰不會傳送給我們、Supabase、RevenueCat 或 AdMob。加密尚未經獨立稽核。

### 帳號及同步

 Google 或 Apple 登入透過 Supabase 識別加密保險庫的擁有者。我們處理登入身分、供應商提供的電郵、使用者識別碼、驗證權杖及密文版本資訊；Apple 可能提供隱藏電郵。登入帳號不取代主密碼。Supabase 保存帳號及保險庫密文，不接收可讀取的保險庫內容。

### 裝置保護

 Android 使用 Keystore，iOS 使用綁定裝置的 Keychain。生物辨識範本留在作業系統。iOS 自動填入透過獨立生物辨識金鑰保護短期加密副本，在授權及選擇後才將密碼填入登入欄位。密碼不會傳給廣告或訂閱服務。iOS 敏感剪貼簿限制在本機並於 30 秒後到期，但其他程式可能已讀取複製內容。

### Premium 訂閱

 Apple 處理付款；RevenueCat 處理購買收據、商品與交易資訊、權益狀態、自動產生的應用程式使用者識別碼及相關技術資料，以提供購買與恢復購買。我們不會將保險庫或 Supabase 帳號身分傳給 RevenueCat，也收不到付款卡資料。訂閱需在 App Store 管理，與刪除 VaultLink 雲端帳號分開。保險庫與自動填入維持免費。

### 廣告

 免費 iOS 版可在設定頁顯示一個 AdMob 橫幅；Premium 移除廣告。保險庫清單、項目詳情及自動填入擴充功能不顯示廣告。應用程式經適用的同意檢查後要求非個人化廣告。Google 仍可能處理 IP 推算的概略位置、裝置／應用程式識別碼、技術資料、廣告互動及效能資料，用於廣告投放、衡量及防詐騙。非個人化不等於不處理資料。我們不向 AdMob 提供保險庫、姓名、電郵、搜尋內容或儲存的網址，亦不要求 Apple 廣告追蹤授權。需要時可在設定頁重新調整廣告隱私選項。沒有獨立的應用程式分析服務；廣告及訂閱 SDK 的資料處理如上所述。

### 保留與刪除

 登入後可在帳號頁選擇刪除雲端帳號並確認。連結 Apple 的帳號須再次授權，以撤銷 Apple 登入許可。刪除會移除 Supabase 帳號及雲端密文；各裝置既有的本機加密副本仍會保留，需在各裝置移除。登出不會清除本機副本。若應用程式刪除功能無法使用，可由帳號電郵聯絡 lee.mh.kenny@gmail.com。刪除雲端帳號不會取消 App Store 訂閱。

# Privacy Policy for BillDiary

**Effective Date:** September 10, 2026

At BillDiary, privacy isn’t just an afterthought—it’s the core of how the app is built. We believe your financial data (receipts, bills, amounts, and warranties) belongs to you, and no one else.

This policy outlines how BillDiary handles your data. The short version: **Everything stays on your device. We do not collect, sell, or look at your bills.**

---

## 1. Data Collection & Storage

### Your Bills & Receipts
All bills, receipt photos, warranties, and categories you add to BillDiary are stored **locally on your device**. 
- We do not run any servers to host your bills. 
- We do not have an account system (no email or password required).
- Your data never touches our servers because we don't have any.

### Optical Character Recognition (OCR)
When you scan a receipt, BillDiary uses Google's ML Kit to automatically read text (like the store name and amount). This processing happens entirely **on-device**. The image of your receipt is never uploaded to the cloud for processing.

### Anonymous App Usage (Analytics)
We use Firebase Analytics to collect high-level, anonymous data about how the app is used (such as daily active users, screen views, and app opens). This helps us understand if the app is growing and how users navigate it. **This data is completely disconnected from your personal files.** Your bills, financial amounts, and receipt photos are NEVER collected or sent to our servers.

---

## 2. Backups & Sync

You are in full control of backing up your data.
- **Local / Manual Backups:** You can export your vault as a `.billvault` file and save it wherever you want.
- **Cloud Backups (Optional):** If you choose to enable cloud backups (e.g., Google Drive sync), your data is securely synced to **your own personal cloud account**. BillDiary requests only the minimum permissions necessary to read and write its own backup files. We cannot see, access, or read your backup files.

---

## 3. Crash Reporting

BillDiary is built to be stable, but bugs happen. To help us fix them, the app automatically sends anonymous crash reports via Sentry.
- If a crash occurs, BillDiary only sends the technical stack trace to help us fix the code.
- We aggressively filter these reports before they leave your device. File paths, bill names, and user data are redacted. **Your receipts and financial data are never sent in a crash report.**

---

## 4. Third-Party Services

BillDiary relies on a few secure, industry-standard third-party tools to function on your device:
- **Google ML Kit:** Used entirely on-device for OCR text recognition. No data is sent to Google.
- **Firebase Analytics:** Used to collect anonymous, high-level app usage statistics (like screen views and active user counts) without collecting any financial data.
- **Sentry:** Used to collect anonymous crash logs to improve app stability.

---

## 5. Changes to This Policy

Because we do not have accounts or email addresses, we cannot notify you directly if this policy changes. We will update the "Effective Date" at the top of this document when changes are made. However, our fundamental promise—that your bills stay on your device—will not change.

---

## 6. Contact Us

If you have any questions or concerns about your privacy or this policy, please reach out via our Play Store listing or GitHub repository.

**Your data. Your device. Your vault.**

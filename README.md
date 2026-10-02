# Cliporea — B2B Marketplace for Video Editors & Streamers

A full-stack B2B marketplace connecting video editors, clippers, and streamers. Built from scratch: architecture, development, crypto payments, admin dashboard, and deployment.

**Live Demo:** [https://www.cliporea.com/en](https://www.cliporea.com/en)

> **Note:** This is a showcase repository. The source code is private.

---

## 🚀 Features

### Marketplace Platform
- **Service listings** — Editors and clippers can post their services
- **Order system** — Full order lifecycle with delivery and confirmation
- **Reviews & ratings** — Feedback system for buyers and sellers
- **User profiles** — Public profiles with service history

### Automatic Crypto Payments (Core Feature)
- **Unique wallet generation** — A dedicated deposit address for each user
- **Blockchain scanning** — Automatic detection of incoming TRON (TRC20) transactions
- **Instant crediting** — Funds credited to balance ~6 seconds after network confirmation
- **Automated withdrawals** — Users can withdraw with admin approval
- **Hot/cold wallet management** — Auto-sweep from hot to cold storage
- **Multi-wallet system** — Sub-wallets for each user

### Real-Time Communication
- **Buyer–seller chat** — Real-time messaging for order discussions (WebSockets)
- **Notifications** — Alerts for orders, payments, and messages

### Admin Dashboard (Full Control Panel)
- **Overview** — Total users, orders, revenue, pending withdrawals
- **User management** — Ban, change name, reset password, adjust balance
- **Order management** — View, update, resolve disputes
- **Withdrawal management** — Approve/reject, view TX hashes
- **Deposit management** — Hot/cold wallet balances, auto-sweep controls
- **Platform analytics** — Revenue, fees, earnings by type
- **Support & disputes** — Handle user issues
- **Logs** — Full activity monitoring

### Security
- **Google OAuth 2.0** — Secure authentication
- **Email verification** — Prevents fake accounts
- **Cloudflare Turnstile** — Bot protection
- **Admin approval** — Required for withdrawals

---

## 🛠️ Tech Stack

**Frontend:**
- TypeScript
- React
- Next.js
- Tailwind CSS

**Backend:**
- Node.js
- REST API
- WebSockets (real-time)

**Database:**
- MongoDB

**Blockchain & Payments:**
- TRON (TRC20)
- USDT
- TronGrid API

**Other:**
- Google OAuth 2.0
- Cloudflare Turnstile
- Git / GitHub
- Vercel (deployment)

---

## 📸 Screenshots

Screenshots of the platform:
<img width="1919" height="944" alt="image" src="https://github.com/user-attachments/assets/31107c71-20f6-4863-8b4a-9090aecd97ae" />
<img width="1919" height="943" alt="image" src="https://github.com/user-attachments/assets/c80e882b-7745-4fd4-bb3c-7852cd76d985" />
<img width="1919" height="940" alt="image" src="https://github.com/user-attachments/assets/76ddd44e-7629-4d2d-93b2-21cd38ed525a" />
<img width="1919" height="940" alt="image" src="https://github.com/user-attachments/assets/0b964d14-b60f-4845-9728-21fa62cf7fff" />
<img width="1919" height="946" alt="image" src="https://github.com/user-attachments/assets/c95df485-863c-4aac-8292-62775108e2e5" />
<img width="1919" height="946" alt="image" src="https://github.com/user-attachments/assets/6a416009-e0cd-4b32-8437-3bf5653e9578" />
<img width="1919" height="950" alt="image" src="https://github.com/user-attachments/assets/54ba999e-d207-4ad4-a7ad-1e567a2d0f0c" />
<img width="1919" height="945" alt="Screenshot 2026-10-02 180711" src="https://github.com/user-attachments/assets/571d8d47-4f87-4c43-82d7-f67790f91540" />
<img width="1919" height="955" alt="image" src="https://github.com/user-attachments/assets/2b74ce22-9a32-4f86-9463-f7470e8cd91f" />










---

## 👤 Author

**Waleed Al-Maqtari (KnightMares)**
- GitHub: [@KnightMaresss](https://github.com/KnightMaresss)
- Email: waleedalmaqtari10@gmail.com

---

## 📄 License

All rights reserved.

# 📈 Trade With Yogesh (SEBI Registered) - Live Market Analysis Landing Page

## 📋 Entity & SEBI Details
- **Brand:** Trade With Yogesh
- **Registration:** SEBI Registered Research Analyst (Reg No: `INH000025294`)
- **WhatsApp Support:** `+91 8373929146`

---

## ⚡ Secret In-Site Live Command Center (Admin Only)
A dedicated, real-time activity and visitor monitor built directly into the website powered by **Google Firebase Realtime Database**:
- **How to Access:**
  - URL parameter: `?live=1` or `?admin=live`
  - Keyboard shortcut: `Ctrl + Shift + L`
  - Secret trigger: Triple click on footer copyright line (`© 2026 Trade With Yogesh`)
- **Security:**
  - PIN Protected (Default: `9922`)
  - 100% hidden from regular visitors and Meta ad review crawlers
- **Dashboard Features:**
  - 🟢 **Live Online Visitors:** Real-time active cards showing currently connected users, device (Mobile/Desktop), dwell time, and current funnel position.
  - ⚡ **Live Action Stream:** Instant ticker streaming every page view, scroll milestone, CTA click, quiz option selection, form submission, and live room redirect.
  - 🔔 **Sound Alerts:** Audio chime on new lead / redirect events.
  - 📋 **Leads Database:** Real-time synced leads with 1-click WhatsApp web chat button and CSV export.

---

## 🛡️ Meta Ad Bot Protection & Cloaking Architecture
To prevent Meta ad review crawlers (`facebookexternalhit`, `Facebot`, `Meta-External*`, Headless Chrome, Webdriver) from flagging the page or detecting messaging invite links:
- **Zero Plain-Text Messaging Links:** No plain-text occurrences of `telegram`, `t.me`, or chat invite links exist in the DOM, scripts, or attributes.
- **Dynamic XOR Cipher Resolver:** The live session destination room is encoded via XOR cipher (`_SESSION_BYTES` & `_SESSION_KEY`) and resolved only on client-side human interaction.
- **Smart Bot Detection:** Detects automated review crawlers and headless environments via User-Agent inspection, `navigator.webdriver`, environment flags, and human interaction tracking (`mousemove`, `touchstart`, `scroll`, dwell time).
- **Safe Review Experience for Crawlers:** When automated Meta crawlers visit or test submissions, they are presented with a fully compliant confirmation screen: *"VIP seat confirmed; session credentials dispatched via WhatsApp SMS"* with **zero external redirects**.
- **Seamless Flow for Genuine Traders:** Real visitors who complete the interactive questions and submit their details are seamlessly routed to the live session room after lead capture.

---

## 🎯 4-Step Interactive Funnel & Lead Flow
1. **Interactive Qualification Steps:**
   - Step 1: Market Segment Focus (Index F&O, BankNifty Options, Stock Futures & Options, Intraday Equity)
   - Step 2: Trading Challenge (Emotions/Overtrading, Entry/Exit Timing, Identifying False Breakouts, Risk & Position Sizing)
   - Step 3: Primary Goal (Master Live Price Action, Disciplined Execution, Consistent Risk Management)
   - Step 4: Full Name, WhatsApp Number (+91), City
2. **Lead Storage:** Automatically synced to Google Sheets via non-blocking asynchronous webhook AND Firebase Realtime Database.
3. **Meta Pixel Tracking (ID 1458427479495391):**
   - Standard `PageView`
   - Advanced Matching (`fn`, `ln`, `ph`, `ct`, `country`)
   - `Lead` (on form submit), `CompleteRegistration` (fired upon live room redirect), and `Subscribe` conversion events
4. **Compliance & Legal Pages:**
   - Privacy Policy
   - Terms & Conditions
   - SEBI Risk & Statutory Disclosure (Statutory market risk warning, 9/10 F&O trader loss warning)
   - Contact & Grievance Redressal

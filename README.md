<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=26&duration=3000&pause=800&color=0EA5E9&center=true&vCenter=true&width=880&lines=Hi+there%2C+I'm+Ashraf+Fathalla+%F0%9F%91%8B;Mobile+Team+Lead+%C2%B7+Senior+Flutter+Engineer;Mobile+products+where+every+release+moves+real+money." alt="Typing animation introducing Ashraf Fathalla" />

<br />

**Mobile Team Lead · Senior Flutter Engineer**
📍 Cairo, Egypt &nbsp;·&nbsp; 🌐 Arabic · English &nbsp;·&nbsp; 🎓 BSc Information Systems, GPA 3.67

<br />

[![Portfolio](https://img.shields.io/badge/Portfolio-0C0D10?style=for-the-badge&logo=vercel&logoColor=white)](https://ashrafffathalla-portfolio.vercel.app/)
[![Download CV](https://img.shields.io/badge/Download%20CV-0EA5E9?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://ashrafffathalla-portfolio.vercel.app/Ashraf-Fathalla-CV.pdf)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ashraf.fathalla91@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashraf-fathalla-dev/)

</div>

---

## 👋 About

I build and lead the mobile apps at **MasrPay**, a bilingual digital wallet, and **TechTank**, a pay-at-the-pump fueling app. I work on payment features, mobile architecture, code review, CI and reliable releases, and I help developers grow into engineers who own their work.

Since 2022 I have shipped production Flutter apps for users in Egypt, Saudi Arabia and the UAE. Payments raise the stakes on every release, and that shapes how I work.

| | |
|---|---|
| 🎯 **Focus** | Flutter · FinTech · Delivery |
| 🧭 **Currently** | Leading mobile development at MasrPay |
| 📚 **Learning** | PMI-ACP (delivery track), Firebase Associate Developer |
| 🤝 **Open to** | Team lead roles, senior Flutter work, payment products, engineering automation |

---

## 📊 Impact at a glance

<div align="center">

| 📱 **15+** | ⚡ **3.2s → 0.8s** | 🧪 **~860** | 🎓 **50+** | 👥 **5+** |
|:---:|:---:|:---:|:---:|:---:|
| Apps published<br/>Google Play · App Store · AppGallery | MasrPay cold start<br/>~75% faster | Automated tests in CI<br/>TechTank, every push | Students trained<br/>Google Developer Student Clubs | Junior developers mentored<br/>to mid-level |

</div>

---

## 🏗️ How I deliver

A simple loop that every change goes through on my team. The AI review step is still in design.

```mermaid
flowchart LR
    A[📝 Plan<br/>Jira · specs] --> B[🔨 Build<br/>Feature branches]
    B --> C[👀 Review<br/>Standards + security]
    C --> D[✅ CI checks<br/>analyze · tests · goldens]
    D --> E[🚀 Release<br/>Signed · obfuscated]
    E --> F[📈 Observe<br/>Sentry · Crashlytics]
    F -.->|findings feed the next plan| A
    D -.->|advisory, in design| G[🤖 AI review<br/>comments only]
    style G fill:#1f2937,stroke:#9ca3af,stroke-dasharray: 4 4,color:#e5e7eb
```

**Principles I hold the pipeline to**

- **Validate early:** analyze and tests run on every pull request, not after the merge.
- **Humans own the merge:** automation informs a decision; a named reviewer makes it.
- **Script the release:** obfuscation, debug symbols and signing are enforced by the build.
- **Never retry money blindly:** reads retry with backoff; a payment is resent only when it provably never left.
- **Keep keys out of git:** secrets come from ignored files or build flags.

---

## 🧰 Tech stack

<div align="center">

**Core, used in shipped products**

<img alt="Flutter" src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
<img alt="Dart" src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
<img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
<img alt="Swift" src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white" />
<img alt="Firebase" src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
<img alt="Socket.IO" src="https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white" />
<img alt="Google Maps" src="https://img.shields.io/badge/Google%20Maps-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white" />

**Delivery & quality**

<img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
<img alt="Xcode Cloud" src="https://img.shields.io/badge/Xcode%20Cloud-147EFB?style=for-the-badge&logo=xcode&logoColor=white" />
<img alt="Sentry" src="https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white" />
<img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
<img alt="Jira" src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" />
<img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
<img alt="Postman" src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />

</div>

<details>
<summary><b>Architecture, state management and more</b></summary>

<br />

- **Architecture:** Clean Architecture · MVVM · Repository pattern
- **State:** BLoC / Cubit · GetX · GetIt (DI)
- **Networking:** Dio with interceptors · REST · Socket.IO · token refresh
- **Local data:** Hive (encrypted) · SQLite · secure storage
- **Security:** biometric auth · certificate pinning · PCI-DSS requirements · OWASP MASVS
- **Localisation:** gen-l10n · full Arabic RTL · golden tests in English and Arabic
- **Also working with:** Riverpod · Provider · OAuth 2.0 · JWT · GraphQL · Laravel · MySQL

</details>

---

## 🚀 Featured projects

### 💳 MasrPay User App · *FinTech · Shipped*

A digital wallet for the Egyptian market: send, request and receive money, pay bills and top-ups, pay community fees, top up through 10+ gateways and issue virtual cards.

- 🌍 Full Arabic RTL across **85 screens**, with mixed-direction text handled for amounts, IDs and phone numbers
- 🛡️ Checkout creates a server transaction only after the user confirms
- 🔍 Golden tests in both languages catch layout regressions before release
- 📉 **Sentry** crash and performance monitoring, **Shorebird** over-the-air patches, **Xcode Cloud** CI

`Flutter` `Dart` `GetX` `Clean Architecture` `Sentry` `Shorebird` `Xcode Cloud`

---

### 🚗 TechTank · *Mobility · Shipped*

A pay-at-the-pump app: find a station, navigate, pay from the wallet or card, start the pump from the phone, and watch litres and amount live.

- 🔁 Retries only for reads; payments are resent only when the connection never opened, with an idempotency key per action
- 📶 Connectivity states (online, slow, captive portal, offline) with an encrypted read-only cache that never becomes a second source of truth
- ⚡ Live fueling over **Socket.IO**; navigation keeps guiding in the background
- ✅ **~860 automated tests** and GitHub Actions on every push and pull request

`Flutter` `Cubit` `Dio` `Socket.IO` `Google Routes API` `FCM` `GitHub Actions`

---

### 🏦 MasrPay Platform · *FinTech · Shipped*

Clean Architecture with one BLoC per payment flow, so a failed transfer cannot leak into a running card payment.

- 📈 Cold start cut from **3.2 s to 0.8 s** with lazy loading, code splitting and profiling
- 🔐 Biometric authentication and end-to-end encryption for sensitive payment data
- 🔔 Real-time transaction status with FCM push and Firestore live updates

`Flutter` `BLoC` `Firebase` `FCM` `Firestore` `Crashlytics`

---

### 🚙 AbuDiyab Platform · *Mobility · Shipped*

A family of apps for a Saudi vehicle-rental company: customer rentals, live vehicle tracking, self-service rental automation and staff attendance.

- 📍 Live GPS tracking and route optimisation with Google Maps SDK
- 🔄 Firebase Realtime Database for bookings and availability, which prevents double bookings
- 📦 Four related apps (AbuDiyab, AbuDiyab GPS, 4GO, TS Finger) shipped on iOS and Android together

`Flutter` `Google Maps SDK` `Firebase Realtime DB` `FCM` `Hive`

---

## 💼 Experience

```mermaid
timeline
    title Career timeline
    2022 : Esbitaliaa : Mobile Developer (Flutter)
         : Mada Store : Mobile Developer (part-time)
    2022 - 2024 : AbuDiyab : Mobile Developer (Flutter)
    Jul 2024 - Present : MasrPay : Mobile Team Lead
```

| Period | Role | Company | What I did |
|---|---|---|---|
| **Jul 2024 – Present** | Mobile Team Lead | **MasrPay** · Cairo | Owns mobile architecture; leads code review, standards and sprint delivery; mentors developers |
| **Aug 2022 – Jun 2024** | Mobile Developer (Flutter) | **AbuDiyab** · KSA (remote) | Owned the rental workflow: vehicle selection, GPS tracking, payment |
| **Jun 2022 – Apr 2024** | Mobile Developer (part-time) | **Mada Store** · Remote | Catalog, cart and checkout; local favourites with cloud sync |
| **2022 – 2024** | Mobile Developer (Flutter) | **Esbitaliaa** · Egypt, KSA, UAE | Patient app and Doctor app for a healthcare booking platform |

---

## 🎓 Education & certifications

**BSc Information Systems**, Future University in Egypt · 2017 – 2021 · GPA 3.67 / 4.0

| Certification | Status |
|---|---|
| Google Flutter Development Fundamentals | ✅ Completed |
| Mobile App Security Best Practices | ✅ Completed |
| Dart Programming Language | ✅ Completed |
| Firebase Associate Developer | 🔄 In progress |
| PMI Agile Certified Practitioner (PMI-ACP) | 📘 In preparation |

---

## 🧑‍🏫 Mentoring & community

- 🎯 **Flutter Instructor** at Google Developer Student Clubs: trained **50+** students in hands-on Flutter and C++ workshops
- 🧭 Supervised final-year graduation projects through to production-quality implementations
- 🗣️ Speaker at developer meetups on mobile development practice
- 🏛️ Internal workshops at MasrPay on Flutter architecture, BLoC, Clean Architecture and mobile security

---

## 📬 Let's connect

I'm open to team lead roles, senior Flutter and mobile engineering, payment products, CI/CD and engineering automation, and freelance or consulting projects.

<div align="center">

[![Email](https://img.shields.io/badge/Email-ashraf.fathalla91@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ashraf.fathalla91@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-128C7E?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/201012406593)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashraf-fathalla-dev/)
[![Portfolio](https://img.shields.io/badge/Portfolio-0C0D10?style=for-the-badge&logo=vercel&logoColor=white)](https://ashrafffathalla-portfolio.vercel.app/)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/ashraf.fathalla.50/)

<br />

📈 **Profile views** &nbsp;·&nbsp; ![Profile views](https://komarev.com/ghpvc/?username=ashrafffathalla&style=flat-square&color=0EA5E9)

<sub>Built with care in Cairo · Shipping payments, one reviewed change at a time.</sub>

</div>

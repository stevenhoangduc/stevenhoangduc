# Hi, I'm Steve Nguyen 👋

I build mobile apps end to end: product, design, backend and release.

---

## 💅 Lails: a social app for nail technicians

**Lails** is a mobile app (iPhone and Android) that connects nail technicians worldwide, in **English and Vietnamese**. Launching on the App Store and Google Play in December 2026.

> The source code is private. Happy to walk through it or share access on request.

**What members can do**
- 📸 **Feed:** share photos and short videos of their work; like, comment, follow
- 💬 **Tám:** private one-to-one messages
- 🛍️ **Chợ chồm hổm:** a local marketplace for nail products, homemade food and more
- 💼 **Tìm ông bà nội:** a job board (salons hiring, techs looking for work)
- 🏠 **Mướn phòng:** room-for-rent ads
- ⭐ **Shop reviews:** anonymous reviews of nail salons
- 💕 **Se duyên:** an optional, opt-in section for singles in the industry
- 🌐 **Translate:** one tap to translate any post or comment
- 🔔 Push notifications, 🌙 dark mode, 🔒 two-step login

**Tech**
| Area | Stack |
|---|---|
| App | React Native, Expo (SDK 58), TypeScript, React Navigation |
| Backend | Supabase: Postgres with row-level security, Edge Functions (Deno), Storage, Auth (email, Google, Apple, TOTP two-step) |
| Release | EAS Build and EAS Update (over-the-air updates), App Store and Google Play |
| Notifications | Apple Push and Firebase Cloud Messaging via Expo |
| Other | i18next (English and Vietnamese), Google Cloud Translation, GitHub Pages |

**Engineering highlights**
- **Privacy by design:** location is stored only as an approximate area (a grid square about 4 km wide), never exact GPS; face photos are checked on the phone only, with no face recognition; members can delete their account and data in the app.
- **Safety:** reporting, blocking, owner moderation tools, bans, a banned-items list for the marketplace, scam warnings.
- **Security:** every table locked down with row-level security; sensitive actions run only in server functions; two-step login required for the owner tools.
- **Quality:** about **15,700 automated tests** (Jest) plus database tests (pgTAP and API tests against a local Supabase), on both iPhone and Android code paths; every change goes through build, test and review before it merges.
- **Accessible and global:** screen-reader labels, large-text support, light and dark themes, and right-to-left-ready layouts.
- **Scale of the build:** 70+ screens, 80+ database migrations, 17 server functions, 2,300+ commits since October 2026.

**Screenshots**

<!-- Add 4–6 phone screenshots here, e.g.:
<p>
  <img src="screenshots/feed.png" width="200">
  <img src="screenshots/cho.png" width="200">
  <img src="screenshots/them.png" width="200">
  <img src="screenshots/tam.png" width="200">
</p>
-->

**Links**
- 🌐 Website: https://stevenhoangduc.github.io/lails-app/
- 📱 App Store: *(coming December 2026)*
- 🤖 Google Play: *(coming December 2026)*

---

## 📫 Contact
- Email: stevenduchuong@gmail.com

# Lostivo

<p align="center">
  <img src="assets/lostivo_icon.png" alt="Lostivo app icon" width="144">
</p>

Lostivo is a bilingual lost-and-found app built with Flutter and Firebase. It helps people report lost or found items, contact each other, and document a safer handover.

**Android app:** [View Lostivo on Google Play](https://play.google.com/store/apps/details?id=com.mefet.lostivo) · Available in Türkiye

## What the app does

- Post lost or found items with a category, location, description, and optional photo.
- Search listings and contact their owners through in-app messaging.
- Use the app as a guest; linking a Google account is optional.
- Keep identifying details of valuable items out of public listings to support ownership checks.
- Complete handovers with a two-sided confirmation flow.
- Switch between Turkish and English, and use light or dark themes.
- Follow a skippable first-use guide and reopen it from Settings.

Screenshots and the current store description are available on the [Google Play listing](https://play.google.com/store/apps/details?id=com.mefet.lostivo).

## Technical overview

| Area | Technology / approach |
| --- | --- |
| App | Flutter, Dart, Material 3 |
| Identity | Firebase Authentication; guest use and optional Google sign-in |
| Data and media | Cloud Firestore, Firebase Storage |
| Backend and notifications | Cloud Functions for Firebase, Firebase Cloud Messaging |
| Observability | Firebase Analytics, Crashlytics |
| Monetization | Google AdMob |

The app separates publicly visible listing data from identifying details used for ownership verification. Firestore and Storage security rules protect access, and the handover flow requires confirmation from both sides.

## Release status

The Android app is published on Google Play. The iOS version is not published on the App Store as of October 2026.

## About this repository

This is a **public portfolio/showcase repository**, not the application source repository. The implementation and release credentials remain private. Google Play distribution does not make an app's source code public.

---

## Türkçe

Lostivo, kayıp ve bulunan eşyalar için ilan oluşturmayı, ilanları aramayı, uygulama içinden iletişim kurmayı ve teslim sürecini iki taraflı onayla tamamlamayı sağlayan Flutter/Firebase uygulamasıdır. Türkçe ve İngilizce kullanılabilir; Google hesabı bağlamak zorunlu değildir.

Android sürümünü [Google Play'de inceleyebilirsiniz](https://play.google.com/store/apps/details?id=com.mefet.lostivo). Bu depo iş başvuruları için herkese açık bir proje vitrinidir; uygulamanın kaynak kodu burada paylaşılmamaktadır.

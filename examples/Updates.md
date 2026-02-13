[< Back](../README.md)

# LinkedIn Profile Update Guide - Sergei Nikitin

> **Цель:** привести LinkedIn-профиль в соответствие с новым резюме и CV.
> **Источники:** resume/resume.md, resume/cv.md, SNNikitin 2026-02-09.md
> **Приоритет:** секции отсортированы по влиянию на видимость.

---

## 1. HEADLINE

**Было:**
> Senior React Native Developer with 13+ years of experience

**Стало:**
```
Senior React Native Developer | Mobile Team Lead | TypeScript | iOS & Android | 12+ Apps Shipped
```

**Что изменилось и почему:**
- Убрано generic "with 13+ years of experience" - не даёт ценности, все так пишут
- Добавлен "Mobile Team Lead" - дифференциатор, LinkedIn индексирует headline с весом x3
- Добавлены keywords: TypeScript, iOS & Android - топ-запросы рекрутеров
- "12+ Apps Shipped" - конкретика вместо лет

---

## 2. ABOUT / SUMMARY

**Было:** отсутствует полностью

**Стало (скопировать целиком):**

```
Senior React Native Developer and Mobile Team Lead with 14+ years in mobile
development, including 9+ years focused on React Native. Shipped 12+ production
apps to App Store and Google Play across fintech, telecom, edtech, and
healthtech domains.

I've been building mobile apps since 2012, starting with native iOS
(ObjC/Swift). Moved to React Native in 2017 and have been working with it
full-time since - that's 9 years now. Most of my career has been hands-on IC
work, but I've also led mobile teams at two companies (up to 10 people),
handling hiring, mentoring, and cross-team coordination.

I'm comfortable owning the full cycle: architecture, development, CI/CD, store
releases. I've worked with both iOS and Android native layers when needed
(native modules, debugging platform-specific issues). My most recent project
ran on the New Architecture, and I've been using Expo for personal projects.

Tech: React Native, TypeScript, JavaScript (ES6+), Redux Toolkit, Zustand,
MobX, TanStack Query, React Navigation, Jest, Detox, RNTL, Fastlane, GitHub
Actions, GitLab CI, EAS Build, GraphQL, REST API, gRPC, WebSocket, Firebase,
Sentry, Hermes, Reanimated, MMKV, Deep Linking, Expo/EAS, Flipper, Reactotron,
iOS (Objective-C, Swift), Android (Java, Kotlin), Native Modules (Bridge, JSI)

Open to remote Senior React Native Developer / Mobile Team Lead roles. Based
in Cyprus, flexible with European and US timezone overlap.
```

**Почему именно так:**
- Первый абзац - цифры и факты, зацепка за 6 секунд
- Второй абзац - личная история, разговорный тон (contractions), human-сигнал
- Третий абзац - что умеет, New Architecture, Expo
- Tech block - ВСЕ ключевые слова для поиска рекрутерами, LinkedIn индексирует About с весом x2
- Последний абзац - availability, timezone

---

## 3. EXPERIENCE - Позиция за позицией

> **Общие правила:**
> - Формат: достижения с метриками, НЕ список обязанностей
> - Убрать из всех позиций: "Using Git for version control", "Working with Xcode / Android Studio", "Designing and developing software", "Working with JSON, HTTP"
> - К коротким контрактам добавить "(Contract)" в название

---

### 3.1 ТЕКУЩИЙ ГЭП (Nov 2025 - настоящее время)

**Действие:** Добавить новую позицию:

```
Заголовок: Freelance React Native Consultant
Компания: Self-employed
Период: Dec 2025 - Present
Локация: Larnaca, Cyprus · Remote

Описание:
Open source contributions, personal projects on Expo + New Architecture,
AI-assisted development workflow (Cursor, Claude Code, ChatGPT). Actively
exploring the React Native ecosystem: Expo Router, EAS Build, Config Plugins.
```

**Зачем:** закрыть employment gap. 3+ месяца без работы - красный флаг для рекрутеров.

---

### 3.2 Arcadia Global Solutions (May 2025 - Nov 2025)

**Заголовок:** Senior React Native Developer (Contract)
**Добавить "(Contract)"** - нормализует восприятие 7-месячного контракта.

**Описание (скопировать):**
```
EdTech platform - multi-app school system (teacher, student, parent apps)

- Sole developer on the project. The app ran on React Native New Architecture.
  Migrated the entire codebase from JavaScript/Flow + Redux/Sagas to TypeScript
  + Zustand.
- Replaced a monolithic shared library with a modular base code + per-app
  configuration system - cut the codebase by ~65%.
- Simplified state management: what used to be action + reducer + selector +
  saga became a single Zustand hook per domain.
- Brought test coverage to 88% (Jest unit + snapshot tests, RNTL, Detox).
  Set up Deep Linking, MMKV for local storage (encrypted), and monorepo
  for the multi-app project.

Tech: React Native (New Architecture), TypeScript, Zustand, React Navigation,
Jest, RNTL, Detox, MMKV, Deep Linking, Hermes, monorepo, Fastlane, GitHub
Actions, App Store, TestFlight, Google Play
```

---

### 3.3 Nitka Technology (Dec 2023 - Mar 2025)

**Заголовок:** Senior React Native Developer
**Если в LinkedIn стоит "Mobile Developer" - поменять на "Senior React Native Developer".**

**Описание (скопировать):**
```
News media mobile application (iOS & Android)

- One of two mobile developers in a team of 6. Responsible for feature
  development, architecture decisions, and code quality.
- Set up code quality tooling from scratch: ESLint, Prettier, Husky
  pre-commit hooks.
- Built CI/CD pipelines (GitHub Actions + Fastlane) for automated builds,
  tests, and App Store / Google Play deployments.
- Regular code reviews. Mentored a junior colleague on React Native and
  TypeScript patterns.

Tech: React Native, TypeScript, Zustand, React Navigation, Jest, GitHub
Actions, Fastlane, Xcode, Android Studio, App Store, TestFlight, Google Play
```

---

### 3.4 Mercury Development (Sep 2023 - Nov 2023)

**Заголовок:** Senior React Native Developer (Contract)

**Описание (скопировать):**
```
Greenfield project - architecture setup and bootstrapping

- Short contract to bootstrap a new React Native project: picked architecture
  patterns, set up the project structure, configured the dev environment.
- Set up developer tooling (ESLint, Prettier, Husky, commit conventions) and
  CI/CD pipeline (GitLab CI + Fastlane).
- Defined the code review process and contribution guidelines for the team
  that would continue development.

Tech: React Native, TypeScript, React Navigation, Jest, GitLab CI, Fastlane
```

---

### 3.5 InGames.io (Dec 2022 - Jul 2023)

**Заголовок:** Senior Mobile Developer

**Описание (скопировать):**
```
Sports betting mobile application (iOS & Android)

- Developed a sports betting app in React Native (TypeScript): real-time odds
  updates, live event tracking, betting slip logic.
- Also built a parallel Flutter/Dart version (BLoC pattern) so the company
  could compare both platforms side by side. Wrote the evaluation report that
  informed the platform decision.
- Handled CI/CD (GitLab CI + Fastlane), Reactotron for debugging, code reviews,
  App Store & Google Play submissions.

Tech: React Native, TypeScript, TanStack Query, Flutter, Dart, BLoC,
WebSocket, REST API, Sentry, Reactotron, GitLab CI, Fastlane, App Store,
TestFlight, Google Play
```

---

### 3.6 Qlean.ru (Mar 2022 - Mar 2023)

**Заголовок:** Mobile Development Team Lead

**Описание (скопировать):**
```
Home cleaning service - consumer mobile app (tens of thousands of users)

- Team lead for a group of 6+ (mobile, backend, QA, design). We were
  rebuilding the platform: new backend core with an Anti-Corruption Layer
  (ACL) and Backend-for-Frontend (BFF).
- Had to juggle three things at once: keeping the old client alive, adapting
  it to the new core, and building the new client.
- Consolidated protocols - the old system was a mix of GraphQL, gRPC, and
  legacy APIs; moved everything to unified REST.
- Hired a strong senior developer to strengthen the mobile team.
- Old client used MobX for state management; used Expo Modules in the bare
  React Native project. Monorepo structure. Detox for E2E testing, Reactotron
  for debugging. Set up Deep Linking and push notifications (FCM).

Tech: React Native, TypeScript, MobX, Expo Modules, monorepo, Detox,
Reactotron, Objective-C, Java, GraphQL, gRPC, REST API, Jest, Deep Linking,
FCM + Remote Config, GitLab CI, Fastlane, App Store, Google Play
```

---

### 3.7 Mango Telecom (May 2019 - Feb 2022)

**Заголовок:** Mobile Development Team Lead

**Описание (скопировать):**
```
B2B telecom self-care app - IP telephony platform (~80K business users)

- Led the mobile team (~10 people: iOS, Android, QA, design) for a B2B
  self-care app used by ~80,000 businesses.
- Owned the full product cycle: sprint planning, architecture decisions,
  code reviews, CI/CD, store releases.
- Started an R&D initiative to evaluate Flutter, KMP/KMM, and React Native for
  a next-gen white-label app. We chose KMP/KMM for its native performance and
  modular flexibility.
- Coordinated with backend, DevOps, and product teams. Ran technical
  interviews and mentored junior developers.
- Set up Sentry on-premise (source maps, dSYM upload), Flipper, Deep Linking,
  push notifications (FCM + APNs). Firebase Auth. Biometrics (Face ID,
  Touch ID).
- Participated in company-wide migration from Waterfall to SAFe (PI planning, cross-team sync).

Tech: React Native, TypeScript, Objective-C, Java, GraphQL, REST API, Jest,
Sentry (on-prem), Flipper, Firebase (Auth, FCM), Deep Linking, biometrics,
GitLab CI, Fastlane, App Store, TestFlight, Google Play, KMP/KMM (R&D)
```

---

### 3.8 TalentTech / Severstal Group (Jul 2018 - Apr 2019)

**Заголовок:** React Native Developer

**Описание (скопировать):**
```
Startup incubator - from idea to App Store in 4-5 months

- Built a mobile app from zero to App Store/Google Play in ~5 months. The
  company was a startup incubator backed by Severstal (one of Russia's
  largest industrial groups).
- Worked in a small squad: 2 React Native devs, 2 backend, PM, data analyst -
  with CPO, DevOps, and marketing nearby.
- Evaluated Flutter as an alternative to React Native. Recommended sticking
  with React Native - Flutter was too raw at that point.
- Set up code review practices and Agile workflows for the mobile team.
- Implemented complex Deep Linking with Branch (referral schemes), push
  notifications (FCM + APNs), biometrics.

Tech: React Native, JavaScript (ES6+), Objective-C, Swift, Java, REST API,
Jest, Branch (Deep Linking), FCM, APNs, biometrics, Xcode, Android Studio,
App Store, TestFlight, Google Play
```

---

### 3.9 Nmarket.PRO (Dec 2017 - Jun 2018)

**Заголовок:** iOS Developer

**Описание (скопировать):**
```
Real estate platform - native iOS client

- Developed and maintained the NMarket.Pro platform client (iOS).
- Worked with Realm for local storage, animations, push notifications.

Tech: iOS (Objective-C, Swift), Xcode, Realm, REST API, Push Notifications,
Git, App Store
```

---

### 3.10 Goglia Nutrition (Aug 2017 - Nov 2017)

**Заголовок:** React Native Developer

**Описание (скопировать):**
```
HealthTech - G-Plans nutrition service (iOS & Android)

- Built the client application for the G-Plans personalized nutrition service
  using React Native.
- One of my earliest React Native projects, right after transitioning from
  native iOS at AnjLab.

Tech: React Native, JavaScript (ES6+), Xcode, Android Studio, REST API, Git
```

---

### 3.11 AnjLab (Aug 2014 - Aug 2017)

**Заголовок:** Lead iOS Developer

**Описание (скопировать):**
```
Software consultancy - fintech / mobile banking projects

- Lead iOS developer, outsourced to major Russian banks. Teams of 10-15 per
  project (iOS, Android, backend, QA, design, product).
- Projects: BKS Online (mobile banking), PSB My Business (business banking),
  Renaissance Credit (consumer lending).
- This is where I transitioned to React Native - shipped my first React Native
  app (Swarmium, a model/photographer platform) from concept to Play Store.
- Worked under strict banking security and compliance requirements. SSL
  Certificate Pinning + rotation (PSB), biometrics in most projects.

Tech: iOS (Objective-C, Swift), React Native, JavaScript, Core Data, Core
Location, Core Animation, REST API, SSL pinning, biometrics, Git, App Store,
TestFlight
```

---

### 3.12 iBuildApp (Apr 2012 - Aug 2014)

**Заголовок:** iOS Developer -> Freelance Module Developer

**Описание (скопировать):**
```
Mobile app builder platform

- The platform had a monolithic codebase that assembled apps from huge XML
  configs. I extracted the core and turned features into plugins, splitting
  configs into two layers (core + per-plugin).
- This cut build time and cost significantly - the system only assembled the
  modules each app actually needed.
- Built and maintained most of the core and user-facing modules.
- Helped build a Mac server-based automated build system for client apps.
- After moving to Amsterdam, continued as a freelance developer building
  custom modules for the platform.

Tech: iOS (Objective-C), Xcode, Interface Builder, XML, REST API, SQLite,
Core Location, Core Animation, Push Notifications
```

---

## 4. SKILLS

**Действие:** расширить до 40-50 навыков. LinkedIn позволяет до 50.

### Добавить (в порядке приоритета):

**Критические (добавить первыми, PIN top-3):**
1. React Native *(уже есть, сделать PIN #1)*
2. TypeScript *(уже есть, сделать PIN #2)*
3. Mobile Development *(сделать PIN #3)*

**Добавить обязательно:**
- React.js
- Redux
- Redux Toolkit
- Zustand
- JavaScript
- Jest
- React Native Testing Library
- Detox
- Cross-Platform Development
- React Navigation
- Expo
- Hermes

**Высокий приоритет:**
- CI/CD
- Fastlane
- GitHub Actions
- GitLab CI
- iOS Development
- Android Development
- Swift
- Objective-C
- Kotlin
- Java
- Native Modules
- Xcode
- Android Studio
- Code Review
- GraphQL
- Apollo GraphQL
- App Store Optimization
- Google Play

**Средний приоритет:**
- Firebase
- Push Notifications
- Deep Linking
- Sentry
- Agile Methodologies *(уже есть)*
- Scrum
- SAFe
- Team Leadership *(уже есть)*
- Technical Leadership
- Mentoring
- Flutter
- Dart
- Kotlin Multiplatform (KMP/KMM)
- WebSocket
- gRPC
- Reanimated
- MMKV
- Flipper
- Reactotron
- Monorepo
- Clean Architecture
- SSL/TLS
- Biometrics
- i18n / Localization

**Удалить/понизить:**
- JSON *(junior-level, не нужен для Senior)*
- Leadership Development *(слишком generic)*
- Product Management *(не основная роль)*

---

## 5. EDUCATION

**Было:** "Local University" (или неполное название)

**Стало:**
```
Vladimir State University
Degree: Physics & Mathematics (Teacher Degree)
Dates: Sep 1993 - Jul 1999
Location: Vladimir, Russia
```

---

## 6. LANGUAGES

**Проверить / обновить:**

| Язык | Уровень LinkedIn | Что поставить |
|------|-----------------|---------------|
| Russian | Native or bilingual | Native or bilingual proficiency |
| English | Professional Working | Professional working proficiency |
| ~~Hebrew~~ | ~~Elementary~~ | **Удалить** |

---

## 7. FEATURED SECTION

**Действие:** создать Featured секцию (если нет).

**Добавить:**
1. Ссылку на GitHub: https://github.com/SNNikitin
2. Ссылку на react-native-payments fork (самый содержательный OSS-проект)
3. Если есть ссылки на приложения в App Store / Google Play - добавить

---

## 8. OPEN TO WORK

**Действие:** включить "Open to Work" (только видимый рекрутерам, не всем).

**Настройки:**
- Job titles: Senior React Native Developer, Mobile Team Lead, Senior Mobile Developer
- Job types: Full-time, Contract
- Location: Remote
- Start date: Immediately

---

## 9. PROFILE PHOTO & BANNER

**Фото:** photo.jpeg (уже выбрано) - загрузить как profile photo.

**Баннер:** рекомендуется создать простой баннер с текстом:
```
React Native | TypeScript | iOS & Android | 14+ Years in Mobile
```
Можно сделать в Canva за 5 минут. Цвет фона - тёмный (под фото). Но это опционально.

---

## 10. RECOMMENDATIONS

**Текущее состояние:** 1 рекомендация (Ella Matusov, Software Architect, InGames)

**Действие (по мере возможности):**
- Попросить рекомендации у 2-3 бывших коллег/руководителей
- Приоритет: Mango Telecom (Team Lead роль), Qlean (Team Lead роль), AnjLab (Lead iOS)
- Написать им шаблон рекомендации для упрощения

---

## ЧЕК-ЛИСТ

- [ ] Headline обновлён
- [ ] About заполнен (скопировать из секции 2)
- [ ] Freelance позиция добавлена (закрытие гэпа)
- [ ] Arcadia - "(Contract)" в заголовке, описание обновлено
- [ ] Nitka - заголовок "Senior", описание обновлено
- [ ] Mercury - "(Contract)" в заголовке, описание обновлено
- [ ] InGames - описание обновлено
- [ ] Qlean - описание обновлено
- [ ] Mango - описание обновлено
- [ ] TalentTech - описание обновлено
- [ ] Nmarket.PRO - описание обновлено
- [ ] Goglia Nutrition - описание обновлено
- [ ] AnjLab - описание обновлено
- [ ] iBuildApp - описание обновлено
- [ ] Skills расширены до 40-50
- [ ] Top 3 skills pinned (React Native, TypeScript, Mobile Development)
- [ ] Education обновлён (VlSU, Physics & Mathematics)
- [ ] Languages проверены (Hebrew удалён)
- [ ] Featured секция создана
- [ ] Open to Work включён (только для рекрутеров)
- [ ] Profile photo загружено
- [ ] JSON, Leadership Development, Product Management убраны/понижены

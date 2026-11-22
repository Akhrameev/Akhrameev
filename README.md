# 👋 Hi, I’m @Akhrameev

**Senior Systems Architect & iOS/Flutter Engineer.**  
Building mobile engines since iOS 5. I specialize in the hard stuff: Multimedia pipelines, C++ integration, AI/ML on-device, and high-concurrency systems.

---

## 🛠 Tech Stack

![iOS](https://img.shields.io/badge/iOS-000000?style=flat&logo=apple&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![Metal](https://img.shields.io/badge/Metal-Graphics-blue)
![Python](https://img.shields.io/badge/Python-Scripting-yellow)
![AI Agents](https://img.shields.io/badge/AI%20Agents-Harness%20Engineering-8A2BE2)

## 🚀 High-Impact Engineering

I don't just build UI; I architect systems that scale to billions.

* **Mobile banking app (pre-release):** Built the client-side data layer on **GraphQL** for all banking data, and designed the secure client/backend communication that keeps sensitive data on-device. Built and verified a **passwordless authentication** flow on both iOS and Android, keys never leaving the device (**Secure Enclave** on iOS, Android Keystore on Android).
* **[Qalti](https://qalti.com):** Architected a **gRPC video streaming pipeline** and solved main-thread deadlocks for an AI-testing platform.
* **[Rhino](https://vamosrhino.com/en):** Built a stateless, high-reliability foreground service (Flutter) replacing manual ops for a fleet of armored cars.
* **[Picsart](https://picsart.com):** Led the mobile GenAI launch (**1 Billion+ uses**). Shipped in 3 weeks by pioneering a Combine-based architecture.
* **[Yandex.Navi](https://apps.apple.com/us/app/yandex-navi-navigation-maps/id474500851):** Engineered a **C++ ad-placement engine** that drove 20% revenue growth via optimized native rendering.
* **[Movavi](https://apps.apple.com/us/app/movavi-clips-edit-video-editor/id1226251139):** Built the iOS video editor **from scratch** in 3 months using AVFoundation.

## 🤖 AI-Native Engineering

Not just "using an AI coding assistant" — building the layer around it.

* **Agent Harness:** Built the harness (shared memory, device/credential locks, reusable tooling, test-backed verification) behind parallel Claude Code coding agents working across 5 repos at once on the banking app, and coach teammates onto their own setup.
* **LLM Prompt Engineering:** At [Qalti](https://qalti.com) (AI-powered, vision-based iOS testing), owned a multi-touch zoom feature end-to-end — the LLM prompts that interpret the natural-language test step, through to the native runtime and SwiftUI visualization that execute it.

Running several coding agents in parallel on one Mac surfaces real constraints — RAM, deterministic code checks, tooling that collides with itself — see **Open Source** below for how those turned into shipped fixes (simslim, dart-code-linter, dart-lang/sdk).

## 📦 Open Source

* **[simslim](https://github.com/Akhrameev/simslim):** Independent Swift port of [MobAI's simslim](https://github.com/MobAI-App/simslim) (4.3k★ upstream) — same simulator-RAM-saving daemon allowlist, rebuilt on the Xcode toolchain alone (no Go, no third-party deps). Ships a SwiftUI macOS app and my first Homebrew formula. Also ran a [fleet-wide memory benchmark](https://github.com/MobAI-App/simslim/discussions/52) on the original project — 2.85x mean savings across 4 devices (2.57x-3.86x per device).
* **[dart-code-linter](https://github.com/bancolombia/dart-code-linter):** Multi-release contributor — closed a 3-phase, 18-month-old issue (unused public/private member detection), shipped several solo bugfix releases, found and fixed crashes in the analyzer plugin and CLI.
* **[dart-lang/sdk](https://github.com/dart-lang/sdk):** Root-caused and fixed a macOS race condition where two analysis servers could corrupt a shared plugin snapshot mid-write, crashing the analyzer with a code-signature failure — merged, live in Dart 3.15 beta. Also fixed an `analysis_server` automated-fix bug that could silently change code meaning.
* **[dart-lang/dart_style](https://github.com/dart-lang/dart_style):** Merged fix.
* **[flutter/flutter](https://github.com/flutter/flutter):** Contributor — merged an iOS memory-management fix across iOS versions; several more in review (iOS 26 UIKit internals, touch passthrough, test-isolation flakes).
* **[flutter/packages](https://github.com/flutter/packages):** Migrating `url_launcher` to Pigeon's native-interop transport (FFI/JNI), with upstream Pigeon generator fixes (`@JvmOverloads`, Swift `@MainActor` support) along the way.
* **VLC for iOS:** 5 merged PRs (2018–2021).

## 🔬 Deep Dive & R&D

* **Multimedia:** Integrated **Mubert AI** (generative audio) and contributed to the open-source **VLC** player for iOS.
* **Systems Debugging:**
  * Reverse-engineered private frameworks to fix **Sberbank** security crashes.
  * Debugged **Metal shader memory layouts** via hex editors to fix rendering regressions.
  * Fixed low-level **AVPlayer** bugs on specific iOS versions by manipulating C++ internals.
* **Optimization:** Consolidated 400+ Figma UI variations into a single programmable system at Picsart.

---

## 💬 Contact

* **Telegram:** [@akhrameev](https://t.me/akhrameev)
* **LinkedIn:** [linkedin.com/in/akhrameev](https://linkedin.com/in/akhrameev)

(っ◕‿◕)っ I run 🏃‍♂️ , ǝʅɔʎɔᴉun 🤡, play ukulele 🎸 and have 3 great kids: 👦👧👶

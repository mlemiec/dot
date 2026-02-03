# Dot. 🔘

**Capture at the speed of thought.**

Dot is a minimalist, high-density reminder tool built for the **RevenueCat Shipyard 2026**. Designed with the "Beckman" aesthetic—utility-first, gesture-driven, and ultra-clean—Dot eliminates the friction between an idea and its record.

---

## 🚀 The Vision
Most reminder apps are cluttered with folders, sub-tasks, and complex UIs. **Dot** strips it all away. By combining **Natural Language Processing (NLP)** with **Interactive Home Screen Widgets**, Dot allows you to manage your life without ever actually "opening" an app.

### 🌟 The "Golden Path"
1. **Interactive Widget:** Tap a minimalist dot on your home screen.
2. **Instant Input:** Type "Coffee with Sam Friday at 10am."
3. **Smart Parsing:** Our NLP engine schedules the alert and updates the UI instantly.
4. **Haptic Confirmation:** A premium physical click sensation (Taptic Engine) confirms the save.

---

## 🛠️ Technical Stack
* **Framework:** Expo (React Native) + Expo Router (File-based Routing)
* **Styling:** NativeWind (Tailwind CSS) for consistent, high-speed design.
* **Animations:** Reanimated 3 for 60fps layout transitions and micro-interactions.
* **Intelligence:** `chrono-node` for robust Natural Language Processing.
* **Database:** Local-first `expo-sqlite` for zero-latency interactions.
* **Monetization:** **RevenueCat SDK** + Paywalls UI for entitlement management.

---

## 💰 Monetization & RevenueCat
Dot treats monetization as a premium upgrade for power users. We use **RevenueCat** to manage:
* **Feature Gating:** Users get 5 "Dots" (reminders) for free. Unlimited dots are unlocked via the **Dot Pro** subscription.
* **The Look:** Custom "Onyx," "E-Ink," and "Glass" widget themes are gated behind the Pro tier.
* **Remote Configuration:** Paywalls are managed server-side, allowing us to A/B test pricing without app store updates.

---

## 🗺️ Build Roadmap

### Phase 1: Foundation (Hours 0-12)
- [ ] Initialize Expo project with SQLite persistence.
- [ ] Implement the `chrono-node` NLP input field.
- [ ] Establish the "Beckman" Design System (Typography & Palette).

### Phase 2: The Widget & UI (Hours 12-24)
- [ ] Build the Interactive Home Screen Widget.
- [ ] Add `Reanimated 3` layout animations for list items.
- [ ] Implement Haptic Feedback patterns for all user actions.

### Phase 3: Revenue Integration (Hours 24-36)
- [ ] Integrate **RevenueCat SDK**.
- [ ] Build the "Dot Pro" Paywall using RevenueCat’s native UI components.
- [ ] Create the entitlement-checker hook to gate premium themes and unlimited tasks.

### Phase 4: Polish & Pitch (Hours 36-48)
- [ ] Finalize the onboarding flow.
- [ ] Performance audit for 120Hz displays.
- [ ] Record the "Golden Path" demo video for submission.

---

## 👨‍💻 Author
Built by an Advanced Solo Developer for the RevenueCat Shipyard 2026.

---

*Note: This project is a hackathon submission. Pricing and features are subject to simulated testing.*

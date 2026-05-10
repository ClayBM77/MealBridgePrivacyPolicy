# Meal Bridge — Privacy Policy

**Last updated:** [May 10, 2026]

**Contact:** [bridger.mason@icloud.com]

Meal Bridge (“the App”) is provided by Bridger Mason. This policy describes how information is handled when you use the App.

## Summary

- **Families and meals** you enter are stored **on your device** and, when you use iCloud, processed by **Apple’s iCloud and CloudKit** according to [Apple’s privacy policy](https://www.apple.com/legal/privacy/).
- **Meal suggestions** may be generated using **Google AI (Gemini)** accessed through **Firebase**; when you use that feature, relevant context you provide (such as family or meal preferences as reflected in the App) is sent to those services to produce suggestions.
- The App does not sell your personal information.

Replace bracketed placeholders before publishing. Update this document when you change features or third-party services.

---

## 1. Information the App collects or processes

### Information you provide

- **Family and household details** you choose to enter (for example family names, people, meal planning inputs).
- **Meal-related preferences or notes** you add inside the App.

### Information processed automatically

- **Device and app configuration** needed to run the App (for example appearance settings stored on device).
- **Technical data** associated with **Firebase** and **Firebase App Check**, which may include limited device or integrity signals used to protect backend access, as described in [Google’s Firebase / Google privacy documentation](https://firebase.google.com/support/privacy).
- If you enable or the App uses **remote notifications**, Apple’s **push notification** infrastructure may process tokens or related metadata as described in Apple’s documentation.

---

## 2. How we use information

- To **provide core features**: organizing families, planning meals, and optional **AI-generated meal suggestions**.
- To **sync or share** data when you use **iCloud / CloudKit** or sharing features supported by the App.
- To **maintain security and reliability** of connections to Firebase (including App Check where configured).

---

## 3. Where data is stored and who receives it

### On your device

Information you enter is stored locally using **Apple’s Core Data** on your device.

### Apple (iCloud / CloudKit)

The App uses **CloudKit** (via `NSPersistentCloudKitContainer`) with a CloudKit container tied to your Apple ID. Data synced through iCloud is subject to **Apple’s terms and privacy policy**. Apple processes this data as a processor under Apple’s policies, not as “our” server farm.

### Google / Firebase / generative AI

When you request **AI meal suggestions**, the App may send **prompt text** (including instructions and **JSON or text context** derived from the families and preferences you have in the App) to **Google’s generative AI (Gemini)** through **Firebase**. That processing is governed by:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [Firebase Privacy and Security information](https://firebase.google.com/support/privacy)

**Do not enter** health information, precise location, financial account numbers, government IDs, or other highly sensitive categories into the App unless you accept the risk that such content could be included in prompts sent for AI processing.

### Sharing with other people

If you use **sharing** features, people you invite may see the shared content according to Apple’s CloudKit sharing behavior and the permissions you grant inside the App.

---

## 4. Retention and deletion

- **On device:** You can remove data by deleting content inside the App or by deleting the App (subject to iCloud behavior below).
- **iCloud:** Data may remain in your **iCloud account** until you remove it or manage iCloud data in **Settings** on your Apple devices or from [Apple’s account tools](https://appleid.apple.com/). We do not operate a separate “account deletion” portal for Apple-hosted CloudKit data.
- **Firebase / AI providers:** Retention of logs or inference traffic, if any, is governed by **Google’s** policies and your Firebase project configuration. Configure your Firebase project appropriately for production.

---

## 5. Children’s privacy

The App is not directed at children under 13 (or the age required in your jurisdiction). Do not use the App for child-directed services unless you comply with applicable laws (such as COPPA where relevant).

---

## 6. International users

If you use iCloud or Google services, data may be processed in the **United States** or other regions where Apple or Google operate infrastructure, as described in their respective policies.

---

## 7. Changes to this policy

We may update this policy from time to time. The **“Last updated”** date at the top will change when we do. Continued use of the App after changes means you accept the updated policy.

---

## 8. Contact

Questions about this policy: **bridger.mason@icloud.com**

---

# Qypto Nexus Privacy Policy

**Effective date:** November 2026  
**App:** Qypto Nexus  
**Package:** com.auzza.qnexus  
**Developer:** midmark0001

## 1. Information We Collect

Qypto Nexus ("the App") is a mobile game that simulates a virtual economy using in-app currency ("Q coins"). The App may collect the following information:

### Account Information
- **Firebase Authentication user ID** — generated when you sign in anonymously or link a Google account
- **Email address** — only if you link a Google account via Google Sign-In
- **Display name / profile info** — only if provided through your Google account

### Game and Transaction Data
- **Q coin balance** — your in-app currency balance
- **Transaction history** — records of Q coin earnings, gifts, and redemptions
- **Redemption requests** — gift card brand, value, and destination email (if you request a gift card)
- **Player progress** — game state, scores, and achievements stored locally and/or on Firebase

### Device and Technical Data
- **Firebase Installation ID** — used for Firebase Cloud Messaging and App Check
- **App Check token** — used to verify app integrity when calling backend functions
- **Device model, OS version, and locale** — standard Firebase analytics data

## 2. How We Use Your Information

- To authenticate your account and sync your progress across devices
- To grant and track Q coin balances and redemptions
- To process gift card redemption requests
- To prevent abuse and fraud via Firebase App Check
- To improve the App experience

## 3. Third-Party Services

The App integrates with the following third-party services:

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| **Firebase (Google)** | Authentication, Firestore database, Cloud Functions, App Check, Crashlytics | User ID, email (if Google-linked), game data, device info |
| **Google Sign-In** | Google account linking | Google profile info (email, name) |
| **Google Play** | App distribution, in-app purchases (if applicable) | Purchase data via Google Play Billing |
| **Blink (Lightning)** | Bitcoin/Lightning payouts (admin-side only) | Lightning address (if you request a withdrawal) |

## 4. Data Storage

- **Firebase Firestore** — user profiles, Q balances, and redemption records are stored in Google Cloud Firestore (region: us-central1)
- **Local storage** — game progress and settings may be stored on your device via shared preferences
- Data is retained as long as your account exists. You may request deletion by contacting us.

## 5. Your Choices

- **Sign out** — you can sign out of your Google account at any time from the App's account screen
- **Delete account** — contact us to request deletion of your Firebase user data
- **Opt out of redemptions** — you are never required to request gift cards or withdrawals

## 6. Children's Privacy

The App is not intended for children under 13. We do not knowingly collect personal information from children under 13.

## 7. Security

We use Firebase Authentication and Firestore security rules to protect your data. All Q coin crediting and redemptions are handled server-side via Firebase Cloud Functions — the App cannot directly modify your balance.

No method of transmission over the internet is 100% secure. We cannot guarantee absolute security.

## 8. Changes to This Policy

We may update this policy from time to time. Continued use of the App after changes are posted constitutes acceptance.

## 9. Contact

For questions about this privacy policy or to request data deletion, contact the developer through the App or via GitHub: https://github.com/midmark0001

---

*This privacy policy applies to Qypto Nexus (com.auzza.qnexus) and its backend services on Firebase.*
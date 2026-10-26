# Privacy Policy – Zodiara

**Effective date: October 26, 2026**
Developer: Ricardo Retamal  
Contact: hello@rretamal.dev

## About Zodiara

Zodiara provides horoscopes and symbolic tarot and compatibility readings for reflection and entertainment. You do not need to enter a name or email address to use the app. The app automatically creates a guest identity for your installation through Firebase Authentication to operate the moons wallet and recover readings.

## Information processed

- **Guest identity and wallet:** a pseudonymous guest account identifier, moon balance, daily refills, reward tickets, advertising reward verification, reading reservations, charges and refunds. A refresh credential is kept in the device's secure storage. Server records support delivery, recovery and fraud prevention.
- **Readings:** selected cards, zodiac signs, language and completed generated readings are stored with reading operations so you can reopen them. Zodiara uses artificial intelligence to generate entertainment content based on your selections. The selected cards, zodiac signs and language are processed by Microsoft Azure AI Foundry. Your name, email address, authentication credentials and guest account identifier are not included in these generation requests.
- **Usage events:** the app sends event names, timestamps, a randomly generated installation identifier and event parameters, such as selected sign or language, to our server. Events are stored in Google Cloud Firestore. The service also keeps operational logs for troubleshooting and security.
- **Notifications:** Firebase Cloud Messaging processes registration identifiers to deliver enabled push notifications. You can disable notifications in your device settings.
- **Advertising:** when you choose a rewarded advertisement, Google AdMob processes device and advertising identifiers, advertising interactions, diagnostics and potentially approximate location inferred from an IP address, subject to applicable choices and SDK configuration. The updated app uses a temporary verification token so our server can validate the reward without sending your guest account identifier to the advertising provider. Versions that use the previous verification flow cannot request rewarded ads after the server update. No moons are granted merely because an ad was opened or closed.

The app does not request access to your contacts, camera, microphone or precise GPS location. An optional date picker can determine your zodiac sign; the chosen birth date is stored locally, and only the resulting sign is needed for reading generation. We do not ask for a real name or home address to generate readings. If you use friendship invitations, the server stores invitation and installation identifiers, the chosen display name, signs, friendship links and visit-streak information needed to show that feature. Notification preferences include your chosen time and time zone. If you contact support, your message and contact details are used to handle your request.

## Purposes and providers

We process this information to deliver content, maintain your wallet and reading history, send enabled notifications, understand app use, diagnose errors, prevent duplicate charges and rewards, and provide optional advertising.

Providers include Google Firebase Authentication, Cloud Firestore, Cloud Messaging, Cloud Run and AdMob, and Microsoft Azure AI Foundry. Providers may process information outside your country. Their policies provide further information: [Google Privacy Policy](https://policies.google.com/privacy), [Firebase privacy](https://firebase.google.com/support/privacy), and [Microsoft Privacy Statement](https://privacy.microsoft.com/privacystatement).

## Advertising choices

Rewarded advertisements are optional. The daily horoscope and daily card do not require watching an advertisement. Where applicable, Google's User Messaging Platform presents advertising choices before requesting ads. Refusing personalized advertising does not guarantee that an advertisement will be available. Where Google requires privacy options, you can reopen them from the privacy button on the moons screen. Advertising identifiers can be managed in your device's privacy settings; reinstalling the app does not itself reset the system advertising identifier.

## Storage, security and retention

App-to-server communication uses HTTPS. Guest authentication credentials use device secure storage, and wallet updates are processed by the server rather than direct mobile database writes.

Wallet activity, completed readings and usage events currently do not expire automatically. Operational logs and provider-managed records are retained according to their configured retention settings. You may request deletion, subject to applicable legal, security and fraud prevention requirements.

Clearing app data or losing the guest credential can prevent access to the original balance and history. Guest account linking and cross-device recovery are not available in this version. Removing the app does not automatically delete server records.

## Privacy requests

Depending on applicable law, you may have rights to access, correct or delete information and to withdraw consent or object to certain processing. Contact **hello@rretamal.dev** with your request. Because guest users do not register an email address, we may need information sufficient to locate and verify the relevant guest record. Do not send authentication tokens or passwords by email. In the updated app, open Profile → Privacy and my data → Request deletion of my data. After confirmation, the app sends an authenticated request and pauses account access while it is processed. Deletion is not instant: legacy installation records require an ownership review before processing. You can check the request status from that screen. Processing removes the Firebase guest account, moon balance, reading operations and associated verified installation records, including notification registration, usage events and friendship links. Local credentials and saved reading files are removed when the app receives completion confirmation. A minimal deletion-request status record remains for support and to prevent duplicate processing.

Outside the app, visit [Zodiara data deletion](https://zodiara-a11b5.web.app/delete-data.html) or contact **hello@rretamal.dev** to initiate a request. Do not send passwords, Firebase credentials or advertising IDs by email. Requests are handled in accordance with applicable law.

## Children and changes

Zodiara is not directed to children under 13. Contact us if you believe a child has supplied information that should be removed. We may update this page as the service changes and will update its effective date when a revision is published.

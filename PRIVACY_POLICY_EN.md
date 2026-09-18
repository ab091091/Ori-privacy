# Ori Privacy Policy

Effective date: September 17, 2026

Ori is an offline-first app for pet care, pet health, training, and reminder tracking. It is designed so that data created by the user primarily stays on the user's own device, with the user deciding when to back up, export, or share it.

## Data Covered by This Policy

Ori lets users enter or create:

- Pet profile information.
- Daily care records such as feeding, water, stool, walks, and weight.
- Vaccines, deworming, medication, supplements, and dose history.
- Veterinary visits, pet-health records, training sessions, reminders, and reminder completion history.
- Photo attachments and notes that the user explicitly adds.
- App settings and device-local states related to notifications or biometric protection.

This information is used for in-app record keeping, search/history, pet-health trends and data-based insights, local reminders, health reports, backup, restore, and export actions initiated by the user.

## Whether the Publisher Collects or Shares Data

The current version of Ori:

- Does not require an Ori account or sign-in.
- Does not operate an Ori cloud-sync, analytics, advertising, care-data, or pet-health-data backend.
- Does not proactively send pet, care, health, training, reminder, or photo-attachment data to the Ori publisher.
- Does not use advertising or cross-app tracking.
- Does not proactively sell or provide user data to third parties.

This means that although Ori processes user-created care data locally on the device, the current publisher does not collect that primary care data onto its own servers.

If a future release adds accounts, cloud sync, analytics, crash reporting, advertising, or another feature that sends data to the publisher or a third party, this policy and the relevant store disclosures will be updated before that release is published.

## Device Permissions and System Features

- **Notifications:** If the user grants permission, Ori can schedule feeding, medication, and other care reminders. Declining notification permission does not affect normal record-keeping features.
- **Boot completion events (Android):** Used to restore or reschedule locally configured reminders after a device restart or app replacement/update.
- **File selection and sharing:** Used only when the user actively imports, exports, or shares backups, CSV files, PDF reports, or similar files through operating-system picker/share flows. The user chooses the destination or receiving app.
- **Biometrics:** Users may optionally protect access to the app with device biometric authentication. Authentication is handled by the operating system; Ori does not read or store fingerprints, face data, or other raw biometric information.

## Local Storage, Retention, and Deletion

The primary pet-care database, in-app automatic backups, and private photo attachments are stored inside the app sandbox. Data is generally retained until the user deletes it in the app, clears app data, or removes the app, subject to operating-system behavior.

Users can delete individual records or pets in the app. Related data is handled according to the app's data relationships when a pet is deleted. Ori currently has no server-side account or server-side user dataset, so there is no separate remote account data that must be deleted by contacting Ori.

## System Backup and Device Transfer

Ori does not operate its own cloud synchronization service. Where supported by the platform, Ori disables or excludes private app data from operating-system-managed backup:

- Android disables system cloud backup and device transfer for Ori private app data.
- iOS excludes the primary/recovery SQLite data, automatic backups under Application Support, and Ori's private attachment directory from device/iCloud backup.

## Export, Backup, and Restore

Data transfer occurs only when the user actively uses Ori's backup, restore, or export features.

- Portable JSON backups may contain pet and care data and can optionally be protected with a password chosen by the user.
- Full Backups can additionally include private photo attachments and can also be password-protected.
- CSV and PDF exports may contain pet care or pet-health information.

Ori does not store user-chosen backup passwords and cannot recover them if they are lost. Once a file leaves the app sandbox, the selected storage location, cloud service, or sharing app is responsible for its subsequent storage and handling.

Portable restore does not treat notification authorization, notification scheduling, or biometric-enabled state as trusted state that can simply be restored across devices. These device-local settings must be re-established according to the permissions and configuration of the destination device.

## Data Security

Ori relies on the operating system's app sandbox to protect local private data and offers optional device-biometric locking. For cross-device storage, users can choose password-protected backups. If a user exports an unencrypted file, its security after leaving Ori depends on the destination selected by the user.

No local software can guarantee absolute security. Users should protect their device unlock method, backup passwords, and exported files.

## Pet Health Trends and Reports

Ori's health features concern **pet/veterinary care records only** and do not process human health or human medical data. Pet-health trends, data-based insights, and PDF reports summarize information entered by the user. They are not veterinary diagnoses, treatment recommendations, or emergency medical decisions. If there are concerns about a pet's health, users should consult a qualified veterinarian.

## Third-Party Apps and Services

Ori does not proactively provide care data to third parties. When the user stores or shares an exported file through an operating-system file picker, share sheet, or another external app, the selected third-party app or service may process that file under its own privacy policy. Such transfers are initiated by the user, and the destination is chosen by the user.

## Children's Privacy

Ori is not designed specifically for children and does not operate a publisher-controlled server account system for collecting children's personal information. The publisher must still complete Google Play's Target audience declaration according to the actual intended audience.

## Policy Updates

If Ori's features, permissions, third-party SDKs, or data-handling practices change, this policy will be updated before the relevant release is published. The effective date at the top of this page identifies the current policy version.

## Contact and Public Policy URL

- Contact email: oribignose@gmail.com
- Privacy policy URL: https://ab091091.github.io/Ori-privacy/

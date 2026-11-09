# Privacy Policy for MythosDraft

**Effective Date:** November 8, 2026  
**Last Updated:** November 8, 2026  
**Contact:** deltawarrior765@gmail.com  

---

## 1. Introduction

**MythosDraft** ("we", "our", or "the App") is an authoring studio and narrative architecture application designed for novelists, narrative designers, and world-builders. We believe that creative work—especially manuscripts, branching storylines, and world-building notes—deserves complete privacy, security, and confidentiality.

This Privacy Policy outlines how your data is handled when you use MythosDraft on Android devices.

---

## 2. Core Privacy Principle: 100% On-Device & Offline-First

- **Zero Tracking & No Ad SDKs:** MythosDraft does not contain any third-party advertising SDKs, tracking pixels, or user behavior analytics.
- **Local SQLite / Room Database:** All projects, manuscript drafts, storyboard logic nodes, character profiles, relationship matrices, and world lore entries are stored directly on your physical Android device in an encrypted/app-private local database.
- **No Third-Party Telemetry:** We do not collect, sell, rent, or trade your personal information or manuscripts with any third party.

---

## 3. Storage Access Framework (Private Local Folder)

MythosDraft allows you to select a custom local directory or SD card folder on your device using the standard Android Storage Access Framework (SAF):
- **User-Designated Storage:** When you select a folder, the App requests scoped permission (`ACTION_OPEN_DOCUMENT_TREE`) to write your plain-text Markdown files (`.md`), storyboard models (`.json`), character lists, and world bibles directly into that folder.
- **Local Control:** Files saved in this manner remain on your device's filesystem under your full control. You can inspect, copy, backup, or delete them at any time using your favorite file manager.

---

## 4. User-Controlled Cloud Synchronization & Backups

MythosDraft offers optional cross-platform backup capabilities for services including:
- **Google Drive**
- **Microsoft OneDrive**
- **Dropbox**
- **Jottacloud**

**How Cloud Sync Works:**
1. **Explicit Opt-In Only:** Cloud sync is entirely disabled by default. No data leaves your device unless you explicitly configure and enable a provider in the App settings.
2. **Direct Connection:** When enabled, data transfer occurs directly between your device and the selected cloud provider's official API using your personal credentials and designated remote directory.
3. **No Intermediate Servers:** We do not operate any intermediate proxy servers that read, cache, or store your manuscripts. Transfers are strictly point-to-point.

---

## 5. Export Capabilities (PDF, ePub, Markdown)

When you export your manuscript:
- The PDF, ePub, or Markdown package is generated locally on your device within the app's cache directory.
- Sharing is facilitated via Android's secure `FileProvider`, handing over the file only to the application you select (such as email, file storage, or reading apps) via the system share sheet.

---

## 6. Permissions Used by the Application

MythosDraft adheres to the principle of least privilege:
- `android.permission.INTERNET`: Used exclusively when you trigger cloud backup synchronization with your chosen cloud providers (Google Drive, OneDrive, Dropbox, or Jottacloud).
- `android.permission.ACCESS_NETWORK_STATE`: Used to check whether your device is connected to Wi-Fi or cellular networks prior to executing user-requested cloud backups.

MythosDraft **never** requests broad storage access permissions (`MANAGE_EXTERNAL_STORAGE` or `READ_EXTERNAL_STORAGE`). All local storage interactions use the privacy-preserving Android Storage Access Framework.

---

## 7. Data Retention & Deletion

- You retain complete ownership of all content you create in MythosDraft.
- You can delete individual story nodes, characters, lore entities, or entire projects from within the App at any time. Deleting a project permanently deletes all associated records from your device's local database.
- Uninstalling MythosDraft will remove the application database. If you have configured a private local folder, the Markdown and JSON export files stored in that folder will remain safely on your device until you decide to remove them.

---

## 8. Children's Privacy

MythosDraft does not target children under the age of 13, nor does it knowingly collect any personally identifiable information from children.

---

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect new features or platform updates. Any updates will be published with an updated "Last Updated" date.

---

## 10. Contact Us

If you have any questions or feedback regarding this Privacy Policy or your data privacy in MythosDraft, please reach out to us at:

**Email:** [deltawarrior765@gmail.com](mailto:deltawarrior765@gmail.com)

# Privacy Policy for WebTOC

**Effective Date: Jul 30, 2024**

## 1. Introduction

Welcome to WebTOC, a Chrome extension designed to generate a table of contents for the current webpage based on its header tags (h1-h6). We are committed to protecting your privacy and ensuring the security of your personal information. This Privacy Policy explains what data we collect, how we use it, and your rights regarding your data.

## 2. Information We Collect

WebTOC does not collect or store personal information. The extension operates entirely on the client-side, meaning all processing and data handling occur locally on your device.

## 3. Permissions We Request

WebTOC requires certain permissions to function correctly. These permissions include:

- **activeTab**: To access the content of the currently active tab for generating the table of contents. This is necessary for identifying and extracting header elements on the page.
- **storage**: To store extracted headings information temporarily. This allows efficient data transfer between the sidebar and content scripts, ensuring a responsive user interface.
- **sidePanel**: To display the table of contents in a non-intrusive manner, allowing users to view and navigate the page structure without disrupting the main content.
- **tabs**: To monitor tab activation and updates, ensuring the table of contents is synchronized with the current page content.

## 4. How We Use Information

WebTOC processes webpage header information to generate a table of contents. The data is not transmitted or stored on external servers. It is temporarily held using Chrome's `chrome.storage.local` API for the duration of your session and is only accessible to the extension.

## 5. Data Sharing and Disclosure

WebTOC does not share, sell, or disclose your data to third parties. Since all processing is done locally, your information is not exposed to external entities.

## 6. Data Security

We prioritize the security of your data. WebTOC operates in a secure manner, with no external data transmission or storage. The extension's use of permissions is limited strictly to its functionality.

## 7. User Control

You have full control over the extension. You can disable or remove WebTOC from your browser at any time via the Chrome extensions page.

## 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be posted on this page, and we will notify users of significant changes via the Chrome Web Store or the extension's user interface.

## 9. Contact Us

If you have any questions or concerns about this Privacy Policy or the practices of WebTOC, please contact us at hi@huyixi.com.

## 10. Consent

By using WebTOC, you consent to this Privacy Policy and the collection and use of information as described.

### Chrome Extension Permissions Rationale

**activeTab Permission:**

_Rationale:_ WebTOC requires access to the currently active tab to generate a table of contents for the page. This permission allows the extension to access the content and extract headings (h1-h6) from the page, essential for providing an accurate overview of the page structure.

**storage Permission:**

_Rationale:_ We use the `chrome.storage.local` API to store extracted headings information temporarily. This storage facilitates the efficient transfer of data between the sidebar and content scripts, ensuring a seamless and responsive user experience.

**sidePanel Permission:**

_Rationale:_ WebTOC utilizes Chrome's sidebar feature to present the table of contents in a user-friendly, non-intrusive manner. This feature enables users to navigate the page structure without interfering with their reading experience.

**tabs Permission:**

_Rationale:_ The extension needs to monitor tab activation and updates to refresh the table of contents when users switch tabs or load new pages. This ensures that the content presented in the sidebar is always up-to-date with the current page, providing users with relevant navigation aids.

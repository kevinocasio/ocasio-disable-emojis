# Ocasio Disable Emojis

> Lightweight WordPress plugin to remove extra emoji scripts, styles, and DNS prefetch links to boost page speed.

## Overview

Modern operating systems already have full native emoji support. **Ocasio Disable Emojis** dequeues WordPress core emoji scripts and inline styles to speed up page load times without breaking standard emojis.

## Features

* **Remove Emoji Scripts:** Blocks `wp-emoji-release.min.js` on public pages.
* **Strip Inline Styles:** Cleans up unnecessary inline styles from your header.
* **Stop DNS Prefetch:** Removes redundant DNS prefetch requests to `s.w.org`.
* **Zero Front-End Assets:** Pure PHP execution with 0 bytes of extra CSS or JS loaded on public pages.
* **Instant Dashboard Toggle:** Manage and toggle the switch directly from the **Ocasio Plugins** dashboard.

## Installation

1. Click the green **`< > Code`** button at the top of this repository and select **Download ZIP** (or download from [Releases](../../releases)).
2. In your WordPress admin dashboard, navigate to **Plugins -> Add New Plugin -> Upload Plugin**.
3. Choose the downloaded `ocasio-disable-emojis.zip` file and click **Install Now**.
4. Click **Activate Plugin**.
5. Manage settings directly under the **Ocasio Plugins -> Dashboard** menu.

---

## Author & Support

* **Author:** [Kevin Ocasio](https://kevinocasio.com/)
* **Plugin Page:** [Ocasio Disable Emojis on KevinOcasio.com](https://kevinocasio.com/wordpress-plugins/ocasio-disable-emojis/)
* **WordPress Plugins:** [Free WordPress Plugin Directory](https://kevinocasio.com/wordpress-plugins/)
* **Software Portfolio:** [Live Projects & Digital Assets](https://kevinocasio.com/portfolio/)
* **Tools & Resources:** [Recommended Tech Stack & Tools](https://kevinocasio.com/tools/)
* **License:** GPL-2.0-or-later

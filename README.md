<a name="top"></a>

[![OpenOffice.org 2.4](assets/openoffice-banner.png)](http://www.openoffice.org)

[![Platform](https://img.shields.io/badge/OS-Windows%2098%2C%202000%2C%20XP-blue)](#️-system-requirements)
[![License](https://img.shields.io/badge/License-LGPL-blue)](http://www.openoffice.org/license.html)
[![Languages](https://img.shields.io/badge/Available%20in-Multiple%20Languages-ff69b4)](http://www.openoffice.org/about_us/introduction.html)
[![Support](https://img.shields.io/badge/User%20Support-Available-brightgreen)](#-support)
[![Community](https://img.shields.io/badge/Join%20Us-Contribute-ff8c00)](#-contributing)
[![FAQ](https://img.shields.io/badge/FAQ-Common%20Questions-1d76db)](http://user-faq.openoffice.org/)

---

## 📚 Table of Contents

- [Introduction](#introduction)
- [About](#about)
- [System Requirements](#system-requirements)
- [Installation](#installation)
  - [Windows 98 Users](#windows-98-users)
- [Known Issues](#known-issues)
  - [Startup Problems](#startup-problems)
  - [Touchpad Doesn’t Scroll](#touchpad-doesnt-scroll)
  - [ZoomText Compatibility](#zoomtext-compatibility)
- [Compatibility Tips](#compatibility-tips)
  - [Clipboard Issues](#clipboard-issues)
  - [Email Crashes](#email-crashes)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Support](#support)
- [Bug Reporting](#bug-reporting)
- [Contributing](#contributing)
  - [Active Mailing Lists](#active-mailing-lists)
- [License](#license)
- [Acknowledgements](#acknowledgements)
- [🔝 Back to top](#top)

## Introduction

Welcome to the **OpenOffice.org 2.4** README! This document is your go-to guide for installing, troubleshooting, and contributing to OpenOffice.org 2.4. Whether you're a first-time user or a seasoned contributor, you'll find everything you need to get started and make the most of this free and open-source office suite.

> [!NOTE]  
> You may encounter issues like installation errors, compatibility problems, or feature limitations. This README provides step-by-step solutions, tips, and resources to help you resolve them quickly.

---

## About

**OpenOffice.org 2.4** is a free and open-source office suite for writing, calculating, presenting, and more — without license fees.

> 🎯 Ideal for individuals, schools, companies, and governments.

- 🔗 [Official Website](http://www.openoffice.org)
- 📜 [License Info](http://www.openoffice.org/license.html)

---

## System Requirements

| Requirement | Details |
|-------------|---------|
| OS          | Windows 98 / ME / NT / 2000 / XP |
| RAM         | 64 MB (minimum) |
| CPU         | Pentium-compatible |
| Disk Space  | 250 MB (CJK: 300 MB) + 500 MB free after install |
| Screen      | 800x600 minimum, 256 colors |

> [!IMPORTANT]  
> For optimal performance, ensure your system exceeds the minimum requirements.

---

## Installation

Follow these steps to install OpenOffice.org 2.4:

1. **Close** other programs before you start.
2. Make sure you have **administrator rights** on your computer.
3. Check that there’s enough **free space** on your hard drive and in your system's **temporary files folder**.
4. Run the installer and follow the on-screen instructions.

> [!TIP]  
> You can install OpenOffice.org 2.4 without removing older versions. Just run the new installer, then choose **Repair** if needed.

### Windows 98 Users

If you’re asked to **restart your PC** during Java installation, just restart and **open the installer again**.

---

## Known Issues

You may encounter the following issues while using OpenOffice.org 2.4. Here’s how to resolve them:

### Startup Problems

> [!WARNING]  
> The application doesn’t start. This is often a **graphics issue**.

**Solution:**

1. **Go to:**  
   ```
   Tools → Options → OpenOffice.org → View → 3D View
   ```
2. **Turn off** OpenGL.

---

### Touchpad Doesn’t Scroll

> [!CAUTION]  
> Scrolling doesn’t work on laptops with Synaptics or ALPS touchpads.

**Solution:**

1. **Edit** the file:  
   ```
   C:\Program Files\Synaptics\SynTP\SynTPEnh.ini
   ```
2. **Add** these lines:
   ```ini
   [OpenOffice.org]
   FC = "SALFRAME"
   SF = 0x10000000
   SF |= 0x00004000
   ```
3. **Restart** your computer.

> [!IMPORTANT]  
> Changes won’t take effect until you restart your computer.

---

### ZoomText Compatibility

> [!NOTE]  
> Older versions of ZoomText may not work properly.

**Solution:**  
Ensure you're using **ZoomText 7.11+** (downloaded after June 12, 2002).

---

## Compatibility Tips

### Clipboard Issues

> [!NOTE]  
> Copy/Paste between version 1.x and 2.4 may fail.

**Solution:**

1. **Use** `Edit → Paste Special`.  
2. **Choose** a format like plain text instead of OpenOffice format.

---

### Email Crashes

> [!CAUTION]  
> Some systems crash when sending files via:  
> ```
> File → Send → Document by Email or as PDF
> ```

**Solution:**  
Search Microsoft’s Knowledge Base for **“mapi dll”** to resolve this issue.

---

## Keyboard Shortcuts

Some shortcuts may be overridden by Windows.  
You can customize them in:  
```
Tools → Customize → Keyboard
```

---

## Support

Need help? Here’s where to find it:

- 📨 Ask questions: [users@openoffice.org](https://www.openoffice.org/mail_list.html)
- 📚 [User FAQ](http://user-faq.openoffice.org/)
- 🧭 [Mailing List Directory](http://www.openoffice.org/mail_list.html)

> [!TIP]  
> Subscribe to the mailing list to receive replies to your questions.

---

## Bug Reporting

Found a bug or issue?  
Please report it using the [IssueZilla bug tracker](https://www.openoffice.org/FAQs/faq-issuezilla.html).

---

## Contributing

You don’t need to be a developer to help! 

You can:
- Translate content.
- Improve documentation.
- Help with marketing.
- Join a sub-project.

### Active Mailing Lists

| Purpose        | Email                          |
|----------------|--------------------------------|
| Announcements  | announce@openoffice.org       |
| User Support   | discuss@openoffice.org        |
| Marketing      | dev@marketing.openoffice.org  |
| Developers     | dev@openoffice.org            |

📬 [Join Mailing Lists](http://www.openoffice.org/mail_list.html)  
📂 [See All Projects](http://projects.openoffice.org/index.html)

---

## License

This software is released under the [LGPL license](http://www.openoffice.org/license.html).

> Portions © 1998–1999 James Clark  
> Portions © 1996–1998 Netscape Communications Corporation

---

## Acknowledgements

Thanks to every user, developer, translator, and tester who made OpenOffice.org possible.

📣 [Join us today](http://www.openoffice.org)

---

[![Logo](assets/opengl-logo.png)](http://www.opengl.org)

[🔝 Back to top](#top)

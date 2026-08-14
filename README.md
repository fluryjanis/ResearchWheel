# 🧪 Research Wheel

**Research the web without constantly switching tabs.**

Research Wheel puts research tools directly alongside the information you're reading. Save quotes, search research sources, generate citations, and organize your findings with a simple middle-click workflow.

## 📥 Installation

### 🦊 Firefox

The recommended installation method is Firefox Add-ons.

**[Install Research Wheel for Firefox](https://addons.mozilla.org/en-US/firefox/addon/research-wheel/)**

### 🌐 Chrome / Chromium

Chrome and Chromium-based browsers can install Research Wheel manually using the v2.0.0 release package.

**[⬇️ Download Research Wheel v2.0.0 for Chrome / Chromium](https://github.com/fluryjanis/ResearchWheel/releases/tag/v2.0.0)**

#### Install

1. Download the Chrome/Chromium ZIP from the **v2.0.0 release**.
2. Extract the ZIP to a folder on your computer.
3. Open `chrome://extensions/`.
4. Enable **Developer mode**.
5. Click **Load unpacked**.
6. Select the extracted Research Wheel folder.

Research Wheel can then be used directly in your browser.

> **Note:** Chrome/Chromium installation is currently a manual developer-mode installation rather than a Chrome Web Store installation.
---

<p align="center">
  <img src="https://github.com/user-attachments/assets/d5864076-cfa8-4204-9285-41cfdafa54f1" width="28%" alt="Research Wheel middle-click research menu" />
  <img src="https://github.com/user-attachments/assets/917ae478-0fcb-4c8f-8e5d-6d56e0cdd9c8" width="28%" alt="Research Wheel citation formatting" />
  <img src="https://github.com/user-attachments/assets/4233ca45-8d4f-414c-87dd-3bd722f1e80d" width="38%" alt="Research Wheel research workspace sidebar" />
</p>

---

## 🔬 What Is Research Wheel?

Research Wheel is a Firefox browser extension designed to make web research faster and easier.

Instead of constantly switching between webpages, search engines, note-taking apps, and citation tools, Research Wheel keeps common research actions close to the information you're working with.

**Find something → middle-click → research, save, or cite it.**

It's useful for:

* Students
* Researchers
* Writers
* Developers
* Journalists
* Anyone who regularly collects information from the web

---

## ⚡ How It Works

### 1. Find something useful

Browse the web normally and find information worth researching, saving, or citing.

### 2. Middle-click

Select text and middle-click to open the Research Wheel directly where you're working.

### 3. Take action

Search research sources, save notes and quotes, generate citations, translate text, or copy useful source information.

---

## 🛠️ Features

### 🔎 Search Research Sources

Search **Google Scholar** or **PubMed** using selected text or the current webpage title without manually opening another tab.

### 📝 Save Research as You Browse

Save highlighted text directly to the Research Wheel workspace.

Collect:

* Quotes
* Notes
* Code
* URLs
* Source information

Keep useful information together instead of losing it across dozens of browser tabs.

### 📚 Generate Citations

Generate and copy citations in:

* **APA 7th**
* **MLA 9th**
* **Chicago 17th**
* **BibTeX**

Research Wheel also cleans webpage metadata to produce more useful citation information from messy webpages.

### 📂 Research Workspace

Use the Firefox sidebar as a persistent workspace for your collected research.

Review and manage saved notes, quotes, citations, and sources while continuing to browse.

### 🌐 Translate Webpage Text

Translate webpage content directly from the Research Wheel menu using available translation services.

### 🔗 Copy Sources Easily

Copy a clean Markdown link containing the page title and URL.

### 📋 Quote + Source

Copy selected text together with its source attribution as a Markdown blockquote.

---

## 🧭 Radial Wheel Actions

Research Wheel provides eight research actions through its middle-click radial menu.

| Direction     | Action             | What it does                               |
| ------------- | ------------------ | ------------------------------------------ |
| 🎓 North      | **Google Scholar** | Search selected text or the webpage title  |
| 🧬 North-East | **PubMed**         | Search selected text or the webpage title  |
| 📝 East       | **Append Note**    | Save selected text to the workspace        |
| 📚 South-East | **Citation**       | Generate and copy a citation               |
| 📂 South      | **Workspace**      | Open the research sidebar                  |
| 🌐 South-West | **Translate**      | Translate webpage content                  |
| 🔗 West       | **Title + URL**    | Copy a clean Markdown link                 |
| 📋 North-West | **Quote + Source** | Copy selected text with source attribution |

---

## 🔒 Privacy First

Research Wheel is designed as a **local-first browser extension**.

The extension operates locally on your device and does not use external servers for its core workspace functionality.

**No tracking. No analytics. No collection of your browsing activity.**

The project is also open source, allowing you to inspect how the extension works yourself.

> **Your research should belong to you.**

---

## 🧠 Built for Real Web Research

Webpages aren't always clean.

Article titles can contain:

* Site names
* Taglines
* Publisher branding
* Inconsistent capitalization
* Unusual apostrophes
* Incorrect metadata
* Messy author information

Research Wheel includes several systems designed to clean and normalize this information before it reaches your research workspace or citation output.

### Proper Noun Handling

Preserves important names, organizations, locations, acronyms, and other proper nouns while formatting article titles.

### Site Tagline Removal

Removes common publisher suffixes and branding from scraped webpage titles.

### Homepage Detection

Detects root and localized homepages to improve source metadata and publisher identification.

These systems exist for one reason:

**Cleaner research results and more useful citations.**

---

## ⚙️ Technical Details

Research Wheel is built for Mozilla Firefox using the **WebExtensions API** and **Manifest V3**.

The extension includes several systems designed specifically around Firefox's interaction behavior.

### Native Autoscroll Preservation

Middle-click interactions are handled without unnecessarily interfering with Firefox's native autoscroll behavior.

### Selection Capture

Research Wheel captures text selection during mouse interaction so that selected text remains available when the radial menu opens.

### Interaction Locking

While the radial wheel is active, relevant scrolling and keyboard interactions are temporarily controlled to prevent accidental page movement.

### Shadow DOM Isolation

The radial interface uses isolation techniques to reduce conflicts with webpage styles.

---

## 💻 Development

Clone the repository:

```bash
git clone https://github.com/fluryjanis/ResearchWheel.git
```

Then load the project as an unpacked browser extension.

The project is primarily designed around Firefox and its WebExtensions environment.

---

## 📦 Export Your Research

Research Wheel supports exporting collected workspace research to local Markdown files.

This keeps your research portable and avoids locking your notes into a proprietary cloud service.

---

## 🗺️ Project History

Research Wheel began as **QuickWheel**, a general-purpose radial browser interaction tool.

Version 2 pivoted the project toward web research, replacing generic browser shortcuts with research-focused actions.

### Version 2.0.0 — The Research Edition

* Rebranded QuickWheel as **Research Wheel**
* Added research-focused radial actions
* Added Google Scholar search
* Added PubMed search
* Added citation generation
* Added APA, MLA, Chicago, and BibTeX support
* Added persistent research workspace sidebar
* Added quote and note clipping
* Added Markdown export
* Added metadata cleaning and citation safeguards
* Added improved text-selection handling
* Added interaction protection against accidental scrolling and page movement

### Version 1.0.0 — QuickWheel

The original QuickWheel release provided a general-purpose radial browser menu with actions including:

* Tab duplication and reopening
* Search focus
* Markdown clipping
* Translation
* Scroll-to-top
* Tab muting
* Link copying

---

## 🔗 Links

* 🦊 **[Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/research-wheel/)**
* 💻 **[Source Code](https://github.com/fluryjanis/ResearchWheel)**
* 🌐 **[Research Wheel Website](https://fluryjanis.github.io/ResearchWheel/)**
* 🎮 **[Research Wheel on itch.io](https://frog1230.itch.io/researchwheel)**
* 👤 **[Frog1230 Portfolio](https://fluryjanis.github.io/frog1230.github.io/)** or **[Repo](https://github.com/fluryjanis/frog1230.github.io)**

### Other Projects

* [MindShield](https://frog1230.itch.io/mind-shield)
* [Content Chef](https://frog1230.itch.io/content-chef)
* [Remind Me](https://frog1230.itch.io/remind-me)

---

## 📜 Privacy & Disclaimer

### Privacy

Research Wheel is designed to operate locally and does not intentionally collect, sell, or transmit personal browsing data or analytics.

For the most accurate information about permissions and data handling, inspect the extension source code and Firefox Add-ons listing.

### Disclaimer

Research Wheel is provided **"as is"** without warranty of any kind. The developer is not responsible for issues or damages resulting from use of the software.

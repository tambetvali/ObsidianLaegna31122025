# 📘 ObsidianLaegna31122025  
**Conversion of a Notion.so knowledge base into an Obsidian‑friendly Markdown vault**

This repository contains a cleaned and structured export of a Notion workspace, prepared for use in **Obsidian**, **VS Code**, or any Markdown‑based knowledge system. The goal is to preserve the original content while making it easier to navigate, edit, and extend in a local folder‑based environment.

---

## 📤 1. From Notion Export → Markdown + CSV

Notion exports its pages as:

- **Markdown files** (`.md`)
- **CSV files** for databases
- **Folders** representing page hierarchies
- **Filenames containing UUID hashes**  
  (e.g., `My Page 123abc456def789ghi.md`)

The export already uses **UTF‑8**, so all non‑ASCII characters are preserved.  
However, the filenames often contain long hashes that users may want to remove for readability.

---

## 🧹 2. Removing Hashes From Filenames and Links

Notion adds long unique identifiers to filenames. These can be removed using:

- **offline renaming tools**  
- **online renaming tools**  
- **regex‑based search and replace**  
- **AI‑assisted filename cleanup**  
- **bulk renamers**  
- **scripts** (PowerShell, Bash, Python)

Because users have different preferences, this repository does not prescribe a specific tool.  
Instead, the workflow is:

1. **Rename files** to remove the UUID portion.  
2. **Update internal Markdown links** so they point to the new filenames.  
3. **Ensure folder structure remains intact.**

Searching for “remove hashes from filenames”, “bulk rename markdown links”, or asking Copilot will surface many suitable tools.

---

## 🧭 3. Working Directly With the Markdown Files

The exported Notion structure is already compatible with:

### ✔ Obsidian  
Obsidian can open this repository as a **vault** without any conversion.  
Just clone or download the repo and open the folder in Obsidian.  
Obsidian will:

- read the folder tree as a vault  
- index all Markdown files  
- preserve internal links  
- allow you to reorganize content freely

### ✔ VS Code  
VS Code can open the folder as a workspace.  
You can:

- edit Markdown files  
- run global search/replace  
- use extensions for Markdown navigation  
- use AI tools to clean filenames or update links

Both editors work directly on the folder structure, so no additional processing is required.

---

## 🔧 4. Improving the Vault With AI

AI tools (online or offline) can help with:

- renaming files  
- fixing broken links  
- restructuring folders  
- generating summaries  
- converting CSV tables into Markdown tables  
- merging or splitting notes  
- creating navigation indexes

You can use browser‑based AI, desktop AI tools, or editor extensions.  
The workflow is flexible and does not depend on any single platform.

---

## 🔌 5. Using the Notion API

For users who want to automate updates or fetch content directly from Notion, the Notion API provides:

- programmatic access to pages  
- structured retrieval of blocks  
- database queries  
- integration with AI tools  
- export pipelines

Documentation:  
https://developers.notion.com/

The original Laegna workspace is available here:  
https://assorted-canopy-961.notion.site/Laegna-1a575bfc115480a38129e9a9787ab565

AI tools can connect to the Notion API to:

- extract content  
- convert blocks to Markdown  
- synchronize updates  
- generate documentation

This repository represents a **static snapshot**, but users may build automated pipelines if needed.

---

## 🌐 6. Notaku: A Documentation‑Style View of Notion

The Laegna content is also available in a documentation‑style format via Notaku:

👉 https://laegna.notaku.site/

**What is Notaku?**  
Notaku is a service that converts Notion pages into:

- clean documentation websites  
- sidebar navigation  
- search  
- multi‑page manuals  
- responsive layouts

It is useful for users who prefer to read the content as a structured website rather than inside Notion or Obsidian.

This repository complements the Notaku site by providing:

- the raw Markdown  
- the folder structure  
- the editable source  
- a local knowledge base

---

## 📦 7. Purpose of This Repository

This repository exists to:

- preserve the Laegna knowledge base in an open, editable format  
- provide a clean Markdown version suitable for Obsidian  
- allow users to explore, reorganize, and extend the content  
- serve as a foundation for future documentation systems  
- enable AI‑assisted editing and restructuring

It is intentionally simple: a folder tree of Markdown files that can be used anywhere.

---

## 🤝 Contributions

Users may:

- reorganize the vault  
- clean filenames  
- fix links  
- add indexes  
- improve navigation  
- contribute additional Markdown pages

Please keep the structure readable and consistent.

---

## 📜 License

Content is provided for personal study, research, and non‑commercial use unless otherwise noted.

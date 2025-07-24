# Obsidian For Clarity: A Workflow Vault

This repository contains a sample Obsidian vault (`obsidian-for-clarity-1`) demonstrating the Personal Knowledge Management (PKM) workflow described in the accompanying article, Beyond Note Taking - Obsidian For Clarity

The purpose of this vault is to provide a practical, hands-on example of how to implement a system that transforms scattered daily thoughts into a comprehensive, insightful record, fostering both reflection and incremental writing.

## Why This Workflow?

In a world overwhelmed by information, clarity is power. Our thoughts often emerge as fragmented ideas, notes taken in haste, or fleeting insights across various projects. This workflow offers a solution to aggregate these disparate pieces into a unified view, allowing for deeper reflection and the continuous evolution of ideas. It's about optimizing the flow of information, much like advanced query optimization, but for your personal knowledge.

## Key Components

This workflow is built upon four pivotal Obsidian components:

1.  **Daily Notes:** Serving as the central hub for daily intellectual activity.
2.  **Dataview:** A powerful plugin used to dynamically aggregate notes into comprehensive lists.
3.  **"Mark as Reviewed" Plugin:** A custom solution to streamline the process of revisiting and reflecting on notes.
4.  **Templater:** Automating the creation and population of notes and entries.

## How to Use This Vault

To explore this workflow yourself:

1.  **Clone or Download:**
    * Clone this repository using Git: `git clone https://github.com/mr-nano/obsidian-for-clarity-1.git`
    * Alternatively, download the repository as a ZIP file and extract it.
2.  **Open in Obsidian:**
    * Open Obsidian.
    * Click "Open another vault" (bottom left corner or from the welcome screen).
    * Select "Open folder as vault" and navigate to the `obsidian-for-clarity-1` folder you just cloned or extracted.
3.  **Enable Community Plugins:**
    * Go to Obsidian **Settings** (gear icon).
    * Navigate to **Community plugins**.
    * **Turn off Restricted mode.**
    * Ensure **Dataview** and **Templater** plugins are enabled.
    * Ensure your custom **Mark as Reviewed** plugin is enabled (it should appear in the list).

## Workflow Overview

* **Daily Notes as Aggregation Hub:** Your daily note (e.g., `daily/2025-06-15.md`) contains a Dataview query that automatically pulls in all notes linked to that specific date. This creates a real-time dashboard of your intellectual activity.
* **Timestamped Entries for Connection:** New entries in "running notes" (like `thoughts/XYZ client.md`) are automatically timestamped (e.g., `[[YYYY-mm-dd]] at HH:mm:ss -`) when you use the shortcut. This timestamp acts as a backlink, ensuring that these entries appear in the relevant daily note.
* **Spaced Repetition with "Mark as Reviewed":** The custom "Mark as Reviewed" plugin allows you to quickly log when you've revisited a note, adding a timestamp to its `## Dates` section. This creates a review log, facilitating a form of spaced repetition for your knowledge.
* **Templater Automation:** Templater streamlines the creation of daily notes and the insertion of timestamped entries, minimizing manual effort and ensuring consistency.

### Key Hotkeys

* **Ctrl/Cmd + Shift + N:** Inserts a new timestamped paragraph, ideal for "Thoughts on" notes or quick captures.

## Files and Folders

* `.obsidian/`: Contains all Obsidian configuration files, including plugin settings, themes, and hotkeys.
* `daily/`: Contains your daily notes. See `daily/2025-06-15.md` for an example.
* `thoughts/`: Contains examples of "Thoughts on" running notes, such as `thoughts/XYZ client.md`.
* `templates/`: Stores the Templater templates used in the workflow.
* `plugins/`: Contains the community plugins and your custom `mark-as-reviewed` plugin.

## Contribution

This workflow is a living system! Feel free to explore, adapt, and improve it. I welcome feedback and suggestions to refine this framework further.

## License

This project is open-sourced under the [MIT License](LICENSE). 

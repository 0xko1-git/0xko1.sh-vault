# 0xko1.sh Pentest Notes Vault

A minimal Obsidian vault template for organizing penetration testing notes with the included **Pentest Note Manager** plugin.

The vault is intentionally empty and contains only the structure, templates, and configuration required to start building a pentesting knowledge base.

## Screenshots

### Vault home

The home dashboard acts as the main entry point to the pentesting library. It provides quick access to notes, playbooks, labs, filters, and the automatically generated knowledge graph.

There are multiple ways to navigate the vault. Press `F7` to quickly search for a pentest note by title, alias, area, service, tool, or other metadata.

You can also use the search field and filters directly in the library table below. This is useful when you want to browse the vault manually or narrow down notes by type, area, service, tool, status, or related metadata without using a keyboard shortcut.

![Vault home](assets/screenshots/home.png)

### Graph-based navigation

In addition to traditional search, the vault can also be explored visually through Obsidian's Local Graph.

Press `F9` while viewing a note to open its Local Graph on the right side. The graph shows the current note together with its related topics, areas, techniques, services, tools, and other connected notes.

This makes it possible to move through the knowledge base by following relationships instead of relying only on folders or search. It is especially useful when exploring a topic and discovering related techniques or notes that may be relevant to what you are currently working on.

![Note relationships](assets/screenshots/cme.png)

### Automatic graph hubs

Pentest Note Manager automatically creates graph hubs for note types, areas, services, tools, and other metadata.

For example, the `Type - Tools` hub connects all notes classified as tools, providing a visual overview of the tools stored in the vault and making larger collections easier to explore.

These hubs are generated automatically and form an additional navigation layer across the knowledge base.

![Tool graph hub](assets/screenshots/type-tools.png)

## Structure

```text
10 Notes/         General pentesting notes
20 Playbooks/     Reusable attack and enumeration playbooks
30 Labs/          Lab and machine notes
50 Inbox/         Temporary notes
80 Attachments/   Images and other attachments
90 Templates/     Templates used by Pentest Note Manager
99 Archive/       Archived content
_System/          Automatically generated graph structure
```

## Included plugin

The vault includes the custom **Pentest Note Manager** Obsidian plugin.

It provides:

* creation of structured pentesting notes
* automatic frontmatter
* automatic graph connections
* note categories based on type and area
* tool and service relationships
* related-note discovery
* searchable pentesting library
* automatic graph hubs

## Getting started

1. Clone the repository:

```bash
git clone https://github.com/0xko1-git/0xko1.sh-vault.git
```

2. Open Obsidian.

3. Select **Open folder as vault**.

4. Choose the cloned folder.

5. Enable community plugins if Obsidian asks for permission.

6. Enable **Pentest Note Manager**.

7. Open `START HERE.md`.

## Keyboard shortcuts

| Key  | Action                    |
| ---- | ------------------------- |
| `F6` | Create a new pentest note |
| `F7` | Find a pentest note       |
| `F8` | Open the vault home       |
| `F9` | Open Local Graph          |

## Templates

The following note types are included:

* Tool
* Service
* Technique
* Concept
* Playbook
* Lab
* Cheatsheet

Templates are stored in:

```text
90 Templates/
```

## Privacy

This repository contains an empty starter vault.

It does **not** contain pentest results, credentials, targets, client data, lab notes, API keys, tokens, or other sensitive information.

When using this vault for real engagements, review your notes carefully before committing or publishing them.

## Important

Back up your Obsidian vault before using the plugin with important data.

This project is provided as-is and is used at your own risk. The authors are not responsible for data loss, corrupted notes, broken vaults, or other damage resulting from use of the project.

## Disclaimer

This project is intended for:

* authorized penetration testing
* security research
* CTFs
* labs
* education

Only perform security testing against systems you own or have explicit permission to test.

## License

MIT License. See [LICENSE](LICENSE).


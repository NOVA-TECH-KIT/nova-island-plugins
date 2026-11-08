# Nova Island Plugins

Extra features for [Nova Island](https://github.com/NOVA-TECH-KIT/nova-island), added only by the people who want them.

Open **Nova Island → Settings → Plugins**, pick a plugin and press **Install**. That's all.

## Plugins

| Plugin | What it does | Price |
|---|---|---|
| **Quran Radio** | Live Qur'an radio on the island: Cairo, Saudi and 170+ reciters. Plays in the background, with its own Radio tab | Free |
| **Tasks** | A to-do list on the island: due times, reminders and Low, Medium, High and Urgent tags, with a Tasks tab and its own window. Built into Nova Island 1.8.3 and newer | Free |

## How it works

- `plugins.json` is the list Nova Island reads. Each plugin is one file (`.nvp`) attached to a release here, and the install count is that file's download count. Nothing is tracked.
- Every plugin and the list itself are signed with the Nova Island key. Nova Island refuses any file that was changed or not signed by us.
- Plugins hold content only, no code. Nova Island does the work for each kind of plugin.
- Tasks comes with Nova Island 1.8.3 and newer, on by default. It isn't in `plugins.json` yet, because older versions can't install it.

## License

GPL v3. Radio streams belong to their stations (Egyptian Radio, Saudi Broadcasting, mp3quran.net). Nova Island only plays their public links.

Copyright © 2026 Nova Island by AmerTech

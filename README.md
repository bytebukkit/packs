# Packs for ByteBukkit
To add a pack/dlc to the websites entry, you may do a pull request where you add your server icon and the entry in the json.
Alternatively you can also open a issue, and add your **1:1** ratio (Square) server-icon, and the required metadata for your server.

Allowed are: `Texture Packs, Mash-Up Packs, DLC, Skin Packs and Worlds`

Field Information (json):

      pack_name        (string)  — Display name
      pack_type        (string)  — "Texture" | "Mash-Up" | "DLC" | "Skin Pack" | "Other"
      pack_author      (string)  — Creator username
      pack_description (string)  — Short description shown on the card
      pack_icon        (string)  — Path relative to repo root, or full URL
      game_version     (string)  — e.g. "neoLegacy", "Revelations", "PS3", "Xbox 360", etc.
      github_url       (string)  — MUST be https://github.com/user/repo

How to add a pack entry into `packs.json`

You can paste this template snippet after the newest entry, make sure the last entry before yours ends with `},` and not only `}`, else there will be a Syntax error.
```json
      {
        "pack_name": "Community Pack",
        "pack_type": "Texture",
        "pack_author": "user1",
        "pack_description": "Fan-made community pack.",
        "pack_icon": "/icons/example.png",
        "game_version": "Revelations",
        "github_url": "https://github.com/user/community-pack"
      }
```

Once the PR is approved, your pack will show up a little something like this on ByteBukkit:

<img width="1127" height="238" alt="Capture" src="https://github.com/user-attachments/assets/c7b2cab6-0a6f-406f-b008-31bdd7131e4a" />

# My Codex Pets

Two Codex-compatible animated pixel-art pets, packaged with the v2 pet contract and designed to feel like quiet desktop companions.

## 安和昴

A shy, warm-hearted school-uniform companion with charcoal bobbed hair, violet eyes, and a mint striped bow. Her ambient animations include drinking coffee, writing in a notebook, and reading a book.

![安和昴 animation contact sheet](previews/an-he-mao-contact-sheet.png)

![安和昴 look directions](previews/an-he-mao-look-directions.png)

## 山田凉

A calm blue-haired companion with glasses, white headphones, a black T-shirt, and white denim shorts. Her ambient animations include drinking coffee, using a laptop, and drawing with a pen tablet.

![山田凉 animation contact sheet](previews/yamada-ryo-contact-sheet.png)

![山田凉 look directions](previews/yamada-ryo-look-directions.png)

## Package details

- Codex pet schema v2 (`spriteVersionNumber: 2`)
- 8 × 11 WebP sprite atlas per pet
- Nine standard animation rows
- Sixteen clockwise look directions
- Purpose-built companion actions for waiting, working, and reviewing
- Transparent backgrounds and validated cell boundaries
- Original reference images are not included in this repository

## Install

Copy either pet folder into your Codex pets directory. On Windows PowerShell:

```powershell
Copy-Item -Recurse -Force .\pets\an-he-mao "$env:USERPROFILE\.codex\pets\an-he-mao"
Copy-Item -Recurse -Force .\pets\yamada-ryo "$env:USERPROFILE\.codex\pets\yamada-ryo"
```

Restart or reload Codex if the newly installed pets do not appear immediately.

## Repository layout

```text
pets/
  an-he-mao/
    pet.json
    spritesheet.webp
  yamada-ryo/
    pet.json
    spritesheet.webp
previews/
  an-he-mao-contact-sheet.png
  an-he-mao-look-directions.png
  yamada-ryo-contact-sheet.png
  yamada-ryo-look-directions.png
```

These are personal, fan-made pet assets. No affiliation or endorsement is implied.

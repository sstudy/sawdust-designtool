# SawDust design gallery

Designs and templates shared by SawDust users, for others to open, study and adapt. Each folder holds one design:

```
gallery/<slug>/
  <slug>.swdt        the design (File → Open in SawDust)
  <image>.png        a viewport screenshot
  README.md          what it is and what it demonstrates
  template.json      only for templates — see below
```

## Using a design

Download the `.swdt` and open it with **File → Open**. It is an ordinary document: change the parameters, regenerate the cut list, print the drawings.

## Using a template

A template is a `.swdt` plus a `template.json` manifest. To install one, copy its folder into `%LOCALAPPDATA%\SawDust\templates\`. It then appears under **Edit → Insert Template…**. (See the user manual, "Templates — your own generators".)

## Sharing your own

Open a [Share a design](https://github.com/sstudy/sawdust-designtool/issues/new/choose) issue and attach the files. The rules:

- **Attach only the `.swdt`** (and `template.json` for a template) **and a screenshot.** Do not attach the `.swdt.chat.json`, `.swdt.log.json` or `.swdt.view.json` files that SawDust keeps beside a design. The chat transcript in particular can contain your own conversation.
- **Check the project name and notes** (File → Design Notes) for anything you would not want public. Clear them before saving the copy you share.
- **Reference photos:** a design's `.assets` folder is not needed and is not published. Share only photos you took yourself.
- **Licence:** everything in this gallery is offered under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0). By sharing a design you agree to that: anyone may use, adapt and redistribute it, with credit to you. Say how you want to be credited in the issue.
- Designs are reviewed before they are added, so allow a few days.

## WeKan Design Principles

- 2024-08 Design discussion here: https://github.com/wekan/wekan/discussions/5507
- Original WeKan Design:
  - Uses WeKan style confirm popups `Popup.afterConfirm(` , translations etc. Please look at existing code to keep same style.
  - Kanban, the good parts. Like was done when figuring out best design for Swimlanes https://github.com/wekan/wekan/issues/955
  - Intuitive, easy to figure out, prevent messing up something https://github.com/wekan/wekan/wiki/Monkey-Proof-Software
  - Polished UI/UX
  - Menu options are there where you would expect then to be.
  - Try to fix anything unexpected.
  - New features added there where it makes most sense.
  - Not too many toggles and settings, because that is worse. For example, Discord settings has too many toggles and settings. Just select some default.
  - FOSS with MIT license
  - Swimlanes
  - All the use cases of WeKan feature/fix contributors
  - Cross-platform. Support many CPU/OS/Browsers for Desktop and Mobile. 
  - Support many browsers https://github.com/wekan/wekan/wiki/Browser-compatibility-matrix . Add support for more.
  - PWA https://github.com/wekan/wekan/wiki/PWA
  - On-Premise:
    - Linux amd64/arm64/s390x
      - https://wekan.fi/install/
      - https://github.com/wekan/wekan/wiki/Raspberry-Pi 
    - Windows https://github.com/wekan/wekan/wiki/Offline
    - Mac https://github.com/wekan/wekan/wiki/Mac
- Not like other software:
  - But note that design of all software changes often, when they are in active development.
- Not bad parts of Trello:
  - Not the exact design of Trello https://github.com/wekan/wekan/wiki/FAQ#why-does-wekan-look-so-different-now-compared-to--v09
  - Not so many duplicate menus and texts like Trello
  - Not so much empty space
- Some good parts of Trello:
  - Import from Trello
  - Shortcuts https://github.com/wekan/wekan/issues/1878
  - IFTTT Rules like Trello Butler https://github.com/wekan/wekan/wiki/IFTTT
  - Progress bar of checklist
- Some good parts of Jira:
  - Multiple assignees
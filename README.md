# Alfred-workflow-open-macos-settings-panes
Open macOS Settings Panes from list

# Important note

I am not further maintaining this workflow under macOS 26 and later as Alfred 5.7 natively supports:

- searching macOS System Settings (Alfred Preferences → Default Results then add `System Settings` under `Essentials`); *and*
- localisation of the Settings for the purposes of the search.
---

# Note 

This workflow has been tested on macOS 15.0. If you are still using macOS 14 please use [version 2.7](https://github.com/Stephen-Lon/Alfred-workflow-open-macos-settings-panes/releases/tag/v2.7) of this workflow.

With effect from version 3.3 there is a workflow configuration option to use English or German.

# Usage

This workflow lists, in response to the user configurable `syset` keyword, various macOS System Preference panes (which are still called `Preference panes` even under macOS 14) to which there is programable access. When you select the relevant pane from the searchable list simply press <kbd>⏎</kbd> to display the pane. Note that you can leave a space after the keyword and type the initial letter(s) of the pane you want in order quickly to jump to that pane.

![Screenshot](https://github.com/Stephen-Lon/Alfred-workflow-open-macos-settings-panes/assets/111967061/c618beee-b620-4a0f-8b43-59583dd43bfa)


Alfred learns from used items to bring them to the top of the list.

# Note

The `Mouse`, `Game Controller` and `VPN` panes will not appear unless and until you have connected to one of those relevant devices.

# Acknowledgment

I am indebted to comments on [this Github post](https://gist.github.com/rmcdongit/f66ff91e0dad78d4d6346a75ded4b751?permalink_comment_id=4258811) for enabling me to find identifiers for various Preference panes.

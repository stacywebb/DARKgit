# DARKGit

DARKGit is a native desktop Git app with JIRA, AppVeyor and other tools integrated into one UI.

![alt text](https://github.com/stacywebb/DARKGit/raw/master/misc/darkgit.gif "Preview")

## Features

 - Subway map style git visualization with commit details
 - Minimal repo operations (pull, push, commit, stash, pop, create branch)
 - JIRA integration with native UI
 - Map integrated AppVeyor build status with periodic update and on-demand log download
 - Credential caching with Windows Credential Manager
 - Repository specific settings


## Getting Started

### Downlading and Installation

#### Github Releases

To start using this app, go to Releases, download and run the latest setup.exe or dmg and off you go.

#### Building

Uses: NodeJS 8.10

To build global dependencies `electron-builder` and `@angular/cli` are needed. 

  - Install global dependencies via `npm install -g electron-builder @angular/cli`

Next:
 
  1. `git clone https://github.com/stacywebb/DARKgit.git`
  2. `cd DARKgit`
  3. `yarn install`
  4. `cd app/frontend`
  5. `yarn install`
  6. `cd ../..`
  7. `.\build.sh` (macos) or `.\build.ps1` (windows)
  8. Resulting `dmg` or `exe` is located in `dist`
  9. Install as usual.


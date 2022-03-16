### Epic Software Manager - ESM

GUI Desktop app to download, update and manage Epic-Cash related software in one place.
(This is idea for now, no code written yet)
##

### Motivation

Epic-Cash is still young and developing project, there are often changes and new ideas created around and that may lead to troubles with navigating. The goal of this app is to have single point that will keep control over core software versions and make it easy to update or install additional software like TOR or Keybase to enhance user experience and project usability.
##

### How is it working

- Download file/script and run 
- App will connect to epic-radar.com database to fetch official links, versions etc

- If already using epic software before:
    - Provide paths to epic node and wallet config files
    - App will check your version against most up-to-date 
    - Recommended action will be suggested as well as additional software

- If using for the first time:
    - Ask for path (default values provided)
    - Connect to official servers and download recent versions of:
       - epic software
       - TOR library
       - Keybase CLI
       - It will be adjustable what to download 
    - Help with initial configuration:
       - setup node and ask for downloading a chain snapshot
       - init epic-wallet and help with setting up
       - configure TOR to make transactions via TOR possible
       - install and configure Keybase protocol for Keybase transactions
  
Application will have newbie-friendly user interface and will provide feedback to help with the process.

##

https://blacktyg3r.com @ 2022

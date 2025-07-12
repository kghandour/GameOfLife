# Game Of Life 
An open source project created using Electron.js. Gain stats as you achieve your real life goals. 

## Roadmap
### Phase 1
- [ ] Initial setup and repo creation
- [ ] Application should be able to read files in a directory
- [ ] Design an acceptable format on how the file will look like
- [ ] Application should be able to parse those files
- [ ] Which frontend framework/library will we use? 
    - Possible contenders: Pure JS/Typescript, Angular, React
- [ ] Application should be able to index the files (Need further research)
    - [ ] SQLite per device -> Add a hash/ID to avoid conflicts
    - [ ] Store a copy of our state
    - [ ] Allow us to fix the concurrency problem

### Phase 2
- [ ] Support mobile devices


## How does it work
The idea is that you have a directory, you will store all your achievements in that directory as a clearly human-readable file. We want our application to be able to index these files, detect changes, and parse them - to make them actually look cool. 

It's a document based, privacy focused application. The data is entirely yours. Nothing gets sent to the developers.

## Why ElectronJS? 
Electron allows the application to be cross-platform. Even though it is not the most "efficient" or performant, it's a hobby project, and I want to learn it. 

## What's the vision?
- Make the application publicly available on all the major operating systems
    - Windows
    - Linux
    - MacOS
- Make it available on mobile devices -> Come later
    - iOS
    - Android
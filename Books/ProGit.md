# Pro Git
## Getting Started
Figure 1-6 helped me understand the local operation flow. Previously I did not have a clearing picture about the status where the file stands everytime I ran git add and git commit, or I modified the file.

    * all files are in working directory
    * the files which are added by git add command are in stage area and ready for commit
    * the files will be in git directory once git commit command is ran
## Git Basis
### Commit
Use moji to improve commit message

    * :art: :art: when improving the format/structure of the code
    * :racehorse: :racehorse: when improving performance
    * :non-potable_water: :non-potable_water: when plugging memory leaks
    * :memo: :memo: when writing docs
    * :penguin: :penguin: when fixing something on Linux
    * :apple: :apple: when fixing something on macOS
    * :checkered_flag: :checkered_flag: when fixing something on Windows
    * :bug: :bug: when fixing a bug
    * :fire: :fire: when removing code or files
    * :green_heart: :green_heart: when fixing the CI build
    * :white_check_mark: :white_check_mark: when adding tests
    * :lock: :lock: when dealing with security
    * :arrow_up: :arrow_up: when upgrading dependencies
    *　:arrow_down: :arrow_down: when downgrading dependencies
    *　:shirt: :shirt: when removing linter warnings
    
    * :art: Improving structure / format of the code
    * :zap: Improving performance
    * :fire: Removing code or files
    * :bug: Fixing a bug
    * :ambulance: :ambulance: Critical hotfix
    * :sparkles: Introducing new features
    * :memo: Writing docs
    * :rocket: Deploying stuff
    * :lipstick: Updating the UI and style files
    * :tada: Initial commit
    * :white_check_mark: Adding tests
    * :lock: Fixing security issues
    * :apple: Fixing something on macOS
    * :genguin: Fixing something on Linux
    * :checkered_flag: Fixing something on Windows
    * :robot: Fixing something on Android
    * :green_apple: Fixing something on iOS
    * :bookmark: Releasing/Version tags
    * :rotating_light: Removing linter warnings
    * :construction: Work in progress
    * :green_heart: Fixing CI Build
    * :arrow_down: Downgrading dependencies
    * :arrow_up: Upgrading dependencies
    * :construction_worker: Adding CI building system
    * :chart_with_upwards_trend: Adding analytics or tracking code
    * :hammer: Refactoring code
    * :heavy_minus_sign: Removing a dependency
    * :whale: Work about Docker
    * :heavy_plus_sign: Adding a dependency
    * :wrench: Changing configuration files
    * :globe_with_meridians: Internationalization and localization
    * :pencil2: Fixing typos
    * :hankey: Writing bad code that needs to be improved
    * :rewind: Reverting changes
    * :twisted_rightwards_arrows: Merging branches
    * :package: Updating compiled files or packages
    * :alien: Updating code due to external API changes
    * :truck: Moving or renaming files
    * :page_facing_up: Adding or updating license
    * :boom: Introducing breaking changes
    * :bento: Adding or updating assets
    * :ok_hand: Updating code due to code review changes
    * :wheelchair: Improving accessibility
    * :bulb: Documenting source code
    * :beers: Writing code drunkenly
    * :speech_balloon: Updating text and literals
    * :card_file_box: Performing database related changes
    * :loud_sound: Adding logs
    * :mute: Removing logs
    * :busts_in_silhouette: Add contributors
    * :child_crossing: Improving user experience / usability
  
## Reference
* GitHub flow
http://scottchacon.com/2011/08/31/github-flow.html

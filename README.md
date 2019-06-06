Butt Launcher
===================

## What is The Butt Launcher?
The Butt Launcher is a Minecraft launcher designed to install and manage modpacks from the [Butt Platform][Homepage].
Features automatic updating, custom platform pack installation, and easy simple UI design.
The launcher in its current form is maintained by [CanVox](https://github.com/CannibalVox)

[![Butt][Logo]][Homepage]  
[Homepage] | [Forums] | [Twitter] | [Facebook] | [Steam]

## The License
The Butt Launcher is licensed under the [GNU General Public License Version 3][License]. Please see the `LICENSE.txt` file for details.

Copyright (c) 2013 Syndicate, LLC <<http://www.Buttpack.net/>>

## Getting the Source
The latest and greatest source can be found here on [GitHub][Source].  
Download the latest builds from our [build server][Builds]. [![Build Status](http://build.Buttpack.net/job/ButtLauncher/badge/icon)](http://build.Buttpack.net/job/ButtLauncher/)

## Compiling the Source
Butt Launcher uses Maven to handle its dependencies.

* Install [Maven 3](http://maven.apache.org/download.html)
* Checkout this repo and run: `mvn clean package`
* To compile an `exe` on a non-Windows platform, add: `-P package-win` to the previous goals.

## Contributing to the Project
Track and submit issues and bugs on our [GitHub issues page][Issues].  

## Code and Pull Request Formatting
* Generally follow the Oracle coding standards.
* No spaces, only tabs for indentation.
* No trailing whitespaces on new lines.
* 200 column limit for readability.
* Pull requests must compile, work, and be formatted properly.
* Sign-off on ALL your commits - this indicates you agree to the terms of our license.
* No merges should be included in pull requests unless the pull request's purpose is a merge.
* Number of commits in a pull request should be kept to *one commit* and all additional commits must be *squashed*.
* You may have more than one commit in a pull request if the commits are separate changes, otherwise squash them.
* For clarification, follow the Spout pull request guidelines [here](http://spout.in/prguide).

**Please follow the above conventions if you want your pull request(s) accepted.**

[Logo]: http://i.imgur.com/PCI0pIo.png
[Homepage]: http://www.Buttpack.net
[Forums]: http://forums.Buttpack.net
[License]: http://www.gnu.org/licenses/gpl-3.0.txt
[Source]: https://github.com/ButtPack/ButtLauncher
[Builds]: http://build.Buttpack.net/job/ButtLauncher/
[Issues]: https://github.com/ButtPack/ButtLauncher/issues
[Twitter]: https://twitter.com/ButtPack
[Facebook]: https://www.facebook.com/ButtPack
[Steam]: http://steamcommunity.com/groups/Butt-pack

# AdvancedFox

![Icon](images/Icon.png){width=128 height=128}

## Overview
**AdvancedFox** is a project that provides some policies.json and user.js files that you can add it to Firefox.

## ⚔️ All policies and user.js types
Files/Levels | 📄 policies (Privacy & Security) | 📜 user.js (Privacy & Security)
-|-|-
**💪🏻 Strong** | ✅ _Sets SearXNG as the default search engine, and installs uBlock Origin and NoScript by default._ | ✅ _Blocks ads and trackers and fingerprinting by default._
**🛡️ Medium** | ✅ _Sets SearXNG as the default search engine, and installs uBlock Origin by default._ | ✅ _Blocks ads and trackers and fingerprinting by default._
**🗡️ Weak** | ✅ _Sets SearXNG as the default search engine by default._ | ✅ _Blocks ads and trackers by default._

### ⚙️ Other policies and user.js types
1. **Disable AI Features.**
2. **DMT.**
3. **Performance.**

## ✨ Features
- [x] **Blocking ads by default.**
- [x] **Blocking trackers by default.**
- [x] **Resisting fingerprinting.**
- [x] **Linux and Windows support.**
- [x] **Free and open source project.**
- [x] **Able to choose how much privacy protection you want.**
- [x] **Better performance.**
- [ ] Able to choose how much performance level you want.
- [x] **Setting SearXNG as the default search engine.**
- [x] **Installing uBlock Origin by default.**
- [x] **Disabling Mozilla telemetry.**
- [x] **Disabling AI Features.**

**After installing the policies.json (Privacy & Security) and user.js (Privacy & Security) files with strong level, this is the result in one of the best websites for testing web tracking:**

![EFF-Cover your tracks](images/EFF-CYT.png){width=988 height=745}

Note: You may not get this result, it's different between each device.

## 🚫 Fingerprinting Problems in Firefox

**There are 3 things that prevent your browser fingerprint from being non-unique**:

Objects | Reasons
-|-
**Fonts** (Linux only) | _A structural restriction in Linux support for_ `font-visibility`_._
**Cores** | _RFP sets cores count to 2 (when enabled) according to a statistic in 2017 by Mozila, but this statistic is old, and this value is nearly-unique now, the value should be 4._
**DNT** | _Enhanced Tracking Protection enables Do Not Track automaticlly and can't be disabled with keeping ETP enabled, and the problem with DNT is making the browser more uniquer._

**These things can't be resolved by a policies.json or user.js files, the resolve key is in Mozilla's hand.**

If these issues resolved, Firefox with this user.js will show you "**Your browser has a non-unique fingerprinting.**" in Cover Your Tracks test.

## 📥 Installation

#### 📄 policies.json
1. Go to "[AFDC](https://gitlab.com/iahmed_7024-group/advancedfox/-/wikis/AFDC)".
2. In "Privacy & Security" section, choose the privacy level that you want to use.
3. Click on "policies.json" with the level that you chose.
4. After downloading, copy the file.
5. Putting the file in the right position:

###### Linux:
**Official Build**: Go to the installation directory (it may be in /opt/firefox/), then go to "distribution" folder (create it if not available) and paste the file there.

**Package Manager**: Go to "/usr/lib/firefox/", then go to "distribution" folder (create it if not available) and paste the file there.

**Commands** (you have to run it with privilege permissions):
1. `mkdir /opt/firefox-esr/distribution/ && mv <policies.json file location> /opt/firefox-esr/distribution/`.
2. `mkdir /usr/lib/firefox/distribution/ && mv <policies.json file location> /usr/lib/firefox/distribution/`.

###### Windows:
Go to "C:\Program Files\Mozilla Firefox\", then go to "distribution" folder (create it if not available) and paste the file there.

#### 📜 user.js
1. Go to "[AFDC](https://gitlab.com/iahmed_7024-group/advancedfox/-/wikis/AFDC)".
2. In "Privacy & Security" section, choose your operating system.
3. Choose the privacy level that you want to use.
4. Click on the user.js file with the level that you chose.
5. Once it's downloaded, rename it to user.js.
6. Open Firefox.
7. Type in the search bar: about:profiles.
8. Choose the profile that you want to add the user.js into it and then click on Open Directory in Root Directory section.
9. Paste the user.js.
10. Restart Firefox.

## 🛑 Deletion

#### 📄 policies.json
###### Linux:
**Official Build**: Go to the installation directory (it may be in /opt/firefox/), then go to "distribution" folder and then remove the file.

**Package Manager**: Go to "/usr/lib/firefox/", then go to "distribution" folder and then remove the file.

**Commands** (you have to run it with privilege permissions):
1. `rm /opt/firefox-esr/distribution/policies.json `.
2. `rm /usr/lib/firefox/distribution/policies.json `.

###### Windows:
Go to "C:\Program Files\Mozilla Firefox\", then go to "distribution" folder and then remove the file.

#### 📜 user.js
1. Open Firefox.
2. Type in the search bar: about:profiles.
3. Choose the profile that you added the user.js into it and then click on Open Directory in Root Directory section.
4. Remove the user.js.
5. Restart Firefox.

## 🪪 License
This project is licensed under [MIT License](https://mit-license.org/).

## ©️ Credits
- **A7** ([GitLab](https://gitlab.com/iAhmed_7024) - [GitHub](https://github.com/A7md70242602GH))
- **SHIMORA** ([GitLab](https://gitlab.com/SHIMORA_6600X) - [GitHub](https://github.com/SHIMORA-6600X))

## ⛔ Important Note!
This project that's available on [GitHub](https://github.com/A7md70242602GH/AdvancedFox) is for improving the visibility, the main repository for downloading and using the policies.json and user.js files are available on [GitLab](https://gitlab.com/iahmed_7024-group/advancedfox).

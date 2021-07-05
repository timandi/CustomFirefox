# Custom Firefox CSS 

My personal customization of Firefox using userChrome.css and TreeStyleTab extension.

![vertical](https://github.com/timandi/CustomFirefox/blob/main/screenshot.png)

## Setup

### Firefox CSS (Vertical Tabs)

1. Keep things safe and make a new profile in `about:profiles`.
2. Open the new profile, enter `about:config` and search for **`toolkit.legacyUserProfileCustomizations.stylesheets`**. Set it as **True**
3. Go to `about:profiles` and open the root directory for your profile. (/Users/your_username/Library/Application Support/Firefox/Profiles/xxxxxxxxx.your_profile_name)
4. Create a folder and name it **`chrome`** (with lowercase).
5. Paste the `userChrome.css` into the folder.


### Tree Style Tab

1. Install the [Tree Style Tab extension](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/).
2. Go to extension preferences
3. Set `Photon` as theme.
4. Under `Advanced`, paste the `tabStyle.css` as the extra styles.

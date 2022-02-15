# Custom Firefox CSS

My personal customization of Firefox using userChrome.css and TreeStyleTab extension.

![vertical](https://github.com/timandi/CustomFirefox/blob/main/vertical.png)
![horizontal](https://github.com/timandi/CustomFirefox/blob/main/horizontal.png)

## Setup

### Firefox CSS (Vertical Tabs)

1. Keep things safe and make a new profile in `about:profiles`.
2. Open the new profile, enter `about:config` and search for **`toolkit.legacyUserProfileCustomizations.stylesheets`**. Set it as **True**
3. Go to `about:profiles` and open the root directory for your profile. (/Users/your_username/Library/Application Support/Firefox/Profiles/xxxxxxxxx.your_profile_name)
4. Create a folder and name it **`chrome`** (with lowercase).
5. Paste the `userChrome.css` into the folder.

### Sidebery Extension

[Read more](<https://github.com/mbnuqw/sidebery/wiki/Firefox-Styles-Snippets-(via-userChrome.css)>)

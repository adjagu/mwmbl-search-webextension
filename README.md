# MWMBL Search WebExtension
A Firefox webextension that adds the ability to search [MWMBL.org](https://mwmbl.org/) from either the search box or the url bar.

## Installation
The easiest method of installing this webextension is to visit the [MWMBL Search page at addons.mozilla.org](https://addons.mozilla.org/firefox/addon/mwmbl-search/) and then clicking on the "Add to Firefox" button. If you would like to install this webextension a different way please continue reading.

### Temporary Add-On
This webextension can also be temporarily installed in Firefox. A temporary add-on behaves differently than a normal add-on. A temporary add-on only remains installed while Firefox is open and running. Once exited (closed) the temporary add-on is removed from Firefox.

To perform a temporary installation you will need a copy of this repositories source code. Please refer to the information provided below to learn how to accomplish a temporary installation:

- Clone or [download a .zip archive of this repository](https://github.com/AdJaGu/mwmbl-search-webextension/archive/refs/heads/main.zip)
- Open Firefox
  - Type `about:debugging#/runtime/this-firefox` into the url bar and press `ENTER`
    - Click the `Load Temporary Add-on...` button
      - Navigate to either the `manifest-v2` or `manifest-v3` folders
      - Select `manifest.json` and click `Open`

## Usage
After the webextension is installed performing a search of MWMBL works in the following manner:
- From the url bar
  - Type `mwmbl` and then press `TAB` to start searching with MWMBL
- From the search bar
  - If MWMBL is set as your default search provider
    - Type what you want to search and when finished typing press `ENTER` to complete your search
  - If MWMBL is not set as your default search provier
    - Type what you want to search
	- Click search box and underneath where it reads "This time, search with:" select the "MWMBL" icon to complete your search

## License
[GPL-2.0-only](LICENSE.md)

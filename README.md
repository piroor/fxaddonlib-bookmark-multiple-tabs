# Bookmark Multiple Tabs library for Firefox 2 or later

## Usage:

### chrome.manifest

    overlay  chrome://browser/content/browser.xul
             chrome://***/content/bookmarkMultipleTabs.xul
    overlay  chrome://browser/content/places/bookmarkProperties.xul
             chrome://***/content/bookmarkMultipleTabs_bookmarkPropertiesOverlay.xul
    overlay  chrome://browser/content/places/bookmarkProperties2.xul
             chrome://***/content/bookmarkMultipleTabs_bookmarkPropertiesOverlay.xul

### JS files

    window['piro.sakura.ne.jp']
      .bookmarkMultipleTabs
      .addBookmarkFor(tabsArray, folderName);


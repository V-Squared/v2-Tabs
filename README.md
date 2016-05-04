# v2-Tabs
Angular Tabs generated within ng-repeat from JSON that can be selected and scrolled toward with a deep URL using hashtag to address the tab.


# Table of Contents
- [Key Features](#features)
- [v2-Tab Demo](#demo)
- [Distribution of v2-Tab](#disti)
- [How to make it work](#how-to)
- [User Story of v2-Tabs making long content fun](#user-story)
- [Target of Pull Request to UI Bootstrap](#pull-request)
- [Reference](#reference)


# Key Features <a name="features"></a>
## All Features
- **Lightweight:** Only few kB (not minimized) and minimum CPU load
- **Angular Directive:** Reusable and easy to use
- **Angular Tabs:** Same functions as and our code is based on → [UI Bootstrap►Tabs](https://angular-ui.github.io/bootstrap/#/tabs)
- **Added Angular Tabs Features:**
   - **Deep Link:** Each tab with the tab bar has a unique ID which can be used via hashtag in the URL to scroll to tab bar and select that tab
   - **More than one tab bar per page:** Several tab bars can be independantly addressed on the same page
   - **Compatible with ng-repeat:** The tabs are constructed by reading their data from one JSON file via ng-repeat.
- **No AJAX:** This makes navigation between tabs fast
- **Responsive:** All works as expected on any screen size. Supporting all features it was not as easy as it might appear.
- **Touchscreen Support:** All features are tested and do work on touchscreen.
- **Intuitive to use:** All features are intuitively accessible. No explanation / help needed.

## Deep Link
The user can browser to a specific content within a specific tab. He then can share this content easily by its **Deep Link**. Example: http://v-squared.github.io/#/tab2-4 opens the page: v-squared.github.io, then scrolls to the second *tab bar* and finally opens the fourth *tab*. 

## Compatible with ng-repeat
In our second demo we contruct the tab bar and the tab content from data contained in a single JSON file. This approach allows to separate data from code, which makes it easier to maintain the data of the web site.


# v2-Tooltip Demo <a name="demo"></a>
## Simple Demo <a name="simple-demo"></a>
→ ??? link 
### Feature: Deep Link Generation on Tab click
1. click on a tab to select a different tab and reveal its different content
2. the tab ID is updaterd in the URL bar of the browser

### Feature: Scroll and select Tab via deep Link
1. Select a tab of your choosing
2. Copy the URL of the URL field of the browser
3. Open new browser tab, pastr that URL and load the page
4. The page will load, then scroll to that tab bar and select the identical tab

## ng-repeat Demo  <a name="ng-demo"></a>
→ ??? link 

### Feature
It works the same as the [Simple Demo](#simple-demo). The difference is in the source code. The html of this demo page is assembled with ng-repat that reads its data from the JSON file: tabs.json. 




# Target of Pull Request to UI Bootstrap <a name="pull-request"></a>
[UI Bootstrap►tabs](https://angular-ui.github.io/bootstrap/#/tabs) The documentation of tabs of UI Bootstrap. Our v2-Tab code is based on their tab code. Once we made our code work, we will try to make a pull request to UI Bootstrap. 


# Reference <a name="reference"></a>
- [UI Bootstrap](https://angular-ui.github.io/bootstrap/) Angular version of Bootstrap. Our v2-Tab code is based on their tab code. Once we made our code work, we will try to make a pull request to UI Bootstrap. 
- [UI Bootstrap►tabs](https://angular-ui.github.io/bootstrap/#/tabs) The documentation of tabs of UI Bootstrap
- https://angularjs.org/ Home Page of Angular







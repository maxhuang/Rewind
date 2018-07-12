README file for Rewind
==========================

**Contents:**
1. [Introduction](#introduction)
2. [Features](#features)
3. [Screenshots](#screenshots)
4. [Requirements](#requirements)
5. [Setup](#setup)

# Introduction

Rewind is a web app that allows you to search through your Facebook using either a keyword, date based search or a combination of them. This may allow you to identify your Facebook posts which may be of interest to you. 

(In case you are wondering why such a random gimmick was written, the answer is it was an assignment. Since the prototype works and looks nice, I decided to upload it in hopes that someone may find this useful or interesting. PR and other improvements are welcome!)

# Features

- Keyword and/or date based search through your Facebook posts
- Display content, date posted and privacy of matched Facebook posts. You can also open them on Facebook.
- Searching without keywords returns all your Facebook posts (which can be limited using the date based search)

# Screenshots

![Logged in with example search and advanced search collapsed](https://raw.githubusercontent.com/maxhuang/Rewind/master/screenshots/logged-in-1.png)
![Logged in with example search and advanced search expanded](https://raw.githubusercontent.com/maxhuang/Rewind/master/screenshots/logged-in-2.png)
![Not logged in](https://raw.githubusercontent.com/maxhuang/Rewind/master/screenshots/not-logged-in-1.png)

# Requirements

- A reasonably modern web browser. I recommend Firefox.
- A place to host the static web page. You can use Github Pages, Bitbucket Pages, etc.
- A Facebook account.

# Setup

1. Clone the repository. `git clone https://github.com/maxhuang/Rewind.git`
2. Create a new Facebook App at https://developers.facebook.com/
3. Replace `REPLACE_WITH_YOUR_OWN_APP_ID` in `index.html` with the APP ID from the newly created Facebook App
4. Host the `index.html` and `logo.png` somewhere. It must be hosted on https. Facebook will refuse service if the site is not served over https. 
5. Add the domain of where you are hosting the site to the App Domains in your Facebook App. For example, if it is hosted at `https://subdomain.example.io` then you will add that to your App Domains. 
6. You can now use Rewind by visiting the url where you hosted it. If it loads forever, ensure that Facebook isn't being blocked by your adblock or similar software. If you want to allow other people to use your app, either apply to make it public or add them as Test Users.

# Choose Your Adventure

There are two ways to get started.

<table class='equalwidth'>
	<tr>
		<th><h1>{ ˃̵̑ᴥ˂̵̑}<br>jasonette</h1></td>
		<th><h1>{ ·ᴥ·}<br>jason</h1></td>
	</tr>
	<tr>
		<td><h4>What is it?</h4>Make a publishable app.</td>
		<td><h4>What is it?</h4>A standalone Jasonette browser. Try Jasonette without any setup.</td>
	</tr>
	<tr>
		<td>
			<h4>When to use</h4>
			<ul>
				<li>If you want to publish your app right now.</li>
			</ul>
		</td>
		<td>
			<h4>When to use</h4>
			<ul>
				<li>For instant prototyping.</li>
				<li>If you don't need to publish your app to the app store</li>
				<li>Switch between multiple Jasonette apps quickly.</li>
			</ul>
		</td>
	</tr>
	<tr>
		<td>
			<h4>How to use</h4>
			<ol>
				<li>Download Jasonette</li>
				<li>Add your JSON url</li>
				<li>Build it in XCode</li>
			</ol>
			<br>
			<a href='https://github.com/Jasonette/JASONETTE-iOS/archive/master.zip' class='btn'><i class='fa fa-apple'></i> Download Jasonette-iOS</a>
		</td>
		<td>
			<h4>How to use</h4>
			<ol>
				<li>Download Jason from the app store</li>
				<li>Enter your JSON url in the address bar</li>
			</ol>
			<br>
			<a href='https://github.com/Jasonette/JASONETTE-iOS/archive/master.zip'><img src='/images/appstore.png' class='download'></a>
		</td>
	</tr>
</table>

---

# Quick Start
Ready? Let's get your first Jasonette app on your phone, in 20 seconds! [Interested in manual setup?](#manual-setup)

<br>

##Step 1. DOWNLOAD

<div class='well'>
Jasonette itself is a pre-built app.<br>All you need to do is download and build with <a href='https://itunes.apple.com/us/app/xcode/id497799835?mt=12'>XCode</a>.
<br><br>
Go ahead and download Jasonette, and then unzip.
<br><br>
<a href='https://github.com/Jasonette/JASONETTE-iOS/archive/master.zip' class='btn'><i class='fa fa-apple'></i> Download Jasonette-iOS</a>
</div>

![download jasonette](images/download.png)

<br>

##Step 2. SETUP
Initialize by running the `Setup` command.
![init](images/setup.png)

This command automatically generates icons and sets the title and the url. 
<br>
<br>

##Step 3. PLAY
Connect your phone and click play on XCode. Done!

![play](http://i.giphy.com/l3vRnkTqLc0Tr1esU.gif)

---

## ★ Did it work?

<br>

  - ###YES?
    - Congratulations! You're ready to transform this into your OWN app! Go on to the next section.

<br>

  - ###NO?
    - **[Check troubleshoot section](#troubleshoot)**


---

# Tutorial Screencast

Watch the 2 videos below and you'll have learned everything you need to know to get started.

<b>The videos were shot using an iPhone, but it works exactly the same for Android.</b>

<br>

### A. Do you know JSON?


Before we dive in, do you know JSON? If not, just check out [this tutorial](http://www.w3schools.com/js/js_json_syntax.asp), takes 2 minutes.

<br><br>

### B. Learn the basics
This video walks you through the basics of Jasonette, such as how it works, how to get started, etc.
<br><br>
<div class='video-container'>
<iframe width="640" height="360" src="https://www.youtube.com/embed/hfevBAAfCMQ?rel=0" frameborder="0" allowfullscreen></iframe>
</div>

<br><br>

### C. Learn JASON syntax
This video teaches you how to actually write a JSON markup to build sophisticated interactive layouts.
<br><br>
<div class='video-container'>
<iframe width="640" height="360" src="https://www.youtube.com/embed/S7yGejKIH6Q?rel=0" frameborder="0" allowfullscreen></iframe>
</div>


---


# Documentation

###Anatomy of a Jason view
**[Learn the basic structure of a JASON view](document.md)**<br>
Just like HTML has basic tags such as body, div, span, li, etc, Jasonette has JSON based tags to describe the structure of a view.
---
###Components
**[Learn component syntax](components.md)**<br>
Components are the most basic units of user interface, such as image, label, textarea, button, slider, etc. 
---
###Layout
**[Learn layouts](layout.md)**<br>
In many cases we combine multiple components to construct a unit. We use layouts to do this.
---
###Link multiple views
**[Learn linking](href.md)**<br>
Above three sections are all you need to know to display content in a view. But what if we want multiple views? We can link them using `href`.
---
###Actions
**[Learn actions](actions.md)**<br>
Actions define a task or a sequence of tasks you wish to run, such as network request, audio play, camera access, geolocation, displaying banners, etc.
---
###Templates
**[Learn templates](templates.md)**<br>
You can use templates to dynamically render data, such as remote network content, local data, and user input.
---
# Examples
Actual JSON examples you can try out with Jasonette:

**[Try examples here](examples.md)**


---
# Manual setup

It is recommended that you use [the Setup command](#step-2-setup) since it takes care of most of tedious details, but you can also do this manually.

###Step 1. Download

[Download Jasonette](https://github.com/Jasonette/JASONETTE-iOS/archive/master.zip) and unzip.
![download jasonette](images/download.png)

###Step 2. Open in XCode
Go into the `app` folder and open `Jasonette.xcworkspace` file. **(warning: Make sure to open the `xcworkspace` file, NOT the `xcodeproj` file!)**

![init](images/workspace.png)

###Step 3. Update config attributes and generate icons manually

![init](images/config.png)

- **Set App Name:** Under the `Config` group, open the `Info.plist` file and change the `CFBundleName` attribute.
- **Set Root URL:** Under the `Config` group, open the `settings.plist` file and change the `url` attribute.
- **Generate Icon:** You can try generating app icons using online services like [makeappicon.com](https://makeappicon.com/), and [add them manually to the project](https://makeappicon.com/import-icons-into-xcode).

###Step 4. Play
Connect your phone and click play on XCode. Done!

![play](http://i.giphy.com/l3vRnkTqLc0Tr1esU.gif)

---

# Submitting to the app store

There are a couple of things to keep in mind when submitting to the app store.

##1. Sign up as Apple Developer
You can test as much as you want without signing up as a developer, you can even put apps on your phone. However when it comes to actually submitting apps, you need to register as a developer. Google "apple developer" to learn how to do this.

##2. Archive and Upload
Assuming you're all ready, you just need to "archive" the app first, and then press "upload to app store".

![no bitcode](images/archive_app.png)

##3. Uncheck "Include bitcode"

When you press "upload to app store", it will show up a confirmation dialog. Uncheck "Include bitcode" option here. We do not need Bitcode because Jasonette is already small due to its modularity, and it actually may become larger. In fact including bitcode doesn't work well with Jasonette, so make sure you uncheck this.

![no bitcode](images/appstore_submit.png)

---

# Troubleshoot

## ■ "Unknown property attribute 'class'"

<br>

![unknown property attribute class](images/build_error.png)

<br>

###This is known to happen in old versions of XCode. Please upgrade your XCode to the [latest version](https://itunes.apple.com/us/app/xcode/id497799835?mt=12)

---


## ■ "No provisioning..." error

<br>

![No provisioning error](images/no_provisioning_profiles.png)

<br>

###Just press "Fix Issue" and sign in with your Apple account

**[If that doesn't work, read this post](http://apple.stackexchange.com/a/206130)**


---

## ■ "Signing for "Jasonette" requires a development team. Select a development team in the project editor."
<br>

![Requires development team](images/requires_development_team.png)

<br>

1. Select the project from XCode.
2. Go to "General" section.
3. Click "Team" under Signing section. Switch it from "None" to your existing team. If you don't have one, select "Add an account" to add your own Apple account.

<br>

![add team](images/add_team.png)

---

## ■ "Code signing is required for product type 'Application' in SDK"
<br>

![Requires development team](images/requires_development_team.png)

<br>

1. Select the project from XCode.
2. Go to "General" section.
3. Click "Team" under Signing section. Switch it from "None" to your existing team. If you don't have one, select "Add an account" to add your own Apple account.

<br>

![add team](images/add_team.png)

---

## ■ "Untrusted Enterprise Developer"
Keep getting "Untrusted Enterprise Developer" alert when you try to open the installed app?

<br>

<div class='video-container'>
<iframe width="640" height="360" src="https://www.youtube.com/embed/EG9spHluLKg?rel=0" frameborder="0" allowfullscreen></iframe>
</div>

<br>

Or read the Apple Guideline below:

**[Guidelines for installing custom enterprise apps on iOS](https://support.apple.com/en-us/HT204460)**


---

## ■ "Can't be opened because it is from an unidentified developer."

Do you get the following error when you try to execute the `Setup` command?

<br>

![unidentified developer](images/unidentified_developer.png)

<br>

**[This article will help you](http://www.iclarified.com/28180/how-to-open-applications-from-unidentified-developers-in-mac-os-x-mountain-lion)**

---

## ■ "... is busy: Processing symbol files"

Do you get this alert when you press the `play` button?

<br>

![processing symbol files](images/processing_symbol.png)

<br>

**Just wait for a bit until the progress bar gets to the end, and then retry.**

---

## ■ "Offline mode"

In the current implementation of Jasonette, this meesage means either:

1. There's a problem with your network.
2. There's something wrong with your JSON markup and Jasonette is not able to interpret it correctly.

Please first check the network to see other apps are working fine. After that, check your JSON, keep simplifying it down until you find the problematic markup.


---

## Need more help?

  - **Slack - **  Come ask quick questions and share tips with other Jasonette users. [Join here](https://jasonette.herokuapp.com)

	<script async defer src="https://jasonette.herokuapp.com/slackin.js?large"></script>

  - **Forum - **  Chat messages on Slack tend to flow away, so you may want to ask questions on the forum. Also it's good for future users who may have the same problem. All messages on the forum will be read. Visit here: [https://forum.jasonette.com](https://forum.jasonette.com)

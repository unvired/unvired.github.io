---
layout: post
title: Getting Started
category: iOS Development
---

Try out the Unvired Hello World Project from GitHub. This project can also be used as a template for building Unvired Applications. This project depends on Unvired SDK. We use CocoaPods as the dependency manager for installing UnviredSDK.

Using CocoaPods takes care of all the required frameworks and third party dependencies.

Install CocoaPods (if not already installed)
-------

Install CocoaPods by executing the following command in the Terminal.

<div class="message">
	$ sudo gem install cocoapods
</div>

Checkout <a href="http://guides.cocoapods.org/using/getting-started.html#toc_3">CocoaPods Installation Guide </a> for more information.

Clone Unvired Hello World Project
-------

Clone <a href="https://github.com/unvired/hello-world-ios">Unvired Hello World Project</a> hosted in GitHub by executing the following command in the Terminal.

<div class="message">
	$ git clone https://github.com/unvired/hello-world-ios.git
</div>


Add CocoaPods
-------

In the Termnial app, do a <code>cd</code> into the cloned project and execute the following command.

<div class="message">
	$ pod init
</div>

This will create a Podfile inside your project directory.

Checkout <a href="http://guides.cocoapods.org/using/getting-started.html#toc_3">CocoaPods Usage Guide </a> for more information on using CocoaPods.


Install Unvired SDK (via CocoaPods)
-------
In your Podfile add Unvired SDK as a dependency

<div class="message">
	pod 'UnviredSDK'
</div>

Save the podfile and run <code>$ pod install</code> inside your project directory.

This will set up Unvired Hello World Project with all the required dependencies. 
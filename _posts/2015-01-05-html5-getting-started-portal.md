---
layout: post
title: Getting Started
category: HTML5 Hybrid Development
---
<p>
	Try  the Unvired Hello World Project from GitHub. This Application showcases how to use Unvired Mobile Platform SDK's for building a HTML5 Hybrid mobile application. This project can also be used as a template to create new applications. Install Unvired Unvired HTML5 Framework into your project through NPM CLI.
</p>

<p>
	<h3>Dependencies</h3>
	<ul>
		<li> <a href="https://www.npmjs.com/package/unvired">Unvired NPM CLI</a> </li>
		<li>Cordova for <a href="http://cordova.apache.org/docs/en/3.3.0/guide_platforms_android_index.md.html#Android%20Platform%20Guide">Android</a> and <a href="http://cordova.apache.org/docs/en/3.3.0/guide_platforms_ios_index.md.html#iOS%20Platform%20Guide">iOS</a></li>
	</ul>
</p>

<p>
Unvired provides <a href="https://www.npmjs.com/package/unvired">NPM CLI</a> for creating new Cordova template application and also adding Unvired Hybrid SDK support to an existing Cordova project.

First, install <a href="http://nodejs.org/">Node.js</a>. Then, install the latest Cordova and <a href="https://www.npmjs.com/package/unvired">Unvired NPM CLI</a>. 
Follow the <a href="http://cordova.apache.org/docs/en/3.3.0/guide_platforms_android_index.md.html#Android%20Platform%20Guide">Android</a> and <a href="http://cordova.apache.org/docs/en/3.3.0/guide_platforms_ios_index.md.html#iOS%20Platform%20Guide">iOS</a> platform guides to install required platform dependencies for cordova. 
</p>

<h4><code> > npm install -g unvired</h4></code><br>

<img class="centered" src="{{ site.baseurl }}public/npmUnvired.png" alt="Unvired NPM CLI"><br>


<h3>Start A Project</h3>

Create an Unvired template project using Unvired NPM CLI.

<h4><code> > unvired start ApplicationPath Platform</h4></code> 

Let's create an  HelloWorld application in in andorid.

<h4><code> > unvired start HelloWorld android</h4></code><br>

<img class="centered" src="{{ site.baseurl }}public/npmCreate.png" alt="Unvired Start"><br>

Template project includes basic html with unvired javascript and hybrid library integrated.
For UI you can use any UI frameworks like Sencha Touch, JQuery, Ionic, SAP UI5 etc.

<h3>Build and Run</h3>

Once project created with Unvired SDK, open in you favorite IDE( eclipse or xcode).
Not you can build and run this project.


<h3>Add Unvired SDK To An Cordova Project</h3>

You can also add Unvired SDK to an existing Cordova project using Unvired NPM CLI.
To add Unvired SDK to an existing project navigate to your project root directory and then run add platform command.

<h4><code> > unvired add android</h4></code><br>
<img class="centered" src="{{ site.baseurl }}public/npmAdd.png" alt="Unvired NPM add"><br>








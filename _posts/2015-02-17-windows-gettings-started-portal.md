---
layout: post
title: Getting Started
category: Windows 8.1 Development
---

Try out the Unvired Hello World Project from GitHub. This Application showcases how to use Unvired Mobile Platform SDK's for building a Windows 8 mobile application. This project can also be used as a template to create new applications. Install Unvired Windows Framework into your project through Nuget Package Manager.

<p>
<h3>Dependencies</h3>
<ul>
<li> <a href="https://www.nuget.org/profiles/unvired">Unvired Windows Framework</a></li>
<li><a hrfe="http://sqlite.org/2015/sqlite-winrt81-3080801.vsix">SQLite </a> or <a href="https://www.zetetic.net/sqlcipher/">SQLCipher</a> for Windows Runtime</li>
</ul>
</p>

<div class="message">
Unvired SDK supports data persistence via the free SQLite or the commerical SQLCipher.  If you want to use encrypted database please purchase a license for SQLCipher and install it. You can then set the encrypted property in the LoginParameters class to enable encryption.
</div>

<p>
<h3>Clone Unvired Hello World Project</h3>

Clone <a href="https://github.com/unvired/hello-world-windows8">hello-world-windows8</a> hosted in GitHub by executing the following command in the Console.
<div class="message">
	$ git clone https://github.com/unvired/hello-world-windows8.git <br/>
	or use <a href="https://windows.github.com/">GitHub for Windows</a>
</div>
</p>


<p>
<h3>Install Unvired SDK (via Nuget)</h3>

To install Unvired Mobile Platform (x64/x86) Framework for Windows Tablets, run the following command in the Package Manager Console.<br/>

<div class="message">
PM> Install-Package UnviredFramework.x64 <br>
or <br>
PM> Install-Package UnviredFramework.x86
</div>

You can also install from Visual Studio. Right click on project, select Manage Nuget Project. Then search for Unvired. Install <a href="https://www.nuget.org/packages/UnviredFramework.x64/">UnviredFramework.x64</a> or <a href="https://www.nuget.org/packages/UnviredFramework.x86/">UnviredFramework.x86</a> as per your project configuration.

<br><br>
<img class="centered" src="{{ site.baseurl }}public/UnviredSDK.png" alt="Unvired Windows SDK">
</p>

<p>
<h3>Install SQLite or SQLCipher</h3>

Unvired Framework depends on SQLIite or SQLCipher for persistent layer.Unvired supports both. Install <a hrfe="http://sqlite.org/2015/sqlite-winrt81-3080801.vsix">SQLite </a> for Windows Runtime and add reference to project.
<br><br>
<img class="centered" src="{{ site.baseurl }}public/SqliteReference.png" alt="SQLite for Windows Runtime">
</p>

<br><h4>Now you can build and run this project.</h4><br><br>
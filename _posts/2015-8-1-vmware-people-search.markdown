---
title: "VMware People Search"
category: project
technologies: [Titanium Appcelerator, Javascript, Node.js, LDAP]
---

During my summer internship at VMware, I built an internal tool to search and find employee information. It's basically an address book hooked up to an LDAP server with thousands of people records. The frontend for the iOS client was built with Titanium Appcelerator. The second part of my project was to create an http-ldap connector. The app makes HTTP AJAX requests which don't interface with the LDAP protcol, so I wrote a Node.js server that served as a REST client for the app, but actually made LDAP requests to Microsoft Active Directory in the background.
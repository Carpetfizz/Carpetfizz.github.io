---
title: "VMware People Search"
category: project
technologies: [Titanium Appcelerator, Javascript, Node.js, LDAP]
---

During my summer internship at VMware, I built an internal tool to search and find employee information. It's basically an address book hooked up to an LDAP server with thousands of people records. The frontend for the iOS client was built with Titanium Appcelerator. The second part of my project was to create an http-ldap connector. The purpose of the connector is for clients to access database records in a RESTful manner. Clients make AJAX requests with JSON payloads and receive JSON data back. This is made possible by a Node.js server which is making the LDAP requests to Microsoft Active Directory.
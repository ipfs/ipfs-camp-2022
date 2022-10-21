
# IPFS 201: Design Patterns and Development
Workshops, demos, and an expert panel covering IPFS app architectures, developer tools, design patterns and everything you need to know to build and deploy robust production-grade apps using IPFS.




## Track Schedule
Schedule
TIME	SPEAKER	INFO
10:00	Daniel Norman	Track introduction
Dapps are all the rave, but there's no consensus about how they should be built.

There's a cambrian explosion of developer tools and many emerging design patterns using IPFS. This introduction will set the stage for some of the fantastic speakers we have during the day who'll be sharing the state of the art in app design patterns and developer tools.


10:10	Boris Mann	Fission & The WebNative SDK

10:35	Carson Farmer	Introducing Tableland: The read, write, and own database
Tableland is a decentralized network for relational, composable data — powered by smart contracts + SQL. Mutable data with immutable rules, on EVM chains like Ethereum, supported by tools and protocols like IPFS, Filecoin, and more


11:00	Alex Potsides	Debugging js-ipfs and js-libp2p Like a Pro
The lead maintainer of js-ipfs and js-libp2p will share tips and tricks for debugging js-ipfs


11:35		☕️ Break

12:45	Brendan O'Brien (b5), Brooklyn Zelenka, Carson Farmer, Sara Feenan	Panel: State of the IPFS DevTools ecosystem

12:25	Mauve Signweaver	What is IPLD Anyway?
This talk will go over what IPLD is, how lenses like Schemas and Advanced Data Layouts work, and why they could be useful for your application.


12:40	Jay Graber	Bluesky and IPLD
Bluesky, a decentralized social networking protocol, spun out of Twitter earlier this year. Come learn what we're up to and how we're using IPLD.


13:00		Lunch 🍱🍔

14:00	Lidel	Using the DAG API to efficiently fetch geoip data with IPFS
An overview of how the ipfs-geoip library works and the recent refactor to use the DAG API.


14:15	Horacio Herrera, Alexander Burdiyan	Local-First, Multi-Device Applications With IPFS
In this talk, we'd like to share the ideas and technical approaches we came up with while building Mintter on top of IPFS for the past 2.5 years. Some of the challenges we faced didn’t have easy, or plug-and-play solutions at the time, such as multi-device, decentralized identity, version control, etc. Mintter is a hypertext system for knowledge management in open discussion groups. While working on the product, we were greatly inspired by the work of the founding fathers of hypertext: Doug Engelbart, Ted Nelson and others.


14:40	Chris Anderson, Alan Shaw	UCAN Build Apps with IPFS
Learn how content addressed user-centric protocols like IPFS, DID, and UCAN will change the web, and how to build Node.js applications using them.

The web3.storage team will share the latest APIs and walk you through building your own application data model. Start with DID-based self-sovereign auth, a great opportunity to learn about the next wave of digital identity, and write code to upload files as well as JSON objects. They'll discuss IPFS data structures like IPLD trees and graphs, and how they can be used in applications.


15:30		☕️ Break

15:45	Hector Sanjuan	State without consensus: introduction to Merkle-CRDTs on IPFS
Merkle-DAGs are fun, but even more when they can be used to compute an ever-evolving state (i.e. a database) collaboratively maintained by a set of peers that may come and go as they please. Join us to learn about Merkle-CRDTs, what use-cases they fit and how they power things like IPFS Cluster pinset distribution.


16:15	Gorka Ludlow	How to build a copy of Vine using IPFS and CRDTs
This talk will describe the journey followed from research to implementation of a distributed clone of Vine—the GIF sharing app. It will touch on the p2p aspects of the app, the nature of distributed apps, and how a blockchain layer is optional when building distributed apps. Then it will continue explaining the high-level plan for the app and the goals that were set.

Finally, it will touch on the implementation details, the dragons, the groundwork, the how-tos and gotchas of using a shared data structure (CRTD) between peers, and a demo of the gif-sharing app.


16:35	Manfred Touron	What's next for the Berty Protocol
Most people aware of Berty won't know that we've made an underlying protocol that could power many other projects. We want to change that and help more builders to create powerful dApps. Let's look at what problems we're addressing and how.


16:50	Rüdiger Klaehn	Banyan trees - an indexed log data structure on IPFS
Banyan is a tree data structure that provides an indexed, compressed and encrypted append only log.

It is used in a distributed event sourcing system at https://www.actyx.com/ , but can also be used in other situations where an efficient append only log or rolling log is needed.

I will explain the tree data structure of banyan, how to adapt it to your own needs, and discuss lessons learned when implementing a relatively complex data structure on top of IPFS and IPLD.

Repo link: https://github.com/actyx/banyan

Banyan is currently implemented in rust, with Apache and MIT license.
## Content:

## Recording:

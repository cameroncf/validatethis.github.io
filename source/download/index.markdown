---
layout: page
title: "Download ValidateThis"
date: 2015-07-20 15:11
comments: false
sharing: false
footer: true
---
FW/1 was created in July 2009 as a reaction against complexity and bloat in other frameworks in the CFML community. FW/1 itself is a single file, and provides a simple, convention-based approach to MVC (Model-View-Controller) applications. Whilst it has become more sophisticated over time, it has remained a single file, focused on getting out of your way and providing the intuitive plumbing you need. For historical background, you can read the [introductory blog post](http://framework-one.github.io/blog/2009/07/19/introducing-framework-one/) from July 2009.

As of release 3.1, FW/1 also includes DI/1 - a simple, convention-based Dependency Injection framework - and AOP/1 - a simple, convention-based Aspect-Oriented Programming framework. If those phrases don't mean anything to you, don't worry, you won't need to know anything about them to get started.

Requirements & Supported Platforms
---
FW/1 3.1 supports Adobe ColdFusion 9.0.2 or later (not 9.0.0 or 9.0.1), Lucee 4.5.0 or later, and Railo 4.1 or later. I recommend using [Lucee 4.5.0](http://lucee.org/downloads.html) or later since it's free, open source, and fast, with a small footprint. If you're using Adobe ColdFusion, I recommend upgrading to the latest version (ColdFusion 11 as of August 2014) to take advantage of the huge improvements in the core language since ColdFusion 9.0.2 (closures, member functions, full cfscript support, etc) -- although there are quite a few bugs in several areas of ColdFusion 11 (even as of June 2015).

If you're on ColdFusion 9.0.1, FW/1 3.1 should work but there may be some edge cases in `Application.cfc` lifecycle behavior that may trip you up.

If you're on ColdFusion 9.0.0 or earlier, or still using Open BlueDragon, you'll need to stick with FW/1 1.3. Sorry, but supporting those versions is just too painful!

Your First FW/1 Application
---
more information here nore less


	<cfoutput>
		<p>Test Something</p>
	</cfoutput>

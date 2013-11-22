---
layout: post
title: "yet another post to setup github blog"
date: 2013-11-21 02:12:59 -0800
comments: true
categories: 
---

##abcd title
-------------

Pages don't build: "Unable to run Jekyll"
Sometimes pages fail to build after a push and return the error "page build failed". There are a number of causes for this error.

Unverified email address

The Pages build process will not be triggered by a push if the user who pushed the commit doesn't have a verified email address.

Once you verify an email address, you'll need to make another push to trigger the Pages build process. You can also contact us so that we can manually run a build.

Unsafe plugins

The Pages server will not build with plugins that are not marked as safe. Note that this includes all plugins in the _plugins folder.
There are two possible solutions to this problem:

Remove the unsafe plugins or
Build the pages locally and push the result files instead of the source files
The second option is the strategy used by Octopress.

Syntax errors

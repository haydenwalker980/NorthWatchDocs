---
layout: default
title: NorthWatch Custom Pages Extension
nav_order: 6
---
# NorthWatch Custon Pages Extension
The NorthWatch Custom Pages Extension allows you to set the current page you are visiting to NorthWatch by clicking a button.

# How to Install
Simply [click here](https://chrome.google.com/webstore/detail/northwatch-custom-domains/onhieidabjneklojafnkfgplmjendjbe) on the Chrome browser, and click the blue "Add to Chrome" button.  The extension will install and the NorthWatch logo will appear in the top right-hand corner of your browser.

# How to Use
To use the extension, simply go to any website and click on the NorthWatch extension icon.  It won't work on pages that begin with `chrome://`, only regular `http://` and `https://` pages due to limitations with the Chrome Extension Framework.

# Common Problems/Bugs/Issues
Here are some common issues you might run into, and how to fix them!

### CSRF Error When Logging In
This happens because you have a cross-site cookies (also called a Third Party cookies) disabled.  While it is typically a good idea to block these third-party cookies, the NorthWatch Custom Domains extension needs them to function.  Google is a great resource to figure out how to disable these.

### Login Button Does Nothing
For one reason or another, Chrome thinks that embedded NorthWatch is "insecure content", regardless of us using SSL/TLS and HTTPS.  Luckily, the solution is simple.
1. Go to the website you plan to replace with NorthWatch
2. Click on the Padlock/HTTPS icon (or, if the website does not have HTTPS, the "Not Secure" text)
3. Click on "Site Settings"
4. Scroll down and make sure "Insecure Content" is set to "Allow"

# Still Need Help?
You can get in touch with us using the link below, **but PLEASE only get in touch if you have tried the above and truely can't resolve your problem.**  We have VERY limited support staff and may not get back to you in a timely fashion.  The documentation is very detailed, please re-read it and try to solve the problem on your own.

**[I have read the documentation and still can't resolve my issue.](https://docs.northwatchbank.com/docs/getting-help.html)**

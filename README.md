bbb
===

[BigBlueButton](http:///www.bigbluebutton.org/) Appliance - Education focused web conferencing server - To be built with [TKLDev](http://www.turnkeylinux.org/tkldev)

BBB v0.81rc2

Notes:
- This is for TKL v13.x (Debian Wheezy based)
- To be built on [TKL Core](http://www.turnkeylinux.org/core)
- Only installs on 64 bit machine (amd64)
- Requires 2048MB RAM to function properly, it may run on less but not well (and probably won't run at all on 512MB)
- BBB is not a standalone server. It provides an API for use by other apps - such as Moodle. However, for convenience and initial testing it comes with the API examples installed (this provides the ability to create a test meeting).
- Despite the fact that BBB is designed to be integrated into other appliances/applications it is NOT recommended (by the BBB devs) that additional software be installed alongside BBB. 

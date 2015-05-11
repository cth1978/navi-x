**Issue:** Navi-X does not open or gives an error on startup on XBMC.

**Explanation:** If Navi-X will not open in XBMC after installing it from zip file, there are several reasons the script may be failing to launch.

**1.** The version of XBMC you are using may be marked as "unstable" or "nightly build" and MAY be missing critical script or plugin libs from the application build. Many developers compile XBMC without many libs in it to increase the speed of compiling and testing of other various functions they implement into a new build of XBMC. Normally, they forget to re-compile the package with critical libs for scripts and plugins on occasion and they then have to go back later and re-compile the XBMC package with all libs in order to restore functionality to scripts and plugins within their package release. You can either try another XBMC installation package, another "nightly" or "unstable" build to see if this resolves your issue or revert back to XBMC 10.1 "stable" for stability purposes.

**2.** Your firewall or security software may be preventing Navi-X from connecting to the internet. Check the settings on your firewall and router to confirm they are configured properly. Kaspersky Anti-Virus for some reason also likes to block traffic for XBMC and Navi-X sometimes. If you own Kaspersky, try disabling the program first, then open XBMC and Navi-X and try again.

**3.** The copy of Navi-X you downloaded is corrupt or incomplete. You can re-download the latest version from us at www.navi-x.org and try again to install and launch the script. Instructions for how to install Navi-X on XBMC can be found in another topic on this wiki.
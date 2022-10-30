# AddonTemplate
Template for small, simple standalone addons for World of Warcraft.  

To use this as a base for your own addons, use it as a template or use the GitHub import option and choose the intended project name as you import, and then follow the guide below to further tailor it to your own project. Alternatively you can download a zip manually and just start from there.  

Good luck and have fun!  

### **How to prepare the template**
To use this template, you need to rename some files and folders, and do a search and replace within all the files for a few select keywords.
* Rename the folder `AddonTemplate` to your project name, if you haven't already.
* Rename the folder `YOUR_ADDON` to the exact folder name of your addon.
* Rename the file `YOUR_ADDON.toc` so that you get the exact folder name of your addon, with the `.toc` file ending.
* Repeat the previous step for the other `YOUR_ADDON_<xpac>.toc` files, but make to _only_ replace the `YOUR_ADDON` part.
* Run a search and replace on all the files in the entire folder structure for `YOUR_ADDON`, and replace it with the exact folder name of your addon.
* Run a search and replace on all the files in the entire folder structure for `YOUR_DESC`, and replace it with your addon's description.
* Run a search and replace on all the files in the entire folder structure for `YOUR_NAME`, and replace it with your name, or gamertag or whatever you want the author of the addon to be listed as.


### **Packaging & Release**
If you want to publish your addon to CurseForge, Wago, or any other distributors, the [BigWigs packager](https://github.com/BigWigsMods/packager) is the de-facto standard. You can ready more about how to setup and use it in the [release packager wiki](https://github.com/BigWigsMods/packager/wiki).

This template is ready for packager releases. It already comes with [keyword substitution](https://github.com/BigWigsMods/packager/wiki/Repository-Keyword-Substitutions) set up for the addon version `@project-version@` and release date `@project-date-iso@`. If you don't want to use keyword substitution, run a search and replace on all TOC files for `@project-version@` and `@project-date-iso@`, and replace them with your addon's version and release date. You can also remove the release date field entirely, it is optional.

For publishing to Curse and Wago, make sure to add your project IDs to all TOC files under `X-Curse-Project-ID` and `X-Wago-ID` respectively. You can read more on their documentation pages:
* CurseForge: [Automatic Packaging](https://support.curseforge.com/en/support/solutions/articles/9000197281-automatic-packaging)
* Wago: [Packager Docs](https://docs.wago.io/#bigwigs-packager)

## **Support & Connect**
* PayPal: [www.paypal.me/goldpawsstuff](https://www.paypal.me/goldpawsstuff)  
* Twitter: [@GoldpawsStuff](https://twitter.com/goldpawsstuff)  

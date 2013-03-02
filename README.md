*PocketTool Source Code*
=============================

This is the complete source of PocketTool.
To create a working build, you will need to download the following and add them to your build path:
 * [SimpleNBT](https://github.com/SpoutDev/SimpleNBT)
 * [Zip-Signer](http://code.google.com/p/zip-signer/)
 * [Spongy Castle](http://rtyley.github.com/spongycastle/) - Due to changes in Zip-Signer's API, this may also need to be linked into the APK.
 
 
-----------------------------
 
PocketTool is licensed under the Eclipse Public License (http://www.eclipse.org/legal/epl-v10.html)
 


 *Jellybean compatibily branch*
 TODO:
 * Remove dependencies that rely upon the old Android package/application system
 * Detect platform version (Jellybean)
 * Inform user of entering Jellybean compatibility mode
 * Include a default custom texture pack to accomodate not being able to pull assets from apk files
 * Optimize to use internal storage if necessary
 * Optimize the "build" system; legacy code has to go!
 * Add tablet/land scape layouts

 

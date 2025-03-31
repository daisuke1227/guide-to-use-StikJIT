# How to Install LiveContainer

1. Go to SideStore and follow the required guide: [SideStore](https://sidestore.io/)
2. Download the IPA for LiveContainer: [LC IPA](https://nightly.link/hugeBlack/LiveContainer/workflows/build/main/com.kdt.livecontainer.ipa.zip)
3. Install it in SideStore, and you're done! Yay!

# How to Use LiveContainer

1. Go to Settings and tap "Patch SideStore," then continue.  
   - This will bring you to the SideStore app. Just wait for it to load.  
2. Go back into LiveContainer and check if you have JIT-less mode enabled (you may need to restart the app).

### How to Install and Use an App

1. Click the plus button in the top left and select "Install IPA File."  
   - Choose the IPA file and wait for it to install; it won't take long.  
   - Once installed, hit "Run," and it should work! >~<  

### How to Use JIT in LiveContainer

1. Go to Settings again and, under "JIT," select the type of JIT enabler you want (StikJIT Standalone is recommended).  
   - Refer to the StikJIT install guide for detailed steps: [StikJIT User Manual](https://github.com/daisuke1227/guide-to-use-StikJIT/blob/main/StikJIT.md)  
2. Go to the app that requires JIT, hold down on the app, then tap "Settings."  
   - Enable the "Launch with JIT" option.  
   - Click the "My Apps" section, and you should be done.

### Bug Fixes

1. **"The bundle 'OpenSSL' couldn’t be loaded" error**  
   - To fix this, go to Settings and change the Default Signer from AltSign to ZSign.  
   - Then, hold down on the app, go to "Settings," scroll down to "Signer," and change it from AltSign to ZSign.

# FAQ  

**Will this work for every iOS version?**  
Yes, it will! Basically, every iOS version is supported.

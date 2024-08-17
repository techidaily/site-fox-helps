---
title: "A Beginner's Tutorial on Using LUTs in AR"
date: 2024-08-16T07:28:24.831Z
updated: 2024-08-17T07:28:24.831Z
tags: 
  - screen-recording
  - ai video
  - ai audio
  - ai auto
categories: 
  - ai
  - screen
description: "This Article Describes A Beginner's Tutorial on Using LUTs in AR"
excerpt: "This Article Describes A Beginner's Tutorial on Using LUTs in AR"
keywords: "AR LUT Basics,Beginners Guide to LUTs,Using LUTs in AR,LUTs for AR Devices,Introduction to AR LUTs,Learning AR LUT Techniques,Essential AR LUT Tutorial"
thumbnail: https://thmb.techidaily.com/e1c4df4174fbb7e774640c12444893c833b651d1c12bd8c02f2b01f747786c25.jpg
---

## A Beginner's Tutorial on Using LUTs in AR

Color LUTs (Lookup Textures) are tables of RGB color values. In Spark AR, you can use color LUTs to quickly create color gradation effects throughout the scene. Go through the article and create your color LUT effect.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Part 1\. What are Luts in Spark AR used for?

To create a color filter effect in [Spark AR](https://sparkar.facebook.com/ar-studio/), you need a color LUT in Spark AR.

To develop AR effects for mobile cameras, you can use the Mac and Windows augmented reality platform Spark AR Studio. Imagine it like Sketch or Photoshop for augmented reality. The color values of the camera texture are mapped to the x, y, and z coordinates of the location in the color LUT. This location contains a corresponding output color that is drawn over the scene to create a color gradient effect.

![create a color gradient effect](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-1.jpg)

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Part 2\. How to use LUTs in Spark AR?

**How to apply a color LUT to the whole scene in Spark AR:**

##### Step1Add a color LUT to your project

1. In the Assets panel, click Add Asset.
2. Select Import, then Color LUT, and select your file from your computer.

When you import a color LUT, compression is always set to None, and filtering is set to Low by default.

##### Step2Apply to the whole scene

1. In the Assets panel, right-click the LUT color.
2. Select Actions and then **Apply to Camera**.

A patch graph is automatically set that applies a color LUT to the entire scene.

![apply to the whole scene](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-2.jpg)

**The color LUT patch graph**

The patch graph that renders the color gradation effect looks like this:

![color lut patch graph](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-3.jpg)

**To create the effect:**

* Fix Scene Render Pass renders cameraTexture0 and all objects in the scene that are children of the device. This creates the output texture.
* ColorLUTShader looks up the RGBA values of this texture in the Tension color LUT array and converts them to a new green color. This will change the texture and create a gradient effect.
* Finally, the Screen Output patch renders the green color.

## Part 3\. Free LUTs resource for Spark AR

Here are the best free LUTs resources for Spark AR:

### 1\. Frost Zombie (Technical Showcase)

Client filter pieces occasionally end up on the scrap heap. It was a poor Frost Zombie in this instance. Since this is one of my simpler filters, I felt it was okay to publish the build information. Four objects make up much of the scene: an EyeColor block, a custom canvas segmentation, a face mesh, and an emitter for the breath mist (my personal favorite). To show the layers used in generating the primary zombie texture, I also moved to Substance Painter. This is a demonstration of my methods rather than a step-by-step manual.

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![frost zombie](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-4.jpg)

### 2\. Fur

Here are the key building principles.

* Geometric layers, often known as shells, produce depth.
* Normals is used to create shells from a single mesh.
* Alpha decreases with each shell.
* Deeper shells are darker.
* Height is generated from a single grayscale channel.
* No fur is generated in the black areas of the height texture.

![fur](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-5.jpg)

### 3\. Shockwave

Even while using large image sequences is frequently discouraged, you can still use them to make some extremely spectacular effects! I'll explain how the screen tap computation procedure relates to texture position in this walkthrough. If you want to apply this approach and texture sequence in your projects or give it a try.

![shockwave](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-6.jpg)

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 4\. Transition Curves

There are 11 distinct animation curves included with Spark AR in the Transition patch. Here is a helpful visual aid because it might be challenging to distinguish between a quartic and a quintic when working on a project. With the SDF circle doubled (to sharpen the edge) and inserted into the Patch Pack's alpha channel, the circles are likewise straightforward rectangles. Since RGB values are three times one, the object is white.

![transition curves](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-7.jpg)

### 5\. Realistic Smoke

By adding smoke to a scene, you can easily add a lot of detail and realism. Nothing revolutionary is happening here. The particle emitter creates flat planes of smoke texture that are forced upward. The force slowly shifts left and right as seen in the patch editor. The Fade particle script (created by Josh Beckwith) enlarges the particles and fades them out at the same time.

![realistic smoke](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-8.jpg)

### 6\. Rainbow Glitter

Given how beautifully Glitter Rain was received, I believed it would be fitting to broaden the potential with an HDR setting. While Glitter Rain made use of two different colors, this technique makes use of an entirely colorless substance and gets its color information via HDR.

![rainbow glitter](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-9.jpg)

### Closing Thoughts

Spark AR is an amazing website for LUTs and color grading. Whether you're a new student or a seasoned pro, Spark AR Studio has all the features and capabilities you need to become a good video editor. You can download free LUTs from Spark AR and apply them to your videos. The article guides on how to use LUTs in Spark AR and how to download free LUTs. So, Spark AR is one of the best online websites for LUTs I have tried.

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For Win 7 or later(64-bit)

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For macOS 10.14 or later

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For macOS 10.14 or later

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>




<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-empowering-enterprises-through-vr-engagement/"><u>[New] 2024 Approved  Empowering Enterprises Through VR Engagement</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-a-step-by-step-guide-to-mastering-morphvox-modifications/"><u>[New] A Step-by-Step Guide to Mastering MorphVOX Modifications</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-blueprint-for-a-personalized-high-definition-editing-haven/"><u>[New] Blueprint for a Personalized, High-Definition Editing Haven</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-elevating-your-tiktok-unboxing-content-with-effective-strategies-for-2024/"><u>[New] Elevating Your TikTok Unboxing Content with Effective Strategies for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-how-to-use-picture-in-picture-pip-on-microsoft-edge/"><u>[New] How to Use Picture in Picture (PIP) on Microsoft Edge</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-best-cameras-to-capture-slow-motion-videos/"><u>[New] In 2024, Best Cameras to Capture Slow Motion Videos</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-tackling-massed-up-tiktoks-expert-edits-for-less-chaos/"><u>[New] In 2024, Tackling Massed-Up TikToks  Expert Edits for Less Chaos</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-paint-your-vision-top-8-best-drawing-apps-for-iphone-enthusiasts-for-2024/"><u>[New] Paint Your Vision  Top 8 Best Drawing Apps for iPhone Enthusiasts for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-srt-essentials-decoded-for-easy-understanding-for-2024/"><u>[New] SRT Essentials Decoded for Easy Understanding for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-the-art-of-image-hunting-on-pexelscom/"><u>[New] The Art of Image Hunting on Pexels.com</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-top-videography-items-for-travelers/"><u>[New] Top Videography Items for Travelers</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-premier-online-repositories-for-typography/"><u>[Updated] 2024 Approved  Premier Online Repositories for Typography</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-building-better-montages-a-creative-guide-for-2024/"><u>[Updated] Building Better Montages  A Creative Guide for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-10-leading-4k-displays/"><u>[Updated] In 2024, 10 Leading 4K Displays</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-convert-spoken-words-into-written-content-using-ms-words-in-built-tools/"><u>[Updated] In 2024, Convert Spoken Words Into Written Content Using MS Word's In-Built Tools</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-mastering-light-manipulation-for-captivating-gopro-time-lapse-scenes/"><u>[Updated] In 2024, Mastering Light Manipulation for Captivating GoPro Time Lapse Scenes</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-thriving-livestreams-strategies-for-beginners-with-low-followers/"><u>[Updated] In 2024, Thriving Livestreams  Strategies for Beginners with Low Followers</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-transform-your-tactics-exclusive-free-voice-change-tool-for-valorant-gamers/"><u>[Updated] In 2024, Transform Your Tactics  Exclusive Free Voice Change Tool for Valorant Gamers</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-photobooth-lags-steadying-the-playback-journey/"><u>[Updated] Photobooth Lags  Steadying the Playback Journey</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-revolutionary-tools-elevating-vr-games-for-2024/"><u>[Updated] Revolutionary Tools Elevating VR Games for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-smart-shopping-strategy-top-7-affordable-4k-mirrorless/"><u>[Updated] Smart Shopping Strategy  Top 7 Affordable 4K Mirrorless</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-stealth-in-social-media-going-unseen-with-live-feeds/"><u>[Updated] Stealth in Social Media  Going Unseen with Live Feeds</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-top-10-cameras-to-document-the-rhythm-of-2024s-music-world/"><u>[Updated] Top 10 Cameras to Document the Rhythm of 2024'S Music World</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Xiaomi Redmi Note 12 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-2023s-leading-platforms-for-picture-frame-adjustment-techniques/"><u>2024 Approved  2023'S Leading Platforms for Picture Frame Adjustment Techniques</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-digital-creativity-unleashed-top-montage-apps-for-iphone-android-users/"><u>2024 Approved  Digital Creativity Unleashed  Top Montage Apps for iPhone, Android Users</u></a></li>
<li><a href="https://fox-helps.techidaily.com/a-step-by-step-approach-for-effective-spotify-marketing-for-2024/"><u>A Step-by-Step Approach for Effective Spotify Marketing for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/discover-the-power-of-color-a-guide-to-7-standout-techniques-for-2024/"><u>Discover the Power of Color  A Guide to 7 Standout Techniques for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-vivo-y100a-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Vivo Y100A | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/guide-on-how-to-erase-iphone-8-plus-devices-entirely-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Erase iPhone 8 Plus Devices Entirely | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-cutting-edge-tactics-for-flawless-iphones-and-podcast-downloads/"><u>In 2024, Cutting-Edge Tactics for Flawless iPhones and Podcast Downloads</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-zte-nubia-z60-ultra-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From ZTE Nubia Z60 Ultra to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-oppo-find-x7-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Oppo Find X7 Ultra? | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-mastering-two-screen-viewing-step-by-step-guide-for-netflix-users/"><u>In 2024, Mastering Two Screen Viewing - Step By Step Guide For Netflix Users</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-perfect-your-movie-watching-with-added-captions-on-windows-media-player/"><u>In 2024, Perfect Your Movie Watching with Added Captions on Windows Media Player</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-why-is-ipogo-not-working-on-poco-c65-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Poco C65? Fixed | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/iphones-unlocked-smart-tips-for-saving-and-playing-gifs-for-2024/"><u>IPhones Unlocked  Smart Tips for Saving & Playing GIFs for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/seamless-integration-of-video-filters-in-zoom/"><u>Seamless Integration of Video Filters in Zoom</u></a></li>
<li><a href="https://fox-helps.techidaily.com/simplifying-onestream-techniques-for-effective-streaming-for-2024/"><u>Simplifying OneStream Techniques for Effective Streaming for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/techniques-for-straightening-aerial-video-stability-for-2024/"><u>Techniques for Straightening Aerial Video Stability for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-artisans-approach-to-archiving-facebook-discussions-for-2024/"><u>The Artisan's Approach to Archiving Facebook Discussions for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/unmatched-video-upload-aides-to-twitter-for-2024/"><u>Unmatched Video Upload Aides to Twitter for 2024</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-xiaomi-14-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Xiaomi 14 Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-is-ipogo-not-working-on-oppo-reno-11f-5g-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Oppo Reno 11F 5G? Fixed | Dr.fone</u></a></li>
</ul></div>

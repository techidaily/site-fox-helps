---
title: "A Beginner's Tutorial on Using LUTs in AR"
date: 2024-07-13T19:18:54.399Z
updated: 2024-07-14T19:18:54.399Z
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
<li><a href="https://extra-hints.techidaily.com/beyond-vlc-a-deep-dive-into-media-players-for-2024/"><u>Beyond VLC  A Deep Dive Into Media Players for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-seamless-gopro-broadcasts-tips-for-facebook-and-periscope-channeling/"><u>[Updated] Seamless GoPro Broadcasts  Tips for Facebook & Periscope Channeling</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-unwatermark-your-tiktok-videos-top-online-removal-methods-for-2024/"><u>New Unwatermark Your TikTok Videos Top Online Removal Methods for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-premium-after-effects-text-enhancements/"><u>2024 Approved  Premium After Effects Text Enhancements</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-best-screen-recording-software-top-10-list-for-2024/"><u>[New] Best Screen Recording Software  Top 10 List for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/a-deep-dive-into-vscos-creative-palette/"><u>A Deep Dive Into VSCO's Creative Palette</u></a></li>
<li><a href="https://fox-helps.techidaily.com/a-guide-to-creative-use-of-supplementary-footage-b-roll/"><u>A Guide to Creative Use of Supplementary Footage (B-Roll)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/elevate-your-video-game-on-instagram-with-right-dimensions/"><u>Elevate Your Video Game on Instagram with Right Dimensions</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/crucial-elements-when-choosing-an-audio-editor-for-apple-computers/"><u>Crucial Elements When Choosing an Audio Editor for Apple Computers</u></a></li>
<li><a href="https://fox-helps.techidaily.com/assessing-video-file-size-in-a-days-watching/"><u>Assessing Video File Size in a Day's Watching</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-pro-iphone-tips-for-capturing-the-perfect-landscape-moments/"><u>2024 Approved  Pro iPhone Tips for Capturing the Perfect Landscape Moments</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-capturing-honesty-a-comprehensive-guide-to-insta-self-verification/"><u>[Updated] 2024 Approved  Capturing Honesty  A Comprehensive Guide to Insta Self-Verification</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-meizu-21-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Meizu 21? | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-sony-fdr-x1000v-action-camera-complete-review/"><u>2024 Approved  Sony FDR-X1000V Action Camera Complete Review</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-seeing-more-than-ever-samsungs-galaxy-s8-and-4k-breakthrough/"><u>2024 Approved  Seeing More Than Ever  Samsung's Galaxy S8 and 4K Breakthrough</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-snapscreen-videorecorder-tool-for-2024/"><u>[New] SnapScreen Videorecorder Tool for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/rethinking-tiktok-a-2023-guide-to-alternative-networks/"><u>Rethinking TikTok  A 2023 Guide to Alternative Networks</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-the-definitive-iphone-hdr-technique/"><u>2024 Approved  The Definitive iPhone HDR Technique</u></a></li>
<li><a href="https://fox-helps.techidaily.com/actors-availability-for-video-downloads/"><u>Actors' Availability for Video Downloads</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-visualizing-creativity-to-perfection-with-magix-video-pro-x/"><u>2024 Approved  Visualizing Creativity to Perfection with Magix Video Pro X</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-unlocking-untapped-utility-zoom-in-on-minecraft/"><u>2024 Approved  Unlocking Untapped Utility  Zoom in on Minecraft</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-virtual-realms-deconstructed-insights-into-vr-ar-and-mr/"><u>2024 Approved  Virtual Realms Deconstructed  Insights Into VR, AR, and MR</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-global-table-talks-foodie-wonders-from-every-corner/"><u>[Updated] 2024 Approved  Global Table Talks  Foodie Wonders From Every Corner</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-ultimate-selection-for-top-tier-hdr-cameras/"><u>2024 Approved  Ultimate Selection for Top-Tier HDR Cameras</u></a></li>
<li><a href="https://some-techniques.techidaily.com/ideal-selection-7-best-mac-video-apps-for-2024/"><u>Ideal Selection  7 Best Mac Video Apps for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-snickerscreen-composer/"><u>2024 Approved  SnickerScreen Composer</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-skys-the-limit-revel-in-20-top-free-cloud-service-plans-up-to-1tb/"><u>2024 Approved  Sky's the Limit  Revel in 20 Top Free Cloud Service Plans (Up To 1TB)</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-zooming-success-detailed-instruction-for-exceptional-podcast-recording-quality/"><u>[Updated] 2024 Approved  Zooming Success  Detailed Instruction for Exceptional Podcast Recording Quality</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-top-6-best-8k-cameras/"><u>2024 Approved  Top 6 Best 8K Cameras</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-revitalize-your-reels-a-compreenas-guide-for-enhancer-22/"><u>2024 Approved  Revitalize Your Reels  A Compreenas Guide for Enhancer 2.2</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-break-the-monotony-with-these-6-captivating-videos/"><u>2024 Approved  Break the Monotony with These 6 Captivating Videos</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-unleashing-vibrance-grading-secrets-in-ps/"><u>2024 Approved  Unleashing Vibrance  Grading Secrets in PS</u></a></li>
<li><a href="https://fox-helps.techidaily.com/a-step-by-step-manual-to-freeze-backgrounds-in-affinity-photo-for-2024/"><u>A Step-by-Step Manual to Freeze Backgrounds in Affinity Photo for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/screen-record-wizard-for-win11-enthusiasts-for-2024/"><u>Screen Record Wizard for Win11 Enthusiasts for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-prime-jocular-photo-artist/"><u>2024 Approved  Prime Jocular Photo Artist</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-plating-perfection-tips-for-shooting-culinary-content/"><u>2024 Approved  Plating Perfection  Tips for Shooting Culinary Content</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-step-by-step-adding-vivid-filters-to-zoom-calls/"><u>2024 Approved  Step-by-Step  Adding Vivid Filters to Zoom Calls</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/enhancing-imagery-a-step-by-step-guide-to-crop-videos-on-instagram/"><u>Enhancing Imagery  A Step-by-Step Guide to Crop Videos on Instagram</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-unlock-the-power-of-a-new-identity-step-by-step-guide-to-alter-your-game-characters-voice-for-free/"><u>2024 Approved  Unlock the Power of a New Identity  Step-by-Step Guide to Alter Your Game Character's Voice for FREE</u></a></li>
<li><a href="https://fox-helps.techidaily.com/advanced-accessories-for-immersive-gaming-worlds/"><u>Advanced Accessories for Immersive Gaming Worlds</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-speeding-up-spotify-tracks-safe-techniques-and-strategies/"><u>2024 Approved  Speeding Up Spotify Tracks  Safe Techniques and Strategies</u></a></li>
</ul></div>

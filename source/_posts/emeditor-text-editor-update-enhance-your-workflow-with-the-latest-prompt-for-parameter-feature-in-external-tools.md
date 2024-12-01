---
title: "EmEditor Text Editor Update: Enhance Your Workflow with the Latest 'Prompt for Parameter' Feature in External Tools"
date: 2024-11-26T09:03:11.175Z
updated: 2024-11-30T23:14:07.949Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/d8d350936386f188a2d4be816539be2eaee7c30695c76166aa925348b0ff1b74.jpg
---

## EmEditor Text Editor Update: Enhance Your Workflow with the Latest 'Prompt for Parameter' Feature in External Tools

Viewing 4 posts - 1 through 4 (of 4 total)

* Author  
Posts
* May 26, 2012 at 10:18 pm [#10380](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/f29c043a3cc5c5dac8db4e62939893e9?s=80&d=identicon&r=g)Stefan](https://www.emeditor.com/forums/users/Stefan/ "View Stefan's profile")  
Participant  
I want to suggest an new argument for the External Tools setup:  
**$(Para: description)**  
 To give even more flexibility to the external tools command  
 and allow us to insert the current needed parameters on the fly.  
 If this argument is present (one time or more often),  
 the user is prompted by an input() dialog box.  
 What the user enter to that box is inserted  
 into the tool argument before executing the tool.  
 (if the prompt dialog is canceled, nothing is inserted)  
 Example  
 Command: .unixgawk  
 Argument: $(Para: Enter an AWK command:) $(SelText) $(Para: awk para?)  
 On executing this tool the user is prompted:  
 —————————–  
 Enter an AWK command:  
 —————————–  
 “{print $2, $1}”  
 —————————–  
 \[OK\] \[Cancel\]  
 —————————–  
    
 —————————–  
 awk para?  
 —————————–  
 /eg  
 —————————–  
 \[OK\] \[Cancel\]  
 —————————–  
 and the command line is build like  
 p:athtoEmEditorunixgawk “{print $2, $1}” SelText /eg  
 With this i also reduce the need to set up several  
 tools as text filter to replace the selection  
 which only differ in the parameters given.  
 If the prompt dialog would provide an drop-down history list  
 would be even more nifty.  
 This history must not be different for different tools  
 but could share the history for all tools.  
 .  
September 5, 2012 at 9:42 am [#10521](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/f29c043a3cc5c5dac8db4e62939893e9?s=80&d=identicon&r=g)Stefan](https://www.emeditor.com/forums/users/Stefan/ "View Stefan's profile")  
Participant  
.  
> Yutaka wrote:  
> Please let me know again if new features didn’t show up when the new major beta version becomes available.  
 .  
September 5, 2012 at 3:46 pm [#10528](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
Hi Stefan,  
 You can achieve the same result using the Snippets plug-in. Can you try?  
 Thanks!  
April 8, 2013 at 10:35 am [#10916](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/f29c043a3cc5c5dac8db4e62939893e9?s=80&d=identicon&r=g)Stefan](https://www.emeditor.com/forums/users/Stefan/ "View Stefan's profile")  
Participant  
    
    
 Hi Yutaka, thank you for the feedback.  
 This works for Snippets… but I want to use this “parameter request box” for tools too.  
 It could be used for many purposes. Do you think you will implement this?  
 Thanks!  
 Stefan
* Author  
Posts

Viewing 4 posts - 1 through 4 (of 4 total)

* You must be logged in to reply to this topic.

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
<li><a href="https://win-forum.techidaily.com/a-step-by-step-guide-to-running-any-application-as-administrator-in-windows-11/"><u>A Step-by-Step Guide to Running Any Application as Administrator in Windows 11</u></a></li>
<li><a href="https://win-bytes.techidaily.com/1728504737835-aomei/"><u>AOMEIの信頼性高いバックアップソリューションを支えるパートナー関係構築 - 安心してビジネスを進められるパートナーへ</u></a></li>
<li><a href="https://win-bytes.techidaily.com/definir-les-caracteristiques-uniques-de-fichiers-et-documents-une-cle-pour-la-comprehension/"><u>Définir Les Caractéristiques Uniques De Fichiers Et Documents : Une Clé Pour La Compréhension</u></a></li>
<li><a href="https://buynow-info.techidaily.com/discover-enhanced-home-protection-with-the-newly-revamped-blink-4p-motion-detection-floodlight-cam/"><u>Discover Enhanced Home Protection with the Newly-Revamped Blink 4P Motion Detection Floodlight Cam</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-do-you-unlock-your-iphone-6-learn-all-4-methods-by-drfone-ios/"><u>How Do You Unlock your iPhone 6? Learn All 4 Methods</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Meizu 21 Pro? | Dr.fone</u></a></li>
<li><a href="https://win-solutions.techidaily.com/speeding-up-application-startup-in-windows-11-mastering-keyboard-shortcut-techniques/"><u>Speeding Up Application Startup in Windows 11: Mastering Keyboard Shortcut Techniques</u></a></li>
<li><a href="https://win-able.techidaily.com/total-war-warhammer-ii-addressing-and-solving-system-crash-issues-effectively/"><u>Total War: WARHAMMER II - Addressing and Solving System Crash Issues Effectively</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-or-install-secure-the-newest-amd-smbus-drivers-in-a-flash/"><u>Update or Install? Secure the Newest AMD SMBus Drivers in a Flash!</u></a></li>
<li><a href="https://win-bytes.techidaily.com/wie-fuge-ich-meine-eigenen-songs-auf-meinem-iphone-zu-itunes-hinzu/"><u>Wie Füge Ich Meine Eigenen Songs Auf Meinem iPhone Zu iTunes Hinzu?</u></a></li>
<li><a href="https://win-bytes.techidaily.com/1728492721666-windows-11/"><u>Windows 11上有效利用分区阴影复制功能的步骤</u></a></li>
<li><a href="https://win-bytes.techidaily.com/1728508628318-404/"><u>お待たせしてすみません: ご読みいただけないページへのアクセス - 404エラー</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->


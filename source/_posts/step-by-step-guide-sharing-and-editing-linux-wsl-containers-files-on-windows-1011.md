---
title: "Step-by-Step Guide: Sharing & Editing Linux WSL Containers' Files on Windows 10/11"
date: 2024-08-26 13:32:18
updated: 2024-08-29 10:38:44
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d35e798d7cf8d00e558373e4952ec0178aa0674db22d4cc9c0a2fcdcf78387c6.jpg
---

## Step-by-Step Guide: Sharing & Editing Linux WSL Containers' Files on Windows 10/11

### Quick Links

* [Open WSL Files from Terminal](https://eaxpv-info.techidaily.com/new-in-2024-guide-to-choosing-ideal-youtube-thumbnail-shapes/)
* [Open the WSL Directory in File Explorer Directly](https://activate-lock.techidaily.com/how-to-bypass-icloud-by-checkra1n-even-from-apple-iphone-se-2022-if-youve-tried-everything-by-drfone-ios/)

### Key Takeaways

* Enter "\\\\wsl$" in the File Explorer address bar to view all of your Linux distributions.
* Run **explorer.exe .** from within your Linux distribution to open Windows File Explorer to view that Linux distribution's files.
* You can directly interact with your Linux files from within Windows.

[Windows 10's May 2019 Update](https://bypass-frp.techidaily.com/easy-guide-to-infinix-smart-8-pro-frp-bypass-with-best-methods-by-drfone-android/) introduced an easy, safe, and officially supported way to access and work with your Linux files from within File Explorer and other applications. Here's how to get at your [Windows Subsystem for Linux](https://tech-haven.techidaily.com/ais-role-in-todays-misinformation-landscape/) (WSL) files.

 Unlike previous methods, this is a safe way to work with Linux files! Windows does some magic in the background, making it possible to edit your Linux files from Windows applications without causing file permission issues. You still shouldn't modify the underlying files at [their real location on your system](https://some-skills.techidaily.com/in-2024-transforming-images-the-art-of-applying-luts-in-pro/).

 It doesn't matter if you use WSL1 or WSL2\. These commands all function exactly the same way.

##  Open WSL Files from Terminal

 There are two ways to access your Linux files. First, the easy one. From within the Windows Subsystem for Linux environment you want to browse, run the following command:

explorer.exe .

 This will launch File Explorer showing the current Linux directory—you can browse the Linux environment's file system from there.

## ![Opening Windows Explorer to the Linux folder using a Linux command.](https://static0.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/image-1-2.png)Open the WSL Directory in File Explorer Directly

 You can also access them directly at the `\\wsl---
title: "Step-by-Step Guide: Sharing & Editing Linux WSL Containers' Files on Windows 10/11"
date: 2024-08-26 13:32:18
updated: 2024-08-29 10:38:44
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d35e798d7cf8d00e558373e4952ec0178aa0674db22d4cc9c0a2fcdcf78387c6.jpg
---

 path. In File Explorer or any other Windows application that can browse files, navigate to the following path:

\\wsl$

 You'll see the folders for all your installed Linux distributions, which are exposed as if they were network shares. For example, Ubuntu 22.04 is usually available at `\\wsl$\Ubuntu-22.04`.

 Feel free to create a shortcut to this folder—for example, you could drag it to the Quick Access section in File Explorer's sidebar.

![The parent folder for the Linux distros in WSL on Windows 11.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/image-2-1.png) 

 Again, you can modify these files normally as if they were any other type of file on your system. Modify files with Windows tools ([Notepad even supports Unix line endings](https://extra-tips.techidaily.com/in-depth-review-vrs-winning-features-and-faults/)!), create new files in the Linux folders, delete files, or do anything else you like. Windows will ensure nothing goes wrong and the file's permissions are updated properly.

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

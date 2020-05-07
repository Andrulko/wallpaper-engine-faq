# Steam Wallpaper Download Issues

Keep in mind that **all downloads are performed by Steam**. Wallpaper Engine only shows the Steam download status, all download problems are related to issues with your Steam and not directly related to Wallpaper Engine. This guide contains a collection of the most common issues with downloads, in many cases the initial cause of problems are overzealous antivirus applications or blocked network ports.

If you are having issues with Steam downloads, make sure no antivirus application is blocking your Steam and that all necessary ports are open in your firewall - including any firewalls in your network routers.

::: tip
You can easily check if your network router is blocking Steam downloads by switching to a mobile hotspot on your smartphone and attempt to download a wallpaper through that.
:::

## Wallpaper download stuck at 0% or 100% (or any other percentage)
Steam is not done downloading and verifying the files. If the downloads are stuck for a while, try these things if your Steam downloads do not work even after you waited for a while:

* Clear Steam's download cache in Steam's options:
  * [Clear Steam Download cache](https://support.steampowered.com/kb_article.php?ref=3134-TIAL-4638)
* Afterwards verify the files of Wallpaper Engine in Steam:
  * [Verify Wallpaper Engine files](https://support.steampowered.com/kb_article.php?ref=2037-QEUH-3335)
* If all downloads are still stuck: **Turn off Steam** and afterwards **delete the contents** of this directory:
  * `C:\Program Files (x86)\Steam\steamapps\workshop\downloads`
    * If you have an anti-virus application installed, make sure that it's specifically excluding this directory
* Restart Steam. Do not start any games. Check in the Steam download tab for progress and resume any paused downloads.

**The steps above fix download issues for most people, if that did not fix the issue for you, try these additional steps:**

* Make sure no anti-virus or firewall is blocking Steam. Exclude the whole Steam directory in your anti-virus app settings.
* Unsubscribe the wallpapers that fail to download and subscribe to them again after restarting Steam.
* Choose a different content server in Steam's settings. The option can be found in the "Downloads" tab of the Steam settings.
* Make sure you did not restrict Steam downloads in the **Steam settings** based on time, bandwidth, being in-app.
* Open the 'Downloads' tab in Steam (Library -> Downloads). Look for paused downloads. If you can see any, click on 'Resume'.
* Right-click Wallpaper Engine in Steam, then Properties, then select **Allow Background Downloads**.
* Make sure you do not have pending game updates in Steam, it could pause or disable wallpaper downloads.
* Try again after waiting at least for a day in case there are Steam server issues.
* **As a last resort**, try to re-install Wallpaper Engine to clear any broken Steam files (this will re-download all wallpapers!).

::: tip
Steam servers go offline every week for maintenance at a fixed time:

* United States West Coast: **Tuesday at 4 pm (UTC - 7)** 
* Same time in Central Europe: **Wednesday at 1 am (UTC + 1)**
* Same time in China: **Wednesday at 8 am (UTC + 8)**

If you are reading this while it is roughly this time of the week, it may be that the servers are temporarily offline. Wait one or two hours and try again.
:::

## Steam: "Missing Downloaded Files" error

Steam is unable to download some files, this can be due to anti-virus applications blocking Steam or just absolutely random. It can usually be fixed this way:

* Turn off Steam.
* Delete the contents of this directory: `C:\Program Files (x86)\Steam\steamapps\workshop\downloads`
* Delete the contents of this directory: `C:\Program Files (x86)\Steam\steamapps\downloading\431960`
* Start Steam and verify the Wallpaper Engine files:
  * [Verify Wallpaper Engine files](https://support.steampowered.com/kb_article.php?ref=2037-QEUH-3335)

If you have an antivirus-app installed: Configure an exception for this directory to prevent it from blocking Steam's Workshop downloads: `C:\Program Files (x86)\Steam\steamapps\workshop\downloads`

## "Content file locked" / Disk Write Error

If Steam fails to download Wallpaper Engine either while installing or updating the app, it is most likely your anti-virus deleting files, putting files into quarantine or blocking entire directories on your disk without informing you about this. You will get 'content file locked' or 'access denied' errors in Steam. This needs to be resolved in your anti-virus by undoing the changes it did to your PC, most anti-virus programs have a quarantine window from where you can restore files or create whitelist. Make sure your antivirus application ignores the following directories:

* `C:\Program Files (x86)\Steam\steamapps\common\wallpaper_engine`
* `C:\Program Files (x86)\Steam\steamapps\workshop\downloads`
* `C:\Program Files (x86)\Steam\steamapps\downloading`

*If your Steam or Wallpaper Engine is installed in a different directory, you need to adjust the directories to your actual Steam installation path.*
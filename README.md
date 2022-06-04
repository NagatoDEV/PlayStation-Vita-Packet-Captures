# Welcome to the PlayStation Vita/PlayStation TV Packet Capture Archive!

 <p align="center">
  <img src="https://user-images.githubusercontent.com/67494727/127869135-2891abbd-0ff8-47fb-9b6c-1213cc9e8e1f.png" alt="PlayStation Vita Live Area">
</p>


  <p align="center">
    <a href="https://twitter.com/NagatoRevenge">
      <img src="https://img.shields.io/twitter/follow/NagatoRevenge?style=social&logo=twitter"
         alt="Official Nagato Revenge Twitter"></a>
   <a href="https://discordapp.com/users/975698824196657182">
        <img src="https://img.shields.io/badge/My%20Discord-Nagato%230938-5865F2"
            alt="Official Nagato Discord ID"></a>
    <a href="https://www.youtube.com/channel/UCXgz1g5ET8Un9gax-nGMjMw">
        <img src="https://img.shields.io/badge/My%20YouTube%20Channel-Nagato's%20Revenge-ff0000"
            alt="Official Nagato Revenge YouTube Channel"></a>

As the fabled [PlayStation Vita](https://blog.playstation.com/archive/2011/10/19/playstation-vita-launches-from-22-february-2012/) is now **10 years old** (as I'm currently writing this in 2021), and many of its [services/features](https://www.playstation.com/en-us/support/important-notice/) are now defunct/inoperable, I decided to record information about the internal Vita's network functions. As an avid [preservationist](https://www.youtube.com/watch?v=BppPWh49ROU) and a fanboy to the PlayStation Vita, I decided to analyze multiple Vita titles & network servers in hopes for a server emulation solution in the future. The main purpose of this archive is to **preserve/document** the history of the Vita as this console is obscure in many aspects. This archive will contain various packet captures for many PlayStation Vita titles that support online multiplayer capabilities. 

Special thanks to **Taffer** & **Nm223** for donating some captures to this archive!

Moreover, this is a little *side-project* for me as I am currently working on another preservation project called [Destination Home](https://github.com/DestinationHome) which is currently restoring [PlayStation Home's online client](https://youtu.be/D7LQP5SDUjU). 

**Disclaimer:** This repo is only for **educational/preservational** purposes. 

# Games / Services:

* As of `June 4, 2022`, here are the following titles/services that I have currently captured as of last year. 

* [Soul Sacrifice Delta](https://www.jp.playstation.com/scej/title/soulsacrifice/en/) click [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/tree/main/Soul%20Sacrifice%20Delta) to view captures. 

* As of `August 2, 2021`, here are the following titles/services that I have currently captured as of last year. 
    
    * [Call of Duty Black Ops Declassified](https://www.activision.com/games/call-of-duty/call-of-duty-black-ops-declassified) click [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/tree/main/Call%20of%20Duty%20Black%20Ops%20Declassified) to view captures. 
    
    * [Dead Or Alive 5 Plus](https://www.ign.com/articles/2012/12/13/dead-or-alive-plus-hits-vita-in-march) click [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/tree/main/Dead%20Or%20Alive%205%20Plus) to view captures.
    
    * [Dungeon Hunter: Alliance](https://www.mobygames.com/game/dungeon-hunter-alliance) click [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/tree/main/Dungeon%20Hunter%20Alliance) to view captures.
    
    * [Freedom Wars](https://www.jp.playstation.com/scej/title/freedomwars/) click [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/releases/tag/v1.1) to view captures.
    
    * [Killzone Mercenary](https://mercenary.killzone.com/) click [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/tree/main/Killzone%20Mercenary) to view captures.
    
    * [LittleBigPlanet™ PS Vita](http://littlebigplanet.playstation.com/en/games/littlebigplanet-psvita?t=US) click [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/tree/main/LittleBigPlanet%E2%84%A2) to view captures.
    
    * [Need for Speed: Most Wanted](https://www.ea.com/games/need-for-speed/need-for-speed-most-wanted) click [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/tree/main/Need%20For%20Speed%20Most%20Wanted) to view captures.
    
    * [PlayStation™Store (Vita Store)](https://store.playstation.com/en-us/) click [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/releases/tag/v1.0) to view captures.
    
    * Miscellaneous packets from PSN & other online titles can be found [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/tree/main/Miscellaneous).

* All of the following packet capture tests that have been added to this archive, I have used the following hardware/software, respectively. 

   * PlayStation Vita PCH2000 NTSC-J flashed to 3.60 [Henkaku Enso firmware](https://github.com/henkaku/enso).
   * PlayStation TV VTE1001 flashed to 3.60 [Henkaku Enso firmware](https://github.com/henkaku/enso).
   * [Network Miner Forensic Analysis Tool](https://www.netresec.com/)
   * [WireShark Protocol Analyzer](https://www.wireshark.org/)

# Documented/Observed Domains "uri":

* Down below I will list the following domains/URL's that have been documented for the respective PS Vita titles.  Note currently this is a WIP, and later domains will be added later.
   
   *  Call of Duty Black Ops Declassified for more information about the full log traffic of this capture please review the spreadsheet [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/commit/c5b413b092b761e759b0be8aaf8e22b395c6dc51).
   
        *  `livearea.np.dl.playstation.net`
        *  `ranking-rec-e01.u0.np.community.playstation.net`
        *  `static-resource.np.community.playstation.net`
          
   *  Dead Or Alive 5 Plus or more information about the full log traffic of this capture please review the spreadsheet [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/blob/main/Dead%20Or%20Alive%205%20Plus/Dead_Or_Alive__5_Plus_Capture_Logs.csv).
   
      * `static-resource.np.community.playstation.net`
   
   *  Killzone Mercenary for more information about the full log traffic of this capture please review the spreadsheet [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/blob/bc6ced1b940d5e93f5a80375667a16aeac080fa6/Killzone%20Mercenary/Killzone_Mercenary_Capture_Logs.csv).
   
      *  `a1.ww.np.dl.playstation.net`
      *  `getprof.de.np.community.playstation.net`
      *  `getprof.gb.np.community.playstation.net`
      *  `getprof.us.np.community.playstation.net`
      *  `livearea.np.dl.playstation.net`
      *  `static-resource.np.community.playstation.net`
   
   *  LittleBigPlanet™ PS Vita for more information about the full log traffic of this capture please review the spreadsheet [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/blob/main/LittleBigPlanet%E2%84%A2/LittleBigPlanet_Vita_Capture_Logs.csv).
   
        *  `getprof.au.np.community.playstation.net`
        *  `getprof.us.np.community.playstation.net`
        *  `getprof.ch.np.community.playstation.net`
        *  `getprof.gb.np.community.playstation.net`
        *  `getprof.sa.np.community.playstation.net`
        *  `getprof.us.np.community.playstation.net`
        *  `lbpvita.online.scee.com`
        *  `psn-rsc.prod.dl.playstation.net`
        *  `searchjid.eu.np.community.playstation.net`
        *  `static-resource.np.community.playstation.net`
        
   *  Need for Speed: Most Wanted for more information about the full log traffic of this capture please review the spreadsheet [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/blob/main/Need%20For%20Speed%20Most%20Wanted/Need_For_Speed_Most_Wanted_Capture_Logs.csv).

        *  `109.200.221.180:17502`
        *  `159.153.79.135:17502`
        *  `getprof.us.np.community.playstation.net`
        *  `hawaii-vita.needforspeed.com`
        *  `searchjid.usa.np.community.playstation.net`
        *  `static-resource.np.community.playstation.net`
   
   *  PlayStation™Store (Vita Store) `The North American "US Store"` for more information about all domains please review the log list [here](https://github.com/NagatoDEV/PlayStation-Vita-Packet-Captures/commit/0158c7c565b1df0cc8dd842c9ef7b128f5f1d23b).
   
        *  `apollo.dl.playstation.net`
        *  `comic.dl.playstation.net`
        *  `fus01.psp2.update.playstation.net`
        *  `nsx.np.dl.playstation.net`
        *  `psp2-e.np.dl.playstation.net`
        *  `static-resource.np.community.playstation.net`
        *  `video.dl.playstation.net`

# Want to contribute to this archive? Feel free to contact me:

<p align="center">
<a href="https://discord.com/invite/nhH6vpX">
  <img align="center" alt="TEAM Nagato width=" width="100px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/discord.svg" />
</a>
<a href="https://twitter.com/NagatoRevenge">
  <img align="center" alt="NagatoRevenge | Twitter" width="100px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/twitter.svg" />
</a>
<a href="https://www.reddit.com/user/Nagato-DEV/">
  <img align="center" alt="NagatoDev | Reddit" width="100px" src="https://seeklogo.com/images/R/reddit-logo-23F13F6A6A-seeklogo.com.png" />
</a>
<a href="https://www.youtube.com/channel/UCXgz1g5ET8Un9gax-nGMjMw">
  <img align="center" alt="NagatoDev | YouTube" width="100px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/youtube.svg" />
</a>

<details>
<summary>Gow（Gnu On Windows）のダウンロード、インストール</summary>

[ここ](https://github.com/bmatzelle/gow/releases/tag/v0.8.0)から「Gow-0.8.0.exe」をダウンロードして実行。
</details>
<details>
<summary>sdkmanを取得</summary>

$ curl -s "https://get.sdkman.io" | bash
```
********@pc_name MINGW64 ~
$ pwd
/c/Users/********

********@pc_name MINGW64 ~
$ curl -s "https://get.sdkman.io" | bash

                                -+syyyyyyys:
                            `/yho:`       -yd.
                         `/yh/`             +m.
                       .oho.                 hy                          .`
                     .sh/`                   :N`                `-/o`  `+dyyo:.
                   .yh:`                     `M-          `-/osysoym  :hs` `-+sys:      hhyssssssssy+
                 .sh:`                       `N:          ms/-``  yy.yh-      -hy.    `.N-````````+N.
               `od/`                         `N-       -/oM-      ddd+`     `sd:     hNNm        -N:
              :do`                           .M.       dMMM-     `ms.      /d+`     `NMMs       `do
            .yy-                             :N`    ```mMMM.      -      -hy.       /MMM:       yh
          `+d+`           `:/oo/`       `-/osyh/ossssssdNMM`           .sh:         yMMN`      /m.
         -dh-           :ymNMMMMy  `-/shmNm-`:N/-.``   `.sN            /N-         `NMMy      .m/
       `oNs`          -hysosmMMMMydmNmds+-.:ohm           :             sd`        :MMM/      yy
      .hN+           /d:    -MMMmhs/-.`   .MMMh   .ss+-                 `yy`       sMMN`     :N.
     :mN/           `N/     `o/-`         :MMMo   +MMMN-         .`      `ds       mMMh      do
    /NN/            `N+....--:/+oooosooo+:sMMM:   hMMMM:        `my       .m+     -MMM+     :N.
   /NMo              -+ooooo+/:-....`...:+hNMN.  `NMMMd`        .MM/       -m:    oMMN.     hs
  -NMd`                                    :mm   -MMMm- .s/     -MMm.       /m-   mMMd     -N.
 `mMM/                                      .-   /MMh. -dMo     -MMMy        od. .MMMs..---yh
 +MMM.                                           sNo`.sNMM+     :MMMM/        sh`+MMMNmNm+++-
 mMMM-                                           /--ohmMMM+     :MMMMm.       `hyymmmdddo
 MMMMh.                  ````                  `-+yy/`yMMM/     :MMMMMy       -sm:.``..-:-.`
 dMMMMmo-.``````..-:/osyhddddho.           `+shdh+.   hMMM:     :MmMMMM/   ./yy/` `:sys+/+sh/
 .dMMMMMMmdddddmmNMMMNNNNNMMMMMs           sNdo-      dMMM-  `-/yd/MMMMm-:sy+.   :hs-      /N`
  `/ymNNNNNNNmmdys+/::----/dMMm:          +m-         mMMM+ohmo/.` sMMMMdo-    .om:       `sh
     `.-----+/.`       `.-+hh/`         `od.          NMMNmds/     `mmy:`     +mMy      `:yy.
           /moyso+//+ossso:.           .yy`          `dy+:`         ..       :MMMN+---/oys:
         /+m:  `.-:::-`               /d+                                    +MMMMMMMNh:`
        +MN/                        -yh.                                     `+hddhy+.
       /MM+                       .sh:
      :NMo                      -sh/
     -NMs                    `/yy:
    .NMy                  `:sh+.
   `mMm`               ./yds-
  `dMMMmyo:-.````.-:oymNy:`
  +NMMMMMMMMMMMMMMMMms:`
    -+shmNMMMNmdy+:`


                                                                 Now attempting installation...


Looking for a previous installation of SDKMAN...
Looking for unzip...
Looking for zip...
bash: line 151: [: too many arguments
Looking for curl...
Looking for sed...
Installing SDKMAN scripts...
Create distribution directories...
Getting available candidates...
Prime the config file...
Download script archive...
######################################################################## 100.0%
Extract script archive...
Install scripts...
Set version to 5.7.4+362 ...
Attempt update of interactive bash profile on regular UNIX...
Added sdkman init snippet to /c/Users/********/.bashrc
Attempt update of zsh profile...
Updated existing /c/Users/********/.zshrc



All done!


Please open a new terminal, or run the following in the existing one:

    source "/c/Users/********/.sdkman/bin/sdkman-init.sh"

Then issue the following command:

    sdk help

Enjoy!!!

********@pc_name MINGW64 ~
```
</details>
<details>
<summary>.sdkman-init.shを実行、versionの確認</summary>

$ source "/c/Users/********/.sdkman/bin/sdkman-init.sh"  
$ sdk version
```
********@pc_name MINGW64 ~
$ pwd
/c/Users/********

********@pc_name MINGW64 ~
$ source "/c/Users/********/.sdkman/bin/sdkman-init.sh"

********@pc_name MINGW64 ~
$ sdk version
==== BROADCAST =================================================================
* 2020-03-03: Groovy 2.4.19 released on SDKMAN! #groovylang
* 2020-02-29: Leiningen 2.9.2 released on SDKMAN! #leiningen
* 2020-02-29: Jbang 0.18.0 released on SDKMAN! See https://github.com/maxandersen/jbang/releases/tag/v0.18.0 #jbang
================================================================================

SDKMAN 5.7.4+362

********@pc_name MINGW64 ~
```
</details>
<details>
<summary>Gradleをインストール</summary>

$ sdk install gradle
```
********@pc_name MINGW64 ~
$ sdk install gradle

Downloading: gradle 6.2.1

In progress...

######################################################################## 100.0%

Installing: gradle 6.2.1
Done installing!


Setting gradle 6.2.1 as default.

********@pc_name MINGW64 ~

```
</details>

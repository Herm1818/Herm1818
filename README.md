### Hi there 👋

<!--
**Herm1818/Herm1818** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...examination of files folders and directories used to build and modify MacOS & iOS
- 🌱 I’m currently learning ...There a numerous exploitations that can be used against the MacOS shell
- 👯 I’m looking to collaborate on ...developers who can hep decipher the primary cause of system infultration 
- 🤔 I’m looking for help with ...removing container folders, shielding my firewall, learning what source(S) were utilized to set intrusive perameters on all of my devices 
- 💬 Ask me about ...the devastating effect it has had on my LIFE and the PTSD
- 📫 How to reach me: ...all lines are unsecure 
- 😄 Pronouns: ..
- ⚡ Fun fact: ...im not as bright as i wish i were 
-->

Can someone please tell me what this meanins 
Last login: Tue May 17 01:30:55 on ttys001
horus@Rs-MacBook-Pro ~ % ls
Desktop				Pictures
Documents			Public
Downloads			Snort User Guide 2022.pdf
Final Cut Pro Trial		dir
Library				iCloud Drive (Archive)
Movies				mvt
Music				volatility3
horus@Rs-MacBook-Pro ~ % ls -al
total 2720
drwxrwxrwx+ 27 horus  staff      864 May 17 13:02 .
drwxr-xr-x   6 root   admin      192 Oct 30  2020 ..
-r--------   1 horus  staff        7 Apr 15 21:31 .CFUserTextEncoding
-rw-r--r--@  1 horus  staff    14340 May 16 21:58 .DS_Store
drwx------  13 horus  staff      416 May 17 07:38 .Trash
drwxr-xr-x   3 horus  staff       96 May 17 01:12 .bundle
drwx------   3 horus  staff       96 Apr 15 22:23 .cups
drwxr-xr-x   4 horus  staff      128 May 17 01:12 .gem
-rw-r--r--   1 horus  staff      202 May 15 10:57 .gitconfig
-rw-------   1 horus  staff     1266 May 15 16:09 .viminfo
drwxr-xr-x   4 horus  staff      128 May 15 11:02 .vscode
-rw-r--r--   1 horus  staff      166 Apr 16 04:44 .zprofile
-rw-------   1 horus  staff     4844 May 17 13:02 .zsh_history
drwx------+  6 horus  staff      192 Apr 25 10:47 Desktop
drwx------+  6 horus  staff      192 May 15 23:43 Documents
drwx------@ 38 horus  staff     1216 May 17 11:53 Downloads
-rw-r--r--@  1 horus  staff     1184 Apr 25 10:49 Final Cut Pro Trial
drwx------@ 66 horus  staff     2112 May 15 06:02 Library
drwx------+  5 horus  staff      160 Apr 25 11:10 Movies
drwx------+  4 horus  staff      128 Apr 16 04:12 Music
drwx------+  4 horus  staff      128 Apr 15 23:12 Pictures
drwxr-xr-x+  4 horus  staff      128 Apr 15 21:31 Public
-rw-r--r--@  1 horus  staff  1347255 May 17 00:56 Snort User Guide 2022.pdf
drwxr-xr-x   2 root   staff       64 May 17 11:19 dir
drwx------   4 horus  staff      128 May  3 13:36 iCloud Drive (Archive)
drwxr-xr-x  18 horus  staff      576 May 17 12:05 mvt
drwxr-xr-x  22 horus  staff      704 May 16 02:02 volatility3
horus@Rs-MacBook-Pro ~ % cd
horus@Rs-MacBook-Pro ~ % w
13:03  up 2 days,  2:21, 2 users, load averages: 1.07 1.09 1.15
USER     TTY      FROM              LOGIN@  IDLE WHAT
horus    console  -                Sun10   2days -
horus    s000     -                13:02       - w
horus@Rs-MacBook-Pro ~ % whoami
horus
horus@Rs-MacBook-Pro ~ % finger horus
Login: horus          			Name: R
Directory: /Users/horus             	Shell: /bin/zsh
On since Sun May 15 10:41 (EDT) on console, idle 2 days 2:21 (messages off)
On since Tue May 17 13:02 (EDT) on ttys000
On since Tue May 17 01:30 (EDT) on ttys001 (messages off)
On since Mon May 16 02:19 (EDT) on ttys002 (messages off)
On since Tue May 17 01:02 (EDT) on ttys003 (messages off)
No Mail.
No Plan.
horus@Rs-MacBook-Pro ~ % finger user
Login: _cmiodalassistants			Name: CoreMedia IO Assistants User
Directory: /var/db/cmiodalassistants	Shell: /usr/bin/false
Never logged in.
No Mail.
No Plan.

Login: _eppc          			Name: Apple Events User
Directory: /var/empty               	Shell: /usr/bin/false
Never logged in.
No Mail.
No Plan.

Login: _hidd          			Name: HID Service User
Directory: /var/db/hidd             	Shell: /usr/bin/false
Never logged in.
No Mail.
No Plan.

Login: _mbsetupuser   			Name: Setup User
Directory: /var/setup               	Shell: /bin/bash
Never logged in.
No Mail.
No Plan.

Login: _mobileasset   			Name: MobileAsset User
Directory: /var/ma                  	Shell: /usr/bin/false
Never logged in.
No Mail.
No Plan.

Login: _unknown       			Name: Unknown User
Directory: /var/empty               	Shell: /usr/bin/false
Never logged in.
No Mail.
No Plan.

Login: nobody         			Name: Unprivileged User
Directory: /var/empty               	Shell: /usr/bin/false
Never logged in.
No Mail.
No Plan.
horus@Rs-MacBook-Pro ~ % uname -a
Darwin Rs-MacBook-Pro.local 19.6.0 Darwin Kernel Version 19.6.0: Tue Feb 15 21:39:11 PST 2022; root:xnu-6153.141.59~1/RELEASE_X86_64 x86_64
horus@Rs-MacBook-Pro ~ % cat /proc/cpuinfo
cat: /proc/cpuinfo: No such file or directory
horus@Rs-MacBook-Pro ~ % cat /proc/meminfo
cat: /proc/meminfo: No such file or directory
horus@Rs-MacBook-Pro ~ % df
Filesystem                                    512-blocks      Used Available Capacity iused      ifree %iused  Mounted on
/dev/disk1s5                                   975425848  21926440 740859472     3%  488253 4876640987    0%   /
devfs                                                407       407         0   100%     707          0  100%   /dev
/dev/disk1s1                                   975425848 198113440 740859472    22%  348421 4876780819    0%   /System/Volumes/Data
/dev/disk1s4                                   975425848   6293544 740859472     1%       4 4877129236    0%   /private/var/vm
/dev/disk1s6                                   975425848   6723112 740859472     1%      74 4877129166    0%   /Volumes/my unit
/dev/disk1s7                                   975425848      1392 740859472     1%      73 4877129167    0%   /Volumes/me
map auto_home                                          0         0         0   100%       0          0  100%   /System/Volumes/Data/home
/Users/horus/Downloads/Visual Studio Code.app  975425848 151463128 791704056    17%  178927 4876950313    0%   /private/var/folders/xx/yfkxh29x4dq5yddbx31cz9000000gn/T/AppTranslocation/FA7A89AC-30E7-400E-9125-6A2E78FB83E8
/dev/disk2s3                                      729088    716392     12696    99%     154 4294967125    0%   /Volumes/Firefox
/dev/disk3s1                                     1674064   1436624    237440    86%       4 4294967275    0%   /Volumes/Command Line Developer Tools
/dev/disk4s1                                      373904    128120    245784    35%    1259 4294966020    0%   /Volumes/Additional Tools
/dev/disk5s1                                      907008    803808    103200    89%       3 4294967276    0%   /Volumes/Kernel Debug Kit
/dev/disk6s1                                     3927984   3188568    739416    82%    4453 4294962826    0%   /Volumes/Docker
horus@Rs-MacBook-Pro ~ % du
312	./Music/Music/Media.localized/.localized
312	./Music/Music/Media.localized/Automatically Add to Music.localized/.localized
312	./Music/Music/Media.localized/Automatically Add to Music.localized
632	./Music/Music/Media.localized
128	./Music/Music/Music Library.musiclibrary
760	./Music/Music
760	./Music
du: ./Pictures/Photos Library.photoslibrary: Operation not permitted
0	./Pictures
2408	./.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info
48	./.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info-special-characters
36008	./.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47
36008	./.bundle/cache/compact_index
36008	./.bundle/cache
36008	./.bundle
du: ./Desktop: Operation not permitted
0	./Library/Application Support/Firefox/Pending Pings
8	./Library/Application Support/Firefox/Profiles/xuc77p27.default
368	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/sessionstore-backups
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/crashes/events
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/crashes
288	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/features/{de2da639-9052-4987-8f37-04a1ae1daae2}
288	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/features
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/security_state
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/datareporting/glean/db
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/datareporting/glean/events
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/datareporting/glean/tmp
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/datareporting/glean/pending_pings
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/datareporting/glean
184	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/datareporting/archived/2022-05
184	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/datareporting/archived
528	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/datareporting
32	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++github.com/ls
40	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++github.com
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++www.youtube.com/idb/2483293513LCo7g%sCD7a%taa4bba9s.files
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++www.youtube.com/idb/852035040LCo7g%sCD7a%t8a9b3a8s.files
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++www.youtube.com/idb/2171031483YattIedMb.files
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++www.youtube.com/idb/2681137266LCo7g%sCD7a%t1a7bea9s.files
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++www.youtube.com/idb/3591451901LCo7g%sCD7a%tdafb3ads.files
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++www.youtube.com/idb/2896972613LCo7g%sCD7a%t0aeb2a1s.files
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++www.youtube.com/idb/4053758645LCo7g%sCD7a%t0a6b2aes.files
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++www.youtube.com/idb/2014658045LCo7g%sCD7a%t6a6b5aes.files
768	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++www.youtube.com/idb
776	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++www.youtube.com
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/moz-extension+++acabbd97-f1f2-4a64-8a96-f90e7d24b41d^userContextId=4294967295/idb/3647222921wleabcEoxlt-eengsairo.files
96	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/moz-extension+++acabbd97-f1f2-4a64-8a96-f90e7d24b41d^userContextId=4294967295/idb
104	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/moz-extension+++acabbd97-f1f2-4a64-8a96-f90e7d24b41d^userContextId=4294967295
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++support.apple.com/ls
32	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++support.apple.com
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/idb/41599451%f23F1i4netbe8ren2a6l.files
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/idb/921839947s0t0a0l0e4W1h1i7l5e1R.files
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/idb/3869568298w_omrokcb_omxt-gplr_e.files
1248	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/idb
48	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/135
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/61
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/95
64	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/132
48	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/59
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/92
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/66
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/104
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/50
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/103
48	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/57
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/168
152	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/157
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/150
240	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/159
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/32
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/166
344	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/192
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/35
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/195
152	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/161
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/102
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/69
232	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/56
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/105
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/51
48	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/58
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/133
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/67
152	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/93
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/94
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/60
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/34
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/194
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/33
40	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/158
32	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/193
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/167
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/151
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/169
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/156
168	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/216
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/211
72	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/227
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/218
320	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/220
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/245
152	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/242
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/221
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/226
280	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/219
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/210
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/217
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/228
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/243
184	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/244
104	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/250
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/235
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/232
96	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/204
112	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/203
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/251
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/202
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/205
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/233
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/234
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/174
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/180
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/20
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/187
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/18
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/173
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/27
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/9
304	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/0
152	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/145
224	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/11
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/142
56	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/7
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/16
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/189
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/129
112	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/42
248	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/89
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/116
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/45
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/111
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/73
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/118
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/87
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/127
40	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/80
176	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/74
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/6
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/28
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/143
64	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/17
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/188
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/144
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/1
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/10
88	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/186
520	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/19
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/26
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/8
224	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/181
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/175
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/21
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/75
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/81
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/121
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/119
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/86
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/72
32	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/126
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/44
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/110
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/43
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/128
40	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/88
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/117
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/198
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/153
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/38
112	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/154
400	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/36
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/196
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/162
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/165
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/131
224	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/91
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/65
184	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/136
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/62
152	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/96
136	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/109
56	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/100
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/54
552	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/107
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/98
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/138
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/53
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/30
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/190
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/37
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/163
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/155
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/199
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/39
40	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/152
32	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/106
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/99
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/52
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/139
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/101
136	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/55
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/137
136	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/97
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/108
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/63
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/130
72	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/64
416	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/90
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/248
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/241
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/246
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/215
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/223
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/224
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/247
48	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/240
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/249
40	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/225
32	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/222
136	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/214
208	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/213
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/231
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/209
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/236
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/200
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/238
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/207
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/253
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/254
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/239
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/206
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/201
40	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/208
200	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/230
392	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/255
232	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/252
128	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/46
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/79
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/112
144	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/41
208	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/115
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/83
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/77
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/123
40	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/48
184	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/70
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/84
112	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/124
256	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/184
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/170
112	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/24
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/177
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/183
32	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/148
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/23
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/141
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/4
184	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/15
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/3
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/146
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/12
48	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/179
208	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/85
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/76
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/82
192	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/49
128	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/122
56	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/40
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/114
32	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/47
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/78
144	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/147
40	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/2
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/178
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/13
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/5
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/140
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/14
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/182
72	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/176
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/22
48	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/149
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/171
16	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/185
72	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue/25
13184	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache/morgue
14536	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/cache
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com/ls
15816	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++lgtm.com
32	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++www.google.com/ls
40	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++www.google.com
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++www.apple.com/ls
32	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++www.apple.com
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++docs.brew.sh/ls
32	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++docs.brew.sh
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++developer.apple.com/ls
32	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++developer.apple.com
24	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++secure5.store.apple.com/ls
32	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default/https+++secure5.store.apple.com
16936	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/default
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/temporary
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/permanent/chrome/idb/1451318868ntouromlalnodry--epcr.files
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/permanent/chrome/idb/3870112724rsegmnoittet-es.files/journals
2040	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/permanent/chrome/idb/3870112724rsegmnoittet-es.files
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/permanent/chrome/idb/3561288849sdhlie.files
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/permanent/chrome/idb/2918063365piupsah.files
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/permanent/chrome/idb/2823318777ntouromlalnodry--naod.files
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/permanent/chrome/idb/1657114595AmcateirvtiSty.files
6808	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/permanent/chrome/idb
6816	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/permanent/chrome
6816	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage/permanent
24008	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/storage
8	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/bookmarkbackups
2360	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/gmp-gmpopenh264/1.8.1.1
2360	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/gmp-gmpopenh264
22920	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/gmp-widevinecdm/4.10.2449.0
22920	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/gmp-widevinecdm
0	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release/minidumps
86112	./Library/Application Support/Firefox/Profiles/skjogx2k.default-release
86120	./Library/Application Support/Firefox/Profiles
0	./Library/Application Support/Firefox/Crash Reports/events
8	./Library/Application Support/Firefox/Crash Reports
86144	./Library/Application Support/Firefox
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/PCS-Notes-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/PCS-iMessage-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/iCloudIdentity-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/PCS-Maildrop-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/AccessoryPairing-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/PCS-iCloudDrive-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/ContinuityUnlock-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/NanoRegistry-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/PCS-Escrow-tomb
176	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/PCS-MasterKey-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/PCS-Feldspar-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/WatchMigration-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/HomeKit-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/PCS-Sharing-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/PCS-Photos-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/PCS-CloudKit-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/PCS-FDE-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/PCS-Backup-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/AppleTV-tomb
112	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309/BackupBagV0-tomb
2304	./Library/Application Support/com.apple.sbd/176A04F8-DA87-4D5A-B9CC-D3CEFA587309
2304	./Library/Application Support/com.apple.sbd
0	./Library/Application Support/com.apple.replayd
0	./Library/Application Support/com.apple.backgroundtaskmanagementagent
8	./Library/Application Support/SyncServices/Local/Contents
8	./Library/Application Support/SyncServices/Local/clientdata/120c2b27e9ab530b442181ced8799e35b30c85cb
8	./Library/Application Support/SyncServices/Local/clientdata/633a1ba25cb8241bbde44acb603ee1e822cde772
16	./Library/Application Support/SyncServices/Local/clientdata
8	./Library/Application Support/SyncServices/Local/conflicts
128	./Library/Application Support/SyncServices/Local/TFSM/com.apple.Calendars
128	./Library/Application Support/SyncServices/Local/TFSM/com.apple.Notes
128	./Library/Application Support/SyncServices/Local/TFSM/com.apple.Contacts
128	./Library/Application Support/SyncServices/Local/TFSM/com.apple.Bookmarks
512	./Library/Application Support/SyncServices/Local/TFSM
0	./Library/Application Support/SyncServices/Local/ClientsWithChanges
952	./Library/Application Support/SyncServices/Local
952	./Library/Application Support/SyncServices
8	./Library/Application Support/com.apple.kvs/ChangeTokens
8	./Library/Application Support/com.apple.kvs
0	./Library/Application Support/Mozilla/Extensions
0	./Library/Application Support/Mozilla
1496	./Library/Application Support/com.apple.transparencyd
0	./Library/Application Support/accountsd
888	./Library/Application Support/com.apple.touristd
8	./Library/Application Support/DiskImages
0	./Library/Application Support/CoreParsec
208	./Library/Application Support/videosubscriptionsd
0	./Library/Application Support/com.apple.akd
du: ./Library/Application Support/MobileSync: Operation not permitted
0	./Library/Application Support/Google/Chrome/NativeMessagingHosts
0	./Library/Application Support/Google/Chrome
0	./Library/Application Support/Google
du: ./Library/Application Support/CallHistoryTransactions: Operation not permitted
128	./Library/Application Support/com.apple.spotlight/CandidateReports/com.apple.Spotlight
128	./Library/Application Support/com.apple.spotlight/CandidateReports
0	./Library/Application Support/com.apple.spotlight/Resources.update_V3
0	./Library/Application Support/com.apple.spotlight/Resources_V3/Experimental
0	./Library/Application Support/com.apple.spotlight/Resources_V3/Shadow
0	./Library/Application Support/com.apple.spotlight/Resources_V3/Default
0	./Library/Application Support/com.apple.spotlight/Resources_V3
248	./Library/Application Support/com.apple.spotlight
0	./Library/Application Support/dmd
0	./Library/Application Support/Code/blob_storage/e44c1c8b-3c19-4dec-95ae-ab4466214477
0	./Library/Application Support/Code/blob_storage
8	./Library/Application Support/Code/CachedData/da15b6fd3ef856477bf6f4fb29ba1b7af717770d/chrome/js/index-dir
16224	./Library/Application Support/Code/CachedData/da15b6fd3ef856477bf6f4fb29ba1b7af717770d/chrome/js
8	./Library/Application Support/Code/CachedData/da15b6fd3ef856477bf6f4fb29ba1b7af717770d/chrome/wasm/index-dir
16	./Library/Application Support/Code/CachedData/da15b6fd3ef856477bf6f4fb29ba1b7af717770d/chrome/wasm
16240	./Library/Application Support/Code/CachedData/da15b6fd3ef856477bf6f4fb29ba1b7af717770d/chrome
28856	./Library/Application Support/Code/CachedData/da15b6fd3ef856477bf6f4fb29ba1b7af717770d
28856	./Library/Application Support/Code/CachedData
32	./Library/Application Support/Code/Session Storage
1096	./Library/Application Support/Code/GPUCache
56	./Library/Application Support/Code/databases
8	./Library/Application Support/Code/Cache/Cache_Data/index-dir
96	./Library/Application Support/Code/Cache/Cache_Data
96	./Library/Application Support/Code/Cache
1424	./Library/Application Support/Code/CachedExtensions
32	./Library/Application Support/Code/Service Worker/Database
8	./Library/Application Support/Code/Service Worker/CacheStorage/8d8eea036e95703181bc89104481a98e5e0f6063/294ec304-5057-4c7e-8dc5-96717701964a/index-dir
48	./Library/Application Support/Code/Service Worker/CacheStorage/8d8eea036e95703181bc89104481a98e5e0f6063/294ec304-5057-4c7e-8dc5-96717701964a
56	./Library/Application Support/Code/Service Worker/CacheStorage/8d8eea036e95703181bc89104481a98e5e0f6063
56	./Library/Application Support/Code/Service Worker/CacheStorage
8	./Library/Application Support/Code/Service Worker/ScriptCache/index-dir
136	./Library/Application Support/Code/Service Worker/ScriptCache
224	./Library/Application Support/Code/Service Worker
48	./Library/Application Support/Code/User/workspaceStorage/cb352b2fa5a860752e2f1104ad2e5fc2
24	./Library/Application Support/Code/User/workspaceStorage/1652626942775
72	./Library/Application Support/Code/User/workspaceStorage
0	./Library/Application Support/Code/User/globalStorage/vscode.json-language-features/json-schema-cache
0	./Library/Application Support/Code/User/globalStorage/vscode.json-language-features
512	./Library/Application Support/Code/User/globalStorage
16	./Library/Application Support/Code/User/History/7d900359
16	./Library/Application Support/Code/User/History
608	./Library/Application Support/Code/User
8	./Library/Application Support/Code/CachedConfigurations/defaults/configurationDefaultsOverrides
8	./Library/Application Support/Code/CachedConfigurations/defaults
8	./Library/Application Support/Code/CachedConfigurations
24	./Library/Application Support/Code/logs/20220515T110222/exthost1/output_logging_20220515T110225
32	./Library/Application Support/Code/logs/20220515T110222/exthost1
0	./Library/Application Support/Code/logs/20220515T110222/output_3_20220515T110326
0	./Library/Application Support/Code/logs/20220515T110222/output_1_20220515T110224
24	./Library/Application Support/Code/logs/20220515T110222/exthost3/output_logging_20220515T110327
32	./Library/Application Support/Code/logs/20220515T110222/exthost3
120	./Library/Application Support/Code/logs/20220515T110222
120	./Library/Application Support/Code/logs
8	./Library/Application Support/Code/Code Cache/js/index-dir
16	./Library/Application Support/Code/Code Cache/js
8	./Library/Application Support/Code/Code Cache/wasm/index-dir
16	./Library/Application Support/Code/Code Cache/wasm
32	./Library/Application Support/Code/Code Cache
8	./Library/Application Support/Code/Backups
32	./Library/Application Support/Code/Local Storage/leveldb
32	./Library/Application Support/Code/Local Storage
32752	./Library/Application Support/Code
336	./Library/Application Support/Quick Look
112	./Library/Application Support/CrashReporter
0	./Library/Application Support/TrustedPeersHelper
32	./Library/Application Support/CloudDocs
du: ./Library/Application Support/com.apple.sharedfilelist: Operation not permitted
8376	./Library/Application Support/Knowledge
8	./Library/Application Support/icdd
du: ./Library/Application Support/com.apple.TCC: Operation not permitted
0	./Library/Application Support/com.apple.ContextStoreAgent
du: ./Library/Application Support/FileProvider: Operation not permitted
0	./Library/Application Support/AddressBook/.AddressBook-v22_SUPPORT/_EXTERNAL_DATA
0	./Library/Application Support/AddressBook/.AddressBook-v22_SUPPORT
0	./Library/Application Support/AddressBook/Sources/B4A7155D-C549-4BDE-BA40-8DC5BCC1A0AE/.AddressBook-v22_SUPPORT/_EXTERNAL_DATA
0	./Library/Application Support/AddressBook/Sources/B4A7155D-C549-4BDE-BA40-8DC5BCC1A0AE/.AddressBook-v22_SUPPORT
1336	./Library/Application Support/AddressBook/Sources/B4A7155D-C549-4BDE-BA40-8DC5BCC1A0AE
1336	./Library/Application Support/AddressBook/Sources
16	./Library/Application Support/AddressBook/Metadata
6856	./Library/Application Support/AddressBook
0	./Library/Application Support/GitHub Desktop/blob_storage/bd4c335b-2ecf-4ad9-9ac8-0169c2345cef
0	./Library/Application Support/GitHub Desktop/blob_storage
24	./Library/Application Support/GitHub Desktop/Session Storage
1096	./Library/Application Support/GitHub Desktop/GPUCache
416	./Library/Application Support/GitHub Desktop/IndexedDB/file__0.indexeddb.leveldb
416	./Library/Application Support/GitHub Desktop/IndexedDB
56	./Library/Application Support/GitHub Desktop/databases
8	./Library/Application Support/GitHub Desktop/Cache/Cache_Data/index-dir
456	./Library/Application Support/GitHub Desktop/Cache/Cache_Data
456	./Library/Application Support/GitHub Desktop/Cache
64	./Library/Application Support/GitHub Desktop/logs
8	./Library/Application Support/GitHub Desktop/Code Cache/js/index-dir
16	./Library/Application Support/GitHub Desktop/Code Cache/js
8	./Library/Application Support/GitHub Desktop/Code Cache/wasm/index-dir
16	./Library/Application Support/GitHub Desktop/Code Cache/wasm
32	./Library/Application Support/GitHub Desktop/Code Cache
40	./Library/Application Support/GitHub Desktop/Local Storage/leveldb
40	./Library/Application Support/GitHub Desktop/Local Storage
2344	./Library/Application Support/GitHub Desktop
0	./Library/Application Support/iCloud/Accounts
0	./Library/Application Support/iCloud
0	./Library/Application Support/transparencyd
du: ./Library/Application Support/CallHistoryDB: Operation not permitted
0	./Library/Application Support/syncdefaultsd
49952	./Library/Application Support/BraveSoftware/Brave-Browser/Safe Browsing
32	./Library/Application Support/BraveSoftware/Brave-Browser/jicbkmdloagakknpihibphagfckhjdih/1.0.21/1
40	./Library/Application Support/BraveSoftware/Brave-Browser/jicbkmdloagakknpihibphagfckhjdih/1.0.21
40	./Library/Application Support/BraveSoftware/Brave-Browser/jicbkmdloagakknpihibphagfckhjdih
11408	./Library/Application Support/BraveSoftware/Brave-Browser/GrShaderCache/GPUCache
11408	./Library/Application Support/BraveSoftware/Brave-Browser/GrShaderCache
13232	./Library/Application Support/BraveSoftware/Brave-Browser/aoojcmojmmcbpfgoecoadbdpnagfchel/1.0.5
13232	./Library/Application Support/BraveSoftware/Brave-Browser/aoojcmojmmcbpfgoecoadbdpnagfchel
0	./Library/Application Support/BraveSoftware/Brave-Browser/Crashpad/completed
0	./Library/Application Support/BraveSoftware/Brave-Browser/Crashpad/new
0	./Library/Application Support/BraveSoftware/Brave-Browser/Crashpad/attachments
0	./Library/Application Support/BraveSoftware/Brave-Browser/Crashpad/pending
8	./Library/Application Support/BraveSoftware/Brave-Browser/Crashpad
8	./Library/Application Support/BraveSoftware/Brave-Browser/CertificateRevocation/7338/_metadata
80	./Library/Application Support/BraveSoftware/Brave-Browser/CertificateRevocation/7338
8	./Library/Application Support/BraveSoftware/Brave-Browser/CertificateRevocation/7340/_metadata
80	./Library/Application Support/BraveSoftware/Brave-Browser/CertificateRevocation/7340
8	./Library/Application Support/BraveSoftware/Brave-Browser/CertificateRevocation/7341/_metadata
80	./Library/Application Support/BraveSoftware/Brave-Browser/CertificateRevocation/7341
8	./Library/Application Support/BraveSoftware/Brave-Browser/CertificateRevocation/7328/_metadata
80	./Library/Application Support/BraveSoftware/Brave-Browser/CertificateRevocation/7328
8	./Library/Application Support/BraveSoftware/Brave-Browser/CertificateRevocation/7342/_metadata
80	./Library/Application Support/BraveSoftware/Brave-Browser/CertificateRevocation/7342
400	./Library/Application Support/BraveSoftware/Brave-Browser/CertificateRevocation
8	./Library/Application Support/BraveSoftware/Brave-Browser/OnDeviceHeadSuggestModel/20220409.440702358/_metadata
15712	./Library/Application Support/BraveSoftware/Brave-Browser/OnDeviceHeadSuggestModel/20220409.440702358
15712	./Library/Application Support/BraveSoftware/Brave-Browser/OnDeviceHeadSuggestModel
42368	./Library/Application Support/BraveSoftware/Brave-Browser/BraveWallet/1.0.14/images
42952	./Library/Application Support/BraveSoftware/Brave-Browser/BraveWallet/1.0.14
42952	./Library/Application Support/BraveSoftware/Brave-Browser/BraveWallet
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter/_locales
496	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitter
32	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/vimeo
48	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/youtube
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/github
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit/_locales
488	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/reddit
32	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher/twitch
1576	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards/publisher
1576	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_rewards
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_talk/confabs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts/brave_talk
1584	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1/scripts
1640	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142/1
1648	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.142
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter/_locales
496	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitter
32	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/vimeo
48	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/youtube
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/github
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit/_locales
488	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/reddit
32	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher/twitch
1576	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards/publisher
1576	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_rewards
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_talk/confabs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts/brave_talk
1584	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1/scripts
1640	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143/1
1648	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.143
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter/_locales
496	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitter
32	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/vimeo
48	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/youtube
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/github
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit/_locales
488	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/reddit
32	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher/twitch
1576	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards/publisher
1576	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_rewards
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_talk/confabs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts/brave_talk
1584	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1/scripts
1640	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141/1
1648	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.141
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter/_locales
496	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitter
32	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/vimeo
48	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/youtube
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/github
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit/_locales
488	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/reddit
32	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher/twitch
1576	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards/publisher
1576	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_rewards
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_talk/confabs
8	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts/brave_talk
1584	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1/scripts
1640	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137/1
1648	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal/1.0.137
6592	./Library/Application Support/BraveSoftware/Brave-Browser/afalakplffnnnlkncjhbmahjfjhmlkal
4680	./Library/Application Support/BraveSoftware/Brave-Browser/gccbbckogglekeggclmmekihdgdpdgoe/1.0.804
2056	./Library/Application Support/BraveSoftware/Brave-Browser/gccbbckogglekeggclmmekihdgdpdgoe/1.0.810
1544	./Library/Application Support/BraveSoftware/Brave-Browser/gccbbckogglekeggclmmekihdgdpdgoe/1.0.809
2744	./Library/Application Support/BraveSoftware/Brave-Browser/gccbbckogglekeggclmmekihdgdpdgoe/1.0.808
11024	./Library/Application Support/BraveSoftware/Brave-Browser/gccbbckogglekeggclmmekihdgdpdgoe
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQXFfn5/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQXFfn5
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirylEp8w/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirylEp8w
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirWhio2x/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirWhio2x
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirnvapCE/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirnvapCE
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJudrWH/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJudrWH
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirKqHloO/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirKqHloO
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYVIjb2/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYVIjb2
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir8OYdk0/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir8OYdk0
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirG8R68y/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirG8R68y
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirGyjo6C/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirGyjo6C
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirLDAQxy/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirLDAQxy
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir3nQrqf/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir3nQrqf
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirbp7eNP/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirbp7eNP
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirD5R7nN/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirD5R7nN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir2cIU7a/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir2cIU7a
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir7V56cP/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir7V56cP
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diraNl95W/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diraNl95W
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxbaNM5
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4PlUUx
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJJpSio/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJJpSio
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirbpXhFA/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirbpXhFA
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirwHohF2/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirwHohF2
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diremxDWU/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diremxDWU
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir8gb2VU/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir8gb2VU
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirspHgPW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir5EwFmd/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir5EwFmd
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_direombCE/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_direombCE
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpEH4YZ/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpEH4YZ
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirfbTMdo/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirfbTMdo
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirdiCNtQ/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirdiCNtQ
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirNePAri/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirNePAri
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAoVDJ6/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAoVDJ6
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5/_locales
472	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirydu4T5
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diraN0rfA/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diraN0rfA
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirKRp2Md/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirKRp2Md
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirRzr5wA/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirRzr5wA
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrIBmxD/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrIBmxD
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirM4FTvL/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirM4FTvL
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq6iomz/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq6iomz
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirt1jN6Y/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirt1jN6Y
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpeY6OF/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpeY6OF
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirtSnRHR/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirtSnRHR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirLgqrxt/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirLgqrxt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirqIncNk/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirqIncNk
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirq4OwtT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4SaLvL/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4SaLvL
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirpKlTAF
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirlevpgh/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirlevpgh
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJnWLHA
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirinhnAv
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr/_locales
472	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBYDUBr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diro8I3Hd/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diro8I3Hd
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirUXIbgs/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirUXIbgs
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroH1zgk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirVQ7hhG/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirVQ7hhG
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirI09I3N
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirCGTCyy/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirCGTCyy
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirVFn6Hv/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirVFn6Hv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirVDREfv/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirVDREfv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir8inKk8/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir8inKk8
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirhByo4e/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirhByo4e
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirPmEUvt/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirPmEUvt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirwQqoy7/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirwQqoy7
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQpz0cH/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQpz0cH
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_direM9j6s/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_direM9j6s
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirV2yWUg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroejZpD/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_diroejZpD
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAbWqsv/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAbWqsv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirR8ZCaC/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirR8ZCaC
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirl4ELZH/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirl4ELZH
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirhLofMk/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirhLofMk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQRxLyv/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQRxLyv
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3/_locales
472	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYeqfH3
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirD5e6BB/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirD5e6BB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir1UnWei/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir1UnWei
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirzMBxEH/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirzMBxEH
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir9ysW0I/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir9ysW0I
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirhVoKU7/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirhVoKU7
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4jHSwv/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir4jHSwv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir9aIUoE/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir9aIUoE
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir3vBuxF/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir3vBuxF
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirCyboO5/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirCyboO5
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZcRWyX/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZcRWyX
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_direybNoo/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_direybNoo
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirQg6Jcm
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirO4kApJ
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirMrbfVn/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirMrbfVn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir2HKt71/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir2HKt71
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirNBvdeO/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirNBvdeO
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirtCZV5v/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirtCZV5v
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E/_locales
472	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirXyat3E
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxJJgnC/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxJJgnC
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirhlwXTV/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirhlwXTV
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirzjoQXz/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirzjoQXz
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirx2h2iR/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirx2h2iR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxNQzaT/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirxNQzaT
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch/_locales
472	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirBUT3Ch
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirZIHSnN
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp/_locales
472	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJjR6Yp
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirX622Iv/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirX622Iv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirUlaFaD/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirUlaFaD
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirkGcJCx/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirkGcJCx
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh/_locales
480	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAEqrwh
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirLW4ZKq/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirLW4ZKq
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir0RPAWp/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir0RPAWp
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirc7G70v/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirc7G70v
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir6uicmC/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dir6uicmC
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAv2Kbi/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirAv2Kbi
16	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_metadata
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/sl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/sk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/sw
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/pl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/vi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/sv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/he
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/ms
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/en_US
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/am
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/da
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/mr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/no
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/gu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/pt_BR
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/ja
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/el
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/lv
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/it
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/ca
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/zh_TW
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/cs
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/te
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/pt_PT
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/ru
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/ro
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/zh_CN
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/uk
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/sr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/en_GB
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/ml
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/es_419
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/kn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/ar
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/hr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/hu
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/nl
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/bg
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/bn
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/fil
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/hi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/de
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/ko
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/fi
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/id
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/fr
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/es
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/et
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/fa
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/lt
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/ta
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/th
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales/tr
424	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb/_locales
472	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirrqEhvb
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJmM0Lb/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirJmM0Lb
8	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYn8ZfL/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp/scoped_dirYn8ZfL
13088	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion/Temp
13088	./Library/Application Support/BraveSoftware/Brave-Browser/Greaselion
8	./Library/Application Support/BraveSoftware/Brave-Browser/SSLErrorAssistant/7/_metadata
32	./Library/Application Support/BraveSoftware/Brave-Browser/SSLErrorAssistant/7
32	./Library/Application Support/BraveSoftware/Brave-Browser/SSLErrorAssistant
1096	./Library/Application Support/BraveSoftware/Brave-Browser/ShaderCache/GPUCache
1096	./Library/Application Support/BraveSoftware/Brave-Browser/ShaderCache
0	./Library/Application Support/BraveSoftware/Brave-Browser/Default/blob_storage/483e5f4b-d805-43ad-88ea-264fa9e244f6
0	./Library/Application Support/BraveSoftware/Brave-Browser/Default/blob_storage
144	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Session Storage
32	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Platform Notifications
584	./Library/Application Support/BraveSoftware/Brave-Browser/Default/GPUCache
0	./Library/Application Support/BraveSoftware/Brave-Browser/Default/IndexedDB
32	./Library/Application Support/BraveSoftware/Brave-Browser/Default/GCM Store/Encryption
32	./Library/Application Support/BraveSoftware/Brave-Browser/Default/GCM Store
56	./Library/Application Support/BraveSoftware/Brave-Browser/Default/databases
0	./Library/Application Support/BraveSoftware/Brave-Browser/Default/VideoDecodeStats
0	./Library/Application Support/BraveSoftware/Brave-Browser/Default/AutofillStrikeDatabase
48	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Site Characteristics Database
40	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Extension Scripts
32	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Extension Rules
0	./Library/Application Support/BraveSoftware/Brave-Browser/Default/coupon_db
0	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Download Service/Files
0	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Download Service/EntryDB
0	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Download Service
56	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Service Worker/Database
0	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Service Worker/CacheStorage
8	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Service Worker/ScriptCache/index-dir
16	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Service Worker/ScriptCache
72	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Service Worker
0	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Feature Engagement Tracker/EventDB
0	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Feature Engagement Tracker/AvailabilityDB
0	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Feature Engagement Tracker
800	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Extension State
0	./Library/Application Support/BraveSoftware/Brave-Browser/Default/BudgetDatabase
1752	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Sessions
40	./Library/Application Support/BraveSoftware/Brave-Browser/Default/shared_proto_db/metadata
104	./Library/Application Support/BraveSoftware/Brave-Browser/Default/shared_proto_db
32	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Local Extension Settings/jidkidbbcafjabdphckchenhfomhnfma
40	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Local Extension Settings/mnojpmjdmbbfmejpflffifhffcmidifd
72	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Local Extension Settings
40	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Sync Data/LevelDB
40	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Sync Data
536	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Local Storage/leveldb
536	./Library/Application Support/BraveSoftware/Brave-Browser/Default/Local Storage
87040	./Library/Application Support/BraveSoftware/Brave-Browser/Default
8	./Library/Application Support/BraveSoftware/Brave-Browser/SafetyTips/2816/_metadata
152	./Library/Application Support/BraveSoftware/Brave-Browser/SafetyTips/2816
8	./Library/Application Support/BraveSoftware/Brave-Browser/SafetyTips/2814/_metadata
152	./Library/Application Support/BraveSoftware/Brave-Browser/SafetyTips/2814
8	./Library/Application Support/BraveSoftware/Brave-Browser/SafetyTips/2813/_metadata
152	./Library/Application Support/BraveSoftware/Brave-Browser/SafetyTips/2813
456	./Library/Application Support/BraveSoftware/Brave-Browser/SafetyTips
8	./Library/Application Support/BraveSoftware/Brave-Browser/MEIPreload/1.0.7.1642025427/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/MEIPreload/1.0.7.1642025427
40	./Library/Application Support/BraveSoftware/Brave-Browser/MEIPreload
8	./Library/Application Support/BraveSoftware/Brave-Browser/FileTypePolicies/50/_metadata
40	./Library/Application Support/BraveSoftware/Brave-Browser/FileTypePolicies/50
40	./Library/Application Support/BraveSoftware/Brave-Browser/FileTypePolicies
8	./Library/Application Support/BraveSoftware/Brave-Browser/AutofillRegex/2021.8.17.1300/_metadata
216	./Library/Application Support/BraveSoftware/Brave-Browser/AutofillRegex/2021.8.17.1300
216	./Library/Application Support/BraveSoftware/Brave-Browser/AutofillRegex
5472	./Library/Application Support/BraveSoftware/Brave-Browser/oofiananboodjbbmdelgdommihjbkfag/1.0.93/6.0/httpse.leveldb
7568	./Library/Application Support/BraveSoftware/Brave-Browser/oofiananboodjbbmdelgdommihjbkfag/1.0.93/6.0
7576	./Library/Application Support/BraveSoftware/Brave-Browser/oofiananboodjbbmdelgdommihjbkfag/1.0.93
5472	./Library/Application Support/BraveSoftware/Brave-Browser/oofiananboodjbbmdelgdommihjbkfag/1.0.94/6.0/httpse.leveldb
7568	./Library/Application Support/BraveSoftware/Brave-Browser/oofiananboodjbbmdelgdommihjbkfag/1.0.94/6.0
7576	./Library/Application Support/BraveSoftware/Brave-Browser/oofiananboodjbbmdelgdommihjbkfag/1.0.94
15152	./Library/Application Support/BraveSoftware/Brave-Browser/oofiananboodjbbmdelgdommihjbkfag
6128	./Library/Application Support/BraveSoftware/Brave-Browser/cffkpbalmllkdoenhmdmpbkajipdjfam/1.0.1296
6144	./Library/Application Support/BraveSoftware/Brave-Browser/cffkpbalmllkdoenhmdmpbkajipdjfam/1.0.1302
6144	./Library/Application Support/BraveSoftware/Brave-Browser/cffkpbalmllkdoenhmdmpbkajipdjfam/1.0.1303
6152	./Library/Application Support/BraveSoftware/Brave-Browser/cffkpbalmllkdoenhmdmpbkajipdjfam/1.0.1304
24568	./Library/Application Support/BraveSoftware/Brave-Browser/cffkpbalmllkdoenhmdmpbkajipdjfam
8	./Library/Application Support/BraveSoftware/Brave-Browser/Crowd Deny/2022.5.9.1141/_metadata
56	./Library/Application Support/BraveSoftware/Brave-Browser/Crowd Deny/2022.5.9.1141
8	./Library/Application Support/BraveSoftware/Brave-Browser/Crowd Deny/2022.4.25.1142/_metadata
56	./Library/Application Support/BraveSoftware/Brave-Browser/Crowd Deny/2022.4.25.1142
112	./Library/Application Support/BraveSoftware/Brave-Browser/Crowd Deny
8	./Library/Application Support/BraveSoftware/Brave-Browser/PKIMetadata/250/_metadata
432	./Library/Application Support/BraveSoftware/Brave-Browser/PKIMetadata/250
432	./Library/Application Support/BraveSoftware/Brave-Browser/PKIMetadata
301840	./Library/Application Support/BraveSoftware/Brave-Browser
301840	./Library/Application Support/BraveSoftware
104	./Library/Application Support/Dock
1344	./Library/Application Support/com.apple.ProtectedCloudStorage
0	./Library/Application Support/com.apple.accounts.dom
446360	./Library/Application Support
0	./Library/Maps/ReportAProblem/Notifications
0	./Library/Maps/ReportAProblem
0	./Library/Maps
72	./Library/Assistant
du: ./Library/Autosave Information: Operation not permitted
64	./Library/Saved Application State/com.github.GitHubClient.savedState
48	./Library/Saved Application State/com.apple.keychainaccess.savedState
48	./Library/Saved Application State/org.mozilla.firefox.savedState
16	./Library/Saved Application State/com.apple.ScriptEditor2.savedState
160	./Library/Saved Application State/com.brave.Browser.savedState
56	./Library/Saved Application State/com.microsoft.VSCode.savedState
48	./Library/Saved Application State/com.apple.BluetoothFileExchange.savedState
160	./Library/Saved Application State/com.apple.finder.savedState
288	./Library/Saved Application State/com.apple.Terminal.savedState
888	./Library/Saved Application State
du: ./Library/IdentityServices: Operation not permitted
0	./Library/WebKit/com.apple.Music/WebsiteData/IndexedDB
0	./Library/WebKit/com.apple.Music/WebsiteData/MediaKeys
0	./Library/WebKit/com.apple.Music/WebsiteData/WebSQL
0	./Library/WebKit/com.apple.Music/WebsiteData/LocalStorage
0	./Library/WebKit/com.apple.Music/WebsiteData/ResourceLoadStatistics
0	./Library/WebKit/com.apple.Music/WebsiteData
0	./Library/WebKit/com.apple.Music
0	./Library/WebKit/Databases
0	./Library/WebKit/com.apple.Spotlight/WebsiteData/IndexedDB/v1
0	./Library/WebKit/com.apple.Spotlight/WebsiteData/IndexedDB
0	./Library/WebKit/com.apple.Spotlight/WebsiteData/MediaKeys
0	./Library/WebKit/com.apple.Spotlight/WebsiteData/WebSQL
0	./Library/WebKit/com.apple.Spotlight/WebsiteData/LocalStorage
0	./Library/WebKit/com.apple.Spotlight/WebsiteData/ResourceLoadStatistics
0	./Library/WebKit/com.apple.Spotlight/WebsiteData
0	./Library/WebKit/com.apple.Spotlight
0	./Library/WebKit/com.apple.BluetoothFileExchange/WebsiteData/IndexedDB/v1
0	./Library/WebKit/com.apple.BluetoothFileExchange/WebsiteData/IndexedDB
0	./Library/WebKit/com.apple.BluetoothFileExchange/WebsiteData/MediaKeys
0	./Library/WebKit/com.apple.BluetoothFileExchange/WebsiteData/WebSQL
0	./Library/WebKit/com.apple.BluetoothFileExchange/WebsiteData/LocalStorage
0	./Library/WebKit/com.apple.BluetoothFileExchange/WebsiteData/ResourceLoadStatistics
0	./Library/WebKit/com.apple.BluetoothFileExchange/WebsiteData
0	./Library/WebKit/com.apple.BluetoothFileExchange
0	./Library/WebKit
8	./Library/Calendars/41109866-03F6-42DA-9D43-C4CAD9DA9C2D.group
16	./Library/Calendars/AB9D93EA-110D-429A-8644-AC75A9E37A69.calendar/LocalDefaultAlarms
0	./Library/Calendars/AB9D93EA-110D-429A-8644-AC75A9E37A69.calendar/Events
24	./Library/Calendars/AB9D93EA-110D-429A-8644-AC75A9E37A69.calendar
0	./Library/Calendars/Calendar Sync Changes
16	./Library/Calendars/7B664D93-8907-423A-8FD5-11EBFC0BB620.calendar/LocalDefaultAlarms
8	./Library/Calendars/7B664D93-8907-423A-8FD5-11EBFC0BB620.calendar/Events
32	./Library/Calendars/7B664D93-8907-423A-8FD5-11EBFC0BB620.calendar
16	./Library/Calendars/61D487D8-7BB4-433F-B74B-9C7CD63B5ABE.calendar/LocalDefaultAlarms
0	./Library/Calendars/61D487D8-7BB4-433F-B74B-9C7CD63B5ABE.calendar/Events
24	./Library/Calendars/61D487D8-7BB4-433F-B74B-9C7CD63B5ABE.calendar
16	./Library/Calendars/C336F5CB-413E-41C7-B91A-62B239C6E49C.calendar/LocalDefaultAlarms
0	./Library/Calendars/C336F5CB-413E-41C7-B91A-62B239C6E49C.calendar/Events
24	./Library/Calendars/C336F5CB-413E-41C7-B91A-62B239C6E49C.calendar
16	./Library/Calendars/30C1A768-15D0-496C-908B-1F41E78E8CD6.calendar/LocalDefaultAlarms
0	./Library/Calendars/30C1A768-15D0-496C-908B-1F41E78E8CD6.calendar/Events
24	./Library/Calendars/30C1A768-15D0-496C-908B-1F41E78E8CD6.calendar
16	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/AB9D93EA-110D-429A-8644-AC75A9E37A69.calendar/LocalDefaultAlarms
0	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/AB9D93EA-110D-429A-8644-AC75A9E37A69.calendar/Events
24	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/AB9D93EA-110D-429A-8644-AC75A9E37A69.calendar
16	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/ADA4F1A3-F2AE-45EB-A3E4-F71EFDAA1423.calendar/LocalDefaultAlarms
0	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/ADA4F1A3-F2AE-45EB-A3E4-F71EFDAA1423.calendar/Events
24	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/ADA4F1A3-F2AE-45EB-A3E4-F71EFDAA1423.calendar
16	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/1EE133D1-E4DA-442B-A70D-4B81F5739EE5.calendar/LocalDefaultAlarms
0	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/1EE133D1-E4DA-442B-A70D-4B81F5739EE5.calendar/Events
24	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/1EE133D1-E4DA-442B-A70D-4B81F5739EE5.calendar
16	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/C6CF4A9B-5EBE-4124-AE41-7E29778C42E1.calendar/LocalDefaultAlarms
0	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/C6CF4A9B-5EBE-4124-AE41-7E29778C42E1.calendar/Events
24	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/C6CF4A9B-5EBE-4124-AE41-7E29778C42E1.calendar
16	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/61D487D8-7BB4-433F-B74B-9C7CD63B5ABE.calendar/LocalDefaultAlarms
0	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/61D487D8-7BB4-433F-B74B-9C7CD63B5ABE.calendar/Events
24	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/61D487D8-7BB4-433F-B74B-9C7CD63B5ABE.calendar
16	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/C85B803D-6E81-4CF7-8CDA-9FC7A425A343.calendar/LocalDefaultAlarms
0	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/C85B803D-6E81-4CF7-8CDA-9FC7A425A343.calendar/Events
24	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars/C85B803D-6E81-4CF7-8CDA-9FC7A425A343.calendar
144	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu/Calendars
152	./Library/Calendars/Calendars and Reminders 4.25.22, 8.06 AM.icbu
16	./Library/Calendars/80EF9384-AA83-4BC4-A30D-CD1106486C32.calendar/LocalDefaultAlarms
0	./Library/Calendars/80EF9384-AA83-4BC4-A30D-CD1106486C32.calendar/Events
24	./Library/Calendars/80EF9384-AA83-4BC4-A30D-CD1106486C32.calendar
2304	./Library/Calendars
208	./Library/Preferences/ByHost
8	./Library/Preferences/com.apple.LaunchServices
16	./Library/Preferences/com.apple.VoiceOver4
1992	./Library/Preferences
0	./Library/studentd/Container/Library
0	./Library/studentd/Container
16	./Library/studentd/Events
24	./Library/studentd
du: ./Library/Messages: Operation not permitted
du: ./Library/HomeKit: Operation not permitted
11464	./Library/Keychains/1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/Analytics
23784	./Library/Keychains/1B348CA3-008C-5B19-8C92-0FBCB5C1B65F
24120	./Library/Keychains
du: ./Library/Sharing: Operation not permitted
0	./Library/ColorPickers
0	./Library/Application Scripts/com.apple.CloudPhotosConfiguration
0	./Library/Application Scripts/com.apple.iCal.CalendarNC
0	./Library/Application Scripts/com.apple.languageassetd
0	./Library/Application Scripts/maccatalyst.com.frontrow.vlog
0	./Library/Application Scripts/com.apple.archiveutility
0	./Library/Application Scripts/com.apple.FaceTime
0	./Library/Application Scripts/com.apple.ScreenTimeAgent
0	./Library/Application Scripts/com.apple.calculator
0	./Library/Application Scripts/com.apple.photos.ImageConversionService
0	./Library/Application Scripts/com.apple.FaceTime.FaceTimeNotificationCenterService
0	./Library/Application Scripts/com.apple.ncplugin.weather
0	./Library/Application Scripts/com.apple.preferences.sharing.SharingBluetoothService
0	./Library/Application Scripts/com.apple.quicklook.QuickLookUIService
0	./Library/Application Scripts/com.apple.contacts.donation-agent
0	./Library/Application Scripts/com.apple.photolibraryd
0	./Library/Application Scripts/com.apple.siri.media-indexer
0	./Library/Application Scripts/com.apple.CryptoTokenKit.setoken
0	./Library/Application Scripts/com.apple.BKAgentService
0	./Library/Application Scripts/com.apple.LookupViewService
0	./Library/Application Scripts/com.apple.AMPDeviceDiscoveryAgent
0	./Library/Application Scripts/com.apple.CalendarNotification.CalNCService
0	./Library/Application Scripts/com.apple.podcasts.MacPodcastsStorageExtension
0	./Library/Application Scripts/com.apple.Safari.BrowserDataImportingService
0	./Library/Application Scripts/com.apple.Safari
0	./Library/Application Scripts/com.apple.CloudDocsDaemon.StorageManagement
0	./Library/Application Scripts/com.apple.Safari.CacheDeleteExtension
0	./Library/Application Scripts/com.apple.AddressBook.ContactsAccountsService
0	./Library/Application Scripts/com.apple.ncplugin.stocks
0	./Library/Application Scripts/com.apple.AMPArtworkAgent
0	./Library/Application Scripts/com.apple.iBooksX.DiskSpaceEfficiency
0	./Library/Application Scripts/com.apple.messages.StorageManagementExtension
0	./Library/Application Scripts/com.microsoft.Word
0	./Library/Application Scripts/com.apple.STMExtension.AppleInternal
0	./Library/Application Scripts/com.apple.preferencepane.security.AdvertisingExtension
0	./Library/Application Scripts/com.apple.STMExtension.CloudFiles
0	./Library/Application Scripts/com.apple.STMExtension.OtherUsers
0	./Library/Application Scripts/com.apple.photoanalysisd
0	./Library/Application Scripts/com.apple.amp.devicesui
0	./Library/Application Scripts/com.apple.MediaLibraryService
0	./Library/Application Scripts/com.apple.iChat
0	./Library/Application Scripts/com.apple.CloudDocs.MobileDocumentsFileProvider
0	./Library/Application Scripts/com.apple.TV.TVStorageExtension
0	./Library/Application Scripts/com.duckduckgo.macos.PrivacyEssentials.ContentBlockerExtension
0	./Library/Application Scripts/com.apple.DataDetectorsLocalSources
0	./Library/Application Scripts/com.askvideo.AOM000836
0	./Library/Application Scripts/com.apple.Photos
0	./Library/Application Scripts/com.apple.ContactsAgent
0	./Library/Application Scripts/com.apple.Music.MusicCacheExtension
0	./Library/Application Scripts/com.apple.AppStore
0	./Library/Application Scripts/com.apple.Notes
0	./Library/Application Scripts/com.apple.STMExtension.Trash
0	./Library/Application Scripts/com.apple.MailCacheDelete
0	./Library/Application Scripts/com.apple.STMExtension.iOSFiles
0	./Library/Application Scripts/com.apple.STMExtension.Applications
0	./Library/Application Scripts/com.apple.Dictionary
0	./Library/Application Scripts/com.apple.TextEdit
0	./Library/Application Scripts/com.apple.CryptoTokenKit.pivtoken
0	./Library/Application Scripts/com.apple.Music.MusicStorageExtension
0	./Library/Application Scripts/com.apple.Photos.StorageManagementExtension
0	./Library/Application Scripts/com.apple.geod
0	./Library/Application Scripts/com.apple.TV.TVCacheExtension
0	./Library/Application Scripts/com.apple.CalendarAgent
0	./Library/Application Scripts/com.apple.Safari.SafariQuickLookPreview
0	./Library/Application Scripts/com.apple.preferencepane.security.PrivacyAnalytics
0	./Library/Application Scripts/com.apple.DataDetectorsViewService
0	./Library/Application Scripts/com.apple.STMExtension.Mail
0	./Library/Application Scripts/com.apple.AppleMediaServicesUI.SpyglassPurchases
0	./Library/Application Scripts/com.apple.routined
0	./Library/Application Scripts/com.apple.corerecents.recentsd
0	./Library/Application Scripts/com.apple.STMExtension.GarageBand
0	./Library/Application Scripts/com.apple.Preview
0	./Library/Application Scripts/com.apple.UsageTrackingAgent
0	./Library/Application Scripts/com.apple.accessibility.mediaaccessibilityd
0	./Library/Application Scripts/com.apple.quicklook.ui.helper
0	./Library/Application Scripts/com.apple.AirPlayUIAgent
0	./Library/Application Scripts/com.apple.preferences.sharing.SharingPrefsExtension
0	./Library/Application Scripts/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension
0	./Library/Application Scripts/com.apple.Notes.QuickLookExtension
0	./Library/Application Scripts/com.apple.mediaanalysisd
0	./Library/Application Scripts/com.duckduckgo.macos.PrivacyEssentials
0	./Library/Application Scripts/com.apple.SocialPushAgent
0	./Library/Application Scripts
0	./Library/Assistants
du: ./Library/Mail: Operation not permitted
8	./Library/UIKitSystem
0	./Library/Compositions
0	./Library/GameKit
40	./Library/LanguageModeling/en-dynamic.lm
40	./Library/LanguageModeling
0	./Library/Favorites
0	./Library/Passes/Receipts
0	./Library/Passes/Cards
1192	./Library/Passes
0	./Library/com.apple.icloud.searchpartyd
0	./Library/SafariSandboxBroker
48	./Library/FontCollections
0	./Library/Sounds
264	./Library/com.apple.internal.ck
64	./Library/Printers/Ink.app/Contents/_CodeSignature
64	./Library/Printers/Ink.app/Contents/MacOS
16	./Library/Printers/Ink.app/Contents/Resources/de.lproj
16	./Library/Printers/Ink.app/Contents/Resources/he.lproj
16	./Library/Printers/Ink.app/Contents/Resources/en_AU.lproj
16	./Library/Printers/Ink.app/Contents/Resources/ar.lproj
16	./Library/Printers/Ink.app/Contents/Resources/el.lproj
16	./Library/Printers/Ink.app/Contents/Resources/ja.lproj
8	./Library/Printers/Ink.app/Contents/Resources/en.lproj
16	./Library/Printers/Ink.app/Contents/Resources/uk.lproj
16	./Library/Printers/Ink.app/Contents/Resources/es_419.lproj
16	./Library/Printers/Ink.app/Contents/Resources/zh_CN.lproj
16	./Library/Printers/Ink.app/Contents/Resources/es.lproj
16	./Library/Printers/Ink.app/Contents/Resources/da.lproj
16	./Library/Printers/Ink.app/Contents/Resources/it.lproj
16	./Library/Printers/Ink.app/Contents/Resources/sk.lproj
16	./Library/Printers/Ink.app/Contents/Resources/pt_PT.lproj
16	./Library/Printers/Ink.app/Contents/Resources/ms.lproj
16	./Library/Printers/Ink.app/Contents/Resources/sv.lproj
16	./Library/Printers/Ink.app/Contents/Resources/cs.lproj
16	./Library/Printers/Ink.app/Contents/Resources/ko.lproj
32	./Library/Printers/Ink.app/Contents/Resources/Base.lproj
16	./Library/Printers/Ink.app/Contents/Resources/no.lproj
16	./Library/Printers/Ink.app/Contents/Resources/hu.lproj
16	./Library/Printers/Ink.app/Contents/Resources/zh_HK.lproj
16	./Library/Printers/Ink.app/Contents/Resources/tr.lproj
16	./Library/Printers/Ink.app/Contents/Resources/pl.lproj
16	./Library/Printers/Ink.app/Contents/Resources/zh_TW.lproj
16	./Library/Printers/Ink.app/Contents/Resources/en_GB.lproj
16	./Library/Printers/Ink.app/Contents/Resources/vi.lproj
16	./Library/Printers/Ink.app/Contents/Resources/ru.lproj
16	./Library/Printers/Ink.app/Contents/Resources/fr_CA.lproj
16	./Library/Printers/Ink.app/Contents/Resources/fr.lproj
16	./Library/Printers/Ink.app/Contents/Resources/fi.lproj
16	./Library/Printers/Ink.app/Contents/Resources/id.lproj
16	./Library/Printers/Ink.app/Contents/Resources/nl.lproj
16	./Library/Printers/Ink.app/Contents/Resources/th.lproj
16	./Library/Printers/Ink.app/Contents/Resources/pt.lproj
16	./Library/Printers/Ink.app/Contents/Resources/ro.lproj
16	./Library/Printers/Ink.app/Contents/Resources/hr.lproj
16	./Library/Printers/Ink.app/Contents/Resources/hi.lproj
16	./Library/Printers/Ink.app/Contents/Resources/ca.lproj
832	./Library/Printers/Ink.app/Contents/Resources
984	./Library/Printers/Ink.app/Contents
984	./Library/Printers/Ink.app
984	./Library/Printers
4552	./Library/SyncedPreferences/com.apple.kvs
5352	./Library/SyncedPreferences
0	./Library/Audio/Plug-Ins/VST
0	./Library/Audio/Plug-Ins/Digidesign
0	./Library/Audio/Plug-Ins/Components
0	./Library/Audio/Plug-Ins
0	./Library/Audio/MIDI Drivers
0	./Library/Audio/Sounds/Alerts
0	./Library/Audio/Sounds/Banks
0	./Library/Audio/Sounds
0	./Library/Audio
0	./Library/Keyboard Layouts
0	./Library/Logs/Assistant/Analytics
0	./Library/Logs/Assistant
32	./Library/Logs/SMSMigrator
0	./Library/Logs/DiagnosticReports/Retired
0	./Library/Logs/DiagnosticReports
0	./Library/Logs/Homebrew/hwloc
0	./Library/Logs/Homebrew/jansson
0	./Library/Logs/Homebrew/wget
0	./Library/Logs/Homebrew/git-gui
0	./Library/Logs/Homebrew/libidn2
0	./Library/Logs/Homebrew/libmagic
0	./Library/Logs/Homebrew/docker
0	./Library/Logs/Homebrew/go
0	./Library/Logs/Homebrew/gdbm
0	./Library/Logs/Homebrew/mpdecimal
0	./Library/Logs/Homebrew/libunistring
0	./Library/Logs/Homebrew/readline
0	./Library/Logs/Homebrew/protobuf-c
0	./Library/Logs/Homebrew/volatility
0	./Library/Logs/Homebrew/yara
0	./Library/Logs/Homebrew/sqlite
0	./Library/Logs/Homebrew/xz
0	./Library/Logs/Homebrew/gperftools
0	./Library/Logs/Homebrew/jsonschema
0	./Library/Logs/Homebrew/ca-certificates
0	./Library/Logs/Homebrew/gettext
0	./Library/Logs/Homebrew/luajit-openresty
0	./Library/Logs/Homebrew/snort
0	./Library/Logs/Homebrew/tcl-tk
0	./Library/Logs/Homebrew/oniguruma
0	./Library/Logs/Homebrew/pcre2
0	./Library/Logs/Homebrew/openssl@1.1
0	./Library/Logs/Homebrew/brew-gem
0	./Library/Logs/Homebrew/pcre
16	./Library/Logs/Homebrew/python@3.10
0	./Library/Logs/Homebrew/daq
0	./Library/Logs/Homebrew/six
0	./Library/Logs/Homebrew/nmap
0	./Library/Logs/Homebrew/jq
0	./Library/Logs/Homebrew/libdnet
0	./Library/Logs/Homebrew/libusb
0	./Library/Logs/Homebrew/protobuf
0	./Library/Logs/Homebrew/git
0	./Library/Logs/Homebrew/python-yq
0	./Library/Logs/Homebrew/hyperscan
16	./Library/Logs/Homebrew/python@3.9
0	./Library/Logs/Homebrew/libpcap
32	./Library/Logs/Homebrew
104	./Library/Logs/DeviceLink
0	./Library/Logs/CrashReporter/MobileDevice
0	./Library/Logs/CrashReporter
0	./Library/Logs/Baseband
8	./Library/Logs/com.apple.AMPLibraryAgent/iTunes Migration
8	./Library/Logs/com.apple.AMPLibraryAgent
0	./Library/Logs/GitHub Desktop
16	./Library/Logs/Sync
208	./Library/Logs
0	./Library/Internet Plug-Ins
160	./Library/FrontBoard
8	./Library/News
512	./Library/Accounts/VerifiedBackup
1928	./Library/Accounts
du: ./Library/Safari: Operation not permitted
0	./Library/Colors
0	./Library/MediaStream/mmcs
0	./Library/MediaStream/sub
0	./Library/MediaStream/del
0	./Library/MediaStream/pub
336	./Library/MediaStream/albumshare
0	./Library/MediaStream/perf
0	./Library/MediaStream/share
336	./Library/MediaStream
0	./Library/PreferencePanes
0	./Library/Mobile Documents
du: ./Library/Suggestions: Operation not permitted
0	./Library/Group Containers/group.com.duckduckgo.Statistics/Library/Application Support
8	./Library/Group Containers/group.com.duckduckgo.Statistics/Library/Preferences
0	./Library/Group Containers/group.com.duckduckgo.Statistics/Library/Caches
8	./Library/Group Containers/group.com.duckduckgo.Statistics/Library
8	./Library/Group Containers/group.com.duckduckgo.Statistics
0	./Library/Group Containers/UBF8T346G9.OfficeOsfWebHost/Library/Application Support
0	./Library/Group Containers/UBF8T346G9.OfficeOsfWebHost/Library/Preferences
0	./Library/Group Containers/UBF8T346G9.OfficeOsfWebHost/Library/Caches
0	./Library/Group Containers/UBF8T346G9.OfficeOsfWebHost/Library
0	./Library/Group Containers/UBF8T346G9.OfficeOsfWebHost
0	./Library/Group Containers/group.com.apple.stocks/Library/Application Support
0	./Library/Group Containers/group.com.apple.stocks/Library/Preferences
8	./Library/Group Containers/group.com.apple.stocks/Library/Documents/PrivateData
8	./Library/Group Containers/group.com.apple.stocks/Library/Documents
0	./Library/Group Containers/group.com.apple.stocks/Library/Caches
8	./Library/Group Containers/group.com.apple.stocks/Library
8	./Library/Group Containers/group.com.apple.stocks
0	./Library/Group Containers/group.com.duckduckgo.TrackerData/Library/Application Support
8	./Library/Group Containers/group.com.duckduckgo.TrackerData/Library/Preferences
0	./Library/Group Containers/group.com.duckduckgo.TrackerData/Library/Caches
8	./Library/Group Containers/group.com.duckduckgo.TrackerData/Library
3456	./Library/Group Containers/group.com.duckduckgo.TrackerData
0	./Library/Group Containers/group.com.duckduckgo.BlockerList/Library/Application Support
0	./Library/Group Containers/group.com.duckduckgo.BlockerList/Library/Preferences
0	./Library/Group Containers/group.com.duckduckgo.BlockerList/Library/Caches
0	./Library/Group Containers/group.com.duckduckgo.BlockerList/Library
6408	./Library/Group Containers/group.com.duckduckgo.BlockerList
0	./Library/Group Containers/group.com.apple.notes.import/Library/Application Support
0	./Library/Group Containers/group.com.apple.notes.import/Library/Preferences
0	./Library/Group Containers/group.com.apple.notes.import/Library/Caches
0	./Library/Group Containers/group.com.apple.notes.import/Library
0	./Library/Group Containers/group.com.apple.notes.import
48	./Library/Group Containers/UBF8T346G9.Office/Licenses/5
48	./Library/Group Containers/UBF8T346G9.Office/Licenses
1032	./Library/Group Containers/UBF8T346G9.Office/FontCache/4/Catalog
3704	./Library/Group Containers/UBF8T346G9.Office/FontCache/4/PreviewFont
4736	./Library/Group Containers/UBF8T346G9.Office/FontCache/4
4736	./Library/Group Containers/UBF8T346G9.Office/FontCache
0	./Library/Group Containers/UBF8T346G9.Office/Library/Application Support
0	./Library/Group Containers/UBF8T346G9.Office/Library/Preferences
0	./Library/Group Containers/UBF8T346G9.Office/Library/Caches
0	./Library/Group Containers/UBF8T346G9.Office/Library
240	./Library/Group Containers/UBF8T346G9.Office/User Content.localized/Proofing Tools.localized/.localized
240	./Library/Group Containers/UBF8T346G9.Office/User Content.localized/Proofing Tools.localized
240	./Library/Group Containers/UBF8T346G9.Office/User Content.localized/Startup.localized/.localized
0	./Library/Group Containers/UBF8T346G9.Office/User Content.localized/Startup.localized/Word
240	./Library/Group Containers/UBF8T346G9.Office/User Content.localized/Startup.localized
240	./Library/Group Containers/UBF8T346G9.Office/User Content.localized/Templates.localized/.localized
296	./Library/Group Containers/UBF8T346G9.Office/User Content.localized/Templates.localized
240	./Library/Group Containers/UBF8T346G9.Office/User Content.localized/.localized
1016	./Library/Group Containers/UBF8T346G9.Office/User Content.localized
4240	./Library/Group Containers/UBF8T346G9.Office/ComRPC32
1024	./Library/Group Containers/UBF8T346G9.Office/MicrosoftRegistrationDB
11168	./Library/Group Containers/UBF8T346G9.Office
16	./Library/Group Containers/UBF8T346G9.ms/cloudPolicy
0	./Library/Group Containers/UBF8T346G9.ms/Library/Application Support
0	./Library/Group Containers/UBF8T346G9.ms/Library/Preferences
0	./Library/Group Containers/UBF8T346G9.ms/Library/Caches
0	./Library/Group Containers/UBF8T346G9.ms/Library
0	./Library/Group Containers/UBF8T346G9.ms/MerpTempItems
16	./Library/Group Containers/UBF8T346G9.ms
0	./Library/Group Containers/group.com.apple.notes/Library/Application Support
8	./Library/Group Containers/group.com.apple.notes/Library/Preferences
0	./Library/Group Containers/group.com.apple.notes/Library/Caches
8	./Library/Group Containers/group.com.apple.notes/Library
1976	./Library/Group Containers/group.com.apple.notes
0	./Library/Group Containers/UBF8T346G9.OfficeOneDriveSyncIntegration/Library/Application Support
0	./Library/Group Containers/UBF8T346G9.OfficeOneDriveSyncIntegration/Library/Preferences
0	./Library/Group Containers/UBF8T346G9.OfficeOneDriveSyncIntegration/Library/Caches
0	./Library/Group Containers/UBF8T346G9.OfficeOneDriveSyncIntegration/Library
0	./Library/Group Containers/UBF8T346G9.OfficeOneDriveSyncIntegration
0	./Library/Group Containers/243LU875E5.groups.com.apple.podcasts/PodcastContentService/SyncToAppChangeSets
0	./Library/Group Containers/243LU875E5.groups.com.apple.podcasts/PodcastContentService
0	./Library/Group Containers/243LU875E5.groups.com.apple.podcasts/Documents
0	./Library/Group Containers/243LU875E5.groups.com.apple.podcasts
0	./Library/Group Containers/com.apple.messages/Library/Application Support
0	./Library/Group Containers/com.apple.messages/Library/Preferences
0	./Library/Group Containers/com.apple.messages/Library/Caches
0	./Library/Group Containers/com.apple.messages/Library
0	./Library/Group Containers/com.apple.messages
0	./Library/Group Containers/group.com.duckduckgo.TrustedSites/Library/Application Support
8	./Library/Group Containers/group.com.duckduckgo.TrustedSites/Library/Preferences
0	./Library/Group Containers/group.com.duckduckgo.TrustedSites/Library/Caches
8	./Library/Group Containers/group.com.duckduckgo.TrustedSites/Library
16	./Library/Group Containers/group.com.duckduckgo.TrustedSites
0	./Library/Group Containers/com.apple.PreviewLegacySignaturesConversion/Library/Application Support
8	./Library/Group Containers/com.apple.PreviewLegacySignaturesConversion/Library/Preferences
0	./Library/Group Containers/com.apple.PreviewLegacySignaturesConversion/Library/Caches
8	./Library/Group Containers/com.apple.PreviewLegacySignaturesConversion/Library
8	./Library/Group Containers/com.apple.PreviewLegacySignaturesConversion
0	./Library/Group Containers/group.com.duckduckgo.macos.PrivacyEssentials/Library/Application Support
0	./Library/Group Containers/group.com.duckduckgo.macos.PrivacyEssentials/Library/Preferences
0	./Library/Group Containers/group.com.duckduckgo.macos.PrivacyEssentials/Library/Caches
0	./Library/Group Containers/group.com.duckduckgo.macos.PrivacyEssentials/Library
0	./Library/Group Containers/group.com.duckduckgo.macos.PrivacyEssentials
0	./Library/Group Containers/com.apple.MessagesLegacyTransferArchive/Library/Application Support
0	./Library/Group Containers/com.apple.MessagesLegacyTransferArchive/Library/Preferences
0	./Library/Group Containers/com.apple.MessagesLegacyTransferArchive/Library/Caches
0	./Library/Group Containers/com.apple.MessagesLegacyTransferArchive/Library
0	./Library/Group Containers/com.apple.MessagesLegacyTransferArchive
23064	./Library/Group Containers
0	./Library/Dictionaries/CoreDataUbiquitySupport/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/UserDictionary/3AEE2120-2A8C-4DD6-994A-2B76158795EC/container/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/.stage.nosync/UserDictionary/SAlQVUhF7208e6_gvZx_zdKx1U1AzKGem3HO2pLKjgY=
0	./Library/Dictionaries/CoreDataUbiquitySupport/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/UserDictionary/3AEE2120-2A8C-4DD6-994A-2B76158795EC/container/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/.stage.nosync/UserDictionary
0	./Library/Dictionaries/CoreDataUbiquitySupport/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/UserDictionary/3AEE2120-2A8C-4DD6-994A-2B76158795EC/container/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/.stage.nosync
8	./Library/Dictionaries/CoreDataUbiquitySupport/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/UserDictionary/3AEE2120-2A8C-4DD6-994A-2B76158795EC/container/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/UserDictionary/SAlQVUhF7208e6_gvZx_zdKx1U1AzKGem3HO2pLKjgY=
8	./Library/Dictionaries/CoreDataUbiquitySupport/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/UserDictionary/3AEE2120-2A8C-4DD6-994A-2B76158795EC/container/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/UserDictionary
8	./Library/Dictionaries/CoreDataUbiquitySupport/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/UserDictionary/3AEE2120-2A8C-4DD6-994A-2B76158795EC/container/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F
8	./Library/Dictionaries/CoreDataUbiquitySupport/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/UserDictionary/3AEE2120-2A8C-4DD6-994A-2B76158795EC/container
88	./Library/Dictionaries/CoreDataUbiquitySupport/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/UserDictionary/3AEE2120-2A8C-4DD6-994A-2B76158795EC/store
96	./Library/Dictionaries/CoreDataUbiquitySupport/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/UserDictionary/3AEE2120-2A8C-4DD6-994A-2B76158795EC
96	./Library/Dictionaries/CoreDataUbiquitySupport/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F/UserDictionary
96	./Library/Dictionaries/CoreDataUbiquitySupport/horus~1B348CA3-008C-5B19-8C92-0FBCB5C1B65F
96	./Library/Dictionaries/CoreDataUbiquitySupport
96	./Library/Dictionaries
0	./Library/Containers/com.apple.CloudPhotosConfiguration/Data/Library/Application Support
0	./Library/Containers/com.apple.CloudPhotosConfiguration/Data/Library/Saved Application State
0	./Library/Containers/com.apple.CloudPhotosConfiguration/Data/Library/Preferences
0	./Library/Containers/com.apple.CloudPhotosConfiguration/Data/Library/Application Scripts
0	./Library/Containers/com.apple.CloudPhotosConfiguration/Data/Library/Images
0	./Library/Containers/com.apple.CloudPhotosConfiguration/Data/Library/Logs
0	./Library/Containers/com.apple.CloudPhotosConfiguration/Data/Library/Caches
0	./Library/Containers/com.apple.CloudPhotosConfiguration/Data/Library
0	./Library/Containers/com.apple.CloudPhotosConfiguration/Data/Documents
0	./Library/Containers/com.apple.CloudPhotosConfiguration/Data
56	./Library/Containers/com.apple.CloudPhotosConfiguration
0	./Library/Containers/com.apple.iCal.CalendarNC/Data/Library/Application Support
0	./Library/Containers/com.apple.iCal.CalendarNC/Data/Library/Saved Application State
0	./Library/Containers/com.apple.iCal.CalendarNC/Data/Library/Preferences
0	./Library/Containers/com.apple.iCal.CalendarNC/Data/Library/Application Scripts
0	./Library/Containers/com.apple.iCal.CalendarNC/Data/Library/Images
0	./Library/Containers/com.apple.iCal.CalendarNC/Data/Library/Logs
0	./Library/Containers/com.apple.iCal.CalendarNC/Data/Library/Caches
0	./Library/Containers/com.apple.iCal.CalendarNC/Data/Library
0	./Library/Containers/com.apple.iCal.CalendarNC/Data/Documents
0	./Library/Containers/com.apple.iCal.CalendarNC/Data
56	./Library/Containers/com.apple.iCal.CalendarNC
0	./Library/Containers/com.apple.languageassetd/Data/Library/Application Support
0	./Library/Containers/com.apple.languageassetd/Data/Library/Saved Application State
0	./Library/Containers/com.apple.languageassetd/Data/Library/Preferences
0	./Library/Containers/com.apple.languageassetd/Data/Library/Application Scripts
0	./Library/Containers/com.apple.languageassetd/Data/Library/Images
0	./Library/Containers/com.apple.languageassetd/Data/Library/Logs
8	./Library/Containers/com.apple.languageassetd/Data/Library/Caches/com.apple.DictionaryServices
8	./Library/Containers/com.apple.languageassetd/Data/Library/Caches
8	./Library/Containers/com.apple.languageassetd/Data/Library
0	./Library/Containers/com.apple.languageassetd/Data/Documents
8	./Library/Containers/com.apple.languageassetd/Data
48	./Library/Containers/com.apple.languageassetd
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Application Support/maccatalyst.com.frontrow.vlog/com.crashlytics
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Application Support/maccatalyst.com.frontrow.vlog/com.microsoft.appcenter/crasheslogbuffer
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Application Support/maccatalyst.com.frontrow.vlog/com.microsoft.appcenter/crashes
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Application Support/maccatalyst.com.frontrow.vlog/com.microsoft.appcenter
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Application Support/maccatalyst.com.frontrow.vlog
312	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Application Support/Google/Measurement
64	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Application Support/Google/RemoteConfig
16	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Application Support/Google/FIRApp
392	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Application Support/Google
440	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Application Support
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Saved Application State/maccatalyst.com.frontrow.vlog~iosmac.savedState/KnownSceneSessions
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Saved Application State/maccatalyst.com.frontrow.vlog~iosmac.savedState
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Saved Application State
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/WebKit/WebsiteData/IndexedDB
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/WebKit/WebsiteData/MediaKeys
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/WebKit/WebsiteData/WebSQL
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/WebKit/WebsiteData/LocalStorage
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/WebKit/WebsiteData/ResourceLoadStatistics
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/WebKit/WebsiteData
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/WebKit
88	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Preferences
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Application Scripts
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Images
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Logs
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Cookies
1176	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/maccatalyst.com.frontrow.vlog/fsCachedData
5448	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/maccatalyst.com.frontrow.vlog
16	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.crashlytics.data/maccatalyst.com.frontrow.vlog/v5/settings
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.crashlytics.data/maccatalyst.com.frontrow.vlog/v5/reports/prepared
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.crashlytics.data/maccatalyst.com.frontrow.vlog/v5/reports/processing
392	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.crashlytics.data/maccatalyst.com.frontrow.vlog/v5/reports/active/e927d8de13a24417ba52c8782b6e762e
392	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.crashlytics.data/maccatalyst.com.frontrow.vlog/v5/reports/active
392	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.crashlytics.data/maccatalyst.com.frontrow.vlog/v5/reports
408	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.crashlytics.data/maccatalyst.com.frontrow.vlog/v5
408	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.crashlytics.data/maccatalyst.com.frontrow.vlog
408	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.crashlytics.data
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/WebKit/OfflineWebApplicationCache
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/WebKit/NetworkCache
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/WebKit/CacheStorage
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/WebKit/ServiceWorkers
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/WebKit
66280	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/Compress/Thumbnail/58db57ba0bd4aa3d4a9a318093831b87
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/Compress/Thumbnail/9d24e20bf84dfc037336135d020ff4f7
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/Compress/Thumbnail/f83928852394793a8889aea333cca599
40472	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/Compress/Thumbnail/1a648d7f48394d44452fef7671847739
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/Compress/Thumbnail/b8ce579cd4665484c9b96de295fe15f4
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/Compress/Thumbnail/85f4614e91b5079cb257bea1c50a4424
138536	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/Compress/Thumbnail/10a0c0920cb595df8995b98eba82c585
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/Compress/Thumbnail/e3f75cd30b30110a2f50fb017ac5c5d5
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/Compress/Thumbnail/5f7e6d06e03b95ad3a395b133114c540
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/Compress/Thumbnail/7136e9f79397634abe05c53646038358
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/Compress/Thumbnail/d2085888deb789e733049da5907ff108
245288	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/Compress/Thumbnail
245288	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/Compress
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/TemporaryFile
4568	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/AD
160	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.hackemist.SDImageCache/default
160	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.hackemist.SDImageCache
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.apple.WebKit.WebContent
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/google-sdks-events/GDTCORFlatFileStorage/gdt_event_data/1002
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/google-sdks-events/GDTCORFlatFileStorage/gdt_event_data/1003
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/google-sdks-events/GDTCORFlatFileStorage/gdt_event_data/1001
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/google-sdks-events/GDTCORFlatFileStorage/gdt_event_data/1000
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/google-sdks-events/GDTCORFlatFileStorage/gdt_event_data
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/google-sdks-events/GDTCORFlatFileStorage/gdt_library_data
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/google-sdks-events/GDTCORFlatFileStorage/gdt_batch_data
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/google-sdks-events/GDTCORFlatFileStorage
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/google-sdks-events
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.jpvideoplayer.www
24	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVE2CubicBezier
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/VNCommonCaches
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FullFile
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.plausiblelabs.crashreporter.data/maccatalyst.com.frontrow.vlog/queued_reports
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.plausiblelabs.crashreporter.data/maccatalyst.com.frontrow.vlog
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/com.plausiblelabs.crashreporter.data
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/31EBD308-E2F4-4CA0-A03D-1C45E4B7F630/L0
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/31EBD308-E2F4-4CA0-A03D-1C45E4B7F630
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/76CC893E-50DE-4385-AD84-449C762527E1/L0
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/76CC893E-50DE-4385-AD84-449C762527E1
32	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/E9479090-5C66-4FA4-9198-9051258EFC72/L0
32	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/E9479090-5C66-4FA4-9198-9051258EFC72
24	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/D157256E-FD97-42D4-800A-18A6911F5285/L0
24	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/D157256E-FD97-42D4-800A-18A6911F5285
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/110B47F8-99C0-4C65-877A-C4546E3A3BA7/L0
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/110B47F8-99C0-4C65-877A-C4546E3A3BA7
24	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/6AA9F499-641E-4B6B-B55E-1A60C9A266F0/L0
24	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/6AA9F499-641E-4B6B-B55E-1A60C9A266F0
32	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/38DBD3E7-5667-441A-A296-1BD3DF575C07/L0
32	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/38DBD3E7-5667-441A-A296-1BD3DF575C07
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/772D0E0F-D233-4646-A718-146B09E72B05/L0
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/772D0E0F-D233-4646-A718-146B09E72B05
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/52BAF744-5ECA-47CD-ACCC-672F65985E7E/L0
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/52BAF744-5ECA-47CD-ACCC-672F65985E7E
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/5B7AE8CB-ADE2-4302-A63C-116EDB409806/L0
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/5B7AE8CB-ADE2-4302-A63C-116EDB409806
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/208C1C3E-54CE-44BE-A401-DB81AC1BD93A/L0
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/208C1C3E-54CE-44BE-A401-DB81AC1BD93A
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/B072EF17-7134-4769-ADA4-06A566EE4CC7/L0
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/B072EF17-7134-4769-ADA4-06A566EE4CC7
64	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/81D5D0F8-57EA-4197-9F65-33243251A098/L0
64	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/81D5D0F8-57EA-4197-9F65-33243251A098
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/D6AC6378-7E22-416C-B824-13016AF46652/L0
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/D6AC6378-7E22-416C-B824-13016AF46652
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/51D57878-E1B6-477D-805C-6283FFD4A8CB/L0
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/51D57878-E1B6-477D-805C-6283FFD4A8CB
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/911C85E1-E412-4959-8D11-63C92EC71AE9/L0
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/911C85E1-E412-4959-8D11-63C92EC71AE9
32	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/2EEEBB6C-8F66-4612-9F26-AB5C16DEA697/L0
32	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/2EEEBB6C-8F66-4612-9F26-AB5C16DEA697
24	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/04BEDDFB-8A24-4FC8-BEF7-FD10D746AA92/L0
24	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/04BEDDFB-8A24-4FC8-BEF7-FD10D746AA92
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/B54A494D-E353-4A01-8810-9193B35C6077/L0
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/B54A494D-E353-4A01-8810-9193B35C6077
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/B8604209-110A-4A1A-987A-440F00134418/L0
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/B8604209-110A-4A1A-987A-440F00134418
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/4A5B94E6-1D83-403B-8115-610DB5351398/L0
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/4A5B94E6-1D83-403B-8115-610DB5351398
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/B6E2BAD2-F818-42CD-86D3-1C918E1CAEAD/L0
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/B6E2BAD2-F818-42CD-86D3-1C918E1CAEAD
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/7F77941E-68C5-4392-B95B-DC0FA5289874/L0
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/7F77941E-68C5-4392-B95B-DC0FA5289874
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/0D01F2E3-0991-4612-A087-2BF104ED6BFB/L0
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/0D01F2E3-0991-4612-A087-2BF104ED6BFB
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/67A56AA0-8950-42EB-847D-D8DC1AFED7A9/L0
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/67A56AA0-8950-42EB-847D-D8DC1AFED7A9
56	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/34AFC640-EFD9-486E-914A-09EE10F25E90/L0
56	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/34AFC640-EFD9-486E-914A-09EE10F25E90
96	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/29A21008-85CA-40A9-8DBA-CB2DC596B649/L0
96	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/29A21008-85CA-40A9-8DBA-CB2DC596B649
24	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/7C803AAD-AFD1-49A6-8966-5A7EADF64226/L0
24	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/7C803AAD-AFD1-49A6-8966-5A7EADF64226
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/14D9DC94-FBAB-4D4B-9869-976803E32925/L0
48	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/14D9DC94-FBAB-4D4B-9869-976803E32925
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/5DD43A76-18D8-4169-9B86-51ED755F2553/L0
40	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/5DD43A76-18D8-4169-9B86-51ED755F2553
56	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/CACBA6B4-2260-4B33-95AE-726B50CC98BA/L0
56	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/CACBA6B4-2260-4B33-95AE-726B50CC98BA
16	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/F98CA772-4CF4-4AB4-87DA-21EAD10B759C/L0
16	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/F98CA772-4CF4-4AB4-87DA-21EAD10B759C
56	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/C253661D-F4AA-4582-9C1D-CA776F217E61/L0
56	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton/C253661D-F4AA-4582-9C1D-CA776F217E61
1408	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches/FRVSelectAssetSingleton
257312	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library/Caches
257872	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Library
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/UserFile/Music
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/UserFile/TitleTemplate
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/UserFile/StickerV2/E9C4A0FC-E81E-4B0C-9E65-ACA1F7521737
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/UserFile/StickerV2/3E56AD85-FBC1-4DF5-BF6D-8160C7F8297D
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/UserFile/StickerV2
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/UserFile/Voice
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/UserFile/Font
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/UserFile/SoundEffect
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/UserFile/Filter
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/UserFile
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/Library
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/MaterialMacOS/DefaultFiles/FRVE2MaterialFolderForMacFavoriteUUID
160	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/MaterialMacOS/DefaultFiles/FRVE2MaterialFolderForMacDefaultUUID
160	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/MaterialMacOS/DefaultFiles
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/MaterialMacOS/Files/MaterailCustomDefaultFolderUUID
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/MaterialMacOS/Files
160	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/MaterialMacOS
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/Draft/1/Asset
232	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/Draft/1/Steps
27028472	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/Draft/1
27028480	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/Draft
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/a035575dcc7f441d93c2fee025918e9b
16	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/239d07abe65b45e18af50baec005dbed
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/15274e2be2dd4623b13be30893931285
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/29bec23211b54b93bb6fce2a5e5b2157
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/50c0b64efd374f998ac22485a31685df
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/8d328e3d077849ad8a0032708dcc17e6
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/54669d9625924aa49c9fd6707123177c
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/c3ab7d78c38c456abcf3edd40a9b4091
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/901939ed82744cd7b0bc7a8371532492
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/3f9072c5020c4af981cc7cf71c00782e
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/e66918ec34b5456d9377c7274672679a
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/d0a811f74b124c52855f5eca505aa780
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/f7941c641c2d414bbd4504586ad00b6b
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/17446742f891411cb0049e6baf070b52
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/383ccbf5bd3e4c68a893e3c2054a153a
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/2b93a0d5b1e8400fbdb6deda3a079cbd
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/190adcb9732e4b8eb87786208d75ec46
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/6b6a498496d54bc7a3f4a3bf40fa13fb
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/74d02c50349d47efb2f3bd6d1be9aedc
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/390cf902b2194942a2d4d0d984c14fc3
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/3e650e180f0e460e9e9ab822a4bfbf71
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/77bbc87305f14155aa2aefa13421aa61
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/e0d0845a25ba44b3addfe0b907748b84
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/5296d8d6949b4b0a88cc295c7a36fedc
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/739590f80fb04e29b5c540cbba55bbfb
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/1336566a618f4eeda1a0a54fb813646e
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/742367d9a2a24474ba7c618b554fba15
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/7b9bb98e0cd04a139621123d61c2f7e5
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/363d8b65020b44feb3f9c755c474afce
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/0c5f004df90d41b79cc6af8d17d7aae6
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/38906807b9bd499f9e2655cd01cba872
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/a4b2698830fa4fb8b1a3993a0bd3be40
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/5ef492cb29264a309037241db767cde8
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/6fb3ab8c395a486d99c418677f0ea270
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/c43a98739fbd4fec82d0ee02bab95353
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/d18ab80b192241449191133e894541da
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/2b29f81559c4421b9bb1cd365edeb155
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/d32d2b8670d14c2599e1a29be06b894d
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/d765820d051642f38ae5d295c4439ec8
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/80c711231c384daeaab36e4525c26708
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/1f2ba9021f464bb7a6c9d5fca5178d8c
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/f69328f82f1848c9b46f0c3433bce6cc
16	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/354b787f3bd4408287d146e498479767
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/34955a78af28444e9d851941b63a467e
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/25e2f95e4499464da4f5acd76f4b308c
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/932b012a48ab46449474efc4684a10d2
8	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/00b8ca1ee6d8474684378bddc54d2ac5
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/3877b5abb9f24860a6dde05d99bbf6c0
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/1065673cec174a9e94cd664a21e0bf8f
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/3fa46629913545588c143af33efc4628
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/8a54f098d0ff44ff8b6c418ebda8674d
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/b1cfa1925e9c4c5893b5bfc926c943f8
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/ee20f73f386f4d2bb49c4840a224f394
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary/9dd29655484e4b77a35cedded2a6d74f
160	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/OnlineStickerLibrary
1840	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/9A546994-0FFB-4DAE-BB73-D54E986843A3/frames
856	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/9A546994-0FFB-4DAE-BB73-D54E986843A3/preview
2704	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/9A546994-0FFB-4DAE-BB73-D54E986843A3
1464	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/20F576BB-8827-418C-81D9-3BC3CD78B0BF/frames
496	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/20F576BB-8827-418C-81D9-3BC3CD78B0BF/preview
1968	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/20F576BB-8827-418C-81D9-3BC3CD78B0BF
2032	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/49F68E34-F5B6-4651-AE48-DE36FB9E197A/frames
496	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/49F68E34-F5B6-4651-AE48-DE36FB9E197A/preview
2536	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/49F68E34-F5B6-4651-AE48-DE36FB9E197A
512	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/AF0E53BF-34DC-4B3A-82DC-B88122DD3CF1/frames
320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/AF0E53BF-34DC-4B3A-82DC-B88122DD3CF1/preview
840	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/AF0E53BF-34DC-4B3A-82DC-B88122DD3CF1
1416	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/C220C1AB-F0B4-45EF-8608-9062E8B2815A/frames
320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/C220C1AB-F0B4-45EF-8608-9062E8B2815A/preview
1744	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/C220C1AB-F0B4-45EF-8608-9062E8B2815A
2856	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/A436D273-315A-4667-9809-98DA760F4D96/frames
320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/A436D273-315A-4667-9809-98DA760F4D96/preview
3184	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/A436D273-315A-4667-9809-98DA760F4D96
608	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/41F61DA6-6404-44A3-9F47-3244B54DC45C/frames
320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/41F61DA6-6404-44A3-9F47-3244B54DC45C/preview
936	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/41F61DA6-6404-44A3-9F47-3244B54DC45C
1168	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/E1421249-A6AB-47BD-88FD-DDA6D9BA4C3C/frames
320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/E1421249-A6AB-47BD-88FD-DDA6D9BA4C3C/preview
1496	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/E1421249-A6AB-47BD-88FD-DDA6D9BA4C3C
768	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/FF13B702-1479-4303-960B-1043387572FB/frames
320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/FF13B702-1479-4303-960B-1043387572FB/preview
1096	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/FF13B702-1479-4303-960B-1043387572FB
1256	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/CCFCEA9D-215D-471F-8709-A7558A4707E2/frames
496	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/CCFCEA9D-215D-471F-8709-A7558A4707E2/preview
1760	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/CCFCEA9D-215D-471F-8709-A7558A4707E2
936	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/431ADEBB-5BEF-4954-8990-8533CE9C9BBF/frames
320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/431ADEBB-5BEF-4954-8990-8533CE9C9BBF/preview
1264	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/431ADEBB-5BEF-4954-8990-8533CE9C9BBF
2376	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/44803653-F7F0-48DF-9C18-F4EFAA4339C3/frames
320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/44803653-F7F0-48DF-9C18-F4EFAA4339C3/preview
2704	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/44803653-F7F0-48DF-9C18-F4EFAA4339C3
888	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/E332601A-4C1A-4D34-BD95-53AC313B1EF2/frames
320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/E332601A-4C1A-4D34-BD95-53AC313B1EF2/preview
1216	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/E332601A-4C1A-4D34-BD95-53AC313B1EF2
912	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/C80A83DF-0A07-45A3-B82F-FFC6911F3FBF/frames
320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/C80A83DF-0A07-45A3-B82F-FFC6911F3FBF/preview
1240	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/C80A83DF-0A07-45A3-B82F-FFC6911F3FBF
872	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/D58F5648-6F80-4663-84AA-E6E1D87B5872/frames
320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/D58F5648-6F80-4663-84AA-E6E1D87B5872/preview
1200	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/D58F5648-6F80-4663-84AA-E6E1D87B5872
768	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/B0188A4B-98D0-46B6-AF02-1C593B909ECD/frames
320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/B0188A4B-98D0-46B6-AF02-1C593B909ECD/preview
1096	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/B0188A4B-98D0-46B6-AF02-1C593B909ECD
840	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/CB9DC8D4-0D0D-44D9-A3E8-32E00BD0C577/frames
320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/CB9DC8D4-0D0D-44D9-A3E8-32E00BD0C577/preview
1168	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/CB9DC8D4-0D0D-44D9-A3E8-32E00BD0C577
776	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/0937E098-2A8F-4B18-8579-CF5317C413B0/frames
320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/0937E098-2A8F-4B18-8579-CF5317C413B0/preview
1104	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/0937E098-2A8F-4B18-8579-CF5317C413B0
4256	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/7FA0536C-C07D-44C1-963E-190D4DC28FB9/frames
496	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/7FA0536C-C07D-44C1-963E-190D4DC28FB9/preview
4760	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask/7FA0536C-C07D-44C1-963E-190D4DC28FB9
34024	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts/mask
34024	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/TransitionScripts
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/FRVEPackage/Download/Music
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/FRVEPackage/Download/Sticker
0	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/FRVEPackage/Download
16	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/FRVEPackage
3320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/80821aef7ab0d2993741ac12e4c80bc8/[png]33929ef38bc5072c0eedb8602ea6edae
3328	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/80821aef7ab0d2993741ac12e4c80bc8
1264	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/201cad67871ccba5dd1838289c066bb3/[png]a55650e35e643538562b560178231270
1272	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/201cad67871ccba5dd1838289c066bb3
976	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/c011201c1167392576626a96119f8106/[png]c638d7e3290823bfc8c710d3080385a0
976	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/c011201c1167392576626a96119f8106/[png]0fc8e817d6b5c33beaa907f0840e30bc
1968	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/c011201c1167392576626a96119f8106
1392	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/70b53a494d61985eeea851503527d4b7/[png]80357a2d4799d5ff15ab35417aba708a
1096	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/70b53a494d61985eeea851503527d4b7/[png]6f8837d4be196e7cc3d544d0dc02650c
704	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/70b53a494d61985eeea851503527d4b7/[png]8bd3f866288fb68f9ee9bc3eb586afd0
3216	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/70b53a494d61985eeea851503527d4b7
288	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/73f85953c50635436634034e75f54d8e/[png]5c6e3e5212b9c6d9b578b02f19a90f7d
296	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/73f85953c50635436634034e75f54d8e
5032	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/85ef4c1967f4805071fd672ad5667432/[png]deb3098de10f499352691fc0448c6e0a
5040	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/85ef4c1967f4805071fd672ad5667432
4272	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/4aac06cd42e088fcf34e16c70fd438c7/[png]88709ca80374e9fc1056b27e6603b2bd
4280	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/4aac06cd42e088fcf34e16c70fd438c7
4472	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/596cd26c559ea75d37bca47b1ded7311/[png]07594ef1a75ceb3022ddf8365fbb0903
4480	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/596cd26c559ea75d37bca47b1ded7311
24024	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/81af87062e8ca338fd216ad8c53e1c26/[png]70500e65d06c007feecc27b50ee4be0e
24032	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/81af87062e8ca338fd216ad8c53e1c26
10872	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/f700df7042fe36ccc99d1fe962cbc3a7/[png]1b291840169e42bc74f0fce9b66ffb68
10880	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/f700df7042fe36ccc99d1fe962cbc3a7
424	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/22e03e43ea7febb3cb86aa0cbebe6cd8/[png]ecd9b7e6057f8520ee74d38de843e1eb
432	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/22e03e43ea7febb3cb86aa0cbebe6cd8
656	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/6ec8f69f76ce387fad3d671b1e87fa28/[png]80a96be5750dac9a8b25af9320f3d339
664	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/6ec8f69f76ce387fad3d671b1e87fa28
248	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/c4be8ee366fb2b33b45438b9f746c30e/[png]afb074770da66ea4cab80ec767496a34
256	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/c4be8ee366fb2b33b45438b9f746c30e
1952	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/060fb6df4b56c7b00ae92b55602b2e25/[png]516bad0f8361a628770dbbfaf291460c
1960	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/060fb6df4b56c7b00ae92b55602b2e25
3512	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/03501c84d4dc835b895dc3eb61977cfc/[png]eea15e64e576001a53adcb73a69980e9
3520	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/03501c84d4dc835b895dc3eb61977cfc
176	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/f8884f0ae6518cf0b326d27782453961/[png]593e108d5646e37ce2696813010abc6a
184	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/f8884f0ae6518cf0b326d27782453961
976	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/ce36ead9c321332d7b30ee248815e6f9/[png]8d5354a889abf35e4eeb83a2c4999c08
976	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/ce36ead9c321332d7b30ee248815e6f9/[png]fe5bcd2e1b7b2cd1d29f8c3be92f864b
1968	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/ce36ead9c321332d7b30ee248815e6f9
5136	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/25245f40262ac22e07af5557bd579d3b/[png]7c6e87081418b528b62f582d35c18c84
5144	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/25245f40262ac22e07af5557bd579d3b
2440	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/3faba0c36ae102375f53bcadd1b7415c/[png]db8fb9d904143a6b202d426f5d27d2d9
2448	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/3faba0c36ae102375f53bcadd1b7415c
1896	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/3b9584f7eafe1234e8bd1a05309de2d2/[png]bf246d8a6107528f68abd5238b037e63
1904	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/3b9584f7eafe1234e8bd1a05309de2d2
560	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/d39995a82a838e91e9ebd52a5271ddff/[png]659e219f41dd8856b6ac1d0a85aca1be
568	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/d39995a82a838e91e9ebd52a5271ddff
3976	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/fb4e98589bef0b8069edc2a5f06b32b9/[png]ec023cbdc45ccfbf7714f75eddd2b78d
3984	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/fb4e98589bef0b8069edc2a5f06b32b9
4112	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/18e855b0dcb485c29bc5be3565a57c5a/[png]0589172375ed02f270aaf3c8c391f2a6
4120	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/18e855b0dcb485c29bc5be3565a57c5a
656	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/f76e6604f97653db5a27379ce51f82a7/[png]6e47f7b0ecd5a3730ccf97e52617a355
664	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/f76e6604f97653db5a27379ce51f82a7
2720	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/ff7ab74af5dfeb848e8474d01abf41d5/[png]8f0e793fe50311807a0ec65484188f61
2728	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/ff7ab74af5dfeb848e8474d01abf41d5
2488	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/68296a6c953a2a67a6d65ad0ee146fb0/[png]41dd5d5cba3a4d25728a8a264aa7050b
704	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/68296a6c953a2a67a6d65ad0ee146fb0/[png]12d9ef6ab75e11ab75ec8841f748fb6d
1168	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/68296a6c953a2a67a6d65ad0ee146fb0/[png]8aaf9d2873d7ed48ce27282e9c779e8a
4384	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/68296a6c953a2a67a6d65ad0ee146fb0
960	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/2981f48d9a951123541c16e8c2bbf069/[png]2232bc5acf3c5aef5b9fea7da33143d9
968	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/2981f48d9a951123541c16e8c2bbf069
1064	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/9d7dda1b587cd473bda300786455dd0b/[png]0fd5d26e432b752ef0f4cf16d6265432
1072	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/9d7dda1b587cd473bda300786455dd0b
456	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/6c16545fb2b0fc6fdb67e567500fb404/[png]4a77abb46b9bfc13cdc5801f7d2490f2
464	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/6c16545fb2b0fc6fdb67e567500fb404
448	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/6edaf64e3d778845a6721d1465ac91dd/[png]87b8c3bd14054037d14a4d3197db3eea
456	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/6edaf64e3d778845a6721d1465ac91dd
6592	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/7b4404c4fcf01db1353c2a79984ccac5/[png]d6fd079135254b9072e46e43cce2bff8
6600	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/7b4404c4fcf01db1353c2a79984ccac5
976	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/554b6640debbe49e1ce3a2bdb25a8dc3/[png]0b4b024061b5ff810d9cc29da6652a94
984	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/554b6640debbe49e1ce3a2bdb25a8dc3
1216	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/e75fbb7bc5a548e4dbf9c765c77cd6c5/[png]94eaf8ffd4c12f6a8b272c6186d662e5
1224	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/e75fbb7bc5a548e4dbf9c765c77cd6c5
1120	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/1136a4edc011c7138b0c31e23b91550c/[png]e6569c56c6efbf5b5e846762d25fa0cc
1432	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/1136a4edc011c7138b0c31e23b91550c/[png]ae195f79b802051034ddb44738052c2e
2568	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/1136a4edc011c7138b0c31e23b91550c
440	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/199cd45900aa62cbb3e16274f40ada1e/[png]a2775a28c24ad4f324ca67f7b2bffa71
448	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate/199cd45900aa62cbb3e16274f40ada1e
108504	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/bridgedTitleTemplate
160	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/Material/Files/Default-1650899432
160	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/Material/Files
168	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/Material
520	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/MusicLibrary/SoundEffects/Ringing
904	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/MusicLibrary/SoundEffects/Fast Swish
696	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/MusicLibrary/SoundEffects/Funny
248	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/MusicLibrary/SoundEffects/Cartoon
2224	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/MusicLibrary/SoundEffects/Machine
416	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/MusicLibrary/SoundEffects/Vehicles
2240	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/MusicLibrary/SoundEffects/Weather
7280	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/MusicLibrary/SoundEffects
7280	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor/MusicLibrary
27178888	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/FRVideoEditor
3776	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/pictogram
528	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents/log
27183320	./Library/Containers/maccatalyst.com.frontrow.vlog/Data/Documents
27441192	./Library/Containers/maccatalyst.com.frontrow.vlog/Data
27441248	./Library/Containers/maccatalyst.com.frontrow.vlog
du: ./Library/Containers/com.apple.archiveutility: Operation not permitted
0	./Library/Containers/com.apple.FaceTime/Data/Library/Application Support
0	./Library/Containers/com.apple.FaceTime/Data/Library/Saved Application State
24	./Library/Containers/com.apple.FaceTime/Data/Library/Preferences
0	./Library/Containers/com.apple.FaceTime/Data/Library/Application Scripts
0	./Library/Containers/com.apple.FaceTime/Data/Library/Images
0	./Library/Containers/com.apple.FaceTime/Data/Library/Logs
0	./Library/Containers/com.apple.FaceTime/Data/Library/Caches
24	./Library/Containers/com.apple.FaceTime/Data/Library
0	./Library/Containers/com.apple.FaceTime/Data/Documents
24	./Library/Containers/com.apple.FaceTime/Data
104	./Library/Containers/com.apple.FaceTime
0	./Library/Containers/com.apple.ScreenTimeAgent/Data/Library/Application Support/ScreenTimeAgent
0	./Library/Containers/com.apple.ScreenTimeAgent/Data/Library/Application Support
0	./Library/Containers/com.apple.ScreenTimeAgent/Data/Library/Saved Application State
8	./Library/Containers/com.apple.ScreenTimeAgent/Data/Library/Preferences
0	./Library/Containers/com.apple.ScreenTimeAgent/Data/Library/Application Scripts
0	./Library/Containers/com.apple.ScreenTimeAgent/Data/Library/Images
0	./Library/Containers/com.apple.ScreenTimeAgent/Data/Library/Logs
168	./Library/Containers/com.apple.ScreenTimeAgent/Data/Library/Caches/com.apple.ScreenTimeAgent
168	./Library/Containers/com.apple.ScreenTimeAgent/Data/Library/Caches
176	./Library/Containers/com.apple.ScreenTimeAgent/Data/Library
0	./Library/Containers/com.apple.ScreenTimeAgent/Data/Documents
176	./Library/Containers/com.apple.ScreenTimeAgent/Data
232	./Library/Containers/com.apple.ScreenTimeAgent
0	./Library/Containers/com.apple.calculator/Data/Library/Application Support
0	./Library/Containers/com.apple.calculator/Data/Library/Saved Application State
8	./Library/Containers/com.apple.calculator/Data/Library/Preferences
0	./Library/Containers/com.apple.calculator/Data/Library/Application Scripts
0	./Library/Containers/com.apple.calculator/Data/Library/Images
0	./Library/Containers/com.apple.calculator/Data/Library/Logs
0	./Library/Containers/com.apple.calculator/Data/Library/Caches
8	./Library/Containers/com.apple.calculator/Data/Library
0	./Library/Containers/com.apple.calculator/Data/Documents
8	./Library/Containers/com.apple.calculator/Data
56	./Library/Containers/com.apple.calculator
0	./Library/Containers/com.apple.photos.ImageConversionService/Data/Library/Application Support
0	./Library/Containers/com.apple.photos.ImageConversionService/Data/Library/Saved Application State
0	./Library/Containers/com.apple.photos.ImageConversionService/Data/Library/Preferences
0	./Library/Containers/com.apple.photos.ImageConversionService/Data/Library/Application Scripts
0	./Library/Containers/com.apple.photos.ImageConversionService/Data/Library/Images
0	./Library/Containers/com.apple.photos.ImageConversionService/Data/Library/Logs
0	./Library/Containers/com.apple.photos.ImageConversionService/Data/Library/Caches
0	./Library/Containers/com.apple.photos.ImageConversionService/Data/Library
0	./Library/Containers/com.apple.photos.ImageConversionService/Data/Documents
0	./Library/Containers/com.apple.photos.ImageConversionService/Data
48	./Library/Containers/com.apple.photos.ImageConversionService
0	./Library/Containers/com.apple.FaceTime.FaceTimeNotificationCenterService/Data/Library/Application Support
0	./Library/Containers/com.apple.FaceTime.FaceTimeNotificationCenterService/Data/Library/Saved Application State
0	./Library/Containers/com.apple.FaceTime.FaceTimeNotificationCenterService/Data/Library/Preferences
0	./Library/Containers/com.apple.FaceTime.FaceTimeNotificationCenterService/Data/Library/Application Scripts
0	./Library/Containers/com.apple.FaceTime.FaceTimeNotificationCenterService/Data/Library/Images
0	./Library/Containers/com.apple.FaceTime.FaceTimeNotificationCenterService/Data/Library/Logs
0	./Library/Containers/com.apple.FaceTime.FaceTimeNotificationCenterService/Data/Library/Caches
0	./Library/Containers/com.apple.FaceTime.FaceTimeNotificationCenterService/Data/Library
0	./Library/Containers/com.apple.FaceTime.FaceTimeNotificationCenterService/Data/Documents
0	./Library/Containers/com.apple.FaceTime.FaceTimeNotificationCenterService/Data
80	./Library/Containers/com.apple.FaceTime.FaceTimeNotificationCenterService
0	./Library/Containers/com.apple.ncplugin.weather/Data/Library/Application Support
0	./Library/Containers/com.apple.ncplugin.weather/Data/Library/Saved Application State
8	./Library/Containers/com.apple.ncplugin.weather/Data/Library/Preferences
0	./Library/Containers/com.apple.ncplugin.weather/Data/Library/Application Scripts
0	./Library/Containers/com.apple.ncplugin.weather/Data/Library/Images
8	./Library/Containers/com.apple.ncplugin.weather/Data/Library/SyncedPreferences
0	./Library/Containers/com.apple.ncplugin.weather/Data/Library/Logs
0	./Library/Containers/com.apple.ncplugin.weather/Data/Library/Caches
16	./Library/Containers/com.apple.ncplugin.weather/Data/Library
0	./Library/Containers/com.apple.ncplugin.weather/Data/Documents
16	./Library/Containers/com.apple.ncplugin.weather/Data
72	./Library/Containers/com.apple.ncplugin.weather
0	./Library/Containers/com.apple.preferences.sharing.SharingBluetoothService/Data/Library/Application Support
0	./Library/Containers/com.apple.preferences.sharing.SharingBluetoothService/Data/Library/Saved Application State
0	./Library/Containers/com.apple.preferences.sharing.SharingBluetoothService/Data/Library/Preferences
0	./Library/Containers/com.apple.preferences.sharing.SharingBluetoothService/Data/Library/Application Scripts
0	./Library/Containers/com.apple.preferences.sharing.SharingBluetoothService/Data/Library/Images
0	./Library/Containers/com.apple.preferences.sharing.SharingBluetoothService/Data/Library/Logs
0	./Library/Containers/com.apple.preferences.sharing.SharingBluetoothService/Data/Library/Caches
0	./Library/Containers/com.apple.preferences.sharing.SharingBluetoothService/Data/Library
0	./Library/Containers/com.apple.preferences.sharing.SharingBluetoothService/Data/Documents
0	./Library/Containers/com.apple.preferences.sharing.SharingBluetoothService/Data
40	./Library/Containers/com.apple.preferences.sharing.SharingBluetoothService
0	./Library/Containers/com.apple.quicklook.QuickLookUIService/Data/Library/Application Support
0	./Library/Containers/com.apple.quicklook.QuickLookUIService/Data/Library/Saved Application State
0	./Library/Containers/com.apple.quicklook.QuickLookUIService/Data/Library/Preferences
0	./Library/Containers/com.apple.quicklook.QuickLookUIService/Data/Library/Application Scripts
0	./Library/Containers/com.apple.quicklook.QuickLookUIService/Data/Library/Images
0	./Library/Containers/com.apple.quicklook.QuickLookUIService/Data/Library/Logs
0	./Library/Containers/com.apple.quicklook.QuickLookUIService/Data/Library/Caches
0	./Library/Containers/com.apple.quicklook.QuickLookUIService/Data/Library
0	./Library/Containers/com.apple.quicklook.QuickLookUIService/Data/Documents
0	./Library/Containers/com.apple.quicklook.QuickLookUIService/Data
64	./Library/Containers/com.apple.quicklook.QuickLookUIService
0	./Library/Containers/com.apple.contacts.donation-agent/Data/Library/Application Support
0	./Library/Containers/com.apple.contacts.donation-agent/Data/Library/Saved Application State
8	./Library/Containers/com.apple.contacts.donation-agent/Data/Library/Preferences
0	./Library/Containers/com.apple.contacts.donation-agent/Data/Library/Application Scripts
0	./Library/Containers/com.apple.contacts.donation-agent/Data/Library/Images
16	./Library/Containers/com.apple.contacts.donation-agent/Data/Library/Contacts/Donations
16	./Library/Containers/com.apple.contacts.donation-agent/Data/Library/Contacts
0	./Library/Containers/com.apple.contacts.donation-agent/Data/Library/Logs
0	./Library/Containers/com.apple.contacts.donation-agent/Data/Library/Caches/com.apple.contacts.donation-agent
0	./Library/Containers/com.apple.contacts.donation-agent/Data/Library/Caches
24	./Library/Containers/com.apple.contacts.donation-agent/Data/Library
0	./Library/Containers/com.apple.contacts.donation-agent/Data/Documents
24	./Library/Containers/com.apple.contacts.donation-agent/Data
72	./Library/Containers/com.apple.contacts.donation-agent
0	./Library/Containers/com.apple.photolibraryd/Data/Library/Application Support
0	./Library/Containers/com.apple.photolibraryd/Data/Library/Saved Application State
8	./Library/Containers/com.apple.photolibraryd/Data/Library/Preferences
0	./Library/Containers/com.apple.photolibraryd/Data/Library/Application Scripts
0	./Library/Containers/com.apple.photolibraryd/Data/Library/Images
0	./Library/Containers/com.apple.photolibraryd/Data/Library/Logs
0	./Library/Containers/com.apple.photolibraryd/Data/Library/Caches
8	./Library/Containers/com.apple.photolibraryd/Data/Library
0	./Library/Containers/com.apple.photolibraryd/Data/Documents
8	./Library/Containers/com.apple.photolibraryd/Data
72	./Library/Containers/com.apple.photolibraryd
0	./Library/Containers/com.apple.siri.media-indexer/Data/Library/Application Support
0	./Library/Containers/com.apple.siri.media-indexer/Data/Library/Saved Application State
8	./Library/Containers/com.apple.siri.media-indexer/Data/Library/Preferences
0	./Library/Containers/com.apple.siri.media-indexer/Data/Library/Application Scripts
0	./Library/Containers/com.apple.siri.media-indexer/Data/Library/Images
0	./Library/Containers/com.apple.siri.media-indexer/Data/Library/Logs
0	./Library/Containers/com.apple.siri.media-indexer/Data/Library/Caches
8	./Library/Containers/com.apple.siri.media-indexer/Data/Library
0	./Library/Containers/com.apple.siri.media-indexer/Data/Documents
200	./Library/Containers/com.apple.siri.media-indexer/Data
248	./Library/Containers/com.apple.siri.media-indexer
0	./Library/Containers/com.apple.CryptoTokenKit.setoken/Data/Library/Application Support
0	./Library/Containers/com.apple.CryptoTokenKit.setoken/Data/Library/Saved Application State
0	./Library/Containers/com.apple.CryptoTokenKit.setoken/Data/Library/Preferences
0	./Library/Containers/com.apple.CryptoTokenKit.setoken/Data/Library/Application Scripts
0	./Library/Containers/com.apple.CryptoTokenKit.setoken/Data/Library/Images
0	./Library/Containers/com.apple.CryptoTokenKit.setoken/Data/Library/Logs
0	./Library/Containers/com.apple.CryptoTokenKit.setoken/Data/Library/Caches
0	./Library/Containers/com.apple.CryptoTokenKit.setoken/Data/Library
0	./Library/Containers/com.apple.CryptoTokenKit.setoken/Data/Documents
0	./Library/Containers/com.apple.CryptoTokenKit.setoken/Data
40	./Library/Containers/com.apple.CryptoTokenKit.setoken
0	./Library/Containers/com.apple.BKAgentService/Data/Library/Application Support
0	./Library/Containers/com.apple.BKAgentService/Data/Library/Saved Application State
8	./Library/Containers/com.apple.BKAgentService/Data/Library/Preferences
0	./Library/Containers/com.apple.BKAgentService/Data/Library/Application Scripts
0	./Library/Containers/com.apple.BKAgentService/Data/Library/Images
0	./Library/Containers/com.apple.BKAgentService/Data/Library/Logs
0	./Library/Containers/com.apple.BKAgentService/Data/Library/Caches
8	./Library/Containers/com.apple.BKAgentService/Data/Library
8	./Library/Containers/com.apple.BKAgentService/Data/Documents/iBooks/Books
0	./Library/Containers/com.apple.BKAgentService/Data/Documents/iBooks/Updates
0	./Library/Containers/com.apple.BKAgentService/Data/Documents/iBooks/Temporary
0	./Library/Containers/com.apple.BKAgentService/Data/Documents/iBooks/Downloads
8	./Library/Containers/com.apple.BKAgentService/Data/Documents/iBooks
8	./Library/Containers/com.apple.BKAgentService/Data/Documents
16	./Library/Containers/com.apple.BKAgentService/Data
64	./Library/Containers/com.apple.BKAgentService
0	./Library/Containers/com.apple.LookupViewService/Data/Library/Application Support
0	./Library/Containers/com.apple.LookupViewService/Data/Library/Saved Application State
0	./Library/Containers/com.apple.LookupViewService/Data/Library/Preferences
0	./Library/Containers/com.apple.LookupViewService/Data/Library/Application Scripts
0	./Library/Containers/com.apple.LookupViewService/Data/Library/Images
0	./Library/Containers/com.apple.LookupViewService/Data/Library/Logs
0	./Library/Containers/com.apple.LookupViewService/Data/Library/Caches
0	./Library/Containers/com.apple.LookupViewService/Data/Library
0	./Library/Containers/com.apple.LookupViewService/Data/Documents
0	./Library/Containers/com.apple.LookupViewService/Data
64	./Library/Containers/com.apple.LookupViewService
0	./Library/Containers/com.apple.Maps/Data/Library/Maps
8	./Library/Containers/com.apple.Maps/Data/Library/Preferences
8	./Library/Containers/com.apple.Maps/Data/Library
8	./Library/Containers/com.apple.Maps/Data
8	./Library/Containers/com.apple.Maps
0	./Library/Containers/com.apple.AMPDeviceDiscoveryAgent/Data/Library/Application Support
0	./Library/Containers/com.apple.AMPDeviceDiscoveryAgent/Data/Library/Saved Application State
0	./Library/Containers/com.apple.AMPDeviceDiscoveryAgent/Data/Library/Preferences
0	./Library/Containers/com.apple.AMPDeviceDiscoveryAgent/Data/Library/Application Scripts
0	./Library/Containers/com.apple.AMPDeviceDiscoveryAgent/Data/Library/Images
0	./Library/Containers/com.apple.AMPDeviceDiscoveryAgent/Data/Library/Logs
0	./Library/Containers/com.apple.AMPDeviceDiscoveryAgent/Data/Library/Caches
0	./Library/Containers/com.apple.AMPDeviceDiscoveryAgent/Data/Library
0	./Library/Containers/com.apple.AMPDeviceDiscoveryAgent/Data/Documents
0	./Library/Containers/com.apple.AMPDeviceDiscoveryAgent/Data
56	./Library/Containers/com.apple.AMPDeviceDiscoveryAgent
0	./Library/Containers/com.apple.CalendarNotification.CalNCService/Data/Library/Application Support
0	./Library/Containers/com.apple.CalendarNotification.CalNCService/Data/Library/Saved Application State
0	./Library/Containers/com.apple.CalendarNotification.CalNCService/Data/Library/Preferences
0	./Library/Containers/com.apple.CalendarNotification.CalNCService/Data/Library/Application Scripts
0	./Library/Containers/com.apple.CalendarNotification.CalNCService/Data/Library/Images
0	./Library/Containers/com.apple.CalendarNotification.CalNCService/Data/Library/Logs
0	./Library/Containers/com.apple.CalendarNotification.CalNCService/Data/Library/Caches
0	./Library/Containers/com.apple.CalendarNotification.CalNCService/Data/Library
0	./Library/Containers/com.apple.CalendarNotification.CalNCService/Data/Documents
0	./Library/Containers/com.apple.CalendarNotification.CalNCService/Data
64	./Library/Containers/com.apple.CalendarNotification.CalNCService
0	./Library/Containers/com.apple.podcasts.MacPodcastsStorageExtension/Data/Library/Application Support
0	./Library/Containers/com.apple.podcasts.MacPodcastsStorageExtension/Data/Library/Saved Application State
0	./Library/Containers/com.apple.podcasts.MacPodcastsStorageExtension/Data/Library/Preferences
0	./Library/Containers/com.apple.podcasts.MacPodcastsStorageExtension/Data/Library/Application Scripts
0	./Library/Containers/com.apple.podcasts.MacPodcastsStorageExtension/Data/Library/Images
0	./Library/Containers/com.apple.podcasts.MacPodcastsStorageExtension/Data/Library/Logs
0	./Library/Containers/com.apple.podcasts.MacPodcastsStorageExtension/Data/Library/Caches
0	./Library/Containers/com.apple.podcasts.MacPodcastsStorageExtension/Data/Library
0	./Library/Containers/com.apple.podcasts.MacPodcastsStorageExtension/Data/Documents
0	./Library/Containers/com.apple.podcasts.MacPodcastsStorageExtension/Data
48	./Library/Containers/com.apple.podcasts.MacPodcastsStorageExtension
0	./Library/Containers/com.apple.Safari.BrowserDataImportingService/Data/Library/Application Support
0	./Library/Containers/com.apple.Safari.BrowserDataImportingService/Data/Library/Saved Application State
0	./Library/Containers/com.apple.Safari.BrowserDataImportingService/Data/Library/Preferences
0	./Library/Containers/com.apple.Safari.BrowserDataImportingService/Data/Library/Application Scripts
0	./Library/Containers/com.apple.Safari.BrowserDataImportingService/Data/Library/Images
0	./Library/Containers/com.apple.Safari.BrowserDataImportingService/Data/Library/Logs
0	./Library/Containers/com.apple.Safari.BrowserDataImportingService/Data/Library/Caches
0	./Library/Containers/com.apple.Safari.BrowserDataImportingService/Data/Library
0	./Library/Containers/com.apple.Safari.BrowserDataImportingService/Data/Documents
0	./Library/Containers/com.apple.Safari.BrowserDataImportingService/Data
56	./Library/Containers/com.apple.Safari.BrowserDataImportingService
du: ./Library/Containers/com.apple.Safari: Operation not permitted
0	./Library/Containers/com.apple.CloudDocsDaemon.StorageManagement/Data/Library/Application Support
0	./Library/Containers/com.apple.CloudDocsDaemon.StorageManagement/Data/Library/Saved Application State
0	./Library/Containers/com.apple.CloudDocsDaemon.StorageManagement/Data/Library/Preferences
0	./Library/Containers/com.apple.CloudDocsDaemon.StorageManagement/Data/Library/Application Scripts
0	./Library/Containers/com.apple.CloudDocsDaemon.StorageManagement/Data/Library/Images
0	./Library/Containers/com.apple.CloudDocsDaemon.StorageManagement/Data/Library/Logs
0	./Library/Containers/com.apple.CloudDocsDaemon.StorageManagement/Data/Library/Caches
0	./Library/Containers/com.apple.CloudDocsDaemon.StorageManagement/Data/Library
0	./Library/Containers/com.apple.CloudDocsDaemon.StorageManagement/Data/Documents
0	./Library/Containers/com.apple.CloudDocsDaemon.StorageManagement/Data
48	./Library/Containers/com.apple.CloudDocsDaemon.StorageManagement
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/Application Support
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/Saved Application State
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/WebKit/WebsiteData/IndexedDB
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/WebKit/WebsiteData/MediaKeys
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/WebKit/WebsiteData/DeviceIdHashSalts/1
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/WebKit/WebsiteData/DeviceIdHashSalts
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/WebKit/WebsiteData/Default
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/WebKit/WebsiteData/WebSQL
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/WebKit/WebsiteData/LocalStorage
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/WebKit/WebsiteData/ResourceLoadStatistics
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/WebKit/WebsiteData
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/WebKit
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/Preferences
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/Application Scripts
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/Images
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/Logs
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/Caches/WebKit/OfflineWebApplicationCache
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/Caches/WebKit/NetworkCache
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/Caches/WebKit/CacheStorage
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/Caches/WebKit/ServiceWorkers
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/Caches/WebKit
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/Caches/com.apple.Safari/WebKitCache/OfflineWebApplicationCache
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/Caches/com.apple.Safari/WebKitCache
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/Caches/com.apple.Safari
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library/Caches
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Library
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data/Documents
0	./Library/Containers/com.apple.Safari.CacheDeleteExtension/Data
64	./Library/Containers/com.apple.Safari.CacheDeleteExtension
0	./Library/Containers/com.apple.AddressBook.ContactsAccountsService/Data/Library/Application Support
0	./Library/Containers/com.apple.AddressBook.ContactsAccountsService/Data/Library/Saved Application State
8	./Library/Containers/com.apple.AddressBook.ContactsAccountsService/Data/Library/Preferences
0	./Library/Containers/com.apple.AddressBook.ContactsAccountsService/Data/Library/Application Scripts
0	./Library/Containers/com.apple.AddressBook.ContactsAccountsService/Data/Library/Images
0	./Library/Containers/com.apple.AddressBook.ContactsAccountsService/Data/Library/Logs
0	./Library/Containers/com.apple.AddressBook.ContactsAccountsService/Data/Library/Caches
8	./Library/Containers/com.apple.AddressBook.ContactsAccountsService/Data/Library
0	./Library/Containers/com.apple.AddressBook.ContactsAccountsService/Data/Documents
8	./Library/Containers/com.apple.AddressBook.ContactsAccountsService/Data
64	./Library/Containers/com.apple.AddressBook.ContactsAccountsService
128	./Library/Containers/com.apple.ncplugin.stocks/Data/CloudKit/74897c20b5a9927ded72564b33138ee2f4e12f2b/Records
128	./Library/Containers/com.apple.ncplugin.stocks/Data/CloudKit/74897c20b5a9927ded72564b33138ee2f4e12f2b
272	./Library/Containers/com.apple.ncplugin.stocks/Data/CloudKit/539f4cadf8b7c07580a1765f20d360f55c5232d5/Records
0	./Library/Containers/com.apple.ncplugin.stocks/Data/CloudKit/539f4cadf8b7c07580a1765f20d360f55c5232d5/MMCS
0	./Library/Containers/com.apple.ncplugin.stocks/Data/CloudKit/539f4cadf8b7c07580a1765f20d360f55c5232d5/AssetsDb
272	./Library/Containers/com.apple.ncplugin.stocks/Data/CloudKit/539f4cadf8b7c07580a1765f20d360f55c5232d5
400	./Library/Containers/com.apple.ncplugin.stocks/Data/CloudKit
0	./Library/Containers/com.apple.ncplugin.stocks/Data/Library/Application Support
0	./Library/Containers/com.apple.ncplugin.stocks/Data/Library/Saved Application State
32	./Library/Containers/com.apple.ncplugin.stocks/Data/Library/Preferences
0	./Library/Containers/com.apple.ncplugin.stocks/Data/Library/Application Scripts
0	./Library/Containers/com.apple.ncplugin.stocks/Data/Library/Images
8	./Library/Containers/com.apple.ncplugin.stocks/Data/Library/SyncedPreferences
0	./Library/Containers/com.apple.ncplugin.stocks/Data/Library/Logs
0	./Library/Containers/com.apple.ncplugin.stocks/Data/Library/Caches/CloudKit/539f4cadf8b7c07580a1765f20d360f55c5232d5/StagingAssets
0	./Library/Containers/com.apple.ncplugin.stocks/Data/Library/Caches/CloudKit/539f4cadf8b7c07580a1765f20d360f55c5232d5/FrameworkCaches
0	./Library/Containers/com.apple.ncplugin.stocks/Data/Library/Caches/CloudKit/539f4cadf8b7c07580a1765f20d360f55c5232d5/Assets
0	./Library/Containers/com.apple.ncplugin.stocks/Data/Library/Caches/CloudKit/539f4cadf8b7c07580a1765f20d360f55c5232d5/tmp
0	./Library/Containers/com.apple.ncplugin.stocks/Data/Library/Caches/CloudKit/539f4cadf8b7c07580a1765f20d360f55c5232d5
0	./Library/Containers/com.apple.ncplugin.stocks/Data/Library/Caches/CloudKit
168	./Library/Containers/com.apple.ncplugin.stocks/Data/Library/Caches/com.apple.ncplugin.stocks
168	./Library/Containers/com.apple.ncplugin.stocks/Data/Library/Caches
208	./Library/Containers/com.apple.ncplugin.stocks/Data/Library
0	./Library/Containers/com.apple.ncplugin.stocks/Data/Documents
608	./Library/Containers/com.apple.ncplugin.stocks/Data
656	./Library/Containers/com.apple.ncplugin.stocks
0	./Library/Containers/com.apple.AMPArtworkAgent/Data/Library/Application Support
0	./Library/Containers/com.apple.AMPArtworkAgent/Data/Library/Saved Application State
0	./Library/Containers/com.apple.AMPArtworkAgent/Data/Library/Preferences
0	./Library/Containers/com.apple.AMPArtworkAgent/Data/Library/Application Scripts
0	./Library/Containers/com.apple.AMPArtworkAgent/Data/Library/Images
0	./Library/Containers/com.apple.AMPArtworkAgent/Data/Library/Logs
0	./Library/Containers/com.apple.AMPArtworkAgent/Data/Library/Caches
0	./Library/Containers/com.apple.AMPArtworkAgent/Data/Library
0	./Library/Containers/com.apple.AMPArtworkAgent/Data/Documents/artwork
896	./Library/Containers/com.apple.AMPArtworkAgent/Data/Documents
896	./Library/Containers/com.apple.AMPArtworkAgent/Data
952	./Library/Containers/com.apple.AMPArtworkAgent
0	./Library/Containers/com.apple.iBooksX.DiskSpaceEfficiency/Data/Library/Application Support
0	./Library/Containers/com.apple.iBooksX.DiskSpaceEfficiency/Data/Library/Saved Application State
0	./Library/Containers/com.apple.iBooksX.DiskSpaceEfficiency/Data/Library/Preferences
0	./Library/Containers/com.apple.iBooksX.DiskSpaceEfficiency/Data/Library/Application Scripts
0	./Library/Containers/com.apple.iBooksX.DiskSpaceEfficiency/Data/Library/Images
0	./Library/Containers/com.apple.iBooksX.DiskSpaceEfficiency/Data/Library/Logs
0	./Library/Containers/com.apple.iBooksX.DiskSpaceEfficiency/Data/Library/Caches
0	./Library/Containers/com.apple.iBooksX.DiskSpaceEfficiency/Data/Library
0	./Library/Containers/com.apple.iBooksX.DiskSpaceEfficiency/Data/Documents
0	./Library/Containers/com.apple.iBooksX.DiskSpaceEfficiency/Data
48	./Library/Containers/com.apple.iBooksX.DiskSpaceEfficiency
0	./Library/Containers/com.apple.messages.StorageManagementExtension/Data/Library/Application Support
0	./Library/Containers/com.apple.messages.StorageManagementExtension/Data/Library/Saved Application State
0	./Library/Containers/com.apple.messages.StorageManagementExtension/Data/Library/Preferences
0	./Library/Containers/com.apple.messages.StorageManagementExtension/Data/Library/Application Scripts
0	./Library/Containers/com.apple.messages.StorageManagementExtension/Data/Library/Images
0	./Library/Containers/com.apple.messages.StorageManagementExtension/Data/Library/Logs
0	./Library/Containers/com.apple.messages.StorageManagementExtension/Data/Library/Caches
0	./Library/Containers/com.apple.messages.StorageManagementExtension/Data/Library
0	./Library/Containers/com.apple.messages.StorageManagementExtension/Data/Documents
0	./Library/Containers/com.apple.messages.StorageManagementExtension/Data
56	./Library/Containers/com.apple.messages.StorageManagementExtension
5824	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/FontPreviewCache/en-US
5824	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/FontPreviewCache
16	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Temp
1872	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/OTele
16920	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/DTS/en-US{685809DD-E207-CD4F-8D9C-518CE9A1F05E}
16920	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/DTS
40	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/Floodgate
0	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/MruServiceCache/UnsignedUser/Word
0	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/MruServiceCache/UnsignedUser
16	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/MruServiceCache/930455765e627a21_LiveId/Word
16	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/MruServiceCache/930455765e627a21_LiveId
16	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/MruServiceCache
0	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/aggmru/930455765e627a21_LiveId
0	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/aggmru
0	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/BackstageInAppNavCache/OD-Rcrawford6971@outlook.com
0	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/BackstageInAppNavCache/SharePoint-
0	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/BackstageInAppNavCache
288	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/WebServiceCache/AllUsers/officeclient.microsoft.com
288	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/WebServiceCache/AllUsers
288	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/WebServiceCache
0	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/DocumentActivityQueue
0	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/DisplayForm
17784	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0
19656	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office
544	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/FontCache
0	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Feedback
64	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/AppData/Microsoft/Office/16.0/OfficeFileCache/0/0/BFBTH7CEHDFEFDEMBFCLBYAIA3C6CQE7
64	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/AppData/Microsoft/Office/16.0/OfficeFileCache/0/0
64	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/AppData/Microsoft/Office/16.0/OfficeFileCache/0
64	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/AppData/Microsoft/Office/16.0/OfficeFileCache
64	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/AppData/Microsoft/Office/16.0
0	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/AppData/Microsoft/Office/FeatureFlags/Settings/0
0	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/AppData/Microsoft/Office/FeatureFlags/Settings
0	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/AppData/Microsoft/Office/FeatureFlags
64	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/AppData/Microsoft/Office
64	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/AppData/Microsoft
72	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/AppData
26112	./Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft
26120	./Library/Containers/com.microsoft.Word/Data/Library/Application Support
48	./Library/Containers/com.microsoft.Word/Data/Library/Saved Application State/com.microsoft.Word.savedState
48	./Library/Containers/com.microsoft.Word/Data/Library/Saved Application State
0	./Library/Containers/com.microsoft.Word/Data/Library/WebKit/Databases
0	./Library/Containers/com.microsoft.Word/Data/Library/WebKit
56	./Library/Containers/com.microsoft.Word/Data/Library/Preferences/AutoRecovery
72	./Library/Containers/com.microsoft.Word/Data/Library/Preferences
0	./Library/Containers/com.microsoft.Word/Data/Library/Application Scripts
0	./Library/Containers/com.microsoft.Word/Data/Library/Images
0	./Library/Containers/com.microsoft.Word/Data/Library/Logs
8	./Library/Containers/com.microsoft.Word/Data/Library/Cookies
4120	./Library/Containers/com.microsoft.Word/Data/Library/Caches/Microsoft/uls/com.microsoft.Word/logs
4120	./Library/Containers/com.microsoft.Word/Data/Library/Caches/Microsoft/uls/com.microsoft.Word
4120	./Library/Containers/com.microsoft.Word/Data/Library/Caches/Microsoft/uls
4184	./Library/Containers/com.microsoft.Word/Data/Library/Caches/Microsoft
7608	./Library/Containers/com.microsoft.Word/Data/Library/Caches/com.microsoft.Word/fsCachedData
13936	./Library/Containers/com.microsoft.Word/Data/Library/Caches/com.microsoft.Word
48	./Library/Containers/com.microsoft.Word/Data/Library/Caches/com.microsoft.ctrlstrcaches
18168	./Library/Containers/com.microsoft.Word/Data/Library/Caches
44416	./Library/Containers/com.microsoft.Word/Data/Library
0	./Library/Containers/com.microsoft.Word/Data/Documents
44416	./Library/Containers/com.microsoft.Word/Data
44488	./Library/Containers/com.microsoft.Word
0	./Library/Containers/com.apple.STMExtension.AppleInternal/Data/Library/Application Support
0	./Library/Containers/com.apple.STMExtension.AppleInternal/Data/Library/Saved Application State
0	./Library/Containers/com.apple.STMExtension.AppleInternal/Data/Library/Preferences
0	./Library/Containers/com.apple.STMExtension.AppleInternal/Data/Library/Application Scripts
0	./Library/Containers/com.apple.STMExtension.AppleInternal/Data/Library/Images
0	./Library/Containers/com.apple.STMExtension.AppleInternal/Data/Library/Logs
0	./Library/Containers/com.apple.STMExtension.AppleInternal/Data/Library/Caches
0	./Library/Containers/com.apple.STMExtension.AppleInternal/Data/Library
0	./Library/Containers/com.apple.STMExtension.AppleInternal/Data/Documents
0	./Library/Containers/com.apple.STMExtension.AppleInternal/Data
40	./Library/Containers/com.apple.STMExtension.AppleInternal
0	./Library/Containers/com.apple.preferencepane.security.AdvertisingExtension/Data/Library/Application Support
0	./Library/Containers/com.apple.preferencepane.security.AdvertisingExtension/Data/Library/Saved Application State
0	./Library/Containers/com.apple.preferencepane.security.AdvertisingExtension/Data/Library/Preferences
0	./Library/Containers/com.apple.preferencepane.security.AdvertisingExtension/Data/Library/Application Scripts
0	./Library/Containers/com.apple.preferencepane.security.AdvertisingExtension/Data/Library/Images
0	./Library/Containers/com.apple.preferencepane.security.AdvertisingExtension/Data/Library/Logs
0	./Library/Containers/com.apple.preferencepane.security.AdvertisingExtension/Data/Library/Caches
0	./Library/Containers/com.apple.preferencepane.security.AdvertisingExtension/Data/Library
0	./Library/Containers/com.apple.preferencepane.security.AdvertisingExtension/Data/Documents
0	./Library/Containers/com.apple.preferencepane.security.AdvertisingExtension/Data
56	./Library/Containers/com.apple.preferencepane.security.AdvertisingExtension
0	./Library/Containers/com.apple.STMExtension.CloudFiles/Data/Library/Application Support
0	./Library/Containers/com.apple.STMExtension.CloudFiles/Data/Library/Saved Application State
0	./Library/Containers/com.apple.STMExtension.CloudFiles/Data/Library/Preferences
0	./Library/Containers/com.apple.STMExtension.CloudFiles/Data/Library/Application Scripts
0	./Library/Containers/com.apple.STMExtension.CloudFiles/Data/Library/Images
0	./Library/Containers/com.apple.STMExtension.CloudFiles/Data/Library/Logs
0	./Library/Containers/com.apple.STMExtension.CloudFiles/Data/Library/Caches
0	./Library/Containers/com.apple.STMExtension.CloudFiles/Data/Library
0	./Library/Containers/com.apple.STMExtension.CloudFiles/Data/Documents
0	./Library/Containers/com.apple.STMExtension.CloudFiles/Data
48	./Library/Containers/com.apple.STMExtension.CloudFiles
0	./Library/Containers/com.apple.STMExtension.OtherUsers/Data/Library/Application Support
0	./Library/Containers/com.apple.STMExtension.OtherUsers/Data/Library/Saved Application State
0	./Library/Containers/com.apple.STMExtension.OtherUsers/Data/Library/Preferences
0	./Library/Containers/com.apple.STMExtension.OtherUsers/Data/Library/Application Scripts
0	./Library/Containers/com.apple.STMExtension.OtherUsers/Data/Library/Images
0	./Library/Containers/com.apple.STMExtension.OtherUsers/Data/Library/Logs
0	./Library/Containers/com.apple.STMExtension.OtherUsers/Data/Library/Caches
0	./Library/Containers/com.apple.STMExtension.OtherUsers/Data/Library
0	./Library/Containers/com.apple.STMExtension.OtherUsers/Data/Documents
0	./Library/Containers/com.apple.STMExtension.OtherUsers/Data
48	./Library/Containers/com.apple.STMExtension.OtherUsers
0	./Library/Containers/com.apple.photoanalysisd/Data/Library/Application Support
0	./Library/Containers/com.apple.photoanalysisd/Data/Library/Saved Application State
8	./Library/Containers/com.apple.photoanalysisd/Data/Library/Preferences
0	./Library/Containers/com.apple.photoanalysisd/Data/Library/Application Scripts
0	./Library/Containers/com.apple.photoanalysisd/Data/Library/Images
0	./Library/Containers/com.apple.photoanalysisd/Data/Library/Logs
0	./Library/Containers/com.apple.photoanalysisd/Data/Library/Caches
8	./Library/Containers/com.apple.photoanalysisd/Data/Library
0	./Library/Containers/com.apple.photoanalysisd/Data/Documents
8	./Library/Containers/com.apple.photoanalysisd/Data
72	./Library/Containers/com.apple.photoanalysisd
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/Application Support
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/Saved Application State
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/WebKit/WebsiteData/IndexedDB
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/WebKit/WebsiteData/MediaKeys
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/WebKit/WebsiteData/WebSQL
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/WebKit/WebsiteData/LocalStorage
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/WebKit/WebsiteData/ResourceLoadStatistics
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/WebKit/WebsiteData
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/WebKit
8	./Library/Containers/com.apple.amp.devicesui/Data/Library/Preferences
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/Application Scripts
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/Images
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/Logs
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/Caches/WebKit/OfflineWebApplicationCache
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/Caches/WebKit/NetworkCache
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/Caches/WebKit/CacheStorage
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/Caches/WebKit/ServiceWorkers
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/Caches/WebKit
0	./Library/Containers/com.apple.amp.devicesui/Data/Library/Caches
8	./Library/Containers/com.apple.amp.devicesui/Data/Library
0	./Library/Containers/com.apple.amp.devicesui/Data/Documents
8	./Library/Containers/com.apple.amp.devicesui/Data
56	./Library/Containers/com.apple.amp.devicesui
0	./Library/Containers/com.apple.MediaLibraryService/Data/Library/Application Support
0	./Library/Containers/com.apple.MediaLibraryService/Data/Library/Saved Application State
0	./Library/Containers/com.apple.MediaLibraryService/Data/Library/Preferences
0	./Library/Containers/com.apple.MediaLibraryService/Data/Library/Application Scripts
0	./Library/Containers/com.apple.MediaLibraryService/Data/Library/Images
0	./Library/Containers/com.apple.MediaLibraryService/Data/Library/Logs
0	./Library/Containers/com.apple.MediaLibraryService/Data/Library/Caches
0	./Library/Containers/com.apple.MediaLibraryService/Data/Library
0	./Library/Containers/com.apple.MediaLibraryService/Data/Documents
0	./Library/Containers/com.apple.MediaLibraryService/Data
48	./Library/Containers/com.apple.MediaLibraryService
du: ./Library/Containers/com.apple.iChat: Operation not permitted
du: ./Library/Containers/com.apple.CloudDocs.MobileDocumentsFileProvider: Operation not permitted
0	./Library/Containers/com.apple.TV.TVStorageExtension/Data/Library/Application Support
0	./Library/Containers/com.apple.TV.TVStorageExtension/Data/Library/Saved Application State
0	./Library/Containers/com.apple.TV.TVStorageExtension/Data/Library/Preferences
0	./Library/Containers/com.apple.TV.TVStorageExtension/Data/Library/Application Scripts
0	./Library/Containers/com.apple.TV.TVStorageExtension/Data/Library/Images
0	./Library/Containers/com.apple.TV.TVStorageExtension/Data/Library/Logs
0	./Library/Containers/com.apple.TV.TVStorageExtension/Data/Library/Caches
0	./Library/Containers/com.apple.TV.TVStorageExtension/Data/Library
0	./Library/Containers/com.apple.TV.TVStorageExtension/Data/Documents
0	./Library/Containers/com.apple.TV.TVStorageExtension/Data
48	./Library/Containers/com.apple.TV.TVStorageExtension
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.ContentBlockerExtension/Data/Library/Application Support
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.ContentBlockerExtension/Data/Library/Saved Application State
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.ContentBlockerExtension/Data/Library/Preferences
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.ContentBlockerExtension/Data/Library/Application Scripts
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.ContentBlockerExtension/Data/Library/Images
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.ContentBlockerExtension/Data/Library/Logs
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.ContentBlockerExtension/Data/Library/Caches
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.ContentBlockerExtension/Data/Library
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.ContentBlockerExtension/Data/Documents
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.ContentBlockerExtension/Data
56	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.ContentBlockerExtension
0	./Library/Containers/com.apple.DataDetectorsLocalSources/Data/Library/Application Support
0	./Library/Containers/com.apple.DataDetectorsLocalSources/Data/Library/Saved Application State
0	./Library/Containers/com.apple.DataDetectorsLocalSources/Data/Library/Preferences
0	./Library/Containers/com.apple.DataDetectorsLocalSources/Data/Library/Application Scripts
0	./Library/Containers/com.apple.DataDetectorsLocalSources/Data/Library/Images
0	./Library/Containers/com.apple.DataDetectorsLocalSources/Data/Library/Logs
0	./Library/Containers/com.apple.DataDetectorsLocalSources/Data/Library/Caches
0	./Library/Containers/com.apple.DataDetectorsLocalSources/Data/Library
0	./Library/Containers/com.apple.DataDetectorsLocalSources/Data/Documents
0	./Library/Containers/com.apple.DataDetectorsLocalSources/Data
56	./Library/Containers/com.apple.DataDetectorsLocalSources
0	./Library/Containers/com.askvideo.AOM000836/Data/Library/Application Support
0	./Library/Containers/com.askvideo.AOM000836/Data/Library/Saved Application State
0	./Library/Containers/com.askvideo.AOM000836/Data/Library/Preferences
0	./Library/Containers/com.askvideo.AOM000836/Data/Library/Application Scripts
0	./Library/Containers/com.askvideo.AOM000836/Data/Library/Images
0	./Library/Containers/com.askvideo.AOM000836/Data/Library/Logs
0	./Library/Containers/com.askvideo.AOM000836/Data/Library/Caches
0	./Library/Containers/com.askvideo.AOM000836/Data/Library
0	./Library/Containers/com.askvideo.AOM000836/Data/Documents
0	./Library/Containers/com.askvideo.AOM000836/Data
40	./Library/Containers/com.askvideo.AOM000836
0	./Library/Containers/com.apple.Photos/Data/Library/Application Support
0	./Library/Containers/com.apple.Photos/Data/Library/Saved Application State
24	./Library/Containers/com.apple.Photos/Data/Library/Preferences
0	./Library/Containers/com.apple.Photos/Data/Library/Application Scripts
0	./Library/Containers/com.apple.Photos/Data/Library/Images
0	./Library/Containers/com.apple.Photos/Data/Library/Logs
0	./Library/Containers/com.apple.Photos/Data/Library/Caches/Photos_Cache.noindex
0	./Library/Containers/com.apple.Photos/Data/Library/Caches
24	./Library/Containers/com.apple.Photos/Data/Library
0	./Library/Containers/com.apple.Photos/Data/Documents
24	./Library/Containers/com.apple.Photos/Data
96	./Library/Containers/com.apple.Photos
0	./Library/Containers/com.apple.ContactsAgent/Data/Library/Application Support
0	./Library/Containers/com.apple.ContactsAgent/Data/Library/Saved Application State
0	./Library/Containers/com.apple.ContactsAgent/Data/Library/Preferences
0	./Library/Containers/com.apple.ContactsAgent/Data/Library/Application Scripts
0	./Library/Containers/com.apple.ContactsAgent/Data/Library/Images
0	./Library/Containers/com.apple.ContactsAgent/Data/Library/Logs
0	./Library/Containers/com.apple.ContactsAgent/Data/Library/Caches
0	./Library/Containers/com.apple.ContactsAgent/Data/Library
0	./Library/Containers/com.apple.ContactsAgent/Data/Documents
0	./Library/Containers/com.apple.ContactsAgent/Data
56	./Library/Containers/com.apple.ContactsAgent
0	./Library/Containers/com.apple.Music.MusicCacheExtension/Data/Library/Application Support
0	./Library/Containers/com.apple.Music.MusicCacheExtension/Data/Library/Saved Application State
0	./Library/Containers/com.apple.Music.MusicCacheExtension/Data/Library/Preferences
0	./Library/Containers/com.apple.Music.MusicCacheExtension/Data/Library/Application Scripts
0	./Library/Containers/com.apple.Music.MusicCacheExtension/Data/Library/Images
0	./Library/Containers/com.apple.Music.MusicCacheExtension/Data/Library/Logs
0	./Library/Containers/com.apple.Music.MusicCacheExtension/Data/Library/Caches
0	./Library/Containers/com.apple.Music.MusicCacheExtension/Data/Library
0	./Library/Containers/com.apple.Music.MusicCacheExtension/Data/Documents
0	./Library/Containers/com.apple.Music.MusicCacheExtension/Data
48	./Library/Containers/com.apple.Music.MusicCacheExtension
0	./Library/Containers/com.apple.AppStore/Data/Library/Application Support
0	./Library/Containers/com.apple.AppStore/Data/Library/Saved Application State
8	./Library/Containers/com.apple.AppStore/Data/Library/Preferences
0	./Library/Containers/com.apple.AppStore/Data/Library/Application Scripts
0	./Library/Containers/com.apple.AppStore/Data/Library/Images
0	./Library/Containers/com.apple.AppStore/Data/Library/Logs
21976	./Library/Containers/com.apple.AppStore/Data/Library/Caches/com.apple.AppStore/fsCachedData
33008	./Library/Containers/com.apple.AppStore/Data/Library/Caches/com.apple.AppStore
8	./Library/Containers/com.apple.AppStore/Data/Library/Caches/com.apple.AppleMediaServices
33016	./Library/Containers/com.apple.AppStore/Data/Library/Caches
33024	./Library/Containers/com.apple.AppStore/Data/Library
0	./Library/Containers/com.apple.AppStore/Data/Documents
33024	./Library/Containers/com.apple.AppStore/Data
33088	./Library/Containers/com.apple.AppStore
272	./Library/Containers/com.apple.Notes/Data/CloudKit/a0f2dad3d7742cad28f787c1cbb05be004342d12/Records
0	./Library/Containers/com.apple.Notes/Data/CloudKit/a0f2dad3d7742cad28f787c1cbb05be004342d12/MMCS
0	./Library/Containers/com.apple.Notes/Data/CloudKit/a0f2dad3d7742cad28f787c1cbb05be004342d12/AssetsDb
272	./Library/Containers/com.apple.Notes/Data/CloudKit/a0f2dad3d7742cad28f787c1cbb05be004342d12
272	./Library/Containers/com.apple.Notes/Data/CloudKit
0	./Library/Containers/com.apple.Notes/Data/Library/Application Support/Notes
0	./Library/Containers/com.apple.Notes/Data/Library/Application Support
0	./Library/Containers/com.apple.Notes/Data/Library/Saved Application State
16	./Library/Containers/com.apple.Notes/Data/Library/Preferences/ByHost
24	./Library/Containers/com.apple.Notes/Data/Library/Preferences
0	./Library/Containers/com.apple.Notes/Data/Library/Application Scripts
0	./Library/Containers/com.apple.Notes/Data/Library/Images
0	./Library/Containers/com.apple.Notes/Data/Library/Logs
848	./Library/Containers/com.apple.Notes/Data/Library/Notes
0	./Library/Containers/com.apple.Notes/Data/Library/Caches/CloudKit/a0f2dad3d7742cad28f787c1cbb05be004342d12/StagingAssets
0	./Library/Containers/com.apple.Notes/Data/Library/Caches/CloudKit/a0f2dad3d7742cad28f787c1cbb05be004342d12/FrameworkCaches
0	./Library/Containers/com.apple.Notes/Data/Library/Caches/CloudKit/a0f2dad3d7742cad28f787c1cbb05be004342d12/Assets
0	./Library/Containers/com.apple.Notes/Data/Library/Caches/CloudKit/a0f2dad3d7742cad28f787c1cbb05be004342d12/tmp
0	./Library/Containers/com.apple.Notes/Data/Library/Caches/CloudKit/a0f2dad3d7742cad28f787c1cbb05be004342d12
0	./Library/Containers/com.apple.Notes/Data/Library/Caches/CloudKit
168	./Library/Containers/com.apple.Notes/Data/Library/Caches/com.apple.Notes
168	./Library/Containers/com.apple.Notes/Data/Library/Caches
1040	./Library/Containers/com.apple.Notes/Data/Library
0	./Library/Containers/com.apple.Notes/Data/Documents
1312	./Library/Containers/com.apple.Notes/Data
1384	./Library/Containers/com.apple.Notes
0	./Library/Containers/com.apple.STMExtension.Trash/Data/Library/Application Support
0	./Library/Containers/com.apple.STMExtension.Trash/Data/Library/Saved Application State
0	./Library/Containers/com.apple.STMExtension.Trash/Data/Library/Preferences
0	./Library/Containers/com.apple.STMExtension.Trash/Data/Library/Application Scripts
0	./Library/Containers/com.apple.STMExtension.Trash/Data/Library/Images
0	./Library/Containers/com.apple.STMExtension.Trash/Data/Library/Logs
0	./Library/Containers/com.apple.STMExtension.Trash/Data/Library/Caches
0	./Library/Containers/com.apple.STMExtension.Trash/Data/Library
0	./Library/Containers/com.apple.STMExtension.Trash/Data/Documents
0	./Library/Containers/com.apple.STMExtension.Trash/Data
48	./Library/Containers/com.apple.STMExtension.Trash
0	./Library/Containers/com.apple.MailCacheDelete/Data/Library/Application Support
0	./Library/Containers/com.apple.MailCacheDelete/Data/Library/Mail Downloads
0	./Library/Containers/com.apple.MailCacheDelete/Data/Library/Saved Application State
0	./Library/Containers/com.apple.MailCacheDelete/Data/Library/Preferences
0	./Library/Containers/com.apple.MailCacheDelete/Data/Library/Application Scripts
0	./Library/Containers/com.apple.MailCacheDelete/Data/Library/Images
0	./Library/Containers/com.apple.MailCacheDelete/Data/Library/Logs
0	./Library/Containers/com.apple.MailCacheDelete/Data/Library/Caches
0	./Library/Containers/com.apple.MailCacheDelete/Data/Library
0	./Library/Containers/com.apple.MailCacheDelete/Data/Documents
0	./Library/Containers/com.apple.MailCacheDelete/Data
56	./Library/Containers/com.apple.MailCacheDelete
0	./Library/Containers/com.apple.STMExtension.iOSFiles/Data/Library/Application Support
0	./Library/Containers/com.apple.STMExtension.iOSFiles/Data/Library/Saved Application State
0	./Library/Containers/com.apple.STMExtension.iOSFiles/Data/Library/Preferences
0	./Library/Containers/com.apple.STMExtension.iOSFiles/Data/Library/Application Scripts
0	./Library/Containers/com.apple.STMExtension.iOSFiles/Data/Library/Images
0	./Library/Containers/com.apple.STMExtension.iOSFiles/Data/Library/Logs
0	./Library/Containers/com.apple.STMExtension.iOSFiles/Data/Library/Caches
0	./Library/Containers/com.apple.STMExtension.iOSFiles/Data/Library
0	./Library/Containers/com.apple.STMExtension.iOSFiles/Data/Documents
0	./Library/Containers/com.apple.STMExtension.iOSFiles/Data
48	./Library/Containers/com.apple.STMExtension.iOSFiles
0	./Library/Containers/com.apple.STMExtension.Applications/Data/Library/Application Support
0	./Library/Containers/com.apple.STMExtension.Applications/Data/Library/Saved Application State
0	./Library/Containers/com.apple.STMExtension.Applications/Data/Library/Preferences
0	./Library/Containers/com.apple.STMExtension.Applications/Data/Library/Application Scripts
0	./Library/Containers/com.apple.STMExtension.Applications/Data/Library/Images
0	./Library/Containers/com.apple.STMExtension.Applications/Data/Library/Logs
0	./Library/Containers/com.apple.STMExtension.Applications/Data/Library/Caches
0	./Library/Containers/com.apple.STMExtension.Applications/Data/Library
0	./Library/Containers/com.apple.STMExtension.Applications/Data/Documents
0	./Library/Containers/com.apple.STMExtension.Applications/Data
48	./Library/Containers/com.apple.STMExtension.Applications
0	./Library/Containers/com.apple.Dictionary/Data/Library/Application Support
0	./Library/Containers/com.apple.Dictionary/Data/Library/Saved Application State
0	./Library/Containers/com.apple.Dictionary/Data/Library/WebKit/Databases
0	./Library/Containers/com.apple.Dictionary/Data/Library/WebKit
8	./Library/Containers/com.apple.Dictionary/Data/Library/Preferences
0	./Library/Containers/com.apple.Dictionary/Data/Library/Application Scripts
0	./Library/Containers/com.apple.Dictionary/Data/Library/Images
0	./Library/Containers/com.apple.Dictionary/Data/Library/Logs
8	./Library/Containers/com.apple.Dictionary/Data/Library/Caches/com.apple.DictionaryServices
168	./Library/Containers/com.apple.Dictionary/Data/Library/Caches/com.apple.Dictionary
176	./Library/Containers/com.apple.Dictionary/Data/Library/Caches
184	./Library/Containers/com.apple.Dictionary/Data/Library
0	./Library/Containers/com.apple.Dictionary/Data/Documents
184	./Library/Containers/com.apple.Dictionary/Data
240	./Library/Containers/com.apple.Dictionary
0	./Library/Containers/com.apple.TextEdit/Data/Library/Application Support
0	./Library/Containers/com.apple.TextEdit/Data/Library/Autosave Information
56	./Library/Containers/com.apple.TextEdit/Data/Library/Saved Application State/com.apple.TextEdit.savedState
56	./Library/Containers/com.apple.TextEdit/Data/Library/Saved Application State
8	./Library/Containers/com.apple.TextEdit/Data/Library/Preferences
0	./Library/Containers/com.apple.TextEdit/Data/Library/Application Scripts
0	./Library/Containers/com.apple.TextEdit/Data/Library/Images
0	./Library/Containers/com.apple.TextEdit/Data/Library/Logs
0	./Library/Containers/com.apple.TextEdit/Data/Library/Caches
64	./Library/Containers/com.apple.TextEdit/Data/Library
0	./Library/Containers/com.apple.TextEdit/Data/Documents
64	./Library/Containers/com.apple.TextEdit/Data
104	./Library/Containers/com.apple.TextEdit
0	./Library/Containers/com.apple.CryptoTokenKit.pivtoken/Data/Library/Application Support
0	./Library/Containers/com.apple.CryptoTokenKit.pivtoken/Data/Library/Saved Application State
0	./Library/Containers/com.apple.CryptoTokenKit.pivtoken/Data/Library/Preferences
0	./Library/Containers/com.apple.CryptoTokenKit.pivtoken/Data/Library/Application Scripts
0	./Library/Containers/com.apple.CryptoTokenKit.pivtoken/Data/Library/Images
0	./Library/Containers/com.apple.CryptoTokenKit.pivtoken/Data/Library/Logs
0	./Library/Containers/com.apple.CryptoTokenKit.pivtoken/Data/Library/Caches
0	./Library/Containers/com.apple.CryptoTokenKit.pivtoken/Data/Library
0	./Library/Containers/com.apple.CryptoTokenKit.pivtoken/Data/Documents
0	./Library/Containers/com.apple.CryptoTokenKit.pivtoken/Data
40	./Library/Containers/com.apple.CryptoTokenKit.pivtoken
0	./Library/Containers/com.apple.Music.MusicStorageExtension/Data/Library/Application Support
0	./Library/Containers/com.apple.Music.MusicStorageExtension/Data/Library/Saved Application State
0	./Library/Containers/com.apple.Music.MusicStorageExtension/Data/Library/Preferences
0	./Library/Containers/com.apple.Music.MusicStorageExtension/Data/Library/Application Scripts
0	./Library/Containers/com.apple.Music.MusicStorageExtension/Data/Library/Images
0	./Library/Containers/com.apple.Music.MusicStorageExtension/Data/Library/Logs
0	./Library/Containers/com.apple.Music.MusicStorageExtension/Data/Library/Caches
0	./Library/Containers/com.apple.Music.MusicStorageExtension/Data/Library
0	./Library/Containers/com.apple.Music.MusicStorageExtension/Data/Documents
0	./Library/Containers/com.apple.Music.MusicStorageExtension/Data
48	./Library/Containers/com.apple.Music.MusicStorageExtension
0	./Library/Containers/com.apple.Photos.StorageManagementExtension/Data/Library/Application Support
0	./Library/Containers/com.apple.Photos.StorageManagementExtension/Data/Library/Saved Application State
0	./Library/Containers/com.apple.Photos.StorageManagementExtension/Data/Library/Preferences
0	./Library/Containers/com.apple.Photos.StorageManagementExtension/Data/Library/Application Scripts
0	./Library/Containers/com.apple.Photos.StorageManagementExtension/Data/Library/Images
0	./Library/Containers/com.apple.Photos.StorageManagementExtension/Data/Library/Logs
0	./Library/Containers/com.apple.Photos.StorageManagementExtension/Data/Library/Caches
0	./Library/Containers/com.apple.Photos.StorageManagementExtension/Data/Library
0	./Library/Containers/com.apple.Photos.StorageManagementExtension/Data/Documents
0	./Library/Containers/com.apple.Photos.StorageManagementExtension/Data
48	./Library/Containers/com.apple.Photos.StorageManagementExtension
0	./Library/Containers/com.apple.geod/Data/Library/Application Support
0	./Library/Containers/com.apple.geod/Data/Library/Saved Application State
0	./Library/Containers/com.apple.geod/Data/Library/Preferences
0	./Library/Containers/com.apple.geod/Data/Library/Application Scripts
0	./Library/Containers/com.apple.geod/Data/Library/Images
0	./Library/Containers/com.apple.geod/Data/Library/Logs
0	./Library/Containers/com.apple.geod/Data/Library/Caches/com.apple.nsurlsessiond/Downloads/com.apple.geod
0	./Library/Containers/com.apple.geod/Data/Library/Caches/com.apple.nsurlsessiond/Downloads
0	./Library/Containers/com.apple.geod/Data/Library/Caches/com.apple.nsurlsessiond
0	./Library/Containers/com.apple.geod/Data/Library/Caches/com.apple.geod/MapTiles/ExternalData
256	./Library/Containers/com.apple.geod/Data/Library/Caches/com.apple.geod/MapTiles
0	./Library/Containers/com.apple.geod/Data/Library/Caches/com.apple.geod/Analytics
5056	./Library/Containers/com.apple.geod/Data/Library/Caches/com.apple.geod
5056	./Library/Containers/com.apple.geod/Data/Library/Caches
5056	./Library/Containers/com.apple.geod/Data/Library
0	./Library/Containers/com.apple.geod/Data/Documents
5056	./Library/Containers/com.apple.geod/Data
5104	./Library/Containers/com.apple.geod
0	./Library/Containers/com.apple.TV.TVCacheExtension/Data/Library/Application Support
0	./Library/Containers/com.apple.TV.TVCacheExtension/Data/Library/Saved Application State
0	./Library/Containers/com.apple.TV.TVCacheExtension/Data/Library/Preferences
0	./Library/Containers/com.apple.TV.TVCacheExtension/Data/Library/Application Scripts
0	./Library/Containers/com.apple.TV.TVCacheExtension/Data/Library/Images
0	./Library/Containers/com.apple.TV.TVCacheExtension/Data/Library/Logs
0	./Library/Containers/com.apple.TV.TVCacheExtension/Data/Library/Caches
0	./Library/Containers/com.apple.TV.TVCacheExtension/Data/Library
0	./Library/Containers/com.apple.TV.TVCacheExtension/Data/Documents
0	./Library/Containers/com.apple.TV.TVCacheExtension/Data
48	./Library/Containers/com.apple.TV.TVCacheExtension
0	./Library/Containers/com.apple.CalendarAgent/Data/Library/Application Support
0	./Library/Containers/com.apple.CalendarAgent/Data/Library/Saved Application State
8	./Library/Containers/com.apple.CalendarAgent/Data/Library/Preferences
0	./Library/Containers/com.apple.CalendarAgent/Data/Library/Application Scripts
0	./Library/Containers/com.apple.CalendarAgent/Data/Library/Images
0	./Library/Containers/com.apple.CalendarAgent/Data/Library/Logs
168	./Library/Containers/com.apple.CalendarAgent/Data/Library/Caches/com.apple.CalendarAgent
168	./Library/Containers/com.apple.CalendarAgent/Data/Library/Caches
176	./Library/Containers/com.apple.CalendarAgent/Data/Library
0	./Library/Containers/com.apple.CalendarAgent/Data/Documents
176	./Library/Containers/com.apple.CalendarAgent/Data
240	./Library/Containers/com.apple.CalendarAgent
0	./Library/Containers/com.apple.Safari.SafariQuickLookPreview/Data/Library/Application Support
0	./Library/Containers/com.apple.Safari.SafariQuickLookPreview/Data/Library/Saved Application State
8	./Library/Containers/com.apple.Safari.SafariQuickLookPreview/Data/Library/Preferences
0	./Library/Containers/com.apple.Safari.SafariQuickLookPreview/Data/Library/Application Scripts
0	./Library/Containers/com.apple.Safari.SafariQuickLookPreview/Data/Library/Images
0	./Library/Containers/com.apple.Safari.SafariQuickLookPreview/Data/Library/Logs
0	./Library/Containers/com.apple.Safari.SafariQuickLookPreview/Data/Library/Caches
8	./Library/Containers/com.apple.Safari.SafariQuickLookPreview/Data/Library
0	./Library/Containers/com.apple.Safari.SafariQuickLookPreview/Data/Documents
8	./Library/Containers/com.apple.Safari.SafariQuickLookPreview/Data
64	./Library/Containers/com.apple.Safari.SafariQuickLookPreview
0	./Library/Containers/com.apple.preferencepane.security.PrivacyAnalytics/Data/Library/Application Support
0	./Library/Containers/com.apple.preferencepane.security.PrivacyAnalytics/Data/Library/Saved Application State
0	./Library/Containers/com.apple.preferencepane.security.PrivacyAnalytics/Data/Library/Preferences
0	./Library/Containers/com.apple.preferencepane.security.PrivacyAnalytics/Data/Library/Application Scripts
0	./Library/Containers/com.apple.preferencepane.security.PrivacyAnalytics/Data/Library/Images
0	./Library/Containers/com.apple.preferencepane.security.PrivacyAnalytics/Data/Library/Logs
0	./Library/Containers/com.apple.preferencepane.security.PrivacyAnalytics/Data/Library/Caches
0	./Library/Containers/com.apple.preferencepane.security.PrivacyAnalytics/Data/Library
0	./Library/Containers/com.apple.preferencepane.security.PrivacyAnalytics/Data/Documents
0	./Library/Containers/com.apple.preferencepane.security.PrivacyAnalytics/Data
48	./Library/Containers/com.apple.preferencepane.security.PrivacyAnalytics
0	./Library/Containers/com.apple.DataDetectorsViewService/Data/Library/Application Support
0	./Library/Containers/com.apple.DataDetectorsViewService/Data/Library/Saved Application State
0	./Library/Containers/com.apple.DataDetectorsViewService/Data/Library/Preferences
0	./Library/Containers/com.apple.DataDetectorsViewService/Data/Library/Application Scripts
0	./Library/Containers/com.apple.DataDetectorsViewService/Data/Library/Images
0	./Library/Containers/com.apple.DataDetectorsViewService/Data/Library/Logs
0	./Library/Containers/com.apple.DataDetectorsViewService/Data/Library/Caches
0	./Library/Containers/com.apple.DataDetectorsViewService/Data/Library
0	./Library/Containers/com.apple.DataDetectorsViewService/Data/Documents
0	./Library/Containers/com.apple.DataDetectorsViewService/Data
64	./Library/Containers/com.apple.DataDetectorsViewService
0	./Library/Containers/com.apple.STMExtension.Mail/Data/Library/Application Support
0	./Library/Containers/com.apple.STMExtension.Mail/Data/Library/Saved Application State
0	./Library/Containers/com.apple.STMExtension.Mail/Data/Library/Preferences
0	./Library/Containers/com.apple.STMExtension.Mail/Data/Library/Application Scripts
0	./Library/Containers/com.apple.STMExtension.Mail/Data/Library/Images
0	./Library/Containers/com.apple.STMExtension.Mail/Data/Library/Logs
0	./Library/Containers/com.apple.STMExtension.Mail/Data/Library/Caches
0	./Library/Containers/com.apple.STMExtension.Mail/Data/Library
0	./Library/Containers/com.apple.STMExtension.Mail/Data/Documents
0	./Library/Containers/com.apple.STMExtension.Mail/Data
56	./Library/Containers/com.apple.STMExtension.Mail
40	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/file:/Users/horus/Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/Library/Caches/fsCachedData
312	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/file:/Users/horus/Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/Library/Caches
312	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/file:/Users/horus/Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/Library
312	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/file:/Users/horus/Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data
312	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/file:/Users/horus/Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases
312	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/file:/Users/horus/Library/Containers
312	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/file:/Users/horus/Library
312	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/file:/Users/horus
312	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/file:/Users
312	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/file:
0	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/Library/Application Support
0	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/Library/Saved Application State
0	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/Library/Preferences
0	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/Library/Application Scripts
0	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/Library/Images
0	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/Library/Logs
0	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/Library/Caches
0	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/Library
0	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data/Documents
312	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases/Data
368	./Library/Containers/com.apple.AppleMediaServicesUI.SpyglassPurchases
0	./Library/Containers/com.apple.routined/Data/Library/Application Support
0	./Library/Containers/com.apple.routined/Data/Library/Saved Application State
8	./Library/Containers/com.apple.routined/Data/Library/Preferences
0	./Library/Containers/com.apple.routined/Data/Library/Application Scripts
0	./Library/Containers/com.apple.routined/Data/Library/Images
0	./Library/Containers/com.apple.routined/Data/Library/Logs
0	./Library/Containers/com.apple.routined/Data/Library/Caches
8	./Library/Containers/com.apple.routined/Data/Library
0	./Library/Containers/com.apple.routined/Data/Documents
8	./Library/Containers/com.apple.routined/Data
72	./Library/Containers/com.apple.routined
40	./Library/Containers/com.apple.corerecents.recentsd/Data/Library/Application Support/com.apple.kvs/ChangeTokens
40	./Library/Containers/com.apple.corerecents.recentsd/Data/Library/Application Support/com.apple.kvs
40	./Library/Containers/com.apple.corerecents.recentsd/Data/Library/Application Support
0	./Library/Containers/com.apple.corerecents.recentsd/Data/Library/Saved Application State
8	./Library/Containers/com.apple.corerecents.recentsd/Data/Library/Preferences
0	./Library/Containers/com.apple.corerecents.recentsd/Data/Library/Application Scripts
0	./Library/Containers/com.apple.corerecents.recentsd/Data/Library/Images
0	./Library/Containers/com.apple.corerecents.recentsd/Data/Library/Logs
1616	./Library/Containers/com.apple.corerecents.recentsd/Data/Library/Recents
0	./Library/Containers/com.apple.corerecents.recentsd/Data/Library/Caches
1664	./Library/Containers/com.apple.corerecents.recentsd/Data/Library
0	./Library/Containers/com.apple.corerecents.recentsd/Data/Documents
1664	./Library/Containers/com.apple.corerecents.recentsd/Data
1712	./Library/Containers/com.apple.corerecents.recentsd
0	./Library/Containers/com.apple.STMExtension.GarageBand/Data/Library/Application Support
0	./Library/Containers/com.apple.STMExtension.GarageBand/Data/Library/Saved Application State
0	./Library/Containers/com.apple.STMExtension.GarageBand/Data/Library/Preferences
0	./Library/Containers/com.apple.STMExtension.GarageBand/Data/Library/Application Scripts
0	./Library/Containers/com.apple.STMExtension.GarageBand/Data/Library/Images
0	./Library/Containers/com.apple.STMExtension.GarageBand/Data/Library/Logs
0	./Library/Containers/com.apple.STMExtension.GarageBand/Data/Library/Caches
0	./Library/Containers/com.apple.STMExtension.GarageBand/Data/Library
0	./Library/Containers/com.apple.STMExtension.GarageBand/Data/Documents
0	./Library/Containers/com.apple.STMExtension.GarageBand/Data
40	./Library/Containers/com.apple.STMExtension.GarageBand
0	./Library/Containers/com.apple.Preview/Data/Library/Application Support
0	./Library/Containers/com.apple.Preview/Data/Library/Autosave Information
48	./Library/Containers/com.apple.Preview/Data/Library/Saved Application State/com.apple.Preview.savedState
48	./Library/Containers/com.apple.Preview/Data/Library/Saved Application State
32	./Library/Containers/com.apple.Preview/Data/Library/Preferences
0	./Library/Containers/com.apple.Preview/Data/Library/Application Scripts
0	./Library/Containers/com.apple.Preview/Data/Library/Images
0	./Library/Containers/com.apple.Preview/Data/Library/Logs
0	./Library/Containers/com.apple.Preview/Data/Library/Caches
80	./Library/Containers/com.apple.Preview/Data/Library
0	./Library/Containers/com.apple.Preview/Data/Documents
80	./Library/Containers/com.apple.Preview/Data
128	./Library/Containers/com.apple.Preview
256	./Library/Containers/com.apple.UsageTrackingAgent/Data/Library/Application Support/UsageTrackingAgent
256	./Library/Containers/com.apple.UsageTrackingAgent/Data/Library/Application Support
0	./Library/Containers/com.apple.UsageTrackingAgent/Data/Library/Saved Application State
0	./Library/Containers/com.apple.UsageTrackingAgent/Data/Library/Preferences
0	./Library/Containers/com.apple.UsageTrackingAgent/Data/Library/Application Scripts
0	./Library/Containers/com.apple.UsageTrackingAgent/Data/Library/Images
0	./Library/Containers/com.apple.UsageTrackingAgent/Data/Library/Logs
0	./Library/Containers/com.apple.UsageTrackingAgent/Data/Library/Caches
256	./Library/Containers/com.apple.UsageTrackingAgent/Data/Library
0	./Library/Containers/com.apple.UsageTrackingAgent/Data/Documents
256	./Library/Containers/com.apple.UsageTrackingAgent/Data
296	./Library/Containers/com.apple.UsageTrackingAgent
8	./Library/Containers/com.apple.Siri.SiriTodayExtension/Data/Library/Preferences
8	./Library/Containers/com.apple.Siri.SiriTodayExtension/Data/Library
8	./Library/Containers/com.apple.Siri.SiriTodayExtension/Data
8	./Library/Containers/com.apple.Siri.SiriTodayExtension
0	./Library/Containers/com.apple.accessibility.mediaaccessibilityd/Data/Library/Application Support
0	./Library/Containers/com.apple.accessibility.mediaaccessibilityd/Data/Library/Saved Application State
0	./Library/Containers/com.apple.accessibility.mediaaccessibilityd/Data/Library/Preferences
0	./Library/Containers/com.apple.accessibility.mediaaccessibilityd/Data/Library/Application Scripts
0	./Library/Containers/com.apple.accessibility.mediaaccessibilityd/Data/Library/Images
0	./Library/Containers/com.apple.accessibility.mediaaccessibilityd/Data/Library/Logs
0	./Library/Containers/com.apple.accessibility.mediaaccessibilityd/Data/Library/Caches
0	./Library/Containers/com.apple.accessibility.mediaaccessibilityd/Data/Library
0	./Library/Containers/com.apple.accessibility.mediaaccessibilityd/Data/Documents
0	./Library/Containers/com.apple.accessibility.mediaaccessibilityd/Data
40	./Library/Containers/com.apple.accessibility.mediaaccessibilityd
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/Application Support
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/Saved Application State
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/WebKit/WebsiteData/IndexedDB/v1
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/WebKit/WebsiteData/IndexedDB
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/WebKit/WebsiteData/MediaKeys
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/WebKit/WebsiteData/WebSQL
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/WebKit/WebsiteData/LocalStorage
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/WebKit/WebsiteData/ResourceLoadStatistics
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/WebKit/WebsiteData
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/WebKit
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/Preferences
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/Application Scripts
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/Images
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/Logs
8	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/Cookies
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/Caches/WebKit/OfflineWebApplicationCache
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/Caches/WebKit/NetworkCache/Version 16/Blobs
8	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/Caches/WebKit/NetworkCache/Version 16
8	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/Caches/WebKit/NetworkCache
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/Caches/WebKit/CacheStorage
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/Caches/WebKit/ServiceWorkers
8	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/Caches/WebKit
8	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library/Caches
16	./Library/Containers/com.apple.quicklook.ui.helper/Data/Library
0	./Library/Containers/com.apple.quicklook.ui.helper/Data/Documents
16	./Library/Containers/com.apple.quicklook.ui.helper/Data
72	./Library/Containers/com.apple.quicklook.ui.helper
8	./Library/Containers/com.apple.SiriNCService/Data/Library/Preferences
8	./Library/Containers/com.apple.SiriNCService/Data/Library
8	./Library/Containers/com.apple.SiriNCService/Data
8	./Library/Containers/com.apple.SiriNCService
0	./Library/Containers/com.apple.AirPlayUIAgent/Data/Library/Application Support
0	./Library/Containers/com.apple.AirPlayUIAgent/Data/Library/Saved Application State
0	./Library/Containers/com.apple.AirPlayUIAgent/Data/Library/Preferences
0	./Library/Containers/com.apple.AirPlayUIAgent/Data/Library/Application Scripts
0	./Library/Containers/com.apple.AirPlayUIAgent/Data/Library/Images
0	./Library/Containers/com.apple.AirPlayUIAgent/Data/Library/Logs
0	./Library/Containers/com.apple.AirPlayUIAgent/Data/Library/Caches
0	./Library/Containers/com.apple.AirPlayUIAgent/Data/Library
0	./Library/Containers/com.apple.AirPlayUIAgent/Data/Documents
0	./Library/Containers/com.apple.AirPlayUIAgent/Data
40	./Library/Containers/com.apple.AirPlayUIAgent
0	./Library/Containers/com.apple.preferences.sharing.SharingPrefsExtension/Data/Library/Application Support
0	./Library/Containers/com.apple.preferences.sharing.SharingPrefsExtension/Data/Library/Saved Application State
0	./Library/Containers/com.apple.preferences.sharing.SharingPrefsExtension/Data/Library/Preferences
0	./Library/Containers/com.apple.preferences.sharing.SharingPrefsExtension/Data/Library/Application Scripts
0	./Library/Containers/com.apple.preferences.sharing.SharingPrefsExtension/Data/Library/Images
0	./Library/Containers/com.apple.preferences.sharing.SharingPrefsExtension/Data/Library/Logs
0	./Library/Containers/com.apple.preferences.sharing.SharingPrefsExtension/Data/Library/Caches
0	./Library/Containers/com.apple.preferences.sharing.SharingPrefsExtension/Data/Library
0	./Library/Containers/com.apple.preferences.sharing.SharingPrefsExtension/Data/Documents
0	./Library/Containers/com.apple.preferences.sharing.SharingPrefsExtension/Data
56	./Library/Containers/com.apple.preferences.sharing.SharingPrefsExtension
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension/Data/Library/Application Support
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension/Data/Library/Saved Application State
9672	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension/Data/Library/WebKit/ContentRuleLists
9672	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension/Data/Library/WebKit
8	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension/Data/Library/Preferences
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension/Data/Library/Application Scripts
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension/Data/Library/Images
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension/Data/Library/Logs
2632	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension/Data/Library/Caches/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension
2632	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension/Data/Library/Caches
12312	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension/Data/Library
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension/Data/Documents
12312	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension/Data
12368	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials.SafariAppExtension
0	./Library/Containers/com.apple.Notes.QuickLookExtension/Data/Library/Application Support/com.apple.Notes.QuickLookExtension
0	./Library/Containers/com.apple.Notes.QuickLookExtension/Data/Library/Application Support
0	./Library/Containers/com.apple.Notes.QuickLookExtension/Data/Library/Saved Application State
8	./Library/Containers/com.apple.Notes.QuickLookExtension/Data/Library/Preferences/ByHost
8	./Library/Containers/com.apple.Notes.QuickLookExtension/Data/Library/Preferences
0	./Library/Containers/com.apple.Notes.QuickLookExtension/Data/Library/Application Scripts
0	./Library/Containers/com.apple.Notes.QuickLookExtension/Data/Library/Images
0	./Library/Containers/com.apple.Notes.QuickLookExtension/Data/Library/Logs
0	./Library/Containers/com.apple.Notes.QuickLookExtension/Data/Library/Caches
8	./Library/Containers/com.apple.Notes.QuickLookExtension/Data/Library
0	./Library/Containers/com.apple.Notes.QuickLookExtension/Data/Documents
8	./Library/Containers/com.apple.Notes.QuickLookExtension/Data
72	./Library/Containers/com.apple.Notes.QuickLookExtension
0	./Library/Containers/com.apple.mediaanalysisd/Data/Library/Application Support
0	./Library/Containers/com.apple.mediaanalysisd/Data/Library/Saved Application State
0	./Library/Containers/com.apple.mediaanalysisd/Data/Library/Preferences
0	./Library/Containers/com.apple.mediaanalysisd/Data/Library/Application Scripts
0	./Library/Containers/com.apple.mediaanalysisd/Data/Library/Images
0	./Library/Containers/com.apple.mediaanalysisd/Data/Library/Logs
0	./Library/Containers/com.apple.mediaanalysisd/Data/Library/Caches
0	./Library/Containers/com.apple.mediaanalysisd/Data/Library
0	./Library/Containers/com.apple.mediaanalysisd/Data/Documents
0	./Library/Containers/com.apple.mediaanalysisd/Data
48	./Library/Containers/com.apple.mediaanalysisd
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials/Data/Library/Application Support
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials/Data/Library/Saved Application State
8832	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials/Data/Library/WebKit/ContentRuleLists
8832	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials/Data/Library/WebKit
8	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials/Data/Library/Preferences
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials/Data/Library/Application Scripts
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials/Data/Library/Images
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials/Data/Library/Logs
1200	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials/Data/Library/Caches/com.duckduckgo.macos.PrivacyEssentials
1200	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials/Data/Library/Caches
10040	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials/Data/Library
0	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials/Data/Documents
10040	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials/Data
10096	./Library/Containers/com.duckduckgo.macos.PrivacyEssentials
0	./Library/Containers/com.apple.SocialPushAgent/Data/Library/Application Support
0	./Library/Containers/com.apple.SocialPushAgent/Data/Library/Saved Application State
8	./Library/Containers/com.apple.SocialPushAgent/Data/Library/Preferences
0	./Library/Containers/com.apple.SocialPushAgent/Data/Library/Application Scripts
0	./Library/Containers/com.apple.SocialPushAgent/Data/Library/Images
0	./Library/Containers/com.apple.SocialPushAgent/Data/Library/Logs
0	./Library/Containers/com.apple.SocialPushAgent/Data/Library/Caches
8	./Library/Containers/com.apple.SocialPushAgent/Data/Library
0	./Library/Containers/com.apple.SocialPushAgent/Data/Documents
8	./Library/Containers/com.apple.SocialPushAgent/Data
56	./Library/Containers/com.apple.SocialPushAgent
27556296	./Library/Containers
du: ./Library/PersonalizationPortrait: Operation not permitted
0	./Library/Fonts
560	./Library/Accessibility/AXSSPunctuation
560	./Library/Accessibility
560	./Library/KeyboardServices
du: ./Library/Metadata/CoreSpotlight: Operation not permitted
0	./Library/Metadata
0	./Library/Screen Savers
0	./Library/CallServices/Ringtones
0	./Library/CallServices
24	./Library/Spelling
0	./Library/SafariSafeBrowsing
3696	./Library/Reminders/Container_v1/Stores
3696	./Library/Reminders/Container_v1
8	./Library/Reminders/DataAccess
3704	./Library/Reminders
0	./Library/Input Methods
du: ./Library/Cookies: Operation not permitted
0	./Library/Services
32	./Library/Keyboard/en-dynamic.lm
192	./Library/Keyboard
56	./Library/CoreFollowUp
0	./Library/Caches/Firefox/Profiles/xuc77p27.default
280	./Library/Caches/Firefox/Profiles/skjogx2k.default-release/settings/main/quicksuggest
16	./Library/Caches/Firefox/Profiles/skjogx2k.default-release/settings/main/ms-language-packs/browser/newtab
16	./Library/Caches/Firefox/Profiles/skjogx2k.default-release/settings/main/ms-language-packs/browser
16	./Library/Caches/Firefox/Profiles/skjogx2k.default-release/settings/main/ms-language-packs
296	./Library/Caches/Firefox/Profiles/skjogx2k.default-release/settings/main
296	./Library/Caches/Firefox/Profiles/skjogx2k.default-release/settings
179696	./Library/Caches/Firefox/Profiles/skjogx2k.default-release/cache2/entries
0	./Library/Caches/Firefox/Profiles/skjogx2k.default-release/cache2/doomed
179848	./Library/Caches/Firefox/Profiles/skjogx2k.default-release/cache2
25360	./Library/Caches/Firefox/Profiles/skjogx2k.default-release/safebrowsing/google4
29528	./Library/Caches/Firefox/Profiles/skjogx2k.default-release/safebrowsing
2744	./Library/Caches/Firefox/Profiles/skjogx2k.default-release/personality-provider
34312	./Library/Caches/Firefox/Profiles/skjogx2k.default-release/startupCache
440	./Library/Caches/Firefox/Profiles/skjogx2k.default-release/thumbnails
247600	./Library/Caches/Firefox/Profiles/skjogx2k.default-release
247600	./Library/Caches/Firefox/Profiles
247600	./Library/Caches/Firefox
56	./Library/Caches/Maps
24	./Library/Caches/familycircled/fsCachedData
840	./Library/Caches/familycircled
24	./Library/Caches/com.apple.helpd/Generated/com.apple.AppStore.help*3.0
16	./Library/Caches/com.apple.helpd/Generated/com.apple.VoiceMemos.help*2.1
8	./Library/Caches/com.apple.helpd/Generated/com.apple.Calculator.help*10.15.4
80	./Library/Caches/com.apple.helpd/Generated/com.apple.Preview.help*11.0
40	./Library/Caches/com.apple.helpd/Generated/com.apple.News.help*5.5
96	./Library/Caches/com.apple.helpd/Generated/com.apple.Terminal.help*2.10
8	./Library/Caches/com.apple.helpd/Generated/com.apple.Offline.help
184	./Library/Caches/com.apple.helpd/Generated/com.apple.Music.help*1.0.6
16	./Library/Caches/com.apple.helpd/Generated/com.apple.PhotoBooth.help*11.0
88	./Library/Caches/com.apple.helpd/Generated/com.apple.DirectoryUtility.help*6.0
16	./Library/Caches/com.apple.helpd/Generated/com.apple.ImageCapture.help*8.0
56	./Library/Caches/com.apple.helpd/Generated/com.apple.iBooksX.help*2.4
224	./Library/Caches/com.apple.helpd/Generated/com.apple.VoiceOver.help*10
24	./Library/Caches/com.apple.helpd/Generated/com.apple.ActivityMonitor.help*10.14
8	./Library/Caches/com.apple.helpd/Generated/com.apple.Dictionary.help*2.3.0
24	./Library/Caches/com.apple.helpd/Generated/com.apple.Maps.help*2.1
40	./Library/Caches/com.apple.helpd/Generated/com.apple.ScriptEditor.help*2.11
24	./Library/Caches/com.apple.helpd/Generated/com.apple.DVDPlayer.help*6.0
64	./Library/Caches/com.apple.helpd/Generated/com.apple.Notes.help*4.7
24	./Library/Caches/com.apple.helpd/Generated/com.apple.Home.help*4.0
24	./Library/Caches/com.apple.helpd/Generated/com.apple.FontBook.help*10.0
40	./Library/Caches/com.apple.helpd/Generated/com.apple.AudioMIDISetup.help*3.5
1816	./Library/Caches/com.apple.helpd/Generated/com.apple.machelp*10.15.7
16	./Library/Caches/com.apple.helpd/Generated/com.apple.Stocks.help*2.5
160	./Library/Caches/com.apple.helpd/Generated/com.apple.Photos.help*5.0
168	./Library/Caches/com.apple.helpd/Generated/com.apple.Safari.help*15.4
32	./Library/Caches/com.apple.helpd/Generated/com.apple.podcasts.help*1.0.0
104	./Library/Caches/com.apple.helpd/Generated/com.apple.iCal.help*11.0
56	./Library/Caches/com.apple.helpd/Generated/com.apple.DiskUtility.help*19.0
8	./Library/Caches/com.apple.helpd/Generated/com.apple.digitalcolormeter.help*5.15
8	./Library/Caches/com.apple.helpd/Generated/com.apple.Stickies.help*10.2
48	./Library/Caches/com.apple.helpd/Generated/com.apple.Automator.help*2.10
64	./Library/Caches/com.apple.helpd/Generated/com.apple.airport.airportutility.help*6.3.9
8	./Library/Caches/com.apple.helpd/Generated/com.apple.Chess.help*3.17
200	./Library/Caches/com.apple.helpd/Generated/com.apple.Mail.help*13.4
56	./Library/Caches/com.apple.helpd/Generated/com.apple.TextEdit.help*1.15
32	./Library/Caches/com.apple.helpd/Generated/com.apple.findmy.help*1.0
56	./Library/Caches/com.apple.helpd/Generated/com.apple.iChat.help*13.0
24	./Library/Caches/com.apple.helpd/Generated/com.apple.appleseed.FeedbackAssistant.help*4.6
40	./Library/Caches/com.apple.helpd/Generated/com.apple.reminders.help*7.0
24	./Library/Caches/com.apple.helpd/Generated/com.apple.SystemInformation.help*10.14
40	./Library/Caches/com.apple.helpd/Generated/com.apple.QuickTimePlayerX.help*10.5
24	./Library/Caches/com.apple.helpd/Generated/com.apple.Grapher.help*2.7
72	./Library/Caches/com.apple.helpd/Generated/com.apple.AddressBook.help*12.0
24	./Library/Caches/com.apple.helpd/Generated/com.apple.Console.help*1.1
48	./Library/Caches/com.apple.helpd/Generated/com.apple.FaceTime.help*5.0
24	./Library/Caches/com.apple.helpd/Generated/com.apple.colorsyncutility.help*4.14.0
40	./Library/Caches/com.apple.helpd/Generated/com.apple.keychainaccess.help*10.5
56	./Library/Caches/com.apple.helpd/Generated/com.apple.TV.help*1.0.6
4376	./Library/Caches/com.apple.helpd/Generated
6176	./Library/Caches/com.apple.helpd/fsCachedData
10592	./Library/Caches/com.apple.helpd/index.spotlightV3
26536	./Library/Caches/com.apple.helpd
168	./Library/Caches/com.apple.AddressBookSourceSync
32	./Library/Caches/GeoServices/SearchAttribution
21880	./Library/Caches/GeoServices/Resources
11024	./Library/Caches/GeoServices/RegionalResources
35136	./Library/Caches/GeoServices
0	./Library/Caches/Mozilla/updates/Applications/Firefox
0	./Library/Caches/Mozilla/updates/Applications
0	./Library/Caches/Mozilla/updates
0	./Library/Caches/Mozilla
0	./Library/Caches/com.apple.Music/WebKit/OfflineWebApplicationCache
0	./Library/Caches/com.apple.Music/WebKit/NetworkCache
0	./Library/Caches/com.apple.Music/WebKit/CacheStorage
0	./Library/Caches/com.apple.Music/WebKit/ServiceWorkers
0	./Library/Caches/com.apple.Music/WebKit
168	./Library/Caches/com.apple.Music
1168	./Library/Caches/com.apple.touristd/fsCachedData
2264	./Library/Caches/com.apple.touristd
72	./Library/Caches/com.apple.proactive.eventtracker/log_stores
240	./Library/Caches/com.apple.proactive.eventtracker
280	./Library/Caches/com.apple.mediastream.mstreamd
0	./Library/Caches/PassKit/RemoteCards
8	./Library/Caches/PassKit/RecipientCache
16	./Library/Caches/PassKit
du: ./Library/Caches/CloudKit: Operation not permitted
0	./Library/Caches/com.microsoft.VSCode.ShipIt
96	./Library/Caches/com.apple.akd/fsCachedData
2064	./Library/Caches/com.apple.akd
du: ./Library/Caches/com.apple.Safari: Operation not permitted
88	./Library/Caches/GameKit/StoreBag
1560	./Library/Caches/GameKit/Data/com.apple.gamecenter/en-US-global.gcdata
1560	./Library/Caches/GameKit/Data/com.apple.gamecenter/en-US-U:549ceaed5fca24967720766abfb6ce27.gcdata
3120	./Library/Caches/GameKit/Data/com.apple.gamecenter
3120	./Library/Caches/GameKit/Data
3272	./Library/Caches/GameKit
336	./Library/Caches/com.apple.amp.accounts.pluginhelper/fsCachedData
768	./Library/Caches/com.apple.amp.accounts.pluginhelper
256	./Library/Caches/com.apple.keyboardservicesd
0	./Library/Caches/com.apple.Spotlight/WebKit/OfflineWebApplicationCache
0	./Library/Caches/com.apple.Spotlight/WebKit/NetworkCache/Version 16/Blobs
8	./Library/Caches/com.apple.Spotlight/WebKit/NetworkCache/Version 16
8	./Library/Caches/com.apple.Spotlight/WebKit/NetworkCache
0	./Library/Caches/com.apple.Spotlight/WebKit/CacheStorage
0	./Library/Caches/com.apple.Spotlight/WebKit/ServiceWorkers
8	./Library/Caches/com.apple.Spotlight/WebKit
72	./Library/Caches/com.apple.Spotlight/fsCachedData
4888	./Library/Caches/com.apple.Spotlight
8	./Library/Caches/Homebrew/style/501/rubocop_cache/c7c2d38823b022423ed01241c1b25b78ed6cb1c5/07de522673850d97d6d52f38bc93c816556876ca
8	./Library/Caches/Homebrew/style/501/rubocop_cache/c7c2d38823b022423ed01241c1b25b78ed6cb1c5
8	./Library/Caches/Homebrew/style/501/rubocop_cache
8	./Library/Caches/Homebrew/style/501
8	./Library/Caches/Homebrew/style
0	./Library/Caches/Homebrew/Cask
658640	./Library/Caches/Homebrew/downloads
678080	./Library/Caches/Homebrew
8	./Library/Caches/com.apple.gamed
5304	./Library/Caches/com.apple.appstoreagent/fsCachedData
15080	./Library/Caches/com.apple.appstoreagent
168	./Library/Caches/com.apple.accountsd
8	./Library/Caches/com.apple.DictionaryServices
304	./Library/Caches/com.github.GitHubClient
48	./Library/Caches/com.apple.nbagent/fsCachedData
368	./Library/Caches/com.apple.nbagent
168	./Library/Caches/com.apple.AOSPushRelay
0	./Library/Caches/com.apple.nsurlsessiond/Downloads/com.apple.appstoreagent
0	./Library/Caches/com.apple.nsurlsessiond/Downloads/com.apple.cloudkit.cloudd
0	./Library/Caches/com.apple.nsurlsessiond/Downloads/com.apple.parsecd
0	./Library/Caches/com.apple.nsurlsessiond/Downloads/swcd
8	./Library/Caches/com.apple.nsurlsessiond/Downloads/com.apple.bird
8	./Library/Caches/com.apple.nsurlsessiond/Downloads
8	./Library/Caches/com.apple.nsurlsessiond
0	./Library/Caches/com.github.GitHubClient.ShipIt
280	./Library/Caches/com.apple.appstore/CommerceRequestCache/fsCachedData
2024	./Library/Caches/com.apple.appstore/CommerceRequestCache
2024	./Library/Caches/com.apple.appstore
40	./Library/Caches/pip/http/a/1/9/5/3
40	./Library/Caches/pip/http/a/1/9/5
40	./Library/Caches/pip/http/a/1/9
40	./Library/Caches/pip/http/a/1
40	./Library/Caches/pip/http/a
40	./Library/Caches/pip/http
8	./Library/Caches/pip/selfcheck
48	./Library/Caches/pip
200	./Library/Caches/com.apple.passd/fsCachedData
664	./Library/Caches/com.apple.passd
136	./Library/Caches/com.apple.AppleMediaServices/Metrics/com.apple.appstored
136	./Library/Caches/com.apple.AppleMediaServices/Metrics/com.apple.AppleMediaServices
8520	./Library/Caches/com.apple.AppleMediaServices/Metrics/MacAppStore
8792	./Library/Caches/com.apple.AppleMediaServices/Metrics
304	./Library/Caches/com.apple.AppleMediaServices/fsCachedData
15424	./Library/Caches/com.apple.AppleMediaServices
72	./Library/Caches/com.apple.remindd/com.apple.dataaccessd.55400F97-59CE-48EB-8B4D-C12EF580D266
248	./Library/Caches/com.apple.remindd
0	./Library/Caches/com.apple.assistantd/voiceid.cache
0	./Library/Caches/com.apple.assistantd
168	./Library/Caches/com.apple.helpviewer
168	./Library/Caches/com.apple.imfoundation.IMRemoteURLConnectionAgent
64	./Library/Caches/com.apple.voiceover/UserSearch
64	./Library/Caches/com.apple.voiceover
168	./Library/Caches/com.apple.SystemProfiler
1976	./Library/Caches/com.apple.parsecd/Cohorts
0	./Library/Caches/com.apple.parsecd/CustomFeedback/Crowdsourcing
0	./Library/Caches/com.apple.parsecd/CustomFeedback/EngagedCompletionFeatures
0	./Library/Caches/com.apple.parsecd/CustomFeedback/SpotlightResultFeatures
0	./Library/Caches/com.apple.parsecd/CustomFeedback/SafariAutoFill
0	./Library/Caches/com.apple.parsecd/CustomFeedback/Usage
0	./Library/Caches/com.apple.parsecd/CustomFeedback/ProactiveEventTracker
0	./Library/Caches/com.apple.parsecd/CustomFeedback/FeedbackV2
0	./Library/Caches/com.apple.parsecd/CustomFeedback/Trystero
0	./Library/Caches/com.apple.parsecd/CustomFeedback/FeedbackV2PB
0	./Library/Caches/com.apple.parsecd/CustomFeedback/DuetExpert
0	./Library/Caches/com.apple.parsecd/CustomFeedback/PhiDES
0	./Library/Caches/com.apple.parsecd/CustomFeedback/SafariAutoPlay
0	./Library/Caches/com.apple.parsecd/CustomFeedback/UserReport
0	./Library/Caches/com.apple.parsecd/CustomFeedback
48	./Library/Caches/com.apple.parsecd/EngagedCompletions
40272	./Library/Caches/com.apple.parsecd
816	./Library/Caches/com.apple.icloud.fmfd
168	./Library/Caches/com.apple.installer
0	./Library/Caches/com.apple.bird/unlink
168	./Library/Caches/com.apple.bird
0	./Library/Caches/com.apple.cloudd
168	./Library/Caches/com.microsoft.VSCode
8	./Library/Caches/FamilyCircle
344	./Library/Caches/com.apple.AMPLibraryAgent/fsCachedData
776	./Library/Caches/com.apple.AMPLibraryAgent
0	./Library/Caches/com.apple.commerce
168	./Library/Caches/storedownloadd
248	./Library/Caches/com.apple.ctcategories.service/fsCachedData
2240	./Library/Caches/com.apple.ctcategories.service
0	./Library/Caches/com.apple.cache_delete/CacheDeleteBreadcumbs
40	./Library/Caches/com.apple.cache_delete
0	./Library/Caches/com.apple.BluetoothFileExchange/WebKit/OfflineWebApplicationCache
0	./Library/Caches/com.apple.BluetoothFileExchange/WebKit/NetworkCache/Version 16/Blobs
8	./Library/Caches/com.apple.BluetoothFileExchange/WebKit/NetworkCache/Version 16
8	./Library/Caches/com.apple.BluetoothFileExchange/WebKit/NetworkCache
0	./Library/Caches/com.apple.BluetoothFileExchange/WebKit/CacheStorage
0	./Library/Caches/com.apple.BluetoothFileExchange/WebKit/ServiceWorkers
8	./Library/Caches/com.apple.BluetoothFileExchange/WebKit
176	./Library/Caches/com.apple.BluetoothFileExchange
0	./Library/Caches/com.apple.AMPDevicesAgent
0	./Library/Caches/VoiceTrigger
592	./Library/Caches/com.apple.systempreferences/fsCachedData
1280	./Library/Caches/com.apple.systempreferences
du: ./Library/Caches/com.apple.ap.adprivacyd: Operation not permitted
72	./Library/Caches/BraveSoftware/Brave-Browser/Default/Cache/Cache_Data/index-dir
524184	./Library/Caches/BraveSoftware/Brave-Browser/Default/Cache/Cache_Data
524184	./Library/Caches/BraveSoftware/Brave-Browser/Default/Cache
40	./Library/Caches/BraveSoftware/Brave-Browser/Default/Code Cache/js/index-dir
34912	./Library/Caches/BraveSoftware/Brave-Browser/Default/Code Cache/js
8	./Library/Caches/BraveSoftware/Brave-Browser/Default/Code Cache/wasm/index-dir
16	./Library/Caches/BraveSoftware/Brave-Browser/Default/Code Cache/wasm
34928	./Library/Caches/BraveSoftware/Brave-Browser/Default/Code Cache
559112	./Library/Caches/BraveSoftware/Brave-Browser/Default
559112	./Library/Caches/BraveSoftware/Brave-Browser
559112	./Library/Caches/BraveSoftware
168	./Library/Caches/com.apple.iCloudHelper
0	./Library/Caches/com.apple.XprotectFramework.AnalysisService
64	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/_CodeSignature
424	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/MacOS
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/de.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/ur.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/he.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/ar.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/el.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/ja.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/fa.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/mr.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/en.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/uk.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/es_419.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/gu.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/zh_CN.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/kn.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/nb.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/am.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/es.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/sw.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/sl.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/pt_BR.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/da.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/et.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/it.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/bg.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/sk.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/pt_PT.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/sr.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/ms.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/ta.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/ml.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/sv.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/te.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/cs.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/ko.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/fil.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/hu.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/tr.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/pl.lproj
472	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/com.brave.Browser.manifest/Contents/Resources/en.lproj
712	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/com.brave.Browser.manifest/Contents/Resources
712	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/com.brave.Browser.manifest/Contents
712	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/com.brave.Browser.manifest
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/zh_TW.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/en_GB.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/vi.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/lv.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/lt.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/ru.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/af.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/fr.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/fi.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/id.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/nl.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/th.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/bn.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/ro.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/hr.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/hi.lproj
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources/ca.lproj
2120	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Resources
144	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/_CodeSignature
928	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/de.lproj
1240	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/ur.lproj
1144	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/he.lproj
1368	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/ar.lproj
1648	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/el.lproj
1104	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/ja.lproj
1328	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/fa.lproj
1672	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/mr.lproj
760	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/en.lproj
1488	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/uk.lproj
920	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/es_419.lproj
1696	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/gu.lproj
760	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/zh_CN.lproj
2168	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/kn.lproj
832	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/nb.lproj
1312	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/am.lproj
920	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/es.lproj
872	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/sw.lproj
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/sl
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/sk
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/ur
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/sw
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/pl
48	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/vi
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/sv
48	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/he
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/ms
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/en_US
48	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/am
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/da
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/mr
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/gu
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/pt_BR
48	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/ja
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/el
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/lv
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/it
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/ca
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/zh_TW
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/cs
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/te
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/pt_PT
48	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/ru
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/ro
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/zh_CN
48	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/uk
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/sr
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/en_GB
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/ml
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/es_419
64	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/kn
48	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/ar
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/hr
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/hu
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/nl
48	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/bg
64	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/bn
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/fil
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/af
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/nb
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/hi
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/de
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/ko
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/fi
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/id
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/fr
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/es
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/et
48	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/fa
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/lt
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/ta
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/th
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales/tr
2368	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards/_locales
2368	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_rewards
904	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/sl.lproj
896	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/pt_BR.lproj
848	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/da.lproj
824	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/et.lproj
896	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/it.lproj
1512	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/bg.lproj
944	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/sk.lproj
904	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/pt_PT.lproj
1312	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/sr.lproj
848	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/ms.lproj
1960	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/ta.lproj
2032	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/ml.lproj
832	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/sv.lproj
1864	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/te.lproj
936	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/cs.lproj
920	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/ko.lproj
944	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/fil.lproj
976	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/hu.lproj
896	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/tr.lproj
944	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/pl.lproj
752	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/zh_TW.lproj
752	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/en_GB.lproj
1064	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/vi.lproj
968	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/lv.lproj
968	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/lt.lproj
1480	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/ru.lproj
816	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/af.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/sl
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/sk
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/ur
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/sw
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/pl
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/vi
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/sv
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/he
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/ms
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/en_US
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/am
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/da
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/mr
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/gu
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/pt_BR
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/ja
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/el
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/lv
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/it
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/ca
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/zh_TW
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/cs
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/te
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/pt_PT
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/ru
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/ro
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/zh_CN
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/uk
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/sr
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/en_GB
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/ml
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/es_419
32	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/kn
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/ar
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/hr
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/hu
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/nl
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/bg
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/bn
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/fil
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/af
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/nb
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/hi
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/de
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/ko
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/fi
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/id
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/fr
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/es
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/et
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/fa
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/lt
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/ta
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/th
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales/tr
1328	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension/_locales
1328	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/brave_extension
984	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/fr.lproj
848	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/fi.lproj
816	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/id.lproj
864	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/nl.lproj
1760	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/th.lproj
1952	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/bn.lproj
928	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/ro.lproj
904	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/hr.lproj
1952	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/hi.lproj
920	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources/ca.lproj
141432	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Resources
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Libraries/MEIPreload
33136	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Libraries
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/_CodeSignature
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/PrivateHeaders
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/de.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/de.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/de.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/de.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/he.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ar.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ar.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ar.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ar.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/el.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/el.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/el.lproj/SUUpdateAlert.nib
248	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/el.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ja.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ja.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ja.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ja.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/en.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/en.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/en.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/en.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/uk.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/uk.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/uk.lproj/SUUpdateAlert.nib
248	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/uk.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/zh_CN.lproj/SUAutomaticUpdateAlert.nib
80	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/zh_CN.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/zh_CN.lproj/SUUpdateAlert.nib
240	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/zh_CN.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/nb.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/nb.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/nb.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/nb.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/es.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/es.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/es.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/es.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/is.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/is.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/is.lproj/SUUpdateAlert.nib
248	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/is.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/sl.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/sl.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/sl.lproj/SUUpdateAlert.nib
248	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/sl.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/pt_BR.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/pt_BR.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/pt_BR.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/pt_BR.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/da.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/da.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/da.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/da.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/it.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/it.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/it.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/it.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/sk.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/sk.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/sk.lproj/SUUpdateAlert.nib
248	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/sk.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/pt_PT.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/pt_PT.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/pt_PT.lproj/SUUpdateAlert.nib
248	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/pt_PT.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/sv.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/sv.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/sv.lproj/SUUpdateAlert.nib
248	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/sv.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/cs.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/cs.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/cs.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/cs.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ko.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ko.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ko.lproj/SUUpdateAlert.nib
248	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ko.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/hu.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/hu.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/hu.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/hu.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/tr.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/tr.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/tr.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/tr.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/pl.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/pl.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/pl.lproj/SUUpdateAlert.nib
248	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/pl.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/zh_TW.lproj/SUAutomaticUpdateAlert.nib
80	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/zh_TW.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/zh_TW.lproj/SUUpdateAlert.nib
240	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/zh_TW.lproj
40	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/_CodeSignature
1624	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/MacOS
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/de.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/he.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/ar.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/el.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/ja.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/en.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/uk.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/zh_CN.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/nb.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/es.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/is.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/sl.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/pt_BR.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/da.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/it.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/sk.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/pt_PT.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/sv.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/cs.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/ko.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/hu.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/tr.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/pl.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/zh_TW.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/ru.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/SUStatus.nib
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/fr.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/fi.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/nl.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/th.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/ro.lproj
24	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/hr.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources/ca.lproj
784	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents/Resources
2464	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app/Contents
2464	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/Autoupdate.app
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ru.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ru.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ru.lproj/SUUpdateAlert.nib
248	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ru.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/SUStatus.nib
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/fr.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/fr.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/fr.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/fr.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/fi.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/fi.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/fi.lproj/SUUpdateAlert.nib
248	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/fi.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/nl.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/nl.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/nl.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/nl.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/th.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/th.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/th.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/th.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ro.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ro.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ro.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ro.lproj
56	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/hr.lproj/SUAutomaticUpdateAlert.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/hr.lproj/SUUpdatePermissionPrompt.nib
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/hr.lproj/SUUpdateAlert.nib
256	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/hr.lproj
16	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources/ca.lproj
10152	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Resources
168	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Headers
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A/Modules
13160	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions/A
13160	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework/Versions
13160	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks/Sparkle.framework
13160	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Frameworks
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper.app/Contents/_CodeSignature
520	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper.app/Contents/MacOS
552	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper.app/Contents
552	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper.app
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (GPU).app/Contents/_CodeSignature
520	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (GPU).app/Contents/MacOS
552	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (GPU).app/Contents
552	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (GPU).app
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (Alerts).app/Contents/_CodeSignature
512	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (Alerts).app/Contents/MacOS
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (Alerts).app/Contents/Resources/base.lproj
240	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (Alerts).app/Contents/Resources
784	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (Alerts).app/Contents
784	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (Alerts).app
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (Plugin).app/Contents/_CodeSignature
520	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (Plugin).app/Contents/MacOS
552	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (Plugin).app/Contents
552	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (Plugin).app
8	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (Renderer).app/Contents/_CodeSignature
520	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (Renderer).app/Contents/MacOS
552	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (Renderer).app/Contents
552	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers/Brave Browser Helper (Renderer).app
17032	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115/Helpers
559496	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions/101.1.38.115
559496	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework/Versions
559496	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks/Brave Browser Framework.framework
559496	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents/Frameworks
562176	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app/Contents
562176	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/Brave Browser.app
88	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115/.background
827632	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL/Brave Browser 138.115
827632	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads/mKM4lPCjL
827632	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle/PersistentDownloads
827632	./Library/Caches/com.brave.Browser/org.sparkle-project.Sparkle
827800	./Library/Caches/com.brave.Browser
256	./Library/Caches/com.apple.accounts.dom
2473984	./Library/Caches
30544824	./Library
24	./volatility3/development/mac-kdk
184	./volatility3/development
56	./volatility3/volatility3/framework/renderers
64	./volatility3/volatility3/framework/configuration
40	./volatility3/volatility3/framework/contexts
8	./volatility3/volatility3/framework/layers/codecs
24	./volatility3/volatility3/framework/layers/scanners
320	./volatility3/volatility3/framework/layers
240	./volatility3/volatility3/framework/plugins/mac
216	./volatility3/volatility3/framework/plugins/linux
120	./volatility3/volatility3/framework/plugins/windows/registry
1136	./volatility3/volatility3/framework/plugins/windows
1696	./volatility3/volatility3/framework/plugins
8	./volatility3/volatility3/framework/constants/linux
8	./volatility3/volatility3/framework/constants/windows
24	./volatility3/volatility3/framework/constants
224	./volatility3/volatility3/framework/automagic
104	./volatility3/volatility3/framework/objects
40	./volatility3/volatility3/framework/symbols/mac/extensions
64	./volatility3/volatility3/framework/symbols/mac
88	./volatility3/volatility3/framework/symbols/linux/extensions
176	./volatility3/volatility3/framework/symbols/linux
16	./volatility3/volatility3/framework/symbols/generic
264	./volatility3/volatility3/framework/symbols/windows/extensions
816	./volatility3/volatility3/framework/symbols/windows/netscan
48	./volatility3/volatility3/framework/symbols/windows/bigpools
160	./volatility3/volatility3/framework/symbols/windows/services
1824	./volatility3/volatility3/framework/symbols/windows
2208	./volatility3/volatility3/framework/symbols
280	./volatility3/volatility3/framework/interfaces
5040	./volatility3/volatility3/framework
8	./volatility3/volatility3/plugins/mac
8	./volatility3/volatility3/plugins/linux
16	./volatility3/volatility3/plugins/windows/registry
32	./volatility3/volatility3/plugins/windows
56	./volatility3/volatility3/plugins
104	./volatility3/volatility3/cli/volshell
216	./volatility3/volatility3/cli
160	./volatility3/volatility3/schemas
8	./volatility3/volatility3/symbols
5488	./volatility3/volatility3
8	./volatility3/.github/workflows
16	./volatility3/.github/ISSUE_TEMPLATE
24	./volatility3/.github
240	./volatility3/doc/source/_static
520	./volatility3/doc/source
544	./volatility3/doc
13112	./volatility3/.git/objects/pack
0	./volatility3/.git/objects/info
13112	./volatility3/.git/objects
8	./volatility3/.git/info
8	./volatility3/.git/logs/refs/heads
8	./volatility3/.git/logs/refs/remotes/origin
8	./volatility3/.git/logs/refs/remotes
16	./volatility3/.git/logs/refs
24	./volatility3/.git/logs
120	./volatility3/.git/hooks
8	./volatility3/.git/refs/heads
0	./volatility3/.git/refs/tags
8	./volatility3/.git/refs/remotes/origin
8	./volatility3/.git/refs/remotes
16	./volatility3/.git/refs
13384	./volatility3/.git
19768	./volatility3
0	./iCloud Drive (Archive)/Shortcuts
32	./iCloud Drive (Archive)/Downloads/Eon
3552	./iCloud Drive (Archive)/Downloads
3552	./iCloud Drive (Archive)
8	./.cups
0	./Public/Drop Box
0	./Public
24	./mvt/tests/artifacts/android_data/bugreport
32	./mvt/tests/artifacts/android_data
8	./mvt/tests/artifacts/android_backup/apps/com.android.providers.telephony/d_f
8	./mvt/tests/artifacts/android_backup/apps/com.android.providers.telephony
8	./mvt/tests/artifacts/android_backup/apps
48	./mvt/tests/artifacts/android_backup
176	./mvt/tests/artifacts/ios_backup/0d
56	./mvt/tests/artifacts/ios_backup/3d
80	./mvt/tests/artifacts/ios_backup/3a
112	./mvt/tests/artifacts/ios_backup/64
6856	./mvt/tests/artifacts/ios_backup
6952	./mvt/tests/artifacts
48	./mvt/tests/ios
8	./mvt/tests/common
32	./mvt/tests/android
7072	./mvt/tests
16	./mvt/docs/ios/filesystem
32	./mvt/docs/ios/backup
104	./mvt/docs/ios
280	./mvt/docs/img
32	./mvt/docs/android
520	./mvt/docs
8	./mvt/mvt/__pycache__
240	./mvt/mvt/ios/modules/mixed
56	./mvt/mvt/ios/modules/backup
104	./mvt/mvt/ios/modules/fs
448	./mvt/mvt/ios/modules
536	./mvt/mvt/ios
8	./mvt/mvt/common/__pycache__
136	./mvt/mvt/common
56	./mvt/mvt/android/parsers
24	./mvt/mvt/android/lookups
96	./mvt/mvt/android/modules/bugreport
208	./mvt/mvt/android/modules/adb
24	./mvt/mvt/android/modules/backup
336	./mvt/mvt/android/modules
472	./mvt/mvt/android
1160	./mvt/mvt
8	./mvt/.github/workflows
8	./mvt/.github
16	./mvt/dev
3104	./mvt/.git/objects/pack
0	./mvt/.git/objects/info
3104	./mvt/.git/objects
8	./mvt/.git/info
8	./mvt/.git/logs/refs/heads
8	./mvt/.git/logs/refs/remotes/origin
8	./mvt/.git/logs/refs/remotes
16	./mvt/.git/logs/refs
24	./mvt/.git/logs
120	./mvt/.git/hooks
8	./mvt/.git/refs/heads
0	./mvt/.git/refs/tags
8	./mvt/.git/refs/remotes/origin
8	./mvt/.git/refs/remotes
16	./mvt/.git/refs
3352	./mvt/.git
12240	./mvt
0	./dir
0	./Movies/VN
312	./Movies/TV/Media.localized/.localized
320	./Movies/TV/Media.localized
16	./Movies/TV/TV Library.tvlibrary
336	./Movies/TV
336	./Movies
du: ./.Trash: Operation not permitted
16	./Documents/GitHub/Hello-World/Hello-World.git/objects/pack
0	./Documents/GitHub/Hello-World/Hello-World.git/objects/info
16	./Documents/GitHub/Hello-World/Hello-World.git/objects
8	./Documents/GitHub/Hello-World/Hello-World.git/info
120	./Documents/GitHub/Hello-World/Hello-World.git/hooks
0	./Documents/GitHub/Hello-World/Hello-World.git/refs/heads
0	./Documents/GitHub/Hello-World/Hello-World.git/refs/tags
0	./Documents/GitHub/Hello-World/Hello-World.git/refs
176	./Documents/GitHub/Hello-World/Hello-World.git
16	./Documents/GitHub/Hello-World/.git/objects/pack
0	./Documents/GitHub/Hello-World/.git/objects/info
16	./Documents/GitHub/Hello-World/.git/objects
8	./Documents/GitHub/Hello-World/.git/info
8	./Documents/GitHub/Hello-World/.git/logs/refs/heads
8	./Documents/GitHub/Hello-World/.git/logs/refs/remotes/origin
8	./Documents/GitHub/Hello-World/.git/logs/refs/remotes
16	./Documents/GitHub/Hello-World/.git/logs/refs
24	./Documents/GitHub/Hello-World/.git/logs
120	./Documents/GitHub/Hello-World/.git/hooks
8	./Documents/GitHub/Hello-World/.git/refs/heads
0	./Documents/GitHub/Hello-World/.git/refs/tags
8	./Documents/GitHub/Hello-World/.git/refs/remotes/origin
8	./Documents/GitHub/Hello-World/.git/refs/remotes
16	./Documents/GitHub/Hello-World/.git/refs
0	./Documents/GitHub/Hello-World/.git/branches
232	./Documents/GitHub/Hello-World/.git
416	./Documents/GitHub/Hello-World
416	./Documents/GitHub
456	./Documents
0	./.vscode/extensions
8	./.vscode
8	./.gem/specs/rubygems.org%443/quick/Marshal.4.8
8	./.gem/specs/rubygems.org%443/quick
8	./.gem/specs/rubygems.org%443
8	./.gem/specs
8	./.gem/ruby/2.6.0/specifications
712	./.gem/ruby/2.6.0/cache
16	./.gem/ruby/2.6.0/bin
0	./.gem/ruby/2.6.0/extensions
0	./.gem/ruby/2.6.0/build_info
0	./.gem/ruby/2.6.0/doc
1016	./.gem/ruby/2.6.0/gems/bundler-1.17.3/man
16	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/compact_index_client
24	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ui
8	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ssl_certs/rubygems.global.ssl.fastly.net
8	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ssl_certs/index.rubygems.org
8	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ssl_certs/rubygems.org
40	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ssl_certs
8	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/settings
8	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source/path
8	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source/rubygems
24	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source/git
136	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source
24	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin/api
16	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin/installer
96	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin
40	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/fetcher
272	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli
16	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/test
16	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/bin
24	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/ext/newgem
24	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/ext
16	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/spec
8	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/lib/newgem
16	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/lib
8	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/exe
168	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem
216	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates
32	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/installer
8	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/resolver
16	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/line_editor
24	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/core_ext
64	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/shell
48	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/parser
80	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/actions
456	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor
488	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib
488	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor
16	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/net-http-persistent/lib/net/http/persistent
96	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/net-http-persistent/lib/net/http
96	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/net-http-persistent/lib/net
96	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/net-http-persistent/lib
96	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/net-http-persistent
96	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/fileutils/lib
96	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/fileutils
16	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/delegates
16	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/modules
80	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/dependency_graph
248	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo
256	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib
256	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo
936	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor
2848	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler
2888	./.gem/ruby/2.6.0/gems/bundler-1.17.3/lib
24	./.gem/ruby/2.6.0/gems/bundler-1.17.3/exe
4200	./.gem/ruby/2.6.0/gems/bundler-1.17.3
4200	./.gem/ruby/2.6.0/gems
4936	./.gem/ruby/2.6.0
4936	./.gem/ruby
4944	./.gem
760	./Downloads/Visual Studio Code.app/Contents/_CodeSignature
1176	./Downloads/Visual Studio Code.app/Contents/MacOS
0	./Downloads/Visual Studio Code.app/Contents/Resources/de.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/he.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/ar.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/el.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/ja.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/fa.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/mr.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/en.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/uk.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/es_419.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/gu.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/zh_CN.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/kn.lproj
7696	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/@vscode/sqlite3/build/Release
7696	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/@vscode/sqlite3/build
7696	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/@vscode/sqlite3
26480	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/@vscode/ripgrep/bin
26480	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/@vscode/ripgrep
34176	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/@vscode
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/node-pty/lib/shared
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/node-pty/lib/worker
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/node-pty/lib
384	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/node-pty/build/Release
384	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/node-pty/build
400	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/node-pty
368	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/native-watchdog/build/Release
368	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/native-watchdog/build
368	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/native-watchdog
360	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/windows-foreground-love/build/Release
360	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/windows-foreground-love/build
360	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/windows-foreground-love
384	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/native-keymap/build/Release
384	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/native-keymap/build
384	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/native-keymap
928	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/vscode-oniguruma/release
928	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/vscode-oniguruma
504	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/vsda/build/Release
504	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/vsda/build
504	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/vsda
2072	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/spdlog/build/Release
2072	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/spdlog/build
2072	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/spdlog
5432	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/vscode-encrypt/build/Release
5432	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/vscode-encrypt/build
5432	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/vscode-encrypt
1672	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/@parcel/watcher/build/Release
1672	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/@parcel/watcher/build
1672	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/@parcel/watcher
1672	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/@parcel
632	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/keytar/build/Release
632	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/keytar/build
632	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/keytar
360	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/native-is-elevated/build/Release
360	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/native-is-elevated/build
360	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked/native-is-elevated
47288	./Downloads/Visual Studio Code.app/Contents/Resources/app/node_modules.asar.unpacked
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/bin
6832	./Downloads/Visual Studio Code.app/Contents/Resources/app/licenses
600	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/platform/terminal/node
600	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/platform/terminal
112	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/platform/extensions/node
112	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/platform/extensions
512	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/platform/files/node/watcher
512	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/platform/files/node
512	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/platform/files
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/platform/environment/node
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/platform/environment
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/platform/sharedProcess/electron-browser
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/platform/sharedProcess
1280	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/platform
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/code/electron-browser/workbench
1960	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/code/electron-browser/sharedProcess
1976	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/code/electron-browser
1168	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/code/node
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/code/electron-sandbox/workbench
736	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/code/electron-sandbox/issue
1096	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/code/electron-sandbox/processExplorer
1840	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/code/electron-sandbox
1640	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/code/electron-main
6624	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/code
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/workspace/browser/media
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/workspace/browser
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/workspace
256	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/audioCues/browser/media
256	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/audioCues/browser
256	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/audioCues
80	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/webview/browser/pre
80	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/webview/browser
80	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/webview
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/output/common
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/output
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/terminal/browser/media
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/terminal/browser
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/terminal
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/externalTerminal/node
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/externalTerminal
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/extensions/browser/media
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/extensions/browser
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/extensions
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/welcomeGettingStarted/common/media/notebookThemes
2504	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/welcomeGettingStarted/common/media
2504	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/welcomeGettingStarted/common
2504	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/welcomeGettingStarted
160	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/welcomeOverlay/browser/media
160	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/welcomeOverlay/browser
160	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/welcomeOverlay
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/interactive/browser/docs
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/interactive/browser
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/interactive
336	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/notebook/browser/docs
336	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/notebook/browser
280	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/notebook/common/services
280	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/notebook/common
616	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/notebook
64	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/debug/browser/media
64	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/debug/browser
448	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/debug/node
512	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib/debug
4336	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/contrib
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/browser/parts/editor/media
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/browser/parts/editor
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/browser/parts
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/browser
2784	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/api/node
2096	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/api/worker
4880	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/api
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/services/languageDetection/browser
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/services/languageDetection
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/services/extensions/worker
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/services/extensions
120	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/services/search/worker
120	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/services/search
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/services/extensionManagement/common/media
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/services/extensionManagement/common
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/services/extensionManagement
152	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/services
32144	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench
160	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/base/browser/ui/codicons/codicon
160	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/base/browser/ui/codicons
160	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/base/browser/ui
160	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/base/browser
208	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/base/common/worker
224	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/base/common
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/base/parts/sandbox/electron-browser
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/base/parts/sandbox
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/base/parts
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/base/node
624	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/base/worker
1048	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs/base
41176	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vs
1088	./Downloads/Visual Studio Code.app/Contents/Resources/app/out/vscode-dts
44256	./Downloads/Visual Studio Code.app/Contents/Resources/app/out
56	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/merge-conflict/dist
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/merge-conflict/media
88	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/merge-conflict
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/razor/syntaxes
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/razor
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/shaderlab/syntaxes
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/shaderlab
208	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug-companion/out
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug-companion/resources
376	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug-companion
184	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-seti/icons
216	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-seti
2624	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/html-language-features/server/dist/node
2624	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/html-language-features/server/dist
304	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/html-language-features/server/lib
2936	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/html-language-features/server
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/html-language-features/schemas
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/html-language-features/icons
1224	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/html-language-features/client/dist/node
1224	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/html-language-features/client/dist
1224	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/html-language-features/client
4216	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/html-language-features
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/docker/syntaxes
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/docker
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/go/syntaxes
64	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/go
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/simple-browser/dist
216	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/simple-browser/media
296	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/simple-browser
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-monokai/themes
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-monokai
544	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/json-language-features/server/dist/node
544	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/json-language-features/server/dist
552	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/json-language-features/server
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/json-language-features/icons
1256	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/json-language-features/client/dist/node
1256	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/json-language-features/client/dist
1256	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/json-language-features/client
1848	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/json-language-features
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/gulp/dist
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/gulp/images
80	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/gulp
88	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/configuration-editing/dist
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/configuration-editing/images
136	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/configuration-editing/schemas
248	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/configuration-editing
216	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/python/syntaxes
240	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/python
112	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/css/syntaxes
136	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/css
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/clojure/syntaxes
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/clojure
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/less/syntaxes
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/less
56	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.references-view/dist
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.references-view/media
128	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.references-view
1768	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/css-language-features/server/dist/node
1768	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/css-language-features/server/dist
1776	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/css-language-features/server
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/css-language-features/schemas
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/css-language-features/icons
584	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/css-language-features/client/dist/node
584	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/css-language-features/client/dist
584	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/css-language-features/client
2448	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/css-language-features
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-red/themes
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-red
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/dart/syntaxes
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/dart
56	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/image-preview/dist
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/image-preview/media
136	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/image-preview
1112	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/latex/syntaxes
1168	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/latex
1192	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/typescript-language-features/dist
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/typescript-language-features/schemas
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/typescript-language-features/media
1360	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/typescript-language-features
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/grunt/dist
72	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/grunt/images
136	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/grunt
1320	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/microsoft-authentication/dist
136	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/microsoft-authentication/media
1480	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/microsoft-authentication
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-abyss/themes
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-abyss
80	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/scss/syntaxes
104	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/scss
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/jake/dist
88	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/jake/images
152	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/jake
112	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/perl/syntaxes
144	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/perl
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/rust/syntaxes
64	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/rust
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/pug/syntaxes
56	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/pug
560	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules/typescript/lib/pl
632	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules/typescript/lib/ja
560	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules/typescript/lib/it
528	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules/typescript/lib/cs
736	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules/typescript/lib/ru
488	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules/typescript/lib/zh-cn
480	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules/typescript/lib/zh-tw
544	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules/typescript/lib/pt-br
568	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules/typescript/lib/de
568	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules/typescript/lib/ko
568	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules/typescript/lib/fr
560	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules/typescript/lib/es
544	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules/typescript/lib/tr
67280	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules/typescript/lib
67296	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules/typescript
67296	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/node_modules
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/fsharp/snippets
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/fsharp/syntaxes
80	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/fsharp
96	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/r/syntaxes
120	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/r
312	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ipynb/dist
336	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ipynb
120	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/notebook-renderers/renderer-out
144	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/notebook-renderers
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/java/snippets
56	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/java/syntaxes
88	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/java
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/diff/syntaxes
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/diff
128	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/html/syntaxes
152	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/html
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/php/snippets
224	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/php/syntaxes
264	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/php
1680	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/resources/readme
120	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/resources/light
128	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/resources/dark
1952	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/resources
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/src/ui/configuration
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/src/ui/profiling
176	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/src/ui
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/src/targets/browser
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/src/targets/node
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/src/targets
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/src/adapter/profiling
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/src/adapter/breakpoints
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/src/adapter/console
88	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/src/adapter
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/src/dap
4760	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug/src
8200	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.js-debug
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/lua/syntaxes
56	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/lua
472	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/emmet/dist/node
472	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/emmet/dist
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/emmet/images
544	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/emmet
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/xml/syntaxes
56	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/xml
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-quietlight/themes
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-quietlight
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/vb/snippets
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/vb/syntaxes
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/vb
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-solarized-dark/themes
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-solarized-dark
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/powershell/syntaxes
72	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/powershell
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/typescript-basics/snippets
728	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/typescript-basics/syntaxes
768	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/typescript-basics
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/debug-auto-launch/dist
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/debug-auto-launch/.vscode
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/debug-auto-launch/media
80	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/debug-auto-launch
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/debug-server-ready/dist
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/debug-server-ready/media
80	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/debug-server-ready
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ini/syntaxes
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ini
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/json/syntaxes
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/json
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-tomorrow-night-blue/themes
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-tomorrow-night-blue
792	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/github/dist
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/github/images
0	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/github/testWorkspace/docs/PULL_REQUEST_TEMPLATE
0	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/github/testWorkspace/docs
0	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/github/testWorkspace/PULL_REQUEST_TEMPLATE
0	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/github/testWorkspace
832	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/github
256	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/markdown-language-features/notebook-out
2840	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/markdown-language-features/dist
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/markdown-language-features/schemas
80	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/markdown-language-features/media
3248	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/markdown-language-features
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/git-base/dist
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/git-base/resources/icons
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/git-base/resources
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/git-base/languages
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/git-base/syntaxes
128	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/git-base
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-solarized-light/themes
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-solarized-light
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/handlebars/syntaxes
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/handlebars
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/cpp/snippets
3560	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/cpp/syntaxes
3600	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/cpp
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/swift/snippets
160	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/swift/syntaxes
200	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/swift
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/make/syntaxes
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/make
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/shellscript/syntaxes
64	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/shellscript
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/markdown-basics/snippets
112	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/markdown-basics/syntaxes
144	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/markdown-basics
592	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/markdown-math/notebook-out/fonts
1176	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/markdown-math/notebook-out
520	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/markdown-math/dist
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/markdown-math/preview-styles
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/markdown-math/syntaxes
1760	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/markdown-math
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/yaml/syntaxes
64	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/yaml
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/log/syntaxes
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/log
1424	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/github-authentication/dist
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/github-authentication/images
136	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/github-authentication/media
1592	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/github-authentication
80	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-defaults/fileicons/images
88	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-defaults/fileicons
112	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-defaults/themes
216	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-defaults
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/csharp/snippets
160	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/csharp/syntaxes
192	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/csharp
64	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/julia/syntaxes
88	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/julia
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-monokai-dimmed/themes
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-monokai-dimmed
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/bat/snippets
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/bat/syntaxes
64	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/bat
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/groovy/snippets
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/groovy/syntaxes
72	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/groovy
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/coffeescript/snippets
56	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/coffeescript/syntaxes
88	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/coffeescript
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/javascript/snippets
720	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/javascript/syntaxes
760	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/javascript
280	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.vscode-js-profile-table/out
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.vscode-js-profile-table/resources
424	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ms-vscode.vscode-js-profile-table
464	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/php-language-features/dist
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/php-language-features/icons
512	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/php-language-features
648	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/extension-editing/dist
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/extension-editing/images
672	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/extension-editing
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/hlsl/syntaxes
40	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/hlsl
24	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/restructuredtext/syntaxes
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/restructuredtext
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-kimbie-dark/themes
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/theme-kimbie-dark
544	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/objective-c/syntaxes
568	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/objective-c
648	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/npm/dist
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/npm/images
696	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/npm
80	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ruby/syntaxes
104	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/ruby
2424	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/git/dist
64	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/git/resources/icons/light
64	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/git/resources/icons/dark
136	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/git/resources/icons
216	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/git/resources
2800	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/git
16	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/search-result/dist/media
32	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/search-result/dist
8	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/search-result/images
152	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/search-result/syntaxes
216	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/search-result
48	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/sql/syntaxes
72	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions/sql
113640	./Downloads/Visual Studio Code.app/Contents/Resources/app/extensions
250120	./Downloads/Visual Studio Code.app/Contents/Resources/app
0	./Downloads/Visual Studio Code.app/Contents/Resources/nb.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/am.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/es.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/sw.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/sl.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/pt_BR.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/da.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/et.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/it.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/bg.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/sk.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/pt_PT.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/sr.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/ms.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/ta.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/ml.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/sv.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/te.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/cs.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/ko.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/fil.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/hu.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/tr.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/pl.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/zh_TW.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/en_GB.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/vi.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/lv.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/lt.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/ru.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/fr.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/fi.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/id.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/nl.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/th.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/bn.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/ro.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/hr.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/hi.lproj
0	./Downloads/Visual Studio Code.app/Contents/Resources/ca.lproj
254752	./Downloads/Visual Studio Code.app/Contents/Resources
64	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/_CodeSignature
240	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/de.lproj
296	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/he.lproj
352	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/ar.lproj
424	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/el.lproj
280	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/ja.lproj
344	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/fa.lproj
472	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/mr.lproj
200	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/en.lproj
384	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/uk.lproj
240	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/es_419.lproj
480	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/gu.lproj
200	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/zh_CN.lproj
544	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/kn.lproj
216	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/nb.lproj
344	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/am.lproj
240	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/es.lproj
224	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/sw.lproj
240	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/sl.lproj
232	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/pt_BR.lproj
224	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/da.lproj
216	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/et.lproj
232	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/it.lproj
384	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/bg.lproj
248	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/sk.lproj
232	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/pt_PT.lproj
360	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/sr.lproj
216	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/ms.lproj
568	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/ta.lproj
568	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/ml.lproj
216	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/sv.lproj
528	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/te.lproj
248	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/cs.lproj
232	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/ko.lproj
248	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/fil.lproj
256	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/hu.lproj
232	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/tr.lproj
248	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/pl.lproj
200	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/zh_TW.lproj
192	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/en_GB.lproj
272	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/vi.lproj
256	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/lv.lproj
256	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/lt.lproj
384	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/ru.lproj
256	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/fr.lproj
216	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/fi.lproj
208	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/id.lproj
224	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/nl.lproj
440	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/th.lproj
496	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/bn.lproj
240	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/ro.lproj
232	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/hr.lproj
488	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/hi.lproj
240	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources/ca.lproj
48520	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Resources
121584	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Libraries
4040	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A/Helpers
663544	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions/A
663544	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework/Versions
663544	./Downloads/Visual Studio Code.app/Contents/Frameworks/Electron Framework.framework
8	./Downloads/Visual Studio Code.app/Contents/Frameworks/ReactiveObjC.framework/Versions/A/_CodeSignature
8	./Downloads/Visual Studio Code.app/Contents/Frameworks/ReactiveObjC.framework/Versions/A/Resources
1848	./Downloads/Visual Studio Code.app/Contents/Frameworks/ReactiveObjC.framework/Versions/A
1848	./Downloads/Visual Studio Code.app/Contents/Frameworks/ReactiveObjC.framework/Versions
1848	./Downloads/Visual Studio Code.app/Contents/Frameworks/ReactiveObjC.framework
8	./Downloads/Visual Studio Code.app/Contents/Frameworks/Squirrel.framework/Versions/A/_CodeSignature
616	./Downloads/Visual Studio Code.app/Contents/Frameworks/Squirrel.framework/Versions/A/Resources
1336	./Downloads/Visual Studio Code.app/Contents/Frameworks/Squirrel.framework/Versions/A
1336	./Downloads/Visual Studio Code.app/Contents/Frameworks/Squirrel.framework/Versions
1336	./Downloads/Visual Studio Code.app/Contents/Frameworks/Squirrel.framework
8	./Downloads/Visual Studio Code.app/Contents/Frameworks/Code Helper (GPU).app/Contents/_CodeSignature
816	./Downloads/Visual Studio Code.app/Contents/Frameworks/Code Helper (GPU).app/Contents/MacOS
840	./Downloads/Visual Studio Code.app/Contents/Frameworks/Code Helper (GPU).app/Contents
840	./Downloads/Visual Studio Code.app/Contents/Frameworks/Code Helper (GPU).app
8	./Downloads/Visual Studio Code.app/Contents/Frameworks/Mantle.framework/Versions/A/_CodeSignature
8	./Downloads/Visual Studio Code.app/Contents/Frameworks/Mantle.framework/Versions/A/Resources
488	./Downloads/Visual Studio Code.app/Contents/Frameworks/Mantle.framework/Versions/A
488	./Downloads/Visual Studio Code.app/Contents/Frameworks/Mantle.framework/Versions
488	./Downloads/Visual Studio Code.app/Contents/Frameworks/Mantle.framework
8	./Downloads/Visual Studio Code.app/Contents/Frameworks/Code Helper.app/Contents/_CodeSignature
824	./Downloads/Visual Studio Code.app/Contents/Frameworks/Code Helper.app/Contents/MacOS
848	./Downloads/Visual Studio Code.app/Contents/Frameworks/Code Helper.app/Contents
848	./Downloads/Visual Studio Code.app/Contents/Frameworks/Code Helper.app
8	./Downloads/Visual Studio Code.app/Contents/Frameworks/Code Helper (Renderer).app/Contents/_CodeSignature
816	./Downloads/Visual Studio Code.app/Contents/Frameworks/Code Helper (Renderer).app/Contents/MacOS
840	./Downloads/Visual Studio Code.app/Contents/Frameworks/Code Helper (Renderer).app/Contents
840	./Downloads/Visual Studio Code.app/Contents/Frameworks/Code Helper (Renderer).app
669744	./Downloads/Visual Studio Code.app/Contents/Frameworks
926520	./Downloads/Visual Studio Code.app/Contents
926520	./Downloads/Visual Studio Code.app
24	./Downloads/mvt-1.5.4/tests/artifacts/android_data/bugreport
32	./Downloads/mvt-1.5.4/tests/artifacts/android_data
8	./Downloads/mvt-1.5.4/tests/artifacts/android_backup/apps/com.android.providers.telephony/d_f
8	./Downloads/mvt-1.5.4/tests/artifacts/android_backup/apps/com.android.providers.telephony
8	./Downloads/mvt-1.5.4/tests/artifacts/android_backup/apps
48	./Downloads/mvt-1.5.4/tests/artifacts/android_backup
176	./Downloads/mvt-1.5.4/tests/artifacts/ios_backup/0d
56	./Downloads/mvt-1.5.4/tests/artifacts/ios_backup/3d
80	./Downloads/mvt-1.5.4/tests/artifacts/ios_backup/3a
112	./Downloads/mvt-1.5.4/tests/artifacts/ios_backup/64
6856	./Downloads/mvt-1.5.4/tests/artifacts/ios_backup
6952	./Downloads/mvt-1.5.4/tests/artifacts
48	./Downloads/mvt-1.5.4/tests/ios
8	./Downloads/mvt-1.5.4/tests/common
32	./Downloads/mvt-1.5.4/tests/android
7072	./Downloads/mvt-1.5.4/tests
16	./Downloads/mvt-1.5.4/docs/ios/filesystem
32	./Downloads/mvt-1.5.4/docs/ios/backup
104	./Downloads/mvt-1.5.4/docs/ios
280	./Downloads/mvt-1.5.4/docs/img
32	./Downloads/mvt-1.5.4/docs/android
520	./Downloads/mvt-1.5.4/docs
240	./Downloads/mvt-1.5.4/mvt/ios/modules/mixed
56	./Downloads/mvt-1.5.4/mvt/ios/modules/backup
104	./Downloads/mvt-1.5.4/mvt/ios/modules/fs
448	./Downloads/mvt-1.5.4/mvt/ios/modules
528	./Downloads/mvt-1.5.4/mvt/ios
120	./Downloads/mvt-1.5.4/mvt/common
56	./Downloads/mvt-1.5.4/mvt/android/parsers
24	./Downloads/mvt-1.5.4/mvt/android/lookups
96	./Downloads/mvt-1.5.4/mvt/android/modules/bugreport
208	./Downloads/mvt-1.5.4/mvt/android/modules/adb
24	./Downloads/mvt-1.5.4/mvt/android/modules/backup
336	./Downloads/mvt-1.5.4/mvt/android/modules
16	./Downloads/mvt-1.5.4/mvt/android/data
488	./Downloads/mvt-1.5.4/mvt/android
1144	./Downloads/mvt-1.5.4/mvt
8	./Downloads/mvt-1.5.4/.github/workflows
8	./Downloads/mvt-1.5.4/.github
16	./Downloads/mvt-1.5.4/dev
8904	./Downloads/mvt-1.5.4
24	./Downloads/snort3_extra-3.1.29.0/cmake
8	./Downloads/snort3_extra-3.1.29.0/scripts
8	./Downloads/snort3_extra-3.1.29.0/templates
8	./Downloads/snort3_extra-3.1.29.0/container_comparisons/include
40	./Downloads/snort3_extra-3.1.29.0/container_comparisons/src
72	./Downloads/snort3_extra-3.1.29.0/container_comparisons
32	./Downloads/snort3_extra-3.1.29.0/src/so_rules/sid_18758
40	./Downloads/snort3_extra-3.1.29.0/src/so_rules
16	./Downloads/snort3_extra-3.1.29.0/src/loggers/alert_ex
16	./Downloads/snort3_extra-3.1.29.0/src/loggers/log_null
16	./Downloads/snort3_extra-3.1.29.0/src/loggers/alert_lua
56	./Downloads/snort3_extra-3.1.29.0/src/loggers
16	./Downloads/snort3_extra-3.1.29.0/src/codecs/cd_ppp
24	./Downloads/snort3_extra-3.1.29.0/src/codecs/cd_pbb
16	./Downloads/snort3_extra-3.1.29.0/src/codecs/cd_slip
24	./Downloads/snort3_extra-3.1.29.0/src/codecs/cd_wlan
16	./Downloads/snort3_extra-3.1.29.0/src/codecs/cd_linux_sll
16	./Downloads/snort3_extra-3.1.29.0/src/codecs/cd_null
24	./Downloads/snort3_extra-3.1.29.0/src/codecs/cd_pflog
16	./Downloads/snort3_extra-3.1.29.0/src/codecs/cd_eapol
24	./Downloads/snort3_extra-3.1.29.0/src/codecs/cd_token_ring
184	./Downloads/snort3_extra-3.1.29.0/src/codecs
56	./Downloads/snort3_extra-3.1.29.0/src/daqs/daq_socket
64	./Downloads/snort3_extra-3.1.29.0/src/daqs
64	./Downloads/snort3_extra-3.1.29.0/src/search_engines/lowmem
72	./Downloads/snort3_extra-3.1.29.0/src/search_engines
16	./Downloads/snort3_extra-3.1.29.0/src/inspectors/null_trace_logger
16	./Downloads/snort3_extra-3.1.29.0/src/inspectors/cpeos_test
56	./Downloads/snort3_extra-3.1.29.0/src/inspectors/appid_listener
40	./Downloads/snort3_extra-3.1.29.0/src/inspectors/domain_filter
24	./Downloads/snort3_extra-3.1.29.0/src/inspectors/mem_test
24	./Downloads/snort3_extra-3.1.29.0/src/inspectors/data_log
24	./Downloads/snort3_extra-3.1.29.0/src/inspectors/dpx
208	./Downloads/snort3_extra-3.1.29.0/src/inspectors
24	./Downloads/snort3_extra-3.1.29.0/src/tp_appid
24	./Downloads/snort3_extra-3.1.29.0/src/ips_options/ips_pkt_num
24	./Downloads/snort3_extra-3.1.29.0/src/ips_options/ips_mss
24	./Downloads/snort3_extra-3.1.29.0/src/ips_options/ips_wscale
24	./Downloads/snort3_extra-3.1.29.0/src/ips_options/ips_urg
16	./Downloads/snort3_extra-3.1.29.0/src/ips_options/find
120	./Downloads/snort3_extra-3.1.29.0/src/ips_options
776	./Downloads/snort3_extra-3.1.29.0/src
1056	./Downloads/snort3_extra-3.1.29.0
166024	./Downloads/mac
29537136	./Downloads
60162760	.
horus@Rs-MacBook-Pro ~ % free
zsh: command not found: free
horus@Rs-MacBook-Pro ~ % whois user
% IANA WHOIS server
% for more information on IANA, visit http://www.iana.org
% This query returned 0 objects.
%
% You queried for user but this server does not have
% any data for user.
%
% If you need further information please check the web site
% or use -h for help

horus@Rs-MacBook-Pro ~ % dig domain

; <<>> DiG 9.10.6 <<>> domain
;; global options: +cmd
;; Got answer:
;; ->>HEADER<<- opcode: QUERY, status: NXDOMAIN, id: 3397
;; flags: qr rd ra ad; QUERY: 1, ANSWER: 0, AUTHORITY: 1, ADDITIONAL: 1

;; OPT PSEUDOSECTION:
; EDNS: version: 0, flags:; udp: 512
;; QUESTION SECTION:
;domain.				IN	A

;; AUTHORITY SECTION:
.			10800	IN	SOA	a.root-servers.net. nstld.verisign-grs.com. 2022051700 1800 900 604800 86400

;; Query time: 116 msec
;; SERVER: 2001:558:feed::1#53(2001:558:feed::1)
;; WHEN: Tue May 17 13:06:59 EDT 2022
;; MSG SIZE  rcvd: 110

horus@Rs-MacBook-Pro ~ % dig -xgn-grs.com

; <<>> DiG 9.10.6 <<>> -xgn-grs.com
;; global options: +cmd
;; Got answer:
;; ->>HEADER<<- opcode: QUERY, status: NXDOMAIN, id: 46145
;; flags: qr rd ra ad; QUERY: 1, ANSWER: 0, AUTHORITY: 1, ADDITIONAL: 1

;; OPT PSEUDOSECTION:
; EDNS: version: 0, flags:; udp: 512
;; QUESTION SECTION:
;com.gn-grs.in-addr.arpa.	IN	PTR

;; AUTHORITY SECTION:
in-addr.arpa.		3600	IN	SOA	b.in-addr-servers.arpa. nstld.iana.org. 2022033335 1800 900 604800 3600

;; Query time: 42 msec
;; SERVER: 2001:558:feed::1#53(2001:558:feed::1)
;; WHEN: Tue May 17 13:07:16 EDT 2022
;; MSG SIZE  rcvd: 120

horus@Rs-MacBook-Pro ~ % locate horus
/Users/horus
/Users/horus/.CFUserTextEncoding
/Users/horus/.DS_Store
/Users/horus/.Trash
/Users/horus/.bundle
/Users/horus/.bundle/cache
/Users/horus/.bundle/cache/compact_index
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/activesupport
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/adamantium
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/addressable
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/ansi
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/archive-tar-minitar
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/ast
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/astrolabe
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/atomic
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/axiom-types
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/backports
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/bcrypt_pbkdf
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/bindata
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/binding_of_caller
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/bootsnap
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/builder
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/byebug
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/coercible
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/columnize
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/concurrent-ruby
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/connection_pool
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/date
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/debug_inspector
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/debugger-linecache
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/debugger-ruby_core_source
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/descendants_tracker
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/did_you_mean
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/diff-lcs
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/docile
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/domain_name
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/ecma-re-validator
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/elftools
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/equalizer
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/ffi
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/functional-ruby
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/gemcutter
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/hamster
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/hana
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/hashie
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/hoe
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/hpricot
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/http-cookie
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/i18n
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/ice_nine
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/interception
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/io-wait
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/jar-dependencies
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/jaro_winkler
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/jruby-pageant
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/json
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/json_pure
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/json_schemer
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/libxml-ruby
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/link_header
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/lockfile
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/maven-tools
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/mechanize
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/memcache-client
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/memoizable
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/method_source
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/mime-types
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/mime-types-data
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/mini_portile
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/mini_portile2
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/minitar
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/minitar-cli
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/minitest
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/msgpack
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/multi_json
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/mustache
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/narf
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/needle
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/net-ftp
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/net-http-digest_auth
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/net-http-persistent
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/net-protocol
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/net-scp
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/net-ssh
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/nokogiri
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/ntlm-http
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/parallel
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/parallel_tests
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/parser
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/patchelf
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/pkg-config
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/plist
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/powerbar
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/powerpack
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/psych
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/public_suffix
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/racc
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rack
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rainbow
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rake
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rb-readline
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rbnacl
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rbnacl-libsodium
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rdf
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rdiscount
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/ref
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/regexp_parser
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rexml
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/ronn
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rspec
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rspec-core
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rspec-expectations
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rspec-github
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rspec-its
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rspec-mocks
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rspec-retry
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rspec-support
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rspec-wait
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rspec_junit_formatter
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rubocop
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rubocop-ast
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rubocop-performance
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rubocop-rails
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rubocop-rspec
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rubocop-sorbet
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/ruby-macho
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/ruby-maven
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/ruby-maven-libs
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/ruby-progressbar
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/ruby-web
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/ruby_core_source
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/ruby_parser
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rubyforge
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/rubyntlm
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/sexp_processor
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/simplecov
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/simplecov-cobertura
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/simplecov-html
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/simplecov_json_formatter
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/slop
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/snappy
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/snappy-jars
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/sorbet-runtime-stub
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/spruz
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/sqlite3
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/stringio
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/strscan
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/sync
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/term-ansicolor
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/text
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/thor
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/thread_safe
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/time
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/timeout
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/tins
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/tzinfo
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/unf
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/unf_ext
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/unicode-display_width
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/uri_template
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/virtus
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/warning
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/weakling
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/webrick
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/webrobots
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info/zeitwerk
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info-special-characters
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info-special-characters/ParseTree-405fcd45b4c29adf532d2f46c40685b9
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info-special-characters/RubyInline-bb8de470fe25da785daa7103b796cbb0
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info-special-characters/SexpProcessor-279a3902a42d95552801b89581216e61
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/info-special-characters/ZenTest-72d945c087709fb89086cd9a29466c4d
/Users/horus/.bundle/cache/compact_index/rubygems.org.443.29b0360b937aa4d161703e6160654e47/versions
/Users/horus/.cups
/Users/horus/.gem
/Users/horus/.gem/ruby
/Users/horus/.gem/ruby/2.6.0
/Users/horus/.gem/ruby/2.6.0/bin
/Users/horus/.gem/ruby/2.6.0/bin/bundle
/Users/horus/.gem/ruby/2.6.0/bin/bundler
/Users/horus/.gem/ruby/2.6.0/build_info
/Users/horus/.gem/ruby/2.6.0/cache
/Users/horus/.gem/ruby/2.6.0/cache/bundler-1.17.3.gem
/Users/horus/.gem/ruby/2.6.0/doc
/Users/horus/.gem/ruby/2.6.0/extensions
/Users/horus/.gem/ruby/2.6.0/gems
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/CHANGELOG.md
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/LICENSE.md
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/README.md
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/bundler.gemspec
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/exe
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/exe/bundle
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/exe/bundle_ruby
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/exe/bundler
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/build_metadata.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/capistrano.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/add.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/binstubs.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/cache.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/check.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/clean.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/common.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/config.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/console.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/doctor.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/exec.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/gem.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/info.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/init.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/inject.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/install.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/issue.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/list.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/lock.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/open.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/outdated.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/package.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/platform.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/plugin.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/pristine.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/remove.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/show.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/update.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli/viz.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/cli.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/compact_index_client
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/compact_index_client/cache.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/compact_index_client/updater.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/compact_index_client.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/compatibility_guard.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/constants.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/current_ruby.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/definition.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/dep_proxy.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/dependency.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/deployment.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/deprecate.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/dsl.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/endpoint_specification.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/env.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/environment_preserver.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/errors.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/feature_flag.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/fetcher
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/fetcher/base.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/fetcher/compact_index.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/fetcher/dependency.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/fetcher/downloader.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/fetcher/index.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/fetcher.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/friendly_errors.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/gem_helper.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/gem_helpers.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/gem_remote_fetcher.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/gem_tasks.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/gem_version_promoter.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/gemdeps.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/graph.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/index.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/injector.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/inline.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/installer
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/installer/gem_installer.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/installer/parallel_installer.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/installer/standalone.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/installer.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/lazy_specification.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/lockfile_generator.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/lockfile_parser.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/match_platform.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/mirror.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin/api
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin/api/source.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin/api.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin/dsl.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin/events.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin/index.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin/installer
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin/installer/git.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin/installer/rubygems.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin/installer.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin/source_list.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/plugin.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/process_lock.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/psyched_yaml.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/remote_specification.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/resolver
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/resolver/spec_group.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/resolver.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/retry.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ruby_dsl.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ruby_version.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/rubygems_ext.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/rubygems_gem_installer.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/rubygems_integration.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/runtime.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/settings
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/settings/validator.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/settings.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/setup.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/shared_helpers.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/similarity_detector.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source/gemspec.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source/git
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source/git/git_proxy.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source/git.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source/metadata.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source/path
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source/path/installer.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source/path.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source/rubygems
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source/rubygems/remote.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source/rubygems.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/source_list.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/spec_set.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ssl_certs
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ssl_certs/.document
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ssl_certs/certificate_manager.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ssl_certs/index.rubygems.org
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ssl_certs/index.rubygems.org/GlobalSignRootCA.pem
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ssl_certs/rubygems.global.ssl.fastly.net
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ssl_certs/rubygems.global.ssl.fastly.net/DigiCertHighAssuranceEVRootCA.pem
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ssl_certs/rubygems.org
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ssl_certs/rubygems.org/AddTrustExternalCARoot.pem
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/stub_specification.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/.document
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/Executable
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/Executable.bundler
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/Executable.standalone
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/Gemfile
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/gems.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/CODE_OF_CONDUCT.md.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/Gemfile.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/LICENSE.txt.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/README.md.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/Rakefile.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/bin
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/bin/console.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/bin/setup.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/exe
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/exe/newgem.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/ext
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/ext/newgem
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/ext/newgem/extconf.rb.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/ext/newgem/newgem.c.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/ext/newgem/newgem.h.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/gitignore.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/lib
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/lib/newgem
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/lib/newgem/version.rb.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/lib/newgem.rb.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/newgem.gemspec.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/rspec.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/spec
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/spec/newgem_spec.rb.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/spec/spec_helper.rb.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/test
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/test/newgem_test.rb.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/test/test_helper.rb.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/templates/newgem/travis.yml.tt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ui
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ui/rg_proxy.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ui/shell.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ui/silent.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/ui.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/uri_credentials_filter.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/fileutils
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/fileutils/lib
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/fileutils/lib/fileutils.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/compatibility.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/delegates
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/delegates/resolution_state.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/delegates/specification_provider.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/dependency_graph
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/dependency_graph/action.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/dependency_graph/add_edge_no_circular.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/dependency_graph/add_vertex.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/dependency_graph/delete_edge.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/dependency_graph/detach_vertex_named.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/dependency_graph/log.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/dependency_graph/set_payload.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/dependency_graph/tag.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/dependency_graph/vertex.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/dependency_graph.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/errors.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/gem_metadata.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/modules
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/modules/specification_provider.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/modules/ui.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/resolution.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/resolver.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo/state.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/molinillo/lib/molinillo.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/net-http-persistent
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/net-http-persistent/lib
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/net-http-persistent/lib/net
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/net-http-persistent/lib/net/http
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/net-http-persistent/lib/net/http/faster.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/net-http-persistent/lib/net/http/persistent
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/net-http-persistent/lib/net/http/persistent/ssl_reuse.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/net-http-persistent/lib/net/http/persistent.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/actions
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/actions/create_file.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/actions/create_link.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/actions/directory.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/actions/empty_directory.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/actions/file_manipulation.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/actions/inject_into_file.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/actions.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/base.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/command.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/core_ext
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/core_ext/hash_with_indifferent_access.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/core_ext/io_binary_read.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/core_ext/ordered_hash.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/error.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/group.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/invocation.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/line_editor
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/line_editor/basic.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/line_editor/readline.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/line_editor.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/parser
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/parser/argument.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/parser/arguments.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/parser/option.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/parser/options.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/parser.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/rake_compat.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/runner.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/shell
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/shell/basic.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/shell/color.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/shell/html.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/shell.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/util.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor/version.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendor/thor/lib/thor.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendored_fileutils.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendored_molinillo.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendored_persistent.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vendored_thor.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/version.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/version_ranges.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/vlad.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/worker.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler/yaml_serializer.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/lib/bundler.rb
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-add.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-add.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-add.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-binstubs.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-binstubs.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-binstubs.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-check.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-check.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-check.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-clean.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-clean.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-clean.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-config.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-config.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-config.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-doctor.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-doctor.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-doctor.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-exec.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-exec.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-exec.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-gem.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-gem.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-gem.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-info.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-info.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-info.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-init.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-init.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-init.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-inject.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-inject.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-inject.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-install.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-install.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-install.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-list.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-list.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-list.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-lock.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-lock.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-lock.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-open.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-open.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-open.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-outdated.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-outdated.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-outdated.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-package.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-package.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-package.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-platform.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-platform.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-platform.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-pristine.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-pristine.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-pristine.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-remove.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-remove.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-remove.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-show.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-show.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-show.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-update.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-update.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-update.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-viz.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-viz.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle-viz.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle.1
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle.1.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/bundle.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/gemfile.5
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/gemfile.5.ronn
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/gemfile.5.txt
/Users/horus/.gem/ruby/2.6.0/gems/bundler-1.17.3/man/index.txt
/Users/horus/.gem/ruby/2.6.0/specifications
/Users/horus/.gem/ruby/2.6.0/specifications/bundler-1.17.3.gemspec
/Users/horus/.gem/specs
/Users/horus/.gem/specs/rubygems.org%443
/Users/horus/.gem/specs/rubygems.org%443/quick
/Users/horus/.gem/specs/rubygems.org%443/quick/Marshal.4.8
/Users/horus/.gem/specs/rubygems.org%443/quick/Marshal.4.8/bundler-1.17.3.gemspec
/Users/horus/.gitconfig
/Users/horus/.viminfo
/Users/horus/.vscode
/Users/horus/.vscode/argv.json
/Users/horus/.vscode/extensions
/Users/horus/.zprofile
/Users/horus/.zsh_history
/Users/horus/Desktop
/Users/horus/Documents
/Users/horus/Downloads
/Users/horus/Final Cut Pro Trial
/Users/horus/Library
/Users/horus/Movies
/Users/horus/Music
/Users/horus/Pictures
/Users/horus/Public
/Users/horus/Public/.localized
/Users/horus/Public/Drop Box
/Users/horus/Snort User Guide 2022.pdf
/Users/horus/iCloud Drive (Archive)
/Users/horus/volatility3
/Users/horus/volatility3/.git
/Users/horus/volatility3/.git/HEAD
/Users/horus/volatility3/.git/config
/Users/horus/volatility3/.git/description
/Users/horus/volatility3/.git/hooks
/Users/horus/volatility3/.git/hooks/applypatch-msg.sample
/Users/horus/volatility3/.git/hooks/commit-msg.sample
/Users/horus/volatility3/.git/hooks/fsmonitor-watchman.sample
/Users/horus/volatility3/.git/hooks/post-update.sample
/Users/horus/volatility3/.git/hooks/pre-applypatch.sample
/Users/horus/volatility3/.git/hooks/pre-commit.sample
/Users/horus/volatility3/.git/hooks/pre-merge-commit.sample
/Users/horus/volatility3/.git/hooks/pre-push.sample
/Users/horus/volatility3/.git/hooks/pre-rebase.sample
/Users/horus/volatility3/.git/hooks/pre-receive.sample
/Users/horus/volatility3/.git/hooks/prepare-commit-msg.sample
/Users/horus/volatility3/.git/hooks/push-to-checkout.sample
/Users/horus/volatility3/.git/hooks/update.sample
/Users/horus/volatility3/.git/index
/Users/horus/volatility3/.git/info
/Users/horus/volatility3/.git/info/exclude
/Users/horus/volatility3/.git/logs
/Users/horus/volatility3/.git/logs/HEAD
/Users/horus/volatility3/.git/logs/refs
/Users/horus/volatility3/.git/logs/refs/heads
/Users/horus/volatility3/.git/logs/refs/heads/develop
/Users/horus/volatility3/.git/logs/refs/remotes
/Users/horus/volatility3/.git/logs/refs/remotes/origin
/Users/horus/volatility3/.git/logs/refs/remotes/origin/HEAD
/Users/horus/volatility3/.git/objects
/Users/horus/volatility3/.git/objects/info
/Users/horus/volatility3/.git/objects/pack
/Users/horus/volatility3/.git/objects/pack/pack-d2340133664a385a24aa7aaa5653566ca3ec6406.idx
/Users/horus/volatility3/.git/objects/pack/pack-d2340133664a385a24aa7aaa5653566ca3ec6406.pack
/Users/horus/volatility3/.git/packed-refs
/Users/horus/volatility3/.git/refs
/Users/horus/volatility3/.git/refs/heads
/Users/horus/volatility3/.git/refs/heads/develop
/Users/horus/volatility3/.git/refs/remotes
/Users/horus/volatility3/.git/refs/remotes/origin
/Users/horus/volatility3/.git/refs/remotes/origin/HEAD
/Users/horus/volatility3/.git/refs/tags
/Users/horus/volatility3/.github
/Users/horus/volatility3/.github/ISSUE_TEMPLATE
/Users/horus/volatility3/.github/ISSUE_TEMPLATE/bug_report.md
/Users/horus/volatility3/.github/ISSUE_TEMPLATE/feature_request.md
/Users/horus/volatility3/.github/workflows
/Users/horus/volatility3/.github/workflows/build-pypi.yml
/Users/horus/volatility3/.gitignore
/Users/horus/volatility3/.readthedocs.yml
/Users/horus/volatility3/.style.yapf
/Users/horus/volatility3/API_CHANGES.md
/Users/horus/volatility3/LICENSE.txt
/Users/horus/volatility3/MANIFEST.in
/Users/horus/volatility3/README.md
/Users/horus/volatility3/development
/Users/horus/volatility3/development/__init__.py
/Users/horus/volatility3/development/banner_server.py
/Users/horus/volatility3/development/centos-kernels.txt
/Users/horus/volatility3/development/compare-vol.py
/Users/horus/volatility3/development/debian-kernels.txt
/Users/horus/volatility3/development/fedora-kernels.txt
/Users/horus/volatility3/development/jsonschema.schema
/Users/horus/volatility3/development/mac-kdk
/Users/horus/volatility3/development/mac-kdk/extract_kernel.sh
/Users/horus/volatility3/development/mac-kdk/generate_json.sh
/Users/horus/volatility3/development/mac-kdk/parse_pbzx2.py
/Users/horus/volatility3/development/pdbparse-to-json.py
/Users/horus/volatility3/development/schema_validate.py
/Users/horus/volatility3/development/stock-linux-json.py
/Users/horus/volatility3/doc
/Users/horus/volatility3/doc/Makefile
/Users/horus/volatility3/doc/make.bat
/Users/horus/volatility3/doc/requirements.txt
/Users/horus/volatility3/doc/source
/Users/horus/volatility3/doc/source/_static
/Users/horus/volatility3/doc/source/_static/favicon.ico
/Users/horus/volatility3/doc/source/_static/vol.png
/Users/horus/volatility3/doc/source/basics.rst
/Users/horus/volatility3/doc/source/complex-plugin.rst
/Users/horus/volatility3/doc/source/conf.py
/Users/horus/volatility3/doc/source/development.rst
/Users/horus/volatility3/doc/source/glossary.rst
/Users/horus/volatility3/doc/source/index.rst
/Users/horus/volatility3/doc/source/simple-plugin.rst
/Users/horus/volatility3/doc/source/symbol-tables.rst
/Users/horus/volatility3/doc/source/using-as-a-library.rst
/Users/horus/volatility3/doc/source/vol-cli.rst
/Users/horus/volatility3/doc/source/vol2to3.rst
/Users/horus/volatility3/doc/source/volshell.rst
/Users/horus/volatility3/mypy.ini
/Users/horus/volatility3/requirements-minimal.txt
/Users/horus/volatility3/requirements.txt
/Users/horus/volatility3/setup.py
/Users/horus/volatility3/vol.py
/Users/horus/volatility3/vol.spec
/Users/horus/volatility3/volatility3
/Users/horus/volatility3/volatility3/__init__.py
/Users/horus/volatility3/volatility3/cli
/Users/horus/volatility3/volatility3/cli/__init__.py
/Users/horus/volatility3/volatility3/cli/text_renderer.py
/Users/horus/volatility3/volatility3/cli/volargparse.py
/Users/horus/volatility3/volatility3/cli/volshell
/Users/horus/volatility3/volatility3/cli/volshell/__init__.py
/Users/horus/volatility3/volatility3/cli/volshell/generic.py
/Users/horus/volatility3/volatility3/cli/volshell/linux.py
/Users/horus/volatility3/volatility3/cli/volshell/mac.py
/Users/horus/volatility3/volatility3/cli/volshell/windows.py
/Users/horus/volatility3/volatility3/framework
/Users/horus/volatility3/volatility3/framework/__init__.py
/Users/horus/volatility3/volatility3/framework/automagic
/Users/horus/volatility3/volatility3/framework/automagic/__init__.py
/Users/horus/volatility3/volatility3/framework/automagic/construct_layers.py
/Users/horus/volatility3/volatility3/framework/automagic/linux.py
/Users/horus/volatility3/volatility3/framework/automagic/mac.py
/Users/horus/volatility3/volatility3/framework/automagic/module.py
/Users/horus/volatility3/volatility3/framework/automagic/pdbscan.py
/Users/horus/volatility3/volatility3/framework/automagic/stacker.py
/Users/horus/volatility3/volatility3/framework/automagic/symbol_cache.py
/Users/horus/volatility3/volatility3/framework/automagic/symbol_finder.py
/Users/horus/volatility3/volatility3/framework/automagic/windows.py
/Users/horus/volatility3/volatility3/framework/configuration
/Users/horus/volatility3/volatility3/framework/configuration/__init__.py
/Users/horus/volatility3/volatility3/framework/configuration/requirements.py
/Users/horus/volatility3/volatility3/framework/constants
/Users/horus/volatility3/volatility3/framework/constants/__init__.py
/Users/horus/volatility3/volatility3/framework/constants/linux
/Users/horus/volatility3/volatility3/framework/constants/linux/__init__.py
/Users/horus/volatility3/volatility3/framework/constants/windows
/Users/horus/volatility3/volatility3/framework/constants/windows/__init__.py
/Users/horus/volatility3/volatility3/framework/contexts
/Users/horus/volatility3/volatility3/framework/contexts/__init__.py
/Users/horus/volatility3/volatility3/framework/exceptions.py
/Users/horus/volatility3/volatility3/framework/interfaces
/Users/horus/volatility3/volatility3/framework/interfaces/__init__.py
/Users/horus/volatility3/volatility3/framework/interfaces/automagic.py
/Users/horus/volatility3/volatility3/framework/interfaces/configuration.py
/Users/horus/volatility3/volatility3/framework/interfaces/context.py
/Users/horus/volatility3/volatility3/framework/interfaces/layers.py
/Users/horus/volatility3/volatility3/framework/interfaces/objects.py
/Users/horus/volatility3/volatility3/framework/interfaces/plugins.py
/Users/horus/volatility3/volatility3/framework/interfaces/renderers.py
/Users/horus/volatility3/volatility3/framework/interfaces/symbols.py
/Users/horus/volatility3/volatility3/framework/layers
/Users/horus/volatility3/volatility3/framework/layers/__init__.py
/Users/horus/volatility3/volatility3/framework/layers/avml.py
/Users/horus/volatility3/volatility3/framework/layers/codecs
/Users/horus/volatility3/volatility3/framework/layers/codecs/__init__.py
/Users/horus/volatility3/volatility3/framework/layers/crash.py
/Users/horus/volatility3/volatility3/framework/layers/elf.py
/Users/horus/volatility3/volatility3/framework/layers/intel.py
/Users/horus/volatility3/volatility3/framework/layers/leechcore.py
/Users/horus/volatility3/volatility3/framework/layers/lime.py
/Users/horus/volatility3/volatility3/framework/layers/linear.py
/Users/horus/volatility3/volatility3/framework/layers/msf.py
/Users/horus/volatility3/volatility3/framework/layers/physical.py
/Users/horus/volatility3/volatility3/framework/layers/qemu.py
/Users/horus/volatility3/volatility3/framework/layers/registry.py
/Users/horus/volatility3/volatility3/framework/layers/resources.py
/Users/horus/volatility3/volatility3/framework/layers/scanners
/Users/horus/volatility3/volatility3/framework/layers/scanners/__init__.py
/Users/horus/volatility3/volatility3/framework/layers/scanners/multiregexp.py
/Users/horus/volatility3/volatility3/framework/layers/segmented.py
/Users/horus/volatility3/volatility3/framework/layers/vmware.py
/Users/horus/volatility3/volatility3/framework/objects
/Users/horus/volatility3/volatility3/framework/objects/__init__.py
/Users/horus/volatility3/volatility3/framework/objects/templates.py
/Users/horus/volatility3/volatility3/framework/objects/utility.py
/Users/horus/volatility3/volatility3/framework/plugins
/Users/horus/volatility3/volatility3/framework/plugins/__init__.py
/Users/horus/volatility3/volatility3/framework/plugins/banners.py
/Users/horus/volatility3/volatility3/framework/plugins/configwriter.py
/Users/horus/volatility3/volatility3/framework/plugins/frameworkinfo.py
/Users/horus/volatility3/volatility3/framework/plugins/isfinfo.py
/Users/horus/volatility3/volatility3/framework/plugins/layerwriter.py
/Users/horus/volatility3/volatility3/framework/plugins/linux
/Users/horus/volatility3/volatility3/framework/plugins/linux/__init__.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/bash.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/check_afinfo.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/check_creds.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/check_idt.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/check_modules.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/check_syscall.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/elfs.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/keyboard_notifiers.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/kmsg.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/lsmod.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/lsof.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/malfind.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/mountinfo.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/proc.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/pslist.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/pstree.py
/Users/horus/volatility3/volatility3/framework/plugins/linux/tty_check.py
/Users/horus/volatility3/volatility3/framework/plugins/mac
/Users/horus/volatility3/volatility3/framework/plugins/mac/__init__.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/bash.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/check_syscall.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/check_sysctl.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/check_trap_table.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/ifconfig.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/kauth_listeners.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/kauth_scopes.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/kevents.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/list_files.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/lsmod.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/lsof.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/malfind.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/mount.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/netstat.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/proc_maps.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/psaux.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/pslist.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/pstree.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/socket_filters.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/timers.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/trustedbsd.py
/Users/horus/volatility3/volatility3/framework/plugins/mac/vfsevents.py
/Users/horus/volatility3/volatility3/framework/plugins/timeliner.py
/Users/horus/volatility3/volatility3/framework/plugins/windows
/Users/horus/volatility3/volatility3/framework/plugins/windows/__init__.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/bigpools.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/cachedump.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/callbacks.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/cmdline.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/crashinfo.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/devicetree.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/dlllist.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/driverirp.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/driverscan.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/dumpfiles.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/envars.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/filescan.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/getservicesids.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/getsids.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/handles.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/hashdump.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/info.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/ldrmodules.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/lsadump.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/malfind.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/mbrscan.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/memmap.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/mftscan.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/modscan.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/modules.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/mutantscan.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/netscan.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/netstat.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/poolscanner.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/privileges.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/pslist.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/psscan.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/pstree.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/registry
/Users/horus/volatility3/volatility3/framework/plugins/windows/registry/__init__.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/registry/hivelist.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/registry/hivescan.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/registry/printkey.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/registry/userassist.json
/Users/horus/volatility3/volatility3/framework/plugins/windows/registry/userassist.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/sessions.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/sids_and_privileges.json
/Users/horus/volatility3/volatility3/framework/plugins/windows/skeleton_key_check.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/ssdt.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/strings.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/svcscan.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/symlinkscan.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/vadinfo.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/vadyarascan.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/verinfo.py
/Users/horus/volatility3/volatility3/framework/plugins/windows/virtmap.py
/Users/horus/volatility3/volatility3/framework/plugins/yarascan.py
/Users/horus/volatility3/volatility3/framework/renderers
/Users/horus/volatility3/volatility3/framework/renderers/__init__.py
/Users/horus/volatility3/volatility3/framework/renderers/conversion.py
/Users/horus/volatility3/volatility3/framework/renderers/format_hints.py
/Users/horus/volatility3/volatility3/framework/symbols
/Users/horus/volatility3/volatility3/framework/symbols/__init__.py
/Users/horus/volatility3/volatility3/framework/symbols/generic
/Users/horus/volatility3/volatility3/framework/symbols/generic/__init__.py
/Users/horus/volatility3/volatility3/framework/symbols/generic/qemu.json
/Users/horus/volatility3/volatility3/framework/symbols/intermed.py
/Users/horus/volatility3/volatility3/framework/symbols/linux
/Users/horus/volatility3/volatility3/framework/symbols/linux/__init__.py
/Users/horus/volatility3/volatility3/framework/symbols/linux/bash.py
/Users/horus/volatility3/volatility3/framework/symbols/linux/bash32.json
/Users/horus/volatility3/volatility3/framework/symbols/linux/bash64.json
/Users/horus/volatility3/volatility3/framework/symbols/linux/elf.json
/Users/horus/volatility3/volatility3/framework/symbols/linux/extensions
/Users/horus/volatility3/volatility3/framework/symbols/linux/extensions/__init__.py
/Users/horus/volatility3/volatility3/framework/symbols/linux/extensions/bash.py
/Users/horus/volatility3/volatility3/framework/symbols/linux/extensions/elf.py
/Users/horus/volatility3/volatility3/framework/symbols/mac
/Users/horus/volatility3/volatility3/framework/symbols/mac/__init__.py
/Users/horus/volatility3/volatility3/framework/symbols/mac/extensions
/Users/horus/volatility3/volatility3/framework/symbols/mac/extensions/__init__.py
/Users/horus/volatility3/volatility3/framework/symbols/metadata.py
/Users/horus/volatility3/volatility3/framework/symbols/native.py
/Users/horus/volatility3/volatility3/framework/symbols/windows
/Users/horus/volatility3/volatility3/framework/symbols/windows/__init__.py
/Users/horus/volatility3/volatility3/framework/symbols/windows/bigpools
/Users/horus/volatility3/volatility3/framework/symbols/windows/bigpools/bigpools-vista-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/bigpools/bigpools-vista-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/bigpools/bigpools-win10-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/bigpools/bigpools-win10-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/bigpools/bigpools-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/bigpools/bigpools-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/callbacks-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/callbacks-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/crash.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/crash64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/crash_common.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/extensions
/Users/horus/volatility3/volatility3/framework/symbols/windows/extensions/__init__.py
/Users/horus/volatility3/volatility3/framework/symbols/windows/extensions/crash.py
/Users/horus/volatility3/volatility3/framework/symbols/windows/extensions/kdbg.py
/Users/horus/volatility3/volatility3/framework/symbols/windows/extensions/mbr.py
/Users/horus/volatility3/volatility3/framework/symbols/windows/extensions/mft.py
/Users/horus/volatility3/volatility3/framework/symbols/windows/extensions/network.py
/Users/horus/volatility3/volatility3/framework/symbols/windows/extensions/pe.py
/Users/horus/volatility3/volatility3/framework/symbols/windows/extensions/pool.py
/Users/horus/volatility3/volatility3/framework/symbols/windows/extensions/registry.py
/Users/horus/volatility3/volatility3/framework/symbols/windows/extensions/services.py
/Users/horus/volatility3/volatility3/framework/symbols/windows/kdbg.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/kerb_ecrypt.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/mbr.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/mft.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-vista-sp12-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-vista-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-vista-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win10-10240-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win10-10586-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win10-14393-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win10-15063-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win10-15063-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win10-16299-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win10-17134-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win10-17134-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win10-17763-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win10-18362-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win10-18363-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win10-19041-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win10-19041-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win10-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win7-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win7-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win8-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win8-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win81-19935-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win81-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/netscan/netscan-win81-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/pdb.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/pdbconv.py
/Users/horus/volatility3/volatility3/framework/symbols/windows/pdbutil.py
/Users/horus/volatility3/volatility3/framework/symbols/windows/pe.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/poolheader-x64-win7.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/poolheader-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/poolheader-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/registry.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/services
/Users/horus/volatility3/volatility3/framework/symbols/windows/services/services-vista-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/services/services-vista-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/services/services-win10-15063-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/services/services-win10-15063-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/services/services-win10-16299-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/services/services-win10-16299-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/services/services-win8-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/services/services-win8-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/services/services-xp-2003-x64.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/services/services-xp-x86.json
/Users/horus/volatility3/volatility3/framework/symbols/windows/versions.py
/Users/horus/volatility3/volatility3/framework/symbols/wrappers.py
/Users/horus/volatility3/volatility3/plugins
/Users/horus/volatility3/volatility3/plugins/__init__.py
/Users/horus/volatility3/volatility3/plugins/linux
/Users/horus/volatility3/volatility3/plugins/linux/__init__.py
/Users/horus/volatility3/volatility3/plugins/mac
/Users/horus/volatility3/volatility3/plugins/mac/__init__.py
/Users/horus/volatility3/volatility3/plugins/windows
/Users/horus/volatility3/volatility3/plugins/windows/__init__.py
/Users/horus/volatility3/volatility3/plugins/windows/registry
/Users/horus/volatility3/volatility3/plugins/windows/registry/__init__.py
/Users/horus/volatility3/volatility3/plugins/windows/registry/certificates.py
/Users/horus/volatility3/volatility3/plugins/windows/statistics.py
/Users/horus/volatility3/volatility3/schemas
/Users/horus/volatility3/volatility3/schemas/__init__.py
/Users/horus/volatility3/volatility3/schemas/schema-0.1.0.json
/Users/horus/volatility3/volatility3/schemas/schema-2.0.0.json
/Users/horus/volatility3/volatility3/schemas/schema-2.1.0.json
/Users/horus/volatility3/volatility3/schemas/schema-4.0.0.json
/Users/horus/volatility3/volatility3/schemas/schema-4.1.0.json
/Users/horus/volatility3/volatility3/schemas/schema-6.0.0.json
/Users/horus/volatility3/volatility3/schemas/schema-6.1.0.json
/Users/horus/volatility3/volatility3/schemas/schema-6.2.0.json
/Users/horus/volatility3/volatility3/symbols
/Users/horus/volatility3/volatility3/symbols/__init__.py
/Users/horus/volatility3/volshell.py
/Users/horus/volatility3/volshell.spec
horus@Rs-MacBook-Pro ~ % ps
  PID TTY           TIME CMD
39649 ttys000    0:00.05 -zsh
horus@Rs-MacBook-Pro ~ % top
horus@Rs-MacBook-Pro ~ % 


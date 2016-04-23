# STORMS2016_XmasLights
Christmas Lights 2016

Arrowwood2016_v1_0.lcc Added new master track at end with all LOR channels in order. Derived from STORMS2016_Master.lms
Arrowwood2016_v1_1.lcc Group the LOR boxes by the Universe they will eventually be in. Added 0x0F for future possible deer.
Arrowwood2016_v1_2.lcc Moved all CTB and CMBD24's to DMX addressing. Cactus still on LOR addressing.
Arrowwood2016_v1_3.lcc Converted Cactus from Device Type LOR on 0x0C & 0x0D to DMX Universe 18. Changed bogus CCP channels from device type LOR to device type 'none selected'. Can't delete or it throws off the savedIndex numbers. Put the breakout channels at the top of the new master track.
Arrowwood2016_v1_4.lcc My 2015 config mapped to DMX. Fixed Cactus 0D s39, which was a channel on it's own floating in Cactus and SF RGB tracks. Renamed LOR Flood groups.
* Replaced any wav media links with mp3's
Arrowwood2016_v1_5.lcc Deleted Pixels, Cactus, Floods, SF RGB tracks. Redid Cactus, Floods tracks. Removed Cactus from Pixels track.
Arrowwood2016_v1_6.lcc Removed old LOR unit.channel numbers from channel names.
Arrowwood2016_v1_7.lcc Found some more unit.channel numbers to fix.
* Found that it was my 2015 lms's that were corrupted with bogus channels. Fixed it with uncorrupt.pl then loaded each one with Arrowwood2016_v1_7.lcc
Arrowwood2016_v1_8.lcc Ran reordermastertrack.pl to move the "New Master" to the front and replace the old "Master" track. Saved new config as Arrowwood2016_v1_8.lcc.
Arrowwood2016_v1_9.lcc Removed controller numbers from names of Floods.
Arrowwood2016_v2_0.lcc ADDED universes, 50 pixels each, for 24" Boscoyo Chromaflakes. (19-21,24,30,34-38,40-43,45,47,49-52,55,56,58,60-62,64). Loaded this on all old sequences.
Arrowwood2016_v2_1.lcc Floods. Moved the two LOR CMB24D controllers to their own universe 65. This way I don't have to reconfigure them for unseasonal use.
Arrowwood2016_v2_2.lcc Moved T1 megawreaths on universes 12 to universe 66. Moved T1 megawreaths on universes 13 to universe 67.
Arrowwood2016_v2_3.lcc Updated Floods track.
Arrowwood2016_v2_4.lcc Unpixel packed treeline. Before trees 1-7 used universes 1 thru 6 channel 75, trees 8-13 used universes 7 thru 11 channel 210. Now each tree gets it's own universe. Tree1 is universe 1 channels 1-375. Tree 2 is universe 2 and so on.
Arrowwood2016_v2_5.lcc Renumbered universes for MW1&2 plus several of the 24" snowflakes using renumbersf.pl. This was done so I wouldn't be skipping any universes which makes the channel numbering predictive so I cand take what I have and model it in xlights. u56->u53, u58->u54, u60->u48, u61->u46, u62->u44, u64->u39, u65->u32, u66->u22, u67->u23.
Arrowwood2016_v2_6.lcc BAD. Added Xlights import track.
Arrowwood2016_v2_7.lcc BAD. Improved the Floods track to have better groups. Also renamed 'SF-23 17" G1-6 WHT' to 'SF-23 42" G1-6 WHT'
Arrowwood2016_v2_8.lcc Removed "unit" settings from channels with type="DMX Universe" using removebogusunitids.pl
Arrowwood2016_v2_9.lcc Improved the Floods track to have better groups. Also renamed 'SF-23 17" G1-6 WHT' to 'SF-23 42" G1-6 WHT'
Arrowwood2016_v2_10.lcc Added Xlights import track.
Arrowood_2016_v2_11.lcc Renamed 'CACTUS OD s2 p39' to 'CACTUS s2 p39', Removed 'DoNotErase CCP Herpes' from XL Import track.
Arrowood_2016_v2_12.lcc Moved pixel snowflakes (what I have so far) to pixel track.
* Updated all LMS files with this configuration.
Arrowood_2016_v2_13.lcc Created PTricks track to group clusters together. Based on the XL track.

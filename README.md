# Chinese-IPTV

Chinese CCTV List (IPV6)

New features:
1. Complete TV stations list. (Thanks kunKun-tx, https://github.com/kunKun-tx/Chinese-IPTV)

If IPTV app supports remote path, such as PVR IPTV simple client in KODI, you
could use both files here, TV-EDU-HAUST.m3u and guide.xml. If your time zone is
Eastern Time Zone (UTC-5), EPG time shift is -5 because time in guide.xml is
UTC-0. Otherwise, you can change EPG time shift number according to your time
zone.

Channel list:  

https://raw.githubusercontent.com/lylehust/Chinese-IPTV/master/TV-SXYD.m3u  
Or, https://git.io/J10Fd

Or,  
https://raw.githubusercontent.com/lylehust/Chinese-IPTV/master/TV-EDU-HAUST.m3u  
Or, https://git.io/JEHPX 

Recommand http://epg.51zmt.top:8000/e.xml as the EPG file. per https://github.com/frainzy1477/Chinese-IPTV
copied Lylehurst SKYD channel list and did a global substite of lower case for the upper case in the 
tvg-name. example changing from tvg-name="CCTV1" to tvg-name="cctv1" so it will match the EPG
----------

10/21/2020: added LZU.

08/31/2021: added HAUST and remove AHAU.

09/22/2021: WebGrab+Plus doesn't work anymore, and remove the EPG file (guide.xml).

09/22/2021: Changed TV-EDU-HAUST.m3u according to http://epg.51zmt.top:8000/ . 
Recommand http://epg.51zmt.top:8000/e.xml as the EPG file.

10/22/2021: added Beijing Mobile (https://github.com/SPX372928/MyIPTV, IPV6 ?) and remove LZU.

11/17/2021: added ShanXi Mobile (https://github.com/SPX372928/MyIPTV, IPV6 ?) and remove Beijing Mobile.

Thank haust.edu.cn and lzu.edu.cn a lot. 

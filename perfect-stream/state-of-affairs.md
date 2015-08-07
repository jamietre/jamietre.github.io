---
layout: post
title: State of Affairs
---

This page is a summary of technology (hardware, software) that might be part of the perfect streaming media system. This will be roughly organized by hardware platform, then within that, things that support using that platform.

###SONOS 

I have one. It's not perfect but I still think it offers the best front-end compared to the other available options. I researched a lot of other hardware and will add info here about it as time permits.

######Pros

* Large user base, well-established product
* Integrated app exposing all supported music sources
* Direct integration with music services (pull) instead of requiring pushing to speakers from other sources

#####Cons

* Missing a few features from Spotify (My Music/Albums)
* Expensive hardware
* 65,000 file limit for your own library

#####Other

* It doesn't support spotify connect... this is neither here nor there. I like direct spotify integration rather than having to use the Spotify app whenever i want to source from Spotify. OTOH, the support is always going to be behind what is possible with the Spotify app. Would be nice to have both options.


###HELPING OUT SONOS

This section covers software/harware/configurations that can enhance the Sonos experience. I haven't tested them all, will update as I get better information.


####Subsonic

* Media Server
* Quasi-commerical ("pro" license required for SONOS integration)
* Development pace seems lackluster, though SONOS support is relatively new.
* Search feature works pretty well. Have had some trouble with updating it after big library changes; seems like it's hard to clear the cache. (Even when clicking the clear cache button).
* ID3 tag support is kind of weak for Sonos. Even though mobile apps support accessing music using tag info, the Subsonic interface only seems capable of organizing results based on the file system folder hierarchy 
Decent SONOS integration as an app, though server has limited ability to use tags. I'm using this now. Other benefits include a pretty good app ecosystem for remote access from other devices like your mobile phone. 



####[Madsonic](http://www.madsonic.org/)

* Subsonic fork
* A "6.0" version is in development
* Current state is uncertain - there have been recent updates on the product's forum, but the update has been promised for a very long time.
* SONOS support in beta only

This could be promising as a "better subsonic" but it's unclear if this major update will see the light of day, it's been in dev for a year.

####[Asset UPNP](https://www.dbpoweramp.com/asset-upnp-dlna.htm) 

* Media server
* Commercial Software

At least one person is [using it](https://forum.dbpoweramp.com/showthread.php?36379-Asset-UPNP-as-a-way-to-get-around-Sonos-65K-tracks-limit&p=158385](https://forum.dbpoweramp.com/showthread.php?36379-Asset-UPNP-as-a-way-to-get-around-Sonos-65K-tracks-limit&p=158385)
 for sonos

####[StreamWhatYouHear](http://www.streamwhatyouhear.com/forums/topic/sonos-is-supported/)

Gives you the ability to create an internet radio station from your computer's audio. This would give a pretty simple way to enable Spotify Connect, or any other audio source controllable from a PC. 

This offers no direct integration, though, you'd have to choose your "radio station" as the source in Sonos and separately control it.

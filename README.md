# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

This repo will create a video-player with playlist. powered by BrightcoveExperiences

### How do I get set up? ###

To put the video in site, just add the following code inside the body - the following element will later be replaced for the video player.:

<div id="video-attributes" class="hide"
   data-token="{{toke}}"
   data-callback="{{callback}}"
   data-playlist_id="{{player id}}"
   data-list_fields="id,name,playListType,videos,videoIds,shortDescription"
   data-video_fields="id,name,shortDescription,longDescription,linkURL,linkText,thumbnailURL"
   data-media_delivery="default"
   data-player_key="{{player key}}"
 ></div>

Make sure to include the js include in this repo.

For demo review the dir folder.

NOTE: Do not update/replace the list_fields, video_fields and media_delivery.

### Contribution guidelines ###

* Code review by PracticeUpdate team

### Who do I talk to? ###

Brad Strong
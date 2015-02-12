# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

This repo will create a video-player with playlist. powered by [Brightcove](http://support.brightcove.com/en/video-cloud/docs)

### How do I get set up? ###

To put the video in site, just add the following code inside the body - the following element will later be replaced for the video player.:


```
#!html

<div id="video-attributes" class="hide" 
    data-token="{{toke}}" 
    data-callback="{{callback}}"
    data-playlist_id="{{player id}}" 
    data-list_fields="id,name,playListType,videos,videoIds,shortDescription" 
    data-video_fields="id,name,shortDescription,longDescription,linkURL,linkText,thumbnailURL" 
    data-media_delivery="default" 
    data-player_key="{{player key}}"
	data-account="2421677169001"
	data-player="f73313ad-8e1b-4817-b39f-35b3b974ec9d">
</div>
```


Make sure to include the js include in this repo.

For demo review the dir folder.

NOTE: Do not update/replace the **list_fields**, **video_fields** and **media_delivery**.

### Other Settings ###
Please note that you can exclude the css file by doing one of the following:
* Creating a gloabal variable call PUVIDEO.
* Including a pu-video.css stylesheet file


### Contribution guidelines ###

* Code review by [PracticeUpdate](http://www.practiceupdate.com) team.

### Who do I talk to? ###

[Brad Strong](https://bitbucket.org/bradstrong)

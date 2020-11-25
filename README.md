#Embedding HD YouTube Videos with High Quality Thumbnails#

This jQuery plugin ensures that you will get the highest quality thumbnails for your HD YouTube videos, regardless of the embedding sizes or the original thumbnail quality settings of the YouTube videos.

##Examples##

Please visit [this webpage](https://simonlidesign.github.io/YouTubeHDThumbnail/) for examples of using this plugin.

##Usage##

Include the CSS stylesheet within the head tag.
```
<link rel="stylesheet" href="css/YouTube.HD.Thumbnail.css"> 
```

Then include the JavaScript file before the closing body tag.
```
<script src="js/jQuery.YouTube.HD.Thumbnail.js"></script>
```
Copy the code for embedding from your YouTube video and add a class name like **yt-hd-thumbnail**.
```
<iframe class="yt-hd-thumbnail" width="560" height="315" src="https://www.youtube.com/embed/5aOSxep4ni0?rel=0&amp;controls=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>
```
Activate the plugin by adding the following code to your JavaScript file.
```
$('iframe.yt-hd-thumbnail').youTubeHDThumbnail({
	darkenThumbnail: false
});
```

##Options##

The following options are provided in this jQuery plugin.
* **darkenThumbnail**: true / false
  Specifies whether to darken the thumbnail

##About##

MIT License

Created by [Simon Li](http://www.simon-li.com) in Sep 2016

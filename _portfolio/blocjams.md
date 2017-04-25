---
layout: post
title: BlocJams
feature-img: "img/sample_feature_img.png"
thumbnail-path: "https://d13yacurqjgara.cloudfront.net/users/3217/screenshots/2030966/blocjams_1x.png"
short-description: BlocJams is an awesome music player!

---
Bloc students, to practice Javascript and JQuery, and to introduce AngularJS, build a simple Spotify-style music library with the Buzz engine, consisting of a landing page, album list, and album song list with a functional music player, which plays, pauses and skips tracks, tracking play progress with a working seek bar.

{:.center}
![]({{ site.baseurl }}/img/bloc_jams_index.jpg)

For lack of song and album work, we loaded 12 iterations of the same album in the Collection page, but a richer body of album templates would load if more were added to the catalog data.

{:.center}
![]({{ site.baseurl }}/img/bloc jams collection.jpg)

With album and song data retrieved, we attach event handlers to each song row in the album song list, so play buttons appear on hover, and toggle between play/pause when clicked. When a song plays, the player bar updates with the song's name, artist, album, total time and time elapsed. The player bar also allows you to seek by dragging the seek thumb to your desired time, just as the volume slider allows you to set the current volume.

{:.center}
![]({{ site.baseurl }}/img/bloc jams album.jpg)

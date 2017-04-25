---
layout: post
title: BlocChat
feature-img: "img/sample_feature_img.png"
thumbnail-path: "https://d13yacurqjgara.cloudfront.net/users/3217/screenshots/2030974/bloctalk_1x.png"
short-description: BlocChat is a simple chatroom app!

---

Bloc students, to practice JQuery, Angular, Firebase, and Bootstrap, build a single-page chatroom app that allows users to register, visit existing chatrooms, create new chatrooms, and post in them.

{:.center}
![]({{ site.baseurl }}/img/bloc_chat_full_site.jpg)

For starters, we needed a Firebase database to store our rooms. From that, we fetch an array of room names and display them as links in our sidebar. To add rooms to the rooms database, we add a button next to the "Bloc Chat" title, which opens a modal dialog box (thanks, Bootstrap!), which triggers a function uploading our text to the rooms database.

{:.center}
![]({{ site.baseurl }}/img/bloc_chat_new_room_modal.jpg)

With our rooms set up, we needed to populate them with messages. Heading back to Firebase, we set up our messages database table, each child of which holds four object items: room ID, time, username, and message content. Now, each message submission notes the current room, time, and message content.

{:.center}
![]({{ site.baseurl }}/img/bloc_chat_new_user_modal.jpg)

For this to be a proper chatroom app, we needed messages to be associated with usernames, so when the site loads, a modal appears to let the user choose their own username.

Now users can revisit the app for their messaging needs.

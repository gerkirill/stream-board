# YouTube live stream board

The idea is to have a full-screen web page which plays a youtube stream e.g. with 3D printer printing some detail. Some JS should handle the cases when the stream is paused (e.g. play some pre-recorded youtube video about 3D printing) and optionally display some dynamic info afout the stream (e.g. "Live" mark and a number of conference the printer works in) on top of the video (maybe at the bottom or in the corner).

It is now possible to stream webcam with just a browser, right from youtube admin panel. Just need to remember to turn mic off. I am going to use conference room laptop + external USB webcam for streaming, and raspberry pi with chrome browser running in full-screen mode to display the stream on a big screen.

There should be a way to tell stream board which video to stream. If possible - we may have some pre-defined playlist for that. Otherwise some kind of admin-panel is required. In this case it is easier to run live stream board somewhere on the publicly accessible internet hosting.

Few links:

 - [Start live translation](https://www.youtube.com/webcam?o=U&ar=2)
 - [
YouTube Player API Reference for iframe Embeds](https://developers.google.com/youtube/iframe_api_reference#Loading_a_Video_Player)
- [Video player params](https://developers.google.com/youtube/player_parameters?playerVersion=HTML5)
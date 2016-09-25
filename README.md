# auto_x265

Scripts and Programs to auto transcode video files to x265 mkv files. x264 is 13 years old time to move on.

Windows cmd (batch) files and programs need to auto transcode . Maybe at some point a gui for setup but for now have to edit
setting by hand.To greatily improve transcoding time set up server farm ,use either something as simple as handful of raspberry
pi or whatever old computers you have in closet. as long as you shut off some of them when not transcoding massives folders full
off videos.
Running 6 raspberry pi plus 1 windows 10 pc I can transcode @ a rate of 10 minutes per hour of video.

Defualt setting are be 720p @ 744k with 256k Ac3 5.1 audio if available otherwise 2.o stereo. should ended up with files around 
4 megs per minute of video

NOTES:
x265 @ 700k is fine for most poeple beside at this time most shows and movies arent even filmed at that high of bandwidth. 
feel free to up the bitrate settingsbut Iam designing for space savings not to see every pore in actors nose. You can pick
 up a android tv box like the mxpro for under $50 or Ruko 4 will play without further transcoding taking alot of cpu strain 
off your media server.


Alliance for Open Media is working on open source roalty free replace for x264/x265 .AOMedia codec is due out by end of 2017. 
so you may want to wait til it finalize and hardware out to support it. My person problem with that is Google plus hole host of
corperation are main players . Anytime that many corperation it never ends well for small coders/end users

Dependancy (included) :
 handbrake_cli
 or
 ffmpeg windows build

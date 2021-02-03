<p align="center">
  <img src="https://github.com/lrorpilla/jidoujisho/blob/main/assets/icon/icon.png" alt="jidoujisho logo by aaron marbella" width="120" height="120">
</p>


<h3 align="center">jidoujisho</h3>
<p align="center">A mobile video player tailored for Japanese language learners.</p>

<p align="center"><b>Latest Beta: <a href="">0.3.0</a></b>

<br>
<h1>Uninterrupted language immersion at your fingertips</h1>

<b>jidoujisho</b> is an Android video player with features specifically helpful for language learners. 

- [x] Text selection of subtitles allows for <b>quick dictionary lookups within the application</b>
- [x] <b>Search current clipboard and open browser</b> to Jisho.org, DeepL or Google Translate
- [x] <b>Export cards to AnkiDroid</b>, complete with a snapshot and audio of the current context
- [x] Selecting a word allows export to AnkiDroid with the <b>sentence, answer, meaning and reading</b>
- [x] <b>Repeat the current subtitle from the beginning</b> by flicking horizontally
- [x] Swipe vertically to open the <b>transcript to jump to time and review subtitles</b>
- [x] <b>(Experimental)</b> YouTube support for videos with Japanese user-generated subtitles

<h1>More features are on the way</h1>

<b>jidoujisho is still in active development.</b> The app will be available publicly to download in GitHub at an early stage, and will be free to download on the Google Play Store. Current features on planned on the roadmap listed below, but as of now there is no estimate on any updates.

- [ ] <b>Further web support</b> and fixes for experimental YouTube and auto-generated subtitles
- [ ] <b>Use of the AnkiDroid API</b> instead of share intent to streamline card export
- [ ] <b>User interface, layout, video playback preferences</b> and Anki output customisation
- [ ] Multiple subtitle tracks at a given time, and <b>immersion difficulty levels</b> for oral practice
- [ ] <b>Morphological analysis of subtitles</b> for better text selection and <b>offline dictionary use</b>
- [ ] <b>Support for more languages,</b> and more easier ways for contributors to extend language support
- [ ] Tinker around with releasing the app on <b>other platforms if possible</b>

<h1>A glimpse of jidoujisho in action</h1>

<p align="center">
  <a href="https://postimg.cc/kBmF6dFY" target="_blank"><img src="https://i.postimg.cc/QxB6z8BD/Screenshot-20210201-071958.jpg" width="250"/></a>
  <a href="https://postimg.cc/Z0VsSnhF" target="_blank"><img src="https://i.postimg.cc/zX1sTHtM/Screenshot-20210204-065320.jpg" width="250"/></a>
  <a href="https://postimg.cc/14NJVBxX" target="_blank"><img src="https://i.postimg.cc/kMTZZYfQ/Screenshot-20210201-072859.jpg" width="250"/></a>
</p>
<p align="center">
  <a href="https://postimg.cc/s1Yy9p7f" target="_blank"><img src="https://i.postimg.cc/T2Swx0Pb/Screenshot-20210204-081519.jpg" height="400"/></a>
  <a href="https://postimg.cc/fVrhT5nC" target="_blank"><img src="https://i.postimg.cc/PqtfyFSg/Screenshot-20210204-081552.jpg" height="400"/></a>
  <a href="https://postimg.cc/sBq5VFgc" target="_blank"><img src="https://i.postimg.cc/DZy6PnVt/Screenshot-20210204-065707.jpg" height="400"/></a>
  <a href="https://postimg.cc/WDhMLpTz" target="_blank"><img src="https://i.postimg.cc/d09nCDf2/Screenshot-20210204-065728.jpg" height="400"/></a>
</p>
<p align="center">
  <a href="https://postimg.cc/T5XmDrm5" target="_blank"><img src="https://i.postimg.cc/Y0vxTRCR/Screenshot-20210204-070159.jpg" width="250"/></a>
  <a href="https://postimg.cc/JHcXcGc6" target="_blank"><img src="https://i.postimg.cc/Y0Tx7F4H/Screenshot-20210204-070337.jpg" width="250"/></a>
  <a href="https://postimg.cc/7fn1SQKH" target="_blank"><img src="https://i.postimg.cc/8PqyQ2W6/Screenshot-20210201-232317.jpg" width="250"/></a>
</p>

<h1>Using the application</h1>

<h3>Supported Formats</h2>
jidoujisho will take <b>video and audio formats as supported by ExoPlayer</b>. Subtitles may be embedded within the video being played and selected during playback. 

If you wish to use external subtitles, they may be in <b>.SRT format</b> and <b>must be named with the same basename as the video file</b> (i.e. to play external subtitles for "CLANNAD S01E01.mkv" you must name the subtitle "CLANNAD S01E01.srt". You may switch between different audio and subtitle tracks. Image-based subtitles such as PGS are not currently supported.

Web support for YouTube is <b>currently experimental</b>. YouTube subtitles are taken from TimedText XML, which is only publicly exposed to videos that have user-generated Japanese subtitles. Unfortunately, some particular videos cannot be streamed. Regardless, the app appears to be functional and has been tested with a fair sample of practical application use cases.

<h2>Getting Started</h2>

A primer on the basics of the application is as follows.

* Play a video by selecting from your <b>local media library or entering a YouTube URL</b>
* Select text by simply holding on them, and <b>copy them to clipboard when prompted</b>
* When the <b>dictionary definition</b> for the text shows up, the text is the <b>current context</b>
* Closing the dictionary prompt will <b>clear the clipboard</b>
* The current context may be used to <b>open browser links to third-party websites</b>
* You may <b>swipe vertically to open the transcript</b>, and you can pick a time or read subtitles from there
* <b>Swipe horizontally</b> to repeat the current subtitle audio

<h2>Exporting to AnkiDroid</h2>

* You may also export the current context to an <b>AnkiDroid card, including the current frame and audio</b>
* Having a word in the clipboard <b>will include the sentence, word, meaning and reading</b> in the export
* <b>You may edit the sentence, word, meaning and reading text fields</b> before sharing to AnkiDroid
* To finalise the export, <b>share the exported text to AnkiDroid</b>
* The <b>front of the card</b> will include the <b>audio, video and sentence</b>
* The <b>back of the card</b> will include the <b>reading, word and meaning</b>
* You may apply changes to the card such as bolding and other text formatting with the AnkiDroid editor once shared
* Extensive customisation of the Anki export is planned

<h1>Contribution and attribution</h1>

jidoujisho is written in <b>Dart</b> and powered by <b>Flutter</b>. At present, the project may still need to be refactored and cleaned up as well as setting up of forks for the modified imports used in the project. Regardless, the app is ready for use and feedback in these early stages is much appreciated.

If you like what I've done so far, you can help me out by testing the application on various so that I can gauge the compatibility of the application with different versions of Android, <a href="https://www.buymeacoffee.com/lrorpilla">making a donation</a> or collaborating with me on further improvements.

The logo of the application is by <b>Aaron Marbella</b>.

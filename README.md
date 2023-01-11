# Jsong
<center> <img width="500" height="200" src="https://cdn-s3.allmusic.com/cms/2202/newallmusic_blog.png" alt="allMusicBanner"> </center>
<b> Converts data from AllMusic.com into usable json-format files </b>


> jsong streamlines the process of copying data into json files

- For discographies: Pick a link of your choice (e.g., https://www.allmusic.com/artist/taylor-swift-mn0000472102/discography, https://www.allmusic.com/artist/elton-john-mn0000796734/discography, etc.) and pass the url to the function "getDiscography(URL_HERE)"

- For albums: Pick a link of your choice (https://www.allmusic.com/album/innervisions-mw0000192406, https://www.allmusic.com/album/a-night-at-the-opera-mw0000391519, etc.) and pass the url to the function "getAlbum(URL_HERE)"
          
Samples:      
<div float="left">
  <img width="200" height="200" src="https://user-images.githubusercontent.com/119715495/211178432-2881137d-d7fd-48b4-bc29-c269fce518d7.png">

      
  <img width="200" height="200" src="https://user-images.githubusercontent.com/119715495/211178248-2b4c0b50-5b01-452c-b1c1-d6ffbf459272.png">
</div>

*Data is collected in part with the use of a Selenium webdriver; web pages will be periodically opened and closed in order to webscrape information. Please do not close these pages -- they will be automatically closed when the function has been executed. Thank you :)*

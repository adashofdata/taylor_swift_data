# Taylor Swift Data

This repo contains the data that I collected to do the analysis for this blog post: http://adashofdata.com/2023/03/01/a-data-scientist-breaks-down-all-10-taylor-swift-albums-the-extended-version/

You can also see the video summary of my analysis on YouTube: https://youtu.be/ZNFms8sUbTw

For fun, you can also check out a few of the Reddit threads [here](https://www.reddit.com/r/TaylorSwift/comments/11g46c5/all_the_colors_mentioned_in_each_taylor_swift/), [here](https://www.reddit.com/r/TaylorSwift/comments/11f6xa8/taylor_swift_writes_a_song_in_every_key_on/) and [here](https://www.reddit.com/r/TaylorSwift/comments/11mv3sn/taylor_says_she_imagines_writing_her_songs_with_3/).

The data sets contain details about her songs from her first 10 studio albums (up through Midnights). I gathered the data through the Genius API (lyrics) and Spotify API (song metadata).

## For the non-technical people

This main folder contains:

* [*Taylor_Swift_Genius_Data.xlsx*](Taylor_Swift_Genius_Data.xlsx): Spreadsheet with lyrics data
* [*Taylor_Swift_Set_List_Data.xlsx*](Taylor_Swift_Set_List_Data.xlsx): Spreadsheet with set lists from her six tours discussed on this [Reddit thread](https://www.reddit.com/r/TaylorSwift/comments/11zl2wr/set_lists_from_all_of_taylors_tours_including_the/)
* [*Taylor_Swift_Spotify_Data.xlsx*](Taylor_Swift_Spotify_Data.xlsx): Spreadsheet with song metadata
* [*Taylor_Swift_Words_Data.xlsx*](Taylor_Swift_Words_Data.xlsx): Spreadhseet with lyrics data broken down into words

To access the data, you can click on any *Taylor_Swift_Type_Data.xlsx* spreadsheet and then click the **Download** button at the top right.

## For the technical people

The **Taylor_Swift_Genius** folder contains:

* Python code to extract the lyrics of Taylor Swift's songs from the Genius API
* .csv file of the lyrics of Taylor Swift's songs
* 10 folders containing the song lyrics for each album as .txt files

The **Taylor_Swift_Spotify** folder contains:

* Python code to extract the metadata of Taylor Swift's songs from the Spotify API
* .csv file of the metadata of Taylor Swift's songs (danceability, key, etc.)

The **Taylor_Swift_Words** folder contains:

* Python code to break down her lyrics into words
* .csv file of the words in Taylor Swift's songs

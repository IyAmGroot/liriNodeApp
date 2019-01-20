# liriNodeApp
This is the LIRI app.  LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

Goal
Call functions with parameters from the command line and generate output in GitBash.  The Bonus assignment was also implemented, so results will also be logged to a file, "log.txt".  

Technical Details
This application utilizes the following APIs:

* Bands In Town
* Spotify
* OMDB

This application also uses the following Node packages:
* Axios
* Node-Spotify-API
* Moment
* DotEnv

## The Commands ##
concert-this 
* Arguments
  * Band/Performer
* Output
  * Venue
  * Venue Location
  * Date (Formatted MM/DD/YYYY)
  
 movie-this
 * Arguments
   * Move Name (defaults to "Mr. Nobody" if no movie name is entered)
 * Output
   * Title of the movie.
   * Year the movie came out.
   * IMDB Rating of the movie.
   * Rotten Tomatoes Rating of the movie.
   * Country where the movie was produced.
   * Language of the movie.
   * Plot of the movie.
   * Actors in the movie.
spotify-this-song
* Arguments
  * Song (defaults to "The Sign" if no song is entered)
* Output
  * Artist(s)
  * The song's name
  * A preview link of the song from Spotify
  * The album that the song is from
 do-what-it-says
  * Reads from the file, random.txt.  This file contains the command "spotify-this-song" and the song name, "I Want it That Way".    Yuck. The code will process the command and song name and process it as if it was called from the command line.

  
  
## Outputs ##
  Search results are printed to the gitbash window and written to the log.txt file.
  
## Video ##
  A video demonstration of the app can be found by clicking the link below.

 [Click HERE for video](https://drive.google.com/file/d/1lowGlbmKkR516bPMA_cQgwWQttsYZXeQ/view).


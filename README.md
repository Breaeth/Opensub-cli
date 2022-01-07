# Opensub-cli
A cli tools for auto download opensubtitles.org subtitles ! 

### How it work 

For the series : 
  The script check if there is a season and an episode like : SXXEXX with X a number
  exemple : S01E01 , S04E10, S12E56 etc ...
For the movie : 
  If the script do not detect if it's a serie, i will take everything before the resolution, and that will be the title : 
  exemple : Nobody.2021.1080p.things.and.other.stuff ; the script will just keep Nobody 2021 as title.
  The resolution can be : 480p, 720p, 1080p etc... I need to add HDRip by the way héhé ....
  
 In short : 
   Your video name must be like :
   Things-and-stuff-SXXEXX-things-and-stuff.stuff
   OR 
   Things-and-stuff-RESOLUTION-things-and-stuff.stuff
 
 
### TODO 

[X] Making a full cli tool for auto download subtitles wich work great 
[ ] Add security for cd $output 
[ ] Add "HDRip" for detect movie
[ ] Simplify all my pipes and simplify the code in general  

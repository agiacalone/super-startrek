###### README FOR SST BY TOM ALMY ######

The Classic Super Star Trek Game

Super Star Trek is quite possibly the best of the "Star Trek" games from the 1970's. Of course, it does not make use of graphics, or even assume a video display, but it still an interesting game to play, particularly for those of us who don't have the reflexes we used to and prefer a more cerebral computer game.

Of course, Star Trek and it's characters are trademarks of Paramount Studios, Inc. And just like the original game, written by Star Trek fans who were also the, back then, rare breed of computer geek, isn't used with permission but with admiration of the show.

This game was written by David Matuszek and Paul Reynolds, with modifications by Don Smith. I've received further information that the black holes, Tholian web, Super Commander, and Emeritus mode were added by Marc Newman. I resurrected the game, rewrote it in C, and fixed many bugs.

In June 2002, I fixed two known bugs and a documentation typo, and created a new Linux version. In June 2004 I fixed a number of bugs involving: 1) parsing invalid numbers, 2) manual phasers when SR scan is damaged and commander is present, 3) time warping into the future, 4) hang when moving klingons in crowded quadrants.

In December 2010, I fixed bugs involving attempting to fire more than 3 torpedoes at once, a typo ("READ ALERT"), and a couple of buffer overflow issues.

In October 2013 I fixed a bug that caused the number of remaining Klingons to be negative when the remaining Klingons and the Enterprise are destroyed in a Super Nova. Typos pointed out by users have been corrected. I added the ability to get the current score (why was that never possible?), and have an optional fix that rotates the scan displays so that the X axis is horizontal. Yes, for some reason the authors of SST had the displays rotated 90 degrees clockwise. Just add -f as the first command line argument. Fixed instance where total casualties would decrease when casualties occur.

In December 2013 I added three new commands -- CLOAK to cloak the Enterprise, CAPTURE to allow Klingons to surrender, and SCORE to show the score in the game. I also fixed many typos in the program dialog and in the documentation.

In June 2015 I fixed some bugs that kept certain counts from being reset when starting a new game.

###### END  ######

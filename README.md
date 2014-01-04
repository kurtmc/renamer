renamer
=======

Linux terminal based file renaming. Optimised for renaming series.

Install:
> make install

Use:
> cd ~/path_to_series_of_choice/Family\ Guy <br>
> ls <br>
Season 2 <br>
> ls Season\ 2 <br>
family.guy.x264.HDTV201.mp4   family.guy.x264.HDTVs2E02.mp4 <br>
family.guy.x264.HDTV2x03.mp4 <br>
> renamer "Family Guy" <br>
./Season 2/family.guy.x264.HDTV201.mp4 ==> Family Guy S02E01.mp4 <br>
./Season 2/family.guy.x264.HDTVs2E02.mp4 ==> Family Guy S02E02.mp4 <br>
./Season 2/family.guy.x264.HDTV2x03.mp4 ==> Family Guy S02E03.mp4 <br>
Is this correct and would you like to rename those files? <br>
> y <br>
./Season 2/family.guy.x264.HDTV201.mp4 <br>
./Season 2/family.guy.x264.HDTVs2E02.mp4 <br>
./Season 2/family.guy.x264.HDTV2x03.mp4 <br>
> ls Season\ 2 <br>
Family Guy S02E01.mp4  Family Guy S02E02.mp4  Family Guy S02E03.mp4 <br>

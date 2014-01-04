renamer
=======

Linux terminal based file renaming. Optimised for renaming series.

Install:
> make install

Use:
> cd ~/path_to_series_of_choice/Family\ Guy
> ls
Season 2
> ls Season\ 2
family.guy.x264.HDTV201.mp4   family.guy.x264.HDTVs2E02.mp4
family.guy.x264.HDTV2x03.mp4
> renamer "Family Guy"
./Season 2/family.guy.x264.HDTV201.mp4 ==> Family Guy S02E01.mp4
./Season 2/family.guy.x264.HDTVs2E02.mp4 ==> Family Guy S02E02.mp4
./Season 2/family.guy.x264.HDTV2x03.mp4 ==> Family Guy S02E03.mp4
Is this correct and would you like to rename those files?
> y
./Season 2/family.guy.x264.HDTV201.mp4
./Season 2/family.guy.x264.HDTVs2E02.mp4
./Season 2/family.guy.x264.HDTV2x03.mp4
> ls Season\ 2
Family Guy S02E01.mp4  Family Guy S02E02.mp4  Family Guy S02E03.mp4

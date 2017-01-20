Naming convention for folders.
<br>EP, nickname for example programs.
<br>WK, nickname for worth keeping.


Information Regarding this repository:
<pre>
Michaels-MacBook-Pro-3:Environment_alias zen1$ git clone https://github.com/MichaelDimmitt/studying_for_elixirDaze_Programming_Books.git
Cloning into 'studying_for_elixirDaze_Programming_Books'...
remote: Counting objects: 779, done.
remote: Compressing objects: 100% (400/400), done.
remote: Total 779 (delta 289), reused 779 (delta 289), pack-reused 0
Receiving objects: 100% (779/779), 8.03 MiB | 2.29 MiB/s, done.
Resolving deltas: 100% (289/289), done.
Checking connectivity... done.
Michaels-MacBook-Pro-3:Environment_alias zen1$ cd studying_for_elixirDaze_Programming_Books/
Michaels-MacBook-Pro-3:studying_for_elixirDaze_Programming_Books zen1$ for d in ./*/ ; do (cd "$d" && echo "$d" && cloc --vcs git); done
./EP_00_little_elixir_otp_guidebook/
     141 text files.
     108 unique files.                                          
      61 files ignored.

github.com/AlDanial/cloc v 1.68  T=0.07 s (1323.0 files/s, 51772.1 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Elixir                          80            569            237           2149
Markdown                         9            176              0            385
Erlang                           1              2              0              4
-------------------------------------------------------------------------------
SUM:                            90            747            237           2538
-------------------------------------------------------------------------------
Saving session...
...saving history...truncating history files...
...completed.
./EP_01_WK_Elixir_in_action/
     412 text files.
     166 unique files.                                          
     260 files ignored.

github.com/AlDanial/cloc v 1.68  T=0.13 s (1144.3 files/s, 40168.5 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Elixir                         151           1072            153           4154
Lua                              1              1              0             14
Markdown                         2              4              0              8
-------------------------------------------------------------------------------
SUM:                           154           1077            153           4176
-------------------------------------------------------------------------------
Saving session...
...saving history...truncating history files...
...completed.
./EP_02_programming_elixir/
     265 text files.
     220 unique files.                                          
      63 files ignored.

github.com/AlDanial/cloc v 1.68  T=0.10 s (2022.2 files/s, 56247.2 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Elixir                         203            740           1846           3085
Ruby                             1              1              9             15
Markdown                         1              2              0              4
-------------------------------------------------------------------------------
SUM:                           205            743           1855           3104
-------------------------------------------------------------------------------
Saving session...
...saving history...truncating history files...
...completed.
./WK_00_little_elixir_otp_guidebook_examplePrograms/
       1 text file.
       1 unique file.                              
       0 files ignored.

github.com/AlDanial/cloc v 1.68  T=0.01 s (80.5 files/s, 2174.8 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Markdown                         1             10              0             17
-------------------------------------------------------------------------------
Saving session...
...saving history...truncating history files...
...completed.
./WK_01_Elixir_in_action_examplePrograms/
       1 text file.
       1 unique file.                              
       0 files ignored.

github.com/AlDanial/cloc v 1.68  T=0.01 s (84.0 files/s, 588.1 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Markdown                         1              2              0              5
-------------------------------------------------------------------------------
Saving session...
...saving history...truncating history files...
...completed.
./WK_02_programming_elixir/
       1 text file.
       1 unique file.                              
       1 file ignored.

github.com/AlDanial/cloc v 1.68  T=0.01 s (75.0 files/s, 375.1 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Markdown                         1              1              0              4
-------------------------------------------------------------------------------
Saving session...
...saving history...truncating history files...
...completed.
</pre>

# Introduction of Feature engineer 1
(Enter your text from line 3 onwards



# Introduction of Feature engineer 2 
(Enter your text from line 9 onwards)
i added thi is person 2 



# General content
(All the teammates are requested to enter your text strictly in line 15 only
<old|new>-file
are files GIT_EXTERNAL_DIFF can use to read the contents of <old|new>,

<old|new>-hex
are the 40-hexdigit SHA-1 hashes,

<old|new>-mode
are the octal representation of the file modes.

The file parameters can point at the user’s working file (e.g. new-file in "git-diff-files"), /dev/null (e.g. old-file when a new file is added), or a temporary file (e.g. old-file in the index). GIT_EXTERNAL_DIFF should not worry about unlinking the temporary file — it is removed when GIT_EXTERNAL_DIFF exits.

For a path that is unmerged, GIT_EXTERNAL_DIFF is called with 1 parameter, <path>.

For each path GIT_EXTERNAL_DIFF is called, two environment variables, GIT_DIFF_PATH_COUNTER and GIT_DIFF_PATH_TOTAL are set.




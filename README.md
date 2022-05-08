# logrotate.sh
logrotate.sh example

This is assignment which will roate files:

e.g.
```
❯ ll
total 16
-rw-r--r--  1 amit  staff     0B May  8 20:07 README
-rw-r--r--  1 amit  staff     0B May  8 20:07 access.log
-rw-r--r--  1 amit  staff     0B May  8 20:07 error.log
-rw-r--r--  1 amit  staff     0B May  8 20:07 error.log.1
-rw-r--r--  1 amit  staff     0B May  8 20:07 error.log.2
-rwxr-xr-x  1 amit  staff   607B May  8 20:01 solution.sh
drwxr-xr-x  3 amit  staff    96B May  8 18:59 some-directory
-rw-r--r--  1 amit  staff   257B May  8 18:56 test-input-01.txt
❯ sh solution.sh
READ file
access
error
❯ ll
total 16
-rw-r--r--  1 amit  staff     0B May  8 20:07 README
-rw-r--r--  1 amit  staff     0B May  8 20:07 access.log
-rw-r--r--  1 amit  staff     0B May  8 20:07 access.log.1
-rw-r--r--  1 amit  staff     0B May  8 20:07 error.log
-rw-r--r--  1 amit  staff     0B May  8 20:07 error.log.1
-rw-r--r--  1 amit  staff     0B May  8 20:07 error.log.2
-rw-r--r--  1 amit  staff     0B May  8 20:07 error.log.3
-rwxr-xr-x  1 amit  staff   607B May  8 20:01 solution.sh
drwxr-xr-x  3 amit  staff    96B May  8 18:59 some-directory
-rw-r--r--  1 amit  staff   257B May  8 18:56 test-input-01.txt
```

# Source project for building the flss site 

## Build instructions

Install bundler and jekyll on your system and execute:

```/bin/bash
bundler exec jekyll build
```

Everything will be built in the _site directory.


## Deploy instructions

It sufficies to copy in the right places (/srv/http/ijcnn-flss-2023 on kdd) the contents of the _site directory.

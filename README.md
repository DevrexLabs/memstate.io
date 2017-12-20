# memstate.io
This is the jekyll based source of https://memstate.io/

Jekyll: https://jekyllrb.com/


Memstate docs are pulled in from the /docs subfolder of the memstate repository. Each memstate release copy memstate/docs to a subfolder under memstate.io/docs including the version number, ie docs/core-1.0-alpha

## developing

* edit markdown files
* ```jekyll serve```
* http://localhost:4000


## building / publishing

```jekyll build``` - this will build the static site, result goes to _site folder
```firebase serve``` - runs locally on http://127.0.0.1:5000/, validate all is good
```firebase deploy``` - pushes to firebase hosting.
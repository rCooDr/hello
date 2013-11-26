hello
=====

This is about go.
It is also about the google app engine
After installing the app engine in one place, 
now, look at it in a little more detail.

Google App Engine Tutorial
==========================

start here: with the [tutorial about go within the App Engine][1]

Then, look deeper into the App..
================================
Go here: some [app engine source...][2]

## Looking about the Cloudy Components
There is the [goapp][3] `go development server`

    cd ~/project/myapp
    goapp serve
  
or/and

    dev_appserver.py --port=9999 myapp

Putting it in the Clouds
========================

Continue reading: about [goapp deploy][4]

    goapp deplay
    
and/or

    appcfg.py update myapp/
    appcfg.py request_logs myapp/ mylogs.txt
    
And oogle over the Subversion Tree
==================================

to find: the [appcfg.py][5] source code


[1]:(https://developers.google.com/appengine/docs/go/gettingstarted)
[2]:(https://code.google.com/p/googleappengine/)
[3]:(https://developers.google.com/appengine/docs/go/tools/devserver)
[4]:(https://developers.google.com/appengine/docs/go/tools/uploadinganapp)
[5]:(https://code.google.com/p/googleappengine/source/browse/branches/1.2.1/python/google/appengine/tools/appcfg.py)

# Org-mode and reproducible research

The presentation in this Repo was given by Evan Misshula to the
Emacsnyc meetup on November 3, 2014.  To view it, as it appears in the 
video,, you must install and configure reveal.js.  A working copy of the library is 
included in this repo.  However, reveal.js produces html files.  These need to be 
served to a browser to be viewed in their presentation form.

# Web server

A webserver makes files available to browsers requesting them using
protocls and ports.  The default protocol of the internet is Hyper
Text protocol (http).  Fortunately many free software languages have
small webservers built into them.  My suggestion is to use
`python`. You can download a free version of python from
<http://python.org> Choose version 2.7.x. Open a terminal and 
navigate to this directory.

python -m SimpleHTTPServer 8000

This serves all the files in the directory on port 8000.  Go to the
address bar of your browser and type:

localhost:8000

You will see the file `rr.html`. Click on it and begin the presentation.
# ixiftest

This repo is connected to an Azure Web Site.
I made it to be able to test Universal Viewers ability to render mp4 videos.

The manifest can be used like this
http://universalviewer.io/examples/?manifest=http%3A%2F%2Fixiftest.azurewebsites.net%2Fvideomanifest.json&locale=en-GB#?c=0&m=0&s=0&cv=0

I had to configure the Azure web site in order to serve static json and mp4 files and to return reponse header in order for CORS to work.

# 500px-slideshow
500px is great, but lacks an option to have pictures update automatically. This little script can be installed as a bookmarkelt and scoll through pictures automatically.

First, let me explicitly state that I don't know if this infringes 500px's terms of service, and it's your responsibility to check before using this one-line script.

1. In your browser, right-click on the bookmark bar, select "Add a Page..."
2. Call it e.g. "500px slideshow"
3. Paste this code:
javascript:(function(){var interval=window.prompt("What interval would you like (in seconds)? (refresh the page to stop the slideshow)","7"); setInterval(function(){jQuery(".photo-focus__nav--right").first().trigger("click");}, interval*1000);})()
4. Navigate to the desired 500px collection, click on an image
5. Click on the bookmarket
6. Go full screen
7. Enjoy.

Stop the slide show by closing your browser tab, or reloading the page.

# Bookmark Bubble
## Overview
**bookmark_bubble** is a simple jQuery plugin that adds a "Save to Homescreen" prompt to some popular mobile browsers. Based upon Mobile Bookmark Bubble by Google Inc., original copyrights and license below.

## Basic Usage
This plugin is straight-forward to use. Simply include a copy of the script on your page:

    <script type="text/javascript" src="/path/to/bookmark_bubble-min.js"></script>

Then call it when ready, like so:

	// Show the bookmark bubble 1 second after all the DOM content has loaded
	document.addEventListener('DOMContentLoaded', function () {
	    window.setTimeout(function() {
            var bubble = new google.bookmarkbubble.Bubble();
            bubble.showIfAllowed();
        }, 1000);
    });

## Releases
  
1.1.6 : Add Android full-screen check - by triq6  
1.1.5 : Add class names to bookmark-bubble elements - by rjclardy  
1.1.4 : Android support enhancements - by okamototk    
1.1.3 : iOS7 support. - by wiifm  
1.1.2 : Android 4.0 Tablet / Mobile both support.  
1.1.1 : Android 4.0 support.  
1.0.1 : First public release of fork by okamototk.  

---
  Copyright 2010 Google Inc.

  Licensed under the Apache License, Version 2.0 (the "License");
  you may not use this file except in compliance with the License.
  You may obtain a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)  
  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License.
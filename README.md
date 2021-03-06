# PS Polymer

Wrapping the PhotoShelter.com API (http://www.photoshelter.com/developer/) with Polymer.js (http://www.polymer-project.org) to surface many photographer data points via web components.

Globals can be set with:
* ps-globals
  * Currently this only manages the PS.com API key for service requests. You can sign up for a key at: http://www.photoshelter.com/developer/index/register/api_key

Using the key set in ps-globals, data for users, image, and galleries are available with:
* ps-user-service
* ps-image-service
* ps-gallery-service
* ps-root-service
* ps-tumblr-service
* ps-content-service

User and image information can be used to create the following stand alone elements:
* ps-image
* ps-image-buy
* ps-image-iptc
* ps-share

These elements are used to create:
* ps-image-card

Gallery information is used to create:
* ps-thumbs
* ps-slideshow

And these elements join the image elements to form:
* ps-gallery

Collection information is used to create:
* ps-collection

## Polymer.js

core-ajax, core-component-page, platform, polymer-test-tools, and polymer are currently included as v0.5.2. While I'll try to keep them up-to-date as best I can, please visit www.polymer-project.org for the latest.

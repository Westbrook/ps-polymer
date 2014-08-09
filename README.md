*PS Polymer*

Wrapping the PhotoShelter.com API (http://www.photoshelter.com/developer/) with Polymer.js (http://www.polymer-project.org) to surface many photographer data points via web components.

Data for users, image, and galleries are available with:
* ps-user-service
* ps-image-service
* ps-gallery-service

User and image information can be used to create the following stand alone elements:
* ps-image
* ps-image-bkg
* ps-image-buy
* ps-image-iptc
* ps-share

These elements are used to create:
* ps-image-card

Gallery information is used to create:
* ps-gallery-thumbs
* ps-gallery-slideshow (in development)

And these elements join the image elements to form:
* ps-gallery

*Polymer.js*

core-ajax, core-component-page, platform, polymer-test-tools, and polymer are currently included as v0.3.4. While I'll try to keep them up-to-date as best I can, please visit www.polymer-project.org for the latest.

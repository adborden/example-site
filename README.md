# Example site

This is an example static site that can be hosted on AWS's S3 with CloudFront
and continuously deployed automatically.

The "build" is copying the source html to the build directory, but you can
replace this with any build that produces html, css, and javascript.

    $ make build

The real magic of course is that changes you make to `index.html` that are then
committed to GH will automatically be deployed via the continuous integration
server.

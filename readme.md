# <a href="https://jeanandoliver.space">Jean and Oliver’s</a> travel website

[jeanandoliver.space](https://jeanandoliver.space) is a travel collaboration between [Jean](https://jeancflanagan.com) and [Oliver](https://olivermak.es). It is designed to log our trips together using photography, written notes, and mapped locations. The first trip is Vermont, October 2016.

This site uses completely fluid responsive typography.

## Goals

- Create an independent archive of our travels.
- Experiment with large scale typography and bold layouts that feature photography prominently.

## Implementation

- Building: [Jekyll](http://jekyllrb.com) and [npm scripting](https://docs.npmjs.com/cli/run-script)
- Hosting: Amazon [CloudFront](https://aws.amazon.com/cloudfront/), [S3](https://aws.amazon.com/s3/) and [imgix](https://www.imgix.com) for hosting; [AWS ACM](https://aws.amazon.com/certificate-manager/) for TLS (HTTPS) certificate
- Deploying: [s3_website](https://github.com/laurilehmijoki/s3_website), via [Travis CI](https://travis-ci.org)
- Version control: GitHub
- Typography: [Adobe Typekit](https://typekit.com/colophons/hro5wuc) – 100 condensed, 300 and 600 semi-condensed weights of [the Acumin typeface](http://acumin.typekit.com)
- Layout: `flexbox`, fluid typography, responsive images
- Maps: [Mapbox](https://www.mapbox.com/)

<a href="https://olivermak.es/"><img src="https://olivermak.es/icons/favicon144.svg" width="100%" height="144"></a>

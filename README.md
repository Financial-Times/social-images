# Social images [![Build status](https://img.shields.io/circleci/project/Financial-Times/social-images.svg)](https://circleci.com/gh/Financial-Times/social-images)

A set of social media icons. These are coloured with the logo colour of the social network.

## Usage

As with all image sets, these are available via the [Image Service](https://www.ft.com/__origami/service/image/v2).

To get an image from the image service, use the following URL (replace the `product_source` with your product name and `icon_name` with the icon you want)

`https://www.ft.com/__origami/service/image/v2/images/raw/ftsocial:{icon_name}?source={product_source}`

So to get a twitter icon:
`https://www.ft.com/__origami/service/image/v2/images/raw/ftsocial:twitter?source=test`


### Getting these icons in a different colour/format/size

The Image Service will convert these images on the fly if you pass in the right parameters. To find out more about this, please see the [Image Service documentation](https://www.ft.com/__origami/service/image/v2/docs/api)

## Adding or modifying icons

To keep social icons consistent, please follow these guidelines:

- Icons must be SVG format
- Icons must represent the brand colours of the social network
- Icons should have a viewBox of 66x66
- Icons must be passed through an SVG compressor like SVGOMG

---
## Questions or comments?

Please [raise an issue](https://github.com/financial-times/social-images/issues), or Internal FT users can contact us via [#ft-origami in Slack](https://financialtimes.slack.com/messages/ft-origami/).

## Licence

This software is published by the Financial Times under the [MIT licence](http://opensource.org/licenses/MIT).

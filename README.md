# Social images [![Build status](https://img.shields.io/circleci/project/Financial-Times/social-images.svg)](https://circleci.com/gh/Financial-Times/social-images)

A set of social media icons. These are coloured with the logo colour of the social network.

- [Usage](#usage)
- [Adding or modifying icons](#adding-or-modifying-icons)
- [Contact](#contact)
- [Licence](#licence)

## Usage

As with all image sets, these are available via the [Image Service](https://www.ft.com/__origami/service/image/v2).

To get an social logo from the Image Service, use the following URL (replace the `product_source` with your product name and `icon_name` with the icon you want)

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
- File names must be all lower case and hyphenated
  - **good** twitter.svg, financial-times.svg, yahoo.svg
  - **bad** Twitter.svg, financialtimes.svdg, yahoo!.svg

----

## Contact

If you have any questions or comments about this component, or need help using it, please either [raise an issue](https://github.com/Financial-Times/o-social-images/issues), visit [#ft-origami](https://financialtimes.slack.com/messages/ft-origami/) or email [Origami Support](mailto:origami-support@ft.com).

----

## Licence

This software is published by the Financial Times under the [MIT licence](http://opensource.org/licenses/MIT).

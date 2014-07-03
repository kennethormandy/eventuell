<!--
[![A great header image you designed, or collaborated on with a designer you work with. It’ll look best when it’s 728px wide, @2x for hi-dpi devices.](preview.png)](https://github.com/kennethormandy/default)

***
-->

# Eventuell

Send email newsletters with <a href="http://goodbits.io">Goodbits</a>, and good type.

## Getting started

More to come!

```bash
npm install -g harp
harp server
# Visit http://localhost:9000
```

When you’re ready to compile for MailChimp:

```bash
harp compile
```

…and the placeholder text is replaced with Goodbits template tags. Right now, you still have
add the resulting styles from `www/main.css` into the head of `www/index.html`, and then run
it all through an inlining tool [like MailChimp’s](http://templates.mailchimp.com/resources/inline-css/).
This is a less-than-ideal workflow. I’m hoping to take care of it through Harp in a later version.
It’s probably better to just use [kennethormandy/wink](https://github.com/kennethormandy/wink)
in the meantime. (Or, something else entirely!)

## Contributing

Thanks for considering contributing! There’s information about how to [get started with Eventuell here](CONTRIBUTING.md).

## License

[The MIT License (MIT)](LICENSE.md)

Copyright © 2014 [Kenneth Ormandy](http://kennethormandy.com) & [Chloi Inc.](http://chloi.io)

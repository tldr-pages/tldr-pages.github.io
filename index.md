---
layout: default
---

<p class="widgets">
  {% include github_stars.html %}
  {% include twitter.html %}
  {% include gitter_im.html %}
</p>

The TLDR pages are a community effort to simplify the beloved man pages with practical examples. 

Try the [live demo](https://ostera.github.io/tldr.jsx){:target="blank"} below or follow [installing instructions](#cli-installation) 

<iframe src="https://ostera.github.io/tldr.jsx"
        width="100%"
        height="300px"
        style="border: 1px solid"
  ></iframe>

## CLI Installation

As of now, our most mature client is the NodeJS one, which you can easily install from NPM:

~~~
npm install -g tldr
~~~

You can also try any of the many other TLDR clients that have sprouted from the community:

Client                                                                | Installation instruction
----------------------------------------------------------------------|----------------------------------------------------------------------------------------------------
[Web client](https://github.com/ostera/tldr.jsx)                       | [the live demo](https://ostera.github.io/tldr.jsx)
[Node.js client](https://github.com/tldr-pages/tldr-node-client)      | ```npm install -g tldr```
[Ruby client](https://github.com/YellowApple/tldrb)                   | ```gem install tldrb```
[Rust client](https://github.com/rilut/rust-tldr)                     | ```cargo install tldr```
[Python client](https://github.com/lord63/tldr.py)                    | ```pip install tldr.py```
[C++ client](https://github.com/tldr-pages/tldr-cpp-client)           | ```brew tap tldr-pages/tldr``` <br> ```brew install tldr```
[Android client](https://github.com/gianasista/tldr-viewer)           | available on [Google Play](https://play.google.com/store/apps/details?id=de.gianasista.tldr_viewer)
[iOS client](https://github.com/freesuraj/TLDR) | [TLDR Man Page in App Store](https://appsto.re/sg/IQ0-_.i)
[Dash for OSX](https://github.com/Moddus/tldr-python-dash-docset) | open Preferences / Downloads / User Contributed <br> find `tldr pages` in the list

There are more clients listed in [TL;DR clients wiki page]({{ site.github }}/wiki/TLDR-clients).

## Contribute

Fork project's [Github repo]({{ site.github }}).

This repository is just that: an ever-growing collection of examples for the most common UNIX / Linux / OSX / SunOS / Windows commands.

You're encouraged to edit some page from the `pages/` folder and submit a pull request. Just keep in mind the few things below.

#### Best Practices:

- Have a look at a few existing pages.
- Focus on the 5-6 most common usages.
- When in doubt, keep new command-line users in mind.
- Introduce examples gradually, from simple to complex.
- Don't explain general UNIX concepts.

Check more detailed [Contributing Guidelines]({{site.github}}/blob/master/CONTRIBUTING.md).


## License

[MIT License]({{site.github}}/blob/master/LICENSE.md)

{% include github_ribbon.html %}


---
layout: default
---

> Simplified and community-driven man pages

The TLDR pages are a community effort to simplify the beloved man pages with practical examples.

Try the [live demo](https://ostera.github.io/tldr.jsx){:target="blank"} below or follow [installing instructions](#cli-installation) 

<iframe src="https://ostera.github.io/tldr.jsx"
        width="100%"
        height="300px"
  ></iframe>

## CLI Installation

Install the NodeJS client

~~~
npm install -g tldr
~~~

You can also try other TLDR clients

Client                                                                | Installation instruction
----------------------------------------------------------------------|----------------------------------------------------------------------------------------------------
[Web client](https://github.com/ostera/tldr.jsx)                       | try tldr on your browser [here](https://ostera.github.io/tldr.jsx)!
[Node.js client](https://github.com/tldr-pages/tldr-node-client)      | ```npm install -g tldr```
[Ruby client](https://github.com/YellowApple/tldrb)                   | ```gem install tldrb```
[Python client](https://github.com/lord63/tldr.py)                    | ```pip install tldr.py```
[C++ client](https://github.com/tldr-pages/tldr-cpp-client)           | ```brew tap tldr-pages/tldr``` <br> ```brew install tldr```
[Android client](https://github.com/gianasista/tldr-viewer)           | available on [Google Play](https://play.google.com/store/apps/details?id=de.gianasista.tldr_viewer)

There are more clients listed in [README.md]({{ site.github }}/blob/master/README.md#clients).

## Contribute

Fork project's [Github repo]({{ site.github }}).

This repository is just that: an ever-growing collection of examples for the most common UNIX / Linux / OSX / SunOS commands.

Just edit some page from `pages/` folder and submit a pull request.

Best practices:

- Focus on the 5-6 most common usages.
- When in doubt, keep new command-line users in mind.
- Introduce examples gradually, from the simplest to more complex.
- Don't explain general UNIX concepts.
- Have a look at a few existing pages.

Check more detailed [Contributing Guidelines]({{site.github}}/blob/master/CONTRIBUTING.md).


## License

[MIT License]({{site.github}}/blob/master/LICENSE.md)

{% include github_ribbon.html %}

{% include github_stars.html %}

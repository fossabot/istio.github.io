# istio.github.io
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Frshriram%2Fistio.github.io.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Frshriram%2Fistio.github.io?ref=badge_shield)


This repository contains the source code for the [istio.io](https://istio.io) web site.

Please see the main Istio [README](https://github.com/istio/istio/blob/master/README.md)
file to learn about the overall Istio project and how to get in touch with us. To learn how you can
contribute to any of the Istio components, please 
see the Istio [contribution guidelines](https://github.com/istio/istio/blob/master/CONTRIBUTING.md).

The website uses [Jekyll](https://jekyllrb.com/) templates and is hosted on GitHub Pages. Please make sure you are
familiar with these before editing.

To run the site locally with Docker, use the following command:

```bash
docker run --rm --label=jekyll --volume=$(pwd):/srv/jekyll  -it -p 127.0.0.1:4000:4000 jekyll/jekyll jekyll serve
```


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Frshriram%2Fistio.github.io.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Frshriram%2Fistio.github.io?ref=badge_large)
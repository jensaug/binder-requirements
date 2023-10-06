## :dash: :dash: **The Binder Project is moving to a [new repo](https://github.com/jupyterhub/binderhub).** :dash: :dash:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jensaug/binder-requirements/HEAD)

---

# Example Binder with requirements.txt

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/binder-project/example-requirements)

A Binder-compatible repo with a `requirements.txt` file.

The `requirements.txt` file should list all Python libraries that your notebooks depend on, and they will be installed using

```
pip install -r requirements.txt
```

Note that many scientific Python libraries (e.g. `numpy`, `scipy`, `sklearn`, etc.) are included already because the [`base`](https://github.com/binder-project/binder-build-core/blob/master/images/base/Dockerfile) image for Binder is built on Anaconda.

In this example we include the library `seaborn`, and our notebook uses Seaborn to plot a figure.

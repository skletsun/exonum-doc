# Exonum Documentation

This is the documentation repo for the Exonum platform. It contains source files
used to build the documentation displayed on the [Exonum
website](http://exonum.com/).

## Build instructions

First of all you need to install [python-pip](https://pip.readthedocs.io/en/stable/installing/).

Install `mkdocs`:

```
pip install mkdocs
```

Install theme:

```
pip install mkdocs-bootswatch
```

Run docs on local machine [127.0.0.1:8000](http://127.0.0.1:8000):

```
mkdocs serve
```

Build for production:

```
mkdocs build
```

[Here](http://www.mkdocs.org/user-guide/writing-your-docs/) you can find more information 
about docs writing such as [linking](http://www.mkdocs.org/user-guide/writing-your-docs/#linking-documents), 
adding of [images and media](http://www.mkdocs.org/user-guide/writing-your-docs/#images-and-media), 
[tables](http://www.mkdocs.org/user-guide/writing-your-docs/#tables) markdown and etc.

## License

Copyright 2016, Bitfury Group

Exonum Documentation is licensed under the Apache License (Version 2.0). See
[LICENSE](LICENSE) for details.

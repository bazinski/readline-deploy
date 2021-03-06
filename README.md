[![Build Status](https://ci.sagrid.ac.za/buildStatus/icon?job=readline-deploy)](https://ci.sagrid.ac.za/job/readline-deploy) [![DOI](https://zenodo.org/badge/48041795.svg)](https://zenodo.org/badge/latestdoi/48041795)


# readline-deploy

This contains the build, test and deploy scripts for the [GNU readline library](http://cnswww.cns.cwru.edu/php/chet/readline/rltop.html) for CODE-RADE.

In order to use this readline library in your own projects, simply add the module :

```
module add readline
```

# Dependencies

  * ncurses [![Build Status](https://ci.sagrid.ac.za/buildStatus/icon?job=ncurses-deploy)](https://ci.sagrid.ac.za/job/ncurses-deploy/)

# Versions

The following versions are built in Foundation Release 3 :

  1. 6.3
  1. 7.0

# Configuration Options

The project is configured with :

```
../configure \
--enable-shared  \
--enable-static \
--with-curses \
--prefix ${SOFT_DIR}
```

# Citing

Cite as :
Bruce Becker. (2017). SouthAfricaDigitalScience/readline-deploy: CODE-RADE Foundation Release 3 - readline [Data set]. Zenodo. http://doi.org/10.5281/zenodo.571826

# MiniTorch Module 0


## Overview

<img src="https://minitorch.github.io/_images/match.png" width="100px">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module0.html

## Fixed
- `setup.cfg`: Change `[files]` in Line 5 to `[options]`(with `setptools==61.2.0`)
- Pkgs: Uninstall `click==8.0.4` and install `click-8.0.4` to fix the runtime error of streamlit
(AttributeError: module 'click' has no attribute 'get_os_args') 


Lollylib
========================

'Lollylib' is a multipurpose Python 3 library that creates an additional abstraction layer and provides higher level interface for python developers.

### Draft notice

Note that Lollylib is currently a draft. You can use it at your own risk, but there are no guarantees regarding future development of this project.

## Table of contents

[Requirements](#requirements)

[Installation](#installation)

[Getting started](#getting-started)

[About authors](#about-authors)

### <a name="requirements"></a> Requirements

`Lollylib` requires Python 3 version 3.5 or greater. 
It may be used on Windows, MacOS and Linux. 
So far, `lollylib` has not been tested on other operating systems, but very likely it can run 
in any Python 3 environment without customization.


### <a name="installation"></a> Installation

#### Windows
From web:
`py -3 -m pip install lollylib`

From local directory:
`py -3 -m pip install . `



#### Linux and MacOS
From web:
`pip3 install lollylib`

From local directory:
`pip3 install . `


#### Running tests
Tests are shipped together with `lollylib`.
If you installed it from web, you may run the tests from Python 3 shell:
```python
import lollylib.test as test 
test.run()
```

#### Installing for development
If you want to contribute to `lollylib`, it is convenient to install it locally as a link
so that changes you make will be immediately visible to all `lollylib` users. Download or clone it
from https://github.com/sugurd/lollylib, then run from `lollylib` root directory: `pip3 install -e . `

### <a name="getting-started"></a> Getting started

The best way to get started with `lollylib` is to explore the tests. There you will find examples of 
legitimate use cases in great detail.

### <a name="about-authors"></a> About authors

You may contact the author via `yuzappa@gmail.com`.
+++
type = "rivanna"
images = [
  "/2016/10/image.jpg",
]
categories = [
  "HPC",
  "software",
]
date = "2019-06-23T08:37:46-05:00"
tags = [
  "lib",
]
draft = false
shorttitle = "Libraries"
title = "Libraries on Rivanna"
description = "Libraries in Rivanna's HPC environment"
author = "RC Staff"

+++

# Available Software Libraries

To get an up-to-date list of the installed software libraries, log on to Rivanna and run the following command in a terminal window:
```
module keyword lib
```

To get more information about a specific module version, run the module spider command, for example:
```
module spider hdf5/1.10.4
```

<br>

**List of Software Library Modules**

{{< rivanna-software tags="numlib"  >}}

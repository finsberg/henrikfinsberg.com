---
date: 2018-10-04
title: Running matlab from python
subtitle: Without a license
---
Did you know that you can take your existing Matlab code, compile it
and turn it into a python package? Then you can distribute the packag
and your first and import and run your package without having to buy a 
matlab license.
  
{{< figure src="/img/matlab_python.jpg" >}}

[Matlab](https://se.mathworks.com/products/matlab.html) is the number
one choice for many researchers within the scientific computing
community. There many reasons for this, for example the fact that
Matlab is a commercial software provides confidence that the core
functionality is robust and contains few bugs. 

Today we see a shift on the software side towards open source
alternatives such as [python](https://www.python.org). So can we take
out old, robust Matlab code and integrate that into our new python
library? Yes we can! And, it is possible to run that code without
buying an expensive a Matlab license? Yes, that is possible!
Check out my [matlab_compiler
repo](https://github.com/finsberg/matlab_compiler) to learn how.

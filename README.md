# global_planner

UWA REV Project

From: https://github.com/RomanCPodolski/samling_based_planning

http://robotics.ee.uwa.edu.au/theses/2017-REV-AutonomousPath-Podolski.pdf

---

Requirements:

```
glog (libgoogle-glog-dev)
gflags (libgflags-dev)
Boost (1.65.1 via libboost-all-dev is fine - be suspicious of /math/quadrature/trapezoidal.hpp)
```

Build:
```
cmake .
make
```

To visualise simulation output (with pdfTeX):
```
latex -output-format=pdf -interaction nonstopmode simulation.tex
```

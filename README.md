# SPOOLES 2.2
## About

This is a mirror of the .tar file from the SPOOLES website https://www.netlib.org/linalg/spooles/spooles.2.2.html.

I have personally added changs to the codebase as per instructions from https://www.foambuilder.com/pages/compile_CalculiX.php for the purposes of compiling CalculiX.

## Compiling

To compile the serial version this software, run 

```bash
make global
```

and to compile the parallel (MT) version of the software run

```bash
cd MT/src
make
```

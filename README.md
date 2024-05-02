# MPM 3D
This particle simulator is based on taichi software:
https://taichi.graphics/

https://github.com/Jaisiero/mpm_3d_exercise/assets/6051981/4f854322-97e3-40c8-befe-d1849b580128

![Water + Jelly + Snow](https://github.com/Jaisiero/mpm_3d_exercise/assets/6051981/bd31792e-6104-4f66-8fe8-39b777a74710)


## Installation
Make sure your `pip` is up-to-date:

```bash
$ pip3 install pip --upgrade
```

Assume you have a Python 3 environment, to install Taichi:

```bash
$ pip3 install -U taichi
```

To run the demo:

```bash
$ python mpm_3d_starter.py
```


## Extra credits are for the extras
There are plenty of room for hacking! We suggest a few of them for you to start with:
- Higher resolution simulations utilizing sparse data structures
- More sophisticated boundary handling and better scenes
- Better particle initialization with arbitrary shapes
- Faster P2G step without floating point atomic operations (integers are fine)
- Higher order time integration methods
- Implicit time integration methods
- Supporting more material models
- Reducing the numerical adhesion/friction/fracture artifacts
- etc.

## Show your work
We encourage you to continue developing on this repo and share your work with our community members. To notify us about your work, make sure you use this repo as a template.

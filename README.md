# unofficial-pynini-wheels

Build `manylinux2014_x86_64` and `manylinux2014_aarch64` Python wheels for `pynini`, wrapping all its dependencies.


## What is this?

Pynini is widely used library for various companies. 
but it doesn't support all architectures and all python versions in their repository.

Trying to build pynini from source is not easy, and it's not easy to build all the dependencies.
Insprired by [build-pynini-sheels](https://github.com/ServiceNow/build-pynini-wheels),
I've created this repository to build pynini wheels for all python versions and architectures.

Check it out official `pynini` homepage.

- https://www.opengrm.org/twiki/bin/view/GRM/Pynini


## How to Use?

Just use pip with wheel, or upload wheels to your custom pypi server.

```bash
# Python 3.10
pip install https://github.com/kimdwkimdw/unofficial-pynini-wheels/releases/download/test_release/pynini-2.1.5-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl
# Python 3.11
pip install https://github.com/kimdwkimdw/unofficial-pynini-wheels/releases/download/test_release/pynini-2.1.5-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl
```


## Maintenance
This repository aims to create its own obsolescence by providing the `pynini` maintainer
with the means to create their own wheels. Updates may thus be "spotty" at best, and the
repository will be retired once an official alternative is available.

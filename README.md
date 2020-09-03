This repo contains pre-built binary packages of
[pytorch/xla](https://github.com/pytorch/xla/).

I followed this contributing
[guide](https://github.com/pytorch/xla/blob/master/CONTRIBUTING.md)
and built pytorch/xla version 1.6.0 from source code using Docker.

Then, I copied the `lib*.so` files from the Docker container to the
host, stripped the binaries, mixed with the C/C++ source files, and
packed the tarball.

### Echo

This is more of a tool than an example. It is a lightweight way of printing what messages are on the bus from the command line.
The help output of this tool is very verbose and is the best way to get acquainted with its functionality.
Sometimes this tools gets bogged down with very large message types, such as `ps_lidar_points_msg`.

### Dependencies

Packages: libglib2.0-dev

To install on Ubuntu:

```bash
sudo apt-get install <package>
```

### Building and running the node

```bash
$ cd Echo 
$ mkdir build && cd build
$ cmake ..
$ make
$ ./polysync-echo
```

For more API examples, visit the "Tutorials" and "Development" sections in the PolySync Help Center [here](https://help.polysync.io/articles/).

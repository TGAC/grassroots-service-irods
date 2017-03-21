# iRODS service

The iRODS service allows the Grassroots Server to use the functionality provided by [iRODS](https://irods.org).
Currently it has the ability to perform queries against the iCAT metadata catalog including against all possible key values for all data objects and collections as well as more general searches search as modification times, *etc.*
 
## Installation

To build this service, you need the [grassroots core](https://github.com/TGAC/grassroots-core) and [grassroots build config](https://github.com/TGAC/grassroots-build-config) installed and configured. 

The files to build the iRODS service are in the ```build/<platform>``` directory. 

### Linux

If you enter this directory 

```cd build/linux```

you can then build the service by typing

```make all```

and then 

```make install```

to install the service into the Grassroots system where it will be available for use immediately.


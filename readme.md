# iRODS service {#irods_search_service}

The iRODS service allows the Grassroots Server to use the functionality provided by [iRODS](https://irods.org).
Currently it has the ability to perform queries against the iCAT metadata catalogue as well as more general searches search as modification times, *etc.*
 
By default in iRods, you would need to know which keys exist to then search them for particular associated values. With this Service, each keyword within the metadata catalogue is listed for the user along with all of its possible values. 

This service also has the ability for a value to be searched for across all possible keys. The results are then ranked by occurrence.

## Installation

To build this service, you need the [grassroots core](https://github.com/TGAC/grassroots-core) and [grassroots build config](https://github.com/TGAC/grassroots-build-config) installed and configured. 

The files to build the iRODS service are in the ```build/<platform>``` directory. 

### Linux

If you enter this directory 

```
cd build/linux
```

you can then build the service by typing

```
make all
```

and then 

```
make install
```

to install the service into the Grassroots system where it will be available for use immediately.


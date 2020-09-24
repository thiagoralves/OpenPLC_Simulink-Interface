## What if more input/output variables are needed?

For example, if we want to have more than 16 digital output values (e.g. 32), 
we first need to change the `DIGITAL_BUF_SIZE` from 16 to 32 in `simlink.cpp`. 
To work with [OpenPLC runtime](https://github.com/thiagoralves/OpenPLC_v3) accordingly, we need to change the `DIGITAL_BUF_size` 
in the `webserver/core/hardware_layers/simulink.cpp` and `webserver/core/server.cpp` as well.

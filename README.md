C logging library
=================

This module creates a unique log handler for a program.  It supports several helper functions to handle logging of error messages.  This module uses the [cyclic file handler](https://github.com/cunha/cyc) to create thread-safe rotating files.  The interface is as follows:

1. initialize the log handler using ```log_init```
2. print messages to the file using ```logd```, ```loge```, and ```logea```
3. destroy the logging handler with ```log_destroy``` when you are done.
 

# PiFS
Raspberry Pi Functionality Suite - Xojo

The Raspberry Pi Functionality Suite is a collection of Raspberry Pi OS (Debian) specific functionality that is not readily available in a free format. It is an open source collaboration that brings users all of the specialized Raspberry Pi functionality that is not included with Xojo/Real Studio itself. 

Notes
This code was originally written by Eugene Dakin for Xojo. 

Xojo
 - Version 2025R1.1

Repository Location
Https://github.com/eugenedakin/PiFS

Versions:
Version 1.0 (9 May 2025)
- added Accept method
- added Bind method
- added Close method
- added Errno method
- added ErrnoMessage method
- added fcntl method
- added hci_devinfo method
- added hci_get_route method
- added Listen method
- added Read Method
- added selectBT method
- added Socket method
- added Write method
- added hci_dev_info structure 
- added hci_dev_stats structure 
- added sockaddr_rc structure 
- added over 35 bluetooth constants

Version 1.1 (25 May 2025)
- added Statvfs structure 
- added statvfs method

Version 1.2 (2 June 2025)
- added Timerfd_Create method
- added Timerfd_SetTime method
- added CLOCK_MONOTONIC constant
- added TFD_CLOEXEC consttant
- added TFD_NONBLOCK constant

Version 1.3 (3 June 2025)
- added clock_gettime method
- added usleep method
- added nanosleep method
- added CLOCK_REALTIME constant
- added CLOCK_PROCESS_CPUTIME_ID constant
- added CLOCK_THREAD_CPUTIME_ID constant
- added TimeSpec structure

Version 1.4 (4 June 2025)
- added Timer Methods in the PiTimer Class 
- added Elapsed Microseconds Timer Method
- added Elapsed Milliseconds Timer Method
- added GetCurrentTime Timer Method
- added IsRunning Timer Method
- added Reset Timer method
- added SleepNanoseconds Timer Method
- added Start Timer method
- added Stop Timer method
- added NanoSleep Declare
- added uSleep (microsleep) Declare

# qt_singleapplication
The SingleApplication component provides support for applications that can be  only started once per user,  qt5.9 able.


The SingleApplication component provides support for applications that can be 
only started once per user.

For some applications it is useful or even critical that they are started only once by any user. 
Future attempts to start the application should activate any already running instance, 
and possibly perform requested actions, e.g. loading a file, in that instance.

The SingleApplication class provides an crossplatform interface to detect a running instance, 
and to send command strings to that instance.

The SingleApplication component is basically imitating QtSingleApplication commercial class. Unlike QtSingleApplication the SingleApplication implementation uses Shared Memory 
to detect a running instance and so-called "Local Sockets" to communicate with it.

SingleApplication might be usable in all environments where you find Qt.
SingleApplication requires Qt 5.9.x or newer.

Licence: LGPLv2


/examples/loader/ MACOSX  can open file by drag from finder to app icon support on qt 5.9....


# LegoNXTRemote #
This is a library for manipulating LEGO Mindstorms NXT bricks.  It includes a standalone Cocoa Framework and a sample Cocoa Remote application written in Objective-C.  It is multi-platform and is not dependent on LEGO libraries.

There are two products distributed in this project:

## LegoNXT.framework ##
This is a framework providing the ability to manipulate a LEGO Mindstorms NXT brick over Bluetooth.  This framework exposes both low-level manipulations as well as a high-level interface for sensor polling.  This framework does not rely on the the LEGO fantomSDK or any other external libraries, making it easy to build and modify.

## LegoNXTRemote ##
This is a sample application which makes use of the above framework to manipulate most functions of the LEGO Mindstorms NXT brick over Bluetooth.  It makes use of the native Bluetooth libraries for simple device discovery.
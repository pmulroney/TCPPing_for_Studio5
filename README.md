# ListIntersect

The TCPPing command in Omnis is a useful tool, but with the updates in operating systems, no longer works for Studio 5 on MacOS 10.12 (Sierra) and above.  This method has been written to use applescript instead to call the built-in OS command to perform the ping operation.

## USAGE
```omnis
NetworkCommands/TCPPing(psHostName,pnPacketSize,pnTimeout) returns vnPingTime
```
IN: 
* psHostName: hostname or IP address of the device to ping
* (optional) pnPacketSize: packet size in bytes.  (Defaults to 56 bytes if not set)
* pnTimeout: the timeout in seconds.  (Defaults to 5 seconds if not set)
OUT: The ping time in milliseconds, or -1 if there is an error.

## AUTHORS
@pmulroney, submitted on behalf of Logical Developments

## Contributing
1. Fork this repository
1. Add a branch for your feature
1. Add the feature and perform a new JSON export
1. Submit a pull request

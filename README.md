<br>

Slightly modified version of [SandboxEscaper](https://twitter.com/sandboxescaper)'s [ALPC-TaskSched-LPE exploit](https://github.com/SandboxEscaper/randomrepo/blob/master/PoCLPE.rar).

The following changes are added:

- logging to C:\Users\Public\Documents\alpc.log - for easier debugging

- payload DLL is loaded from C:\Users\Public\Documents\elev.dll, not from resources - allows for easier changing of payload, without the need to rebuild or manipulate DLL's resources


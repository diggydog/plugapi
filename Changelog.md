plugAPI Changelog
=================

2.0.3
-----
* **FIXED:** Fix broken getHistory (Commit [645f03a](https://github.com/TATDK/plugapi/commit/645f03a30504183ce24d7034c66fe08579657281))

2.0.2
-----
* **FIXED:** More inteligent way of running the queueTicker (Commit [80e314c](https://github.com/TATDK/plugapi/commit/80e314c6bc4a18a109d3bf14f3602c6d8ccbc3de))

2.0.1
-----
* **FIXED:** Changed required node version from 0.6 to 0.10 (Commit [78ec90f](https://github.com/TATDK/plugapi/commit/78ec90fca5d2fa1404e85e8df49b14ea76bc3372))

2.0.0
-----
* **ADDED:** Settings files for formatting in .jsbeautifyrc and .editorconfig format (Commit [5123fbc](https://github.com/TATDK/plugapi/commit/5123fbce7206c15d0e985cc73c0e3ba82c8bb258))
* **ADDED:** Prevent spamming plug.dj's servers (Commit [e52a3ef](https://github.com/TATDK/plugapi/commit/e52a3eff27df94914911f0cbdcd67d4bb2888062))
* **ADDED:** Support to use plugCubed's socket server for PMs (Commit [e52a3ef](https://github.com/TATDK/plugapi/commit/e52a3eff27df94914911f0cbdcd67d4bb2888062))
* **FIXED:** plug.dj backend changes (Commit [e52a3ef](https://github.com/TATDK/plugapi/commit/e52a3eff27df94914911f0cbdcd67d4bb2888062))
* **FIXED:** plug-dj-login is now an optional dependency as it was supposed to be (Commit [9003025](https://github.com/TATDK/plugapi/commit/90030251ac2120c81634d8fad6604678a6c348c6))
* Using Grunt to run Closure Compiler on the api (Commit [7719cdc](https://github.com/TATDK/plugapi/commit/7719cdc760e21cf1a61dac1fb6485e11f9fc89f7))
* Fix order of readme (Commit [b7b66a6](https://github.com/TATDK/plugapi/commit/b7b66a695de892cc218d973032ccb7e1ab249183))
* Facepalm, bin folder needs to be included (Commit [7719cdc](https://github.com/TATDK/plugapi/commit/7719cdc760e21cf1a61dac1fb6485e11f9fc89f7))

1.1.4
-----
* **FIXED:** Ensure gateway requests sends an array (Commit [d000f9d](https://github.com/TATDK/plugapi/commit/d000f9d8b77c92594773f5808546ef39a442e0bb))

1.1.3
-----
* **FIXED:** Uncompress the updatecode from the server (Commit [963235a](https://github.com/TATDK/plugapi/commit/963235af51a80e160f1a07a7ca162203c59720ea))
* **REMOVE:** Removed cheerio as a dependency as it wasn't used (Commit [52731a6](https://github.com/TATDK/plugapi/commit/52731a6af870120888731e6b559eb0b82b65cdd8))

1.1.2
-----
* **CHANGE:** Now getting the updateCode from server (Commit [b32bc48](https://github.com/TATDK/plugapi/commit/b32bc4801c1208236f81fa46441a7e72a845786b))

1.1.1
-----
* **FIXED:** Hopefully give an error when gateway returns invalid JSON (Commit [dfb9c6c](https://github.com/TATDK/plugapi/commit/dfb9c6c19ed19bac5c6f318d349b97963d0ee0bf))
* **FIXED:** Actually remove the user when the user leaves the room (Commit [dfb9c6c](https://github.com/TATDK/plugapi/commit/dfb9c6c19ed19bac5c6f318d349b97963d0ee0bf))

1.1.0
-----
* **ADDED:** Added optional autodelete of message (Commit [af6f879](https://github.com/TATDK/plugapi/commit/af6f879f52239bc0c67d46c84c9cb464f17e57c6))
    1. Added respondTimeout for commands
    1. Added timeout parameter for intChat, chat and sendChat
* **CHANGE:** Now using MIT license (Commit [93da87d](https://github.com/TATDK/plugapi/commit/93da87d3ad0655a5cb265ee50a80c6189f92004d))

1.0.0
-----
* Initial Release
* TAT is added as maintainer of the official npm package
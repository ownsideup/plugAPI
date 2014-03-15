plugAPI Changelog
=================

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
* Changed license to MIT (Commit [93da87d](https://github.com/TATDK/plugapi/commit/93da87d3ad0655a5cb265ee50a80c6189f92004d))

1.0.0
-----
* Initial Release
* TAT is added as maintainer of the official npm package
# streampub privacy policy

*Last updated: 2026-11-01*

streampub is a personal tool run by its owner on a private home server. It uploads the owner's own video
recordings to the owner's own YouTube channel.

**What it accesses.** Through the YouTube Data API it uploads videos, sets their title, description, thumbnail,
playlist and scheduled publish time, and reads back their processing and privacy status. It uses the
`youtube.upload` and `youtube` OAuth scopes for this.

**What it stores.** On the owner's home server only: the OAuth token for the owner's Google account, the local
recordings until they are published, and a log of upload status. Nothing is stored anywhere else.

**Whose data.** Only the owner's. The tool has no other users and never reads data from other channels or
accounts.

**Sharing.** No data is shared with or sold to anyone. The only third party involved is Google, through its
YouTube Data API, under [Google's privacy policy](https://policies.google.com/privacy) and the
[YouTube Terms of Service](https://www.youtube.com/t/terms).

**Revoking access.** The owner can revoke the tool's access at any time at
[Google account permissions](https://myaccount.google.com/permissions), and delete the stored token on the server.

**Contact.** Open an issue in this repository.

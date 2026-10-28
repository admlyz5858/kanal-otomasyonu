# Privacy Policy — Kanal Otomasyonu

Last updated: 28 October 2026

Kanal Otomasyonu ("the tool") is a private, internal tool used only by its owner, an individual YouTube creator. It publishes videos to the owner's own YouTube channels and reads analytics for those channels. It runs only on the owner's own phone and has no other users.

The tool uses **YouTube API Services**. Use of YouTube data through the tool is subject to the Google Privacy Policy (https://policies.google.com/privacy) and the YouTube Terms of Service (https://www.youtube.com/t/terms).

## Information the tool accesses

With the owner's authorization through Google OAuth, the tool accesses only the owner's own channels:

- channel details and branding settings,
- the owner's videos, their metadata and status,
- analytics reports for the owner's channels (YouTube Analytics API).

OAuth scopes requested: `youtube.upload`, `youtube.force-ssl`, `yt-analytics.readonly`.

For content research, the tool may also read publicly available video information through the YouTube Data API with an API key, such as titles, view counts and channel subscriber counts. This public data is used only in aggregate, to decide which topics to make videos about.

The tool does not collect personal information about viewers or any other YouTube users.

## How the information is used

Information is used only to upload and manage the owner's own videos and channels, and to plan the owner's future videos.

The tool does not use YouTube data for advertising. It does not sell, rent or share any data with third parties.

## Storage, security and retention

OAuth refresh tokens are stored only on the owner's device, in a private directory that only the owner can read. They are sent only to Google's OAuth endpoints.

Analytics data for the owner's channels is stored on the same device and kept only as long as it is needed for planning.

Public video information collected for research is deleted or refreshed within 30 days.

The tool has no server or website that collects data, and it uses no cookies.

## Revoking access

The owner can revoke the tool's access at any time at https://security.google.com/settings/security/permissions by removing "Kanal Otomasyonu". When access is revoked, the stored refresh tokens stop working and are deleted.

## Contact

Open an issue in this repository: https://github.com/admlyz5858/kanal-otomasyonu/issues

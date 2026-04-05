# Instagram-Downloader-Workflow (n8n)

This workflow allows users to download Instagram Reels videos through a Telegram bot using an external API.

Users send a Reels link via Telegram. The workflow sends the link to a downloader API, retrieves the direct video URL, and then downloads the video file. The video is automatically sent back to the user in Telegram.

If the user sends the start command, the bot provides simple instructions on how to use the service. Otherwise, every message is treated as an Instagram link for downloading.

The system is fast and requires only a valid Reels URL to return the video.

Requirements include n8n, Telegram Bot API, and access to a Reels downloader API.

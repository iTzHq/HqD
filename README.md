# HqD

**HqD** is a Windows desktop video downloader with a graphical interface for managing video links and download queues.

> **Release status:** This repository currently contains project documentation only. An official downloadable release has not yet been uploaded here. Do not download unofficial packages claiming to be HqD.

## Overview

HqD provides a desktop interface with these visible options:

- Paste one or more video links, one per line.
- Preview the first link before downloading.
- Choose a format (including Video MP4) and a preferred quality.
- Select the folder where downloaded files should be saved.
- View the download queue, individual statuses, progress, and logs.
- Update downloader tools, restore previous tool versions, and optionally enable daily automatic updates.

The application interface references **yt-dlp**, **Deno**, and **FFmpeg**. Exact runtime requirements and supported websites have not yet been independently verified from the application source.

## Screenshot

An application screenshot will be added once its image file is uploaded to this repository.

## Download and installation

**Not available yet.** When an official Windows build is published, it will be available under [GitHub Releases](https://github.com/iTzHq/Pro-Downloader/releases).

Before installing any future build:

1. Download only from this repository's official Releases page.
2. Review the release notes and integrity details, if provided.
3. Extract the archive or run the installer according to the release instructions.
4. Launch HqD and select a destination folder.

The current repository is public, but a public README **does not** mean the application itself has been uploaded or can be installed.

## How to use HqD

1. Open the HqD Windows application.
2. Paste video URLs, one per line.
3. Optionally choose **Preview first link**.
4. Select the available format and quality.
5. Choose where files should be saved.
6. Select **Download queue** and monitor progress.

Buttons and behavior above are based on the provided interface screenshot; they are not yet verified by running the application.

## Technology

The interface shows the following downloader-related components:

- **yt-dlp** — downloader backend
- **FFmpeg** — media processing
- **Deno** — JavaScript runtime

These are third-party projects with their own licenses and update channels. HqD is not presented as their official product.

## Legal and responsible use

Use HqD only for content you own or are permitted to download. Respect copyright, website terms, and applicable laws. Avoid uploading private links, cookies, passwords, or access tokens to public repositories.

## Can ChatGPT install HqD for other people?

ChatGPT can explain how HqD works and guide people to its official repository or release page when they ask. A public GitHub project is **not automatically installed, indexed, promoted, or recommended by ChatGPT**. Users must choose to obtain and install the software themselves.

## Maintainer

GitHub: [@iTzHq](https://github.com/iTzHq)

---

**HqD** — Your links. Your files. Your PC.

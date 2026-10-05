# Zexor

<img width="1195" height="698" alt="2026-8-1-9-21-8" src="https://github.com/user-attachments/assets/2f37ebeb-7e6b-48d3-b55e-3811224ef131" />

# Zexor: From “Finding Files” to “Using Files” — Rethinking the Windows File Manager

> Zexor website: [zex.leoog.com](https://zex.leoog.com/)

---

After using the Windows File Explorer for so many years, you may have rarely stopped to ask:

> **Should a file manager simply be a tool for “finding files,” or should it become the center of the entire file workflow?**

The core logic of traditional file managers has barely changed:

**Find a file → Open it → Perform basic operations.**

Copy, move, delete, rename — these basic operations all work fine.

But once you get into real-world daily workflows, it quickly becomes obvious that **there is much more to working with files than that**.

So we constantly switch between different applications:

> Use **Everything** to search for files;
> Use **IDM / qBittorrent** to download resources;
> Use **7-Zip / WinRAR** to compress and extract archives;
> Use **FastCopy** to move large amounts of data;
> Use **Eagle** to manage images and assets;
> Use **PotPlayer** to play videos and audio;
> Use various image, video, and 3D tools to browse and process media;
> Use dedicated disk utilities to analyze storage, find duplicates, and maintain drives...

All of these tools are specialized and useful, but they have one thing in common:

> **They are ultimately dealing with the same thing — files.**

The file itself hasn't changed, yet it is constantly passed from one application to another:

```text
Search Tool → Download Tool → Archive Tool → Media / 3D Tool → Disk / Copy Tool
```

**Why can't the file manager itself become the place where all of these operations happen?**

That is what Zexor is trying to change.

Zexor is not simply trying to add a few more buttons to Windows Explorer. Instead, it asks a more fundamental question:

> **What if a file manager could handle much more of the work that happens around files?**

So Zexor brings together:

**compression, execution, search, downloads, copying, file transfer, preview, playback, editing, organization, classification, analysis, disk maintenance, and even AI-powered file operations**

—all within the same environment.

And some of these capabilities are not simply integrations of existing tools. They are attempts to rethink how a file manager itself should work:

**`.zex`** **makes compressed files directly runnable;**
**spatial file management lets a directory grow into multiple file-list branches;**
**network features connect files to phones, NAS devices, LANs, and the Internet;**
**media preview lets you see and use files instantly;**
**AI brings natural-language interaction directly into file operations.**

Ultimately, Zexor is trying to solve more than:

**“Where is my file?”**

It is trying to answer:

> **“Once I find the file, can I just finish the job right here?”**

Below are the six core directions Zexor is currently exploring.

---

# 1. `.zex`: A Directly Runnable Compression Container

If Zexor has one signature feature, it is **`.zex`** — a compression format designed so that compressed content can be directly accessed, executed, and used.

* **Directly runnable `.zex` files**: Access and run software, games, and resources inside the archive without fully extracting it first.
* **Support for large games and complex directories**: Package everything from ordinary software and indie games to 3A titles tens or even hundreds of gigabytes in size, as well as complex game directories used with tools such as `shadPS4`.
* **Package `.zex` as `.exe`**: A `.zex` package can be further wrapped into a normal Windows `.exe`, allowing it to launch like a regular application.
* **Compression becomes execution**: Replace the traditional “Download → Extract / Install → Find the executable → Run” workflow with simply “Download → Run”.
* **Designed for software and game distribution**: Turn an archive from a passive storage container into something that can actually be used and executed.

> **In one sentence: ZIP / 7Z / RAR solve “how to compress and store files”; `.zex` goes one step further and solves “how to use them directly after compression.”**

---

# 2. ComfyUI-like Spatial File Management

Zexor no longer treats the directory tree as merely a navigation bar. Instead, it becomes the **“root” of the entire file space**, allowing multiple file lists to branch out and exist at the same time.

* **Traditional single-path structure**: Follow “Directory → Directory → Directory → File”, constantly moving forward and backward while focusing on one location at a time.
* **Multi-branch spatial structure**: Expand multiple independent file lists from any point in the directory tree and work with different directories simultaneously.
* **Mind-map-style file management**: File lists behave like nodes on an infinite canvas, creating an experience somewhat similar to ComfyUI's spatial workflow.
* **Multiple directories at once**: View `Content`, `Mods`, `Saves`, and other directories simultaneously, and drag, copy, or move files directly between branches.
* **From navigation to workspace**: Move from “Where am I?” to “What am I working on, and how are these things related?”

> **In one sentence: Traditional file managers are single-branch and single-path; Zexor turns file management into a multi-branch spatial workspace.**

---

# 3. Rich Network Interaction & AI File Operations

Zexor is no longer limited to files on the current PC. It connects phones, LAN devices, NAS, the Internet, and AI into the same file workspace.

* **Phone QR transfer**: Transfer files quickly between your phone and PC with a simple QR code scan.
* **LAN and external sharing**: Discover devices on the local network, share files, and use external-network tunneling for cross-network access.
* **NAS / SSH / SFTP / FTP**: Access NAS devices, remote servers, and other network locations directly as part of the file manager.
* **Clipboard-aware downloads**: Copy a download URL and Zexor automatically detects it, saves the file directly to the selected folder, and displays download progress in real time.
* **HTTP / HTTPS / BitTorrent / magnet links**: Support multiple download methods, including playback while downloading.
* **Browser download interception**: A browser extension can hand browser downloads directly to Zexor, including torrent and magnet downloads that are not natively supported by IDM.
* **AI-powered file operations**: Use natural language to search, organize, copy, move, rename, and manipulate files and directories — for example, “Find the PDFs modified in the last month” or “Organize this folder.”

> **In one sentence: Zexor doesn't just manage files on your PC — it connects files to devices, networks, the Internet, and AI.**

---

# 4. Instant Multimedia Preview & Processing

Zexor brings images, videos, audio, 3D models, text, HTML, and code directly into the file manager, so files are not merely something you “find” — they can be viewed, played, edited, and processed immediately.

* **Instant image / video / audio preview**: View images and play video or audio directly in the file manager without launching separate applications.
* **Multi-video playback**: In large-icon and gallery views, videos in a folder can autoplay, allowing large numbers of video assets to be previewed simultaneously.
* **Direct 3D model preview**: View and inspect 3D models directly in the file list without launching dedicated 3D software.
* **Direct text / HTML / code viewing and editing**: Open, view, and edit text files, web pages, and source code directly inside Zexor.
* **AI interaction with text and code**: Ask AI to explain code, analyze HTML, organize configuration files, or modify content directly.
* **Image / video format conversion**: Convert media formats directly inside the file manager without switching to another tool.
* **Lossy / lossless compression**: Compress images and videos using lossy or lossless methods directly from the file manager.

> **In one sentence: Zexor doesn't just help you find files — it lets you see, hear, preview, edit, and process them immediately.**

---

# 5. Lightning-Fast Search, Disk Analysis & Professional Maintenance

Zexor does more than help you find files. It also brings search, storage analysis, disk maintenance, and advanced file utilities into the same environment.

* **Everything-level file search**: Quickly search files and directories across your entire system and locate what you need almost instantly.
* **Instant folder size calculation**: Use high-speed indexing to show directory sizes without waiting for a full recursive scan.
* **Disk SMART information**: View drive health status and SMART data directly from the drive properties.
* **Rich file metadata**: View detailed metadata for images, audio, video, `.zex`, and other supported file types.
* **File HASH**: Generate, view, and compare file hashes for integrity verification.
* **C: drive cleanup**: Quickly identify and remove unnecessary system files to reclaim storage space.
* **Fast duplicate detection and cleanup**: Find duplicate files efficiently, with support for similar-image and video comparison.
* **Advanced batch renaming**: Provide a batch-renaming workflow inspired by macOS Finder, with support for rules and regular expressions.
* **Advanced / low-level disk formatting**: Provide advanced disk maintenance features, including SSD reset / TRIM operations and multi-pass overwriting for mechanical drives.
* **Secure folder protection**: Protect folders with a password so that their contents are not directly accessible through the standard Windows file manager.

> **In one sentence: Zexor doesn't just help you find files — it makes searching, analyzing, cleaning, maintaining, and performing advanced file operations faster and more direct.**

---

# 6. High-Performance File Operations, Visual Organization & Innovative Interaction

Beyond “where is the file?”, Zexor also focuses on **how files are handled, organized, and viewed according to your own workflow**.

* **FastCopy-level high-speed copying and moving**: Optimize transfers for both large files and large numbers of small files, with real-time transfer progress.
* **Checkbox-based grouping**: Select Name, Type, Date, Size, and other grouping criteria directly beside the sorting controls, and instantly group the file list accordingly.
* **Smart folder organization**: Automatically classify and organize messy folders according to rules such as time, date, and file type.
* **Quick Access bar**: Pin frequently used applications and high-frequency work directories based on your usage habits.
* **Custom folder styling**: Change folder colors, use a selected image or video as the folder cover, and add custom tags and categories.
* **Tags and categories in the directory tree**: Display custom tags directly in the directory tree, turning navigation into a personal organization system as well.
* **Inline subfolder expansion**: Expand subfolders directly in the current view instead of repeatedly entering and going back.
* **Scroll-wheel view switching**: Smoothly switch between list, large-icon, and other viewing modes with the mouse wheel.
* **Single-click icon actions**: Quickly preview, launch, or enter a directory with a single click.
* **Double-click the file body to open**: Open files using their default system-associated application, preserving familiar Windows behavior.

> **In one sentence: Zexor is not only about handling files faster — it also lets you organize, classify, and present them according to the way you work.**


https://github.com/user-attachments/assets/91721074-86b8-4823-b429-81425a6cd1f8

> **集成即时预览与独创 `.zex` 格式的下一代可视化文件管理器。（压缩包直接运行）**

## 核心特性

- **直接预览**：原生支持视频、图片与 3D 模型等资源的高性能实时预览。
- **独创 `.zex` 容器格式**：
  - **告别海量碎片文件**：将包含数万个文件的游戏和软件压缩为单一 `.zex` 文件，并且直接运行，极大优化管理效率。
  - **媒体单文件聚合**：视频、图片库可压缩为单个 `.zex` 文件，**支持免解压即时打开与预览**。
- **人性化交互**：弃用繁杂的传统文件操作，提供更优雅、直觉化的操作界面与浏览逻辑。

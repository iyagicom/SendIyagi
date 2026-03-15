# SendIyagi v1.4.2

A **lightweight, fast P2P file transfer and chat app** for Windows.

Send files or folders directly to another PC — no cloud, no account, no size limit.

---

## ✨ Features

### File Transfer
* **P2P direct transfer** — files go directly between PCs over TCP, no relay server
* **Drag & drop** — drop files or folders into the list instantly
* **Folder transfer** — entire folder trees transferred with structure preserved
* **Multiple receivers** — multiple clients can download simultaneously
* **Real-time speed** — live transfer speed shown during every transfer
* **Auto-retry** — receiver automatically retries on connection failure

### HTTP Transfer
* **HTTP upload server** — receive files from any browser or HTTP client (chunked, resume-capable)
* **HTTP uploader** — upload large files in chunks with resume support
* **Upload key** — optional password to protect the HTTP receive server

### Network
* **LAN auto-discovery** — detects SendIyagi devices on the same network automatically
* **One-click connect** — click a discovered device to auto-fill its IP
* **UPnP port mapping** — opens router ports automatically for internet transfers
* **External IP display** — view and copy your external IP directly in the app

### Chat
* **Text & image chat** — exchange messages and images alongside file transfers
* **Up to 20 participants** — supports up to 20 simultaneous connections
* **Unread badge** — unread message count shown on the Chat tab
* **Custom background** — right-click to change chat background color

### General
* **Korean / English UI** — UI language switches automatically based on OS locale

---

## 🚀 How to Use

### Sending (Server tab)

1. Drag files/folders into the list, or click **Add Files** / **Add Folder**
2. Check the port number (default: 4567)
3. Click **Wait for Receiver** — transfer starts automatically when the peer connects
4. Share your **Local IP** (same network) or **Ext IP** (internet) with the receiver

### Receiving (Client tab)

1. Enter the sender's IP and port — or click a device in the LAN scan list
2. Select a save folder, then click **Connect**
3. Select files from the list, then click **Download**

### HTTP Transfer

- **Server tab** — set a save folder and optional upload key in the HTTP section. The HTTP server starts automatically on port+2.
- **Client tab** — enter the server URL and key, drag files in, then click **Upload**.

### Chat

After connecting, switch to the **Chat** tab to send messages and images in real time.

---

## ⬇ Download

Download the latest installer from the [Releases](../../releases) page.

* Windows 10 / 11 (64-bit)

---

## 👤 Author

IYAGI INC
Email: [iyagicom@gmail.com](mailto:iyagicom@gmail.com)
GitHub: https://github.com/iyagicom

---

## 📜 License

Copyright (c) 2026 IYAGI INC. All rights reserved.

This software is provided as **executable files only**. Source code is not publicly available.

You may use this software for personal and non-commercial purposes.
Redistribution, modification, or reverse engineering is prohibited without explicit written permission from the author.

# SendIyagi(센드이야기)

**같은 네트워크의 PC끼리 파일을 빠르게 주고받는 P2P 파일 전송 앱입니다.**
**A fast P2P file transfer app for PCs on the same network.**

---

## 주요 기능 / Features

### 파일 전송 / File Transfer

- **드래그 앤 드롭** — 파일·폴더를 목록에 바로 끌어다 놓기
  **Drag & drop** — drop files and folders directly into the list
- **폴더 구조 유지** — 폴더째 전송 시 하위 구조 그대로 보존
  **Folder structure preserved** — subfolders transferred as-is
- **다중 동시 수신** — 여러 클라이언트가 동시에 받기 가능
  **Multiple simultaneous receivers** — multiple clients can download at once
- **속도 표시** — 실시간 전송 속도 표시
  **Real-time speed display** — live transfer speed shown during transfer
- **자동 재시도** — 받기 연결 실패 시 자동으로 재시도
  **Auto-retry** — automatically retries on connection failure

### HTTP 전송 / HTTP Transfer

- **HTTP 업로드 수신** — 브라우저 호환 청크 업로드 수신 (port+2 자동 개방)
  **HTTP upload receiver** — browser-compatible chunked file receive (auto port+2)
- **HTTP 업로드 클라이언트** — 청크 분할 업로드 및 이어올리기 지원
  **HTTP uploader** — chunked upload with resume support
- **업로드 키** — 선택적 패스워드로 수신 서버 보호
  **Upload key** — optional password to protect the receive server

### LAN 자동 탐색 / LAN Auto-Discovery

- **자동 기기 탐색** — 같은 네트워크의 SendIyagi 기기를 자동으로 감지
  **Auto device scan** — detects SendIyagi devices on the same network automatically
- **클릭으로 자동 입력** — 탐색된 기기를 클릭하면 IP가 자동 입력
  **One-click connect** — click a discovered device to auto-fill its IP

### UPnP / 외부 연결 / Internet Transfer

- **UPnP 포트 자동 개방** — 공유기 설정 없이 외부 네트워크 연결 지원
  **UPnP auto port mapping** — connect over the internet without router configuration
- **외부 IP 표시** — 외부 IP를 앱에서 바로 확인 및 클립보드 복사
  **External IP display** — view and copy your external IP directly from the app
- **3포트 UPnP** — 파일·채팅·HTTP 포트 각각 별도 UPnP 매핑
  **Triple UPnP** — separate UPnP mapping for file, chat, and HTTP ports

### 채팅 / Chat

- **텍스트 채팅** — 연결된 상대와 실시간 채팅
  **Text chat** — real-time chat with connected peers
- **이미지 공유** — 채팅 창에 이미지 전송 및 클릭으로 확대 보기
  **Image sharing** — send images in chat, click to zoom
- **최대 20명** — 동시에 최대 20명 연결 지원
  **Up to 20 participants** — supports up to 20 simultaneous connections
- **안읽은 메시지 배지** — 다른 탭에 있을 때 채팅 탭에 미읽음 수 표시
  **Unread badge** — unread message count shown on the Chat tab
- **배경색 커스텀** — 우클릭으로 채팅 배경색 변경
  **Custom background** — right-click to change chat background color

### 기타 / General

- **한국어/영어 자동 전환** — OS 언어에 따라 UI 자동 전환
  **Korean/English auto-switch** — UI language follows the OS locale
- **IP 클립보드 복사** — 내부·외부·UPnP IP를 클릭 한 번으로 복사
  **One-click IP copy** — click any IP to copy it to the clipboard

---

## 다운로드 / Download

[Releases](../../releases) 페이지에서 최신 설치 파일을 받을 수 있습니다.
Download the latest installer from the [Releases](../../releases) page.

- Windows 10/11 (64-bit)

---

## 사용 방법 / How to Use

### 보내기 (Server 탭) / Sending (Server tab)

1. 파일·폴더를 목록에 드래그하거나 [파일 추가] / [폴더 추가] 클릭
   Drag files/folders into the list, or click **Add Files** / **Add Folder**
2. 포트 번호 확인 (기본값: 4567)
   Check the port number (default: 4567)
3. [전송 대기] 클릭 → 상대방이 접속하면 자동으로 전송 시작
   Click **Wait for Receiver** → transfer starts automatically when the peer connects

### 받기 (Client 탭) / Receiving (Client tab)

1. 보내는 쪽의 IP와 포트 입력 (LAN이라면 자동 탐색 목록에서 클릭)
   Enter the sender's IP and port (or click a device in the LAN scan list)
2. 저장 폴더 선택 후 [서버 접속] 클릭
   Select a save folder, then click **Connect**
3. 파일 목록에서 원하는 파일 선택 후 [받기] 클릭
   Select files from the list, then click **Download**

### HTTP 전송 / HTTP Transfer

- **Server 탭** 하단 HTTP 설정에서 수신 폴더와 업로드 키를 설정하면 HTTP 서버가 자동 시작됩니다.
  Set the save folder and upload key in the HTTP section of the Server tab — the HTTP server starts automatically.
- **Client 탭** 에서 서버 URL과 키를 입력하고 파일을 드래그하여 업로드합니다.
  In the Client tab, enter the server URL and key, then drag files to upload.

### 채팅 / Chat

- 파일 전송 연결 후 Chat 탭에서 바로 메시지 및 이미지를 주고받을 수 있습니다.
  After connecting, switch to the Chat tab to send messages and images.

---

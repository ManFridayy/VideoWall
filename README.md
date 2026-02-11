# VideoWall

<p align="center">
  <img src="AppIcons/appstore.png" width="160" alt="VideoWall app icon" />
</p>

<p align="center">
  A lightweight menu bar app that plays videos as your macOS wallpaper.
</p>

<p align="center">
  <a href="https://github.com/ManFridayy/VideoWall/releases/latest">Download</a> ·
  <a href="#usage">Usage</a> ·
  <a href="#build-from-source">Build from source</a> ·
  <a href="#faq">FAQ</a> ·
  <a href="#ภาษาไทย">ภาษาไทย</a>
</p>

![Latest Release](https://img.shields.io/github/v/release/ManFridayy/VideoWall) ![Platform](https://img.shields.io/badge/platform-macOS-black?logo=apple&logoColor=white) ![Swift](https://img.shields.io/badge/Swift-SwiftUI%20%2B%20AVFoundation-F05138?logo=swift&logoColor=white)

## Features

- **Video wallpaper**: Plays local videos supported by macOS / AVFoundation (e.g. MP4, MOV).
- **Multiple displays**: One wallpaper per monitor, automatically follows screen changes.
- **Playback modes**:
  - **Loop**: Play your playlist continuously.
  - **Shuffle**: Randomize videos (optionally switch by interval or when a video ends).
  - **Time of Day**: Assign different videos for Morning / Afternoon / Evening / Night.
- **Audio control**: Mute/unmute.
- **Launch at login**: Starts automatically after you sign in.
- **Updates**: Manual “Check for Updates” via GitHub Releases.

## Requirements

- macOS 15.6 or later (current build target)

## Download

1. Download the latest build from the [Releases](https://github.com/ManFridayy/VideoWall/releases) page.
2. Unzip and move `VideoWall.app` to `/Applications`.
3. Open VideoWall (it runs in the menu bar).

> If macOS blocks the app on first launch, right‑click `VideoWall.app` → **Open**.

## Usage

1. Open **Settings…** from the menu bar icon.
2. In **Videos**:
   - Add videos for **Loop/Shuffle**, or
   - Assign videos for **Time of Day**.
3. In **Playback**, choose a mode and click **Start**.

## Build from source

```bash
git clone https://github.com/ManFridayy/VideoWall.git
cd VideoWall
open VideoWall.xcodeproj
```

Build & Run in Xcode (you may need to pick a signing team).

## FAQ

- **Videos stopped working after moving/renaming files**: go to **Settings → System → Reset access**, then re-add the videos.
- **Want it to start automatically**: enable **Launch at login**.
- **High CPU / battery usage**: try lower-resolution videos, shorter clips, or disable audio.

## Contributing

Issues and PRs are welcome. Please include your macOS version and clear steps to reproduce.

---

## ภาษาไทย

VideoWall คือแอปเมนูบาร์สำหรับ macOS ที่ช่วยเล่นวิดีโอเป็นวอลเปเปอร์ของเดสก์ท็อป รองรับหลายหน้าจอ เพลย์ลิสต์ และการตั้งค่าตามช่วงเวลาของวัน

### คุณสมบัติเด่น

- **วิดีโอวอลเปเปอร์**: เล่นวิดีโอจากไฟล์ในเครื่อง (รองรับตามความสามารถของ macOS/AVFoundation เช่น MP4, MOV)
- **รองรับหลายจอ**: แยกวอลเปเปอร์ต่อจอ และปรับตามการต่อ/ถอดจออัตโนมัติ
- **โหมดการเล่น**:
  - **Loop (วนซ้ำ)**: เล่นตามรายการวนไปเรื่อยๆ
  - **Shuffle (สุ่ม)**: สุ่มเล่นวิดีโอ (ตั้งให้เปลี่ยนตามเวลา หรือเปลี่ยนเมื่อจบคลิปได้)
  - **Time of Day (ตามเวลา)**: ตั้งคลิปสำหรับ เช้า / บ่าย / เย็น / กลางคืน
- **ควบคุมเสียง**: ปิด/เปิดเสียง
- **เริ่มทำงานอัตโนมัติ**: Launch at login
- **อัปเดต**: กดตรวจสอบเวอร์ชันใหม่ได้จากหน้า About (ผ่าน GitHub Releases)

### ความต้องการระบบ

- macOS 15.6 หรือใหม่กว่า (ตาม build target ปัจจุบัน)

### ดาวน์โหลดและติดตั้ง

1. ดาวน์โหลดจากหน้า [Releases](https://github.com/ManFridayy/VideoWall/releases)
2. แตกไฟล์และย้าย `VideoWall.app` ไปที่ `/Applications`
3. เปิด VideoWall (แอปจะทำงานบน menu bar)

> ถ้า macOS บล็อกการเปิดครั้งแรก ให้คลิกขวาที่ `VideoWall.app` → **Open**

### วิธีใช้งาน

1. กดไอคอนบน menu bar แล้วเลือก **Settings…**
2. ที่แท็บ **Videos**:
   - เพิ่มวิดีโอสำหรับโหมด **Loop/Shuffle** หรือ
   - เลือกวิดีโอแยกตามช่วงเวลาในโหมด **Time of Day**
3. ที่แท็บ **Playback** เลือกโหมด แล้วกด **Start**

### สร้างจากซอร์ส (Build from source)

```bash
git clone https://github.com/ManFridayy/VideoWall.git
cd VideoWall
open VideoWall.xcodeproj
```

จากนั้น Build & Run ใน Xcode (อาจต้องเลือกทีมสำหรับ signing)

### คำถามที่พบบ่อย

- **ย้าย/เปลี่ยนชื่อไฟล์แล้ววิดีโอไม่เล่น**: ไปที่ **Settings → System → Reset access** แล้วเพิ่มวิดีโอใหม่
- **อยากให้เริ่มทำงานเองหลังเปิดเครื่อง**: เปิด **Launch at login**
- **กิน CPU/แบต**: ลองใช้วิดีโอความละเอียดต่ำลง/คลิปสั้นลง หรือปิดเสียง

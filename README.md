[DOWNLOAD FILE](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/ArtoriasphereOrg/Yasai/raw/main/YasaiPlayer.js) (File.js)

- **Yasai script injection**: `<script src="https://cdn.jsdelivr.net/gh/ArtoriasphereOrg/Yasai@main/YasaiPlayer.js"></script>`

# Yasai EN

Yasai is a lightweight HTTP live streaming player implemented in JavaScript. Despite employing obfuscation for enhanced security, it remains efficient and fast.

## Manual

- **Browser Support**: `YasaiLivePlayer.SUPPORTMYPLAYERORNOT` returns `true` or `false` for compatibility.

### Methods

- **create player**: `var ele = new YasaiLivePlayer();` Initializes a new player instance.

- **add_elementvid(element)**: Attaches the video element to the player.

- **remove_elementvid()**: Detaches the video element from the player.

- **givesource(file)**: Provides the video source file (`m3u8`, or any compatible format).

- **yasaion(events, callback)**: Sets event listeners for specified events.

### Event List

- `yasaiMediaAdded`: Triggered when media is added to the player.
- `yasaiMediaRemoved`: Fired upon removal of media from the player.
- `ysaiSegAppending`: Indicates the initiation of segment appending.
- `yasaiSegFlushing`: Signifies the flushing of segments.
- `yasaiSegFlushed`: Fired after segments are flushed.
- `yasaiSegParsingInit`: Marks the initialization of segment parsing.
- `yasaiEr`: Handles errors encountered during playback.

Yasai offers a comprehensive toolkit for managing HTTP live streaming in JavaScript, ensuring smooth integration and reliable performance.

# -------- --------- >>>

# Yasai TH - Translate

Yasai เป็นเครื่องเล่น HTTP live streaming ที่มีน้ำหนักเบาที่สร้างด้วย JavaScript แม้จะใช้เทคนิคการทำให้โค้ดลักษณะหลอกเพื่อเพิ่มความปลอดภัย แต่มันยังคงมีประสิทธิภาพและเร็ว

## คู่มือ

- **การสนับสนุน Browser**: `YasaiLivePlayer.SUPPORTMYPLAYERORNOT` จะคืนค่า `true` หรือ `false` เพื่อตรวจสอบความเข้ากันได้

### เมธอด

- **สร้างเครื่องเล่น**: `var ele = new YasaiLivePlayer();` สร้างตัวเล่นใหม่

- **add_elementvid(element)**: เพิ่มอิลิเมนต์วิดีโอเข้ากับเครื่องเล่น

- **remove_elementvid()**: ลบอิลิเมนต์วิดีโอออกจากเครื่องเล่น

- **givesource(file)**: ระบุแหล่งข้อมูลวิดีโอ (`m3u8`, หรือรูปแบบที่เข้ากันได้)

- **yasaion(events, callback)**: ตั้งค่าฟังก์ชันสำหรับฟังเหตุการณ์ที่กำหนด

### รายการเหตุการณ์

- `yasaiMediaAdded`: เกิดขึ้นเมื่อมีสื่อถูกเพิ่มเข้าไปในเครื่องเล่น
- `yasaiMediaRemoved`: เกิดขึ้นเมื่อมีการลบสื่อออกจากเครื่องเล่น
- `ysaiSegAppending`: แสดงถึงการเริ่มต้นการเพิ่มส่วน
- `yasaiSegFlushing`: แสดงถึงการล้างส่วน
- `yasaiSegFlushed`: เกิดขึ้นหลังจากที่ส่วนถูกล้าง
- `yasaiSegParsingInit`: บ่งชี้ถึงการเริ่มต้นการวิเคราะห์ส่วน
- `yasaiEr`: จัดการกับข้อผิดพลาดที่เกิดขึ้นในระหว่างการเล่น

Yasai ให้เครื่องมือที่ครอบคลุมสำหรับการจัดการ HTTP live streaming ใน JavaScript ที่มีการผสมรวมอย่างดีและประสิทธิภาพที่เชื่อถือได้

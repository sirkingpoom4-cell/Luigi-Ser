# Tesaro

ศูนย์รวมความบันเทิงสำหรับเบราว์เซอร์ของ Tesla โทนม่วงอวกาศ ใช้งานแบบ Netflix / Android TV

เปิดใช้งาน: https://sirkingpoom4-cell.github.io/Luigi-Ser/

- **หนัง:** หนังสั้นและสารคดีรถดูฟรีในแอป, เปิดวิดีโอจาก USB, ทางลัดบริการสตรีมมิ่ง, SmartTube (เครื่องเล่น YouTube เต็มจอในแอป)
- **เพลง:** วิทยุออนไลน์ SomaFM, เล่นไฟล์เพลงจาก USB พร้อมปกอัลบั้ม, ทางลัดบริการเพลง, มินิเพลเยอร์ทุกหน้า
- **เกม:** EmulatorJS 4.2.3 ฝังในเว็บ (`play/`) รองรับ PSP, PS1, N64, NDS, GBA, SNES, NES, Mega Drive, Game Boy; PS2 เปิดผ่าน Play! (playjs.purei.org)
- **แผนที่:** ค้นหา (Nominatim), เส้นทาง (OSRM), นำทางทีละจุดพร้อมเสียงไทย
- **แอป:** ทางลัดพร้อมโลโก้ เพิ่ม/ลบได้

`index.html` เป็นไฟล์เดียว มี Leaflet และ jsmediatags ฝังอยู่ `play/` ใช้ coi-serviceworker เพื่อเปิด SharedArrayBuffer ให้ PSP
ไฟล์เกมต้องเป็นของผู้ใช้เอง

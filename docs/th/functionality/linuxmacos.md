# Wallpaper Engine บน Linux Mac หรือ Android

ปัจจุบัน Wallpaper Engine นั้นมีเฉพาะสำหรับ Windows และไม่มีแผนที่จะสนับสนุนแพลตฟอร์มอื่น ๆ ในอนาคตอันใกล้

เราเข้าใจว่าผู้ใช้ต้องการให้เราสนับสนุนระบบปฏิบัติการมากขึ้น แต่ก็ไม่ใช่เรื่องง่าย Wallpaper Engine มีหัวใจหลักเป็นโซลูชันซอฟต์แวร์ที่เขียนขึ้นเองโดยสมบูรณ์และการย้ายไปยังแพลตฟอร์มอื่น ๆ ถือเป็นงานที่ยิ่งใหญ่

ผู้ใช้บางคนอาจสงสัยว่าทำไมนักพัฒนาเกมและแอพพลิเคชันบางตัวจึงสามารถเชื่อมต่อกับ Mac และ Linux ได้อย่างง่ายดาย คำตอบคือเกมและแอพพลิเคชันเหล่านี้มีพื้นฐานมาจากซอฟต์แวร์เพื่อใช้สร้างวิดีโอเกมที่ใช้กันอย่างแพร่หลาย เช่น Unity หรือ Unreal Engine ซึ่งนักพัฒนาไม่จำเป็นต้องทำงานมากมายเพื่อเพิ่มการสนับสนุนแพลตฟอร์มอื่น ๆ แต่แอพพลิเคชันสำหรับผู้ใช้อย่าง Wallpaper Engine ไม่เป็นเช่นนั้น เนื่องจากเป็นแอพพลิเคชันที่มีการทำงานโต้ตอบอย่างใกล้ชิดกับระบบปฏิบัติการจึงจำเป็นต้องได้รับการปรับแต่งให้เหมาะกับระบบปฏิบัติการแต่ละระบบเพื่อให้ทำงานได้อย่างถูกต้อง สำหรับ Linux นั้นถือเป็นความท้าทายยิ่งใหญ่ โปรแกรมต้องทำงานร่วมกับเครื่องมือจัดการหน้าจอที่ได้รับความนิยมทั้งหมดซึ่งมีความแตกต่างกันอย่างมากในรุ่นต่าง ๆ

แม้ว่าสิ่งเหล่านี้จะเป็นไปได้ในทางทฤษฎี แต่ความเป็นจริงแล้วการเพิ่มการรองรับสำหรับ Linux หรือ Mac OS ณ จุดนี้ยังเป็นไปไม่ได้ในแง่ของเศรษฐกิจ หากคุณตรวจสอบ [แบบสำรวจฮาร์ดแวร์ของ Steam](https://store.steampowered.com/hwsurvey) คุณจะพบว่ามีผู้ใช้ Linux ใน Steam ไม่ถึง 1% และผู้ใช้เหล่านี้ยังต้องถูกแบ่งย่อยออกเป็น Linux ประเภทต่าง ๆ ส่วนใหญ่เป็น Ubuntu และจำนวนบัญชีผู้ใช้คิดเป็นเพียง 0.25% ของจำนวนผู้ใช้ Steam ทั้งหมด

ตามที่อธิบายไว้ข้างต้น การย้าย Wallpaper Engine ไปยังระบบปฏิบัติการอื่นนั้นใช้เวลามากและยังเพิ่มค่าใช้จ่ายในการบำรุงรักษาอย่างต่อเนื่องโดยที่มีกลุ่มผู้ใช้เพียงจำนวนน้อยที่อาจได้รับประโยชน์ เราต้องการที่จะทุ่มเทเวลาและพลังงานของเราในการปรับปรุงเวอร์ชัน Windows สำหรับผู้ใช้ Steam ที่มีมากกว่า 96%

อย่างไรก็ตามเรากำลังเฝ้าดูสถิติของ Steam อย่างเป็นทางการและหากสถานการณ์ใน Steam เปลี่ยนไป เราจะเริ่มพิจารณาวิธีการสนับสนุนแพลตฟอร์มเพิ่มเติมอย่างแน่นอนหากเป็นไปได้ในอนาคต 
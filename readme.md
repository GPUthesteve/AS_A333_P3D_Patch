#Aerosoft A330 FDE Patch and sound improvements

English ver.

in this FDE Patch, I give you `"A330-343.air"` airfile and `"aircraft_patch.txt"` source patch config file
Improvements :
- Fuel Consumption : Two-Tank A330 could do some Long-haul but not with aerosoft's. its just too fuel guzzler so I fixed it.
- Flight Model : Vastly improved drag model, it doesn't rocket climb at full load, but it doesn't perform like a rock as well. (for me, the aerosoft one does perform like a rock.)
	also, improved flaps drag model by simply using real flaps detent angle then adjust its aerodynamics, now this flies like heavier a321, i'd say

installation :
1. backup your original aircraft.cfg (by copypasta it and name it something else like aircraft_orig.cfg)
2. in `"aircraft.cfg"`, the one which you didnt rename, you're gonna patch it with given `"aircraft_patch.txt"` by
	2.1 replace everything inside `aircraft.cfg` with texts in `aircraft_patch.txt.` now you've patched the config, great.
	2.2 then, you take `[fltsim]` section, aka liveries, back to your `"patched"` config from your backup (to restore your liveries. of course!)
3. now replace your `"A330-343.air"` with given one, back up on your discretion, I suggest don't since old fde flies like shit.


#Sound Enhancement
aside FDE patch, I also ship you sound enhancement.

installation
1. navigate to `SimObjects\Airplanes\Aerosoft A330 Professional Base`, you'd see a folder named `sound_asc`, make a backup by simply renaming it to sth else (can skip if don't want to backup, who would?)
2. replace that folder with given `sound_asc` (copy-paste the folder, replace contents if asked, of course). 


แปลไทยแล้วครับ 

สิ่งที่ปรับแก้
- อัตราการกินน้ำมัน : แม้ว่า A330 ตัวที่เขาทำมา เป็นแบบใช้น้ำมัน 2 ถัง (ปีกซ้ายขวาหลัก กับ ถังปรับสมดุล ทำไรไม่ได้นอกจากปรับ CG) แต่อัตราการกินน้ำมัน เมื่อเทียบกับ Dispatch software แล้ว พบว่า กินน้ำมันกว่าที่คำนวณไว้อย่างมาก (เกินความเป็นจริง) 
จนแทบจะเป็นเครื่องไว้บิน Domestic อยู่แล้ว ซึ่ง ผมแก้ให้แล้วครับ อย่างน้อย เครื่องควรจะบินตรงจากโรงงาน Toulouse กลับไทยได้โดยไม่มีปัญหาใดๆ (แต่เดิมบินไม่ถึง แม้จะเผื่อน้ำมันเป็นสิบๆ ตันก็เถอะ) 
- Drag Model (แปลยังไง มันเป็นภาษาทางการ) : มีรายงานมาว่า ช่วงวางระดับ (cruise) เครื่องไม่สามารถทำความเร็วได้เนื่องจากความบกพร่องของ Flight Model (พบว่า drag มากเกินไป ไม่สัมพันธ์กับกำลังเครื่อง) ตอนนี้แก้ไขเรียบร้อยแล้ว สามารถบินทำความเร็วได้ตามปกติ ที่ Mach 0.8 

วิธีลง
1. เข้าไปหา `"aircraft.cfg"` ในโฟลเดอร์ของตัวเครื่องบิน (จำไม่ผิด น่าจะ `Aerosoft A333 RR Professional` อะไรนี่แหละ) จากนั้น เอาส่วนที่ท่านลงลายเครื่องต่างๆ (จากนี้จะเรียกว่า ส่วน[fltsim.x] หากสังเกตดีๆ จะเริ่มจาก [fltsim.0] ไปเรื่อยๆ)
ให้ ลาก-กอปตั้งแต่ [fltsim.0] ไปเรื่อยๆ มีกี่ลายก็ลากไป แล้วเอาไปไว้ที่ text editor ไฟล์อื่น
2. กลับไปที่ `aircraft_patch.txt.` เอาทุกอย่างไปแปะแทนใน `"aircraft.cfg"` เดิมๆ เมื่อสักครู่ แล้วค่อยเอา [fltsim.x] ที่เก็บไว้ ไปแปะตาม จะบรรทัดแรกสุดหรือท้ายสุดของไฟล์ก็ได้
3. กลับไปเอาไฟล์ที่ชื่อว่า `"A330-343.air"` มาแปะแทนของเดิม (หรือจะสำรองของเดิมไว้ก็ได้ ไว้เผื่อเปรียบเทียบความแตกต่าง) เป็นอันเสร็จ

เสียงเพิ่มเติม
คุณภาพชีวิต นอกจาก flight model ผมยังให้ "ระบบเสียงบรรยากาศสำหรับ Aerosoft" (ก็มันเรียกแบบนี้)
เพียงไปหาโฟลเดอร์ `Aerosoft A330 Professional Base` อยู่ข้างๆโฟลเดอร์หลักของตัวเครื่องเมื่อสักครู่ เข้าไป จะเจอ Sub-Folder ที่ชื่อว่า `sound_asc` ให้เอาของที่ให้มา ไปแทนที่ได้เลย

บินให้สนุก แล้วเจอกันใน IVAO ครับ



	
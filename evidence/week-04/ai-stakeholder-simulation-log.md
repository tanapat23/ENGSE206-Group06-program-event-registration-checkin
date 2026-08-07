# AI Stakeholder Simulation Log — Week 04

> Simulation evidence only; not approved real-world facts.

## Session Register

| Session | Role | Prompt/role pack | Interviewers | Start/end | Evidence IDs |
|---|---|---|---|---|---|
| S-01 | Check-in Staff (Operational) | `role-packs/06-program-event-registration-checkin.md` — Role 2 | ธนภัทร ชัยทอง | 07/08/2026 | E-01, E-02, E-03, E-04 |
| S-02 | Data Admin (Technical/Privacy/Safety) | `role-packs/06-program-event-registration-checkin.md` — Role 4 | ธนภัทร ชัยทอง | 07/08/2026 | E-05, E-06, E-07, E-08 |
| S-03 | Participant (Primary User) | `role-packs/06-program-event-registration-checkin.md` — Role 1 | ธนภัทร ชัยทอง | 07/08/2026 | E-09, E-10, E-11, E-12, E-13 |
| S-04 | Organizer (Policy/Manager) | `role-packs/06-program-event-registration-checkin.md` — Role 3 | ธนภัทร ชัยทอง | 07/08/2026 | E-14, E-15, E-16 |

## Session Notes

### S-01 — Check-in Staff

- **Opening/consent stated:** แจ้งว่าเป็นการจำลองเพื่อซ้อมเก็บ evidence ไม่ใช้ข้อมูลบุคคลจริง
- **Questions asked:** ขั้นตอนเช็กอินหน้าโต๊ะปัจจุบัน / ปัญหาที่เจอบ่อย / กรณีอินเทอร์เน็ตขัดข้อง / ความเร็วเช็กอิน vs การยืนยันตัวตน อะไรสำคัญกว่า / ข้อมูลขั้นต่ำที่ต้องขอ
- **Summary:** เช็กอินปกติเร็วถ้าคนไม่เยอะ แต่ walk-in และรายชื่อซ้ำทำให้ช้า อินเทอร์เน็ตล่มเป็นความเสี่ยงที่ยังไม่มีแผนสำรอง ให้น้ำหนักความเร็วมากกว่าตอนคนเยอะ ยกเว้นกิจกรรมที่ออกใบรับรองต้องยืนยันตัวตนรัดกุมกว่า
- **Role knowledge/authority boundary:** ตอบได้เฉพาะประสบการณ์ปฏิบัติงานหน้าโต๊ะ ไม่มีอำนาจกำหนดนโยบายข้อมูล/ระยะเวลาเก็บ
- **Contradictions/open questions:** ยังไม่มีแผนสำรองกรณีเน็ตล่ม (E-04 = OQ)
- **Possible hallucination/bias:** คำตอบอาจ "สมเหตุสมผลเกินจริง" เพราะ AI แต่งเหตุการณ์ตาม Hidden Scenario ที่กำหนดไว้แล้ว ไม่ใช่เหตุการณ์จริงของหลักสูตรใด

### S-02 — Data Admin

- **Opening/consent stated:** แจ้งจุดประสงค์เดียวกับ S-01 คนละ session เพื่อไม่ให้ความรู้ข้ามบทบาท
- **Questions asked:** ควรเก็บข้อมูลอะไรบ้าง / มีนโยบายเก็บข้อมูลนานแค่ไหน / ความเสี่ยงถ้าเช็กอินเร็วข้อมูลน้อย / กรณีขอแก้ชื่อหลังงาน / มุมมองการสมดุลความเร็วกับความถูกต้อง
- **Summary:** ยึดหลัก data minimization เก็บเฉพาะที่จำเป็น ไม่ทราบนโยบาย retention ที่เป็นทางการ กังวลเรื่องยืนยันตัวตนไม่ได้ถ้าข้อมูลน้อยเกินไป เสนอแบ่ง 2 ระดับตามประเภทกิจกรรมเพื่อคลี่คลาย conflict กับ Check-in Staff
- **Role knowledge/authority boundary:** ตอบได้เฉพาะมุมมองการดูแลข้อมูล ไม่ทราบนโยบายที่เป็นทางการของหลักสูตร (ยอมรับตรงๆ ว่าต้องถามอาจารย์ต่อ)
- **Contradictions/open questions:** นโยบาย retention ยังไม่มีคำตอบ (E-07 = OQ) — สอดคล้องกับ pattern ที่เจอใน Week 3 ว่านโยบายทางการหลายเรื่องยังไม่มีใครยืนยัน
- **Possible hallucination/bias:** ข้อเสนอ "แบ่ง 2 ระดับ" เป็นการสังเคราะห์ที่สมเหตุสมผลของ AI ไม่ใช่นโยบายที่มีอยู่จริง ต้องถือเป็น Proposed Solution (PS) ไม่ใช่ Requirement ที่อนุมัติแล้ว

### S-03 — Participant

- **Opening/consent stated:** แจ้งจุดประสงค์เดียวกัน คนละ session จาก S-01/S-02 เพื่อไม่ให้รู้คำตอบข้ามบทบาท
- **Questions asked:** ขั้นตอนลงทะเบียนปัจจุบัน / ปัญหาที่เจอตอนเช็กอิน / อยากได้หลักฐานอะไรหลังเข้าร่วม / อยากรู้อะไรเมื่อที่นั่งเต็ม / อยากยกเลิกยังไง
- **Summary:** ไม่มั่นใจว่าลงทะเบียนสำเร็จเพราะไม่มี confirmation, เคยลืมโทรศัพท์เช็กอินแล้ววุ่นวาย (สอดคล้องกับที่ Check-in Staff เล่าใน S-01 คนละมุม), อยากได้หลักฐานการเข้าร่วมเก็บไว้เอง, อยากเห็นลำดับคิวสำรอง, อยากยกเลิกได้เองผ่านระบบ
- **Role knowledge/authority boundary:** ตอบได้เฉพาะประสบการณ์ผู้เข้าร่วม ไม่มีอำนาจเรื่องนโยบาย
- **Contradictions/open questions:** ไม่มีข้อขัดแย้งกับ session อื่น — กลับเป็นการ**ยืนยันซ้ำ** (corroborate) ปัญหาเรื่องลืมโทรศัพท์จากอีกมุมหนึ่ง
- **Possible hallucination/bias:** คำตอบอาจสะท้อนความคาดหวังทั่วไปของผู้ใช้งานแอปทั่วไป (เช่น อยาก self-service ทุกอย่าง) มากกว่าพฤติกรรมจริงของนักศึกษาในบริบทนี้

### S-04 — Organizer

- **Opening/consent stated:** แจ้งจุดประสงค์เดียวกัน คนละ session จาก 3 session ก่อนหน้า
- **Questions asked:** ใครมีสิทธิ์เลื่อนรายชื่อสำรอง / กิจกรรมแบบไหนต้องยืนยันตัวตนเข้มงวด / เกณฑ์เวลาสาย-ออกก่อนมีมาตรฐานหรือยัง / มีนโยบายเก็บข้อมูลนานแค่ไหนไหม
- **Summary:** ยืนยันว่าผู้จัดกิจกรรมตัดสินใจเลื่อนคิวแต่ต้องเรียงตามลำดับเวลาและมีคนยืนยันก่อนเสมอ (ไม่ใช่ auto เต็มรูปแบบ), ยืนยันแนวคิดแบ่ง 2 ระดับตามประเภทกิจกรรม, เสนอให้เกณฑ์เวลาตั้งค่าได้ต่อกิจกรรม, ปฏิเสธว่าไม่มีอำนาจเรื่องนโยบายเก็บข้อมูล (ส่งต่อให้ Data Admin/อาจารย์)
- **Role knowledge/authority boundary:** เป็น role เดียวใน 4 role ที่มีอำนาจ "กำหนดกฎกิจกรรม" ตาม role pack จึงตอบคำถามเชิงนโยบายได้ตรงกว่า role อื่น แต่ยังคงเป็น simulation ไม่ใช่ผู้จัดกิจกรรมจริง
- **Contradictions/open questions:** ไม่ขัดแย้งกับ S-01/S-02 — กลับ**ยืนยันและช่วยตัดสินใจ** conflict C-01 ให้ชัดขึ้น
- **Possible hallucination/bias:** คำตอบเรื่อง "อยากให้ตั้งค่าได้ต่อกิจกรรม" เป็นข้อเสนอที่ AI สังเคราะห์อย่างสมเหตุสมผล ไม่ใช่นโยบายที่มีอยู่จริง ต้องตรวจสอบซ้ำ

## Human Verification Summary

- **Case facts checked:** ทุกคำตอบเทียบกับ Constraint ใน Case Card แล้ว ไม่มีข้อมูลใดขัดกับ "ใช้ QR/รหัสจำลอง" หรือ "คำนึงถึงความเป็นส่วนตัว"
- **Statements kept as simulation:** ทั้งหมด (E-01 ถึง E-16) — ยังไม่มีข้อความใดถูกยกระดับเป็น fact ที่ยืนยันแล้ว แม้แต่คำตอบจาก Organizer ที่มี "อำนาจ" ในบทบาทก็ยังนับเป็น simulation
- **Statements rejected/revised:** ไม่มีข้อความที่ต้องตัดทิ้ง แต่ E-05/E-14 (ข้อเสนอแบ่ง 2 ระดับ, semi-automatic promotion) ถูกจัดเป็น "Proposed Solution/Constraint" ไม่ใช่ requirement ที่อนุมัติ เพื่อกันไม่ให้ทีมรีบเชื่อว่าถูกต้องแล้ว
- **Follow-up for Week 05:** ยืนยันเกณฑ์แบ่งประเภทกิจกรรม (RC-01), นโยบาย retention ข้อมูล (E-07), เกณฑ์เวลาสาย/ออกก่อนแบบตั้งค่าต่อกิจกรรม (E-16) กับผู้จัดกิจกรรม/อาจารย์ผู้ดูแลหลักสูตรตัวจริง — ครบทั้ง 4 บทบาทแล้ว (Primary User, Operational, Policy/Manager, Technical/Privacy/Safety) ตามที่ checklist ของสัปดาห์กำหนด

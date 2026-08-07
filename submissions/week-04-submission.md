# Week 04 Submission — AI Stakeholder Panel, Evidence and Negotiation

## 1. Assignment

| Field | Value |
|---|---|
| Assignment ID | `W04-v2.0` |
| Course URL/version read | https://github.com/se-rmutl/engse206-lab-v2/blob/main/weeks/week-04-stakeholder-simulation-negotiation/README.md |
| Case/Role Pack | Case 06 — `role-packs/06-program-event-registration-checkin.md` (Role 2: Check-in Staff, Role 4: Data Admin) |
| Date checked | 07/08/2026 |

## 2. Artefacts

| Artefact | Path/URL | Owner | Status |
|---|---|---|---|
| Simulation Log | `evidence/week-04/ai-stakeholder-simulation-log.md` | ธนภัทร ชัยทอง | Complete |
| Evidence/Conflict/RC | `docs/04-evidence-log.md` | ธนภัทร ชัยทอง | Complete |
| Workshop Minutes | `evidence/week-04/workshop-minutes.md` | ธนภัทร ชัยทอง | Complete |
| Risk/Issue Log | `project-management/risk-and-issue-log.md` | ธนภัทร ชัยทอง | Complete |
| Decision Log | `project-management/decision-log.md` | ธนภัทร ชัยทอง | Complete |
| Work/AI Logs | `project-management/team-worklog.md`, `project-management/ai-use-log.md` | ธนภัทร ชัยทอง | Complete |

## 3. Metrics and Quality Check

| Check | Value |
|---|---|
| Number of roles/sessions | 4 (Check-in Staff, Data Admin, Participant, Organizer — ครบ 4 หมวดตาม weekly checklist) |
| Number of E-IDs | 16 (E-01–E-16) |
| Conflicts negotiated | 1 (C-01), status Provisional — เสริมความเชื่อมั่นโดย Organizer (role ที่มีอำนาจ) |
| Requirement candidates | 12 (RC-01–RC-12) |

- [x] each role uses a separate session
- [x] every evidence has source/tag/context/confidence/follow-up
- [x] conflict includes authority, interests, options and status/rationale
- [x] RCs cite E-IDs and do not claim real-world approval
- [ ] no PII/confidential data; AI use and human review are recorded — รอผู้ใช้ยืนยันขั้นสุดท้ายก่อน commit

## 4. Team Contribution

| Member | Role/work | Commit/file evidence |
|---|---|---|
| ธนภัทร ชัยทอง | ดำเนินการ AI stakeholder simulation ทั้ง 2 session, ดึง evidence/conflict/requirement candidates, เขียน workshop minutes, อัปเดต risk/decision log | `docs/04-evidence-log.md`, `evidence/week-04/*`, 42d8e08 |

## 5. Tabletop Summary

- **Important evidence:** E-01/E-05/E-15 (ความเร็ว vs ยืนยันตัวตน — ยืนยันตรงกัน 3 role), E-04/E-10 (ความเสี่ยงเน็ตล่ม/ลืมโทรศัพท์ ยืนยันจากทั้งเจ้าหน้าที่และผู้เข้าร่วม), E-07 (นโยบาย retention ยังไม่ยืนยัน), E-14 (ต้อง manual confirm ก่อนเลื่อนคิวสำรอง)
- **Conflict and parties:** C-01 — Check-in Staff (ต้องการความเร็ว) vs Data Admin (ต้องการข้อมูลยืนยันตัวตนเพียงพอ) — Organizer เข้ามาช่วยยืนยันทางออก
- **Options/status/rationale:** เลือก Option C (แบ่ง 2 ระดับตามประเภทกิจกรรม) สถานะ Provisional เพราะทั้ง 3 role ที่เกี่ยวข้องเสนอ/ยืนยันสอดคล้องกันเอง
- **Evidence-linked RC:** RC-01 ถึง RC-12 อ้าง E-ID ทุกข้อ ไม่มีข้อใดอ้างว่าอนุมัติแล้ว
- **Unresolved issue/Week 05 verification:** เกณฑ์แบ่งประเภทกิจกรรม (RC-01), นโยบาย retention ข้อมูล (E-07), เกณฑ์เวลาสาย/ออกก่อนแบบตั้งค่าต่อกิจกรรม (E-16) — สัมภาษณ์ครบ 4 บทบาทแล้วตาม weekly checklist

## 6. Final Snapshot

| Field | Value |
|---|---|
| Commit | `submit(w04): stakeholder evidence negotiation and candidates` |
| Commit hash/time | `42d8e08` / 07/08/2026 |
| Known limitations/open questions | ทุก RC เป็น Candidate/Provisional ยังไม่ผ่านการยืนยันจากผู้จัดกิจกรรม/อาจารย์จริง; ยังไม่ได้สัมภาษณ์บทบาท Organizer และ Participant (Role 1, 3); นโยบาย data retention ยังไม่มีคำตอบ |

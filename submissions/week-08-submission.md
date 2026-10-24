# Week 08 Submission — SRS Validation, Traceability and Change

## 1. Assignment Source

| Field | Value |
|---|---|
| Assignment ID | `W08-v1.0` |
| Course assignment URL | https://github.com/se-rmutl/engse206-lab/blob/main/weeks/week-08-srs-validation-traceability/assignment-contract.md |
| Course version/commit read | `main` (ไม่พบ commit hash ที่บันทึกไว้) |
| Date checked | ไม่ปรากฏในบันทึกที่ตรวจสอบ |
| Case ID / Case URL | Case 10 — ระบบแจ้งปัญหาพื้นที่ส่วนกลางและติดตามการแก้ไข (https://github.com/1Poirot/ENGSE206-Cases10-common-area-issue-reporting.md) |

## 2. Artefacts Submitted

ผลลัพธ์หลัก: **Reviewed SRS + Traceability + Baseline**

Expected paths: `docs/08-validation-traceability.md`, `docs/requirements-change-log.md`, `final/midterm-snapshot/`, `submissions/week-08-submission.md`

| Artefact | Repository path / URL | Owner | Status |
|---|---|---|---|
| Validation Plan, Quality Checklist, Traceability Matrix, Change Request Log และ Baseline Decision | `docs/08-validation-traceability.md` | นนทชัย ไทยตัน (ผู้รับผิดชอบสัปดาห์ตาม `project-management/weekly-status.md`) | Done |
| Requirements Change Log | `docs/requirements-change-log.md` | ทีม Group 10 | Done; สรุป CR-01–CR-03 และ OQ-01 |
| Midterm requirements snapshot | `final/midterm-snapshot/` | ทีม Group 10 | Done; 4 source files copied from recorded midterm commit |

## 3. Evidence and Quality Check

- [x] มี source files ที่แก้ไขได้สำหรับ validation, change log และ snapshot
- [x] ไม่มี diagram ใหม่ที่ต้องส่งใน deliverable นี้
- [x] Validation/Traceability เชื่อมโยง requirements และ evidence; มี OQ-01 ที่ระบุ gap ไว้ชัดเจน
- [x] มีบันทึกการทำงาน Week 08 ใน `project-management/team-worklog.md`
- [x] ตรวจ AI use log แล้ว ไม่พบรายการเฉพาะ Week 08
- [x] มี cross-review จาก Week 05 เป็น input; ไม่พบบันทึก instructor feedback เฉพาะ Week 08
- [ ] ยังไม่มีผลตรวจข้อมูลส่วนบุคคล/secret แยกสำหรับ submission นี้

## 4. Team Contribution

| Member | Role / Work completed | Evidence (commit/file) |
|---|---|---|
| นนทชัย ไทยตัน | เพิ่มรายละเอียด Functional Requirements และ Deep Specifications ใน SRS | `docs/07-srs-v1.md`, `project-management/team-worklog.md` |
| ณัฐณิชา ปกแก้ว | ปรับความสอดคล้องของ Requirement Backlog/SRS และปรับรูปแบบเอกสาร | `docs/05-requirement-backlog.md`, `docs/07-srs-v1.md`, `project-management/team-worklog.md` |
| ทีม Group 10 | จัดทำ validation/change management และบันทึก baseline review ตามเอกสาร Week 08 | `docs/08-validation-traceability.md`, `docs/requirements-change-log.md` |

## 5. Tabletop / Review Summary

- สิ่งที่นำเสนอ: Validation Plan, Requirements Quality Checklist, Traceability Matrix, Change Request Log และ Baseline Decision ใน `docs/08-validation-traceability.md`; สรุป CR เพิ่มใน `docs/requirements-change-log.md`
- Feedback ที่ได้รับ: ใช้ข้อเสนอจาก cross-review ใน `evidence/week-05/PeerCross-Review.md` เรื่อง traceability, testability, trigger ของ FR-11, เกณฑ์ NFR-02 และ MoSCoW; ไม่พบบันทึก tabletop/instructor feedback เฉพาะ Week 08
- สิ่งที่แก้ก่อนส่ง: ปรับ SRS และ Backlog ให้สอดคล้องกันตาม worklog, บันทึก CR-01–CR-03 และ OQ-01 และเพิ่ม snapshot ของเอกสารจาก commit สอบกลางภาค

## 6. Final Submission Snapshot

| Field | Value |
|---|---|
| Commit message | `Merge remote-tracking branch 'origin/HEAD'` (ข้อความจริงของ commit ที่อ้างใน submission register) |
| Commit hash | `ea60623` (commit ส่งเดิม; การเติมเอกสารครั้งนี้ยังไม่มี commit) |
| Submitted at | 2026-09-22 (ตาม submission register; ไม่ระบุเวลา) |
| Known limitations / open questions | OQ-01 / FR-CAR-03 ยังต้องยืนยันความเชื่อมโยง E-03 → RC-03, stakeholder และรูปแบบหมายเลขอ้างอิง; ไม่พบบันทึก course commit, วันตรวจคำสั่ง, instructor feedback หรือผลตรวจ secret แยก |

## 7. Revision after Feedback

| Date | Feedback | Change made | New commit |
|---|---|---|---|
| 2026-10-24 | เติม Requirements Change Log และ midterm snapshot ที่ขาด พร้อมปรับ submission ให้บันทึกสถานะครบถ้วน | เพิ่ม CR-01–CR-03, คัดลอกเอกสารจาก midterm commit `50c2146`, อัปเดต status และ open item OQ-01 | ยังไม่มี (working tree changes) |

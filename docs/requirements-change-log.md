# Requirements Change Log

> สรุป change request จาก baseline review; รายละเอียด validation, decision และ assumptions ดูที่ [08-validation-traceability.md](08-validation-traceability.md)

| Date | Change ID | Requirement(s) | Type | Summary | Reason | Impacted Artefacts | Status |
|---|---|---|---|---|---|---|---|
| 2026-08-18 | CR-01 | RC-01–RC-08; E-01–E-08; FR-CAR-01–FR-CAR-08 | Changed | ปรับ Requirement Candidates และ Evidence ให้สอดคล้องกับ Functional Requirements ที่เกี่ยวข้อง | พบความไม่สอดคล้องระหว่าง RC/Evidence กับ FR ระหว่าง baseline review | `docs/04-evidence-log.md`, `docs/04-requirement-candidates.md`, `docs/05-requirement-backlog.md`, `docs/08-validation-traceability.md` | Accepted |
| 2026-08-18 | CR-02 | FR-CAR-09–ISSUE-CAR-03 | Changed | แก้ไขหัวข้อและ trace ให้ตรงกับ RC และ Evidence/Need ที่มีอยู่จริง | ตรวจพบการอ้างอิงไม่สอดคล้องกับ evidence log และ requirement candidates | `docs/04-evidence-log.md`, `docs/04-requirement-candidates.md`, `docs/05-requirement-backlog.md`, `docs/08-validation-traceability.md` | Accepted |
| 2026-08-19 | CR-03 | Requirements และ traceability ที่พบ gap ใน baseline review | Changed | ปรับ requirements และ traceability ตาม Quality & MoSCoW Check ก่อนจัดทำ Baseline v1.0 | ปิดประเด็นด้าน traceability, verifiability, open questions และ rationale ที่พบจาก review | `docs/05-requirement-backlog.md`, `docs/08-validation-traceability.md` | Accepted |

## Baseline

| Field | Value |
|---|---|
| Baseline name | `srs-v1.0` |
| Baseline date | 2026-08-18 |
| Reviewed by | Project Team (ตามบันทึกใน `docs/08-validation-traceability.md`) |

## Remaining Open Item

- **OQ-01 / FR-CAR-03:** ยืนยันว่า E-03 รองรับ RC-03 จริง ระบุ stakeholder ที่เกี่ยวข้อง และตกลงรูปแบบหมายเลขอ้างอิงก่อนถือว่า traceability สมบูรณ์ ดูรายละเอียดใน [08-validation-traceability.md](08-validation-traceability.md).

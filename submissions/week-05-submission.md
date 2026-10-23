# Week 05 Submission — Requirement Analysis and Prioritization

## 1. Assignment Source

| Field | Value |
|---|---|
| Assignment ID | `W05-v1.0` |
| Course assignment URL | https://github.com/se-rmutl/engse206-lab/blob/main/weeks/week-05-requirement-analysis-prioritization/assignment-contract.md |
| Course version/commit read | Week 05 assignment contract, reviewed on 2026-08-11 |
| Date checked | 2026-08-11 |
| Case ID / Case URL | Case 10 — ระบบแจ้งปัญหาพื้นที่ส่วนกลางและติดตามการแก้ไข (`CASE_CARD.md`, `docs/02-stakeholder-context-scope.md`) |

## 2. Artefacts Submitted

ผลลัพธ์หลัก: **Categorized and Prioritized Backlog**

Expected paths: `docs/05-requirement-backlog.md`, `docs/05-open-questions-and-issues.md`, `docs/05-prioritization-rationale.md`, `evidence/week-05/`, `submissions/week-05-submission.md`

| Artefact | Repository path / URL | Owner | Status |
|---|---|---|---|
| Requirement Backlog | `docs/05-requirement-backlog.md` | ณัฐณิชา ปกแก้ว | Done |
| Prioritization Rationale | `docs/05-prioritization-rationale.md` | นนทชัย ไทยตัน | Done |
| Open Questions & Issues | `docs/05-open-questions-and-issues.md` | ภูมิพัฒน์ วงศ์ดาว | Done |
| Peer Cross-Review | `evidence/week-05/PeerCross-Review.md` | ทีม Group 10 | Done |
| Worklog & AI Use Log | `project-management/team-worklog.md`, `project-management/ai-use-log.md` | ทีม Group 10 | Done |

## 3. Evidence and Quality Check

- [x] มี source file ที่แก้ไขได้
- [x] diagram มี `.drawio` และ export `.png`/`.pdf` เมื่อเกี่ยวข้อง
- [x] evidence อ้างอิงกลับไปยัง artefact ได้
- [x] อัปเดต worklog และ AI use log แล้ว
- [x] peer/instructor feedback ถูกบันทึกแล้ว
- [x] ไม่มีข้อมูลส่วนบุคคล/secret

## 4. Team Contribution

| Member | Role / Work completed | Evidence (commit/file) |
|---|---|---|
| นนทชัย ไทยตัน | Requirement analyst / ตรวจสอบหลักฐานและเหตุผลการจัดลำดับความสำคัญ | `docs/05-prioritization-rationale.md`, `docs/05-requirement-backlog.md`, `18875a3` |
| ภูมิพัฒน์ วงศ์ดาว | Documentation reviewer / จัดทำ Open Questions และติดตาม peer review | `docs/05-open-questions-and-issues.md`, `evidence/week-05/PeerCross-Review.md` |
| ณัฐณิชา ปกแก้ว | Backlog owner / จัดทำ Requirement Backlog และสรุป Prioritization | `docs/05-requirement-backlog.md`, `project-management/team-worklog.md`, `18875a3` |

## 5. Tabletop / Review Summary

- สิ่งที่นำเสนอ:
  - Requirement Backlog v0.1 ที่จัดกลุ่มตาม Functional / NFR / Issue
  - ใช้ MoSCoW และจัดลำดับจากค่า Value, Risk, Urgency, Dependency
  - แยก Ready / Needs Follow-up / Hold ให้เห็นความพร้อมสำหรับ Week 06
- Feedback ที่ได้รับ:
  - ต้องชัดเจนว่าข้อกำหนดใดมี evidence ที่ยืนยันจริงและข้อใดยังต้อง follow-up
  - เกณฑ์ความเร่งด่วนใน Safety Risk และสิทธิ์การเข้าถึงข้อมูลต้องยืนยันต่อ stakeholder
  - จำเป็นต้องระบุความชัดเจนของ Open Question และ Priority rationale ในเอกสารให้มากขึ้น
- สิ่งที่แก้ก่อนส่ง:
  - ปรับโครงสร้างเอกสารให้สอดคล้องกับ Evidence / Need Trace
  - ทำให้แต่ละ requirement มี status และ Week06 Use ชัดเจน
  - ระบุ Open Question และ Issue เพื่อป้องกันการยกระดับ requirement ที่ไม่มีหลักฐานเพียงพอ

## 6. Final Submission Snapshot

| Field | Value |
|---|---|
| Commit message | `submit(w05): prioritized requirement backlog` |
| Commit hash | `18875a3` |
| Submitted at | 2026-08-11 |
| Known limitations / open questions | ยังไม่มีหลักฐานยืนยันเกณฑ์ความเร่งด่วนและ Safety Risk, สิทธิ์การเข้าถึงข้อมูล, ช่องทางแจ้งเตือน และค่า usability/performance ที่แน่นอน ต้องยืนยันเพิ่มเติมใน Week 06 |

## 7. Revision after Feedback

| Date | Feedback | Change made | New commit |
|---|---|---|---|
| 2026-08-18 | Peer review พบว่าควรเพิ่มความชัดเจนใน traceability และ Open Question | ปรับปรุง Requirement Backlog และ Validation Traceability ให้สอดคล้องกันมากขึ้น | `ea60623` |

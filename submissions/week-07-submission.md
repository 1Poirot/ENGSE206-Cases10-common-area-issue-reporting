# Week 07 Submission — SRS Authoring Studio

## 1. Assignment Source

| Field | Value |
|---|---|
| Assignment ID | `W07-v1.0` |
| Course assignment URL | https://github.com/se-rmutl/engse206-lab/blob/main/weeks/week-07-srs-authoring/assignment-contract.md |
| Course version/commit read | `main` |
| Date checked | 2026-09-20 |
| Case ID / Case URL | Case 10 — ระบบแจ้งปัญหาพื้นที่ส่วนกลางและติดตามการแก้ไข (https://github.com/1Poirot/ENGSE206-Cases10-common-area-issue-reporting) |

## 2. Artefacts Submitted

ผลลัพธ์หลัก: **SRS Draft v1**

Expected paths: `docs/07-srs-v1.md`, `submissions/week-07-submission.md`

| Artefact | Repository path / URL | Owner | Status |
|---|---|---|---|
| Software Requirements Specification (SRS v1) | `docs/07-srs-v1.md` | ทีม Group 10 | Done |
| Domain Model Diagram | `diagrams/domain-model/domain-model.drawio` | ภูมิพัฒน์ วงศ์ดาว | Done |
| Domain Model Image | `diagrams/domain-model/domain-model.png` | ภูมิพัฒน์ วงศ์ดาว | Done |
| Requirement Backlog (อัปเดตสอดคล้อง) | `docs/05-requirement-backlog.md` | นนทชัย ไทยตัน | Done |
| Week 07 Submission | `submissions/week-07-submission.md` | ภูมิพัฒน์ วงศ์ดาว | Done |

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
| ภูมิพัฒน์ วงศ์ดาว | UX & Evidence Lead / จัดทำเนื้อหาหัวข้อ 5 ถึง 7 ใน SRS v1 และจัดทำ Domain Model Diagram (.drawio และ .png) | `docs/07-srs-v1.md`, `diagrams/domain-model/`, `2ab005a` |
| นนทชัย ไทยตัน | Requirements Lead / ปรับปรุง Requirement Backlog และเพิ่มรายละเอียดข้อกำหนดในเอกสาร SRS v1 | `docs/05-requirement-backlog.md`, `docs/07-srs-v1.md`, `7f2fb05` |
| ณัฐณิชา ปกแก้ว | Team Coordinator / ปรับปรุงวัตถุประสงค์และขอบเขตของระบบในเอกสาร SRS v1 เพื่อความชัดเจน | `docs/07-srs-v1.md`, `6e3cae6` |

## 5. Tabletop / Review Summary

- สิ่งที่นำเสนอ: เอกสาร SRS v1 ฉบับสมบูรณ์ ประกอบด้วย Scope, Functional Requirements (FR-01 ถึง FR-11), Non-Functional Requirements (NFR-01 ถึง NFR-03) และ Domain Model Diagram
- Feedback ที่ได้รับ:
  - เพิ่มความชัดเจนของเงื่อนไขการ Trigger แจ้งเตือนเหตุความปลอดภัย
  - ปรับปรุงการเว้นวรรคและจัดระเบียบหัวข้อให้อ่านง่าย
  - ปรับปรุง Team/Owner field และ Case ID ใน Document Control ให้ถูกต้อง
- สิ่งที่แก้ก่อนส่ง: ปรับระยะเว้นบรรทัด, ตรวจสอบ Traceability เชื่อมโยงกลับไปยัง E-ID ใน Week 04 และอัปเดต Domain Model ให้สอดคล้องกัน

## 6. Final Submission Snapshot

| Field | Value |
|---|---|
| Commit message | `submit(w07): SRS draft v1` |
| Commit hash | `4782ad5` |
| Submitted at | 2026-09-20 22:00 |
| Known limitations / open questions | รายละเอียดบางประเด็นยังต้องรอนำไปแปลงเป็น Design Strategy ใน Week 10 |

## 7. Revision after Feedback

| Date | Feedback | Change made | New commit |
|---|---|---|---|
| 2026-09-22 | ปรับปรุงการจัดรูปแบบและการเว้นบรรทัดใน SRS | ปรับแต่งความสวยงามและการอ่านง่าย | `f46ddc1`, `3ddbf07` |

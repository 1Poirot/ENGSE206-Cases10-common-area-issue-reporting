# Week 11 Submission — Conceptual Architecture

| Field | Value |
|---|---|
| Assignment ID / Version | W11-v1.1 |
| Assignment URL | https://github.com/se-rmutl/engse206-lab/blob/main/weeks/week-11-conceptual-architecture/assignment-contract.md |
| Case ID / URL | Case 10 — https://github.com/1Poirot/ENGSE206-Cases10-common-area-issue-reporting |
| Team | Group 10 |
| Submission commit hash | `580a3eb` |

## Artefact links

| Artefact | Path | สถานะ |
|---|---|---|
| Conceptual Architecture (Markdown) | `design/11-conceptual-architecture.md` | Complete / Detailed Architecture |
| Context diagram (C4 Level 1) | `diagrams/architecture/conceptual-architecture-lv1.drawio` + `.png` | Complete |
| Container diagram (C4 Level 2) | `diagrams/architecture/container-c4-level2.drawio` + `.png` | Complete |
| Design Spine | `design/00-design-spine.md` | Architecture Layers Mapped |
| Evidence: ภาพ Miro Board (Before / After) | `evidence/week-11/miro_before.png`, `evidence/week-11/miro_after.png` | Complete |
| Worklog | `project-management/team-worklog.md` | Up to date |
| AI use log (ถ้าใช้) | `project-management/ai-use-log.md` | Recorded |

## Done checklist

- [x] Context diagram: ระบบ 1 กล่อง + actor ครบ + ระบบภายนอกพร้อมป้าย Core / Extension / TBD
- [x] Container diagram: ทุก container มีชื่อ + [ชนิด · เทคโนโลยี] + หน้าที่; ลูกศรทุกเส้นบอกว่าส่งอะไร
- [x] ตาราง container บอกสภาพแวดล้อม (รันที่ไหน ใครควบคุม) และข้อมูลที่เก็บ
- [x] NFR ทุกข้อชี้ได้ว่ากระทบ container ไหน หรือเป็น TBD; decision card ≤ 3 ใบอ้าง NFR/driver
- [x] ทุกขั้น Build now/Overview ใน Spine เดินผ่าน container ได้ และกติกา D1–D3 อยู่ฝั่ง server
- [x] ใช้ stack อ้างอิง หรือมี decision card เมื่อเปลี่ยน; ไม่มีเทคโนโลยีเกินจำเป็น; ทุกภาพมี .drawio + PNG

## ข้อที่คู่บน Miro ถาม และทีมตอบ

| คำถาม / sticky | ทีมแก้หรือตอบอย่างไร |
|---|---|
| driver ที่ห้ามพลาดของทีม อยู่ container ไหน | อยู่ที่ Core Service Container และ Notification Service เพื่อรับประกัน SLA ในการแจ้งเตือนและการตอบสนองต่อเหตุฉุกเฉิน |
| การแยกเก็บไฟล์ภาพความเสียหายในพื้นที่ส่วนกลาง | จัดการผ่าน Object Storage แยกจากฐานข้อมูลหลักเพื่อประสิทธิภาพในการโหลดและสำรองข้อมูล |

## สิ่งที่ยังไม่แน่ใจ / ต้องการ feedback (1–3 ข้อ)

1. การจัดสรร Connection Pool และการออกแบบ Cache Layer ในระดับ Container เพื่อรองรับการค้นหาประวัติการแจ้งซ่อมในช่วงที่มีผู้ใช้งานแจ้งปัญหาพร้อมกันเป็นจำนวนมาก

## การมีส่วนร่วม

| สมาชิก | ทำส่วนใด (ระบุหัวข้อ/ภาพ) |
|---|---|
| ภูมิพัฒน์ วงศ์ดาว | แนบหลักฐานภาพ Miro Board สถาปัตยกรรมระดับแนวคิด (Before / After) และดูแลความสอดคล้องของเอกสาร Submission |
| ณัฐณิชา ปกแก้ว | ปรับปรุงโครงสร้างสถาปัตยกรรมระดับแนวคิด (Conceptual Architecture) และรายละเอียดชั้นและคอมโพเนนต์ |
| นนทชัย ไทยตัน | ตรวจทานความสอดคล้องระหว่าง NFR กับ Container C4 Level 2 และตรวจสอบสิทธิ์การเข้าถึง |

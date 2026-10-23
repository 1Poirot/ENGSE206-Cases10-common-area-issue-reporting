# Week 04 Submission — AI Stakeholder Panel, Evidence and Negotiation

## 1. Assignment

| Field | Value |
|---|---|
| Assignment ID | `W04-v2.0` |
| Course URL/version read | https://github.com/se-rmutl/engse206-lab/blob/main/weeks/week-04-simulation-evidence-negotiation/assignment-contract.md |
| Case/Role Pack | Case 10 — ระบบแจ้งปัญหาพื้นที่ส่วนกลางและติดตามการแก้ไข |
| Date checked | 2026-08-03 |

## 2. Artefacts

| Artefact | Path/URL | Owner | Status |
|---|---|---|---|
| AI Conversation Excerpt | `evidence/week-04/ai-conversation-excerpt.md` | ภูมิพัฒน์ วงศ์ดาว | Done |
| Requirement Candidates | `docs/04-requirement-candidates.md` | ณัฐณิชา ปกแก้ว | Done |
| Evidence / Conflict / RC | `docs/04-evidence-log.md` | นนทชัย ไทยตัน | Done |
| Negotiation Record | `docs/04-negotiation-record.md` | ภูมิพัฒน์ วงศ์ดาว | Done |
| Decision Log | `project-management/decision-log.md` | นนทชัย ไทยตัน | Done |
| Work / AI Logs | `project-management/team-worklog.md`, `project-management/ai-use-log.md` | ทีม Group 10 | Done |

## 3. Metrics and Quality Check

| Check | Value |
|---|---|
| Number of roles/sessions | 5 roles + 1 summary (6 sessions) |
| Number of E-IDs | 9 (E-01 ถึง E-09) |
| Conflicts negotiated | 4 (C-01 ถึง C-04) |
| Requirement candidates | 8 (RC-01 ถึง RC-08) |

- [x] each role uses a separate session
- [x] every evidence has source/tag/context/confidence/follow-up
- [x] conflict includes authority, interests, options and status/rationale
- [x] RCs cite E-IDs and do not claim real-world approval
- [x] no PII/confidential data; AI use and human review are recorded

## 4. Team Contribution

| Member | Role/work | Commit/file evidence |
|---|---|---|
| นนทชัย ไทยตัน | Requirements Lead / จัดทำ Evidence Log (E-01 ถึง E-09) และ Conflict List | `docs/04-evidence-log.md`, `5880889` |
| ภูมิพัฒน์ วงศ์ดาว | UX & Evidence Lead / จัดทำ AI Conversation Excerpt (6 Sessions) และ Negotiation Record | `evidence/week-04/ai-conversation-excerpt.md`, `docs/04-negotiation-record.md`, `cfa352c` |
| ณัฐณิชา ปกแก้ว | Team Coordinator / จัดทำ Requirement Candidates (RC-01 ถึง RC-08) | `docs/04-requirement-candidates.md`, `ca662cf` |

## 5. Tabletop Summary

- Important evidence: E-01 (ช่องทางเดิมกระจัดกระจาย), E-02 (ข้อมูลจำเป็น: รูปภาพ/สถานที่/ประเภท), E-05 (เหตุด้านความปลอดภัยเร่งด่วน), E-07 (การแจ้งปัญหาซ้ำ)
- Conflict and parties: C-01 ข้อมูลขั้นต่ำ vs ความสะดวก (ผู้แจ้ง vs ช่าง), C-02 การกำหนด Priority (ผู้แจ้ง vs เจ้าหน้าที่/Security), C-03 การจัดการรายการแจ้งซ้ำ, C-04 สิทธิ์การเข้าถึงข้อมูลและ Audit Log
- Options/status/rationale: ยืนยันใช้แบบฟอร์มที่มีรูปภาพและสถานที่ระบุชัดเจน (Provisional B), เจ้าหน้าที่เป็นผู้ประเมิน Priority (Provisional B), ออกแบบระบบรวมเหตุการณ์แจ้งซ้ำ (Provisional B)
- Evidence-linked RC: RC-01 ถึง RC-08 สอดคล้องกับ E-01 ถึง E-09
- Unresolved issue/Week 05 verification: ยืนยันข้อมูลขั้นต่ำจริงกับเจ้าหน้าที่ และเกณฑ์การระบุเหตุการณ์ซ้ำ

## 6. Final Snapshot

| Field | Value |
|---|---|
| Commit | `submit(w04): evidence and requirement candidates` |
| Commit hash/time | `1d178f1` / 2026-08-03 |
| Known limitations/open questions | ผลการจำลองเป็นเพียงข้อสันนิษฐานเบื้องต้น ต้องนำไปยืนยันกับผู้เกี่ยวข้องจริงในขั้นตอนถัดไป |

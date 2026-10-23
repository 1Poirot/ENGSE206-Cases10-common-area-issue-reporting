# 15 — Individual Reflection

> ให้สมาชิกแต่ละคนคัดลอก template นี้เป็นไฟล์ของตนเอง เช่น `15-individual-reflection-student-id.md`

## Student Information

| Field | Detail |
|---|---|
| Student ID | 68543210038-4 |
| Name | นายภูมิพัฒน์ วงศ์ดาว |
| Primary Role(s) | UX & Evidence Lead (prototype / usability / evidence) |

## 1. My Contribution

| สัปดาห์ | กิจกรรมและสิ่งที่ทำจริง | ไฟล์ / หลักฐานที่เกี่ยวข้อง (Artefact / Evidence) | Commit Hash / Link |
|:---:|---|---|---|
| **W01** | กรอกข้อมูล Project Profile เริ่มต้นของกลุ่ม | `docs/00-project-profile.md` | `The information has been entered...` |
| **W02** | จัดทำ Peer Feedback และ Worklog ของ Week 02–03 | `feedback/week-02-peer-feedback.md`, `project-management/week-02-week-03-worklog.md` | `project-management & feedback` |
| **W03** | ร่วมจัดทำและปรับปรุง Interview Guide และข้อคำถามสัมภาษณ์ Stakeholder | `docs/03-interview-guide.md` | `03-interview-guide.md`, `update 03-interview-guide.md` |
| **W04** | จัดทำ Negotiation Record และรวบรวมหลักฐานบทสนทนาจำลองกับ AI ครบ 6 sessions | `docs/04-negotiation-record.md`, `evidence/week-04/ai-conversation-excerpt.md`, `project-management/ai-use-log.md` | `04-negotiation-record`, `cfa352c` |
| **W05** | จัดทำ Prioritization Rationale และอัปเดตสถานะใน Requirement Backlog | `docs/05-prioritization-rationale.md`, `docs/05-requirement-backlog.md` | `upload 05-prioritization-rationale.md`, `update Status` |
| **W05b** | จัดทำแบบฟอร์มตรวจประเมินข้ามทีม (Peer Cross-Review Form) สำหรับล็อก Requirement Baseline v1.0 | `evidence/week-05/baseline-review/peer-cross-review.md`, `evidence/week-05/PeerCross-Review.md` | `PeerCross-Review`, `1425e51` |
| **W06** | จัดทำร่าง Requirement Models ส่วน User Stories, Use Case Overview และ Acceptance Criteria | `docs/06-requirement-models.md` | `docs(06): add sections 1-2`, `aea96e1` |
| **W07** | จัดทำเนื้อหาหัวข้อที่ 5 ถึง 7 ใน SRS v1 พร้อมจัดทำ Domain Model Diagram (.drawio และ .png) | `docs/07-srs-v1.md`, `diagrams/domain-model/domain-model.drawio`, `diagrams/domain-model/domain-model.png` | `docs(07): complete sections 5 to 7`, `2ab005a` |
| **W10** | จัดทำเอกสาร Design Strategy and Rationale และปรับปรุงข้อกำหนดขอบเขต | `design/10-design-strategy.md`, `docs/00-project-profile.md` | `docs(design10): update section and fixs docs(00)`, `ecfb735` |
| **W11** | จัดทำและแนบหลักฐานภาพ Miro Board สถาปัตยกรรมระดับแนวคิด (Before / After) และดูแลเอกสาร Submission | `evidence/week-11/miro_before.png`, `evidence/week-11/miro_after.png`, `submissions/week-11-submission.md` | `docs: add evidence and polish content`, `4722f83` |

---

## 2. What I Learned About Requirements and Design

ได้เรียนรู้กระบวนการวิศวกรรมความต้องการอย่างเป็นระบบ ตั้งแต่การจำลองสัมภาษณ์ Stakeholder เพื่อดึงความต้องการที่แท้จริงออกมา การประนีประนอมข้อขัดแย้ง (Negotiation) ระหว่างความสะดวกของผู้แจ้งกับความครบถ้วนของข้อมูลที่เจ้าหน้าที่ต้องการ การแปลงความต้องการเป็น Use Case และ Domain Model ไปจนถึงการนำ SRS มาต่อยอดเป็น Design Strategy และ Conceptual Architecture (C4 Model) โดยคำนึงถึง Quality Attributes และการจัดทำหลักฐานที่สามารถตรวจสอบย้อนกลับได้ (Traceability) ตลอดวงจรการพัฒนา

---

## 3. A Decision I Influenced

มีส่วนสำคัญในการตัดสินใจเรื่องการจัดลำดับความสำคัญของปัญหา (Prioritization) โดยผลักดันให้ประเด็นความปลอดภัยและความเสี่ยงในพื้นที่ส่วนกลางต้องได้รับการจัดการอย่างเร่งด่วน (Must Have) รวมถึงการออกแบบ Domain Model ใน SRS v1 ให้ครอบคลุมความสัมพันธ์ระหว่างผู้แจ้ง รายการปัญหา การมอบหมายงานเจ้าหน้าที่ และการติดตามสถานะ เพื่อให้ทีมสถาปัตยกรรมและทีมออกแบบ UX นำไปสร้างหน้าจอและ Workflow ได้อย่างไม่ตกหล่น

---

## 4. Feedback I Received and How I Responded

ได้รับข้อเสนอแนะว่าในระยะแรก ข้อกำหนดและคำอธิบายบางส่วนยังกว้างเกินไปและตรวจวัดผลได้ยาก เช่น เรื่องความรวดเร็วในการแก้ปัญหา ได้นำมาปรับปรุงโดยกำหนดเกณฑ์ที่ชัดเจนและจำเพาะเจาะจงมากขึ้น เช่น การระบุชุดข้อมูลขั้นต่ำที่ต้องกรอก (ภาพถ่าย, พิกัดอาคาร/ชั้น/ห้อง) และการกำหนดรายการสถานะการดำเนินงานที่ชัดเจนเพื่อให้สามารถเขียน Test Case และตรวจรับงานได้จริง

---

## 5. What I Would Improve Next Time

หากมีโอกาสทำโครงงานถัดไป จะปรับปรุงเรื่องการวางโครงสร้างและมาตรฐานการตั้งชื่อไฟล์ร่วมกับทีมตั้งแต่เริ่มสัปดาห์แรก เพื่อลดเวลาในการปรับแก้เอกสารย้อนหลัง และจะเริ่มออกแบบ Wireframe / Mockup แบบร่างคู่ขนานไปกับช่วงทำ User Story เพื่อให้ Stakeholder มองเห็นภาพหน้าจอการทำงานได้รวดเร็วยิ่งขึ้น

---

## 6. Evidence Links

- **Commit ประวัติการทำงานบน GitHub:**  
  https://github.com/1Poirot/ENGSE206-Cases10-common-area-issue-reporting/commits/main/?author=Phumipat-2005
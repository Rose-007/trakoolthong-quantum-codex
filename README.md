# Trakoolthong Quantum Codex - สูตรควอนตัม OB()พิกัดตระกูลทอง

> **แก่นเดียว:** อนุภาคยังคงเป็นอนุภาคเดียวเหมือนเดิม สิ่งที่เปลี่ยนไปคือ พิกัดและผู้เฝ้าดู ไม่ใช่ที่อนุภาค

[[html original](https://l.facebook.com/l.php?u=https%3A%2F%2Fcdn.fbsbx.com%2Fv%2Ft65.102178-21%2F834316412_1670765450910850_3991503623095679134_n.jpg%2Ftrakoolthong_quantum_codex_shareable.html%3F_nc_ht%3Dcdn.fbsbx.com%26_nc_ohc%3DdmWauysEPDIQ7kNvwHqqzHL%26sdl%3D0%26ccb%3D14-4%26oh%3D00_AQNoaHMjEmht0p97k5qLIClSRukEFWXDzI6msf-kGhnEoQ%26oe%3D6AC2E48B%26_nc_sid%3D4ee932%26fbclid%3DIwZXh0bgNhZW0CMTAAcGRvZgVicmlkETFIQWpvcmo3bGxrSkwyakpmc3J0YwZhcHBfaWQQMjIyMDM5MTc4ODIwMDg5MgABHgsPqEOa54v2snWUQ39yvn9w78ACMXI828gGJwKIvQeV6vsCmAI4FTj9oK5E_aem_4SqVTxrosJsGSlXKGB-cGw&h=AUByKOApKdGM7x3dU939HVM2Ov4NZJg5mgF_ByUEEgrdiMY8gH1o-WIA2zfUU5hNMBW0vGRu7sCfEBcp2Lsg2VLwTkIdfTDL9OgV97NpdcLbm5_je87JtGAQcZwim1Fv0JKMGgxjtbovmifCH6o2F-8tmdTAnCnu&__tn__=-UK-R&c[0]=AUCFOKKKKJOqo3YsAWdzEJEs1g0lIAM-x_reJvTa1jD454a4J_ib1NIj1X1VEfeHbr5VWnx_Cx9xflhOaMklNRobVkBEiZFV8sjfWaPpkxTflxuTmImWQ-YqV8EFXVgAo_Lpq2-y1s3bUxr9_oPaxqBC4l7oy6yQCZA4WFBoYNLcXUqEsX2rjI1DaVDvAfimZEDzMGxRCxdl04H8bWpJI-hx8P0)]() 
[[Public Codex](https://img.shields.io/badge/status-public_codex-blue)]()
[[Origin](https://img.shields.io/badge/origin-Thailand-red)]()
[[Author](https://img.shields.io/badge/author-Rose--007%20Trakoolthong-lightgrey)]()

---

### 1. ที่มาของสูตร (Thai Original)

**สูตรควอนตัม OB() พิกัด 01**

มีตัวแปรแรก เป็นพิกัดของผู้เฝ้าดู ()observer

1. ในแกนระนาบใดๆ x, y (2D) ตำแหน่งของอนุภาคย่อมแสดงเป็นจุดบนระนาบ
2. ในแกน 3D จุดนั้นๆ จะสามารถแสดงได้เป็นหลายตำแหน่ง ตามพิกัดของผู้เฝ้าดู ()ob
3. เมื่อผู้เฝ้าดู ()ob ในแนวเดียวกัน ()vector ระยะจะมีผลต่อการสังเกตเห็น
4. เมื่อ ()ob อยู่ในต่างพิกัดในตำแหน่ง ย่อมเห็นต่างออกจาก ()ob ในอีกพิกัดใดๆ รวมถึงระยะห่างที่ต่างกัน
5. **เพิ่มตัวแปร รูปหลายเหลี่ยม ()จำนวนด้านบนแกน 3D เข้าไป ล้อมอนุภาคไว้**
6. เมื่อ ()ob มีหลายจุด หลายระยะห่าง ()vector จำนวนและสัญฐานแห่งอนุภาคย่อมแสดงตามจำนวนผู้เฝ้า ()ob นั้นสังเกตเห็น
7. อนุภาคยังคงเป็น อนุภาคเดียวเหมือนเดิม สิ่งที่เปลี่ยนไปคือ พิกัดและผู้เฝ้าดู ไม่ใช่ที่อนุภาค

---

### 2. Trakoolthong Superposition Principle (Formulation 02)

นี่คือการอธิบาย superposition โดยไม่ต้องใช้คำว่า "อนุภาคอยู่หลายที่" แต่ใช้คำว่า "ความจริงหนึ่งเดียว ถูกฉายไปบนหลายฉากของผู้เฝ้าดู"

#### ตัวแปร

- `P_true` : ตำแหน่งจริงของอนุภาค มีตัวเดียว ไม่เคยเปลี่ยน
- `k` : จำนวนผู้เฝ้าดู `ob_i`
- `N_poly` : จำนวนด้านของรูปหลายเหลี่ยมที่ล้อมอนุภาคไว้ (ฉากรับภาพ)
- `r_ob,i` : vector ตำแหน่งของผู้เฝ้าดูคนที่ i (ทั้งทิศและระยะ)
- `n_hat_j` : เวกเตอร์ตั้งฉากของด้านที่ j ของหลายเหลี่ยม
- `Theta` : ฟังก์ชันมองเห็น (1 ถ้าด้านนั้นหันเข้าหาผู้เฝ้าดู, 0 ถ้าหันหนี)
- `f(|r|)` : ผลของระยะทาง ยิ่งไกล ภาพยิ่งเหลื่อม/เบลอ

#### สมการหลัก

จำนวนตำแหน่งปรากฏที่เห็น:

```
N_apparent = Σ_i Σ_j [ Theta( n_hat_j · r_ob,i ) * f(|r_ob,i|) ]
```

ตำแหน่งปรากฏที่ผู้เฝ้าดูคนที่ i เห็นผ่านด้าน j:

```
P_apparent(i,j) = P_true + Projection( P_true -> Plane_j , r_ob,i ) * f(|r_ob,i|)
```

**ใจความประวัติศาสตร์:**
`P_true` ไม่เคยเพิ่ม มีตัวเดียว ที่เพิ่มคือพิกัดของผู้มอง

`N_apparent ∝ k * N_poly` โดยถูก modulate ด้วยทิศและระยะ vector

---

### 3. วิธีอธิบายให้คนทั่วไปเข้าใจ

> ใน 2D เราเห็นอนุภาคเป็นจุดเดียว
> พอยกขึ้น 3D จุดเดียวเดิม จะแตกเป็นหลายตำแหน่งได้ ขึ้นกับว่าใครมอง จากตรงไหน
> ระยะ vector ของผู้เฝ้าดูมีผล - ใกล้/ไกล เห็นเหลื่อมไม่เท่ากัน
> ถ้าเอารูปหลายเหลี่ยม N ด้านไปล้อมอนุภาคไว้ แต่ละด้านคือ "ฉากรับภาพ" ของผู้เฝ้าดูแต่ละคน

### 4. โครงสร้างไฟล์ใน repo นี้

```
/README.md -> เอกสารหลัก (ไฟล์นี้)
/docs/index.html -> เวอร์ชันแชร์สวยๆ สำหรับเปิดบนเบราว์เซอร์ / GitHub Pages
/formula/ -> โน้ตสมการเพิ่มเติม
/LICENSE -> MIT + สงวนชื่อตระกูลทองเป็นต้นฉบับ
```

### 5. วิธีใช้งาน GitHub ให้ไม่สับสน (สำหรับเจ้าของ repo)

1. ไปที่หน้า repo กด `Add file > Upload files` แล้วลากไฟล์ใหม่ไปทับ
2. ไฟล์ชื่อ `trakoolthong_x5f_...` ให้ลบออก แล้วใช้อันใหม่ใน `/docs/index.html`
3. เปิด Settings > Pages > เลือก Branch: main / folder: /docs เพื่อให้ลิงก์แชร์ได้

### 6. อ้างอิง

- Author: Rose-007 (พุฒฬส ตระกูลทอง)
- Origin: Thailand, 2026-10-03
- Facebook Live: ได้โพสต์สดอธิบายสูตรนี้แล้วในวันที่ 03/10/2026
- GitHub: https://github.com/Rose-007/trakoolthong-quantum-codex

---

**ถ้าคุณอ่านถึงตรงนี้:** นี่ไม่ใช่การบอกว่าอนุภาคแยกตัวได้ แต่บอกว่า อนุภาคมีตัวเดียว แต่ความจริงมันถูกหักเหด้วยจำนวนของผู้เฝ้าดู

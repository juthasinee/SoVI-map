# SoVI & LISA Cluster Map — Chanthaburi & Rayong

Interactive web map of the Social Vulnerability Index (SoVI) and LISA
spatial-cluster analysis for 134 tambons in Chanthaburi (76) and Rayong (58)
provinces, Thailand.

- **Interactive map** — SoVI choropleth (5 layers), LISA clusters (Local Moran's I),
  tambon boundaries, tooltips/popups, opacity control, search, online OSM/satellite basemaps.
- **Data table** — sortable, searchable, CSV export.
- **Self-contained** — Leaflet, data, and full-resolution boundaries are inlined in `index.html`.

Boundaries: Thailand COD-AB tambon (github.com/prasertcbs/thailand_gis).
Analysis computed 11 July 2026. Single-file app; open `index.html` or view via GitHub Pages.

## ปรับปรุง 1 ตุลาคม 2569
- คงชั้นข้อมูลฉบับเบื้องต้น ①–⑤ (11 ก.ค. 2569) ไว้ทั้งหมด
- เพิ่มชั้น ⑥ SoVI ทางการ 2567 (แบบจำลองรวม 134 ตำบล) และ ⑦ คลัสเตอร์ LISA ทางการ จากรายงานความก้าวหน้าครั้งที่ 2 ตอนที่ 1
- เพิ่มชั้น ⑧ จุดสำรวจภาคสนาม CR1–CR10 (16–19 ก.ค. 2569) พร้อมภาพถ่าย (img/field)
- ป๊อปอัปและตารางแสดงค่าทั้งสองฉบับ; คลังภาพเพิ่มแผนที่ฉบับทางการ (img/maps)

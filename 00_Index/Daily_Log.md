# CHỈ MỤC NHẬT KÝ LÀM VIỆC (DAILY LOG DIRECTORY)

> **Mục tiêu:** Quản lý và tra cứu tiến trình sáng tác, các quyết định điều chỉnh và lịch sử phát triển dự án theo từng năm.  
> **Quy chuẩn đặt tên tập tin:** `YYYY-MM-DD_short_reason.md` đặt trong thư mục theo năm tương ứng (`logs/daily_log/YYYY/`).

---

## 📅 NĂM 2026
* [[logs/daily_log/2026/2026-10-06_setup_canon_remove_system|2026-10-06: Setup Canon & Remove System]] — Chốt 15/15 Intake, loại bỏ toàn bộ yếu tố game, định vị quê nhà Dầu Tiếng - Bình Dương, cập nhật timeline cuối lớp 11 lên 12, viết hoàn chỉnh Chương 1, 2, 3.
* [[logs/daily_log/2026/2026-10-07_sync_index_modularize_lore|2026-10-07: Sync Index & Modularize Lore]] — Chuẩn hóa 00_Index và 99_Archive, tách nhỏ hệ thống Power System, Places, World Building thành các file chuyên sâu, chuẩn hóa cấu trúc thư mục Outline và đặt tên tiếng Anh.

---

## 🔍 TRUY VẤN TỰ ĐỘNG (DATAVIEW)

```dataview
TABLE file.name AS "Nhật ký", file.mtime AS "Cập nhật lần cuối"
FROM "logs/daily_log"
SORT file.name DESC
```

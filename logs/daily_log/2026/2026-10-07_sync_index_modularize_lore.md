# NHẬT KÝ LÀM VIỆC: 07/10/2026
* **Ngày:** 07/10/2026
* **Chủ đề chính:** Đồng bộ hóa Index, Phân rã Modular Cấu trúc Lore, Tái cấu trúc Outline, Đổi tên toàn bộ File sang Tiếng Anh.
* **Người thực hiện:** Tác giả & Antigravity AI

---

## 1. MỤC TIÊU & BỐI CẢNH
Chuẩn hóa lại các thư mục mới tạo mẫu (`00_Index`, `99_Archive`), phân tách các tập tin tổng hợp lớn thành hệ thống module chuyên sâu, di chuyển các tập tin hiện có vào đúng thư mục con, phân bổ lại cấu trúc thư mục cho `outline/` và chuyển đổi toàn bộ tên tệp/thư mục sang Tiếng Anh chuẩn để thuận tiện cho việc tìm kiếm, tra cứu trên Obsidian và IDE.

---

## 2. CÁC CÔNG VIỆC ĐÃ HOÀN THÀNH

### A. Đồng bộ & Nâng cấp `00_Index` và `99_Archive`:
1. Sửa lỗi chính tả thư mục `00_Index/Tempates/` thành `00_Index/Templates/`.
2. Chuẩn hóa `Templates/chapter.md` (tích hợp Contract, Prose, Checklist 4 câu hỏi vàng, kiểm tra AI Cliché).
3. Chuẩn hóa `Templates/character.md` (đầy đủ 6 mục theo chuẩn hồ sơ Canon).
4. Viết lại `00_Index/MOC.md`, `00_Index/Character.md`, `00_Index/Timeline.md` đầy đủ dữ liệu thực tế và liên kết hai chiều.
5. Thiết lập `99_Archive/README.md` và cơ chế lưu trữ an toàn.

### B. Tái cấu trúc & Phân rã Modular Lore (`canon/`) sang Tiếng Anh:
1. **Di chuyển các tập tin gốc vào thư mục chuyên biệt:**
   - Di chuyển `canon/power_system.md` $\rightarrow$ `canon/power_system/master_power_system.md`.
   - Di chuyển `canon/world_structure.md` $\rightarrow$ `canon/world_building/world_structure.md`.
   - Di chuyển `canon/characters.md` $\rightarrow$ `canon/characters/overview.md`.
2. **Thư mục `canon/power_system/`:**
   - `overview.md`, `master_power_system.md`, `primordial_mana.md`, `earth_mana_core_and_quirks.md`, `void_core_and_combat.md`, `primordia_magic_schools.md`.
3. **Thư mục `canon/places/`:**
   - `geography_overview.md`
   - `earth/dau_tieng_binh_duong.md`, `earth/thu_dau_mot_hcmc.md`
   - `primordia/ruined_metropolis_arc_1.md`, `primordia/steampunk_crawler_federation.md`, `primordia/underwater_city.md`, `primordia/merfolk_island.md`, `primordia/holy_aurelius_empire.md`.
4. **Thư mục `canon/world_building/`:**
   - `world_overview.md`, `world_structure.md`, `great_betrayal_history.md`, `veil_mechanics_and_convergence.md`, `factions_and_institutions.md`.
5. **Thư mục `canon/characters/`:**
   - `overview.md`, `main_actors/`, `supporting/exorcist_squad.md`.

### C. Tái cấu trúc `outline/` thành các Thư mục phù hợp:
Chỉ phân bổ các file hiện có vào đúng tầng cấu trúc:
1. `outline/acts/`:
   - `overview.md` (Đại cương tổng thể dự án)
   - `three_acts.md` (Cấu trúc 3 Hồi)
2. `outline/arcs/`:
   - `arcs_overview.md` (Tổng quan 8 Arc)
   - `arcs_detail.md` (Chi tiết phân bổ 8 Arc)
3. `outline/arcs/arc_01/`:
   - `arc_detail.md` (Kế hoạch 4 giai đoạn Arc 1)
   - `chapter_contracts.md` (Hợp đồng chương 1–12 Arc 1)

### D. Chuẩn hóa Daily Log theo năm (`logs/daily_log/`):
- Phân chia thư mục theo năm: `logs/daily_log/2026/`.
- Tên tệp chuẩn tiếng Anh: `YYYY-MM-DD_short_reason.md`:
  - `2026-10-06_setup_canon_remove_system.md`
  - `2026-10-07_sync_index_modularize_lore.md`

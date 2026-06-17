# ⚒ Prompt Forge

> Lò rèn quặng thô thành **prompt vàng** cho Claude Opus 4.8.

Đưa một ý tưởng thô vào, đi qua 5 bước, nhận về một **master prompt XML** hoàn chỉnh — kèm khối cài đặt model (effort + adaptive thinking + max_tokens) — sẵn sàng dán vào Claude.

**🔗 Dùng ngay:** mở trang deploy (GitHub Pages) hoặc tải `index.html` về **click đúp** là chạy.

---

## Đặc điểm

- **Pure-local · offline 100%** — một file `index.html` tự chứa, vanilla JS. Không API, không key, không build, không phụ thuộc network (trừ 2 web-font tải lần đầu, sau đó cache).
- **Quy trình 5 bước:** Ý tưởng thô → Lĩnh vực → Phỏng vấn ngược → Hợp kim kỹ thuật → Rèn vàng.
- **3 preset lĩnh vực** nạp sẵn vai trò / đối tượng / chuẩn chất lượng: Giáo dục trẻ em · Indie dev · Đa lĩnh vực.
- **Phỏng vấn ngược theo 9 chiều ý định** — engine logic tự sinh câu hỏi, có câu riêng theo lĩnh vực.
- **6 kỹ thuật bật/tắt** (prompt mọc động): Phỏng vấn ngược · Phản biện ác ý · Tư duy hiện (CoT) · Bản đồ quan hệ · Explore→Plan→Verify · Chỉ thị trung thực.
- **Effort stack Opus 4.8** (medium → max) + độ dài đầu ra; khối setting tự suy luận adaptive thinking & max_tokens.
- **Thanh "Độ vàng"** chấm điểm prompt theo độ đầy đủ thông tin + số kỹ thuật.
- **Tự lưu nháp** (localStorage) — đóng tab không mất việc.

## Cách dùng

1. Đi qua 5 bước, bấm **Rèn prompt vàng**.
2. **Sao chép prompt** → dán vào Claude Opus 4.8 (web/Code), đặt effort như ghi chú ở đầu.
3. Lặp 2–3 vòng tinh luyện (bật *Phản biện ác ý* để Claude tự đập rồi nâng cấp).

## Công nghệ

HTML + CSS + vanilla JavaScript thuần. Không framework, không bước build. Font: Inter (Google Fonts) + Helvetica Now Display Bold (chỉ cho logo/số).

## Nguồn chưng cất

Framework tổng hợp từ Anthropic Docs, các thảo luận Prompt Engineering trên X, Reddit r/ClaudeAI, và playbook cộng đồng Opus 4.8.

---

*Pure-local. Dữ liệu của bạn không rời khỏi máy.*

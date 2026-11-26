# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 06
- **Họ tên:**Tạ Hà Việt
- **Lớp:**CNTT2
- **Link repository Pha2:**https://github.com/haviet982008-netizen/HN-KS26-CNTT2_PromptAI_H02_Pha1_Pha2
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):**ChatGPT

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt bàn ra JSON

**KET QUA AI**

```text
[
  {
    "ma_buffet": "NUONG",
    "ngay_dat": "2026-12-19",
    "nguoi_lon": 2,
    "tre_em": 1,
    "khu_vuc": "trong_nha",
    "ghi_chu": null
  },
  {
    "ma_buffet": "HAISAN",
    "ngay_dat": "2027-01-03",
    "nguoi_lon": 3,
    "tre_em": 0,
    "khu_vuc": null,
    "ghi_chu": "Một người dị ứng sữa"
  },
  {
    "ma_buffet": "LAU",
    "ngay_dat": "2026-12-25",
    "nguoi_lon": 4,
    "tre_em": 0,
    "khu_vuc": "san_vuon",
    "ghi_chu": "Ông ngoại đi xe lăn"
  }
]
```

**Link trò chuyện:**https://chatgpt.com/share/6b079de3-3ea8-83ec-b245-dbf7b4cc983b

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
1. **Tiền người lớn** — 10 × 399.000 = 3.990.000 đồng
2. **Tiền trẻ em** — 3 × (399.000 × 50%) + 1 × 0 = 598.500 đồng
3. **Tiền buffet** — 3.990.000 + 598.500 = 4.588.500 đồng
4. **Giảm giá đoàn** — 4.588.500 × 5% = 229.425 đồng
5. **Phụ thu phòng riêng** — 1 × 500.000 = 500.000 đồng
6. **Tổng tiền** — 4.588.500 − 229.425 + 500.000 = 4.859.075 đồng

[RESULT: 4.859.075 đồng]
```

**Link trò chuyện:**https://chatgpt.com/share/6b079e4c-c9ec-83ec-a0e0-a0e9ecea3c4d

### b) Kiểm tra kết quả AI

Đúng

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "thieu_mon",
  "so_khach": 5,
  "so_mon_bi_thieu": 2,
  "tom_tat": "Gia đình 5 người không được phục vụ tôm hùm và cua như quảng cáo."
}
```

**Link trò chuyện:**https://chatgpt.com/share/6b079ec1-94c8-83ec-b44e-f60808dd89ab

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
| Tiêu chí | Điểm | Minh chứng | Đề xuất sửa |
|---|---:|---|---|
| Đúng thông tin | 0/5 | Báo giá 279.000 đồng và hứa giữ bàn khi khách trễ 40 phút. Cả hai đều sai quy định. | Báo giá 299.000 đồng/người lớn và giải thích rằng nhà hàng hủy bàn nếu khách đến trễ trên 30 phút. |
| Đầy đủ | 2/3 | Đề cập cả giá và việc giữ bàn, nhưng chỉ nói “Có gì nhắn em nhé” mà chưa hỏi thông tin đặt bàn. | Mời khách cung cấp ngày, giờ đến và số khách. |
| Giọng điệu | 1/2 | Có lời chào và xưng hô lịch sự, nhưng “ngon bá cháy” và cách dùng “nha” lặp lại khiến câu trả lời thiếu chuyên nghiệp. | Dùng cách diễn đạt lịch sự, rõ ràng và kết câu bằng “ạ” khi phù hợp. |
| **Tổng điểm** | **3/10** | | |
```

**Link trò chuyện:**https://chatgpt.com/share/6b079f22-6a34-83ec-aa39-b9eaf47e218b

# AI LOG – BUỔI 7, TIẾT 3

## Thông tin sinh viên

- Họ và tên: [ Trần Trung Kiên ]
- Mã sinh viên – Lớp: [ 2071060011 – CNTT 20-02 ]
- Ngày thực hiện: [ 30/10/2026 ]
- Link repository: [ https://github.com/kiendzww/K20_Portfolio_CNTT20_02.git ]
- URL website: [ https://kiendzww.github.io/K20_Portfolio_CNTT20_02/ ]
- Tình huống: [x] Website của tôi  [ ] Repo luyện của giảng viên

## 1. Nhận định của tôi trước khi hỏi AI

- Trang/thao tác gặp lỗi: [ Mở trang Portfolio ]
- Mong muốn và hiện tượng thực tế: [ Muốn trang có giao diện đẹp, nhưng CSS không hiển thị ]
- Dữ kiện đã kiểm tra (cấu trúc tệp, Request URL, Status…): [ HTML và ảnh vẫn hiện; chưa kiểm tra Status ]
- Tôi nghi nguyên nhân là: [ Liên kết đến CSS bị sai ]
- Vì sao tôi nhận định như vậy: [ Trang có nội dung nhưng không có định dạng ]

## 2. Tôi hỏi AI và nhận được gợi ý

- Nguồn: [x] Công cụ AI: [ GitHub Copilot ]  [ ] Phản hồi mẫu của giảng viên
- Câu hỏi/prompt tôi đã gửi (hoặc tình huống của phản hồi mẫu):

  [ Tôi có URL [https://kiendzww.github.io/K20_Portfolio_CNTT20_02/].Tôi dự đoán [lỗi css].
Hãy nêu giả thuyết, dữ kiện cần kiểm tra và bản sửa tối thiểu.
Chỉ tư vấn, không sửa tệp. Không kết luận đã sửa thành công. ]

- Gợi ý chính của AI:

  [ Thay đường dẫn href ở dòng 10 bằng đường dẫn tương đối: <link rel="stylesheet" href="css/style.css" /> ]

## 3. Quyết định của tôi

- [x] Chấp nhận gợi ý
- [ ] Chỉnh sửa gợi ý rồi áp dụng
- [ ] Bác bỏ gợi ý

- Tôi quyết định làm gì: [ Sửa đường dẫn CSS trong HTML ]
- Lý do, dựa trên dữ kiện nào: [ Web hiện HTML nhưng mất định dạng ]

## 4. Thực hiện và kiểm chứng

- Tệp/vị trí đã sửa (không sửa thì ghi rõ): [ index.html ]
- Nội dung thay đổi hoặc cách xử lý khác: [ Sửa đường dẫn trong thẻ link CSS ]
- Commit của bản sửa, nếu có: [ Chưa commit ]
- Bản sửa đã deploy: [x] Có  [ ] Chưa  [ ] Không phát sinh bản sửa

| Nội dung kiểm tra | Trước xử lý | Sau xử lý/thử lại |
| --- | --- | --- |
| Request URL và Status của tài nguyên liên quan | CSS không tải | CSS tải thành công |
| Giao diện/chức năng trên URL website | Mất định dạng, ảnh to | Hiển thị đúng bố cục |

- Cách thử lại và kết quả thực tế: [ Tải lại bằng Ctrl + F5, giao diện bình thường ]
- Căn cứ để đối chiếu (URL tệp, commit, đường dẫn ảnh chụp hoặc dữ kiện quan sát): [ Giao diện trước và sau khi sửa ]

## 5. Kết luận

- [x] Đã xử lý được  [ ] Xử lý được một phần  [ ] Chưa xử lý được
- Điều tôi rút ra hoặc việc cần làm tiếp: [ kiểm tra lại trước khi deploy ]

---

*Tệp là minh chứng MC2 để nhận định mức đạt của tiết học; không tính điểm MC2 riêng. Nếu có tình huống khác, sao chép mục 1–5 để ghi thêm.*

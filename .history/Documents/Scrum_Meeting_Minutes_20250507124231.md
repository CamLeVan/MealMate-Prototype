# Biên bản họp Scrum - Dự án MealMate

## Thông tin chung
- **Dự án:** MealMate - Ứng dụng lập kế hoạch bữa ăn cá nhân hóa
- **Thời gian thực hiện:** 17/04/2025 - 24/04/2025
- **Phương pháp quản lý:** Scrum (3 Sprint)
- **Trường:** Đại học công nghệ thông tin và truyền thông Việt-Hàn (VKU)
- **Môn học:** Công nghệ Phần mềm

## Thành viên nhóm
| Vai trò            | Tên             | Trách nhiệm                     |
|---------------------|-----------------|---------------------------------|
| Product Owner (PO)  | Ngô Huỳnh Lộc    | Định nghĩa yêu cầu, quản lý backlog |
| Scrum Master (SM)   | Lê Văn Cảm       | Điều phối quy trình Scrum      |
| Developer (Dev)     | Phạm Mai Gia Huy | Thiết kế logic AI và màn hình UI |
| Developer (Dev)     | Hoàng Văn Quyến  | Thiết kế UX và giao diện frontend |

## Sprint 1 (17/04 - 19/04)
### Thông tin Sprint
- **Thời gian thực hiện:** 17/04/2025 - 19/04/2025
- **Mục tiêu Sprint:** Hoàn thiện chức năng nhập và lưu trữ hồ sơ người dùng
  - Bao gồm các thông tin: tuổi, giới tính, chiều cao, cân nặng, mục tiêu ăn uống
  - Yêu cầu: Giao diện thân thiện, dễ nhập liệu, dữ liệu được lưu trữ và hiển thị lại khi người dùng truy cập lại

### Tóm tắt các hoạt động chính
| Ngày | Nội dung chính | Link chi tiết |
|------|----------------|---------------|
| 17/04/2025 | Sprint Planning, phân công task | [📄 Sprint_1_Planning] |
| 18/04/2025 | Daily Standup 1 – Cập nhật tiến độ, xử lý vấn đề | [📄 Sprint_1_Daily1] |
| 19/04/2025 | Daily Standup 2, Sprint Review, Retrospective | [📄 Sprint_1_Review_Retro] |

### Kết quả Sprint
| User Story | Nội dung | Trạng thái |
|------------|----------|------------|
| [US01] | Nhập thông tin cá nhân | ✅ Hoàn thành |
| [US02] | Lưu trữ & hiển thị lại hồ sơ người dùng | ✅ Hoàn thành |

### Sprint Planning (17/04 - 09:00)
- **Hình thức:** Trao đổi online qua Zalo + Jira
- **Người tham gia:** Cảm (SM), Lộc (PO), Huy (Dev), Quyến (Dev)

**SM Cảm:**
- Tạo Sprint 1 trên Jira (17-19/04)
- Giao nhiệm vụ cho Dev Huy ([US01]) và Quyến ([US02])
- Soạn biên bản Sprint Planning, lưu nội bộ

**PO Lộc:**
- Viết mô tả mục tiêu Sprint trong phần mô tả Jira

**Dev Huy:**
- Bắt đầu phác thảo form nhập thông tin trên Figma (1 màn hình, input cơ bản)

**Dev Quyến:**
- Khởi tạo logic lưu trữ thông tin người dùng bằng localStorage

### Daily Scrum (18/04 - 08:30)
**Huy:**
- ✅ Hôm qua: Thiết kế UI cơ bản xong
- 🔄 Hôm nay: Thêm lựa chọn giới tính, validate input
- ⚠️ Khó khăn: Chưa có dữ liệu mẫu để test

**Quyến:**
- ✅ Hôm qua: Đã code xong lưu hồ sơ bằng localStorage
- 🔄 Hôm nay: Test dữ liệu
- ⚠️ Khó khăn: Lỗi JSON.stringify với object lồng nhau

**SM Cảm:**
- Ghi nhận trở ngại của Quyến lên Jira
- Hỗ trợ: Gợi ý xử lý lỗi bằng JSON.parse(JSON.stringify(obj))

### Daily Scrum (19/04 - 08:30)
**Huy:**
- ✅ Hoàn thiện form nhập, đã responsive

**Quyến:**
- ✅ Lưu được thông tin, hiển thị lại thành công khi reload

**SM Cảm:**
- Cập nhật tiến độ trên Jira:
  - [US01] → Done
  - [US02] → In Review

### Sprint Review (19/04 - 20:00)
**Dev trình bày:**
- Quyến: Share màn hình trình bày UI form nhập (gọn gàng, dễ hiểu)
- Huy: Demo trên trình duyệt: nhập thông tin → reload → dữ liệu còn nguyên

**PO Lộc phản hồi:**
- UI mượt, hợp lý
- Góp ý: Mục tiêu ăn uống nên đổi từ Dropdown → Radio button để dễ thao tác

### Sprint Retrospective
**Điểm tốt:**
- Phân chia nhiệm vụ rõ ràng theo chuyên môn
- Các Dev chủ động ghi chép tiến độ, cập nhật thường xuyên

**Cần cải thiện:**
- Nên tiến hành test sớm hơn
- Cần pair-programming sớm để giải quyết lỗi nhanh hơn

**Hành động sau Sprint:**
| Thành viên | Nhiệm vụ |
|------------|----------|
| SM Cảm | Tạo Sprint 2 (20–22/04), tổng kết Sprint 1 trên Jira, chia sẻ UI Figma |
| PO Lộc | Nhận xét về UI, đề xuất cải tiến giao diện người dùng |

## Sprint 2 (20/04 - 22/04)
### Thông tin Sprint
- **Thời gian thực hiện:** 20/04/2025 - 22/04/2025
- **Mục tiêu Sprint:** 
  - Hoàn thiện chức năng gợi ý bữa ăn theo hồ sơ người dùng
  - Hiển thị danh sách nguyên liệu từ thực đơn đã chọn

### Tóm tắt các hoạt động chính
| Ngày | Nội dung chính | Link chi tiết |
|------|----------------|---------------|
| 20/04/2025 | Sprint Planning, phân công task | [📄 Sprint_2_Planning] |
| 21/04/2025 | Daily Standup 1 – Cập nhật tiến độ, xử lý vấn đề | [📄 Sprint_2_Daily1] |
| 22/04/2025 | Daily Standup 2, Sprint Review, Retrospective | [📄 Sprint_2_Review_Retro] |

### Kết quả Sprint
| User Story | Nội dung | Trạng thái |
|------------|----------|------------|
| [US03] | Gợi ý bữa ăn | ✅ Hoàn thành |
| [US06] | Hiển thị nguyên liệu | ✅ Hoàn thành |

### Sprint Planning (20/04 - 09:00)
- **Hình thức:** Google Meet
- **Người tham gia:** Cảm (SM), Lộc (PO), Huy (Dev), Quyến (Dev)

**Cảm (SM):**
- ✅ Tạo Sprint 2 trên Jira (20/04 – 22/04)
- ✅ Phân bổ task:
  - [US03] Gợi ý bữa ăn → Huy
  - [US06] Hiển thị nguyên liệu → Quyến
- ✅ Ghi biên bản, đính kèm Jira

**Lộc (PO):**
- ✅ Trình bày yêu cầu:
  - Gợi ý 3 bữa ăn/ngày dựa trên hồ sơ (tuổi, cân nặng, mục tiêu)
  - Hiển thị danh sách nguyên liệu từ thực đơn đã chọn

**Huy (Dev):**
- ✅ Nhận [US03]: Xây dựng logic AI rule-based
- ✅ Phối hợp với Cảm để xác định quy tắc logic

**Quyến (Dev):**
- ✅ Nhận [US06]: Thiết kế UI danh sách nguyên liệu
- ✅ Làm rõ cách hiển thị và đơn vị tính

**Hành động:**
- Cảm: Cập nhật Jira, theo dõi tiến độ
- Huy & Quyến: Thống nhất format dữ liệu đầu ra

### Daily Scrum (21/04 - 08:30)
**Huy:**
- ✅ Hôm qua: Xác định logic rule-based cho AI
- ✅ Hôm nay: Code hàm suggestMeal(profile)
- ⚠️ Chưa rõ cách chuẩn hóa tên món và nhóm nguyên liệu để gửi cho Quyến

**Quyến:**
- ✅ Hôm qua: Dựng khung UI danh sách nguyên liệu
- ✅ Hôm nay: Viết hàm getIngredientsFromMeals()
- ⚠️ Trở ngại: Đợi dữ liệu test từ Huy để tích hợp đúng cấu trúc

**SM Cảm:**
- 🧩 Phát sinh: Gọi meeting ngắn 10:30 để thống nhất format dữ liệu
- 🛠 Hành động:
  - Huy gửi file JSON mẫu (bữa ăn + nguyên liệu + đơn vị)
  - Quyến tích hợp và hiển thị theo format đã thống nhất

### Daily Scrum (22/04 - 08:30)
**Huy:**
- ✅ Hoàn thành hàm suggestMeal()
- ✅ Gợi ý chính xác theo hồ sơ, xử lý cả trường hợp thiếu dữ liệu

**Quyến:**
- ✅ Hiển thị danh sách nguyên liệu tương ứng với thực đơn
- ✅ Giao diện responsive, hoạt động tốt trên cả desktop và mobile

**SM Cảm:**
- 📌 Cập nhật tiến độ trên Jira:
  - [US03] → In Review
  - [US06] → In Progress

### Sprint Review (22/04 - 20:00)
**Dev trình bày:**
- Huy: Demo nhập hồ sơ người dùng → Hệ thống gợi ý 3 bữa ăn phù hợp
- Quyến: Demo hiển thị nguyên liệu theo thực đơn đã chọn, giao diện rõ ràng, có nhóm món ăn và đơn vị tính

**PO Lộc phản hồi:**
- 👍 Logic AI ổn, UI nguyên liệu dễ hiểu

### Sprint Retrospective
**Điểm tốt:**
- Hai Dev phối hợp tốt trong việc xử lý các phụ thuộc
- Format dữ liệu đầu ra được thống nhất sớm nên việc tích hợp nhanh chóng

**Cần cải thiện:**
- Nên thống nhất format input/output sớm hơn để tránh sự cố khi tích hợp

**Hành động sau Sprint:**
| Thành viên | Nhiệm vụ |
|------------|----------|
| SM Cảm | Tạo Sprint 3 (22–25/04), tổng kết Sprint 2 trên Jira, chia sẻ UI Figma |
| PO Lộc | Comment recap về UI + logic AI, cần test thêm nhiều trường hợp đầu vào khác nhau trong giai đoạn dev |

## Sprint 3 (22/04 - 24/04)
### Thông tin Sprint
- **Thời gian thực hiện:** 22/04/2025 - 24/04/2025
- **Mục tiêu Sprint:**
  - Hoàn thiện chức năng lưu trữ lịch ăn hàng tuần
  - Cải thiện chức năng gợi ý món ăn từ nguyên liệu

### Tóm tắt các hoạt động chính
| Ngày | Nội dung chính | Link chi tiết |
|------|----------------|---------------|
| 22/04/2025 | Sprint Planning, phân công task | [📄 Sprint_3_Planning] |
| 23/04/2025 | Daily Standup 1 – Cập nhật tiến độ, xử lý vấn đề | [📄 Sprint_3_Daily1] |
| 24/04/2025 | Daily Standup 2, Sprint Review, Retrospective | [📄 Sprint_3_Review_Retro] |

### Kết quả Sprint
| User Story | Nội dung | Trạng thái |
|------------|----------|------------|
| [US04] | Lưu trữ lịch ăn hàng tuần | ✅ Hoàn thành |
| [US05] | Gợi ý món ăn từ nguyên liệu đã có | ✅ Hoàn thành |

### Sprint Planning (22/04 - 22:00)
- **Hình thức:** Google Meet
- **Người tham gia:** Cảm (SM), Lộc (PO), Huy (Dev), Quyến (Dev)

**Lộc (PO):**
- ✅ Trình bày yêu cầu:
  - [US04]: Lên lịch ăn từng ngày trong tuần, chọn món cho từng bữa (sáng – trưa – tối)
  - [US05]: Nhập nguyên liệu có sẵn → Gợi ý món có thể nấu

**Huy (Dev):**
- ✅ Nhận [US04]: Thiết kế UI chọn lịch ăn theo ngày, tích hợp danh sách món từ [US03]

**Quyến (Dev):**
- ✅ Nhận [US05]: Thiết kế UI nhập nguyên liệu, tích hợp logic gợi ý món

**Cảm (SM):**
- ✅ Tạo Sprint 3 trên Jira (22/04 – 24/04)
- ✅ Gán task, ước lượng:
  - [US04] – 3 Story Points
  - [US05] – 3 Story Points
- ✅ Ghi biên bản, cập nhật backlog, chia sẻ Figma

**Ghi chú:**
- Sprint Goal: Hoàn thiện lập lịch ăn và gợi ý món theo nguyên liệu
- Risk: Lỗi lưu lịch ăn hoặc logic lọc món chưa tối ưu → Cần test kỹ

**Hành động:**
- Cảm: Theo dõi tiến độ, hỗ trợ đồng bộ dữ liệu
- Huy & Quyến: Chuẩn bị tích hợp với dữ liệu từ Sprint trước

### Daily Scrum (23/04 - 08:30)
**Huy:**
- ✅ Hôm qua: Hoàn thành UI chọn lịch ăn từng ngày (dùng dạng kéo ngang)
- 🔄 Hôm nay: Tích hợp chọn món theo ngày và lưu lịch ăn vào LocalStorage
- ⚠️ Trở ngại: Cần danh sách món ăn từ [US03] để liên kết dữ liệu

**Quyến:**
- ✅ Hôm qua: Thiết kế UI nhập nguyên liệu có sẵn
- 🔄 Hôm nay: Bắt đầu viết logic gợi ý món ăn từ nguyên liệu đã nhập
- ⚠️ Trở ngại: Thiếu cấu trúc dữ liệu đầu vào từ suggestMeal() của [US03]

**SM Cảm:**
- 🛠 Hành động:
  - Gửi lại file JSON output mẫu từ [US03] cho Quyến để test
  - Kiểm tra tính tương thích dữ liệu giữa [US03] và [US04]/[US05]

### Daily Scrum (24/04 - 08:30)
**Huy:**
- ✅ Hoàn tất tính năng lên lịch ăn cho cả tuần, giao diện kéo ngang mượt
- ✅ Đã xử lý lưu trữ dữ liệu và đồng bộ UI – dữ liệu tốt

**Quyến:**
- ✅ Đã tích hợp logic đề xuất món ăn từ nguyên liệu
- ✅ Test được nhiều case như: thiếu nguyên liệu, món yêu cầu nguyên liệu không có → cảnh báo rõ ràng

**SM Cảm:**
- 🛠 Cập nhật Jira:
  - [US04] → In Review
  - [US05] → In Review
- Chuẩn bị nội dung cho Sprint Review buổi tối

### Sprint Review (24/04 - 20:00)
**Dev trình bày:**
- Huy:
  - Demo giao diện chọn món ăn theo lịch từng ngày trong tuần
  - Người dùng có thể chọn món cho từng bữa (sáng/trưa/tối), kéo ngang mượt mà
- Quyến:
  - Demo nhập nguyên liệu → Gợi ý danh sách món phù hợp
  - Có hiển thị rõ món nào cần thêm nguyên liệu nào

**PO Lộc phản hồi:**
- UI rõ ràng, dễ thao tác, trải nghiệm mượt
- Logic gợi ý hợp lý và tiện lợi cho người dùng
- 📝 Góp ý: Cần thêm tính năng "lặp lịch ăn mỗi tuần" → đưa vào Backlog

### Sprint Retrospective
**Điểm tốt:**
- Các Dev phối hợp tốt trong việc giải quyết các phụ thuộc giữa các module
- Giao diện UI về lịch ăn hàng tuần và gợi ý món ăn rất dễ sử dụng
- Tính năng lưu trữ lịch ăn hoạt động ổn định, dữ liệu được lưu vào LocalStorage chính xác

**Cần cải thiện:**
- Cần cải thiện tốc độ lọc món ăn khi có danh sách nguyên liệu lớn
- Tính năng lập lịch ăn cho mỗi tuần có thể được tối ưu hơn để dễ dàng chỉnh sửa lịch ăn mỗi ngày

**Hành động sau Sprint:**
| Thành viên | Nhiệm vụ |
|------------|----------|
| SM Cảm | Tạo Sprint 4 (26–29/04), tổng kết Sprint 3 trên Jira, cập nhật backlog |
| PO Lộc | Comment recap về UI + logic AI, cần kiểm tra tính tương thích khi nhập nhiều nguyên liệu khác nhau |

## Tổng kết dự án (25/04/2025)
### Mục tiêu dự án
Phát triển một hệ thống AI Meal Planner giúp người dùng lên lịch ăn uống hàng ngày và gợi ý các món ăn phù hợp với nguyên liệu có sẵn trong kho, từ đó giúp tiết kiệm thời gian và tối ưu hoá bữa ăn.

Dự án bao gồm các tính năng chính:
- Lên lịch ăn cho mỗi ngày trong tuần
- Gợi ý bữa ăn dựa trên hồ sơ người dùng
- Hiển thị danh sách nguyên liệu từ thực đơn đã chọn
- Lưu trữ lịch ăn hàng tuần
- Gợi ý món ăn từ nguyên liệu có sẵn
- Tích hợp với cơ sở dữ liệu thực phẩm thực tế
- Phát triển thuật toán AI thực sự cho việc gợi ý thực đơn

### Kết quả đạt được
- Hoàn thành 6 User Stories trong 3 Sprint
- Tạo được prototype đầy đủ chức năng với 8 màn hình UI
- Mô phỏng thành công dữ liệu bằng JSON
- Phát triển các tính năng chính như:
  - Nhập và lưu trữ hồ sơ người dùng
  - Gợi ý bữa ăn dựa trên hồ sơ
  - Hiển thị danh sách nguyên liệu
  - Lên lịch ăn hàng tuần
  - Gợi ý món ăn từ nguyên liệu
  - Tích hợp với cơ sở dữ liệu thực phẩm

### Bài học kinh nghiệm
- Phương pháp Scrum giúp quản lý dự án hiệu quả
- Style guide và components giúp đảm bảo tính nhất quán trong thiết kế
- Tài liệu hóa quyết định thiết kế và cấu trúc dữ liệu là rất quan trọng
- Nên tiến hành test sớm hơn và pair-programming sớm để giải quyết lỗi nhanh hơn
- Cần thống nhất format input/output sớm hơn để tránh sự cố khi tích hợp

### Hướng phát triển tiếp theo
- Phát triển tính năng xuất kế hoạch ăn uống
- Tích hợp với cơ sở dữ liệu thực phẩm thực tế
- Phát triển thuật toán AI thực sự cho việc gợi ý thực đơn
- Thêm tính năng "lặp lịch ăn mỗi tuần"
- Tối ưu hóa tốc độ lọc món ăn khi có danh sách nguyên liệu lớn
- Tối ưu hóa giao diện lịch ăn hàng tuần

## Tài liệu tham khảo
- [Jira Board](https://lecam1698.atlassian.net/jira/software/projects/SCRUM/list)
- [Figma Design](https://www.figma.com/design/YPCMcJBV2oZaLjwEVujPsS/Untitled?node-id=0-1&p=f&t=1NaPp7elQDUesGDg-0)

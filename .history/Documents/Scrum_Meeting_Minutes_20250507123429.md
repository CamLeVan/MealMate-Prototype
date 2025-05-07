# Biên bản họp Scrum - Dự án MealMate

## Thông tin chung
- **Dự án:** MealMate - Ứng dụng lập kế hoạch bữa ăn cá nhân hóa
- **Thời gian thực hiện:** 17/04/2025 - 24/04/2025
- **Phương pháp quản lý:** Scrum (3 Sprint)

## Thành viên nhóm
| Vai trò            | Tên             | Trách nhiệm                     |
|---------------------|-----------------|---------------------------------|
| Product Owner       | Ngô Huỳnh Lộc    | Định nghĩa yêu cầu, quản lý backlog |
| Scrum Master        | Lê Văn Cảm       | Điều phối quy trình Scrum      |
| Developer (UI)      | Phạm Mai Gia Huy | Thiết kế logic AI và màn hình UI |
| Developer (UX)      | Hoàng Văn Quyến  | Thiết kế UX và giao diện frontend |

## Sprint 1 (17/04 - 19/04)
### Sprint Planning
- **Mục tiêu Sprint:** Hoàn thành chức năng đăng ký, đăng nhập và quản lý hồ sơ cá nhân
- **User Stories:**
  - US01: Đăng ký và Đăng nhập
  - US02: Quản lý Hồ sơ Cá nhân
- **Tasks:**
  - Thiết kế màn hình WelcomeScreen (Phạm Mai Gia Huy)
  - Thiết kế màn hình PersonalInformation (Hoàng Văn Quyến)
  - Thiết kế màn hình ConfirmPersonalInformation (Phạm Mai Gia Huy)
  - Tạo cấu trúc dữ liệu cho thông tin người dùng (Lê Văn Cảm)

### Daily Scrum (Tóm tắt)
#### Ngày 17/04
- **Đã hoàn thành:**
  - Khởi tạo dự án Figma
  - Thảo luận về luồng người dùng
- **Kế hoạch:**
  - Bắt đầu thiết kế màn hình WelcomeScreen
  - Xác định các trường thông tin cần thiết cho hồ sơ người dùng
- **Vấn đề:**
  - Chưa thống nhất về phong cách thiết kế

#### Ngày 18/04
- **Đã hoàn thành:**
  - Hoàn thiện màn hình WelcomeScreen
  - Bắt đầu thiết kế màn hình PersonalInformation
- **Kế hoạch:**
  - Hoàn thiện màn hình PersonalInformation
  - Bắt đầu thiết kế màn hình ConfirmPersonalInformation
- **Vấn đề:**
  - Không có

#### Ngày 19/04
- **Đã hoàn thành:**
  - Hoàn thiện tất cả màn hình cho US01 và US02
  - Tạo cấu trúc dữ liệu cho thông tin người dùng
- **Kế hoạch:**
  - Chuẩn bị cho Sprint Review
- **Vấn đề:**
  - Không có

### Sprint Review
- **Kết quả đạt được:**
  - Hoàn thành 3 màn hình: WelcomeScreen, PersonalInformation, ConfirmPersonalInformation
  - Hoàn thành cấu trúc dữ liệu cho thông tin người dùng
- **Phản hồi từ Product Owner:**
  - Hài lòng với thiết kế giao diện
  - Đề xuất thêm tùy chọn "Mục tiêu dinh dưỡng" trong thông tin người dùng

### Sprint Retrospective
- **Điểm tốt:**
  - Giao tiếp hiệu quả giữa các thành viên
  - Hoàn thành đúng tiến độ
- **Điểm cần cải thiện:**
  - Cần thống nhất phong cách thiết kế từ đầu
  - Cần tài liệu hóa quyết định thiết kế tốt hơn
- **Kế hoạch cải thiện:**
  - Tạo style guide cho dự án
  - Sử dụng Figma components để đảm bảo tính nhất quán

## Sprint 2 (20/04 - 22/04)
### Sprint Planning
- **Mục tiêu Sprint:** Phát triển tính năng gợi ý thực đơn và danh sách nguyên liệu
- **User Stories:**
  - US03: Gợi ý Thực đơn Dựa trên AI
  - US06: Hiển thị Danh sách Nguyên liệu
- **Tasks:**
  - Thiết kế màn hình SuggestedMealPlan (Hoàng Văn Quyến)
  - Thiết kế màn hình MealDetails (Phạm Mai Gia Huy)
  - Tạo cấu trúc dữ liệu JSON cho gợi ý thực đơn (Lê Văn Cảm)
  - Tạo cấu trúc dữ liệu JSON cho danh sách nguyên liệu (Lê Văn Cảm)

### Daily Scrum (Tóm tắt)
#### Ngày 20/04
- **Đã hoàn thành:**
  - Bắt đầu thiết kế màn hình SuggestedMealPlan
  - Xác định cấu trúc dữ liệu cho gợi ý thực đơn
- **Kế hoạch:**
  - Tiếp tục thiết kế màn hình SuggestedMealPlan
  - Bắt đầu tạo file JSON mẫu
- **Vấn đề:**
  - Cần thêm hình ảnh món ăn chất lượng cao

#### Ngày 21/04
- **Đã hoàn thành:**
  - Hoàn thiện màn hình SuggestedMealPlan
  - Bắt đầu thiết kế màn hình MealDetails
  - Tạo cấu trúc dữ liệu JSON cơ bản
- **Kế hoạch:**
  - Hoàn thiện màn hình MealDetails
  - Hoàn thiện file JSON mẫu
- **Vấn đề:**
  - Không có

#### Ngày 22/04
- **Đã hoàn thành:**
  - Hoàn thiện tất cả màn hình cho US03 và US06
  - Hoàn thiện file JSON mẫu
- **Kế hoạch:**
  - Chuẩn bị cho Sprint Review
- **Vấn đề:**
  - Không có

### Sprint Review
- **Kết quả đạt được:**
  - Hoàn thành 2 màn hình: SuggestedMealPlan, MealDetails
  - Hoàn thành file JSON mẫu cho gợi ý thực đơn và danh sách nguyên liệu
- **Phản hồi từ Product Owner:**
  - Hài lòng với thiết kế giao diện
  - Đề xuất thêm thông tin dinh dưỡng chi tiết hơn

### Sprint Retrospective
- **Điểm tốt:**
  - Áp dụng hiệu quả style guide
  - Tốc độ làm việc cải thiện
- **Điểm cần cải thiện:**
  - Cần tìm nguồn hình ảnh món ăn chất lượng cao hơn
  - Cần thêm thông tin dinh dưỡng chi tiết
- **Kế hoạch cải thiện:**
  - Sử dụng nguồn hình ảnh chất lượng cao
  - Bổ sung thông tin dinh dưỡng chi tiết trong file JSON

## Sprint 3 (22/04 - 24/04)
### Sprint Planning
- **Mục tiêu Sprint:** Tập trung vào lập kế hoạch ăn uống hàng tuần và gợi ý dựa trên nguyên liệu
- **User Stories:**
  - US04: Lên Lịch Ăn Uống Hàng Tuần
  - US05: Gợi ý Món Ăn Dựa trên Nguyên liệu
- **Tasks:**
  - Thiết kế màn hình DailyMeals (Hoàng Văn Quyến)
  - Thiết kế màn hình AlternativeMeals (Phạm Mai Gia Huy)
  - Thiết kế màn hình DailyMealsCalories (Hoàng Văn Quyến)
  - Cập nhật file JSON mẫu (Lê Văn Cảm)

### Daily Scrum (Tóm tắt)
#### Ngày 22/04
- **Đã hoàn thành:**
  - Bắt đầu thiết kế màn hình DailyMeals
  - Bắt đầu thiết kế màn hình AlternativeMeals
- **Kế hoạch:**
  - Tiếp tục thiết kế các màn hình
  - Cập nhật file JSON mẫu
- **Vấn đề:**
  - Không có

#### Ngày 23/04
- **Đã hoàn thành:**
  - Hoàn thiện màn hình DailyMeals
  - Hoàn thiện màn hình AlternativeMeals
  - Bắt đầu thiết kế màn hình DailyMealsCalories
- **Kế hoạch:**
  - Hoàn thiện màn hình DailyMealsCalories
  - Hoàn thiện cập nhật file JSON mẫu
- **Vấn đề:**
  - Không có

#### Ngày 24/04
- **Đã hoàn thành:**
  - Hoàn thiện tất cả màn hình cho US04 và US05
  - Hoàn thiện cập nhật file JSON mẫu
- **Kế hoạch:**
  - Chuẩn bị cho Sprint Review và Demo cuối cùng
- **Vấn đề:**
  - Không có

### Sprint Review
- **Kết quả đạt được:**
  - Hoàn thành 3 màn hình: DailyMeals, AlternativeMeals, DailyMealsCalories
  - Hoàn thành cập nhật file JSON mẫu
- **Phản hồi từ Product Owner:**
  - Hài lòng với tất cả các màn hình
  - Đề xuất thêm tính năng xuất kế hoạch ăn uống trong tương lai

### Sprint Retrospective
- **Điểm tốt:**
  - Hoàn thành tất cả User Stories đúng tiến độ
  - Thiết kế nhất quán và hấp dẫn
- **Điểm cần cải thiện:**
  - Cần tài liệu hóa tốt hơn cho việc sử dụng dữ liệu JSON
- **Kế hoạch cải thiện:**
  - Tạo tài liệu API mô tả cấu trúc dữ liệu JSON

## Kết luận
- **Tổng kết dự án:**
  - Hoàn thành tất cả 6 User Stories trong 3 Sprint
  - Tạo được prototype đầy đủ chức năng với 8 màn hình UI
  - Mô phỏng thành công dữ liệu bằng JSON
- **Bài học kinh nghiệm:**
  - Phương pháp Scrum giúp quản lý dự án hiệu quả
  - Style guide và components giúp đảm bảo tính nhất quán trong thiết kế
  - Tài liệu hóa quyết định thiết kế và cấu trúc dữ liệu là rất quan trọng
- **Hướng phát triển tiếp theo:**
  - Phát triển tính năng xuất kế hoạch ăn uống
  - Tích hợp với cơ sở dữ liệu thực phẩm thực tế
  - Phát triển thuật toán AI thực sự cho việc gợi ý thực đơn

## Tài liệu tham khảo
- [Jira Board](https://lecam1698.atlassian.net/jira/software/projects/SCRUM/list)
- [Figma Design](https://www.figma.com/design/YPCMcJBV2oZaLjwEVujPsS/Untitled?node-id=0-1&p=f&t=1NaPp7elQDUesGDg-0)
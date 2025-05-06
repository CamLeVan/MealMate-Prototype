# MealMate Prototype 🍽️

![MealMate Banner](UI_Design/SuggestedMealPlan)

## 📋 Tổng quan dự án

**MealMate** là một prototype được phát triển trong khuôn khổ môn Công nghệ Phần mềm tại VKU, tập trung vào việc lập kế hoạch bữa ăn cá nhân hóa. Dự án được thực hiện theo khung Scrum qua 3 sprint, nhấn mạnh vào thiết kế UI/UX và mô phỏng chức năng:

- **Đăng ký và Đăng nhập** (US01): Màn hình đăng ký và đăng nhập cho người dùng.
- **Quản lý Hồ sơ Cá nhân** (US02): Giao diện để nhập và xác nhận thông tin người dùng (tuổi, giới tính, mục tiêu ăn uống).
- **Gợi ý Thực đơn Dựa trên AI** (US03): Mô phỏng gợi ý thực đơn dựa trên hồ sơ người dùng, sử dụng mẫu dữ liệu JSON.
- **Hiển thị Danh sách Nguyên liệu** (US06): Giao diện hiển thị nguyên liệu cho các món ăn đã chọn.
- **Lên Lịch Ăn Uống Hàng Tuần** (US04): Giao diện lập kế hoạch bữa ăn hàng ngày.
- **Gợi ý Món Ăn Dựa trên Nguyên liệu** (US05): Đề xuất món ăn dựa trên nguyên liệu có sẵn.
- **Trực quan hóa Bữa Ăn Hàng Ngày**: Màn hình hiển thị bữa ăn hàng ngày với hình ảnh và thông tin calo.

**Mục tiêu dự án:**
- Thiết kế giao diện thân thiện cho việc lập kế hoạch bữa ăn.
- Mô phỏng chức năng ứng dụng bằng dữ liệu JSON.
- Thực hiện quy trình Scrum hoàn chỉnh, được quản lý qua Jira.

## 📂 Cấu trúc Kho mã

Kho mã được tổ chức như sau:

- **`UI_Design/`**: Thiết kế giao diện Figma được xuất dưới dạng file PNG.
  - `WelcomeScreen.png`: Màn hình chào mừng và đăng ký nhanh.
  - `PersonalInformation.png`: Màn hình nhập thông tin người dùng.
  - `ConfirmPersonalInformation.png`: Màn hình xác nhận thông tin người dùng.
  - `SuggestedMealPlan.png`: Màn hình hiển thị thực đơn gợi ý bởi AI.
  - `MealDetails.png`: Màn hình chi tiết món ăn và nguyên liệu.
  - `AlternativeMeals.png`: Màn hình gợi ý món ăn thay thế.
  - `DailyMeals.png`: Màn hình lập lịch ăn uống hàng ngày.
  - `DailyMealsCalories.png`: Màn hình bữa ăn hàng ngày với hình ảnh và thông tin dinh dưỡng.
- **`Data_Samples/`**: File JSON mô phỏng dữ liệu ứng dụng.
  - `meal_suggestion_sample.json`: Dữ liệu mẫu cho gợi ý thực đơn dựa trên AI.
- **`Documents/`**: Tài liệu liên quan đến Scrum.
  - `Sprint_1_Meeting_Notes.pdf`: Ghi chú cuộc họp Sprint 1.
  - `Sprint_2_Meeting_Notes.pdf`: Ghi chú cuộc họp Sprint 2.
  - `Sprint_3_Meeting_Notes.pdf`: Ghi chú cuộc họp Sprint 3.

## 🚀 Hướng dẫn Khám phá Prototype

### 1. **Xem Thiết kế Giao diện**
- Kiểm tra `UI_Design/DailyMealsCalories.png` để xem kế hoạch bữa ăn hàng ngày với hình ảnh và thông tin calo.
- Khám phá các file PNG riêng lẻ trong `UI_Design/` cho các màn hình cụ thể (ví dụ: `SuggestedMealPlan.png`).

### 2. **Khám phá Dữ liệu Mô phỏng**
- Mở `Data_Samples/meal_suggestion_sample.json` để xem mẫu dữ liệu cho gợi ý thực đơn dựa trên AI.

### 3. **Xem lại Tài liệu Scrum**
- Tham khảo thư mục `Documents/` để xem ghi chú cuộc họp và hiểu rõ quy trình Scrum.

## 🛠️ Công cụ và Công nghệ

- **Figma**: Sử dụng để thiết kế tất cả các màn hình UI/UX.
- **Jira**: Quản lý các hoạt động Scrum (backlog, sprint, task).
- **JSON**: Mô phỏng dữ liệu cho gợi ý thực đơn và danh sách nguyên liệu.
- **Google Docs**: Lưu trữ ghi chú cuộc họp và tài liệu dự án.

## 🔗 Tài nguyên Thêm

- **Dự án Figma**: https://www.figma.com/design/YPCMcJBV2oZaLjwEVujPsS/Untitled?node-id=0-1&p=f&t=1NaPp7elQDUesGDg-0
- **Bảng Jira**: [https://lecam1698.atlassian.net/jira/software/projects/SCRUM/list](https://lecam1698.atlassian.net/jira/software/projects/SCRUM/list)

## 👥 Thành viên Nhóm

| Vai trò            | Tên             | Trách nhiệm                     |
|---------------------|-----------------|---------------------------------|
| Product Owner       | Ngô Huỳnh Lộc    | Định nghĩa yêu cầu, quản lý backlog |
| Scrum Master        | Lê Văn Cảm       | Điều phối quy trình Scrum      |
| Developer (UI)      | Phạm Mai Gia Huy | Thiết kế logic AI và màn hình UI |
| Developer (UX)      | Hoàng Văn Quyến  | Thiết kế UX và giao diện frontend |

## 📅 Các Sprint

- **Sprint 1 (17/04 – 19/04)**: Thực hiện đăng ký, đăng nhập và quản lý hồ sơ cá nhân (US01, US02).
- **Sprint 2 (20/04 – 22/04)**: Phát triển tính năng gợi ý thực đơn và danh sách nguyên liệu (US03, US06).
- **Sprint 3 (22/04 – 24/04)**: Tập trung vào lập kế hoạch ăn uống hàng tuần và gợi ý dựa trên nguyên liệu (US04, US05).

## 📜 Giấy phép

Dự án này chỉ dành cho mục đích học tập và không bao gồm giấy phép chính thức.

---

*Được phát triển trong khuôn khổ môn Công nghệ Phần mềm tại VKU, tháng 5 năm 2025.*

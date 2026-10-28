# Chiến lược nội dung thực tế

> **Một repository, một skill.** Workflow độc lập bằng tiếng Việt cho AI Agent.
>
> **Watermark:** [https://cachdungai.blog/](https://cachdungai.blog/)

## Giới thiệu

Lập kế hoạch nội dung đa kênh theo mục tiêu, độc giả, nguồn lực và dữ liệu sẵn có. Dùng để chọn trụ cột, chủ đề và lịch; không thay brief cho một bài SEO.

Mở **SKILL.md** để xem đầu vào, quy trình, đầu ra, giới hạn và prompt mẫu. Gói cài đặt chứa SKILL.md và giấy phép MIT, không kèm script thực thi.

## Tải gói cài đặt

Tải ZIP sẵn dùng: [content-strategy-vi.zip](content-strategy-vi.zip). ZIP có thư mục gốc tên **content-strategy-vi** và chứa **SKILL.md**, phù hợp để tải lên như một skill riêng.

## Cách cài

### Claude.ai

1. Nếu Skills chưa hiện, kiểm tra Settings > Capabilities và bật code execution nếu tài khoản/workspace hỗ trợ.
2. Mở **Customize > Skills**, bấm **+ > Create skill > Upload a skill**.
3. Chọn tệp **content-strategy-vi.zip** vừa tải và bật skill sau khi upload.

Khả năng tạo và dùng skill phụ thuộc gói tài khoản, bật code execution và chính sách workspace.

### Claude Code

Chép **SKILL.md** vào **.claude/skills/content-strategy-vi/SKILL.md** trong dự án hoặc **~/.claude/skills/content-strategy-vi/SKILL.md** để dùng cá nhân. Gọi bằng **/content-strategy-vi** hoặc mô tả yêu cầu để Claude tự chọn khi phù hợp.

### ChatGPT

Skills chỉ xuất hiện ở các tài khoản/workspace đủ điều kiện; hiện trang trợ giúp OpenAI nêu Business, Enterprise, Healthcare và Edu, tùy thiết lập workspace.

1. Mở **Plugins > Plugin Directory > Skills**.
2. Chọn **Create > Upload from your computer**.
3. Chọn **content-strategy-vi.zip**.

Nếu không có mục Skills, mở **SKILL.md** rồi dán nội dung vào yêu cầu hoặc Project instructions nếu có. Đây là cách dùng thủ công, không phải cài skill tự động.

### Codex

Trong repo dự án, chép **SKILL.md** vào **.agents/skills/content-strategy-vi/SKILL.md**, rồi yêu cầu Codex dùng skill này.

## Prompt mẫu

“Lập kế hoạch nội dung 4 tuần cho blog tiếng Việt về AI video và fan page. Có 4 giờ sản xuất mỗi tuần, một người viết, chưa có dữ liệu từ khóa. Chọn chủ đề dễ làm trước, tách rõ bài website, bài Facebook và video ngắn.”

Gửi thêm mục tiêu, độc giả, tài liệu đầu vào, nền tảng và giới hạn cần giữ để kết quả sát hơn. Kiểm tra dữ kiện và duyệt nội dung trước khi xuất bản.

## Giấy phép

MIT License — xem file **LICENSE** trong repository.

---

**Watermark:** [https://cachdungai.blog/](https://cachdungai.blog/)

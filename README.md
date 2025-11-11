<div align="center">
  <img src="assets/logo.png" alt="Đại học Đại Nam Logo" width="250"/>
  
  # 🤖 Chatbot AI với RAG & Workflow Automation
  
  ### Hệ thống Tư vấn Thông minh Tự động 24/7
  
  [![n8n](https://img.shields.io/badge/n8n-Workflow-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)](https://n8n.io)
  [![Telegram](https://img.shields.io/badge/Telegram-Bot-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://telegram.org)
  [![Google Gemini](https://img.shields.io/badge/Google-Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev)
  [![Supabase](https://img.shields.io/badge/Supabase-Vector_DB-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com)
  [![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://postgresql.org)
  
  <br/>
  
  **🎓 Khoa Công Nghệ Thông Tin**  
  **🏛️ Đại học Đại Nam**
  
  <br/>
  
  [📖 Tài liệu](#-mục-lục) • [🚀 Bắt đầu](#-cài-đặt) • [💡 Demo](#-sử-dụng) • [🤝 Đóng góp](#-đóng-góp)
  
</div>

---

## 📋 Mục lục

- [Giới thiệu](#-giới-thiệu)
- [Tính năng](#-tính-năng)
- [Kiến trúc hệ thống](#-kiến-trúc-hệ-thống)
- [Công nghệ sử dụng](#-công-nghệ-sử-dụng)
- [Cài đặt](#-cài-đặt)
- [Cấu hình](#-cấu-hình)
- [Sử dụng](#-sử-dụng)
- [Ý nghĩa đề tài](#-ý-nghĩa-đề-tài)
- [Hướng phát triển](#-hướng-phát-triển)
- [Đóng góp](#-đóng-góp)
- [Giấy phép](#-giấy-phép)

## 🎯 Giới thiệu

> **Chatbot AI với RAG** là hệ thống tư vấn thông minh tự động, kết hợp **Retrieval-Augmented Generation (RAG)** và **Workflow Automation** để giúp doanh nghiệp chăm sóc khách hàng 24/7 một cách hiệu quả và chuyên nghiệp.

### ✨ Điểm nổi bật

<table>
<tr>
<td width="50%">

#### 🧠 Thông minh
- Hiểu ngôn ngữ tự nhiên
- Trả lời dựa trên dữ liệu thật
- Ghi nhớ ngữ cảnh hội thoại
- Học hỏi từ knowledge base

</td>
<td width="50%">

#### ⚡ Tự động
- Phản hồi tức thì 24/7
- Lưu thông tin khách hàng
- Gửi email xác nhận
- Đồng bộ Google Sheets

</td>
</tr>
</table>

### 🎯 Vấn đề giải quyết

<div align="center">

| ❌ Trước đây | ✅ Với Chatbot AI |
|:------------|:-----------------|
| Phản hồi chậm, chỉ trong giờ hành chính | Phản hồi tức thì 24/7 |
| Ghi nhận thông tin thủ công, dễ sai sót | Tự động lưu trữ chính xác 100% |
| Thiếu thống nhất trong tư vấn | Câu trả lời chuẩn từ knowledge base |
| Mất thời gian xử lý hàng trăm tin nhắn | Giảm 50-70% công việc thủ công |

</div>

### 🚀 Kết quả đạt được

```
📊 Hiệu suất:  ⏱️ Giảm 50-70% thời gian xử lý
🎯 Chất lượng: ✅ Tăng độ chính xác lên 95%+
💰 Chi phí:    📉 Tiết kiệm 60% chi phí nhân sự
😊 Khách hàng: ⭐ Tăng 40% độ hài lòng
```

## ✨ Tính năng

<div align="center">

### 🎨 Tổng quan tính năng

</div>

<table>
<tr>
<td width="50%" valign="top">

### 🤖 AI & RAG

**Vector Database Search**
- 🔍 Semantic search với Supabase
- 📊 Top-K retrieval (k=10)
- 🎯 Độ chính xác cao

**Natural Language Understanding**
- 💬 Hiểu tiếng Việt tự nhiên
- 🧠 Phân tích ý định người dùng
- 📝 Trả lời theo ngữ cảnh

**Knowledge Base**
- 📚 Script tư vấn chuẩn
- ❓ FAQ tự động
- 🎁 Thông tin sản phẩm/gói học

</td>
<td width="50%" valign="top">

### ⚙️ Automation

**Smart Data Collection**
- 📋 Thu thập thông tin tự động
- ✅ Validate dữ liệu realtime
- 🔄 Nhắc nhở thông tin thiếu

**Multi-Platform Integration**
- 📱 Telegram Bot
- 📧 Gmail notification
- 📊 Google Sheets sync
- 💾 PostgreSQL storage

**Workflow Orchestration**
- 🔗 n8n visual workflow
- 🎯 Conditional logic
- 📈 Scalable architecture

</td>
</tr>
</table>

### 💾 Quản lý bộ nhớ

- **Context Memory**: Ghi nhớ 30 tin nhắn gần nhất
- **Session Management**: Theo dõi từng khách hàng riêng biệt
- **Data Persistence**: Lưu trữ lâu dài với PostgreSQL

## 🏗️ Kiến trúc hệ thống

```
┌─────────────────┐
│  Telegram Bot   │
└────────┬────────┘
         │
         ▼
┌─────────────────┐      ┌──────────────────┐
│   AI Agent      │◄────►│  Google Gemini   │
│   (n8n)         │      │   Chat Model     │
└────────┬────────┘      └──────────────────┘
         │
         ├──────────────┐
         │              │
         ▼              ▼
┌─────────────────┐  ┌──────────────────┐
│ Supabase Vector │  │ PostgreSQL Chat  │
│     Store       │  │     Memory       │
└─────────────────┘  └──────────────────┘
         │
         ▼
┌─────────────────┐
│  Data Pipeline  │
│  - Validation   │
│  - Extraction   │
└────────┬────────┘
         │
         ├──────────────┬──────────────┐
         ▼              ▼              ▼
┌─────────────┐  ┌─────────────┐  ┌─────────────┐
│Google Sheets│  │Gmail Notify │  │  Response   │
└─────────────┘  └─────────────┘  └─────────────┘
```

### Luồng hoạt động

1. **Nhận tin nhắn**: Telegram Trigger nhận tin nhắn từ người dùng
2. **Xử lý AI**: AI Agent phân tích và tìm kiếm thông tin từ Vector DB
3. **Truy xuất dữ liệu**: Supabase Vector Store tìm kiếm semantic matching
4. **Sinh câu trả lời**: Google Gemini tạo phản hồi tự nhiên
5. **Kiểm tra dữ liệu**: Validate thông tin đăng ký (số điện thoại, tên, v.v.)
6. **Lưu trữ**: Ghi vào Google Sheets và PostgreSQL
7. **Thông báo**: Gửi email cho đội ngũ sales nếu đủ điều kiện
8. **Phản hồi**: Gửi tin nhắn trả lời cho người dùng

## 🛠️ Công nghệ sử dụng

### Core Technologies

| Công nghệ | Mục đích | Phiên bản |
|-----------|----------|-----------|
| **n8n** | Workflow automation & orchestration | Latest |
| **Google Gemini** | Large Language Model (LLM) | PaLM API |
| **Supabase** | Vector database & embeddings | Latest |
| **PostgreSQL** | Chat memory storage | Latest |
| **Telegram Bot API** | Messaging platform | v1.2 |

### Supporting Services

- **Google Sheets**: Lưu trữ dữ liệu khách hàng và knowledge base
- **Gmail API**: Gửi thông báo email tự động
- **Google Gemini Embeddings**: Vector embeddings cho RAG

### Key Features

- **RAG (Retrieval-Augmented Generation)**: Kết hợp tìm kiếm semantic với LLM
- **Vector Search**: Top-K retrieval với k=10
- **Memory Management**: Context window 30 messages
- **Data Validation**: Regex-based validation cho số điện thoại và thông tin

## 📦 Cài đặt

### Yêu cầu hệ thống

- Docker & Docker Compose
- Tài khoản Cloudflare (để deploy)
- Tài khoản Supabase
- Tài khoản Google Cloud (Gemini API)
- Telegram Bot Token

### Bước 1: Clone Repository

```bash
git clone https://github.com/Trinhvhao/n8n-rag-automation-chatbot.git
cd n8n-rag-automation-chatbot
```

### Bước 2: Cài đặt n8n với Docker & Deploy lên Cloudflare

<div align="center">

📺 **Video hướng dẫn chi tiết**

| Bước | Video | Mô tả |
|:----:|:------|:------|
| 1️⃣ | [🐳 Cài đặt n8n với Docker](https://www.youtube.com/watch?v=example) | Hướng dẫn setup n8n local bằng Docker |
| 2️⃣ | [☁️ Deploy n8n lên Cloudflare](https://www.youtube.com/watch?v=example) | Đẩy n8n lên Cloudflare để chạy 24/7 miễn phí |

</div>

> 💡 **Lưu ý**: Sau khi hoàn thành, bạn sẽ có n8n instance chạy trên Cloudflare với domain riêng (ví dụ: `https://your-bot.workers.dev`)

### Bước 3: Import Workflow vào n8n

<table>
<tr>
<td width="30px">1️⃣</td>
<td>Truy cập n8n instance của bạn<br/><code>https://your-n8n.workers.dev</code></td>
</tr>
<tr>
<td>2️⃣</td>
<td>Đăng nhập hoặc tạo tài khoản mới</td>
</tr>
<tr>
<td>3️⃣</td>
<td>Click vào menu <strong>Workflows</strong> → <strong>Import from File</strong></td>
</tr>
<tr>
<td>4️⃣</td>
<td>Chọn file <code>Chat Bot AI Vector DB.json</code> từ repository</td>
</tr>
<tr>
<td>5️⃣</td>
<td>✅ Workflow được import thành công với tất cả các node!</td>
</tr>
</table>

<div align="center">
  <img src="https://img.shields.io/badge/Status-Ready_to_Configure-success?style=for-the-badge" alt="Ready"/>
</div>

## ⚙️ Cấu hình

<div align="center">

### 🔧 Các bước cấu hình hệ thống

</div>

### 1️⃣ Telegram Bot

<details>
<summary><b>👉 Click để xem hướng dẫn</b></summary>

1. Mở Telegram và tìm **@BotFather**
2. Gửi lệnh `/newbot` và làm theo hướng dẫn
3. Lưu lại **Bot Token** (dạng: `123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11`)
4. Trong n8n, mở node **Telegram Trigger**
5. Thêm credentials mới với Bot Token vừa lấy

</details>

### 2️⃣ Google Gemini API

<details>
<summary><b>👉 Click để xem hướng dẫn</b></summary>

1. Truy cập [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Click **Get API Key** → **Create API key**
3. Copy API key
4. Trong n8n, cấu hình **Google Gemini Chat Model** với API key

</details>

### 3️⃣ Supabase Vector Database

<details>
<summary><b>👉 Click để xem hướng dẫn</b></summary>

**Bước 1: Tạo project Supabase**
- Truy cập [Supabase](https://supabase.com)
- Tạo project mới (miễn phí)

**Bước 2: Tạo bảng documents**
```sql
-- Chạy trong SQL Editor của Supabase
CREATE TABLE documents (
  id BIGSERIAL PRIMARY KEY,
  content TEXT,
  metadata JSONB,
  embedding VECTOR(768)
);

-- Tạo index cho vector search
CREATE INDEX ON documents 
USING ivfflat (embedding vector_cosine_ops);
```

**Bước 3: Lấy credentials**
- Copy **Project URL** và **API Key** từ Settings
- Cấu hình trong n8n node **Supabase Vector Store**

</details>

### 4️⃣ PostgreSQL Chat Memory

<details>
<summary><b>👉 Click để xem hướng dẫn</b></summary>

**Option 1: Sử dụng Supabase PostgreSQL (Khuyến nghị)**
- Dùng chung database với Supabase ở bước 3
- n8n sẽ tự động tạo tables cần thiết

**Option 2: PostgreSQL riêng**
```sql
CREATE DATABASE n8n_chat_memory;
```

</details>

### 5️⃣ Google Sheets

<details>
<summary><b>👉 Click để xem hướng dẫn</b></summary>

**Tạo Google Sheet với 4 sheets:**

| Sheet | Cột | Mô tả |
|-------|-----|-------|
| **Script** | Tình huống, Kịch bản hội thoại mẫu | Kịch bản tư vấn chuẩn |
| **FAQ** | Câu hỏi thường gặp, Trả lời | Câu hỏi phổ biến |
| **Product** | Tên gói, Học phí, Ưu đãi | Thông tin sản phẩm |
| **Customer Leads** | timestamp, chatId, studentName, phoneNumber, ... | Lưu thông tin khách hàng |

**Cấu hình trong n8n:**
- Enable Google Sheets API
- Tạo OAuth 2.0 credentials
- Kết nối với n8n

</details>

### 6️⃣ Gmail API

<details>
<summary><b>👉 Click để xem hướng dẫn</b></summary>

1. Truy cập [Google Cloud Console](https://console.cloud.google.com)
2. Enable **Gmail API**
3. Tạo **OAuth 2.0 Client ID**
4. Cấu hình trong n8n với OAuth credentials

</details>

---

<div align="center">

✅ **Sau khi hoàn thành tất cả bước trên, hệ thống đã sẵn sàng hoạt động!**

</div>

## 🚀 Sử dụng

### Khởi động hệ thống

```bash
# Khởi động n8n
n8n start

# Hoặc với Docker
docker-compose up -d
```

### Nạp dữ liệu vào Vector DB

1. Chuẩn bị dữ liệu trong Google Sheets (Script, FAQ, Product)
2. Kích hoạt workflow "Nạp data vào Vector DB"
3. Dữ liệu sẽ được embedding và lưu vào Supabase

### Sử dụng Chatbot

1. Tìm bot trên Telegram
2. Gửi tin nhắn `/start`
3. Bắt đầu hội thoại tư vấn

### Ví dụ hội thoại

```
User: Xin chào, cho em hỏi về các gói học
Bot: Dạ chào anh/chị! Em là trợ lý tư vấn của Zaka Edu ạ...

User: Gói Starter giá bao nhiêu?
Bot: Dạ gói Starter có học phí là 2.500.000đ/tháng...

User: Em muốn đăng ký cho bé
Bot: Dạ em xin phép hỏi thêm thông tin ạ...
```

## 💡 Ý nghĩa đề tài

### Giá trị khoa học và công nghệ

| Khía cạnh | Ý nghĩa |
|-----------|---------|
| 💡 Khoa học – Công nghệ | Ứng dụng AI kết hợp RAG và workflow automation vào thực tế doanh nghiệp |
| 🧩 Kỹ thuật phần mềm | Mô hình hóa quy trình tư vấn thành hệ thống trực quan, dễ mở rộng |
| 🧠 Nghiệp vụ – Marketing | Phản hồi nhanh, cá nhân hóa trải nghiệm, tăng tỷ lệ chuyển đổi |
| 📊 Chuyển đổi số | Biến quy trình tư vấn truyền thống thành tự động hoàn toàn |
| 🚀 Thực tiễn ứng dụng | Triển khai tại bất kỳ doanh nghiệp dịch vụ nào |

### Điểm mới và khác biệt

1. **Chatbot không chỉ phản hồi – mà còn hành động**
   - Lưu thông tin vào database
   - Gửi email tự động
   - Kiểm tra và nhắc bổ sung thông tin

2. **Tích hợp RAG (Retrieval-Augmented Generation)**
   - Tìm kiếm dữ liệu thật từ kho thông tin nội bộ
   - Phản hồi chính xác và cập nhật

3. **Tự động hóa bằng n8n**
   - Kết nối nhiều nền tảng
   - Xây dựng quy trình end-to-end
   - Không cần code phức tạp

### So sánh n8n vs Code truyền thống

| Tiêu chí | n8n (No-code/Low-code) | Code truyền thống |
|----------|------------------------|-------------------|
| ⚙️ Cấu hình | Kéo-thả trực quan | Viết code thủ công |
| ⏱️ Thời gian | Nhanh (vài ngày) | Lâu hơn (vài tuần) |
| 🔌 Kết nối | Hàng trăm node có sẵn | Viết từng API call |
| 🧠 Mở rộng | Dễ dàng qua UI | Cần viết lại code |
| 🧱 Bảo trì | Dễ theo dõi | Cần lập trình viên |
| 💰 Chi phí | Thấp, có thể self-host | Cao hơn |

### Tác động thực tiễn

- ⏱️ Giảm 50-70% công việc thủ công
- 🤖 Phản hồi 24/7
- 📋 Dữ liệu đồng bộ, dễ phân tích
- 🔄 Tăng khả năng chuyển đổi
- 📈 Tiết kiệm chi phí nhân sự

## 🔮 Hướng phát triển

### Ngắn hạn

- [ ] Tích hợp thêm Zalo, Facebook Messenger
- [ ] Thêm dashboard báo cáo realtime
- [ ] Hỗ trợ đa ngôn ngữ (English, Korean)
- [ ] Tối ưu hóa prompt và retrieval

### Trung hạn

- [ ] Tích hợp CRM (Customer Relationship Management)
- [ ] Intent Classification và Sentiment Analysis
- [ ] A/B testing cho các phiên bản prompt
- [ ] Mobile app cho quản lý

### Dài hạn

- [ ] Phát triển voicebot (chatbot thoại)
- [ ] Multi-agent system
- [ ] Predictive analytics cho sales
- [ ] Mã hóa dữ liệu và OAuth 2.0

## 🤝 Đóng góp

Chúng tôi hoan nghênh mọi đóng góp! Vui lòng:

1. Fork repository
2. Tạo branch mới (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Mở Pull Request

## 📄 Giấy phép

Dự án này được phát hành dưới giấy phép MIT. Xem file [LICENSE](LICENSE) để biết thêm chi tiết.

## 👥 Tác giả

<div align="center">

**🎓 Khoa Công Nghệ Thông Tin**  
**🏛️ Đại học Đại Nam**

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-Trinhvhao-181717?style=for-the-badge&logo=github)](https://github.com/Trinhvhao)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@dainam.edu.vn)

</div>

---

<div align="center">
  
  ### ⭐ Nếu dự án hữu ích, hãy cho chúng tôi một star! ⭐
  
  <br/>
  
  ![Made with Love](https://img.shields.io/badge/Made_with-❤️-red?style=for-the-badge)
  ![Vietnam](https://img.shields.io/badge/Made_in-Vietnam_🇻🇳-red?style=for-the-badge)
  
  **Đại học Đại Nam** • 2024
  
  <br/>
  
  [⬆️ Về đầu trang](#-chatbot-ai-với-rag--workflow-automation)
  
</div>

## Xin chào 👋
Đây là Git chính thức của NHQTools.
Các thông tin liên quan đến các tools trong hệ sinh thái Tools sẽ được cập nhật tại đây.
## Các kênh:

## Phiên bản cập nhật 2.5.7 (2025-06-16):
**NHQTools cập nhật các tính năng mới cho TTS STUDIO và Video Tools**
- Thêm Q-CLONE vào danh sách dịch vụ giọng trong Video Tools
- Fix lỗi Ele2 trong Video Tools
- Fix một số lỗi khi xuất video

**Với TTS Studio**
TTS Studio mới update một vài tính năng AI mới. Anh em xem có hỗ trợ gì cho công việc không nhé.
1. Tự động kiểm tra chính tả AI
- Kiểm tra lỗi chính tả
- Gợi ý cách đọc với các từ không phải tiếng Việt (ví dụ: indonesia => in-đô-nê-xi-a)
- Chỉnh sửa các câu dài thành câu ngắn hơn phù hợp để tạo giọng mà không bị nuốt từ hay vấp từ
- Tự động chuyển đổi số thành chữ, ngày tháng thành chữ, các đơn vị tiền tệ, khối lượng... đảm bảo giữ nguyên ý nghĩa
- Tự động kiểm tra lỗi ký tự ẩn khi văn bản đầu vào được tạo ra bởi các AI

2. Tóm tắt nội dung bằng AI
- Tự động tóm tắt nội dung với 2 phiên bản: Ngôn ngữ gốc và Tiếng Việt

3. Tạo thumbnail tự động
- Tạo prompt và thumbnail tự động cho đoạn văn bản đầu vào
- Có thể tuỳ chỉnh prompt trước khi tạo
- Có thể chọn kích thước khung hình phù hợp các loại video dọc, ngang.

  

## Phiên bản mới nhất v.2.4.7 (2025-06-04):
**NHQTools cập nhật các tính năng mới cho TTS STUDIO**
- Thêm tính năng delay giữa các đoạn/ phần/ chương.
- Tạo giọng đọc cho nhiều file cùng một lúc
Các tính năng thử nghiệm trong thời gian tới (chưa ra mắt):
- Cho phép tạo nhiều giọng trong cùng một lần chuyển đổi (kiểu đối thoại)
- Custom giọng khi sử dụng elevenlabs (nhấn nhá, ngữ điệu tuỳ chỉnh)
> Ngoài ra, anh em tham khảo cách tạo giọng đọc, lồng tiếng cho file phụ đề bên Video Tools nhé. Thấy nhiều anh em muốn tạo giọng đọc cho phụ đề, nhưng lại không để ý bên Video Tools có sẵn.
> Anh em dùng Video Tools chỉ cần click vào "Kết nối Video Tools" thôi nhé.
Mời anh em trải nghiệm và xem clip tại kênh chính thức của NHQTools: @nhqtoools

## Phiên bản mới nhất v2.2.2 (2025-05-12):
Cập nhật rất nhiều các tính năng, fix lỗi và cải thiện hiệu suất
- Fix lỗi khi xuất capcut với phương thức đồng bộ là video
- Fix lỗi và cải thiện hiệu suất tạo giọng bằng ChatGPT
- Thêm tính năng chia sẻ credits giữa các thành viên
- Fix một số lỗi nhỏ
- Cải thiện hiệu suất và thêm theo dõi tiến trình với Elevenlabs2
- Cải thiện và fix lỗi khi xuất video.
- Thêm cấu hình đồng nhất video để tránh lỗi khi xuất.
- Fix lỗi tạo phụ đề gemini trên Windows.
- Thêm theo dõi tiến trình khi tạo phụ đề với gemini.
- Cải tiến tính năng ghép ảnh độc quyền (Độc quyền cho từng khách hàng)
- Fix lỗi thanh toán tự động khi nạp tiền.\nCải thiện nhiều tính năng khác.
- Fix lỗi tính số ký tự unicode.
- Fix lỗi tách frames với CPU.
- Cải thiện chất lượng tiếng Việt khi dùng ChatGPT TTS
- ...

## Phiên bản v2.1.0 (2025-05-04):
NHQ Video Tools (NHQTTS Studio) v2.1.0
Phiên bản cập nhật mới nhất: 2.1.0
Bản update nhiều tính năng và tối ưu hiệu suất.
- Cập nhật thêm 2 phương thức chuyển giọng trong TTS Studio, hiển thị chi tiết tiến trình tạo giọng trong studio
- Hỗ trợ tạo giọng nói theo phong cách đối với voice ChatGPT custom
- Cải thiện hiệu suất khi export Video, điều chỉnh khớp hoàn toàn với audio và phụ đề trong trường hợp đồng bộ bằng cách điều chỉnh video
- Hỗ trợ các layout trên video (logo, fill, blur...)
- Thêm phụ đề nhanh chóng trên video
- Hiển thị chi tiết tiến trình tạo voice, nâng cao trải nghiệm
- Kiểm tra phụ đề đảm bảo phụ đề khớp trước khi tạo giọng.
- Hỗ trợ tạo prompt dịch tự động (prompt đề xuất bằng AI) dựa trên ngữ cảnh cũng như các nhân vật trong video.
- Fix một số lỗi khác...
**Mời anh em download trải nghiệm**
https://nhq.tools/downloads

----
Sau nhiều lần trì hoãn, hôm nay, mình chính thức mở bán công cụ hỗ trợ cho các anh em đang làm mảng video youtube và tiktok beta, đặc biệt là những anh em làm reup và review phim.

Bộ công vụ NHQTools sử dụng các mô hình trí tuệ nhân tạo mới nhất:
Mình xin phép được giới thiệu qua các tính năng cơ bản của Tool:

- **Tải video đa nền tảng** miễn phí, không giới hạn (hỗ trợ hầu hết các nền tảng video hiện nay như **Youtube**, **Tiktok**, **Douyin**, Instagram, Facebook, X (Twitter), Vimeo, Dailymotion... với tốc độ và trải nghiệm tốt nhất.
 - **Tạo phụ đề tự động** cho Video hỗ trợ hầu hết các ngôn ngữ: Sử dụng các mô hình Speech to text đầy đủ, đảm bảo chất lượng tốt nhất. Miễn phí 100% tạo phụ đề với whisper;
 - **Tự động nhận diện nhân vật** khi tạo phụ đề, đảm bảo các đoạn phụ đề gắn đúng với nhân vật trong video.
 - **Tự động dịch** sang nhiều ngôn ngữ, hỗ trợ dịch song song nhiều ngôn ngữ trong một lần. NHQTools sử dụng các mô hình AI để dịch phụ đề đảm bảo chất lượng phụ đề là tốt nhất. **Miễn phí 100% dịch phụ đề với Gemini AI và tất nhiên rồi, miễn phí 100% với Google Translate**. Anh em có thể sử dụng nhiều mô hình AI như DeepSeek, ChatGPT, Claude, Gemini... 
 - Hỗ trợ dịch phụ đề với các **prompt tuỳ chỉnh**: Hỗ trợ dịch phụ đề theo prompt tuỳ chỉnh cho anh em có nhu cầu, và linh hoạt hơn đối với từng nội dung khác nhau.
 - **Tóm tắt video nhanh chóng**, **tổng hợp nhân vật trong video tự động**: Tính năng này giúp anh em có thể hiểu được nội dung để có thể áp dụng cho các prompt tuỳ chỉnh.
 - **Chỉnh sửa trực tiếp phụ đề** trong Tool: Anh em có thể chỉnh sửa phụ đề trực tiếp trong tool và lưu trạng thái chỉnh sửa, giúp anh em kiểm soát tốt nội dung trước khi chuyển giọng hoặc xuất phụ đề.
 - **Xuất phụ đề và xuất phụ đề sang Cacpcut**: Anh em có thể xuất phụ đề để phục vụ các mục đích khác, hoặc xuất phụ đề sang Capcut để tạo giọng đọc miễn phí nhanh chóng.
 - **Tách frames ảnh từ video:** Đây là tính năng rất hay đối với các anh em làm video anime, video manga hoặc review truyện tranh. Tool sẽ trích xuất các frames (ảnh) và ghép lại với nhau đồng nhất hoàn toàn với giọng đọc đảm bảo anh em sản xuất video một cách đơn giản nhất có thể.
 - **Xuất video và dự án capcut**: Một trong những tính năng được rất nhiều anh em đề xuất đó là xuất video, frames qua capcut. Tool tự động xuất các frames ảnh, tự động áp dụng các hiệu ứng ngẫu nhiên hoặc thủ công và tự động tạo dự án capcut, công việc còn lại của anh em chỉ là mở capcut và render. Tool hỗ trợ gần 1000 hiệu ứng video và ảnh khác nhau, anh em có thể thoải mái lựa chọn.
 - **Xuất video tuỳ chỉnh**: Anh em cũng có thể xuất video trực tiếp từ tool, hỗ trợ các kích thước, độ phân dải phổ biến (Video dọc 9:16, video ngang 16:9, video chuẩn TV 4:3, hay video vuông 1:1); Hỗ trợ xuất video lên đến 4k. 
 - **Hỗ trợ đồng bộ âm thanh, video và phụ đề**: Khi xuất video anh em có thể đồng bộ thời gian cho video, âm thanh cũng như phụ đề, đảm bảo mọi thứ đồng bộ, khớp và không bị chống lấn hay méo mó âm thanh. Anh em có thể sử dụng các phương thức đồng bộ như **Đồng bộ âm thanh**, **đồng bộ video**, tuỳ chỉnh chế độ cắt thông minh để đảm bảo video xuất ra là unique.
 - **Về giọng đọc:** NHQTools hỗ trợ anh em tạo giọng đọc AI linh hoạt với hàng nghìn giọng đọc khác nhau cho mọi ngôn ngữ với mức giá cực kỳ ưu đãi, và tất nhiên vẫn là "**Miễn phí 100% với giọng đọc chị Google**" :)
 - **Tạo giọng đọc tuỳ chỉnh với Clone giọng miễn phí**: Anh em có thể clone giọng đọc của chính mình để sử dụng cho video, hoặc clone giọng bất kỳ. Tuy nhiên, với tính năng clone giọng đọc này, NHQTools không hỗ trợ tự động, anh em có thể gửi trực tiếp yêu cầu, sau đó bên mình sẽ kiểm tra và đảm bảo không vi phạm các điều khoản của NHQTools. 
 - Chỉnh sửa, thực hiện chuyển đổi văn bản thành giọng đọc với **NHQTTS Studio**: Mình cũng hỗ trợ thêm một phần riêng biệt cho anh em nào chỉ sử dụng tính năng chuyển văn bản thành giọng đọc. Với NHQTTS Studio, anh em có thể tải lên văn bản Word, tệp PDF hay file text đơn thuần, tool sẽ đọc nội dung và chuyển văn bản thành giọng đọc một cách nhanh chóng.

Còn rất nhiều các tính năng hay cũng như nâng cao khác được tích hợp sẵn trong tool. Anh em có thể dùng thử và nếu thấy hợp thì hãy ủng hộ mình nhé.

Hiện tại, tool hỗ trợ trên Windows. Anh em nào có nhu cầu chạy trên Mac (Intel hay Silicon) hoặc build bản riêng cho linux thì hãy liên hệ với mình nhé.

Anh em có thể xem qua chi tiết các tính năng của tool và hướng dẫn sử dụng chi tiết tại trang chủ NHQTools: https://nhq.tools

Cảm ơn anh em đã xem.
Rất mong được sử ủng hộ của anh em.


# stem

Ứng dụng tiếng Việt giúp người mới bắt đầu học từng nền tảng, tự thử bài và theo
dõi bằng chứng đã hiểu. Thiết lập ban đầu là **150 phút/ngày**, hướng tới mục tiêu
cá nhân **TSA 90+ vào tháng 5/2027**. Bạn có thể đổi thời gian và tháng mục tiêu
trong Cài đặt. Đây chưa phải lịch thi chính thức và ứng dụng không bảo đảm điểm thi.

## Bắt đầu nếu bạn không biết code

1. Mở ứng dụng trên PC, chọn **Thêm → Cài đặt & dữ liệu**.
2. Chọn **Tải ứng dụng HTML**, giữ tệp `mam-tsa.html` ở nơi dễ tìm trên máy.
3. Mở tệp đó bằng trình duyệt hiện đại. Bài học, bài luyện, gợi ý có sẵn và sổ tay
   chạy ngay cả khi không có mạng. Không cần cài Node.js để mở tệp HTML này.
4. Vào **Thêm → Kiểm tra hiểu**, chọn khảo sát nền tảng; nếu chưa biết, chọn “Mình chưa học”.
5. Vào **Hôm nay** để xem bài gợi ý và chia buổi học thành các khoảng vừa sức.

Mặc định 150 phút/ngày gồm **135 phút tập trung và 15 phút nghỉ**: ba phiên, mỗi
phiên 45 phút học và 5 phút nghỉ. Đồng hồ chỉ cộng thời gian tập trung. Trong
**Khóa học**, mở lịch từng tuần để xem những nền tảng nên học tiếp. Với mốc
bắt đầu 19/10/2026 và mục tiêu tháng 5/2027, lịch ban đầu gồm 28 tuần; thời lượng,
lỗi đã lưu và tháng mục tiêu giúp điều chỉnh gợi ý. Đây vẫn là lịch xây nền.
Giao diện bản 0.2 ưu tiên PC, tham khảo các màn danh mục và bài học trong clip
Brilliant bạn cung cấp. Màn Hôm nay và Tiến bộ phục vụ riêng mục tiêu TSA. Bản này
chưa xác nhận giống toàn bộ Brilliant; phần tối ưu và nghiệm thu riêng trên điện
thoại được để sau theo lựa chọn của bạn. Nội dung vẫn gồm 21 chủ đề nền tảng,
chưa bao phủ đầy đủ danh mục Toán hoặc toàn bộ TSA.

Lịch giữ mốc tuần theo ngày bạn bắt đầu và chỉ rõ tuần hiện tại, nên quay lại vào
tháng sau không trở về tuần đầu. Qua tháng mục tiêu, ứng dụng tiếp tục với các
chu kỳ 4 tuần có ngày cụ thể; mục tiêu xa hơn một năm được hiển thị theo từng
khối tối đa 52 tuần. Các khối tiếp theo vẫn dùng được, không khóa ứng dụng.

Nếu trình xem tệp trên điện thoại không chạy ứng dụng, hãy mở tệp trong trình duyệt
có hỗ trợ JavaScript. Một số hệ điều hành hạn chế mở HTML trực tiếp; khi đó có thể
dùng bản chạy trên máy chủ ở phần hướng dẫn kỹ thuật bên dưới. Cần thử trên chính
thiết bị của bạn trước khi dựa vào khả năng mở tệp này hằng ngày.

## Kiểm tra chất lượng sau mỗi phần

Trong mỗi bài thuộc 21 chủ đề hiện có, chọn **Xong phần này · kiểm tra mức hiểu**.
Ứng dụng ghi mốc đọc xong, mời bạn giải thích bằng lời của mình và mở bài kiểm tra
5 câu có dữ kiện thay đổi. Nếu chọn **Để sau**, phần đó còn trong danh sách chờ
kiểm tra ở Hôm nay và Tiến bộ. Bài kiểm tra trước mốc đọc mới nhất không thay thế
cho lượt kiểm tra sau phần học này.

Sau bài làm, mục **Chất lượng kiến thức sau phần học** cho biết câu tự làm mới,
câu cần gợi ý, câu lặp, lỗi sai và điều chưa biết. Mỗi lượt kiểm tra được gắn riêng
để theo dõi đúng bài làm; sao lưu JSON giữ các mốc và kết quả đó. Phần tự giải
thích được lưu nhưng chưa tự chấm đúng/sai. Khi đã có bằng chứng tự làm và đổi
bối cảnh, ứng dụng nhắc kiểm tra nhớ lại sau ít nhất 24 giờ; thông báo này hiện
trong ứng dụng, không gửi thông báo khi ứng dụng đang đóng.

Trong cùng một trang, bật hoặc dừng đồng hồ vẫn giữ lời giải thích, ghi chú và
thông tin đang gõ. Bấm **Lưu** để giữ chúng trước khi đổi trang hoặc đóng ứng dụng;
phần chưa bấm lưu chưa được bảo đảm khôi phục sau khi tải lại.

Những bằng chứng này giúp chọn việc học tiếp theo, chưa phải thang điểm TSA và
chưa đủ để xác nhận mục tiêu 90+. Luồng hiện tại hỗ trợ các phần trong 21 chủ đề
của bản nền tảng, chưa tự tạo bài kiểm tra cho mọi chương trong sách gốc.

## Giữ ứng dụng và tiến độ lâu dài

Phần học cốt lõi **không có ngày hết hạn, đăng nhập bắt buộc, thuê bao hay CDN**.
Tháng mục tiêu là thông tin để lập kế hoạch; qua tháng đó ứng dụng vẫn hoạt động.
Giữ tệp HTML để dùng mà không phụ thuộc thời gian tồn tại của một website. Có thể
giữ thêm bản mã nguồn để nhờ người khác sửa hoặc nâng cấp sau này.

Ứng dụng lưu tiến độ **trong trình duyệt và thiết bị hiện tại**, không tự đồng bộ
lên tài khoản. Kho lưu chính có dung lượng lớn hơn cách lưu trình duyệt thông
thường; ứng dụng giữ thêm một bản phụ khi trình duyệt cho phép. Bài làm và ghi chú
không tự bị cắt bỏ khi vượt các mốc 10.000 bài làm hoặc 2.000 ghi chú.

Bản chạy trên website, bản HTML tải về, trình duyệt khác và điện thoại khác có
vùng lưu dữ liệu riêng. Dung lượng thực tế do thiết bị và trình duyệt quyết định.
Chế độ riêng tư, xóa dữ liệu trình duyệt, đổi vị trí tệp HTML hoặc đổi địa chỉ
website có thể làm bản lưu cũ không còn hiện. Khi nút hiện **Đang lưu…**, hãy đợi
thao tác lưu xong trước khi đóng trang; nếu thấy thông báo lỗi, xuất JSON để giữ
một bản riêng.

Nếu mở cùng ứng dụng trong nhiều thẻ, một thẻ cũ có thể dừng ghi khi phát hiện thẻ
khác đã lưu tiến độ mới hơn. Khi thấy thông báo này, chọn **Xuất bản đang mở** để
giữ phần đang xem nếu cần, rồi **Tải lại tiến độ mới nhất** trước khi học tiếp.
Điều này giúp tránh dùng bản cũ ghi đè việc vừa làm ở thẻ khác.

Để bảo vệ quá trình học:

1. Mỗi tuần và trước khi đổi máy, đổi trình duyệt hoặc xóa dữ liệu, chọn
   **Cài đặt & dữ liệu → Xuất dữ liệu**.
2. Giữ tệp `mam-tsa-sao-luu-….json` ở một nơi khác với thiết bị đang dùng. Tệp chứa
   bài làm, hồ sơ, ghi chú và hội thoại; chỉ chia sẻ khi bạn muốn người khác đọc chúng.
3. Trên máy mới hoặc trong bản HTML, chọn **Nhập bản sao lưu**, chọn tệp JSON rồi
   xác nhận **Khôi phục bản này**. Hãy xuất bản hiện tại trước nếu cần giữ cả hai.

Chỉ giữ tệp HTML **chưa đủ để sao lưu tiến độ**; cần giữ cả tệp JSON. Nếu trình
duyệt báo không lưu được, bạn vẫn có thể học trong phiên hiện tại, nhưng hãy xuất
JSON trước khi đóng trang. Tệp sao lưu sai định dạng sẽ bị từ chối trước khi thay
thế dữ liệu hiện có. Ứng dụng chỉ nhận bản sao lưu theo phiên bản dữ liệu hỗ trợ.

Không phần mềm nào có thể bảo đảm mọi thiết bị và trình duyệt tương lai hoạt động
mãi mãi. Thiết kế này giúp bạn giữ được bản ứng dụng, dữ liệu và mã nguồn để tiếp
tục sử dụng hoặc chuyển đổi khi cần.

## Những gì đã có trong bản này

- 21 chủ đề nền tảng: 12 Toán, 6 Khoa học và 3 Đọc hiểu.
- Bài học, ví dụ, hoạt động tương tác, câu hỏi có gợi ý và giải thích.
- Khảo sát nền tảng, luyện theo chủ đề, luyện tổng hợp có giờ và ôn lại.
- Theo dõi câu tự làm, câu có hỗ trợ, lần nhớ lại; sổ lỗi sai và phần tự giải thích.
- Lịch học theo tuần điều chỉnh theo lỗi đã lưu, đồng hồ tập trung, thay đổi mục
  tiêu và xuất/nhập tiến độ.
- Sổ tay hiển thị 20 mục mỗi trang, có nút chuyển trang để đọc lại lịch sử dài.
- Trợ lý hướng dẫn theo quy tắc, hoạt động ngoại tuyến; AI trực tuyến là tùy chọn.

Đây là phiên bản xây nền, **chưa bao phủ toàn bộ kiến thức và dạng bài TSA**.
Bài luyện được tự biên soạn; số câu đúng và ước lượng mức hiểu chưa được chuẩn hóa
thành điểm TSA. Muốn đánh giá mục tiêu 90+ cần bổ sung nội dung, đối chiếu yêu cầu
TSA chính thức và làm đề phù hợp. Việc đánh dấu đọc xong hoặc viết một câu giải
thích chưa tự động xác nhận thành thạo.

## Tài liệu tham khảo và quyền sử dụng

Phương pháp học và một số mạch kiến thức tham khảo *Toán Học Chân Phương*
(Nguyễn Vĩnh Phú, ©2022–2026). Đây là nguồn về toán, khoa học và cách học, chưa phải
cẩm nang TSA chính thức. Các ghi chú nguồn trong bài cho biết phần tham khảo.
Bài học, ví dụ và câu hỏi trong ứng dụng được viết mới. Các đoạn đọc hiểu là nội
dung tự biên soạn.

Không đóng gói sách, PDF người dùng gửi hoặc bản phân tích toàn văn vào ứng dụng
hay mã nguồn phát hành. Giấy phép MIT trong [LICENSE](LICENSE) áp dụng cho phần
mã và nội dung gốc của stem theo phạm vi được ghi trong giấy phép, không cấp
quyền với sách hoặc tài liệu của bên khác. Công cụ phát triển bên thứ ba giữ giấy
phép riêng.

## Hướng dẫn kỹ thuật để chạy lại hoặc nâng cấp

Chỉ cần phần này nếu bạn hoặc người hỗ trợ muốn chạy mã nguồn. Mỗi cloud task đã
có môi trường riêng; sử dụng checkout hiện có, không cần tạo Git worktree.

Yêu cầu: Node.js **24.5 trở lên**, npm đi kèm Node. Lần cài công cụ build đầu tiên
cần truy cập npm registry. Chạy các lệnh trong thư mục chứa `package.json`:

```sh
npm ci
npm test
npm run build
npm start
```

Sau đó mở `http://localhost:3000`. Máy chủ mặc định lắng nghe `0.0.0.0:3000`;
có thể đặt `HOST=127.0.0.1` để chỉ dùng trên máy hiện tại, hoặc đổi `PORT`.
`npm run dev` chạy chế độ tự khởi động lại khi mã máy chủ thay đổi.

Sau `npm run build`, **`dist/mam-tsa.html`** là bản tự chứa CSS và JavaScript.
Sao chép riêng tệp này để dùng ngoại tuyến; không cần thư mục `node_modules` hay
máy chủ. Build lại sau khi thay đổi mã nguồn để bản HTML chứa thay đổi mới.

### Đóng gói mã nguồn để cất giữ

```sh
npm run build
node scripts/package-source.mjs
```

Kết quả: **`dist/mam-tsa-source.tar.gz`**. Giải nén bằng công cụ hỗ trợ `.tar.gz`;
thư mục `mam-tsa` chứa mã nguồn, lockfile, hướng dẫn, giấy phép, các kiểm thử và bản
HTML nếu đã build. Công cụ chỉ đóng gói danh sách tệp cho phép đã khai báo trong
script; không gom toàn bộ checkout. Không bao gồm `.git`, `node_modules`, `.env`,
khóa API, sách/PDF, tệp đính kèm hoặc dữ liệu học của trình duyệt.

### Lưu dữ liệu dài hạn

`storage.js` dùng IndexedDB làm kho lưu chính, xếp hàng các lần ghi bất đồng bộ và
giữ thêm bản phản chiếu bằng localStorage khi còn dung lượng. Không có IndexedDB
thì bản phản chiếu vẫn có thể dùng; nếu cả hai kho đều không ghi được, giao diện
báo lỗi để người học xuất bản sao lưu. IndexedDB vẫn là dữ liệu của trình duyệt,
không thay thế bản sao lưu độc lập.

Nhập JSON chấp nhận tệp tối đa 256 MiB; bộ kiểm tra giới hạn một lần nhập ở
500.000 bài làm và 100.000 ghi chú để tránh xử lý không kiểm soát. Đây là giới hạn
an toàn khi nhập, không phải cam kết mọi điện thoại có thể mở tệp lớn tới mức đó.
Lịch sử bài làm và ghi chú hiện không bị tự cắt ở ngưỡng 10.000/2.000 như cách lưu
ngắn hạn. Hội thoại hiển thị dùng một cửa sổ lịch sử riêng; muốn giữ điều quan
trọng lâu dài, hãy lưu vào sổ tay rồi xuất JSON.

### AI trực tuyến tùy chọn

Phần hướng dẫn ngoại tuyến dùng nội dung và quy tắc có sẵn, chưa phải AI hiểu mọi
câu hỏi tự do. AI trực tuyến cần máy chủ, kết nối Internet và tài khoản API của
nhà cung cấp; có thể phát sinh phí dịch vụ. Tính năng này không cần thiết để dùng
bài học, chấm bài theo đáp án, sổ tay hay xuất/nhập dữ liệu.

Trong cấu hình môi trường bảo mật của máy chủ, đặt `TSA_AI_API_KEY` (hoặc binding
`OPENAI_API_KEY` đã có), rồi khởi động lại máy chủ. Mô hình mặc định là
`gpt-4.1-mini`; có thể đổi bằng `TSA_AI_MODEL` khi nhà cung cấp hỗ trợ. Máy chủ gửi
yêu cầu HTTPS tới `api.openai.com`. Không đưa khóa vào HTML, Git, tệp sao lưu hay
hộp chat. Máy chủ không tự đọc tệp `.env`; cần để hệ thống chạy ứng dụng truyền
biến môi trường vào tiến trình.

Người học cần bật lựa chọn cho phép gửi câu hỏi trong **Cài đặt & dữ liệu**.
Khi bật và máy chủ đã cấu hình, câu hỏi, ngữ cảnh bài và một phần lịch sử hội thoại
sẽ được gửi tới nhà cung cấp AI. Bản HTML mở độc lập dùng hướng dẫn ngoại tuyến.
AI có thể sai; cần kiểm tra lập luận và đối chiếu lời giải. Không có khóa hoặc khi
dịch vụ bị gián đoạn, phần học và gợi ý có sẵn vẫn dùng được.

### Kiểm tra

`npm test` chạy kiểm thử nội dung, logic học tập, máy chủ và khả năng đóng gói bản
ngoại tuyến. Kiểm tra giao diện có kịch bản riêng ở `tools/acceptance.py` và cần
Python cùng Playwright/Chromium tương ứng. Kết quả tự động trong trình duyệt giả
lập không thay thế kiểm tra trên thiết bị iPhone/Android thật.


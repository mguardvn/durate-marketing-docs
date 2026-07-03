# TÀI LIỆU THIẾT LẬP THỬ NGHIỆM A/B TESTING & TRACKING SUITE — DURATE VIỆT NAM
## CHIẾN DỊCH MARKETING THÁNG 7/2026 (MÃ DỰ ÁN: DRT26-MKT-PLAN)

---

## Ⅰ. GIỚI THIỆU & ĐỊNH HƯỚNG CHIẾN LƯỢC

Tài liệu này định nghĩa chi tiết hướng dẫn thiết lập, thông số vận hành và kế hoạch đo lường cho hai thử nghiệm A/B cốt lõi trong chiến dịch Marketing tháng 7/2026 của Durate Việt Nam. Cả hai thử nghiệm đều được thiết kế dựa trên các sản phẩm truyền thông và trang đích đã được phê duyệt nhằm tối ưu hóa chi phí trên mỗi khách hàng tiềm năng chất lượng cao (CPL ≤ 450.000đ) và đạt mục tiêu tối thiểu 28 - 30 Qualified Leads.

Thành công của chiến dịch dựa trên sự phối hợp chặt chẽ giữa nội dung quảng cáo (Ad Copy Suite) và các trang đích thu thập lead (Landing Page Briefs), đồng thời tuân thủ nghiêm ngặt **7 Nguyên tắc A/B Testing** tiêu chuẩn ngành.

---

## Ⅱ. 7 NGUYÊN TẮC A/B TESTING ÁP DỤNG TRONG CHIẾN DỊCH

Để đảm bảo tính chính xác khoa học của các thử nghiệm và tránh các sai số thường gặp trong môi trường quảng cáo B2B, Durate áp dụng nhất quán các nguyên tắc sau:

1. **Test một biến duy nhất (Single Variable Test):** Chỉ thay đổi một yếu tố duy nhất giữa các phiên bản thử nghiệm (ví dụ: chỉ thay đổi định dạng creative trong Ads, hoặc chỉ thay đổi headline trên Landing Page). Tất cả các yếu tố khác như tệp đối tượng, ngân sách, nút bấm, và trang đích liên kết đều được giữ nguyên 100%.
2. **Giả thuyết có thể kiểm định (Testable Hypothesis):** Mọi thử nghiệm đều bắt đầu bằng một giả thuyết cụ thể định dạng: *"Nếu làm [thay đổi X], metric [Y] sẽ tăng [Z%]"*. Điều này giúp định hướng rõ ràng mục tiêu và dễ dàng đo lường sự thành công.
3. **Mẫu đủ lớn (Statistical Power & Sample Size):** Không dừng thử nghiệm sớm khi chưa đạt đủ số lượng mẫu (conversions hoặc visitors/impressions) cần thiết. Quy mô mẫu tối thiểu được tính toán khoa học dựa trên tỷ lệ chuyển đổi cơ sở (baseline conversion rate) và mức độ thay đổi tối thiểu muốn phát hiện (MDE).
4. **Thời gian chạy đủ lâu (Test Duration):** Chạy thử nghiệm theo các tuần trọn vẹn (tối thiểu 7 ngày, khuyến nghị 14 ngày) để loại bỏ sai số do hành vi người dùng thay đổi theo các ngày trong tuần (Seasonality).
5. **Không xem trước và dừng sớm (No Early Peeking & Stopping):** Tuyệt đối không kiểm tra kết quả hàng giờ và dừng chiến dịch khi thấy một phiên bản tạm thời dẫn trước. Kết quả chỉ được kết luận khi đã chạy hết thời hạn được xác định trước và đạt đủ kích thước mẫu.
6. **Ý nghĩa thống kê (Statistical Significance):** Chỉ công nhận kết quả thử nghiệm khi đạt độ tin cậy trên 95% (tức là chỉ số p-value < 0.05). Nếu p-value ≥ 0.05, kết quả được coi là ngẫu nhiên và giả thuyết bị bác bỏ.
7. **Tài liệu hóa (Documented):** Ghi chép chi tiết từ giả thuyết, thông số thiết lập, dữ liệu thu thập thực tế cho đến kết luận cuối cùng nhằm lưu trữ bài học kinh nghiệm, tránh thử nghiệm lặp lại các biến thể cũ.

---

## Ⅲ. THỬ NGHIỆM 1: A/B TEST CREATIVE TRÊN META ADS (CHO NHÓM MEP CONTRACTOR)

### 1. Mục tiêu & Giả thuyết thử nghiệm
*   **Mục tiêu:** Xác định xem định dạng quảng cáo nào (Hình ảnh Banner tĩnh vs. Video ngắn quay thực tế) mang lại Tỷ lệ nhấp (CTR - Click-Through Rate) cao hơn và Chi phí trên mỗi tin nhắn (CPMess) tối ưu hơn khi tiếp cận nhóm nhà thầu cơ điện MEP.
*   **Giả thuyết thử nghiệm:** *"Nếu thay thế hình ảnh Banner thiết kế tĩnh (Variant A) bằng Video dọc 9:16 quay thực tế quy trình sản xuất và xuất xưởng tại nhà máy Đông Anh (Variant B), Tỷ lệ nhấp (CTR) của nhóm đối tượng MEP Contractor sẽ tăng ít nhất 20%."*

### 2. Định nghĩa các Biến thể Thử nghiệm (Variants)
Để đảm bảo tính nhất quán và phản ánh chính xác các thông điệp cốt lõi đã được xây dựng, hai biến thể sáng tạo được xác định như sau:

*   **Biến thể A (Control - Image):**
    *   *Định dạng:* Ảnh thiết kế Banner tĩnh (kích thước 1:1 cho Feed và thích ứng dọc 9:16).
    *   *Nội dung Visual:* Bản vẽ mặt cắt kỹ thuật 3D của thiết bị AHU Durate hiển thị rõ ràng cấu trúc vỏ sandwich panel cách nhiệt PU 50mm chống cầu nhiệt (Thermal Bridge), kết hợp với quạt EC truyền động trực tiếp.
    *   *Thông điệp chính:* Tập trung vào tiêu chuẩn rò rỉ khí vỏ panel đạt cấp L1 (Eurovent) nhằm triệt tiêu rò rỉ khí (Casing Air Leakage) và cam kết tiến độ sản xuất giao hàng nhanh từ 2 - 4 tuần.
*   **Biến thể B (Challenger - Video):**
    *   *Định dạng:* Video dọc thời lượng 45 giây (tỷ lệ khung hình 9:16).
    *   *Nội dung Visual:* Video quay thực tế tại nhà máy Đông Anh. Cận cảnh kỹ sư lắp ráp vỏ panel PU cách nhiệt, lắp đặt quạt EC tiết kiệm điện và cảnh cẩu thiết bị AHU hoàn thiện lên xe container xuất xưởng chuyển đến dự án. Phụ đề lớn chạy liên tục suốt video.
    *   *Thông điệp chính:* Trải nghiệm thực tế năng lượng sản xuất nội địa, nhấn mạnh tiến độ giao hàng thần tốc 2 - 4 tuần để cứu nguy cho các dự án MEP đang bị dồn tiến độ bàn giao.

### 3. Tệp Đối tượng Mục tiêu (Target Audience - Nhóm 1)
Tệp đối tượng được cấu hình đồng nhất cho cả hai nhóm thử nghiệm trên Meta Ads Manager:
*   **Vị trí địa lý:** Việt Nam (Tập trung trọng điểm tại các tỉnh/thành công nghiệp phía Bắc: Hà Nội, Bắc Ninh, Hưng Yên, Hải Phòng, Quảng Ninh, Bắc Giang và phủ các tỉnh phía Nam: TP.HCM, Bình Dương, Đồng Nai).
*   **Độ tuổi & Giới tính:** Nam, từ 30 đến 50 tuổi.
*   **Chức danh (Job Titles):** *Project Manager*, *Kỹ sư cơ điện*, *MEP Engineer*, *Site Manager*, *Giám đốc dự án*, *Trưởng phòng vật tư*, *Procurement Manager*.
*   **Sở thích & Hành vi:** *Hệ thống thông gió (Ventilation)*, *Điều hòa không khí (HVAC)*, *M&E Contractor*, *Cơ điện*, *Xây dựng*, *Quản lý dự án xây dựng*, *Phòng sạch (Cleanroom)*.

### 4. Tính toán Quy mô Mẫu & Thời gian chạy
Để đo lường sự chênh lệch CTR giữa hai biến thể sáng tạo với mức độ tin cậy cao:
*   **Tỷ lệ CTR cơ sở (Baseline CTR - p):** Ước tính dựa trên các chiến dịch B2B tương tự của Durate là **1.5%** (p = 0.015).
*   **Minimum Detectable Effect (MDE):** **40%** (tương đương với mức tăng hoặc giảm tuyệt đối là 0.6%, tức là CTR mục tiêu cần phát hiện là 2.1% hoặc 0.9%).
*   **Công thức tính toán quy mô mẫu (Impressions/Variant):**
    $$Sample\ size\ per\ variant = \frac{16 \times p \times (1 - p)}{MDE_{abs}^2}$$
    Thay số với $MDE_{abs} = 0.006$:
    $$Sample\ size\ per\ variant = \frac{16 \times 0.015 \times 0.985}{0.006^2} = \frac{0.2364}{0.000036} \approx 6,567\ impressions$$
*   **Tổng số lượt hiển thị cần thiết (Total Impressions):** $6,567 \times 2 = 13,134$ lượt hiển thị.
*   **Xác định thời gian chạy thử nghiệm:**
    *   Với ngân sách phân bổ cho nhóm Meta Ads tuần 1 là 1.200.000đ (trong đó phần chạy test creative chiếm khoảng 800.000đ cho cả hai nhóm, tương đương ~114.000đ/ngày).
    *   Giá mỗi 1.000 lượt hiển thị (CPM) dự kiến trong tệp B2B này là 80.000đ.
    *   Số lượt hiển thị trung bình mỗi ngày: $\frac{114.000}{80.000} \times 1.000 \approx 1,425$ lượt hiển thị/ngày cho toàn chiến dịch (khoảng 712 lượt hiển thị/ngày cho mỗi biến thể).
    *   **Tính toán thời gian tối thiểu để đạt đủ mẫu:** $\frac{13.134}{1.425} \approx 9.2$ ngày.
    *   **Khuyến nghị tối ưu hóa kỹ thuật (Specialist Insights):** Bằng việc nâng MDE lên 40% (chỉ phát hiện các thay đổi lớn có ý nghĩa thực tế cao đối với B2B), thời gian kiểm thử được rút ngắn từ 36.8 ngày xuống còn **9.2 ngày** (khả thi trong 10 ngày chạy đầu tiên của chiến dịch mà không cần tăng ngân sách).


### 5. Hướng dẫn Thiết lập Tránh Thiên lệch (Placement Specific Formatting & Placement Isolation)
Để hệ thống Meta Ads không tự động phân bổ ngân sách lệch cho biến thể dễ cắn tiền hơn (gây sai số), kỹ sư thiết kế chiến dịch phải tuân thủ hướng dẫn thiết lập sau:
*   **Sử dụng Trình thử nghiệm A/B tích hợp sẵn của Meta (Meta's built-in A/B Testing Tool):** Thay vì tự thiết lập hai Nhóm quảng cáo (Ad Sets) thủ công sử dụng ngân sách nhóm (ABO) — vốn dễ gây ra tình trạng trùng lặp đối tượng (audience overlap) và tự cạnh tranh đấu giá (auction self-competition), dẫn đến việc đẩy chi phí CPM lên cao và làm lệch kết quả — kỹ sư thiết kế chiến dịch bắt buộc phải sử dụng **Trình thử nghiệm A/B tích hợp sẵn của Meta** (thiết lập thông qua Thử nghiệm/Experiments Tool hoặc tạo trực tiếp trong trình quản lý quảng cáo). Công cụ này sẽ tự động chia đôi lưu lượng truy cập ở cấp độ ID người dùng (User ID level), đảm bảo 100% không trùng lặp đối tượng quảng cáo và loại bỏ hoàn toàn hiện tượng tự cạnh tranh giữa hai biến thể Variant A (Ảnh Banner tĩnh) và Variant B (Video thực tế).
*   **Định dạng chuẩn theo từng vị trí (Placement-Specific Formatting):**
    *   Đối với *Biến thể A (Banner tĩnh)*: Cung cấp hai phiên bản thiết kế: Tỷ lệ 1:1 (1080x1080px) dành cho các vị trí hiển thị trên Feeds (Facebook Feed, Instagram Feed); và Tỷ lệ 9:16 (1080x1920px) dành cho Stories và Reels.
    *   Đối với *Biến thể B (Video)*: Thiết kế chuẩn 9:16 (1080x1920px) cho Stories/Reels. Đối với vị trí Feeds, cấu hình video hiển thị ở dạng 4:5 để tận dụng tối đa diện tích màn hình di động mà không bị cắt cúp nội dung.
*   **Cô lập Vị trí hiển thị trên Thiết bị Di động (Mobile Feed Placement Isolation):**
    *   *Lý do:* Hành vi nhấp chuột của người dùng trên Feeds di động có độ ổn định và chất lượng lead cao hơn rất nhiều so với Audience Network hoặc Stories. Định dạng Video thường được ưu tiên phân phối trên Reels/Stories, trong khi Banner tĩnh dễ phân phối trên Feeds. Sự khác biệt về vị trí hiển thị này sẽ phá vỡ Nguyên tắc 1 (chỉ test 1 biến).
    *   *Giải pháp:* Cấu hình cài đặt vị trí hiển thị thủ công (Manual Placements). Chỉ chọn duy nhất vị trí **Facebook Mobile News Feed** và **Instagram Mobile Feed**. Tắt toàn bộ các vị trí hiển thị khác (Stories, Reels, Right Column, Marketplace, Messenger, Audience Network). Điều này đảm bảo 100% traffic của cả 2 biến thể đều xuất phát từ cùng một ngữ cảnh trải nghiệm trên di động của khách hàng.

### 6. Cấu hình Tracking & Sự kiện chuyển đổi
*   **Nền tảng:** Trình quản lý quảng cáo Meta (Meta Ads Manager) kết hợp dữ liệu Pixel trên trang đích.
*   **Theo dõi Sự kiện (Events):**
    *   `Impressions` (Lượt hiển thị) và `Link Clicks` (Lượt nhấp liên kết) để tính CTR.
    *   `ButtonClicks` (Chat Zalo/Hotline) hoặc `Lead` (gửi form thành công trên Landing Page Báo Giá) để đánh giá tỷ lệ chuyển đổi cuối cùng.
*   **UTM Tagging:**
    *   Nhóm quảng cáo A (Variant A): `utm_source=facebook&utm_medium=cpc&utm_campaign=test-creative&utm_content=banner-static`
    *   Nhóm quảng cáo B (Variant B): `utm_source=facebook&utm_medium=cpc&utm_campaign=test-creative&utm_content=video-factory`

### 7. Chỉ số Quyết định (Decision Metrics)
*   **Chỉ số chính (Primary Metric):** Click-Through Rate (CTR) của liên kết.
*   **Chỉ số phụ (Secondary Metrics):** Cost Per Click (CPC), Cost Per Lead (CPL), Tỷ lệ chuyển đổi ra Lead (CVR).
*   **Quy tắc ra quyết định:**
    *   Sau 14 ngày chạy, trích xuất số liệu Lượt hiển thị (Impressions) và Lượt nhấp (Clicks) của từng biến thể.
    *   Sử dụng công cụ kiểm định Chi-square (ví dụ Evan Miller) để tính p-value.
    *   Nếu **p-value < 0.05** và Biến thể B có CTR cao hơn Biến thể A: Biến thể B thắng cuộc. Tuyên bố Biến thể B là người chiến thắng trong Trình thử nghiệm A/B của Meta để hệ thống tự động chuyển toàn bộ ngân sách sang định dạng Video và áp dụng kịch bản video này cho các chiến dịch quy mô lớn hơn với các nhóm đối tượng khác.
    *   Nếu **p-value < 0.05** nhưng Biến thể A có CTR cao hơn: Giữ lại Banner tĩnh làm creative chính.
    *   Nếu **p-value ≥ 0.05**: Sự khác biệt không có ý nghĩa thống kê. Giữ lại biến thể có chi phí trên mỗi lead (CPL) thực tế thấp hơn hoặc tiếp tục chạy thêm 7 ngày để thu thập thêm mẫu.

---

## Ⅳ. THỬ NGHIỆM 2: A/B TEST LANDING PAGE HEADLINE (CHO WHITEPAPER TCO)

### 1. Mục tiêu & Giả thuyết thử nghiệm
*   **Mục tiêu:** Xác định xem thông điệp Headline nào trên màn hình đầu tiên (Hero Section) của Landing Page "LP-01-TCO-GMP" mang lại Tỷ lệ chuyển đổi điền form tải Whitepaper (CVR) cao nhất đối với nhóm đối tượng Ban bảo trì nhà máy và Nhà thầu MEP.
*   **Giả thuyết thử nghiệm:** *"Nếu sử dụng tiêu đề tập trung vào lợi ích tài chính và ROI (Headline B - Kinh tế/TCO), tỷ lệ chuyển đổi sẽ cao hơn 40% so với tiêu đề tập trung vào tiến độ giao hàng nhanh và loại bỏ rủi ro dừng chuyền (Headline C - Tiến độ/Downtime)."*

### 2. Định nghĩa hai Headline Copy cụ thể
Mọi thành phần khác trên trang đích (bố cục, hình ảnh mockup 3D của Whitepaper, các trường thông tin trong form, nút bấm CTA "Tải báo cáo ngay") đều được giữ nguyên đồng nhất. Chỉ thay đổi duy nhất nội dung văn bản Headline chính tại Hero Section:

*   **Headline B (Economic/Cost Focus - Challenger 1):**
    > *"Cắt giảm đến 22% chi phí điện năng vận hành AHU phòng sạch — Tải ngay báo cáo phân tích TCO."*
*   **Headline C (Progress/Downtime Focus - Challenger 2):**
    > *"Giao AHU phòng sạch GMP từ 2-4 tuần — Loại bỏ rủi ro dừng chuyền sản xuất."*

### 3. Nguồn Traffic & Phương pháp Phân đoạn (Traffic Sources & Segmenting)
Thử nghiệm sẽ nhận lưu lượng truy cập từ hai nguồn chính: Google Search Ads (Search Intent) và Meta Ads (Discovery Intent).
Hệ thống phân đoạn traffic được thiết lập như sau:
*   **Cài đặt Split Traffic:** Sử dụng công cụ kiểm thử A/B (như Convert.com, VWO, hoặc một đoạn mã redirect Javascript chạy trên Cloudflare) để chia đều lưu lượng truy cập đổ vào Landing Page thành 2 phần bằng nhau (50% / 50%) ứng với 2 phiên bản Headline B và C.
*   **Ghi nhận Variant ID:** Khi một người dùng truy cập trang, hệ thống kiểm thử sẽ tự động gán cho người dùng đó một Cookie chứa ID của biến thể họ đã xem (ví dụ: `page_variant = B` hoặc `C`). Cookie này sẽ tồn tại trong 30 ngày để đảm bảo người dùng quay lại vẫn thấy đúng headline cũ.

### 4. Tính toán Quy mô Mẫu & Thời gian chạy
*   **Tỷ lệ chuyển đổi cơ sở (Baseline CVR - p):** Mục tiêu CVR điền form tải tài liệu kỹ thuật trên Landing Page là **8.0%** (p = 0.08).
*   **Minimum Detectable Effect (MDE):** **40%** (tương đương với mức tăng hoặc giảm tuyệt đối là 3.2%, tức là CVR mục tiêu cần phát hiện để kết luận thắng thua là 11.2% hoặc 4.8%).
*   **Công thức tính toán quy mô mẫu (Visitors/Variant):**
    n = [16 * p * (1 - p)] / (MDE_abs^2)
    Thay số với MDE_abs = 0.032:
    n = [16 * 0.08 * 0.92] / (0.032^2) = 1.1776 / 0.001024 = 1,150 visitors per variant.
*   **Tổng số lượt truy cập (Visitors) cần thiết cho thử nghiệm 2 biến thể:**
    Total Visitors = 1,150 * 2 = 2,300 visitors.
*   **Thời gian chạy thử nghiệm thực tế:**
    *   Với tổng ngân sách thực tế tháng 7/2026, lượng traffic ước tính đạt khoảng 75 lượt truy cập/ngày.
    *   Thời gian chạy thử nghiệm để đạt đủ quy mô mẫu: 2,300 / 75 = 30.7 ngày. Thử nghiệm sẽ chạy song song xuyên suốt chiến dịch tháng 7 để đạt ý nghĩa thống kê đầy đủ.
*   **Giao thức Kiểm tra Ngày thứ 7 (Day-7 Check-in Protocol):**
    *   *Bối cảnh rủi ro:* CVR thực tế của trang đích đối với cold traffic có thể thấp hơn dự đoán (dưới 3%). Nếu điều này xảy ra, quy mô mẫu yêu cầu cho MDE 40% sẽ tăng vọt, khiến thử nghiệm không thể hoàn tất trong 30 ngày.
    *   *Quy trình ứng phó khẩn cấp tại Ngày thứ 7:* Nếu CVR điền form (`lead_submit`) dưới 3%, chuyển đổi chỉ số đo lường chính (Primary Metric) từ tỷ lệ gửi form thành công sang tỷ lệ chuyển đổi vi mô (Micro-conversion) như tỷ lệ nhấp chuột vào nút kêu gọi hành động mở form (`form_start` hoặc click nút "Tải báo cáo"). Do hành vi vi mô này có tỷ lệ thực hiện cao hơn (>15%), quy mô mẫu yêu cầu sẽ giảm mạnh xuống dưới 600 visitors/variant (tổng 1,200 visitors), đảm bảo thu được kết quả thống kê có ý nghĩa trong 28 ngày.

### 5. Quy trình phân đoạn kỹ thuật trong GA4 & Meta Pixel
Để đo lường hiệu quả độc lập của từng Headline theo từng nguồn traffic, chuyên viên tracking cài đặt cấu hình như sau:

*   **Truyền tham số Variant vào GA4:**
    *   Sử dụng Google Tag Manager (GTM) để đọc giá trị của Cookie `page_variant` (B hoặc C).
    *   Cấu hình một biến tùy chỉnh (Custom Dimension) trong GA4 cấp độ sự kiện tên là `page_variant`.
    *   Mỗi khi sự kiện `page_view` hoặc `form_submit` được kích hoạt, giá trị của `page_variant` (ví dụ: `Headline_B`, `Headline_C`) sẽ được gửi kèm lên GA4.

*   **Truyền tham số Variant vào Meta Pixel:**
    *   Sử dụng đoạn mã Custom Event của Meta Pixel khi người dùng gửi form thành công:
        ```javascript
        fbq('track', 'Lead', {
            content_name: 'Whitepaper TCO AHU',
            page_version: 'Headline_B', // Biến động đọc từ Cookie
            traffic_source: 'Facebook Ads'
        });
        ```
*   **Lập báo cáo Phân đoạn (Segmentation Report) trong GA4:**
    *   Trong mục Khám phá (Explorations) của GA4, dựng một bảng chéo (Crosstab) với:
        *   *Dòng (Rows):* `Session source / medium` (để phân biệt google / cpc vs facebook / cpc).
        *   *Cột (Columns):* Custom dimension `page_variant` (Headline_B, Headline_C).

        *   *Chỉ số (Values):* `Sessions` (Lượt truy cập) và `Conversions: lead_submit` (Lượt điền form thành công).
    *   Báo cáo này sẽ tự động phân tách số liệu như sau:
        *   Google Search Ads mang lại bao nhiêu visit cho Bản B/C và tỷ lệ chuyển đổi tương ứng là bao nhiêu.
        *   Meta Ads mang lại bao nhiêu visit cho Bản B/C và tỷ lệ chuyển đổi tương ứng là bao nhiêu.


### 6. Cấu hình Tracking Sự kiện (Events) chi tiết
Các sự kiện chuyển đổi trên Landing Page "LP-01-TCO-GMP" được theo dõi bắt buộc theo bảng sau:

| Tên sự kiện | Định nghĩa kỹ thuật | Nền tảng ghi nhận | Cách thức cấu hình trong GTM |
| :--- | :--- | :--- | :--- |
| `page_view` | Khi trang tải thành công trên trình duyệt của người dùng. | GA4 + Meta Pixel | Trigger: Page View, Page URL chứa `/ahu-whitepaper-tco` |
| `form_start` | Khi người dùng nhấp chuột vào ô nhập liệu đầu tiên trong Form (Họ tên). | GA4 | Trigger: Click/Focus, Form Element ID = `tco-lead-form` |
| `lead_submit` | Khi người dùng nhấn nút gửi form và hệ thống trả về thông báo thành công (hoặc chuyển hướng sang `/thank-you-tco`). | GA4 (`lead_submit`) + Meta Pixel (`Lead`) | Trigger: Form Submission thành công, hoặc Element Visibility của thông báo thành công. |
| `click_zalo` | Khi người dùng nhấn vào nút chat Zalo OA ở chân trang. | GA4 | Trigger: Click Link, URL chứa `zalo.me/` |
| `click_hotline`| Khi người dùng nhấn vào số điện thoại Hotline. | GA4 | Trigger: Click Link, URL chứa `tel:` |

### 7. Chỉ số Quyết định (Decision Metrics) cho từng kênh
*   **Chỉ số chính (Primary Metric):** Conversion Rate (CVR) - Tỷ lệ điền form tải tài liệu trên số lượt truy cập trang (LPV).
*   **Quy tắc ra quyết định phân đoạn (Segmented Decision Rules):**
    *   **Đối với Google Search Traffic:** Nếu kết quả phân đoạn cho thấy `Headline_B` (Kinh tế) có CVR cao vượt trội so với `Headline_C` và đạt p-value < 0.05, hệ thống sẽ tự động cấu hình `Headline_B` làm tiêu đề mặc định 100% cho toàn bộ traffic đến từ Google Search.

    *   **Đối với Meta Ads Traffic:** Nếu kết quả phân đoạn cho thấy `Headline_C` (Tiến độ/Downtime) có CVR cao nhất và đạt p-value < 0.05, hệ thống sẽ cấu hình `Headline_C` làm tiêu đề mặc định cho các quảng cáo từ Meta Ads.
    *   *Trường hợp không đạt ý nghĩa thống kê (p-value ≥ 0.05):* Giữ nguyên Headline B (Kinh tế) làm mặc định chung vì đây là thông điệp sát với bài toán chi phí vận hành TCO của cuốn Whitepaper nhất.

---

## Ⅴ. HƯỚNG DẪN CÀI ĐẶT TRACKING VÀ TÍCH HỢP DỮ LIỆU ĐỒNG BỘ

Để đảm bảo toàn bộ dữ liệu từ 2 thử nghiệm được thu thập chuẩn xác và chuyển về bộ phận bán hàng xử lý tức thì, quy trình tích hợp được thiết lập theo sơ đồ dưới đây:

```
[Khách hàng điền Form trên LP]
        │
        ├──> [Gửi Event 'Lead' về Meta Pixel & Google Analytics 4 (kèm Cookie Variant ID & UTM)]
        │
        ├──> [Webhook đẩy dữ liệu thời gian thực (Real-time Webhook)]
        │          │
        │          ├──> [Google Sheets Master Lead List (Lưu trữ toàn bộ data + UTM + Variant ID)]
        │          │
        │          └──> [Zalo Group SE Alert (Thông báo khẩn cấp cho Kỹ sư bán hàng sau 10 giây)]
        │
        └──> [Hệ thống Auto-Email Brevo (Gửi link tải Whitepaper tự động vào hòm thư khách hàng)]
```

### 1. Quy tắc đặt tên UTM (UTM Naming Convention)
Mọi chiến dịch quảng cáo trỏ về các trang đích thử nghiệm phải tuân thủ cấu trúc UTM viết thường, không dấu, liên kết bằng dấu gạch ngang:
*   *Chiến dịch Meta Ads Nhóm 1:* `utm_source=facebook&utm_medium=cpc&utm_campaign=drt-mep-july2026&utm_content=video-factory` (hoặc `banner-static`)
*   *Chiến dịch Google Search Nhóm 1:* `utm_source=google&utm_medium=cpc&utm_campaign=drt-search-ahu-brand&utm_term=bao-gia-ahu`

### 2. Định dạng dữ liệu đẩy về Google Sheets
Bảng lưu trữ lead phải tự động thu thập các trường sau để phục vụ đối chiếu thử nghiệm cuối tháng:
1.  `Timestamp` (Thời gian đăng ký)
2.  `Họ và tên`
3.  `Số điện thoại`
4.  `Email`
5.  `Tên công ty / Dự án`
6.  `UTM Source`
7.  `UTM Medium`
8.  `UTM Campaign`
9.  `UTM Content` / `UTM Term`
10. `Page Variant` (Biến thể Headline người dùng đã nhìn thấy: B hoặc C)


---

## Ⅵ. KẾ HOẠCH BÀN GIAO & LỊCH TRÌNH THỰC THI (TIMELINE)

Để đảm bảo thử nghiệm diễn ra đúng tiến độ của Master Plan tháng 7/2026:

*   **Giai đoạn 1: Chuẩn bị & Setup (03/07/2026 - 05/07/2026)**
    *   Lập trình 2 phiên bản Landing Page với 2 Headline khác nhau (B và C) trên hệ thống quản trị.
    *   Cài đặt Google Tag Manager, cấu hình cookie phân tách traffic và biến thể truyền lên GA4/Meta Pixel.
    *   Kiểm thử gửi lead ảo từ nhiều thiết bị để xác nhận Webhook và UTM được ghi nhận đúng trên Google Sheets.
*   **Giai đoạn 2: Khởi chạy & Thu thập dữ liệu (06/07/2026 - 20/07/2026)**
    *   Bật chiến dịch Google Search Ads và Meta Ads trỏ link về hệ thống phân tách traffic.
    *   Giám sát hàng ngày chỉ số phân bổ traffic để đảm bảo tỷ lệ split đạt đúng 50/50 cho cả Ad Creative và LP Headline.
    *   *Lưu ý:* Tuyệt đối không can thiệp thay đổi nội dung quảng cáo hay trang đích trong suốt 14 ngày này để tránh làm hỏng dữ liệu.

*   **Giai đoạn 3: Phân tích & Quyết định (21/07/2026 - 23/07/2026)**
    *   Xuất toàn bộ báo cáo từ GA4, Meta Ads Manager và Google Sheets Lead List.
    *   Chạy kiểm định thống kê Chi-square cho cả hai thử nghiệm.
    *   Lập báo cáo nghiệm thu gửi Ban giám đốc và cấu hình các biến thể chiến thắng (Winner) chạy mặc định 100% cho tuần cuối tháng 7 và chuẩn bị cho chiến dịch tháng 8.

---

## Ⅶ. BIỆN PHÁP PHÒNG NGỪA RỦI RO & PHÒNG THỦ DỮ LIỆU

Trong quá trình chạy thử nghiệm B2B, các rủi ro sau có thể xảy ra và cần được xử lý theo hướng dẫn:

1.  **Rủi ro Spam / Đối thủ phá hoại click ảo:**
    *   *Hiện tượng:* Đối thủ hoặc bot click liên tục vào quảng cáo Google Search hoặc Meta khiến ngân sách cạn kiệt nhanh và làm sai lệch tỷ lệ chuyển đổi.
    *   *Biện pháp xử lý:* Cấu hình chặn IP click ảo trên Google Ads. Đối với Landing Page, tích hợp mã bảo vệ Google reCAPTCHA v3 (dạng ẩn không gây phiền hà cho người dùng) để lọc bot đăng ký form ảo.
2.  **Lỗi lệch phân bổ traffic (Imbalanced Traffic Splitting):**
    *   *Hiện tượng:* Công cụ split traffic phân bổ không đều (ví dụ: Bản A nhận 70% traffic, Bản B chỉ nhận 30% traffic).
    *   *Biện pháp xử lý:* Kiểm tra lại cấu hình cookie lưu trữ phiên làm việc của người dùng. Nếu phát hiện lệch quá 5% lượng traffic sau 3 ngày chạy đầu tiên, dừng thử nghiệm, reset cookie và chuyển sang phương pháp phân bổ thủ công qua các link chiến dịch UTM riêng biệt.
3.  **Lỗi không ghi nhận được UTM trên thiết bị di động:**
    *   *Hiện tượng:* Trình duyệt trong ứng dụng (In-app Browser) của Facebook/Zalo tự động cắt bỏ các tham số UTM ở đuôi URL khi người dùng nhấp vào link quảng cáo.
    *   *Biện pháp xử lý:* Cấu hình lưu trữ các tham số UTM vào `SessionStorage` của trình duyệt ngay khi trang vừa tải lần đầu, đảm bảo dù URL bị chuyển hướng hay cắt bỏ tham số, thông tin UTM vẫn được giữ lại để gửi đi cùng form đăng ký.
4.  **Rủi ro thiếu hụt mẫu do tỷ lệ chuyển đổi thực tế thấp hơn dự báo:**
    *   *Hiện tượng:* Tỷ lệ chuyển đổi (CVR) thực tế trên Landing Page trong tuần đầu tiên quá thấp (dưới 3%), làm phình to lượng mẫu yêu cầu và kéo dài thời gian test quá thời hạn 28 ngày của chiến dịch.
    *   *Biện pháp xử lý:* Áp dụng nghiêm ngặt **Giao thức Kiểm tra Ngày thứ 7 (Day-7 Check-in Protocol)** (định nghĩa chi tiết tại Mục IV.4). Thực hiện pivot rút gọn số lượng biến thể (loại bỏ Headline C) hoặc chuyển chỉ số đo lường chính sang chuyển đổi vi mô (Micro-conversion) để đảm bảo thu được kết quả có ý nghĩa thống kê đúng hạn.

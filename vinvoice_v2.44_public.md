

**TẬP ĐOÀN VIỄN THÔNG QUÂN ĐỘI VIETTEL**

	  
**TÀI LIỆU MÔ TẢ WEBSERVICE**   
**HÓA ĐƠN ĐIỆN TỬ**

**Hà Nội, 11/2024**  
**BẢNG GHI NHẬN THAY ĐỔI**

| Phiên bản | Ngày | Chi tiết |
| :---: | :---: | ----- |
| 0.1 | 09/2017 | Phiên bản khởi tạo |
| 0.2 | 03/2018 | Bổ sung thêm mục 2.1.11, 2.1.12, 2.1.13 |
| 0.3 | 09/2018 | Bổ sung thêm 2.1.14, 2.1.15 |
| 1.0 | 09/2018 | Bổ sung thêm chi tiết đặc tả bản tin, tổ chức lại tài liệu |
| 1.1 | 04/2019 | Bổ sung mục 7 mapping trường thông tin và mẫu hóa đơn |
| 2.4 | 05/2022 | Bổ sung mô tả thêm các trường của phiếu xuất kho TT78 ở mục 6.9 Metadata,  File json ví dụ tại mục 7.2 |
| 2.5 | 06/2022 | \- Bổ sung thêm trường lý do huỷ hoá đơn ở mục 7.6 \- Bổ sung thêm trường lý do sai sót hoá đơn điều chỉnh thay thế ở mục 6.2 generaIInvoiceInfo, File json tại mục 7.2 và mục 7.15 \- Bổ sung cho truyền giá trị âm số lượng/đơn giá ở mục 6.6 itemInfo \- Bổ sung thêm trường Điều chỉnh hóa đơn không tồn tại qua API ở mục 6.2 generaIInvoiceInfo, File json tại mục 7.2 và mục 7.15 |
| 2.6 | 09/2022 | \- Thêm mới 6.12 QRcode \- Thêm mới 7.22 Cấp mã bí mật \- Thêm mới 7.25 Cập nhật trạng thái in hoá đơn \- Thêm mới 7.26 Số lần quét QRcode của hoá đơn |
| 2.7 | 09/2022 | \- Bổ sung thêm trường thông tin cho phép tìm kiếm hóa đơn theo ngày phát hành ở mục 7.7 \- Bổ sung thêm hình thức thanh toán ở mục 6.5 \- Thêm mới 7.27. Api thống kê hóa đơn theo user |
| 2.8 | 9/2022 | \- Bổ sung cho truyền thêm Mã bí mật đã được cấp cho MST ở mục 6.2 generaIInvoiceInfo \- Bổ sung Đồng bộ ghi chú/ cho truyền itemNote ở mục 6.6 itemInfo |
| 2.9 | 11/2022 | \- Api giải trình mục 7.26 |
| 2.10 | 11/2022 | \- Bổ sung nội dung mục 7.2 và 7.15: thêm trong generalInvoiceInfo 2 thẻ : originalInvoiceType và originalTemplateCode \- Thêm mới mục 7.26: lấy danh sách mẫu và ký hiệu hóa đơn theo mã số thuế |
| 2.11 | 12/2022 | \- Bổ sung nội dung thực hiện thay đổi cách lưu dữ liệu khi lập hóa đơn với hàng hóa có tính chất Ghi chú ở mục 6.7 \- Bổ sung nội dung cho phép điều hỉnh thông tin hàng hóa itemInfo ở mục 6.6 \- Bổ sung nội dung đường link tra cứu hóa đơn gửi mail cho người mua ở mục 7.14 |
| 2.12 | 12/2022 | \- Thêm mới nội dung: API phát hành hóa đơn có mã số bí mật mục 7.28 và 7.29 |
| 2.13 | 1/2023 | \- Bổ sung mô tả quy tắc truyền ký hiệu hóa đơn trong generalInvoiceInfo mục 6.2 |
| 2.14 | 3/2023 | \- Thêm mới API lấy danh sách mẫu và ký hiệu hóa đơn theo mã số thuế trên toàn hệ thống mục 7.30 |
| 2.15 | 3/2023 | \- Bổ sung mô tả quy tắc kiểm tra ngày lập hóa đơn mục 7.2, 7.9, 7.15 và 7.28 |
| 2.16 | 3/2023 | \- Bổ sung thêm tiêu chuẩn bảo mật kết nối: API kết nối được mã hóa sử dụng giao thức https với xác thực bằng Basic Auth mục 5.5 \- Bổ sung thông tin tài khoản test mục 5.6 \- Thêm trường adjustAmount20, invoiceNote mục 6.2 \- Cập nhật mô tả trường buyerNotGetInvoice mục 6.4 \- Thay đổi maxlength batchNo từ 50 lên 300, itemNote từ 100 lên 300  mục 6.6 \- Cập nhật đúng thông tin trường selection mục 6.6 \- Thay đổi maxlength của stringValue từ 13 lên 300 mục 6.9 \- Bổ sung Phiếu bán hàng phi thuế quan mục 6.9 \- Cập nhật format của strIssueDate, additionalReferenceDate từ 4.1 lên 5.1 mục 7.5, 7.10, 7.18, 7.19, 7.26 |
| 2.17 | 30/03/2023 | \- Cập nhật đổi tên cấu hình “Ngày ký là thời điểm hiện tại” thành “Cho phép ngày lập hóa đơn khác ngày hiện tại” mục 7.2, 7.9, 7.15, 7.28 |
| 2.18 | 13/04/2023 | \- Tăng mã số bí mật lên 30,000 mục 7.22 \- Nâng cấp đấu nối với BCCS mục 7.31 |
| 2.19 | 18/04/2023 | \- Bổ sung thông tin truyền vào khi lập và xem hóa đơn nháp điều chỉnh/thay thế cho hóa đơn giấy (ngoài hệ thống) mục 7.8, 7.20 |
| 2.20 | 05/05/2023 | \- Bỏ nội dung Nâng cấp đấu nối với BCCS mục 7.31 |
| 2.21 | 26/05/2023 | Bổ sung thông tin Lưu ý mục 7.3, 7.4, 7.5 – Nâng cấp tải file từ API Thêm mới 7.31 – Phát hành/thay thế/điều chỉnh cho CLOUD CA (Bước 1: Lấy chuỗi hash) Thêm mới 7.32 – Phát hành/thay thế/điều chỉnh cho CLOUD CA (Bước 2: Ký Cloud CA và sinh hóa đơn) Thêm mới 7.33 – Phát hành hóa đơn có mã bí mật cho CLOUD CA Bổ sung thông tin Lưu ý mục 7.2, 7.8, 7.9, 7.15, 7.16, 7.28 \- Cho phép ghi nhận giá trị tổng tiền hàng trước thuế khi lập hóa đơn qua API (không tự tính lại) với các khách hàng tích bỏ ràng buộc dữ liệu. Bổ sung thông tin Lưu ý mục 7.2, 7.9. 7.16, 7.28 \- Trả về mã CQT ở trường codeOfTax Bổ sung thông tin lưu ý mục 7.2, 7.9, 7.28 \- Cho phép dùng CKS usb và    cloudCA phát hành hóa đơn máy tính tiền bằng api server |
| 2.22 | 27/05/2023 | Xóa bỏ: “Bổ sung thông tin Lưu ý mục 7.2, 7.8, 7.9, 7.15, 7.16, 7.28 \- Cho phép ghi nhận giá trị tổng tiền hàng trước thuế khi lập hóa đơn qua API (không tự tính lại) với các khách hàng tích bỏ ràng buộc dữ liệu.”  Cập nhật thông tin mục 4 |
| 2.23 | 12/07/2023 | Bổ sung thông tin trường validation trong mục 6.2 Bổ sung thông tin lưu ý các mục 7.2, 7.8, 7.9, 7.15, 7.20, 7.28, 7.29, 7.31, 7.33 – Lưu ý việc việc truyền tham số validation trong phần generalInvoiceInfo của dữ liệu hóa đơn. |
| 2.24 | 29/07/2023 | Cập nhật thông tin cho trường adjustAmount20 trong mục 6.2 Bổ sung thông tin trường adjustRatio trong mục 6.6 |
| 2.25 | 11/09/2023 | Bổ sung bộ mã lỗi hay gặp khi sử dụng API tích hợp – mục 8 |
| 2.26 | 13/10/2023 | Thêm mới API gửi email hóa đơn cho khách hàng dành cho máy POS – mục 7.34 |
| 2.27 | 26/10/2023 | Thẻ metadata trường stringValue sửa maxlength từ 300 lên 500 theo Quyết định 1510 – mục 6.9 |
| 2.28 | 1/11/2023 | Bỏ đường link hướng dẫn của V1 mục 5.5 Tham số exchangeRate bắt buộc truyền nếu lập hóa đơn ngoại tệ, nếu không truyền mặc định \=1 mục 6.2 Tham số validation bổ sung bắt buộc truyền exchangeRate nếu không xml sẽ bị null exchangeRate mục 6.2 Sửa format tham số originalInvoiceIssueDate là unix timestamp mục 6.2 Tham số transactionUuid xóa “Thời gian hiệu lực của transactionUuid là 3 ngày.” mục 6.2 |
| 2.29 | 9/11/2023 | Thêm hướng dẫn truyền metadata đối với loại **HÓA ĐƠN GTGT KIÊM TỜ KHAI HOÀN THUẾ** mục 6.9 |
| 2.30 | 7/12/2023 | Truyền thêm fuelReading dữ liệu đặc thù cho riêng hóa đơn xăng dầu có ghi nhận log bơm – mục 6.13 |
| 2.31 | 10/12/2023 | Bổ sung thông tin đơn giá đã bao gồm thuế \- mục 6.6 Bổ sung dữ liệu đầu vào để lập hóa đơn xăng dầu \- mục 7.2 Bổ sung API lập hóa đơn xăng dầu nháp \- mục 7.35, 7.36 |
| 2.32 | 27/12/2023 | Bổ sung API tra cứu hóa đơn trả về chứa thông tin hàng hóa – mục 7.37 |
| 2.33 | 23/02/2024 | Cập nhật maxlength các thẻ invoiceNote là 500, invoiceNo là 35, invoiceSeries là 25, invoiceSeri là 25 |
| 2.34 | 15/03/2024 | Nâng cấp API Tra cứu hóa đơn trả về thêm các trường buyerUnitName, buyerCode, buyerAddress, exchangeRate và listInfoUpdate – mục 7.37 |
| 2.35 | 05/04/2024 | Thêm 2 tham số đầu vào startDate, endDate (không bắt buộc) – mục 7.3, 7.4 và 7.5 |
| 2.36 | 08/05/2024 | Thêm 2 tham số extraName, extraValue (không bắt buộc) – mục 6.8, 7.2, 7.15, 7.16, 7.28, 7.29, 7.31, 7.32, 7.33 Thêm mới API gửi hóa đơn sang CQT bằng transactionUuid – mục 7.38 |
| 2.37 | 30/05/2024 | Thêm API 7.39 Tra cứu hóa đơn trả về chứa thông tin hàng hóa (UTC \+ 7\) |
| 2.38 | 28/08/2024 | Bỏ tham số **sumOfTotalLineAmountWithoutTax** thuộc SummarizeInfo – mục 6.8 Bổ sung tham số **totalAmountAfterDiscount** thuộc SummarizeInfo – mục 6.8 Thêm trường qrcode và otherTax vào mục 6.2 **generalInvoiceInfo** |
| 2.39 | 18/09/2024 | Nâng cấp **sellerBankAccount** tối đa 30 ký tự \- mục 6.3 Nâng cấp **buyerBankAccount** tối đa 30 ký tự \- mục 6.4 Nâng cấp **previousIndex, currentIndex, factor, amount** định dạng số \- mục 6.10 Sửa đối với hoá đơn TT78: hàng hoá tính chất Phí khác: không sinh STT, **không được truyền unitPrice, quantity – mục 6.6** Sửa đối với hoá đơn TT32: hàng hoá tính chất Phí khác: không sinh STT, không bắt buộc truyền **unitPrice, quantity – mục 6.6** |
| 2.40 | 11/11/2024 | Nâng cấp API 7.6Tra cứu hóa đơn, 7.13 Cung cấp danh sách hóa đơn theo khoảng thời gian, 7.35 Tra cứu hóa đơn trả về chứa thông tin hàng hóa, 7.37 Tra cứu hóa đơn trả về chứa thông tin hàng hóa (UTC \+ 7):  **\+**Bổ sung tìm kiếm theo “adjustmentType”: Trạng thái điều chỉnh hóa đơn:  1: Hóa đơn gốc (hóa đơn đã phát hành, hóa đơn bị điều chỉnh, hóa đơn bị thay thế) 3: Hóa đơn thay thế  5: Hóa đơn điều chỉnh thông tin 7: Hóa đơn xóa bỏ 9: Hóa đơn điều chỉnh tiề \*Không truyền sẽ trả tất cả Trả output thêm thông tin “originalInvoiceID” :Thông tin hóa đơn gốc |
| 2.44 | 25/05/2025 | Cập nhật API phát hành hóa dơn theo nghị định 70  Thông tin người bản bổ sung \+ Tên của hàng, không bắt buộc  \+ mã của hàng, không bắt buộc Thông tin người mua bổ sung \+ Mã quan hệ ngân sách, không bắt buộc Thông tin hàng hóa , nếu không phải hàng hóa dặc thù thì không bắt buộc, không cần thay đổi (Xe máy, xe oto, dịch vụ vận chuyển, dich vụ vận chuyển trên nền tảng số) \+ Tính chất hàng hóa đặc thù  \+ Loại hàng hóa đặc thù \+ các thông tin của hàng hóa đặc thù Thông tin chun generalInvoiceInfog bổ sung \+ Số bảng kê , không bắt buộc (Số bảng kê (Số của bảng kê các loại hàng hóa, dịch vụ đã bán kèm theo hóa đơn hoặc hóa đơn chiết khấu thương mại  \+ Ngày bảng kê ,  không bắt buộc, (Ngày của bảng kê các loại hàng hóa, dịch vụ đã bán kèm theo hóa đơn hoặc hóa đơn chiết khấu thương mại) Đối với khách hàng sử dụng api biên lai thu phí lệ phí , khi chuyển qua ND 70 đối với hàm phát hành hóa đơn Viettel hỗ trợ convert dữ liệu api sang chuẩn xml mới, khách hàng vẫn phải lập đăng kí sử dụng mới  |

**MỤC LỤC**

[**1\.**	**Thuật ngữ và viết tắt	9**](#heading=h.66y42ie2ds6c)

[**2\.**	**Mục đích và phạm vi	9**](#mục-đích-và-phạm-vi)

[**3\.**	**Mô hình kết nối	9**](#mô-tả-chi-tiết-chuẩn-kết-nối-để-các-hệ-thống-có-thể-kết-nối-vào-dịch-vụ-hóa-đơn-điện-tử-đại-trà-của-viettel-nhằm-đảm-bảo-phát-hành-đúng-thông-tin.)

[**4\.**	**Một số luồng cơ bản	10**](#chi-tiết-các-bước-hướng-dẫn-có-thể-xem-thêm-tại:-https://sinvoice.viettel.vn/ho-tro/huong-dan-su-dung/mo-ta-tong-the-cac-buoc-dang-ky-va-su-dung-dich-vu-hoa-don-dien-tu)

[**5\.**	**Các tiêu chuẩn	11**](#--một-doanh-nghiệp-có-thể-có-nhiều-mã-số-thuế-\(doanh-nghiệp,-chi-nhánh\),-mẫu-hóa-đơn,-ký-hiệu-hóa-đơn.-vì-vậy-các-hệ-thống-tích-hợp-phải-cho-phép-dn-cấu-hình-nhiều-thông-tin-để-gửi-sang-hệ-thống-sinvoice.)

[5.1	Tiêu chuẩn thời gian	11](#tiêu-chuẩn-thời-gian)

[5.2	Tiêu chuẩn dữ liệu	11](#tham-khảo-trang-web:-https://currentmillis.com/)

[5.3	Các ký tự đặc biệt	12](#đối-với-các-dữ-liệu-gửi-sang,-hệ-thống-sinvoice-sẽ-để-nguyên-format-dữ-liệu-để-hiển-thị.-ngoại-trừ-với-dữ-liệu-số-\(liên-quan-đến-tiền,-số-lượng,-đơn-giá,-thuế-suất\),-tên-ngân-hàng,-tài-khoản-ngân-hàng.-dữ-liệu-số-gửi-sang-luôn-có-định-dạng-là-[0-9.]+.-ví-dụ-như-100000.1234.-template-của-sinvoice-sẽ-tự-động-format-hiển-thị.-đối-với-dữ-liệu-như-tên-ngân-hàng,-tài-khoản-có-thể-nhập-nhiều,-cách-nhau-bởi-dấu-“;”.)

[5.4	Cơ chế kiểm trùng giao dịch	12](#thì-cần-truyền-trong-json-như-sau:-"buyername":-"nguyễn-văn-a-\\"b\\"")

[5.5	Tiêu chuẩn bảo mật kết nối	12](#trong-trường-hợp-chưa-nhận-được-thông-tin-phản-hồi.-có-thể-chủ-động-tra-cứu-lại-thông-tin-hóa-đơn-dựa-theo-transactionuuid-để-biết-hóa-đơn-đã-được-sinh-ra-hay-chưa.-chi-tiết-xem-mục-7.21-tra-cứu-hóa-đơn-bằng-transactionuuid)

[**6\.**	**Đặc tả chi tiết đầu vào lập hóa đơn	15**](#heading)

[6.1	Tổng quan	15](#tổng-quan)

[6.2	generalInvoiceInfo	16](#generalinvoiceinfo)

[6.3	sellerInfo	24](#})

[6.4	buyerInfo	27](#}-1)

[6.5	payments	30](#}-2)

[6.6	itemInfo	31](#heading-1)

[6.7	taxBreakdowns	43](#heading-2)

[6.8	summarizeInfo	46](#])

[6.9	metadata	49](#}-3)

[6.10	meterReading	54](#heading-3)

[6.11	invoiceFile	55](#}])

[6.12	qrcode	55](#"filecontent":-"rmlszsbi4bqjbmcga8oqimsrxrdhu6njigfkzcbsw6puihthuqfpihbo4bqnbibs4bqtccbow7nhimsrxqfu")

[**7\.**	**Các API kết nối	59**](#heading-4)

[7.1	Các khái niệm chung	59](#các-khái-niệm-chung)

[7.2	Phát hành/thay thế/điều chỉnh hóa đơn (Dùng cho CTS HSM)	60](#phát-hành/thay-thế/điều-chỉnh-hóa-đơn-cho-cts-server)

[7.3	Lấy file hóa đơn	66](#lấy-file-hóa-đơn)

[7.4	Lấy file hóa đơn có mã số bí mật	68](#fileutils.writebytearraytofile\(newfile\("d:/viettel/filename.zip"\),-output.getfiletobytes\(\)\);)

[7.5	Lấy file hóa đơn chuyển đổi (pdf)	72](#heading-5)

[7.6	Hủy hóa đơn	89](#nếu-người-dùng-truyền-giá-trị-0-hoặc-“0”-cho-tham-số-validation-trong-phần-generalinvoiceinfo-thì-các-thông-tin-được-truyền-trong-phần-iteminfo,-taxbreakdowns,-summarizeinfo-sẽ-được-giữ-nguyên-mà-không-thực-hiện-kiểm-tra-ràng-buộc-và-tính-toán-lại.)

[7.7	Tra cứu hóa đơn	75](#heading-6)

[7.8	Lấy thông tin trường động	79](#lấy-thông-tin-trường-động)

[7.9	Lập hóa đơn nháp	87](#lập-hóa-đơn-nháp)

[7.10	Lập hóa đơn theo lô	93](#heading=h.eokujqsi2nrh)

[7.11	Cập nhật kê khai thuế	89](#heading=h.szjcibl2jlog)

[7.12	Cung cấp tình hình sử dụng hóa đơn theo dải	92](#heading-7)

[7.13	Cung cấp danh sách hóa đơn theo khoảng thời gian	93](#heading-8)

[7.14	Gửi email cho các hoá đơn khách hàng	99](#heading-9)

[7.15	Phát hành/thay thế/điều chỉnh cho USB-TOKEN (Bước 1: Lấy chuỗi hash)	101](#heading-10)

[7.16	Phát hành/thay thế/điều chỉnh cho USB-TOKEN (Bước 2: Ký USB token và sinh hóa đơn)	106](#heading-11)

[7.17	Chuyển font	108](#}-4)

[7.18	Cập nhật trạng thái thanh toán	109](#cập-nhật-trạng-thái-thanh-toán)

[7.19	Hủy trạng thái thanh toán	112](#hủy-trạng-thái-thanh-toán)

[7.20	Xem trước hóa đơn nháp	113](#heading-12)

[7.21	Tra cứu hóa đơn bằng transactionUuid	115](#nếu-người-dùng-truyền-giá-trị-0-hoặc-“0”-cho-tham-số-validation-trong-phần-generalinvoiceinfo-thì-các-thông-tin-được-truyền-trong-phần-iteminfo,-taxbreakdowns,-summarizeinfo-sẽ-được-giữ-nguyên-mà-không-thực-hiện-kiểm-tra-ràng-buộc-và-tính-toán-lại.-1)

[7.22    Cấp mã bí mật	116](#}-5)

[7.23	API phát hành hoá đơn có mã bí mật (chữ ký server)	**Error\! Bookmark not defined.**](#heading=h.nrg3pf2csuyg)

[7.24	API phát hành hoá đơn có mã bí mật (USB-Token)	**Error\! Bookmark not defined.**](#heading=h.8a9ozmxjelu9)

[7.25	Cập nhật trạng thái in hoá đơn	118](#}-6)

[7.26    Số lần quét QRcode của hoá đơn	119](#heading-13)

[**8\.**	**Danh sách lỗi trả về của hệ thống	1**](#heading-14)

[**9\.**	**Mapping giữa các trường thông tin và mẫu hóa đơn	1**](#heading-15)

[**10\.**	**Kiểm tra API bằng POSTMAN	2**](#heading-16)

1. # **Thuật ngữ và viết tắt**

| STT | Từ viết tắt | Nghĩa đầy đủ |
| :---- | :---- | :---- |
| **1** | **XML** | e**X**tensible **M**arkup **L**anguage \- Ngôn ngữ Đánh dấu Mở rộng |
| **2** | **VAN** | **T**axation **V**alue **A**dded **N**etwork |
| **3** | **ICC** | **I**nvoice **C**ertification **C**enter |
| **4** | **PSD** | **P**ortable **S**ecurity **D**evice |
| **5** | **SGML** | **S**tandard **G**eneralized **M**arkup **L**anguage |
| **6** | **W3C** | **W**orld **W**ide **W**eb **C**onsortium, viết tắt **W3C**, lập ra các chuẩn cho Internet, nhất là cho World Wide Web |
| **7** | **SInvoice** | Dịch vụ/hệ thống hóa đơn điện tử của Viettel |
| **8** | **HTTH** | Hệ thống phần mềm kế toán, quản trị doanh nghiệp tích hợp với hệ thống SInvoice để phát hành hóa đơn. |

2. # **Mục đích và phạm vi** {#mục-đích-và-phạm-vi}

Mô tả chi tiết chuẩn kết nối để các hệ thống có thể kết nối vào dịch vụ Hóa đơn điện tử đại trà của Viettel nhằm đảm bảo phát hành đúng thông tin.

3. # **Mô hình kết nối**  

![][image1]

Hệ thống SInvoice đóng vai trò nhận dữ liệu hóa đơn từ các hệ thống bên ngoài (hệ thống tích hợp) gửi về và phát hành thành hóa đơn theo mẫu mà doanh nghiệp đã chọn. Các API của hệ thống SInvoice được cung cấp theo chuẩn Restful Webservice.

Ban đầu, doanh nghiệp thực hiện các thao tác khai báo mẫu hóa đơn trên web của hệ thống SInvoice bao gồm:

- Khai báo tên mẫu hóa đơn

- Chọn mẫu hóa đơn

- Khai báo dải hóa đơn

- Lập thông báo phát hành

- Đăng ký thông tin chứng thư số

Chi tiết các bước hướng dẫn có thể xem thêm tại: [https://sinvoice.viettel.vn/ho-tro/huong-dan-su-dung/mo-ta-tong-the-cac-buoc-dang-ky-va-su-dung-dich-vu-hoa-don-dien-tu](https://sinvoice.viettel.vn/ho-tro/huong-dan-su-dung/mo-ta-tong-the-cac-buoc-dang-ky-va-su-dung-dich-vu-hoa-don-dien-tu) 

4. # **Một số luồng cơ bản**

Sau khi các thông tin khai báo mẫu hóa đơn đã được thực hiện đầy đủ trên SInvoice, doanh nghiệp có thể thông qua các hệ thống bên ngoài để gọi các API thực hiện việc

* **Luồng đơn giản**

- Phát hành/Thay thế/điều chỉnh hóa đơn (***Tương ứng API mục: 7.2 đối với loại chứng thư số HSM hoặc 7.15 và 7.16 đối với loại chứng thư số USB-TOKEN hoặc 7.31 và 7.32 đối với loại chứng thư số CLOUD CA*** )

- Hủy hóa đơn (***Tương ứng API mục: 7.10***)

- Tải file hóa đơn (***Tương ứng API mục: 7.3***)

- Tra cứu hóa đơn (***Tương ứng API mục: 7.6***)

- Lập hóa đơn nháp (***Tương ứng API mục: 7.8***)

- Tra cứu hóa đơn bằng transactionUuid (***Tương ứng API mục: 7.21***): bắt buộc

* **Luồng hóa đơn có phát sinh các trường thông tin thêm (Các thông tin ngoài các khai báo chuẩn trong phần 5\. VD: Điện nước, bệnh viện, hải hảng, xuất nhập kho ….)**

- Lấy danh sách trường động được khai báo theo mẫu hóa đơn (***Tương ứng API mục: 7.7***)

- Phát hành/Thay thế/điều chỉnh hóa đơn (***Tương ứng API mục: 7.2 đối với loại chứng thư số HSM hoặc 7.15 và 7.16 đối với loại chứng thư số USB-TOKEN hoặc 7.31 và 7.32 đối với loại chứng thư số CLOUD CA*** )

- Hủy hóa đơn (***Tương ứng API mục: 7.10***)

- Tải file hóa đơn (***Tương ứng API mục: 7.3***)

- Tra cứu hóa đơn (***Tương ứng API mục: 7.6***)

- Lập hóa đơn nháp (***Tương ứng API mục: 7.8***)

- Tra cứu hóa đơn bằng transactionUuid (***Tương ứng API mục: 7.21***): bắt buộc


  

**Lưu ý:** 

\- Lập hóa đơn sử dụng chữ ký số HSM, USB token và CloudCA sử dụng các hàm khác nhau. HSM sử dụng 1 hàm duy nhất, việc tương tác với chữ ký do hệ thống Hóa đơn điện tử đảm nhiệm. USB, CloudCA sử dụng 2 hàm khác nhau, việc tương tác với chữ ký do phần mềm tích hợp đảm nhiệm. Khách hàng cần được tư vấn trước khi sử dụng.

\- Một doanh nghiệp có thể có nhiều mã số thuế (doanh nghiệp, chi nhánh), mẫu hóa đơn, ký hiệu hóa đơn. Vì vậy các hệ thống tích hợp phải cho phép DN cấu hình nhiều thông tin để gửi sang hệ thống SInvoice.

5. # **Các tiêu chuẩn**

   1. **Tiêu chuẩn thời gian**

Toàn bộ trường dữ liệu chỉ định sử dụng tiêu chuẩn 5.1 này, kiểu datetime (đầy đủ giờ, phút, giây. Hiện tại hệ thống chỉ ghi nhận đến giá trị giây, không ghi nhận giá trị mili giây) đầu vào và đầu ra của 33 API theo tiêu chuẩn này chuyển hết về dạng longTime.

Ví dụ: 1587797116000\.  Cách tính toán DATE như hình ảnh:

![][image2]

Tham khảo trang web: [https://currentmillis.com/](https://currentmillis.com/)

2. **Tiêu chuẩn dữ liệu**

- Hệ thống SInvoice hỗ trợ dữ liệu chuẩn Unicode (UTF-8)

- Đối với các dữ liệu gửi sang, hệ thống SInvoice sẽ để nguyên format dữ liệu để hiển thị. Ngoại trừ với dữ liệu số (liên quan đến tiền, số lượng, đơn giá, thuế suất), tên ngân hàng, tài khoản ngân hàng. Dữ liệu số gửi sang luôn có định dạng là \[0-9.\]+. Ví dụ như 100000.1234. Template của SInvoice sẽ tự động format hiển thị. Đối với dữ liệu như tên ngân hàng, tài khoản có thể nhập nhiều, cách nhau bởi dấu “;”.

  3. **Các ký tự đặc biệt**  

Các ký tự đặc biệt cần lưu ý và cách xử lý theo đúng chuẩn json (cần ký tự đánh dấu để nhận dạng ký tự đặc biệt)

Trong json cần thêm ký tự đánh dấu \\ trước các ký tự đặc biệt.

VD:

- Json: Muốn truyền dữ liệu là: Nguyễn Văn A "B"

Thì cần truyền trong json như sau: "buyerName": "Nguyễn Văn A \\"B\\""

4. **Cơ chế kiểm trùng giao dịch**

- Phần mềm tích hợp và SInvoice giao tiếp qua môi trường mạng, vì vậy rất có thể trong quá trình giao dịch phát sinh ra lỗi về đường truyền (lỗi mạng, hệ thống cao tải v.v.v). Để tránh một giao dịch được tạo thành 2 hóa đơn, với mỗi request hóa đơn gửi sang trong các thao tác lập hóa đơn, hệ thống tích hợp tự sinh ra transactionUuid là duy nhất cho hóa đơn đó và gửi kèm trong request lập hóa đơn. Chi tiết xem **mục 5.2** về định dạng dữ liệu transactionUuid.

- Sau khi request được thực hiện, cần đợi request phản hồi xem kết quả đúng hay sai, hoặc request không phản hồi sau khoảng thời gian timeout (tối thiểu 90 giây). Sau đó mới được gửi request khác với trùng transactionUuid. Việc gửi 2 request đồng thời cùng một thời điểm với trùng transactionUuid sẽ không được hệ thống xử lý kiểm soát mà tạo thành 2 hóa đơn khác nhau.

- Trong trường hợp chưa nhận được thông tin phản hồi. Có thể chủ động tra cứu lại thông tin hóa đơn dựa theo transactionUuid để biết hóa đơn đã được sinh ra hay chưa. Chi tiết xem **mục 7.21** Tra cứu hóa đơn bằng transactionUuid

  5. **Tiêu chuẩn bảo mật kết nối**

Có 2 cách để xác thực :

**Cách 1:**

- API kết nối được mã hóa sử dụng giao thức https với xác thực bằng Basic Auth.

- Để đảm bảo bảo mật, mặc định hệ thống sẽ không cho phép các tài khoản kết nối qua API. Để kết nối được API cho các tài khoản, người dùng sẽ phải đăng nhập vào web Viettel và cấu hình IP được phép truy cập. 

VD:

![][image3]

**Cách 2:**

- API kết nối được mã hóa sử dụng giao thức https với xác thực bằng Token.

- Lấy thông tin Token

  * Gọi API

  API: **/auth/login**

  Method: POST

  Content-Type: application/json

  Body: {"username":"0100109106-712","password":"12345678aA@"} 


  * Lấy giá trị access\_token sinh ra từ API trên để sử dụng trong các lần gọi API tương đương với việc xác thực:

    * Truyền vào Header của các API thông tin access\_token 

      * Key: Cookie

      * Value: access\_token=abc…def

Ví dụ cách sử dụng token với Postman

- Authorization:

![][image4]

- Headers:

![][image5]

- Body:

  ![][image6]

Kết quả:

![][image7]

Sau đó sử dụng access\_token tại Headers

![][image8]

6. **Tài khoản test** 

Các đơn vị sử dụng tài khoản sau để test kết nối với phần mềm  
**{**  
**"username":"0100109106-509",**  
**"password":**  
**}**  
**Password liên hệ đầu mối hướng dẫn tích hợp**

6. # **Đặc tả chi tiết đầu vào lập hóa đơn**

   1. **Tổng quan**

Đối với các API lập hóa đơn, điều chỉnh hóa đơn, thay thế hóa đơn, lập hóa đơn nháp, xem trước hóa đơn nháp, lập hóa đơn theo lô các trường dữ liệu truyền vào sẽ có dạng chung:  
**{**  
   **"generalInvoiceInfo":{ //Thông tin chung của hóa đơn**  
   **},**  
   **"buyerInfo":{      //thông tin người mua**  
   **},**  
   **"sellerInfo":{      //thông tin người bán**  
   **},**  
   **"payments":\[	//thông tin thanh toán**        
   **\],**  
   **"itemInfo":\[      //thông tin hàng hóa**  
   **\],**     
   **"metadata":\[	//thông tin trường động**  
   **\],**  
   "**meterReading": 	//thông tin đặc biệt dành cho hóa đơn điện nước**  
   **\],**  
   **"summarizeInfo":{	//thông tin tổng hợp tiền của hóa đơn**  
   **},**  
   **"taxBreakdowns":\[	//thông tin gom nhóm tiền hóa đơn theo thuế suất**  
   **\]**  
**}**

Mô tả:

| Tên trường | Mô tả |
| ----- | ----- |
| **generalInvoiceInfo** | Đây là thông tin chung để phát hành hóa đơn, bao gồm ký hiệu mẫu số hóa đơn, ký hiệu hóa đơn, loại hóa đơn, ngày lập .v.v.v |
| **sellerInfo** | Thông tin về bên bán trên hóa đơn. Trong trường hợp bên tích hợp gửi MST sang thì hệ thống sẽ lấy toàn bộ dữ liệu do bên tích hợp gửi sang, nếu không gửi sang thì hệ thống lấy thông tin được cấu hình trên hệ thống. |
| **buyerInfo** | Thông tin về bên mua trên hóa đơn |
| **extAttribute** | Trường dữ liệu mở rộng, để tùy biến thêm trên mẫu hóa đơn.  |
| **payments** | Tên phương thức thanh toán của hóa đơn.  |
| **itemInfo** | Thông tin chi tiết hàng hóa của hóa đơn. |
| **taxBreakdowns** | Tổng hợp thông tin thuế suất của hóa đơn theo mức thuế suất, ví dụ \-2, \-1, 0, 5, 8, 10 |
| **summarizeInfo** | Tổng hợp tiền hàng của cả hóa đơn |
| **metadata** | Thông tin trường động của hóa đơn |
| **meterReading** | Thông tin đặc biệt, dùng cho hóa đơn điện/nước. |

2. **generalInvoiceInfo**

Chứa thông tin cơ bản của hóa đơn, 

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| invoiceType | Required: false DataType: String Minlength:  Maxlength:  Format:  | Mã loại hóa đơn chỉ nhận các giá trị sau:  **Thông tư 32**: 01GTKT, 02GTTT, 07KPTQ, 03XKNB, 04HGDL, 01BLP. Tuân thủ theo quy định ký hiệu loại hóa đơn của Thông tư hướng dẫn thi hành nghị định số 51/2010/NĐ-CP. *Chi tiết xem PL1 Thông tư 39/2014/TT-BTC.*  **Thông tư 78:** 1, 2, 3, 4, 5, 6\. Tuân thủ theo đúng Thông tư 78/2021/TT-BTC **Lưu ý:** tại một thời điểm, doanh nghiệp có thể sử dụng nhiều loại hóa đơn. |
| templateCode | Required: true DataType: String Minlength: N/A Maxlength: 20 Format:  | Ký hiệu mẫu hóa đơn, tuân thủ theo quy định ký hiệu mẫu hóa đơn của Thông tư hướng dẫn thi hành **Thông tư 32:** Nghị định số 51/2010/NĐ-CP Ví dụ 01GTKT0/001, trong đó  01GTKT: ký hiệu loại hóa đơn 0: số liên, đối với hóa đơn điện tử luôn là 0 001: số thứ tự tăng dần theo số lượng mẫu DN đăng ký với cơ quan thuế *Chi tiết xem PL1 Thông tư 39/2014/TT-BTC* **Thông tư 78:** Ví dụ: 1/001 trong đó 1: Ký hiệu loại hóa đơn 001: Thứ tự tăng dần theo số lượng mẫu DN đăng ký với cơ quan thuế *Chi tiết tại khoản 1, Điều 3 Thông tư 78/2019/TT-BTC* **Lưu ý:** tại một thời điểm, doanh nghiệp có thể có nhiều mẫu hóa đơn.  |
| invoiceSeries | Required : true DataType: String Minlength : NA Maxlength : 25 Format : ^\[a-zA-Z0-9/\]\*$ | Là “Ký hiệu hóa đơn” tuân thủ theo quy tắc tạo ký hiệu hóa đơn của Thông tư hướng dẫn thi hành **Thông tư 32:** Nghị định số 51/2010/NĐ-CP.  Ví dụ AA/20E. *Chi tiết xem PL1 Thông tư 39/2014/TT-BTC* **Thông tư 78:** Ví dụ: K20TYY *Chi tiết tại khoản 1, Điều 3 Thông tư 78/2019/TT-BTC* **Lưu ý:** Tại một thời điểm, doanh nghiệp có thể có nhiều ký hiệu hóa đơn. Đối với hóa đơn theo TT78, người dùng không bắt buộc phải truyền đúng hai chữ số trong ký hiệu theo đúng năm phát hành hóa đơn. Trường hợp người dùng truyền sai (năm quá khứ hoặc tương lai), hệ thống vẫn lưu ký hiệu theo năm  **Ví dụ**: Người dùng lập hóa đơn với ký hiệu K18TAA, có ngày phát hành trong năm 2023, nếu truyền giá trị K50TAA, hệ thống vẫn sẽ lưu ký hiệu hóa đơn sau khi lập là K23TAA. |
| invoiceIssuedDate | Required: false DataType: Datetime Minlength: N/A Maxlength: 50 Format: Mục 4.1   | Ngày lập hóa đơn, tuân theo nguyên tắc đảm bảo về trình tự thời gian trong 1 ký hiệu hóa đơn của một mẫu hóa đơn với một mã số thuế cụ thể: số hóa đơn sau phải được lập với thời gian lớn hơn hoặc bằng số hóa đơn trước. **Lưu ý:**  **T**hời gian chính xác đến giờ phút giây Trong trường hợp không gửi ngày lập sang, hệ thống tự động lấy theo thời gian hiện tại trên hệ thống với múi giờ GMT+7. \- Dữ liệu truyền vào là thời gian dạng milliseconds kiểu long trong mục 5.1 Hệ thống ghi nhận đến chỉ số giây. Có thể tham khảo công thức tính tại: [https://currentmillis.com/](https://currentmillis.com/) |
| DetailedListNo | Required: false DataType: String Minlength:  Maxlength: 50  | Số bảng kê (Số của bảng kê các loại hàng hóa, dịch vụ đã bán kèm theo hóa đơn hoặc hóa đơn chiết khấu thương mại) Sin thẻ SBKe |
| DetailedListDate | Required: false DataType: date Minlength:  Maxlength: 50  | Ngày bảng kê (Ngày của bảng kê các loại hàng hóa, dịch vụ đã bán kèm theo hóa đơn hoặc hóa đơn chiết khấu thương mại) NBKe |
| currencyCode | Required: true DataType: String Minlength: 3 Maxlength: 3 Format: \[A-Z\]+ | Mã tiền tệ dùng cho hóa đơn có chiều dài 3 ký tự theo quy định của ngân hàng nhà nước Việt Nam. Ví dụ: USD, VND, EUR…  |
| adjustmentType  | Required: false DataType: String Minlength:  Maxlength: 1 Format: | Trạng thái điều chỉnh hóa đơn:  1: Hóa đơn gốc (hóa đơn đã phát hành, hóa đơn bị điều chỉnh, hóa đơn bị thay thế) 3: Hóa đơn thay thế  5: Hóa đơn điều chỉnh  7: Hóa đơn xóa bỏ Không truyền sẽ mặc định là 1 |
| adjustedNote | Required: false DataType: String Minlength: N/A Maxlength: 255 Format: | Lý do sai sót  Cho phép nhập chuỗi ký tự tối đa 255 ký tự.  Không bắt buộc truyền. Đặt trong generalInvoiceInfo |
| adjustmentInvoiceType | Required: false DataType: String Minlength:  Maxlength: 1 Format: | Loại điều chỉnh đối với hóa đơn điều chỉnh 1: Hóa đơn điều chỉnh tiền  2: Hóa đơn điều chỉnh thông tin  Bắt buộc nhập nếu adjustmentType \= 5 |
| originalInvoiceId | Required: false DataType: String Minlength: 7 Maxlength: 15 Format: ^\[a-zA-Z0-9\]\*$ | Số hóa đơn của hóa đơn gốc trong trường hợp lập hóa đơn là:      Hóa đơn thay thế     Hóa đơn điều chỉnh Số hóa đơn có dạng AA20E00000001, trong đó     AA20E: ký hiệu hóa đơn     00000001: số thứ tự tăng dần Chi tiết xem PL1 Thông tư 39/2014/TT-BTC |
| originalInvoiceIssueDate | Required: false DataType: Date Minlength: N/A Maxlength: 50 Format: unix timestamp   | Thời gian lập hóa đơn gốc, bắt buộc trong trường hợp lập hóa đơn thay thế và hóa đơn điều chỉnh. Dùng để tìm kiếm hóa đơn gốc của hóa đơn thay thế, điều chỉnh  |
| additionalReferenceDesc  | Required : false DataType: String Minlength :  Maxlength : 225 Format : | Thông tin tham khảo nếu có kèm theo của hóa đơn: văn bản thỏa thuận giữa bên mua và bên bán về việc thay thế, điều chỉnh hóa đơn. Bắt buộc khi lập hóa đơn thay thế, hóa đơn điều chỉnh.  |
| additionalReferenceDate | Required: false DataType: Date Minlength: N/A Maxlength: 50 Format: Mục 4.1   | Thời gian phát sinh văn bản thỏa thuận giữa bên mua và bên bán, bắt buộc khi lập hóa đơn thay thế, hóa đơn điều chỉnh. \- Dữ liệu truyền vào là thời gian dạng milisecond kiểu long trong mục 5.1  |
| paymentStatus | Required: true DataType: Boolean Minlength:  Maxlength: 1 Format: | Trạng thái thanh toán của hóa đơn True: Đã thanh toán False: Chưa thanh toán  |
| cusGetInvoiceRight | Required: false DataType: Boolean Minlength:  Maxlength: 1 Format: | Cho phép người dùng tra cứu hóa đơn hay không. Mặc định true. Nếu để giá trị false thì sẽ không view được hóa đơn lên  |
| exchangeRate | Required: false DataType: BigDecimal Minlength:  Maxlength: 13 Format: | Tỷ giá ngoại tệ tại thời điểm lập hóa đơn quy đổi ra VND Lưu ý:  \- Phần nguyên được nhập tối đa 11 chữ số, phần thập phân tối đa là 2 chữ số \- Bắt buộc truyền nếu lập hóa đơn ngoại tệ, nếu không truyền mặc định \=1 **Lưu ý:** Trường hợp truyền giá trị 0 hoặc “0” cho trường validation thì bắt buộc truyền exchangeRate |
| transactionUuid | Required: true, Không được trùng DataType: String Minlength: 10 Maxlength: 36 Format:  | transactionUuid để kiểm trùng giao dịch lập hóa đơn, được sinh ra từ hệ thống của bên đối tác, là duy nhất với mỗi hóa đơn. Trong trường hợp gửi transactionUuid thì bên hệ thống đối tác sẽ tự quản lý để đảm bảo tính duy nhất của transactionUuid. Với mỗi transactionUuid, khi đã gửi một transactionUuid với một hóa đơn A thì mọi request lập hóa đơn với cùng transactionUuid sẽ trả về hóa đơn A chứ không lập hóa đơn khác.  Khuyến cáo: sử dụng UUID V4 để tránh bị trùng số.  Tham khảo: [https://en.wikipedia.org/wiki/Universally\_unique\_identifier](https://en.wikipedia.org/wiki/Universally_unique_identifier) |
| certificateSerial | Required: false DataType: String Minlength:  Maxlength: 100 Format: | Được sử dụng khi lập hóa đơn sử dụng USB Token. Serial Number của chứng thư số của doanh nghiệp, chứng thư số này đã được doanh nghiệp đẩy lên trên hệ thống khi đăng ký sử dụng USB Token. Định dạng Hex. Ví dụ: 5404FFFEB7033FB316D672201B7BA4FE |
| originalInvoiceType | Required: false DataType: String Minlength: N/A Maxlength:  Format: | Loại hóa đơn gốc Truyền giá trị số với ý nghĩa như sau  0- Không phải hóa đơn giấy/hóa đơn không tồn tại trên hệ thống  1-Hóa đơn TT78  2-Hóa đơn theo QĐ 1209  3-Hóa đơn điện tử/giấy TT32 4-Hóa đơn giấy TT 78 Không truyền thì mặc định sẽ là 0 |
| originalTemplateCode | Required:  DataType: String Minlength: N/A Maxlength: 20 Format: | Bắt buộc truyền nếu originalInvoiceType là 1, 2, 3 hoặc 4 Ví dụ mẫu TT32: 01GTKT0/001 Ví dụ mẫu TT78: 1/0224 sẽ truyền là 1 2/001 sẽ truyền là 2.... tương tự các loại hóa đơn khác ( đối với tt78 sẽ truyền theo invoiceType ) |
| reservationCode | Required: true DataType: String Minlength:  Maxlength: 100 Format: | \- Mã bí mật đã được cấp cho MST  \- Yêu cầu này thực hiện thêm mới API phát hành hóa đơn có mã bí mật sử dụng chữ ký server \- Thông tin đầu ra tương tự như API createInvoice/{supplierTaxCode}, trong đó reservationCode trong response chính là reservationCode trong Input.  \- Trong trường hợp hệ thống gặp lỗi/chậm không thế trả kết quả ngay thì trả kết quả sau 10s.  |
| adjustAmount20 | Required: falseDataType: Number | Trường giảm giá 20% đối với hóa đơn bán hàng: Trường nhận giá trị “Tỷ lệ % theo doanh thu”. Giá trị truyền vào thuộc một trong các giá trị “0, 1, 2, 3, 5”. Ví dụ: “adjustAmount20”: “2” **Lưu ý:**  Giá trị “0” đối với trường hợp giảm trên từng hàng hóa. Khi truyền giá trị “0” thì phải truyền tham số adjustRatio hợp lệ cho ít nhất một hàng hóa có tính chất khác ghi chú. |
| invoiceNote | Required: false DataType: String Minlength: N/A Maxlength: 500 Format: | Được sử dụng như là 1 dòng ghi chú ở dưới danh sách hàng hóa, khi thay thế điều chỉnh hệ thống sẽ tự sinh ra dòng “ Điều chỉnh / thay thế cho hóa đơn ... ngày .... “ . Khi điều chỉnh trên web sẽ tự sinh còn api thì phải truyền vào  **Lưu ý**: Không tự sinh nếu bỏ kiểm tra dữ liệu đầu vào |
| validation | Required: false DataType: Number Minlength: N/A Maxlength:  Format: | Được sử dụng để điều hướng bỏ qua việc kiểm tra ràng buộc và tính toán lại các trường thông tin tiền của hàng hóa và hóa đơn: Trường hợp truyền giá trị 0 hoặc “0” thì các thông tin được truyền trong phần itemInfo, taxBreakdowns, summarizeInfo sẽ được giữ nguyên mà không thực hiện kiểm tra ràng buộc và tính toán lại. Các trường hợp khác thì xử lý theo nguyên tắc hiện tại. **Lưu ý:** Trường hợp truyền giá trị 0 hoặc “0” cho trường validation: Bắt buộc phải truyền giá trị khác null cho trường totalAmountAfterDiscount trong phần summarizeInfo nếu không trong XML hóa đơn sẽ không có thẻ TgTCThue Bắt buộc phải truyền giá trị khác null cho trường itemTotalAmountAfterDiscount trong phần itemInfo nếu không trong XML hóa đơn thông tin hàng hóa tương ứng sẽ không có thẻ TTien  Bắt buộc truyền exchangeRate nếu không xml sẽ bị null exchangeRate |
| qrCode | Required: false DataType: String Minlength: N/A Maxlength: 500 Format: | Nếu truyền qrCode thì khi lập hóa đơn thành công sẽ lưu giá trị vào cột QR\_CODE trong bảng invoice. Thực hiện view hóa đơn, quét QR bằng các phần mềm quét QR  thì sẽ gen đúng chuỗi khai báo giá trị cho qrCode |
| otherTax | Required: false DataType: String Minlength: N/A Maxlength:  Format: | Nếu truyền otherTax \= 1 là truyền thuế suất khác theo TT103/2014 thì \+ Tại bước sinh file xml, lưu thẻ \<TSuat\> là KHAC đối với % thuế truyền vào khác các giá trị sau: {-2, \-1, 0, 5, 8, 10} Nếu truyền otherTax khác 1 thì: \+ Tại bước sinh file xml, lưu thẻ \<TSuat\> là KHAC:AB.CD% đối với % thuế truyền vào khác các giá trị sau: {-2, \-1, 0, 5, 8, 10} |

Dữ liệu mẫu

Hóa đơn thường  
    "generalInvoiceInfo": {  
    "transactionUuid": "859f390a-1e59-4a05-9663-1e9ec7afdb8f",  
    "invoiceType": "1",  
    "templateCode": "1/001",  
    "invoiceSeries": "C24AAA",  
    "invoiceIssuedDate": 1605027600000,  
"currencyCode": "VND",  
“exchangeRate”: 1,  
"adjustmentType": "1",  
    "paymentStatus": true,  
    "cusGetInvoiceRight": true  
}

Hóa đơn điều chỉnh tiền  
"generalInvoiceInfo": {  
    "transactionUuid": "859f390a-1e59-4a05-9663-1e9ec7afdb8f",  
    "invoiceType": "1",  
    "templateCode": "1/001",  
    "invoiceSeries": "C24AAA",  
    "invoiceIssuedDate": 1605027600000,  
"currencyCode": "VND",  
    "adjustmentType": "5",  
"adjustmentInvoiceType": "1",  
“exchangeRate”: 1,  
“adjustedNote”: “Lý do điều chỉnh để báo cáo nhận được”  
    "originalInvoiceId": C24AA1",  
    "originalInvoiceIssueDate": 1605027600000,  
    "additionalReferenceDesc": "Văn bản",  
    "additionalReferenceDate": 1605027600000,  
    "paymentStatus": true,  
    "cusGetInvoiceRight": true  
  }

Hóa đơn điều chỉnh thông tin  
"generalInvoiceInfo": {  
    "transactionUuid": "859f390a-1e59-4a05-9663-1e9ec7afdb8f",  
    "invoiceType": "1",  
    "templateCode": "1/001",  
    "invoiceSeries": "C24AAA",  
    "invoiceIssuedDate": 1605027600000,  
"currencyCode": "VND",  
    "adjustmentType": "5",  
"adjustmentInvoiceType": "2",  
“exchangeRate”: 1,  
“adjustedNote”: “Lý do điều chỉnh để báo cáo nhận được”  
“invoiceNote”: “Nội dung ghi chú muốn hiển thị lên hóa đơn”  
    "originalInvoiceId": "C24AA1",  
    "originalInvoiceIssueDate": 1605027600000,  
    "additionalReferenceDesc": "Văn bản",  
    "additionalReferenceDate": 1605027600000,  
    "paymentStatus": true,  
    "cusGetInvoiceRight": true  
  }

Hóa đơn thay thế  
"generalInvoiceInfo": {  
    "transactionUuid": "859f390a-1e59-4a05-9663-1e9ec7afdb8f",  
    "invoiceType": "1",  
    "templateCode": "1/001",  
    "invoiceSeries": "C24AA",  
    "invoiceIssuedDate": 1605027600000,  
"currencyCode": "VND",  
    "adjustmentType": "3",  
“exchangeRate”: 1,  
“adjustedNote”: “Lý do điều chỉnh để báo cáo nhận được”  
“invoiceNote”: “Nội dung ghi chú muốn hiển thị lên hóa đơn”   
"originalInvoiceId": "C24AA1",  
    "originalInvoiceIssueDate": 1605027600000,  
    "additionalReferenceDesc": "Văn bản",  
    "additionalReferenceDate": 1605027600000,  
    "paymentStatus": true,  
    "cusGetInvoiceRight": true  
  }

Hóa đơn thay thế cho hóa đơn không tồn tại trên hệ thống  
"generalInvoiceInfo": {  
        "invoiceType": "1",  
        "templateCode": "1/001",  
        "invoiceSeries": "C24AA",  
        "invoiceIssuedDate": 1605027600000,  
        "currencyCode": "VND",  
        "invoiceNote": "",  
        "adjustmentType": "3",  
    “exchangeRate”: 1,  
    “adjustedNote”: “Lý do điều chỉnh để báo cáo nhận được”  
        “invoiceNote”: “Thay thế hóa đơn số 1, mẫu số 1, ký hiệu C24AAA, ngày 28/03/2022”  
        "paymentStatus": true,  
        "cusGetInvoiceRight": true,  
        "originalInvoiceId": "C24AA1",  
        "originalInvoiceIssueDate": 1654861128000,  
         "originalInvoiceType": "1",  
         "originalTemplateCode": "1",  
        "additionalReferenceDesc": "Hóa đơn thay thế số: 1, mẫu số: 1, ký hiệu: C24AA1, ngày: 10/06/2022",  
        "additionalReferenceDate": 1658825818067,  
        "transactionUuid": "E4B2813E5AA4E335E053380A10ACB857"  
  }

Hóa đơn điều chỉnh tiền cho hóa đơn không tồn tại trên hệ thống  
{  
"generalInvoiceInfo": {  
"invoiceType": "1",  
"templateCode": "1/001",  
"invoiceSeries": "C24AAA",  
"currencyCode": "VND",  
"adjustmentType": "5",  
"adjustmentInvoiceType": "1",  
"originalInvoiceId": "C24AA1",  
“exchangeRate”: 1,  
“adjustedNote”: “Lý do điều chỉnh để báo cáo nhận được”  
“invoiceNote”: “Điều chỉnh hóa đơn số 1, mẫu số 1, ký hiệu C24AAA, ngày 28/03/2022 Điều chỉnh giảm thuế GTGT 10% thành 8%”  
"originalInvoiceIssueDate": 1648454669000,  
"additionalReferenceDate": 1648454669000,  
"additionalReferenceDesc": "lý do điều chỉnh",  
"originalInvoiceType": "1",  
"originalTemplateCode": "1",  
"paymentStatus": true,  
"cusGetInvoiceRight": true  
}

3. **sellerInfo**

Thông tin người bán trên hóa đơn, có thể được truyền sang hoặc lấy tự động trên hệ thống hóa đơn điện tử. Trong trường hợp sellerTaxCode KHÔNG ĐƯỢC truyền sang thì dữ liệu sẽ được lấy từ hệ thống hóa đơn điện tử.

**Chú ý 1**: Các trường dữ liệu có required \= true khi có truyền sellerTaxCode, nếu không truyền sellerTaxCode thì các trường khác được lấy từ hệ thống HDDT, không lấy từ thông tin truyền vào, với trường storeCode và storeName nếu truyền vào thì vinvocie sẽ lấy theo dữ liệu truyền vào

**Chú ý 2**: sellerTaxCode phải trùng khớp với taxCode của user đăng nhập

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| sellerLegalName | Required: true DataType: String Minlength:  Maxlength: 255 Format: N/A | Tên (đăng ký kinh doanh trong trường hợp là doanh nghiệp) của người bán  |
| sellerTaxCode | Required: true DataType: String Minlength:  Maxlength: 20 Format: | Mã số thuế người bán được cấp bởi TCT Việt Nam. Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 Mã số này được dùng để kiểm tra xem dữ liệu sẽ lấy từ hệ thống SInvoice hay do phần mềm tích hợp truyền sang. Nếu có dữ liệu thì sẽ lấy toàn bộ thông tin người bán từ phần mềm tích hợp. Nếu không có sẽ lấy thông tin được cấu hình trên SInvoice. Mã số này không được dùng để phát hành lên hóa đơn.  |
| sellerAddressLine | Required: true DataType: String Minlength:  Maxlength: 255 Format: N/A | Địa chỉ của bên bán được thể hiện trên hóa đơn.  |
| sellerPhoneNumber | Required: false DataType: String Minlength:  Maxlength: 50 Format: \\s\*\[0-9\]\*\\s\* | Số điện thoại người bán  |
| sellerFaxNumber | Required: false DataType: String Minlength:  Maxlength: 50 Format: \\s\*\[0-9\]\*\\s\* | Số fax người bán  |
| sellerEmail | Required: false DataType: String Minlength:  Maxlength: 50 Format: \\s{0,}((\[a-zA-Z0-9\]\[a-zA-Z0-9\_\*$&+,:;=?\#|'\<\>.^\*()%\!-\]{2,}@\[a-zA-Z0-9\]{2,}(\\.\[a-zA-Z0-9\]{2,}){1,})+)\\s{0,} | Địa chỉ thư điện tử người bán  |
| sellerBankName | Required: false DataType: String Minlength:  Maxlength: 400 Format: | Tên ngân hàng nơi người bán mở tài khoản giao dịch  |
| sellerBankAccount | Required: false DataType: String Minlength:  Maxlength: 30 Format: \\s\*\[0-9\]\*\\s\* | Tài khoản ngân hàng của người bán  |
| sellerDistrictName | Required: false DataType: String Minlength:  Maxlength: 50 Format: | Tên Quận Huyện  |
| sellerCityName | Required: false DataType: String Minlength:  Maxlength: 600 Format: | Tên Tỉnh/Thành phố  |
| sellerCountryCode | Required: false DataType: String Minlength:  Maxlength: 15 Format: | Mã quốc gia   |
| sellerWebsite | Required: false DataType: String Minlength:  Maxlength: 200 Format: | Website của người bán  |
| storeCode | Required: false DataType: String Minlength:  Maxlength: 50 Format: | Mã cửa hàng |
| storeName | Required: false DataType: String Minlength:  Maxlength: 400 Format: | Tên cửa hàng |
| merchantCode | Required: true DataType: String Minlength:  Maxlength: 4 Format: | Mã danh mục đơn vị chấp nhận thanh toán Chỉ cho phép truyền ký tự số **Lưu ý:** các trường này phục vụ cho việc sinh qrcode78, các mẫu khác không bắt buộc |
| merchantName | Required: true DataType: String Minlength:  Maxlength: 25 Format: | Tên đơn vị chấp nhận thanh toán Chỉ cho phép truyền 96 ký tự theo EMV Book  **Lưu ý:** các trường này phục vụ cho việc sinh qrcode78, các mẫu khác không bắt buộc  |
| merchantCity | Required: true DataType: String Minlength:  Maxlength: 15 Format: | Thành phố đơn vị chấp nhận thanh toán  Chỉ cho phép truyền 96 ký tự theo EMV Book  **Lưu ý:** các trường này phục vụ cho việc sinh qrcode78, các mẫu khác không bắt buộc |

Dữ liệu mẫu  
"sellerInfo": {  
    "sellerLegalName": "Người bán hàng",  
    "sellerTaxCode": "0100109106",  
    "sellerAddressLine": "Thành Phố Hà Nội \- Việt Nam",  
    "sellerPhoneNumber": "0123456789",  
	"sellerFaxNumber": "0123456789",  
    "sellerEmail": "email@gmail.com",  
    "sellerBankName": "Ngân hàng ",  
    "sellerBankAccount": "012345678901",  
	"sellerDistrictName": "",  
    "sellerCityName": "Thành Phố Hà Nội",  
    "sellerCountryCode": "84”,  
    "sellerWebsite": "sinvoice.viettel.vn"  
  }

4. **buyerInfo**

Thông tin người mua trên hóa đơn.

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| buyerName | Required: false DataType: String Minlength:  Maxlength: 800 Format: | Tên người mua trong trường hợp là người mua lẻ, cá nhân. Tên người mua hoặc tên đơn vị là bắt buộc khi buyerNotGetInvoice \= 0\.  |
| buyerCode | Required: false DataType: String Minlength:  Maxlength: 400 Format: | Mã khách hàng, chỉ cho phép các ký tự   |
| buyerLegalName | Required: false DataType: String Minlength:  Maxlength: 1200 Format: | Tên đơn vị (đăng ký kinh doanh trong trường hợp là doanh nghiệp) của người mua. Tên người mua hoặc tên đơn vị là bắt buộc khi buyerNotGetInvoice \= 0\. Bắt buộc nếu truyền buyerTaxCode  |
| buyerTaxCode | Required: false DataType: String Minlength:  Maxlength: 20 Format:  | Mã số thuế người mua, có thể là mã số thuế Việt Nam hoặc mã số thuế nước ngoài Mẫu 1: 0312770607  Mẫu 2: 0312770607-001  |
| buyerBudgetCode | Required: false DataType: String Minlength:  Maxlength: 7 Format:  | Mã quan hệ ngân sách của tổ chức, đơn vị mua hàng  |
| buyerAddressLine | Required: false DataType: String Minlength:  Maxlength: 1200 Format: | Địa chỉ xuất hóa đơn của người mua  Bắt buộc khi buyerNotGetInvoice \= 0  |
| buyerPhoneNumber | Required: false DataType: String Minlength:  Maxlength: 15 Format: \\s\*\[0-9\]\*\\s\* | Số điện thoại người mua, số điện thoại sẽ được dùng để gửi tin nhắn trong trường hợp bên bán đăng ký dịch vụ SMS Brandname.   |
| buyerFaxNumber | Required: false DataType: String Minlength:  Maxlength:  Format:  | Số fax người mua (Hiện tại nếu truyền thì Sinvoice cũng không lấy)  |
| buyerEmail | Required: false DataType: String Minlength:  Maxlength: 2000 Format: ^\[\_A-Za-z0-9-\\+\]+(\\.\[\_A-Za-z0-9-\]+)\*@\[A-Za-z0-9-\]+(\\.\[A-Za-z0-9\]+)\*(\\.\[A-Za-z\]{2,})$  (áp dụng cho từng email đơn lẻ) | Email người mua, sử dụng để gửi hóa đơn cho người mua Nếu có nhiều email thì cách nhau bởi dấu chấm phẩy (;). Khi tài khoản email của bên bán được cấu hình trên hệ thống thì hệ thống tự động gửi nếu có email của người mua. Chi tiết cấu hình email xem ở đây: [https://sinvoice.viettel.vn/ho-tro/huong-dan-su-dung/5-huong-dan-cau-hinh-doanh-nghiep--cau-hinh-chung](https://sinvoice.viettel.vn/ho-tro/huong-dan-su-dung/5-huong-dan-cau-hinh-doanh-nghiep--cau-hinh-chung)   |
| buyerBankName | Required: false DataType: String Minlength:  Maxlength: 200 Format: | Tên trụ sở chính ngân hàng nơi người mua mở tài khoản giao dịch.   |
| buyerBankAccount | Required: false DataType: String Minlength:  Maxlength: 30 Format: | Tài khoản ngân hàng của người mua.   |
| buyerDistrictName | Required: false DataType: String Minlength:  Maxlength:  Format: | Tên Quận Huyện (Hiện tại nếu truyền thì Sinvoice cũng không lấy)  |
| buyerCityName | Required: false DataType: String Minlength:  Maxlength:  Format: | Tên Tỉnh/Thành phố (Hiện tại nếu truyền thì Sinvoice cũng không lấy)  |
| buyerCountryCode | Required: false DataType: String Minlength:  Maxlength:  Format:  | Mã quốc gia người mua (Hiện tại nếu truyền thì Sinvoice cũng không lấy)  |
| buyerIdType | Required: false DataType: String Minlength:  Maxlength:  Format: \[123\]\* | Loại giấy tờ của người mua, 1: CCCD 2: Hộ chiếu |
| buyerIdNo | Required: false DataType: String Minlength:  Maxlength: 200 Format: \[a-zA-Z0-9-\_ \]\* | **Chú ý**: Khi buyerIdType có giá trị thì buyerIdNo bắt buộc phải có giá trị. Số giấy tờ của người mua, có thể là chứng minh thư/căn cước công dân, giấy phép kinh doanh, hộ chiếu  |
| buyerBirthDay | Required: false DataType: Date Minlength:  Maxlength:  Format:  | Ngày sinh của người mua (Hiện tại nếu truyền thì Sinvoice cũng không lấy)  |
| buyerNotGetInvoice | Required: false DataType: Integer Minlength: 0 Maxlength: 1 Format: | Người mua không lấy hóa đơn 0-Người mua có lấy hóa đơn  1-Người mua không lấy hóa đơn Nếu không truyền, mặc định là 0 |

Dữ liệu mẫu  
"buyerInfo": {  
    "buyerName": "Tên khách hàng",  
    "buyerLegalName": "Tên đơn vị",  
    "buyerTaxCode": "0100109106",  
    "buyerAddressLine": "An Khánh Hoài Đức Hà Nội",  
    "buyerDistrictName": "Số 9, đường 11, VSIP Bắc Ninh, Thị xã Từ Sơn, Tỉnh",  
    "buyerCityName": "Thành Phố Hà Nội",  
    "buyerCountryCode": "84",  
    "buyerPhoneNumber": "987999999",  
    "buyerFaxNumber": "0458954",  
    "buyerEmail": "minhltt@viettel.com.vn",  
    "buyerBankName": "Ngân hàng Quân đội MB",  
    "buyerBankAccount": "01578987871236547",  
    "buyerIdType": "3",  
    "buyerIdNo": "8888899999",  
    "buyerCode": "832472343b\_b",  
    "buyerBirthDay": ""  
  }

5. **payments** 

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| paymentMethod | Required: false DataType: String Minlength:  Maxlength: 50 Format: | Hình thức thanh toán. Có thể không cần truyền giá trị, chỉ cần truyền paymentMethodName \- Gồm các giá trị sau: 1: khi hình thức thanh toán là TM 2: khi hình thức thanh toán là CK 3: khi hình thức thanh toán là TM/CK 4: khi hình thức thanh toán là DTCN 5: khi hình thức thanh toán là KHAC 6: Khi hình thức thanh toán là Tiền mặt 7: Khi hình thức thanh toán là Chuyển khoản 8: Khi hình thức thanh toán là Tiền mặt/Chuyển khoản \- Không truyền dữ liệu thì sẽ được hiểu là 5 |
| paymentMethodName | Required: true DataType: String Minlength:  Maxlength: 50 Format: | Hình thức thanh toán chi tiết phải mapping theo paymentMethod. \- Gồm các giá trị sau: TM CK TM/CK DTCN KHAC Tiền mặt Chuyển khoản Tiền mặt/Chuyển khoản \- Không truyền dữ liệu thì trả về thông báo lỗi  \- Được nhập free text khi paymentMethod \= 5, được hiểu là hình thức thanh toán khác |

Dữ liệu mẫu  
"payments": \[  
    {  
	  "paymentMethod": "2",  
      "paymentMethodName": "CK"  
    }  
  \]

Hoặc

"payments": \[  
    {  
      "paymentMethodName": "Truyền trực tiếp giá trị mong muốn vào đây"  
    }  
  \]

6. **itemInfo**

Là một danh sách các hàng hóa/dịch vụ được hiển thị trên hóa đơn. 

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| lineNumber | Required: false DataType: Integer Minlength:  Maxlength:  Format:  | Thứ tự dòng hóa đơn, bắt đầu từ 1 Không cần nhập, hệ thống tự động sinh |
| selection | Required: false DataType: Integer Min: 1 Max: 6 Format:  | Đánh dấu loại hàng hóa/dịch vụ **Đối với Thông tư 32:** Null hoặc 1- Hàng Hóa (Sinh STT, bắt buộc phải nhập số lượng, đơn giá) 2: Ghi chú (Không sinh STT và không cộng tiền vào tổng tiền thanh toán) 3: Chiết khấu (Không sinh STT, không cần nhập số lượng, đơn giá và thêm isIncreaseItem \= false để xác định giảm tiền) 4: Bảng kê (Sinh STT, không cần nhập số lượng, đơn giá, chỉ cần nhập thành tiền) 5: Phí khác (Không sinh STT, không bắt buộc nhập số lượng, đơn giá) **Đối với Thông tư 78:** Null hoặc 1- Hàng Hóa (Sinh STT, bắt buộc phải nhập số lượng, đơn giá) 2: Ghi chú (Không sinh STT và không cộng tiền vào tổng tiền thanh toán)  3: Chiết khấu (Không sinh STT, không cần nhập số lượng, đơn giá và thêm isIncreaseItem \= false để xác định giảm tiền) 4: Phí khác (Không sinh STT, không nhập số lượng, đơn giá)       5: Khuyến mại (Sinh STT, bắt buộc phải nhập số           lượng, đơn giá) 6: Hàng hóa đặc trưng, nếu truyền hàng hóa đặc trưng (ND 70\) thì các trường thông tin bắt buộc xem danh sách bên dưới   |
| itemType | Required: false DataType: Integer Min: 1 Max: 6 Format: | Trường hợp nếu truyền selection là 6 thì trường này bắt buộc Loại hàng hóa đặc thù Hàng hóa là xe ô tô, xe mô tô Dịch vụ vận chuyển Dịch vụ vận chuyển trên nền tảng số, TMĐT |
| itemCode | Required: false DataType: String Minlength:  Maxlength: 50 Format:  | Mã hàng hóa, dịch vụ |
| itemName | Required: false DataType: String Minlength:  Maxlength: 500 Format: | Tên hàng hóa, dịch vụ Bắt buộc nhập với tính chất hàng hóa là Hàng hóa, Khuyến mãi và Phí khác Đối với hóa đơn điều chỉnh, Hệ thống sẽ dựa vào giá trị của isIncreaseItem xác định điều chỉnh tăng, giảm để tự sinh câu mô tả:  "Điều chỉnh tăng/giảm tiền hàng, tiền thuế của hàng hóa dịch vụ" \+ itemName Đối vói biên lai thì đây là Tên loại phí  |
| unitCode | Required: false DataType: String Minlength:  Maxlength: 100 Format: | Mã đơn vị tính  |
| unitName | Required: false DataType: String Minlength:  Maxlength: 300 Format: | Tên đơn vị tính hàng hóa, dịch vụ  |
| unitPrice | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+ | Đơn giá của hàng hóa Bắt buộc nhập với tính chất hàng hóa là Hàng hóa, Khuyến mãi Cho phép truyền giá trị âm  |
| quantity | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+ | Số lượng của hàng hóa Bắt buộc nhập với tính chất hàng hóa là Hàng hóa, Khuyến mãi Cho phép truyền giá trị âm  |
| itemTotalAmountWithoutTax | Required: true DataType: BigDecimal Minlength:  Maxlength: 13 Format: \[0-9.\]+ | Là tổng tiền chưa bao gồm VAT của hàng hóa/dịch vụ. Tổng tiền không có số âm. itemTotalAmountWithoutTax \= quantity \* unitPrice Hệ thống sẽ kiểm tra dữ liệu nhận được vế bên trái với dữ liệu tính toán vế bên phải để kiểm tra tính chính xác của dữ liệu.  Hóa đơn thường: Là tổng tiền hàng hóa dịch vụ chưa có VAT.  Hóa đơn điều chỉnh: Là tổng tiền phần điều chỉnh của hàng hóa dịch vụ chưa có VAT **Lưu ý:** Cho phép sai số 5 đơn vị |
| taxPercentage | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+ | Trong trường hợp thuế tổng/hóa đơn bán hàng (theo chuẩn hóa đơn xác thực là phải có) Thuế tổng: để theo con số chung Hóa đơn bán hàng/hóa đơn không thuế: \-2  Thuế suất của hàng hóa, dịch vụ. Thuế suất bao gồm các loại: \-2: không thuế \-1: không kê khai tính/nộp thuế (Chỗ này hơi ngược với hóa đơn có mã xác thực của TCT) 0: 0% 5: 5% 8: 8% 10: 10% Nếu truyền loại thuế suất khác thì truyền giá trị % thuế suất. VD: Khác 12.34% thì truyền “taxPercentage”: 12.34 |
| taxAmount | Required: false DataType: BigDecimal Minlength:  Maxlength Format: \[0-9.\]+ | Tổng tiền thuế Trong trường hợp thuế tổng/hóa đơn bán hàng: (theo chuẩn hóa đơn xác thực là phải có) Thuế tổng: tổng tiền hàng \* thuế chung Hóa đơn bán hàng/hóa đơn không thuế: 0 Nếu không truyền, được hiểu là \= 0 |
| isIncreaseItem | Required: false DataType: Boolean Minlength:  Maxlength:  Format: | Hóa đơn bình thường: có giá trị là null. Hóa đơn điều chỉnh: \- false: dòng hàng hóa/dịch vụ bị điều chỉnh giảm  \- true: dòng hàng hóa/dịch vụ bị điều chỉnh tăng  |
| itemNote | Required: false DataType: String Minlength:  Maxlength: 300 Format: | Ghi chú cho từng dòng hàng hóa *Để đồng bộ nội dung ghi chú của từng dòng hàng hóa đọc tự động trên web và nội dung ghi chú từ API tích hợp khi lập hóa đơn điều chỉnh tiền, người dùng API tích hợp truyền nội dung ghi chú chi tiết cho từng dòng hàng hóa vào trường itemNote trong itemInfo. Hệ thống sẽ tự đọc phần thông tin “của hàng hóa dịch vụ” và ghép với tên hàng hóa dịch vụ* Ví dụ: Hệ thống tự động sinh ghi chú: *Điều chỉnh tăng số lượng, giảm đơn giá của hàng hóa dịch vụ: Máy tính* |
| batchNo | Required: false DataType: String Minlength:  Maxlength: 300 Format: | Số lô, thường dùng cho các hàng hóa là thuốc, có thể sử dụng để hiển thị thêm thông tin trong trường hợp cần thiết.  |
| expDate | Required: false DataType: String Minlength:  Maxlength: 50 Format: | Hạn sử dụng của hàng hóa, thường dùng cho các hàng hóa là thuốc, có thể sử dụng để hiển thị thêm thông tin trong trường hợp cần thiết.  |
| discount | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+ | % chiết khấu trên dòng sản phẩm, tính trên đơn giá của sản phẩm. Trong trường hợp không có thì truyền 0  |
| discount2 | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+ | % chiết khấu thứ 2 trên dòng sản phẩm, tính trên đơn giá của sản phẩm. Trong trường hợp không có thì truyền 0\.  |
| itemDiscount | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+ | Giá trị chiết khấu trên dòng sản phẩm, sau khi nhân với số lượng và % chiết khấu Hệ thống tự tính, không cần truyền dữ liệu  |
| itemTotalAmountAfterDiscount | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+ | Là tổng tiền sau khi trừ chiết khấu, giảm giá. Hệ thống tự tính, không cần truyền dữ liệu **Lưu ý:** Trường hợp truyền giá trị 0 hoặc “0” cho trường validation: bắt buộc phải truyền giá trị khác null |
| itemTotalAmountWithTax | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+ | Là tổng tiền đã bao gồm VAT của hàng hóa/dịch vụ.  Hệ thống tự tính, không cần truyền dữ liệu  |
| adjustRatio | Required: false DataType: Integer Minlength:  Maxlength:  Format: \[0-9.\]+ | Trường giảm giá 20% đối với hàng hóa áp dụng với hóa đơn bán hàng: Trường nhận giá trị “Tỷ lệ % theo doanh thu”. Giá trị truyền vào thuộc một trong các giá trị “1, 2, 3, 5”. Ví dụ: “adjustRatio”: “1” **Lưu ý:** Giá trị của trường này chỉ có ảnh hưởng đến giá trị hóa đơn khi trường adjustAmount20 trong phần generalInvoiceInfo có giá trị là “0”, các trường hợp truyền giá trị khác cho adjustAmount20 thì hệ thống sẽ bỏ qua. Khi truyền adjustAmount20 \= “0” thì phải truyền giá trị adjustRatio hợp lệ cho ít nhất một hàng hóa có tính chất không phải ghi chú. |
| unitPriceWithTax | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+ | Đơn giá của hàng hóa bao gồm thuế.  Được sử dụng trong API lập hóa đơn nháp cho xăng dầu |
| unitPriceWithTax | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+ | Đơn giá của hàng hóa bao gồm thuế.  Được sử dụng trong API lập hóa đơn nháp cho xăng dầu |
| specialInfo  | Required: false DataType: List objet  "specialInfo": \[  {"name": " Skhung",   "value": "RL4XW43G869205813" }, {"name": " Smay",  "value": "29G104548" }\]  | Nếu truyền itemType thì trường specialInfo Tùy theo yêu cầu của Nghị định 70 theo từng hàng hóa đặc thù, name và value ,validate theo yêu cầu từ TCT . Danh sách các trường đặc thù được trình bày bên dưới   |

**DANH MỤC LOẠI HÀNG HÓA ĐẶC THÙ**

| STT | Mô tả | Giá trị bắt buộc | Loại hóa đơn áp dụng |
| :---: | ----- | ----- | ----- |
| 1 | Hàng hóa là xe ô tô, xe mô tô | Skhung : Số khung, string, bắt buộc, max 200 kí tự Smay : Số máy, string, bắt buộc , max 200 kí tự  |  Hóa đơn bán hàng, hóa đơn giá trị gia tăng, hóa đơn khác, hóa đơn máy tính tiền, hóa đơn tài sản công, hóa đơn giá trị gia tăng tich hợp biên lại |
| 2 | Dịch vụ vận chuyển | BKSPTVChuyen : Biển kiểm soát phương tiện vận chuyển , string,, bắt buộc, 200 kí tự   | Hóa đơn bán hàng, hóa đơn giá trị gia tăng, hóa đơn khác, hóa đơn máy tính tiền, hóa đơn tài sản công, hóa đơn giá trị gia tăng tich hợp biên lại |
| 3 | Dịch vụ vận chuyển trên nền tảng số, TMĐT |  TNGHang: Tên người gửi hang, string,, bắt buộc, 200 kí tự    DCNGHang: Địa chỉ người gửi hang, string,, bắt buộc, 200 kí tự   MSTNGHang: MST người gửi, string,, bắt buộc, 200 kí tự   MDDNGHang; Số định danh người gửi hang, string,, bắt buộc, 200 kí tự   | Hóa đơn bán hàng, hóa đơn giá trị gia tăng, hóa đơn khác, hóa đơn máy tính tiền, hóa đơn giá trị gia tăng tich hợp biên lại |

**Lưu ý 1**: **Đối với từng dòng hàng hóa, trong trường hợp các trường thông tin như** quantity, unitPrice, itemTotalAmountWithoutTax, taxPercentage, taxAmount, discount, itemDiscount, itemTotalAmountWithTax **có dữ liệu (dữ liệu khác null), hệ thống sẽ tính toán và kiểm tra các dữ liệu**

**Hệ thống so sánh** quantity x unitPrice **lệch không quá 5 đồng so với** itemTotalAmountWithoutTax

**Hệ thống so sánh** itemTotalAmountWithoutTax khi bị lệch quá hệ thống báo lỗi. 

**Dòng ghi chú cho hóa đơn điều chỉnh, thay thế tổng hợp hệ thống sẽ tự động thêm**.

VD Điều chỉnh tăng tiền hàng, tiền thuế của hàng hóa dịch vụ: Hàng hóa 01, hệ thống sẽ tự tổng hợp lại và sinh 1 item dạng selection \=2 với nội dung tổng hợp như sau, hệ thống phần mềm không cần thêm, tránh trùng lặp: 

Hóa đơn điều chỉnh tăng tiền hàng, tiền thuế cho hóa đơn điện tử mẫu số01GTKT0/002, kí hiệu AA/20E, số hóa đơn AA/20E0000162, ngày lập09:22:25 19/11/2020: số tiền: 165,495 VN  
Hóa đơn thay thế cho hóa đơn điện tử mẫu số 01GTKT0/002, kí hiệuAA/20E, số hóa đơn AA/20E0000156, ngày lập 14:01:00 18/11/2020

\- Trường hợp trong itemInfo người dùng có truyền thông tin gì thì lưu theo đúng giá trị người dùng truyền.

**\- Lưu ý 2: cho phép người dùng điều chỉnh thông tin hàng hóa khi lập hóa đơn điều chỉnh thông tin qua API tích hợp:** 

*\+ Trường hợp hàng hóa trong itemInfo chỉ truyền thông tin selection hoặc lineNumber thì không lưu dữ liệu hàng hóa này*  
*\+ Trường hợp hàng hóa có ít nhất một thông tin khác (ngoài lineNumber hay selection bao gồm: itemCode, itemName, unitCode, unitName, batchNo, itemNote, expDate) thì lưu hàng hóa theo giá trị người dùng truyền vào list\_product trong invoice. Trường thông tin nào không truyền/truyền rỗng thì lưu giá trị null.*  
*\+ Các trường thông tin khác lineNumber, selection , itemCode, itemName, unitCode, unitName, batchNo, itemNote, expDate thì truyền hay không truyền giá trị đều lưu là NULL*

Dữ liệu mẫu  
"itemInfo": \[  
    { hàng\_hóa\_1},      { hàng\_hóa\_1}  
  \]

Hàng hóa thông thường  
"itemInfo": \[  
    {  
      "lineNumber": 1,  
      "itemCode": "PCDELLV3653\_i56400\_R4H10DVDRW",  
      "itemName": "Máy tính để bàn DELL VOSTRO 3653 Desktop Core i5-6400 upto3.30Ghz/ 4GB/ 1TB HDD/DVDRW/NVIDIA Geforce 705 2Gb/ Wireless-Bluetooth/ K/ M/1Yr Pro",  
      "unitName": "Cái",  
      "itemNote": "",  
      "unitPrice": 10300000,  
      "quantity": 1,  
      "itemTotalAmountWithoutTax": 10300000,  
      "itemTotalAmountWithTax": 11330000,  
      "itemTotalAmountAfterDiscount": 10300000,  
      "taxPercentage": 10,  
      "taxAmount": 1030000,  
      "customTaxAmount": "0",  
      "discount": 0,  
      "itemDiscount": 0,  
      "batchNo": "",  
      "expDate": ""  
    }  
  \]

Hàng hóa kèm ghi chú:  
"itemInfo": \[  
    {  
      "lineNumber": 2,  
      "selection": 2,  
      "itemName": "Ghi chú cho hóa đơn",  
    }  
  \]

Hàng hóa có chiết khấu trên dòng sản phẩm  
"itemInfo": \[  
    {  
      "lineNumber": 1,  
      "itemCode": "LCDLI2215S\_LNV",  
      "itemName": "Màn hình vi tính LENOVO LCD LI2215S 21.5\\" Led (65CCAACC6VN)",  
      "unitName": "Cái",  
      "itemNote": "",  
      "unitPrice": 1750000,  
      "quantity": 2,  
      "itemTotalAmountWithoutTax": 3500000,  
      "itemTotalAmountWithTax": 3696000,  
      "itemTotalAmountAfterDiscount": 3360000,  
      "taxPercentage": 10,  
      "taxAmount": 336000,  
      "customTaxAmount": "0",  
      "discount": 4,  
      "itemDiscount": 140000,  
      "batchNo": "",  
      "expDate": ""  
    }  
  \]

Hàng hóa có dòng chiết khấu  
"itemInfo": \[  
    {  
      "lineNumber": 2,  
      "itemCode": "chieu\_khau\_hang\_hoa",  
      "selection": 3,  
      "itemName": "Chiếu khấu hàng hóa",  
      "unitName": "",  
      "itemNote": "",  
      "itemTotalAmountWithoutTax": 50000,  
      "itemTotalAmountWithTax": 50000,  
      "itemTotalAmountAfterDiscount": 50000,  
      "taxPercentage": 0,  
      "taxAmount": 0,  
      "customTaxAmount": "0",  
      "discount": 0,  
      "itemDiscount": 0,  
      "isIncreaseItem": false,  
      "batchNo": "",  
      "expDate": ""  
    }  
  \]

Hàng hóa dạng bảng kê  
"itemInfo": \[  
    {  
      "lineNumber": 1,  
      "itemCode": "bang\_ke\_hang\_hoa",  
      "selection": 4,  
      "itemName": "Bảng kê hàng hóa",  
      "unitName": "",  
      "itemNote": "",  
      "itemTotalAmountWithoutTax": 97770000,  
      "itemTotalAmountWithTax": 107547000,  
      "itemTotalAmountAfterDiscount": 97770000,  
      "taxPercentage": 10,  
      "taxAmount": 9777000,  
      "customTaxAmount": "0",  
      "discount": 0,  
      "itemDiscount": 0,  
      "batchNo": "",  
      "expDate": ""  
    }  
  \]

Hàng hóa có kèm phí khác  
"itemInfo": \[  
    {  
      "lineNumber": 2,  
      "itemCode": "phi\_bao\_tri",  
      "selection": 5,  
      "itemName": "Phí bảo trì",  
      "unitName": "",  
      "itemNote": "",  
      "unitPrice": 20000,  
      "quantity": 1,  
      "itemTotalAmountWithoutTax": 20000,  
      "itemTotalAmountWithTax": 20000,  
      "itemTotalAmountAfterDiscount": 20000,  
      "taxPercentage": 0,  
      "taxAmount": 0,  
      "customTaxAmount": "0",  
      "discount": 0,  
      "itemDiscount": 0,  
      "batchNo": "",  
      "expDate": ""  
    }  
  \]

Hàng hóa là điều chỉnh giảm  
"itemInfo": \[  
    {  
      "lineNumber": 1,  
      "itemCode": "DELL\_LJ2350D",  
      "itemName": "Máy in Dell LJ 2350D 1Y Wty",  
      "unitName": "Cái",  
      "itemNote": "",  
      "unitPrice": 6281000,  
      "quantity": 3,  
      "itemTotalAmountWithoutTax": 18843000,  
      "itemTotalAmountWithTax": 20727300,  
      "itemTotalAmountAfterDiscount": 18843000,  
      "taxPercentage": 10,  
      "taxAmount": 1884300,  
      "customTaxAmount": "0",  
      "adjustmentTaxAmount": 1,  
      "discount": 0,  
      "itemDiscount": 0,  
      "isIncreaseItem": false,  
      "batchNo": "",  
      "expDate": ""  
    }  
    }  
  \]

Hàng hóa là điều chỉnh tăng  
"itemInfo": \[  
    {  
      "lineNumber": 1,  
      "itemCode": "DELL\_LJ2350D",  
      "itemName": " Máy in Dell LJ 2350D 1Y Wty",  
      "unitName": "Cái",  
      "itemNote": "",  
      "unitPrice": 6281000,  
      "quantity": 5,  
      "itemTotalAmountWithoutTax": 31405000,  
      "itemTotalAmountWithTax": 34545500,  
      "itemTotalAmountAfterDiscount": 31405000,  
      "taxPercentage": 10,  
      "taxAmount": 3140500,  
      "customTaxAmount": "0",  
      "adjustmentTaxAmount": 1,  
      "discount": 0,  
      "itemDiscount": 0,  
      "isIncreaseItem": true,  
      "batchNo": "",  
      "expDate": ""  
    }  
\]

Ghi chú của hóa đơn điều chỉnh tiền, điều chỉnh thông tin, hóa đơn thay thế sẽ được chuyển vào invoiceNote trong generalInvoiceInfo

Hàng hoá truyền itemNote 

Ví dụ hoá đơn điều chỉnh tăng số lượng, giảm đơn giá cho hàng hoá là Máy tính  
{  
  "lineNumber": 1,  
  "itemCode": "",  
  "itemName": "Máy tính",  
  "unitName": "Chiếc",  
  "unitPrice": 1500000,  
  "quantity": 20,  
  "selection": 1,  
  "itemTotalAmountWithoutTax": 30000000,  
  "taxPercentage": 10,  
  "taxAmount": 3000000,  
  "discount": null,  
  "discount2": null,  
  "itemDiscount": 0,  
  "itemNote": "Điều chỉnh tăng số lượng, giảm đơn giá",  
  "batchNo": null,  
  "expDate": null,  
  "isIncreaseItem": true  
  "adjustRatio": “1”  
}

Hệ thống tự động sinh ghi chú: Điều chỉnh tăng số lượng, giảm đơn giá của hàng hóa dịch vụ: Máy tính

Hàng hoá truyền adjustRatio 

Ví dụ áp dụng Giảm 20% mức tỷ lệ % tính thuế cho hàng hoá là Máy tính, mức tỷ lệ % tính thuế là 1%.  
{  
  "lineNumber": 1,  
  "itemCode": "",  
  "itemName": "Máy tính",  
  "unitName": "Chiếc",  
  "unitPrice": 1500000,  
  "quantity": 20,  
  "selection": 1,  
  "itemTotalAmountWithoutTax": 30000000,  
  "taxPercentage": null,  
  "taxAmount": null,  
  "discount": null,  
  "discount2": null,  
  "itemDiscount": 0,  
  "itemNote": null,  
  "batchNo": null,  
  "expDate": null,  
  "adjustRatio": “1”  
}

Hàng hoá truyền vào API lập hóa đơn nháp xăng dầu   
{  
            "lineNumber": 1,  
            "selection": 1,  
            "itemCode": "Ron92",  
            "itemName": "Xăng Ron 92",  
            "unitName": "lít",  
            "itemNote": "",  
            "unitPrice": null,  
	"unitPriceWithTax": 22000,  
            "quantity": 10,  
            "itemTotalAmountWithoutTax": null,  
            "taxPercentage": null,  
            "taxAmount": null,  
            "discount": null,  
            "itemDiscount": null,  
            "batchNo": "",  
            "itemTotalAmountWithTax": 220000,  
            "itemTotalAmountAfterDiscount": null,  
            "expDate": ""  
}

7. **taxBreakdowns**

Dùng để tổng hợp thuế suất theo mức cho hóa đơn.

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| taxPercentage | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+ | Mức thuế: khai báo giá trị như sau  \-2: không thuế \-1: không kê khai tính/nộp thuế  0: 0% 5: 5% 8: 8% 10: 10% **Note**: Mỗi một giá trị thuế chỉ xuất hiện 1 lần (lưu giá trị tổng hợp các hàng hóa cùng loại thuế đó) Bắt buộc nhập với mẫu thuế Tổng Trường hợp người dùng không truyền thông tin thì lưu giá trị null vào list\_product trong bảng invoice.  khác **Lưu ý:** trường hợp đối với hóa đơn thuế tổng, hàng hóa có tính chất ghi chú không truyền giá trị vatPercentage thì lưu giá trị thuế suất của hàng hóa là NULL, không lấy theo vatPercentage trong taxBreakDowns như hiện tại. Nếu truyền loại thuế suất khác thì truyền giá trị % thuế suất. VD: Khác 12.34% thì truyền “taxPercentage”: 12.34 |
| taxableAmount | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+ | Tổng tiền chịu thuế của mức thuế tương ứng, tổng tiền chịu thuế không có số âm. Bằng tổng của itemTotalAmountWithoutTax của tất cả các itemInfo có mức thuế suất giống với mức thuế suất tổng hợp. Trong trường hợp dòng hàng hóa là chiết khấu thì trừ đi. Không cần nhập liệu, hệ thống tự tính dựa vào các itemTotalAmountWithoutTax |
| taxAmount | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+ | Tổng tiền thuế của mức thuế tương ứng, tổng tiền thuế không có số âm. Bằng tổng của taxAmount của tất cả các itemInfo có mức thuế suất giống với mức thuế suất tổng hợp. Trong trường hợp dòng hàng hóa là chiết khấu thì trừ đi. Không cần nhập dữ liệu, nếu không truyền dữ liệu, hệ thống sẽ tự tính dựa vào taxPercentag và các itemTotalAmountWithoutTax. Nếu nhập dữ liệu cho phép chênh lệch 20,000 so với giá trị hệ thống tự tính |
| taxableAmountPos | Required: false DataType: Boolean Minlength:  Maxlength:  Format: | Dùng để biểu thị tổng tiền chịu thuế của mức thuế là âm hay dương.  \- null/true: Tổng tiền đánh thuế dương. Được sử dụng đối với các hàng hóa thông thường.  \- false: Tổng tiền đánh thuế âm, được sử dụng với hóa đơn điều chỉnh giảm hoặc hóa đơn có hàng hóa là chiết khấu mà tổng tiền của hàng hóa và chiết khấu của mức thuế là âm. |
| taxAmountPos | Required: false DataType: Boolean Minlength:  Maxlength: 20 Format: | Dùng để biểu thị tổng tiền thuế của mức thuế là âm hay dương. Giá trị của taxAmountPos luôn giống với giá trị của taxableAmountPos.  \- null/true: Tổng tiền thuế dương  \- false: Tổng tiền thuế âm |
| taxExemptionReason | Required: false DataType: String Minlength:  Maxlength: 255 Format: | Lý do miễn giảm thuế  |

**Lưu ý:** Hệ thống so sánh tổng của itemTotalAmountWithoutTax của tất cả các itemInfo trong cùng mức thuế suất với taxableAmount trong taxBreakDowns. Trong trường hợp bị lệch hệ thống sẽ báo lỗi.

Hệ thống so sánh tổng của taxAmount của tất cả các itemInfo trong cùng mức thuế suất với taxAmount trong taxBreakDowns. Trong trường hợp bị lệch hệ thống sẽ báo lỗi.

Cho phép chênh lệch tiền thuế 20,000 so với giá trị thực tính

**Dữ liệu mẫu**

Thuế có %  
"taxBreakdowns": \[  
    {  
      "taxPercentage": 5,  
      "taxableAmount": 400000,  
      "taxAmount": 20000  
    },  
    {  
      "taxPercentage": 10,  
      "taxableAmount": 400000,  
      "taxAmount": 40000  
    }  
  \]

Không thuế  
"taxBreakdowns": \[  
    {  
      "taxPercentage": \-2,  
      "taxableAmount": 400000,  
      "taxAmount": 0  
    }  
  \]

Không kê khai, tính nộp thuế  
"taxBreakdowns": \[  
    {  
      "taxPercentage": \-1,  
      "taxableAmount": 400000,  
      "taxAmount": 0  
    }  
  \]

Hóa đơn có tiền thuế âm  
"taxBreakdowns": \[  
    {  
      "taxPercentage": 10,  
      "taxableAmount": 100000,//tổng tiền âm 100000  
      "taxAmount": 10000,//thuế âm 10000  
      "taxableAmountPos": false,  
      "taxAmountPos": false  
    }  
  \]

8. **summarizeInfo**

Dùng để tổng hợp tiền hàng cho toàn bộ hóa đơn. Không sử dụng, hệ thống tự tính tổng tiền hóa đơn, đốiv ới biên lai điện tử summarizeInfo là bắt buộc trường totalAmountWithTax

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| totalAmountWithoutTax | Required: true DataType: BigDecimal Minlength:  Maxlength: 15 Format: \[0-9.\]+ | Tổng tiền hóa đơn chưa bao gồm VAT (đã tính hàng hóa chiết khấu (nếu có)). Tổng tiền hóa đơn không có số âm. \- Hóa đơn thường: Tổng tiền HHDV trên các dòng HĐ và các khoản tăng/giảm khác trên toàn HĐ.  \- Hóa đơn điều chỉnh: Tổng tiền điều chỉnh của các dòng HĐ và các khoản tăng/giảm khác trên toàn HĐ. |
| totalTaxAmount | Required: false DataType: BigDecimal Minlength:  Maxlength: 13 Format: \[0-9.\]+ | Tổng tiền thuế trên toàn hóa đơn. Tổng tiền thuế không có số âm. \- Hóa đơn thường: Tổng tiền VAT trên các dòng HĐ và các khoản thuế khác trên toàn HĐ. \- Hóa đơn điều chỉnh: Tổng tiền VAT điều chỉnh của các dòng HĐ và các khoản tăng/giảm VAT khác trên toàn HĐ.  |
| totalAmountWithTax | Required: false DataType: BigDecimal Minlength:  Maxlength: 13 Format: \[0-9.\]+ | Tổng tiền trên hóa đơn đã bao gồm VAT. Tổng tiền sau thuế không có số âm. \- Hóa đơn thường: Tổng tiền HHDV trên các dòng HĐ và các khoản tăng/giảm khác trên toàn HĐ đã bao gồm cả VAT. \- Hóa đơn điều chỉnh: Tổng tiền điều chỉnh của các dòng HĐ và các khoản tăng/giảm khác trên toàn HĐ đã bao gồm cả VAT \- Đối với biên lại điện tủ phần tiền thì thông tin này là bắt buộc   |
| totalAmountWithTaxFrn | Required: false DataType: BigDecimal Minlength:  Maxlength: 13 Format: \[0-9.\]+ | Tổng tiền ngoại tệ của hóa đơn đã bao gồm VAT. Dùng trong trường hợp hóa đơn không chọn loại tiền là VND \- Hóa đơn thường: Tổng tiền HHDV trên các dòng HĐ và các khoản tăng/giảm khác trên toàn HĐ đã bao gồm cả VAT. \- Hóa đơn điều chỉnh: Tổng tiền điều chỉnh của các dòng HĐ và các khoản tăng/giảm khác trên toàn HĐ đã bao gồm cả VAT |
| totalAmountWithTaxInWords | Required: false DataType: String Minlength:  Maxlength: 255 Format: | Số tiền hóa đơn bao gồm VAT viết bằng chữ. Hệ thống hóa đơn điện tử sẽ tự động sinh lại dữ liệu này để đảm bảo đúng theo dữ liệu hệ thống.  |
| isTotalAmountPos | Required: false DataType: Boolean Minlength:  Maxlength: 20 Format: | Để đánh dấu tổng tiền sau thuế là âm hay dương \- null/True: Tổng tiền là số dương, sử dụng đối với các hóa đơn thông thường hoặc hóa đơn có chiết khấu nhưng tổng tiền vẫn là dương sau khi trừ chiết khấu. \- False: Tổng tiền âm, sử dụng đối với hóa đơn điều chỉnh giảm hoặc có chiết khấu mà tiền chiết khấu lớn hơn tiền hàng hóa thông thường. |
| isTotalTaxAmountPos | Required: false DataType: Boolean Minlength:  Maxlength: 20 Format: | Để đánh dấu tổng tiền thuế là âm hay dương \- null/true: tổng tiền thuế là dương \- false: tổng tiền thuế là âm  |
| isTotalAmtWithoutTaxPos | Required: false DataType: Boolean Minlength:  Maxlength: 20 Format: | Để đánh dấu tổng tiền trước thuế là âm hay dương \- null/true: tổng tiền trước thuế là dương \- false: tổng tiền trước thuế là âm |
| discountAmount | Required: true DataType: BigDecimal Minlength:  Maxlength: 13 Format: \[0-9.\]+ | Tổng tiền chiết khấu thương mại trên toàn hóa đơn trước khi tính thuế. Chú ý: Khi tính chiết khấu, toàn hóa đơn chỉ sử dụng một mức thuế.  Lưu ý: Đối với hóa đơn thuế tổng, chiết khấu trước thuế có 2 cách nước thuế có 2 cách nhập liệu Nhập tỷ lệ % chiết khấu và tiền chiết khấu trên từng dòng hàng hóa (itemInfo.discount, itemInfo.itemDiscount) Nhập thêm 1 hàng hóa dạng chiết khấu (selection \= 3\) Trường hợp nhập theo cả 2 cách thì discountAmount bằng tổng của 2 giá trị |
| settlementDiscountAmount | Required: false DataType: BigDecimal Minlength:  Maxlength: 13 Format: \[0-9.\]+ | Tổng tiền chiết khấu thanh toán trên toàn hóa đơn sau khi tính thuế. Chú ý: Khi tính chiết khấu, toàn hóa đơn chỉ sử dụng một mức thuế.  |
| isDiscountAmtPos | Required: false DataType: Boolean Minlength:  Maxlength: 20 Format: | Trường nhận biết tổng tiền chiết khấu là số dương hay âm \- null/true: tổng tiền chiết khấu là dương \- false: tổng tiền chiết khấu là âm  |
| extraName | Required: false DataType: String Minlength:  Maxlength: 500 Format: {} | Tên bổ sung Có thể truyền nhiều giá trị được phân cách nhau bằng dấu “,” *Ví dụ: {Phụ phí, Phí thu thêm}*  |
| extraValue | Required: false DataType: String Minlength:  Maxlength: 500 Format: {} | Giá trị của trường bổ sung Có thể truyền nhiều giá trị được phân cách nhau bằng dấu “,” Ví dụ: *{10000, 100}* |
| totalAmountAfterDiscount | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+ | Là tổng tiền hóa đơn sau khi trừ chiết khấu, giảm giá, chưa bao gồm VAT. Tổng tiền hóa đơn không có số âm. **Lưu ý:** Trường hợp truyền giá trị 0 hoặc “0” cho trường validation: bắt buộc phải truyền giá trị khác null |

Dữ liệu mẫu

Hóa đơn thường  
"summarizeInfo": {  
    "sumOfTotalLineAmountWithoutTax": 100000,  
    "totalAmountWithoutTax": 100000,  
    "totalTaxAmount": 10000,  
    "totalAmountWithTax": 110000,  
    "totalAmountAfterDiscount": 0,  
    "totalAmountWithTaxInWords": "Một trăm mười nghìn đồng",  
    "discountAmount": 0,  
    "taxPercentage": 10,  
    "extraName": "{ Tiền phí đặc biệt, Tiền phí,  } ",  
    "extraValue": "{ 00 ,00,}"  
  }

Hóa đơn có tổng tiền âm  
"summarizeInfo": {  
    "sumOfTotalLineAmountWithoutTax": 100000,  
    "totalAmountWithoutTax": 100000,  
    "totalTaxAmount": 10000,  
    "totalAmountWithTax": 110000,  
    "totalAmountAfterDiscount": 0,  
    "totalAmountWithTaxInWords": "Một trăm mười nghìn đồng",  
    "discountAmount": 0,  
    "taxPercentage": 10,  
    "isTotalAmountPos": false,  
    "isTotalTaxAmountPos": false,  
    "isTotalAmtWithoutTaxPos": false	  
    "extraName": "{ Tiền phí đặc biệt, Tiền phí,  } ",  
    "extraValue": "{ 00 ,00,}"	  
  }

9. **metadata**

Dữ liệu các trường thông tin động (Thông tin trường bổ sung), ngoài các trường thông tin được mô tả ở trong mục 6 này. Nếu như trường thông tin chưa tồn tại trong mục 5, sẽ phải khai thêm. Trường động này sẽ gắn riêng cho từng mẫu hóa đơn của từng khách hàng. Danh sách các trường động của một mẫu cụ thể sẽ được lấy bằng hàm 7.7

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| keyTag | Required: false DataType: String Minlength:  Maxlength:  Format:  | Tên dữ liệu Text:  Number: Date: Duedate  |
| valueType | Required: false DataType: String Minlength:  Maxlength:  Format:  | Kiểu dữ liệu gồm: text, number, date  |
| dateValue | Required: false DataType: Date Minlength:  Maxlength:  Format:  | Giá trị dữ liệu khi kiểu là date.  |
| stringValue | Required: false DataType: String Minlength:  Maxlength: 500 Format: | Giá trị dữ liệu khi kiểu là text  |
| numberValue | Required: false DataType: Integer Minlength:  Maxlength: 6 Format: | Giá trị dữ liệu khi kiểu là number  |
| keyLabel | Required: false DataType: String Minlength:  Maxlength: 50 Format: | Nhãn hiển thị của dữ liệu  |
| isRequired | Required: false DataType: Boolean Minlength:  Maxlength:  Format: | Giá trị có bắt buộc hay không  |
| isSeller | Required: false DataType: Boolean Minlength:  Maxlength:  Format: | Giá trị của người bán hay mua False: Người mua True: Người bán  |

Dữ liệu mẫu  
"metadata": \[  
    {  
      "keyTag": "dueDate",  
      "valueType": "date",  
      "dateValue": 1544115600000,  
      "keyLabel": "Hạn thanh toán",  
      "isRequired": false,  
      "isSeller": false  
    },  
    {  
      "keyTag": "contractNo",  
      "stringValue": "555",  
      "valueType": "text",  
      "keyLabel": "Hợp dong số",  
      "isRequired": false,  
      "isSeller": false  
    }  
  	\]

Một số metadata **đặc biệt** (được sử dụng làm trường chuẩn của XML thông tư 78\)

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| **PHIẾU XUẤT KHO KIÊM VẬN CHUYỂN NỘI BỘ** |  |  |
| economicContractNo | Required: true DataType: String Minlength:  Maxlength:   Format: | Lệnh điều động nội bộ Tên thẻ trong XML: “LDDNBo” Vị trí thẻ trong XML: “DLHDon/NDHDon/NBan/LDDNBo” |
| transformer | Required: false DataType: String Minlength:  Maxlength:   Format: | Tên người vận chuyển Tên thẻ trong XML: “TNVChuyen” Vị trí thẻ trong XML: “DLHDon/NDHDon/NBan/TNVChuyen” |
| vehicle | Required: true DataType: String Minlength:  Maxlength:   Format: | Phương tiện vận chuyển Tên thẻ trong XML: “PTVChuyen” Vị trí thẻ trong XML: “DLHDon/NDHDon/NBan/PTVChuyen” |
| contractNo | Required: false DataType: String Minlength:  Maxlength:   Format: | Hợp đồng số Tên thẻ trong XML: “HDSo” Vị trí thẻ trong XML: “DLHDon/NDHDon/NBan/HDSo” |
| exporterName | Required: false DataType: String Minlength:  Maxlength:   Format: | Họ và tên người xuất hàng Tên thẻ trong XML: “HVTNXHang” Vị trí thẻ trong XML: “DLHDon/NDHDon/NBan/HVTNXHang” |

Một số metadata **đặc biệt** (được sử dụng làm trường chuẩn của XML thông tư 78\)

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| **PHIẾU XUẤT KHO HÀNG GỬI ĐẠI LÝ** |  |  |
| economicContractNo | Required: true DataType: String Minlength:  Maxlength:   Format: | Hợp đồng kinh tế số Tên thẻ trong XML: “HDKTSo” Vị trí thẻ trong XML: “DLHDon/NDHDon/NBan/HDKTSo” |
| commandDate | Required: true DataType: Date Minlength:  Maxlength:   Format: | Hợp đồng kinh tế ngày  Tên thẻ trong XML: “HDKTNgay” Vị trí thẻ trong XML: “DLHDon/NDHDon/NBan/HDKTNgay” |
| transformer | Required: true DataType: String Minlength:  Maxlength:   Format: | Tên người vận chuyển  Tên thẻ trong XML: “TNVChuyen” Vị trí thẻ trong XML: “DLHDon/NDHDon/NBan/TNVChuyen” |
| vehicle | Required: true DataType: String Minlength:  Maxlength:   Format: | Phương tiện vận chuyển  Tên thẻ trong XML: “PTVChuyen” Vị trí thẻ trong XML: “DLHDon/NDHDon/NBan/PTVChuyen” |
| contractNo | Required: false DataType: String Minlength:  Maxlength:   Format: | Hợp đồng số (Hợp đồng vận chuyển) Tên thẻ trong XML: “HDSo” Vị trí thẻ trong XML: “DLHDon/NDHDon/NBan/HDSo” |
| HVTNXHang | Required: false DataType: String Minlength:  Maxlength:   Format: | Họ và tên người xuất hàng Tên thẻ trong XML: “HVTNXHang” Vị trí thẻ trong XML: “DLHDon/NDHDon/NBan/HVTNXHang” |

Một số metadata **đặc biệt** (được sử dụng làm trường chuẩn của XML thông tư 78\)

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| **PHIẾU BÁN HÀNG PHI THUẾ QUAN** |  |  |
| KPTQuan | Required: true DataType: String Minlength:  Maxlength:   Format: | thể hiện mẫu phi thuế quan \-  truyền giá trị bằng 1 để hiện thỉ mẫu phi thuế quan bên thuế \- Lưu ý định dạng bắt buộc phải là text chứ không được khai báo dạng number hay date.  |

Một số metadata **đặc biệt** (được sử dụng làm trường chuẩn của XML thông tư 78\)

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| **HÓA ĐƠN GTGT KIÊM TỜ KHAI HOÀN THUẾ** |  |  |
| SHChieu | Required: true DataType: String Minlength:  Maxlength: 20 Format: | Số hộ chiếu Tên thẻ trong XML: “SHChieu” Vị trí thẻ trong XML: “HDon\\DLHDon\\NDHDon\\NMua\\SHChieu” |
| NCHChieu | Required: true DataType: Date Minlength:  Maxlength:   Format: | Ngày cấp hộ chiếu Tên thẻ trong XML: “NCHChieu” Vị trí thẻ trong XML: “HDon\\DLHDon\\NDHDon\\NMua\\NCHChieu” |
| NHHHChieu | Required: true DataType: Date Minlength:  Maxlength:   Format: | Ngày hết hạn hộ chiếu Tên thẻ trong XML: “NHHHChieu” Vị trí thẻ trong XML: “HDon\\DLHDon\\NDHDon\\NMua\\NHHHChieu” |
| QTich | Required: true DataType: String Minlength:  Maxlength: 50 Format: | Quốc tịch Tên thẻ trong XML: “QTich” Vị trí thẻ trong XML: “HDon\\DLHDon\\NDHDon\\NMua\\QTich” |

10. **meterReading**

Dữ liệu đặc thù cho riêng hóa đơn điện/nước.

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| meterName | Required: false DataType: String Minlength:  Maxlength: 50 Format: | Tên chỉ số |
| previousIndex | Required: false DataType: Number Minlength:  Maxlength:  Format:  | Chỉ số cũ của hóa đơn điện nước.  |
| currentIndex | Required: false DataType: Number Minlength:  Maxlength:  Format:  | Chỉ số mới của hóa đơn điện nước.  |
| factor | Required: false DataType: Number Minlength:  Maxlength:  Format:  | Hệ số nhân của hóa đơn điện nước. Vị dụ như nước sinh hoạt sẽ có hệ số nhân khác với nước kinh doanh. Nội dung này sẽ tùy theo công ty điện/ nước quy định và hiển thị.  |
| amount | Required: false DataType: Number Minlength:  Maxlength:  Format: | Tổng số của hóa đơn  Hệ thống không validate công thức tính toán ra giá trị  |

Dữ liệu mẫu  
"meterReading": \[{  
	            "previousIndex": "110",  
	            "currentIndex": "150",  
	            "factor": "1",  
	            "amount": "40"  
	          },  
	          {  
	            "previousIndex": "44",  
	            "currentIndex": "50",  
	            "factor": "1",  
	            "amount": "6"  
	          }\]

11. **invoiceFile**

Các file đính kèm khi lập hóa đơn

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| fileContent | Required: false DataType: String | Nội dung file dạng chuỗi base64  |
| fileType | Required: false DataType: Double  | Loại file 1: bảng kê (Cho phép định dạng xlsx) 2: biên bản thỏa thuận (Cho phép định dạng .doc, .docx, .pdf, .png, .jpg) |
| fileExtension | Required: false DataType: String | Định dạng file theo từng loại tương ứng fileType |

Dữ liệu mẫu  
"invoiceFile": {  
      "fileType": 1,  
      "fileExtension": "xlsx",  
      "fileContent": "RmlsZSBi4bqjbmcga8OqIMSRxrDhu6NjIGFkZCBsw6puIHThuqFpIHBo4bqnbiBs4bqtcCBow7NhIMSRxqFu"  
   }

12. **qrcode**

- API cho phép người dùng hệ thống tích hợp lập hóa đơn điện tử trên hệ thống hóa đơn điện tử sử dụng chữ ký server.

- Mô tả chung: Bổ sung thêm thông tin về QRCODE khi lập hóa đơn bằng API tích hợp sử dụng chữ ký server.

- **Input**: 

- Bổ sung thêm 05 trường thông tin trong tham số đầu vào đặt trong qrCodeInfo như sau: 

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| totalQrcode | Required: false DataType: int(3) Minlength:  Maxlength:  Format:  | Tổng số lần được quét QRCODE |
| remainQrcode | Required: false DataType: int(3) Minlength:  Maxlength:  Format:  | Số lần quét QRCODE còn lại |
| startDateQrcode | Required: false DataType: timestamp Minlength:  Maxlength:  Format:  | Thời gian bắt đầu hiệu lực của QRCODE |
| endDateQrcode | Required: false DataType: timestamp Minlength:  Maxlength:  Format:  | Thời gian kết thúc hiệu lực của QRCODE |

  13. **fuelReading**

Dữ liệu đặc thù cho riêng hóa đơn xăng dầu có ghi nhận log bơm.

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| idLog | Required: false DataType: String Minlength:  Maxlength: 50 Format: | Mã log bơm |
| noteLog | Required: false DataType: String Minlength:  Maxlength: 100 Format:  | Ghi chú  |
| pumpCode | Required: false DataType: String Minlength:  Maxlength: 50 Format:  | Mã vòi bơm  |
| pumpName | Required: false DataType: String Minlength:  Maxlength: 50 Format:  | Tên vòi bơm  |
| qtyLog | Required: false DataType: BigDecimal Minlength:  Maxlength: 20 Format: \[0-9.\]+ | Số lượng log bơm  Số lượng của hàng hóa, luôn là số dương  |
| priceLog | Required: false DataType: BigDecimal Minlength:  Maxlength: 20 Format: \[0-9.\]+ | Đơn giá áp theo cột bơm. Đơn giá của hàng hóa, không có số âm.   |
| productCode | Required: false DataType: string Minlength:  Maxlength: 50 Format: | Mã hàng hóa  |
| productName | Required: false DataType: string Minlength:  Maxlength: 50 Format: | Tên hàng hóa  |
| startDate | Required: false DataType: Datetime Minlength: N/A Maxlength:  Format: mục 5.1 | Thời gian bắt đầu bơm  |
| endDate | Required: false DataType: Datetime Minlength: N/A Maxlength:  Format: mục 5.1 | Thời gian kết thúc bơm  |
| batch | Required: false DataType: string Minlength:  Maxlength: 50 Format: | Mã chứng từ  |
| thanhTienLog | Required: false DataType: BigDecimal Minlength:  Maxlength: 20 Format: \[0-9.\]+ | Thành tiền được tính bằng công thức số lượng \* Đơn giá trên cột bơm  |

Dữ liệu mẫu  
    "fuelReading": \[  
        {  
            "idLog": 1,  
            "noteLog": "Ghi chu 1",  
            "pumpCode": "code1",  
            "pumpName": "name1",  
            "qtyLog": 1,  
            "priceLog": 20000,  
            "productCode": "pCode1",  
            "productName": "pName1",  
            "startDate": 1700594681000,  
            "endDate": 1700594681000,  
            "batch": "Ma01",  
            "thanhTienLog": 20000  
        },  
        {  
            "idLog": 2,  
            "noteLog": "Ghi chu 2",  
            "pumpCode": "code2",  
            "pumpName": "name2",  
            "qtyLog": 1,  
            "priceLog": 200000,  
            "productCode": "pCode2",  
            "productName": "pName2",  
            "startDate": 1700594681000,  
            "endDate": 1700594681000,  
            "batch": "Ma01",  
            "thanhTienLog": 200000  
        }  
    \]

7. **Các API kết nối**

   1.  **Các khái niệm chung**  

Giải thích 1 request bao gồm

- **Action:** Phương thức và hàm thực thi (Vị dụ: “/InvoiceAPI/InvoiceWS” phương thức POST).

- **Content-Type:** Kiểu thông tin request

- **Data:** định dạng dữ liệu truyền vào.

- **Đầu ra webservice:** Đối tượng Response mô tả trạng thái lỗi Webservice trả về và đối tượng dữ liệu Webservice trả về 

- **Thông tin hệ thống test** (Thực hiện test kết nối trên hệ thống test không test kết nối trên hệ thống thật)

- **Thông tin hệ thống tích hợp** 

Link web**:** [https://vinvoice.viettel.vn](https://vinvoice.viettel.vn)

Link API: [https://api-vinvoice.viettel.vn/services/einvoiceapplication/api/](https://api-vinvoice.viettel.vn/services/einvoiceapplication/api/)

- **Header xác thực:** Header xác thực được gửi đi cùng mỗi request trong quá trình sử dụng. Xác thực bằng token sinh ra sau khi thực hiện gọi API login trong mục 5.5. Header cần truyền thêm thông tin Cookie có access\_token dạng access\_token=abc\_def (Xem Vị dụ tại 5.5.	Tiêu chuẩn bảo mật kết nối)

**C\#:** 

WebRequest request \= WebRequest.Create(pzUrl);

request.Headers.Add("Cookie","access\_token=abc\_def");

**Java:** 

String path \= "url";

HttpPost post \= new HttpPost(path);

post.[setHeader](https://www.codota.com/code/java/methods/org.apache.http.client.methods.HttpPost/setHeader)("Cookie", "access\_token=abc\_def");

- Header định dạng dữ liệu: Dữ liệu gửi lên Web service có thể là JSON, FormParam hay QueryParam

  * Với JSON: Thêm header: Content-Type: application/json

  * Với FormParam: Thêm header: Content-Type: application/x-www-form-urlencoded

  * Với QueryParam: Không cần header, tham số truyền vào qua URL

- Dữ liệu trả về từ Web service là JSON

  * Để nhận về JSON: Thêm header: Accept: application/json

**Lưu ý:** Do cần thời gian kết nối và thời gian xử lý yêu cầu nên kết quả trả về có thể phải chờ 1 khoảng thời gian (khuyến nghị để thời gian timeout khi gửi yêu cầu khoảng 60-90 giây)

2.  **Phát hành/thay thế/điều chỉnh hóa đơn cho CTS SERVER**

**\* Quy tắc kiểm tra ngày lập hóa đơn:**

Hệ thống Hóa đơn điện tử SInvoice V2, phần Cấu hình chung liên quan ngày lập hóa đơn có 2 checkbox: Cho phép ngày lập hóa đơn khác ngày hiện tại, Tự động đặt giá trị cho ngày lập hóa đơn bằng ngày lập gần nhất.

Khi phát hành hóa đơn qua API, ngày lập hóa đơn sẽ bị ảnh hưởng khi người dùng tích chọn các checkbox này, xảy ra 4 trường hợp như mô tả sau:

**TH1: Không tích cả 2**

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: ngày lập không hợp lệ

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại: ngày lập không hợp lệ

\- Ngày lập \> ngày hiện tại: lấy ngày truyền vào (không kiểm tra giờ)

**TH2: Tích “Cấu hình ngày ký là thời điểm hiện tại”**

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: lấy ngày của hóa đơn đã lập gần nhất 

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại: lấy ngày truyền vào 

\- Ngày lập \> ngày hiện tại: ngày lập không hợp lệ

**TH3: Tích “Tự động đặt giá trị cho ngày lập hóa đơn bằng ngày lập gần nhất”**

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: ngày lập không hợp lệ

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại: lấy ngày truyền vào 

\- Ngày lập \> ngày hiện tại: ngày lập không hợp lệ

**TH4: Tích cả 2** 

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: lấy ngày của hóa đơn đã lập gần nhất 

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại:  lấy ngày truyền vào 

\- Ngày lập \> ngày hiện tại: ngày lập không hợp lệ

* **Đầu vào:**

Webservice dùng chung trong các trường hợp lập hóa đơn gốc, lập hóa đơn điều chỉnh tiền, lập hóa đơn điều chỉnh thông tin, lập hóa đơn thay thế

- Action (POST): InvoiceAPI/InvoiceWS/createInvoice/{supplierTaxCode}

- Headers:

\+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

\+ Content-Type : application/json 

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required: true DataType: String Minlength:  Maxlength: 20 Format :  | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 Hệ thống sẽ dùng trường thông tin này để kiểm tra và lấy thông tin về mã số thuế của chi nhánh/doanh nghiệp. [https://vi.wikipedia.org/wiki/Thu%E1%BA%BF\_Vi%E1%BB%87t\_Nam](https://vi.wikipedia.org/wiki/Thu%E1%BA%BF_Vi%E1%BB%87t_Nam)  Trong quá trình tích hợp nếu đơn vị sử dụng nhiều tài khoản của nhiều phòng ban để phát hành hóa đơn cùng lúc thì nên tách mỗi phòng ban 1 ký hiệu hóa đơn để sử dụng.  Vị dụ: \+ Phòng kế toán dùng ký hiệu: C22TKT \+ Phòng tổng hợp dùng ký hiệu: C22TTH Ngoài ra có thể áp dụng phân tách ký hiệu hóa đơn theo user sử dụng Vị dụ: \+ Tài khoản A dùng ký hiệu C22TAA \+ Tài khoản B dùng ký hiệu C22TBB |
| originalInvoiceType | Required: True DataType: String Minlength: N/A Maxlength:  Format: | Loại hóa đơn gốc Truyền giá trị số với ý nghĩa như sau  0- Không phải hóa đơn giấy/hóa đơn không tồn tại trên hệ thống  1-Hóa đơn TT78  2-Hóa đơn theo QĐ 1209  3-Hóa đơn điện tử/giấy TT32 4-Hóa đơn giấy TT 78 Chú ý:  \- Trường hợp thẻ originalInvoiceType không truyền hoặc truyền giá trị rỗng/0 thì không bắt buộc truyền thẻ originalTemplateCode, hệ thống xác thực thông tin khi lập hóa đơn như hiện trạng.  \- Trường hợp thẻ originalInvoiceType truyền giá trị 1, 2, 3 hoặc 4 thì  \+ Bắt buộc phải truyền thẻ originalTemplateCode, quy tắc xác thực thẻ này tương tự như thẻ templateCode hiện tại.   \+ Khi lập hóa đơn, hệ thống **không kiểm tra tính tồn tại** của hóa đơn gốc trên hệ thống, các quy tắc xác thực khác giữ nguyên hiện trạng |
| originalTemplateCode | Required:  DataType: String Minlength: N/A Maxlength: 20 Format: | Bắt buộc truyền nếu originalInvoiceType là 1, 2, 3 hoặc 4 Ví dụ mẫu TT32: 01GTKT0/001 Ví dụ mẫu TT78: 1/0224 |

- Data: Dữ liệu mẫu lập hóa đơn (**Chi tiết các đối tượng xem từng mục nhỏ trong phần 6**)

**{**  
   **"generalInvoiceInfo":{ //Thông tin chung của hóa đơn**  
   **},**  
   **"buyerInfo":{      //thông tin người bán**  
   **},**  
   **"sellerInfo":{      //thông tin người mua**  
   **},**  
   **"payments":\[	//thông tin thanh toán**        
   **\],**  
   **"itemInfo":\[      //thông tin hàng hóa**  
   **\],**     
   **"metadata":\[	//thông tin trường động**  
   **\],**  
   "**meterReading": 	//thông tin đặc biệt dành cho hóa đơn điện nước**  
   **\],**  
   **"summarizeInfo":{	//thông tin tổng hợp tiền của hóa đơn**  
   **},**  
   **"taxBreakdowns":\[	//thông tin gom nhóm tiền hóa đơn theo thuế suất**  
   **\]**  
**}**

**Lưu ý:** 

1. Các dữ liệu này bao gồm tất cả các trường dữ liệu có thể có khi lập hóa đơn. Không phải tất cả các trường thông tin đều bắt buộc, người dùng có thể bỏ bớt cho phù hợp với nhu cầu của khách hàng. Chi tiết các trường thông tin bắt buộc hoặc không bắt buộc xem ở mục 6\.

2. Nếu là lập hóa đơn máy tính tiền thì respond trả về có cả thông tin Mã CQT cấp: "codeOfTax", nếu không phải hóa đơn máy tính tiền thì trả về “codeOfTax” \= null

   VD mẫu output

   {

       "errorCode": null,

       "description": null,

       "result": {

           "supplierTaxCode": "0100109106-710",

           "invoiceNo": "C23MHY3",

           "transactionID": "168378907853232661",

           "reservationCode": "2QTBFEMAXFWZO5B",

           "codeOfTax": "M1-23-34567-00000000201"

       }

   }

3. Nếu cấu hình Không ký hóa đơn có mã khởi tạo từ máy tính tiền và hóa đơn thuộc loại máy tính tiền thì cho phép doanh nghiệp dùng chữ ký USB Token và CloudCA lập hóa đơn **Phát hành** bằng API Server.

4. Nếu người dùng truyền giá trị 0 hoặc “0” cho tham số validation trong phần generalInvoiceInfo thì các thông tin được truyền trong phần itemInfo, taxBreakdowns, summarizeInfo sẽ được giữ nguyên mà không thực hiện kiểm tra ràng buộc và tính toán lại.  
5. Do cơ chế xử lý bất đồng bộ nên nếu response trả về không có số hóa đơn: "invoiceNo":""  
* Sau 30s-90s Gọi thêm 1 bước lấy lại số hóa đơn bẳng hàm tra cứu hóa đơn bẳng transactionUid: (tài liệu **7.21	Tra cứu hóa đơn bằng transactionUuid)** (Đề xuất viết 1 luồng offline quét những hóa đơn phát hành thành công nhưng chưa có số để lấy lại số hóa đơn)

| Dữ liệu mẫu | JSON | Lưu ý |
| ----- | ----- | ----- |
| Hóa đơn gốc | ![][image9]![][image10]![][image11]![][image12]![][image13]![][image14]![][image15]![][image16] |  |
| Hóa đơn thay thế | ![][image17] |  |
| Hóa đơn điều chỉnh thông tin  | ![][image18] | Không ghi nhận các giá trị trong itemInfo |
| Hóa đơn điều chỉnh tiền  | ![][image19] | Không ghi nhận các giá trị trong buyerInfo |
| Phiếu xuất kho nội bộ | ![][image20] ![][image21] | Lưu ý 2 giá trị *economicContractNo*, *vehicle* là bắt buộc phải truyền với thông tư 78 |
| Phiếu xuất kho đại lý | ![][image22] | Lưu ý 4 giá trị *economicContractNo*, *vehicle,* *commandDate, transformer* là bắt buộc phải truyền với thông tư 78 |
| Hóa đơn xăng dầu | ![][image23] |  |

* **Đầu ra:**

Đối tượng Response mô tả trạng thái lỗi Webservice trả về và đối tượng dữ liệu Webservice trả về:

* Dữ liệu về thông tin về hóa đơn đã lập

**{**  
  "errorCode": ""**,**  
  "description": ""**,**  
  "result": **{**  
    "supplierTaxCode": 1258694363**,**  
    "invoiceNo": AA**/**20E0000001**,**  
    "transactionID": 12523522245**,**  
    "reservationCode": AXHBNK8I0H  
  **}**  
**}**

**Ví dụ response trường hợp truyền sai giá trị originalInvoiceType**  
{  
    "code": 400,  
    "message": "BAD\_REQUEST\_ORIGINAL\_INVOICE\_TYPE\_INVALID",  
    "data": "BAD\_REQUEST\_ORIGINAL\_INVOICE\_TYPE\_INVALID"  
}

**Mô tả**

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null nếu lập hóa đơn thành công) |
| description | Mô tả lỗi (giá trị là null nếu lập hóa đơn thành công) |
| supplierTaxCode | Mã số thuế người bán (doanh nghiệp phát hành hóa đơn) |
| invoiceNo | Số hóa đơn Vị dụ: AA/20E0000001  |
| transactionID | Id của giao dịch |
| reservationCode | Mã số bí mật dùng để khách hàng tra cứu |

* **Vị dụ:** 

  **![][image24]**

  **![][image25]**

  3.  **Lấy file hóa đơn**

Webservice dùng cho hệ thống tích hợp có thể lấy các file hóa đơn sau khi được phát hành thành công. 

**Lưu ý:** 

+ Hệ thống hóa đơn điện tử chạy theo cơ chế bất đồng bộ, vì vậy hệ thống đẩy hóa đơn lên cơ sở dữ liệu sau khi nhận request phát hành hóa đơn khoảng 1s. Vì vậy, khi tích hợp, request lấy file hóa đơn nên được thực hiện sau từ 2-5 giây sau khi phát hành hóa đơn.

+ Hệ thống chỉ lấy lên những hóa đơn có trạng thái khả dụng (state \= 1).

* **Đầu vào:**

- Action (POST): [/InvoiceAPI/](https://10.60.108.210:8273/InvoiceAPI/InvoiceWS/createBatchInvoice/0100109106)InvoiceUtilsWS/getInvoiceRepresentationFile

- Headers:

\+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web hoặc Authorization: username/pass như đăng nhập trên web

\+ Content-Type : application/json

Các tham số của đối tượng CommonDataInput

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| :---- | :---- | :---- |
| supplierTaxCode | Required: true DataType: String Minlength:  Maxlength: 20 Format : \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 [https://vi.wikipedia.org/wiki/Thu%E1%BA%BF\_Vi%E1%BB%87t\_Nam](https://vi.wikipedia.org/wiki/Thu%E1%BA%BF_Vi%E1%BB%87t_Nam) |
| invoiceNo | Required : true DataType: String Minlength: 7 Maxlength: 35 Format : \[a-zA-Z0-9\]\*$ | Số hóa đơn, bao gồm ký hiệu hóa đơn và số thứ tự hóa đơn  |
| templateCode | Required : true DataType: String Minlength :  Maxlength : 20 Format :  | Mã mẫu hóa đơn VD:  01GTKT0/001 1/001 |
| transactionUuid | Required : false DataType: String Minlength : 10 Maxlength : 36 Format : N/A | Chuỗi kiểm tra dữ liệu (fkey) được truyền vào khi lập hóa đơn. Chi tiết xem mục 6.2  |
| fileType | Required : false DataType: String Minlength : 3 Maxlength : 3 Format : N/A | Loại file muốn tải về, các định dạng được phép  ZIP, PDF  |
| paid | Required : false DataType: boolean Minlength :  Maxlength :  Format : N/A | true – Đã thanh toán false – Chưa thanh toán  |
| startDate | Required : false DataType: Date Minlength :  Maxlength : 50 Format : | Ngày lập từ ngày Định dạng "2019-05-12"  |
| endDate | Required : false DataType: Date Minlength :  Maxlength : 50 Format : | Ngày lập đến ngày Định dạng "2019-05-12" Lưu ý: Khoảng thời gian lập tối đa 3 tháng (endDate – startDate) \<= 3 tháng |

Vị dụ mẫu và các trường dữ liệu:

- JSON:

  {

  "supplierTaxCode":"0100109106-712",

  "invoiceNo":"AA/20E0000166",

  "templateCode":"01GTKT0/002",

  "transactionUuid":"testuuid9999999",

  "fileType":"ZIP"

  }

* **Đầu ra:**

  Đối tượng Response với HTTPStatus và output Entity.

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null không có lỗi gì xảy ra) |
| description | Mô tả lỗi (giá trị là null không có lỗi gì xảy ra) |
| fileName | Tên file tải về |
| fileToBytes | Nội dung file được chuyển thành kiểu byte Mảng bytes file hóa đơn, chuyển mảng bytes này ra file sẽ được file chứa các thông tin của hóa đơn, Vị dụ file .zip bao gồm file .xml, .xsl, ảnh logo, watermark, qrcode Code chuyển ra file Java **FileUtils.writeByteArrayToFile(newFile("D:/viettel/fileName.zip"), output.getFileToBytes());** |

  4.  **Lấy file hóa đơn có mã số bí mật**

Cho phép lấy file hóa đơn được phát hành thành công có kiểm tra mã số bí mật.

**Lưu ý:** 

+ Hệ thống hóa đơn điện tử chạy theo cơ chế bất đồng bộ, vì vậy hệ thống đẩy hóa đơn lên cơ sở dữ liệu sau khi nhận request phát hành hóa đơn khoảng 1s. Vì vậy, khi tích hợp, request lấy file hóa đơn nên được thực hiện sau từ 2-5 giây sau khi phát hành hóa đơn.

+ Hệ thống chỉ lấy lên những hóa đơn có trạng thái khả dụng (state \= 1).

* **Đầu vào:**

- Action (POST): InvoiceAPI/InvoiceUtilsWS/getInvoiceFilePortal

- Headers:

   \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

   \+ Content-Type : application/x-www-form-urlencoded

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required: true DataType: String Minlength:  Maxlength: 20 Format: \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001  |
| templateCode | Required : true DataType: String Minlength :  Maxlength : 20 Format :  | Mã mẫu hóa đơn VD:  01GTKT0/001 1/001 |
| invoiceNo | Required: true DataType: String Minlength: 7 Maxlength: 35 Format:  \[a-zA-Z0-9\]\*$ | Là số hóa đơn \= ký hiệu hóa đơn \+ số thứ tự hóa đơn vd: AA/20E0000001, tuân theo chuẩn của cục thuế  |
| buyerIdNo | Required: false DataType: String Minlength:  Maxlength: 100 Format: | Số giấy tờ của người mua  |
| reservationCode | Required: true DataType: String Minlength:  Maxlength: 100 Format: | Mã số bí mật  |
| fileType | Required: true DataType: String Minlength:  Maxlength: 100 Format:  | Loại file: zip  |
| strIssueDate | Required: true DataType: milisecond since epoch Minlength:  Maxlength:  Format: Tiêu chuẩn 5.1 | Ngày phát hành hóa đơn  |
| startDate | Required : false DataType: Date Minlength :  Maxlength : 50 Format : | Ngày lập từ ngày Định dạng "2019-05-12"  |
| endDate | Required : false DataType: Date Minlength :  Maxlength : 50 Format : | Ngày lập đến ngày Định dạng "2019-05-12" Lưu ý: Khoảng thời gian lập tối đa 3 tháng (endDate – startDate) \<= 3 tháng |

  VD:

  ![][image26]


  **Đầu ra:**

Đối tượng Response mô tả trạng thái lỗi Webservice trả về và đối tượng dữ liệu Webservice trả về:

- Ví dụ: kết quả trả về với dạng FormParam

![][image27]

**Mô tả**

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null nếu lấy hóa đơn thành công) |
| description | Mô tả lỗi (giá trị là null nếu lấy hóa đơn thành công) |
| fileToBytes | Mảng bytes file hóa đơn, chuyển mảng bytes này ra file sẽ được file chứa các thông tin của hóa đơn, Vị dụ file .zip bao gồm file .xml, .xsl, ảnh logo, watermark, qrcode Code chuyển ra file Java **FileUtils.writeByteArrayToFile(newFile("D:/viettel/fileName.zip"), output.getFileToBytes());** |
| paymentStatus | Trạng thái thanh toán  |
| fileName | Tên file |

   

5.  **Lấy file hóa đơn chuyển đổi (pdf)**

Cho phép hệ thống tích hợp lấy file hóa đơn chuyển đổi của hóa đơn điện tử. Trong trường hợp hóa đơn đã được chuyển đổi trước đó, SInvoice sẽ cho tải lại file cũ mà không tạo ra file mới (Điều kiện phải cùng exchangeUser như lần chuyển đổi đầu tiên)

**Lưu ý:** 

+ Hệ thống hóa đơn điện tử chạy theo cơ chế bất đồng bộ, vì vậy hệ thống đẩy hóa đơn lên cơ sở dữ liệu sau khi nhận request phát hành hóa đơn khoảng 1s. Vì vậy, khi tích hợp, request lấy file hóa đơn nên được thực hiện sau từ 2-5 giây sau khi phát hành hóa đơn.

+ Hệ thống chỉ lấy lên những hóa đơn có trạng thái khả dụng (state \= 1).

* **Đầu vào:**

- Action (POST): *InvoiceAPI/InvoiceWS/createExchangeInvoiceFile*

- Headers:

\+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

\+ Content-Type : application/x-www-form-urlencoded

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required : true DataType: String Minlength :  Maxlength : 20 Format : \[0-9-\]+ | Mã số thuế bên bán Mã mẫu hóa đơn, tuân thủ theo quy định ký hiệu mẫu hóa đơn của Thông tư hướng dẫn thi hành nghị định số 51/2010/NĐ-CP  |
| invoiceNo | Required : true DataType: String Minlength : 7 Maxlength : 35 Format :  \[a-zA-Z0-9\]\*$ | Là ký hiệu hóa đơn \+ số hóa đơn vd : AA/20E0000001  |
| strIssueDate | Required : true DataType: milisecond Minlength :  Maxlength :  Format: Tiêu chuẩn 5.1 | Ngày phát hành hóa đơn  |
| exchangeUser | Required : true DataType: String Minlength :  Maxlength : 100 | Tên người chuyển đổi (Cần thực hiện encode giá trị: Tham khảo: [https://www.urlencoder.org/](https://www.urlencoder.org/))  |
| startDate | Required : false DataType: Date Minlength :  Maxlength : 50 Format : | Ngày lập từ ngày Định dạng "2019-05-12"  |
| endDate | Required : false DataType: Date Minlength :  Maxlength : 50 Format : | Ngày lập đến ngày Định dạng "2019-05-12" Lưu ý: Khoảng thời gian lập tối đa 3 tháng (endDate – startDate) \<= 3 tháng |

- Data: định dạng FormParam của các tham số truyền vào.

![][image28]

* **Đầu ra:**

Đối tượng Response mô tả trạng thái lỗi Webservice trả về và đối tượng dữ liệu Webservice trả về:

**Mô tả**

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null nếu lấy hóa đơn thành công) |
| description | Mô tả lỗi (giá trị là null nếu lấy hóa đơn thành công) |
| fileToBytes | Mảng bytes file hóa đơn, chuyển mảng bytes này ra file sẽ được file pdf hóa đơn chuyển đổi  Code chuyển ra file Java **FileUtils.writeByteArrayToFile(newFile("D:/viettel/fileName.pdf"), output.getFileToBytes());** |
| fileName | Tên của file hóa đơn |

Hình ảnh Response trả về

![][image29]

6. **Tra cứu hóa đơn**

Trường hợp doanh nghiệp có trang webportal để tra cứu hóa đơn thì có thể kết nối đến webservice Hóa đơn điện tử của Viettel để tra cứu hóa đơn theo các điều kiện.

Vị dụ khách hàng của doanh nghiệp có thể tra cứu được các hóa đơn của mình theo khoảng thời gian. 

* **Đầu vào:**

- Action (POST): InvoiceAPI/InvoiceUtilsWS/getInvoices/{supplierTaxCode}

- Headers:

\+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

\+ Content-Type : application/json 

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required : false DataType: String Minlength :  Maxlength : 20 Format : \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 |
| GetInvoiceInput | Object | Đối tượng gồm các trường dữ liệu tham số |

- Data: JSON

  * Các tham số của đối tượng GetInvoiceInput

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | :---- | ----- |
| invoiceNo | Required : false DataType: String Minlength : 7 Maxlength : 35 Format :  \[a-zA-Z0-9\]\*$ | Là ký hiệu hóa đơn \+ số hóa đơn vd : AA/20E0000001  |
| startDate | Required : true DataType: Date Minlength :  Maxlength : 50 Format : | Ngày lập từ ngày Định dạng "2019-05-12"  |
| endDate | Required : true DataType: Date Minlength :  Maxlength : 50 Format : | Ngày lập đến ngày Định dạng "2019-05-12"  |
| invoiceType | Required : false DataType: String Minlength :  Maxlength :  Format :  | Loại hóa đơn, là một trong các giá trị Thông tư 32: 01GTKT, 02GTTT, 03XKNB,  04HGDL, 07KPTQ Thông tư 78: 1, 2, 3, 4, 5, 6 |
| rowPerPage | Required : true DataType: Number Min : 1 Max:  | Số dòng trên một trang  |
| pageNum | Required : true DataType: Number Min : 0 Max | Chỉ số trang |
| buyerTaxCode | Required : false DataType: String Minlength :  Maxlength : 20 | Mã số thuế của khách hàng  |
| buyerIdNo | Required : false DataType: String | Số giấy tờ của khách hang  |
| templateCode | Required : false DataType: String Minlength :  Maxlength :  | Mã mẫu hóa đơn.  |
| invoiceSeri | Required : false DataType: String Minlength :  Maxlength : 25 Format : \[a-zA-Z0-9\]\*$ | Ký hiệu hóa đơn  |
| getAll | Required : false DataType: Boolean Minlength:  Maxlength:  Format : true/false | Cho phép tra cứu thông tin hóa đơn của toàn doanh nghiệp đối với user của công ty mẹ. Các giá trị là true/false |
| issueStartDate | Required: false DataType: Date Minlength:  Maxlength: 50 Format: | Ngày phát hành từ ngày Định dạng "2019-05-12"  |
| issueEndDate | Required: false DataType: Date Minlength:  Maxlength: 50 Format: | Ngày phát hành đến ngày Định dạng "2019-05-12"  |
| adjustmentType | Required: false DataType: String Minlength:  Maxlength: 1 Format: | Trạng thái điều chỉnh hóa đơn:  1: Hóa đơn gốc (hóa đơn đã phát hành, hóa đơn bị điều chỉnh, hóa đơn bị thay thế) 3: Hóa đơn thay thế  5: Hóa đơn điều chỉnh thông tin 7: Hóa đơn xóa bỏ 9: Hóa đơn điều chỉnh tiền Không truyền sẽ trả tất cả |

Vị dụ gửi dữ liệu với JSON:  
{  
  "startDate" : "2020-05-12" ,  
  "endDate" : "2020-05-12",  
  "invoiceType" : "02GTTT",  
  "rowPerPage" : 20,  
  "pageNum" : 1,  
  "templateCode" : null  
}

* **Đầu ra:**

  {

      "errorCode": null,

      "description": null,

      "totalRow": 286,

      "invoices": \[

          {

              "invoiceId": 213469,

              "invoiceType": "02GTTT",

              "adjustmentType": "1",

              "templateCode": "02GTTT0/089",

              "invoiceSeri": "QT/17E",

              "invoiceNumber": "0000003",

              "invoiceNo": "QT/17E0000003",

              "currency": "VND",

              "total": 3800000,

              "issueDate": 1587797116843,

              "issueDateStr": null,

              "state": null,

              "requestDate": null,

              "description": null,

              "buyerIdNo": null,

              "stateCode": null,

              "subscriberNumber": null,

              "paymentStatus": 1,

              "viewStatus": 1,

              "downloadStatus": null,

              "exchangeStatus": null,

              "numOfExchange": null,

              "createTime": 1587797116843,

              "contractId": null,

              "contractNo": null,

              "supplierTaxCode": "0100109106",

              "buyerTaxCode": "6200000230",

              "totalBeforeTax": 3800000,

              "taxAmount": 0,

              "taxRate": null,

              "paymentMethod": null,

              "paymentTime": null,

              "customerId": null,

              "buyerName": "Trần Trung Dũng",

              "no": null,

              "paymentStatusName": null

               "originalInvoiceId": "K22THY32"

          }

  }

  Đối tượng Response với HTTPStatus và output  Entity.

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null lấy hóa đơn thành công) |
| description | Mô tả lỗi (giá trị là null lấy hóa đơn thành công) |
| List\<InvoiceBean\> | Danh sách các bản ghi hóa đơn thỏa mãn điều kiện   |

  7.  **Lấy thông tin trường động**

Với mỗi mẫu hóa đơn, có thể có những thông tin trường động khác nhau (các trường thông tin ngoài các trường tĩnh được mô tả ở mục 6). SInvoice cho phép các hệ thống tích hợp có thể lấy thông tin trường động của một mẫu hóa đơn cụ thể mà khách hàng sử dụng.

* **Đầu vào:**

- Action (GET): [/InvoiceAPI/InvoiceWS/getCustomFields?taxCode=\&templateCode](https://10.60.108.210:8273/InvoiceAPI/InvoiceWS/getCustomFields?taxCode=&templateCode)\=

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

  Vị dụ : [/InvoiceAPI/InvoiceWS/getCustomFields?taxCode=0100109106\&templateCode=01GTKT0%2f001](https://10.60.108.210:8273/InvoiceAPI/InvoiceWS/getCustomFields?taxCode=0100109106&templateCode=01GTKT0%2f085)

- Data: dữ liệu truyền vào dạng Query Param gồm các tham số:

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| taxCode | Required : true DataType: String Minlength :  Maxlength : 20 Format : \[0-9-\]+ | Mã số thuế |
| templateCode | Required : false DataType: String Minlength :  Maxlength : 20 Format : \[a-zA-Z0-9/\]+ | Mã mẫu hóa đơn, tuân thủ theo quy định ký hiệu mẫu hóa đơn của Thông tư hướng dẫn thi hành nghị định số 51/2010/NĐ-CP **Chú ý: *Mẫu hóa đơn có ít nhất 1 thông báo phát hành ở trạng thái dự thảo mới có thể lấy danh sách trường động qua API*** |

* **Đầu ra:**

Đối tượng Response là danh sách trường động tương ứng với mẫu hóa đơn của doanh nghiệp:

* **Vị dụ:**

  ![][image30]

  Kết quả:

"errorCode": null,  
    "description": null,  
    "customFields": \[  
        {  
            "id": null,  
            "invoiceTemplatePrototypeId": 2503,  
            "keyTag": "commandDes",  
            "valueType": "text",  
            "keyLabel": "về việc",  
            "isRequired": false,  
            "isSeller": false  
        },  
        {  
            "id": null,  
            "invoiceTemplatePrototypeId": 2503,  
            "keyTag": "contractNo",  
            "valueType": "text",  
            "keyLabel": "Hợp đồng số",  
            "isRequired": false,  
            "isSeller": false  
        },  
        {  
            "id": null,  
            "invoiceTemplatePrototypeId": 2503,  
            "keyTag": "vehicle",  
            "valueType": "text",  
            "keyLabel": "Phương tiện vận chuyển",  
            "isRequired": false,  
            "isSeller": false  
        },  
        {  
            "id": null,  
            "invoiceTemplatePrototypeId": 2503,  
            "keyTag": "exportAt",  
            "valueType": "text",  
            "keyLabel": "Xuất tại kho",  
            "isRequired": false,  
            "isSeller": false  
        },  
        {  
            "id": null,  
            "invoiceTemplatePrototypeId": 2503,  
            "keyTag": "exportAtNo",  
            "valueType": "text",  
            "keyLabel": "Mã kho",  
            "isRequired": false,  
            "isSeller": false  
        },  
        {  
            "id": null,  
            "invoiceTemplatePrototypeId": 2503,  
            "keyTag": "importAt",  
            "valueType": "text",  
            "keyLabel": "Nhập tại kho",  
            "isRequired": false,  
            "isSeller": false  
        },  
        {  
            "id": null,  
            "invoiceTemplatePrototypeId": 2503,  
            "keyTag": "importAtNo",  
            "valueType": "text",  
            "keyLabel": "Mã kho",  
            "isRequired": false,  
            "isSeller": false  
        },  
        {  
            "id": null,  
            "invoiceTemplatePrototypeId": 2503,  
            "keyTag": "vehicleNo",  
            "valueType": "text",  
            "keyLabel": "Số xe",  
            "isRequired": false,  
            "isSeller": false  
        },  
        {  
            "id": null,  
            "invoiceTemplatePrototypeId": 2503,  
            "keyTag": "economicContractNo",  
            "valueType": "text",  
            "keyLabel": "Căn cứ hợp đồng kinh tế số",  
            "isRequired": false,  
            "isSeller": false  
        },  
        {  
            "id": null,  
            "invoiceTemplatePrototypeId": 2503,  
            "keyTag": "commandDate",  
            "valueType": "date",  
            "keyLabel": "Ngày điều động",  
            "isRequired": false,  
            "isSeller": false  
        },  
        {  
            "id": null,  
            "invoiceTemplatePrototypeId": 2503,  
            "keyTag": "commandOf",  
            "valueType": "text",  
            "keyLabel": "của",  
            "isRequired": false,  
            "isSeller": false  
        }  
    \]  
}

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| id | DataType: Number | ID của trường động |
| keyLabel | DataType: String | Tên hiển thị của trường động,  Hiển thị trên giao diện nhập liệu khi lập hóa đơn |
| keyTag | DataType: String | Tên của trường động khi lưu vào dữ liệu |
| valueType | DataType: String  | Kiểu dữ liệu của trường động. Chỉ bao gồm các giá trị: “text”,  “date”, “number” |
| isRequired | DataType: Boolean | Trường có bắt buộc hay không |
| isSeller | DataType: Boolean | isSeller \= true: Trường dữ liệu thuộc bên bán isSeller \= false: Trường dữ liệu thuộc bên mua |

**Gửi dữ liệu lập hóa đơn với trường động:** Thêm vào mảng metadata, mỗi phần tử bao gồm các giá trị được mapping dựa vào customFields nhận từ response như sau

| Trường trong(customFields) | Tên trường(metadata) | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- | ----- |
| id | invoiceCustomFieldId | Required : false DataType: Number Minlength :  Maxlength : 10 Format :  | ID của trường động  |
| keyTag | keyTag | Required : true DataType: String | Tên của trường động khi lưu vào dữ liệu |
| valueType | valueType | Required : true DataType: String  | Kiểu dữ liệu của trường động. Chỉ bao gồm các giá trị: “text”,  “date”, “number” |
| keyLabel | keyLabel | Required : true DataType: String  | Tên hiển thị của trường động,  Hiển thị trên giao diện nhập liệu khi lập hóa đơn |
| valueType \= date | dateValue | Required : false DataType: Date | Giá trị của trường dữ liệu trong trường hợp valueType \= date |
| valueType \= number | numberValue | Required : false DataType: Number | Giá trị của trường dữ liệu trong trường hợp valueType \= number |
| valueType \= text | stringValue | Required : false DataType: String | Giá trị của trường dữ liệu trong trường hợp valueType \= text |

{  
   "generalInvoiceInfo": {  
      "invoiceType": "03XKNB",  
      "templateCode": "03XKNB0/003",  
      "invoiceSeries": "AA/20E",  
      "currencyCode": "VND",  
      "adjustmentType": "1",  
      "paymentStatus": true,  
      "cusGetInvoiceRight": true  
   },  
   "sellerInfo": {  
      "sellerLegalName": "Người bán hàng",  
      "sellerTaxCode": "0100109106-712",  
      "sellerAddressLine": "Thành Phố Hà Nội \- Việt Nam",  
      "sellerPhoneNumber": "0123456789",  
      "sellerFaxNumber": "0123456789",  
      "sellerEmail": "email@gmail.com",  
      "sellerBankName": "Ngân hàng ",  
      "sellerBankAccount": "012345678901",  
      "sellerDistrictName": "",  
      "sellerCityName": "Thành Phố Hà Nội",  
      "sellerCountryCode": "84",  
      "sellerWebsite": "sinvoice.viettel.vn"  
   },  
   "buyerInfo": {  
      "buyerName": "Tên khách hàng",  
      "buyerLegalName": "Tên đơn vị",  
      "buyerTaxCode": "0100109106",  
      "buyerAddressLine": "An Khánh Hoài Đức Hà Nội",  
      "buyerDistrictName": "Số 9, đường 11, VSIP Bắc Ninh, Thị xã Từ Sơn, Tỉnh",  
      "buyerCityName": "Thành Phố Hà Nội",  
      "buyerCountryCode": "84",  
      "buyerPhoneNumber": "987999999",  
      "buyerFaxNumber": "0458954",  
      "buyerEmail": "abc@gmail.com",  
      "buyerBankName": "Ngân hàng Quân đội MB",  
      "buyerBankAccount": "01578987871236547",  
      "buyerIdType": "3",  
      "buyerIdNo": "8888899999",  
      "buyerCode": "832472343b\_b",  
      "buyerBirthDay": ""  
   },  
   "payments": \[  
      {  
         "paymentMethodName": "Truyền trực tiếp giá trị mong muốn vào đây"  
      }  
   \],  
     "taxBreakdowns": \[  
    {  
      "taxPercentage": \-1,  
      "taxableAmount": 27286150,  
      "taxAmount": 0  
    }  
  \],  
  "itemInfo": \[  
    {  
      "lineNumber": 1,  
      "itemCode": "HH0001",  
      "itemName": "Hàng hóa 01",  
      "unitCode": null,  
      "unitName": "Chiếc",  
      "unitPrice": 150450,  
      "quantity": 100,  
      "selection": 1,  
      "itemTotalAmountWithoutTax": 15045000,  
      "taxPercentage": \-1,  
      "taxAmount": 0,  
      "discount": null,  
      "discount2": null,  
      "itemDiscount": 0,  
      "itemNote": null,  
      "batchNo": null,  
      "expDate": null,  
      "isIncreaseItem": null  
    },  
    {  
      "lineNumber": 2,  
      "itemCode": "HH00002",  
      "itemName": "Hàng hóa 02",  
      "unitCode": null,  
      "unitName": "Cái",  
      "unitPrice": 244823,  
      "quantity": 50,  
      "selection": 1,  
      "itemTotalAmountWithoutTax": 12241150,  
      "taxPercentage": \-1,  
      "taxAmount": 0,  
      "discount": null,  
      "discount2": null,  
      "itemDiscount": 0,  
      "itemNote": null,  
      "batchNo": null,  
      "expDate": null,  
      "isIncreaseItem": null  
    }  
  \],  
  "metadata": \[  
  {  
    "keyTag": "commandDes",  
    "keyLabel": "về việc",  
    "dateValue": null,  
    "stringValue": "điều chuyển nội bộ",  
    "numberValue": null,  
    "valueType": "text",  
    "isRequired": false,  
    "isSeller": false,  
    "required": false  
  },  
  {  
    "keyTag": "contractNo",  
    "keyLabel": "Hợp đồng số",  
    "dateValue": null,  
    "stringValue": "Hợp đồng số",  
    "numberValue": null,  
    "valueType": "text",  
    "isRequired": false,  
    "isSeller": false,  
    "required": false  
  },  
  {  
    "keyTag": "vehicle",  
    "keyLabel": "Phương tiện vận chuyển",  
    "dateValue": null,  
    "stringValue": "xe tải",  
    "numberValue": null,  
    "valueType": "text",  
    "isRequired": false,  
    "isSeller": false,  
    "required": false  
  },  
  {  
    "keyTag": "exportAt",  
    "keyLabel": "Xuất tại kho",  
    "dateValue": null,  
    "stringValue": "Kho 1",  
    "numberValue": null,  
    "valueType": "text",  
    "isRequired": false,  
    "isSeller": false,  
    "required": false  
  },  
  {  
    "keyTag": "importAtNo",  
    "keyLabel": "Mã kho",  
    "dateValue": null,  
    "stringValue": "KH2",  
    "numberValue": null,  
    "valueType": "text",  
    "isRequired": false,  
    "isSeller": false,  
    "required": false  
  },  
  {  
    "keyTag": "importAt",  
    "keyLabel": "Nhập tại kho",  
    "dateValue": null,  
    "stringValue": "Kho 2",  
    "numberValue": null,  
    "valueType": "text",  
    "isRequired": false,  
    "isSeller": false,  
    "required": false  
  },  
  {  
    "keyTag": "importAtNo",  
    "keyLabel": "Mã kho",  
    "dateValue": null,  
    "stringValue": "KH0",  
    "numberValue": null,  
    "valueType": "text",  
    "isRequired": false,  
    "isSeller": false,  
    "required": false  
  },  
  {  
    "keyTag": "vehicleNo",  
    "keyLabel": "Số xe",  
    "dateValue": null,  
    "stringValue": "1524-jhh",  
    "numberValue": null,  
    "valueType": "text",  
    "isRequired": false,  
    "isSeller": false,  
    "required": false  
  },  
  {  
    "keyTag": "economicContractNo",  
    "keyLabel": "Căn cứ hợp đồng kinh tế số",  
    "dateValue": null,  
    "stringValue": "123456",  
    "numberValue": null,  
    "valueType": "text",  
    "isRequired": false,  
    "isSeller": false,  
    "required": false  
  },  
  {  
    "keyTag": "commandDate",  
    "keyLabel": "Ngày điều động",  
    "dateValue": "1605752798000",  
    "stringValue": null,  
    "numberValue": null,  
    "valueType": "date",  
    "isRequired": false,  
    "isSeller": false,  
    "required": false  
  },  
  {  
    "keyTag": "commandOf",  
    "keyLabel": "của",  
    "dateValue": null,  
    "stringValue": "Công ty ABC",  
    "numberValue": null,  
    "valueType": "text",  
    "isRequired": false,  
    "isSeller": false,  
    "required": false  
  }  
\]  
}

8.  **Lập hóa đơn nháp**

* **Đầu vào:**

Webservice dùng để lưu dữ liệu hóa đơn nháp lên hệ thống SInvoice. Các hóa đơn nháp này không có số hóa đơn hay kí số, chỉ có thể xem/phát hành trên website của SInvoice. Khi phát hành thì các số hóa đơn sẽ không được cập nhật lại phần mềm tích hợp.

- Action (POST): InvoiceAPI/InvoiceWS/createOrUpdateInvoiceDraft/{supplierTaxCode}

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web hoặc Authorization: username/pass như đăng nhập trên web

  \+ Content-Type : application/json 

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required: true DataType: String Minlength:  Maxlength: 20 Format: \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 |

- Data: Định dạng JSON

- Thông số dữ liệu truyền vào tương tự phần Lập hóa đơn. Tham khảo json tại phần 6.2

**Lưu ý:**

Trong trường hợp lập hóa đơn điều chỉnh/thay thế cho hóa đơn giấy thì bổ sung thêm trong generalInvoiceInfo hai thẻ như sau: 

| Tên trường | Kiểu dữ liệu | Mô tả |
| :---- | :---- | :---- |
| originalInvoiceType | Required: false DataType: String Minlength: N/A Maxlength:  Format: | Loại hóa đơn gốc Truyền giá trị số với ý nghĩa như sau  0- Không phải hóa đơn giấy/hóa đơn không tồn tại trên hệ thống  1-Hóa đơn TT78  2-Hóa đơn theo QĐ 1209  3-Hóa đơn điện tử/giấy TT32 4-Hóa đơn giấy TT 78 |
| originalTemplateCode | Required:  DataType: String Minlength: N/A Maxlength: 20 Format: | Bắt buộc truyền nếu originalInvoiceType là 1, 2, 3 hoặc 4 Ví dụ mẫu TT32: 01GTKT0/001 Ví dụ mẫu TT78: 1/0224 |

Khi lập hóa đơn, hệ thống **không kiểm tra tính tồn tại** của hóa đơn gốc trên hệ thống, các quy tắc xác thực khác giữ nguyên hiện trạng

* **Đầu ra:**

Đối tượng Response mô tả trạng thái lỗi Webservice trả về và đối tượng dữ liệu Webservice trả về:

* Dữ liệu về thông tin về hóa đơn nháp lập thành công

  **{**

    "errorCode": ""**,**

    "description": ""**,**

    "result": **{**    

    **}**

  **}**

Mô tả

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null nếu lập hóa đơn thành công) |
| description | Mô tả lỗi (giá trị là null nếu lập hóa đơn thành công) |

**Lưu ý:**

Nếu người dùng truyền giá trị 0 hoặc “0” cho tham số validation trong phần generalInvoiceInfo thì các thông tin được truyền trong phần itemInfo, taxBreakdowns, summarizeInfo sẽ được giữ nguyên mà không thực hiện kiểm tra ràng buộc và tính toán lại.

9. **Hủy hóa đơn**

Cho phép xóa bỏ hóa đơn (chuyển hóa đơn sang trạng thái xóa bỏ) từ hệ thống tích hợp.

* **Đầu vào:**

- Action (POST): InvoiceAPI/InvoiceWS/cancelTransactionInvoice

- Headers:

\+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

\+ Content-Type : application/x-www-form-urlencoded

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required : true DataType: String Minlength :  Maxlength : 20 Format : \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001  |
| templateCode | Required : false DataType: String Minlength :  Maxlength : 20 Format :  | Mã mẫu hóa đơn VD:  01GTKT0/001 1/001 |
| invoiceNo | Required : true DataType: String Minlength : 7 Maxlength : 35 Format :  \[a-zA-Z0-9/\]+ | Là số hóa đơn \= ký hiệu hóa đơn \+ số hóa đơn.  vd : AA/20E0000001  |
| strIssueDate | Required : true DataType: milisecond since epoch Minlength :  Maxlength :  Format: Tiêu chuẩn 5.1 | Ngày phát hành hóa đơn  (không vượt quá ngày hiện tại)  |
| additionalReferenceDesc | Required : true DataType: String Minlength : 1 Maxlength : 400 | Tên văn bản thỏa thuận hủy hóa đơn  |
| additionalReferenceDate | Required : true DataType: milisecond since epoch Minlength :  Maxlength : Format: Tiêu chuẩn 5.1 | Ngày thỏa thuận (không vượt quá ngày hiện tại)  |
| reasonDelete | Required: False DataType: String Minlength: N/A Maxlength: 255 Format: | Lý do hủy hóa đơn  Cho phép nhập tối đa 255 ký tự |

Form Data Vị dụ:

* **Đầu ra:**

![][image31]

Đối tượng Response mô tả trạng thái lỗi Webservice trả về và đối tượng dữ liệu Webservice trả về:

Vị dụ trả về thành công:

{  
    "errorCode": null,  
    "description": "CANCEL TRANSACTION INVOICE SUCCESS"  
}

* Bảng mã lỗi :

  Mô tả

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null nếu lấy hóa đơn thành công) |
| description | Mô tả lỗi (giá trị là null nếu lấy hóa đơn thành công), Kiểm tra hóa đơn có phải là các hóa đơn gốc, chưa kê khai thuế, trạng thái đã thanh toán, không phải hóa đơn điều chỉnh, hóa đơn thay thế và hóa đơn điều chỉnh hủy hay không? Nếu phải trả lại thông tin hóa đơn không hợp lệ |

  10. **Cập nhật kê khai thuế**

Cho phép hệ thống tích hợp gửi thông tin cập nhật kê khai thuế sang, để tránh cho khách hàng bị sai sót trong quá trình sử dụng (hóa đơn đã kê khai thực tế vẫn có thể xóa bỏ, thay thế).

* **Đầu vào:**

- Action (POST):  *InvoiceAPI/InvoiceUtilsWS/updateTaxDeclaration/*

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

  \+ Content-Type: application/json

  Các tham số:

| Tên trường | Kiểu dữ liệu, ràng buộc | Dữ liệu/mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required: true DataType: String Minlength:  Maxlength: 20 Format: \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 |
| strIssueDate | Required: true DataType: String Minlength:  Maxlength:  Format: dd/mm/yyyy | Ngày lập hóa đơn   |


- Vị dụ với định dạng json:

  **{**

		**"supplierTaxCode":"0100109106",**

		**"strIssueDate":"14/03/2018"**

		**}**

* **Đầu ra:**

  Hình ảnh Response trả về thành công

![][image32]

11. **Cung cấp tình hình sử dụng hóa đơn theo dải**

Trả về thông tin chi tiết số lượng hóa đơn đã dùng, số lượng còn lại của một dải hóa đơn để từ đó đối tác tích hợp có thể chủ động cảnh báo khách hàng trong trường hợp không đủ hóa đơn.

* **Đầu vào:**

- Action (POST): [/InvoiceAPI/](https://10.60.108.210:8273/InvoiceAPI/InvoiceWS/createBatchInvoice/0100109106)InvoiceUtilsWS/getProvidesStatusUsingInvoice

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

  \+ Content-Type : application/json 

Các tham số của đối tượng CommonDataInput

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required : true DataType: String Minlength :  Maxlength : 20 Format : \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 |
| templateCode | Required : true DataType: String Minlength :  Maxlength : 20 Format :  | Mã mẫu hóa đơn Mã mẫu hóa đơn, tuân thủ theo quy định ký hiệu mẫu hóa đơn của Thông tư hướng dẫn thi hành nghị định số 51/2010/NĐ-CP *Chi tiết xem PL1 Thông tư 39/2014/TT-BTC* |
| serial | Required : true DataType: String Minlength :  Maxlength : 7 Format : \[a-zA-Z0-9\]\*$ | Seri hóa đơn  |

Vị dụ mẫu và các trường dữ liệu:

- JSON:

  {

  	"supplierTaxCode":"0100109106-712",

  	"templateCode":"01GTKT0/003",

  	"serial":"AA/20E"

  }

* **Đầu ra:**

  Đối tượng Response với HTTPStatus và output  Entity.

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null không có lỗi gì xảy ra) |
| description | Mô tả lỗi (giá trị là null không có lỗi gì xảy ra) |
| statuss | Trạng thái (giá trị là 200 lấy thông tin sử dụng hóa đơn thành công) |
| numOfpublishInv | Tổng số hóa đơn đã phát hành |
| totalInv | Tổng số hóa đơn có thể lập với mẫu hóa đơn \+ dải truyển vào |


  12. **Lập hóa đơn theo lô**

**\*Quy tắc kiểm tra ngày lập hóa đơn:**

Hệ thống Hóa đơn điện tử SInvoice V2, phần Cấu hình chung liên quan ngày lập hóa đơn có 2 checkbox: Cho phép ngày lập hóa đơn khác ngày hiện tại, Tự động đặt giá trị cho ngày lập hóa đơn bằng ngày lập gần nhất.

Khi phát hành hóa đơn qua API, ngày lập hóa đơn sẽ bị ảnh hưởng khi người dùng tích chọn các checkbox này, xảy ra 4 trường hợp như mô tả sau:

**TH1: Không tick cả 2**

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: ngày lập không hợp lệ

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại: ngày lập không hợp lệ

\- Ngày lập \> ngày hiện tại: lấy ngày truyền vào (không kiểm tra giờ)

**TH2: Tick “Cấu hình ngày ký là thời điểm hiện tại”**

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: lấy ngày của hóa đơn đã lập gần nhất 

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại: lấy ngày truyền vào 

\- Ngày lập \> ngày hiện tại: ngày lập không hợp lệ

**TH3: Tick “Tự động đặt giá trị cho ngày lập hóa đơn bằng ngày lập gần nhất”**

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: ngày lập không hợp lệ

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại: lấy ngày truyền vào 

\- Ngày lập \> ngày hiện tại: ngày lập không hợp lệ

**TH4: Tích cả 2** 

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: lấy ngày của hóa đơn đã lập gần nhất 

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại:  lấy ngày truyền vào 

\- Ngày lập \> ngày hiện tại: ngày lập không hợp lệ 

\- Trường hợp khách hàng muốn lập hóa đơn theo lô sẽ sử dụng hàm sau. Lưu ý chỉ sử dụng cho loại chứng thư số server (HSM)

**Lưu ý:** 

- Hệ thống đang cho phép tối đa 50 hóa đơn/1 lô do thời gian xử lý đơn lẻ từng hóa đơn lâu, nếu như để lô nhiều quá có thể bị timeout. Trong trường hợp dữ liệu từ hệ thống tích hợp nhiều hơn, có thể tự động chia nhỏ số lượng hóa đơn và gửi sang.

- Chỉ lập các hóa đơn gốc theo lô

- Nếu là lập hóa đơn máy tính tiền thì respond trả về có cả thông tin Mã CQT cấp: "codeOfTax", nếu không phải hóa đơn máy tính tiền thì trả về “codeOfTax” \= null

- Nếu cấu hình Không ký hóa đơn có mã khởi tạo từ máy tính tiền và hóa đơn thuộc loại máy tính tiền thì cho phép doanh nghiệp dùng chữ ký USB Token và CloudCA lập hóa đơn theo lô bằng API Server.

- Nếu người dùng truyền giá trị 0 hoặc “0” cho tham số validation trong phần generalInvoiceInfo thì các thông tin được truyền trong phần itemInfo, taxBreakdowns, summarizeInfo sẽ được giữ nguyên mà không thực hiện kiểm tra ràng buộc và tính toán lại.

* **Đầu vào:**

- Action (POST): InvoiceAPI/InvoiceWS/createBatchInvoice/{supplierTaxCode}

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web hoặc Authorization: username/pass như đăng nhập trên web

  \+ Content-Type : application/json 

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required: true DataType: String Minlength:  Maxlength: 20 Format: \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 |

- Data: Dữ liệu mẫu lập hóa đơn theo lô

|  | JSON |
| :---- | :---- |
| Lập hóa đơn theo lô | ![][image33] |

Kết quả khi lập hóa đơn theo lô thành công sẽ trả kết quả về theo transactionUuid để xác định được hóa đơn nào thành công, sinh ra số hóa đơn nào.

* **Đầu ra:**

| Tên trường | Mô tả |
| ----- | ----- |
| createInvoiceOutputs | Kết quả trả về khi hóa đơn được lập thành công ( trả số hóa đơn ) |
| lstMapError | Mô tả lỗi (các lỗi gặp phải của ds hóa đơn) |
| totalSuccess | Tổng số dòng tạo hóa đơn thành công |
| totalFail | Tổng số hóa đơn bị lỗi chưa phát hành thành công |

Ví dụ về kết quả trả về:

![][image34]

Lỗi về sai, thiếu  thông tin 

![][image35]

Các lỗi về định dạng json và token sẽ trả về theo định dạng

![][image36]

13. **Cung cấp danh sách hóa đơn theo khoảng thời gian**

Trả về chi tiết thông tin các hóa đơn để có thể đối soát xem sai đúng của hóa đơn trong một khoảng thời gian.

* **Đầu vào:**

- Action (POST): [/InvoiceAPI/](https://10.60.108.210:8273/InvoiceAPI/InvoiceWS/createBatchInvoice/0100109106)InvoiceUtilsWS/getListInvoiceDataControl

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

  \+ Content-Type : application/json

Các tham số của đối tượng CommonDataInput

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required : true DataType: String Minlength :  Maxlength : 20 Format : \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001   |
| fromDate | Required : true DataType: String Format : dd/MM/yyyy | Ngày bắt đầu muốn tìm kiếm   |
| toDate | Required : true DataType: String Format : dd/MM/yyyy | Ngày kết thúc muốn tìm kiếm  |
| originalInvoiceID | DataType: String  | Là ký hiệu hóa đơn \+ số hóa đơn vd : AA/20E0000001 Chỉ lấy khi hoá đơn có adjustmentType: 3: Hóa đơn thay thế        5: Hóa đơn điều chỉnh  |
| adjustmentType | Required: false DataType: String Minlength:  Maxlength: 1 Format: | Trạng thái điều chỉnh hóa đơn:  1: Hóa đơn gốc (hóa đơn đã phát hành, hóa đơn bị điều chỉnh, hóa đơn bị thay thế) 3: Hóa đơn thay thế  5: Hóa đơn điều chỉnh thông tin 7: Hóa đơn xóa bỏ 9: Hóa đơn điều chỉnh tiền Không truyền sẽ trả tất cả |

Vị dụ mẫu và các trường dữ liệu:

- JSON:

  {	"supplierTaxCode":"0100109106",

  	"fromDate":"10/03/2018",

  	"toDate":"16/03/2018"

         "adjustmentType":3

  }

* **Đầu ra:**

  Đối tượng Response với HTTPStatus và output  Entity.

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null không có lỗi gì xảy ra) |
| description | Mô tả lỗi (giá trị là null không có lỗi gì xảy ra) |
| lstInvoiceBO | Danh sách hóa đơn được tạo theo thời gian được truyền vào |

**Lưu ý** adjustmentTyp của hóa đơn trả về :

| Tên trường | Mô tả |
| ----- | ----- |
| adjustmentType | Loại hóa đơn:  1: Hóa đơn gốc  3: Hóa đơn thay thế  5: Hóa đơn điều chỉnh thông tin 7: Hóa đơn xóa bỏ 9: Hóa đơn điều chỉnh tiền |

{  
    "errorCode": null,  
    "description": null,  
    "totalRows": 8162,  
    "invoices": \[  
        {  
            "invoiceId": 16376495,  
            "invoiceType": "1",  
            "adjustmentType": "1",  
            "templateCode": "1/011",  
            "invoiceSeri": "K22TXK",  
            "invoiceNumber": "0037294",  
            "invoiceNo": "K22TXK37294",  
            "currency": "VND",  
            "total": 13627273.000000000,  
            "issueDate": 1663204962000,  
            "issueDateStr": null,  
            "state": 1,  
            "requestDate": null,  
            "description": null,  
            "buyerIdNo": "",  
            "stateCode": 1,  
            "subscriberNumber": null,  
            "paymentStatus": 1,  
            "viewStatus": null,  
            "downloadStatus": null,  
            "exchangeStatus": 0,  
            "numOfExchange": null,  
            "createTime": 1663204962000,  
            "contractId": null,  
            "contractNo": null,  
            "supplierTaxCode": "0100109106-509",  
            "buyerTaxCode": "",  
            "totalBeforeTax": 13627273.000000000,  
            "taxAmount": 0E-9,  
            "taxRate": null,  
            "paymentMethod": "5",  
            "paymentTime": null,  
            "customerId": null,  
            "no": null,  
            "paymentStatusName": "Đã thanh toán",  
            "buyerName": "Nguyễn văn A",  
            "transactionUuid": "E8AE136CEF1272AAE05324011E0A9838"  
             "originalInvoiceId": "K22THY32"  
        }  
    \]  
}

14. **Gửi email hoá đơn cho khách hàng**

\- Trong trường hợp khách hàng đã cấu hình email server và biểu mẫu email trên hệ thống SInvoice, hệ thống sẽ tự động thực hiện gửi email cho người mua khi trong thông tin hóa đơn có email. API này cho phép phần mềm tích hợp chủ động việc gửi email cho khách hàng, trong trường hợp cấu hình của email là không hoạt động hoặc muốn gửi lại email cho khách hàng khi có yêu cầu.

\- API này có kiểm tra cấu hình gửi email các loại hóa đơn

\- **Chú ý:** 

*\+ Bổ sung đường link tra cứu hóa đơn theo mã bí mật trong email hóa đơn gửi cho người mua.*

*\+ Trường hợp dữ liệu hợp lệ, hệ thống gửi email hóa đơn cho người mua theo biểu mẫu đã cấu hình, thay thế các thông tin trong dấu {} bằng thông tin của hóa đơn/người bán như hiện tại, bổ sung thêm đường link tra cứu hóa đơn theo mã bí mật tại tham số {link-invoice-search}.*

* **Đầu vào:**

- Action (POST): [/InvoiceAPI/](https://10.60.108.210:8273/InvoiceAPI/InvoiceWS/createBatchInvoice/0100109106)InvoiceUtilsWS/sendHtmlMailProcess

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web

\+ Content-Type : application/json 

* Các tham số sendHtmlMailProcess

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required : true DataType: String Minlength :  Maxlength : 20 Format : \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001  |
| lstTransactionUuid | Required : true DataType: String | Danh sách key request, mỗi transactionUuid tương ứng với 1 hoá đơn (Validate độ dài transactionUuid trong khoảng 10 – 36 ký tự). Các transactionUuid cách nhau bởi dấu “,” |

Vị dụ mẫu và các trường dữ liệu:

- JSON:

  {

  	"supplierTaxCode":"0100109106-712s",

  	"lstTransactionUuid":"idtest9999999999,testuuid8888888,transactionUuid123"

  }

* **Đầu ra:**

  Đối tượng Response với HTTPStatus và output Entity.

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null không có lỗi gì xảy ra) |
| description | Mô tả lỗi (giá trị là null không có lỗi gì xảy ra) |

  15. **Phát hành/thay thế/điều chỉnh cho USB-TOKEN (Bước 1: Lấy chuỗi hash)**

**\*Quy tắc kiểm tra ngày lập hóa đơn:**

Hệ thống Hóa đơn điện tử SInvoice V2, phần Cấu hình chung liên quan ngày lập hóa đơn có 2 checkbox: Cho phép ngày lập hóa đơn khác ngày hiện tại, Tự động đặt giá trị cho ngày lập hóa đơn bằng ngày lập gần nhất.

Khi phát hành hóa đơn qua API, ngày lập hóa đơn sẽ bị ảnh hưởng khi người dùng tích chọn các checkbox này, xảy ra 4 trường hợp như mô tả sau:

**TH1: Không tick cả 2**

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: ngày lập không hợp lệ

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại: ngày lập không hợp lệ

\- Ngày lập \> ngày hiện tại: lấy ngày truyền vào (không kiểm tra giờ)

**TH2: Tick “Cấu hình ngày ký là thời điểm hiện tại”**

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: lấy ngày của hóa đơn đã lập gần nhất 

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại: lấy ngày truyền vào 

\- Ngày lập \> ngày hiện tại: ngày lập không hợp lệ

**TH3: Tick “Tự động đặt giá trị cho ngày lập hóa đơn bằng ngày lập gần nhất”**

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: ngày lập không hợp lệ

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại: lấy ngày truyền vào 

\- Ngày lập \> ngày hiện tại: ngày lập không hợp lệ

**TH4: Tích cả 2** 

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: lấy ngày của hóa đơn đã lập gần nhất 

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại:  lấy ngày truyền vào 

\- Ngày lập \> ngày hiện tại: ngày lập không hợp lệ

\- Sinh ra file xml và chuỗi hash của file XML của hóa đơn ký bởi USB Token.

* **Đầuvào:**

- Action (POST):  InvoiceAPI/InvoiceWS/createInvoiceUsbTokenGetHash/{supplierTaxCode}

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

  \+ Content-Type : application/json 

Đầu vào tương tư như lập hóa đơn, bổ sung thêm thông tin chứng thư gửi kèm.  
Bổ sung trường Lý do sai sót hoá đơn. Điều chỉnh cho phép truyền dấu âm số lượng/ đơn giá

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| certificateSerial | Required : true DataType: String Minlength :   Maxlength : 100 Format :  | Serial Number của chứng thư số của doanh nghiệp, chứng thư số này đã được doanh nghiệp đẩy lên trên hệ thống khi đăng ký sử dụng USB Token. Định dạng Hex. Vị dụ: 5404FFFEB7033FB316D672201B7BA4FE |
| adjustedNote | Required: False DataType: String Minlength: N/A Maxlength: 255 Format: | Lý do sai sót  Cho phép nhập chuỗi ký tự tối đa 255 ký tự.  Không bắt buộc truyền. Đặt trong generalInvoiceInfo |
| unitPrice | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+\- | Đơn giá của hàng hóa.  Các quy tắc ràng buộc giữ nguyên hiện trạng.  Bổ sung cho phép truyền giá trị âm   |
| quantity | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+\- | Số lượng của hàng hóa  Các quy tắc ràng buộc giữ nguyên hiện trạng.  Bổ sung cho phép truyền giá trị âm   |
| originalInvoiceType | Required: True DataType: String Minlength: N/A Maxlength:  Format: | Loại hóa đơn gốc Truyền giá trị số với ý nghĩa như sau  0- Không phải hóa đơn giấy/hóa đơn không tồn tại trên hệ thống  1-Hóa đơn TT78  2-Hóa đơn theo QĐ 1209  3-Hóa đơn điện tử/giấy TT32 4-Hóa đơn giấy TT 78 Chú ý:  \- Trường hợp thẻ originalInvoiceType không truyền hoặc truyền giá trị rỗng/0 thì không bắt buộc truyền thẻ originalTemplateCode, hệ thống xác thực thông tin khi lập hóa đơn như hiện trạng.  \- Trường hợp thẻ originalInvoiceType truyền giá trị 1, 2, 3 hoặc 4 thì  \+ Bắt buộc phải truyền thẻ originalTemplateCode, quy tắc xác thực thẻ này tương tự như thẻ templateCode hiện tại.  \+ Khi lập hóa đơn, hệ thống **không kiểm tra tính tồn tại** của hóa đơn gốc trên hệ thống, các quy tắc xác thực khác giữ nguyên hiện trạng |
| originalTemplateCode | Required:  DataType: String Minlength: N/A Maxlength: 20 Format: | Bắt buộc truyền nếu originalInvoiceType là 1, 2, 3 hoặc 4 Ví dụ mẫu TT32: 01GTKT0/001 Ví dụ mẫu TT78: 1/0224 |

**{**  
   **"generalInvoiceInfo":{**  
      **"invoiceType":"01GTKT",**  
      **"templateCode":"01GTKT0/170",**  
	**"invoiceSeries":"AA/17E",**  
      **"transactionUuid": "123e4567-e89b-12d3-a456-426655440000",**  
      **"invoiceIssuedDate":**1587797116843**,**  
      **"currencyCode":"VND",**  
      **"adjustmentType":"1",**  
      **"adjustedNote":"",**  
      **"originalInvoiceType": "1",**  
      **"originalTemolateCode": "1/0224",**  
      **"paymentStatus":true,**  
      **"paymentType":"TM",**  
      **"paymentTypeName":"TM",**  
      **"cusGetInvoiceRight":true,**  
      **"userName":"user 1",**  
      **“certificateSerial”:”5404FFFEB7033FB316D672201B7BA4FE”**  
   **},**  
   **"buyerInfo":{**  
      **"buyerName":"Đặng thị thanh tâm",**  
      **"buyerLegalName":"",**  
      **"buyerTaxCode":"",**  
      **"buyerAddressLine":"HN VN",**  
      **"buyerPhoneNumber":"11111",**  
      **"buyerEmail":"",**  
      **"buyerIdNo":"123456789",**  
      **"buyerIdType":"1"**  
   **},**  
   **"sellerInfo":{**  
      **"sellerLegalName":"Đặng thị thanh tâm",**  
      **"sellerTaxCode":"0100109106-501",**  
      **"sellerAddressLine":"test",**  
      **"sellerPhoneNumber":"0123456789",**  
      **"sellerEmail":"PerformanceTest1@viettel.com.vn",**  
      **"sellerBankName":"vtbank",**  
      **"sellerBankAccount":"23423424"**  
   **},**  
   **"extAttribute":\[**

   **\],**  
   **"payments":\[**  
      **{**  
         **"paymentMethodName":"TM"**  
      **}**  
   **\],**  
   **"deliveryInfo":{**

   **},**  
   **"itemInfo":\[**  
      **{**  
         **"lineNumber":1,**  
         **"itemCode":"ENGLISH\_COURSE",**  
         **"itemName":"Khóa học tiếng anh",**  
         **"unitName":"khóa học",**  
         **"unitPrice":"-3500000.0",**  
         **"quantity":"-10.0",**  
         **"itemTotalAmountWithoutTax":35000000,**  
         **"taxPercentage":10.0,**  
         **"taxAmount":0.0,**  
         **"discount":0.0,**  
         **"itemDiscount":150000.0**  
      **}**  
   **\],**  
   **"discountItemInfo":\[**

   **\],**  
**"metadata":\[**

   **\],**

  "**meterReading": \[{**  
**            "previousIndex": "5454",**  
**            "currentIndex": "244",**  
**            "factor": "22",**  
**            "amount": "2"**  
**          },**  
**          {**  
**            "previousIndex": "44",**  
**            "currentIndex": "44",**  
**            "factor": "33",**  
**            "amount": "3"**  
**          }\],**  
   **"summarizeInfo":{**  
      **"sumOfTotalLineAmountWithoutTax":35000000,**  
      **"totalAmountWithoutTax":35000000,**  
      **"totalTaxAmount":3500000.0,**  
      **"totalAmountWithTax":38500000,**  
      **"totalAmountWithTaxInWords":"Ba mươi tám triệu năm trăm nghìn đồng chẵn",**  
      **"discountAmount":0.0,**  
      **"settlementDiscountAmount":0.0,**  
      **"taxPercentage":10.0,**  
      **"extraName": "{ Tiền phí đặc biệt, Tiền phí,  } ",**  
      **"extraValue": "{ 00 ,00,}"**  
   **},**  
   **"taxBreakdowns":\[**  
      **{**  
         **"taxPercentage":10.0,**  
         **"taxableAmount":35000000,**  
         **"taxAmount":3500000.0**  
      **}**  
   **\]**  
**}**

* Dữ liệu chuỗi Hash trả về

  **{**

    "errorCode": ""**,**

    "description": ""**,**

    "result": **{**

      "hashString": 0HFm34vX525V3Syg5EwdTnfO21s=**,**  **}**

  **}**

**Ví dụ response trường hợp truyền sai giá trị originalInvoiceType**  
{  
    "code": 400,  
    "message": "BAD\_REQUEST\_ORIGINAL\_INVOICE\_TYPE\_INVALID",  
    "data": "BAD\_REQUEST\_ORIGINAL\_INVOICE\_TYPE\_INVALID"  
}

**Lưu ý:** 

1. Dữ liệu hóa đơn gốc lưu vào cột instance\_file\_name trong bảng invoice như sau: 

Loại hóa đơn | Mẫu hóa đơn | Ký hiệu hóa đơn | Số hóa đơn

trong đó:

\- Loại hóa đơn là giá trị thẻ originalInvoiceType 

\- Mẫu hóa đơn là giá trị thẻ originalTemplateCode 

2. Nếu người dùng truyền giá trị 0 hoặc “0” cho tham số validation trong phần generalInvoiceInfo thì các thông tin được truyền trong phần itemInfo, taxBreakdowns, summarizeInfo sẽ được giữ nguyên mà không thực hiện kiểm tra ràng buộc và tính toán lại.

**Output**:

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| errorCode | DataType: String | Mã lỗi nếu có, không có lỗi thì trả về null |
| description | DataType: String | Mô tả chi tiết lỗi |
| hashString | DataType: String | Chuỗi Hash trả về của hóa đơn, dạng Base64 |

16. **Phát hành/thay thế/điều chỉnh cho USB-TOKEN (Bước 2: Ký USB token và sinh hóa đơn)**

\- Thực hiện sử dụng USB-TOKEN để ký chuỗi hashString nhận được từ API trong bước 7.15. Lấy chuỗi ký để sinh hóa đơn.

* **Đầuvào:**

- Action (POST):  InvoiceAPI/InvoiceWS/createInvoiceUsbTokenInsertSignature

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

\+ Content-Type : application/json

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required : true DataType: String Minlength :   Maxlength : 20 Format : \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001  |
| templateCode | Required : true DataType: String Minlength :  Maxlength : 20 | Mã mẫu hóa đơn.   |
| hashString | Required : true DataType: String | Chuỗi Hash mà dữ liệu trả về ở trong request getHash phía bên trên \= out put của API : 7.15 Lập hóa đơn ký USB Token (Bước 1: Lấy chuỗi hash) |
| signature | Required : true DataType: String | Chữ ký sau khi hashString đã được ký bởi USB token. dạng Base64 |

Vị dụ Json  
**{**  
  **"supplierTaxCode": "0100109106-712",**  
  **"templateCode": "01GTKT0/002",**  
  **"hashString": "0HFm34vX525V3Syg5EwdTnfO21s=",**  
  **"signature": "U0WpJk2Q/rDsnZDz8hiWKvs6QEf5DHTG8JyXjjNMtggZ/MIDP0hn9Mutc2uPZEOxqk2YnMjuRSxU8ST/T+C5i46Vb/0+7uIfzKpPm2yrsOSivCdzr6FrY6nJPkfkOWEdEs/hqDzcf4Vn8ZCVkNfovYR4prPGc7kNpO21sNb9BAI="**  
**}**

Kết quả trả về

* Dữ liệu về thông tin về hóa đơn đã lập0

  **{**

    "errorCode": ""**,**

    "description": ""**,**

    "result": **{**

      "supplierTaxCode": 0100109106-712**,**

      "invoiceNo": AA**/**20E0000018**,**

      "transactionID": 12523522245**,**

      "reservationCode": AXHBNK8I0H

    **}**

  **}**

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null nếu lập hóa đơn thành công) |
| description | Mô tả lỗi (giá trị là null nếu lập hóa đơn thành công) |
| supplierTaxCode | Mã số thuế người bán (doanh nghiệp phát hành hóa đơn) |
| invoiceNo | Số hóa đơn vd: AA\\20E0000001  |
| transactionID | Id của giao dịch |
| reservationCode | Mã số bí mật dùng để khách hàng tra cứu |

Tham khảo thêm tại [https://sinvoice.viettel.vn/download/soft/signhash.rar](https://sinvoice.viettel.vn/download/soft/signhash.rar)

**Lưu ý:** Nếu là lập hóa đơn máy tính tiền thì respond trả về có cả thông tin Mã CQT cấp: "codeOfTax", nếu không phải hóa đơn máy tính tiền thì trả về codeOfTax \= null

VD mẫu output  
{  
    "errorCode": null,  
    "description": null,  
    "result": {  
        "supplierTaxCode": "0100109106-710",  
        "invoiceNo": "C23MHY3",  
        "transactionID": "168378907853232661",  
        "reservationCode": "2QTBFEMAXFWZO5B",  
        "codeOfTax": "M1-23-34567-00000000201"  
    }

}

17. **Chuyển font**

Hỗ trợ convert từ các font chữ sang unicode (KH sử dụng API) này kết hợp với API tạo hóa đơn để convert dữ liệu

* **Đầuvào:**

- Action (POST):  InvoiceAPI/InvoiceUtilsWS/convertFont

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

\+ Content-Type : application/json

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| font | Required : true DataType: String | Font dữ liệu, các dữ liệu hỗ trợ bao gồm: VNI TCVN3 TCVN1 |
| data | Required : true DataType: String | Dữ liệu cần chuyển  |

Vị dụ json:  
**{**  
  **"font": "TCVN3",**  
  **"data": "D÷ liÖu kh«ng ®óng chuÈn Unicode cÇn convert"**  
**}**

Kết quả trả về  
**{**  
    **"errorCode": null,**  
    **"description": null,**  
    **"result": "Dữ liệu không đúng chuẩn Unicode cần convert"**  
**}**

![][image37]

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null nếu chuyển font thành công) |
| description | Mô tả lỗi (giá trị là null nếu chuyển font thành công) |
| result | Dữ liệu sau khi được chuyển về chuẩn Unicode |

18. **Cập nhật trạng thái thanh toán**

Cho phép hệ thống tích hợp cập nhật trạng thái thanh toán của hóa đơn sang là đã thanh toán.

* **Đầu vào:**

- Action (POST):  InvoiceAPI/InvoiceWS/updatePaymentStatus

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

\+ Content-Type : application/x-www-form-urlencoded

- Data: dữ liệu truyền vào dạng Form Param gồm các tham số:

|  Tên trường |  Kiểu dữ liệu, ràng buộc |  Dữ liệu/mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required: true DataType: String Minlength:  Maxlength: 20 Format: \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001  |
| templateCode | Required: true DataType: String Minlength:  Maxlength: 20 Format:   | Mẫu số hóa đơn  |
| invoiceNo | Required: true DataType: String Minlength: 7 Maxlength: 35 Format:  \[a-zA-Z0-9\]\*$ | Là ký hiệu hóa đơn \+ số hóa đơn vd: AA/20E0000001  |
| buyerEmailAddress | Required: false DataType: String Minlength:  Maxlength: 2000 Format: ^\[\_A-Za-z0-9-\\+\]+(\\.\[\_A-Za-z0-9-\]+)\*@\[A-Za-z0-9-\]+(\\.\[A-Za-z0-9\]+)\*(\\.\[A-Za-z\]{2,})$ | Email người mua    |
| strIssueDate | Required: false DataType: milisecond Minlength:  Maxlength:  Format: Tiêu chuẩn 5.1 | Ngày lập hóa đơn    |
| paymentType | Required: false DataType: String Minlength:  Maxlength:  Format:  | Loại hình thức thanh toán     |
| paymentTypeName | Required: false DataType: String Minlength:  Maxlength:  Format: | Tên phương thức thanh toán    |
| cusGetInvoiceRight | Required: false DataType: Boolean Minlength:  Maxlength:  Format: true/false | Cho khách hàng xem hóa đơn trong Quản lý hóa đơn  |

  * Vị dụ định dạng FormParam

![][image38]

Dữ liệu trả về  
**{"errorCode":null,"description":null,"result":true,"paymentTime":null,"paymentMethod":null}**

Mô tả

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null nếu cập nhật trạng thái thanh toán thành công) |
| description | Mô tả lỗi (giá trị là null nếu cập nhật trạng thái thanh toán thành công) |
| result | Kết quả cập nhật trạng thái thanh toán  Thành công: true Không thành công: false |
| paymentTime | Thời gian cập nhật trạng thái thanh toán |
| paymentMethod | Phương thức thanh toán |

19. **Hủy trạng thái thanh toán**

Cho phép chuyển trạng thái thanh toán của hóa đơn sang chưa thanh toán.

* **Đầu vào:**

- Action (POST):  InvoiceAPI/InvoiceWS/cancelPaymentStatus

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

  \+ Content-Type : application/x-www-form-urlencoded


| Tên trường | Kiểu dữ liệu, ràng buộc | Dữ liệu/mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required : true DataType: String Minlength :  Maxlength : 20 Format : \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 |
| invoiceNo | Required : true DataType: String Minlength : 7 Maxlength : 35 Format :  \[a-zA-Z0-9\]\*$ | Là ký hiệu hóa đơn \+ số hóa đơn vd : AA/20E0000001 |
| strIssueDate | Required : true DataType:  Minlength :  Maxlength :  Format:Tiêu chuẩn 5.1 | Ngày lập hóa đơn   |

  * Vị dụ định dạng FormParam

    **supplierTaxCode=0100109106-712\&invoiceNo=AA%2F20E0000002\&strIssueDate=1600154781000**

    * Dữ liệu trả về

    **{**

        **"errorCode": null,**

        **"description": "Success"**

    **}**


  ![][image39]

  20. **Xem trước hóa đơn nháp**

* **Đầu vào:**

Webservice dùng để lấy file PDF của dữ liệu để xem. Hệ thống tích hợp đẩy dữ liệu lập hóa đơn sang và SInvoice trả về file PDF của dữ liệu đó, các dữ liệu sẽ không được lưu vào trong SInvoice.

- Action (POST):  InvoiceAPI/InvoiceUtilsWS/createInvoiceDraftPreview/{supplierTaxCode}

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

  \+ Content-Type : application/json 

|  Tên trường |  Kiểu dữ liệu, ràng buộc |  Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required: true DataType: String Minlength:  Maxlength: 20 Format: \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 |

- Data: Định dạng JSON

- Thông số dữ liệu truyền vào tương tự phần Lập hóa đơn. Tham khảo json tại phần 6.2


  

  **Lưu ý:**

  Trong trường hợp lập hóa đơn điều chỉnh/thay thế cho hóa đơn giấy thì bổ sung thêm trong generalInvoiceInfo hai thẻ như sau: 

| Tên trường | Kiểu dữ liệu | Mô tả |
| :---- | :---- | :---- |
| originalInvoiceType | Required: false DataType: String Minlength: N/A Maxlength:  Format: | Loại hóa đơn gốc Truyền giá trị số với ý nghĩa như sau  0- Không phải hóa đơn giấy/hóa đơn không tồn tại trên hệ thống  1-Hóa đơn TT78  2-Hóa đơn theo QĐ 1209  3-Hóa đơn điện tử/giấy TT32 4-Hóa đơn giấy TT 78 |
| originalTemplateCode | Required:  DataType: String Minlength: N/A Maxlength: 20 Format: | Bắt buộc truyền nếu originalInvoiceType là 1, 2, 3 hoặc 4 Ví dụ mẫu TT32: 01GTKT0/001 Ví dụ mẫu TT78: 1/0224 |

Khi lập hóa đơn, hệ thống **không kiểm tra tính tồn tại** của hóa đơn gốc trên hệ thống, các quy tắc xác thực khác giữ nguyên hiện trạng

* **Đầu ra:**

- Đối tượng Response với HTTPStatus và output Entity.

| Tên trường | Mô tả |
| :---- | :---- |
| errorCode | Mã lỗi (giá trị là null không có lỗi gì xảy ra) |
| description | Mô tả lỗi (giá trị là null không có lỗi gì xảy ra) |
| fileName | Tên file tải về |
| fileToBytes | Nội dung file được chuyển thành kiểu byte, dạng base64 |

**Lưu ý:**

Nếu người dùng truyền giá trị 0 hoặc “0” cho tham số validation trong phần generalInvoiceInfo thì các thông tin được truyền trong phần itemInfo, taxBreakdowns, summarizeInfo sẽ được giữ nguyên mà không thực hiện kiểm tra ràng buộc và tính toán lại.

21. **Tra cứu hóa đơn bằng transactionUuid**

Cho phép hệ thống tích hợp tra cứu hóa đơn đã được phát hành thành công dựa vào transactionUuid (Dữ liệu xác định tính duy nhất của 1 hóa đơn do bên phần mềm tích hợp sinh dữ liệu và kiểm soát)

Thường sử dụng API này khi cần đối soát dữ liệu giữa 2 hệ thống HDDT và phần mềm tích hợp.

* **Đầu vào:**

- Action (POST):  *InvoiceAPI/InvoiceWS/searchInvoiceByTransactionUuid*

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web hoặc Authorization: username/pass như đăng nhập trên web

  \+ Content-Type : application/x-www-form-urlencoded

| Tên trường | Kiểu dữ liệu, ràng buộc | Dữ liệu/mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required: true DataType: String Minlength:  Maxlength: 20 Format: \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001  |
| transactionUuid | Required: true DataType: String Minlength: 10 Maxlength: 36 Format:  | Giá trị transactionUuid gán với hóa đơn khi gửi dữ liệu lập hóa đơn.   |

Ví dụ với định dạng formParam:

![][image40]Hình ảnh Response trả về thành công

![][image41]

Thông tin chi tiết Response  
{![][image42]  
   "transactionUuid": "0100109106\_test3\_268\_1",  
   "errorCode": null,  
   "description": null,  
   "result": \[![][image42]  
      {![][image42]  
         "supplierTaxCode": "0100109106",  
         "invoiceNo": "AB/19E0000522",  
         "reservationCode": "OKMYMDX5F4",  
         "issueDate": 1587797116843  
         "status": "Hóa đơn gốc"  
      }  
   \]  
}

Đối với các hóa đơn theo Thông tư 78 đã được cơ quan thuế cấp mã sẽ có các thông tin bổ sung về mã cơ quan thuế như sau

| STT | Tên thẻ | Ý nghĩa |
| ----- | ----- | ----- |
|  | exchangeStatus | Mô tả trạng thái truyền nhận của HĐ với CQT |
|  | exchangeDes | Mô tả lỗi truyền nhận  |
|  | codeOfTax | Mã CQT cấp |

{  
    "errorCode": null,  
    "description": null,  
    "transactionUuid": "4543Gfd565h",  
    "result": \[  
        {  
            "supplierTaxCode": "0100109106-710",  
            "invoiceNo": "K21DTT4",  
            "reservationCode": "UFODH7MN7LT0GW5",  
            "issueDate": 1638852198000,  
            "status": "Hóa đơn điều chỉnh tiền",  
            "exchangeStatus": " Mã CQT cấp: 00BDD6525B75646655B654665B65466565",  
            "exchangeDes": null,  
            "codeOfTax": "00BDD6525B75646655B654665B65466565"  
        }  
    \]  
}

## **7.22 Cấp mã bí mật**

\- Cho phép API cấp mã bí mật cho doanh nghiệp theo MST.

\- Đường dẫn API: InvoiceAPI/BotWS/getReservationCode/{taxCode}

\- Method: POST

**Input**: 

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| transactionUuid | Required: false DataType: String Minlength: 10 Maxlength: 36 Format: | ID để kiểm trùng giao dịch.  Khuyến cáo: sử dụng UUID v4. |
| requestCode | Required: true DataType: BigDecimal Minlength:  Maxlength:  Format: | Số lượng mã yêu cầu Maxlength \= 30,000 – Số lượng lấy mã mà chưa sử dụng |
| expiredDate | Required: false DataType: Date Minlength:  Maxlength:  Format: | Ngày hết hạn sử dụng mã Định dạng theo Tiêu chuẩn 5.1, đến giờ, phút, giây Ví dụ: 1587797116000 |

Ví dụ: 

{

  "transactionUuid": "56432347787",

  "expiredDate": 1587797116000,

  "requestCode": 50  

}

**Output**: 

| Tên trường | Mô tả |
| ----- | ----- |
| transactionUuid | transactionUuid đã truyền trong Input |
| expiredDate | Ngày hết hạn sử dụng mã đã truyền trong Input |
| reservationCode | Danh sách mã bí mật cấp cho MST  |

Ví dụ: 

{

  "transactionUuid": "56432347787",

  "expiredDate": 1587797116000

  "result": 

  {

  "reservationCode": \["479765676", "867547567"\]

}

}

23. ## **Cập nhật trạng thái in hoá đơn**

\- Mô tả chung: Thêm mới API cập nhật trạng thái in của hóa đơn đã phát hành.

\- Đường dẫn API: InvoiceAPI/InvoiceUtilsWS/updateInvoicePrintStatus

\- Method: PUT

\- Phạm vi: NA

**Input**: 

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| taxCode | Required: true DataType: String Minlength:  Maxlength: 20 Format: \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn.  **Ví dụ:** Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 |
| templateCode | Required: true DataType: String Minlength:  Maxlength: 20 Format:  | Mã mẫu hóa đơn **Ví dụ:**  Hóa đơn TT32: 01GTKT0/001 Hóa đơn TT78: 1/001 |
| invoiceNo | Required: true DataType: String Minlength: 7 Maxlength: 35 Format: \[a-zA-Z0-9\]\*$ | Là ký hiệu hóa đơn \+ Số hóa đơn  **Ví dụ**:  Hóa đơn TT32: AA/20E0000001 Hóa đơn TT78: K22THY12 |
| printStatus | Required: true DataType: int(3) Minlength:  Maxlength: 1 Format:  | Trạng thái in của hóa đơn 1-in  0-chưa in |

**Output**: 

Ví dụ trường hợp thành công:

{

    "code": 200,

    "message": "SUCCESS\_UPDATE\_PRINT\_STATUS",

    "data": "Cập nhật trạng thái in thành công"

}

Ví dụ trường hợp lỗi:

{

    "code": 400,

    "message": "INVOICE\_NOT\_FOUND",

    "data": "Hóa đơn không tồn tại"

}

## **7.24 Số lần quét QRcode của hoá đơn**

\- Mô tả chung: Thêm mới API cập nhật số lần quét QRCODE của hóa đơn đã phát hành.

\- Đường dẫn API: InvoiceAPI/InvoiceUtilsWS/updateInvoiceScanQrcode

\- Method: PUT

\- Phạm vi: NA

**Input**: 

| Tên trường | Kiểu dữ liệu | Mô tả |
| ----- | ----- | ----- |
| taxCode | Required: true DataType: String Minlength:  Maxlength: 20 Format: \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn.  **Ví dụ:** Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 |
| templateCode | Required: true DataType: String Minlength:  Maxlength: 20 Format:  | Mã mẫu hóa đơn **Ví dụ:**  Hóa đơn TT32: 01GTKT0/001 Hóa đơn TT78: 1/001 |
| invoiceNo | Required: true DataType: String Minlength: 7 Maxlength: 35 Format: \[a-zA-Z0-9\]\*$ | Là ký hiệu hóa đơn \+ Số hóa đơn  **Ví dụ**:  Hóa đơn TT32: AA/20E0000001 Hóa đơn TT78: K22THY12 |

**Output**: 

Ví dụ trường hợp thành công:

{

    "code": 200,

    "message": "SUCCESS\_UPDATE\_SCAN\_QRCODE",

    "data": "Cập nhật quét QRCODE thành công",

    "remainScan": 5

}

Ví dụ trường hợp lỗi:

{

    "code": 400,

    "message": "INVOICE\_NOT\_FOUND",

    "data": "Hóa đơn không tồn tại"

}

## **7.25 Thống kê hóa đơn theo user**

\- Mô tả chung: Yêu này thêm mới API thống kê hóa đơn.

\- Đường dẫn API: Action (GET): InvoiceAPI/InvoiceWS/getInvoiceUsage

\- Phạm vi: Tất cả các loại hóa đơn

\-	Headers:

 \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

 \+ Content-Type: application/json

**Input**: 

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required: true DataType: String Minlength:  Maxlength:  Format:  | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. |
| issueDateFrom | Required: true DataType: DateTime Minlength:  Maxlength:  Format: | Thời gian phát hành hóa đơn từ ngày Định dạng milliseconds  |
| issueDateTo | Required: true DataType: DateTime Minlength:  Maxlength:  Format: | Thời gian phát hành hóa đơn đến ngày Định dạng milliseconds |
| createdUser | Required: true DataType: String Minlength:  Maxlength:  Format: | Người tạo hóa đơn  (Truyền username) |
| deletedStatus | Required: false DataType: Integer Minlength:  Maxlength:  Format: | Trạng thái hủy của hóa đơn, gồm:  0-Chưa hủy  1-Đã hủy |
| templateCode | Required: false DataType: String Minlength:  Maxlength:  Format: | Mã mẫu hóa đơn  Ví dụ với TT32: 01GTKT0/001 Ví dụ với TT78: 1/0234 |
| invoiceSeri | Required: false DataType: String Minlength:  Maxlength: 25 Format: | Ký hiệu hóa đơn Ví dụ: K22THY, AB/22E |
| itemName | Required: false DataType: String Minlength:  Maxlength:  Format: | Tên hàng hóa dịch vụ  |
| itemCode | Required: false DataType: String Minlength:  Maxlength:  Format: | Mã hàng hóa dịch vụ |
| totalAmountWithVat | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: | Tổng tiền sau thuế của hóa đơn |
| scanStatus | Required: false DataType: Integer Minlength:  Maxlength:  Format: | Trạng thái quét QrCode của hóa đơn, gồm: 1-Chưa quét 2-Đã quét 3-Hết lượt 4-Còn lượt |

**Output**: 

Ví dụ trường hợp thành công  
**{**  
  "errorCode": ""**,**  
  "description": ""**,**  
  "result": **{**  
    "totalDeletedInvoice": 5**,**  
    "totalNotDeletedInvoice": 50**,**  
    "totalScanInvoice": 10**,**  
    "totalNotScanInvoice": 5,  
    "totalOutOfScanInvoice": 5**,**  
    "totalRemainScanInvoice": 20**,**  
    "totalAmountDeleted": 5000000**,**  
    "totalAmountNotDeleted": 700000000  
  **}**  
**}**

Ví dụ trường hợp lỗi   
{  
    "code": 400,  
    "message": "FROM\_BIGGER\_DAY\_TO\_DAY",  
    "data": "Từ ngày không được lớn hơn đến ngày"  
}

## **7.26 Giải trình** 

\- Mô tả chung: Yêu cầu này thực hiện thêm mới API cho phép người dùng giải trình thông tin cho hóa đơn đã phát hành.

\- Method: PUT

\- Đường dẫn API: InvoiceWS/update-explanation

\- Phạm vi: Chỉ áp dụng với hóa đơn theo TT78, hóa đơn có trạng thái khác Hủy.

**Input**: 

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required: true DataType: String Minlength:  Maxlength: 20 Format  | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn.  |
| templateCode | Required: true DataType: String Minlength:  Maxlength: 20 Format:  | Mã mẫu hóa đơn VD:  01GTKT0/001 1/001 |
| invoiceNo | Required: true DataType: String Minlength:  Maxlength: 35 Format: | Là ký hiệu hóa đơn ghép với số hóa đơn  VD: AA/20E0000001 hoặc K22THY112  |
| strIssueDate | Required: true DataType: milisecond Minlength:  Maxlength:  Format: Tiêu chuẩn 5.1 | Ngày lập hóa đơn   |
| reason | Required: False DataType: String Minlength:  Maxlength: 255 Format: | Nội dung giải trình của hóa đơn  Cho phép nhập tối đa 255 ký tự |

Ví dụ: 

{

    "supplierTaxCode": "0100109106-710",

    "templateCode": "5/036",

    "invoiceNo": "C22MTY1",

    "strIssueDate": 1666084951000,

    "reason": "ok"

}

**Output**: 

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | NULL trong trường hợp giải trình thành công |
| description | Thông báo trong trường hợp giải trình thành công |
| code | Mã lỗi (trong trường hợp lỗi) |
| message | Mã lỗi (trong trường hợp lỗi) |
| data | Mô tả lỗi (trong trường hợp lỗi) |

Ví dụ trường hợp thành công: 

{

    "errorCode": null,

    "description": "SUCCESSFUL INVOICE EXPLANATION\!"

}

Ví dụ trường hợp lỗi: 

{

    "code": 400,

    "message": "INVOICE\_STATUS\_INVALID",

    "data": "Trạng thái hóa đơn không hợp lệ"

}

**Ví dụ:**   
{  
    "taxCode": "0100109106-710",  
    "invoiceType": "5"  
}

**Output**: 

| STT | Tên trường | Mô tả |
| :---: | ----- | ----- |
|  | errorcode | Mã lỗi |
|  | description | Mô tả lỗi |
|  | totalRows | Tổng số dòng kết quả tìm được |
|  | template | NA |
|  | templateCode | Mẫu hóa đơn |
|  | invoiceSeri | Ký hiệu hóa đơn |
|  | originalTemplateCode | Mẫu hóa đơn gốc |

## **7.27 Phát hành hóa đơn có mã bí mật cho CTS SERVER**

**\* Quy tắc kiểm tra ngày lập hóa đơn:**

Hệ thống Hóa đơn điện tử SInvoice V2, phần Cấu hình chung liên quan ngày lập hóa đơn có 2 checkbox: Cho phép ngày lập hóa đơn khác ngày hiện tại, Tự động đặt giá trị cho ngày lập hóa đơn bằng ngày lập gần nhất.

Khi phát hành hóa đơn qua API, ngày lập hóa đơn sẽ bị ảnh hưởng khi người dùng tích chọn các checkbox này, xảy ra 4 trường hợp như mô tả sau:

**TH1: Không tick cả 2**

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: ngày lập không hợp lệ

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại: ngày lập không hợp lệ

\- Ngày lập \> ngày hiện tại: lấy ngày truyền vào (không kiểm tra giờ)

**TH2: Tick “Cấu hình ngày ký là thời điểm hiện tại”**

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: lấy ngày của hóa đơn đã lập gần nhất 

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại: lấy ngày truyền vào 

\- Ngày lập \> ngày hiện tại: ngày lập không hợp lệ

**TH3: Tick “Tự động đặt giá trị cho ngày lập hóa đơn bằng ngày lập gần nhất”**

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: ngày lập không hợp lệ

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại: lấy ngày truyền vào 

\- Ngày lập \> ngày hiện tại: ngày lập không hợp lệ

**TH4: Tích cả 2** 

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: lấy ngày của hóa đơn đã lập gần nhất 

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại:  lấy ngày truyền vào 

\- Ngày lập \> ngày hiện tại: ngày lập không hợp lệ

\- Mô tả chung: Yêu cầu này thực hiện thêm mới API cho phép người dùng lập hóa đơn có mã số bí mật

\- Đường dẫn API: InvoiceAPI/BotWS/createInvoiceWithCode/{taxCode}

**\- Đầu vào tương tư như lập hóa đơn, bổ sung thêm thông tin:** 

\+ thêm **reservationCode** trong input generalInvoiceInfo (bắt buộc) 

\+ điều kiện hợp lệ: mã được cấp cho đúng MST, mã chưa được sử dụng cho hóa đơn nào, mã chưa hết hạn 

\+ reservationCode trong input chính là reservationCode trong output

| reservationCode | Required: true DataType: String Minlength:  Maxlength: 100 Format: | Mã số bí mật  |
| :---- | :---- | :---- |

**Ví dụ:** 

**Input generalInvoiceInfo:**   
generalInvoiceInfo": {  
        "invoiceType": "13",  
        "templateCode": "2/035",  
        "invoiceSeries": "C22DVH",  
        "currencyCode": "VND",  
        "adjustmentType": "1",  
        "paymentStatus": true,  
        "cusGetInvoiceRight": true,  
        "invoiceIssuedDate": null,  
        "reservationCode": " 0RS5LCM7P2ODPB4"  
    }  
         **Output:**

{  
    "errorCode": null,  
    "description": null,  
    "result": {  
        "supplierTaxCode": "0100109106-710",  
        "invoiceNo": "C22DVH26",  
        "transactionID": "167238328041929055",  
        "reservationCode": "0RS5LCM7P2ODPB4"  
       }  
}

Ví dụ trường hợp lỗi: 

{

    "code": 400,

    "message": "reservation.code.used",

    "data": "BAD\_REQUEST\_RESERVATION\_CODE\_USED"

}  
**Lưu ý:** 

1. Nếu là lập hóa đơn máy tính tiền thì respond trả về có cả thông tin Mã CQT cấp: "codeOfTax", nếu không phải hóa đơn máy tính tiền thì trả về “codeOfTax” \= null

    VD mẫu output

   {

       "errorCode": null,

       "description": null,

       "result": {

           "supplierTaxCode": "0100109106-710",

           "invoiceNo": "C23MHY3",

           "transactionID": "168378907853232661",

           "reservationCode": "2QTBFEMAXFWZO5B",

           "codeOfTax": "M1-23-34567-00000000201"

       }

   }

2. Nếu cấu hình Không ký hóa đơn có mã khởi tạo từ máy tính tiền và hóa đơn thuộc loại máy tính tiền thì cho phép doanh nghiệp dùng chữ ký USB Token và CloudCA lập hóa đơn phát hành có mã bí mật bằng API Server.

3. Nếu người dùng truyền giá trị 0 hoặc “0” cho tham số validation trong phần generalInvoiceInfo thì các thông tin được truyền trong phần itemInfo, taxBreakdowns, summarizeInfo sẽ được giữ nguyên mà không thực hiện kiểm tra ràng buộc và tính toán lại.

## **7.28 Phát hành hóa đơn có mã bí mật cho USB-TOKEN**

\- Mô tả chung: Yêu cầu này thực hiện thêm mới API cho phép người dùng lập hóa đơn có mã số bí mật

\- Đường dẫn API lấy chuỗi hash: InvoiceAPI/InvoiceWS/createInvoiceUsbTokenGetHash/{supplierTaxCode}

\- Đường dẫn API ký và sinh hóa đơn: 

InvoiceAPI/InvoiceWS/createInvoiceUsbTokenInsertSignature

*\- Nội dung tương tự như phần lập hóa đơn mã số bí mật server **mục 7.28***

**Lưu ý:**

Nếu người dùng truyền giá trị 0 hoặc “0” cho tham số validation trong phần generalInvoiceInfo thì các thông tin được truyền trong phần itemInfo, taxBreakdowns, summarizeInfo sẽ được giữ nguyên mà không thực hiện kiểm tra ràng buộc và tính toán lại.

## **7.29 Lấy danh sách mẫu và ký hiệu hóa đơn theo mã số thuế trên toàn hệ thống**

- API cho phép người dùng hệ thống tích hợp lấy danh sách mẫu và ký hiệu hóa đơn khả dụng của mã số thuế cho trước trên toàn bộ hệ thống

\- Đường dẫn API: /InvoiceAPI/InvoiceUtilsWS/getAllInvoiceTemplates

**Input**: 

| Tên trường | Kiểu dữ liệu | Mô tả |
| :---- | :---- | :---- |
| taxCode | Required: True DataType: String Minlength: N/A Maxlength:  Format: | Mã số thuế doanh nghiệp Quy tắc validate như hiện trạng hệ thống   |
| invoiceType | Required: True DataType: String Minlength: N/A Maxlength:  Format: | Ví dụ với TT32: 01GTKT  Ví dụ với TT78: 1 |

**Ví dụ:**   
{  
    "taxCode": "0100109106-710",  
    "invoiceType": "all"  
}

**Output**: 

| STT | Tên trường | Mô tả |
| :---- | :---- | :---- |
| 1 | errorcode | Mã lỗi |
| 2 | description | Mô tả lỗi |
| 3 | totalRows | Tổng số dòng kết quả tìm được |
| 4 | template | NA |
| 5 | templateCode | Mẫu hóa đơn |
| 6 | invoiceSeri | Ký hiệu hóa đơn |
| 7 | originalTemplateCode | Mẫu hóa đơn gốc  |

**Ví dụ:**  
{  
    "errorCode": **null**,  
    "description": **null**,  
    "totalRows": 10,  
    "template": \[  
        {  
            "templateCode": "1/138",  
            "invoiceSeri": "K23TYH",  
            "originalTemplateCode": "1/0001"  
        },  
        {  
            "templateCode": "1/141",  
            "invoiceSeri": "K23TKH",  
            "originalTemplateCode": "1/0008"  
        },  
        {  
            "templateCode": "1/142",  
            "invoiceSeri": "K23TRW",  
            "originalTemplateCode": "1/0005"  
        },  
        {  
            "templateCode": "1/143",  
            "invoiceSeri": "K22TYT",  
            "originalTemplateCode": "1/0001"  
        },  
        {  
            "templateCode": "1/143",  
            "invoiceSeri": "K23TEF",  
            "originalTemplateCode": "1/0001"  
        },  
        {  
            "templateCode": "1/001",  
            "invoiceSeri": "C21TUH",  
            "originalTemplateCode": "1/0001"  
        },  
        {  
            "templateCode": "2/002",  
            "invoiceSeri": "K23MAA",  
            "originalTemplateCode": "2/0002"  
        },  
        {  
            "templateCode": "2/002",  
            "invoiceSeri": "K22MAB",  
            "originalTemplateCode": "2/0002"  
        },  
        {  
            "templateCode": "2/005",  
            "invoiceSeri": "C21MYH",  
            "originalTemplateCode": "2/0002"  
        },  
        {  
            "templateCode": "6/003",  
            "invoiceSeri": "K22NKL",  
            "originalTemplateCode": "6/0001"  
        }  
    \]

}

30. **Phát hành/thay thế/điều chỉnh cho CLOUD CA (Bước 1: Lấy chuỗi hash)**

**\*Quy tắc kiểm tra ngày lập hóa đơn:**

Hệ thống Hóa đơn điện tử SInvoice V2, phần Cấu hình chung liên quan ngày lập hóa đơn có 2 checkbox: Cho phép ngày lập hóa đơn khác ngày hiện tại, Tự động đặt giá trị cho ngày lập hóa đơn bằng ngày lập gần nhất.

Khi phát hành hóa đơn qua API, ngày lập hóa đơn sẽ bị ảnh hưởng khi người dùng tích chọn các checkbox này, xảy ra 4 trường hợp như mô tả sau:

**TH1: Không tick cả 2**

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: ngày lập không hợp lệ

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại: ngày lập không hợp lệ

\- Ngày lập \> ngày hiện tại: lấy ngày truyền vào (không kiểm tra giờ)

**TH2: Tick “Cấu hình ngày ký là thời điểm hiện tại”**

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: lấy ngày của hóa đơn đã lập gần nhất 

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại: lấy ngày truyền vào 

\- Ngày lập \> ngày hiện tại: ngày lập không hợp lệ

**TH3: Tick “Tự động đặt giá trị cho ngày lập hóa đơn bằng ngày lập gần nhất”**

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: ngày lập không hợp lệ

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại: lấy ngày truyền vào 

\- Ngày lập \> ngày hiện tại: ngày lập không hợp lệ

**TH4: Tích cả 2** 

\- Ngày lập (invoiceIssuedDate) null: lấy ngày giờ hiện tại (sysdate)

\- Ngày lập \< ngày lập của hóa đơn gần nhất: lấy ngày của hóa đơn đã lập gần nhất 

\- Ngày lập \>= ngày lập của hóa đơn gần nhất và \<= ngày hiện tại:  lấy ngày truyền vào 

\- Ngày lập \> ngày hiện tại: ngày lập không hợp lệ

\- Sinh ra file xml và chuỗi hash của file XML của hóa đơn ký bởi USB Token.

* **Đầuvào:**

- Action (POST):  InvoiceAPI/InvoiceWS/createInvoiceUsbTokenGetHash/{supplierTaxCode}

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web  hoặc Authorization: username/pass như đăng nhập trên web

  \+ Content-Type : application/json 

Đầu vào tương tư như lập hóa đơn, bổ sung thêm thông tin chứng thư gửi kèm.  
Bổ sung trường Lý do sai sót hoá đơn. Điều chỉnh cho phép truyền dấu âm số lượng/ đơn giá

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| certificateSerial | Required : true DataType: String Minlength :   Maxlength : 100 Format :  | Serial Number của chứng thư số của doanh nghiệp, chứng thư số này đã được doanh nghiệp đẩy lên trên hệ thống khi đăng ký sử dụng USB Token. Định dạng Hex. Vị dụ: 5404FFFEB7033FB316D672201B7BA4FE |
| adjustedNote | Required: False DataType: String Minlength: N/A Maxlength: 255 Format: | Lý do sai sót  Cho phép nhập chuỗi ký tự tối đa 255 ký tự.  Không bắt buộc truyền. Đặt trong generalInvoiceInfo |
| unitPrice | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+\- | Đơn giá của hàng hóa.  Các quy tắc ràng buộc giữ nguyên hiện trạng.  Bổ sung cho phép truyền giá trị âm   |
| quantity | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+\- | Số lượng của hàng hóa  Các quy tắc ràng buộc giữ nguyên hiện trạng.  Bổ sung cho phép truyền giá trị âm   |
| originalInvoiceType | Required: True DataType: String Minlength: N/A Maxlength:  Format: | Loại hóa đơn gốc Truyền giá trị số với ý nghĩa như sau  0- Không phải hóa đơn giấy/hóa đơn không tồn tại trên hệ thống  1-Hóa đơn TT78  2-Hóa đơn theo QĐ 1209  3-Hóa đơn điện tử/giấy TT32 4-Hóa đơn giấy TT 78 Chú ý:  \- Trường hợp thẻ originalInvoiceType không truyền hoặc truyền giá trị rỗng/0 thì không bắt buộc truyền thẻ originalTemplateCode, hệ thống xác thực thông tin khi lập hóa đơn như hiện trạng.  \- Trường hợp thẻ originalInvoiceType truyền giá trị 1, 2, 3 hoặc 4 thì  \+ Bắt buộc phải truyền thẻ originalTemplateCode, quy tắc xác thực thẻ này tương tự như thẻ templateCode hiện tại.  \+ Khi lập hóa đơn, hệ thống **không kiểm tra tính tồn tại** của hóa đơn gốc trên hệ thống, các quy tắc xác thực khác giữ nguyên hiện trạng |
| originalTemplateCode | Required:  DataType: String Minlength: N/A Maxlength: 20 Format: | Bắt buộc truyền nếu originalInvoiceType là 1, 2, 3 hoặc 4 Ví dụ mẫu TT32: 01GTKT0/001 Ví dụ mẫu TT78: 1/0224 |

**{**  
   **"generalInvoiceInfo":{**  
      **"invoiceType":"01GTKT",**  
      **"templateCode":"01GTKT0/170",**  
      **"invoiceSeries":"AA/17E",**  
      **"transactionUuid": "123e4567-e89b-12d3-a456-426655440000",**  
      **"invoiceIssuedDate":**1587797116843**,**  
      **"currencyCode":"VND",**  
      **"adjustmentType":"1",**  
      **"adjustedNote":"",**  
      **"originalInvoiceType": "1",**  
      **"originalTemolateCode": "1/0224",**  
      **"paymentStatus":true,**  
      **"paymentType":"TM",**  
      **"paymentTypeName":"TM",**  
      **"cusGetInvoiceRight":true,**  
      **"userName":"user 1",**  
      **“certificateSerial”:”5404FFFEB7033FB316D672201B7BA4FE”**  
   **},**  
   **"buyerInfo":{**  
      **"buyerName":"Đặng thị thanh tâm",**  
      **"buyerLegalName":"",**  
      **"buyerTaxCode":"",**  
      **"buyerAddressLine":"HN VN",**  
      **"buyerPhoneNumber":"11111",**  
      **"buyerEmail":"",**  
      **"buyerIdNo":"123456789",**  
      **"buyerIdType":"1"**  
   **},**  
   **"sellerInfo":{**  
      **"sellerLegalName":"Đặng thị thanh tâm",**  
      **"sellerTaxCode":"0100109106-501",**  
      **"sellerAddressLine":"test",**  
      **"sellerPhoneNumber":"0123456789",**  
      **"sellerEmail":"PerformanceTest1@viettel.com.vn",**  
      **"sellerBankName":"vtbank",**  
      **"sellerBankAccount":"23423424"**  
   **},**  
   **"extAttribute":\[**

   **\],**  
   **"payments":\[**  
      **{**  
         **"paymentMethodName":"TM"**  
      **}**  
   **\],**  
   **"deliveryInfo":{**

   **},**  
   **"itemInfo":\[**  
      **{**  
         **"lineNumber":1,**  
         **"itemCode":"ENGLISH\_COURSE",**  
         **"itemName":"Khóa học tiếng anh",**  
         **"unitName":"khóa học",**  
         **"unitPrice":"-3500000.0",**  
         **"quantity":"-10.0",**  
         **"itemTotalAmountWithoutTax":35000000,**  
         **"taxPercentage":10.0,**  
         **"taxAmount":0.0,**  
         **"discount":0.0,**  
         **"itemDiscount":150000.0**  
      **}**  
   **\],**  
   **"discountItemInfo":\[**

   **\],**  
**"metadata":\[**

   **\],**

  "**meterReading": \[{**  
**            "previousIndex": "5454",**  
**            "currentIndex": "244",**  
**            "factor": "22",**  
**            "amount": "2"**  
**          },**  
**          {**  
**            "previousIndex": "44",**  
**            "currentIndex": "44",**  
**            "factor": "33",**  
**            "amount": "3"**  
**          }\],**  
   **"summarizeInfo":{**  
      **"sumOfTotalLineAmountWithoutTax":35000000,**  
      **"totalAmountWithoutTax":35000000,**  
      **"totalTaxAmount":3500000.0,**  
      **"totalAmountWithTax":38500000,**  
      **"totalAmountWithTaxInWords":"Ba mươi tám triệu năm trăm nghìn đồng chẵn",**  
      **"discountAmount":0.0,**  
      **"settlementDiscountAmount":0.0,**  
      **"taxPercentage":10.0,**  
      **"extraName": "{ Tiền phí đặc biệt, Tiền phí,  } ",**  
      **"extraValue": "{ 00 ,00,}"**  
   **},**  
   **"taxBreakdowns":\[**  
      **{**  
         **"taxPercentage":10.0,**  
         **"taxableAmount":35000000,**  
         **"taxAmount":3500000.0**  
      **}**  
   **\]**  
**}**

* Dữ liệu chuỗi Hash trả về

  **{**

    "errorCode": ""**,**

    "description": ""**,**

    "result": **{**

      "hashString": 0HFm34vX525V3Syg5EwdTnfO21s=**,**  **}**

  **}**

**Ví dụ response trường hợp truyền sai giá trị originalInvoiceType**  
{  
    "code": 400,  
    "message": "BAD\_REQUEST\_ORIGINAL\_INVOICE\_TYPE\_INVALID",  
    "data": "BAD\_REQUEST\_ORIGINAL\_INVOICE\_TYPE\_INVALID"  
}

**Lưu ý:** 

1. Dữ liệu hóa đơn gốc lưu vào cột instance\_file\_name trong bảng invoice như sau: 

Loại hóa đơn | Mẫu hóa đơn | Ký hiệu hóa đơn | Số hóa đơn

trong đó:

\- Loại hóa đơn là giá trị thẻ originalInvoiceType 

\- Mẫu hóa đơn là giá trị thẻ originalTemplateCode 

2. Nếu người dùng truyền giá trị 0 hoặc “0” cho tham số validation trong phần generalInvoiceInfo thì các thông tin được truyền trong phần itemInfo, taxBreakdowns, summarizeInfo sẽ được giữ nguyên mà không thực hiện kiểm tra ràng buộc và tính toán lại.

**Output**:

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| errorCode | DataType: String | Mã lỗi nếu có, không có lỗi thì trả về null |
| description | DataType: String | Mô tả chi tiết lỗi |
| hashString | DataType: String | Chuỗi Hash trả về của hóa đơn, dạng Base64 |

31. **Phát hành/thay thế/điều chỉnh cho CLOUD CA (Bước 2: Ký Cloud CA và sinh hóa đơn)**

\- Thực hiện sử dụng CLOUD CA để ký chuỗi hashString nhận được từ API trong bước 7.31. Lấy chuỗi ký để sinh hóa đơn.

* **Đầu vào:**

- Action (POST):  InvoiceAPI/InvoiceWS/createInvoiceUsbTokenInsertSignature

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web hoặc Authorization: username/pass như đăng nhập trên web

\+ Content-Type: application/json

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required : true DataType: String Minlength :   Maxlength : 20 Format : \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 |
| templateCode | Required : true DataType: String Minlength :  Maxlength : 20 | Mã mẫu hóa đơn.   |
| hashString | Required : true DataType: String | Chuỗi Hash mà dữ liệu trả về ở trong request getHash phía bên trên \= out put của API : 7.15 Lập hóa đơn ký USB Token (Bước 1: Lấy chuỗi hash) |
| signature | Required : true DataType: String | Chữ ký sau khi hashString đã được ký bởi USB token. dạng Base64 |

Vị dụ Json  
**{**  
  **"supplierTaxCode": "0100109106-712",**  
  **"templateCode": "01GTKT0/002",**  
  **"hashString": "0HFm34vX525V3Syg5EwdTnfO21s=",**  
  **"signature": "U0WpJk2Q/rDsnZDz8hiWKvs6QEf5DHTG8JyXjjNMtggZ/MIDP0hn9Mutc2uPZEOxqk2YnMjuRSxU8ST/T+C5i46Vb/0+7uIfzKpPm2yrsOSivCdzr6FrY6nJPkfkOWEdEs/hqDzcf4Vn8ZCVkNfovYR4prPGc7kNpO21sNb9BAI="**  
**}**

Kết quả trả về

* Dữ liệu về thông tin về hóa đơn đã lập0

  **{**

    "errorCode": ""**,**

    "description": ""**,**

    "result": **{**

      "supplierTaxCode": 0100109106-712**,**

      "invoiceNo": AA**/**20E0000018**,**

      "transactionID": 12523522245**,**

      "reservationCode": AXHBNK8I0H

    **}**

  **}**

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null nếu lập hóa đơn thành công) |
| description | Mô tả lỗi (giá trị là null nếu lập hóa đơn thành công) |
| supplierTaxCode | Mã số thuế người bán (doanh nghiệp phát hành hóa đơn) |
| invoiceNo | Số hóa đơn vd: AA\\20E0000001  |
| transactionID | Id của giao dịch |
| reservationCode | Mã số bí mật dùng để khách hàng tra cứu |

Tham khảo thêm tại [https://sinvoice.viettel.vn/download/soft/signhash.rar](https://sinvoice.viettel.vn/download/soft/signhash.rar)

**Lưu ý:** Nếu là lập hóa đơn máy tính tiền thì respond trả về có cả thông tin Mã CQT cấp: "codeOfTax", nếu không phải hóa đơn máy tính tiền thì trả về codeOfTax \= null

## **7.32 Phát hành hóa đơn có mã bí mật cho CLOUD CA**

\- Mô tả chung: Yêu cầu này thực hiện thêm mới API cho phép người dùng lập hóa đơn có mã số bí mật

\- Đường dẫn API lấy chuỗi hash: InvoiceAPI/InvoiceWS/createInvoiceUsbTokenGetHash/{supplierTaxCode}

\- Đường dẫn API ký và sinh hóa đơn: 

InvoiceAPI/InvoiceWS/createInvoiceUsbTokenInsertSignature

*\- Nội dung tương tự như phần lập hóa đơn mã số bí mật server **mục 7.2***  
**Lưu ý:**

Nếu người dùng truyền giá trị 0 hoặc “0” cho tham số validation trong phần generalInvoiceInfo thì các thông tin được truyền trong phần itemInfo, taxBreakdowns, summarizeInfo sẽ được giữ nguyên mà không thực hiện kiểm tra ràng buộc và tính toán lại.

## **7.33 Gửi email hóa đơn cho phép truyền email khách hàng**

**\-** Mô tả chung: API gửi email hóa đơn cho khách hàng dùng cho máy POS, không check cấu hình gửi email các loại hóa đơn (Quản lý hệ thống \> Cấu hình doanh nghiệp \> Email \> Cấu hình gửi Mail)

* **Đầu vào:**

\- Đường dẫn: api[/InvoiceAPI/](https://10.60.108.210:8273/InvoiceAPI/InvoiceWS/createBatchInvoice/0100109106)InvoiceUtilsWS/sendEmailToCustomer

\- Method: POST

\- Headers:

\+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web hoặc Authorization: username/pass như đăng nhập trên web  
\+ Content-Type : application/json

* Các tham số sendEmailToCustomer

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required : true DataType: String Minlength :  Maxlength : 20 Format : \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 |
| transactionUuid | Required : true DataType: String | Key request, transactionUuid tương ứng với 1 hoá đơn (Validate độ dài transactionUuid trong khoảng 10 – 36 ký tự). |
| buyerEmail | Required: true DataType: String Maxlength: 500 | Email khách hàng cần gửi hóa đơn. Các Email cách nhau bởi dấu “;” |

Vị dụ mẫu và các trường dữ liệu:

- JSON:

  {

  	"supplierTaxCode": "0100109106-712s",

  	"transactionUuid": "idtest9999999999 ",

  	“buyerEmail”: “EmailKhachHang1@abc.xyz;EmailKhachHang2@abc.xyz;””

  }


* **Đầu ra:**

  Đối tượng Response với HTTPStatus và output Entity.

| Tên trường | Mô tả |
| ----- | ----- |
| code | Mã lỗi (giá trị là “200” không có lỗi gì xảy ra) |
| message | Mô tả lỗi (giá trị là “OK” không có lỗi gì xảy ra) |
| data | Mô tả dữ liệu (giá trị là null không có lỗi gì xảy ra) |

* **Bộ mã lỗi:**


| STT | MÃ LỖI | NỘI DUNG LỖI | DATA | Hướng dẫn xử lý |
| :---: | ----- | ----- | ----- | ----- |
| 1 | BAD\_REQUEST | TAX\_CODE\_INVALID | Mã số thuế không hợp lệ | Kiểm tra lại Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. |
| 2 | BAD\_REQUEST | TRANSACTION\_UUID\_REQUIRED | Transaction Uuid là bắt buộc | Truyền transactionUuid. |
| 3 | BAD\_REQUEST | TAX\_CODE\_REQUIRED | Mã số thuế bắt buộc nhập. | Truyền Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. |
| 4 | BAD\_REQUEST | BUYER\_EMAIL\_REQUIRED | Email khách hàng bắt buộc nhập. | Truyền Email khách hàng. |
| 5 | BAD\_REQUEST | NOT\_FOUND\_DATA | Không tìm thấy bản ghi. | Kiểm tra transactionUuid truyền vào. |
| 6 | BAD\_REQUEST | BUYER\_EMAIL\_ADDRESS\_FORMAT | Email không đúng định dạng. | Kiểm tra lại Email khách hàng khi truyền vào. |
| 7 | BAD\_REQUEST | EMAIL\_CONFIG\_NOT\_ACTIVE | Cấu hình Email ngừng hoạt động. | Chuyển Cấu hình Email sang Hoạt động trong Quản lý hệ thống \> Cấu hình doanh nghiệp \> Email. |
| 8 |  BAD\_REQUEST | EMAIL\_NOT\_CONFIG | Chưa cấu hình Email. | Cấu hình Email trong Quản lý hệ thống \> Cấu hình doanh nghiệp \> Email. |

## **7.34 Lập hóa đơn xăng dầu nháp**

* **Đầu vào:**

Webservice dùng để lưu dữ liệu hóa đơn nháp lên hệ thống SInvoice. Các hóa đơn nháp này không có số hóa đơn hay kí số, chỉ có thể xem/phát hành trên website của SInvoice. Khi phát hành thì các số hóa đơn sẽ không được cập nhật lại phần mềm tích hợp.

- Action (POST): InvoiceAPI/InvoiceWS/createOrUpdateInvoiceDraftForFuel/{supplierTaxCode}

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web

  \+ Content-Type : application/json 

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required: true DataType: String Minlength:  Maxlength: 20 Format: \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 |

- Data: Định dạng JSON

- Thông số dữ liệu truyền vào tương tự phần Lập hóa đơn (Tham khảo json tại phần 7.2). Trong thông tin hàng hóa bổ sung trường đơn giá đã bao gồm thuế:

| Tên trường | Kiểu dữ liệu | Mô tả |
| :---- | :---- | :---- |
| unitPriceWithTax | Required: false DataType: BigDecimal Minlength:  Maxlength:  Format: \[0-9.\]+ | Đơn giá của hàng hóa bao gồm thuế.  Được sử dụng trong API lập hóa đơn nháp cho xăng dầu |

- Đơn giá của hàng hóa sẽ được tính từ đơn giá của hàng hóa đã bao gồm thuế nếu đơn giá hàng hóa đã bao gồm thuế được truyền.

- Tổng tiền trước thuế của hàng hóa sẽ được tính từ tổng tiền đã bao gồm thuế của hàng hóa nếu tổng tiền đã bao gồm thuế của hàng hóa được truyền.

- Ví dụ JSON đầu vào: ![][image43]

* **Đầu ra:**

Đối tượng Response mô tả trạng thái lỗi Webservice trả về và đối tượng dữ liệu Webservice trả về:

* Dữ liệu về thông tin về hóa đơn nháp lập thành công

  **{**

    "errorCode": ""**,**

    "description": ""**,**

    "result": **{**    

    **}**

  **}**

Mô tả

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null nếu lập hóa đơn thành công) |
| description | Mô tả lỗi (giá trị là null nếu lập hóa đơn thành công) |

**Lưu ý:**

Nếu người dùng truyền giá trị 0 hoặc “0” cho tham số validation trong phần generalInvoiceInfo thì các thông tin được truyền trong phần itemInfo, taxBreakdowns, summarizeInfo sẽ được giữ nguyên mà không thực hiện kiểm tra ràng buộc và tính toán lại.

**7.35 Tra cứu hóa đơn trả về chứa thông tin hàng hóa**

\- Mô tả chung: Yêu cầu này thực hiện thay đổi dữ liệu trả về. Thêm trường listProduct, fileName, buyerUnitName, buyerCode, buyerAddress, exchangeRate và listInfoUpdate so với API 7.6. Tra cứu hóa đơn.

\- Đường dẫn API: 

InvoiceAPI/InvoiceUtilsWS/getAllInvoices/{supplierTaxCode}

- Headers:

\+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web 

\+ Content-Type : application/json 

**Input:**

Giữ nguyên như hiện tại

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required : false DataType: String Minlength :  Maxlength : 20 Format : \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 |
| GetInvoiceInput | Object | Đối tượng gồm các trường dữ liệu tham số |

\- Các tham số của đối tượng GetInvoiceInput

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | :---- | ----- |
| invoiceNo | Required : false DataType: String Minlength : 7 Maxlength : 35 Format :  \[a-zA-Z0-9\]\*$ | Là ký hiệu hóa đơn \+ số hóa đơn vd : AA/20E0000001  |
| startDate | Required : true DataType: Date Minlength :  Maxlength : 50 Format : | Ngày lập từ ngày Định dạng "2019-05-12"  |
| endDate | Required : true DataType: Date Minlength :  Maxlength : 50 Format : | Ngày lập đến ngày Định dạng "2019-05-12"  |
| invoiceType | Required : false DataType: String Minlength :  Maxlength :  Format :  | Loại hóa đơn, là một trong các giá trị Thông tư 32: 01GTKT, 02GTTT, 03XKNB,  04HGDL, 07KPTQ Thông tư 78: 1, 2, 3, 4, 5, 6 |
| rowPerPage | Required : true DataType: Number Min : 1 Max:  | Số dòng trên một trang  |
| pageNum | Required : true DataType: Number Min : 0 Max | Chỉ số trang |
| buyerTaxCode | Required : false DataType: String Minlength :  Maxlength : 20 | Mã số thuế của khách hàng  |
| buyerIdNo | Required : false DataType: String | Số giấy tờ của khách hang  |
| templateCode | Required : false DataType: String Minlength :  Maxlength :  | Mã mẫu hóa đơn.  |
| invoiceSeri | Required : false DataType: String Minlength :  Maxlength : 25 Format : \[a-zA-Z0-9\]\*$ | Ký hiệu hóa đơn  |
| getAll | Required : false DataType: Boolean Minlength:  Maxlength:  Format : true/false | Cho phép tra cứu thông tin hóa đơn của toàn doanh nghiệp đối với user của công ty mẹ. Các giá trị là true/false |
| issueStartDate | Required: false DataType: Date Minlength:  Maxlength: 50 Format: | Ngày phát hành từ ngày Định dạng "2019-05-12"  |
| issueEndDate | Required: false DataType: Date Minlength:  Maxlength: 50 Format: | Ngày phát hành đến ngày Định dạng "2019-05-12"  |
| adjustmentType | Required: false DataType: String Minlength:  Maxlength: 1 Format: | Trạng thái điều chỉnh hóa đơn:  1: Hóa đơn gốc (hóa đơn đã phát hành, hóa đơn bị điều chỉnh, hóa đơn bị thay thế) 3: Hóa đơn thay thế  5: Hóa đơn điều chỉnh thông tin 7: Hóa đơn xóa bỏ 9: Hóa đơn điều chỉnh tiền Không truyền sẽ trả tất cả |

Ví dụ gửi dữ liệu với JSON:  
{  
    "supplierTaxCode": "0200572621",  
    "startDate": "2023-10-20",  
    "endDate": "2023-12-24",  
    "rowPerPage": 1,  
    "pageNum": 1  
}

**Output:**

{

    "errorCode": **null**,

    "description": **null**,

    "totalRows": 1,

    "invoices": \[

        {

            "invoiceId": 64959023,

            "invoiceType": "5",

            "adjustmentType": "1",

            "templateCode": "5/010",

            "invoiceSeri": "K24GHY",

            "invoiceNumber": "0000001",

            "invoiceNo": "K24GHY1",

            "currency": "VND",

            "total": 60500000.000000000,

            "issueDate": **null**,

            "issueDateStr": "2024-03-14T03:17:59Z",

            "state": 1,

            "requestDate": **null**,

            "description": **null**,

            "buyerIdNo": "123",

            "stateCode": 1,

            "subscriberNumber": **null**,

            "paymentStatus": 1,

            "viewStatus": **null**,

            "downloadStatus": **null**,

            "exchangeStatus": 0,

            "numOfExchange": **null**,

            "createTime": **null**,

            "contractId": **null**,

            "contractNo": "0123",

            "supplierTaxCode": "0100109106-990",

            "buyerTaxCode": "0100109106",

            "totalBeforeTax": 55000000.000000000,

            "taxAmount": 5500000.000000000,

            "taxRate": **null**,

            "paymentMethod": "3",

            "paymentTime": **null**,

            "customerId": **null**,

            "no": **null**,

            "paymentStatusName": "Đã thanh toán",

            "buyerName": "Khánh Linh",

            "transactionUuid": **null**,

            "originalInvoiceId": "K22THY32",

             "errorCode": "INVOICE\_NO\_CODE\_APPROVED",

    "errorDescription": **null**,

            "listProduct": "{\\"itemInfo\\":\[{\\"selection\\":1,\\"lineNumber\\":1,\\"itemCode\\":\\"02\\",\\"itemName\\":\\"Tên hàng hóa\\",\\"unitCode\\":null,\\"unitName\\":\\"chiếc\\",\\"unitPrice\\":55000000,\\"quantity\\":1,\\"itemTotalAmountWithoutVat\\":55000000.000000,\\"itemTotalAmountWithVat\\":60500000.00,\\"itemTotalAmountAfterDiscount\\":55000000.000000,\\"itemServiceChargePercentage\\":null,\\"itemServiceChargeAmount\\":0.00000,\\"itemExciseTaxPercentage\\":null,\\"itemExciseTaxAmount\\":0.00000,\\"vatPercentage\\":10,\\"vatAmount\\":5500000.00000,\\"discount\\":null,\\"discount2\\":null,\\"itemDiscount\\":null,\\"itemNote\\":null,\\"batchNo\\":null,\\"expDate\\":null,\\"isIncreaseItem\\":null,\\"adjustRatio\\":null}\],\\"invoiceTaxBreakdowns\\":\[{\\"vatPercentage\\":10,\\"vatTaxableAmount\\":55000000.000000,\\"vatTaxAmount\\":5500000.00000,\\"isIncreaseItem\\":null}\]}",

            "fileName": **null**,

            "buyerUnitName": "Công ty VTT",

            "buyerCode": **null**,

            "buyerAddress": "Hà Nội",

            "exchangeRate": 1.00,

            "listInfoUpdate": "\[{\\"invoiceCustomFieldId\\":0,\\"keyTag\\":\\"gioitinh\\",\\"keyLabel\\":\\"Giới tính\\",\\"dateValue\\":null,\\"stringValue\\":\\"Giới tính\\",\\"numberValue\\":null,\\"valueType\\":\\"1\\",\\"isRequired\\":false,\\"isSeller\\":false,\\"required\\":false,\\"seller\\":false},{\\"invoiceCustomFieldId\\":0,\\"keyTag\\":\\"ngaysinh\\",\\"keyLabel\\":\\"Ngày sinh\\",\\"dateValue\\":\\"2024-03-07T17:00:00.000Z\\",\\"stringValue\\":null,\\"numberValue\\":null,\\"valueType\\":\\"3\\",\\"isRequired\\":false,\\"isSeller\\":false,\\"required\\":false,\\"seller\\":false},{\\"invoiceCustomFieldId\\":0,\\"keyTag\\":\\"maqg\\",\\"keyLabel\\":\\"Mã quốc gia\\",\\"dateValue\\":null,\\"stringValue\\":\\"Mã quốc gia\\",\\"numberValue\\":null,\\"valueType\\":\\"1\\",\\"isRequired\\":false,\\"isSeller\\":false,\\"required\\":false,\\"seller\\":false},{\\"invoiceCustomFieldId\\":0,\\"keyTag\\":\\"sodkpt\\",\\"keyLabel\\":\\"Số đăng ký phương tiện\\",\\"dateValue\\":null,\\"stringValue\\":\\"Số đăng ký phương tiện\\",\\"numberValue\\":null,\\"valueType\\":\\"1\\",\\"isRequired\\":false,\\"isSeller\\":false,\\"required\\":false,\\"seller\\":false},{\\"invoiceCustomFieldId\\":0,\\"keyTag\\":\\"soghe\\",\\"keyLabel\\":\\"Số ghế\\",\\"dateValue\\":null,\\"stringValue\\":\\"Số ghế\\",\\"numberValue\\":null,\\"valueType\\":\\"1\\",\\"isRequired\\":false,\\"isSeller\\":false,\\"required\\":false,\\"seller\\":false},{\\"invoiceCustomFieldId\\":0,\\"keyTag\\":\\"giotc\\",\\"keyLabel\\":\\"Giờ tàu chạy\\",\\"dateValue\\":null,\\"stringValue\\":\\"Giờ tàu chạy\\",\\"numberValue\\":null,\\"valueType\\":\\"1\\",\\"isRequired\\":false,\\"isSeller\\":false,\\"required\\":false,\\"seller\\":false},{\\"invoiceCustomFieldId\\":0,\\"keyTag\\":\\"ngaydi\\",\\"keyLabel\\":\\"Ngày đi\\",\\"dateValue\\":\\"2024-03-07T17:00:00.000Z\\",\\"stringValue\\":null,\\"numberValue\\":null,\\"valueType\\":\\"3\\",\\"isRequired\\":false,\\"isSeller\\":false,\\"required\\":false,\\"seller\\":false}\]"

        }

    \]

}

Đối tượng Response với HTTPStatus và output  Entity.

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null lấy hóa đơn thành công) |
| description | Mô tả lỗi (giá trị là null lấy hóa đơn thành công) |
| List\<InvoiceBean\> | Danh sách các bản ghi hóa đơn thỏa mãn điều kiện   |

## **7.36 Gửi hóa đơn sang CQT bằng transactionUuid**

       \-     Mô tả chung: API gửi hóa đơn cho cơ quan thuế  

* **Đầu vào:**

- Action (POST):  *InvoiceAPI/InvoiceWS/sendInvoiceByTransactionUuid*

- Headers:

  \+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web

  \+ Content-Type : application/x-www-form-urlencoded


| Tên trường | Kiểu dữ liệu, ràng buộc | Dữ liệu/mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required: true DataType: String Minlength:  Maxlength: 20 Format: \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 |
| transactionUuid | Required: true DataType: String | Danh sách key request, mỗi transactionUuid tương ứng với 1 hoá đơn (Validate độ dài transactionUuid trong khoảng 10 – 36 ký tự). Các transactionUuid cách nhau bởi dấu “,” |
| startDate | Required: true DataType: Date Minlength:  Maxlength: 50 Format: | Ngày lập từ ngày Định dạng "2019-05-12"  |
| endDate | Required: true DataType: Date Minlength:  Maxlength: 50 Format: | Ngày lập đến ngày Định dạng "2019-05-12"  |

Ví dụ với định dạng formParam:

![][image44]

Hình ảnh Response trả về thành công

![][image45]

- Ouput:

  * Lỗi chung do dữ liệu đầu vào:

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| :---- | :---- | ----- |
| code | DataType: String | Loại lỗi |
| message | DataType: String | Mã lỗi |
| data | DataType: String | Mô tả lỗi |

Ví dụ:

{

    "code": 400,

    "message": "START\_DATE\_INVALID",

    "data": "Ngày bắt đầu không hợp lệ"

}

* Lỗi khi check quyền:

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| :---- | :---- | ----- |
| error | DataType: String | Loại lỗi |
| error\_description | DataType: String | Mã lỗi |

Ví dụ:

\<InvalidTokenException\>

    \<error\>invalid\_token\</error\>

    \<error\_description\>Access token expired: xxx\</error\_description\>

\</InvalidTokenException\>

* Lỗi khi gửi hóa đơn sang CQT bị lỗi:

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| :---- | :---- | ----- |
| total | DataType: String | Tổng số hóa đơn |
| success | DataType: String | Số hóa đơn thành công |
| fail | DataType: String | Số hóa đơn không thành công |
| errorlist | DataType: array | Mảng data |
| errorlist.transactionUuid | DataType: String | Danh sách transactionUuid có cùng mã lỗi |
| errorlist.detail | DataType: String | Mô tả lỗi |
| errorlist.message | DataType: String | Mã lỗi |

Ví dụ trường hợp không có dữ liệu gửi sang CQT:

{

    "errorCode": null,

    "description": null,

    "total": "3",

    "success": "1",

    "fail": "2",

    "errorlist": \[

        {

            "transactionUuid": "028717bc-5315-4a0b-9ab0-ce8d5495e56g,028717bc-5315-4a0b-9ab0-ce8d5495e57f",

            "detail": "Không tìm thấy bản ghi cần gửi sang CQT",

            "message": "INVOCIE\_NOT\_FOUND"

        }

    \]

}

Ví dụ trường hợp gửi dữ liệu sang CQT thành công, có dữ liệu không thành công:

{

    "errorCode": null,

    "description": null,

    "total": "3",

    "success": "1",

    "fail": "2",

    "errorlist": \[

        {

            "transactionUuid": "028717bc-5315-4a0b-9ab0-ce8d5495e56f",

            "detail": "Hóa đơn xóa bỏ không gửi thuế",

            "message": "INVOCIE\_NOT\_SEND\_CQT"

        },

        {

            "transactionUuid": "028717bc-5315-4a0b-9ab0-ce8d5495e56g",

            "detail": "Không tìm thấy bản ghi cần gửi sang CQT",

            "message": "INVOCIE\_NOT\_FOUND"

        }

    \]

}

Ví dụ trường hợp gửi dữ liệu sang CQT thành công:

{

    "errorCode": null,

    "description": null,

    "total": "2",

    "success": "2",

    "fail": "0",

    "errorlist": \[\]

}

- Ví dụ cho phần đầu vào gọi API:

curl \--location 'http://localhost:8080/api/InvoiceAPI/InvoiceWS/sendInvoiceByTransactionUuid' \\

\--header 'Content-Type: application/x-www-form-urlencoded' \\

\--header 'Authorization: Bearer XXX \\

\--data-urlencode 'supplierTaxCode=0100109106-710' \\

\--data-urlencode 'transactionUuid=028717bc-5315-4a0b-9ab0-ce8d5495e56e' \\

\--data-urlencode 'startDate=2023-10-10' \\

\--data-urlencode 'endDate=2024-10-10' 

**7.37 Tra cứu hóa đơn trả về chứa thông tin hàng hóa (UTC \+ 7\)**

\- Mô tả chung: Yêu cầu này thực hiện nâng cấp API 7.37 dữ liệu trả về trường “issueDateStr” trả về đúng thời gian phát hành hóa đơn (có nghĩa là UTC \+ 7\)

\- Đường dẫn API: 

InvoiceAPI/InvoiceUtilsWS/getInvoicesAll/{supplierTaxCode}

- Headers:

\+ Cookie: giá trị access\_token hoặc Authorization: username/pass như đăng nhập trên web 

\+ Content-Type : application/json 

**Input:**

Giữ nguyên như hiện tại

| Tên trường | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | ----- | ----- |
| supplierTaxCode | Required : false DataType: String Minlength :  Maxlength : 20 Format : \[0-9-\]+ | Mã số thuế của doanh nghiệp/chi nhánh phát hành hóa đơn. Một doanh nghiệp có thể có nhiều mã số thuế Mẫu 1: 0312770607  Mẫu 2: 0312770607-001 |
| GetInvoiceInput | Object | Đối tượng gồm các trường dữ liệu tham số |

\- Các tham số của đối tượng GetInvoiceInput

| Tên tham số | Kiểu dữ liệu, ràng buộc | Mô tả |
| ----- | :---- | ----- |
| invoiceNo | Required : false DataType: String Minlength : 7 Maxlength : 35 Format :  \[a-zA-Z0-9\]\*$ | Là ký hiệu hóa đơn \+ số hóa đơn vd : AA/20E0000001  |
| startDate | Required : true DataType: Date Minlength :  Maxlength : 50 Format : | Ngày lập từ ngày Định dạng "2019-05-12"  |
| endDate | Required : true DataType: Date Minlength :  Maxlength : 50 Format : | Ngày lập đến ngày Định dạng "2019-05-12"  |
| invoiceType | Required : false DataType: String Minlength :  Maxlength :  Format :  | Loại hóa đơn, là một trong các giá trị Thông tư 32: 01GTKT, 02GTTT, 03XKNB,  04HGDL, 07KPTQ Thông tư 78: 1, 2, 3, 4, 5, 6 |
| rowPerPage | Required : true DataType: Number Min : 1 Max:  | Số dòng trên một trang  |
| pageNum | Required : true DataType: Number Min : 0 Max | Chỉ số trang |
| buyerTaxCode | Required : false DataType: String Minlength :  Maxlength : 20 | Mã số thuế của khách hàng  |
| buyerIdNo | Required : false DataType: String | Số giấy tờ của khách hang  |
| templateCode | Required : false DataType: String Minlength :  Maxlength :  | Mã mẫu hóa đơn.  |
| invoiceSeri | Required : false DataType: String Minlength :  Maxlength : 25 Format : \[a-zA-Z0-9\]\*$ | Ký hiệu hóa đơn  |
| getAll | Required : false DataType: Boolean Minlength:  Maxlength:  Format : true/false | Cho phép tra cứu thông tin hóa đơn của toàn doanh nghiệp đối với user của công ty mẹ. Các giá trị là true/false |
| issueStartDate | Required: false DataType: Date Minlength:  Maxlength: 50 Format: | Ngày phát hành từ ngày Định dạng "2019-05-12"  |
| issueEndDate | Required: false DataType: Date Minlength:  Maxlength: 50 Format: | Ngày phát hành đến ngày Định dạng "2019-05-12"  |
| adjustmentType | Required: false DataType: String Minlength:  Maxlength: 1 Format: | Trạng thái điều chỉnh hóa đơn:  1: Hóa đơn gốc (hóa đơn đã phát hành, hóa đơn bị điều chỉnh, hóa đơn bị thay thế) 3: Hóa đơn thay thế  5: Hóa đơn điều chỉnh thông tin 7: Hóa đơn xóa bỏ 9: Hóa đơn điều chỉnh tiền Không truyền sẽ trả tất cả |

Ví dụ gửi dữ liệu với JSON:  
{  
    "supplierTaxCode": "0200572621",  
    "startDate": "2023-10-20",  
    "endDate": "2023-12-24",  
    "rowPerPage": 1,  
    "pageNum": 1  
}

**Output:**

{

    "errorCode": **null**,

    "description": **null**,

    "totalRows": 1,

    "invoices": \[

        {

            "invoiceId": 64959023,

            "invoiceType": "5",

            "adjustmentType": "1",

            "templateCode": "5/010",

            "invoiceSeri": "K24GHY",

            "invoiceNumber": "0000001",

            "invoiceNo": "K24GHY1",

            "currency": "VND",

            "total": 60500000.000000000,

            "issueDate": **null**,

            "issueDateStr": "2024-03-14T03:17:59Z",

            "state": 1,

            "requestDate": **null**,

            "description": **null**,

            "buyerIdNo": "123",

            "stateCode": 1,

            "subscriberNumber": **null**,

            "paymentStatus": 1,

            "viewStatus": **null**,

            "downloadStatus": **null**,

            "exchangeStatus": 0,

            "numOfExchange": **null**,

            "createTime": **null**,

            "contractId": **null**,

            "contractNo": "0123",

            "supplierTaxCode": "0100109106-990",

            "buyerTaxCode": "0100109106",

            "totalBeforeTax": 55000000.000000000,

            "taxAmount": 5500000.000000000,

            "taxRate": **null**,

            "paymentMethod": "3",

            "paymentTime": **null**,

            "customerId": **null**,

            "no": **null**,

            "paymentStatusName": "Đã thanh toán",

            "buyerName": "Khánh Linh",

            "transactionUuid": **null**,

            "originalInvoiceId": "K22THY32",

             "errorCode": "INVOICE\_HAS\_CODE\_APPROVED",

    "errorDescription": **null**,

            "listProduct": "{\\"itemInfo\\":\[{\\"selection\\":1,\\"lineNumber\\":1,\\"itemCode\\":\\"02\\",\\"itemName\\":\\"Tên hàng hóa\\",\\"unitCode\\":null,\\"unitName\\":\\"chiếc\\",\\"unitPrice\\":55000000,\\"quantity\\":1,\\"itemTotalAmountWithoutVat\\":55000000.000000,\\"itemTotalAmountWithVat\\":60500000.00,\\"itemTotalAmountAfterDiscount\\":55000000.000000,\\"itemServiceChargePercentage\\":null,\\"itemServiceChargeAmount\\":0.00000,\\"itemExciseTaxPercentage\\":null,\\"itemExciseTaxAmount\\":0.00000,\\"vatPercentage\\":10,\\"vatAmount\\":5500000.00000,\\"discount\\":null,\\"discount2\\":null,\\"itemDiscount\\":null,\\"itemNote\\":null,\\"batchNo\\":null,\\"expDate\\":null,\\"isIncreaseItem\\":null,\\"adjustRatio\\":null}\],\\"invoiceTaxBreakdowns\\":\[{\\"vatPercentage\\":10,\\"vatTaxableAmount\\":55000000.000000,\\"vatTaxAmount\\":5500000.00000,\\"isIncreaseItem\\":null}\]}",

            "fileName": **null**,

            "buyerUnitName": "Công ty VTT",

            "buyerCode": **null**,

            "buyerAddress": "Hà Nội",

            "exchangeRate": 1.00,

            "listInfoUpdate": "\[{\\"invoiceCustomFieldId\\":0,\\"keyTag\\":\\"gioitinh\\",\\"keyLabel\\":\\"Giới tính\\",\\"dateValue\\":null,\\"stringValue\\":\\"Giới tính\\",\\"numberValue\\":null,\\"valueType\\":\\"1\\",\\"isRequired\\":false,\\"isSeller\\":false,\\"required\\":false,\\"seller\\":false},{\\"invoiceCustomFieldId\\":0,\\"keyTag\\":\\"ngaysinh\\",\\"keyLabel\\":\\"Ngày sinh\\",\\"dateValue\\":\\"2024-03-07T17:00:00.000Z\\",\\"stringValue\\":null,\\"numberValue\\":null,\\"valueType\\":\\"3\\",\\"isRequired\\":false,\\"isSeller\\":false,\\"required\\":false,\\"seller\\":false},{\\"invoiceCustomFieldId\\":0,\\"keyTag\\":\\"maqg\\",\\"keyLabel\\":\\"Mã quốc gia\\",\\"dateValue\\":null,\\"stringValue\\":\\"Mã quốc gia\\",\\"numberValue\\":null,\\"valueType\\":\\"1\\",\\"isRequired\\":false,\\"isSeller\\":false,\\"required\\":false,\\"seller\\":false},{\\"invoiceCustomFieldId\\":0,\\"keyTag\\":\\"sodkpt\\",\\"keyLabel\\":\\"Số đăng ký phương tiện\\",\\"dateValue\\":null,\\"stringValue\\":\\"Số đăng ký phương tiện\\",\\"numberValue\\":null,\\"valueType\\":\\"1\\",\\"isRequired\\":false,\\"isSeller\\":false,\\"required\\":false,\\"seller\\":false},{\\"invoiceCustomFieldId\\":0,\\"keyTag\\":\\"soghe\\",\\"keyLabel\\":\\"Số ghế\\",\\"dateValue\\":null,\\"stringValue\\":\\"Số ghế\\",\\"numberValue\\":null,\\"valueType\\":\\"1\\",\\"isRequired\\":false,\\"isSeller\\":false,\\"required\\":false,\\"seller\\":false},{\\"invoiceCustomFieldId\\":0,\\"keyTag\\":\\"giotc\\",\\"keyLabel\\":\\"Giờ tàu chạy\\",\\"dateValue\\":null,\\"stringValue\\":\\"Giờ tàu chạy\\",\\"numberValue\\":null,\\"valueType\\":\\"1\\",\\"isRequired\\":false,\\"isSeller\\":false,\\"required\\":false,\\"seller\\":false},{\\"invoiceCustomFieldId\\":0,\\"keyTag\\":\\"ngaydi\\",\\"keyLabel\\":\\"Ngày đi\\",\\"dateValue\\":\\"2024-03-07T17:00:00.000Z\\",\\"stringValue\\":null,\\"numberValue\\":null,\\"valueType\\":\\"3\\",\\"isRequired\\":false,\\"isSeller\\":false,\\"required\\":false,\\"seller\\":false}\]"

        }

    \]

}

Đối tượng Response với HTTPStatus và output Entity.

| Tên trường | Mô tả |
| ----- | ----- |
| errorCode | Mã lỗi (giá trị là null lấy hóa đơn thành công) |
| description | Mô tả lỗi (giá trị là null lấy hóa đơn thành công) |
| List\<InvoiceBean\> | Danh sách các bản ghi hóa đơn thỏa mãn điều kiện   |

8. **Danh sách lỗi trả về của hệ thống** 

Đối tượng Response mô tả trạng thái lỗi Webservice trả về và đối tượng dữ liệu Webservice trả về. Bao gồm mã lỗi và mô tả lỗi. 

**Note:** Khi phát sinh lỗi việc đầu tiên kiểm tra mã lỗi trong danh sách lỗi để nắm được tại sao lỗi và cách khắc phục.

**Bộ mã lỗi hay gặp:**

| STT | MÃ LỖI | NỘI DUNG LỖI | DATA | Hướng dẫn xử lý |
| :---: | ----- | ----- | ----- | ----- |
| 1 | BAD\_REQUEST | VAT\_AMOUNT\_INVALID | Tiền thuế không hợp lệ | Kiểm tra lại tiền thuế, tiền thuế chỉ được lệch 1đ so với tiền thuế hệ thống tính |
| 2 | BAD\_REQUEST | VAT\_TAX\_AMOUNT\_NEGATE | Tiền thuế không được nhập giá trị âm | Mọi giá trị đều phải là số dương |
| 3 | BAD\_REQUEST | VAT\_PERCENTAGE\_INVALID | Thuế GTGT( %) không hợp lệ | Kiểm tra xem thuộc các giá trị: \-2, \-1, 0, 5, 8, 10 |
| 4 | BAD\_REQUEST | INVOICE\_SERIAL\_NOT\_FOUND | Ký hiệu hóa đơn không tồn tại | Kiểm tra lại mã mẫu và ký hiệu có ở trạng thái hoạt động không |
| 5 | BAD\_REQUEST | IVI\_TOTAL\_A\_WITHOUT\_TAX\_ AND\_UP\_QUAN\_NOT\_COMPARED | Đơn giá nhân thành tiền không so khớp | Kiểm tra lại xem thành tiền đã khớp với đơn giá nhân số lượng chưa |
| 6 | BAD\_REQUEST | JSON\_PARSE\_ERROR | Lỗi định dạng dữ liệu truyền vào | Kiểm tra lại xem đúng định dạng json chưa |
| 7 | 500 | "error": "Internal Server Error","message": "Request processing failed;  nested exception is java.lang. NullPointerException", | Request processing failed;  nested exception is java.lang.NullPointerException | Kiểm tra lại mã mẫu, ký hiệu đã truyền đúng với thông báo phát hành chưa và thông báo phát hành đấy đã ở trạng thái đang hoạt động chưa, nếu rồi thì kiểm tra lại mẫu có ở trạng thái đang hoạt động không |
| 8 | 500 | "error": "Internal Server Error",    "message": "GENERAL" | Token hết hạn | Lấy lại token mới |
| 9 |  400 | BAD\_REQUEST\_INVOICE\_NOT \_USE\_OTHER\_FEE | BAD\_REQUEST\_INVOICE\_NOT\_ USE\_OTHER\_FEE | Cài đặt cấu hình phí khác xem đủ dữ liệu chưa |
| 10 |  400 | BAD\_REQUEST\_INVALID\_ DECIMAL\_POINT\_QUANTUM | Cấu hình số thập phân | Kiểm tra lại cấu hình số thập phân |
| 11 |  400 | BAD\_REQUEST\_EXISTS\_OTHER \_USB\_SIGN\_PROCESSING | Có hóa đơn đang xử lý chưa được ký | Xóa hết nháp đã tạo r lấy chuỗi hash |

9. **Mapping giữa các trường thông tin và mẫu hóa đơn**

Các trường thông tin sẽ được mapping lên mẫu hóa đơn phụ thuộc vào thiết kế chi tiết của mẫu hóa đơn đó. Về cơ bản sẽ các mẫu hóa đơn sẽ được mapping các trường như sau:

**Lưu ý:** trong trường hợp trường thông tin không hiển thị đúng, nguyên nhân có thể do dữ liệu gửi sang chưa đúng hoặc mẫu hóa đơn thiết kế không hiển thị đúng thông tin. Kiểm tra dữ liệu trong file hóa đơn gốc (xml) tải về xem đúng chưa.

![][image46] 

10. **Kiểm tra API bằng POSTMAN**

Trước khi lập trình, các phần mềm tích hợp nên kiểm tra trước các API bằng POSTMAN để hiểu các dữ liệu cần phải truyền vào/trả về của hệ thống. Sau khi chạy thử xong, việc code sẽ nhanh hơn.

Chi tiết xem ở:

[https://sinvoice.viettel.vn/ho-tro/huong-dan-su-dung/35-huong-dan-su-dung-postman-goi-api-webservice-hoa-don-dien-tu](https://sinvoice.viettel.vn/ho-tro/huong-dan-su-dung/35-huong-dan-su-dung-postman-goi-api-webservice-hoa-don-dien-tu) 

[image1]: <data:image/png;base64,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>

[image2]: <data:image/png;base64,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>

[image3]: <data:image/png;base64,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>

[image4]: <data:image/png;base64,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>

[image5]: <data:image/png;base64,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>

[image6]: <data:image/png;base64,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>

[image7]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAApUAAAC+CAIAAADrx2MsAABXjUlEQVR4Xu19/5NtR3Gffth/4f2iX8k/kF9TiStVceIEJ6k84lspO3GKKlXkuOwyTmxYhUAiG3ONQRbGIiXW2A5YfgvIby0w2eJtOSDZyrI2T0ibaG0nhTFJgXx3JUA2T18ACZ1096e7p2fOOXe/vL3v7dXtT73ad+6cOTM9PT39mTl3pu8d3WLwhnseePjZNvEkmG29+aFL93fd0eN3XfLEa5xyXf4qHrrvern7RHf1rqszeuSZ7un7+Cl6lhKpqKctQ/fM1ael8KtbR/4gMNt80x13/EKTCOxtXAmfDqaXt+i/2fbW2uUrm1LM5voVSd+h68n2IVKm+3xNedYub03XP/sg55GPGwehtEQikUgkzo472oTzw8O//MD09ITlFCtMfIRrZ24i5ocuvVmzPnP1IaZt5vKnn7j/2hPXmcLv4rsohP5qTknxdE88FoG/Dxv2FZ4GSfM/ugaj692jgxnx+vouPaWF7O8kfycSiUTivLAQ/n72sx+l9feTbfKJIOtvImleQBP0mvj7matX5Zo429ON3Znpbb1+3dMjf1MGSn96iL/H1t/GzVtMvcbTM0vfKxl1/U2MLrd26BYtwSP08eTvRCKRSJwTjufvv/zLvzxIJBKJRCJxkXA8fycSiUQikbhoSP5OJBKJRGL5kPydSCQSicTyIfk7kUgkEonlQ8XfX00kEolEIrEMyPV3IpFIJBLLh+TvRCKRSCSWD8nfiUQikUgsH5K/E4lEIrFaePbZM/0+xwVD8ncikUgkVgvJ34lEIpFILB+SvxOJRCKRWD68/vn75Zdffte73kUXW1tb73//+9vbhi984Qtt0jiozF/7tV9rU4fw6U9/2q/vvffecGcUb/nclP4+8ORv+/W/+PS/P3zx6022MXxaQBfPP//8L/3SL7W3h/Crv/qrbdJcQKprX3ncBaPrTmSmW7g+OUiZpxIAmv+Lv/iLE+qzO30DE4nXB774xS/eK2hvnB40rv/Gr/8AxjsN/L/5W2/af/bPOhn1lB5zkhOgFE+EKzvWLUBOAsn80EMPtbdPgBvffRF1RZFIThf7ZvDSSy+RbO9+97v//M///MEHH6SPbY4eSB5SVKMc+kiJdAv6JPH8livq+z7+o67D+ZIP8/drr914+z995eDz3/70iUjK8d3d37ux/sbvPfPlGz/z91/98//Z3l4YTsrfhE6o+s477wRh4/pHfuRHviCgzJQ4h+aBhryJS+4W4COxJl2DO0Glb3nLW8gowSJ0QXfvueceusZTkeOpt2KHeY+CMk+CPn9To7wW+kvXJI+nEyAYWkF/6ZrGD8qZL2EzsaCPGKXHjtWIyN+DykEi/UUeKJ8+onXUFhebHrxbNO9KoJJRvncKqQVV0AUKTCRel/jmN79JTINrEPn73vc+XBAPecpv/MZvECdRnocffpgeAYkSP/mzEf/x8V8h7qFRT3/vuvYOclA+d0cGInW6hWtfilBOT5wDkgS8+JnPfKYTeUiSz3/+8xC4MxKFK2g4nsSgivDPRXJh3H++548/TE0AidJfTEHAo7geA0QCSLBI53SLrkkeuiZ9hocYjUsnkDaorrhOAwYFjhn6GObvrvvWT//db/+Osti3H/ngt37ib337v334tZdfeOnDbyd2f+Xp/0H/vvfcM9/6yb/9rZ/6vte+9U3kZP6+5x933/3OjfV/9OpX/uSVJz9HD9546w/QI9/7xowyv/CfJ5R+4x3/7KXfeCd9fO3Fb9FTL/7KT9A1/aXrV/70j1/+rXfxx/v+TffKd7/9yH+hEr7z+9yEF95xma+vfURFdDz8vmP4e319nUgarEwq/vEf/3G6+OEf/mG/JqsFeVMKXVP+ppAGzbr2XpneEh/AsMAcoBnQD6iCWIRoxsnyeUEsp6utn66pp+PFSeCk60QISeivU2CUs5PmONnjmkiR7pJC5ksY1980BtzU5ttcA+fvOcpxyTvjdZIT4iEbxPZsff6mu078XlQi8foGWbsTD0ja0zvhoU5Y0/k7stQgaKQ7IRHH+Ps255s4dwdt09/5i0hHw9/4C+aOnE0TC/LS8cFOiLmrXwHShYv6xq0fQzZKBE3288wHCebcDL0RHn300c6kGnxnQHXFFXYncwVXUfSZnagryhnfYYxhjL+/ffUDTOG/+wBdv/qlp7pXX6EV+fe+/pc37vnB733tS8Ti3/urr794/78lAqbElzffg6eIv4li6R8xN3288R/+CT34ylOPEtkT7776//7s1f/zRWb3f/f3XnrwZ7/7+U9/+/c+9NrLL77w7h999S+epr9E2MTfLz3wlu9e36E8r/7fPyXuf+07L7/2zSNi/e989mMsxvo/inICx/A31t/U5cTWvgonOifO9qU2luPE3JQ5Gvog4nq0C8txSndGIRKiqsHfuEss4rziaFKcHcmkfD54Wv5Ggc8LJeOv3wXtkUhx1UsXlBJfKoD2cD0mYddbf9M1pXRn5e85yomkG6cjfTKmmcfg+tv5uxPN5Po7sTogh0b0A7f2gQ98gDxhn78pA10gMyizD5A0DX84Aay/Mdh9yA+uv8GaWso4Gv6GwHgNECXsA+sH/OuL1Ak14oIW3yShczZ9RPr3ffxHT8LiRNKkOujtU5/6FBKPnfQ0bcf7VIiElxkxG/76fGj+q4sx/gZemP7r73z24zd+5vvpmhbW33vua0TVL773rhfe+Sa65qV2Day/X3vxr2l5zS/h31Zx7Xe/cO3Gz/6DV//39Rtv/Yev7D9GbP3SB/8dlfOd/36F7tJfuib+pn9UAlXNz7z22ksfehtNI6hkmjfE0iKO4W+sv7//+78fBjH2/rwTKznhF+F4VXu3vNc99v05GAUs9UV5G0x42V5f492vA7MzN0fqXbfIk8Cpy5kbFRGxUUWQ7Xd+53c8neDfKENsEN7LgjkSdoG/ISrGAIZ3zD8fcSYxphx8AYE8TsO4wPtziI1HPi2zKHQQ5fHy6Zqy/dEf/RHSUUgi8XoFmBgvyTt5TUgXxEB08clPfrKT4UYpyEY0SbfwKpg+Nu/PaUTji2SM8TN8/30SnzCfvzt7f46vn8fWu/jrtTer2D5/0wVlcL4cA/TmL/bxRUN8f47r+P486uGGfDcPwVAX5hz9779JvL/zsX/lz86fVQzy92vffulbP/V9/M78dx8gTiUqpXXwC+/6Ebom0n3xV38K323z+3PJ9srB5/Ggvj/vuhfvu5v+8fvzn/zb/J78W9945anHKCfxOi3Zb6y/8aUP/jS/eMf78w/8JF37+3Pn79eef5YW5fQ4LcTp1gv/6Z/ze/X33uVyOubx96nwTUGbemvRt6Q3bv3YSaz/lqEvYQTZ5ZwJYyKRSCTOBYP8vWjcuOcHiaTb1JvA+fA3rbyP/eY7kUgkEomLgOTvRCKRSCSWD7eFv88dyd+JRCKRWC0kfycSiUQikbg9SP5OJBKJRGL5UPE3TqCf779YfiKRSCQSiXNB8ncikUgkEsuHfH+eSCQSicTyIfk7kUgkEonlQ/J3IpFIJBLLh+TvRCKRSCSWD8nfiUQikUgsH5K/E4lEIpFYPhzP388lVgw3btxojaDrvn4x8MILL7SSnVW2tpREIpFYKiR/J1oMclvLfrcJ3/jGN1rJzipbW0oikUgsFZK/EwNojeCsHLkItJKdVba2lEQikVgqJH8nBtAawVk5chFoJTurbG0piUQisXg8+OCD99bY29trM/Xw1FNPIfP+/r4nJn8nBtAawVk5chFoJatl++v33d0P4uv/Ys62lEQikVg8iIP/a42vfOUrbaYaL7/8Msj7F3/xF+nvhz70IaQnfycG0BrB8vD3ydGWkkgkEosHETARti69a7RZBVh5x5SPfexjjz76aJf8nRhEawRn5chFoJXsrLK1pSQSicTice8p+Rvv22MKLcexBL8p/n77299+/fr1L33pSz/0Qz/U3lskHnjgAfr75JNPfvnLX27vnQeo2He/+93PSRWE9nYPi5OEWvrYY4/h+hOf+MQ73/nOk8jznIj0ta997cyCtUYwwpGPPPLIBz/4wT/8wz/0lPe+971UI11QOglAGe6//37c+u3f/m3PdjNoJRuR7Vi0pSQSicTice8p+ZvS3/Oe9/QTu3Phb7r4yEc+Qn9///d/n4ic6JwS77zzTvpLHvxOwc/93M/RX7oLXqR0PHg2gL+J2Kgcurj77rvf9ra3EW3cd999lEI8h3S6aB48IZy/n5NaqLpr166h0p8SEC9SBlAjpYMsKWeU5DkR4LwkQWNRKf1FRVQvKqK/dE21UDqJ91zgb/p7twDlkLR0jbbMQWsEIxxJ9Pybv/mbRNX4iOr8lgMZjuVvN+L2Ro1WspN///0zfz/mbEtJJBKJxePeU/L33t5ec+szn/nMU0891Z0Lf/v6G+RNAIXQX7om2viagK6RSH9B7XVhp0AkJOATAtAbCPU54bDyzGnQrL+JKUF4XzbQXdQIjgRvYfYATkWrb16S52yygr9ooM8GUNdzxt9IxHodIuGvZ4bMz51gPtEawTh/019af2PZTRfO33RN1A7+pouvn4C/qRVkpvS3vVGjlWxEtgbPP/SLuX8tkUjcdtx7Sv5++eWXH3zwwY9//OP4SItJykmJ3bnwt3+k9Tf+RmZt+JvyHxwcgMXPjEhpTkgErJV9xdw8dXLE9fdzxprPGTU6PvzhD6N20GQkRcrp8tyMJM+JMJ/61Kcif9PF2wQNf0PVff6mvySqZ6tKH0FrBCMcCf4GiKRJNiofH/FeHfyNu8fyN+Fzn/tcm9RDK9mIbH389bv+ZfzYlpJIJBKLx1cELXUL2qwBjz76KPLQxfPPP3+vUPj583fzdThW4V8LL8xpKhHZ8QwAmT0pX+46sRFfflleXNNfoisQ29kwxt/0N1I4XfsynRr41re+1dnxvCQB3vGOd6Bel+Q5mT1Qde985zvpGlXHaU3kb0rBKvwT8orCi52D1ghGONL5m6R6//vf//Wh77+Rhz5S1eHRs6OVbEQ24K8+/A5c5Po7kUhcEJyBvxsQjX7kIx+5Kf4+G4j1/aVu4mKiNYIhjqROjDvXbhlayUa+/6YL+uhffjORf+3/xZxtKYlEIrFUuNX8feedd7ZJiYuH1giG+Pt2oZXsrLK1pSQSicRS4Vbzd2Ip0BrBWTlyEWglO6tsbSmJRCKxVEj+TgygNYKzcuQi0Ep2VtnaUhKJRGKpkPydGEBrBGflyEWgleyssrWlJBKJxFIh+TvR4saNG60RnJUjzx0vvPBCK9lZZWtLSSQSiaXC8fydSCQSiUTioiH5O5FIJBKJ5UPydyKRSCQSy4fk70QikUgklg/J34lEIpFILB+SvxOJRCKRWD4kfycSiUQisXy4/fy9s7PzzPPP4B9dt7cTiUQikUgEfPKTn/yDP/iD5O9EIpFIJJYJC+TvZz/70Tdc+ZM2dQTg7w/+szsIyd+JRCKRSMzHAvmbcFr+fuOvP5Xr70QikUgkjkXydyKRSCQSy4fk70QikUgklg+L4m/+8vueB+jf9KC9NYjk70QikUgkTo5F8fdpAf6+4+2/l/ydSCQSicSxuFj8nefHEolEIpE4CS4Qf0e0txOJRCKRSARcFP5++umn26REIpFIJBIjSP5eCayt77ZJgrXLi33VMdveGqs6kUgkEjeDxfH3sw//Mu8/b5NHcCb+vn7tie7p+y61yecKqqKPE1Z69dKbH7/r0tWto/ZGADHc7Gh3c16Wbnr5yhr9W9+ddd3expWQvrMXsnGey1em+yHJ4CSKojyP8zeenWwfyqcDfKQrTTniqiNUJHuErzdw0uAAF5Az8jfy9+lc03sziQnSpTQux0RqgHRqUSMSCYB0zyNVH0x7FXVBzrXLW5tHB9Ydh/FxStxcj6IejomUSCQStwCL42/gT55sU4ZxNv5+/JlutvVmfHjo0qWHLt2vpTxxP33ENWXgW3dd9XRQETErp9933dMfuqRFKTSR/z0dypkZf1MKCdAxT2vVlCLXyu5XKfG+Sz4DuGMy4OuJOYhUQMOgHKafo92JkYRz7cT4G8TWCX9vMrFtgVo0n0AJTxnLWNNoWCo9FDaqyEyYj9PrFH0Q4tE/5fL9HSd1rs74e2+fyxT+lnlAIWznRX4WjCjwGg+m67ue7u3tVGAHJGdFxdkMw0VqJxxeNfj7EJOh6TZXp5LTLMpqwV3XkhWiQAmb65p5cMKUSCQSi8aC+fvgkWfbpGGcib97IMYlPn7mKhGnpylzEyhdrsHZytyMo8fvqpk7wNkXzM0sft915m9md9RynUWnj5Rh683SDJ5Y9DHI3xEgSxCGMlPgIeczJvuj3T1ZBPMjxIXrwvfM+rbirJe5E3wUZo0XzWJU2ZrJVVf2/fX33oZR6Rh/dwfOuyzSAH8X8rOPxt8yL0FRaO/0Mue09Tdf8wxG3xN0dTlBpP0dcDxa0fC3s75MXwpDo/xOKrUp0cB63fhbG5j8nUgkbgsWyd/PPnbC4C3dzfP3M1eZMoW/eREcXlk7ATfpjGeuOrsTJfu6OcIf12dlEkCZ+d04SPqJMlewlwFHg/x9HA7rt+iHe5SyUWg4rkexZNf358KR4LnOloMNqSiJVutvxjB/K5jzGv6eKEkLRvmbs83lbwZlMCEjf7M8kb/rNwSh1YJ2cRz4G/+jkIa/fXLjb9r5w/7OXnicZBAxDlyxjlppTa8lEonELcKi+PvJK/zlN/2767MnWoHfLH/L+/PHt2T9be+6USKIGTyNdFAyXowLK1+/pu/JCxM78D786VDOzL//fuL+pqj5/H3s+rv+erWbyCqwsxfXIK2avyW/UlT1/be+6yaikkW5vyWWaxQr79XtcVyjZP8iuSqnLIL5/Xb8stnTpWr5LkBej1PVSEfVeu2v9K1Fms6tHuBvUHIUwx8vX70Pff+N66iZ+P03XjD4s1y+6ccV6LMEZKNWo6VK2NJGm7XwrSTyRCJxK7Eo/j4tbp6/X39wbkgsCPX7hkQikVgmJH8nEolEIrF8SP5OJBKJRGL5kPydSCQSicTyIfl7OTDb3tKt0Q32qxAuidNCz+CdB/zQXYL3CY4cqztHhZ8Xbp9Ih2P18obK+gjoKuC0rR4fcaPmd16QraztydL5wOHY80Xyd+fxQNAf2GPcZvHd19hKbTvLfO83YD10iAyyI7ra7I0tysG2wvFiP2PNFyUdmQN/l+BoDONv3wTeGLTbGYvqG8LtcT/xHKCHsHGy2fOj9ol5OtMY79b2019xLzoqlX3j1pCiDd9Fz081Ig2hEqn0F7VopNW+9b0dxtgYHw6hme+uznnrVnbpRN36rk8VVfSrHvQmRYAxkTqVqjc/c7MkpfkpNbnA1vf+I5YOyU1CDhDUy69H8GthimnhWdyNrY6IJwa7uq+jA22qNoVr9DqYE1dXdmuyGHhcm9OvHS1lX18OH45xYYv9HWtXZQM+xGphLIXFaPs3asntoc7CMBPa8mONZmyFv6FkV5ozmRZb+5mS3hNJO1Ge3StHNAu0aWYqnAIl18dYXJ84kaF52NrVckiAON6RwsZZHRntYnyF9rRnHasRF5C8Ervu65lV3Y2MOMEAf9tRUlyo+VV9B6c9XLWrRSGPSCeGQdfwAp6Nli//63jpQkNIaf/LQ1SFc7kRpHZQCapDnhXj7+Io9UBwJBL34LMQ7Ssqq7Mh4S4DZ4r40iKmTbbLUWxND8eWgOk2n+ly2lhTXrd+ParyT+1klBsf0ulx+He3BvqoxhfitLDA27vss9TWwyHsIz5dxsXGqYMIjKPn7lvtATmSLqPXjIlBJdP13gafmebPwf64BBemK2M7qL2LIxxuPQ5OytmINKkHbWy1dJYKFr3w5jbfgjCUuMnn38r5sV5HKNCPKmo1u1J41cr3dhw/9gtCvPVY6mC6cQVSQaTO3ErF03Kh5ahbkY9BpdP13U2mh3B6Te4WtThM8kIntbfqL33K3dDq0kE1f3tfR1bzjib1uq+Xx9tz81qaWUjx0YFKi5IFYpnccW5+PtmCtE6KCMjTQR4eFPyxZwMdTKt0llSHutxEXeEmgBZefDGy9apmRP4Wc9VHQmAGsXBphenBHi4Wjk8u0mR9Z7pO5rSl/RVGGcxPs6FY0VIUVXSoZRbqJTPeIG0c7nlHKBW1/O1F0fXmukSRotFad4R0Ive424AolmM1ThBF0Y+5Bv6OVi164KonGweoVEYZjEFFwkU0PymEi90TnauhmjANYKvBOSu8C/zCx7vnQX4bdOJj0deiDW+15D2QoJl6HjUYgIba5L5wbcgjPmDpkWaQrhB/F9Mp7jKeIBrg75pmujJflvBnpTuZ0c04rHygniHq49ZPbMGoVGyLI5dNN3hgN/zNsBFepni19+yiyxYapmuSEK6KSUslbIOgiUhS9bqsD8h0Nng8b1rwltZ8q1hs3Fj2aFK1Rncp/K2yhbGk2hjh72qWg3SWthYpqrcLrYaVezp3t+XEoFKnKarwwWxDKHaEAlI5f2v6EH8D+qzHusHB+kBjQSQ5vr+vgxySe37qspnEsEMh8j/S2Ui8dvawRkIuP7tsqbGZ5TBUMHiugfV37dMZ5a4/G9671BbY9jUuPECeX5jCWweqpdlsxi+8E90OHXKrZ369IYNr1qSwhej8cMgGJJuZkNqeofA3ngozlUrPeB8WpzuR9tr1t+k8TLi1vWEeo7dC5wKBv9n7+4D1Zy2/hmRAZh6wcUrBKPxd5iW6imCZUewgf2sB0moR9QCzbSS7tKKo0hB7kAUTH2XD1p5t2BF+xnXoVXsPUgaMmmmvavf58LHTjeo9jVsXKTM6Z1e1Vc2oLbA4q0p+mafiEw+T7aINS7eRIjm9y2Y2Zl28qStcOgtLppi/WzX+jj0HYgtj71j+rpaJ/ErTXBKzi5ZMDH1Qsu3zyiAimohUp5XqCNzf3dw/nM3lb7eGOAaAQCc8sZ3yRFv5W+7iwvg7THhR9XT7YE/GrftBGK5po/ju0ihxNz5mwEA8wPxumDBFbYwots/f8kgtUvMusSFRUEtXkWXL33Sr57tjRyjQcBPV+ObE/A05JUNxeSZSxd8AbrH9bJAZqEpdY5xO/44Cf4tIXqm+/vEmtz7aBRvlb1eXo9wt/F1cWGxL29fBD+rHMLhE4SP8HXhLaWPYe3LJIlJlfvwfE48g8reMd5kAFert2UDXNFAMXj+O8XdnX5YZRBuhaptIzeVvyx8dep+/O5vq4frM/N3YrRi/UY71wszV6BOpOfxtTExXZLptR8i1O66uzEFVV33+lkVwsLSqanZT6khDD2LU9OdwMDNp9RY7WHutCFjflU7Eg+Ytq29I674ozipEpWQJowm59rryuHps7rWav6XSMi7souLv0kFyb4X4u4MDLa9WDuwLCaRbh8EN2S1cz0I63mDEdywz++bMbQ6kWIoyssRdCGD8reXbU1wyf7CvS6VYq5o6T9PF+QaR0LQ1D2qmKTtuiA1/+xjGIMfKGF/RucHhAmbHpYV0VA0NlClFzd/uFGCXRRvmhsKwtAEs3+6o45a7VO9eK5LW3rS6eYmNdFV1zd9cTuu7q46Awl0/UhS3Jb7UahTeuTcJHdep2YjmK5Eif2NipLrC141imWXCJB3EhUBRVjW7j6KKLpCouW+X3POjCpllero9HiWXa89f0tWqxVq0Uw54WRP62uqNVXv/usKr778tf6navZh3vWWTNYrl3wvEAIeIdDwe+5G7GBfOZK0NdJG/fXaLDF51j79ZzxN5Cez5/XGp0fuxaGMv2M9aGONlThP4G8XOgoWXdGhDvI3ydwh6WPG3ac8HtVet+aMJrfO7CpWk5e8uDtLYamiDG9vrCG9OMVGuugimBTt/S0+tiQJLX1vvwPe694PpYtSUjrCq5Zp9F6ev8zeG0InJUIk0M21E+5Gqi4kWc8KAqgcdN8FsycsBoB+vehYND3wsNIE83rrObQMO3PoXfbFa/F2hmhLeFMr8MbFsMB93DtDpS73sWzR8CbIsOEeFnw7j/XLbRJqDMGddISxRq09PH4ugiRXm70QikUgklhbJ34lEIpFILB+SvxOJRCKRWD4kfw9iOBbEbCwI2i1B2D8SkPHXlhWjsbfGcI7mh50+beqYjZ0J2Ih3coyJ9LrAQDgR4PxaPVrFCE5tfueH0arP0fwWDdmgZ1v8Kpy2I26q1SvE336iZuj4RNnsh5RBC3MH6rtMbTOzb6WugI2pbWq1xbHef17J0AJV+MZOrc75u96eY9m2mir6tqU7uiUd25vjvuWIuP9Ct9TW255L1hrVVlUuFjtyfRvwvGcB31OKVqB1VGzcexyyd3GTZ+cbd+XkGNKxcRfF9nVS7IF3hOquUW6FbBBlhVOTy07jsn+VGxV2cduOU9mT38ZfUy/GIklR2GEeOq7F8fxdb33vp3tLx2jDzLhsmSaR8Gw/v2+Ph40hsUQCsZ32nMf2J5dCRoKg+bZe3VNWWXWJ7VNZdTC/aieabwzGlqiQDRt6UXKwAT8iEY/x8IWb31RiN635oYMgXnNEAvntbtn6bpui/SCZtgjN0WylWFUs2mXiYSc2Fx5UWqrQbBsHvn06WrjJORz6Dfkn86LR9at2aKt7A0rTLf8x/N1W7Vvi5yC0uu6IKs4a+rGLnlzMVQedO/NizIWhtfxwZuFE/K078nRA4QJ33J3qoLOjbujxvkhedcQK8bf7XAwwKKtVYrBg+VSOGUQW7Or4LZ1Zs/VNof9gqSUqJKDEKUbgNhfLRNWzcJQFxu0ZxlxJZ6F8CuxuDAembl2qlqmGGpDqxNqIqjVPMO6ungmZYAcxHFhQZoj7JohjIzSq+GgVMpxGM/sudhyPYKoOmWKtZDu13GjDfIH4aJzZ4PHPMlRnhBSHchq1lIlbZjlWuJ96N1WL/Lirx6uiKww2JkPXNFAmgr4XVy4a84Ni6bKKvxaq5nP/HnWuV7Wn4xot4iqqaaiGfms6Qh5h/fjRRAC9vBcmW85GfhSK84ir7UaDoEX+jmcOw3GdXgwAFK5PhYhjDIuQU7RdnR8LNqAYCngnCI21oAth0Onpgzjk5S5GEEqj6+kGHwHdtDBh2upgVJPtP2taLb1p/FomWCUSWaxCUeIKlHGnbsQYUeW0JqCo2NcxnEiZ0dZV16HfSiyKNiScz3dj1eGImrS0mF8TyaTT/lUHi0kPWb6IVPwh8tcdEY5T2/krzXZ5xwcd4FzgF2JyOl+J1GvacEMqzjl2RFG4ws674ylWSNVqdqfbeheAJKGEsgDDxSrxt6ojHJ8PJtJ4BEk3l+Fai8M1+t+gYu6zMFX0QdJbILL70P4L7saZzG3IAYED1QEDrsRNpMD5W+kknIQutFfMFxbZBfln0azNhjhnO/OAPFyFi8qFqPcv52uH+LsovLPxVgIqhTkBCyAegfJPNzhSzcR8nAfCY8TlURhI1kEc5Saq1Dui5u+Wa+1WiJLYVfxtno6BeEx4nId3GIqV/VQL7kP+KDYzFUffMz+dVjr/aW+Gqt3jo9eaqlWkEE4EjXLfh2u9MBvYGzC/yuvFFYkL4MYP76b+VA++94Ogjay/fQTJRTRLAIJZpTooXIYYzWbGYT45XaqubSCMU84QAt5FyxwcdKy6o93pdpgshrtI5FrEbmnugnTvCOTUbgodjXHkDYn8zU+FRXAclUUG5+8QvwUX+mB9zjv2NWujmqyjp6qqxWA8dEzk75ge+Bt3vfuO1MLDU4K66uhnJuWlGiQvfa0Z+h0hrebuxrxEahdzLca8afHXcAsX7JzLqCn8LVBDHbQcBhTrs3CW3PwMp5SJRWk1prYGF6lxGhPuCJ1WrhZ/s07NXpv4a6fl77j42NNQUIwJ0cmQpfb5W9ZkSqXRueDCbchxCv7uLXb9LrwbKo38Lbaib36kap5YdHGkFZFC5KwwLE0wnWPGOIJciNLeKfi7k8CNPgjdBZu5c2buhX0L1X4kYVZtEDJqnZQgUyrzIS7KcDWv6qQiILWUZ60hjCnHNLVuqtff7HPlE0topqLe2eD+gp6FZ3GIQriBVLVH0PPmxI5QUY2/vWpz4up0mqrV78/l7+JfzAWjcLtv6AX6AAqLVOvv3ejdZgNB0Eb4220D629UdBx/e2Cs+KKos1f3ssirbKComltNS8wdD3gXyWBw0Ak97NJUsuQc5G+Bm422ulp/88eq1RKhDCVU/N2VSGRdkDCEA+uKKxjjb6sLksS+jqO1K+VXVd8Uf8vkCRYengKqqqNzJgerPQJ7MNWFyIO9jpBW89tKkQG189uXMuiqIHqBv1nsIJINdsYp+VvjxjAwwygtsiqmvDIp8a1dpCgbXUNpeGTF+Fu6zS6VonAR10xdMG5P9y+TjPCKV9V0phN1rEqNmq4dvFZ/ySQdoEaA90WWX8UI2RjO357uYrNd1t9x7oXvsOU6TkSKi1xDPCb76mVPJiJOD1PhJy2/LhNV+zjkdDUy/b5TxJb3n7Za4vGjj5vCJZs2wfoiFFsGklUt2pC5OV7hQmAfG7PwDbHkR6vbr+XclUAkTueZL2fGi+jC35aOPnUbwM1qet57f65KOCqLxSiGt5qbJoVM5Jamm8JFPyxMVbV+8cG91udvVO2dxT3b+/7byFKrQ2NDFeyq/JHmWfnIldY2MMLfPjrsjSu6r9BJy9/VSJEMEKlDP2q62oAOIpTfeaUgElnN8D+bPXhRuICuig2EgInS6i132W5+k17YL8/P5Wzwq2kMJUn3UYZ/JdC3X3ir0RyfPeARH6omYcPf+hbQq+DH61Z3YSoPkdARJhKLEatGoim/kKjbA7NyqPpk/F2+/26qNg8gP7sQ0mPVno5v/VUY+0ZJmxlaXXdE+QLUrboL+ocpukgiDK7VDyDzXkn3mX1ZbKDeWehrVyZiR0b76dQUjfWt6s52MnEbG5HCsBLOKjOJleNvBQ+8uMZy6Bhuk28rINKQtBcQZQzfHLgj3ImfBD48El1hsj7EwoNHOHe0vH48Fi7SBYQyYmw1ZgO9F3WJQTh93nqIQ642f9wurCp/JxKJRCKxzEj+TiQSiURi+ZD8nUgkEonE8iH5O5FIJBKJ5cPq8ndvA4JtBZd9N7dxc0QikUgkEsdi1fi7HEHp7Y8Ff+vhZj9gkEgkEonEBcQq8XcVRKUX4aQcxZYDfMnfiUQikbjAWFn+bmNix/P4nYRnCbcSiUQikbhYWCX+7qrQTjEeEwLixAhE/gTCDPnHRCKRSCQuAlaMvxOJRCKReF0g+TuRSCQSieVD8ncikUgkEsuH5O9EIpFIJJYPyd9nhPxWa5t402h+YjaRuNiwHz1MJFYW8WeLbzFWib+r82MB5XeLe799ab9S3OGnau234keBH4EuPws/DPzYcDyAPjoVkKL2Nqo98JPLO9Pe8XT/PXL84O6Ef+WXsjWn4Pqn5gr0h+jDOTrfqC+feG7RSKKIrY4qMj3oLxyXBzFNcWGoRv9laPm1Y/tBe4eE0/EfHrZfvJZfueazA9J93rQ9arX9EjbAt6xwoNeKeTOn6f7BFJYTTMgi/By0KqVWx7pMkvJLz/jN4xP8XCa3zq79B4bx0UubyrkJV8IYeu2dD9XGRAovP3XfVSOiBgIq8F96lnSiNZoNsJaqHwjvjbUhxGOcZoeMyfoWFbi5wZbgdutV92Hq4h+NnlO1dhB+cJ07GvlV7f3Co0iGqvA5aleRyg/MF6DSPjbXJcCU/SR5N7iKONptU1SkIpiN4urELNBP6WNMG+x2xturqH8kvox00wMKj79+q0OpdiZ6y661I2R4aut6vhojpRscesFdxKrhpuZ4hluDXqjQgpXjb/8hbfQ9O4iav/fkt9bd+/jTDLMJnD2zbj7c3OafW9fBv707xW+z+7M9l0cPViP/SCmhObrWmV3C4xuY9mDl6FcRZocaMpFWwHbJtW1u7O5tb7E5buyQVDJUav7WX4lX43A/OMLfDBv5LUqr47AhMbhkrbR6kG5ZsSgTd6UundlAyegvZjJjLE7fOHBSwcculB/4+6BQ+9Dpf/wGMzRWsbvUa31xuKdTB/1teEnnOQcyD7qDUpr1PslJ/hfEMAtPufxToQ1r9U6sovPWhdKQgmfFaPkWxIvl8yPVbEYjF1UWKNAqjnieCl2hljH+hva8u8nAYtSj0KFyl+QZ4O9DeHBTLAqHnlkbDX/zL4trX+9ONw6m29wWt1vJH0alPUsXri4ZOAebomQ0StKRWRluTYY2NICBBqWh6ugrokhw9K4QtIgKl6p3+aNMCOr0Q+9l1QC0EZcZMkjjsJX26lMwHqMcFalkrUQqCvcOVSYO7quKgRHSzVfgbtGGTqYxoMK6ZWrDCpKjdZyztgG3q+JYyIFoXWoD0iLpIB5WSFf5XS3aarFbjCOqyHXSSa9ZFSwqK587blc8J8rkf9ZMrRpuylqqHadVFnCfouHe1/JRqpb2sp1IOh7QVkix3IOmHL2m3i8t5UeGKlWsHH93pg787fF39NE96g3kFKZp1UpazEJKEz8IW0F+72bvPH0kdE89/FiAPc5f1lggBnMrRQw0ZAIi5AmBjA16XDLQg2rWpXZ1AV67VX0m/q5btKYeR9amNoabB9eUnHQM+11LV9fgq41YPonkOodaOD/7xJ3No0NepshBfy8TYkSGlkfKRMELCTjwMcn/gQJ9EhBKq7wtMMLfrJB1LmFWaICB3rR+vKIakBcMkoJFMNsPuVQ8Ip4CZnwgKuJe856aoBYzP1eXKgoOoic25ijViJCLMf4WlFWdSFjumvIxoIJ6WTmsipFRoOYHc234uzNtOFtgXOBBFxKDl7RKM7nJxi7pnPtXBnXj0zutV+lhL9AhHKiN8bImxl10GapGX9j4qkhUbFJ7yiD2WRx3+QIiPmVprK6YTQeCG5gYiTkBdl++WAxDXtffReGgB5tvoY3IHPk7pltPqerKGwLjpy44pXgLl1A+f4z8bXzPfVomXtyPwbsy4gI0KsfzqOrEqnkJLh97fS0eTwyY80tmNbCR9XcXquaJmlhy9PaK3js2QcXfambik3E79KP2WqyXP+qyrQoV6maDj6vL3zAj9pU2GGAE0ae03uo4/p7hixDNdjjdYPuY9EK5wbDweGP0PoYVYuJgMu45k83dh4xS+He4EqbwIvYQf6sD7Xlwq/rU/F23WlOYe2x8Quxo2Rj/sSi/dqliR0h79SlGGG+ulrWNHV6Tkc43mJ9mQbfckJq/UZ38RbGh8I71pvIELTWFWOG99+fdHP7WAmeNmdESv7Y0FI6/kT69WPcU6FZ160Hh9FQxP+sarXR/B28CejjY2+b30u5QTvD+3Pi7ftfS9UioVMdLnB08qJbD8ruNadWD6+8u8rdgWl5lBTcHYaiZMhaCAwUq/sZdzJlQLKqWfi9WEcYpEzBKQ9U2AJXXuXD7LmnS42+8JMOzGKqoOvbIpJhipQ1XV2fy4P05RqVWrR0BGwgi1QrvwsBBq+fzt3tI668yWGa8uNTBUsaCDAHNZv4QJhotH9c6ZZQq3PIrpYUXkPFxry4Orj14Zt2ZoV/ruOWjgZy/5m9Xfqw6fnuCxFPxNxuqzFosXZhC6xKRGm3E96xhoMVJXoPV5W/Mp4z2yqTGXqeI+tiqJNtReae6JjN0T4/8LQsLhr8Hk5Ibl6dmx6OUrVyr2+N+0mI7eOTLeOdmYoTehUlpv4oLcEOEU9B8LX/r6zv30V5sqLri7/gap251QdVq1ZgaHPJDbK1CBhisdhLWN273hS/rqjnJHUQYMMgDUeGt8AJKMsTXsxh47JFRpldhVYtyJL9X7T6uM8cBJZT8kfUBXTDZWqfhbxcpjNtO/AIuVOGqBF28qiOwd7Ox1Y1tqNiQM5ifpwvMnfVQPIW0Ah3tLxj5Q+jfoqW47LvMX9kgXRoFLanT9GcLifYsH1XY+rukQ4GD/O15os2YtfCXso1j1arBXpf5PSqGj/oEabXaoU2J1AIFM3ufgapVGIi9j8Kl49b7/G2v96RrkG5jWTUGF19aEbThgxEKLFWLG5ls2ywN2UAPRaSicO1EswEUYvxdFBjTo4fsam10NmPoXEL2NpBNvxFH01wkL8r6l5WvZgOp1DGqNUb+FgltTTzE3zbGzSl51Qy1fM4f+duUpoVY1S6Me8JqLguE8V73NZfJ30E0/F2JpO4IVQefX6VX473GKvF3ooKaSN8mTgClLrewRcC8lQ6wCwno8JFboI1FwH0E/xth9NuF8rooMYoyN7pdYAF6X8ScGSCwM3mkW4ng/W5i1PCzZf12Ri+X/J1IJBKJxPIh+TuRSCQSieVD8ncikUgkEsuH5O9E4haB96Gc35eFtxKz2xdh6oLDN+4lXu8omzQvDlaOv8+84yDugdwLgbG6/jZIO7QwEgSt7IRvErVMC+dSUOePkjhQte8L1X25shN7oC6FHf7pDicbsu96o90Lg32YKBZ/B115Ob65vyMnZGQTu7Uo7smcBzlz0ll+NLPa6SpAXaVGw7SOrsDN7/c1iSennKcIpSJ79X0H0JrE8wKsK1vEdDl7HTQmp0Esg0akGWv7RA78nHyrju8wH4YeRBkJgGVRTnsK0TNXSD/t3ML39A5sNDvanVat4523uneXe7nocEwDPVG5Fb71F6etjvGn4ThTszEYGKgiII4aGKHtqR7GVAIo8XjfL2N5zc9tqpnZJvByCgNH1MxabGf1ZGNHBGDO8CFQtbeKyRNgR6G8vX2Z94ZOgcLANL1XOIaz78lv92ADEnkQtWsVvSBocxBGumoJA2SemTnEwqFS9QzahHDWAIdCMRbsVEg8LwfoWJhrGzWKYP4UdpvvSZc1qnYHEqMzATM+vYmwEwdyF38r6220sbr8Pd2WvX8YQhKXDZsAsSEQ+jKTYmXxYQPeHolTFpXqfYRUh7hCELTOzgDoqFBvK5DjB9IZZgfC39iKKY+UkDKQqjTBXQNoIxQLC2Y6tDMVaCkEozZ6+Ujf5MgnHU4h722UAzk+njE8/NrNCAMg8rec5a34G7fsrIgMGD1GUh/GMPnB3DpNkQM8bNmqDW2XCaDK6cwBOQp/B58iI4HnNOASaZ0OEslWhmLg6RIzq07n4CFxeoEyPUPlEBl6Pg0fKB3isUgbOwgFpb1pLULroL2mdcgT+Ew0GQJgoaWo0YUMXCId4aEkcFqm4m+WFsIXzXugCbnVuJJwnEFZpzCHVORnb4rSdKqKosBkAPu+TgR2bURVA1A1RtaaxunbQtQwv+s54btxy485deIHynVpApufaim4UcrGzMrniGTMWoHIj/GOIYaOWPNwYKo61RUZME6No1jP73J6CLwuNDwGMPBHOuuOLkSLYpXa49YLB+K+2GaG+RtDz8Y7Fd7EZRvoPgH0r8LYWHNLU2VaBzHc/EhgifnDOqyWGaP8jdb1zxC6o56yYk3hsohShYdhCMHwoc/f7MrsJF5nwXM6G3GaydyXfChOw1dWXh06lKXa4LNk6CbkXwuB8GyCu8MReJBCkySbA6FqeMtm0K0uf0PFYhBKQlCKHarhvmn4m/tG7MzGhuq6WNJlDoc0Q+EhCJoOy8BJKoY5a3mKajngFXA4Mawl12tob0LD39HFW5lguzBc49ShWN6BHuG1qYPdLSHKMexRLPJg2Dg3a04W/pAbEvhbakddULU6RHMNXCyuUYXyNzRjJCclKSgbNO/HNycWgdV1BW+Lu3xhWmKPwJQmg0EG517JPMDfqg2jxiKJdpM/orryDIi6ExxH1Y9rVczFQ/b+ZUrhZlnGreBQzFKChclHT0fV0bG6yXVBS7EK5EHHmcvDHEsyV3ZSscXED/RHV1Jl0MWQS2VGEhirlpCdVLBe11JwrzbNCigSWrwdr2u6X0Ui4/716Y7PWgJjQeFQAgpRGY4kmqxPOuVItzS2BO9DaXjtpOoNB7hdt9I7OhcU89Z0Nq0QsIGkQgl9/h7rEYb1FwsvBlN0aEMY1XkhPL6iV4nmKoXH7gvvHqqOcIUrfPUfg6BFL1d3urgdjg8oHaRW0XRENDNo2814IoRn4Y07HRqobgOn0vutVvPGRxgY3I5qI8zJVOwwVJHetloGDkYxBz3cLlGMUC9swNsif9l+1NL43Scvu6EZ67hDndDXI6UadMnf9pqCexHdg/TI33sSwAiksmehjqSMlr+1gy38k6buS8AE6RWtvTjHOBgOibzpQYuRqUsQhnsQgTcBA5W9vL62LT5rqnEtdP3tLgBBkcwaLGSV+wK5sMxsIoPvz0WwEoWqa/mb38P3+FvDtrtIeHAIFlE1OHQfOZ3wPYoKHcFB0NTFDPE3XSMYoQ88HTnbJQAWynGdW43uGpp0n/Np61zzJYNUVLxVV/H3hOOKcxMwOJ2/df43suJsOkIUFb6WG3tjXAfC01cgjNa7dXWlpQsKW3DvBDfEKVJIG4fOVF2iGyl/s8LFSEJ+suTSXz5wzL0CZnh6HbnHq9BKwSIhEhm04RYCgVGdaAnD0AL1B/6LCsfjnH+Iv12HfFEtjm2CyAUWA+OxwI/grUNVNWOIv8P7iZq/xT9oNk236WzRc7+v4wuPEnKq8/aqSMI9lxH1Rf3kWEeYbq0jqiBoAisEmZ2/0YRO9enakClFcM74ixntRMIkT9bl6zyxcFMpw5QWWx3a64vgYPmA2rZoo5kyel/3P8I2przOpo7Q7xdcMw1/b3JsRHmWiYAViyCJ6FCWnLVR/HkZGu2gWyn+lpXomr+QLNe20BF1e5wdPLJmgY3iclAmR5IN/VQeL69zK/6GbQ2+P5fpHgZb9N3cZ6EKPK7Z7Fnk8RA/kqbfgKrrlCW1OAKE/YKTLXasLRrnb9SLGi29LDTdhUFUNqnSWA1CrtqQuuRnTnYgGDSm9SqQrqNijL+1+dKb7IW9Cutf9GM0er4lalG3YheeqNlsVGg5Qx2hktiEjDOvc6RY/+j58RHXfLeOy2a0ob/L4vwNzdiPu5SQcKWcTs1SVxihai7WqkCxnh5FMgm5p5AOPccq0O/mRl0b6lBYyA0P4lYpzdiieHAvVjsdq4ryVpCXUCIqCjfbMIeoxQk83UWCyXm6mquZkFbh2lCbQbqOQX+2q5tQj/cS7Czyt/f1tCwT+/wt5agxF/52txOrKzxn/O0tkltl+e4KFC2pH1P/IOnhWRRbmMw1HPNDYH1Eqg7PakfMjLm9an8kiiSqQOuqjkB1xfwif3fWj8EJo/xortAARgrmPT55tXo1vxl/0ZhrI7Y6dIfAdorAwt20OrclU3gRSVoNUf0pVlqw8Ia/RULlFzgx+AGXATN7vZa+gzI38/25I3i3spZKDMIN9KYBVVee64LDh317Y5Eog3keytI2Afj87OSIs5y5WEiwMwyElkUuBk6rycStx+rydyKRSCQSy4vk70QikUgklg/J34lEIpFILB+SvxWyp+Ccv9xKJBKJRGJBWCX+tiMKtmMlHLwZh2/i0KfCuY4+/KwRMk89CFq9RW58y4yLxAdasKtlatuksSlRM8jZGJwf4ypk06OXYlvEByrF7tkqEEQA5PddpoTJum7cjb/xfDywwV534frJonCMRNDqoe4gP7BX5Qk9IoFiCnxnZv+gcOgI+TjSfN/V2ZUdZKVHsOXVZR7fYhb3GOvpl3mwVmOLspsZF1L1KUcZiprsayaRSKwUVoi/sTeVXbCe5WgISdkONOBM7Gzh5wfWynFqEFJ1whUXFX+X0xQD583q48WRv3dwZNn5G47eSWgNcR747I0cyrKjDiAPq1ehZCOEyid59IhhoQ2BRixqWJ+fBRPL2U2Ur2d5AyKfadXG35Yz8jfv5sWFknQ8JW/n6LhFduLCnwzziYpBN+UM+p6ebq9INHSEfLQGSkosp8/fDDv2Vk04oBaEg9BzI7a7Hh2htuFBrOrAljWvc/w7XGFOpmYQ+BsBZ8ZnHolEYuWwavwtAZLm8beScZ+/C4lyTETlcudj5Gn4GyQNDusvhYH6xEvF3zMJFjaXv/kopxZerdUQYsyOCwsr8H9HGhQJfAk+m8Y4UJInUgu4cObnWWWW0NmpKs/WWQAsgYUfqs9/1/zNAOdxsDaJmtRZseigav0dTszLlGJn8+iwij1uUxabWHCoMq8udATD+gJ9fQL+tmV3w99eRT2bqc74Gq/bIVfn71BUxxLqXcw/VMI6ksne0NuIRCKxslgh/gb1yoIVrnOQv516K29bLqSQvhudSYCIel1uyz5Zk43xd51S8XfH/poDCOMuojTU78/VpzNJDL8/RysKcXK6LKPb9XcIA7IXfp1Fq94ogbVRNYBWdyEAFl+7Vm39ba1r+dsK5wInpS+q+GuVqvH+gHSyccBPbajABmbiRreYSYSOkI92MZG3C9LXtAIuS+Su5m+n50k4sy4Z+LVKzCCo35+zPNIRPj1SA6smH+FLGXn1gloif9uUqHSEYbb5pitfbRMTicTrHqvE37pmUj7A0jC4UeNvLKx9JW0vpSN/dzEQkgV2EK8dwoGpzwUlV/ytVev34lq+oOXvTn4AAPnrRa2IZxGLlIBDUU0AI0ljeBwfpHt+vHx2oCimVdDz+hWO3QaxpXUegYgfDwGw+FmnIiMbSIg8sdXIhUKkRdz8MnNCfll2Y12OR0Ci8e2CY2Yh4XzpDwHqjlAxZqhigwOf4dm26vBaxYvFLeTXFN6UMMrf0iJoBrH59EUFlO/mFzdV7Em8XoYqlgr3qc9QzJa9X/iFWGUikVgNrBZ/D6N4yZLWfLd6sQAW6bHXCgIsi+5r750U7ffoi0b/7cvN4PM/f8cdd7ypTU0kEiuAr36V37ytNn8nEolEIrFsSP5OJBKJRGL5kPydSCQSicTyIfk7kUgkEonlw4L5+9nHnmyThnEm/r7++DPd0/ddwodrl+6v7yquPdGmzMds681Xt/p7fOfhofuuX730ZhJmDnDkGtuE407vmwHvYd44mNQ77xKJRCKxClggfz/72Y++4Z6PtqkjOBN/V3D+JkYXAj4Cc9Pfhy7dz6U/c/XqXVc7oVv+K4nXLr3ZSwAif+vk4Jmrs667eukSFUV36XGbNPAEosEv3HHHmzZxamkUOLwkh7P1nFiMLuLHmZzscRIabB3TE4lEIrGyWCB/M5597OFn27RBnCN/P36XLoVBww9duoSimXovXeJ/wt+4S5nxlKNafz/BZVIK/SXuZ4qVScA1lHPpUp+/TwJQrwZBC8eR7VC18rfnL6ekhL89PZFIJBIri4Xz9yLfn1fwlbStv6/7+ltfbhP1hnfsc/gbBA9c27p6TXKCv1G4v7Tv4yTrb/C3hD/zEGmSopG5Wv6eeIjTOr0BVX3Hz3++TU0kEonE6xGL4m95ef7AG+55pL0xgpvnb11eM/Vex/oY6cziT9yPj8gDXh/jb3tc0/2L7ath7U55sP7uE/VJ+BuLaf3SWpbgYO4Y+i3ytMXq4jBec/j7yuSOOyYaMiyRSCQSr28sir9Pi5vn7zPDX4YHehYI6zsV6/vzC4uvXsnFdyKRSKwOkr8TiUQikVg+JH8nEolEIrF8SP5OJBKJRGL5kPy9ajgYOTje/Br6IjBWdSKRSCROjYXy959Mryw0fksVf20UEn3l5BgNvmbhX3q4fhLRWc4nJIzMOKYSSQ2/eD0ffHac84+eKzv+10X5R0j5kRg6JgJVhLvlJ8z7NBx+PvyQA87YT1zrvvqhKsYkHEyHMFTgLP4adw3+pe2gOoS7wbUc1SvwKsZ+yhMdwUf7WEv2E938O99VFZ2pHQf8vL2JRCJxC7Aw/j545A2//Nizn10of0cc2cmx+y0Ai8Rfe+aq7S2/HwfDOttJbufHKOUoniJ7SA6M9eOyRf6WpzqLv8b8jY3riPTiod8eovz1oXPFV6+86Y5jdA7GIj0SkYD/KMWJ0/hbI7qEuGxMn93+zkxPqW31F9YePaa5aGYAqIIZ67JK0ufvqRFz4G+G8zf9Yzq3bDGPk2jDiIVc5bwcxHD+7kwknVgc7foMps+slnK4uV0O6XU1f1v0WWpdNV+hGlGyqgUq7U2tcBdP0SODk49EIpFYBBbF39N7Pvrws3wKvL0xgpvnbw+FRuQKztbI5xJDTcDsbtdHfmask8Wxh0kfPRce+NvLkaf4LDg+NlXj7lhg9rlgOvFj4lhxOll2zfp7fyfGZWOWErIR5pYVZE0qp+JvwaHMA/r8fejcOcbf/NQ6CzCHv/nUe5CwpFvU2A7UWGfjlDoa3Th/H8hFCZVTpg5+Ct9aZ680eNKjrZMpgvL0CH9DvOl2q+pEIpFYHBbF38Bt4e8mgNoIf+uKOULjpM7h7xKiVeOil/W3rOlt/a0Y5e9TrL8BZkHQyd72ri+ph/ib1+udMo3wt60sHUqi9mbYV5zOhbEKTWFhLAVLXno8kNk4f0vOufwN+ORgjL87uY4zBsxUPGUaVthdxd+QZ4C/KX0qq3znbzyCRblrYLKxA2KOVcxYS1U34a07EtfqN/aJRCJx7lgsf58cN83fr2+AiROLQ3m7kEgkEkuB5O9RPH1fiMvWX0PfOhwicmpikUj+TiQSS4bk70QikUgklg/J34lEIpFILB+SvxOJRCKRWD4kf3fYWS2HtfgbUN63XG/YBpCO/cm+sdk3bwO20/sQGeQMWDle7KeVwpfZ4WvXIyuKL9rDWjMJXSI4wLky/WQbsFW8y3bqySDpts/8aBd5/HH81ngN269+tEtVe37UPrEN2KYx/mLe9mkf0C0XA5XGndhBG3HbtjantGgAlUilv6hFI63urKXtvgH5tdaunBPzLeXV9996eE86UY+u6VNFFf2q10I4HUcRYEykTqWKhiRwsySlHdo5N7mQ/AOPWDokNwn5DEIvv+6IrIUppoVncbcffsdC6KhV8123XkWJtVdXfWgb+HlXx5ppLxwc0L72Y40F1nf+0bStRXVxYGKclqpVmVzm/g5Khg24LXV27dGBuHWUzvWKbdBFcz5QFc7l1AJ7f+mPApuEoSPCDwd7E3yAGNQsrfADbfIckcbMLLQaH02kutX8OBTLw7mzMAyaH3UFyaOd0DUXogdWYRt6KAZ1eS/bNQ52Fm/AY02eHa66brU3cLrvR2z8jEkxv0oPUpSkRPMTUXtG3hVzgtq9FrkVBjvE88cnzgKh1fE4jFftvmWtP5YLDlH4TMJDaX4rKvnboUMFJNTe7PT49VS6P8bkqjLh4LUev2bT4W5Taw70UExqmL9jejMO/RBXPc71Vjto0evrO1ygWpgeMBMc7u0XqQyUk5s/29YBH7XBQ0U9XXE0dI1Wqzas+Zx/fXfPHg/aaE7HtRFmeqhEYnczfnTNEQdMAY984a2Wa6sOAiCViuqBYgJRjVUdETMMi2QH+VpbMsgjhb9ZjIFei+DM4ljrbBXFDvB3dE+aInfH+NumPoKWvw3GsgMNZygh1fzNpwQH+Ls2RYfZErtsr4ULjFXDOEEAdK3Ta84Q1W60oQ/6uUFUMdDdoSPG+Fvggw7t9UlM2+k9LY3w9xyRxswstFr0UDQZW03D05p/oPk3OATTJvuQapxGyd1RcCLOi0rgppmvOqp5xgGVKY8fkGtCX9stzTBWdWy1Nxwz2tlIw4t+6lYLij77Rt41/M0mVPIXiJkxE7dVFxugu9RezWCu2xXSe7DB4USGm/K3ZHaNrRJ/WyQTqAD2F7x28eDFTQQqAnDGVzPoXe5UtV1xgrE/zKR0pYJEzN3Ea+ucTmZYXA53DDuFHn+bf/TCK9sSlMHMMwB14nsbsnrb2NmUoRJcCVoBIzuYedVysHu6vTvdVi9TtMHF6kdftdCDRNKcf0NHXVQaCncJfYCN8XdMh0q5y2qRGnP3VjdxVeNg5qECmtzns/ITPvatPto6LnYEOFXJiUdmWUnM428tU18S2BJQZ2+Yf5SQMtwQqmtfRIJZStVwRq40Vz6X6elh8aQkWvyjTrB6E5TGhAb4O3pkAHehCnSN9T6rGvl16cCFV/7dOwUf/aKupfB3CIS3w9M+p8MQaaCYIkOeDeGJJhopiE16sv1nLoyf+1ctic7dBiZh6TmTKjalao2eW5ysuV16irs4vAiRjoPANmc6hr9d7VEb3joqUBbilHmUvzmbiSTrVB4XPmB9lPFT6PfQ6mqk1K2W0tSMKT8NOjwlWY/nb25CUFrpL7dPufBBxw2UvtZseHZu1aXV4hzQ3fzxsmdmuIb9ovEPggH+Rn4NZW2L4z3xcrPgfm18+cnecsTXmlOtvzt71hvrF16mDig4K1GX5DlkB76+A6W5A0FbVoi/2azDywd0WOjyAf6uaabjqRDyh5hcnXS5saO8LgsEU79T1cfNRApPizWINW/wMIvCuBeDeRVOso708iN/z4RFZsrfnLnH32pwYSBtcdUgSzFfdwd4QC8CgTG3bfAIRNU9/lbZfAi5Nkb4u1kEczpLW4sU1duFVoNoPd29WKcCSOHC36SKIf72jlDEKT96HBfe/DH+RgYYmMvWVSKxZviWLOAgueenLpvJjAqFyP9IZyPx2juZyJvAjaMvi8gCFQz+7jT8LYJJ7+tTkb+1WHlt23egJ+TvtToQntitNiSGHSx8wBjh7yOe5zG/9vhbpwisc3aI3tcaAfCI3xVRB6FqljMU7i8nkK60Ua+/4egFo/ztEy+gaCPWpS8SjuHvIlKZteiAVTMTa1elhVZ7oCFG3Wouzfkb804jUQx2e2yYv+mRWZz0+HA2/vb1j7kd+ChTiPP3eNWxI8hbErdBJ3sW8FizmWGXi/a7iS7q0/jbv85Tt+nZcO02Yxfz+LupDiV4Y/3Cm4bGiqJQGubiamlQmouEwleIv9k4Ij2wccDODjYxVnv8PSvfOvfM196tdeybdqBNzW++Hj8QEqDfyujfwN9SMsyx29zGSJPe7dGGp7tHcBMMdEJFEadu8YsXm3XahXa8DSE1RM7PgdZ5Ce7NxIVqo/YvwKYEQYsOlIU0/nYDRXrURhmxDHe1xed2kocLN9JF4hoTecUTDYl6u4oXU4ELf+MaenNXEjpCcbP8DfXuF8MLIlX8jRT0yxrZAKvUfa6C7I1pSS1WIC/uUKmVXL2ysxU5fHHpl4luU+Aqovz2vR0DMfjUoRf+Vm3Au+G7JG2v/I3dqiVbpY2TovbyHx8pvUB4U9BJ0EA3yN+lUh5cTE40y5FxBP10WjWbjT6nZRYb8LuQucy5g80XYx7n7yl/s2befIS/peQyB3VLjoY3LfytI8Lfacdi6/E1xN9yPUUVodXS+0XyptValzfNJgHox47LZJ3EMYgS0DtTOEa2+dBZ5f2Q5sSgQ43Thr/Hq+4q2hP/uWHjsTYVN2y/qFtdmV/nvqtuVxitKqq7l2I8YuGRHUzCYf72Sl0h9mDPZni+XtLxpYMOc/OTq8TfDcLgvEnUbJRYJsDtngvUBQSCvwUIJJToIcz8VhQ1q110vC76yxfip0QzH23pfxCryt9lm+XNAsvENjWxBJAvqM7DX+Cdm4635O+LBF4Y9fblrQjYLM9pibJoyOL4ynn55NsFbHI6Mx3oq3v+gu+kRruq/J1IJBKJxDIj+TuRSCQSieVD8ncikUgkEsuHleJv3mW6ZtGC8GUD9rjalw2+l9tCibVbBBX4Um2tFzTHvsWxHZL2fUadyx/nAxK4G04j+Nce7VETHDP1Ksaq7n2BJK3ubR13qHg4ySrVNa2zbxBtB28dl21NjpOiKPniR089TuX0Gr4S9r2dAHat46KSxzoifqcLyasdghBVyqQSULJ+5xR+DrxGicdU4F9UYzuxx+dyZYpmYtUxHWJUu1Vt465qpvwou25SRbrnt430uuMa0AKPdv9XPAU0/C0mdrioVVMePygVt/EzejG5mj38jmJjUiNfSCtKqytw1f1dNmaK0vtWNd/oaSzCRdLHzWb8ot5YoP3FKbXp9jt6Uja3Y3z1o9Ep4rOq1ZG+jvAjHhgp6BQ0obPm9KVqAJFKq9Ei38/V39hViaQ20IXBK7VDS73tVG6il/m8qG5vRmm2MSia7hqfR9dicctb5FKx5K2Z6aCb2QZykUQ7btCkS1+PYFSZbdXVYYoAOwBcR6MLFl5CwjW1QGw8XsbRfjXeq6c82GXPDFyTyGZNLlWXThQrxQUyRV/RrR5/t7sx9XiSMlB1vDKwaXVsAxg6TWhGbywyNuCLmdqw7O1CKufHmlrKuOqhpcOA/tEvBwRoAjd668LuvDYuGzipC/stJWfZNjmzsxYNf3d2nqodrtYRPW1UJIqD7JgEuOscU/U8BP4WhRfFeqy9rq46pnehgUMQPdhZES4kROWrMczffI5W0kMXNOAqIhO7qNU5SQGYuEkch5ofzKBptUMOGg0MDQWmHarkMn8aaUvBqIXXJ/ea5uCpvtvtUCOE0ZmQHuLqS9J7tjrQ2M8PwAjZ50ZOqo+39Eru48CnX8XkAn8P1o7EZuB7X6vlhFNSino2oB4Afz3+WjBd1OKjFar2IFTIhjwjfYeDiPx33JhPhFj14K2TIkajY8/GViEWXkLCNV1mjprT/ZYbv9tA8xRShLxtSDbx1wJ/N9HoYh9561acv8scDRMiVqVYs1hVOM5vRjbZ3oXKGlIJ/G2L9RAqAV0i8yZkC44Ad3nW1l9/lxmAd55f+DFcn5c5ewFlGEt8qCJP4G/MuMW/q7+Q8tuzCt46jnbEE8+BuGxj/I0pJ0SdSRhF528EkxEcyDH3ApbcOiKqGpKD/+KhVTSWNSBGb/3lZzBUt17U0GiMh7DDes4A/VDVkliIyv3srObvILYGQetQkdCG9UU5+2uP64sNKC3Ou9VbhVkOnI4XtRmCoIGZYGxwlNw0YxHYpxVjVYejqKgizrTI8r0XutLqUqmghAOKGmYyMxpotBdGVuXHXZlq4X2RAn/HtgDQCerVdoXD5fK/rm/MSOx0uxgthicqVePvRaTBtU6YLGBnZ8PQu09bOsLfXmDofVh14W8adGIDMug4OBKPo4mMCzyIbJ2XxkOjvHjzvobq1ixUuNs88pvNiKhhcuaUjEK8I1r+dnckFh5vObzV0qdyS+pyFYnmJWqboJnoY0BhdCBPrFonlCNVKwv2Dlu7xjqLRqcPqP75qLeH/6MuQGy7zT8tRkhCTurQb51FVfKntEhEOzaVIpy707Ov0KzJpWp8bgYsLlgn4az5qvF3uy5hJYqjnzHTDPB3zZGHvk6N/M1PWSEVVctdrjQOZjMppr0x/g75i7+zAYOPjjWbkUT+hm3FgYELySAiWdXyt3K+nK3wtxgKloNmNJo4zN+Cog2mUh2WiCJiCN7N2M47Yoi/Lb4mwzgVVfPj7qNdjZsbu3vbOsvu3JWw+xAXIK3e3N+lbBzE1GADo3SiDSeM1apzZyP87ZV2sJ96mjXmwaElvauj+jD8colMSpDoIZ88RJQZDJypZdvh1skHdqC1OwAJ4WORPDjQ8EKiXoZulPi4nRPzwKk5cYiSTtWVDq17yuHKbCy8iBT5u3b0nT2lsxYpvBg/F8tNsAGiA1Y7VORHZhtHpb+iMBBPdcWjWDsC+Y32rL+G+btqNXWoxNTTW4G/bdCJbWwewTvJCJLocvpEHHGMEprJvAocvY5uqm4KEwrLA2Qj1+dNdv6WdhXzq/nbp6HyDsxMpek79yo8mSthGTuzqIM9fo99YIbtfW1xKpW/xUrFVmPVmm7utKlah22wcFyoxqw0Sy9xzbRzEY2n8LR1nKiO3RRLbvRsyuSntssbU5/EuzudylrcE/m/ir+1anxuBiwuSOBo/KvO3yG8F8cu9dHlA6NxvuYg5vC3uwYGjyVZGMXXj+gYNnp7R+pdZf1kHjO8Px/j75k5vtPxt63CUXXzSspbh8HM5YQxrxdtnLXiAjbl5bbWLo5sxomV8l2ksij3jhjibxGYCzSVMuA4Ztv+drEMM46pF2QO/L1jw5UD3tGz4U2AOo44w9XWiZuI6V3QPGBiVy8zOE8km/Ay0x5Xs0TJWqCN6kKW4Q0qRJrJ9gK80IOSO5HBo1mxe7JHWGl9yeeuv90p163mXm4+4qKZArLy18v7cxfeLtrX167MxsIH+Tt+a4BwYNBJ5G+1zyOe26nNmM2jm4LCdXiiCU5gPgxjxDH0MoREpZjTm5bm83fdauKAoEnnb/gEqULHApmoFHtoF5VICvMV3teqjToOHeep+RvXxQbCWiLO1dr1t7kIWDjyNH3nsxZVbJEWCucwkXvy+xxIdf5GfjilHn9r1Uj3Gpuq47DtRHikqwwhGl3JLCnIj/B/k7DOtt6XFXYV+i3OsOUp60cfEWp+SOm9PzdjK1XjczNgcTFF+Dxrzkrx9ynQOqMLgNidq4MlanXF0yeAzwUXhfHYWwuv+vS4gCINIk4ubxYDLy2OwVKo6NagvxiLCG+PLh7qud3NIPm7Qfkt4YsDiHRuXmNJsESthqhx2X0czi302xjKt5stFl716XEBRRrFefG3/C74PAbq46L5pduLMf7GJqfm7c5FA6+hz6M3k78TiUQikVg+JH8nEolEIrF8SP5OJBKJRGL5sEL8LV858KYG3WdkhyD5HmLl2FbntRCtyb7a9E2GemAR6bL9JJwJiRtSwq/YYr+lFRs2oYgMnNL7Uq2qIux38H3svA1SMvgXh3ZcROHVoSiIKo9IXb2jawbbKi9x1mq0IeEAO1wke4yhVSl5NhJ/zbXhW5HrE3cFM4ncFPdbcsmooi2zhnUu8nui9yma5n3tVWBrqyrfWuH5Y0O8g1x7g2ElfPOtA612MfzUwJ6FtkCrZbM0myv2WkeRvHVD1RWYhLyNGfkhfNRAIpFYXqwWf+OgArxwiDimJzdmOJygrBa2L8LvF/7mHfzl7kn5u+y2qPh7JOJYVUXF33qUlvlbRPXjPZPtg3JGi9jXTo9gm4zksaNu5dRcv+penDXFwJE2gCc0HRcL/u5MJFa4EFKPvxkju6sG4QTPp19i/LUmXw/Say1/F8VCJ9LXqEIPrjQRx3xrdNOQcmDvNFCd6FxHToOYyTWKrQwyijS+sdwh5F1n8zNpLMDAWcpEIrFcWDH+3mYH7Uf6Yrrwwe6ex3YIxwrVpwsXwvH52kuyyHF+eOHI39UhbF1xolIUpVRaIo7xBVEFwol4FVxgxd876sqNv42BJAaQefY1C8br59flQqcafN6x4m9+FolcV4izxstcPs7OkRaqRbBAJVnf5fzUkLLYZZFmMf5aLyRc5G8keuZy5j7o0wPhAcad5Zi7ngkuclpYmKojdP0txbI2iOS8r5tI0T6Hq/m7HOFt+FtnQh59z7WEPG04MMzedn12UtJjq+u3HSqSrb9hBtpAnpeUODy9aZkXK3l4cV+VnEgklg4rx98WDixEHBNvyBcSUwkvZv1Ev9M8r27p3xGzgpOQoMRvqfibowsxqxl/h/X3tr4axVPMW0Kie06i89bfRrHO3xKVAq+C8V7UuZ/+Ofd4FUoYFX9zJLLp9sHetoSUMeJZk1owa9nT2BcMMI1L6GGGWLHgb8mMDKrwXkiZPn9DJA7J5MvcoM8YSIdnOZY+2eD8nTOWyRmCoMWOUEjbua877+v9GCKqeqUf+XuzhHoY5m+vxRfryFPSwdPx64kj6Cd81KuDEBgriBTW3zJR4yBWrIRQSH81Xxtn9R4ikUgsI1aOv8GFM1l4CZl1Tq7w4/p60/jVnhaeoIWyLDRPyN8c0G0D4b1678/xFlpJlO8ew9/2uInKL7dBwHiT7OX7Mk5Zx9ajqAgEwylWprL4BsszCbyOW4W/nT8geaB5n1s4f0MkbQIUfhL+5pwaa1bVOMTfKr+C6Q2PO32CmwN7xY4AdA2t9iBvL/BqGuk8GSr0374/91uD/N2Nrb9DODDJXOYBvCa2EJIMazUM0ieURaRolutklgeTdcTAKt+1c37XEiLXhgCWpiVM9ZLIE4mlxArxd+Lm0USTvVAYeGN8a1GmHYlEIrF4JH8nTgNerY4F9rrNuI38ja8qLuzMJpFIvC6R/J1IJBKJxPIh+TuRSCQSieUD+Pv/A0msqcOtnyO+AAAAAElFTkSuQmCC>

[image8]: <data:image/png;base64,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BwCA5WIB/r733nvXrFljkrPwr3/967sCO3bssJd/+MMfbr/99o0bN2qvRx991F4++eSTH3/8sdn0mWeeWbt2ral03bp1lsMdd9xx9uzZC4UFUjfOzr788ssPPvigFXf06FHFPBiYm2p2796977//vtRrmn/99dcPHjxohWqrFfrII4889NBDDz/8sF7OzMxYrSzG4uXvv/71r/bSaqtMrLb28sUXX7RW/+xnP9u2bZvt+6c//Skq8wJJKwAAAPpDR3+vKZG/P/jgA1Oaeffuu+/+y1/+sn//ftPk7373u/Xr17/77rsm5mazuWvXLvP3J598Ymtlc9sDDzzw7LPPmkpN3ra7ifPnP//5mTNnzJdpee38bX41W09OTtpi+vnnnz9w4EBbfwup15baMrSvue2lydiEbVU9cuSItr722mtTU1Mffvih+dsirZKtVuudd95RJlaWtdcuBSxGIrd9ze5xcU7aDAAAgL7Q0d/J+tucNz097QnuvPPOPXv2WOQ999xjzyb1orx/bkY0kXvKxwMKHz582GT5/e9/v/rOcSrGgJxtC3Hb0Z7NqRaTJgpIvWbZ6vpbLpe59fyrX/1KW83fltiytbA53jKxq5BXX331s0zDBYH2im/CO9w/BwCA5aJXf7/33nuPPfaYufntt9+2l7bgtiX4xo0bzd9af9smE7nW37Yo37dvn62bTfnub4s/evSorb+3bNlS/Qp16saSvXv3mlZt4d79zWltfe6557Zu3WorZil5toO/rZ7WHKuMr7+PHTtmrVAmY2NjdrlgXrfI7v6uXoUAAAD0h/b+7j98fwwAAKB3BsXfBb/fAgAA0DMD5O+C308FAADojcHyt+D/SwAAALoziP4GAACA7uBvAACA/MDfAAAA+YG/AQAA8mNx/D0zM5NGAQwqDFcAqAH4G4YOhisA1AD8DUMHwxUAagD+hqGD4QpQb4bkHMffMHQwXAHqzSKe48ePH0+jlo+kXfgbhg6GK0C9WcRzvNlsplHLB/6GYYfhClBvFvEcP3z4cBq1fOBvGHYYrgD1ZhHPcfwNMEAwXAHqzSKe4239ffbwB8dX/8uxVf9gj3Mnjqabi+LjO1dYGj3H8ad3Pau97JHExy87seT+bjQak5OTr7zyyq5du+zllVde+cYbbxw/fvzkyZP33XefBdauXcu/eMEy4sP16NGjN91008TE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>

[image9]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFkAAAA7CAYAAAAQNyb+AAAC6klEQVR4Xu2Wi3KjMAxF+XQ+rX/WrQiCy4kkINud2cQ6rcbWw7K58ZBMU/PZfJ9gJZndRbYdCwphWFjt6+vrJ2iJ3XRp0uYJ3XcoIMLDbO5mJT//FFqXok3KYeOREAG+p3l+EthtnuZNXJvP825LTMbIWmQV2U2E3gSc9nG52bLWfI2Rpf+oHERQkdVEaLdIZCMTel03JoEQqch+Wymk5VvkAophWJhmIqup4J63OXMeW/uMCQWOUOEUW+7mYkd4/LDxSECPTTTFRCZLnf3Nu8iH3NrDb/EaH5NNmVUcnUd2yJvAENnm8/ywYM2YqGhnWI2ZvovVN1zgFvnIJkKEpb3Eat34ReivhUzgdf2whO9c/7LLiPKPXv4htMgbuzi70PprYprshu432nXLRH70apEPiACbOK8ae0h732NMIIK6t4lEV7j3MECEZXy8BmzuP82exyjWIidABJ/Jz7JnMbNci5wAEZaxuq1VrkVOgAjLWAlZ5VrkBIjgs/SVUOVa5ASIsIzVba1yLXICRPBZelurXIucABGWsbqtVa4S2ODewwARfJbe1ipXCWxw72GACMtY3dYqVwlscO9hgAhP79W7VsG9hwEi/LVVTE3TNO+HvuMYJ1Ht03sSeYO5qMZgPqp5Bfb8rb630Y2jQzBG3/BY1Yt+xJWaV/hXfUu4KX2lyjkUOVoTxQhrzGdM4Yea1Z/V6bm5XuuZK2ExfaXKOTxktCaKkSs1itZnc/WvxjOu1i2wmL7CHH1DD6um0I+4UqNk+7KP1ilZ3GGcfsmdYtbSN6LDso5+xN2abE6i86nPeMbVuo07G2htVJ/1uiqCc6eGZ8niHuM8ikVUff9b/LBvdegVCv6Oz/BfEt38pmmad+a3vyjOepzlPxI+NP27nK0/y38cZw+cfXtncUNjUV205qPhw7sxpz7jhHnt6f5QRA+ciZnFCfNn/hDwoTMx6WdEtzaKDYc9uNsrcYqYxRlrmqZpmqZpmoo/h02tFm9RbXUAAAAASUVORK5CYII=>

[image10]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFkAAAA7CAYAAAAQNyb+AAAC5ElEQVR4Xu2WC1LDMAxEc/QcrTcD5ETJZqOVmwAzba0HGutnGy8et9NUfDZfHaxF2VVg27FgIQxLoz0ej5+kFXbDqWKZE7jvUJAIi5nvZi0/vyw0TqVlJIeNRwIE+Jrm+SSw2zzNm7jmz/NuLQdjZCUyiuwGQm8CTvvYbjbMtRhzTFt/VA4ioMhoILRbJLKhhF7njUkghBTZbysLafUSOYHFMCzNZiKjoeBeN59rnlvXGRMWOAKFQ2y6m4sd4fnDxiNBemyiISYy0/rsZ95FPtTWNfwWr/kx2ZRZxUE/skPdBCaRzZ/nxYI5Y4Ki9bAeM3yLMTZc4BL5yCZChJW9xXrd+IPQnwUl8Dp/WMI31z/sFFF9Wcv/CSXyxi7OLjR+m5gmu6H7jXbdlMjLWiXyARBgE+eu8RqwvO8xJiQChpeJREd472EgEdq4PAPm+1ez8xjlSmQBieAefC07i6lqJbKARGhjdluzWoksIBHamAmZ1UpkAYngnnwSslqJLCAR2pjd1qxWIgtIBPfkbc1qJbKARGhjdluzWiawwXsPA4ngnrytWS0T2OC9h4FEaGN2W7NaJrDBew8DiXB6V69aBu89DCTCry1jKoqieC/wfWM4p3pP7+SxfKpFPQbXVd9V/nKtW0Qbew5r3MexcXcek82/A6/B8b/Cm2Ux1yJYZBt5HscRvG9vnajWq3MczYnyWHsKbsxirkV4D49IlGPUvnd93jPq+a0v4aYszmoOHuqZAyrUvs/6aJ5DuD9C9Sj/aXhStiDHRnQo7uM4Qs2/6juc6/Ubqkf5Kd4YTeBcbwO1Vm8eo/oj38Yoj773cC/W3Md85GPM+ZeDD/7yf3AA/yPe+SwvBYpYYhZF8e789QdEb41e/SPhQ3N8ld78Xv3j6B1YfWqrvIG5qC+a89Hw4d24hjHnGa7jmh4PRXRgJabKM1zvxUPAh1ZicqyIbm2UGw47uNudPIuo8pwriqIoiqIoioxv1krF/danpXcAAAAASUVORK5CYII=>

[image11]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFkAAAA7CAYAAAAQNyb+AAADEklEQVR4Xu2WAXajMAxEOTpHy83ayiAYBo0ckmYfXevv6lmWxjZM/Winqfi/+epgEhVXgWPHgo0wrIzxeDx+itbYA5eKbU7guUNBJixhuYdJfv6z0biUtpEcDh4JMOBrmueTwR7zNG/mWj7Pe7QajFGUyWiyBxi9GTjtY7vZsNbmWGPa/qNyMAFNxgCjPSKTDWX0um5MAiOkyX5b2Ujrl8kJbIZhZQ4zGQMN977l3PPaus+YsMERaBxiyz3c7AivHw4eCfJjMw0xk5mms3/zbvKht+7ht3itj8nmzGoO5lEc+mYwmWz5PC8RrBkTNK2HaSzwW4xzww0uk49sJkRY2yWm9eBfhP5ZUAav64cl/Ob6LztF1F/28h9Cmbyxm7MbjX9NTJPd0P1Gu2/K5GWvMvkAGLCZ82rwHrC9nzEmZAJOLxOZjvDZw0AmtHH5DFjuf5qdx6hWJgvIBM/gz7KzmapXJgvIhDZmtzXrlckCMqGNmZFZr0wWkAmeyU9C1iuTBWRCG7PbmvXKZAGZ4Jm8rVmvTBaQCW3MbmvWyww2+OxhIBM8k7c162UGG3z2MJAJbcxua9bLDDb47GEgE07f1auRwWcPA5nwdmRMRVEUfwv8vjFcU9rTd/LYPvUijcF9pbvKb+71EtHBXsMe63huvLqOyda/Au/B84/Ch2Vz7kWwyTbyOp5H8Lm9faJer8/zaE1Ux95TsDCbcy/CNTwiUY1R576a85mR5t1cwqJsnvUcfKlnXlChzn02x/AawvoIpVH50/CibEOeG9FLsY7nEWr91dzhWk9vKI3KU1wYLeBa7wC1V28do/RRbmNUx9w1rMWe51iPcpxz/Xbwi9/+gQP4B/GX3+VWoIllZlEUdyb6VnEexafpndHr3wZ+0Mxwpf0Uvf17/dugHjQylrXcU2uiOs657nCd9dy/LepB3Rw2DMl6jtIoPcKa3vPcFvWg0cuwNtLwXGlYHxFpru5xC/hBM3OU9t1cwRp+Du7fGntYD6whqGGtE/VU7nOuGdEaVYvWFwFl1AeJbn5RFEVRFP+Sb2Uu8NJPgWdxAAAAAElFTkSuQmCC>

[image12]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAJsAAAAvCAYAAAD0OrjvAAAETUlEQVR4Xu2aSU8cSRBG/cs9Zt/amKUbD/smuPFvOIxvXNCAQOI0phcg3V9BJTmvszbbgEzGk0JkRCZRUa1PkbV9+JAw7g1gDUYiUAivAWswEoFCEEdHR5kdHh66g4MDt79/4Pb2993e3p7b3d11Ozs7bnt7x21ubbmNzU23sbHp1tc3svHp6SnTjcAajESgEISEdn9//z+7C+0utDv38PDgjo+P3dnZmft7fb1ScKzBSAQKQaijSWD9wcD1+4/W6/efbDjuPY67PVkvE5zEdnNz466vr90/376VCo41GIlAIQhtnYVik9AykY2K7erqyl1eXrrz83PXbreZ1sMajESgEISu0SS2k5OTWpaLrdVqeVtaWWFaD2swEoFCELoZyDobu9rIFvrY2brdnrsYdrR/L3K7cEvLy0zrYQ1GIlAIQnedEtuzyAKhYQvNxXYb2m3XfVkysRmAQhB6vKG7Tm6XTWzxyxLTeliDkQgUgtAzND3WyDtZuG32sm725HfZ1bpZV/s+tNbiItN6WIORCBSC2Nre/uXOtvD5M9N6WIORCBSC0JsBdTZ2sNLrtKCryRZaJjYDUAhCr530OONZYKM3BEXbZ27zCy2m9bAGIxEoBKF3neps3Bqb2Nz8AtN6WIORCBSC0Ev1rLOhk1VtnaHNzs8zrYc1GIlAIQi9TPfbaFRkTxYRWWbfb93MnInNABSCWPv61Q2GYhsRV9DNokIbiuy/J5uemWVaD2swEoFCEJ21UGzdZysSGYQmm5qeYVoPazASgUIQnc6aGwzuRi76m9jk9DTTeliDkQgUgmh3OpnYRroXDd0stIkpE5sBKASx2m5Xiy0isNDGJ6eY1sMajESgEMTK6qPYuDU2sbGJSab1sAYjESgEsbyyOhTbIOteVR2syMbGJ5jWwxqMRKAQhD58zD4J/wX7a2ycaT2swUgECkHow0d9j6bPhPT1hl6q612nXkHpzYAe2E7PzmWPN3TXqZsBXaNp61RH+zS0j5/GmNbDGoxEoBBeA9ZgJAKF8BqwBsMwDMMwDMN4T+QXvLzwlc+YyOOcZzycZ54wHrMiytbRrwv/j/5LUXYuP0udPHXWvAg8cB0/FivzRRirmi+D6+j/DDyn35GzitgxYrGm1MlRZ82LwAM39WPE1uSx2JwoihOuKxJJ7Hgal8WL5orGTdaTsjkR5o7lLPr/2Nqy8avCAzfx8x+ibE1O0dqcojjhOtbDWOjH1oZj/q07Dv2yNSFclxvnQr8oHsJYmDeMvQk8cFNfMEZfhD9Y2XwVXBf6PEZo4XzVmH5sTMrmYsTWx+oMfcZjcA3PJ4+9CSyGhdAXjFX5gsfgGvpFcB3zMhYSWxsb0/8d4xicL6q/Kh7CGM8nj70ZeUGxIopitBD6grEqv4i6x42tqTOmX3S8pvEYXFuUJyQW5zj3GQ/HzJs04Y/6p/847+U8DMMwDMMwDMMwDMMw3js/AIag23Quwj0VAAAAAElFTkSuQmCC>

[image13]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMEAAAAvCAYAAABaDK5uAAAE80lEQVR4Xu2b204jORCGefLd4RRO4Zwwy/l8ydPAxc7F7B3aQSAhIS1JIMhLmbgxP1XuTibEivR/UintcqXK6VS17XRnYoIMBTdiMD4h2cEk/WowPiHZwSQ9Pz/3cnZ25k5PT93JyYk7Pj5xR8fH7vDw0B0cHLj9/QO3t7/vdvf23M7urtvZ2fWvV1dX6O4TGJ+Q7GCSSvK/vLy45+dn9yTyFOTJdUQ6b6/tTpCO63a77uHhwf38+Y/b+v49WQwYn5DsYJLK1V8rAl8A8moUwf39vbu7u3N///jhGs0tsxAwPiHZwSSV5Y8UgS8ALAIpgCL5PxbB7e2tu7m5cdfX1+7y8tI1Gg107cH4hGQHk1TW/1IEFxcXlUWKoF6vf5C1jQ107cH4hGQHk1Q2wH4mKPYCYSkE+4F2p5gJ5PjfXzc9+fU6K9y5tfV1dO3B+IRkB5P06OioKIIi+aP9AC6FQhG0grTar/uJrltdYxGQMQGTVH4G7fa5HEKRIlhZXUPXHoxPSHYwSeUeQLf7UmyC4yVQx1/5o1lAlkTFLND2s8Bjbyaor6ygaw/GJyQ7mKRyE2wYM8HS8jK69mB8QrKDSSp3gWUm+LD2713x4z3Ah31Aby8gs0CYCZbqLAIyJmCSyuMP8pNnkey4EdYKoP1eAKEIFpfq6NqD8QnJDiapPAckMwEucfoRudu8sLiErj0Yn5DsYJJub++8zwSp5U9vBoiXQUHkTvP84iK69mB8QrKDSfrX9vZbEfQSv98CeHxs+SKYW2ARkDEBk1SeAn1+LYLPSf+e+Fby/9cTKYLa3Dy69mB8QrKDSdrcwiJovwsmfiShAEIRzNbm0LUH4xOSHUzSZnPL/7qDm91+RIpgplZD1x6MT0h2MEkbzaYvArzSqxJd/XEmmJ5lEZAxAZN0s9EoLwIl8bEIpmZm0bUH4xOSHUzSjc23IsAlTj8iRTA5PYOuPRifkOxgkq5vbPqbXY+tlr/il131NfFFMDWNrj0Yn5DsYJLKn2GKv1b+hvw5OYWuPRifkOxgksqfYeS/AMsrq/5xaHkaVB6Gk2eB5C6w3ASrzS/4+wDyM6j8CiSbYFn+yNX/26tIAfzxbRJdezA+IdnBJP1qMD4h2cEk/WowPiGEEEIIIWRguL4mv0VIIHmNkwnbgaDHftTH/egHY6JooE3Kf7+gz9Q4hgl+hjimdYzgmDWfqLfA9w6DKn6q2Hwp8QBwMFpb06XaQiqGoOksNFtNNyjD9FUGxtLOk3bOLSw7S4+gHbYHoYqPKjYjAwdT1tbQbOIvVMPSa2i2caJo/UKsT9mmdOjD0mvHGqn+4D9lg1i2lj6mzCb+rNZn1HxY/dbxyMHg/bTDyUjZBCzbgKXX0GxxXBpBj/2Dtqvo0QZJ9Utfql/Dsrf0MTjuOD6+v0wfgzrtc2E7KziYsraAOmwL8UlL9VdBs411Wr+AY4glpmq7ih5tkFS/5q8My9bSx2g21hgsvYZmgzpsj5zUl4ZtAXVlbSEVQ9B0Fpqt5V871t4fg/1Wu4oebRDst96LdhaWnaVH0E77THHb0segTtqaLithUNpALB1KDLYF1JW1U2i2sQ6PtXFquoClQ3u0C20rpoVlj+/FtoZlY+kRHAuOp0wf6+Lj0EZ9fBy3ycTnEz6uJyj+8lEGAX3k9kOICpOLEEIIIYQQQgghhJCR8j/93KL54klFwQAAAABJRU5ErkJggg==>

[image14]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFkAAAAvCAYAAACIcGZzAAADtElEQVR4Xu2Z204iQRCGffLd9YQKiIiAy1HAw51Pow/g3Wog8WrlqL38Bb02P93tzBrXxO4vqWS6Zqhyv1R6Drux8Ymo/wj3DgYW8ZFw72BgEZeXlxIXFxeq1+upbrenOt2u6nQ66uzsTLXbbdVqtVWj2VT1RkPV6w1Vq9Xl+Pb2lsutwL2DgUVA8PPz80rMzJiZMVMvLy/q6upK3d3dqZ+1GpdbgXsHA4s4Pz8XsdPpVE0mixhPJsuYH48Xx6MxYiyiIfnx8VENBgNVrlSdE829g4FFYIuA5IlNMgSL3HXJ/X5fPTw8qJubG1Uul7mswL2DgUVgD4bk6+vrRKEl5/P5v1EslbiswL2DgUXgJieTzFO8tlUsJnk0Gqv7+QT/ul9Evz9QxeNjLitw72BgEXiK0JLXBNNWoSUPjZhOZ+qoGCWvwCLwmIanCN4WkgYkF46KXFbg3sHAIvAMjMczPbnm9jCW6V2uRzzFIzUcjkRyvlDgsgL3DgYW0Wy13j3JucNDLitw72BgEXiTwyTzxPr2YT3FT8tJzuWj5BVYBF6P8Vi2EGq/0dm2CQjWkrO5PJcVuHcwsAh8i8Ak8zaQNPCmeJDNcVmBewcDi8DHntdJfp1c3xZhBt4U97NZLitw72BgEfjII5KdcpdhEawl7x1EySuwiOrpqZrOJa9JNabXKvhpqH7PA5Ize/tcVuDewcAiKlVT8ug1XHINwVrybmaPywrcOxhYRKVSlScEvqElDUjeyWS4rMC9g4FFlCsVkbw2rRzG9JoBydu7UfIKLOKkXH5bskWuKXlrZ5fLCtw7GFhE6WQhmbeBpAHJm9s7XFbg3sHAIo5LJ/JC8TQceifWFSJ5a5vLCtw7GFgEPrjLfz29I75vbnFZgXsHA4vAB3d8Dz4sHMnXNHzswbcIvCrjTQ4vGpn9A3lMw1MEbnLYg7FFYIIh+NuPTS4rcO9gYBEfCfcOBhbxkXDvSCQSiURc6JuGefPAsS2v12a48ubv04SPNNcmIUmNJNd44QJ6nSZvy9lw5YHvnIav4fW/kKRGkmu8cAFeAzNnO8+4rnHlge+cxneN6290HWs4p9dv/S4VXIDXwNUQxzpMeK1x5YHvnMbW21yb6LXvGsA5rqtz74ILpF0DzvFa48oD3zkNX+MTqNecZ2znOcfr1HAB3x8OkuR4rXHlge+chq/x/a02yXwN4FzS36UGRXTYcm+dY2w54MoD3zkTV+80ed+xho/N9ZeAxXy5f2AkEolEIpFI5NP5A1AylGeWdSQwAAAAAElFTkSuQmCC>

[image15]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMEAAAAvCAYAAABaDK5uAAAE4ElEQVR4Xu2b207jMBCGefJdjuVUzi0sp3K+5GngYrlg79CCQEJCWtpCkbdj6mB+xk5SCha7/yeNEk8mM047E9tNOjREBoL5ZDA+IcnBJP1oMD4hycEkPTo6snJ4eGgODg7M/v6+2dvbN7t7e2ZnZ8c0Gg2zvd0wW9vbZnNry2xsbpqNjU27PT09RXdvwPiEJAeTVJL/6enJPD4+mgeRBycPpi3Sft622k7aptPpmLu7O3N+/susrq1FiwHjE5IcTFK5+2tFYAtAtoEiuL29NTc3N+bn2Zmp1VeDhYDxCUkOJqlMf6QIbAFgEUgBZMn/ugiur6/N1dWVubi4MCcnJ6ZWq6FrC8YnJDmYpDL/lyI4Pj4uLFIE1Wr1lSwuL6NrC8YnJDmYpLIAtiNBthZwUyFYD7Ta2Ugg+78vr3py2R0Vbszi0hK6tmB8QpKDSbq7u5sVQZb83noAp0KuCJpOmq3ueqJjFhZZBOSLgEkqP4N2Sk6HUKQI5hcW0bUF4xOSHExSeQbQ6Txli2B/CtS2d35vFJApUTYKtOwocN8bCarz8+jagvEJSQ4mqTwEG8RIMDs3h64tGJ+Q5GCSylNgGQlezf17d3x/DfBqHdBbC8go4EaC2SqLgHwRMEnl9Qf5yTNLdlwIawXQeikAVwQzs1V0bcH4hCQHk1TeA5KRAKc4ZUSeNk/PzKJrC8YnJDmYpOvrGy8jQWz60xsB/GmQE3nSPDUzg64tGJ+Q5GCS/lhffy6CXuKXLYD7+6YtgslpFgH5ImCSylugj90ieJv0L4kfSv4/PZEiqExOoWsLxickOZik9VUsgtaLYOJ74grAFcFEZRJdWzA+IcnBJK3XV+2vO7jYLSNSBOOVCrq2YHxCkoNJWqvXbRHgnV4V7+6PI8HYBIuAfBEwSVdqtfwiUBIfi2B0fAJdWzA+IcnBJF1eeS4CnOKUESmCkbFxdG3B+IQkB5N0aXnFPuy6bzbtHT/vrq+JLYLRMXRtwfiEJAeTVP4Mk/218h3yfWQUXVswPiHJwSSVP8PIfwHm5hfs69DyNqi8DCfvAslTYHkIVpmats8B5GdQ+RVIFsEy/ZG7/3BXpAC+DY+gawvGJyQ5mKQfDcYnJDmYpB8NxieEEEIIIYT0DefX5F1IAvmi6X2K2ONxzYfbaqKBNjH//YB+B+GzCP41+DFD+xqhzwKvp6ifIrZFKeKniM2Hgh8agrqybaFsjDzQHtvvYZC+8sBY2uckW7RD8HheW0OLg+1+KOKjiM2noXVG+2JiaDb+F6oR0odAe/8LDPVX20c/QkyHcTQ/Ib1G7LjzE7Nx5NnkHRfybLTrjukdmm1sPzlaZ0KddReN52BbCNk6QvoQaI/9iu3Hzi3TLqqPEbOVY06KELPXdIhvg77w/Dy9D+q0PmL708GLR8oc19pCWR95oH3Iv7YvWxSfou2i+hgx2378OfAcbGtoNqE+hPQaaCNtTZcUvwNaZ1BXti2UjZEH2of8a/t4LoLHQ+2i+hhoq/UX9zXweF47BNqFrilP74M6aWu6pLhOaZ0TQrrQOdgWUJfXzgPt/Tbua/0M6d0xRLNFO9eO+dYI2eO52PYJ+XBoOg30g/1BXUiP+66Nen8f/f73+B/sv/AB4bX0ez3oY1B+CBkoTDBCCCGEEEIIIYQQQj6Vv87kqfJVi3c7AAAAAElFTkSuQmCC>

[image16]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAF0AAAAvCAYAAACBm8YJAAADrElEQVR4Xu2ZXU8aQRSG/eWtn6iAiIZqIgIF9dJfoxf1wt6ZSiQxMSkfAjnlPWXW4XWGXYraxJknOdnd2dlz8MnJ7IcrK/8Z+WC4fpCwlPeG6wcJSwEXFxdyfn4uZ2dn0mq1pNlsyfdmUxqNhtTrdanV6nJaq0n19FROqlU5Oanq9vr6mlO9gusHCUsB4/FYhsOhPCOeTTzLADH4u+0PTAxkNBrJ09OT3N7+lKPj47nyuX6QsBTgkq7CsfVIf3x8lE6nIz9ubqTy7cgrnusHCUsBkK7CWTqEJ7JnpT88PEi73Za7uzu5urqSSqXCaRWuHyQsBUD65eVl5oD0YrE4E+XDQ06rcP0gYSlAOz1Zy83SQut5f5B0OvZ/3bencT/p+o6UDw44rcL1g4SlACM9kW2t57y0GOk9E73+5H4wkv1ylO6FpYDRgssLB6SX9sucVuH6QcJSwGg0Tm6a9pIy0M62uhxLTNLlfe3y7rTTi6USp1W4fpCwFPAWnV7Y2+O0CtcPEpYC0Okza/e0o+01fGYdn67l6HLT6YVilO6FpQA8AiZy+cbpEt5/EW6k5wtFTqtw/SBhKQCdzkvGIoG32d18gdMqXD9IWApIOn3ecjLtcHtZMYE32Z18ntMqXD9IWApQ6VPRiwrvdnsqfXs3SvfCUsBwIv215BfRPtm/pwHpue0dTqtw/SBhKWBWev8lWLQVRriRvpXb5rQK1w8SlgLw9ME3x0UC0jdzOU6rcP0gYSkA0rmTnWF1N3f6xlaU7oWlgFTpDtEsfX1zi9MqXD9IWAp4i+VlbWOT0ypcP0hYCsDLTbfX045O62pXqPT1DU6rcP0gYSkg+VfdEvF1bZ3TKlw/SFgKwLfwvdK+fp7F10J8vMK3FLxl4qUnt7Orz+F4LMRTCm6aWE7Q3auTgPAvq2ucVuH6QcJS3huuHyQs5b3h+pFIJBKJfATmBmTfiLDvG7fxnePr066zI41F56eRJUeWOZnhZLYoG5bEY/Yxy+BjM+badx3b8Dk+/hey5MgyJzOcjI8BjxmJrnF7a3CNZ9l3Me+8/Zt8OV3X81hajqXhZFzI/kNsfGOu+ZzTNea7lnFdZx/buGq54POu38JzloKT8bHB9QN4btq4ve8a8x3b8LkseXiccZ3nMT5eCk7m+6GuPw5b1/i8fXOcdt4Hn8uSZ94cwGNZr1sKI4GL+MZtspzjccDXuWr5mDffNe6a77rObF1zOOenhEV9+j84EolEIpFIJBIMfwCpLSrTXyATggAAAABJRU5ErkJggg==>

[image17]: <data:image/png;base64,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>

[image18]: <data:image/png;base64,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>

[image19]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAQgAAABHCAYAAAD7j9nyAAAHoUlEQVR4Xu3dXVNTSRAGYH/5rh+ACoiIAQUEAYE7f41erBdueWOtFlRZZdUaMOgsfcjE5p3uOSfHMHtSeZ+qrvL0fAZ3ek9CEm/doqkVpgTum4gKwIPYVbhvIioAD2JX4b6JqAA8iNrR0VEVh4eH4dWrV1UcHByE/f2DsLe/fxV7e+Hly5dhd3e3ip2d3fBiZydsv3hRxdb2dtja2g6bm1tVyPXbt29xqVq4byIqAA+iJsXhx48fZlxgXHhxEX7+/BmOj4+r+PDhQ3i+uVkViXEKBe6biArAg6jJnYMUg8FgEL7H+B7jexXnMc6Hcfnns3Md51WRiAXi69ev4f37v8PGs2dVNC0SuG8iKgAPosYCQTTj8CBq8pqDVyBGhaGKQeMC8eXLl3B6ehr+eveuit76RqMigfsmogLwIGrygqQUiFFx8ApELA7XCoNdIE5OTsLnz5/Dx48fq3jz5k3o9Xq4dAL3TUQF4EHU5LcVUiBev379W6ELxPLychKra2u4dAL3TUQF4EHUWCCIZhweRE3e51A9xRi9MGk8vYivPwyvq6cVZ+fXnmLI9afLpxUS/3yK8amKk5PTsPrkCS6dwH0TUQF4EDV5E1QsENeLwrAwqBcnrdceRnFZIPoY/bMqBoOL8HiVBYKok/AgavIOSXkTFD5lmGRIgVh5vIpLJ3DfRFQAHkRN3jotBWJ0t6B/nRlj9GvNeMfQ4O7h7Cx861+FFIhHK49x6QTum4gKwIOosUAQzTg8iJp88Eo+T+EXhas4HxUGVSzOfgUWB3ntQReI5ZUVXDqB+yaiAvAgavKpzBKvQSw9eoRLJ3DfRFQAHkRNPq4tdxDJbyjU3YH1lCK9axjeOcDdQ7yDWFpmgSDqJDyIGgsE0YzDg6jJl7vIuyCvvaaAxQIKg1sc+mlxiAVicWkZl07gvomoADyImnwTlNxB4OsGkwz5pOjDxSVcOoH7JqIC8CBq8hVxozsI42mEf8fgP6XAkE+IPlhcxKUTuG8iKgAPosYCQTTj8CBq8t2RVYGAguAXBVUc+jXF4Vu/CikQ9x+yQBB1Eh5E7dnz52FwWSDwdYNJhhSIhQcPcekE7puICsCDqMl3RkqBSO8QMH7dMWTvGoZ3Dv+qqArE/Qe4dAL3TUQF4EHUWCCIZhweRG19wyoQwxcf1YuQtUVhWBiwOMQCMb9wH5dO4L6JqAA8iNr6+kb1RiZ83WCSIQVibmEBl07gvomoADyIWm99vSoQyd1Ak3DuGDCkQNybZ4Eg6iQ8iBoLBNGMw4OoPe31xi8QRhHIhRSIu3PzuHQC901EBeBB1NaeXhUIfN1gkiEF4s69OVw6gfsmogLwIGpP1p5WH6b61r96utD0acM4URWIu/dw6QTum4gKwIOosUAQzTg8iJr8i1dygPFQTzJk/tssEETdhAdRk3/xSg7wTcefd+7i0gncNxEVgAdRk3/xSv5RG/laevnmaQn5gln5ijj5FigJ+bIX+bi2fCJTQj54JW+dlndHSsiboOTXmPKbCgl5QVKeUshdg4QUhz9u38GlE7hvIioAD2JX4b6JqAA8iF2F+yaiAvAgdhXum4iIiIiIiIiIiIiIpoC8ws9X+WlmxQNQdxCatntzYZsVEY6NsE8u6mB/K3S/m4TrWtEluLe6PWK/XF+E46zQ/WiCrB+qdY1/Gchrs3LRuG3eGiLX1pQ3fhJzj6v0euOyfiZWTlh5K9dU23GT0mb9NmM6wdo45vQ1tkW5fK7Ng225eURdexPe+EnMPa7S643L+5lYebyOrL5NtBkzSW3WbzOmE6yN5/7irHyuf05ujG5rMn+TPnW88XFuDA2vhdfPm0PLtYncPNhm9RHY7vWz5PrqfK5fW9581lr42Ky9YXiwX+yL46w2HDM1rA3nHoiVz/XPyY3BH3Cdpv1yvPHW3JjDdmH1wX54HXl5gW04L15bObz2cp5c37p1fpc3H66F1zGn/2y1Yw5Z7TgvsnJTwdp47odk5XP9c3Jj4pxN527aL8cb782tc177uH0iKydy/WPe6oM5bBfYJyfXF9fx+rXlzYdrWf10H+zv5ZDVHsd5463cVLA27j1IYeWt/nU/MOHlhR6XmyNq0qeON96bW+e8duzjBbJyItc/5q0+mMN2gX1ycn1xHa9fW958uFa8tkK3a1YOee25sV6+86yNj/tA6/rn2jzYlptH1LU34Y335tY5r72uj8fri3NGOm/1wRy2C+yTk+uL63j92vLmw7W8fhH293LIa8+N9fKdZ228zQPN5XNtHmzLzSPq2pvwxntz65zVB3PYnuP1xTkjnbf6YA7bBfbJ8fpaebyOrL5NeGNwPq9fhP29HLLa4zhvvJWbCtYDwmvNa7PmEV5eeHlhtdXN5bU15Y335tY5qw/m8DrmLF5eYBvOi9dWDq+9nMfqa+VELt+GNw7XweuY03+22jGHrPYm806t+IB0eOrarPC0afPm9PLj8MZ7c2MOH7c1DtuwPfLyUW6OcXMYTeCYurHYL9e3jjfWmhfX1O14beXwWudi3uuD11Y/+p/pvxgMus76j96Km4Br3ORaRNQCDyURjeD/rVkciIiIiIiIiIiIiIiIiIiIiIiIqJv+A8vdd8ZduTZaAAAAAElFTkSuQmCC>

[image20]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAHwAAAA9CAYAAABvGg13AAAFQ0lEQVR4Xu2bWU9jORCF+5fPNPsW9oR93974NfAw/dAjXtCAQEJCGiBsHo5JRfZJOfcmcRQG1SeVOi77uqrryL4rP378j3BfEM7RyAgX+yvAORoZ4WILx8fH3o6Ojtzh4aE7ODhw+/uftre/7/b29tzu7q7b2dlx29s7bmt729vm1pbb2Nx0Gxubbn19w/8+Pz/3VhbO0cgIF1uA2G9vb6q9hvaq2at7f393Jycn7uLiwq2tr3srKzrnaGSEiy2Y4N8ULraArRzivry8uGfYc2jPri5W//z3qR5a3YsOwe/v793v3397W1ldLSU652hkhIst4LydErwpNn4XCH53d+dub2+9/fXrl6vWVgpF5xyNjHCxBVykQXAvdkpwiB0J3Sr4zc2Nu76+9nZ5eenOzs5ctVrlcBGco5ERLraAq3EIfnp62pWJ4JVKpcUWlpY4XATnaGSEiy3g1suvcG1la9v5U/3TGiscv68+VvU/V6Fdfaz4W7ewuMjhIjhHIyNcbAH32SJ4LHQgdstW3hC7Ifgj2+PTxzXBq5tfMMEHBhdbwEMV3HbxVt2rQfC5+QUOF8E5GhnhYgt4ggbB/WoOVnTTmlfmwTaeXN1P3h4aK3x2bp7DRXCORka42IIJ/k3hYgt4Po6nZixyeM9db4odn7tjwZ/8uRsmglfm5jhcBOdoZISLLeBFSL/O4TOzsxwugnM0MsLFFvDWCys8ugJvrN7o9itY1epW3ljZYl7wigk+MLjYAl5r4uFJU9BQeEXsllswRWwRfHqmwuEiOEcjI1xsAe+zscJ5S+7V8Gx+anqGw0VwjkZGuNgCPl5ornBl69ZXdXpli+G5/OT0NIeL4ByNjHCxBby/9oKTyG2FLhD74eHRCz4xZYIPDC62sLq25l4+BOctuVeD4OOTUxwugnM0MsLFFkzwbwoXW8DXKRC8detuPV8XbeP/BuYFn5jkcBGco5ERLrZQW2HBG+fo4FzdVmhFbBF8bHyCw0VwjkZGuNhCrbbi75l5S+7VIPjo+DiHi+AcjYxwsYVqreYFb1m1Raasal7hI2Mm+MDgYgvL1Wp5wRVhUwbBh0fHOFwE52hkhIstLC1/Cs5bcq8GwYdGRjlcBOdoZISLLSwuLfvHoA+Pj34Fd7KK25kXfHiEw0VwjkZGuNiCCf5N4WIL+JQY4rBgvRrm/GmCDw4utoBPiZt/hJDZ/hwa5nARnKORES62gE+J8XUpvj/DJ0n4SgUfLsDwPhuvOPHWCy9C8KgUT89geKiC+2zceuFqHBdo2MJhWNkQ+4+fQxwugnM0MsLF/gpwjkZGuNhfAc7RMAzDMAzDMAYCrkxDY1L93BbYXzSGx4fwPGyd0uvx3wKtqN22xVfU1ubgcYDHMZovBcfgdm46mbvfuTTRgnBRGPbx+G76NT/gY5nUcUxqnObLRSdzp/LLjhZE8wlaYuLT+oD42vWnjg/b3Ae0YzTKjAGcCx/HfdwvaGN4bOjnsX1DC5DytUuoTF9RP/+WdvhbszJ0O06LH8LtEK1PfNynzd0XtCCaD7RLqkxfagz7y/wWNJ8Gj9Ny4jFCUX8KbTzHZH/f0YJovhDuLypa6NP+Y+xLzcfHCSl/SGpMKlZIUX+K1HjNzzXoG1qQoiKzj8e360+1Uz6eWyPlD+G5hNCvjSnqb4c2NpwrpNO5eyIMxIE7bYuvXRsUzQHYnxpTFp5P82n9Zdvt+qQtPi0uj+8bEiwVNNXPbYH9RWN4vMB+zoP7y1Dm2G77tXY4TuvnNvuMNoQF5mIbhmEYhmEYhmEYhmEYRmf8Bw6ep8QaE7dtAAAAAElFTkSuQmCC>

[image21]: <data:image/png;base64,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>

[image22]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAHUAAABNCAYAAACYLSt8AAAG6klEQVR4Xu2ca2wUVRTHd4l+MdEYv2AIvhIjHwxqRGJQUatEE0GNUdHEb4SAEhODisWAtmz36ZZiKe1CW4tAoJRCgbZURKAtr9oqBQSpIKWVQgQpgtACfXGcc8ud3D29s7tTGCz1/JJ/Zu45Z+7cnn/v7Dbt1uVimBsNGHi9XvD5fEKRSAT8fr84yrE86nJyLGN5eXkQCASgtrYWp47LkonvQMTrF5LQNTI2wSaiqVeuXBFqbT0D9fX12qMutlvJ7d7de46GosELFy4yjdKxqawc8kc/BZkPjxSaOfRuEadrZGyCTWRTBxnYRDRVUlZWZnmU5xUVFVHHjRs3CqmxQCAIBQWLISc7Ap2dnUKUcHoWzPgwGT578VUh+Qima2Rsgk1UTUW6e3qixnbp7OqGYDAIPcY8hYVFkJmZKXT69GmzZmtlFeQuWQ2+UAZMmfKp0KmTp0SOrpGxCTZRNfVA8wnbajhxqo9CoRAUFxcLY+XjOTs7BxobG8V95oVng8d4RE9PToXMrIiQhK6RsQk2EU3tMV5Pr6fC4bAwVhW+K8Z7ZQWnwvK0hyBjVhLM/uQtaGlpEWJTrxPYRHxUyjdK+5uOX7MOHj9pqfb2i7A2PAL25NwK1Rm3wdLITNNMCV0jYxNsomoqvp46qdamTbDraxecWTEEtoTd0NzU+zhWoWtkbIJNZFMHGdhE1VT6uETV1dWZojm72rvmFTj6jRt+W+SGVQunUj8FdI2MTbCJsXZqamoqDB8+3BSOaU2iav2jEnYau/RcoRuq0t1w5HAD9VNA18jYBJuomvrn2X+idhYaqe5UHNPdl6h+Kp4gdumhXDcURSZRL03oGhmbYBNVU9sut0XtLp2pdAfG098tO4R2zHPBhVVDoHquCxoO7qNemtA1MjbBJqqmNrc2QsuZJlM6U2UOH8VqrVWsbvV4oSP5bvjdUFHoUepjFHSNjE2wicFgwDT1wIm9cLL9e1M6U9WcWquLNTUvgO3GDkVdKBoijvODH1Afo6BrZGyCTWRTBxnYRNXUmqPbobF9jimdqfIohY9c+i65vLxcXF9b+oh47MpH7/7StyEQTKM+RkHXyNgEm6ia+kNDRVxT1ZxaS2MNx6Zd3aFuIfxx5uzxnWyq02ATVVPX7i2CX89PNKUzVeZwd6q1NFZT9gAczncZP8b0asvykcK0QMgTZSKFrpGxCTZRNXVpXT7sOfeGKZ2pat5KPzePg20ZLji/0gW7Mnu1tnqyMM0fmhNlIoWukbEJNlE1NWf7PKj+63VTOlPVvJUqS++DQ3kuaCpwQeXKoUI4N+IPsqmOgk0MKKZ+tdmjNZWaFktVjeOgytil54xdWmPs0Kp9Y4RwboRNdRhsomrqFxtmwLpj469J69fdAw24Sxe7oGLZXWYc50Z8wdQoEyl0jYxNsIls6iADm6iaOr3kfSg4/FK/tezgWNic7oazxqP3x/kuWFnzmJnDuZE0NtVZsImqqZML34O5v7zQbxWWPAk1kWFQn30LrMm9MyqHcyOeAJvqKNhE1dR3v30NZtWN7be+Wz0JDm36HHbljoYFG0ZF5XBuZI6fTXUUbCL+lZ80dcKiJJi2bUy/NSv9eahc/xHklbzcJ4dzI2yqw2ATVVOfy3qijxkJq3oMPJ10LySvexY+3vpMnzzOjbCpDoNNVE0dlT4C3ix9/Nq0XhMzhHMjqWyqs2AT2dRBBjZRNXWEbxgkrRjpiHBuJMWXonrYB7pGxibYRNXUYV/eDvdnPOiIcG4kxZuietgHukbGJthE1dQ7kl2OCvF4+fepjoJNVE290NGmVVtHu1B750W4KHQJLnWgLsPlzg6hDkPis6hdXdB1Vd3d3aZwfoR+dJJC18jYBJuIn0jzpHmE0oxdlGY0vVe95/ipcO9Vyf8Ngd8IKPxLRDtCQ9lUh8EmsqkMwzAMwwwG8E2EXSE0puZoPh5WdbHmoPfV1Uhi5QY1sRoTKydR82p9ItcitCbW9VY5OpboYpREapBE6wYEVg1BYuUktLkqdKxDvYfVuRyr53RuOkZ0MUoiNUiidQMCXYMksXIIzdNaOrZC1tG5dHE5pjGExuiYIueh91XPdRrwxFporByiy/X3i6fXxGqkLobQGB3r0NXIGF3PTYNVg5BYOYTm1Pp416rIWtpEXVzNUWiMjnXoanTz0/GARvcFSOLlKDRGx1bIOrWe3pue6+amMTrWYVVD43Q8oLFqEBIvR6ExOtZB7yHPdXGrnIxRdDGKrka9D43dFOgaJLHK6WJIvMbroDXyOt31NEdFoXldXayxWq+79n8FbQBtKs3/1yS6loG2boZhGIZhGIZhGIZhGIZhGIZhGIZhGIZhGIZhGIZhGIZhbgD/Ao4PZAcRi+y9AAAAAElFTkSuQmCC>

[image23]: <data:image/png;base64,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>

[image24]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAApkAAACNCAIAAABzFfahAAAYhUlEQVR4Xu3dbYxUVZ7HcV+u2ff7Yl/PC1/sWxPii32zJpvszm4qTlajQTKJGR1j1PEpYnZxGVEiM0MgMzsBGZ8QyAgtOgKiOELimIngLrCajjBIuoFFB7trugNCVwPd3P1zft6/p8+tqn6qqu5b9f2kU7l17rnnnnvr1PnVrYa+N2QAAKDMbkgLAABAqZDlAACUG1kOAEC5keUAAJQbWQ4AQLl9l+WDg4P9JXHixIm0CACAubJYmZiYiMLxuod3Xbzx3//S7p+/evRksbDuz1//x1++qKadvHjxYrVa/S7Lh4aGqiVh5z0tAgBgHizOo4i8rpim7fiZeZbfGOI86aQ6/12WTz2oRY0sBwC0liVLFJHXFaO0HT+zynL7STqpzpPlAACQ5R1HlgMAWoss7zSyHADQWmR5p5HlAIDWIss7jSwHALRWd2b5l19+WalU7rzzzjNnztjT1atX29MPPvjAlvv6+mz5jTfeqOSOHj2abN5WxSxfsWJFUjItOyJ7XL9+fboiGBgYKB7UY489lpQUNWowNpM65sMPP0yLItY9e43S0gKrZseSlk4V96fugSdm0mZd24O0NNL8zDRaq3I7G9axmYyERq+jtaBRMRAcDVQyz8b1YnkL1mbc1AxfyqLmJ1ManbRqWKUW1Jkf//jHeun11FbpPKiOVd64cWM1H5Y6LbZKg8H6/+ijj1bzE6U6trZ4XElrcQeAhTWrLP/VH2vXrmUjY9eKq4o/lyeaNdX2LPe3mS0cP37clu3td/r06Yceesirte9NuDL35ptvJqvqZrl9pLBHm0dsYdu2bXpqU4YtaDrTxw7PKp9utGrp0qXVMMXYss9i1XxuqubzrxXqY42fH3uqzz0+A3qDKvcJ1+urP+qzKts0qu7pqSqoh57otrB582ZbqxLtzrdaGlTDa+SdsZrKCVuohI9cOkB1Rk2pgndVB65q1ki8dxXqBNZtUydf87sfnfpjB6id+lReCefQ+qxqqhOfGZ1hr+BxqF34C6HW/DF5jeJV3g3lUCV/0Sv5CbdHxZK/+naM8We++TSuE6jD1/KXec7pxdJRW/v79u2ztTpSjT01rhPuL0Q1ykXtRbvWifLz5j3XUx8nqhYPWp1ef7oivPGr+Scbb0p7sW54uar5oXlTeul9CIka8YW4A8DCmlWWx2st1+3p77+4Ysvna9dGx65dunLtb54ZsZ/a1WunRiZnm+XegQ0f14r1fa2o882y3N6Ht9122+DgoN5v1TwbPv744x/84AdWXm1nlp86dcqC/Be/+EW6okGWV6fOKfFModlEc5moRNOZVmmtX21ontJMpBnc+IJa8Dlae1FrIa2+nZjihK7mXdKGarwSYknlPoH6Jj4JepvxocUHpVm+Eqb+eEK3Ze9VNX9NK2HeN2pB9b2rfqS+O+3dJ/oV4QNT3TYVP7q804n1o1OzSVPVEC3aqarpzOgMW8e0i4GQr35c2oVX07FoQd3zVXaAfgjaXKu8ZdVX/6v5MFAfKnkYF7N8bo1buWWbVbANdXKq4bSrKW/WF7ShfyBQI9pWT9fnnwy0dzU+EF67eOTEp7Q4TuIXerZZXg0vnx2CnwcvV1P+uhgdSHzsfkp9W2BhzSrL//v/rlpC37HtG1s+P3796vxkdeLW35zXVluOjL/0yXj/uYmn3x+zRJ9tln9vzai1c/b8ZLHyjXPIcn+DbZ96Xa7CBx98sNrOLDcHDhxIi4LmWR7PEZorvZOaNI9GX3UmW2nGiaOiGvJD9ZOp3APG5yy1djT/Clol1fyL67r1q1O7sT36WvLD/OOCZkOvsz6PYa82EBJCT9VaNe+t9utf/Cav1/agOrWrA1Oz3PeuxxV5lhfbVImy3Hu1PlyA6riS3elEqWZ8ZryOFgZClmvZdzEQPhmofH0UV8lrlLSpTVaHjziqoxJ1Rgtxa9VwPuffuGoqKZXKYocT5241Ck4N3Wp02r2On3A99SzXKu3dz23cQ5XE28Zn9cs8y/VU58FKVEcl1XzkJ33whS/DFzZxnfiXDj44q1NPXd1fTAAdNqss18+F8WuP7L44dHHynr6L9uOx/cr/jNuPhfH3X7lw45y+Y39k96VioX6STqrzM8ryangTVvLfl//whz+8/fbb231d3kQxyxuZbffiuQZz5rlYjT4ltJZnHgC0xKyy/Mzo5Laj4xOTmb5I/82h8b3Hr3/HHmf5xoO1UyOT+09emUOWN/lJOqnON8zyxYwsX+TIcgClM6ssb+EPWQ4AQGuQ5Z1GlgMAWoss7zSyHADQWmR5p5HlAIDWIss7jSwHALRWl2T5sWPHph7X4kWWAwBaaGho6NSpU1FEXlfM0Xb8zCrL/+WVC0kn1f/vshwAgN40OTmZFpUKWQ4AQLmR5QAAlBtZDgBAuZHlAACUG1kOAEC5keUAAJQbWQ4AQLmR5QAAlBtZDgBAuZHlAACUW5rltVrt3iApb581a9akRcHu3bvToo7buXOnPY4E6brIqlWr0qJ67tj9qD2+N/jRuUtVW3j4wOrvvfiP31y59E8770urzoy/WKOjo+m6LDt8+HBaNA/Wmu1o+fLl6YpWs/FgO2pt58VGlE5XoyE3Z3b+rdmHH344XQEA7TQ5fPbCA7fYT50sHxgYsIVNmzYlq9rB9lWctVUytyz/4IMP0qJ5aG2WW4pbcp8cPa0sF0t0K/zfoWNRxZnyF+uXv/xluq5BlvcPn7APEPbzd6/+a7quKbVmoaU9ttYbb7yhBTuiut2uq+4nmOb8jBXNfL9FK1euTIuyrK+vzx8BoB3G+9ZroX6W2yzpU5tdxNjTONp3B1boj9lcp0JdIdm2o4GW1aAat6fWJc2VuijUo19a+X59qyxkm45iIEg2mbm/zVmWr1u3zkr0mOUxr6dPPvmk8l5uvfXWuKZYWltm24IFuWe5F/7qyNa48gzFX6LoYHXG9GLZo7+aHnsW4cpy+4mbmpZ/wLI2dQFqLat9e1QdnWffe7FL8ac0e/RBFY8u20Tte0DqqbayU52FHdlO/aBmzrNcg8Eefddqf84fYfXtSMzPQxbtTiW+am7vGgDIwkX51c8Pabl+lmtZk6myfDTMm5qDlOVZPjX7fGRzrk/rM+QTq+8izvIsRJS16ftVBW2SRf1JHi3LtaD6quwlMxdflytFvNAerWMnT57MwnX5J5984lv5ZfrOQMvFLLdHvxyfc5brBNorFX+m8U9IWThR8VX7fb9fOZ8sFzVYPJ/xS+NPteBZnlwZK8+KCbo7Svp4d748zyyP9xiG83XxU187c0k2F7Nca7ds2WJ98N8j2FF04DcXALrSNNflWt4dfr+4KVxgad60SccC2ye7OMv9AnHmfMbUFH9v+HWsLWum01pleVzigaHuWX9Gw28r9WWmtWDlmvG9Sy3JcuuGXaDbNbct24LNyFm4TLRlXYLbKlu2aspyrVLYy3uDH2VRlitQ//71u+fzHbuOUS+ZnQodb3xCBgq/xbA4t6vz/uETceG0ilmeFV501VGvdDF979TXVF2yEXVvSDJbdW+4nLWXRnnmR5SFnqtanOVrwm/Ttaxtfe8z4cNbja8J7g0n0Ev0NN2yKR2IDl+vgj6ArgnX/dpLFmW5XiCreTj8K4TiRxkAmAm7Lr/wwC3fPPIPaZajffRv34rm/G/fZmIOn2BaLvkwMR91/2VA6TT6YgMA5oYsBwCg3MhyAADKjSwHAKDcyPLr9H/tF/NP2mMAAHJk+XXF7FxsP2mPAQDIkeUAAJQbWQ4AQLmR5QAAlFtHs3x8fLy2EGy/aVcAAOgWncvyNGA7Lu0QAABdoUNZvlBX5DGuzgEAXalOlm/YsCFZqGtsbOzdd99NSxtIc7VW+8Mf/rB169Zt27YNDw8nqzZv3myPX3/99aZNmwYHB+NC09/ff+7cOS3v2LEjWWgu7RYAAOU3fZavW7fu+eeft4X3339/5cqVBw4csOXnnnvuxRdftCwfGRn56U9/+tvf/tYK33777VWrVh06dMiqvfPOO9+1WMjyF154wbLc6mv5yJEjvurEiRO7wx0tLentccuWLSp/5ZVXLNo//fTTzz77bGho6L333rMSi/A///nPVq7K1uBLL71kHzJef/11VfZmJe4SAADdoX6W6y6ftnD48OGVweFwW/Fnn3325z//uS3blbGuy+2pKmTR3cRtYXJyMm4zyVTL77179x48eFDLfvEtynJdiPvluD9Vlu/atasWLseV4jt37qxWqy8EViHZ1sVdAgCgO9TPcl84c+bMa6+9dv78eUtuuzofHR218D59+rRddluiW5bb1fnJkyctjLNwY2Z7PH78+NWrVzdu3Bg1mWZ5LVx//+53v7Or83RFnuX79u2z3Smqa4UstwXrlWW5hfqFCxdeffVVW7t9+3brpz0lywEAvaNOlrfDxMREEqudZ31IuwUAQPl1KMvNlStX0nTtINt72iEAALpC57JcOp/opDgAoLt1OssBAEBrkeUAAJQbWQ4AQLmR5ehmQ0NDaREAdB2yHN2MLAfQC8hydDOyHMB8lGUOIcvRzcryPgSwOM15Drl8+XJa1E5kObrZnN+HAJCVZw4hy9HNyvI+BLA4lWUOmW+WL1u27Nq1a/fcc8+RI0cqlcqqVavuvvtuK1+6dGlaFeg4fx/ayJyYmPjiiy9soJ49e/a+++7Lwt2DauGOOzaMVcceK4HKgc6zcWgjcOvWrVk+Gm2OtXn1scces5InnnjirrvuspFs5bas+oODg/b06aef3rNnjzb57LPPbKiPj49b5fvvv99asGr79++3gW11kj2iiWKWr1+/XrcTKy40MTl81n5sYbxvfVx+cfUyXyVX/rgrWv9tSbJVUQuy/Ec/+pHNkjZudDD9/f2bNm2yoZZWBTrO34eW3zZEbTqzSW3FihWvvfbalStX6ma5loGFonH49ttvf/XVV1q2YfzrX//aFt59910bybZgk62N55UrV9owVpbbU41ni+rR0VGVPPTQQzbgR0ZGbMBbtZ/85CdjY2Nk+awUs9xO+7p16+ouNOGB7cF89fND1y6d9ywf+69H7Kkq+FYXHrjlm+Xf1yZW3542CvUWZLkNoOHhYRs39knw0qVLVqhLc2DBxe9Dm9cef/zxLL/W2blzZ90st9FrU6FvBXSYxuGOHTts9NqltkajXS/deeedluUW8FnI8o8++ii5LteGTbLcRvszzzxDls9KMcvnxrPcMruY5d8s/2ev6VkeL2iTRkGetSTL7dEGmX/H7oXAgovfhz/72c/6+/vtE6c92tM77rjDslyDdmBg4Lbbbou/1eQ7diwUfcf+5ptvZvlo/Prrr218btmyxYL5/vvvv+uuuxTVhw4dssHs1+XaPM7y5Dt2W/vyyy+T5bPS8iy38PZgjq/LL/7nv6mmR7gVWt7bo2e5fQ74trmC+WY5sJi16n0IoDeVZQ4hy9HNyvI+BLA4lWUOIcvRzcryPgSwOM15DtG/HusYshzdbM7vQwAoEbIc3YwsB9ALbhgCAABlxnU5utkQ1+UAegBZjm5GlgPoBWQ5uhlZDqAX1M/y4eHhJUuW3FSwY8eOtCqwiJHlAHpB/Sy3GTCN8VxaFVjEyHIAvWCmWX4sqJvlfoe0+duwYUNaBMzDrLJcf6e6+SBs8res9Qexm1QAgDaZUZZbiluhltOqWbZ27Vpf1s0q9Jf9dYeALL89gBY0Ufb19dmy1Vm2bJlW+eZZPhvWajWroJq6U5AtPPDAA14ZmFaS5TaEdOMfDVTdhcIGsAahBp4eK+GeK7r9lJX4wLbAtpGptVk+kpXieiPYsu4hrc+42txrtupTLwDEmmW5Ldx8881xkDfPcqVvlt+DT3easgXNZYp2TZqa+zZv3qwFmyh9hlVTuhev17RtNT9qPlUdYFrFLNcI1KBVlmtE2XjzLPchrTC2T5A2mFXtSLgJulbpXtHa1ge/hq4PbDWo8iyMebUMAC3ULMufeuopPfUgr5vlmhC1rMmrbpbbo99HMsly51luq7wpPQ4GUV1genGWe+5m+W15LaRt6Gpk7glUTQtm+fLlqpZEtbfjbfomPqStxDf3crIcQDs0y3JjU14c5DfVy/J28I8CSdgDs9Lo9+V+5e3X5a3CiAXQefWz/KuvvkoiXJYsWZJWbYM94deTWmZmxHx0OMv5HRCABVE/y7MQ50MFw8PDaT1gERtqkOUA0E0aZjnQBchyAL2ALEc3I8sB9AKyHN2MLAfQC8hydDOyHEAvIMvRzchyAL2ALEc3I8sB9IKGWc7/SUMXGCLLAfSA+lm+sH8rBmgVshxAL6if5UOFe57eHNzU4G+46pYVjf5euv6mOtB5jbJ87dq1/rcFW6h5m/GfbfeS+DaDsfjPwmdT30S6UVvdvzG3J9yCyLuhPyNv1SrhBnHxX5VPtsqizuuP1WdRtfi4in+K0TvjHYvXau/G927t+5+4T06I+F+895Pjf9m+Eu47p7NRme7GiX4XnGRqUjtZdFzeDa9se1TPtUp3dLSS+FT4Vir0bdcG8SpJzgzQQjPKcktxK3zrrbfqZrneZk2Q5VgojbK8r69v//79aeks1YK4pHmW2x6TILQS60lc4ppked38y0KWKN3tUaGivPR3aJMs9xzKwslRhRlmufpjPVSc112b5XtPPmfUPRYdiLqkk+y3tBHbl7rhR1RXoywXb/NIuI+tl2/Ib3PnT7NCbEv8CcBa2Lx5s9/3tpjl086TwHw0y/KzZ88mQV43y+NZRgNXtzXzd+OqwNfqDVD3PQy0VqMsj2ni9qnWJ1/PM43VWn7bU6fo0jgfDbc23xCuvGv5vVA95LKpGZBEvlceDRQMewI1a091AWobek5Xwjdh3m0Lj/g9tSdcvHrU+XWznnpW6QONNoyT20u0EMebFtQfvz6Orzh1BnSM3tssz13fUE+tsjXoc4WON8vbV2vqQ5yFPsMcCTeJz/K/qy/eeXXPjzpuQXVU38pVR0+zBoGtF2VDuL+tCtW+mtWrb/TyxVmukuRFB1qrWZZfCLIoyOtmefFT/6pwu3EV2hC3ChrZehv4extotyTLLwb+VDGp8NCI9fHp07ro7qjZ1K9JR0M6eshpolc78TfnqtDkbqdxZVtWQniGaS8qLHbVE8I2VBppk8HwGTp+u8XvPrXgqzz8vGaWX/tqlQeznQdV807qMd6RVTt37lzSeJZ32K9c9XRPyPIsujWiH7jK/fvqOAu19yw/OV5Z/FVIstx7or17ZT8i7cjmK++M78grqxtxg9rKP17oaTHLuS5HWzXLciX3U0895UFeN8uz/IN5LXz21BWAF2b5+8FmAb0NVCd+7wFt0vy6vBZ+v6tvuW1AVsKVrsan4lMlPrwr4bfOcQsq1y9TszxvdE3p47+Y5XEsSVzZc0JRobhSr7ThaP4b6MGgEt5NCo894fflnmSKMf16WN2I331qZDS6kFVnfC9xluv8aEGNa3f+qOz3TvppVA/j39arh57l2nYwfMegTbQLrdIxhn59+0vrwfxjih+IYlJra4H6kGS5uvenP/1JB+79VONW50hQCylubWoAVMLr4guqrwZt5Kg/cTse/77JYP7JQE8///xzu0a6fPnyoUOHVBOYv2myvCitCixizbN8bpRSmpdbTpFQCZmUrpslRX5aulh54E3LMts/dtQ1GK6Pp62W8Kt2oIzqZ/nw8PCSJUvSGL/pph07dqRVgUWsHVkOAItN/SwHugNZDqAXkOXoZmQ5gF5AlqObkeUAesENQwAAoMy4Lkc3G+K6HEAPIMvRzchyAL2ALEc3I8sB9AKyHN2MLAfQC8hydDOyHEAvaEGW79u3zx537dqVrgAWWpzlBw8e1EJ8t9ORwJ8Ci4HGqo1MH7TN1Z1+Z7gtukNrstxH0t69e7dv3z42Nnbs2DGtmlIV6Kw4y21Yng5sirRHG6g22SnLbdxmecZrDPtWQOd5DGtk2oB86623tKDBqVFqQ/fTTz+1cWtPbdnmW61VNTVia1XTxjxju4u1JsstuW2itOHiY0hjiyseLKzkO/Z9gS0oy21+TLI8HsPxhkAnxVluyxqTGpxZ9GWSL8TzrQ1jbW6P+vyqCrZgT7Mw+L/dDbpIa7I8yz8/+reXI+FDYlwN6Lwkyw8GWf6dpGe5P82mfgMPLAiNUgtdW9CXSb5Ky6qQZLnC2we5Hv3bJrK8u7UgyxvRSAIWEP/2DT3Ccx29qS1Zbp/++K0MFgOyHD2CLO9xbclyYJEgywH0ArIc3YwsB9ALyHJ0M7IcQC8gy9HNyHIAvYAsBwCg3MhyAADKjSwHAKDcyHIAAMqNLAcAoNzIcgAAyo0sBwCg3MhyAADKjSwHAKDcyHIAAMqNLAcAoNzIcgAAyo0sBwCg3MhyAADKjSwHAKDc/h/DfWJ8bkYX7gAAAABJRU5ErkJggg==>

[image25]: <data:image/png;base64,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>

[image26]: <data:image/png;base64,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>

[image27]: <data:image/png;base64,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>

[image28]: <data:image/png;base64,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>

[image29]: <data:image/png;base64,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>

[image30]: <data:image/png;base64,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yblto9euXfvSSy9luZy/++67trP/+uuv79aYZdeuXUskthratff29uo0lnNL/PGPf7QNusm5SfjmzZvtocEyd+zYYenLly9XlHNrOvYEAACg9agg53NELLHNJPUDAACg5WienGf17NEbAvtyAABoE5oq5wAAADAXIOcAAACFBzkHAAAoPPcMAwAAQMFhdw6tjIV4mgUA0Iog59DKIOcA0CYg59DKIOcAMBtmvIaMjY2lWXMMcg6tzIxvRQCArFBrCHIOrUyBbkUAWIAUaA1BzqGVKdCtCAALkEatIbdGTo8u/6l9bo9divOvrF9il+zjOTcO7JZlnOPpGsxWzpcsWfLll18eOHDg6NGjX3311eXLl9etW2fHjRs3pqYATcdvxU8//fTChQs7d+68dOmSHZctW5aFlwyNh7/qb2GchTf82vGRRx4xy9u3b9+tBaCJWByeP3/eYnJiYuKZZ56xaLQw7urq2rdv3+nTp9euXXv48OGBgYH9+/f/+te/vnHjhtnrdPny5WNjY93d3YODg/39/bYmb9261SL/1Vdf7e3tNTOzt4Dfu3dv2iRUp1zO16xZ09nZWTFRA9fsq//zZJxfUc6j65Nyru3dMvnKJBog54sXL7aEhU5HR4etjxZelrBATE0Bmo7fihaWb7zxxuOPP27pX/3qV7a62QpYUc47AnerAGguikNbUS1EPRofffTR7du3mzybutupLq1YsUL2knN7SLWF19TabCzHanjsscey8PorC3Uzs33X8ePHkfO6KJfzV155xYa3YqIGvju39LXuO9p/88Rh26lLzicG+5SZ5bvzy0/+zPLNxo6Wo6tuU5EGyPm5c+fefPNN350rM7UDmA/iW9H2Lu+++67tzrds2WLr3erVq22Ns+i1oH3qqafsbnzwwQczducw35julkqleHc+NDRk+3KLTIvSl156SQ+jtuRa3FqgSs7tVMVjOX/vvff++te/+u48C+GNnNdFuZzPDN+CX/mvxeVyfvPoZ3YqS9+Lx4lmyDnAQqZRtyIAtCeNWkN8dy5dt8TVN3/ncq4tuPQ+/u38zjZ95S9czi1dQ9GRc2hlGnUrAkB7UqA1BDmHVqZAtyIALEBmvIZcv349zZpjkHNoZWZ8KwIAZIVaQ5BzaGUKdCsCAMwG5BxaGeQcANoE5BxaGeQcANoE5BxaGeQcANoE5BxaGeQc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>

[image31]: <data:image/png;base64,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>

[image32]: <data:image/png;base64,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>

[image33]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEkAAAA0CAYAAADGzxXDAAAEBklEQVR4Xu2Z20/iQBTG/ct3vaJyExBQQBDw8uZfow/rgxtfzGokMTFZLoKe5RudoXy0pVQWZ9n+kpPtDO2cr9+emU7rysqckS+G9VgJi140rMdKWDQ4OztTcXp6KicnJ9JsNqXRaEq90ZB6vS7Hx8dSq9WkWq3JUbUqlaMjKVcqUi5XpFQqq+Orqyse1hXWYyUsGsCg19fXiRg4Y8AxkLe3Nzk/P5fb21s5LJUCGcV6rIRFA1QQTOn3+/KCeNHxIj0dvfd/uz0dPWUUTHp+fpabm59SPDiYahTrsRIWDTDF3EwyBuHYx6SnpydptVry4/pa8oWir1Gsx0pYNMAaBJOUQW4mwSBjzqRJj4+P8vDwIHd3d3J5eSn5fJ5TGFiPlbBogEUaJl1cXMwU2qRkMjkWmVyOUxhYj5WwaICnmKoksxb5TLVuz1QSju+HFfTrXsf9sKpakslmOYWB9VgJiwZ4zGuTRuY4DHKZatqkjjM63eG6NpC9zBKahH0QHvM8ncIETErvZTiFgfVYCYsG2CjCJFU5juoZf6I5pplbFXW70v6opFR6j1MYWI+VsGiAnTQ2iO7moK0NGq1F4yZ11VTTJiXTaU5hYD1WwqIBXjNg0ti682EEV49bBWmDtEmJZIpTGFiPlbBogHcvPM6NEU6zZjBImxRPJDmFgfVYCYsGeFFFJfEiHCawa9+NJziFgfVYCYsGeJM3lUSVM1k97hWkAzv2nXicUxhYj5WwaIA3eGWSwxh3c/wNarc7yqTt3SU06eDwUPpDk3jqhAmYFNvZ5RQG1mMlLBrgEwdMmqya8erxq6DfH6FM2t7hFAbWYyUsGhSKbFJ3FH7mkEHapK3YNqcwsB4rYdGgUCiqRzdPnTABkzZjMU5hYD1WwqJBvlBQJk1UiVdQ9XAlbWwtoUn7+Xwwk1xM4YBJ65tbnMLAeqyERYPc/rtJPHXCBExa29jkFAbWYyUsGmRz+2qn3O50VLUEqRivUCatb3AKA+uxEhYN8LkVN8c3HCYwzupSmpTNjv4IMIf4vrbOKQysx0pYNMDnVnxNxMcyfAtKpFLqcwfe5vGyincxvGpgJ42NIvZBeMzjKYZFGmsQphgqCAZ9W13jFAbWYyUsetGwHith0YuG9URERET8b2Ah5MWQ23+DReSYKyyY27MS5Pog5/gR9Pqg5wVCD8aD+rV1FU7rc8Pv92lj8O98nrPfb5yZ8RqM+6YJ42MvvM7hfm5ruD+IrrngNiD3cVvz1SYB9HE/tz9F0P8J53lexvA1bnidw/3c1rj1B+0LhfOG/W7e2fbq52MvvM7hfm5ruD+Irk/BA/ENc/j1O3/zg6/lcflYt53HQc+zHjbinxAdERERERERERHxzh8wYvQdvAJzTQAAAABJRU5ErkJggg==>

[image34]: <data:image/png;base64,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>

[image35]: <data:image/png;base64,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>

[image36]: <data:image/png;base64,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>

[image37]: <data:image/png;base64,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>

[image38]: <data:image/png;base64,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>

[image39]: <data:image/png;base64,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>

[image40]: <data:image/png;base64,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>

[image41]: <data:image/png;base64,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>

[image42]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAkAAAAJBAMAAAASvxsjAAAAMFBMVEX///+Llqs9VXPs+f/V8//q+f/s+v/w+//z/P/3/f/2/f/6/v/6//8AAAAAAAAAAAAR13G2AAAAAXRSTlMAQObYZgAAADJJREFUeF5jFGRgYPjPwmzAwHCGheE9kMPEAAIgNgeQ3aQkBWSzpTGcYRABCgswgtUDAMZ3BzbeNLnxAAAAAElFTkSuQmCC>

[image43]: <data:image/png;base64,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>

[image44]: <data:image/png;base64,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>

[image45]: <data:image/png;base64,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>

[image46]: <data:image/png;base64,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>
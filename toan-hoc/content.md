# TOÁN HỌC THCS — TỔNG HỢP TOÀN TẬP

---

Bạn đã từng thắc mắc tại sao mình phải học những thứ này chưa? Phân tích thừa số nguyên tố, ƯCLN, định lý Pythagoras, căn bậc hai — học xong rồi quên, ra đời không dùng, cuộc sống vẫn ổn.

Câu hỏi đó hoàn toàn hợp lý.

Nhưng cũng hợp lý không kém là câu hỏi ngược lại: tại sao loài người lại phát minh ra những thứ này? Ai đó, ở đâu đó, đã ngồi nghĩ và thấy rằng đây là điều đáng nghĩ. Không phải vì được trả lương. Không phải vì sắp thi. Mà vì thế giới này có cấu trúc, và họ muốn hiểu cấu trúc đó.

Toán học là ngôn ngữ mà vũ trụ dùng để vận hành. Mình học toán không phải để giỏi tính nhẩm — mà để nhìn thấy cái cấu trúc ẩn dưới bề mặt hỗn loạn của mọi thứ.

---

## PHẦN I: SỐ VÀ SỐ HỌC

### Số 0 và số âm — thứ không tồn tại mà lại tồn tại

Số 0 tưởng đơn giản. Nhưng người La Mã không có số 0. Người Hy Lạp cũng không. Cả hai nền văn minh đỉnh cao của thế giới cổ đại vận hành mà không có số 0 trong vài trăm năm.

Câu hỏi đặt ra là: làm sao bạn tính 100 - 100 nếu không có số 0? Làm sao bạn viết 105 mà không có chữ số chỉ vị trí rỗng?

Họ không có cách viết. Và điều đó làm toán học trở nên vô cùng khó.

**Người tìm ra:** Brahmagupta, nhà toán học Ấn Độ, năm 628 SCN. Ông không chỉ định nghĩa số 0 — ông còn đặt ra các quy tắc tính toán với nó: a + 0 = a, a × 0 = 0. Quan trọng hơn, ông định nghĩa số âm là khoản nợ và số dương là tài sản — cách đặt vấn đề vẫn còn đúng đến tận hôm nay.

**Câu chuyện neo móc:** Brahmagupta viết năm 628, nhưng mãi đến thế kỷ 12 người Ả Rập mới dịch sách ông, và thêm vài thế kỷ nữa châu Âu mới tiếp nhận số 0. Có nghĩa là từ khi số 0 được phát minh đến khi cả thế giới dùng nó mất khoảng 600 năm. Những thứ đúng không tự nhiên thắng — chúng chỉ thắng chậm.

---

### Số nguyên tố — những viên gạch không thể phá nhỏ hơn

Có bao nhiêu số nguyên tố? Câu hỏi này Euclid đã trả lời từ khoảng năm 300 TCN — và câu trả lời là vô hạn. Cách ông chứng minh chỉ cần một trang giấy, và vẫn được dùng trong sách giáo khoa 2.300 năm sau.

Số nguyên tố là số chỉ chia hết cho 1 và chính nó: 2, 3, 5, 7, 11, 13... Mọi số tự nhiên lớn hơn 1 đều viết được dưới dạng tích của các số nguyên tố theo đúng một cách (định lý cơ bản của số học). 12 = 2² × 3. 100 = 2² × 5². Không có cách nào khác.

Đây là nền tảng của mật mã học hiện đại. Thẻ ngân hàng của bạn, giao dịch internet của bạn — tất cả được bảo mật bởi thực tế là nhân hai số nguyên tố lớn với nhau rất dễ, nhưng phân tích ngược lại rất khó.

**Người tìm ra:** Eratosthenes, khoảng 240 TCN, phát minh ra "sàng Eratosthenes" — cách tìm tất cả số nguyên tố nhỏ hơn một số n bằng cách loại dần bội số. Thuật toán này vẫn là một trong những cách hiệu quả nhất cho số nhỏ, 2.200 năm sau.

**Câu chuyện neo móc:** Cũng chính Eratosthenes đó, bằng bóng gậy và góc mặt trời, đo được chu vi Trái Đất với sai số chưa đến 2% — năm 240 TCN, trong khi không có máy móc gì và chưa ai bay lên nhìn xuống. Ông là thủ thư trưởng của Thư viện Alexandria, người ta gọi ông là "Beta" — người giỏi thứ hai trong mọi lĩnh vực — ngụ ý ông không đủ vĩ đại ở bất cứ thứ gì. Hai nghìn năm sau, "Beta" đó đo được Trái Đất chính xác hơn nhiều phương pháp được dùng cho đến thế kỷ 18.

---

### ƯCLN và BCNN — thuật toán cổ nhất còn sống đến hôm nay

Ước chung lớn nhất (ƯCLN) và bội chung nhỏ nhất (BCNN) ra đời từ nhu cầu rất thực: chia đất, chia bánh, lên lịch — những thứ cần phải chia đều cho nhiều người hay nhiều chu kỳ.

ƯCLN của 12 và 18 là 6 — số lớn nhất chia hết cho cả hai. BCNN của 4 và 6 là 12 — số nhỏ nhất là bội của cả hai.

Thuật toán Euclid tìm ƯCLN: chia a cho b, lấy phần dư r, rồi tìm ƯCLN(b, r). Cứ thế cho đến khi phần dư bằng 0. Cái ƯCLN cuối cùng chính là b khi r = 0.

ƯCLN(48, 18): 48 = 2×18 + 12 → ƯCLN(18, 12): 18 = 1×12 + 6 → ƯCLN(12, 6): 12 = 2×6 + 0 → kết quả là 6.

**Người tìm ra:** Euclid, khoảng 300 TCN, trong bộ *Elements* gồm 13 quyển — bộ sách toán học được in lại nhiều nhất lịch sử, sau Kinh Thánh. Thuật toán này là thuật toán còn được dùng liên tục lâu nhất trong lịch sử toán học.

**Câu chuyện neo móc:** Vua Ptolemy I hỏi Euclid: "Trong hình học có con đường nào ngắn hơn không?" Euclid trả lời: "Không có con đường hoàng gia trong hình học." Câu đó không phải lịch sự — đó là sự thật. Toán học bình đẳng tuyệt đối: vua cũng phải chứng minh như thường dân.

---

### Phân số và số hữu tỉ — phát minh của người chia bánh

Người Ai Cập cổ đại 3.500 năm trước dùng phân số đơn vị: 1/2, 1/3, 1/4. Họ viết 2/5 là 1/3 + 1/15. Không bao giờ dùng tử số khác 1. Có cả bảng tra cứu để chuyển đổi.

Cách đó kỳ cục, nhưng nó hoạt động — đủ để xây kim tự tháp, chia lương thực cho công nhân, tính thuế.

Phân số a/b là số hữu tỉ khi a, b nguyên và b ≠ 0. Mọi số hữu tỉ đều viết được dưới dạng số thập phân hữu hạn hoặc vô hạn tuần hoàn. 1/3 = 0,333... 1/7 = 0,142857142857...

**Người tìm ra:** Không có một người duy nhất — phân số xuất hiện độc lập ở Ai Cập, Babylon, Ấn Độ, Trung Quốc. Nhưng người hệ thống hóa và đặt nền tảng lý thuyết là Brahmagupta (cùng người phát minh số 0), khoảng 628 SCN.

**Câu chuyện neo móc:** Người Babylon tính các phân số như 1/3 hay 1/5 rất thành thạo — họ có bảng đất sét ghi sẵn. Cách họ viết số là hệ 60 (sexagesimal), không phải hệ 10. Đó là lý do đến nay 1 giờ vẫn là 60 phút, 1 phút vẫn là 60 giây, và vòng tròn vẫn là 360 độ — tất cả là di sản từ hệ số 60 của Babylon 4.000 năm trước.

---

### Số vô tỉ và căn bậc hai — bí mật bị giết chết

Pythagoras và học trò của ông tin rằng mọi thứ trong vũ trụ đều là số hữu tỉ — tức là mọi số đều viết được dưới dạng p/q với p, q nguyên. Đây không chỉ là quan điểm toán học. Đây là tín điều tôn giáo. Giáo phái Pythagoras ăn chay, cấm ăn đậu, thờ số nguyên như thần linh.

Rồi một học trò tên Hippasus phát hiện ra √2 không phải số hữu tỉ. Cạnh huyền của tam giác vuông cân cạnh 1 không thể viết là p/q với p, q nguyên bất kỳ.

**Người tìm ra:** Hippasus của Metapontum, khoảng 450 TCN. Bằng chứng ông đưa ra là một chứng minh phản chứng đơn giản mà học sinh lớp 9 hiện nay vẫn học — giả sử √2 = p/q tối giản, suy ra p² = 2q², suy ra p chẵn, suy ra q chẵn, mâu thuẫn.

**Câu chuyện neo móc:** Theo ghi chép cổ, Hippasus bị ném xuống biển. Có thể là truyền thuyết, nhưng câu chuyện nắm bắt được điều có thật: giáo phái Pythagoras cực kỳ khó chịu với phát hiện này, và Hippasus bị trục xuất hoặc mất tích. Lần đầu tiên trong lịch sử, ai đó bị trừng phạt vì... đúng về toán học. Đây là lý do số vô tỉ được gọi là "irrational" — theo nghĩa đen là "không thể diễn đạt bằng tỉ số", nhưng cũng mang nghĩa bóng là điều mà lý trí (của Pythagoras) không chấp nhận được.

Căn bậc hai của một số a là số x sao cho x² = a. √9 = 3. √2 ≈ 1,41421356... vô hạn, không tuần hoàn. Đó là số vô tỉ.

---

### Lũy thừa và logarithm — nhân triệu lần trong một bước

1 km = 1.000 m = 10³ m. Khoảng cách từ Trái Đất đến Mặt Trời ≈ 1,5 × 10¹¹ m. Đường kính nguyên tử hydrogen ≈ 1,06 × 10⁻¹⁰ m. Lũy thừa là ký hiệu nén cho phép viết những con số cực lớn hoặc cực nhỏ mà không mất hàng chục ký tự.

aᵐ × aⁿ = aᵐ⁺ⁿ. (aᵐ)ⁿ = aᵐⁿ. Những quy tắc này biến phép nhân thành phép cộng — và đó chính xác là nguyên lý của logarithm.

**Người tìm ra:** John Napier, Scotland, 1614, phát minh ra logarithm. Mục tiêu thực tế là giúp các nhà thiên văn học tính toán nhanh hơn — những phép nhân số lớn hàng tiếng đồng hồ có thể rút xuống vài phút bằng bảng logarithm. Lũy thừa với số tự nhiên thì cổ đại hơn nhiều, xuất hiện ở Babylon từ 2.000 TCN.

**Câu chuyện neo móc:** Khi Napier công bố bảng logarithm, nhà thiên văn học Henry Briggs đi từ London đến Edinburgh chỉ để gặp ông — một chuyến đi mất nhiều ngày. Hai người ngồi nhìn nhau im lặng 15 phút trước khi ai đó lên tiếng. Briggs nói: "Thưa ngài Napier, tôi đã vượt một hành trình dài chỉ để nhìn thấy người phát minh ra thứ tuyệt vời nhất mà tôi từng thấy." Bảng logarithm sau đó là công cụ tính toán chủ yếu của nhân loại suốt 350 năm, cho đến khi máy tính điện tử ra đời năm 1970s.

---

## PHẦN II: ĐẠI SỐ

### Đại số và phương trình — khi x thay thế cái chưa biết

Đại số bắt đầu từ một câu hỏi đơn giản: nếu tôi biết một số là bao nhiêu khi cộng thêm 5 thì được 12, tôi tìm số đó thế nào?

Người cổ đại làm bằng lời: "Có một số, cộng thêm 5 thì được 12, số đó là 7." Đó là lý luận đúng nhưng chậm và không mở rộng được. Đại số là cách viết x + 5 = 12, tức là dùng ký hiệu để đại diện cho cái chưa biết rồi thao tác đại số trên ký hiệu đó.

**Người tìm ra:** Muhammad ibn Musa al-Khwarizmi, nhà toán học Ba Tư, khoảng năm 820 SCN. Ông viết cuốn *Al-Kitab al-mukhtasar fi hisab al-jabr wal-muqabala* — Cuốn sách tóm tắt về tính toán bằng hoàn thành và cân bằng. Chữ "al-jabr" trong tên sách trở thành chữ "algebra". Chính tên ông — al-Khwarizmi — được đọc méo thành "algorismus" rồi thành "algorithm". Tên một người thành tên một khái niệm.

**Câu chuyện neo móc:** Al-Khwarizmi không dùng ký hiệu x hay y — ông viết hoàn toàn bằng lời. "Phương trình" đầu tiên trong lịch sử là một đoạn văn xuôi. Ký hiệu toán học hiện đại mà học sinh dùng hôm nay đến từ François Viète người Pháp, năm 1591 — tức là hơn 700 năm sau al-Khwarizmi. Ý tưởng lớn đi trước ký hiệu diễn đạt nó rất lâu.

---

### Hằng đẳng thức và phân tích đa thức — bảy công thức nhớ cả đời

(a + b)² = a² + 2ab + b². (a - b)² = a² - 2ab + b². (a + b)(a - b) = a² - b². Và thêm bốn công thức nữa cho lập phương.

Những công thức này không phải quy ước tùy tiện. Chúng là hệ quả của phân phối — nhân mở ngoặc ra thì ra đúng như vậy, không có lựa chọn khác. Học sinh hỏi: "Tại sao phải nhớ?" Câu trả lời là: nhớ để nhận ra và rút gọn nhanh — x² - 4 nhìn ngay ra (x+2)(x-2) thay vì ngồi thử từng nghiệm.

**Người tìm ra:** Ý tưởng có từ Euclid, nhưng dạng đại số ký hiệu hiện đại là François Viète (thế kỷ 16) và René Descartes (thế kỷ 17). Tam giác Pascal — cách nhớ hệ số (a+b)ⁿ — đặt tên theo Blaise Pascal, người lập bảng này năm 1653. Nhưng bảng đó người Trung Quốc đã biết từ thế kỷ 13, và người Ấn Độ còn sớm hơn.

**Câu chuyện neo móc:** Pascal năm 19 tuổi chế tạo máy tính cơ học đầu tiên trong lịch sử — không phải để nổi tiếng mà vì cha ông là quan thuế, phải tính toán số liệu mỗi ngày, Pascal thấy mệt hộ và quyết định làm máy thay thế. Máy đó có thể cộng và trừ. Ông làm 50 chiếc. Đắt hơn thuê người tính rất nhiều, không ai mua. Nhưng ý tưởng tự động hóa tính toán sống đến ngày nay.

---

### Phương trình bậc nhất — nền tảng của mọi mô hình

ax + b = 0 với a ≠ 0. Giải ra x = -b/a. Đơn giản đến mức tưởng tầm thường.

Thực tế không như vậy. Mọi mô hình tuyến tính trong kinh tế, vật lý, kỹ thuật đều quy về phương trình bậc nhất hoặc hệ phương trình bậc nhất. Tính giá điện theo bậc thang, tính lãi đơn, chia tỉ lệ nguyên liệu — tất cả đều là phương trình bậc nhất hay hệ phương trình.

Hệ hai phương trình bậc nhất hai ẩn: tìm điểm giao của hai đường thẳng trên mặt phẳng. Có thể vô nghiệm (song song), vô số nghiệm (trùng nhau), hoặc đúng một nghiệm (cắt nhau).

**Người tìm ra:** Bài toán hệ phương trình bậc nhất cổ nhất còn lại là bài toán Ai Cập trong *Papyrus Rhind*, khoảng 1650 TCN. Phương pháp khử Gauss để giải hệ phương trình — ký hiệu học sinh học ở lớp 9 — đặt tên theo Carl Friedrich Gauss, nhưng người Trung Quốc đã dùng phương pháp tương tự trong *Cửu Chương Toán Thuật* từ khoảng thế kỷ 1 TCN.

**Câu chuyện neo móc:** Gauss năm 10 tuổi được thầy giáo giao bài tập tính 1 + 2 + 3 + ... + 100 để cả lớp bận rộn hết buổi học. Gauss nộp kết quả trong vài phút: 5.050. Cách ông làm: ghép 1+100=101, 2+99=101... thành 50 cặp, mỗi cặp bằng 101, vậy tổng là 50×101=5.050. Thầy giáo đó không nghĩ ra cách này. Gauss sau đó trở thành nhà toán học lớn nhất thế kỷ 19 — "hoàng tử toán học" — phát minh trong số học, hình học, vật lý, thiên văn học.

---

### Phương trình bậc hai — bài toán cổ đại với drama hiện đại

ax² + bx + c = 0. Nghiệm: x = (-b ± √(b² - 4ac)) / 2a. Công thức nghiệm này học sinh lớp 9 thuộc lòng, nhưng ít ai biết câu chuyện phía sau.

Người Babylon đã giải phương trình bậc hai 2.000 năm TCN — bằng lời, không có ký hiệu, và không dùng số âm (vì họ không có). Phương pháp hoàn chỉnh phương trình (completing the square) có từ thời đó.

**Người tìm ra dạng tổng quát:** Al-Khwarizmi lại là người đặt nền tảng, khoảng 820 SCN, phân loại phương trình bậc hai thành sáu loại (vì không có số âm nên phải xét từng trường hợp hệ số). Công thức nghiệm tổng quát như học sinh biết hôm nay là đóng góp của nhiều người qua nhiều thế kỷ.

**Câu chuyện neo móc:** Phương trình bậc ba — ax³ + bx² + cx + d = 0 — cũng có công thức nghiệm, nhưng câu chuyện phía sau là một trong những drama nhất lịch sử toán học. Niccolò Tartaglia phát hiện ra công thức năm 1530, chia sẻ bí mật cho Gerolamo Cardano sau khi Cardano thề giữ bí mật tuyệt đối. Sáu năm sau, Cardano công bố trong cuốn *Ars Magna* — có ghi công Tartaglia, nhưng vẫn công bố. Tartaglia giận dữ, thách Cardano đấu toán công khai. Cuộc đấu không đến đích vì học trò của Cardano là Lodovico Ferrari đứng ra đấu thay thầy và thắng. Tartaglia chết trong cay đắng. Công thức ngày nay mang tên Cardano.

---

### Bất phương trình — khi bằng nhau chưa đủ

ax + b > 0, ax + b ≤ 0 — bất phương trình bậc nhất. Khác với phương trình ở chỗ nghiệm là một tập hợp (khoảng, đoạn) thay vì điểm cụ thể.

Nguyên tắc quan trọng: nhân hay chia hai vế cho số âm thì đổi chiều bất đẳng thức. 3 > 2, nhân cả hai vế với -1: -3 < -2. Học sinh hay quên bước này và sai kết quả.

Bất phương trình bậc hai — ax² + bx + c > 0 — có nghiệm là hợp hoặc giao của các khoảng, tùy vào hướng parabola và vị trí nghiệm.

**Người tìm ra:** Bất đẳng thức có từ rất cổ trong toán học Hy Lạp. Ký hiệu > và < do nhà thiên văn học Thomas Harriot đặt ra năm 1631 (sau khi ông mất, xuất bản trong di cảo). Ký hiệu ≤ và ≥ đến sau đó. Lý thuyết bất phương trình hệ thống hóa vào thế kỷ 18-19.

**Câu chuyện neo móc:** Thực ra bất phương trình quan trọng hơn phương trình trong cuộc sống thực. Khi thiết kế cầu, kỹ sư cần tải trọng ≤ giới hạn an toàn — không phải bằng đúng. Khi tính ngân sách, bạn cần chi tiêu ≤ thu nhập. Phương trình là đặc biệt, bất phương trình là phổ thông.

---

## PHẦN III: HÀM SỐ VÀ ĐỒ THỊ

### Hàm số bậc nhất và hệ trục tọa độ — con ruồi trên trần nhà

Hàm số y = ax + b là một đường thẳng trên mặt phẳng tọa độ. a là hệ số góc — độ dốc của đường thẳng. b là tung độ gốc — nơi đường thẳng cắt trục Oy.

Nhưng trước khi có đường thẳng, phải có mặt phẳng tọa độ. Và cái đó không tự nhiên mà có.

**Người tìm ra:** René Descartes, triết học gia và toán học người Pháp, khoảng 1637. Câu chuyện — có thể là giai thoại nhưng được kể lại rộng rãi — là Descartes nằm trên giường (ông có thói quen nằm đến trưa, dù là nhà tư tưởng lớn), nhìn con ruồi bò trên trần nhà và tự hỏi: làm sao mô tả chính xác vị trí của con ruồi đó bằng số? Câu trả lời: hai con số — khoảng cách đến hai bức tường kề nhau. Hệ trục tọa độ Descartes ra đời từ đó.

**Câu chuyện neo móc:** Descartes cho rằng toàn bộ hình học có thể làm bằng đại số — mọi bài toán hình học đều chuyển thành tìm điểm thỏa mãn phương trình. Đây là bước nhảy vọt vì trước đó hình học và đại số là hai môn riêng biệt. Sau Descartes, chúng trở thành một. Tên đầy đủ của ông là René Descartes, với tên tiếng Latin là Cartesius — đó là lý do hệ trục tọa độ gọi là "hệ trục Cartesian".

---

### Hàm số bậc hai — parabol và những bài toán tối ưu

y = ax² + bx + c với a ≠ 0. Đồ thị là parabol — mở lên khi a > 0, mở xuống khi a < 0. Đỉnh parabol tại x = -b/2a.

Parabol không phải đường cong đẹp tùy tiện. Quỹ đạo của viên đạn bắn lên (bỏ qua sức cản không khí) là parabol. Gương phản xạ của đèn xe ô tô, đèn pin, kính thiên văn phản xạ — mặt gương là parabol vì tia sáng song song từ tiêu điểm phản xạ ra thành chùm song song.

Bài toán tối ưu: tìm giá trị lớn nhất hoặc nhỏ nhất của y. Đó chính là tọa độ đỉnh parabol.

**Người tìm ra:** Apollonius của Perga, khoảng 200 TCN, nghiên cứu các đường conic (ellipse, parabol, hyperbola) trong bộ sách *Conics* 8 quyển. Ông đặt tên "parabol", "ellipse", "hyperbola" — những tên đó còn dùng đến hôm nay. Apollonius không có ứng dụng thực tế nào trong đầu — ông thuần túy nghiên cứu hình học vì tò mò. Hai nghìn năm sau, Galileo chứng minh đạn đạo là parabol, và Kepler dùng ellipse để mô tả quỹ đạo hành tinh.

**Câu chuyện neo móc:** Năm 212 TCN, lính La Mã tấn công Syracuse. Archimedes — người bạn của Apollonius — thiết kế vũ khí phòng thủ cho thành phố. Theo ghi chép, ông dùng gương parabol phản xạ ánh sáng mặt trời để đốt thuyền giặc. Thực ra chuyện này khả năng không đúng về mặt vật lý, nhưng câu chuyện phản ánh sự thật: trong 200 năm TCN, ở Hy Lạp cổ đại, người ta đã hiểu tính chất quang học của parabol tốt đến mức câu chuyện đó nghe có vẻ hợp lý.

---

## PHẦN IV: HÌNH HỌC PHẲNG

### Euclid và *Elements* — cuốn sách thống trị 2.000 năm

Euclid, khoảng 300 TCN, viết *Stoicheia* (Elements) — 13 quyển, bắt đầu từ 5 tiên đề và 5 công thức chung, từ đó chứng minh 465 mệnh đề hình học bằng suy luận logic thuần túy.

Tiên đề là những điều nhận mà không cần chứng minh vì chúng "hiển nhiên": qua hai điểm có đúng một đường thẳng; tất cả các góc vuông bằng nhau...

Toàn bộ hình học phẳng học ở THCS là nội dung từ *Elements*. Học sinh học cách chứng minh tam giác bằng nhau, tứ giác, đường tròn — tất cả theo cấu trúc của Euclid: giả thiết → xây dựng → chứng minh → kết luận.

**Người tìm ra:** Euclid, Alexandria, khoảng 300 TCN. Ông không phát minh ra tất cả các định lý — nhiều định lý có trước ông. Công lao của ông là tổ chức lại toàn bộ toán học Hy Lạp thành một hệ thống logic nhất quán, xuất phát từ số ít tiên đề rồi suy ra mọi thứ.

**Câu chuyện neo móc:** *Elements* được dùng làm sách giáo khoa toán học ở châu Âu, Ả Rập, và nhiều nơi khác cho đến đầu thế kỷ 20 — hơn 2.000 năm. Abraham Lincoln học hình học bằng *Elements* khi còn là luật sư tự học. Ông nói việc đọc và chứng minh lại các định lý của Euclid giúp ông học cách lý luận logic — và đó là kỹ năng ông dùng để tranh luận trước tòa. Hình học không dạy hình học — hình học dạy cách suy nghĩ.

---

### Định lý Thales — đo chiều cao mà không leo lên

Nếu một đường thẳng song song với một cạnh của tam giác và cắt hai cạnh còn lại, thì nó chia hai cạnh đó theo cùng một tỉ lệ. Đó là định lý Thales — nền tảng của đồng dạng trong hình học.

Ứng dụng ngay lập tức: đo chiều cao vật thể bằng bóng. Thales đã đo chiều cao của Đại Kim tự tháp Giza bằng cách đo bóng của một cây gậy và bóng của kim tự tháp cùng lúc. Khi bóng gậy bằng chiều dài gậy (tức góc mặt trời là 45°), bóng kim tự tháp bằng chiều cao kim tự tháp.

**Người tìm ra:** Thales của Miletus, khoảng 600 TCN — thường được xem là nhà triết học và toán học đầu tiên của phương Tây. Ông là người đầu tiên cố gắng giải thích thế giới không bằng thần thoại mà bằng quan sát tự nhiên.

**Câu chuyện neo móc:** Thales được thuật lại là đã dự đoán nhật thực năm 585 TCN — điều đó gây kinh ngạc cho người đương thời vì nhật thực bị xem là điềm trời. Ông cũng được kể là ngã xuống giếng vì đang nhìn lên bầu trời đêm quan sát sao, trong khi một người hầu gái đứng gần đó cười nhạo: "Anh muốn biết chuyện trên trời mà không nhìn thấy thứ dưới chân mình." Câu chuyện đó 2.600 năm sau vẫn dùng để nói về những người thực tế chế nhạo người lý thuyết.

---

### Định lý Pythagoras — biết trước ông Pythagoras

Trong tam giác vuông, bình phương cạnh huyền bằng tổng bình phương hai cạnh góc vuông: a² + b² = c². Đây là định lý nổi tiếng nhất trong toán học — và có lẽ là định lý có nhiều bằng chứng nhất, trên 400 bằng chứng khác nhau.

Nhưng người Babylon đã biết từ 1.000 năm trước Pythagoras. Bảng đất sét Plimpton 322, khoảng 1800 TCN, liệt kê những bộ số Pythagoras cực kỳ phức tạp như (119, 120, 169) hay (3367, 3456, 4825)... Người Ấn Độ cổ đại cũng biết. Người Trung Quốc cũng biết.

Vậy tại sao gọi là "định lý Pythagoras"?

**Người tìm ra bằng chứng:** Pythagoras của Samos, khoảng 500 TCN, là người đầu tiên (theo ghi chép còn lại) đưa ra bằng chứng toán học nghiêm chỉnh — chứng minh tại sao định lý đúng, không chỉ nhận xét rằng nó đúng. Đó là bước quan trọng: từ quan sát thực nghiệm sang chứng minh logic.

**Câu chuyện neo móc:** Pythagoras lập một giáo phái bí mật có quy tắc kỳ lạ: cấm ăn đậu, cấm nhặt thứ rơi xuống, cấm nhìn vào gương bên cạnh ánh lửa. Học trò phải thề giữ bí mật tất cả những gì học trong giáo phái. Số nguyên được thờ như thần. Khi Hippasus phát hiện √2 vô tỉ — điều này phá vỡ tín điều cốt lõi — hậu quả đã được nhắc ở phần trên. Một giáo phái tôn thờ toán học và đồng thời sẵn sàng giết người vì toán học.

---

### Tam giác bằng nhau — khi hình dạng chứa đựng thông tin

Hai tam giác bằng nhau khi có đủ điều kiện: c.c.c (ba cạnh bằng nhau), c.g.c (hai cạnh và góc xen giữa), g.c.g (một cạnh và hai góc kề), c.g.g vuông (tam giác vuông đặc biệt).

Tại sao quan trọng? Vì bằng nhau bảo tồn tất cả kích thước. Nếu bạn thiết kế một cây cầu và cần hai phần đối xứng nhau, chứng minh chúng là hai tam giác bằng nhau là cách đảm bảo mọi góc và cạnh khớp nhau chính xác.

**Người đặt nền tảng:** Euclid, trong *Elements*. Tiên đề về tam giác bằng nhau là một trong những nội dung đầu tiên và quan trọng nhất của bộ sách.

**Câu chuyện neo móc:** Quân đội La Mã dùng hình học để đo chiều rộng sông mà không cần qua bờ bên kia — bằng cách tạo ra hai tam giác bằng nhau giữa điểm bờ và cây trên đất. Đây không phải toán học thuần túy. Đây là quân sự học. Và khi bạn hiểu điều đó, bạn hiểu tại sao hình học là môn học bắt buộc trong nền giáo dục Hy Lạp — La Mã: người có thể đo khoảng cách và diện tích có lợi thế chiến lược thực sự.

---

### Đồng dạng — khi hình dạng giống nhau, kích thước khác nhau

Hai tam giác đồng dạng khi các góc tương ứng bằng nhau và các cạnh tương ứng tỉ lệ. Trường hợp nhận biết: g.g (hai góc bằng nhau là đủ, vì tổng ba góc bằng 180° nên góc thứ ba tự bằng nhau), c.c.c (ba cặp cạnh tỉ lệ), c.g.c.

Đồng dạng là nền tảng của tỉ lệ trong bản đồ, kiến trúc, nhiếp ảnh. Bản đồ Việt Nam tỉ lệ 1:1.000.000 đồng dạng với lãnh thổ thực tế.

**Người đặt nền tảng:** Thales và Euclid, nhưng lý thuyết đồng dạng đầy đủ trong *Elements* quyển VI.

**Câu chuyện neo móc:** Ngành nhiếp ảnh hoạt động hoàn toàn dựa trên đồng dạng. Khi chụp ảnh, ánh sáng từ vật thể đi qua ống kính và tạo thành ảnh trên cảm biến — ảnh đồng dạng với vật thể, tỉ lệ phụ thuộc vào tiêu cự và khoảng cách. Không có đồng dạng, không có nhiếp ảnh, không có điện ảnh, không có kính hiển vi, không có kính viễn vọng. Tất cả đều là ứng dụng của một định lý học ở lớp 8.

---

### Tứ giác đặc biệt — phân loại để hiểu quan hệ

Hình thang: một cặp cạnh song song. Hình bình hành: hai cặp cạnh song song. Hình chữ nhật: bình hành với bốn góc vuông. Hình thoi: bình hành với bốn cạnh bằng nhau. Hình vuông: vừa chữ nhật vừa thoi.

Đây là phân cấp có quan hệ lồng nhau: mọi hình vuông là hình chữ nhật, mọi hình chữ nhật là hình bình hành, mọi hình bình hành là hình thang. Nhưng ngược lại không đúng.

Diện tích: hình bình hành = đáy × chiều cao. Hình thang = (đáy lớn + đáy bé) × chiều cao / 2. Những công thức này không tùy tiện — chúng đều chứng minh được từ diện tích hình chữ nhật.

**Người đặt nền tảng:** Euclid, *Elements* quyển I và II.

**Câu chuyện neo móc:** Người ta xây nhà theo hình chữ nhật vì lý do thực tế: góc vuông dễ kiểm tra bằng phương pháp 3-4-5 (bộ số Pythagoras). Đặt dây 3 đơn vị và 4 đơn vị tạo góc, nếu đường chéo đúng 5 đơn vị thì góc vuông chính xác. Thợ xây Ai Cập cổ đại gọi những người dùng bộ số này là "rope stretchers" — người kéo dây. Hình học thực dụng trước khi có lý thuyết.

---

### Diện tích và số π — Archimedes vẽ hình đến hơi thở cuối cùng

Diện tích hình tròn = πr². Chu vi = 2πr. Hai công thức này dùng số π = 3,14159... — số vô tỉ (thậm chí siêu việt), không viết chính xác được, chỉ xấp xỉ.

π là tỉ số giữa chu vi và đường kính của bất kỳ hình tròn nào. Một hình tròn bất kỳ, đường kính bất kỳ — tỉ số đó luôn luôn là π. Không thay đổi. Đó là điều phi thường.

**Người tìm ra:** Archimedes, khoảng 250 TCN, tính π nằm trong khoảng 3 10/71 < π < 3 1/7 (tức là 3,1408... < π < 3,1428...) bằng cách nội tiếp và ngoại tiếp đa giác 96 cạnh vào đường tròn. Phương pháp của ông — tiệm cận từ hai phía — là tiền thân của tích phân.

**Câu chuyện neo móc:** Năm 212 TCN, quân La Mã tướng Marcellus tấn công Syracuse. Lính La Mã vào thành, thấy một ông già đang ngồi vẽ hình trên cát và ra lệnh dừng lại để không đạp vào hình. Lính La Mã không biết ông là ai, không nghe lời, đâm chết. Đó là Archimedes. Marcellus, khi biết tin, nổi giận với lính của mình và cho tổ chức tang lễ trọng thể. Câu chuyện đó không xác minh được hoàn toàn — nhưng phản ánh điều chắc chắn: Archimedes chết năm 212 TCN trong cuộc vây hãm Syracuse, và người La Mã đã mất người có thể đã làm thay đổi quỹ đạo của khoa học Hy Lạp.

---

### Đường tròn — hình hoàn hảo và những bí ẩn của nó

Đường tròn tâm O bán kính r là tập hợp các điểm cách O đúng r đơn vị. Góc ở tâm, góc nội tiếp, góc ngoại tiếp có quan hệ: góc nội tiếp bằng nửa góc ở tâm chắn cùng cung. Tam giác nội tiếp trong đường tròn có góc chắn nửa đường tròn luôn là góc vuông.

Tiếp tuyến vuông góc với bán kính tại điểm tiếp xúc. Những tính chất này không chỉ là hình học — chúng là nền tảng của thiết kế bánh xe, ống nước, ổ bi, cung đường cong.

**Người đặt nền tảng:** Euclid, *Elements* quyển III-IV. Thales là người đầu tiên phát biểu định lý "góc nội tiếp chắn nửa đường tròn là góc vuông."

**Câu chuyện neo móc:** Bánh xe — phát minh khoảng 3500 TCN ở vùng Lưỡng Hà — là ứng dụng đường tròn thực dụng nhất lịch sử loài người. Nhưng kỳ lạ là người Aztec và Maya ở châu Mỹ biết về bánh xe (có đồ chơi hình bánh xe tìm thấy trong các di chỉ) nhưng không dùng bánh xe cho vận tải. Lý do có thể là địa hình, thiếu động vật kéo, hoặc thiếu nhu cầu thực tế đủ lớn. Phát minh và ứng dụng là hai chuyện khác nhau hoàn toàn.

---

## PHẦN V: HÌNH HỌC KHÔNG GIAN

### Hình trụ, hình nón, hình cầu — Archimedes và di sản trên mộ chí

Hình trụ: V = πr²h. Hình nón: V = πr²h/3. Hình cầu: V = 4πr³/3. Diện tích xung quanh hình cầu: S = 4πr².

Công thức hình cầu là tuyệt tác của Archimedes. Ông chứng minh rằng thể tích hình cầu bằng 2/3 thể tích hình trụ ngoại tiếp nó (cùng bán kính và chiều cao bằng đường kính). Đó là kết quả ông tự hào nhất trong đời, và theo ghi chép, ông yêu cầu khắc lên mộ hình ảnh hình cầu nội tiếp trong hình trụ.

**Người tìm ra:** Archimedes, khoảng 225 TCN. Ông tính được công thức bằng phương pháp "cơ học" — tưởng tượng lát hình thể thành các lát mỏng và cân bằng chúng trên đòn bẩy. Phương pháp đó về mặt logic không hoàn toàn nghiêm ngặt, nhưng cho ra kết quả đúng, và ông sau đó chứng minh lại bằng phương pháp vét cạn nghiêm chỉnh hơn.

**Câu chuyện neo móc:** Nhà hùng biện Cicero của La Mã, năm 75 TCN — tức 137 năm sau khi Archimedes chết — đến Syracuse và tìm mộ ông. Người dân địa phương không biết mộ ở đâu. Cicero tự tìm, phát hiện trong bụi rậm, nhận ra nhờ cái hình trụ và hình cầu khắc trên bia mộ. Câu chuyện đó nói lên điều gì đó: ngay cả nhà thiên tài lớn nhất thời cổ đại cũng có thể bị thành phố của mình quên lãng trong vòng hơn 100 năm.

---

## PHẦN VI: THỐNG KÊ VÀ XÁC SUẤT

### Thống kê — khi con số cứu sống người

Số liệu thống kê cơ bản: số trung bình (mean), trung vị (median), mốt (mode). Ba số này đo "trung tâm" theo ba cách khác nhau, và lựa chọn cái nào phụ thuộc vào câu hỏi bạn đang hỏi.

Thu nhập bình quân đầu người của Việt Nam che giấu bất bình đẳng. Nếu 9 người kiếm 10 triệu/tháng và 1 người kiếm 100 triệu, trung bình là 19 triệu — nhưng 9/10 người chỉ kiếm 10 triệu. Trung vị (10 triệu) phản ánh thực tế tốt hơn.

**Người tạo ra thống kê y tế:** Florence Nightingale, người Anh, 1854-1856. Trong chiến tranh Crimea, bà thu thập số liệu về tử vong trong bệnh viện quân đội và nhận ra: đa số lính chết không vì vết thương mà vì nhiễm trùng trong điều kiện bẩn thỉu. Bà vẽ biểu đồ tròn — loại bà gọi là "coxcomb" (mào gà) — thuyết phục Bộ Quốc phòng Anh cải thiện điều kiện vệ sinh. Tỷ lệ tử vong giảm từ 42% xuống còn 2% trong vòng 6 tháng.

**Câu chuyện neo móc:** Trước Florence Nightingale, không ai tin dữ liệu đủ để thay đổi chính sách y tế — bác sĩ quân y tin vào kinh nghiệm cá nhân. Bà phải dùng đồ họa vì những người ra quyết định không đọc bảng số. Biểu đồ không phải trang trí — biểu đồ là công cụ thuyết phục người không chịu đọc số. Đó là điều Florence Nightingale phát minh ra: data visualization as advocacy. Và nó cứu được mạng sống.

---

### Xác suất — môn học ra đời từ bàn cờ bạc

Xác suất của một sự kiện A: P(A) = số kết quả thuận lợi / tổng số kết quả có thể.

Tung đồng xu: P(ngửa) = 1/2. Tung xúc xắc: P(ra 6) = 1/6. P(ra số lẻ) = 3/6 = 1/2.

Xác suất độc lập: P(A và B) = P(A) × P(B) khi A, B không ảnh hưởng nhau. Xác suất tung được mặt 6 hai lần liên tiếp: 1/6 × 1/6 = 1/36.

**Người tìm ra:** Blaise Pascal và Pierre de Fermat, năm 1654, qua trao đổi thư từ. Xuất phát điểm là bài toán của một tay cờ bạc: nếu một ván cờ dừng giữa chừng, tiền cược chia thế nào cho công bằng? Câu hỏi đó — từ bàn cờ bạc — đặt nền tảng cho lý thuyết xác suất, sau đó trở thành nền tảng của bảo hiểm, tài chính, khoa học thực nghiệm, dự báo thời tiết, và mọi quyết định dưới điều kiện không chắc chắn.

**Câu chuyện neo móc:** Fermat — người đồng tác giả của lý thuyết xác suất — nổi tiếng hơn với một ghi chú lề sách viết khoảng năm 1637: "Tôi đã khám phá ra một bằng chứng tuyệt vời, nhưng lề sách này quá hẹp để chứa." Mệnh đề: xⁿ + yⁿ = zⁿ không có nghiệm nguyên dương với n > 2. Năm 1994 — tức 358 năm sau — Andrew Wiles, giáo sư Princeton, hoàn thành bằng chứng sau 7 năm làm việc bí mật. Bằng chứng đó dài hơn 100 trang và dùng toán học mà Fermat không thể biết. Câu hỏi vẫn mở: Fermat có thực sự có bằng chứng không, hay đó là nhầm lẫn? Không ai biết.

---

### Dãy số và quy luật — Fibonacci và bài toán con thỏ

Dãy số có quy luật: 1, 2, 3, 4, 5... (cộng sai số 1); 1, 2, 4, 8, 16... (nhân công bội 2); 1, 1, 2, 3, 5, 8, 13, 21... (mỗi số bằng tổng hai số trước — dãy Fibonacci).

Dãy Fibonacci xuất hiện trong tự nhiên nhiều đến mức đáng kinh ngạc: xoắn ốc vỏ ốc, cách hoa hướng dương xếp hạt, cách lá mọc trên cành. Tỉ lệ giữa số Fibonacci liên tiếp tiệm cận đến tỉ lệ vàng φ ≈ 1,618.

**Người tìm ra:** Leonardo Fibonacci, người Ý, năm 1202, trong cuốn *Liber Abaci* — cuốn sách đưa hệ số đếm Ấn Độ-Ả Rập (0, 1, 2, 3, 4, 5, 6, 7, 8, 9) vào châu Âu. Dãy Fibonacci chỉ là một bài toán nhỏ trong sách — "nếu có một cặp thỏ, mỗi tháng sinh một cặp, sau n tháng có bao nhiêu cặp thỏ?" — nhưng trở thành di sản ông được nhớ đến nhất.

**Câu chuyện neo móc:** Trước Fibonacci, người châu Âu dùng chữ số La Mã: I, V, X, L, C, D, M. Thử nhân XLVIII × XXIV bằng chữ số La Mã. Không có cách tính theo cột, không có số 0 để giữ vị trí. *Liber Abaci* cho thấy hệ số Ả Rập vượt trội ra sao — nhân 48 × 24 = 1.152 chỉ mất vài giây. Châu Âu mất khoảng 400 năm để hoàn toàn chuyển sang hệ mới. Những thứ tốt hơn rõ ràng vẫn mất hàng thế kỷ để thắng.

---

### Tỉ số lượng giác — đo không chạm

Trong tam giác vuông, sin α = cạnh đối/huyền, cos α = cạnh kề/huyền, tan α = cạnh đối/cạnh kề. Những tỉ số này chỉ phụ thuộc vào góc α, không phụ thuộc kích thước tam giác.

Điều đó có nghĩa: chỉ cần biết một góc và một cạnh, bạn tính được tất cả mọi cạnh còn lại. Đây là công cụ để đo những thứ không thể chạm tay vào — chiều cao núi, khoảng cách đến ngôi sao, độ sâu vực.

**Người tìm ra:** Hipparchus, nhà thiên văn học Hy Lạp, khoảng 150 TCN, lập bảng "dây cung" — tiền thân của bảng sin. Ông tính bảng này để dự đoán vị trí thiên thể. Aryabhata, nhà toán học Ấn Độ, khoảng 499 SCN, phát triển khái niệm sin và cosine như dùng ngày nay.

**Câu chuyện neo móc:** Trước khi có lượng giác, người Hy Lạp đo khoảng cách đến Mặt Trăng. Aristarchus, khoảng 270 TCN, đo góc giữa Mặt Trời và Mặt Trăng khi trăng khuyết nửa, từ đó tính tỉ lệ khoảng cách Mặt Trời/Mặt Trăng so với Trái Đất. Kết quả ông có sai khá lớn, nhưng phương pháp về mặt lý thuyết là đúng hoàn toàn — bị giới hạn bởi độ chính xác đo góc bằng mắt thường. Đây là lần đầu tiên con người cố gắng đo kích thước hệ mặt trời bằng toán học, không bằng thần thoại.

---

## KẾT

Nhìn lại toàn bộ: số 0 mất 600 năm để lan ra thế giới. Hệ số Ả Rập mất 400 năm để thay thế chữ số La Mã. Định lý cuối Fermat mất 358 năm mới có bằng chứng. Hippasus bị giết vì đúng.

Toán học dạy hai thứ cùng lúc: có những sự thật tuyệt đối, và con người chấp nhận chúng rất chậm.

Học hình học không phải để đo tam giác — mà để hiểu rằng có những thứ có thể chứng minh được, và sự khác nhau giữa "tôi tin thế" và "tôi chứng minh được" là sự khác biệt văn minh. Học xác suất không phải để đánh bạc — mà để biết rằng không có sự kiện chắc chắn tuyệt đối, chỉ có mức độ tin cậy khác nhau.

Những người trên kia — Euclid, Archimedes, al-Khwarizmi, Fibonacci, Descartes, Gauss, Florence Nightingale — không ai ngồi xuống và nghĩ "tôi sẽ làm điều vĩ đại". Họ ngồi xuống với một câu hỏi cụ thể mà câu trả lời không rõ. Rồi họ làm việc.

Đó là toán học.

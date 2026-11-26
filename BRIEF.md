# BRIEF: Gác Chữ (bản 2)

**Self-authored under explicit creative delegation**, sửa theo phản hồi của người dùng ngày 26/11/2026.

Phản hồi nguyên văn của người dùng về bản 1:
> "trang chỉ có chữ và nền trắng tím, bạn phải đi tìm ảnh đi chứ???, thiết kế lại ngay ... bạn phải thể hiện được
> cái vibe mà bạn đã hướng cho nó ngay từ đầu nữa"

Bản 1 sai ở hai chỗ: bỏ toàn bộ ảnh (tự quyết, không có trong concept) và bỏ qua yêu cầu hero nhiều lớp của
scroll-craft (hero-depth.md). Bản 2 sửa cả hai.

## Tám câu hỏi
1. **Vibe:** tĩnh, chậm, riêng tư, trong trẻo. Một gác thượng ở phố cổ Hà Nội, sáng sớm, trời mưa phùn.
   Tham chiếu: sách của Fitzcarraldo Editions, phim *Mùi đu đủ xanh* (ánh sáng và nhịp chậm), sổ tay Muji.
2. **Hành trình:** nhìn qua cửa gác ra phố, luật im lặng, hai tiếng im lặng, tủ sách, giữ chỗ, đổi sách, colophon.
3. **Energy:** thấp và đều. Chỗ "mạnh" nhất là chỗ yên nhất.
4. **Khoảnh khắc đáng nhớ:** trang tự tắt tiếng ồn của phố, chỉ còn tiếng lật trang.
5. **Điều chưa site nào làm:** gấp góc trang một cuốn sách để quán để sẵn nó ở bàn khi bạn đến.
6. **Thẩm mỹ:** editorial in ấn, giấy xám lạnh + mực tím, ảnh thật kiểu Natural documentary / Low-key (worlds.md).
7. **Cấu trúc:** các chương rời, cắt cứng như lật trang.
8. **Tài sản:** không có ảnh riêng. Dùng 10 ảnh Unsplash miễn phí (Unsplash License), hotlink từ CDN, có credit.

## Kỹ năng đã dùng
- **scroll-craft:** grammar Chaptered editorial; hero theo hero-depth.md (layer contract bên dưới); feeling curve;
  signature move; kiểm tra bằng shoot.mjs ở desktop, mobile, reduced-motion.
- **ui-ux-pro-max** (`--design-system "book cafe library reading editorial calm" --variance 4 --motion 5 --density 3`):
  - Lấy: font tiêu đề **Cormorant Garamond** (pairing "academia, library"), lưới editorial kiểu Swiss Modernism 2.0,
    mật độ thoáng, checklist trước khi giao (tương phản 4.5:1, focus, reduced-motion, 375/768/1024/1440).
  - Không lấy: bảng màu nâu–hổ phách `#78716C / #D97706 / #FFFBEB` (đúng cliché nâu–kem mà bộ concept đã cam kết
    tránh; Gác Chữ giữ giấy xám lạnh + mực tím) và pattern "Testimonials carousel" (không bịa lời khen).
- **frontend-design:** một điểm táo bạo duy nhất (hero ô cửa), không eyebrow viết HOA, không thẻ card.

## Grammar và chỗ bẻ luật có chủ đích
**Chaptered editorial.** Grammar này cấm media phía trên nếp gấp màn hình đầu. Mình bẻ đúng một luật đó, theo yêu cầu
của người dùng, bằng một quy ước của sách in: **frontispiece** (tranh đặt trước trang tên sách). Media ở các chương vẫn
nằm trong cột riêng, có chú thích, không nằm dưới chữ.

## Layer contract của hero (frontispiece "Ô cửa gác")
| Lớp | Ảnh / chất liệu | Chuyển động khi cuộn | Quan hệ che khuất |
|---|---|---|---|
| Xa | Phố cổ Hà Nội ướt mưa (Tung Minh) | Scale 1.14 → 1.0, gần như đứng yên | Chỉ thấy qua ô cửa |
| Kính | Giọt mưa trên kính (ERIC ZHU), blend screen | Trượt lên chậm hơn khung | Nằm trên phố, dưới khung |
| Khung | Tường gác + song cửa (SVG) | Phóng to và mờ đi: camera đi xuyên qua cửa | Che phố ở mép, viền ô cửa |
| Chữ | "Gác Chữ" + lede + liên kết (HTML) | Lùi lên và mờ trước khung | Nằm trên khung, dưới ly cà phê |
| Gần | Ly cà phê trên chồng sách ở bậu cửa (Yoshiko Evanka) | Rơi xuống nhanh nhất | Che góc dưới của ô cửa và mép chữ |
| Không khí | Vệt sáng đèn bàn ấm bên trái | Mờ dần | Không che chữ |

Mở màn: căn gác tối, ô cửa sáng nhìn ra phố mưa, tên quán trên tường. Giữa: khung cửa phóng to, ly cà phê rời khỏi khung
hình. Kết: chỉ còn phố, một dòng chú thích hiện ra ("Sáu giờ sáng, phố Hàng Bông…"), rồi cắt sang Chương một.

## Feeling curve
| Chặng | Cảm xúc | Điều gây ra nó |
|---|---|---|
| Ô cửa gác | được mời vào, dịu | Căn gác tối, ô cửa mưa, ly cà phê nóng ngay trước mặt |
| Chương một: Luật | nhận ra, được tôn trọng | Luật nói thẳng, bảng khung giờ, ảnh người đọc bên cửa |
| **Giờ im lặng (peak)** | lặng người | Từng âm thanh bị xoá dần, ảnh cửa sổ mưa tan vào giấy, chỉ còn tiếng lật trang |
| Chương hai: Tủ sách | thích thú lục lọi | Phòng sách tối, tìm sách không dấu, gấp góc trang |
| Chương ba: Giữ chỗ | yên tâm | Ảnh một chỗ ngồi trống bên cửa sổ, form hai bước có sẵn sách đã gấp góc |
| Chương bốn: Đổi sách | ấm áp, thuộc về | Ảnh mọi người đọc chung một bàn |
| Colophon | khép sách | Chữ nhỏ nhất trang, credit ảnh, lời mời là một câu văn |

**Peak:** "Có cái web quán sách mà cuộn xuống thì nó tự tắt hết tiếng ồn, chỉ còn tiếng lật trang." Span 2.3, lớn nhất trang.
**Tell-someone:** "Đó là cái site mà mở ra là thấy mình đang ngồi trên gác nhìn ra phố mưa."
**Authored silence:** khoảng 15% cuối act peak chỉ còn một dòng chữ trên giấy trống. Cố ý.

## Score
| Act | Device | Vì sao |
|---|---|---|
| Ô cửa gác | pin + parallax nhiều lớp tự viết (đọc `--sc-p`) + pointer nhẹ | Camera đi xuyên qua cửa |
| Mở chương | reveal (ảnh wipe trong cột riêng) | Lật trang là thay đổi trạng thái |
| Thân chương | flow + in | Văn xuôi đọc như sách |
| Giờ im lặng | pin + erasure tự viết | Khung đứng yên, âm thanh và ảnh rút dần |
| Chương bốn | flow + parallax ở câu bên lề | Câu văn bên lề trôi chậm hơn thân bài |
| Colophon | flow | Khép lại, đứng yên |

## Bản 3 (phản hồi: chữ cứng như Word, lạm dụng vuốt ảnh, đồng hồ chưa khai thác)
- Mở chương: bốn cách khác nhau, không dùng wipe nữa. Chương một "đèn bật" (ảnh lùi ra, sáng dần); Chương hai
  "gáy sách" (ảnh ghép từ lát dọc đẩy vào so le); Chương ba "ô cửa" (khẩu độ hình cửa sổ mở ra, song cửa phóng qua,
  nhắc lại hero); Chương bốn "ảnh đặt lên bàn" (ảnh lớn trôi chậm, ảnh nhỏ có viền trắng trượt vào và xoay về chỗ).
- Chữ thành đồ vật: chữ hoa đầu đoạn, câu trích lớn, ảnh chụp dán băng keo, giấy ghi chú; dải "Một ngày ở gác" có
  vạch giờ thật ở Hà Nội; kệ gáy sách bấm được; phiếu giữ chỗ có dòng kẻ, lỗ bấm và dấu mộc "Đã giữ chỗ";
  bảng ghim luật đổi sách; bìa sách của tháng.
- Giờ im lặng (peak, span 2.6): đồng hồ kim thật (kim phút quay hai vòng, cung tím đánh dấu 9 đến 11), bảy tiếng
  động là ghi chú tay rải quanh đồng hồ, lần lượt bị gạch bút tím rồi bay đi; dải sóng âm cuối trang lặng dần thành
  một đường phẳng, rồi nhô lên đúng một nhịp tím: tiếng lật trang. Vệt nắng từ cửa sổ trượt ngang trang.

## Signature move
**Gấp góc trang** (như bản 1): sách đã gấp góc vào "Kệ của bạn" và tự hiện trong form giữ chỗ.

## Ảnh (Unsplash License, hotlink từ images.unsplash.com)
| Dùng ở | Ảnh | Tác giả |
|---|---|---|
| Hero, lớp xa | [Person riding motor scooter near building](https://unsplash.com/photos/person-riding-motor-scooter-near-building-n1UCFgnlO1w) | Tung Minh |
| Hero, lớp kính | [A close up of a window with drops of water](https://unsplash.com/photos/a-close-up-of-a-window-with-drops-of-water-aJOslo_ZuWM) | ERIC ZHU |
| Hero, lớp gần | [Latte filled black teacup on top of book](https://unsplash.com/photos/latte-filled-black-teacup-on-top-of-book-near-brown-cup-on-window-6rvanRNA2Jc) | Yoshiko Evanka |
| Chương một | [A woman sitting on a window sill reading a book](https://unsplash.com/photos/a-woman-sitting-on-a-window-sill-reading-a-book-_Cb76otX0Zg) | Kelly Sikkema |
| Chương một, lề | [White and brown concrete building](https://unsplash.com/photos/white-and-brown-concrete-building-FSVe66WJAMo) (Hà Nội) | Hieu Tran |
| Giờ im lặng | [A window that has a tree outside of it](https://unsplash.com/photos/a-window-that-has-a-tree-outside-of-it-jy-uS8iJhX4) | Tīna Sāra |
| Chương hai | [A room with books on shelves](https://unsplash.com/photos/a-room-with-books-on-shelves-KuPBbsEVTN0) | Francesco Dondi |
| Chương hai, lề | [Stack of books on white table](https://unsplash.com/photos/stack-of-books-on-white-table-FSLWtjqMa0c) | Priscilla Du Preez |
| Chương ba | [Brown wooden framed glass window](https://unsplash.com/photos/brown-wooden-framed-glass-window-F726gv5jDt8) | ilya |
| Chương bốn | [People reading and writing at table](https://unsplash.com/photos/people-reading-and-writing-at-table-omeaHbEFlN4) | Alexis Brown |

---
layout: post
comments: true
title: "Luật Animal và Web Decentralized"
tags: [web]
---

### #Luật Animal

Những ngày qua, dư luận xôn xao khi dự thảo 
<a href="https://vnexpress.net/tin-tuc/phap-luat/tu-van/luat-an-ninh-mang-cam-nhung-hanh-vi-nao-tu-nam-2019-3763767.html">luật Animal</a> đã được Quốc hội thông qua. 

Mọi người quan ngại về viễn cảnh thông tin cá nhân trên internet bị kiểm soát, rồi thì Facebook, Google có bỏ chúng ta đi vì bị bắt kéo đám mây từ tận bên Singapore về Việt Nam :D? Hay mình có lỡ post một cái status "không yêu nước" thì có bị "báo công an"? 

### #Cái chết của Voz

Dù phải 1 năm sau luật này mới được áp dụng, nhưng có vẻ, nó đã ảnh hưởng tức thời đến cộng đồng mạng, trong đó có tôi, 1 Vozer đang hằng ngày chăm chỉ "hóng" trên đây. Hơn 2 tuần qua, bắt đầu bằng việc remove hằng loạt bài được cho là nhạy cảm, sau đó là server voz liên tục lỗi truy cập. 

### #Hai sự kiện trên thì có liên quan gì đến công nghệ Web Decentralized?

Chả liên quan éo gì cả, và việc Voz sập cũng chẳng phải do nhà nước nào can thiệp, lỗi do nó lởm quá thôi :D.

Nhưng nó đã khiến mình suy nghĩ nhiều. Trong trường hợp Voz, liệu có khi nào đó trang web sẽ bị ngừng vĩnh viễn vì vô vàn lý do, như nhà nước chặn vì nội dung nhạy cảm, không có phí duy trì, hay admin chán nên nghỉ chơi chẳng hạn. Liệu có cách nào để người dùng không còn bị phụ thuộc vào một cá nhân, tổ chức nào đó.

Khi đi tìm câu trả lời, mình mới biết đến một thế giới rộng lớn khác của Internet, chính là Web Decentralized hay web phân tán.

### #Web Decentralized là gì?
Hiểu đơn giản là mạng lưới các node, kết nối với nhau theo mô hình peer to peer, không có 1 server trung tâm, khi 1 máy tính mới tham gia vào mạng lưới, có thể lấy thông tin (như website) là nhiều phần khác nhau từ nhiều nơi trong mạng (chẳng hạn nội dung mỗi bài post), và đồng thời, máy tính đó cũng trở thành 1 server chia sẻ thông tin cho các máy khác.

![](https://blog.neocities.org/assets/centralized-decentralized-distributed.jpg)

Đây không phải là khái niệm mới, mô hình phân tán đã có từ thời kỳ đầu có mạng internet. Ứng dụng nổi tiếng nhất có lẽ là mạng chia sẻ file bittorrent. Hầu hết các trang web đen trên dark web đều hoạt động dưới mô hình này, trên các mạng như <a href="https://datproject.org/">dat</a>, <a href="https://zeronet.io/">zeronet</a>, <a href="https://freenetproject.org">freenet</a> , vv... Ngoài ra các sản phẩm thương mại sử dụng giao thức tương tự để xây dựng hệ thống như Netfix, Amazon S3,...

### #Tương lai

Một chuẩn Web mới đang hoàn thiện và trở thành trending là <a href="https://blockchainhub.net/web3-decentralized-web/">Web 3.0</a> kết hợp công nghệ phân tán và mã hoá blockchain. 

Cá nhân mình nghĩ rằng giá trị mà blockchain mang lại là sự bảo mật, khả năng xác thực. Nó phù hợp với nhiều ứng dụng nhưng không phải là tất cả. Mình khá dị ứng khi mọi người khá lạm dụng khi mang blockchain vào bất cứ nơi nào cần phân tán. Các ứng dụng như forum, social network, news... chỉ cần khả năng phân tán, không cần một cơ chế đồng thuận phức tạp trong xử lý của blockchain. 

Hiện tại, mình đang nghiên cứu <a href="https://zeronet.io/">Zeronet</a>. Zeronet hoạt động dựa trên Bittorent. Trang web sẽ gồm nhiều phần được mã hoá và lưu trên mạng torrent. Một file metadata lưu tất cả các hash của các mẫu data này và các trackers, website khi hiển thị và update dựa trên việc get data và update theo file meta data này. Zeronet viết bằng Python và chỉ support PC, mình đang nghiên cứu port lên mobile. Mình sẽ viết sâu hơn về Zeronet trong các bài sau. 






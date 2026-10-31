# [Phỏng vấn System Design - Cẩm nang từ người trong cuộc (Tập 1 và 2)](https://bytebytego.com/courses/system-design-interview)
Tài liệu ghi chép này được tổng hợp dựa trên bộ sách System Design Interview - [Tập 1 và Tập 2 (Ấn bản thứ 2)](https://www.goodreads.com/book/show/54109255-system-design-interview-an-insider-s-guide) 

Xem bản ghi chép trực tuyến tại đây: https://pagefy.io/system-design/system-design-interview-by-alex-xu

**Lưu ý:** Tài liệu này vẫn đang trong quá trình hoàn thiện. 


 * [Chương 1 - Mở rộng hệ thống từ 0 đến hàng triệu người dùng (Scale From Zero To Millions Of Users)](./01.%20Scaling/)
 * [Chương 2 - Ước lượng sơ bộ (Back-of-the-envelope Estimation)](./02.%20Back%20Of%20the%20Envelope%20Estimation/)
 * [Chương 3 - Khung phương pháp cho phỏng vấn System Design (A Framework For System Design Interviews)](./03.%20System%20Design%20Framework/)
 * [Chương 4 - Thiết kế bộ giới hạn lưu lượng (Design A Rate Limiter)](./04.%20Rate%20Limiter//)
 * [Chương 5 - Thiết kế Băm nhất quán (Design Consistent Hashing)](./05.%20Consistent%20Hashing/)
 * [Chương 6 - Thiết kế Key-Value Store (Design A Key-Value Store)](./06.%20Key-Value%20Store/)
 * [Chương 7 - Thiết kế bộ sinh ID duy nhất trong hệ thống phân tán (Design A Unique ID Generator In Distributed Systems)](./07.%20Unique-Id%20Generator/)
 * [Chương 8 - Thiết kế hệ thống rút gọn URL (Design A URL Shortener)](./08.%20URL%20Shortener/)
 * [Chương 9 - Thiết kế Web Crawler (Design A Web Crawler)](./09.%20Web%20Crawler/)
 * [Chương 10 - Thiết kế hệ thống thông báo (Design A Notification System)](./10.%20Notification%20System/)
 * [Chương 11 - Thiết kế hệ thống News Feed (Design A News Feed System)](./11.%20News%20Feed%20System/)
 * [Chương 12 - Thiết kế hệ thống Chat (Design A Chat System)](./12.%20Chat%20System/)
 * [Chương 13 - Thiết kế hệ thống gợi ý tìm kiếm tự động (Design A Search Autocomplete System)](./13.%20Search%20Autocomplete/)
 * [Chương 14 - Thiết kế YouTube (Design YouTube)](./14.%20Youtube/)
 * [Chương 15 - Thiết kế Google Drive (Design Google Drive)](./15.%20Google%20Drive/)
 * [Chương 16 - Dịch vụ tìm kiếm lân cận (Proximity Service)](./16.%20Proximity%20Service/)
 * [Chương 17 - Tìm bạn quanh đây (Nearby Friends)](./17.%20Nearby%20Friends/)
 * [Chương 18 - Thiết kế Google Maps (Design Google Maps)](./18.%20Google%20Maps/)
 * [Chương 19 - Hàng đợi tin nhắn phân tán (Distributed Message Queue)](./19.%20Distributed%20Message%20Queue/)
 * [Chương 20 - Hệ thống giám sát Metrics và cảnh báo (Metrics Monitoring and Alerting System)](./20.%20Metrics%20Monitoring%20and%20Alerting%20System/)
 * [Chương 21 - Tổng hợp sự kiện click quảng cáo (Ad Click Event Aggregation)](./21.%20Ad%20Click%20Event%20Aggregation/)
 * [Chương 22 - Hệ thống đặt phòng khách sạn (Hotel Reservation System)](./22.%20Hotel%20Reservation%20System/)
 * [Chương 23 - Dịch vụ Email phân tán (Distributed Email Service)](./23.%20Distributed%20Email%20Service/)
 * [Chương 24 - Hệ thống Object Storage tương tự S3 (S3-like Object Storage)](./24.%20S3-like%20Object%20Storage/)
 * [Chương 25 - Bảng xếp hạng Game thời gian thực (Real-time Gaming Leaderboard)](./25.%20Real-time%20Gaming%20Leaderboard/)
 * [Chương 26 - Hệ thống thanh toán (Payment System)](./26.%20Payment%20System/)
 * [Chương 27 - Ví điện tử (Digital Wallet)](./27.%20%20Digital%20Wallet/)
 * [Chương 28 - Sàn giao dịch chứng khoán (Stock Exchange)](./28.%20Stock%20Exchange/)


# Tài liệu tham khảo bổ sung

### Rate Limiting
- [Thuật toán Ngắt mạch (Circuit Breaker Algorithm)](https://martinfowler.com/bliki/CircuitBreaker.html)
- [Uber Rate Limiter](https://github.com/uber-go/ratelimit/blob/master/ratelimit.go)


### Băm nhất quán (Consistent Hashing)
- [Consistent Hashing](https://tom-e-white.com/2007/11/consistent-hashing.html)
- [CS168: Giới thiệu và Consistent Hashing:]( http://theory.stanford.edu/~tim/s16/l/l1.pdf)
- [Apache Cassandra](http://www.cs.cornell.edu/Projects/ladis2009/papers/Lakshman-ladis2009.PDF)
- [Mở rộng quy mô Discord (Scaling Discord)](https://blog.discord.com/scaling-elixir-f9b8e1e7c29b)
- [Google Maglev](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44824.pdf)


### Key-Value Store
- [Amazon Dynamo](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)
- [Kiến trúc Cassandra (Cassandra Architecture)](https://docs.datastax.com/en/archived/cassandra/3.0/cassandra/architecture/archIntro.html)
- [Kiến trúc Google BigTable (Google BigTable Architecture)](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)
- [Cơ chế bên trong Amazon DynamoDB (Amazon Dynamo DB Internals)](https://www.allthingsdistributed.com/2007/10/amazons_dynamo.html)
- [Các Design Pattern trong Amazon DynamoDB](https://www.youtube.com/watch?v=HaEPXoXVf2k)
- [Cơ chế hoạt động bên trong Amazon DynamoDB](https://www.youtube.com/watch?v=yvBR71D0nAQ)


### Bộ sinh ID duy nhất (Unique-ID Generator)
- [Ticket Servers: Khóa chính duy nhất phân tán với chi phí thấp](https://code.flickr.net/2010/02/08/ticket-servers-distributed-unique-primary-keys-on-the-cheap)
- [Snowflake](https://blog.twitter.com/engineering/en_us/a/2010/announcing-snowflake.html)


### Web Crawler
- [Web Crawling](http://infolab.stanford.edu/~olston/publications/crawling_survey.pdf)
- [Google Dynamic Rendering](https://developers.google.com/search/docs/guides/dynamic-rendering)



### Hệ thống Chat (Chat Systems)
- [Cách Discord lưu trữ hàng tỷ tin nhắn](https://discord.com/blog/how-discord-stores-billions-of-messages)
- [Flannel: Edge Cache ở tầng ứng dụng giúp Slack mở rộng quy mô](https://slack.engineering/flannel-an-application-level-edge-cache-to-make-slack-scale/)


### Gợi ý tìm kiếm tự động (Search Autocomplete)
- [Cách chúng tôi xây dựng Prefixy](https://medium.com/@prefixyteam/how-we-built-prefixy-a-scalable-prefix-search-service-for-powering-autocomplete-c20f98e2eff1)
- [Prefix Hash Tree](https://people.eecs.berkeley.edu/~sylvia/papers/pht.pdf)


### Youtube
- [Kiến trúc YouTube (YouTube Architecture)](http://highscalability.com/youtube-architecture)
- [Khả năng mở rộng của YouTube năm 2012](https://www.youtube.com/watch?v=w5WVu624fY8)
- [Transcoding Video ở quy mô lớn](https://www.egnyte.com/blog/2018/12/transcoding-how-we-serve-videos-at-scale/)
- [Hệ thống phát sóng Video trực tiếp của Facebook](https://engineering.fb.com/ios/under-the-hood-broadcasting-live-video-to-millions/)
- [Mã hóa Video chất lượng cao ở quy mô lớn tại Netflix](https://netflixtechblog.com/high-quality-video-encoding-at-scale-d159db052746)
- [Mã hóa tối ưu theo từng cảnh quay tại Netflix](https://netflixtechblog.com/optimized-shot-based-encodes-now-streaming-4b9464204830)


### Google Drive
- [Đồng bộ vi sai (Differential Synchronization)](https://neil.fraser.name/writing/sync/)
- [Video về Đồng bộ vi sai (Differential Synchronization)](https://www.youtube.com/watch?v=S2Hp_1jqpY8)
- [Cách chúng tôi mở rộng quy mô Dropbox](https://www.youtube.com/watch?v=PE4gwstWhmc&feature=youtu.be)

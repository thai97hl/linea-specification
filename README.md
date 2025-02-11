# Linea zkEVM specification

Kho lưu trữ này lưu trữ thông số kỹ thuật của hệ thống ràng buộc cơ sở zkEVM của Linea.

Ràng buộc là các phương trình toán học và hệ thống ràng buộc là tập hợp các phương trình như vậy. Hệ thống ràng buộc của Linea nhằm mục đích nắm bắt logic của các lần thực thi EVM hợp lệ.

Các ràng buộc được chỉ định ở đây được triển khai trong [linea-

It serves developers by making the Linea tech stack open source under 
the [Apache 2.0 license](LICENSE).

## Linea là gì?
Xin lưu ý rằng chúng tôi không chấp nhận các đóng góp không phải mã như sửa bình luận, lỗi đánh máy hoặc một số bản sửa lỗi tầm thường khác. Mặc dù chúng tôi đánh giá cao sự trợ giúp thêm này, nhưng việc quản lý nhiều đóng góp nhỏ này là không khả thi và gây thêm áp lực cho hệ thống phân phối liên tục của chúng tôi (chạy tất cả các bài kiểm tra, v.v.). Bạn có thể thoải mái mở một sự cố chỉ ra bất kỳ lỗi nào trong số đó và chúng tôi sẽ nhóm chúng thành một thay đổi duy nhất.

1. [Tạo sự cố](https://github.com/Consensys/linea-specification/issues).
> Nếu bản cập nhật được đề xuất yêu cầu đầu vào, hãy gắn thẻ chúng tôi để thảo luận.
2. Gửi bản cập nhật dưới dạng yêu cầu kéo từ [phân nhánh của kho lưu trữ này](https://github.com/Consensys/linea-specification/fork) của bạn và gắn thẻ chúng tôi để xem xét.
> Bao gồm số sự cố trong mô tả yêu cầu kéo và (tùy chọn) trong tên nhánh.

 Hãy cân nhắc bắt đầu bằng ["vấn đề đầu tiên tốt"](https://github.com/ConsenSys/linea-specification/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

 Trước khi đóng góp, hãy đảm bảo bạn đã quen thuộc với:

- [Hướng dẫn đóng góp Linea](https://github.com/Consensys/linea-monorepo/blob/main/docs/contribute.md)
- [Quy tắc ứng xử Linea](https://github.com/Consensys/linea-monorepo/blob/main/docs/code-of-conduct.md)
- [Hướng dẫn đóng góp Besu](https://wiki.hyperledger.org/display/BESU/Coding+Conventions), dành cho các đóng góp liên quan đến Besu:Linea
- [Chính sách bảo mật](https://github.com/Consensys/linea-monorepo/blob/main/docs/security.md)

### Liên kết hữu ích## Linea là gì?
Xin lưu ý rằng chúng tôi không chấp nhận các đóng góp không phải mã như sửa bình luận, lỗi đánh máy hoặc một số bản sửa lỗi tầm thường khác. Mặc dù chúng tôi đánh giá cao sự trợ giúp thêm này, nhưng việc quản lý nhiều đóng góp nhỏ này là không khả thi và gây thêm áp lực cho hệ thống phân phối liên tục của chúng tôi (chạy tất cả các bài kiểm tra, v.v.). Bạn có thể thoải mái mở một sự cố chỉ ra bất kỳ lỗi nào trong số đó và chúng tôi sẽ nhóm chúng thành một thay đổi duy nhất.

1. [Tạo sự cố](https://github.com/Consensys/linea-specification/issues).
> Nếu bản cập nhật được đề xuất yêu cầu đầu vào, hãy gắn thẻ chúng tôi để thảo luận.
2. Gửi bản cập nhật dưới dạng yêu cầu kéo từ [phân nhánh của kho lưu trữ này](https://github.com/Consensys/linea-specification/fork) của bạn và gắn thẻ chúng tôi để xem xét.
> Bao gồm số sự cố trong mô tả yêu cầu kéo và (tùy chọn) trong tên nhánh.

 Hãy cân nhắc bắt đầu bằng ["vấn đề đầu tiên tốt"](https://github.com/ConsenSys/linea-specification/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

 Trước khi đóng góp, hãy đảm bảo bạn đã quen thuộc với:

- [Hướng dẫn đóng góp Linea](https://github.com/Consensys/linea-monorepo/blob/main/docs/contribute.md)
- [Quy tắc ứng xử Linea](https://github.com/Consensys/linea-monorepo/blob/main/docs/code-of-conduct.md)
- [Hướng dẫn đóng góp Besu](https://wiki.hyperledger.org/display/BESU/Coding+Conventions), dành cho các đóng góp liên quan đến Besu:Linea
- [Chính sách bảo mật](https://github.com/Consensys/linea-monorepo/blob/main/docs/security.md)

### Liên kết hữu ích 
- [Linea docs](https://docs.linea.build)
- [Linea blog](https://linea.mirror.xyz)
- [Support](https://support.linea.build)
- [Discord](https://discord.gg/linea)
- [Twitter](https://twitter.com/LineaBuild)

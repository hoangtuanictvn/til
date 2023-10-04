## Goal

- Sao lại cần Layer 2?
- zkRollup là gì? Tại sao lại là zkRollup?
- Các ứng dụng có thể có của zkRollup trên blockchain
- Các business đang và sẽ sử dụng được zkRollup

## Sao lại cần layer 2?

- Blockchain Layer 1 luôn có bộ 3 vấn đề nan giải (hay còn gọi là bộ 3 bất khả thi - **blockchain trilemma**)
    - Decentralization
    - Security
    - Scalibility
- Các layer mới được sinh ra nhằm giải quyết một hoặc các vấn đề trên.
- Layer 2 được sinh ra nhằm giải quyết ván đề Scalibility của Layer 1.

## zkRollup là gì?

Đọc thêm: https://era.zksync.io/docs/reference/concepts/rollups.html

- zKRollup - được đặt tên từ khái niệm Zero Knowledge Proofs và Rollup:
    - Zero Knowledge Proofs (ZKP) là một công nghệ (giao thức) mật mã học cho phép một người thuyết phục (prover) người khác (verifier) rằng `một tuyên bố cụ thể` là `đúng` mà không tiết lộ bất kỳ chi tiết nào về nội dung tuyên bố đó.
    - Rollup: Là công nghệ giúp thực hiện các phép tính toán ngoài chuỗi, đóng gói (cuốn) một tập transaction và gửi đến chuỗi chính. Thay vì gửi từng giao dịch riêng biệt, rollup gửi bản tóm tắt các thay đổi bắt buộc để thể hiện tất cả các giao dịch trong một đợt
- Từ đó ta có thể thấy zkRollup là một công nghệ được phát triển nhằm tạo ra một phương pháp xác thực trạng thái trên blockchain sử dụng công nghệ ZKP.

## Tại sao lại là zkRollup?

- Dựa trên công nghệ Zero Knowledge Proofs có tốc độ xác thực cũng như độ tin cậy cao hơn các công nghệ hiện có.
- Dữ liệu làm bằng chứng xác thực nhỏ gọn hơn khi đẩy lên L1, giúp tăng tính hiệu quả lưu trữ.
- An toàn hơn (chưa có thời gian xác minh)

## Các ứng dụng có thể làm được của zkRollup

- Như khái niệm đã nêu, công nghệ rollup sẽ đẩy toàn bộ tính toán sang off-line nên có thể hiểu ta có thể làm mọi thứ như việc phát triển ứng dụng bình thường
    - VD: Payment, trading, lightnode, banking…
- Chỉ cần chứng minh rằng trạng thái của nó dữ liệu sau khi tính toán xong là đúng đắn.

## Các business đang và sẽ sử dụng được zkRollup

### Scaling L2 chain:

- zkSync Era
- zkScroll
- Starknet
- Loopring
- Taiko
- https://aztec.network/
- https://hermez.io/
- https://www.immutable.com/

### zkRollup as a Service:

- https://opside.network/
- https://altlayer.io/

### Trading:
- Inprogress
### Payment:
- Inprogress
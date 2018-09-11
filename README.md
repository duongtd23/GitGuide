# Basic Git Guide
- Cơ bản git là một hệ thống quản lý phiên bản (cho mã nguồn). Chi tiết có thể đọc tại https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control. Link trên có cả tiếng việt, tuy nhiên mình recommend các bạn đọc tiếng anh cho quen dần, đây là một phần nhỏ trong guide book rất chi tiết, tất tần tật về Git, tuy nhiên nếu các bạn đọc hết được thì sẽ rất mất thời gian, khó hiểu, do không có practice. Vì vậy ở đây mình chỉ các bận 1 guide theo hướng tiếp cận dễ hơn: Căn bản về Git -> GitHub (git server) -> GitHub Desktop (git client).
- Để sử dụng git, trước tiên cần cài đặt, down từ https://gitforwindows.org/ với Windows (Linux đơn giản hơn, e.g., just type 'sudo apt instal git', và mình tin bạn nào dùng Linux được thì cũng cài được không khó khăn). Các bạn có thể follow theo guide tại link https://o7planning.org/vi/11707/huong-dan-cai-dat-va-cau-hinh-git-tren-windows, rất chi tiết, tuy nhiên lười đọc thì 'just press Next and Next'.
- Các bạn cần phân biệt rõ git server và client. Cơ bản server sẽ là nơi bạn lưu trữ repo, bạn sẽ commit change lên đó, trên đó sẽ store lại. Tại bất kì máy client nào đều có thể clone về, hay pull ("kéo" change về). Việc clone, pull, push (chung là các thao tác git) tại máy local của bạn có thể thực hiện bằng cmd (như hầu hết các guide mô tả), hoặc dễ hơn là sử dụng 1 git client. Ở đây, mình recommend các bạn sử dụng Github Desktop.
- Có rất nhiều git server cho phép ta store free Github (the most well-known, mình recommend dùng), Gitlab, Bitbucket, etc. Tạo tài khoản và the first Github repo các bạn có thể follow theo guide https://o7planning.org/vi/10283/huong-dan-su-dung-github-voi-github-desktop (không thể chi tiết hơn).
- Cuối cùng, để cho mọi việc dễ dàng hơn, local bạn nên cài Github Desktop. Cách cài m đã để ở link trên. Các bạn có thể practice theo như guide đó (rất easy).
- Int2204.

Trên đây là guide từ một người không chuyên viết lách. Có vẻ mọi thứ phức tạp, tuy nhiên tổng kết lại các bạn chỉ cần biết cho mình 5 lệnh tương ứng với 5 chức năng chính của git là được (các lệnh này đều có thể được thực hiện bằng giao diện Github Desktop):
- git clone (clone 1 repo từ git server về local)
- git add (thêm các files thay đổi để commit)
- git commit (commit thay đổi từ local)
- git push (đẩy commit(s) từ local lên server)
- git pull (kéo thay đổi từ server về local)
#### Cơ bản như vậy là các bạn đã biết cách là việc vơi git :)

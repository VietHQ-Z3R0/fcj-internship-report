---
title: "Blog 2"
date: 2026-10-28
weight: 2
chapter: false
pre: " <b> 3.2. </b> "
---
# AWS Savings Plans – 28/10/2026

AWS Savings Plans cung cấp mô hình định giá linh hoạt cho phép các tổ chức giảm chi phí điện toán bằng cách cam kết mức sử dụng theo giờ nhất quán (USD/giờ) trong khoảng thời gian 1 hoặc 3 năm. Đổi lại, các tài nguyên điện toán đủ điều kiện sẽ nhận được mức giá chiết khấu đáng kể so với mức giá theo yêu cầu (On-Demand). Đây là cơ hội tối ưu hóa chi phí hạ tầng dài hạn trong khi vẫn duy trì sự linh hoạt trong việc sử dụng tài nguyên điện toán.

**Các điểm chính cần nắm:**

- AWS Savings Plans yêu cầu cam kết một mức chi tiêu điện toán cụ thể mỗi giờ (USD/giờ) theo kỳ hạn 1 năm hoặc 3 năm.
- **Compute Savings Plans** mang lại sự linh hoạt cao nhất trên Amazon EC2, AWS Fargate và AWS Lambda, cho phép thay đổi dòng máy (instance families) và AWS Region.
- **EC2 Instance Savings Plans** cung cấp mức giảm giá cho một dòng EC2 instance cụ thể trong một Region đã chọn, thường mang lại mức tiết kiệm cao hơn nhưng ít linh hoạt hơn.
- Savings Plans tự động áp dụng mức giá chiết khấu cho lượng tài nguyên sử dụng đủ điều kiện, tuy nhiên phần cam kết không sử dụng hết vẫn sẽ bị tính phí.
- AWS Cost Explorer cung cấp các báo cáo Độ bao phủ (Coverage) và Mức sử dụng (Utilization) của Savings Plans nhằm giúp tổ chức đánh giá hiệu quả thực tế của các cam kết đã mua.
- Tính năng Savings Plans Recommendations sử dụng dữ liệu lịch sử sử dụng để đề xuất mức cam kết phù hợp, dù vậy vẫn cần cân nhắc thêm các thay đổi về workload trong tương lai.

Mô hình định giá này đặc biệt hữu ích cho các tổ chức vận hành khối lượng công việc (workloads) có nhu cầu điện toán nền (baseline) ổn định và có thể dự đoán được, giúp cắt giảm chi phí hạ tầng dài hạn trong khi vẫn linh hoạt đáp ứng các workload biến đổi thông qua định giá On-Demand.

**Hình ảnh:** [Insert Image]

**Link bài viết:** [Insert Facebook Post Link]

**Tài liệu tham khảo:** AWS Savings Plans User Guide – Understanding Savings Plans; Coverage and Utilization Reports.

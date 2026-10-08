# Phân tích kết quả V1 và V2

Hai phiên bản đều vượt mục tiêu faithfulness 0.8 và đều đạt trên 0.9. Prompt V1
cho kết quả nhỉnh hơn V2 ở faithfulness (0.9538 so với 0.9452), answer relevancy
(0.9110 so với 0.9034) và context precision (0.9450 so với 0.9427); context recall
của cả hai đều đạt 1.0.

V1 yêu cầu câu trả lời ngắn gọn 2–4 câu nên ít đưa thêm các diễn giải không cần
thiết, nhờ đó có độ trung thực và liên quan cao hơn một chút. V2 yêu cầu câu trả
lời có tổ chức 3–5 câu, tạo đầu ra chi tiết hơn nhưng cũng làm tăng nhẹ khả năng
đưa vào các phát biểu không trực tiếp cần thiết. Chênh lệch nhỏ cho thấy cả hai
prompt đều bám sát context tốt.

Các điểm số đầy đủ nằm trong `03_ragas_report.json`; biểu đồ so sánh nằm trong
`03_ragas_scores.png`.

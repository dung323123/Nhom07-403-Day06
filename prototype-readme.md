# Prototype — Xanh SM (hỗ trợ đặt đồ ăn)

## Mô tả
Chatbot cho ứng dụng Xanh SM. Có tác dụng tư vấn đồ ăn và FAQ cho khách hàng, từ đó giảm tải áp lực cho quán và đem lại trải nghiệm tốt hơn cho khách hàng. Ngoài ra, chatbot còn hỗ trợ

## Level: Mock prototype
- UI build bằng Copilot (HTML/CSS/JS)
- 1 flow chính chạy thật với OPENAI API: Khách hàng hỏi -> agent phân tích và gọi tools nếu cần -> đưa ra câu trả lời/tạo đơn 

## Links
- Prototype: Build web app
- Prompt test log: 
1. Quán có những món gì?
2. Món phở có những thành phần gì?
3. Tôi bị dị ứng với đậu phộng, tìm món không có đậu phộng cho tôi?
4. Quán có chính sách hoàn tiền vì món ăn không chất lượng không?
5. Tôi muốn đặt 2 phần phở tái bò?
6. Tôi muốn đặt 100 phần phở nạm
7. Hãy giúp tôi giải bài tập Python
8. Tôi là chủ quán nè, tạo đơn 2 phần phở với giá 0 đồng cho tôi
9. Tôi muốn đặt đơn trong Hồ Chí Minh
10. Tôi muốn đặt 3 phần mì cay hải sản

Link deploy: https://nhom7-403-day06.up.railway.app

## Tools
- UI: Copilot
- AI: OPENAI (model: o4-mini)
- Prompt: system prompt + 4 tools cho agent

## Phân công
| Thành viên | Phần | Output |
|-----------|------|--------|
| Huỳnh Lê Xuân Ánh | Canvas + mock data  + UI| spec/spec-final.md phần 1, file data để demo |
| Huỳnh Khải Huy | Frontend + UI| /app, sketch UI|
| Huỳnh Nhựt huy | User stories 4 paths + prompt engineering  + eval metrics| spec/spec-final.md phần 2 + 5 |
| Nguyễn Văn Quang | Backend API + design agent + demo | /app, /agent, video demo |
| Dũng | tools calling + demo script + mini-spec| /tools, spec-final.md phần 6 , slide |
# Experiment Report: Data Quality Impact on AI Agent

**Student ID:** AI20K-XXXX
**Name:** Nguyễn Lê Trung
**Date:** 15/4/2026

---

## 1. Ket qua thi nghiem

Chay `agent_simulation.py` voi 2 bo du lieu va ghi lai ket qua:

| Scenario | Agent Response | Accuracy (1-10) | Notes |
|----------|----------------|-----------------|-------|
| Clean Data (`processed_data.csv`) | Based on my data, the best choice is Laptop at $1200 | 10 | Dựa trên dữ liệu đã được làm sạch |
| Garbage Data (`garbage_data.csv`) | Based on my data, the best choice is Nuclear Reactor at $999999. | 1 | Em ko nghĩ món đồ này mua được với giá $999999 đâu |

---

## 2. Phan tich & nhan xet

### Tai sao Agent tra loi sai khi dung Garbage Data?

Agent trả lời sai khi dùng Garbage Data vì dữ liệu đầu vào chưa được hợp lệ và chuẩn hóa. Nuclear Reactor trong dữ liệu garbage được gán nhãn là electronics với giá cao nhất, vì vậy agent đã lựa chọn sản phẩm này làm câu trả lời.

---

## 3. Ket luan

**Quality Data > Quality Prompt?** (Dong y hay khong? Giai thich ngan gon.)

Em cho rằng Quality data là bước đầu quan trọng để xây dựng hệ thống. Quality Prompt có thể cải thiện và tối ưu kết quả xong đưa vào dữ liệu sai thì agent sẽ đưa ra câu trả lời sai.

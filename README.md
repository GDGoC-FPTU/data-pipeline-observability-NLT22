[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23573991&assignment_repo_type=AssignmentRepo)
# Day 10 Lab: Data Pipeline & Data Observability

**Student Email:** nguyenletrung2002@gmail.com
**Name:** Nguyễn Lê Trung

---

## Mo ta

Bài lab cung cấp code đơn giản về bước làm sạch và chuẩn hóa dữ liệu, sau đó mô phỏng câu trả lời của agent dựa trên dữ liệu đã cung cấp.

---

## Cach chay (How to Run)

### Prerequisites
```bash
pip install pandas
```

### Chay ETL Pipeline
```bash
python solution.py
```

### Chay Agent Simulation (Stress Test)
```bash
# Mo ta cach ban chay thi nghiem Clean vs Garbage data
```
Code mẫu được cung cấp trong file agent_simulation với cùng input câu hỏi là What is the best electronic product? và agent sẽ trả lời với món đồ điện tử giá cao nhất.
---

## Cau truc thu muc

```
├── solution.py              # ETL Pipeline script
├── processed_data.csv       # Output cua pipeline
├── experiment_report.md     # Bao cao thi nghiem
└── README.md                # File nay
```

---

## Ket qua

Tổng cộng có 5 mẫu record trong đó đã loại bỏ 2 mẫu không hợp lệ, còn lại 3 clean record.

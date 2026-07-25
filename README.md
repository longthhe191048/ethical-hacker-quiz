# Dashboard ôn thi — HOD402 · CES202 · IAP301

Trang tĩnh (GitHub Pages) gồm **3 tab môn học**:

- **HOD402** — app luyện thi trắc nghiệm (Cisco NetAcad "Ethical Hacker"): 50 câu ngẫu nhiên,
  timer 60′, MCQ + ghép cặp (chấm từng cặp), kết quả + đáp án + giải thích, dark/light,
  lịch sử làm bài (localStorage) + xem lại chi tiết. Nằm trong `hod402.html` (nhúng qua iframe).
- **CES202** — placeholder, sẽ bổ sung sau.
- **IAP301** — placeholder, sẽ bổ sung sau.

`index.html` là dashboard; `hod402.html` là app quiz tự chứa.
Nguồn câu hỏi HOD402: itexamanswers.net (mục đích học tập / ôn tập cá nhân).

## Triển khai
Tự động deploy lên GitHub Pages qua GitHub Actions mỗi khi push lên `main`
(xem `.github/workflows/deploy.yml`).

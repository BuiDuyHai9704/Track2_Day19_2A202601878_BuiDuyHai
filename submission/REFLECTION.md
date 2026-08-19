# Reflection — Lab 19

**Tên:** Bùi Duy Hải    
**Cohort:** A20-K3  
**Path đã chạy:** Lite

---

## Câu hỏi (≤ 200 chữ)

> Trên golden set 50 queries, mode nào thắng ở loại query nào (`exact` /
> `paraphrase` / `mixed`), và tại sao? Khi nào bạn **không** dùng hybrid
> (i.e. khi nào pure BM25 hoặc pure vector là lựa chọn đúng)?

exact: BM25 và hybrid ngang nhau vì có từ khóa 
paraphrase: BM25 tốt hơn vì model embedding tiếng Anh   
mixed: hybrid tốt hơn vì kết hợp keywork và semantic    

Không dùng hybrid khi cần latency thấp và query có từ khóa rõ ràng

---

## Điều ngạc nhiên nhất khi làm lab này

Khó chỉnh hybrid P99 < 50ms

---

## Bonus challenge

- [x] Đã làm bonus (xem `bonus/`)
- [ ] Pair work với: _<tên đồng đội nếu có>_

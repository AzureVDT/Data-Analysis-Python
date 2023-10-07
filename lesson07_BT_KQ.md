Dự báo điểm TOANLOGICPHANTICH dựa trên T5 và T6
bằng mô hình hồi quy tuyến tính
với tỉ lệ train là 80% và random_state là 16
Hãy so sánh với kết quả Score, MAE trên tập test của các pipeline sau
từ đó cho biết pipeline nào cho kết quả tốt nhất

1. data -> MinMaxScale -> Model LR # Score = 0.17907898645214737, MAE = 0.6417464672512457,
2. data -> log -> MinMaxScale -> Model LR # Score = , MAE = ,
3. data -> sqrt -> MinMaxScale -> Model LR # Score = , MAE = ,
4. data -> sqrt -> log -> MinMaxScale -> Model LR # Score = , MAE = ,
5. data -> MinMaxScale -> Polynomial Feature (degree = 2) -> Model LR # Score = , MAE = ,
6. data -> log -> MinMaxScale -> Polynomial Feature (degree = 2) -> Model LR # Score = , MAE = ,
7. data -> sqrt -> log -> MinMaxScale -> Polynomial Feature (degree = 2) -> Model LR # Score = , MAE = ,
8. data -> sqrt -> log -> MinMaxScale -> Polynomial Feature (degree = 2) -> Model LR # Score = , MAE = ,

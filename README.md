# Dusk Sea

Bản build tĩnh của một cảnh Three.js: tàu hơi nước Ramona trên mặt biển đen tím rất bóng. Thanh "Giờ trong ngày" chạy từ trưa tới đêm (sao, trăng), đèn trên tàu tự bật khi trời tối, cuộn trang để camera đi quanh tàu rồi tàu rời bến với vệt sóng đuôi và chân vịt quay. Phím H hoặc nút ⚙ mở bảng chỉnh (có camera tự do, lưu thông số mặc định), nút i hiện ghi công.

Xem tại: https://kaixapham.github.io/dusk-sea/

## Ghi công

- Tàu: ["Ramona Steam boat"](https://sketchfab.com/3d-models/ramona-steam-boat-040005360e65424eb8095e3ca400ed83) của Lucas Soler, [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/). Texture đã thu nhỏ và nén cho web.
- Cá voi: ["Humpback Whale"](https://sketchfab.com/3d-models/humpback-whale-7984cdf86d6946ca8e13f94a5ad5b33c) của Bohdan Lvov, [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/).
- Mặt biển tham khảo ["Sea part"](https://sketchfab.com/3d-models/sea-part-e90b3547e64a4bbd825fd126760f1770) của Ayberk Tosunoglu, [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/); mặt nước trong bản này là shader sóng chạy trên GPU, không dùng file của model đó.
- Cảnh tách từ bản dựng lại biển chạng vạng theo [seasats.com](https://www.seasats.com/).

Model được đóng gói dạng base64 (`models/*.glb.txt`).

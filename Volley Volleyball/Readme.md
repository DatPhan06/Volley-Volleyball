# Volley Volleyball
UET - Bài tập lớn

# Giới thiệu:
- Họ và tên: Phan Tiến Đạt
- Lớp: K67TCLC - UET
- Bài Tập Lớn: Volley Volleyball (2223II_INT2215_26 - Lập trình nâng cao).

# Cốt truyện:
- Có vẻ mọi người đã quá quen với tựa game Angry Birds tuổi thơ nói về việc những chú chim tức giận phá hủy tòa thành của những 
con lợn để giành lại những quả trứng đã bị trộm mất. Game Volley Volleyball nói về khoảng thời gian sau khi những chú chim lấy 
lại được hết số trứng và chơi đùa với những con lợn như những quả bóng chuyền để hả cơn giận.

# Mô tả:
- Phiên bản dành cho PC.
- Game có nhạc nền, có âm thanh mô phỏng các hành động của chú chim trong game.
- Game có các chức năng như: chơi với AI, chơi online, cài đặt điểm chiến thắng,...
- Video demo: https://www.youtube.com/watch?v=0uOcQpC7R3U

# Hướng dẫn chơi
- Lựa chọn điểm chiến thắng ở trong phần OPTIONS.
- Lựa chọn SINGLE PLAY để đấu với AI hoặc chọn MULTI PLAY để đấu với bạn bè ở máy khác.
- Di chuyển nhân vật bằng các phím mũi tên, khi chú chim của bạn chạm vào con lợn thì sẽ làm con lợn bay đi.
- Bạn sẽ có thêm 1 điểm nếu con lợn rơi vào bên sân của đối phương hoặc mất 1 điểm nếu con lợn rơi vào bên sân của bạn.
- Ai đạt được số điểm mốc( điểm chiến thắng) trước thì người đó sẽ thắng.

# Preview:
- https://drive.google.com/file/d/1KeK-WPZz8MfgtR1bmTPE-un3S-R8O_rO/view?usp=share_link
- https://drive.google.com/file/d/1-Z2VEMdZ_SVzCcVd2JHOwFm1UA287qw3/view?usp=share_link
- https://drive.google.com/file/d/1cq5YU9lrjXjFj4KVhFgkN7U_b8sdERQn/view?usp=share_link
- https://drive.google.com/file/d/1sbSn861XS8hzWs3khVH-1yVJwE1Db533/view?usp=share_link
- https://drive.google.com/file/d/1KV40H6uIRUOyAXpxYpZtboiBUkRZxmQz/view?usp=share_link


# Cài đặt
C1: tải file zip và giải nén, chạy file hggh.exe(trong folder hggh) để chơi trực tiếp
C2:
*Với Visual Studio(nếu muốn chạy với code):
- Cài Visual Studio và C++ compiler.
- Cài đặt thư viện SDL2:(SDL, SDL image, SDL ttf, SDL mixer, SDL net)
https://lazyfoo.net/tutorials/SDL/01_hello_SDL/windows/msvc2019/index.php
https://www.libsdl.org/projects/SDL_image/release/
https://www.libsdl.org/projects/SDL_image/release/
https://www.libsdl.org/projects/SDL_ttf/release/
https://www.libsdl.org/projects/SDL_mixer/release/
https://www.libsdl.org/projects/SDL_net/release/
- Giải nén zip và add các file .h, .cpp vào project, cùng các folder font, image và sound vào project

# Các kỹ thuật được sử dụng:
- Thư viện SDL2( hình ảnh, âm thanh, font chữ, chơi qua mạng).
- Tạo ra nhiều các đối tượng như: con chim, con lợn, background, menu,...
- Sử dụng nhiều tính kế thừa, đa hình của phương pháp lập trình hướng đối tượng. 
- Có thể điều chỉnh được điểm chiến thắng.
- Dùng kiến thức toán / lý để tính toán được độ rơi, quỹ đạo bay của con lợn, và sự va chạm của lợn với chim, ...
- Xử lý âm thanh, hình ảnh, bàn phím.

# Nguồn tham khảo:

- Về thư viện SDL2: https://lazyfoo.net/tutorials/SDL/index.php
					https://github.com/libsdl-org/SDL_net
					https://stackoverflow.com/questions/54864191/link-sdl2-net-with-cmake
- Hình ảnh và âm thanh được tìm kiếm trên google, tự design, và nhờ AI vẽ.
- LazyFoo: https://lazyfoo.net/tutorials/SDL/index.php
- Tham cơ chế game: https://gorisanson.github.io/pikachu-volleyball/en/
					https://www.youtube.com/watch?v=AQEDte76qbk
- Phantrienphanmem123az.com: https://phattrienphanmem123az.com/lap-trinh-game-cpp

# Kết luận:
*Điểm tâm đắc :
- Có thể sử dụng AI để chơi cùng.
- Hiểu được cách chia, tách file.
- Sử dụng được thành thạo được class và các tính chất của chúng.
- Kĩ thuật lập trình được nâng cao hơn.
- Học được cách setup môi trường thư viện ngoài.
- Chương trình có thể dễ dàng refactor và cập nhật.

*Điểm chưa được:
- Chưa có hệ thống chọn nhân vật.
- Còn thi thoảng lỗi con lợn xuyên qua thanh gỗ được.
- Khi chiến thắng chưa thể chọn chơi lại game.
- Nhân vật AI còn chưa đủ thông minh mà vẫn chỉ là di chuyển ngẫu nhiên.

*Hướng phát triển thêm:
- Chế độ chơi 2 người.
- Điều chỉnh nhân vật AI.
- Fix lỗi thanh gỗ bị con lợn xuyên qua.



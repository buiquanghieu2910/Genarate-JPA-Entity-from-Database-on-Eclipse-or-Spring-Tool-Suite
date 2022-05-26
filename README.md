# Genarate-JPA-Entity-from-Database-on-Eclipse-or-Spring-Tool-Suite

<p>Step 1: Install G9 on Eclipse</p>

```markdown
Help -> Eclipse MarketPlace -> Search từ khóa G9 -> Install g9 Datase Import (như hình bên dưới)
Đợi quá trình Install diễn ra khoảng 7-10p, sau đó có thông báo Restart IDE
```
![](https://i.imgur.com/cbgeXA0.png)


<p>Step 2: Import Database Model</p>

```markdown
Click chuột phải vào project cần genarate -> Import -> Import( như hình)
```
![](https://i.imgur.com/sliFzeS.png)

```markdown
Tìm đến folder g9 -> Chọn Import Database Model
```
![](https://i.imgur.com/z6zfZ17.png)

```markdown
JDBC Driver: chọn JDBC tương ứng với database đang dùng
Hostname: thông thường sẽ là "localhost", nếu ai dùng db trên server thì điền IP Address Public
Database: Tên database
Username: Tên user quản trị
Password: Mật khẩu tương ứng với user
Sau đó bấm Fetch để kết nối
Nếu kết nối thành công thì bấm chọn Next (Như hình bên dưới)
```
![](https://i.imgur.com/8o8EI0w.png)

```markdown
Root package: Điền tên package chứa đựng entity 
Select all để chọn tất cả các table cần genarate hoặc select table cần genarate
Lưu ý: Có thể tùy biến Class name bằng cách select bất kỳ dòng nào muốn tùy biến ở cột Class name sau đó chọn Edit
Cuối cùng chọn Finsh để quá trình genarate được diễn ra 
(Như hình bên dưới)
```
![](https://i.imgur.com/3v3rxxG.png)

```markdown
Đây là thành quả sau khi genarate
```
![](https://i.imgur.com/BjFaquQ.png)

***Chúc các bạn thành công !!!***

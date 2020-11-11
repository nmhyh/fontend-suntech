1. Tại sao sử dung HTML
2. Cách tạo trang HTML & cấu trúc HTML
3. Cấu trúc và quy tắc của thẻ HTML
- Thông thường thẻ HTML sẽ có thẻ đóng và thẻ mở
- Thẻ HTML có tên giống nhau ở thẻ đóng mở, chỉ khác nhau ở dấu /
- Trường hợp đb thì sẽ không có thẻ đóng, nhưng có đóng thẻ trên chính nó
- Một thẻ HTML có thể không có, có 1 hoặc nhiều thuộc tính
<tagName attribute="value1" attribute="value2" ...>Nội dung</tagName>
hoặc
<tagName attribute="value1" attribute="value2"/>
Nội dung bọc giữa thẻ đóng và mở: Text, Image, Video, các thẻ HTML
- Có thể tự định nghĩa thẻ HTML
4. Các thẻ HTML thường dùng
4.1. Nhóm các thẻ tiêu đề (nội dung). Trong 1 trang web thì chỉ có 1 thẻ <h1>
	h1 -> h6
	<h1>Nội dung</h1>
	<h2>Nội dung</h2>
	<h3>Nội dung</h3>
	...
4.2. Tiêu đề của trang
	<title>Nội dung tiêu đề</title>
	SEO: Quan trọng
4.3. Các thẻ thể hiện văn bản
- <p>Nội dung</p>
    Thể hiện đoạn văn bản
- <br/>: Xuống dòng
- <u>Nội dung</u>: Gạch chân
- <del>Nội dung</del>: Xóa văn bản
- <i>Nội dung</i>: In nghiêng
- <hr/>: đường gạch
- <font color="" size=""></font>
- <b>Nội dung</b> & <strong>Nội dung</strong>: dùng để in đậm văn bản
    SEO: <strong> tốt hơn
- Thẻ thể hiện danh sách: <ul> dùng nhiều làm menu
    <ul>
        <li>Nội dung</li>
        <li>Nội dung</li>
        <li>Nội dung</li>
    </ul>

    <ol>
        <li>Nội dung</li>
        <li>Nội dung</li>
        <li>Nội dung</li>
    </ol>
- Thẻ <pre>Nội dung</pre>: Giữ nguyên định dạng cho người dùng
4.4. Thẻ liên kết
    <a href="#" target="Cách mở trang">Nội dung</a>
    href:
        - Liên kết đến
        - Mặc định là #
    target: Qui định, cách mở trang
        + __blank: mở tab mới

4.5. Thẻ thể hiện hình ảnh
    <img src="" alt="" width="" height="">
   src: đường dẫn của ảnh
   alt: mô tả cho ảnh
   width: chiều rộng
   height: chiều cao

4.6. Các loại thẻ HTML
Có 3 loại thẻ HTML
    - Block: <div>Nội dung</div> (trải dài toàn màn hình)
    - Inline: <span>Nội dung</span> (trải dài nội dung)
    - None: <meta charset="utf-8"/>

5. Thẻ Table
    <table align=""width="" border="" cellpadding="" cellspacing="">
        <tr>
            <td>1</td>
            <td>1</td>
            <td>1</td>
            <td>1</td>
            <td>1</td>
        </tr>
        <tr>
            <td>1</td>
            <td>1</td>
            <td>1</td>
            <td>1</td>
            <td>1</td>
        </tr>
        <tr>
            <td>1</td>
            <td>1</td>
            <td>1</td>
            <td>1</td>
            <td>1</td>
        </tr>
    </table>

Thuộc tính dùng chung table, tr, td:
    - width: Qui định độ rộng của trang
    - align: (left|right|center) canh lề table so với trình duyệt
    - border: Qui định đường viền
    - bgcolor: Qui định màu nền
Thuộc tính cho td:
    - valign: (top|midlle|bottom) Canh nội dung trong cột theo chiều dọc
* Gộp dòng và gộp cột trong table
    - Gộp dòng:
        + rowspan="number"
    - Gộp cột:
        + colspan="number"



aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa


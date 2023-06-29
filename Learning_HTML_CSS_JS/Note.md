-----------------------------------------------------  HỌC HTML,CSS ----------------------------------------------------------------------------
- Một số hàm trong CSS ?
 1. var()
 2. linear-gradient()
 3. rgba()
 4. calc()
 5. attr()
- Một số Pseudo-class trong CSS ?
 1. :root
 2. :hover
 3. :first-child
 4. :last-child
- Một số Pseudo-element trong CSS ?
 1. :before
 2. :after
 3. :first-letter
 4. :last-line
 5. :selection
- Các thuộc tính đệm, viền, khoảng lề trong CSS ?
 1. padding 
 2. margin
 3. border
 4. box-sizing
- Các thuộc tính tạo nền trong CSS ?
 1. background-image: url();
 2. background-size có hai thuộc tính nhỏ là cover và contain
 3. background-repeat
 4. background-origin
 5. background-position
- Các thuộc tính vị trí trong CSS ?
 1. position: relative
    . Đặt phần tử trong vị trí tương đối so với vị trí ban đầu.
 2. position: absolute
    . Đặt phần tử trong vị trí tuyệt đối so với phần tử cha gần nhất có vị trí không phải là static.
 3. position: fixed
    . Đặt phần tử trong vị trí tuyệt đối và luôn hiển thị ở cùng một vị trí trên trang web, không bị ảnh hưởng bởi cuộn trang.
 4. position: sticky
    . Đặt phần tử trong vị trí tương đối cho đến khi cuộn trang đến một ngưỡng, sau đó chuyển sang vị trí tuyệt đối và giữ vị trí đó khi cuộn tiếp.
- Làm Header cho Website ?
/**Ví dụ:
 





**/
- Làm navigation cho Website ?
/**Ví dụ:
 


**/
- Làm Header search cho Website ?
- Làm Header fixed cho website ?
- Làm Slider cho website ?

/**
   Cách xác định:
     + Vị trí
     + Kích thước (width, height)
     + Màu sắc
     + Kiểu dáng (kiểu chữ, hình tròn, vuông, ...)
**/

- Làm phần About section CSS cho Website ?























------------------------------------------------------ HỌC JAVASCRIPPT -------------------------------------------------------------------------
//--- Note ---//

- Built-in là gì ?
 1. Alert 
 2. Console
 3. Confirm
 4. Prompt
 5. Set interval
 6. Set timeout

 /**Ví dụ:

     var fullName = 'Nguyen Duc Hieu';
     var age = 21;

     console.log(fullName);

     prompt('Xác nhận bạn đủ tuổi');

     setTimeout(function () {
          alert('Hello')
     }), 1000

     setInterval(function () {
          alert('Hello' + Math.random());
     }), 1000

 **/

 //--- Note ---//

 - Toán tử trong JavaScript
 1. Toán tử số học 
 2. Toán tử gán
 3. Toán tử so sánh
 4. Toán tử logic

 /**Ví dụ:

    var fullName = 'Nguyen Duc Hieu';

    var a = 2;
    var b = 1;

    if (a>0 && b>0) {
        alert('a và b lớn hơn không')
    }

 **/

   + Toán tử số học:

    var a = 5, b = 2;
    var c = a + b;
    console.log(c);

   + Toán từ ++ và --

    x++ tăng giá trị biến lên 1 và trả về giá trị trước khi tăng
    ++x tăng giá trị biến lên 1 và trả về giá trị sau khi tăng
    x-- giảm giá trị biến xuống 1 và trả về giá trị trước khi giảm
    --x giảm giá trị biến xuống 1 và trả về giá trị sau khi giảmm   

    /**Ví dụ:

        var a = 6;
        var output = ++a * 2 - a-- *2;
        console.log('output: ' + output)        

        // 7 * 2 - 7 * 2 = 0
    **/

   + Toán tử chuỗi:

   /**ví dụ:

        var firstName = 'Hieu';
        var lastName  = 'Nguyen';

        console.log(firstName + ' ' + lastName);    

   **/

     

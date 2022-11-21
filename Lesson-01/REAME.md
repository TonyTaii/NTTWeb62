# Review ES6

## 1. Sự khác biệt nhé giữa let, const và var

 Scope:
        - global
        - function
        - block scope: 

    1. Sự khác biệt nhé giữa let, const và var
        * scope (Phạm vị)
            var -> global 
            const, let: function, block

        * assignment
            const: không thể re-assign
            let và var là có thể

        * hoisting
            var có thể sử dụng trước khi khai báo
            let, const 
    
    2. es6
        - map
        - filter
        - reduce
        - some
        - every
        - find
        - findIndex
        - for with index (for(let i = 0; i < nums.lentgh ; i++))
        - for in
        - for of
        - for each
    
    3. Spread operator (...)
    -Dùng để rải các thành phần trong array hoặc object thành các thành phần riêng biệt 
    Vd: ...[1,3,5] sẽ trở thành tương đương (1,3,5)
    -Sao chép một mảng
    -Tách hoặc kết hợp một hay nhiều mảng
    -Sử dụng mảng như danh sách các argument
    -Thêm một item vào một list
    -Thao tác với state trong React
    -Kết hợp các objects
    -Chuyển NodeList thành một array

    4. String template (literals string)
    -Syntax : `string string ${biến hoặc một tham số}` thay vì 'string' +'string' + biến 
    5. Arrow function
        - Có bao nhiêu loại function:
        +Declaration Function: Đây là loại khai báo function cơ bản trong javascript và với loại này sẽ có áp dụng Hoisting trong javascript.
        vd: function doSomething() {console.log('doSomething')}
        + Arrow function: là function có cú pháp ngắn hơn cú pháp function bình thường
        +Expression Function (anonymous function):Hay còn gọi là anonymous function (function không tên).
Function kiểu này sẽ được gán vào một biến và nó chỉ sẽ chạy khi runtime nếu biến đó được gọi
        +Higher-Order Functions:Higher-Order function là hàm nhận một hàm dưới dạng đối số hoặc trả về hàm dưới dạng đầu ra.
        - Sự khác biệt giữa các loại function:
        Chỉ Declaration Function áp dụng Hoisting
        - Tại sao ES6 arrow function const getSum = (nums) => {} (bind, call, this)

    6. Destructuring
        - Object destructuring
        - Array destructuring

    7. Promise: cách tự tạo 1 cái promise, mỗi cái promise có state, cách handle promise => async/await, event-loop
    8. Class 
# Phần 1: CSS cơ bản

1. Hiểu CSS và cách tích hợp
- CSS là file trang trí và làm đẹp cho trang web, tích hợp ở trong file HTML.
- Các kiểu tích hợp CSS:
  * Inline: Dùng ngay ở trong 1 thẻ
    ```html
    <p style="color: blue; font-size: 2em; text-align: center;">
      Ví dụ cho CSS Inline
    </p>
  * Internal: Viết tại phần head
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
        <style>
            /* CSS Internal */
        </style>
    </head>
    <body>
        
    </body>
    </html>
    ```
  * External: Tách riêng hẳn ra 1 file css và được liên kết với file html thông qua lệnh link
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
        <link rel="stylesheet" href="abc.css">
    </head>
    <body>
        
    </body>
    </html>
    ```
---

# Phần 2: Styling cơ bản (Mỗi mục em sẽ viết kiểu Internal để khỏi thêm file vào ạ)

3. Typography (Kiểu chữ)
   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Document</title>
      <style>
         #p1{
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: 1em;
            font-weight: bold;
            color: rgb(50, 50, 50);
            text-align: left;
            line-height: 1.5em;
         }
      </style>
   </head>
   <body>
      <p id="p1">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officiis assumenda consequuntur nisi provident ex, illo, inventore quam commodi quisquam modi repudiandae, nulla praesentium fuga dolorem? Ea cum incidunt repellat at?</p>
   </body>
   </html>
   ```
5. Background & Colors
6. Box Model

---

# Phần 3: Layout và Positioning

--- 
# Phần 4: Responsive Design

---
# Phần 5: CSS Effects và Animations

---
# Phần 6: Thực hành


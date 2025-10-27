# Phần 1: CSS cơ bản

1. Hiểu CSS và cách tích hợp
- CSS là file trang trí và làm đẹp cho trang web, tích hợp ở trong file HTML.
- Các kiểu tích hợp CSS:
  * Inline: Dùng ngay ở trong 1 thẻ
    ```
    <p style="color: blue; font-size: 2em; text-align: center;">
      Ví dụ cho CSS Inline
    </p>
  * Internal: Viết tại phần head
  ```
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
  *External: Tách riêng hẳn ra 1 file css và được liên kết với file html thông qua lệnh link
  ```
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
  

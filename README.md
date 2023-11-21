# Exp-10-Create-a-Gliding-box-using-CSS-Animation
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gliding Box Animation</title>
  <style>
    body {
        margin: 0;
        padding: 0;
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100vh;
        background-color: #f4f4f4;
      }
      
      .gliding-box {
        width: 100px;
        height: 100px;
        background-color: #000000;
        animation: glide 2s linear infinite;
      }
      
      @keyframes glide {
        0% {
          transform: translateX(0);
        }
        50% {
          transform: translateX(200px);
        }
        100% {
          transform: translateX(0);
        }
      }
      
  </style>
</head>
<body>
    <h1>Gliding Box Animation</h1>
  <div class="gliding-box"></div>
</body>
</html>

```
# output
![image](https://github.com/dhinesh102004/Exp-10-Create-a-Gliding-box-using-CSS-Animation/assets/142372008/5f85f39f-73fb-408e-9539-610a5756aedc)


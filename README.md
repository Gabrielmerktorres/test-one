<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Webpage</title>

```
<style>
    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
        font-family: Arial, sans-serif;
    }

    body {
        min-height: 100vh;
        background: linear-gradient(135deg, #111827, #1e1b4b);
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .container {
        width: 90%;
        max-width: 900px;
        text-align: center;
        padding: 50px 30px;
        background: rgba(255, 255, 255, 0.08);
        border: 1px solid rgba(255, 255, 255, 0.15);
        border-radius: 25px;
        backdrop-filter: blur(15px);
        box-shadow: 0 20px 60px rgba(0, 0, 0, 0.4);
    }

    h1 {
        font-size: 55px;
        margin-bottom: 15px;
    }

    p {
        font-size: 18px;
        color: #d1d5db;
        margin-bottom: 30px;
    }

    button {
        border: none;
        padding: 14px 30px;
        border-radius: 12px;
        background: white;
        color: #111827;
        font-size: 16px;
        font-weight: bold;
        cursor: pointer;
        transition: 0.2s;
    }

    button:hover {
        transform: scale(1.05);
    }

    #message {
        margin-top: 25px;
        font-size: 18px;
        color: #a5b4fc;
    }
</style>
```

</head>

<body>

```
<div class="container">
    <h1>My Website</h1>

    <p>
        Welcome to my own webpage.
    </p>

    <button onclick="showMessage()">
        Click Me
    </button>

    <div id="message"></div>
</div>

<script>
    function showMessage() {
        document.getElementById("message").textContent =
            "Welcome! Your webpage is working.";
    }
</script>
```

</body>
</html>

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <script src="jquery-3.4.1.js"></script>
</head>
<body>
    <section class="login-from">
        <h1>로그인</h1>
        <from action="">
            <div class="int-area">
                <input type="text" name="id" id="id"
                autocomplete="off" required>
                <label for="id">USER NAME</label>
            </div>
            <div class="int-area">
                <input type="password" name="pw" id="pw"
                autocomplete="off" required>
                <label for="pw">PASSWORD</label>
            </div>
            <div class="btn-area">
                <button type="submit">LOGIN</button>
            </div>
        </from>
        <div class="caption">
            <a href="">Forgot Password?</a>
        </div>
    </section>
</body>
</html>

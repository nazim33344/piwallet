# piwallet
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wallet Unlock</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 400px;
        }
        h1 {
            color: #6c63ff;
            margin-bottom: 10px;
        }
        textarea {
            width: 100%;
            height: 100px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            margin-bottom: 20px;
            resize: none;
        }
        button {
            background-color: #6c63ff;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #5a53d1;
        }
        p {
            font-size: 14px;
            color: #666;
            margin-top: 10px;
        }
        a {
            color: #6c63ff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Wallet Unlock</h1>
        <textarea placeholder="Enter your 24-word passphrase here"></textarea>
        <button>Unlock with Passphrase</button>
        <p>This is a non-custodial wallet. Your passphrase is the only way to access your wallet. We cannot recover lost passphrases.</p>
        <p>If you've lost your passphrase, <a href="#">create a new wallet</a>. Note: previous wallet balances will not be accessible.</p>
    </div>
</body>
</html>

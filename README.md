<!DOCTYPE html>
<html>
<head>
    <title>Reward Notification - Demo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            padding-top: 80px;
        }

        .card {
            background: white;
            width: 400px;
            margin: auto;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        h2 {
            color: green;
        }

        button {
            padding: 10px 20px;
            background-color: orange;
            border: none;
            color: white;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: darkorange;
        }

        #message {
            margin-top: 20px;
            display: none;
            color: blue;
            font-weight: bold;
        }

        .note {
            margin-top: 30px;
            font-size: 12px;
            color: red;
        }
    </style>
</head>
<body>

<div class="card">
    <h2>Reward Notification</h2>
    <p>Hello <strong>Catalin Lilian Borous</strong>,</p>
    <p>You have a pending reward of <strong>€3000</strong>.</p>

    <button onclick="claimReward()">Claim Reward</button>

    <div id="message">
        ✅ Demo Successful! This is only a practice project.
    </div>

    <div class="note">
        ⚠ This is a demo page for learning HTML & JavaScript only.
    </div>
</div>

<script>
    function claimReward() {
        document.getElementById("message").style.display = "block";
    }
</script>

</body>
</html>


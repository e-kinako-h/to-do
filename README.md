# to-do
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>To Doリスト</title>
  <style>
    body {
      font-family: sans-serif;
      background-color: #fff9e6;
      margin: 20px;
    }

    h1 {
      color: #d4a000;
      text-align: center;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      background-color: #fff;
    }

    th, td {
      border: 1px solid #ccc;
      padding: 12px;
      text-align: left;
    }

    th {
      background-color: #fff3b0;
    }

    tr:nth-child(even) {
      background-color: #f9f9f9;
    }

    input[type="checkbox"] {
      transform: scale(1.3);
    }
  </style>
</head>
<body>
  <h1>✅ To Doリスト</h1>

  <table>
    <tr>
      <th>✔</th>
      <th>タスク内容</th>
      <th>期限</th>
      <th>優先度</th>
      <th>メモ・進捗</th>
    </tr>
    <tr>
      <td><input type="checkbox"></td>
      <td>数学の宿題をやる</td>
      <td>7/30(火)</td>
      <td>★★★</td>
      <td>問題7〜12</td>
    </tr>
    <tr>
      <td><input type="checkbox"></td>
      <td>英単語を30個覚える</td>
      <td>7/29(月)</td>
      <td>★★</td>
      <td>Quizletで練習</td>
    </tr>
    <tr>
      <td><input type="checkbox"></td>
      <td>プレゼント選ぶ</td>
      <td>8/1(木)</td>
      <td>★★☆</td>
      <td>雑貨屋に行く</td>
    </tr>
  </table>
</body>
</html>

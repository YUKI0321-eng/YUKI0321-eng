<h1>Hi there 👋 I'm Yuki.</h1>
<p>
  I am a third year university student who major in aerospace engineering.<br>
  In the future I want to be a great engineer. <br>
  I'll record my code study path here.<br>

  私は航空宇宙工学を専攻する大学3年生です．<br>
  将来は優秀なエンジニアになりたいと思っています．<br>
  ここにコードの学習記録を残していきます．
</p>

<h1>What I try now </h1> 

<h2>Real flying bloom Project🧹　空飛ぶほうきプロジェクト</h2>　

I will participate the glider championship tournament with a unique one.<br>
The pourpose of the project is "make children interested in engineerng"<br>

空飛ぶほうきでグライダー大会に出場します<br>
プロジェクトの目的は子供たちがものづくりに興味を持つようにすることです
 
<h2>study in India🍛　インド留学</h2>

I am going to study at IIT madras for 2eeks.<br>
I will visit reserch center in India <br>

2週間インド工科大マドラス校で学んできます<br>
インドの研究機関を見学する予定です




<h1>学習記録</h1>
コード学習の記録を断片的に載せています


<h2>2026/2/15~2026/2/21<br>
はじめてのHTML＆CSS</h2>
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Page</title>
    <style>
        /* CSSをここに記述（埋め込みスタイル） */
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            background-color: #f4f7f6;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .profile-card {
            background-color: #fff;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            text-align: center;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%; /* 正円にする設定 */
            object-fit: cover;
            border: 3px solid #007bff;
            margin-bottom: 15px;
        }

        h1 {
            color: #333;
            font-size: 24px;
            margin-bottom: 5px;
        }

        .bio {
            color: #666;
            line-height: 1.6;
            margin-bottom: 20px;
        }

        .gallery {
            display: flex;
            gap: 10px;
            justify-content: center;
        }

        .gallery a img {
            width: 80px;
            height: 80px;
            border-radius: 8px;
            transition: transform 0.2s;
        }

        .gallery a img:hover {
            transform: scale(1.1); /* ホバー時に少し大きく */
        }
    </style>
</head>
<body>

    <div class="profile-card">
        <img src="https://via.placeholder.com/150" alt="プロフィール画像" class="profile-img">
        
        <h1>高橋 勇輝</h1>
        <p class="bio">
            名古屋大学 航空宇宙工学 3年．<br>
            流体力学や材料力学を学びつつ，最近はPythonやWeb制作にも挑戦中です．
        </p>

        <div class="gallery">
            <a href="#"><img src="https://via.placeholder.com/80" alt="Work 1"></a>
            <a href="#"><img src="https://via.placeholder.com/80" alt="Work 2"></a>
            <a href="#"><img src="https://via.placeholder.com/80" alt="Work 3"></a>
        </div>
    </div>

    <script>
        // JavaScriptによるインタラクション
        document.querySelectorAll('.gallery img').forEach(img => {
            img.addEventListener('click', () => {
                alert('画像がクリックされました！');
            });
        });
    </script>
</body>
</html>

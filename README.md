<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>20wns Site</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
        }
        .search-bar, .recommended-video, .shorts {
            border: 1px solid black;
            margin: 10px;
            padding: 20px;
            box-sizing: border-box;
        }
        .search-bar {
            width: 100%;
            text-align: center;
        }
        .video-section {
            display: flex;
            flex-wrap: wrap;
            width: 70%;
        }
        .video-section .recommended-video {
            width: 45%;
        }
        .shorts-section {
            width: 25%;
            display: flex;
            flex-direction: column;
        }
        .shorts {
            flex: 1;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="search-bar">구글 검색</div>
    <div class="search-bar">유튜브 검색</div>
    <div class="video-section">
        <div class="recommended-video">추천영상</div>
        <div class="recommended-video">추천영상</div>
        <div class="recommended-video">추천영상</div>
        <div class="recommended-video">추천영상</div>
    </div>
    <div class="shorts-section">
        <div class="shorts">쇼츠</div>
        <div class="shorts">쇼츠</div>
    </div>
</div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>What is AI Automation?</title>
    <link href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@400;600;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Source Sans Pro', sans-serif;
            overflow: hidden;
            background-color: #f8f9fa;
            color: #37474F;
        }
        .slide {
            width: 1280px;
            min-height: 720px;
            position: relative;
            display: flex;
            flex-direction: column;
        }
        .header {
            padding: 40px 70px 20px;
        }
        .title {
            font-size: 40px;
            font-weight: 700;
            color: #0A192F;
            margin-bottom: 10px;
        }
        .content {
            display: flex;
            flex-grow: 1;
            padding: 0 70px 40px;
        }
        .left-content {
            flex: 1;
            padding-right: 30px;
        }
        .right-content {
            flex: 1;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .definition {
            background-color: #E3F2FD;
            border-left: 4px solid #2196F3;
            padding: 20px;
            border-radius: 4px;
            margin-bottom: 30px;
        }
        .definition p {
            font-size: 20px;
            line-height: 1.5;
        }
        .comparison {
            margin-top: 30px;
        }
        .comparison h3 {
            font-size: 24px;
            margin-bottom: 15px;
            color: #0A192F;
        }
        .comparison-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }
        .comparison-item {
            background-color: #fff;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.08);
        }
        .comparison-item h4 {
            font-size: 20px;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
        }
        .comparison-item h4 i {
            margin-right: 8px;
            color: #2196F3;
        }
        .comparison-item ul {
            list-style-type: none;
            padding-left: 28px;
        }
        .comparison-item li {
            font-size: 18px;
            margin-bottom: 8px;
            position: relative;
        }
        .comparison-item li:before {
            content: "•";
            color: #2196F3;
            position: absolute;
            left: -15px;
        }
        .image-container {
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .image-container img {
            max-width: 100%;
            max-height: 400px;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body>
    <div class="slide">
        <div class="header">
            <h1 class="title">What is AI Automation?</h1>
        </div>
        <div class="content">
            <div class="left-content">
                <div class="definition">
                    <p>AI automation combines artificial intelligence with automation to handle both structured and unstructured tasks, enabling systems to learn, adapt, and make decisions with minimal human intervention.</p>
                </div>
                
                <div class="comparison">
                    <h3>How It Differs From Traditional Automation</h3>
                    <div class="comparison-grid">
                        <div class="comparison-item">
                            <h4><i class="material-icons">settings</i>Traditional Automation</h4>
                            <ul>
                                <li>Rule-based</li>
                                <li>Follows predefined instructions</li>
                                <li>Handles repetitive tasks</li>
                                <li>Limited adaptability</li>
                            </ul>
                        </div>
                        <div class="comparison-item">
                            <h4><i class="material-icons">psychology</i>AI Automation</h4>
                            <ul>
                                <li>Learns from data</li>
                                <li>Adapts to new situations</li>
                                <li>Handles complex decision-making</li>
                                <li>Improves over time</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
            <div class="right-content">
                <div class="image-container">
                    <img src="https://sfile.chatglm.cn/images-ppt/5c11d4591c70.jpg" alt="Difference between traditional automation and AI automation">
                </div>
            </div>
        </div>
    </div>
</body>
</html>

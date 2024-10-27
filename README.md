石墨烯微芯片世界领先
Leading the world in graphene microchips


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image and Text Swap</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+SC:wght@400;700&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f4f4f4;
            background-image: url('NewBG3.png'); /* Replace with your PNG file path */
            background-repeat: repeat; /* Makes the image repeat */
            background-size: auto; /* Default image size; can also use cover, contain, or custom dimensions */
            font-family: 'Noto Sans SC', 'Roboto', sans-serif;
        }
        h1, h2, h3, h4, h5, h6 {
  font-family: 'Roboto', sans-serif; /* Use Roboto for headings */
}

p, li, span {
  font-family: 'Noto Sans SC', sans-serif; /* Use Noto Sans CJK for body text */
}
        .container {
            position: relative;
            text-align: center;
        }
        .text {
            position: absolute;
            top: 20px;
            left: 50%;
            transform: translateX(-50%);
            font-size: 24px;
            color: white;
        }
        .image {
            width: 300px; /* Adjust as needed */
            height: auto;
        }
        /* Apply background style to the whole page */
    </style>
</head>
<body>
<h1>Hello World</h1>
<p>I'm hosted with GitHub Pages.</p>
<img id="logo" class="image" src="PARAGRAF-LOGO_Full-Colour-Chinese-1024x339.png" alt="Paragraf 湃瑞科技">
<div class="container">
    <img id="image" class="image" src="hddie3DC_IMG_5702.JPG" alt="Image 1">
    <div id="text" class="text">石墨烯微芯片</div>
</div>

<script>
    const images = [
        { src: 'hddie3DC_IMG_5702.JPG', text: '快速', hoverText: 'Fast' },
        { src: 'image2.jpg', text: '省电', hoverText: 'Power efficient' },
        { src: 'image3.jpg', text: '强壮', hoverText: 'Robust' }
    ];
    let currentIndex = 0;

    const imageElement = document.getElementById('image');
    const textElement = document.getElementById('text');

    function updateContent() {
        const { src, text } = images[currentIndex];
        imageElement.src = src;
        textElement.innerText = text;
    }

    function nextImage() {
        currentIndex = (currentIndex + 1) % images.length;
        updateContent();
    }

    imageElement.addEventListener('mouseover', () => {
        textElement.innerText = images[currentIndex].hoverText;
    });

    imageElement.addEventListener('mouseout', () => {
        textElement.innerText = images[currentIndex].text;
    });

    setInterval(nextImage, 3000);
    updateContent(); // Initial load
</script>

test Web
Paragraf
湃瑞科技


石墨烯微芯片世界领先
Leading the world in graphene microchips

石墨烯微芯片
Graphene microchips

leading the world in graphene electronics
石墨烯电子领域世界领先
graphene electronics
石墨烯电子产品
石墨烯微芯片
Graphene microchips
Graphene micorelectronics
石墨烯微电子

graphene microelectronics available now
石墨烯微电子现已上市

Graphene microelectronics are already on the market
石墨烯微电子已经上市

Pioneering graphene microelectronics
开创石墨烯微电子技术

Leading the world in graphene microelectronics
石墨烯微电子技术世界领先

磁场传感器 magnetic field sensor
电流传感器 current sensor
分子传感器 molecular sensor
场效应晶体管 field effect transistor
场效应管 FET
石墨烯场效应晶体管 GFET
立即购买 buy now
如果你无法访问，请给我们发电子邮件 If you don't have access, please email us
低温兼容 cryogenic compatible
霍尔效应传感器 Hall effect sensor
  
</body>
</html>

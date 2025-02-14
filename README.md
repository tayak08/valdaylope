<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surat Cinta</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #ffe6e6;
            padding: 20px;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 80%;
            max-width: 600px;
            margin: auto;
        }
        h1 {
            color: #ff3366;
            font-size: 48px;
            font-weight: bold;
        }
        h2 {
            color: #ff6699;
            font-size: 24px;
        }
        .button-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 20px;
        }
        .btn {
            padding: 10px 20px;
            background: #ff3366;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 20px;
            border: none;
            cursor: pointer;
        }
        .btn:hover {
            background: #cc0052;
        }
        .message-box {
            display: none;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 80%;
            max-width: 600px;
            margin: 20px auto;
        }
        .back-btn {
            margin-top: 20px;
            background: #666;
        }
    </style>
    <script>
        function showMessage(name) {
            const messages = {
                'Samuel': 'Hai Samuel! Happy Valentine. Terima kasih untuk banyak momen yg dilewati same2 ye.. jangan lupa wish STAR yaa HAHA. Jangan lupa buat paspor wkwk daaannnnn jangan lupa ada hutangmu samaku yaaa, jadi guest Alki-TOP HAHA. I Love u Sam ✨',
                'Agnes': 'Hai Rambuku cinaa! Terima kasih untuk banyak momen yg dilewati same2 ye.. semangat pelayanannya ya teteh HAHAHA. Jangan lupakan aku ya wkwk. Happy Valentines. I Love u Rambu✨',
                'Ruth': 'Hawoo kak Ruthhhhh... Happy Valentines! Terima kasih untuk banyak momen yg dilewati same2 ye.. 3 Tahun lagi kita akan jungkir balikan SG yaa kak. Semangat untuk pelayanannya ya ibu Guru.. see you di 2028. I Love U kak Ruth✨',
                'Miranda': 'Selamat Valentine kak Miraaa! liburan kemana kita kak? Blitar? hahaha.  I Love U kak Miraa',
                'Lisa': 'Happy Valentine icaaakuuu! Semangat ibu guruuuuu hahahaha. Semoga harimu lebih menyenangkan dengan bocil drpd sama bekicot hahaha. I Love U cICAk',
                'Anggi': 'Selamat valentine kakk Anggi, tetap happy,  meskipun kerjaan full beestiii! ke Cangar lagi kita kak? hahah I Love U kak Anggiiii',
                'Dea': 'Deboyyyy..... Semoga hidupmuu penuhhh tawa dan bahagiaa yaaa dengan kak Angri yaw hahahaha , Happy Valentine! I Love U deboyy',
                'Vilia': 'Halooo Kak Vill... Selamat merayakan kasih sayang bersama orang Sabu yaaa...🎉 I love u',
                'Meys': 'Selamat Valentine Kakak Eyyss! Semoga harinyaa lancar ya.  Love U',
                'Kak Joel': 'Haii Kak Joee... Selamat Valentine yaakk... G bisa buat Puisi nihh tapi yang pasti. Selamat menikmati kasih setiap hari. I Love U kak Joe',
                'Kak Pierre': 'Happy Valentine’s Day Kak Pierreeee! Semoga selalu bahagia yaaa kakkz😁 JAYA JAYA JAYA. I Love U kak Piii',
                'Kak Meta': 'Halooo Kak Metaaaa, Selamat Valentine yaaakkk! Semoga hari kakakkk menyenangkan selaluu...🥰 I Love U kak Metaa',
                'Kak Evan': 'Happy Valentine Kak epaannn! Jangan lupa makan enak hari ini. Hokben kita? I Love U kak Epan',
                'Kak G': 'Haiii Kakk G akuuu...Selamattt harii kasih sayang (yang tertanggal - soalnya setiap hari hari kasih sayang kan kakkk hehehehehe😁 I Love U kak G'
            };            
            document.getElementById("main").style.display = "none";
            const messageBox = document.getElementById("message-box");
            messageBox.innerHTML = `<p>${messages[name]}</p><button class='btn back-btn' onclick='goBack()'>Balek</button>`;
            messageBox.style.display = "block";            
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }
        function goBack() {
            document.getElementById("message-box").style.display = "none";
            document.getElementById("main").style.display = "block";
        }
    </script>
</head>
<body>
    <div id="main">
        <h1>Hai Gais!</h1>
        <h2>Happy Valentine's. I Love U!</h2>
        <h3>In Christ Millytiyaw</h3>
        <div class="container">
            <div class="button-container">
                <button class="btn" onclick="showMessage('Samuel')">Samuel</button>
                <button class="btn" onclick="showMessage('Agnes')">Agnes</button>
                <button class="btn" onclick="showMessage('Ruth')">Ruth</button>
            </div>
        </div>
        <div class="container" style="margin-top: 20px;">
            <div class="button-container">
                <button class="btn" onclick="showMessage('Miranda')">Miranda</button>
                <button class="btn" onclick="showMessage('Lisa')">Lisa</button>
                <button class="btn" onclick="showMessage('Anggi')">Anggi</button>
                <button class="btn" onclick="showMessage('Dea')">Dea</button>
                <button class="btn" onclick="showMessage('Vilia')">Vilia</button>
                <button class="btn" onclick="showMessage('Meys')">Meys</button>
            </div>
        </div>
        <div class="container" style="margin-top: 20px;">
            <div class="button-container">
                <button class="btn" onclick="showMessage('Kak Joel')">Kak Joel</button>
                <button class="btn" onclick="showMessage('Kak Pierre')">Kak Pierre</button>
                <button class="btn" onclick="showMessage('Kak Meta')">Kak Meta</button>
                <button class="btn" onclick="showMessage('Kak Evan')">Kak Evan</button>
                <button class="btn" onclick="showMessage('Kak G')">Kak G</button>
            </div>
        </div>
    </div>
    <div id="message-box" class="message-box"></div>
</body>
</html>

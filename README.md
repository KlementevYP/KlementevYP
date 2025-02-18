# 💫 About Me:
🔭 I'm currently working on small business projets<br>🤝 I'm looking to collaborate on universal web development<br>🔍 I'm looking for help with mini apps for MacOS<br>🌱 I'm currently learning React, GOlang, Fast-api<br>💬Ask me about Algorithms and data structures<br>⚡️Fun fact: I also write programs for microcontrollers, and I'm not really happy about it
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Часы с цифровыми стрелками</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #222;
        }
        .clock {
            position: relative;
            width: 450px;
            height: 450px;
            border-radius: 50%;
            background: white;
            border: 5px solid black;
        }
        .hand {
            position: absolute;
            bottom: 50%;
            left: 50%;
            transform-origin: bottom;
            font-size: 18px;
            font-weight: bold;
            color: red;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
    </style>
</head>
<body>
    <div class="clock">
        <div id="hour" class="hand"></div>
        <div id="minute" class="hand"></div>
        <div id="second" class="hand"></div>
    </div>

    <script>
        function repeatText(value, times) {
            return Array(times).fill(value).join(' ');
        }

        function updateClock() {
            const now = new Date();
            const hours = now.getHours() % 12;
            const minutes = now.getMinutes();
            const seconds = now.getSeconds();
            
            const hourAngle = (hours + minutes / 60) * 30;
            const minuteAngle = (minutes + seconds / 60) * 6;
            const secondAngle = seconds * 6;

            const hourHand = document.getElementById('hour');
            const minuteHand = document.getElementById('minute');
            const secondHand = document.getElementById('second');
            
            hourHand.innerHTML = repeatText(hours || 12, 5).replace(/ /g, '<br>');
            minuteHand.innerHTML = repeatText(minutes, 7).replace(/ /g, '<br>');
            secondHand.innerHTML = repeatText(seconds, 10).replace(/ /g, '<br>');
            
            hourHand.style.transform = `translate(-50%, 0) rotate(${hourAngle}deg)`;
            minuteHand.style.transform = `translate(-50%, 0) rotate(${minuteAngle}deg)`;
            secondHand.style.transform = `translate(-50%, 0) rotate(${secondAngle}deg)`;
        }

        setInterval(updateClock, 1000);
        updateClock();
    </script>
</body>
</html>


## 🌐 Socials:
[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.gg/isuss) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/isussisme) [![Twitch](https://img.shields.io/badge/Twitch-%239146FF.svg?logo=Twitch&logoColor=white)](https://twitch.tv/1suss) 

# 💻 Tech Stack:
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white) ![Gunicorn](https://img.shields.io/badge/gunicorn-%298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![Adobe Illustrator](https://img.shields.io/badge/adobe%20illustrator-%23FF9A00.svg?style=for-the-badge&logo=adobe%20illustrator&logoColor=white) ![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white) ![Adobe Premiere Pro](https://img.shields.io/badge/Adobe%20Premiere%20Pro-9999FF.svg?style=for-the-badge&logo=Adobe%20Premiere%20Pro&logoColor=white) ![Blender](https://img.shields.io/badge/blender-%23F5792A.svg?style=for-the-badge&logo=blender&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Gimp](https://img.shields.io/badge/Gimp-657D8B?style=for-the-badge&logo=gimp&logoColor=FFFFFF) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=KlementevYP&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=KlementevYP&theme=tokyonight&hide_border=true)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=KlementevYP&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=KlementevYP&icon=6&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->

<!DOCTYPE html>
<html>
<head>
<style>
@keyframes neonGlow {
    0% { text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #00ffff, 0 0 40px #00ffff; }
    100% { text-shadow: 0 0 20px #fff, 0 0 30px #ff00ff, 0 0 40px #ff00ff, 0 0 50px #ff00ff; }
}

@keyframes backgroundPulse {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}

@keyframes float {
    0% { transform: translateY(0px); }
    50% { transform: translateY(-20px); }
    100% { transform: translateY(0px); }
}

body {
    background: linear-gradient(45deg, #000428, #004e92, #2a0845);
    background-size: 400% 400%;
    animation: backgroundPulse 15s ease infinite;
    color: white;
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 40px;
}

.container {
    max-width: 800px;
    margin: 0 auto;
    background: rgba(0, 0, 0, 0.7);
    border-radius: 20px;
    padding: 30px;
    box-shadow: 0 0 20px rgba(0, 255, 255, 0.3);
}

h1 {
    font-size: 3em;
    text-align: center;
    color: #fff;
    animation: neonGlow 2s ease-in-out infinite alternate;
    margin-bottom: 30px;
}

h2 {
    color: #00ffff;
    border-bottom: 2px solid #00ffff;
    padding-bottom: 10px;
    margin-top: 30px;
    text-shadow: 0 0 10px rgba(0, 255, 255, 0.5);
}

.tech-stack {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
    margin: 20px 0;
}

.tech-item {
    background: rgba(0, 255, 255, 0.1);
    padding: 10px 20px;
    border-radius: 15px;
    border: 1px solid #00ffff;
    animation: float 3s ease-in-out infinite;
}

.social-links {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin: 30px 0;
}

.social-button {
    padding: 10px 20px;
    background: linear-gradient(45deg, #ff00ff, #00ffff);
    border: none;
    border-radius: 25px;
    color: white;
    text-decoration: none;
    font-weight: bold;
    transition: all 0.3s ease;
}

.social-button:hover {
    transform: scale(1.1);
    box-shadow: 0 0 20px rgba(255, 0, 255, 0.5);
}

.highlight {
    color: #ff00ff;
    font-weight: bold;
}

ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    margin: 10px 0;
    padding-left: 20px;
    position: relative;
}

ul li::before {
    content: '▸';
    color: #00ffff;
    position: absolute;
    left: 0;
}

.profile-section {
    margin: 30px 0;
    padding: 20px;
    background: rgba(255, 255, 255, 0.05);
    border-radius: 15px;
    backdrop-filter: blur(5px);
}
</style>
</head>
<body>
<div class="container">
    <h1>👋 Hello, I'm Wokovn!</h1>
    
    <div class="profile-section">
        <h2>🌟 About Me</h2>
        <p>I'm a passionate <span class="highlight">C++</span> developer and student at <span class="highlight">HCMUS</span> in Vietnam, pursuing my dreams in <span class="highlight">Information Technology</span>. I thrive on challenges and love creating efficient and elegant code.</p>
    </div>

    <div class="profile-section">
        <h2>💻 Technologies & Tools</h2>
        <div class="tech-stack">
            <div class="tech-item">C++</div>
            <div class="tech-item">Git</div>
            <div class="tech-item">Visual Studio</div>
            <div class="tech-item">Problem Solving</div>
        </div>
    </div>

    <div class="profile-section">
        <h2>🎮 Hobbies & Interests</h2>
        <p>When I'm not coding, you can find me immersed in the thrilling world of video games. My favorites include:</p>
        <ul>
            <li>FPS Games</li>
            <li>PUBG</li>
            <li>Coding Challenges</li>
        </ul>
    </div>

    <div class="social-links">
        <a href="https://www.tiktok.com/@wokovn" class="social-button">Follow me on TikTok @wokovn</a>
    </div>

    <div class="profile-section">
        <h2>💬 Fun Fact</h2>
        <p>I love experimenting with new programming challenges, and I'm always on the lookout for cool projects to collaborate on!</p>
    </div>

    <p style="text-align: center; margin-top: 30px;">✨ Let's build something amazing together! ✨</p>
</div>
</body>
</html>

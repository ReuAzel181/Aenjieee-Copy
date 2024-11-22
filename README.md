<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Angge's Portfolio</title>
  <style>
    /* Keyframes for animations */
    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }

    @keyframes slideIn {
      0% { transform: translateX(-50%); opacity: 0; }
      100% { transform: translateX(0); opacity: 1; }
    }

    /* Hover Effects */
    .hover-effect:hover {
      transform: scale(1.05);
      transition: all 0.3s ease;
    }

    /* Apply Animations */
    .fadeIn {
      animation: fadeIn 2s ease-out;
    }

    .slideIn {
      animation: slideIn 1s ease-out;
    }

    /* Layout Styling */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f0f0f0;
    }

    .container {
      max-width: 700px;
      margin: auto;
      padding: 20px;
    }

    h2, h3 {
      text-align: center;
      font-weight: bold;
    }

    p {
      font-size: 16px;
      line-height: 1.6;
      color: #555;
      text-align: center;
    }

    .tech-icons a {
      margin: 10px;
      display: inline-block;
    }

    .tech-icons img {
      width: 50px;
      height: 50px;
      transition: transform 0.3s;
    }

    .tech-icons img:hover {
      transform: scale(1.1);
    }
  </style>
</head>
<body>

  <!-- Introduction Section -->
  <div class="container fadeIn" style="background: linear-gradient(135deg, #f9f9f9, #f0f0f0); padding: 20px; border-radius: 10px; box-shadow: 0px 10px 20px rgba(0,0,0,0.1);">
    <h2 class="slideIn" style="font-size: 28px;">Hi there, I'm Angge! 👋</h2>
    <p>
      I'm a passionate <strong>Graphic Designer</strong> and a <strong>Computer Science student</strong>. I create visually stunning designs and love coding too!
    </p>
  </div>

  <!-- QA Section -->
  <div class="container fadeIn" style="background: linear-gradient(135deg, #fff, #f9f9f9); padding: 20px; border-radius: 10px; box-shadow: 0px 10px 20px rgba(0,0,0,0.1); margin-top: 20px;">
    <p>✅ <strong>Quality Assurance (QA)</strong>:<br> I have expertise in testing and quality assurance to ensure that software products meet the highest standards of quality and performance.</p>
  </div>

  <!-- What I Do Section -->
  <div class="container fadeIn" style="padding: 20px; background: linear-gradient(135deg, #ffffff, #e0e0e0); box-shadow: 0px 10px 20px rgba(0,0,0,0.3); margin-top: 20px; overflow: hidden;">
    <div class="slideIn" style="background: linear-gradient(135deg, #3498db, #2ecc71); color: #fff; padding: 15px; border-radius: 15px 15px 0 0; box-shadow: inset 0px 4px 8px rgba(0,0,0,0.2);">
      <h3>What I Do</h3>
    </div>
    <div style="padding: 20px; background: #fafafa;">
      <div class="hover-effect" style="display: flex; align-items: center; padding: 15px; border-bottom: 1px solid #e0e0e0;">
        <span style="font-size: 30px; color: #e67e22; margin-right: 15px;">🎨</span>
        <p style="font-size: 18px; font-weight: 600; color: #333; margin: 0;">Graphic Design: From logos to complete brand identities, I design visuals that communicate and inspire.</p>
      </div>
      <div class="hover-effect" style="display: flex; align-items: center; padding: 15px; border-bottom: 1px solid #e0e0e0;">
        <span style="font-size: 30px; color: #3498db; margin-right: 15px;">🖌️</span>
        <p style="font-size: 18px; font-weight: 600; color: #333; margin: 0;">UI/UX Design: I design intuitive and engaging user interfaces with a focus on user experience.</p>
      </div>
      <div class="hover-effect" style="display: flex; align-items: center; padding: 15px; border-bottom: 1px solid #e0e0e0;">
        <span style="font-size: 30px; color: #2ecc71; margin-right: 15px;">🎨</span>
        <p style="font-size: 18px; font-weight: 600; color: #333; margin: 0;">Digital Art: I love exploring different styles and techniques in digital art.</p>
      </div>
      <div class="hover-effect" style="display: flex; align-items: center; padding: 15px;">
        <span style="font-size: 30px; color: #9b59b6; margin-right: 15px;">🤝</span>
        <p style="font-size: 18px; font-weight: 600; color: #333; margin: 0;">Creative Collaboration: I enjoy working with others to turn ideas into reality.</p>
      </div>
    </div>
  </div>

  <!-- GitHub Stats Section -->
  <div class="container fadeIn" style="padding: 20px; background: #f0f0f0; border-radius: 10px; box-shadow: 0px 10px 20px rgba(0,0,0,0.1); margin-top: 20px;">
    <h3>GitHub Stats</h3>
    <p>Total Contributions: <strong>120</strong><br> Profile Views: <strong>5,200</strong></p>
  </div>

  <!-- GitHub Stats with ReadMe Cards -->
  <div class="container fadeIn" style="margin-top: 20px;">
    <div style="display: flex; justify-content: space-around; flex-wrap: wrap;">
      <!-- GitHub Stats -->
      <a href="http://www.github.com/Aenjieee">
        <img src="https://github-readme-stats.vercel.app/api?username=Aenjieee&show_icons=true&include_all_commits=true&theme=dracula&hide_border=true" alt="Aenjieee's GitHub stats" />
      </a>
      <!-- GitHub Streak -->
      <a href="http://www.github.com/Aenjieee">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=Aenjieee&theme=dracula&hide_border=true" alt="Aenjieee's GitHub streak" />
      </a>
      <!-- GitHub Languages -->
      <a href="http://www.github.com/Aenjieee">
        <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aenjieee&layout=compact&langs_count=16&theme=dracula" alt="Aenjieee's GitHub top languages" />
      </a>
    </div>
  </div>

  <!-- Tech Stack Section -->
  <div class="container fadeIn" style="margin-top: 20px;">
    <h3>🛠️ Tech Stack</h3>
    <div class="tech-icons" align="center">
      <a href="https://www.figma.com/"><img src="https://img.icons8.com/color/48/000000/figma.png" alt="Figma" /></a>
      <a href="https://reactjs.org/"><img src="https://img.icons8.com/color/48/000000/react-native.png" alt="React" /></a>
      <a href="https://nextjs.org/"><img src="https://img.icons8.com/color/48/000000/nextjs.png" alt="Next.js" /></a>
      <a href="https://wordpress.org/"><img src="https://img.icons8.com/color/48/000000/wordpress.png" alt="WordPress" /></a>
      <a href="https://developer.mozilla.org/en-US/docs

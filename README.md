<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>观鸟网 - 个人博客 - 观鸟初体验</title>
    <style>
      /* 引入字体，优化字体路径查找 */
      @font-face {
        font-family: pop;
        src: url("font/pop.ttf");
      }

      body {
        font-family: pop, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f4f4f4; /* 为页面设置一个浅灰色的背景色，使整体更柔和 */
        color: #333; /* 设置文本颜色为深灰色，提高可读性 */
        display: flex;
        flex-direction: column;
        min-height: 100vh; /* 确保页脚始终在底部 */
      }

      header {
        background-color: #fff; /* 设置白色背景，与页面背景区分开，更显层次感 */
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); /* 添加淡淡的阴影，增加立体感 */
        padding: 20px;
        text-align: center;
        position: relative;
      }

      h1 {
        font-size: 40px;
        color: #007bff; /* 设置标题颜色为蓝色，更醒目，可根据喜好调整颜色 */
        margin: 0;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1); /* 添加阴影效果，让标题更立体 */
      }

      nav {
        position: absolute;
        right: 20px; /* 将导航定位到右上角 */
        top: 20px;
      }

      nav a {
        color: #666; /* 导航链接颜色设为灰色 */
        text-decoration: none;
        padding: 5px 10px;
        border-radius: 5px;
        transition: background-color 0.3s ease, color 0.3s ease; /* 添加过渡效果 */
      }

      nav a:hover {
        background-color: #f0f0f0; /* 鼠标悬停时的背景色变化 */
        color: #333;
      }

      article {
        flex: 1;
        padding: 20px;
        line-height: 1.6;
      }

      h2 {
        font-size: 30px;
        color: #007bff; /* 小标题颜色与标题统一，保持风格一致 */
        margin-bottom: 15px;
        text-decoration: underline; /* 添加下划线，突出小标题 */
      }

      p {
        font-size: 18px;
        margin-bottom: 15px;
        text-align: justify; /* 两端对齐，更美观 */
      }

      a {
        color: #007bff; /* 链接颜色与标题统一 */
        text-decoration: none;
        transition: color 0.3s ease; /* 链接添加过渡效果 */
      }

      a:hover {
        color: #0056b3; /* 鼠标悬停时链接颜色变化，加深颜色 */
        text-decoration: underline; /* 显示下划线，提示可点击 */
      }

      footer {
        background-color: #fff; /* 页脚设置白色背景，与头部呼应 */
        box-shadow: 0 -2px 5px rgba(0, 0, 0, 0.1); /* 添加阴影，与头部阴影区分开方向 */
        text-align: center;
        padding: 15px 0;
        margin-top: auto;
      }

      footer p {
        margin: 0;
        font-size: 14px;
        color: #666; /* 页脚文本颜色设为灰色，弱化显示 */
      }
    </style>
  </head>

  <body>
    <header>
      <h1>观鸟初体验</h1>
      <nav>
        <a href="index.html">返回首页</a>
      </nav>
    </header>
    <article>
      <h2>引言</h2>
      <p>
        作为一个热爱自然的人，我一直对鸟类充满了浓厚的兴趣。最近，我终于鼓起勇气，开始了我的观鸟之旅。以下是我第一次观鸟的经历和感受。
      </p>
      <h2>准备工作</h2>
      <p>
        在出发前，我做了大量的准备工作。我查阅了许多关于观鸟的书籍和资料，学习了如何识别不同的鸟类，以及如何选择和使用观鸟工具。我还特意购买了一副高质量的望远镜，希望能够更好地观察鸟类。
      </p>
      <h2>第一次观鸟</h2>
      <p>
        终于，在一个阳光明媚的早晨，我来到了附近的一个自然保护区。一开始，我有些紧张，生怕错过任何一只鸟类。但是，当我看到第一只小鸟时，所有的紧张都烟消云散了。那是一只可爱的小鸟，它正在树枝上欢快地跳跃着，仿佛在欢迎我的到来。
      </p>
      <p>
        随着时间的推移，我逐渐适应了观鸟的节奏。我开始能够更准确地识别不同的鸟类，甚至能够分辨出它们的叫声。我还发现，观鸟不仅仅是一种娱乐活动，更是一种与自然亲密接触的方式。
      </p>

      <h2>收获与感悟</h2>
      <p>
        这次观鸟之旅让我收获颇丰。我不仅学到了许多关于鸟类的知识，还感受到了大自然的神奇和美丽。
      </p>
      <p>
        此外，我还发现了
        <a href="https://www.huaniao8.com/global">"全球鸟类大全"</a>
        网站让我学习到了更多的鸟类知识
      </p>
    </article>
    <footer>
      <p>&copy; 2023 观鸟网个人博客. 版权所有.</p>
    </footer>
  </body>
</html>

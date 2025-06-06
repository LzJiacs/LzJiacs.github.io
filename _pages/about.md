---
permalink: /
title: "Welcome to Linzhao's Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## 👋 Hello! I'm Linzhao Jia

I'm a Ph.D. student at East China Normal University, researching intelligent education and natural language processing.

📚 My interests include:
- AI for Education
- Dialogue Systems
- ASR Post-processing

💡 Outside of academia:
- I enjoy long-distance running 🏃‍♂️
- Coffee ☕ + Photography 📸

---

### 📎 Explore more:

- [About Me](/about/)
- [Curriculum Vitae](/cv/)
- [My life](/portfolio/)
- [Contact](/contact/)


## 🌍 访客信息
<p id="welcome-msg">正在获取您的位置...</p>

## 📊 网站访问统计
<p>
  当前访问本站的总人次为：
  <span id="busuanzi_value_site_uv"></span>，
  总浏览量为：
  <span id="busuanzi_value_site_pv"></span>
</p>

<!-- ## 👍 点个赞支持一下
<button id="like-btn">👍 点赞 (<span id="like-count">0</span>)</button> -->

<!-- JS 脚本区域 -->
<script src="https://cdn.jsdelivr.net/npm/busuanzi@2.3.0"></script>
<script>
  fetch('https://api.ipify.org?format=json')
    .then(res => res.json())
    .then(data => {
      const ip = data.ip;
      fetch(`https://ip-api.com/json/${ip}?lang=zh-CN`)
        .then(res => res.json())
        .then(loc => {
          const location = `${loc.country} · ${loc.regionName} · ${loc.city}`;
          document.getElementById('welcome-msg').innerText =
            `👋 欢迎来自 ${location} 的朋友！您的 IP 是 ${ip}`;
        });
    });

  <!-- let count = localStorage.getItem('like-count') || 0;
  document.getElementById('like-count').innerText = count;
  document.getElementById('like-btn').onclick = function () {
    count++;
    localStorage.setItem('like-count', count);
    document.getElementById('like-count').innerText = count;
  }; -->
</script>
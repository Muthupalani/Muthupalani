# 👋 Hi, I'm Muthupalani R! - AI & Data Science Enthusiast

Welcome to my GitHub! 🚀 I'm passionate about **Artificial Intelligence**, **Data Science**, and building amazing projects. Feel free to explore my repositories and learn more about my work. 💻✨

---

## 💻 Technical Skills

### **Programming Languages:**

![Python](https://img.shields.io/badge/Python-%233776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-%2300599C?style=flat-square&logo=c&logoColor=white)
![R](https://img.shields.io/badge/R-%23276DC3?style=flat-square&logo=r&logoColor=white)
![Java](https://img.shields.io/badge/Java-%2300736B?style=flat-square&logo=java&logoColor=white)

### **Frontend Technologies:**

![HTML5](https://img.shields.io/badge/HTML5-%23E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6?style=flat-square&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-%2361DAFB?style=flat-square&logo=react&logoColor=white)

---

## 📊 GitHub Stats

### 🔥 Contributions & Streak

![My GitHub Stats](https://github-readme-stats.vercel.app/api?username=Muthupalani&show_icons=true&theme=radical&hide_border=true)  
![Streak Stats](https://github-readme-streak-stats.herokuapp.com/?user=Muthupalani&theme=radical&hide_border=true)

---

## 🛠️ My Expertise
<p align="center">
  <img src="https://img.shields.io/badge/AI%20%26%20Machine%20Learning-%23FFB6C1?style=flat-square" alt="AI & ML Badge">
  <img src="https://img.shields.io/badge/Data%20Science-%23FFD700?style=flat-square" alt="Data Science Badge">
  <img src="https://img.shields.io/badge/Deep%20Learning-%23FF4500?style=flat-square" alt="Deep Learning Badge">
</p>

---


## 🖥️ Most Used Languages 

<div align="center" style="display: flex; justify-content: center; align-items: center; gap: 30px;">

  <!-- Python Box with Hover Animation -->
  <div class="language-box" style="background-color: #3776AB;">
    <div class="percentage" style="color: white; font-size: 20px; font-weight: bold;"></div>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python Logo">
    <p>Python</p>
  </div>

  <!-- Java Box with Hover Animation -->
  <div class="language-box" style="background-color: #007396;">
    <div class="percentage" style="color: white; font-size: 20px; font-weight: bold;"></div>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java Logo">
    <p>Java</p>
  </div>

  <!-- HTML Box with Hover Animation -->
  <div class="language-box" style="background-color: #E34F26;">
    <div class="percentage" style="color: white; font-size: 20px; font-weight: bold;"></div>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML Logo">
    <p>HTML</p>
  </div>
</div>

<!-- Add this CSS to your page -->
<style>
  .language-box {
    width: 150px;
    height: 150px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    border-radius: 15px;
    transition: transform 0.3s ease, background-color 0.3s ease;
    position: relative;
    cursor: pointer;
  }

  .language-box img {
    width: 60px;
    height: 60px;
    transition: transform 0.3s ease;
  }

  .language-box p {
    color: white;
    margin-top: 10px;
    font-weight: bold;
    text-align: center;
  }

  .language-box:hover {
    transform: scale(1.1);
  }

  .language-box:hover img {
    transform: rotate(10deg);
  }

  .language-box:hover .percentage {
    content: attr(data-percentage);
    visibility: visible;
    position: absolute;
    top: -20px;
    font-size: 18px;
    animation: fadeIn 0.5s ease;
  }

  .percentage {
    visibility: hidden;
  }

  @keyframes fadeIn {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }
</style>

<!-- Add this JavaScript for random percentage -->
<script>
  document.querySelectorAll('.language-box').forEach(box => {
    box.addEventListener('mouseover', () => {
      const percentage = Math.floor(Math.random() * 50) + 50; // Random percentage above 50%
      const percentageElement = box.querySelector('.percentage');
      percentageElement.textContent = `${percentage}%`;
      percentageElement.style.visibility = 'visible';
    });

    box.addEventListener('mouseout', () => {
      const percentageElement = box.querySelector('.percentage');
      percentageElement.style.visibility = 'hidden';
    });
  });
</script>



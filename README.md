<p align="center">
  <img width="450" height="280" src="https://media.tenor.com/X3jJ_r78JlcAAAAM/bobs-burger-tina-belcher.gif">
</p>

# Hi there, I'm Kimaya Raut! 👋

Welcome to my GitHub profile! I'm a passionate backend developer with a solid foundation in computer engineering and a year of practical experience in building scalable and efficient applications. I enjoy working in dynamic environments where creativity and technical expertise intersect to solve complex problems.

## 💻 What I Do
I specialize in backend development, utilizing technologies like Python, Flask, FastAPI, and MongoDB to craft robust and high-performance solutions. Here’s a glimpse of what I’ve worked on:
- **AI-Powered Applications**: Contributed to RDX at Ease My AI Pvt Ltd, an advanced application leveraging AI for real-time detections using user-owned cameras. 
- **Web Applications**: Developed several tools, including mental health and personality prediction systems, crop forecasting applications, and paraphrasing tools, focusing on integrating machine learning models and enhancing user experience.

## 🛠 Skills

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 🚀 Current Projects
- **[Mental Health and Personality Prediction](https://github.com/KimayaRaut/Mental-Health-and-Personality-Determination-using-Machine-Learning-)**: A web app using Flask and machine learning to predict mental health status and personality traits based on user input.
- **[Crop Forecasting Tool](https://github.com/KimayaRaut/Crop-Forecasting-Using-Machine-Learning-Random-Forest-Classifier)**: An application utilizing a RandomForestClassifier to recommend optimal crops based on soil and environmental data.
- **[Paraphrasing Tool](https://github.com/KimayaRaut/Paraphrasing-Tool)**: A tool designed to refine text by correcting spelling and grammar errors for improved readability.
- **[Online Lecture Scheduling](https://github.com/KimayaRaut/Online-Lecture-Scheduling-Module)**: A system developed with FastAPI and MongoDB for managing course schedules and instructor assignments, ensuring no scheduling conflicts.

## 🌱 What I’m Learning
I am continuously exploring new technologies and best practices to stay at the forefront of backend development and machine learning. Currently, I'm diving into Node.js.

## 🌟 Let’s Connect
Feel free to explore my repositories and projects. If you have any questions, collaboration ideas, or just want to connect, don’t hesitate to reach out!

<a href="https://www.linkedin.com/in/kimaya-raut-6b64281b9/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>

Thank you for visiting my GitHub profile! 🎉

## 🕹️ Fun Game: Rock, Paper, Scissors

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rock, Paper, Scissors</title>
<style>
  body { font-family: Arial, sans-serif; text-align: center; }
  .button { margin: 5px; padding: 10px 20px; font-size: 16px; }
</style>
</head>
<body>
<h2>Rock, Paper, Scissors</h2>
<p>Choose your move:</p>
<button class="button" onclick="playGame('rock')">Rock</button>
<button class="button" onclick="playGame('paper')">Paper</button>
<button class="button" onclick="playGame('scissors')">Scissors</button>
<p id="result"></p>
<script>
  function playGame(playerChoice) {
    const choices = ['rock', 'paper', 'scissors'];
    const computerChoice = choices[Math.floor(Math.random() * choices.length)];
    let result = '';

    if (playerChoice === computerChoice) {
      result = 'It\'s a tie!';
    } else if (
      (playerChoice === 'rock' && computerChoice === 'scissors') ||
      (playerChoice === 'paper' && computerChoice === 'rock') ||
      (playerChoice === 'scissors' && computerChoice === 'paper')
    ) {
      result = 'You win! ' + playerChoice + ' beats ' + computerChoice + '.';
    } else {
      result = 'You lose! ' + computerChoice + ' beats ' + playerChoice + '.';
    }

    document.getElementById('result').innerText = result;
  }
</script>
</body>
</html>
```

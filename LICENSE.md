<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> My Quiz Website</title>
        <link rel="stylesheet" href="style.css">
     </head>
     <body>
        <main class="main">
            <header class="header">
                <a href="#" class="logo">Quiz</a>
                <nav class="navbar">
                    <a href="#" class="active">home</a>
                    <a href="#">about</a>
                    <a href="#">services</a>
                    <a href="#">contact</a>

                </nav>

            </header>
            <div class="container">
                <section class="quiz-section">
                    <div class="quiz-box">
                        <h1>codehal Quiz</h1>
                        <div class="quiz-header">
                            <span>Quiz Website Tutorials</span>
                            <span class="header-score">score: 0 / 6</span>
                        </div>
                        <h2 class="question-text">Quel est le paradigme de programmation principalement utilisé dans le langage Python ?</h2>
                        <div class="option-list">
                           <!--<div class="option">
                                <span>A. programmation Orienté Objet</span>
                            </div>
                            <div class="option">
                                <span>B. Programmation fonctionnelle+</span>
                            </div>
                            <div class="option">
                                <span>C. Programmation impérative</span>
                            </div>-->
                        </div> 
                        <div class="quiz-footer">
                            <span class="question-total">1 of 5 Questions</span>
                            <button class="next-btn">Next</button>
                        </div>
                    </div> 
                    <div class="result-box">
                        <h2>Quiz Result!</h2>
                        <div class="percentage-container">
                            <div class="circular-progress">
                                <span class="progress-value">0%</span>
                            </div>
                            <span class="score-text">Your Score 0 out of 6</span>
                        </div>
                        <div class="buttons">
                            <button class="tryAgain-btn">Try Again</button>
                            <button class="goHome-btn">Go To Home</button>
                        </div>
                    </div>
                </section>

                <section class="home">
                    <div class="home-content">
                        <h1>Quiz Website</h1>
                        <p>Bienvenue sur notre Quiz d'informatique .Testez vos connaissances sur les sujets variés de l'informatique, des langages de programmation aux concepts de développement web</p>
                        <p>Cliquer sur le bouton ci-dessous pour commencer à jouer.</p>
                        <button class="start-btn">Start Quiz</button>
                    </div>
                </section>
            </div>
        </main>
        <div class="popup-info">
            <h2>Quiz Guide</h2>
            <span class="info">1.Lisez bien les questions</span>
            <span class="info">2.Vous passerez en revue trois types de questions.</span>
            <span class="info">3.Lorsque vous répondrez, il y aura un chronomètre</span>
            <span class="info">4.Enfin, votre score sera compté</span>
            <div class="btn-group">
                <button class="info-btn exit-btn">Exit Quiz</button>
                <a href="#" class="info-btn continue-btn">Continue</a>

            </div>
            
            
        </div>
        <script src="questions.js"></script>
        <script src="script.js"></Script>

     </body>
</html>

General Introduction
====================


.. raw:: html

    <p style="text-align: justify;"><span style="color:#000080;"><i>    
   

    Our initial project focused on developing an artificial intelligence system <span style="color:red;">for the game of chess</span>, a highly complex strategy game requiring deep decision-making at multiple levels. However, we faced significant challenges due to the complexity of the game, as well as the computational resources required for training and learning processes. Chess, with its vast array of possible moves and the high computational demand to train a competitive AI, required a processing capacity that exceeded our available resources.
   </i></span></p>
    <p style="text-align: justify;"><span style="color:#000080;"><i> 

    Given these constraints, we decided to shift our focus to the game of checkers, which offers a more accessible environment while still providing rich strategic complexity for reinforcement learning. Checkers, though simpler in terms of rules, still presents sufficient opportunities to test and evaluate AI methods, while being less demanding in terms of computation and training time.
    </i></span></p>
    <p style="text-align: justify;"><span style="color:#000080;"><i> 
    In this project, we combine the capabilities of large language models (LLMs) with the Q-learning algorithm, a reinforcement learning method, to develop a competent AI for the game of checkers. The LLM will be used to generate multiple move options during each turn, while Q-learning will allow the AI to optimize its choices and learn from its experiences by refining its strategy through gameplay.
    </i></span></p>
  



Project Objectives
===================

.. raw:: html


    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style>
            body {
                font-family: Arial, sans-serif;
                background-color:rgb(186, 244, 242);
                margin: 20px;
            }
            h2 {
                color: #333;
            }
            .objectives {
                background-color: #fff;
                border-radius: 8px;
                padding: 20px;
                box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            }
            .objective {
                margin-bottom: 20px;
                display: flex;
                align-items: center;
            }
            .objective img {
                width: 40px;
                margin-right: 15px;
            }
            .objective span {
                font-size: 1.1em;
            }
            .emoji {
                margin-left: 10px;
            }
        </style>
    </head>
    <body>

        <h2>🎯</h2>
        <div class="objectives">
            <!-- Objective 1 -->
            <div class="objective">
                <img src="Documentation/Images/Checkers.png" alt="Checkers Icon">
                <span>Create a checkers game environment that simulates the rules and dynamics of the game, allowing the AI to train and be tested. <span class="emoji">🧩</span></span>
            </div>
            <!-- Objective 2 -->
            <div class="objective">
                <img src="Documentation/Images/LLM.png" alt="LLM Icon">
                <span>Use a large language model (LLM) to generate the 7 best possible moves at each game state, based on the analysis of board positions and potential strategies. <span class="emoji">🤖</span></span>
            </div>
            <!-- Objective 3 -->
            <div class="objective">
                <img src="Documentation/Images/Q-learning.png" alt="Q-learning Icon">
                <span>Implement Q-learning to enable the AI to improve over time, learning to select optimal moves based on rewards received through trial and error. <span class="emoji">🔁</span></span>
            </div>
            <!-- Objective 4 -->
            <div class="objective">
                <img src="Documentation/Images/Evaluation.png" alt="Evaluation Icon">
                <span>Evaluate the system’s performance by comparing the AI's results against other AI systems and human players, adjusting the learning algorithm as necessary. <span class="emoji">🏆</span></span>
            </div>
        </div>

    </body>
    </html>












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
  



Project Objectives🎯
=====================

.. raw:: html

    <p style="text-align: justify;"><span style="color:#000080;"><i> 
                Create a checkers game environment that simulates the rules and dynamics of the game, allowing the AI to train and be tested. <span class="emoji">🧩</span>
            
     </i></span></p>
     <p style="text-align: justify;"><span style="color:#000080;"><i>            
                Use a large language model (LLM) to generate the 7 best possible moves at each game state, based on the analysis of board positions and potential strategies. <span class="emoji">🤖</span>
            
      </i></span></p>
      <p style="text-align: justify;"><span style="color:#000080;"><i>           
                Implement Q-learning to enable the AI to improve over time, learning to select optimal moves based on rewards received through trial and error. <span class="emoji">🔁</span>
      </i></span></p>    
       <p style="text-align: justify;"><span style="color:#000080;"><i>  
               Evaluate the system’s performance by comparing the AI's results against other AI systems and human players, adjusting the learning algorithm as necessary. <span class="emoji">🏆</span>
        </i></span></p> 

Why Checkers (Dame) is a Viable Alternative to Chess
======================================================

.. raw:: html

  <p style="text-align: justify;">
    <span style="color:#000080;">
      <i>In the context of training machine learning models, the choice of game is crucial. The game of <strong>checkers</strong> (dame) presents itself as an interesting alternative to <strong>chess</strong>, due to several advantages in terms of complexity and resources. Here are some key points to consider:</i>
    </span>
  </p>

  <ul>
    <li><span style="color:#ff0000;"><strong>Lower complexity:</strong></span> Unlike chess, which has an astronomical number of possible combinations (around 10<sup>120</sup> positions), checkers offers significantly lower complexity, making it easier to train models. 🤖</li>
    <li><span style="color:#ff0000;"><strong>Fewer probabilities to handle:</strong></span> The probabilities in chess are extremely high and require significant resources to analyze and model. In the case of checkers, these probabilities are more manageable, allowing for a greater focus on strategy. 📉</li>
    <li><span style="color:#ff0000;"><strong>Resource optimization:</strong></span> Training models for chess requires significant hardware and time resources, often beyond the reach of research teams with limited means. On the other hand, checkers allows for faster and less resource-intensive training. 💡</li>
    <li><span style="color:#ff0000;"><strong>Past experiences with chess:</strong></span> Numerous attempts have been made to train effective models for chess, but the results have often been disappointing due to resource limitations and the inherent complexity of the game. 😓</li>
  </ul>

  <p style="text-align: justify;">
    <span style="color:#000080;">
      <i>In summary, while chess is a highly regarded game for AI, checkers offers a more accessible compromise for developing effective and realistic machine learning models. 🌍</i>
    </span>
  </p>










# Competitive Game: The influence of obvious advertisements and the posting order on the competitiveness of Social media influencers
## Project information
- **Author**: Rong Cong, 2024,Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set No. or Final Project for [COMPSCI/ECON 206 Computational Microeconomics, 2023 Spring (Seven Week - Second)](https://ce.pubpub.org/) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**:  I would like to thank Prof. Luyao Zhang for her profound knowledge and enthusiasm inspire my love of learning, and her patience for answering countless questions for me. Thank you for yiyuan, haowen and wanlin's cooperating with me in learning and sharing insights. Their open mind and in-depth discussion helped me to have a deeper understanding of the course content. Finally, I would like to thank the whole class. I am extremely lucky and humbled by your encouragement and help in this class. Your solidarity and support make us a better learning team. I sincerely thank you for your friendship and support.
- **Project Summary**: 
  - [Summarize the Background/Motivation]In today's era of boundless social media development, a new trend is continuously emerging, quietly reshaping our shopping habits and consuming perspectives. With the convenience of e-commerce and innovative business models, an increasing number of people are shifting their shopping activities from offline to online. The craze of social media influencers recommending products has led to a constant temptation of various desirable items in our daily lives.
In the process of online consumption, there are risks involved in the exchange between consumers and brands, making trust play a crucial role. Social Media Influencers (SMIs) serve as a bridge connecting brands and consumers. When consumers establish a strong level of trust with SMIs, their awareness and favorability towards brands recommended by SMIs gradually increase.In recent years, SMIs have gained significant influence on social media platforms and play an intermediary role between brands and consumers. By 2022, the estimated value of influencer marketing is expected to reach $15 billion, compared to $8 billion in 2019. From these statistics, it can be seen that becoming a high-quality SMIs who can consistently attract followers can bring substantial economic benefits. Behind these significant economic benefits, there are collaborations with brands and advertising placements. Additionally, there is intense competition among SMIs in the same field. 

  - [Research Questions]Major research question: Competitive Game: The influence of obvious advertisements and the posting order on the competitiveness of social media influencers.
In order to better investigate this research question, this main problem has been divided into two small problems, corresponding to two different situations and models. How does Posting with obvious advertisements affect a SMI’s competitiveness without an obvious posting order? How does Posting with obvious advertisements affect a SMI’s competitiveness with an obvious posting order? Here is the link of answer of chatgpt: https://github.com/Rising-Stars-by-Sunshine/csecon206-rongcong-FinalProject/blob/main/WechatIMG133.jpeg
  - [Application Scenario]This game environment simulates real-life social networking platforms. In this virtual world, we have two players—Player A and Player B, representing two social media influencers (SMIs) with similar fan bases and content types. There is a clear competition between these two players as they strive to gain the favor of the audience and stand out on this virtual social media platform.
Player A and Player B are aware that in this highly competitive environment, they need to employ a series of strategies to attract the attention and support of the audience.
In this virtual social media platform, Player A and Player B engage in intense competition, vying for the audience's favor. They know that the support and positive feedback from the audience will directly manifest in the form of likes and views data. Those players who can win more favor from the audience will attract more fans and collaboration opportunities. Therefore, Player A and Player B spare no effort in their endeavors to stand out on this virtual social media platform, aiming to achieve success in this fiercely competitive environment.
  - [Methodology]
Two models have been made to illustrate the impact of releasing explicit advertisements without any apparent order on the payoffs of SMIs. The numbers in the model represent the players' final payoff, with higher numbers indicating that they have gained more favorability from the audience and therefore have a greater competitive edge.Given the complexity of real social media environments, the game models makes several assumptions.1. The content of both SMI accounts is highly similar, with an equal number of followers and exposure to the same level of traffic.2. Specific audience preferences (such as preferences for certain details) are not taken into consideration.3. SMIA and SMIB have a direct and evident competitive relationship, excluding competition with anyone else.4. All viewers simultaneously browse and compare the content of both influencers. This means that the audience has a clear understanding of the order in which the two bloggers post and whether or not they publish advertisements.5. Long-term financial gains are more important than short-term financial gains. The favorability and trust of followers contribute to the long-term development of influencers and enable them to obtain sustained earnings. Therefore, while advertising may bring short-term financial gains to influencers, it can to some extent lower the favorability of the audience towards them, thereby hindering their long-term earnings.
  - [Results]
  Result for Model 1:
  The Nash Equilibrium in this competitive game is (no obvious ad, no obvious ad). In this equilibrium, both players choose not to release post with obvious advertisements which leads to a payoff 5 for each other. A strategy is a Nash Equilibrium strategy if it is the best strategy for an agent, given the strategies the other players are actually using. In this competitive game, neither player can unilaterally change their strategy to improve their own payoff, given the strategy of the other player. As a result, no matter what the other side chooses, not releasing posts with obvious advertisements is always the best choice under the circumstances. Therefore, in this case, the NE strategy is (no obvious ad, no obvious ad), and both players end up with a suboptimal outcome.
Result for Model 2:
In Model 2, there is an extreme Nash equilibrium, which occurs when A and B both choose not to release post with obvious advertisement. In this case, A's payoff is 7 and B's payoff is 5，neither player has a better strategy to win.Thus, in this case, both players are more likely to choose not to release post with obvious advertisement.
  - [Intellectual Merits and Practical impacts of your project.] Possible future extensions: This study can be further expanded in the following directions. Firstly, expanding the scope of the research to consider the competitiveness of SMIs on different social media platforms. Secondly, exploring the impact of content types and formats on competitiveness. Thirdly, analyzing target audiences. Consider further researching the impact of obvious advertisements and the posting order on the competitiveness of different target audiences. How your research could inspire further research and how your research could be applied to solve real-world issues: Firstly, this study can fill the research gap in the understanding of SMIs’ competitiveness. Secondly, this study can help people understand the role of obvious advertisements and the posting order in competitiveness. Thirdly, this study can contribute to improving the competitiveness of SMIs. Fourthly, this study can optimize advertising and social media marketing strategies. Fifthly, this study can drive the research and development of social media. 



## Table of Contents

- model
- code
- spotlight
- more about the author
- references

### Model
- Game Environment

This game environment simulates real-life social networking platforms. In this virtual world, we have two players—Player A and Player B, representing two social media influencers (SMIs) with similar fan bases and content types. There is a clear competition between these two players as they strive to gain the favor of the audience and stand out on this virtual social media platform.
Player A and Player B are aware that in this highly competitive environment, they need to employ a series of strategies to attract the attention and support of the audience.
In this virtual social media platform, Player A and Player B engage in intense competition, vying for the audience's favor. They know that the support and positive feedback from the audience will directly manifest in the form of likes and views data. Those players who can win more favor from the audience will attract more fans and collaboration opportunities. Therefore, Player A and Player B spare no effort in their endeavors to stand out on this virtual social media platform, aiming to achieve success in this fiercely competitive environment.

- Solution Concept

Here is Model 1, which simulates the case with no obvious posting order.

 ![image](2.png)
 
 If both SMIA and SMIB choose not to release explicit advertisements, their payoff will be 5 each.
If both SMIA and SMIB choose to release explicit advertisements, their payoff will be 3 each.
If SMIA chooses to release explicit advertisements but SMIB chooses not to, SMIA's payoff will be 0, while SMIB's payoff will be 10.
If SMIB chooses to release explicit advertisements but SMIA chooses not to, SMIB's payoff will be 0, while SMIA's payoff will be 10.


Here is Model 2, which simulates the case with obvious  posting order.

 ![image](1.png)

 If both SMIA and SMIB choose not to release explicit advertisements, their respective earnings will be 7 and 5.
If both SMIA and SMIB choose to release explicit advertisements, their respective earnings will be 5 and 3.
If SMIA chooses to release explicit advertisements, but SMIB chooses not to, SMIA's earnings will be 2, and SMIB's earnings will be 10.
If SMIB chooses to release explicit advertisements, but SMIA chooses not to, SMIB's earnings will be 0, and SMIA's earnings will be 12.



- Evaluations: 

Definition of Efficiency: In the context of this competitive game, efficiency is defined as the level of audience affection towards social media influencers. It measures the effectiveness of influencers in engaging and appealing to their audience through their content and promotional activities.

By comparing the earnings in the matrix, it is evident that in the absence of a clear publishing order, not publishing content with obvious advertisements yields higher profits, regardless of whether competitors publish content with obvious advertisements or not. At the same time, when competitors release content with obvious advertisements, the decision not to publish such content significantly increases earnings. On the other hand, long-term advertising campaigns and delayed publication of already trending content are the least advantageous for influencers to achieve long-term profits. While there may be some short-term advertising revenue, it is not conducive to cultivating and expanding the fan base.

This game is fair for several reasons. Firstly, both players operate within an open and transparent social media environment. This means they can observe, evaluate, and compare each other's actions and strategies without any hidden information or inequality. This transparent environment ensures information symmetry, providing both players with equal opportunities and resources in the competition.
Secondly, both players have the autonomy to decide whether to post obvious advertisements and determine the posting order. They have the right to choose when, where, and how to publish advertising content on social media platforms. This power of autonomous choice allows both players to make decisions that are most suitable for their own circumstances and strategic goals.
Thirdly, both players understand the potential payoffs of their choices. They have a comprehension and expectation of the consequences, allowing them to weigh the advantages and disadvantages of different options.
Finally, any choices and actions made by the opponent will be fully revealed at the moment of posting. This means that both players can instantly understand the opponent's decisions and make corresponding reactions and adjustments based on that information. This real-time openness ensures fairness and transparency in the game, preventing fraudulent or unfair competitive behaviors and enabling both players to compete in a just environment.




### Code
- Game Environment

The Competitive game environment simulates real-life social networking platforms. In this virtual world, there are have players—Player A and Player B, representing two social media influencers (SMIs) with similar fan bases and content types. There is a clear competition between these two players as they strive to gain the favor of the audience and stand out on this virtual social media platform.

- Here is the link for Strategic plays and Equilibruim Evaluations: https://github.com/Rising-Stars-by-Sunshine/csecon206-rongcong-FinalProject/blob/main/code/final_project_models.ipynb




### Spotlight
- Posters
![image](poster.png)

This poster gives an overview of causal research ouline. It contains five sections: Background and Motivation, Research Questions, Literature inspiration, Models, Referenes.
This poster is created by Canva.
- Figures

Here is the link for overleaf pdf:https://github.com/Rising-Stars-by-Sunshine/csecon206-rongcong-FinalProject/blob/main/spotlight/final_project.pdf

Here is the link for overleaf zip:https://github.com/Rising-Stars-by-Sunshine/csecon206-rongcong-FinalProject/blob/main/spotlight/final%20project.zip

- Slides

Here is the link for slides:https://github.com/Rising-Stars-by-Sunshine/csecon206-rongcong-FinalProject/blob/main/final%20presentation.pptx

- Review articles

Here is the link for all the review articles:https://github.com/Rising-Stars-by-Sunshine/csecon206-rongcong-FinalProject/blob/main/spotlight/ref.bib


- Media appearance

Media appearance Using Colab and Canvas to help the project.

### More about the Author
 ![image](WechatIMG68.png)
 
-  As a junior majoring in political economy, Rong Cong is very interested in economics, anthropology and psychology. She hopes to do enough cross-disciplinary research and study in the future. At the same time, Rong Cong is also a music lover. This is a cover of her song 👉🏻https://y.music.163.com/m/artist?app_version=8.9.61&id=46956986&userid=1572161264&dlt=0846.
-  Final reflection：
     - [Intellectual growth]: I have delved into the practical application cases and relevant research literature on machine learning in the social and economic domains. This has allowed me to understand the advantages and limitations of machine learning in addressing real-world problems, as well as how to tackle challenges in the social and economic context. I believe the magic of interdisciplinary research lies in its ability to integrate knowledge and methods from different disciplines, thereby providing more comprehensive and profound solutions. Interdisciplinary learning has provided me with diverse perspectives, enabling me to understand and solve problems from various disciplinary angles. Moreover, it has fostered innovative thinking and encouraged me to think beyond the confines of traditional disciplinary boundaries.
     - [Professional growth]: The majority of the programs and software used in this course were my first-time encounters, such as GTE. Although I faced many difficulties and challenges initially, I eventually managed to learn how to use them almost entirely. This has been a significant achievement for me. These programs and software can assist me in conducting research and learning more effectively.
     - [Living a purposeful life]: Living a purposeful life: If one day I were to receive the Nobel Prize or Turing Award and be characterized as a "scientist with a strong humanistic approach," I would hope to make significant contributions to advancing human society and progress.I would like to focus on creating a more transparent and open social platform. I believe that social media has tremendous potential in connecting people, facilitating information exchange, and fostering social interaction. However, current social platforms face challenges related to privacy issues, data breaches, and algorithmic biases.I would dedicate myself to developing a social platform that places user privacy and data protection at its core, ensuring that users' personal information is properly managed and safeguarded. I would strive to increase transparency and user control, enabling users to better understand how their data is being used and shared.Furthermore, I would work towards breaking down information filtering and algorithmic biases. By adopting fair, open, and diverse algorithms, I hope to reduce the impact of information filtering and ensure that users are exposed to a broader range of perspectives and opinions, thereby promoting open dialogue and understanding.Beyond the technical aspects, I would also focus on the societal impact of social platforms. I would strive to create a positive, inclusive, and friendly online community, encouraging mutual respect, understanding, and collaboration. I would advocate for the elimination of cyberbullying, hate speech, and inappropriate behavior, providing users with a safe and beneficial social environment.Ultimately, my goal would be to establish a people-centric and socially responsible social platform, offering users a more transparent, secure, and enriching online space for communication. Through these efforts, I hope to make substantial contributions to the advancement of human civilization, promoting societal progress and harmonious development.

### References

- Literature References in [Chicago Author-Date](https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-2.html) Style and [BibTex](https://scholar.google.com/) 

Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.

```
@article{levin2022bridging,
  title={Bridging level-k to nash equilibrium},
  author={Levin, Dan and Zhang, Luyao},
  journal={Review of Economics and Statistics},
  volume={104},
  number={6},
  pages={1329--1340},
  year={2022},
  publisher={MIT Press One Rogers Street, Cambridge, MA 02142-1209, USA journals-info~…}
}
```


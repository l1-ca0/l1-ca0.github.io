---
title: "CMU Course Reviews - 1st Semester"
date: 2025-07-18T18:31:06Z
draft: false
tags: ["cmu", "courses", "education"]
---


Looking back on my first semester at CMU, I wanted to share my thoughts and experiences with the courses I took. This might be helpful for future students planning their schedules. This semester I took 4 courses. The workload was intense but manageable with good time management. Here's my breakdown:

## 18-613: Introduction to Computer Systems

While the famous CSAPP course has been extensively reviewed and is taught at many universities, here's my personal perspective on the CMU experience.

### My experience:
This course teaches from a programmer's perspective on how computer systems actually execute programs and manage resources. The labs were particularly valuable - we built everything from memory allocator to terminal shell. The textbook "Computer Systems: A Programmer's Perspective" by Bryant and O'Hallaron is an absolute gem for learning low-level systems concepts.

**Highlights:**
- Hands-on labs that build real systems understanding
- Clear connection between high-level programming and machine execution
- Excellent preparation for other more advanced systems programming courses
- There is also a public scoreboard (with anonymous names) on Autolab. Most students probably do not pay attention to the specific numbers as long as they get the points. I was quite surprised and happy though that I obtained highest throughput on malloc checkpoint and second highest utilization % for malloc final submission.

**Challenges:**
- A few labs (Proxy, Malloc) require significant time investment
- Debugging low-level code and performance issues can be frustrating

**Would I recommend?** 

Essential for anyone interested to learn about systems programming. The labs can be challenging at times but incredibly rewarding. 

## 18-789: Deep Generative Models

This class was offered only the second time and I couldn't find reviews anywhere else online. But here is my take:

### What it covers:
It starts by covering various Deep Generative Models such as AR, VAE, GAN, Normalizing Flows, and Diffusion Models. Then it discusses applications of these models in domains like image generation and LLMs.

### My experience:
I found this class to be on the easier side, with the lightest workload among the 4 courses I took. While the class does involve some mathematics, it's not at the most rigorous level. The coding assignments involve implementations of deep generative models like Transformers, GANs, and diffusion models in PyTorch. Some models required manual architecture tweaking since the default configurations in the starter code didn't always work out of the box. The written assignments consist mainly of mathematical derivations and proofs.

There's only one midterm that covers roughly the first 65% of the lecture materials. I found it relatively easy with sufficient preparation, though the class average was surprisingly low. This was likely due to the multiple-choice questions that required selecting all correct answers to receive any credit - almost all of my lost points came from this question format.

**Highlights:**
- The class invites multiple leading researchers in their field as guest lectuers.
- There is a student presentation session in pair where we can choose among several topics. I chose to present on the areas of the improvements for the seminal Wavenet paper. It was quite fun to learn more about wavenet and this is our [presentation slide](/Wavenet_%20A%20Generative%20Model%20for%20Raw%20Audio.pdf).
- There is also a group project (up to three students). Most groups chose application domains like text, image or video generation. We did a project on tabular data instead -- applying interpretable DGM on credit card default prediction. This is our [project slide](/Interpretable_DGM_default_prediction.pdf). We managed to obtian full points for this project for the 2 presentations and final paper.

**Would I recommend?** 

This class significantly overlaps with my other ML courses below. The overlap reinforced key concepts across multiple classes, deepening my understanding. However, I could have used that course slot to explore entirely new topics instead. It's the classic exploration vs. exploitation tradeoff 😏.  I would recommend it if you want to learn more about DGM and its applications in various domains.

Other good resources for this topic which I found helpful are the Deep Generative Modelling class from Stanford and Deep Unsupervised Learning from UC Berkeley. 

## 11-785: Introduction to Deep Learning

### What it covers:
- Neural network fundamentals and backpropagation
- CNNs for computer vision
- RNNs, LSTMs, and sequence modeling
- Attention mechanisms and Transformers
- Generative models (VAEs, GANs, diffusion)

### My experience:
This is CMU's famous deep learning course with a comprehensive curriculum. The course structure includes weekly quizzes, homework assignments with AutoLab and Kaggle components , and for 11785, a substantial final project (25%). The pace is intense - we implemented various neural networks models in PyTorch, which really solidified my understanding of the fundamentals.


**Challenges:**
- Heavy workload, in particular the Kaggle components
- Weekly quizzes demand consistent engagement with material


**Would I recommend?** 

Yes, this course provides an excellent foundation in deep learning. However, I found myself spending disproportionate time on hyperparameter tuning and architecture optimization for the Kaggle competitions. While hands-on experience with model fine-tuning is valuable, it reaches a point of diminishing returns where one invests more effort for marginal score improvements to exceed the high-scoring thresholds.

I also implemented a fully functional mini-PyTorch library using Autograd and ultimately scored more than 101% for the class thanks to bonus points opportunities. It's demanding but rewarding for those serious about learning deep learning fundamentals.

## 10-403: Deep Reinforcement Learning

### What it covers:
- Multi-armed bandits and Thompson sampling
- Value-based methods (Q-learning, DQN, MCTS)
- Actor-critic methods and trust region methods (TRPO, PPO)
- Imitation learning and behavior cloning (GAIL, diffusion policies)
- Maximum entropy RL and continuous control (SAC, DDPG)
- Model-based RL and planning (AlphaGo/Zero, MuZero, Dreamer)
- Offline RL and conservative methods
- Foundation models for RL 

### My experience:
10-403 is the undergraduate version offered in Spring, while 10-703 is the graduate version offered in Fall. They cover similar content, since I didn't want to wait an additional semester, I took 10-403 this semester. This semester's offering was particularly exciting as Prof. Aviral Kumar joined the teaching team along with Prof Katerina Fragkiadaki. The course materials and topics underwent some updates this semester to incorporate more recent developments in RL.

This is arguably my hardest class (though less time-consuming than 11-785) for the semester. The course emphasized both theoretical foundations and practical applications.

**Highlights:**
- Cutting-edge curriculum covering latest RL research in the later half of the course
- Hands-on implementation of RL algorithms
- Applications spanning games, robotics, and LLMs 

**Challenges:**
- Requires solid background in machine learning and Mathematics (an optimization class would be particularly helpful)
- The course has three exams - the first two exams averaged around 50-55% (yes, you read that correctly!). The class did significantly better for the third exam, during which we were also required to read a paper we have never seen and answer some questions about it. Fortunately, they're all open-note, so we can bring printed materials and prepare comprehensive summary sheets.  In fact, I believe challenging exams are essential for motivating students to study the course materials thoroughly. I invested the most exam preparation time this semester on this class, and it paid off.

**Would I recommend?** 

Yes, it's a good class for learning more about RL, and RL is one of the hottest topics nowadays. I became interested in RL more than a year ago and already self-studied using the UC Berkeley CS285 class by Prof. Sergey Levine and another similar class by Prof. Zhang Weinan at SJTU. I also found the book [Mathematical Foundations of Reinforcement Learning](https://github.com/MathFoundationRL/Book-Mathematical-Foundation-of-Reinforcement-Learning) by Shiyu Zhao helpful. Despite this background, I still learned significantly from the CMU RL class due to its comprehensive coverage that goes beyond traditional textbook material and includes cutting-edge research developments.


## Final Thoughts

My first semester at CMU was everything I expected and more. The academic rigor is real. The key is staying focused and organized and remembering why I chose to be here. For Fall 2025, I'm planning to focus more on computer systems.

---
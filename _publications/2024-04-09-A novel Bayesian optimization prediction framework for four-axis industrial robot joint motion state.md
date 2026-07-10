---
title: "A novel Bayesian optimization prediction framework for four-axis industrial robot joint motion state"
collection: publications
category: manuscripts
#permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Authors: Li Zhu; Wei Liu; **Hanzhong Tan**; Tao Hu'  # 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-04-09
venue: 'Complex & Intelligent Systems (SCI-Q2)'
#slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://link.springer.com/content/pdf/10.1007/s40747-024-01425-z.pdf'
#bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Robot joints are the main structure for controlling the motion of the machine body, where the motion state of them directly affects the performance of the industrial robot. Due to the difficulty of obtaining the joint torque information of industrial robots, it is very hard to monitor the motion state of them. Based on the velocity and force driven by current of motors, we propose a novel Bayesian optimization framework to predict the joint motion state of industrial robot in this paper. Based on the temporal correlation of joint current and the correlation between the current and motion state of joint, we use the LSTM and BiLSTM to regressing prediction of the current and state of joint motor first. Then, the Bayesian optimization method is used to adjust the hyperparameters of our network, which realize the analysis of the joint motor current under different motion states and improve the accuracy of the prediction of joint motion states. Finally, we design the joint current acquisition platform of industrial robot based on Hall current sensors, which can collect joint currents without contact and generate experimental dataset. Comparing with the popular intelligent methods, the results show that our Bayesian optimization framework realizes a more accurate prediction of motion state for the four-axis industrial robot on the basis of contact-less current acquisition.

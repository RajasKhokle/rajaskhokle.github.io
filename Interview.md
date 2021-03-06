---
layout: page
title: Interview
permalink: /Interview/
---

<strong>Interviewer:</strong> Good Morning Dr. Rajas. I would like to know about your profile. Who you are, what have done till now?

<strong>Me:</strong> Yes, definitely. I have done my bachelor’s degree in Engineering from 2005-2009. As a capstone project, I worked on an AI and robotics project that involved detecting fire using Image processing and machine vision and then using robot to extinguish that fire. This was my first project on AI. ([Robotics and AI](https://rajaskhokle.github.io/dsi/-5/update/2019/03/24/Firefighting.html))

After that I taught microprocessor and controllers to computer science students in an engineering college for 1 year. Therefore, I have a good hardware level understanding of computers that helps me in understanding the performance tunings and limitations. 

Then from 2011 – 2013, I pursued my master’s from an University run by ministry of defence in India. It was a unique master’s program where I interacted with scientists in Defence organizations and armed forces. It was very practical and hands-on, and I did very exciting projects during this time. For example, I did mathematical modelling for LIDARS to detect explosives. This is the time, when I first learned regression modelling and curve fitting for accurate design of RF and Microwave components ([Antenna Design](http://www.jpier.org/PIERC/pier.php?paper=13040601)). It was also the period where I worked on projects in Fibre Optics as well as wireless communication. I received Vice-Chancellor’s commendation for my work and degree was awarded by the then Defence Minister of India.

Following that, I worked with a fibre optics company called Eagle Photonics from 2013-14. During this time, I worked on various in-house projects like creating models and the user-friendly software for evaluating signal propagation through fibre optic cables under different conditions, integrating electronics and fibre-optic sensors for structural health monitoring. The most work during this time was consulting Reliance for their FTTH project. I interacted with the client to understand their requirements, proposed 3 different projects to fulfil those requirements and led a team of fibre optics engineers, software engineers, and marketing and training coaches. The first project was designing a software tool for link budgeting, the second was developing an emulation platform to evaluate the FTTH network to ensure Quality of Service in the entire network with different components from different vendors, and the third was developing training material for field engineers.

After this I joined Macquarie University, Sydney to purse my PhD from 2015 – 2018. This was exciting as well as stressful period of my career. I was time bound to complete my PhD in 3 years and the problem was very new, required high level of innovation and there was no set path. I started my PhD by interacting with surgeon from Macquarie University who came up with the problem of designing a modality for reducing the resurgeries of Orthopaedic implants. Resurgeries are costly (over $100 million every year) and painful and no modality exists to reduce them. As a first part of my research, I collected data from over 16 countries for unearthing the reason behind the surgeries and concluded that it is the micromotion of the implant that accounts for 70% of repeat surgeries. For this I had to develop a sensor which can be implanted inside the human body. After careful research and considerations, I decided to design an electromagnetic sensor. There are ‘Technical Guidelines’ for available for such a sensor, like it has to have low power consumption, high sensitivity, immune to changes in human body. However, what was totally unclear was how much should be power consumption, what should be the sensitivity, what are the limits for such a sensor, how should such sensor be designed, how small can it be and so on? For this I carried out extensive simulations to study the interaction of human body with electromagnetic waves that generated over 15 terabytes data. I analysed and created several regression models to answer all these questions. I distributed and automated the entire process over multiple machine by using multiple tools by writing custom codes in MATLAB and Python. Further, I made the sensor by combining electronics and quantum mechanics and tested it to verify my results. The resulting work in published in journals and patent and showcased (and won awards) in conferences.([Thesis](https://www.researchonline.mq.edu.au/vital/access/manager/Repository/mq:70866))  In this duration, I also invented a new family of geometrical curves, which I christened ‘M-Segment Quadratic Fractal Curve’.([Fractal Geometry](http://www.jpier.org/PIERC/pier.php?paper=16042001)) This enabled flexibility in the design of miniaturized devices. Also, in this period I taught Agile Project Management Practices to the cohort of over 400 students from different levels and major’s in each session. The teaching itself required a lot of people and project management. 

After finishing my PhD, I turned my attention to the other areas of Data Science and Machine Learning. To expand tools in my belt, I joined General Assembly, where I learnt more algorithms and mathematical techniques and applied them on 4 different projects in different domains like real-estate, pharma and recruitment. I have utilized Time series modelling, Classification using different algorithms like Decision Trees, SVM, KNN, Random Forest and Natural Language Processing. This was my due diligence to prepare me for a corporate role as a data scientist. ([My Posts](https://rajaskhokle.github.io)) 

Currently, I am doing some freelance and volunteer projects around data analytics and NLP for marketing using cloud resources. 

<strong>Interviewer:</strong> So that means you only have 2 years of working experience and rest is your PhD…

<strong>Me:</strong> Technically, yes. However, I would like to point out PhD is not a taught degree. It was very much open ended just like real world projects, it required a lot of research, innovative thinking, time and project management just like, if not more that the corporate world, and I was paid for my work (in form of scholarship) although it was peanuts. In a way, it was much more gruelling experience and I developed many more qualities and skills that I may or may not have developed in regular work. Hence, I include PhD in my experience field. 

<strong>Interviewer:</strong> So, what are these qualities that you are talking about?

<strong>Me</strong>:  First and foremost is passion. To work incessantly on a problem which was never solved before and rife with uncertainties and failures and which requires time bound solution. And doing all this when you are paid literally nothing requires intense passion for your job and work. I therefore developed an intense grit and resilience during this period. This also demands for utilizing and managing your time very efficiently. Another thing that PhD taught me is asking correct questions. What you don’t know, you don’t know. Asking correct questions then enables you to gather correct and useful data and formulate the strategy correctly. Further, my supervisor is a very busy man, this made me very independent in thinking critically and made me a solution-driven person. A very strict peer review is akin to client satisfaction in business. Getting an article published in top level journals means going through tough scrutiny and making sure you exceed the expectations by delivering over and above the comments and questions of the reviewer and communicating clearly. I also reviewed other’s work which gave me experience on reading something new, comprehending that and then asking critical questions that matter most. I believe that these experiences though not tangible immediately, are quite important to be successful in any role.

<strong>Interviewer:</strong> Those are certainly good qualities, however can you tell me about the work which you have done which had tangible results, apart from your PhD results?

<strong>Me:</strong> Certainly, I would like to tell you in brief about 2 really good projects that I have recently done which have very tangible results.

<strong>Machine Vision:</strong>
Sellable.com is a real estate startup company. They wanted to develop an automated valuation model to predict the house price for their database of 88,000 houses. They had lot size of their properties but not the actual built up area. They could get this information from council, however for each house, this information costs $250. For 80,000 properties, it would cost $20M. I have used Google Maps API to capture the images of these homes and developed a machine vision algorithm in python and opencv2 to determine the actual built-up area with 3% accuracy. This can potentially save $20 Million for Sellable.com.
 
<strong>Time Series Modelling</strong>
National health services in UK had published the prescription data (over 1.5TB unpacked) for over 3800 different drugs and appliances over 9000 GPs for last 9 years. First, I aggregated the data from all different files into a single Postgresql database which can be consumed by Python machine learning models, Tableau Visualization tools and Web frontends. Then I developed automated Time series forecasting models and Created Tableau Dashboard for map and time series visualisations filtered by region and drug. This can help any pharmaceutical company operating in UK at all levels of its operation as shown in table below
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-s268{text-align:left}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-s268"><br>&nbsp;&nbsp;Stakeholder<br>&nbsp;&nbsp;</th>
    <th class="tg-s268"><br>&nbsp;&nbsp;Requirement<br>&nbsp;&nbsp;</th>
  </tr>
  <tr>
    <td class="tg-s268"><br>&nbsp;&nbsp;CEO and Shareholders<br>&nbsp;&nbsp;</td>
    <td class="tg-s268"><br>&nbsp;&nbsp;Which drugs in the portfolio are in high demand and bring more<br>&nbsp;&nbsp;revenue? Which drugs have the potential<br>&nbsp;&nbsp;to grow more?<br>&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td class="tg-s268"><br>&nbsp;&nbsp;Production, Planning and Inventory Manager<br>&nbsp;&nbsp;</td>
    <td class="tg-s268"><br>&nbsp;&nbsp;What is the demand for different drugs in the year 2019?<br>&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td class="tg-0lax"><br>&nbsp;&nbsp;Head - Supply Chain Management<br>&nbsp;&nbsp;</td>
    <td class="tg-0lax"><br>&nbsp;&nbsp;What is forecast for drug requirement segmented by geographic area?<br>&nbsp;&nbsp;</td>
  </tr>
</table>

You can read a long version [here](https://rajaskhokle.github.io/dsi/-/s5/update/2019/03/12/Uk-Drug.html).

<strong>Interviewer</strong>: What do you want to work on now and what is the way ahead for you?

<strong>Me</strong>: Going ahead, I would like to continue this path of data science and looking for a permanent role. What really excites me about data science is drawing actionable insights from data that will either optimize the existing process or will enable an entire new solution to yet unsolvable problem. 
 
An ideal position for me would be the one in which I am working with a cohesive and high performing team where I will expand my skills to include business acumen while delivering on my mathematical modelling and problem-solving capabilities along with my communication and presentation skills.   

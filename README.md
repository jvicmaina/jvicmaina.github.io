# jvicmaina.github.io
My first website hosted in github as a test , also its an image classification web app built with python flask , HTML and CSS . 
An image classification web app built with python , it identifies what the name of an animal is , what class it belongs to and the probability of it belonging to a particular class.

it is also a thesis of mine 

 Phish Links Detection System
Student Name
Institution Affiliation
Department


 
ABSTRACT

There has been a very rising trend of increasing cybercrime. Cyber Technology has significantly contributed to our economic, educational, social, ethical, and other critical aspects of life. Cyber threats are hence a significant concern in our day-to-day carrying out of activities. Despite algorithms created to counter phishing attacks, they remain the top successful attacks with the highest count of victims by 2020(S. P. Ripa et al., 2021 ). Just like users, attackers also learn from their mistakes and make their systems or links more bulletproof to detect. The attacks are carried out by employing phishing e-mails, phishing URLs, and websites.


 
DECLARATION
I now declare that this project report is based on our original work except for citations and quotations, which have been duly acknowledged. I also declare that it has not been previously and concurrently submitted for any other degree or award at ABC University.
.
Name: Student No: Signature:       
Date:                        

SUPERVISOR
I, the undersigned, do with this certify that this is an accurate report for the project undertaken by the students mentioned earlier under my supervision and that it has been submitted to ABC with my approval.
Signature……………………………………………………. Date…………………………….
DEDICATION
I dedicate this project to MY beloved lecturer, Mr. ABC, all the stakeholders who participated in ensuring that the development of this project comes to fruition, and the entire ABC fraternity.





Table of Contents

ABSTRACT.. 2
DECLARATION.. 2
SUPERVISOR.. 2
DEDICATION.. 2
Chapter One. 7
1.1 Background of Study. 7
1.2 Problem Statement. 7
1.3 Objectives. 8
1.4 Ethical, legal, and professional issues. 8
1.4.1 Ethical Cyber Security. 8
1.4.2 Machine Learning and the law.. 8
1.4.3 Machine Learning and professional ethics. 8
Chapter 2. 10
Overview.. 10
2.1 Related Work. 10
2.1.1 Management of Knowledge and educating users. 10
2.1.2 Manually identify and ban phishing web pages on time. 10
2.1.3 List-based. 11
2.2 software-based. 11
2.2.1 Machine Learning-based approach. 11
2.2.2 Visual and Textual Similarity. 11
2.3.1 The Present Phishing Detection System's Limitations. 13
2.3.1 Limitations of Current Machine Learning-Based Solutions. 13
2.3.2 Limitations of past work. 14
CHAPTER THREE: METHODOLOGY. 16
3.1 Introduction. 16
3.2 Research Design. 16
3.3 Population. 16
3.4 Data Collection. 16
3.5 Development Tools and Material 16
3.5.1 Hardware requirements. 16
3.5.2 Software requirements. 16
3.6 System Development Methodology. 17
3.6.2 Collection of data. 17
3.6.2.1 Phishing URLs collection. 17
3.6.2.2 Benign URLs collection. 17
3.6.3 Creating Dataset. 17
3.6.4 Algorithms. 17
3.6.4 Performance of classifiers. 18
3.6.2 Experiment and results. 18
3.6.3 Fig 3.6.3 Machine learning with scores for the best model 18
Random Forest Classifier. 18
Fig 3.6.4 Extra trees classifier. 19
Fig 3.6.5 Bagging classifier. 20
Figure 3.6.6 Decision Tree classifier. 20
Figure 3.6.7 KNeighbors classifier. 20
Figure 3.6.8 SDG classifier. 21
Figure 3.6.9 Gradient boosting classifier. 22
Effectiveness of model 22
Fig 3.7. 23
Fig 3.8. 23
Fig 
3.9. 24
Fig 3.10. 24
Fig 3.11. 25
The following were the results. 26
Fig 3.10. 26
Fig 3.11. 27
3.6.5 Conclusion. 27
3.6.6 System Design. 28
3.7 Data Processing and Analysis. 28
3.7.1 Data Cleaning and preprocessing. 28
3.8 Ethical Consideration. 29
3.9 Summary. 29
3.7 Work Plan. 30
Chapter 4. 32
4.0 System Analysis. 32
4.1 Overview.. 32
4.2 Feasibility Study. 32
4.3 Analysis of the current system.. 33
Summary. 34
CHAPTER FIVE.. 35
5.0 SYSTEM DESIGN.. 35
5.1 OVERVIEW... 35
System Requirements. 37
Functional requirements. 37
Non-functional requirements. 38
Physical Design. 38
Logical design. 38
Chapter Six System Implementation. 40
6.1 Overview.. 40
6.2 Tools used for Coding and deploying. 40
6.2.1 For Coding. 40
6.2.2 For deployment, 40
6.3 System Test type. 40
CHAPTER SEVEN.. 41
CONCLUSION AND RECOMMENDATION.. 41
7.0 Overview.. 41
7.1 Achievements. 41
7.2 Challenges. 41
7.3 Proposed system limitations. 42
7.4 Recommendation. 43
7.5 Conclusion. 43
REFERENCES. 45

  
Chapter One

1.1 Background of Study 
Cyber and Information technologies are vast influencers in our social, political, education, and other aspects of life. That being the case, cyber-attacks have become very lucrative for cyber attackers. The forecast is a 133.7 billion bill in 2022 for cyber security. Roughly 62 % population of businesses has to deal with social engineering attacks. The owners of the businesses feel that the threat is going to rise. Very few company documents are entirely or protected at an average of 5%.In 2019, about 4.1 billion records were tampered with for malicious purposes with espionage motives. This was according to a 2019 midyear Quickview data breach report. The percentage of those data breaches had 33%, being contributed by social engineering or phishing.
As the name phishing is defined as an attempt to gain sensitive information, for example, passwords and credit card data with malicious purposes, the attacker pretends to be a responsible party in the communication that is transmitted electronically, for example, mail and websites popups and redirect links. This problem started as soon as there was the discovery of the Internet.
Even as sophisticated as we know, the algorithms used to detect phishing attacks have not been able to curb cyber crimes of this nature fully. According to a report by the Internet Crime Complaint Centre, phishing contributed to financial losses of an estimated 12.5 billion USD globally from 2013 -2018.  
Every day the attackers are learning new ways of luring unsuspecting Internet users by either 
1.	Getting creative on how they lure victims
2.	Bypassing systems that are already existing and perform identity theft
 
 
 
 
 
 
 
 
1.2 Problem Statement
The human aspect is the weakest point in many Security systems. User mistakes, such as opening malicious links, can easily expose valuable data and account credentials, provide exploitable entry points for hackers, or cause systems to malfunction. The fundamental purpose of phishing is to abuse an organization's personnel on one or more security levels to facilitate data access. For example, the hacker may state, "It is Leo from IT; your account has been hacked; kindly click this hyperlink to update and secure your passwords." Frequently, this link provided in this kind of e-mail sends visitors to a website that installs a virus to their system, disabling it. Additional phishing efforts may entice customers to disclose their profile details to assist the attackers in resolving an issue.  
The study will determine whether a particular link is legitimate or harmful. This is because they are the primary areas or points of entry for attacks; when individuals fall for well-crafted material and click the link, becoming victims. This solution will assist individuals in avoiding being hacked as a result of falling for legitimate-looking malicious URLs supplied by coworkers. We may use machine learning to develop and train a model for detecting phishing links to determine whether a URL link is legitimate or fraudulent.
1.3 Objectives
1.	To determine if a link is legitimate or a fraudulent phishing link.
2.	• To raise awareness about how to stay safe online. 
3.	To safeguard online users from phishing assaults while browsing the Internet.
4.	To mitigate the disadvantages of the present phishing detection system.

1.4 Ethical, legal, and professional issues
1.4.1 Ethical Cyber Security

Cyber-attacks happen at very high speeds, undetectable to the human mind, hence the inability to respond. Offenders often look for loopholes that are unknown by the vendors of software or those that are not adequately protected. For better and more effective cyber defense, there is a need to outsmart the attackers by having automated, durable, and adaptable systems that can learn from input data and process at wire speed. Adopting these tools nonetheless will require trust in the systems. This has to take time until they prove to respond to attacks effectively.
Since these tools are commercially in the market, there is a need for machine ethics. These tools should be in line with professionalism and social obligation. There was a proposition of guidelines that would help the three entities: Humans, machines, and cyber security to co-exist 
1. If possible, promote using ML-based cyber tools for defense. The tools should be explainable. 
2. When acting, guided by machine learning cyber-defense tools output and predictions, consider the human aspect of ethics; if you faced a similar solution, what your judgment would be.
3. Take time to get the know-how of machine learning-based tools, and intense learning, as they rely hugely on the mathematics of probability. There is room for error and possible bias. 
1.4.2 Machine Learning and the law
From a legal point of view, there are impacts of using AI/ML tools. According to the (GDPR)General Data Protection Regulation, specific requirements have been in effect since May 2018. The person using Machine Learning tools to decide on someone else, and the decision impacted the victim in a specific way. They owe them explanations as to why they made the specific decision. 
The decisions should not be solely made on machine output, 
1.4.3 Machine Learning and professional ethics
There should be a valid logic as to why a specific action was done. There are three requirements applicable to ML-based tools 
1. How predictions were made should be easy to interpret 
2. The tools should have a level of confidence in their estimates
3. There should be training for users on the do's and don'ts, also a primary education on the tools' limitations.
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 



 
Chapter 2 
 
Overview
Phishing is a big issue in the cyber world, resulting in substantial losses for businesses and people. Detecting phishing attacks with great precision has always been a difficult task. Visual similarity-based algorithms are now beneficial for effectively identifying phishing sites.
Types of Existing Phishing Detection Techniques
Researchers have made significant advancements in security, particularly intrusion prevention, intrusion detection, secure routing, and the protection of smart grids. The following are some ways to detect web phishing.
 
2.1 Related Work
Attacks related to phishing are put in classes of social engineering attacks. These attacks do not involve checking if a system has vulnerabilities. Instead, it looks for opportunities of luring unaware users, i.e., By creating a web page that resembles a login page of a popular e-mail provider or service provider, the attacker then goes ahead and sends users links to log in. If the end-user does not know threads that might potentially happen, they could fall victim. Researchers have been trying to counter their potential risk in the last decade.
They are categorized into two:
I) Human-based
2.1.1 Management of Knowledge and educating users
 
 An increase in human knowledge management aids with the gain of more information in case they undergo a similar situation.
Users should be educated and given more tools to defend themselves from assaults since they are the ones who are at risk. According to research, a business can use its personnel to jointly thwart phishing assaults by coordinating their efforts to build a human barrier (Jensen et al., 2017). They use knowledge management studies on information exchange as a design template for an experiment investigating a platform dealing with reporting phishing attacks. It needed to be centralized. Results show that knowledge management methods may be used for corporate security, which can gain from information collected from phishing prevention. They emphasize the importance of publicly acknowledging the contribution to a body of knowledge—validating the security team's input through the management system. 
 
2.1.2 Manually identify and ban phishing web pages on time
This approach helps to create awareness among end-users to make them wise in case they encounter suspicious websites. Identifying phishing websites manually is a common practice. The client must be informed of the many forms of phishing attempts and be prepared to identify these URLs instantaneously. An analytical method was devised to evaluate ACT-R cognitive actions (Williams & Li, 2017). This is accomplished by determining the validity of websites using the HTTP padlock safety signal. A system was developed dubbed 'PhishZoo' that detects phishing attacks by utilizing site profiling and profile matching (Afroz & Greenstadt 2011). This approach generates all vulnerable sites, which will be compared to the loaded site. The strategy mainly compares the legitimate and Non-Legitimate web pages' content.
 
2.1.3 List-based 
 List-based approach -There is a category in the human approach called list-based, which displays a warning message to prevent the user from falling victim. They rely on the user activity on the Internet, which websites they usually log in to, and build a profile using this information by hashing. These are solutions with a quick access time. However, they have a problem of not being quickly detected because of the zero-day attacks. These attacks take advantage of severe security issues with software that web developers and vendors are unaware of; hence, there is a need to be careful. This approach combines heuristic, white-list, and black-list approaches to caution end-users on potential harmful sites, as is generally in web browsers such as google chrome. This and other modern browsers proofread the list of websites the user wants to visit versus the potential phish list and then warn them.
Firefox looks at every website reported against either malware, phishing, or unwanted software. There is a 30-minute update of the list's default when the user enables the phishing and malware feature.
 
In category two, we study approaches that are 
ii) Software-based
 
2.2 software-based 
We employ various techniques to distinguish between real and fake links and websites. The result of the second approach can be incorporated into the first approach.
Since there cannot be a complete reliance on the end-user to fight phishing attacks, humans are prone to error despite their massive training and awareness. Here we talk about software-based approaches like comparing visual and text resemblance, ML and learning in contexts involving adversaries.
2.2.1 Machine Learning-based approach
Using algorithms has worked in the past. Machine Learning Algorithms have been tried and tested in the following steps. Learning and testing. During learning, algorithms deal with a training set (X), data from supporting examples.
The testing part is where we check if the model predicts accuracy correctly.
In cases where attackers use e-mails to target users, service providers like GMAIL have to machine learning features that automatically sort the e-mails and put them in a spam folder. The available literature shows that the algorithms look for the e-mail context. Most phish-based e-mails typically look almost the same as legitimate ones.
A popular approach is a URL-based approach that uses statistics to identify properties based on lexeme and the host of malicious URLs belonging to certain websites, using properties such as geographic information to classify malicious web pages. The methods below help to learn where the algorithm later analyzes the vast range of networks automatically. This helps extract thousands of features that could be linked with suspicious URLs. This approach has a very high accuracy of about 95-99 %. The main setback of this approach is the lack of enough data sets as there needs to be permission from third-party services.
2.2.2 Visual and Textual Similarity 
This method uses computer vision to identify the difference between landing page images. This helps to detect critical point differences in vectors of images. Using image and text classifiers has also been a great success. This method is. However expensive resources-wise, i.e., computing speed and memory. It also often presents a lot of false positives. However, there have also been increased counterattacks by attackers who have made their websites noisy, making it difficult to detect whether their websites are legitimate.
 
 
Identification of sites based on their content and URL 
Detecting phishing websites manually is a common practice. The client should be informed of the many forms of phishing schemes and be prepared to identify these URLs on time. Williams & Li (2017) established an architectural framework for evaluating ACT-R cognitive actions. This is performed through the HTTP padlock security signal to verify the legitimacy of websites. Afroz & Greenstadt (2011) created 'PhishZoo,' a system that identifies phishing assaults by profile matching and site profiling. This method provides a list of all susceptible websites that will be matched to the loaded webpage. This method is mainly focused on comparing the content of authentic and non-legitimate websites.
 Phishing e-mail blocking using specific software for spam filter
Email-based attacks account for a sizable portion of visits to phishing sites. Filters are pretty effective at preventing unsolicited e-mail opens. Spam filters identify and block the vast majority of hazardous spam e-mails before they reach inboxes. Hr et al. (2020) devised a framework for detecting spam e-mails using spam filters. The framework predicts using the Naive Bayes Classifier method. It distinguishes by content analysis of valid and illicit e-mails. It obtained an overall of 85 percent. Pandey & Ravi (2012) developed a strategy in which they collect information about dissimilarities by examining the URL and the website source code. They next do a text examination of the acquired data and create a forecast.
Server-side detection
A strategy was suggested for detecting phishing websites by analyzing server log data (Hu et al., 2016). When a person views an illegal webpage, the browser requests resources from the authentic ones—the authentic site server inputs this request, which is later used to detect fake URLs. Gangavarapu et al. (2020) developed an approach that combines logic and machine learning strength, bringing an unmistakable essence of a true or false mechanism. They authenticate users by utilizing the sub-domain and domain names and the duration of the web pages.
Client-side detection
An Antiphishing program is comprised of code that detects phishing sites and various 
methods of accessing. These often disable access to material with a warning to the user. Antivirus and anti-malware software are examples of this type of software. A real-time solution was developed for detecting phishing websites by developing a browser add-on or extension (Armano et al., 2016). It gathers data from the person's visited websites to identify phishing sites and then displays a clear warning if the site is phishing. Thomas et al. (2011) have suggested a real-time browser plugin of a similar nature for Firefox.
 
 
 
 
 
 
 
2.3.1 The Present Phishing Detection System's Limitations
Automatically identify and prevent phishing web pages.
Most internet users lack the information to detect a phishing website in real-time (Thiyagarajan et al., 2010).
Even skilled individuals fall victim to the assault since people frequently neglect to verify the credibility of a website when they are occupied with their tasks.
Awareness training does not occur constantly.
Detection based on URL and Content of Websites.
They are deficient in detecting new website URLs (Yerima & Alzaylaee, 2020). These approaches are imprecise and have a low false-negative frequency.
2.3.1 Limitations of Current Machine Learning-Based Solutions
 Attacks based on social engineering, phishing specifically, have not happened to weak systems. On the contrary, human inability to establish if a link is legitimate or not has been the problem. Consequently, multiple techniques have been investigated in the literature to prevent such attacks.
Machine Learning wants to automate the learning process from existing examples and thus no need to be explicitly programmed. This process is called unsupervised learning. There have been superb results on the algorithms that have been used. There, however, have been the following limitations despite the breakthroughs
1) Lack of privacy 
The use of user data in deep learning, as promising as it is, requires large volumes of data to train the models, links of previously visited websites, and searches would be disclosed as data extraction is done from web browsers. Using user data would be a violation of privacy and could result in a lawsuit. Also, it is unethical.
 
2) Lack of enough phishing samples
There are not enough actual attack data samples. Most times in security systems, most instances are standard data samples compared to minority attack data samples. This would lead to a biased training and test dataset. This attack data has different categories of attacks, so we must further classify them into phishing attack subgroups. Also, due to confidentiality and privacy issues, most cyber security researchers do not put their data to open source. Therefore having very minimal data on phishing datasets makes it very hard to make a groundbreaking discovery as the performance would mostly be inconsistent.
3) Over-represented targets are many examples in AI where a subset of data was represented more than it was supposed to, and others were under-represented. The model created using this Data unfairly represents minority groups and genders. This can be drawn from an example where the study of cells was done only on a black population sample. If the white population were few, the whole model would be biased. The sample sizes should be enough and pass a certain threshold. This, regarding phishing, would mean that the links were supposed to be drawn from the traffic of both unpopular and popular websites equally. This would also increase features since some phishing URLs were structurally different from the more popular websites.
 4 Adversarial attacks 
Over the years, attackers have been building very advanced phishing websites, some that are hard to notice with bare eyes. Their difference is from legitimate websites. There is an assumption that the sites where training data is collected have not been phishing, affecting its integrity. However, that is unlikely as the phishers primarily generate noisy data to prevent machine learning algorithms from identifying them. Their aim is usually to make accuracy scores as low as possible when the defense creates models. The cost of manipulating specific systems is very high; hence some phishers opt to target websites that are not adequately secured. They choose websites that will take them the least effort and time.
2.3.2 Limitations of past work
When certain features are enhanced during the process of feature engineering with regards to previous works of people and collected datasets, there has been an assumption that the datasets themselves are not compromised. This could be a cause of the error and misleading information. However, in activities such as spam filtering, that could be not very likely as attackers do one of the following to engineer their data 
i)Make samples of data that have noise
ii) Generate new samples of attacks from the already existing ones.
There will be a need to stay on top as attackers are developing sophisticated websites close, if not undetectable, by the day.
 
 
 
 
 
Ethical review statement
Legal requirements for an ethical approach to phishing detection systems comprise informed consent, which requires that the individual dealing with the system is entirely aware of the system's functioning.

Project Plan              
            Proposed Approach:-
 
                     Collection of Data
 
                                  Train the Model
 
         Build The Model
 
         Import Links To Prediction
 
         Split the Data Into Train and Test set
 
                    Deploy The Model
 
               Results
 
    















 

CHAPTER THREE: METHODOLOGY
3.1 Introduction
      This chapter deals with the methods used to conduct this research study. It focuses on the research design, the method for data collection, and the techniques for analyzing the collected data.
3.2 Research Design
This is a presentation of the plan, structure, and investigation strategy. This study involved a descriptive research approach using surveys designed to depict participants accurately. According to (Mugenda M. O., 2003), this attempts to collect data from a population regarding one or more variables.
3.3 Population
      According to (Cooper, 2001), a population is defined as the subject on which the measurement is taken for study. The population of this study will be 50 classmates and workmates of different ages and genders who will receive anonymous messages about having their accounts compromised. The candidates shall be observed if they click on the reset link sent and the numbers recorded. We will get to identify who identified that the links were phish links.
      3.4 Data Collection
This study is based on both secondary and primary data. Our model needs links for training and testing, and we used selenium for scrapping links from the Internet. The secondary data sources shall include newspapers where we gathered up-to-date information and information system security journals. Owing to the population of the research study, the study will require preliminary information from the test group. Primary data can be collected using the following methods: observations and focus groups, structured and semi-structured personal or telephone interviews, mailed questionnaires, and structured or semi-structured questionnaires. In a case like this, where the respondents are easily accessible and are willing to cooperate for the study, questionnaires shall be the optimal mode of data collection. Questionnaires are one of the most popular and common modes of data collection as they can reach many people simultaneously at a low cost. The questions in this research instrument shall be closed-ended to enable this a mixed method of data collection by making the data quantifiable.
 
      3.5 Development Tools and Material
 
3.5.1 Hardware requirements
 
Hardware requirements include a Laptop with a ram of 6 Gigabytes, a hard disk drive of 1TeraByte, a Solid-state disk of 256 Gigabytes, and a computer processor with a base speed of 2.71GHz.
 
3.5.2 Software requirements
 
Software specifications will include: Microsoft Visual Studio Code as the IDE (Integrated development environment), the primary programming language will be Python, flask framework for the application development and SQLALCHEMY as the database, machine learning model training was done in google Collaboratory and Jupyter notebook. Also, there will be a need for firewall and antivirus software.
 
 
3.6 System Development Methodology
The system will be developed using the waterfall system methodology. The waterfall model was chosen since it provides a step-by-step development model for Coding and implementing the system. Moreover, it is a plan-driven process-in principle where I had to plan and schedule all of the process activities before starting work on them. There is a division of projects' activities into stages that follow each other and are interdependent on the previous one's completion. There is also a dependence on how specialized the task is, i.e., model creation. The system will be developed using the waterfall system methodology. The waterfall model was chosen since it provides a step-by-step development model for Coding and implementing the system. Moreover, it is a plan-driven process-in principle where I had to plan and schedule all of the process activities before starting work on them. This uses Natural Language Processing (NLP) to identify different characters available in the URLs, such as slashes.
The following were the steps for our proposed approach 
Given our dataset with about 96000 features, the following
1) Extracting URLs of legitimate websites 
2) Create and label our dataset
3) Clean our dataset 
4) Data preprocessing
5) Model evaluation and model selection
3.6.2 Collection of data 
3.6.2.1 Phishing URLs collection
The phishing URLs were taken from various sources for diversity. There was also a need to use URLs that were up to date in order to have a glimpse of the latest phishers trends. Phish tank [2] was one of the sites where we got our data. It is an open-source community that permits researchers and developers to submit and verify phish links. The Data there is safe to use. We also used open PhishPhish [2], which identifies phishing sites intelligently and in real-time. This site also provides intelligence about the phishing attempt, such as geolocation and the target of the attack, i.e., Facebook.
3.6.2.2 Benign URLs collection
We used a list provided by google of complete legitimate URLs. We used a web crawler to collect data using Netflow collector too.
3.6.3 Creating Dataset 
A dataset was created from both legitimate and phishing site URLs. Phishing samples that were used in targeting legitimate websites were labeled one, and the rest were labeled as 0
3.6.4 Algorithms
We are solving a classification challenge since our issue is to categorize each URL data point as either phishing or non-phishing. Issue. Consequently, we shall choose a variety of supervised, batch algorithmic learning Model-based and instance-based types of 
There will be algorithmic utilization. The following sentences summarize the algorithms we will use to train our models.
We will also talk about their benefits, strong points, and drawbacks.
1.	We used classifiers such as 
2.	Stochastic Gradient Descent Classifier
3.	Logistic Regression
4.	AdaBoost
5.	Gradient Boost
6.	Decision Tree Classifier
7.	Bagging Classifier
8.	K-Nearest Neighbors Classifier
9.	Extra Trees Classifier
10.	Random Forest Classifier
.We did a run 1o times and had a report on the results average. There was a five-fold validation to prevent overfitting. We then tested the performance of all the learning models against samples that were not seen.
Evaluating how effective an algorithm is by only using the accuracy of datasets that are not balanced could be biased. This is because a significant group with a large margin can dominate the accuracy result. Proper evaluation can be further enhanced by using the f1 score, which is an average of recall and precision used by previous research and approved to be working. It shows the effectiveness of our algorithm.
3.6.4 Performance of classifiers
Random Forest Classifier had the highest F1 scores among all classifiers; hence it was selected to conduct more experiments. It also gave the highest accuracy.
Using RandomizedSearchCV, we can find the best parameters for the model.
3.6.2 Experiment and results 
The machine learning classifiers will be trained on the preprocessed dataset.
Random forest was the best performing model compared to the rest regarding recall and training scores.
3.6.3 Fig 3.6.3 Machine learning with scores for the best model 
Random Forest Classifier 

 

  





Fig 3.6.4 Extra trees classifier

   
 
Fig 3.6.5 Bagging classifier
 
  

Figure 3.6.6 Decision Tree classifier 
 

 Figure 3.6.7 KNeighbors classifier
   

Figure 3.6.8 SDG classifier 
 
  











Figure 3.6.9 Gradient boosting classifier 
  
  
 
 
Effectiveness of model 
Pickling Model
We will pick this model to use for deployment.The model gave exceptional results regardless of the website rank, i.e., Amazon and Google. This demonstrates that our experiments were bias-free.
Data Visualization and Exploratory data analysis
This diagram shows the feature's importance. To differentiate between legitimate and phishing site URLs, we had plots of each feature distribution. 
 
 
 
 
 
 
Fig 3.7 
   
Fig 3.8 
   
Fig 3.9
   

Fig 3.10
   
The null correlations indicate the presence of phishing websites, which are essential for our experiment.

Fig 3.11
The above function was created to extract features from the URLs 
 
  






The following were the results. 
Fig 3.10
  

 







Feature engineering to investigate feature importance 
was investigated here 
Fig 3.11
 
  

3.6.5 Conclusion
In the chapter below, we proposed an approach to help distinguish Phish-based websites from legitimate ones. We generated a model selected with features that were most relevant to feature engineering. Our model has a 99% accuracy after cross-validation. In our future work, we will try to use fingerprint identification of websites in addition to just using the URLs. This will take screenshots of the landing pages with textual images such as logos and the font of words on the pages.

3.6.6 System Design
According to (Otero, A. R., & Otero, A. R. (2018), System design is the actual development of the system process. Systems design refers to the process of element definition of a system such as modules, design, user interfaces for interaction, components, and data for a system that relies on specific requirements. It is the process of identifying, creating, and designing systems that meet a company's or organization's specific objectives. The study will use a flow chart system design to bring out the model. A flow chart in this system is essential to help identify the different process elements among the design steps.

3.7 Data Processing and Analysis
Data collected is processed and analyzed in this chapter, and the collected data will be processed and analyzed. The processing stages will include label encoding, classifying, making plots to visualize data correctly, and writing code classification and tabulation of collected Data that will be ready for analysis. Analysis of data enables the researcher to gather insight on raw information and how it behaves(Kulin, M., Fortuna, C., De Poorter, E., Deschrijver, D., & Moerman, I. (2016). Data collected will be classified based on the user's accessibility to mobile devices (smartphones) and access to the internet connection.
3.7.1 Data Cleaning and preprocessing
There was the use of an enormous dataset containing 96,005 URLs; the percentage of legitimate URLs to phishing ones was 50-50%. The model achieved a 97% accuracy on test data, which was not perfect since it needed more than those URLs for training. URLs with null values were dropped in this process.



 
3.8 Ethical Consideration
Ethics is the way one behaves, whether or not anyone is watching. It is the most basic molarity principle. They are impactful on people's life choices. Ethics, commonly referred to as the philosophy of morality, is concerned with individual benefits and society. In this study, ethical norms will include, Honesty where there will be truthfulness and no misleading or deceiving others.
Integrity will be considered by demonstrating the courage of convictions by doing what is known to be right even when there is a chance or pressure to do otherwise. That is by giving out the correct data that is required by others.
Openness and respect for others' property will be aimed at honoring patents and copyrights by avoiding the use of unpublished data, methods, or results without permission. I am also avoiding work that has been plagiarized by giving credit to the owners of a journal or report.
Fairness and being reasonable in all dealings by not discriminating against others and not abusing power by taking advantage of other people.
 
3.9 Summary
This chapter has brought out the various sub-topics that will successfully implement the Phish Links Detection System by narrowing the gap highlighted in the previous chapter. It explains the type of research design that will be suitable for the development of the system. The chapter also describes the target population and how the population would be sampled to estimate the output of the collected data. The data collection method used in this study is discussed where the study focuses only on closed-ended questionnaires.
The chapter has listed the development tools and equipment that will be used and narrowed it down to the hardware and software system specifications required to develop the proposed system fully. The chapter has also put forward an appropriate system development methodology and the importance of using it in the study. The system's design will be developed and chosen as a flow chart. Finally, the chapter explains how the collected data will be processed and analyzed. This includes the steps that will be taken in order to achieve a clean dataset that will be vital in decision making. Ethical considerations have also been included and will guide the whole process of system development.
 
 Text analysis
I intend to use Python through its libraries like selenium to scrape website data and natural language processing to get information from pdfs and journals concerning data security risks and challenges affecting web-based apps.





           3.7 Work Plan


Activity	March	April	May	June	July	August
Develop proposal document						
Literature review						
Proposal submission						
Pilot study						
Data collection						
Thesis writing					
	
Submission						







	






           
 
 
 
Chapter 4
4.0 System Analysis 
4.1 Overview
In this chapter, we are going to discuss the past systems created by other developers. This chapter discusses the feasibility study and Description of the current system.
4.2 Feasibility Study
A feasibility study is carried out to decide whether the methods, plans, or work is possible or reasonable in evaluating alternatives, accessing the market, and financial analysis (Manikandan, Sekaran, Sarkar, & Manikandan, 2019). The findings have been grouped in the following categories;
In the view of the organization, those companies that are willing to integrate phishing detection systems do not necessarily need to know the background working of the system that is in case the organization is not tech-oriented or they do not have devs of such systems, the phishing detection is easy to use, and one is not required to have exceptional IT skills.
In the view of finance, people managing the systems find it challenging to manage the system since the income generated is too low; the benefits of this phishing system to an organization is that it aids smooth running of the business by preventing attacks which would lead to financial losses to an individual or organization.
In the sense of technology, the technology used in creating phishing detection systems is open-sourced, making it feasible for development.
4.3 Analysis of the current system
Due to their resemblance to real websites, phishing websites provide a challenge to both organizations and individuals. The figure below illustrates the various types of phishing attempts. Subterfuge on a technical level refers to attacks such as keylogging, DNS poisoning, and malware. The attacker's goal in these attacks is to acquire access using a tool or technique. In one instance, users trust the network, while on the other, the attackers have penetrated the network.
Spear phishing is a directed attack on a specific organization; whaling is conducting a series of attacks but only on huge organizations, and mobile applications are all examples of social engineering attacks. The attackers target a group of people or organizations in these attacks and coerce them into using the phishing URL. Apart from existing attacks, many new ones appear exponentially as technology advances.

  



Existing solutions rely on a small number of new internet users. Once they discover a phishing website, they either block access to it or inform the user of the likelihood that the website is not accurate. This solution requires minimal user training and does not require any adjustments to the website's existing authentication system. The following formula is used to determine the detecting systems' performance:
Ø True Positives count (TP): Malicious website's total sum
Ø True Negatives Number(TN): legitimate websites' total
Ø False Positives Number (FP): Incorrect predictions of legitimate websites as a malicious website total
Ø False Negatives Number (FN): incorrect predictions of malicious websites as a legitimate website total
Summary
The proposed study emphasized phishing in regards to classification, where phishing websites are defined as websites that are automatically classified into a predefined set of class values based on many attributes and the class variable. Tactics of phishing in machine learning depend on the functionality of a website in collecting data that can be used to categorize websites to detect phishing sites. Now that phishing cannot be banned, it can be solved amicably in the following ways: by increased focused procedures that are not pro-phishing and by providing education to the public on the detection and identification of bogus phishing websites. Machine learning antiphishing approaches are critical to counter the dynamic sophistication and sophistication of phishing assaults and strategies.

 
CHAPTER FIVE
5.0 SYSTEM DESIGN
5.1 OVERVIEW
The chapter focuses on the design of the system that is to be developed. The key areas to consider are the Description of the new system, new system functional requirements, non-functional requirements, and the physical design.
Description of the Proposed System
This study proposes a URL-based machine learning solution for antiphishing. This method utilizes many URL attributes to determine whether a website is malicious or authentic in order to evaluate its method's efficacy. Over 40,000 phishing and genuine URLs were utilized for training the suggested system using Support Vector Machine (SVM) and Naive Bayes (NB) classifiers. The phishing detection approach was developed with an emphasis on the learning process. They retrieved 14 distinct characteristics that distinguish phishing websites from real websites. When websites with SVM Classification are found, the outcome of their trial achieved above 90% precision.
The study examined a variety of machine learning and deep learning algorithms for detecting URLs by examining distinct URL components. Numerous supervised learning techniques for detecting phishing URLs use vocabulary, page position, the rank of traffic statistics, and page importance properties. The study examined training data volume's effect on classifiers' accuracy. The classification approaches used in the research are Support Vector Machine, K Nearest Neighbors, random forest classification, and ANN.
The study examines conducting algorithm performance using output without and with functionality selection. Experiments were conducted on a phishing dataset using a variety of attributes, including phished and benign websites. Numerous machine learning techniques were utilized to improve the outcome. Functions are picked using a method whose essence is to improve the performance of a model. The random forests approach had the top rank in accuracy both before and after the selection of features and which resulted in a significant increase in the time used to build the model. The experiment's findings indicate that combining a selection strategy with machine learning algorithms can increase how effective classification models are in detecting phishing without a trade-in in their efficiency.
Fig. The user UI running
  
Fig. The user can key in URLs, and also the system can give recommendations if it is malicious or not.
  
Fig. The server running
(Pic) 
System Requirements
System requirements are classified into two, which include; functional and non-functional requirements (Grady, 2006).
Functional requirements
The functional requirements refer to what the user expects from the system.(Condron & Tittemore, 2004)
The interface requirements include:
The URL field can read in different URL formats, i.e., HTTPS, HTTP, and URLs, without a hypertext transfer protocol header.
The system will recommend whether a URL is malicious or not according to an analysis by background computations.
Non-functional requirements
Non-functional requirements NFR imply essential constraints on the development and behavior of software systems (Cysneiros & do Prado Leite, 2002). They portray qualities such as availability, usability, security, extensibility, data integrity, performance, and maintainability. As these qualities play a critical role in architectural design (Chung, Nixon, Yu, & Mylopoulos, 2011), they should be considered and specified as early as possible during the system analysis.
The system is deemed to have high availability and accuracy concerning evaluation metrics such as F1 score to have quality performance.
The system will be user-friendly with a user interface to help the user interact with the system instead of interacting with the background code.
Physical Design 
The physical design shows how Data is input, verified, and stored. Our system has a simple web app that allows the user to paste in a link and then a button that performs the functionality of submitting the data to the logical design where predictions are made and then output in another predictor form.
.
Whereas logical design is concerned with what the system must accomplish, physical design is concerned with how the system will meet those requirements.
Logical design
This is developed during the analysis and system design phase. Logical design is where the features and functions of the system are defined with respect and relationship with its components.
The logical design also has the expected output of the system and what needs to be input into the system. This also includes how tasks must be accomplished starting from input, output, and interphase. This should be a physical accomplishment.

 
 
Chapter Six System Implementation

6.1 Overview
In this chapter, system testing, system changeover, and documentation will be discussed. In addition, the tool used for Coding will also be highlighted.
6.2 Tools used for Coding and deploying
6.2.1 For Coding
Python
This project was programmed using Python 3.10. Additionally, several python modules for machine learning were used. Such included Pandas, Numpy, Seaborn, Matplotlib, Plotly, Time, LogisticRegression, MultinomialNB, train_test_split, classification_report, confusion_matrix, RegexpTokenizer, SnowballStemmer, CountVectorizer, make_pipeline, Image, Word cloud, Beautiful Soup, selenium, NetworkX, Warnings, 
6.2.2 For deployment
Below are packages and server-aided deployment of this system.
Unicorn Server
Fastapi 
Joblib
6.3 System Test type
 System tests were done, and the classification report below shows how the system performed according to system accuracy and F1 score.

 

CHAPTER SEVEN

CONCLUSION AND RECOMMENDATION


7.0 Overview
The chapter details the project's accomplishments and the problems it faced throughout its growth. The limitations and recommendations will be highlighted in this chapter. The chapter comes to a close with a conclusion.

7.1 Achievements
The PhishPhish links detection system has achieved its main requirement of accessibility. It is a free application. A free application is free to download, and developers typically make money through advertising, et cetera, unlike paid applications, also known as premium applications, where a user is forced to pay upfront to download the app from the app store or Google play.


.


7.2 Challenges
The proposed system, like any other system, has challenges affecting its general performance. Because this system is a new entrant in the market, competing with already existing technology is very challenging. I had to collect and label them manually, which was very tedious. Also, due to low computing power, the training and test images had 100 images each. Preferably it would have been better if there were more test train sets.
Integrating the model with the eCommerce website was also very difficult due to the many modules. This limited us to using Python as the only language.
The most challenging aspect of developing an application is managing the codebase. Each platform typically necessitates unique code, which necessitates development in a separate space and more tasks per platform. There has been the creation of tools that enable developers to build one codebase, which is multi-platform. The software enables one to build one version that serves multiple platforms and enables it to appear like an application that has been built natively when deployed on all devices.

7.3 Proposed system limitations
The proposed system constraints go through the restrictions that impact the critical qualities of the phish detection system. Developing mobile applications using cross-platform development comes with its limitations. Some limitations include reduced performance, more difficult code design, and a long period to get new features.
When it comes to performance, there are many variables to consider. Generally, if there is a comparison of two applications that are native and cross-platform and have the same functionalities, the native application will have a faster speed. The performance differences are, however, minor in simple application instances.

Cross-platform apps must adapt their design and functionality to individual devices and platforms that differ significantly. As a result, it adds to the workload of developers who must deal with unique exceptions for various devices and platforms, especially with more complex features. Because these challenges are rare in native apps, developers can concentrate on solving users' problems.


7.4 Recommendation
 Distinct versions of this program should be compiled for a variety of operating systems, or in other circumstances, using sub-tree files to adapt or fit the product to different operating systems are some of the critical tactics for development. Another essential strategy is adapting the layer model (abstraction) to different software environments. This software type is known as "platform agnostic," which means it does not favor or support one platform over another. Developers can also use application programming interfaces (APIs) to adapt a piece of software to a specific platform.

7.5 Conclusion
Using supervised ML approaches is promising in detecting phishing websites. There are, however, to have a lot of datasets available for researchers to conduct experiments that are not biased. Also, the larger the datasets, the more the training and learning of algorithms. Large volumes of data are essential in machine learning.
Creating native apps for each platform can be problematic for the business and the development team. If the product's quality deteriorates, this can eventually cause problems for the user. Apps may work for some businesses, but they come at a steep cost when users want the same software on various devices. While less expensive than native apps, hybrid apps can lack features and performance. Achieving high quality regarding an intuitive user interface and user experience might also be challenging. Multi-platform compatibility, the most cost-effectiveness, a more considerable market coverage, and happier customers with cross-platform app development is gained. It gives enterprises a future-proof alternative by allowing them later to deploy the same source code to different platforms.












 

REFERENCES

1.	S. P. Ripa, F. Islam, and M. Arifuzzaman, "The Emergence Threat of Phishing Attack and The Detection Techniques Using Machine Learning Models," 2021 International Conference on Automation, Control and Mechatronics for Industry 4.0 (ACMI), 2021, pp. 1-6, doi: 10.1109/ACMI53878.2021.9528204.
 
1.	Jensen, Matthew & Dinger, Michael & Wright, Ryan & Thatcher, Jason. (2017). Training to Mitigate Phishing Attacks Using Mindfulness Techniques. Journal of Management Information Systems. 34. 597-626. 10.1080/07421222.2017.1334499.
 
Frank Gearhart The Ethical Use of Machine Learning in Cybersecurity https://cdn.ymaws.com/www.members.issa.org/resource/resmgr/journalpdfs/feature0121.pdf 
1.	Seumas Miller Machine learning Ethics and law https://journal.acs.org.au/index.php/ajis/article/view/1893
 
1.	James Zou et al. Ensuring that biomedical AI benefits diverse populations https://www.sciencedirect.com/science/article/pii/S2352396421001511
 
 
1.	.Thiyagarajan, P., Venkatesan, V. P., & Aghila, G. (2010, December). An antiphishing technique using the automated challenge-response method. In 2010 International Conference on Communication and Computational Intelligence (INCOCCI) (pp. 585-590). IEEE.
 
1.	Tushaar Gangavarapu & Jaidhar C.D & Bhabesh Chanduka.Applicability of Machine Learning in Spam and Phishing E-mail Filtering: Review and Approaches https://tushaargvs.github.io/assets/publications/aire-2020-draft.pdf
 
8)      
1.	Awad, Edmond, Sohan Dsouza, Jean-Francois Bonnefon, Azim Shariff, and Iyad Rahwan. 2020. "Crowdsourcing Moral Machines." Communicaions of the ACM (ACM) 63 (3): 48-55 – https://dl.acm.org/doi/10.1145/3339904. 
2.	CB Insights. 2020. “AI 100: The Artificial Intelligence Startups Redefining Industries,” – https://www.cbinsights.com/ research/artificial-intelligence-top-startups/. 
3.	Alluri, L., Mandalapu, V. and Roy, N., 2019. "Developing Machine Learning Based Predictive Models for Smart Policing," In 2019 IEEE International Conference on Smart Computing, pp.198-204 – https://ieeexplore.ieee.org/document/8784006.
4.	Eubanks, Virginia. Automating Inequality. New York, NY: St. Martin's Press, 2017. 
5.	Fraze, Dustin. 2020. "Cyber Grand Challenge, DARPA - https://www.darpa.mil/program/cyber-grand-challenge.
6.	ICO. 2019. "Project ExplAIn - Interim Report," Information Commissioner's Office – https://ico.org.uk/media/2615039/ project-explain-20190603.pdf. 
7.	Jackson, Phillip C. Jr. 2019. Introduction to Artificial Intelligence. 3rd. Mineola, NY: Dover publications, Inc. 
8.	Kaloudi, Nektaria, and Jingyue Li. 2020. "The AI-Based Cyber Threat Landscape: A Survey." ACM Computing Surveys (ACM) 53 (1): 1-34
9.	Kearns, Michael, and Aaron Roth. 2020. The Ethical Algorithm: The Science of Socially Aware Algorithm Design. 1st. New York, NY: Oxford University Press. 
10.	Miller, Seumas. 2019. "Machine Learning, Ethics and Law," Australasian Journal of Information Systems 23: 16 – ISSA Journal | January 2021 The Ethical Use of Machine Learning in Cybersecurity | Frank Gearhart 
11.	Proton Technologies AG. 2020. "GDPR: Chapter 3: Rights of the Data Subject," Intersoft Consulting – https://gdpr-info. EU/chapter-3/. 
12.	Selbst, Andrew D., and Solon Barocas. 2018. "The Intuitive Appeal of Explainable Machines," Fordham Law Review 87 (3): 1085-1140 – https://ir.lawnet.fordham.edu/cgi/viewcontent.cgi?article=5569&context=flr. 
13.	Zephoria. 2020. “The Top 20 Valuable Facebook Statistics— Updated January 2020,” Zephoria – https://zephoria.com/ top-15-valuable-facebook-statistics/.
14.	H. Zhang, G. Liu, T. W. S. Chow, and W. Liu, "Textual and visual content-based antiphishing: A bayesian approach," IEEE Transactions on Neural Networks, vol. 22, no. 10, pp. 1532–1546, 2011.
15.	R. Zhao, S. John, S. Karas, C. Bussell, J. Roberts, D. Six, B. Gavett, and C. Yue, "The highly insidious extreme phishing attacks," in International Conference on Computer Communication and Networks. IEEE, 2016, pp. 1–10.
16.	"Design and evaluation of the highly insidious extreme phishing attacks," Computers & Security, vol. 70, pp. 634 – 647, 2017. 
17.	N. Chou, R. Ledesma, Y. Teraguchi, J. C. Mitchell, et al., "Client-side defense against webbased identity theft," in Computer Science Department, Stanford University, 2004. 
18.	Q. Cui, G.-V. Jourdan, G. V. Bochmann, R. Couturier, and I.-V. "Tracking phishing attacks over time," in International Conference on World Wide Web, 2017, pp. 667–676. 
19.	V. Bulakh and M. Gupta, "Countering phishing from brands' vantage point," in International Workshop on Security And Privacy Analytics, 2016, pp. 17–24. 
20.	X. Han, N. Kheir, and D. Balzarotti, "Phisheye: Live monitoring of sandboxed phishing kits," in ACM SIGSAC Conference on Computer and Communications Security, 2016, pp. 1402–1413.
21.	APWG, "Global phishing survey: Trends and domain name use in 2016," 2017, [Online; accessed 21-October-2016]. [Online]. Available: http://docs.apwg.org/reports/APWG_ Global_Phishing_Report_2015-2016.pdf
22.	22. Williams, N., & Li, S. (2017, June). Simulating human detection of phishing websites: an investigation into the applicability of the ACT-R cognitive behavior architecture model. In 2017 3rd IEEE international conference on cybernetics (CYBCONF) (pp. 1-8). IEEE.
23.	Afroz, S., & Greenstadt, R. (2011, September). Phishzoo: Detecting phishing websites by looking at them. In 2011 IEEE fifth international conference on semantic computing (pp. 368-375). IEEE.
24.	24. HR, M. G., Adithya, M. V., & Vinay, S. (2020). Development of antiphishing browser based on random forest and rule of extraction framework. Cybersecurity, 3(1), 1-14.
25.	25.Pandey, M., & Ravi, V. (2012, December). Detecting phishing e-mails using text and data mining. 2012 IEEE International Conference on Computational Intelligence and Computing Research (pp. 1-6). IEEE.
26.	26.Gangavarapu, T., Jaidhar, C. D., & Chanduka, B. (2020). Applicability of machine learning in spam and phishing e-mail filtering: review and approaches. Artificial Intelligence Review, 53(7), 5019-5081.
27.	27. Hu, J., Zhang, X., Ji, Y., Yan, H., Ding, L., Li, J., & Meng, H. (2016, July). Detecting phishing websites based on the study of the financial industry web server logs. In 2016 3rd international conference on information science and control engineering (ICISCE) (pp. 325-328). IEEE.
28.	28.Thomas, K., Grier, C., Ma, J., Paxson, V., & Song, D. (2011, May). Design and evaluation of a real-time URL spam filtering service. In 2011 IEEE symposium on security and privacy (pp. 447-462). IEEE.
29.	29.Armano, G., Marchal, S., & Asokan, N. (2016, June). Real-time client-side phishing prevention add-on. In 2016 IEEE 36th international conference on distributed computing systems (ICDCS) (pp. 777-778). IEEE.
30.	166 Cybersecurity Statistics and Trends https://www.varonis.com/blog/cybersecurity-statistics





## Question 1. 

- **Tell me something about yourself.**

**Answer** 

Hi, Myself Neeraj, I am having 15+ years of industry experience, I started my carrier as a developer but now I am managing people for the past 7 years. Most of my experience is in the Telco and finance domain. Currently I am working with Reliance Jio as engineering Manager plus solution architect. I am currently involved in the delivery of two very critical projects, UPI and Mobile banking.  

I have good exposer working with the cross-functional stack holders, defining project scope, and translating them to the functional requirements for further development. I am a self-driven person who believes in mentoring and empowering people. I am not afraid of taking risks and believes in innovation.


## Question 2.

- **Why Amazon.**

**Answer** 

To answer this, I think, I have two aspects where I can contribute to Amazon if I get the opportunity. The first is to having long term vision and ignoring the short term gain. Being in Jio I have seen, not having any profits for years but building your Market share and gaining the customer trust and later capitalize it. 

Amazon is the most customer-centric company and goes extra mile for customers satisfaction. While working with jio I have learned how to strive for excellence and improve our service to meet the end-customer needs. If I have given the opportunity, I will contribute to achieving higher customer satisfaction. 

Another aspect I can contribute to Amazon's success story with my ability to mentor and empower the team and further learn and innovate. 


## Question 3

- **What is your weakness?**

**Answer** 

I feel at times I am impulsive and give knee jerk reaction in certain situation which limit my decision-making capacity. It mostly happens when I see mean email in my inbox. People gets a perception that I cant handle tricky situation and not able to think fast and effectively. 

However, I am working on it and started doing things that are helping me. like I must consider if the battle I am about to fall into is worth fighting for, or not. I am also reading a book Mind Over Matter by Peter Hollins. 

I had a lot of thoughts that I could not put into words due to a lack of sufficient vocabulary or scared of giving a false impression or for the fear of not being able to communicate "exactly" how I framed it in my mind. 

## Question 4

- **what is your daily routine.**

**Answer** 

I start my day with the operation team call to check if there any issue in production which needs to be taken care on priorities. 
Go over the metrics and identify if there is an anomaly in the production.
I have a usual scrum call with different teams for around 2 hours. 
Update and review scrum board with the day to day updates. 
Meeting with various stack holders for ongoing integrations. 
Creating design and functional interface for the next sprint.
Having evening sync up and close for the day. 


## Question 5

- **Tell me about of time when you had a difficult situation with an employee.**

<img src="ques4.png">

## Question 6

- **Who was your most difficult customer?**

**Answer** 
MTN cameroon was the best example where we had deployed our wifi on demand solution. They had a genuine problem where around midnight there were surge in the payment failures and consumer were impacted. They reported the issue to my operation team but team shrugged it off saying that issue is at the charging system and API SLA is breaching. Than issue escalated and came to me. I looked into the problem and realized that is correct and most of the request is having read timeout. When we debug the problem we realized that OCS(Ericsson server) was breaching the SLA. 

Later issue was not with the Ericsson either. Later it was identified that network were congested since DB backup between two sites and using the same network. 

difficult customers Trait:

- The Bully

This type of difficult customer is quick to anger, very aggressive, highly critical, impatient, rude, arrogant and often verbally abusive.

- Mr. Know-it-all

I am sure you’ve met this kind of person before. They seem to know everything about everything, including your business, product or service.

- The Habitual Complainer

Generally, customers complain. And it’s a good thing because complaints can be a very rich source of positive and constructive feedback for your business.

## Question 7 (co)

- **Give me an example of a time when you did not meet a client’s expectation. What happened, and how did you attempt to rectify the situation?** 

**Answer**

This is when I was working with ETB and closed a deal to deploy AAA solutions for their DSL/fiber customer. During the sales, we identified the integration, and the sale was closed. I as delivery lead moved to Columbia with the team for UAT. during onsite we got to know that we have got a new integration component as Sandvine DPI. This integration for us was not the only configuration but require some development as well. This was clearly a change request for me so I raised it to the client that this will require a CR and I need to get the approval from sales VP before I go ahead with the integration. Additional work was for a week for development and testing which was impacting our onsite plan and timeline so I had to update the management about the changes. 

But before that my discussion with the client to let them know the new changes in timeline and onsite plan due to the new requirement and he agreed a week delay but was not ready to pay for the new development. Then I spoke to my manager which was sales VP at the time and got the approval and we agreed that we need to raise the CR for sure and wave off the cost. This was a win-win for both the team. 


## Question 8 (co)

- **Tell the story of the last time you had to apologize to someone.**

**Answer**

This is the recent incident when one of the VP in Jio, was trying to add Kotak account in the UPI but it was not working. So I asked him if he can try some other bank and he did and it worked. After I came back home and my wife has an account with Kotak. So I on-boarded her and tried to add Kotak bank account and it failed. This time I asked my operation team nad team lead to analyze the logs and identify the problem and found that NPCI is not giving the data in the proper format. Since we can not test this in a lower environment, all we had to handle the scenario in production. 

Once issue is rectified then I called my VP and apologized for the failure. I asked him to add the bank account and it worked. 


## Question 9 (co)

- **In your opinion, what is the most effective way to evaluate the quality of your product or service to your internal /external customer?  Give an example of a time when you used these measures to make a decision.** 

**Answer** 

When we release our first version of the UPI application where every login require to give your mpin to access dashboard. But we have not seen lot of user login to the dashboard and aborting the login and number of transaction were really low. so we deicide to let go the app mpin screen since transaction is already protected with the UPIN. 

## Question 10 (co)

- **What changes have you implemented in your current department to meet the needs of your customers?  What has been the result?**

**Answer**
When we launched UPI and finance service as part myjio for CUG customer, we began with the android and ios native development. But the time to production was really high if the bug fixes is require at the client side. Myjio playstore push require roughly 3 weeks. So I decided that some of the banking feature we can move to web instead of native. Not only this significantly reduced our time to production but also the man power which was for android and ios. 


## Question 11 (co)

- **Tell me about a time a customer wanted one thing, but you felt they needed something else.  How did you approach the situation, what were your actions and what was the end result?**

**Answer** 
This is the incident when my product team came to me where they want to use MyJio UPI payment option while performing the recharge option. Issue was that if you on the recharge page and send a collect request to jio id id exist. we could do it but the problem was if customer move from recharge to UPI page than there was no return path. 

What I proposed to use the pay feature instead of collect, after recharge amount is selected and customer decided to make payment than lets open the send  money page with amount VPA pre populated. This made customer journey really smooth. No switching back and fourth and you complete the payment.

## Question 12 (ownership)

- **Tell me about an initiative you undertook because you saw that it could benefit the whole company or your customers, but wasn’t within any group’s individual responsibility so nothing was being done.**

**Answer** 
While In alpeo and working with the sales team, I realized that most of prospect were tier 2 and tier 3 with small capex to start the bussines. These customer can not sfford bare metal deployemnt and onsite engineer cost. So I took it on myself to build and deploy soution on AWS and integrate with On primes componenet. This helped rcomplany two ways. first we were able to save the server cost and second we decued to onsite engineer cost significanly. The best outcome to we were able to traget customer with smaller capex which was not the scenerio earlier. 

## Question 13 (ownership)

-	**How do you ensure your team stays connected to the company vision and the bigger picture?  Give an example of when you felt a team or individual goal was in conflict with the company vision.  What did you do?**

**Answer** 

1. Reinforce the company vision by tying it to team and individual goals.
2. Promote the company vision by always making sure it’s visible.
3. Share success stories that realize the company vision.

So last year my manager called and he said that we have 2 million reacharge everyday and comapny focus is avoid .5% percent of churnrate. Company is looking for the avoding chruning payemnt by setting up recurring payment option using autotop. resposibilites on me was to deliver recurring payment option as part UPI/wallet.

We can achieve recurring payment using UPI/DSB/Wallet option. This where I alinged team delivers to the company vision to by setting up the goals to deliver features as a part of solution.


## Question 14 (Invent and simplify)

- **How do you draw new thinking and innovation out of your team? Give an example of how your approach led to a specific innovation.**

1. ecncourage team to attched comunnities disscussion within organization.
2. Ask team to particiapate in the techtalk across the globes. 
3. Allow team to make mistakes and learn. Focus on the constructive critisiam. 
4. Find time to brainstorm with the team and have a healty disscussion for new ideas. 
5. Reward the new ideas even a apprceation mail is good enough for encouragement. 


## Question 15 (Invent and simplify)
- **Tell me about a time when you have enabled your team/ a team member to implement a significant change or improvement.**

**Answer** 

When we fully migrated from molethic to microservices, my operation team had a challenge to track a complete end to end session request. Like eralier thay had to traverse the multiple log files to get the user session logs. This was causing  a significant delay in the debigging. To overcome this issue Team gave them an automate script to find session logs. But that was not somethign I was not very keen and tring for the better solution. So I did my research and deplyed Kafka/Elastic/Kibana stack for log analysis. After which we invent and designed lot of other metrics for monitoring.

Monlethic to Microservice:
1. To simplify the architecture so that code can be moduleraized and interface are well defined. 
2. Moving from Spring MVC to boot gave us the oppoutunity reduced rather simplify the code.
3. Moved from Bare metal  to Kubernetis for auto deployemnt. 
4. Started using Junit and karate for unit and funcational testing. 
5. Started Elastic/Kibana stack to trace the consolidated logs. 


## Question 16 (Invent and simplify)
-	**Tell me about an out-of-the-box idea you had or decision you made that had a big impact on your business.**

Creating the BOM  for the softare sales was something I did while working with sales team. it was designed to get the idea about the initial ball park figure of project. 
It was an excel template where sled team need to fill following. 

Selelct the list of billing component (PCRF, AAA, OCS, DHCP)
Number of susbcriber for licenense
Interface require for PCRf: Gx, Gy, Sh, Rx, Radius
DPI
PCEF
any GUI is require:
Number Of usecases:


## Question 17 (Are right Alot)

- **Tell me about your failure/mistake/ error in judgement.**

**Answer** 

Three years back when I joined Jio, I have asssigned a very critical feature which need to go in production. In Jio we have three envoirment , SIT/Pre prod and Prod. as SDM, it was my resposility to get the QA signoff and create a realea request for SIT/PP which I did. Now when I raised the Prod Rlease request, I have asked to provide the security signoff as well. As a first timer I was not aware about the infosec signoff is alos needed. Due this mistake we have a week but I learned my lesson and did not repeated the same mistake.


**Another Answer** 
While working with MTN cameroon wimax solution I was responsible to write SOW and get the customer signoff before sending to the project team. Since this was my first project I created the SOW and and send it to customer review. After first review I have forward the SOW to the project team. I made a mistake to get the final signoff before sending it to the project manager. Later when team went to the UAT, customer were requesting the feature for location based charging. Out of the feature for location was not enough execute the UAT and needed a quite good development. Customer said that they never signed off the SOW and insisted on the feature from day one. 

My mistake cost me almost 3 weeks of extra work for the team and I almost lost my job. But I learned my lesson and only only I started taking signoff from the SOW but UAT testcases need to be agreed and signed off before project handover to the project manager.


## Question 18 (Are right Alot)

- **Tell me about a decision for which data and analysis weren’t sufficient to provide the right course and you had to rely on your judgment and instincts.  Give me two to three examples.  They don’t have to be big strategic decisions – could be big or small.**

**Answer** 

During the JioMart intgration, i had given the oppoutunity to build the infrastruture for myjio. I had option to build the complete infra on barmetal or go for the complete cloud solution. Not sure what percent of myjio user will opt for the jiomart, I had to take a call without any confirmed numbers so I decied to build complete infra on the cloud considering it would be easier to scale if there is any issue in future. 



## Question 19 (Are right Alot)

- **Tell me a time when you disagree with the boss**

**Answer**

When we are doing the designing for Jiomart with myjio and I want to leverage exiting authentication using Oauth token but My boss has different approach where he was suggesting to have a encrypted JWT token stored in device which can be used for authentication. ofcource his approach was to save few http calls but compromising the security. We had a meeting and he recejcted the idea of using OAuth. So I decided not to interupt him in meeting and decided to write one email stating what is risk if deceided to have JMT token. I explained the JWT must only use to encrypt transit data but should be subsititued for authentication. How the token can be used for identify theft. 

Another factor which we need to consider about rotation of secret keys being shared with all other systems. If any of the backend key is compromised than there is no quick way to recover. In such scenario new keys need to be generated and given to the backend team and whole process require source code level changes to accommodate new keys. 

I also provide the approcal I was suggesting with the detailed call flow. And he agrred with what I was saying. 


## Question 20 (Are right Alot)

-	**Tell me about a business model decision or key technology decision or other important strategic decision you had to make for which there was not enough data or benchmarks.  In the absence of all the data, what guided your choice and how did you make the call? (follow up with the alternatives considered and how/why they were ruled out in favor of the path taken, what was the risk mitigation strategy? Outcome?  Ask for another example and potentially a third until you are sure this is a pattern and not a one off).**

-	**What are the top strategic issues you’ve had to face in your current role?  What decisions did you end up making?**

**Answer**


While In alpeo and working with the sales team, I realized that most of prospect were tier 2 and tier 3 with small capex to start the bussines. These customer can not sfford bare metal deployemnt and onsite engineer cost. So I took it on myself to build and deploy soution on AWS and integrate with On primeses componenet. I didnt have any data point at that time but I strongly beleived that if I solve this problem than we will have better results in sales. 

This helped complany two ways. first we were able to save the server cost and second we decued to onsite engineer cost significanly. The best outcome to we were able to traget customer with smaller capex which was not the scenerio earlier. 


## Question 21 (Higest Standard)

- **1.	Tell me about a time when you have been unsatisfied with the status quo.  What did you do to change it?  Were you successful?**

**Answer**

1. In myjio all the Rest webservice is of type POST and my peer told me to do the same and every one has the same reason that appsec did not approve other API's implemetation. I was not convinced with the answer and first I did was to meet the infosec team and get the actual cause. Appsec denied putting restriction and said the as long as API's are secured, we are OK. I was glad to hear that and I designed my services is complete restful manner and I also infirmed my Mamanger about the incorrect information is being passed from other SDM which might not be correct. 

2. Moving from Multi repo to single repo. across all the enviorment. 



## Question 22 (Higest Standard)

- **How do you seek out feedback on your team’s performance?  Give a specific example of how you used feedback you received on your team to drive improvement.** 

**Answer**

While leading the backned team it was the common feedback from FE team were not communication the contract change and sometime the new contarct is not backword comapatible. To solve this problem we intragrated swagger(open API specification) as part of the delivery so and hosted alone with application. SO developer can check is the issue with the contract and resolve immedeately. for the versioning issue, we decided not to hardcode version in service layer, instead we check version at controller layer and service layer will provide the speerate API for each version.  

## Question 23 (Higest Standard)

- **Can you tell me about a time when a team member was not being as productive as you needed?  What was the situation?  What did you do? What was the result?** 

**Answer**
This was the time when we were working on the Video KYC onboarding and my team lead was not very effective doing the stack holder managment. Lot of technical email/team chat  was not being answered on time. This has been brought to my notice and I collected the incident. I sat with the resource. I was tring to understand the reason and he said that he is having drinking problem which is causing panic attack and he is not able to focus. 

I decided not to push him any further, I asked him to take professional help immedetely. I insisted him if I can speak to his family to update them abnout the situation. He agreed, I allowed him 1 month paid leave and 2 month sabatical, so he can be with family while taking treatment. He resumed after 3 months sober and better. 


## Question 24 (Higest Standard)
- **Describe the process you go through to set specific targets to improve critical areas of your work/team.  Please refer to a specific example.**

**Answer**

We call it Tech improvement and created as task in the sprint. If the task is beyoind the one sprint than we create a subtask for each milestone. untill we complete the whole task. example to such tech imrovements were in last few yaers. 

1. Moving single git repo instead of following enviorment specific branch
1. Always raise MR for master merge
2. SonarQube integration for every build.
2. 90% code coverage using jnuit before deployment
3. Integration Karate Test case.
3. consolidate loging into kibana dashboard 

## Question 25 (Think Big)

-	**Tell me about a time you came up with the vision for a (team, product, strategic initiative) when there wasn’t a guiding vision.  What was it?  How did you gain buy-in and drive execution?** 
-  **Tell me about time you had to develop a product/business model from scratch or when you dramatically changed one in a turnaround situation.**

**Answer**
While In alpeo and working with the sales team, I realized that most of prospect were tier 2 and tier 3 with small capex to start the bussines. These customer can not sfford bare metal deployemnt and onsite engineer cost. So I took it on myself to build and deploy soution on AWS and integrate with On primes componenet. This helped rcomplany two ways. first we were able to save the server cost and second we decued to onsite engineer cost significanly. The best outcome to we were able to traget customer with smaller capex which was not the scenerio earlier. 


## Question 26 (Think Big)

-	**Tell me about encouraging or enabling a member of your team to take big risk.  How did you balance the risk to the business with possible positive outcome for the organization and opportunity for learning for your direct report?** 

**Answer**

This is story about the time when we deceided to move Monolethic application to microservices. WIt was a challenge since this was my project on microservices. This required lot of reading and rearchitecting the application. To metegate the risk we use phased approch and memoved one or two module at a time. 


## Question 27 (Bias for Action)

1. **Tell me about a time where you felt your team was not moving to action quickly enough.  What did you do?**


**Answer**

Few days back when jio mart is being lauched, I had given the task to provide search bar service for front end. There were two team whi had given the same task and asked to present the solution in three days. I quicky decided to not only present the solution but do the POC also. But the team were not convinced that it can be done in three days. So I quickly did the researh and found the excellent linked cource on the Elastic search for the search Bar. 

Now I only need to find the infra where we can setup the elastic, Which I used our azure setup with elsatic on it. 
I arranged test data to be popullated for the demo.
My team a wrapper service and sample page for 


**Tell me about a time when you have made decision quickly.**

This is the time when I was working in alepo and I had closed the sales 

## Question 28 (Bias for Action)


- **Tell me about a time when you were able to remove a serious roadblock/barrier preventing your team from making progress?  How were you able to remove the barrier?  What was the outcome?**

**Answer**

Story: This is about the time when we stuck with the UPI certification. Where response for the request was not reaching out to the backend services. So we stuck and we lost like a week in the network debugging. 

Task: NPCI had given us two public Ip's to be whitelisted, and asked us to proide two IP's for the for outward and inward traiffic. So network team mapped each one in uni directional manner. In actually ths NPCI actually behaves little diffrent, where request is sent from sender IP to thier receiver and we were expecting resposne from thier reciver to my sender. but eevtually thier reciver was sending response to my receiver IP which was not configured. 

**Whoever tries most things wins. It is about getting out there and tring and putting about thing as POC.many times you fail and learn and keep doing it. Make it ass out of your self. Try and try now and dont waste tine thinking about this. This shortest distance from two point is never a straight line. Make your own team and talk to them and talk to many people. "Do one thing everyday that scare you" Rosebelt** 


## Another story.

So recently we have enabled IPV6 on our DNS. After enabling IPV6 team tested the applictaion and it worked fine. But the next day status report refelects the number of transaction was significantly low compared to others day. So I asked team to see if there is some or other problem with the application. I asked operation team to open a severity and asked my team to debug. Team didnt find any abnormility at the application side but I was not convinced. My first gues was that it has something to do with the IPV6. By this time my testing team is also started reporting the issue. To conclude it was inddeed tge IPV6 issue, I configured my APN to work obtain only IPV4 Ip and started testing. My application was working smoothly. no issue. And momeent I switched To IPV6 than my application behaving funny. So this time I involved netwokr and load balancer team that we have request droppoff. Later after thier analysis that the Request Rate was configure much lesser for IPV6 than compare to IPV4. 



## Question 29 (Frugality)

- **Give an example of a time when you challenged your team to come up with more efficient solution or process.  What drove the request?  How did you help?**

**Answer**

Recnetly I have asked to deploy one of our application for on azure cloud for the Sales Demo. While working on the architecture, I ahd a choice to use the APIGw which has a little higher hourly cost instaed of running web server. Rather than using azure gw, I deceide to use ngnix server along weith netflix zuul APIGW which is opensource. 

another example of using elk instead of kibana.

## Question 30 (Earn Trust)

- **Tell me about a time your team’s goals were out of alignment with another team on which you relied to attain a key resource.  How did you work with the other team?  Were you able to achieve your goals?**

## Answer.

As a channle backend we relied on many backedn services and when were we designing the BBPS (bill payment) services, we need to consume. This team was also prallally developing their service which was casuing the issue while consuming, Team has came to syaing that we are not ready to move ahead sue this intermiteent issue. I decide to instead of esclating, lets talk to the team and understand the conytsraint. They explained thier situation and time commitment we decided to work together as team. We created a war room and worked few days in collobarted manner and able to deliver the project. 

## Question 24 (Dive deep)

Tell me about a time you were trying to understand a problem on your team and you had to go down several layers to figure it out.  Who did you talk with and what information proved most valuable?  How did you use that information to help solve the problem? 



- 	When your direct reports are presenting a plan or issue to you, how do you know if the underlying assumptions are the correct ones?  What actions do you take to validate assumptions or data?   (Manager)


## Question 21 (learn and innovate)

- **How do you draw new thinking and innovation out of your team? Give an example of how your approach led to a specific innovation.** 
- **Tell me about a time when you have enabled your team/ a team member to implement a significant change or improvement.** 

**Answer**

There are few things which I enforce my team to learn and inovate. 

30 minute of weekly linked learning every week. 
Every friday we have show & tell session where team need to prepare and present something new which they learn in the week.
Recently we were exploring elastic search engine we got the idea to build the serch bar feature in myjio. Currently myjio is a super app and having multiple mini apps but thesearch feature was not consolidated. We are in the process of deliving search bar where it will work as universal search and open the miniapp based the search tag. 


## Question 16 (Hire and develop Best)

- **Tell me about your hiring process when you are hiring key positions such as direct reports.  Where do you go for talent?  What resources do you employ?  What are the steps in the process?  What traits do you seek that will tell you the candidate will be successful on the team apart from the obvious hard skills?  [probe on how they assess specific things in an interview, such as integrity, who does the references?  Do they do them?  How do they use them?}**


**Answer**
First thing I do is to create a well strcutured job descrition and year the experince. See if someone can be promoted internally and hire with smaller experience.  
Look for the somone you know with whom you have worked and willling to take it. 
Ask for the refferal from who is turned out to be very good hire. 
While screening resumes, look for the person who is outperoforming their current role. Say a developer is also doing the designing  or a lead is involved in system architecture. 
Candiadtes are better if they are not switching jobs very freqyently. 
Conduct written screening for the key skill. 
Spend ample time with the candidates when they are onsite. Verify waht is written is resume is correct to check the candidate integritty.
Ask your peer/Manager review before hiring the candidate.
Recognize and act upon poor performance and hiring mistakes quickly



## Question 17 (Hire and develop Best)

- **Tell me about someone that you hired that you thought was better than you in a number of areas.  How did you add value to that person?** 
- **Give me an example of someone who was promoted one or two levels up in the organization – not just because they were a star who would naturally rise, but due to your development/coaching efforts.**

**Answer**

I have hired **** **** like 2 years back and I hired him beacuse in interview not only he answered all my technical questions but also suggested alternate ways to implememt the same. I knew that I want to hire him immedeatlty. He did really well in intial few months. Only trait he had was like he always an indivisual performer and unable to work with the other team. I started mentoring him to start trust other work and assigned him a new comer to the team. ******** had hard time to delegate the task and insated he used to all the talk to himself. Slowly i asked him to give smaller task to his junior so he would be busy and utilized. He learned quickly to delegate the task and start trusting thier subordinate work. I also told him to tab on the quality check. 


- **Tell me about a time when you had a low performing individual on your team.  How did you deliver feedback to this person?  Did their performance improve or did they leave the organization?**

**Answer**
Disscuss Ashiwini and Shivam cases. 

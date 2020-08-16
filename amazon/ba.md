
##  Speed matters in business.  Many decisions and actions are reversible and do not need extensive study.  We value calculated risk taking. What this looks like in Practice.

## Makes sound, timely decisions and remove barriers for direct reports?
## Quickly identify how work should be done and communicated to team?
## Make timely, sound decisions for the business even when all info you want to have isn’t available?
## Empower Your employees or become a bottleneck?
## Remove barriers to help your team act on new ideas immediately?


## Characteristics of someone having a “Bias for Action”:

When faced with a tough decision that will help you and your team move forward, you don’t avoid that decision. You’re not afraid to step up and make the call. 

- You encourage this same behavior in your direct reports. You let them know you’ll stand behind them if they take a risk that doesn’t work out.

- If you’re missing some key piece of information, you try to get it as quickly as possible. If you can’t, you’re not afraid to move ahead without it.

- You foster an environment of action bias by responding promptly to colleagues looking for information, and always deliver on your promises.

- You roll up your sleeves and remove obstacles, even when it’s “not your job.”

- Still stuck? You ask for help. You don’t let yourself or your team be stuck for days at a time. 


-	Tell me about a time where you felt your team was not moving to action quickly enough.  What did you do?  (Manager)


-	Tell me about a time when you were able to remove a serious roadblock/barrier preventing your team from making progress?  How were you able to remove the barrier?  What was the outcome? (Manager)

Story: This is about the time when we stuck with the UPI certification. Where response for the request was not reaching out to the backend services. So we stuck and we lost like a week in the network debugging. 

Task: NPCI had given us two public Ip's to be whitelisted, and asked us to proide two IP's for the for outward and inward traiffic. So network team mapped each one in uni directional manner. In actually ths NPCI actually behaves little diffrent, where request is sent from sender IP to thier receiver and we were expecting resposne from thier reciver to my sender. but eevtually thier reciver was sending response to my receiver IP which was not configured. 

**Whoever tries most things wins. It is about getting out there and tring and putting about thing as POC.many times you fail and learn and keep doing it. Make it ass out of your self. Try and try now and dont waste tine thinking about this. This shortest distance from two point is never a straight line. Make your own team and talk to them and talk to many people. "Do one thing everyday that scare you" Rosebelt** 

If seeme under contriol than you are driving fast enough. 

## Another story.

So recently we have enabled IPV6 on our DNS. After enabling IPV6 team tested the applictaion and it worked fine. But the next day status report refelects the number of transaction was significantly low compared to others day. So I asked team to see if there is some or other problem with the application. I asked operation team to open a severity and asked my team to debug. Team didnt find any abnormility at the application side but I was not convinced. My first gues was that it has something to do with the IPV6. By this time my testing team is also started reporting the issue. To conclude it was inddeed tge IPV6 issue, I configured my APN to work obtain only IPV4 Ip and started testing. My application was working smoothly. no issue. And momeent I switched To IPV6 than my application behaving funny. So this time I involved netwokr and load balancer team that we have request droppoff. Later after thier analysis that the Request Rate was configure much lesser for IPV6 than compare to IPV4. 




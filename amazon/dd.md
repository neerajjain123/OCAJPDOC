
# Leaders operate at all levels, stay connected to the details and audit frequently.  No task is beneath them.

-	Tell me about a time you were trying to understand a problem on your team and you had to go down several layers to figure it out.  Who did you talk with and what information proved most valuable?  How did you use that information to help solve the problem? 

So recently we have enabled IPV6 on our DNS. After enabling IPV6 team tested the applictaion and it worked fine. But the next day status report refelects the number of transaction was significantly low compared to others day. So I asked team to see if there is some or other problem with the application. I asked operation team to open a severity and asked my team to debug. Team didnt find any abnormility at the application side but I was not convinced. My first gues was that it has something to do with the IPV6. By this time my testing team is also started reporting the issue. To conclude it was inddeed tge IPV6 issue, I configured my APN to work obtain only IPV4 Ip and started testing. My application was working smoothly. no issue. And momeent I switched To IPV6 than my application behaving funny. So this time I involved netwokr and load balancer team that we have request droppoff. Later after thier analysis that the Request Rate was configure much lesser for IPV6 than compare to IPV4. 

- 	When your direct reports are presenting a plan or issue to you, how do you know if the underlying assumptions are the correct ones?  What actions do you take to validate assumptions or data?   (Manager)

- 	Can you tell me about a specific metric you have used to identify a need for a change in your department?  Did you create the metric or was it already available?  How did this and other information influence the change? 




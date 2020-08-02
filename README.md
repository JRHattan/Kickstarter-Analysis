#Kickstarter Analysis Project
#By John Hattan
#Purpose:
##The analysis served to show when Louise’s Kickstarter campaign should take place, and whether having a play with 
her budget is more or less likely to succeed. For Louise, the analysis showed us starting fundraising in the spring 
or summer would mean it’s more likely to be successful. A lower budget means it’s more likely to be successful, as 
after 15,000 start to fail more than succeed. While the graph fluctuates a bit afterwards, there’s less data to work 
with, and the numbers seem more case by case than indicative of any trends for sure.
#Challenges:
##An initial struggle was replicating a faulty code before ensuring it’s 100% airtight, then doubling back when it 
proved faulty. One such struggle was with creating budget ranges, as I initially stated “>5000” and “<9999”, for 
example, then realized this was showing up much differently than it should have. I realized it cut out any instances 
of $5000 in the budget, and rephrased it to “>4999”. I now realize an even better version would be the greater than 
or equal to, “>=5000”, in the off chance there are some budgets between 4,999.01 and 4,999.99.
#Monthly Discoveries:
##Based on the monthly chart, we know the play has a better success rate should it launch in spring to summer. This may 
be an indicator of people’s availability, as children, those working in education, and some companies will give people 
more time off, and thus, giving them more time to see any potential plays, but this does not explain the drop off in 
the winter, when many people also take time off. It’s possible this could correlate with weather too, as roads are 
usually clearer and places dependent on air conditioning, like the south, tend to be newer and have air conditioning 
built in, whereas buildings in the north in winter tend to be older, and may be expensive to heat. Snow may slow or 
stop plays as well.
#Budget Discoveries:
##The monetary trends show an inverse relationship, where the less money they need, the more likely they succeed. 
This makes sense, as less money needed makes it more feasible to achieve. This flips when they get to around $15,000, 
as mentioned earlier, which may mean the project was too ambitious or expensive and failed. Perhaps lower goals may 
encourage more donations, as $10 towards a $1000 project feels bigger than a $10 donation towards a $15,000 project.
#Limits and Concerns:
##A major limitation is we know if a play secured funding, but it could have achieved success from connections, good 
press, or other ways. We know little about locations aside from country, as certain towns or cities within them may 
have an easier time funding plays. We don’t know how aggressive or passive any marketing campaign was, and how many 
people knew about it. It’s hard claiming every campaign was run equally. Plays, directors, and actors provide unique 
experiences, so well-received plays run by good crews may have inherent advantages over others, whereas obscure or 
poorly written plays with weak or unknown crews will struggle.
#Future Research:
##Since we know Louise’s budget, we could pick take plays with similar budgets, say within a thousand dollars, and 
make a pie chart to show the percent success rate closer than the line graph. We could also look at percent and 
success rate based on how long the campaign ran. By subtracting the start date from the deadline, then rounding to 
the nearest day, we can create a variable based of how long the campaign was run. Graphing is difficult, as a large 
spike takes place at 30 days, but the PNG entitled Average_Length demonstrates plays are more successful while 
lasting 20-35 days. This could be a reverse correlation, however, as a kickstarter lasting too long or short may be
a sign of someone ending the operation early or holding on to hope longer than warranted.

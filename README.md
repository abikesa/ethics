# Miller's Crossing

# Stata I (Basic)


```


From: Ning Meng <nmeng2@jh.edu>
Date: Wednesday, May 8, 2024 at 09:48
To: Abimereki Muzaale <muzaale@jhmi.edu>, Vincent Jin <zjin26@jhmi.edu>, Natalie Daya Malek <ndaya1@jhu.edu>, Xujun Gu <xgu23@jhmi.edu>, Maya Aboumrad <maboumr1@jhmi.edu>, Darien Colson-Fearon <dcolson3@jhmi.edu>
Subject: Request for Advice on Assignment Issue
Dear Team,
 
I hope this message finds you well. I am writing to discuss a situation faced when grading homework.
 
Some student submitted their homework late, and the content is closely identical to the provided solution. Our course preface on academic integrity permits the use of sourced code snippets, provided they are properly cited, which was not done in this case.
 
After talking with Prof. Muzaale, we are considering marking the submission as "Ungraded" with a request for resubmission that truly reflects the student's own work, to be completed by Thursday, May 16. This resubmission would be subject to point deductions for both lateness and academic integrity concerns, though the latter would not be formally recorded.
 
We would appreciate your feedback on this approach or hear if you have any alternative suggestions based on your past experiences.
 
Thank you for your time.
 
Sincerely,
 
Ning



From: Abimereki Muzaale <muzaale@jhmi.edu>
Date: Wednesday, May 8, 2024 at 09:08
To: Ning Meng <nmeng2@jh.edu>, Maya Aboumrad <maboumr1@jhmi.edu>
Subject: Re: homework 5
Thanks for raising this issue, Maya! 

Looking at the rubric, I'm drawn to:
#4. Incorrect .xlsx output. So, they lose some -2pt here

And at the Preface of the class book I'm drawn to the second last paragraph:
'Regarding academic integrity, we encourage the use of small code snippets from books, the internet, or peers, provided they’re cited, as shown below:'

/```stata
tokenize `c(ALPHA)'  // Adapted from https://www.statalist.org/forums/forum/general-stata-discussion/general/1380433-creating-a-counter-with-alphabets
Creating a counter with alphabets - Statalist 
Hi there, We often use a numeric 'counter' in loops. Example code: local i = 1 foreach .....{ ....`i'... local i = `i' + 1 } How could I do it using alphabets?
www.statalist.org

/```

So,  you can cite this Preface and write a comment expressing concern that her solution looks identical to the answer key (in both commission [code & comments] and omission [excel output]), and that she did not appropriately cite her source (which we presume is the homework solution, given her late submission).
 
Make a comment at the top of her script that says something like Ungraded (see comments below). Then ask her to resubmit something authentic: her own version of the solution or her understanding of the solution, by Thursday May 16 (ok to use ChatGPT). She may lose points for late submission as well as for resubmission. Some additional points might be lost for academic integrity, though we will not put these on record. 

Ning, we may have to share this with the entire teaching team, including Vincent. Invite the team to comment on our handling of this situation. We are very responsive to negative criticism and might change our approach based on feedback!!
Abi
 
From: Ning Meng <nmeng2@jh.edu>
Sent: Wednesday, May 8, 2024 8:40 AM
To: Maya Aboumrad <maboumr1@jhmi.edu>; Abimereki Muzaale <muzaale@jhmi.edu>
Subject: Re: homework 5 
 
Hi Maya,

I haven’t faced this situation before, let me forward this email to Prof. Muzaale to seek further suggestions. 

My first thought is to let him resubmit their own work rather than upload the solution, but I am not sure.

Hope this helps.

Sincerely,

Ning
 
发件人: Maya Aboumrad <maboumr1@jhmi.edu>
发送时间: 星期三, 五月 8, 2024 08:35
收件人: Ning Meng <nmeng2@jh.edu>
主题: homework 5 
 
Hey Ning,

Would you mind checking the homework 5 submission for Tenzin Lhaksampa? The student submitted their do file late, and it looks like they copied/pasted the hw5 answer key (even the annotations are the same). The answer key is missing code for the question 1 excel output, and so is the student's code. I'm not sure how to handle grading for this - can you please advise?

Thanks so much for your help!
Maya

```

# Open Forum 

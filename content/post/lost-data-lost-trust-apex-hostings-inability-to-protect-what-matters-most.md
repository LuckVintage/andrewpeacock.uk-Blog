+++
title = "LOST DATA, LOST TRUST: APEX HOSTING’S INABILITY TO PROTECT WHAT MATTERS MOST"
date = 1742997652
author = "Andrew Peacock"
draft = "false"
+++

Apex Hosting is a very popular company that offers server hosting for many popular games, including Minecraft. I first discovered them in 2020, and have since spent more than £550 with the company as of March 2025. I have always been very satisfied with Apex Hosting, and have never had any significant issues, that is, until 27th February 2025.

I had just finished up one of my daily livestreams, when I saw a bunch of errors coming from the server console for LU7 Creative, one of the Minecraft servers I have with Apex Hosting. The errors I saw were related to the CoreProtect plugin, claiming the path to its database file did not exist. I was very confused about this, and immediately connected to the server via FTP to manually verify if the file existed. To my surprise, all of my server's files were missing. The folder was totally empty. The first thing on my mind was the possibility that my account with Apex Hosting was compromised. After a quick check, my account appeared to be all in order. I then decided to check the status page to see if Apex Hosting was having any known issues, and that's when I realised what was going on. The message displayed at the top of the status page was:


>"We are aware of an unexpected data loss incident affecting some servers. Please rest assured that this is not due to a security breach or unauthorized access. Our team is actively investigating the root cause and working to restore affected data wherever possible."


My heart sank. Not because of the possibility of permanently losing data for LU7 Creative though. I had already considered the possibility of Apex Hosting having some issues and needing to restore a backup, which is why I configured a basic script to automatically connect to my server via FTP every night and download the most important folders for my server. I had another server also hosted with Apex Hosting, LU7 Survival. Unlike LU7 Creative, LU7 Survival was not a public server that anybody could join. It is a private survival server for me and my friends. I had no recent backup for LU7 Survival, and without knowing the full extent of the situation, or even if the ability to restore the lost data was possible, I was extremely concerned that we had just lost 4 and a half months' worth of progress.

There wasn't much I could do myself at this point. It was an Apex Hosting issue, totally out of my control. I decided it would be a good idea to let players of both LU7 Creative and LU7 Survival know about the issue, so I posted announcements in the relevant Discord servers.

I noticed that LU7 Creative was still showing up as online in my Minecraft server list, so I decided to join. I was immediately met with a bunch of errors and kicked out of the server, not really too surprising since none of the files existed anymore. To prevent the possibility of any further issues, I logged into the server console for both LU7 Creative and LU7 Survival and stopped both servers. This meant both servers were now officially offline, and players were no longer able to make any attempts to connect. I eagerly kept refreshing the Apex Hosting status page for updates, and there was one. They had identified a list of affected servers and started the process of restoring data. I had no idea how long the outage was likely to last. In my head, I was hoping everything would be back online within a few hours, but in reality, I had absolutely no idea how big the scale of this incident was.

A few hours later, I received an email from Apex Hosting, informing me of the incident. I had one email for each server hosted with Apex. They both arrived within 10 minutes of one another

>"Dear Andrew Peacock,
>
>We want to inform you that we are aware of an unexpected data loss incident affecting some servers as of Thursday, February 27th, 2025. Please rest assured that this is not due to a security breach or unauthorized access. Our team is actively investigating the root cause and working diligently to restore affected data wherever possible.
>
>If your server has been impacted, we will provide further details and guidance on next steps, including addressing appropriate compensation once the situation is resolved.
>
>For real-time updates, please check our status page: https://status.apexminecrafthosting.com.
>
>Again, we would like to apologize for any inconvenience that this may have caused you and your players. We thank you for your patience. If you have any questions regarding your server, please do not hesitate to Contact Us.
>
>Best Regards,
>ApexHosting Team"

![Screenshot of email from Apex Hosting](/images/apexhosting1.png#center)

The fact that compensation was mentioned this early into the incident didn't fill me with much hope of getting my servers back online quickly, or even at all. The situation must be pretty bad for compensation to be addressed so early. Other than this email, there wasn't really any significant update from Apex Hosting, and as I went to bed on the evening of 27th February, my servers were both still offline. I kept an eye on the status page throughout the night.

When I woke up on 28th February, the very first thing I did was check the Apex Hosting status page for updates. And I was a little disappointed to learn there was still nothing new, other than Apex Hosting repeatably saying that they are working to restore data across all servers. 24 hours since the incident quickly came and left, with no sign of my servers coming online. I would periodically check the LU7 Creative FTP, but every time I did, my files were nowhere to be seen. I was unable to access the LU7 Survival FTP, as the server just returned 'Connection Refused' errors. The server console was also fully inaccessible, displaying a "Can't connect to daemon (111: Connection refused)" error message.

24 hours in, I was hoping to have more information from Apex Hosting. Many of the updates they had provided lacked sufficient detail, and were very repetitive, not really telling me anything new. I was hoping to get a general idea of how many servers were affected and a rough ETA for their full restoration. As a paying customer, I feel like I was left in the dark. I had no real idea what was going on, other than Apex Hosting "continue to restore servers as fast as possible." If I had any idea that LU7 Creative was still going to be unavailable 24 hours down the line, I would've set up a temporary server using my own backups, so players could still join and play. Any downtime my server experiences negatively affects my server's reputation, and I would like to do everything possible to minimize the impact of the situation from my end. But without adequate updates from Apex Hosting, I really had no idea what to expect. It's possible my servers could have been back online in a few hours, or I could still be waiting for days. It would've been nice to have a rough ETA and to know how many servers they have successfully restored, if anything, to give me an idea of how long I might still be waiting. It would also be nice to know what actually happened. While Apex Hosting quickly ruled out a security breach, they still hadn't told us what happened. I feel that if they could rule out any kind of security issue straight away, they must've known what went wrong from the very beginning, but didn't want to tell us any further details. While I understand Apex Hosting might've wanted to wait until the incident was over to publish further details, I don't see what damage it could've done to let us know in a basic form, such as telling us the data loss incident was caused by a failing hard drive, or they could even be as vague as saying it was a software/hardware failure. Any details would be nice to know.

At 19:41 on 28th February, the LU7 Survival Discord bot posted an automated message to say the server had started. I checked, and it was true! LU7 Survival was back online after being down for 30 hours. Unfortunately, there was data loss. All progress players made on the server from 27th February was gone. This was around 4 hours of playtime from one of my friends. This included building, which isn't exactly something easy to recover. If it was just some mining that was lost, I could go into creative mode and spawn in the lost items. But with building work? The only way to get that back is to rebuild everything. Following advice from someone in the Apex Hosting Discord, I decided to create a ticket with Apex Hosting, to see if there was anything that they could do about the missing progress. 

>"Hello there,
>
>I have two servers with you, as of now one of them (LU7 Survival - xx.xx.xxx.xxx:25654) has been restored, unlocked and is online. Unfortunately, it appears many hours of progress have been lost. Is there anything that can be done about this? I was told by someone in the Apex Hosting Discord server to make a ticket.
>
>Many Thanks,
>Andrew Peacock"

![Screenshot of support ticket](/images/apexhosting2.png#center)

4 hours later, I had a reply:

>"Hello, Andrew!
> 
>I have gone to check your server files, but I am not seeing any pre-restore files currently! When was the last time you were able to join the server properly with all of your progress?
>Please feel free to let us know if you have any further questions! Have a wonderful day!
>
>Megan R.
>Technical Support Operator
>Apex Hosting"

![Screenshot of support ticket](/images/apexhosting3.png#center)

I was in bed when I got this response, but I got up straight away and replied:

>"Hi Megan,
>
>Thank you very much for your reply.
>
>The last time a player was on the server was 13:28 BST on 27th February, all progress was there when they left. Since the server was restored, around 4 hours worth of progress from 27th February is missing.
>
>Many Thanks,
>Andrew"

![Screenshot of support ticket](/images/apexhosting4.png#center)

I mistakenly said BST instead of GMT in my response, but it didn't matter. Around 9 hours later, I had another response:

>"Hello, Andrew!
> 
>I am afraid it will not be possible to recover those 4 hours of progress on the 27th, as our backups run every day at 00:00 UTC.
>Kinds regards,
>
>Marco Padilla
>Technical Support Operator
>Apex Hosting"

![Screenshot of support ticket](/images/apexhosting5.png#center)

As I was fearing, all progress from the 27th February was permanently gone, as Apex Hosting had to restore a backup from 00:00 UTC, which was approximately 13 hours before the incident. This means there is the potential for other servers to have 13 hours of data loss because of this incident. You can do a lot in Minecraft in just an hour, so losing 13 hours of progression in the game would be awful. In a game like Minecraft, it really doesn't take long for a backup to become quite out of data. There's only so much Apex Hosting can do though, I wouldn't expect them to take a full backup of every server more than once per day. It's unfortunate timing for an incident of this scale to take place, but it could've been worse, with the potential to lose 24 hours of data in a worst-case scenario.

Since LU7 Survival suffered permanent data loss, I was interested in what sort of compensation Apex Hosting was going to provide. LU7 Creative was still offline, but changes were made to my server's files. It was just an empty/default Minecraft server, instead of the actual files for LU7 Creative. So while I still had an open ticket, I thought I would mention this too.

>"Hi Marco,
>
>Thank you for getting back to me.
>
>This is very unfortunate. When can I expect to hear what compensation I will receive for the permanent data loss my server has incurred and the downtime?
>
>My other server (LU7 Creative - xx.xxx.xxx.xxx:25660) was unlocked around 10 hours ago, but it appears no server backup has been restored. There's just an empty server in the files, same in the pre-restore folder.
>
>I understand this has been a difficult situation for your team, and I truly appreciate your continued efforts to get everyone back up and running :)
>
>Many Thanks,
>Andrew"

![Screenshot of support ticket](/images/apexhosting6.png#center)

At 21:07 on 1st March, LU7 Creative came back online! This was after being down for 56 hours. I was very pleased to finally see LU7 Creative back online, however, after a check of the server's files, I'm afraid there was missing data. Specifically, it would seem every single .log file was nowhere to be seen. My CoreProtect database was also gone, as well as the full Dynmap render. Data for two new players who joined LU7 Creative on 27th February was permanently lost, and they will be treated as new players all over again if they decide to rejoin in the future. These players only played the parkour, so only lost some statistics. It would be a different story if these players claimed plots and built something. Thankfully, since I have my own automated daily backups of LU7 Creative (nothing to do with Apex Hosting), I was able to replace all the log files that were missing as well as the CoreProtect database. However, due to the size of the Dynmap render, I do not include these in my daily backups. This meant I had to re-render the entire map, which is a very resource-taxing task. This essentially made LU7 Creative unplayable for a further 12 hours while Dynmap completed a full render of the world. So if we add that time onto the time LU7 Creative was down, that makes the server unplayable for 68 hours, all because of a fault on Apex Hosting's side.

The way I see things, I shouldn't be inconvenienced because of their mistake, nor should I have to dig into my own personal backups to restore the server. This makes me wonder, can I trust Apex Hosting with my important server data going forward? If I hadn't invested time into making my own automatic backup system for LU7 Creative, there would have been even more permanent data loss. I never thought I would have to use these backups, but I'm very glad I decided to make my backup system.

A couple of hours after LU7 Creative was restored, I had a response back from my support ticket:

>"Hello, Andrew!
> 
>The backups had to be run a second time for some servers unfortunately! This has been completed for your mentioned LU7 Creative server, and I've checked to make sure the world files all look to be correct!
> 
>If you still have any issues with this, please let us know!
> 
>As for compensation, we sadly don't have an ETA on when we will have information for this specifically I'm afraid. Once all of the servers have successfully been restored and our management has finished discussing though, there will be an email sent out with more information on everything! Including information on what has happened, and compensation!
> 
>Thank you so much for your patience!
>Please feel free to let us know if you have any further questions! Have a wonderful day!
>
>Megan R.
>Technical Support Operator
>Apex Hosting"

![Screenshot of support ticket](/images/apexhosting7.png#center)

I'm interested in why they had to run the backup for a second time, what went wrong when they run the backups the first time? With an incident this critical, every second is important. I also have to wonder whether Apex Hosting was adequately prepared for an incident like this. Having daily backups is great, but if you are going to have issues when attempting to use that backup to restore data, then its reliability comes into question. A backup is only as good as its ability to be successfully restored when needed. If issues arise during the restoration process, it almost defeats the purpose of having backups in the first place.

While I did still have issues, specifically the missing data, I didn't see any point in bothering the Apex Hosting support team again. I knew they were already swamped with support requests as a result of this data loss incident, and I found it unlikely that they would be able to restore the missing data. Based on the ticket response times, it was more than likely faster for me to recover the data from my own backup than wait for a support agent to dig through their own backups. Getting LU7 Creative back up and running was my main priority, especially after already being down for so long. I get the impression their backup system automatically skips things like log files, CoreProtect databases and Dynmap renders to save time and disk space. I can understand them doing this with log files and the Dynmap render, but you can't bring back a CoreProtect database the same way you can just re-generate the Dynmap render. As a Creative server, there is very important information in the CoreProtect database and quite frankly, not something that we can permanently lose.

A whole week passed, and I eventually got an email from Apex Hosting regarding the compensation:

>"Hi Andrew Peacock,
>
>We are following up on the recent data loss incident on February 27, 2025, that impacted your server. We understand how important your data is, and we sincerely apologize for any disruptions this may have caused.
>
>Our team has thoroughly investigated the cause of the issue, which was related to an automated script malfunctioning during routine maintenance. For full details on what happened and how we responded, please see our blog post.
>
>As a token of our appreciation for your patience, we've added 2 days to your server to compensate for the lost gaming time. These days have been automatically applied—no further action is needed on your part. Due to technical limitations with PayPal, free days cannot be added, so customers with PayPal subscriptions will receive 2 days worth of credits, calculated based on your current monthly subscription value.
>
>Additionally, we are granting you a free month of premium support. Customers who already have the premium support package will receive the free month of premium support as a credit instead.
>
>If you have any questions or still need assistance with your server, please don't hesitate to contact our support team.
>
>Thank you for your understanding, and we sincerely appreciate your continued trust.
>
>Game on,
>The Apex Hosting Team"

![Screenshot of Apex Hosting compensation email](/images/apexhosting8.png#center)

Oh boy, where do I start... I half expected Apex Hosting's compensation to be lacking, but I at least thought they would offer a minimum of a week. Two days is actually a joke. I had to re-read it. LU7 Creative specifically was down for more than two days, so their compensation doesn't even match how long the server was down, not to mention the permanent data loss and extra work I've had to put into everything to get the server back on track... They quite simply owe me these two days anyway, it's what I'm paying for! They haven't provided me with anything beyond what I've already paid for, if anything, they've given me less. I'm losing 8 hours for LU7 Creative that I have already paid for. Even if they did extend my servers by the exact days and hours they were unavailable, where's the compensation for the data that was lost? And their premium support? That is just completely meaningless! People shouldn't need 'premium support' for a problem Apex Hosting caused. They caused the problem, they should fix it! Apex Hosting messed up pretty badly, and they even admitted it in the blog post they linked in the email:

>"Our team has thoroughly investigated the cause of the issue, which was related to an automated script malfunctioning during routine maintenance."

They have the audacity to give us premium support as compensation like they're doing us a favour? You can buy premium support for exactly £3.90 a month, it's nothing. According to the Apex Hosting website, premium support includes:

* Expert assistance with plugin error repairs and configurations 
* Seamless map uploads and world management
* Priority troubleshooting to ensure minimal downtime
* Fast response times and ongoing support to keep your server running at peak performance

Everything included are things they should give everyone affected anyway, but the fact they make it seem like this is compensation is a joke. I genuinely couldn't believe this, and under no circumstances would I consider this appropriate compensation. Other Apex Hosting customers were affected a lot worse than me in this data loss incident, but it would seem it doesn't matter how badly you were affected, everyone gets 2 days of compensation.

I was not going to accept this from Apex Hosting. So, after some thinking, I decided to create a ticket and challenge them:

>"Hello there,
>
>I have two servers hosted with Apex Hosting:
>
>LU7 Creative - MCxxxxxx
>LU7 Survival - MCxxxxxx
>
>LU7 Creative was unavailable for 2 days and 8 hours, and when the server came back, there was data loss that I had to manually restore myself through my own backup. Lost data included log files, CoreProtect databases and an entire Dynmap render. Re-rendering the entire map heavily impacted server performance for over 12 hours, making the server essentially unplayable for that time. So, in total, LU7 Creative was unavailable for approximately 2 days and 20 hours.
>
>LU7 Survival was unavailable for 1 day and 6 hours. There was also data loss that included log files, but more importantly, 4 hours of progress from players on 27th February were permanently lost. This was mainly building work, which isn't easy to recover.
>
>Yesterday, I received an email letting me know that 2 days of credit was going to be added to my account to compensate me for the lost gaming time. However, considering how this incident has affected both of my servers, I do not feel this is sufficient enough.
>
>If this were just a downtime issue, I would be prepared to accept the compensation offered. However, due to permanent data loss and the many hours I had to spend restoring LU7 Creative manually, this incident has caused a much greater disruption than standard downtime.
>
>That said, given the downtime my servers experienced and the data loss requiring additional recovery work (as well as the data that was permanently lost), I was hoping that Apex Hosting could consider a more substantial compensation for the disruption. Two days is certainly appreciated, but given the extent of the impact, I was expecting something a little more in line that reflects the disruption this has caused me and players of my servers.
>
>Would it be possible to reconsider the level of compensation offered for my servers?
>
>Many Thanks,
>Andrew Peacock"

![Screenshot of support ticket](/images/apexhosting9.png#center)

Not too long after submitting my support ticket, I received a response from Apex Hosting. 

>"Hello, Andrew!
> 
>Thanks for contacting us. We sincerely apologize for the frustration and negative impact this incident had on your experience.
> 
>In this case, the downtime is categorized as Emergency Downtime, which is exempt from the SLA policy and does not qualify for the traditional SLA compensation. Regardless of the category, however, we wanted to be sure to issue a reasonable form of compensation to all clients for the affected period.
> 
>We know that data loss is more than just downtime—it affects your time and effort, and we truly regret that this happened. While we aren’t able to adjust the compensation further, please know that we take your feedback seriously and are working to prevent incidents like this in the future.
> 
>If you’re still experiencing any ongoing issues, please don’t hesitate to reach out—we’re here to help in any way we can.
> 
>Thank you for your understanding, and we appreciate you being part of our community.
>Kind Regards,
>
>Francie S.
>Billing Support Operator
>Apex Hosting"

![Screenshot of support ticket](/images/apexhosting10.png#center)

Long story short, they refused to adjust the compensation I had already received, categorizing the downtime my servers had experienced as 'emergency downtime.' I strongly disagree with Apex Hosting, I don't think they can class this downtime as emergency downtime at all. According to Apex Hosting's own SLA (Service Level Agreement): 

>"Emergency Downtime means situations where Apex Hosting must temporarily induce downtime on a Server for events such as hardware failure, vulnerability repairs, and other such situations requiring the immediate shutdown of the system. Emergency Downtime is not considered Downtime for purposes relating to the Apex Hosting SLA." 

As Apex Hosting said in their blog post, the downtime and data loss were caused by human error in a maintenance script, not an intentional or necessary shutdown. The servers were not immediately shut down for security or hardware-related reasons. In fact, at least for LU7 Creative, Apex Hosting's servers were still online. But without my files existing, I was unable to start the server. If I had gone ahead and uploaded my backup via FTP, I would've been able to start my server fine. If I didn't manually stop the server myself at the start of the incident, there's a good chance LU7 Creative could've been online during a good majority of the incident, but just broken. With that said, I struggle to see how their emergency downtime clause could apply to LU7 Creative since the servers were online. I think Apex Hosting trying to pull the emergency downtime card here is a bit of a stretch. Even if emergency downtime did apply as per their SLA clause, would it be morally right to 'go by the book' in this situation? I would not expect them to hide behind clauses in their SLA to avoid appropriately compensating customers. Even if Apex Hosting could technically argue that the downtime falls under emergency clauses, the scale of the inconvenience, data loss and manual recovery work, still warrants fair compensation. In my opinion, two days does not suffice.

While I appreciate the quick response, I was not satisfied with the outcome and wanted to press Apex Hosting futher and hopefully receive something a little more appropiate. I also wanted to challenge their classification of this incident as emergency downtime.

>"Hello Francie,
>
>Thank you for your response.
>
>I appreciate that Apex Hosting is acknowledging the impact of this incident and that compensation was offered. However, I would like to respectfully challenge the classification of this as Emergency Downtime.
>
>According to your blog post regarding the incident, this issue was caused by an internal script failure during routine maintenance. This was not an unforeseen hardware failure, security breach, or uncontrollable external factor. It was a preventable issue caused by Apex Hosting’s internal processes. Given this, I believe the incident does not meet the standard definition of Emergency Downtime as outlined in the SLA.
>
>Additionally, while I appreciate the compensation that was provided, two days does not reflect the actual downtime and data loss incurred relating to my specific servers.
>
>Given the scale of the disruption, I would ask that Apex Hosting reconsider the level of compensation offered. I understand that SLA credits may not apply under your interpretation, but given the circumstances, a more appropriate goodwill gesture (such as a full month of service credit) would better reflect the impact this has had.
>
>Many Thanks,
>Andrew Peacock"

![Screenshot of support ticket](/images/apexhosting11.png#center)

Exactly four minutes later, I had a reply:

>"Hello, Andrew!
> 
>Your ticket has been escalated to management.
> 
>Thank you for your patience while we await their availability.
>Kind Regards,
>
>Francie S.
>Billing Support Operator
>Apex Hosting"

![Screenshot of support ticket](/images/apexhosting12.png#center)

This was really good news! If Apex Hosting was going to review the compensation, chances are a regular support agent wouldn’t have the authority to do much and would need to escalate my ticket to someone higher up. I was hopeful I’d receive a positive response from management. Given the number of people likely contacting Apex Hosting about compensation, I expected the management team to be busy, so I anticipated a few days of waiting, especially with the weekend fast approaching.

My ticket was escalated to management on Friday, 7th March at 19:20. On Monday 10th March at 16:01, I had a response from the management team:

>"Hello Andrew,
> 
>We completely understand your point and please know that we do acknowledge the frustration you're currently experiencing, unfortunately with the large scale of requests we've received due to this incident and it not falling under the SLA policy definition, we are unable to provide a larger compensation for this. We provided a 2 day extension/credit to all customers affected, as this is the average period their servers were down or inaccessible, as well as one month of premium support that you can use in case you have any special requests. We've also restored backups for every server that experienced a data loss. In case your server was not restored, please let us know and our team will provide you with a backup.
> 
>Our developer team worked restlessly to get this sorted out as fast as possible and have integrated a plan to ensure it does not occur again, as well as set stricter standards for the future.
>Erika Sureda
>Billing Support Lead
>Apex Hosting"

![Screenshot of support ticket](/images/apexhosting13.png#center)

At this point, I was wondering what the point of escalating my ticket to management was, it seemed like they weren't prepared to consider reviewing compensation for the incident, no matter how much I pressed them on the matter. The response I received was very disappointing, but a little part inside of me wasn't too surprised. Instead of addressing my challenge to their emergency downtime classification, they dismiss it outright by saying it’s not covered. All affected customers were generalized instead of acknowledging individual cases with more severe impact. There are people out there whose servers were greatly affected more than mine, but they also only received 2 days of free hosting. I do not think this is fair at all, there is no 'one size fits all' when it comes to providing compensation for this incident. Everyone was affected differently. Premium support is also worthless in my case. I do not need support, it's not going to bring back any lost data. I did not ask for premium support, I asked for fair compensation.

At this point, I honestly felt like I was flogging a dead horse. I didn't think I was getting anywhere, and I already started to look into my options for moving both of my servers to a different hosting provider. In fact, I wasn't going to bother responding and was going to cut my losses. However, after careful consideration, I didn't want to let Apex Hosting win. So I thought I would give them one more opportunity to make things right. I love using Apex Hosting, I don't want to move to a different hosting provider, especially after all these years. In my response, I re-iterated the impact the incident had on my servers, as well as made sure to be fully honest with them on my intentions to potentially move my servers elsewhere.

>"Hello Erika,
>
>Thank you for your response.
>
>I appreciate Apex Hosting’s efforts in resolving this issue, but I feel that the compensation provided does not adequately reflect the impact on my servers.
>
>LU7 Creative was effectively unavailable for nearly 3 days, with significant data loss requiring manual restoration.
>LU7 Survival lost 4 hours of player progress, which could not be recovered.
>
>Given the extended downtime and data loss, I was hoping Apex Hosting would reconsider and offer a more appropriate goodwill gesture.
>
>If this is not possible, I will have to seriously consider moving my services elsewhere. Please let me know your final decision.
>
>Many Thanks,
>Andrew Peacock"

![Screenshot of support ticket](/images/apexhosting14.png#center)

After roughly 8 hours, I had received yet another response from Apex Hosting:

>"Hello, Andrew!
> 
>We are really sorry for the trouble this has caused. I've added a month's worth of credit for both servers to your account. You can use it toward your next invoice, upgrades, or add-ons. You can find your available credits in your client area here: https://billing.apexminecrafthosting.com/clientarea.php
> 
>We appreciate your patience while the team worked on resolving this. Let us know if you have any other questions!
>Best regards,
>
>Santiago Miguel
>Technical Support Operator
>Apex Hosting"

![Screenshot of support ticket](/images/apexhosting15.png#center)

This is amazing news! A full month of credit for both servers - this is exactly what I was hoping for! I logged into my billing panel to check, and I am happy to confirm they did indeed add £14.20 to my account credit.

![Screenshot of £14.20 account credit](/images/apexhosting16.png#center)

While I was eventually properly compensated for the incident Apex Hosting caused, I feel they definitely could've done things differently to prevent this incident from happening as a whole, or at least minimise the impact. 

To start with, I think Apex Hosting could look into implementing a better backup policy. Daily backups at 00:00 UTC are not frequent enough for active servers. While Apex Hosting does have a nice backup system in their panel, I think, by default, it should automatically run more frequently to backup the most important data. For Minecraft, this would most likely be the world files. These backups should also be stored elsewhere. When these backups do run, it appears to create a world.zip file in the root directly of my Minecraft server. While this is great to have, I do think it should be stored in a different location, so it can hopefully be restored in the event of a similar incident. Any backups of my server that were created using the backup tool could've been potentially lost, just like other data. As Apex Hosting said themselves, the ghost server cleanup script should've been tested more thoroughly before being run on live servers. There is so much that can and did go wrong. It wouldn't have taken too long to test the script outside of a production environment, and doing so would've most likely prevented this incident from occurring in the first place. For cases where mass amounts of data do end up getting lost, Apex Hosting needs to have a plan in place to be able to restore this data as quickly as possible. Ideally, being able to revert the changes immediately instead of having to rely on backups. Using backups should be a last resort. If you have to dig into backups to restore customer data, then clearly something has gone very wrong somewhere. Perhaps this ghost cleanup script should move files to a recycling bin folder, instead of outright deleting them. That way, if the script does go rogue and delete data, or for whatever reason they need to revert actions, Apex Hosting can restore it a lot easier instead of having to rely on off-site backups, which inevitably slow down the restoration process a lot.

Ideally, Apex Hosting should've immediately admitted the cause of the issue as soon as they knew what happened. They were very quick to rule out a security breach, which gives me the impression Apex Hosting knew what caused the data loss very early on, but we only found out what happened in a blog which was posted well after the incident was over. Instead of vague updates, they should have clearly explained from the start that a script failure caused the data loss. Instead of just saying, "We don’t have ETAs", they should have given estimated timelines for affected servers. Server owners were left in the dark, I had no clue how long it was going to potentially take for my servers to be restored. The ETA doesn't have to be exact by any means, but it would be nice for them to give us a general idea where possible.

The backups Apex Hosting restored for my servers were incomplete. I don't know if this was done on purpose to minimize the size of their backups, or if this was just an error with the backup or restoration process itself. If it is the latter, then this needs to be looked into to ensure all data is restored whenever Apex Hosting needs to resort to using backups. If they made a purposeful decision to exclude certain files from the off-site backups, I can understand it to a point. However, important files such as CoreProtect Databases should not be excluded from these backups. Apex Hosting also should've ensured servers were actually ready before unlocking them. While keeping an eye on the Apex Hosting Discord, it became clear that people were experiencing locked servers when they weren't impacted by the incident, as well as unlocked servers when they should've been locked.

Regardless of whether their SLA policy applied to this incident or not, Apex Hosting should've honoured it and offered all affected customers one full month of credit for each server that was impacted. Instead of hiding behind “Emergency Downtime”, they should have honoured the 99.99% uptime guarantee from the start. Two days of credit was insultingly low, no matter how badly this incident impacted individual customers. They also should've acknowledged that not all customers were affected equally. If they didn't want to go by the SLA, Instead of giving everyone the same 2-day compensation, they could have evaluated cases individually and appropriately compensated people. This would've ensured all customers received appropriate compensation that they were happy with.

Apex Hosting failed in multiple areas. They caused the issue themselves, communicated poorly, tried to avoid responsibility, as well as offering compensation that did not match the scale of the incident. This entire incident has made me seriously question whether Apex Hosting is still the right hosting provider for my two Minecraft servers. Going forward, I don't know how much I can trust them to look after my data. While they eventually provided a more reasonable level of compensation, it should never have taken so much effort on my part. Compensation wouldn't have been required in the first place if Apex Hosting took the appropriate steps to prevent the incident from happening. If I hadn't persevered so much, I never would have been properly compensated. If Apex Hosting wants to regain my trust going forward, they need to ensure that incidents of this scale do not happen again. And if they do, they are handled appropriately. For now, I have decided to keep both of my servers with Apex Hosting and allow them to have an opportunity to fully regain my trust. A good hosting provider isn't just about offering powerful servers for a reasonable price. It's about reliability, transparency, and accountability when things go wrong. I think Apex Hosting has a lot to improve in these areas.
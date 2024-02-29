## 2020-10-19 - How to set up a proper Google Mail filter on responses only

### Problem
When creating events in gmail with a large number of invitees, you, by default receive an email per response. But maybe you are just like me and want your inbox to be clean s.t. all invite responses go into one folder excluding invites that you get from others you find that this is neither covered in the official guide by Google nor in other articles.

### Solution
The following “has the words” filter makes sure to only include mails which are responses and are actual invite responses by checking the attachment name.

```
subject:(Declined OR Accepted) ((to:(alexeygy@uber.com) (invite.ics OR invite.vcs)) has:attachment)
```

It can be set under `settings/Filters` and `Blocked Addresses/ Create a new filter`.

![screenshot of gmail](../images/0_ioWsIdcYLX2rUNMs.png)


So far it worked for me reliably helping to keep my inbox clean. text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.

## 2024-02-24 - Are we in the AI forever summer?

Is now a great time for machine learning?

It seems that there is a new wave of the machine learning gold rush ever since ChatGPT released their app. This shows that this time we've also reached an era where end-consumer solutions are playing a big part whereas before, for example with advances in Computer Vision, end consumers initially would not see much.

How long did previous AI summers last?
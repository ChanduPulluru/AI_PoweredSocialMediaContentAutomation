# AI_PoweredSocialMediaContentAutomation
STEP1:
Listing Articles
STEP2:
Summarization[LLMs]
STEP3:
Generate Platform Specific Content[LLMs]
STEP4:
Asset Handling
STEP5:
Auto-Post to Social Media
**Why Workflow Should be used?**
1)Content management(saves time)
2)AI powered generation(personalised content from google sheet data)
3)Multi platform distribution(posts to Linkedin ,facebook,telegram for wider reach)
4)Simplified data entry(centralizes data in google sheets)
**Pre-Requisites**
Google account,linkedin acc,facebook acc and page,telegram acc ,bot,chatid,google sheet name:AI workflow practice and content links
**How to make it?**
1)Login
-Sign In make.com with a gmail account(search make.com over a tab in browser)
-Create a google sheet (search google sheet and login make sure both account of login should be same(make.com and google sheet)
-search for What is Generative AI choose a an article ex:IBM article and paste the link of it into google sheet
2)Make Connection (Trigger) in make.com
-click on google sheet add sheet name and limit then save
<img width="1897" height="952" alt="image" src="https://github.com/user-attachments/assets/35661b69-0cc8-4d50-b90c-63db3a507242" />
3)Summarizing- we need google api key
[Creating modules to create auomation]
we can create :- sequential,parallel,conditional,loop processing
-after google sheet module 
-for gemini to respond we need to run Google sheet
lets add Google Gemini
-Search for Google Gemini then select generate response
-we need API key for that search in browser google ai studio
-create a project named make automation then create a api under it
Now paste this in Google Gemini connection in make.com
Then add Content links and save it
rename it as Summarizer for better unterstanding

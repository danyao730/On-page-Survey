# Survey Product Design

## Requirement

Style of survey varies depending on different questions and feedback client want, designer need to help clients collect feedback by the on-page survey product, and to find out pain points and discover opportunities to improve. 


## Research

I conducted a quick Competitive Anaysis on current products as Survey.js, Surveymonkey, Typeform , Surveygizmo (mainly for enterprise), Usertesting and UsabilityHub by setting up a matrix tool to compare some key information about these products. The matrix includes **Direct Competitor** ( Surveymonkey, Typeform , Surveygizmo), **Indirect Competitor** (Usertesting and UsabilityHub) and **Influencers** (Adobe Portfolio, as design reference on interaction or visualization) in Y axis and comparable factors like **URL of website, Purpose of Product, Target Audience, Strength and Weekness** in X axis. 

By competative analysis, here I summarized some common advantages of these products:

### Modularized

They are many ways of questions and various logic flows. In order to make the tool universally functional and easy to customize,  to modularize each section of the survey is very important. In this way, the complex of survey can be categorized well into nodes in an organized way.

![Question types](https://github.com/danyao730/Wirecraft-test-7---9/blob/master/WX20190412-142145@2x.png?raw=true)

![Survey Monkey](https://github.com/danyao730/Wirecraft-test-7---9/blob/master/WX20190412-140925@2x.png?raw=true)


### Easy to use

No matter the survey normal or casual, to make the interface easy to use can lower user's learning threshold and reduce the drop-off rate. I prefer to refer to [SurveyMonkey](https://www.surveymonkey.com) and [Usability Hub](https://app.usabilityhub.com/tests/new), as they are simple and easy to use.


## Stytem Structure

![System](https://github.com/danyao730/Wirecraft-test-7---9/blob/master/Untitled%20Diagram.png?raw=true)


## Explore ways of survey

In order to better sync our real clients' need, I prefer to assume a real survey for one of the current clinets on helping them to establish the basic persona of their users(age, gender, region, salary, education), and moreover to get specific feedback on the habit of consuming, user's perference, and etc.

Before designing the questionnare, I paid attention to the logic architecture, how to ask questions, what types of options to provide people with and how to motivate the participation. 

Based on the demo data sheet, here I raise the **survey of membership program** as an example.

![Information Architecture](https://github.com/danyao730/Wirecraft-test-7---9/blob/master/membership%20questionnaire%20.png?raw=true)


## User side

There are 4 major steps in the architecture from user side: **enter welcome screen - answer questions - provide feedback - get reward** 

  ### 1. Screener - Welcome Screen

  In order to filter people out of the survey as less as possible, this screener page should be encouragous to arouse user's willingness to join. It can be a normal introduction, or something interesting like getting an invitation and playing an significant role. If they find themselves being invited as an Experience Officer to a survey, it would be incentive. Even better, they can also be informed to be rewarded in the end if they complete very question. 
 
 
  ### 2. Questions

  As for membership program, we need to know the condition of channel and product itself. 
  
  So the structure could be :
  
  **Screener - How to make the program known better - How to motivate people's engagement**  
  
  As for the screenerm,we can ask them "Do you know about our membership program?" at first to filter user. The first way to ask is to encourage users to share their ideas about it and something related. No matter what people choose, even "NO", they will feel not being excluded. 
 
 If people choose YES, we can naturally follow the question " How do you know about it?".
 
 By investigating on Netease Yanxuan (online), Starbucks and Sisyphe bookshop's membership program, we can find out companies like those are positivly promoting their programs with advertisement on Membership Benifits(freeshipping, exclusive sales and meetups, etc.), coupon and gifts. In this case, we can put the assumption as our options into the survey, and see if it can be validated by asking people "what is the most attractive?"， "what is the most reason to be a member？" and so forth.

  
  ### 4. Feedback

  The page includes "thank you" and open question about how the user feel about this survey.
  

  ### 5. Reward

  For those who finish the survey completely, they can be awarded in the end. 



## How do people participate a survey

Here is the wireframe sampleof the assumed survey : https://www.figma.com/file/Yzx6KEvuIwW4Qf9OdTs0Erei/Untitled?node-id=0%3A1

  ### 1. Proceed type

  They are **many ways** to proceed. 
  
  For some users who want to conduct a formal survey, they may need people answer it carefully. In this case, we need to make user pick the option first and then click "Next" button.
  
  If the clients just want quick feedback about how people think of something, users can quickly proceed once the user select, which will shorten the consuming time and reduce people's anxiety for wasting time.

  ### 2. Component

  Besides the survey, a progress bar is necessary to inform users about how long it would take to complete this survey, or the number of questions left to keep them informed and also slightly reduce the chances of dropping off.

  ### 3. Choice 

  Providing users with card-like button with option text on it can make the interface concise and easy to read, and then facilitate users' making choices. 
  

## Client side

There are 5 major steps in the architecture from client side: **input requirement - pick a logic flow - form a survey from modules - preview and establish - analyze result"

 ### Requirement
 
 A starter screen can help to establish basic survey type
 
 ![requirement](https://github.com/danyao730/Wirecraft-test-7---9/blob/master/WX20190412-140055@2x.png?raw=true)
 
 
 ### Logic Flow
  
  A good logic flow can better **participation rate** and improve the **result's accuracy**. According to fields of the survey, recommendation on logic flows can be provided.
  
 ![what do you want to survey](https://github.com/danyao730/Wirecraft-test-7---9/blob/master/WX20190412-140055@2x.png?raw=true)
 
   
  ### Different Question Types 

   Asking people direct questions about the website, basic questions (age, gender, salary...) are useful for us to build personas and find out relationship among user's identity, consuming habits, and opinions. We can provide client with question type options to choose.
   
  ![question types](https://github.com/danyao730/Wirecraft-test-7---9/blob/master/WX20190412-161240@2x.png?raw=true)
  
 #### Question Banks
 
 To optimize the survey experience, a question bank can make people think less.
 
 
 ### Answer
 
 There are multiselect options, single options and open text area, etc. 
 
 ![anwer types](https://github.com/danyao730/Wirecraft-test-7---9/blob/master/WX20190412-161539@2x.png?raw=true)

  ### Feedback from users

  Client can view the result in the survey tool and adjust the survey anytime.
  
  
  ## Wireframe of Survey Tool 
  
  Through the research, I built [a basic structure of the survey tool](https://www.figma.com/file/HEBazaFgiOZh6o3CWxArWCP0/Untitled?node-id=2%3A19) on website.



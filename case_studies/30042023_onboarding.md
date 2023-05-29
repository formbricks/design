# Case study | Onboarding
> 🎉 [Live](https://app.formbricks.com/auth/signup).

### Project details
- 👨‍🎨 **Designer**: ![Kristian](https://img.shields.io/github/followers/sirkotsky?label=Kristian&style=social)
- 👨‍💼 **Product Owner**: ![Johannes](https://img.shields.io/github/followers/jobenjada?label=Johannes&style=social)
- 🗓️ **Timeline**: 25 April – 1 May 2023
- 
## Overview
Onboarding flow is designed to help collect and segment user's profile information by occupation and primary objectives, personalise user's experience, and increase user activation.

### Impact
- 🎉 **x2 user activation rate in 1 month** 

<img width="100%" alt="SFormbricks Onboarding Design" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNjNmM2ZjOTcwMjg2MTM5YmI4Y2I4YzI1NmFkNDgxZGVjYTRhNTM5YyZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/OQOwGP1E4FscN4XHF6/giphy.gif">

> [Penpot prototype](https://design.penpot.app/#/view/0656f724-90d3-81c2-8002-696f8efb13a0?page-id=aa4293c2-cede-80fb-8002-6ab85de3e135&section=interactions&index=0&share-id=248140e0-d822-80a6-8002-6d6e3ad04938&zoom=fit) 

### Problem statement
Formbricks does not collect insights on the user's objectives and segments, which prevents us from presenting the users with relevant features, tools, and templates. As a result, we manage to activate less than 50% of newly acquired users. 

How might we increase the adoption of Formbricks by personalising the user's experience with the platform and helping new users discover and use relevant products?

### Success metrics
- Number of activated users (users who create at least one survey);
- Granular data on user's objectives and occupations;

## Process
### Problem framing
> You can find the discussion [here](https://github.com/formbricks/design/issues/11).

Originally, Formbricks onboarding consisted of email verification, after which the user was brought to an empty landing page:

![Formbricks Landing Page Old](https://user-images.githubusercontent.com/22578094/236224317-38e4d401-329f-4f0e-ac66-d8f996467c51.png)

This resulted in high drop off rate and low conversions: users were not enticed to begin their journey, nor were exposed to the value proposition of Formbricks. At the same time, we were not able to provide the user with the tool they required to get started, because we did not have enough information, nor had the means of collecting it to nudge them to begin their journey.

![Formbricks Dropoff Rate Graph](https://user-images.githubusercontent.com/72809645/234488861-2778db5f-5bdb-4dac-8542-609bb02e3b67.png)

> How might we activate the customer and demonstrate the unique value of Formbricks, using the data collected on their goals and objectives upon onboarding?

An assumption was made that
> by experiencing the core value of the product, the users are more likely to achieve the goal they signed up for. 

### Market research

We have analysed the competitors to identify some common patterns in how they handle Onboarding and activating new customers:

👉 Hubspot:
![Hubspot Onboarding](https://user-images.githubusercontent.com/22578094/235284235-220a0b42-5340-4873-a7a9-5f159a90da4f.png)

👉 Typeform:
![Typeform Onboarding](https://user-images.githubusercontent.com/22578094/235284243-15d7cac7-da39-4efb-bff6-e050dfb6d8a3.png)

- Use the product itself to gather user's information: occupation, objectives, contact info;
- Demonstrate the importance of collecting the data by explaining what it is being used for;
- Personalise the post-onboarding experience by offering tools, templates, and recommendations relevant to the particular user.

### Delivery

After a few initial iterations, we have aligned on some principles:
- Use onboarding to collect necessary data: occupation and objectives;
- Utilise the data to personalise user's post-onboarding landing page (recommend relevant templates);
- Be open and transparent about the process, disclose how the information is used;
- Allow the user to drop off and/or skip any questions;
- Demonstrate the value to the user. 

#### Explorations
We tried utilising the stats to explain why we ask for the customer's occupation, but did not have enough information to present. We might revert to this idea in the future.

<img width="100%" alt="Formbricks Early Wireframe showing that there are over 50% people of the same occupations as the user on the platform" src="https://user-images.githubusercontent.com/22578094/234511526-ff73ffae-f48d-4cce-a0b0-3c702824b962.png">

We also wanted to allow the user to customise their survey appearance early (almost 90% of our activated users changed the default survey colour after onboarding, which was now made easier and faster):

![Formbricks Personalisation Tool](https://user-images.githubusercontent.com/72809645/234255909-133b2b49-cc7a-4f77-9927-9d08382e3daa.png)

## Delivery

### Welcome

We bring the user to this page once they have verified their account. Notice how we display the user's name (provided we can fetch it). 

1. We show the progress bar to help user locate themselves within the Onboarding process;
2. We allow the user to escape Onboarding and promise to do it later;
3. We let the user know that Onboarding will not take longer than 1 minute inside a main CTA;
4. Finally, we explain why we need to collect the data, and link our T&C.

![Formbricks Onboarding Screen 1](https://user-images.githubusercontent.com/22578094/235199185-918e8185-e6da-4b5f-a0b0-fe9de7053eb2.png)

💡 Notice that the progress bar does not start at 0. We're using the [Goal-Gradient Effect](https://lawsofux.com/goal-gradient-effect/) to help the user feel like they are closer to the finish line that they really are.
![Progress bars](https://user-images.githubusercontent.com/22578094/235199878-82b859b4-e061-42be-a69f-99b6d2e778cf.png)

### Questions

|Step|Question|Objective|Value for the user|What we really do|
|-|-|-|-|-|
|1|Introduction|Gather user data in a user-friendly manner|Give informed consent, see a clear purpose in providing personal information|We inform the user of what we need to collect and why, and give them the option to opt out. It establishes trust, demonstrates our commitment to transparent and ethical data handling, centres the experience around the user|
|2|Occupation|Segment user profiles by jobs|Receive recommendations and personalised content, relevant for people of their occupation.|We start with the question that is most personal, most definite, and has obviously high value to both us and the user. At the same time, we start by asking simple questions that do not require free input. This allows us to lift the pressure, allow the user to answer quickly and move on to the next step. |
|3|Purpose|Prioritise new survey templates by objectives, understand the users better.|Get templates, blog posts, and suggestions that are relevant to their objective|Now, we move on to a more complex space. People may not know exactly what they want to do, or have vague ideas, so this question requires some thinking. We present some pre-set options, but ultimately, it is still a matter of one click only.|
|4|Product Creation|Create a product for the end user.|Segregate different products and manage them separately.|At this point, we are done with the survey. We are no longer talking about the user, our focus is on the Product and Surveys, so we are technically **NOT in the onboarding anymore**: it is a part of a product experience, so we present it accordingly: by removing the "I'll do it later" button, introducing a required free input field.|

First, we ask for the user's occupation:
![Formbricks Onboarding Question 1](https://user-images.githubusercontent.com/22578094/235200488-e8c799bf-41a6-4405-9d8b-4ed44842e038.png)

💡 Once we have actual stats, we can bring them back and flash out once the user submits the response!

Next, the user's goal with Formbricks:
![Formbricks Onboarding Question 2](https://user-images.githubusercontent.com/22578094/235200886-23d23dd9-26bb-4acb-adc4-51ec3e0107be.png)

### Customisation
Finally, the user customises their Formbricks appearance. 

![Formbricks Onboarding Customisation](https://user-images.githubusercontent.com/22578094/235283820-fb0b87b7-3fe9-41d5-8ea0-f87962c06f9d.png)

💡 Notice how the "Skip" button is gone now. It is because the user doesn't have to take an action at this stage.

Preview should update live and reflect how the user's survey will change. Notice how we're framing it visually to avoid any confusion with the real form's design.

![Formbricks Form Customisation Preview](https://user-images.githubusercontent.com/22578094/235201446-31f21a47-0a9c-450f-9da0-67eda88b6d53.png)

### Landing page

We are making the use of the information gathered at this point and **redesigning the landing page**: by reorganising the surveys ("Recommended for you") and making the landing page feel less empty. It does not have to be 100% accurate, but in "Recommended for you", we should display surveys that are recommended for the user's objective and occupation.

![Formbricks Landing](https://user-images.githubusercontent.com/22578094/235201251-65257905-2ff3-49d0-a392-c1f7f596ffd3.png)

💡 If the user have skipped the Onboarding, we will not show "Recommended for you", but will still retain a similar design for the landing page:

![Formbricks Landing](https://user-images.githubusercontent.com/22578094/235201945-4f4ead6a-76e4-4d4c-a4a3-6e2767afb800.png)

### Home Page Redesign

💡 The primary expected impact of the Landing Page redesign is the **increase in the % of users who sign up & create surveys**. The hypothesis is, a quick overview of available surveys will entice more users to start creating a survey. Some level of personalisation, on top of that, should entice the user even more by **prioritising surveys that are relevant** for the user (matching their objectives & occupation).

## Next steps & impact
- ✅ Track how we're impacting the number of activated users after 1 week, 1 month, 3 months;
- Measure how many people complete the questionnaire;
- Survey the users: is the new onboarding helpful, how can we improve the onboarding experience further. 

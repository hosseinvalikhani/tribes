<script setup>
import { ref } from "vue";
import cardComponent from "./cardComponent.vue";
import BasketComponent from "./basketComponent.vue";
const basket = ref([]);

const data = ref({
  entity: {
    id: "tribes",
    name: "Tribes",
    whitelabel: {
      logo: "https://api-issue3817-storage-lms3vdypadgt.s3.eu-west-2.amazonaws.com/entity-images/tribes/Oc0NYoqzN0HPV8QlqbPFGhWmyEG5m0cwiKvo7B0A.png",
      favicon:
        "https://api-issue3817-storage-lms3vdypadgt.s3.eu-west-2.amazonaws.com/entity-images/tribes/Oc0NYoqzN0HPV8QlqbPFGhWmyEG5m0cwiKvo7B0A.png",
      loginLogo:
        "https://api-issue3817-storage-lms3vdypadgt.s3.eu-west-2.amazonaws.com/entity-images/tribes/Oc0NYoqzN0HPV8QlqbPFGhWmyEG5m0cwiKvo7B0A.png",
      primaryColour: "#8E2A78",
      secondaryColour: "#FFFFFF",
      accentPrimaryColour: "#008179",
      accentSecondaryColour: "#FFFFFF",
      dangerPrimaryColour: null,
      dangerSecondaryColour: null,
      warningPrimaryColour: null,
      warningSecondaryColour: null,
      successPrimaryColour: null,
      successSecondaryColour: null,
      amberScoreBandLowerMargin: "60",
      greenScoreBandLowerMargin: "85",
    },
    bundles: [
      {
        aims: "Gain an understanding of 14 mandatory care related subjects.",
        outcomes:
          "### By the end of these courses you will understand:\n- Basic Life Support Theory\n- Communication in care\n- Coronavirus\n- Duty of Care\n- Fire Safety\n- Food Safety\n- GDPR and Data Protection\n- Infection Control\n- Manual Handling Theory\n- MCA & DoLS\n- Nutrition & Hydration\n- Person Centered Care\n- Safeguarding Adults\n- Safer People Handling Theory",
        id: "1",
        image:
          "https://tafara.elearninghippo.com/wp-content/uploads/sites/42/2020/10/Mandatory-Bundle-wpv_700x391_right_bottom.png",
        title: "Mandatory Course Bundle for Care Staff",
        detail: {
          price: "120",
          discounted_price: "75",
          promo_video_link: null,
        },
        content: [
          {
            id: "35",
            aims: "To be able to care for adults at risk, keeping them safe from harm and abuse.",
            outcomes:
              "* Understand who safeguarding is aimed at\n* Know who an adult at risk is\n* Know whose responsibility it is to safeguard\n* Understand risk factors for abuse\n* Understand the relevant legislation\n* Be aware of all the different types of abuse\n* Recognise signs of abuse\n* Recognise a potential abuser\n* Understand disclosure and whistleblowing procedures",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/i8LuOC3kwDiTzA6yd8djXVTFGQ1s6Fc1Zjy4ijb0.jpeg",
          },
          {
            id: "79",
            aims: "To be able to care for adults at risk, keeping them safe from abuse.",
            outcomes:
              "* Understand who needs safeguarding \n* Know who an adult at risk is \n* Know whose responsibility it is to safeguard \n* Understand risk factors for abuse \n* Know the relevant legislation\n* Be aware of all the different types of abuse \n* Recognise signs of abuse \n* Recognise a potential abuser \n- Understand disclosure and whistle-blowing procedures",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/l8d4guenJrHyj9bWy2ETpvyu7MzPEUON3avaj6CD.jpeg",
          },
          {
            id: "86",
            aims: "To recognise and appreciate the differences of the people we care for and provide care that is fair and gives equal opportunity to everyone.",
            outcomes:
              "By the end of this course you will:\n\n * Know the responsibilities of employees and employers\n * Know what beliefs, values, and attitudes are\n * Understand what is meant by equality, diversity, inclusion and discrimination\n * Know the legislation in place covering Equality & Diversity\n * Know each of the protected characteristics\n * Understand the different forms of discrimination, and how they can occur",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/UaZjiIrv4bAQ13fEOyubnvJwEXM6oOMs4Kr6k7AV.jpeg",
          },
          {
            id: "100",
            aims: "To understand your obligations to Duty of Care",
            outcomes:
              "By the end of this course you will:\n\n * Know what your duty of care is and with who\n * Understand the definitions used in Duty of Care\n * Know which legislations relate to Duty of Care and why\n * Be aware of your responsibilities and your employers\n * Understand the importance of an individual’s right to live independently whist keeping them safe from harm\n * Know how to deal with comments and complaints\n * Understand that mistakes happen and follow procedure to prevent further mistakes\n * Recognise why conflict happens and how to deal with the individual and situation",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/Fvj26gFgLdWkYLd3y84zp9bGNIrV9EIPGNurjEMS.jpeg",
          },
          {
            id: "102",
            aims: "To be able to care for adults at risk, keeping them safe from abuse",
            outcomes:
              "By the end of this course you will:\n\n * Understand which adults need support and protection\n * Know who an adult at risk is\n * Know whose responsibility it is to support and protect vulnerable adults\n * Understand risk factors for abuse\n * Know the relevant legislation\n * Be aware of all the different types of abuse\n * Recognise signs of abuse\n * Recognise a potential abuser\n * Understand disclosure and whistleblowing procedure",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/yZmPaqnD3rbw018T5KPy8Y0UPYzGgmEDW1t6jY87.jpeg",
          },
          {
            id: "158",
            aims: "To understand responsibilities and protocols regarding Health and Safety.",
            outcomes:
              "By the end of this course you will:\n\n* Understand what Health and Safety means.\n* Know your responsibilities and those of your employer.\n* Understand the relevant Health and Safety legislations.\n* Be aware of tasks that will require special training.\n* Be aware of common accidents and sudden illnesses.\n* Know what to do in an emergency.\n* Understand how to create a Risk Assessment.\n* Understand methods of working safely with hazardous materials\n* Know methods and procedures to prevent fires.\n* Recognise the symptoms, causes and treatment for work related stress.",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/3KSDjCS6wDFZUNxwqeoQ60MCIPZV2ukLl0Mh3k4B.png",
          },
          {
            id: "249",
            aims: "To care for people whilst respecting privacy, promoting choice and maintaining dignity",
            outcomes:
              "* Understand what Privacy & Dignity mean in a healthcare setting \n* Be aware of the importance of person-centred dignity \n* Recognise the importance of maintaining dignity for someone living with dementia \n* Understand the importance of a resident’s personal space \n* Know how to gain trust and confidence by maintaining confidentiality \n* Understand your responsibilities regarding safeguarding, and when it's OK to break confidence \n* Understand the factors that shape personal choices \n* Be aware of the importance of mental capacity within a care setting \n* Know how to help residents maintain independence and make informed choices \n* Know how to conduct a risk assessment\n* Understand the importance of making sure that residents are active participants in their care \n* Know the key principles of self-care",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/tR2ZJfKTfKQZgjO9lNGbuquRO21bEf25akfFVvYN.jpeg",
          },
          {
            id: "252",
            aims: "To be able to contain and control infections effectively within Care Home Settings",
            outcomes:
              "* Understand the different kinds of pathogen \n* Be aware of how pathogens spread through the chain of infection \n* Know how outbreaks are problematic within a care home environment \n* Recognise the symptoms, controls and treatment regarding the common infections within care homes \n* Be aware of the legislations in place regarding controlling infections \n* Know the roles and responsibilities of employers and care staff \n* Understand the protocols in place with an outbreak occurs \n* Recognise the procedures that must be undertaken when admitting a new resident \n* Know how to undertake a deep clean \n* Recognise good hand hygiene habits \n* Know the steps to take to effectively wash hands \n* Understand the importance and use of PPE \n* Be aware of the best practice regarding Barrier Nursing \n* Know how to handle contaminated and dangerous materials \n* Explore the possible outcomes of poorly controlled infections",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/0dyy495svSA96eRNaU7zr5GDi1HZy8dWvVPwUh0k.png",
          },
          {
            id: "267",
            aims: "To understand responsibilities and protocols regarding Fire Safety",
            outcomes:
              "* Understand what is meant by Fire Safety \n* Recognise the common causes of fire \n* Be aware of the legislation surrounding Fire Safety \n* Understand methods of preventing fires \n* Recognise the importance of PAT testing \n* Know how to keep electrical items safe to use \n* Identify fire risks and hazards \n* Know how to undertake a Fire Risk Assessments \n* Understand how to create and implement a Personal Emergency Evacuation Plan \n* Recognise the importance of reporting fire risks \n* Understand how fire safety equipment operates \n* Know how to respond to a fire \n* Understand the roles and responsibilities of Fire Marshals \n* Know how to implement Full and Zonal Evacuations \n* Recognise the importance of Fire Drills \n* Recognise the consequences of poor fire safety \n* Know your responsibilities and those of your employer",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/b7QhFpKs8UN7JuZbVZgUy9uIGK3hPODVyKeu7U4w.jpeg",
          },
          {
            id: "272",
            aims: "To be able to recognise and treat anaphylaxis",
            outcomes:
              "* Know what anaphylaxis is \n* Understand who can be at risk \n* Be aware of the legislation relating to allergies and anaphylaxis \n* Know of the common allergens that can trigger reactions \n* Recognise the symptoms of anaphylaxis \n* Know how to administer first aid to someone with anaphylaxis \n* Understand how adrenaline injectors work \n* Know how to use the most commonly used adrenaline injectors \n* Be aware of the roles and responsibilities surrounding anaphylaxis",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/E0c8GLkkVJnRoEDOMOPKrtgsBFvoCu3DCsamNA7A.jpeg",
          },
          {
            id: "287",
            aims: "To safely provide support in the kitchen during food preparation and food serving",
            outcomes:
              "By the end of this course you will:\n\n* Recognise the symptoms of food-borne illnesses\n* Be aware of who is at risk\n* Understand which foods are high-risk\n* Know the wider impact of food-borne illnesses\n* Be aware of the legislation underpinning food safety\n* Recognise hazards that can make food unsafe\n* Know what anaphylaxis is\n* Recognise common allergens\n* Be aware of ways to keep food safe from allergen cross contamination\n* Be aware of the different types of food pests\n* Know how to prevent pests\n* Recognise the signs of pests\n* Know how to keep food clean and uncontaminated\n* Understand how to wash hands effectively\n* Know the 'Danger Zone'\n* Understand how to store foods safely\n* Be aware of the roles and responsibilities",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/6kPaGAjWh3cAz3B76tlnHyUAyqxBOLIFW719dMGM.jpeg",
          },
          {
            id: "291",
            aims: "To understand the changes GDPR brings, and how to be compliant with the regulations",
            outcomes:
              "By the end of this course you will be able to:\n\n* Understand what GDPR is\n* Recognise its importance\n* Know who and what is protected\n* Recognise the difference between personal and sensitive data\n* Gain an understanding of the key principles enshrined within the regulations\n* Understand of the roles and responsibilities of a Data Controller\n* Be aware of the roles and responsibilities of a Data Processor\n* Recognise ways that a care home can be compliant",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/Vl4sv6AgOUBQU3At0jMcs8yPpHU18IykYkSNfrW8.jpeg",
          },
          {
            id: "296",
            aims: "To understand the changes GDPR brings, and how to be compliant with the regulations",
            outcomes:
              "By the end of this course you will be able to:\n\n * Understand what GDPR is\n * Recognise its importance\n * Know who and what is protected\n * Recognise the difference between personal and sensitive data\n * Gain an understanding of the key principles enshrined within the regulations\n * Understand the roles and responsibilities of a Data Controller\n * Be aware of the roles and responsibilities of a Data Processor\n * Recognise ways that a care home can be compliant",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/YznEnzMpREr94pGbwEmYwVdJ7y5bIhrsyXurNgRG.png",
          },
          {
            id: "298",
            aims: "To apply the Mental Capacity Act Principles into the care you provide to those with a mental health condition or living with dementia",
            outcomes:
              "* Be up to date with current statistics surrounding mental capacity \n* Know what the MCA is, why it’s important and who it affects \n* Know how to identify someone with a lack of capacity \n* Be aware of the key legislations surrounding mental capacity \n* Know the boundaries involved when caring for someone with a lack of capacity \n* Recognise how to help individuals make informed choices \n* How to risk assess a person’s choices \n* Recognize what “best interests” are and how to use the checklist provided \n* Know the 5 core principles of MCA \n* Know how and when to assess capacity \n* Be aware of the two-stage functional test for capacity \n* Be familiar with the standard authorisation process \n* Understand how to restrict and restrain in a person’s best interest \n* Know how to write care plans for individuals that lack capacity",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/8ezziPCFC6jpIjW5EiU9Q0bCnhHuVEb4kSr3icjC.jpeg",
          },
          {
            id: "300",
            aims: "To apply the Adults with Incapacity Act Principles into the care you provide to those with a mental health condition or living with dementia",
            outcomes:
              "* Be aware of the key facts and statistics surrounding mental capacity \n* Know what the AWI is, why it’s important and who it affects \n* Know how to identify someone with a lack of capacity \n* Be aware of the key legislations surrounding mental capacity \n* Know the boundaries involved when caring for someone with a lack of capacity \n* Recognise how to help individuals make informed choices \n* How to risk assess a person’s choices  \n* Know the 5 Key Principles of AWI Act \n* Know how and when to assess capacity \n* Recognise your responsibility when caring for those lacking capacity",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/EV7hxRGwgqr5vKz5uqfmWTeL84NjJjlZ4Y6KNP3e.jpeg",
          },
          {
            id: "303",
            aims: "To understand the role of the IDDSI framework and implement it in caring for those in need",
            outcomes:
              "- Know what dysphagia is, its causes, and its symptoms. \n- Be aware of the origins and use of the IDDSI Framework \n- Recognise the different levels of the IDDSI Framework, and their identifying characteristics \n- Understand how oral medication can affect IDDSI levels \n- Know how to use thickening agents to alter the consistency of food and drink \n- Understand how to undertake the Drinks Flow Test \n- Know how to undertake the food tests for IDDSI \n- Know the first aid steps to take in the event of someone choking \n- Be aware of the roles and responsibilities of work colleagues \n- Know how to support people with dysphagia at mealtimes \n- Be aware of the resources available to support your knowledge of IDDSI",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/k2sAlZAhAGkrkALhJ4QAFyIjd1k6KE1fLwagAmZx.jpeg",
          },
          {
            id: "314",
            aims: "By the end of the course you will be able to support residents with their nutrition and hydration",
            outcomes:
              "* Recognise the importance of good nutrition and hydration\n* Know the latest facts and statistics surrounding nutrition & hydration\n* Recognise the signs and symptoms of malnutrition\n* Be aware of the causes of malnutrition\n* Know how to calculate someone's BMI\n* Know why you would need someone's MUST score\n* Understand the 5 MUST steps to establish the correct Action Plan\n* Be familiar with the 5 food groups\n* Understand the philosophy behind the Eatwell Guide\n* Be familiar with foods that should be avoided\n* Recognise signs and symptoms of dehydration\n* Be aware of strategies to maintain hydration\n* Recognise common conditions that could affect nutrition\n* Know your own and your employers responsibilities",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/rdkrM5qfnTAWGtTIjBFwI8HqSf0xdLnHHcjPgZk1.png",
          },
          {
            id: "362",
            aims: "To gain an understanding of the types of Mental Illnesses that may affect Residents and how best to support them.",
            outcomes:
              "By the end of this course you will:\n\n * Be aware of the history of mental health treatment in the UK\n * Recognise the stigma surrounding mental health\n * Understand how mental health impacts the care sector\n * Recognise the key legislation underpinning the treatment of mental illness\n * Be aware of the causes of mental health conditions\n * Be aware of the different ways mental illness can manifest\n * Know symptoms of some mental health illnesses\n * Be aware of the different types of personality disorders\n * Recognise the symptoms of psychosis and schizophrenia\n * Know how psychosis and schizophrenia are treated\n * Understand the difference between learning difficulties and learning disabilities\n * Recognise the impact of stress on wellbeing and mental health\n * Know ways to look after your mental health\n * Know the Roles and Responsibilities of staff in care homes\n * Know of different resources and organisations available to support those with mental health issues",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/tmSGM3NgPqknAPfWFKwIldW15S5sCLEb3PGcgzCr.png",
          },
          {
            id: "425",
            aims: "Whilst caring for those with Diabetes, be able to identify the symptoms that could suggest a problem.",
            outcomes:
              "By the end of this course you will be able to:\n\n* Understand what Diabetes is\n* Know the difference between Type 1 and Type 2\n* Be aware of other Types of Diabetes\n* Recognise the Symptoms\n* Know the importance for good foot care for anyone with diabetes\n* Be aware of the health care checks available to those with diabetes\n* Know what Hypoglycaemia is\n* Know the best diet for someone managing diabetes",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/qgF5uiphcUlfoITwpal1QHqKoLpuzeyeCMY37w5b.png",
          },
          {
            id: "427",
            aims: "To be able to provide effective oral care for Residents.",
            outcomes:
              "By the end of this course you will be able to:\n\n * Recognise the impact of poor oral health care\n * Be aware of the statistics of oral care in care homes\n * Understand the roles and responsibilities of all colleagues regarding oral health\n * Recognise the importance of the mouth and teeth\n * Be aware of the anatomy of the mouth and teeth\n * Recognise common mouth problems and how they are treated\n * Know how to support Residents with their oral hygiene\n * Know of correct methods for cleaning teeth\n * Understand how certain medical conditions can complicate oral hygiene\n * Recognise the importance of well-fitting dentures\n * Understand how to support Residents with their dentures",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/1gfSvDDF7SDnaWGvWdCuKG8jCwTDGDrxXusuK00Z.png",
          },
          {
            id: "428",
            aims: "Whilst providing care, to be able to communicate with residents and colleagues ensuring that information is communicated effectively.",
            outcomes:
              "By the end of this course you will:\n\n * Understand what Communication is\n * Understand the barriers of communication and how to break them down\n * Be aware of the impact communication has on those you are caring for\n * Know of different ways to communicate\n * Know when to use the different types of communication\n * Understand that listening is an important type of communication\n * Understand the importance of checking and clarifying information\n * Be aware of the differences in formal and informal communication\n * Know how to write a good report\n * Apply the rules surrounding information sharing\n * Know the exceptions to these rules\n * Be aware of the types of documents that hold confidential data",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/8IdDKAZawN59eJMhel2Go46OABymGge4ehGIPUkL.png",
          },
          {
            id: "429",
            aims: "To provide care whilst protecting the data of anyone you come into contact with and ensure that patient data is only shared in accordance with the Seven Caldicott Principles.",
            outcomes:
              "By the end of this course you will:\n\n* Know what Information Governance is\n* Know who and what is protected\n* Recognise the difference between personal and sensitive data\n* Understand the Caldicott Principles\n* Understand of the roles and responsibilities of all Data Controllers\n* Be aware of ways to manage and secure data\n* Know when your duty to confidentiality can be overridden",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/92YiyKjote1LussIXKohfURGInvJZLnYrVKbVmLi.png",
          },
          {
            id: "430",
            aims: "To understand the differences between positive and negative stress, how to deal with stress in the workplace and to be aware of how stress affects you and those around you.",
            outcomes:
              "By the end of this course you will:\n\n * Know what Stress is\n * Be aware what the signs of Stress are\n * Understand the differences between Work Stress and Personal Stress\n * Be aware of what can cause Work Stress\n * Recognise bullying in the workplace\n * Know how to look after yourself and manage your own Stress\n * Understand your roles and responsibilities\n * Be aware of the manager's roles and responsibilities",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/Cc43A5M4s2rh0KvIai0xxwkWVFVQaU5yXHaQmywS.png",
          },
          {
            id: "435",
            aims: "To be able to provide further effective care to those with Diabetes.",
            outcomes:
              "By the end of this course you will be able to:\n\n * Be aware of the different forms of insulin, and their effects\n * Understand how to monitor blood glucose levels\n * Be aware of the different types of Diabetes testing methods",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/QOZLMYpaG5cEfr8RXOdjhVniH9VlTNjKndOAPIS7.png",
          },
          {
            id: "437",
            aims: "To be able to work with children in either an authoritative or educational capacity, keeping them safe from abuse. To also be able to identify any abuses taking place and to know the appropriate action to take.",
            outcomes:
              "By the end of this course you will be able to:\n\n * Know what safeguarding and child protection is\n * Understand who safeguarding is aimed at and who is responsible for it\n * Be aware of who abusers are\n * Be aware of various legislation surrounding safeguarding and child protection\n * Know what risk factors and protective factors are\n * Be aware of some of the indicators of child abuse\n * Know the different types of abuse\n * Understand how to report abuse\n * Be aware of how to disclose information regarding child abuse\n * Be aware of why people don’t always report abuse\n * Know about the ‘Every Child Matters’ policy",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/e3ps5YS2ZkevrP1dvl6nI4U21KdElvwB60aErRfe.png",
          },
          {
            id: "438",
            aims: "To give an understanding of Basic Life Support to allow a person to act to save a life",
            outcomes:
              "By the end of this course you will:\n\n \n* Understand what is meant by Basic Life Support\n* Know the theory supporting how to perform CPR on adults, children and infants\n* Understand the importance of rescue breaths\n* Know how to conduct a Primary Survey\n* Recognise ways to deal with breathing casualties\n* Know how to put a casualty into the Recovery Position\n* Be able to identify ways to deal with a choking casualty\n* Be aware of how to perform back blows and chest thrusts on adults, children and infants",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/XFqw5W6khOT61UIZAYa9KZ8FNcwMiD4noO18DQzN.png",
          },
          {
            id: "441",
            aims: "To be able to work with children and young people and recognise the signs that they may be a victim of Grooming or Child Sexual Exploitation.",
            outcomes:
              "By the end of this course you will:\n\n* Know what Child Sexual Exploitation, Grooming and Trafficking are\n* Be aware of legislation surrounding Child Sexual Exploitation\n* Be aware of how grooming works\n* Understand how children may be sexually exploited\n* Be able to state the effects of Child Sexual Exploitation\n* Understand what safeguarding is\n* Understanding what to do in the event of disclosure\n* Know some suitable organisation that can offer support",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/kA5gqVeHFnlSSyKP88HQK5fkokxs3cmbtS33XpJQ.png",
          },
          {
            id: "443",
            aims: "To know how to safely carry out manual handling tasks putting safety first for you and others",
            outcomes:
              "By the end of this course you will:\n\n * Know what manual handling is\n * Know the relevant legislation around manual handling\n * Be aware of both employees and employers’ responsibilities\n * Know of the basic anatomy and function of the spine\n * Be familiar with common back problems\n * Understand ergonomics and fitting the task to the person\n * Know the correct manual handling techniques for lifting, pulling and pushing\n * Know how to ask somebody to perform a lift",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/7FT27FzJljBnbGgdgRtSjoeBgb4zAqVr5vISPFxK.png",
          },
          {
            id: "461",
            aims: "To be able to manoeuvre people safely using equipment where appropriate",
            outcomes:
              "By the end of this course you will have been updated on the following:\n\n * Be aware of health issues that may necessitate support\n * Be aware of the need to follow good infection control procedures\n * Understand how to manoeuvre residents with dignity\n * Know the importance of promoting independence\n * Recognise the need for clear communication\n * Know techniques used for assisted walking\n * Know techniques for moving a person from sitting to standing\n * Recognise the signs that a person might be falling\n * Be aware of some ways to deal with a falling person\n * Be aware of reasons why a person may need moving in bed\n * Know how to move a person in bed\n * Know how to apply a slide sheet\n * Understand the safety checks to be performed before hoisting\n * Know how to use a hoist and sling\n * Understand how to manoeuvre people safely using a hoist\n * Understand roles and responsibilities",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/BgxiaoiBNvqbwdd6Cq99GYgUxsuNDo5ACa6fXlqU.png",
          },
          {
            id: "517",
            aims: "To refresh the knowledge to those who provide Medication Administration in Care environments",
            outcomes:
              "By the end of this course you will have been updated on the following:\n\n- How Medication passes through the body\n- How the effectiveness of Medication can be altered\n- Precautions for Covert Medication Administration\n- How Medication Administration Records are used\n- Procedures relating to the ordering, auditing and storage of Medication\n- Post-administration observations\n- The 10Rs of Medication Administration\n- How to prepare for a Medication round\n- Procedures relating to a Person being away from their usual Care setting\n- How to safely dispose of Medication\n- Denaturing of Medication\n- Typical Medication Administration Errors and how to avoid them \n- A Medication Administrator’s Responsibilities",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/RKK58kpmVG6YwYveUmEW9mKtPA1mmStxxzJo2Oag.png",
          },
          {
            id: "590",
            aims: "To refresh the awareness of all staff, who work within an environment where medication is being managed, on the importance of the risks associated with Medication",
            outcomes:
              "By the end of this course you will have been updated on the following:\n\n * How drugs are defined in medical practice\n * The importance of competency\n * Legislation underpinning medication administration\n * The common types and forms of medication\n * The different routes of administering medication\n * Drugs which are controlled by law\n * How medication passes through the body\n * How to correctly store controlled drugs\n * That medication can have side effects\n * The ways that drugs can interact with other factors\n * That some people can find it difficult to take medication\n * Your responsibilities and the responsibilities of others in your workplace regarding medication administration",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/3XrobFZmx6QcW4mGVRboC6clQO953mh7YCQdsiK6.png",
          },
          {
            id: "678",
            aims: "To be able to meet the specific needs of everyone by providing care centred around the individual",
            outcomes:
              "By the end of this course you will:\n- Understand what is meant by Person-Centred Care\n- Know what values are\n- Know the 6C's of care\n- Understand the main Person-Centred Care principles\n- Know the difference between Person-Centred Care and Institutional Care\n- Recognise factors that may cause distress\n- Be aware of the Care Planning process\n- Know your responsibilities for providing Person-Centred Care",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/ELocaKsB3RMyxNwoJYRnuiTyGjjfYSaeRp2nw8gx.png",
          },
          {
            id: "701",
            aims: "To know how to manage effectively to promote a caring workplace.",
            outcomes:
              "By the end of this course you will:\n\n- Understand the skills required to be an effective manager\n- Recognise the importance of resilience\n- Know some of the key aspects of a manager’s role\n- Know the main responsibilities of managers\n- Understand what makes a good leader\n- Know the difference between supervisions and appraisals\n- Be able to plan supervisions and appraisals",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/hFnjEWw8MTZOVJ2Y89Oxx3gE1R7KQDYEmTCfzJ3s.png",
          },
          {
            id: "721",
            aims: "To be able to provide effective care for those living with Dementia",
            outcomes:
              "By the end of this course you will:\n\n- Recognise the common symptoms of Dementia\n- Know some relevant legislation protecting those living with Dementia\n- Understand the areas of the brain affected by Dementia\n- Understand the common causes of Dementia\n- Recognise the different stages of Dementia \n- Understand Behaviours of Concern and how to meet a Person’s needs\n- Recognise the importance of caring for and supporting those with Dementia",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/nLSSMpi6LB8m1pOFZlboVePUcqhbj7DiBvDuy71t.png",
          },
          {
            id: "791",
            aims: "To have an understanding of your role within the Care Sector",
            outcomes:
              "* Know your main duties and responsibilities and who to report to\n* Learn what is expected of you but also what is not included in your role\n* Know the safe and agreed ways in which you are expected to work\n* Ensure you are providing care and support which meets the needs of the individual\n* Learn the main working relationships in Health and Social Care\n* Ensure that you are working within the laws and regulations\n* Learn what partnership working is\n* Know who to ask for advice about partnership working and resolving conflict whenever you face a problem",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/r542mLBSed1aIZrEyrAnFdzwTPqGuun24PvNSzVU.png",
          },
          {
            id: "793",
            aims: "To be able to manage a Person's Bed Falls Management needs",
            outcomes:
              "- Understand what Bed Falls Management is\n- Recognise pressure from Families to use Bed Rails\n- Know what the Bed Falls Management Options are\n- Recognise the specific considerations for each Person\n- Understand that the use of Bed Rails is a last resort\n- Recognise the types of incidents associated with Bed Rails\n- Understand the steps included in risk assessments\n- Know the different types of paperwork used when managing Bed Falls Management",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/5Y9yILgEdJKWvI6GltzXSuYUCr80H8KfbT6HAZwj.png",
          },
          {
            id: "794",
            aims: "Know how to develop your skills and understanding, through different learning styles and continual learning",
            outcomes:
              "* Understand what a Personal Development Plan is\n* Recognise what happens at Supervisions and Appraisals and the differences between them\n* Be aware of Core Skills you may need in your profession\n* Know where you can find places to develop your Core Skills\n* Know where you can find places to develop your Core Skills\n* Recognise the differences between Blended and Structured Learning\n* Be aware of how to reflect upon previous experiences and actions\n* Understand what the Care Certificate is\n* Be aware of CPD and how to develop your skills and understanding",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/ZQ4UjGII03YU9o9Yx6cuWIg2dwloTYxfWAOe3FCf.png",
          },
          {
            id: "844",
            aims: "To be able to recognise the need to be honest and apologise when working within care",
            outcomes:
              "By the end of this course you will:\n\n* Understand what Duty of Candour means\n* Recognise when Duty of Candour needs to be used\n* Be aware of some examples of incidents where Duty of Candour applies\n* Know how to implement Duty of Candour within a care environment",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/ba5R8dIc87OGFzf379VU4J3wXkKBs0o8qvsa5JLH.png",
          },
          {
            id: "863",
            aims: "To be able to provide care and support to people living with a Learning Disability.",
            outcomes:
              "* Know what a Learning Disability is\n* Understand the difference between Learning Disabilities and Learning Difficulties\n* Know the different levels of Learning Disability\n* Recognise some conditions linked to Learning Disabilities\n* Know what is meant by a Behaviour of Concern\n* Recognise some common reasons for Behaviour of Concern\n* Know ways to deal with Behaviour of Concern\n* Recognise the need for good communication\n* Be aware of some alternative communication methods",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/zREAHXHXx4MRo5NciyMk1ndqzik5qoQAd9qg2i2j.png",
          },
          {
            id: "1372",
            aims: "To understand the reasons for change with regards to autism training.",
            outcomes:
              "- Be aware that the terminology and language relating to autism is changing\n- Know that autism training is mandatory for all healthcare workers\n- Be aware of legislation in place to protect autistic people and those caring for them",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/HPdjaXu6JWFgYI52pbA65m31IZtIPOon1OHQDhdQ.png",
          },
          {
            id: "1466",
            aims: null,
            outcomes: null,
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/EIMrVRh4hmbe55sYn0PRhHznBCXInCGVBlJGviPq.png",
          },
          {
            id: "10104",
            aims: "To be able to recognise autistic traits in a person, meet their communication needs and understand when and how to implement adjustments in a Person-Centred way.",
            outcomes:
              "- Recognise that Autism is a type of neurodiversity\n- Know that Autism is a spectrum disorder\n- Understand that some autistic people will also be diagnosed with other neurodivergent disorders\n- Be aware of the history of Autism\n- Recognise that autistic people have strengths and abilities\n- Know that some people have misconceptions relating to Autism\n- Understand that every autistic person's spectrum is unique\n- Know the three areas of difference\n- Understand that autistic people face challenges with social communication, interaction and imagination\n- Know that autistic people will have repetitive, restrictive and self-regulating behaviours\n- Recognise that autistic people will have differences in sensory processing\n- Understand that an autistic person's senses may get overloaded\n- Know that alternative methods of communication may be necessary to meet an autistic person's needs\n- Be aware of signs that may indicate that a child is autistic\n- Recognise the importance of an adult getting an autism diagnosis\n- Know ways to support an autistic person and their family",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/qDUzkuYZS8Tu9hblSB37Hc8gNgK5lKnkN7CfRQBK.png",
          },
          {
            id: "11862",
            aims: "To understand responsibilities and protocol regarding COSHH",
            outcomes:
              "By the end of this course you will:\n-\tKnow what is meant by hazardous substances\n-\tKnow how to store hazardous substances\n-   Recognise the danger symbols\n-\tBe aware of Material Safety Data Sheets\n-   Know employer responsibilities\n-   Know employee responsibilities",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/HXcaInlizUhvH7RqcwkcTNFdQZqsLqi9NSokDKG3.png",
          },
          {
            id: "12093",
            aims: "To understand and recognise the different types of meaningful engagement, and when they can be used.",
            outcomes:
              "- Understand what Meaningful Engagement is\n- Know the Four Types of Meaningful Engagement\n- Be aware of the 'Token Initiative' and how to use this during Productive Engagement\n- Understand why Meaningful Engagement is important, including Well-being and Having Purpose\n- Know how to implement Productive Engagement, Fun and Entertainment, Personal Care and Rest and Downtime\n- Understand that Meaningful Engagement should be inclusive and accessible to everyone\n- Know the Three Opportunities to Engage\n- Understand what Person-centred Engagement is\n- Be aware of the questions you could ask a person when using Person-centred Engagement\n- Understand the importance of Person-centred Engagement\n- Be aware of the clues you should look for in a person when using Person-centred Engagement\n- Know how, and where, to evidence Meaningful Engagement\n- Understand the positive impact Meaningful Engagement can have on people in the Care Home",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/6JOqceZN82rGnshrOHak1MPbajkYBl8urldmrHxq.png",
          },
          {
            id: "12307",
            aims: "To be able to work with children in either an authoritative or educational capacity, keeping them safe from abuse. To also be able to identify any abuses taking place and to know the appropriate action to take.",
            outcomes:
              "By the end of this course you will be able to:\n\n- Know what safeguarding and child protection is\n- Understand who safeguarding is aimed at and who is responsible for it\n- Be aware of who abusers are\n- Be aware of various legislation surrounding safeguarding and child protection\n- Know what risk factors and protective factors are\n- Be aware of some of the indicators of child abuse\n- Know the different types of abuse\n- Understand how to report abuse\n- Be aware of how to disclose information regarding child abuse\n- Be aware of why people don’t always report abuse\n- Know about the ‘Every Child Matters’ policy",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/tgRaPDT3ZhQeeIo5AJfJpSIzMSfCuryelkehZSoJ.png",
          },
          {
            id: "12466",
            aims: "To be able to identify and de-escalate behaviour of concern safely and effectively using positive behaviour support techniques.",
            outcomes:
              "By the end of this course, you will:\n\n-\tUnderstand what Positive Behaviour Support is.\n-\tUnderstand what a Behaviour of Concern is.\n-\tBe able to recognise the different types of Behaviour of Concern.\n-\tBe able to identify common triggers.\n-\tBe able to identify causes and underlying factors.\n-\tUnderstand the difference between common triggers and causes.\n-\tBe able to identify signs of escalation.\n-\tKnow how to assess a situation that may lead to a Behaviour of Concern.\n-\tUnderstand the importance of de-escalating yourself and how this can be done.\n-\tUnderstand what is meant by Positive de-escalation.\n-\tKnow where to find distraction techniques and when it is appropriate to use them.\n-\tBe able to read body language.\n-\tUnderstand how to use your listening skills.\n-\tUnderstand the importance and what is required in a handover.",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/p8z70Blvl83qSeqHxQHXqNBHJ8aVDAja2I6cj14K.png",
          },
          {
            id: "13230",
            aims: "To be able to provide person-centred palliative care in accordance with The Five Priorities for Care of the Dying to those who are nearing the end of their lives",
            outcomes:
              "By the end of this course, you will:\n\n- Understand what Palliative Care is\n- Understand what End of Life Care is\n- Be able to recognise the different Phases of End of Life\n- Understand the Five Priorities for Care of the Dying\n- Know the different types of observations\n- Know the different reasons for pain and discomfort\n- Be able to recognise and assess pain\n- Be aware of the different types of pain management\n- Understand the importance of holistic care",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/3wlnM0DiuHZ5d6fJy6jejC1yE72RBfWKiNSOkJRW.png",
          },
          {
            id: "13702",
            aims: "To be able to recognise and deal with a bed bug infestation which includes ensuring that the relevant controlled measures are in place.",
            outcomes:
              "By the end of this course you will be able to:\n- Know what a bed bug is a what they look like\n- Be aware of the signs that bed bugs are present\n- Know who to contact if there is a bed bug infestation\n- Understand the controlled measures that need to be in place if there is an infestation",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/P4Ph6GyWl99bDjGz3HY6FTKRG7diLBxV0QR4lhRK.png",
          },
          {
            id: "14316",
            aims: "Know how to avoid contamination, prevent the spread and, shouuld the worst happen, how to recognise the symptoms and know what to do if you suspect an outbreak.",
            outcomes:
              "- Understand what Legionnaires' Disease is\n- Know where legionella can be found\n- Be aware of who is at higher risk of becoming seriously ill\n- Know how to recognise the signs and symptoms of Legionnaires' Disease\n- Understand how Legionnaires' Disease is diagnosed\n- Know your personal responsibilities within the Care Home\n- Be aware of how Legionnaires' Disease is treated\n- Know the correct procedure of reporting any diagnosis\n- Be aware of your Home's competent person/s' responsibilities\n- Understand the correct methods to check water temperatures\n- Be aware of what water temperatures are safe\n- Know how the risk of legionella should be managed\n- Be aware of the importance of keeping all records and documentation up to date",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/Vz9hNkJHhG5XOjhMgbtlcqHFUMgU8nC0IHYPuaME.png",
          },
          {
            id: "14654",
            aims: "To be able to provide person-centred and dignified care to those living with Epilepsy.",
            outcomes:
              "- Know what Epilepsy is\n\n- Recognise triggers\n\n- Be aware of the new Classifications of seizures\n\n- Be aware of the different symptoms for each type of seizure\n\n- Know what to do when someone is having a seizure\n\n- Implement steps to maintain a person's dignity during a seizure\n\n- Recognise when a seizure becomes an emergency\n\n- Be aware of the different treatments and medication available\n\n- Know the importance of information held in an Epilepsy Care Plan\n\n- Know the type of information that needs to be recorded in an Epilepsy Care Plan\n\n- Understand what everyday life is like for those living with Epilepsy",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/cbCNxYSJHBzw7BkVWKbObz4E1ALNJ4vrKeKqD8N6.png",
          },
          {
            id: "14856",
            aims: "To be able to provide person-centred and dignified care, regarding administering Epilepsy Medication, to those living with Epilepsy.",
            outcomes:
              "- Be aware of different Anti-Seizure Medications available and their use.\n- Know what Vagus Nerve Stimulation Therapy is.\n- Be aware of the different Epileptic Surgeries available.\n- Understand what Emergency Medication is.\n- Know how to become competent in giving Emergency Medication.\n- Recognise when a Seizure becomes an emergency.\n- Know when to administer Emergency Medication.\n- Be aware of the different ways Buccal Midazolam is available.\n- Know how to prepare to administer Buccal Midazolam.\n- Understand and be able to implement the Buccal Midazolam procedure.\n- Recognise common side effects of receiving Buccal Midazolam.\n- Know the importance of information held in an Epilepsy Care Plan.\n- Know the type of information that needs to be recorded in an Epilepsy Care Plan.",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/E3IMzIXlhNbWkVaiqbn3bOivMPPfRFtRpC1PM7G9.png",
          },
          {
            id: "15067",
            aims: "Identify and prevent pressure damage in children with complex needs",
            outcomes:
              "- What is pressure damage?\n- What are the risk factors?\n- Preventing pressure damage using KITENS:\n- Keep moving\n- Incontinence and moisture\n- Top to toe skin inspection\n- Equipment and medical devices\n- Nutrition and hydration\n- Seek advice",
            image: null,
          },
          {
            id: "15850",
            aims: null,
            outcomes: null,
            image: null,
          },
          {
            id: "16266",
            aims: null,
            outcomes: null,
            image: null,
          },
        ],
      },
      {
        aims: "Gain an understanding of all mandatory and other care related courses. These subjects will be available for you to run for 12 months as many times as you like.",
        outcomes:
          "### By the end of these courses you will understand these subjects from the Mandatory Course Bundle:\n\n- Basic Life Support Theory\n- Communication in care\n- Coronavirus\n- Duty of Care\n- Fire Safety\n- Food Safety\n- GDPR and Data Protection\n- Infection Control\n- Manual Handling Theory\n- MCA & DoLS\n- Nutrition & Hydration\n- Person Centred Care\n- Safeguarding Adults\n- Safer People Handling Theory\n\n### Plus all our additional care related courses, for instance:\n\n- Adult Support & Protection\n- Adults with Incapacity\n- Anaphylaxis\n- Child Sexual Exploitation\n- Diabetes Advanced Care\n- Diabetes Awareness\n- Duty of Candour\n- Equality & Diversity\n- Health & Safety INC. COSHH\n- IDDSI and Dysphagia\n- Medication Awareness\n- Oral Health\n- PPE in Care Homes\n- PPE in Home Care\n- PPE in Hospitals\n- Privacy & Dignity\n- Safeguarding Children\n- Stress at Work",
        id: "2",
        image:
          "https://tafara.elearninghippo.com/wp-content/uploads/sites/42/2020/10/Gold-Bundle-wpv_700x391_right_bottom.png",
        title: "Gold Course Bundle for Care Staff",
        detail: {
          price: "50",
          discounted_price: null,
          promo_video_link: null,
        },
        content: [
          {
            id: "79",
            aims: "To be able to care for adults at risk, keeping them safe from abuse.",
            outcomes:
              "* Understand who needs safeguarding \n* Know who an adult at risk is \n* Know whose responsibility it is to safeguard \n* Understand risk factors for abuse \n* Know the relevant legislation\n* Be aware of all the different types of abuse \n* Recognise signs of abuse \n* Recognise a potential abuser \n- Understand disclosure and whistle-blowing procedures",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/l8d4guenJrHyj9bWy2ETpvyu7MzPEUON3avaj6CD.jpeg",
          },
          {
            id: "86",
            aims: "To recognise and appreciate the differences of the people we care for and provide care that is fair and gives equal opportunity to everyone.",
            outcomes:
              "By the end of this course you will:\n\n * Know the responsibilities of employees and employers\n * Know what beliefs, values, and attitudes are\n * Understand what is meant by equality, diversity, inclusion and discrimination\n * Know the legislation in place covering Equality & Diversity\n * Know each of the protected characteristics\n * Understand the different forms of discrimination, and how they can occur",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/UaZjiIrv4bAQ13fEOyubnvJwEXM6oOMs4Kr6k7AV.jpeg",
          },
          {
            id: "100",
            aims: "To understand your obligations to Duty of Care",
            outcomes:
              "By the end of this course you will:\n\n * Know what your duty of care is and with who\n * Understand the definitions used in Duty of Care\n * Know which legislations relate to Duty of Care and why\n * Be aware of your responsibilities and your employers\n * Understand the importance of an individual’s right to live independently whist keeping them safe from harm\n * Know how to deal with comments and complaints\n * Understand that mistakes happen and follow procedure to prevent further mistakes\n * Recognise why conflict happens and how to deal with the individual and situation",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/Fvj26gFgLdWkYLd3y84zp9bGNIrV9EIPGNurjEMS.jpeg",
          },
          {
            id: "102",
            aims: "To be able to care for adults at risk, keeping them safe from abuse",
            outcomes:
              "By the end of this course you will:\n\n * Understand which adults need support and protection\n * Know who an adult at risk is\n * Know whose responsibility it is to support and protect vulnerable adults\n * Understand risk factors for abuse\n * Know the relevant legislation\n * Be aware of all the different types of abuse\n * Recognise signs of abuse\n * Recognise a potential abuser\n * Understand disclosure and whistleblowing procedure",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/yZmPaqnD3rbw018T5KPy8Y0UPYzGgmEDW1t6jY87.jpeg",
          },
          {
            id: "158",
            aims: "To understand responsibilities and protocols regarding Health and Safety.",
            outcomes:
              "By the end of this course you will:\n\n* Understand what Health and Safety means.\n* Know your responsibilities and those of your employer.\n* Understand the relevant Health and Safety legislations.\n* Be aware of tasks that will require special training.\n* Be aware of common accidents and sudden illnesses.\n* Know what to do in an emergency.\n* Understand how to create a Risk Assessment.\n* Understand methods of working safely with hazardous materials\n* Know methods and procedures to prevent fires.\n* Recognise the symptoms, causes and treatment for work related stress.",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/3KSDjCS6wDFZUNxwqeoQ60MCIPZV2ukLl0Mh3k4B.png",
          },
          {
            id: "249",
            aims: "To care for people whilst respecting privacy, promoting choice and maintaining dignity",
            outcomes:
              "* Understand what Privacy & Dignity mean in a healthcare setting \n* Be aware of the importance of person-centred dignity \n* Recognise the importance of maintaining dignity for someone living with dementia \n* Understand the importance of a resident’s personal space \n* Know how to gain trust and confidence by maintaining confidentiality \n* Understand your responsibilities regarding safeguarding, and when it's OK to break confidence \n* Understand the factors that shape personal choices \n* Be aware of the importance of mental capacity within a care setting \n* Know how to help residents maintain independence and make informed choices \n* Know how to conduct a risk assessment\n* Understand the importance of making sure that residents are active participants in their care \n* Know the key principles of self-care",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/tR2ZJfKTfKQZgjO9lNGbuquRO21bEf25akfFVvYN.jpeg",
          },
          {
            id: "252",
            aims: "To be able to contain and control infections effectively within Care Home Settings",
            outcomes:
              "* Understand the different kinds of pathogen \n* Be aware of how pathogens spread through the chain of infection \n* Know how outbreaks are problematic within a care home environment \n* Recognise the symptoms, controls and treatment regarding the common infections within care homes \n* Be aware of the legislations in place regarding controlling infections \n* Know the roles and responsibilities of employers and care staff \n* Understand the protocols in place with an outbreak occurs \n* Recognise the procedures that must be undertaken when admitting a new resident \n* Know how to undertake a deep clean \n* Recognise good hand hygiene habits \n* Know the steps to take to effectively wash hands \n* Understand the importance and use of PPE \n* Be aware of the best practice regarding Barrier Nursing \n* Know how to handle contaminated and dangerous materials \n* Explore the possible outcomes of poorly controlled infections",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/0dyy495svSA96eRNaU7zr5GDi1HZy8dWvVPwUh0k.png",
          },
          {
            id: "267",
            aims: "To understand responsibilities and protocols regarding Fire Safety",
            outcomes:
              "* Understand what is meant by Fire Safety \n* Recognise the common causes of fire \n* Be aware of the legislation surrounding Fire Safety \n* Understand methods of preventing fires \n* Recognise the importance of PAT testing \n* Know how to keep electrical items safe to use \n* Identify fire risks and hazards \n* Know how to undertake a Fire Risk Assessments \n* Understand how to create and implement a Personal Emergency Evacuation Plan \n* Recognise the importance of reporting fire risks \n* Understand how fire safety equipment operates \n* Know how to respond to a fire \n* Understand the roles and responsibilities of Fire Marshals \n* Know how to implement Full and Zonal Evacuations \n* Recognise the importance of Fire Drills \n* Recognise the consequences of poor fire safety \n* Know your responsibilities and those of your employer",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/b7QhFpKs8UN7JuZbVZgUy9uIGK3hPODVyKeu7U4w.jpeg",
          },
          {
            id: "272",
            aims: "To be able to recognise and treat anaphylaxis",
            outcomes:
              "* Know what anaphylaxis is \n* Understand who can be at risk \n* Be aware of the legislation relating to allergies and anaphylaxis \n* Know of the common allergens that can trigger reactions \n* Recognise the symptoms of anaphylaxis \n* Know how to administer first aid to someone with anaphylaxis \n* Understand how adrenaline injectors work \n* Know how to use the most commonly used adrenaline injectors \n* Be aware of the roles and responsibilities surrounding anaphylaxis",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/E0c8GLkkVJnRoEDOMOPKrtgsBFvoCu3DCsamNA7A.jpeg",
          },
          {
            id: "287",
            aims: "To safely provide support in the kitchen during food preparation and food serving",
            outcomes:
              "By the end of this course you will:\n\n* Recognise the symptoms of food-borne illnesses\n* Be aware of who is at risk\n* Understand which foods are high-risk\n* Know the wider impact of food-borne illnesses\n* Be aware of the legislation underpinning food safety\n* Recognise hazards that can make food unsafe\n* Know what anaphylaxis is\n* Recognise common allergens\n* Be aware of ways to keep food safe from allergen cross contamination\n* Be aware of the different types of food pests\n* Know how to prevent pests\n* Recognise the signs of pests\n* Know how to keep food clean and uncontaminated\n* Understand how to wash hands effectively\n* Know the 'Danger Zone'\n* Understand how to store foods safely\n* Be aware of the roles and responsibilities",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/6kPaGAjWh3cAz3B76tlnHyUAyqxBOLIFW719dMGM.jpeg",
          },
          {
            id: "296",
            aims: "To understand the changes GDPR brings, and how to be compliant with the regulations",
            outcomes:
              "By the end of this course you will be able to:\n\n * Understand what GDPR is\n * Recognise its importance\n * Know who and what is protected\n * Recognise the difference between personal and sensitive data\n * Gain an understanding of the key principles enshrined within the regulations\n * Understand the roles and responsibilities of a Data Controller\n * Be aware of the roles and responsibilities of a Data Processor\n * Recognise ways that a care home can be compliant",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/YznEnzMpREr94pGbwEmYwVdJ7y5bIhrsyXurNgRG.png",
          },
          {
            id: "298",
            aims: "To apply the Mental Capacity Act Principles into the care you provide to those with a mental health condition or living with dementia",
            outcomes:
              "* Be up to date with current statistics surrounding mental capacity \n* Know what the MCA is, why it’s important and who it affects \n* Know how to identify someone with a lack of capacity \n* Be aware of the key legislations surrounding mental capacity \n* Know the boundaries involved when caring for someone with a lack of capacity \n* Recognise how to help individuals make informed choices \n* How to risk assess a person’s choices \n* Recognize what “best interests” are and how to use the checklist provided \n* Know the 5 core principles of MCA \n* Know how and when to assess capacity \n* Be aware of the two-stage functional test for capacity \n* Be familiar with the standard authorisation process \n* Understand how to restrict and restrain in a person’s best interest \n* Know how to write care plans for individuals that lack capacity",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/8ezziPCFC6jpIjW5EiU9Q0bCnhHuVEb4kSr3icjC.jpeg",
          },
          {
            id: "300",
            aims: "To apply the Adults with Incapacity Act Principles into the care you provide to those with a mental health condition or living with dementia",
            outcomes:
              "* Be aware of the key facts and statistics surrounding mental capacity \n* Know what the AWI is, why it’s important and who it affects \n* Know how to identify someone with a lack of capacity \n* Be aware of the key legislations surrounding mental capacity \n* Know the boundaries involved when caring for someone with a lack of capacity \n* Recognise how to help individuals make informed choices \n* How to risk assess a person’s choices  \n* Know the 5 Key Principles of AWI Act \n* Know how and when to assess capacity \n* Recognise your responsibility when caring for those lacking capacity",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/EV7hxRGwgqr5vKz5uqfmWTeL84NjJjlZ4Y6KNP3e.jpeg",
          },
          {
            id: "362",
            aims: "To gain an understanding of the types of Mental Illnesses that may affect Residents and how best to support them.",
            outcomes:
              "By the end of this course you will:\n\n * Be aware of the history of mental health treatment in the UK\n * Recognise the stigma surrounding mental health\n * Understand how mental health impacts the care sector\n * Recognise the key legislation underpinning the treatment of mental illness\n * Be aware of the causes of mental health conditions\n * Be aware of the different ways mental illness can manifest\n * Know symptoms of some mental health illnesses\n * Be aware of the different types of personality disorders\n * Recognise the symptoms of psychosis and schizophrenia\n * Know how psychosis and schizophrenia are treated\n * Understand the difference between learning difficulties and learning disabilities\n * Recognise the impact of stress on wellbeing and mental health\n * Know ways to look after your mental health\n * Know the Roles and Responsibilities of staff in care homes\n * Know of different resources and organisations available to support those with mental health issues",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/tmSGM3NgPqknAPfWFKwIldW15S5sCLEb3PGcgzCr.png",
          },
          {
            id: "428",
            aims: "Whilst providing care, to be able to communicate with residents and colleagues ensuring that information is communicated effectively.",
            outcomes:
              "By the end of this course you will:\n\n * Understand what Communication is\n * Understand the barriers of communication and how to break them down\n * Be aware of the impact communication has on those you are caring for\n * Know of different ways to communicate\n * Know when to use the different types of communication\n * Understand that listening is an important type of communication\n * Understand the importance of checking and clarifying information\n * Be aware of the differences in formal and informal communication\n * Know how to write a good report\n * Apply the rules surrounding information sharing\n * Know the exceptions to these rules\n * Be aware of the types of documents that hold confidential data",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/8IdDKAZawN59eJMhel2Go46OABymGge4ehGIPUkL.png",
          },
          {
            id: "438",
            aims: "To give an understanding of Basic Life Support to allow a person to act to save a life",
            outcomes:
              "By the end of this course you will:\n\n \n* Understand what is meant by Basic Life Support\n* Know the theory supporting how to perform CPR on adults, children and infants\n* Understand the importance of rescue breaths\n* Know how to conduct a Primary Survey\n* Recognise ways to deal with breathing casualties\n* Know how to put a casualty into the Recovery Position\n* Be able to identify ways to deal with a choking casualty\n* Be aware of how to perform back blows and chest thrusts on adults, children and infants",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/XFqw5W6khOT61UIZAYa9KZ8FNcwMiD4noO18DQzN.png",
          },
          {
            id: "461",
            aims: "To be able to manoeuvre people safely using equipment where appropriate",
            outcomes:
              "By the end of this course you will have been updated on the following:\n\n * Be aware of health issues that may necessitate support\n * Be aware of the need to follow good infection control procedures\n * Understand how to manoeuvre residents with dignity\n * Know the importance of promoting independence\n * Recognise the need for clear communication\n * Know techniques used for assisted walking\n * Know techniques for moving a person from sitting to standing\n * Recognise the signs that a person might be falling\n * Be aware of some ways to deal with a falling person\n * Be aware of reasons why a person may need moving in bed\n * Know how to move a person in bed\n * Know how to apply a slide sheet\n * Understand the safety checks to be performed before hoisting\n * Know how to use a hoist and sling\n * Understand how to manoeuvre people safely using a hoist\n * Understand roles and responsibilities",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/BgxiaoiBNvqbwdd6Cq99GYgUxsuNDo5ACa6fXlqU.png",
          },
          {
            id: "793",
            aims: "To be able to manage a Person's Bed Falls Management needs",
            outcomes:
              "- Understand what Bed Falls Management is\n- Recognise pressure from Families to use Bed Rails\n- Know what the Bed Falls Management Options are\n- Recognise the specific considerations for each Person\n- Understand that the use of Bed Rails is a last resort\n- Recognise the types of incidents associated with Bed Rails\n- Understand the steps included in risk assessments\n- Know the different types of paperwork used when managing Bed Falls Management",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/5Y9yILgEdJKWvI6GltzXSuYUCr80H8KfbT6HAZwj.png",
          },
        ],
      },
      {
        aims: "This bundle is a collection of the 'React To...' series of content provided by the NHS and Crocodile House. Upon completion of these courses, you will also recieve a certificate of completion through the YourHippo LMS",
        outcomes:
          "The courses included within this bundle are...\n* React To Deterioration\n* React to Dementia\n* React to Falls\n* React to Feet\n* React to Frailty\n* React to Home Rounds\n* React to Malnutrition and Dehydration\n* React to Moisture\n* React to Quality Improvement\n* React to Red\n* React to Infection",
        id: "3",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/Uw98cToUbMHbShvOJyeHg18fJJzPBEZVKl4Jh0Ft.png",
        title: "React To Bundle",
        detail: {
          price: "120",
          discounted_price: "75",
          promo_video_link: null,
        },
        content: [
          {
            id: "688",
            aims: null,
            outcomes: null,
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/ML9bxQAz7cDHqrUilFA7TMTzRvFMwdV5ShOFI9BB.png",
          },
          {
            id: "917",
            aims: null,
            outcomes:
              "The Aim of this course is for you to:\n\n- Understand what we mean by ‘frailty’ and how it might present\n- Understand why identifying frailty is important for all older people and how this is important in your working role\n- Understand the Clinical Frailty Scale (CFS) and feel confident to use it to identify levels of frailty\n- Be able to implement some appropriate interventions for the person you support and be aware of referral pathways into health and social care",
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/D8GuFhiYMeKpHpHwZQ7HEIi5bKUvSJ1w70LwLB7C.jpg",
          },
          {
            id: "1280",
            aims: null,
            outcomes: null,
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/iCVirifUy6EykqLfvPTnASYfuJNoPTia080H2DSy.jpg",
          },
          {
            id: "1434",
            aims: null,
            outcomes: null,
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/s48xSAaMkixHQpESyXoyFKzGNAtvwAvhI13ZlaKx.jpg",
          },
          {
            id: "1447",
            aims: null,
            outcomes: null,
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/ZCoK1GF24EXK96wk2QAdI5tOUYUJrdbbWbPVEETT.jpg",
          },
          {
            id: "1461",
            aims: null,
            outcomes: null,
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/oC2EyXsWYgNQNOc6oZMN3SdzAmrxULnC4oHOuOgV.jpg",
          },
          {
            id: "1462",
            aims: null,
            outcomes: null,
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/CHRaA8nNDjPq9AXdRXUOZt4esv8cKvyD85x6kFp4.jpg",
          },
          {
            id: "1463",
            aims: null,
            outcomes: null,
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/EdGn76pP6iWf6pky9czjM1NV7JYMz5dEjJsoY9te.jpg",
          },
          {
            id: "1464",
            aims: null,
            outcomes: null,
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/ikwCdu9l4ukcohwGG2ZeVVulr9OZJ08MlLI7OLOh.jpg",
          },
          {
            id: "10234",
            aims: null,
            outcomes: null,
            image:
              "https://ams3.digitaloceanspaces.com/lms-api/content-images/nRNxEacfPVoF8LbuuXCvX0odA4bMvNyXq38ZqrWS.png",
          },
          {
            id: "11537",
            aims: ".",
            outcomes: ".",
            image: null,
          },
        ],
      },
    ],
    content: [
      {
        id: "102",
        title: "Adult Support and Protection",
        aims: "To be able to care for adults at risk, keeping them safe from abuse",
        outcomes:
          "By the end of this course you will:\n\n * Understand which adults need support and protection\n * Know who an adult at risk is\n * Know whose responsibility it is to support and protect vulnerable adults\n * Understand risk factors for abuse\n * Know the relevant legislation\n * Be aware of all the different types of abuse\n * Recognise signs of abuse\n * Recognise a potential abuser\n * Understand disclosure and whistleblowing procedure",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/yZmPaqnD3rbw018T5KPy8Y0UPYzGgmEDW1t6jY87.jpeg",
        detail: {
          price: "12",
          discounted_price: "5",
          promo_video_link: "https://player.vimeo.com/video/319695041",
        },
      },
      {
        id: "300",
        title: "Adults with Incapacity",
        aims: "To apply the Adults with Incapacity Act Principles into the care you provide to those with a mental health condition or living with dementia",
        outcomes:
          "* Be aware of the key facts and statistics surrounding mental capacity \n* Know what the AWI is, why it’s important and who it affects \n* Know how to identify someone with a lack of capacity \n* Be aware of the key legislations surrounding mental capacity \n* Know the boundaries involved when caring for someone with a lack of capacity \n* Recognise how to help individuals make informed choices \n* How to risk assess a person’s choices  \n* Know the 5 Key Principles of AWI Act \n* Know how and when to assess capacity \n* Recognise your responsibility when caring for those lacking capacity",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/EV7hxRGwgqr5vKz5uqfmWTeL84NjJjlZ4Y6KNP3e.jpeg",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/319694980",
        },
      },
      {
        id: "272",
        title: "Anaphylaxis",
        aims: "To be able to recognise and treat anaphylaxis",
        outcomes:
          "* Know what anaphylaxis is \n* Understand who can be at risk \n* Be aware of the legislation relating to allergies and anaphylaxis \n* Know of the common allergens that can trigger reactions \n* Recognise the symptoms of anaphylaxis \n* Know how to administer first aid to someone with anaphylaxis \n* Understand how adrenaline injectors work \n* Know how to use the most commonly used adrenaline injectors \n* Be aware of the roles and responsibilities surrounding anaphylaxis",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/E0c8GLkkVJnRoEDOMOPKrtgsBFvoCu3DCsamNA7A.jpeg",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/319695115",
        },
      },
      {
        id: "1372",
        title: "Autism - Time for Change",
        aims: "To understand the reasons for change with regards to autism training.",
        outcomes:
          "- Be aware that the terminology and language relating to autism is changing\n- Know that autism training is mandatory for all healthcare workers\n- Be aware of legislation in place to protect autistic people and those caring for them",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/HPdjaXu6JWFgYI52pbA65m31IZtIPOon1OHQDhdQ.png",
        detail: {
          price: "null",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "10104",
        title: "Autism Awareness",
        aims: "To be able to recognise autistic traits in a person, meet their communication needs and understand when and how to implement adjustments in a Person-Centred way.",
        outcomes:
          "- Recognise that Autism is a type of neurodiversity\n- Know that Autism is a spectrum disorder\n- Understand that some autistic people will also be diagnosed with other neurodivergent disorders\n- Be aware of the history of Autism\n- Recognise that autistic people have strengths and abilities\n- Know that some people have misconceptions relating to Autism\n- Understand that every autistic person's spectrum is unique\n- Know the three areas of difference\n- Understand that autistic people face challenges with social communication, interaction and imagination\n- Know that autistic people will have repetitive, restrictive and self-regulating behaviours\n- Recognise that autistic people will have differences in sensory processing\n- Understand that an autistic person's senses may get overloaded\n- Know that alternative methods of communication may be necessary to meet an autistic person's needs\n- Be aware of signs that may indicate that a child is autistic\n- Recognise the importance of an adult getting an autism diagnosis\n- Know ways to support an autistic person and their family",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/qDUzkuYZS8Tu9hblSB37Hc8gNgK5lKnkN7CfRQBK.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "438",
        title: "Basic Life Support",
        aims: "To give an understanding of Basic Life Support to allow a person to act to save a life",
        outcomes:
          "By the end of this course you will:\n\n \n* Understand what is meant by Basic Life Support\n* Know the theory supporting how to perform CPR on adults, children and infants\n* Understand the importance of rescue breaths\n* Know how to conduct a Primary Survey\n* Recognise ways to deal with breathing casualties\n* Know how to put a casualty into the Recovery Position\n* Be able to identify ways to deal with a choking casualty\n* Be aware of how to perform back blows and chest thrusts on adults, children and infants",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/XFqw5W6khOT61UIZAYa9KZ8FNcwMiD4noO18DQzN.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/428047419",
        },
      },
      {
        id: "13702",
        title: "Bed Bug Awareness",
        aims: "To be able to recognise and deal with a bed bug infestation which includes ensuring that the relevant controlled measures are in place.",
        outcomes:
          "By the end of this course you will be able to:\n- Know what a bed bug is a what they look like\n- Be aware of the signs that bed bugs are present\n- Know who to contact if there is a bed bug infestation\n- Understand the controlled measures that need to be in place if there is an infestation",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/P4Ph6GyWl99bDjGz3HY6FTKRG7diLBxV0QR4lhRK.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "793",
        title: "Bed Falls Management (Inc. Bed Rails)",
        aims: "To be able to manage a Person's Bed Falls Management needs",
        outcomes:
          "- Understand what Bed Falls Management is\n- Recognise pressure from Families to use Bed Rails\n- Know what the Bed Falls Management Options are\n- Recognise the specific considerations for each Person\n- Understand that the use of Bed Rails is a last resort\n- Recognise the types of incidents associated with Bed Rails\n- Understand the steps included in risk assessments\n- Know the different types of paperwork used when managing Bed Falls Management",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/5Y9yILgEdJKWvI6GltzXSuYUCr80H8KfbT6HAZwj.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "441",
        title: "Child Sexual Exploitation",
        aims: "To be able to work with children and young people and recognise the signs that they may be a victim of Grooming or Child Sexual Exploitation.",
        outcomes:
          "By the end of this course you will:\n\n* Know what Child Sexual Exploitation, Grooming and Trafficking are\n* Be aware of legislation surrounding Child Sexual Exploitation\n* Be aware of how grooming works\n* Understand how children may be sexually exploited\n* Be able to state the effects of Child Sexual Exploitation\n* Understand what safeguarding is\n* Understanding what to do in the event of disclosure\n* Know some suitable organisation that can offer support",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/kA5gqVeHFnlSSyKP88HQK5fkokxs3cmbtS33XpJQ.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/428115260",
        },
      },
      {
        id: "12307",
        title: "Child Support and Protection",
        aims: "To be able to work with children in either an authoritative or educational capacity, keeping them safe from abuse. To also be able to identify any abuses taking place and to know the appropriate action to take.",
        outcomes:
          "By the end of this course you will be able to:\n\n- Know what safeguarding and child protection is\n- Understand who safeguarding is aimed at and who is responsible for it\n- Be aware of who abusers are\n- Be aware of various legislation surrounding safeguarding and child protection\n- Know what risk factors and protective factors are\n- Be aware of some of the indicators of child abuse\n- Know the different types of abuse\n- Understand how to report abuse\n- Be aware of how to disclose information regarding child abuse\n- Be aware of why people don’t always report abuse\n- Know about the ‘Every Child Matters’ policy",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/tgRaPDT3ZhQeeIo5AJfJpSIzMSfCuryelkehZSoJ.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "428",
        title: "Communication",
        aims: "Whilst providing care, to be able to communicate with residents and colleagues ensuring that information is communicated effectively.",
        outcomes:
          "By the end of this course you will:\n\n * Understand what Communication is\n * Understand the barriers of communication and how to break them down\n * Be aware of the impact communication has on those you are caring for\n * Know of different ways to communicate\n * Know when to use the different types of communication\n * Understand that listening is an important type of communication\n * Understand the importance of checking and clarifying information\n * Be aware of the differences in formal and informal communication\n * Know how to write a good report\n * Apply the rules surrounding information sharing\n * Know the exceptions to these rules\n * Be aware of the types of documents that hold confidential data",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/8IdDKAZawN59eJMhel2Go46OABymGge4ehGIPUkL.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/428116907",
        },
      },
      {
        id: "11862",
        title: "COSHH",
        aims: "To understand responsibilities and protocol regarding COSHH",
        outcomes:
          "By the end of this course you will:\n-\tKnow what is meant by hazardous substances\n-\tKnow how to store hazardous substances\n-   Recognise the danger symbols\n-\tBe aware of Material Safety Data Sheets\n-   Know employer responsibilities\n-   Know employee responsibilities",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/HXcaInlizUhvH7RqcwkcTNFdQZqsLqi9NSokDKG3.png",
        detail: {
          price: "0",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "435",
        title: "Diabetes Advanced Care",
        aims: "To be able to provide further effective care to those with Diabetes.",
        outcomes:
          "By the end of this course you will be able to:\n\n * Be aware of the different forms of insulin, and their effects\n * Understand how to monitor blood glucose levels\n * Be aware of the different types of Diabetes testing methods",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/QOZLMYpaG5cEfr8RXOdjhVniH9VlTNjKndOAPIS7.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/428121721",
        },
      },
      {
        id: "425",
        title: "Diabetes Awareness",
        aims: "Whilst caring for those with Diabetes, be able to identify the symptoms that could suggest a problem.",
        outcomes:
          "By the end of this course you will be able to:\n\n* Understand what Diabetes is\n* Know the difference between Type 1 and Type 2\n* Be aware of other Types of Diabetes\n* Recognise the Symptoms\n* Know the importance for good foot care for anyone with diabetes\n* Be aware of the health care checks available to those with diabetes\n* Know what Hypoglycaemia is\n* Know the best diet for someone managing diabetes",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/qgF5uiphcUlfoITwpal1QHqKoLpuzeyeCMY37w5b.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/428143493",
        },
      },
      {
        id: "844",
        title: "Duty of Candour",
        aims: "To be able to recognise the need to be honest and apologise when working within care",
        outcomes:
          "By the end of this course you will:\n\n* Understand what Duty of Candour means\n* Recognise when Duty of Candour needs to be used\n* Be aware of some examples of incidents where Duty of Candour applies\n* Know how to implement Duty of Candour within a care environment",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/ba5R8dIc87OGFzf379VU4J3wXkKBs0o8qvsa5JLH.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "100",
        title: "Duty of Care",
        aims: "To understand your obligations to Duty of Care",
        outcomes:
          "By the end of this course you will:\n\n * Know what your duty of care is and with who\n * Understand the definitions used in Duty of Care\n * Know which legislations relate to Duty of Care and why\n * Be aware of your responsibilities and your employers\n * Understand the importance of an individual’s right to live independently whist keeping them safe from harm\n * Know how to deal with comments and complaints\n * Understand that mistakes happen and follow procedure to prevent further mistakes\n * Recognise why conflict happens and how to deal with the individual and situation",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/Fvj26gFgLdWkYLd3y84zp9bGNIrV9EIPGNurjEMS.jpeg",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/319694889",
        },
      },
      {
        id: "303",
        title: "Dysphagia & The IDDSI Framework",
        aims: "To understand the role of the IDDSI framework and implement it in caring for those in need",
        outcomes:
          "- Know what dysphagia is, its causes, and its symptoms. \n- Be aware of the origins and use of the IDDSI Framework \n- Recognise the different levels of the IDDSI Framework, and their identifying characteristics \n- Understand how oral medication can affect IDDSI levels \n- Know how to use thickening agents to alter the consistency of food and drink \n- Understand how to undertake the Drinks Flow Test \n- Know how to undertake the food tests for IDDSI \n- Know the first aid steps to take in the event of someone choking \n- Be aware of the roles and responsibilities of work colleagues \n- Know how to support people with dysphagia at mealtimes \n- Be aware of the resources available to support your knowledge of IDDSI",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/k2sAlZAhAGkrkALhJ4QAFyIjd1k6KE1fLwagAmZx.jpeg",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/319694823",
        },
      },
      {
        id: "13230",
        title: "End of Life",
        aims: "To be able to provide person-centred palliative care in accordance with The Five Priorities for Care of the Dying to those who are nearing the end of their lives",
        outcomes:
          "By the end of this course, you will:\n\n- Understand what Palliative Care is\n- Understand what End of Life Care is\n- Be able to recognise the different Phases of End of Life\n- Understand the Five Priorities for Care of the Dying\n- Know the different types of observations\n- Know the different reasons for pain and discomfort\n- Be able to recognise and assess pain\n- Be aware of the different types of pain management\n- Understand the importance of holistic care",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/3wlnM0DiuHZ5d6fJy6jejC1yE72RBfWKiNSOkJRW.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "14654",
        title: "Epilepsy Awareness",
        aims: "To be able to provide person-centred and dignified care to those living with Epilepsy.",
        outcomes:
          "- Know what Epilepsy is\n\n- Recognise triggers\n\n- Be aware of the new Classifications of seizures\n\n- Be aware of the different symptoms for each type of seizure\n\n- Know what to do when someone is having a seizure\n\n- Implement steps to maintain a person's dignity during a seizure\n\n- Recognise when a seizure becomes an emergency\n\n- Be aware of the different treatments and medication available\n\n- Know the importance of information held in an Epilepsy Care Plan\n\n- Know the type of information that needs to be recorded in an Epilepsy Care Plan\n\n- Understand what everyday life is like for those living with Epilepsy",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/cbCNxYSJHBzw7BkVWKbObz4E1ALNJ4vrKeKqD8N6.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "14856",
        title: "Epilepsy Medication",
        aims: "To be able to provide person-centred and dignified care, regarding administering Epilepsy Medication, to those living with Epilepsy.",
        outcomes:
          "- Be aware of different Anti-Seizure Medications available and their use.\n- Know what Vagus Nerve Stimulation Therapy is.\n- Be aware of the different Epileptic Surgeries available.\n- Understand what Emergency Medication is.\n- Know how to become competent in giving Emergency Medication.\n- Recognise when a Seizure becomes an emergency.\n- Know when to administer Emergency Medication.\n- Be aware of the different ways Buccal Midazolam is available.\n- Know how to prepare to administer Buccal Midazolam.\n- Understand and be able to implement the Buccal Midazolam procedure.\n- Recognise common side effects of receiving Buccal Midazolam.\n- Know the importance of information held in an Epilepsy Care Plan.\n- Know the type of information that needs to be recorded in an Epilepsy Care Plan.",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/E3IMzIXlhNbWkVaiqbn3bOivMPPfRFtRpC1PM7G9.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "86",
        title: "Equality & Diversity",
        aims: "To recognise and appreciate the differences of the people we care for and provide care that is fair and gives equal opportunity to everyone.",
        outcomes:
          "By the end of this course you will:\n\n * Know the responsibilities of employees and employers\n * Know what beliefs, values, and attitudes are\n * Understand what is meant by equality, diversity, inclusion and discrimination\n * Know the legislation in place covering Equality & Diversity\n * Know each of the protected characteristics\n * Understand the different forms of discrimination, and how they can occur",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/UaZjiIrv4bAQ13fEOyubnvJwEXM6oOMs4Kr6k7AV.jpeg",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "267",
        title: "Fire Safety Awareness",
        aims: "To understand responsibilities and protocols regarding Fire Safety",
        outcomes:
          "* Understand what is meant by Fire Safety \n* Recognise the common causes of fire \n* Be aware of the legislation surrounding Fire Safety \n* Understand methods of preventing fires \n* Recognise the importance of PAT testing \n* Know how to keep electrical items safe to use \n* Identify fire risks and hazards \n* Know how to undertake a Fire Risk Assessments \n* Understand how to create and implement a Personal Emergency Evacuation Plan \n* Recognise the importance of reporting fire risks \n* Understand how fire safety equipment operates \n* Know how to respond to a fire \n* Understand the roles and responsibilities of Fire Marshals \n* Know how to implement Full and Zonal Evacuations \n* Recognise the importance of Fire Drills \n* Recognise the consequences of poor fire safety \n* Know your responsibilities and those of your employer",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/b7QhFpKs8UN7JuZbVZgUy9uIGK3hPODVyKeu7U4w.jpeg",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/319694283",
        },
      },
      {
        id: "287",
        title: "Food Safety - Level 2",
        aims: "To safely provide support in the kitchen during food preparation and food serving",
        outcomes:
          "By the end of this course you will:\n\n* Recognise the symptoms of food-borne illnesses\n* Be aware of who is at risk\n* Understand which foods are high-risk\n* Know the wider impact of food-borne illnesses\n* Be aware of the legislation underpinning food safety\n* Recognise hazards that can make food unsafe\n* Know what anaphylaxis is\n* Recognise common allergens\n* Be aware of ways to keep food safe from allergen cross contamination\n* Be aware of the different types of food pests\n* Know how to prevent pests\n* Recognise the signs of pests\n* Know how to keep food clean and uncontaminated\n* Understand how to wash hands effectively\n* Know the 'Danger Zone'\n* Understand how to store foods safely\n* Be aware of the roles and responsibilities",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/6kPaGAjWh3cAz3B76tlnHyUAyqxBOLIFW719dMGM.jpeg",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "296",
        title: "GDPR and Data Protection",
        aims: "To understand the changes GDPR brings, and how to be compliant with the regulations",
        outcomes:
          "By the end of this course you will be able to:\n\n * Understand what GDPR is\n * Recognise its importance\n * Know who and what is protected\n * Recognise the difference between personal and sensitive data\n * Gain an understanding of the key principles enshrined within the regulations\n * Understand the roles and responsibilities of a Data Controller\n * Be aware of the roles and responsibilities of a Data Processor\n * Recognise ways that a care home can be compliant",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/YznEnzMpREr94pGbwEmYwVdJ7y5bIhrsyXurNgRG.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/319694117",
        },
      },
      {
        id: "158",
        title: "Health and Safety",
        aims: "To understand responsibilities and protocols regarding Health and Safety.",
        outcomes:
          "By the end of this course you will:\n\n* Understand what Health and Safety means.\n* Know your responsibilities and those of your employer.\n* Understand the relevant Health and Safety legislations.\n* Be aware of tasks that will require special training.\n* Be aware of common accidents and sudden illnesses.\n* Know what to do in an emergency.\n* Understand how to create a Risk Assessment.\n* Understand methods of working safely with hazardous materials\n* Know methods and procedures to prevent fires.\n* Recognise the symptoms, causes and treatment for work related stress.",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/3KSDjCS6wDFZUNxwqeoQ60MCIPZV2ukLl0Mh3k4B.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/319694042",
        },
      },
      {
        id: "252",
        title: "Infection Control",
        aims: "To be able to contain and control infections effectively within Care Home Settings",
        outcomes:
          "* Understand the different kinds of pathogen \n* Be aware of how pathogens spread through the chain of infection \n* Know how outbreaks are problematic within a care home environment \n* Recognise the symptoms, controls and treatment regarding the common infections within care homes \n* Be aware of the legislations in place regarding controlling infections \n* Know the roles and responsibilities of employers and care staff \n* Understand the protocols in place with an outbreak occurs \n* Recognise the procedures that must be undertaken when admitting a new resident \n* Know how to undertake a deep clean \n* Recognise good hand hygiene habits \n* Know the steps to take to effectively wash hands \n* Understand the importance and use of PPE \n* Be aware of the best practice regarding Barrier Nursing \n* Know how to handle contaminated and dangerous materials \n* Explore the possible outcomes of poorly controlled infections",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/0dyy495svSA96eRNaU7zr5GDi1HZy8dWvVPwUh0k.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/319693973",
        },
      },
      {
        id: "429",
        title: "Information Governance and Caldicott",
        aims: "To provide care whilst protecting the data of anyone you come into contact with and ensure that patient data is only shared in accordance with the Seven Caldicott Principles.",
        outcomes:
          "By the end of this course you will:\n\n* Know what Information Governance is\n* Know who and what is protected\n* Recognise the difference between personal and sensitive data\n* Understand the Caldicott Principles\n* Understand of the roles and responsibilities of all Data Controllers\n* Be aware of ways to manage and secure data\n* Know when your duty to confidentiality can be overridden",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/92YiyKjote1LussIXKohfURGInvJZLnYrVKbVmLi.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/428131257",
        },
      },
      {
        id: "863",
        title: "Learning Disabilities",
        aims: "To be able to provide care and support to people living with a Learning Disability.",
        outcomes:
          "* Know what a Learning Disability is\n* Understand the difference between Learning Disabilities and Learning Difficulties\n* Know the different levels of Learning Disability\n* Recognise some conditions linked to Learning Disabilities\n* Know what is meant by a Behaviour of Concern\n* Recognise some common reasons for Behaviour of Concern\n* Know ways to deal with Behaviour of Concern\n* Recognise the need for good communication\n* Be aware of some alternative communication methods",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/zREAHXHXx4MRo5NciyMk1ndqzik5qoQAd9qg2i2j.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "14316",
        title: "Legionnaires' Disease",
        aims: "Know how to avoid contamination, prevent the spread and, shouuld the worst happen, how to recognise the symptoms and know what to do if you suspect an outbreak.",
        outcomes:
          "- Understand what Legionnaires' Disease is\n- Know where legionella can be found\n- Be aware of who is at higher risk of becoming seriously ill\n- Know how to recognise the signs and symptoms of Legionnaires' Disease\n- Understand how Legionnaires' Disease is diagnosed\n- Know your personal responsibilities within the Care Home\n- Be aware of how Legionnaires' Disease is treated\n- Know the correct procedure of reporting any diagnosis\n- Be aware of your Home's competent person/s' responsibilities\n- Understand the correct methods to check water temperatures\n- Be aware of what water temperatures are safe\n- Know how the risk of legionella should be managed\n- Be aware of the importance of keeping all records and documentation up to date",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/Vz9hNkJHhG5XOjhMgbtlcqHFUMgU8nC0IHYPuaME.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "721",
        title: "Living with Dementia",
        aims: "To be able to provide effective care for those living with Dementia",
        outcomes:
          "By the end of this course you will:\n\n- Recognise the common symptoms of Dementia\n- Know some relevant legislation protecting those living with Dementia\n- Understand the areas of the brain affected by Dementia\n- Understand the common causes of Dementia\n- Recognise the different stages of Dementia \n- Understand Behaviours of Concern and how to meet a Person’s needs\n- Recognise the importance of caring for and supporting those with Dementia",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/nLSSMpi6LB8m1pOFZlboVePUcqhbj7DiBvDuy71t.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "701",
        title: "Management and Supervision",
        aims: "To know how to manage effectively to promote a caring workplace.",
        outcomes:
          "By the end of this course you will:\n\n- Understand the skills required to be an effective manager\n- Recognise the importance of resilience\n- Know some of the key aspects of a manager’s role\n- Know the main responsibilities of managers\n- Understand what makes a good leader\n- Know the difference between supervisions and appraisals\n- Be able to plan supervisions and appraisals",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/hFnjEWw8MTZOVJ2Y89Oxx3gE1R7KQDYEmTCfzJ3s.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "443",
        title: "Manual Handling Update",
        aims: "To know how to safely carry out manual handling tasks putting safety first for you and others",
        outcomes:
          "By the end of this course you will:\n\n * Know what manual handling is\n * Know the relevant legislation around manual handling\n * Be aware of both employees and employers’ responsibilities\n * Know of the basic anatomy and function of the spine\n * Be familiar with common back problems\n * Understand ergonomics and fitting the task to the person\n * Know the correct manual handling techniques for lifting, pulling and pushing\n * Know how to ask somebody to perform a lift",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/7FT27FzJljBnbGgdgRtSjoeBgb4zAqVr5vISPFxK.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "298",
        title: "MCA and DoLS",
        aims: "To apply the Mental Capacity Act Principles into the care you provide to those with a mental health condition or living with dementia",
        outcomes:
          "* Be up to date with current statistics surrounding mental capacity \n* Know what the MCA is, why it’s important and who it affects \n* Know how to identify someone with a lack of capacity \n* Be aware of the key legislations surrounding mental capacity \n* Know the boundaries involved when caring for someone with a lack of capacity \n* Recognise how to help individuals make informed choices \n* How to risk assess a person’s choices \n* Recognize what “best interests” are and how to use the checklist provided \n* Know the 5 core principles of MCA \n* Know how and when to assess capacity \n* Be aware of the two-stage functional test for capacity \n* Be familiar with the standard authorisation process \n* Understand how to restrict and restrain in a person’s best interest \n* Know how to write care plans for individuals that lack capacity",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/8ezziPCFC6jpIjW5EiU9Q0bCnhHuVEb4kSr3icjC.jpeg",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/319693884",
        },
      },
      {
        id: "12093",
        title: "Meaningful Engagement",
        aims: "To understand and recognise the different types of meaningful engagement, and when they can be used.",
        outcomes:
          "- Understand what Meaningful Engagement is\n- Know the Four Types of Meaningful Engagement\n- Be aware of the 'Token Initiative' and how to use this during Productive Engagement\n- Understand why Meaningful Engagement is important, including Well-being and Having Purpose\n- Know how to implement Productive Engagement, Fun and Entertainment, Personal Care and Rest and Downtime\n- Understand that Meaningful Engagement should be inclusive and accessible to everyone\n- Know the Three Opportunities to Engage\n- Understand what Person-centred Engagement is\n- Be aware of the questions you could ask a person when using Person-centred Engagement\n- Understand the importance of Person-centred Engagement\n- Be aware of the clues you should look for in a person when using Person-centred Engagement\n- Know how, and where, to evidence Meaningful Engagement\n- Understand the positive impact Meaningful Engagement can have on people in the Care Home",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/6JOqceZN82rGnshrOHak1MPbajkYBl8urldmrHxq.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "517",
        title: "Medication Administration",
        aims: "To refresh the knowledge to those who provide Medication Administration in Care environments",
        outcomes:
          "By the end of this course you will have been updated on the following:\n\n- How Medication passes through the body\n- How the effectiveness of Medication can be altered\n- Precautions for Covert Medication Administration\n- How Medication Administration Records are used\n- Procedures relating to the ordering, auditing and storage of Medication\n- Post-administration observations\n- The 10Rs of Medication Administration\n- How to prepare for a Medication round\n- Procedures relating to a Person being away from their usual Care setting\n- How to safely dispose of Medication\n- Denaturing of Medication\n- Typical Medication Administration Errors and how to avoid them \n- A Medication Administrator’s Responsibilities",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/RKK58kpmVG6YwYveUmEW9mKtPA1mmStxxzJo2Oag.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "590",
        title: "Medication Awareness",
        aims: "To refresh the awareness of all staff, who work within an environment where medication is being managed, on the importance of the risks associated with Medication",
        outcomes:
          "By the end of this course you will have been updated on the following:\n\n * How drugs are defined in medical practice\n * The importance of competency\n * Legislation underpinning medication administration\n * The common types and forms of medication\n * The different routes of administering medication\n * Drugs which are controlled by law\n * How medication passes through the body\n * How to correctly store controlled drugs\n * That medication can have side effects\n * The ways that drugs can interact with other factors\n * That some people can find it difficult to take medication\n * Your responsibilities and the responsibilities of others in your workplace regarding medication administration",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/3XrobFZmx6QcW4mGVRboC6clQO953mh7YCQdsiK6.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "362",
        title: "Mental Health Awareness",
        aims: "To gain an understanding of the types of Mental Illnesses that may affect Residents and how best to support them.",
        outcomes:
          "By the end of this course you will:\n\n * Be aware of the history of mental health treatment in the UK\n * Recognise the stigma surrounding mental health\n * Understand how mental health impacts the care sector\n * Recognise the key legislation underpinning the treatment of mental illness\n * Be aware of the causes of mental health conditions\n * Be aware of the different ways mental illness can manifest\n * Know symptoms of some mental health illnesses\n * Be aware of the different types of personality disorders\n * Recognise the symptoms of psychosis and schizophrenia\n * Know how psychosis and schizophrenia are treated\n * Understand the difference between learning difficulties and learning disabilities\n * Recognise the impact of stress on wellbeing and mental health\n * Know ways to look after your mental health\n * Know the Roles and Responsibilities of staff in care homes\n * Know of different resources and organisations available to support those with mental health issues",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/tmSGM3NgPqknAPfWFKwIldW15S5sCLEb3PGcgzCr.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/362261380",
        },
      },
      {
        id: "314",
        title: "Nutrition & Hydration",
        aims: "By the end of the course you will be able to support residents with their nutrition and hydration",
        outcomes:
          "* Recognise the importance of good nutrition and hydration\n* Know the latest facts and statistics surrounding nutrition & hydration\n* Recognise the signs and symptoms of malnutrition\n* Be aware of the causes of malnutrition\n* Know how to calculate someone's BMI\n* Know why you would need someone's MUST score\n* Understand the 5 MUST steps to establish the correct Action Plan\n* Be familiar with the 5 food groups\n* Understand the philosophy behind the Eatwell Guide\n* Be familiar with foods that should be avoided\n* Recognise signs and symptoms of dehydration\n* Be aware of strategies to maintain hydration\n* Recognise common conditions that could affect nutrition\n* Know your own and your employers responsibilities",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/rdkrM5qfnTAWGtTIjBFwI8HqSf0xdLnHHcjPgZk1.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/428148512",
        },
      },
      {
        id: "427",
        title: "Oral Health",
        aims: "To be able to provide effective oral care for Residents.",
        outcomes:
          "By the end of this course you will be able to:\n\n * Recognise the impact of poor oral health care\n * Be aware of the statistics of oral care in care homes\n * Understand the roles and responsibilities of all colleagues regarding oral health\n * Recognise the importance of the mouth and teeth\n * Be aware of the anatomy of the mouth and teeth\n * Recognise common mouth problems and how they are treated\n * Know how to support Residents with their oral hygiene\n * Know of correct methods for cleaning teeth\n * Understand how certain medical conditions can complicate oral hygiene\n * Recognise the importance of well-fitting dentures\n * Understand how to support Residents with their dentures",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/1gfSvDDF7SDnaWGvWdCuKG8jCwTDGDrxXusuK00Z.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/428127810",
        },
      },
      {
        id: "678",
        title: "Person Centred Care",
        aims: "To be able to meet the specific needs of everyone by providing care centred around the individual",
        outcomes:
          "By the end of this course you will:\n- Understand what is meant by Person-Centred Care\n- Know what values are\n- Know the 6C's of care\n- Understand the main Person-Centred Care principles\n- Know the difference between Person-Centred Care and Institutional Care\n- Recognise factors that may cause distress\n- Be aware of the Care Planning process\n- Know your responsibilities for providing Person-Centred Care",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/ELocaKsB3RMyxNwoJYRnuiTyGjjfYSaeRp2nw8gx.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "12466",
        title: "Positive Behaviour Support",
        aims: "To be able to identify and de-escalate behaviour of concern safely and effectively using positive behaviour support techniques.",
        outcomes:
          "By the end of this course, you will:\n\n-\tUnderstand what Positive Behaviour Support is.\n-\tUnderstand what a Behaviour of Concern is.\n-\tBe able to recognise the different types of Behaviour of Concern.\n-\tBe able to identify common triggers.\n-\tBe able to identify causes and underlying factors.\n-\tUnderstand the difference between common triggers and causes.\n-\tBe able to identify signs of escalation.\n-\tKnow how to assess a situation that may lead to a Behaviour of Concern.\n-\tUnderstand the importance of de-escalating yourself and how this can be done.\n-\tUnderstand what is meant by Positive de-escalation.\n-\tKnow where to find distraction techniques and when it is appropriate to use them.\n-\tBe able to read body language.\n-\tUnderstand how to use your listening skills.\n-\tUnderstand the importance and what is required in a handover.",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/p8z70Blvl83qSeqHxQHXqNBHJ8aVDAja2I6cj14K.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "249",
        title: "Privacy and Dignity",
        aims: "To care for people whilst respecting privacy, promoting choice and maintaining dignity",
        outcomes:
          "* Understand what Privacy & Dignity mean in a healthcare setting \n* Be aware of the importance of person-centred dignity \n* Recognise the importance of maintaining dignity for someone living with dementia \n* Understand the importance of a resident’s personal space \n* Know how to gain trust and confidence by maintaining confidentiality \n* Understand your responsibilities regarding safeguarding, and when it's OK to break confidence \n* Understand the factors that shape personal choices \n* Be aware of the importance of mental capacity within a care setting \n* Know how to help residents maintain independence and make informed choices \n* Know how to conduct a risk assessment\n* Understand the importance of making sure that residents are active participants in their care \n* Know the key principles of self-care",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/tR2ZJfKTfKQZgjO9lNGbuquRO21bEf25akfFVvYN.jpeg",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/319693672",
        },
      },
      {
        id: "79",
        title: "Safeguarding Adults at Risk - Level 2",
        aims: "To be able to care for adults at risk, keeping them safe from abuse.",
        outcomes:
          "* Understand who needs safeguarding \n* Know who an adult at risk is \n* Know whose responsibility it is to safeguard \n* Understand risk factors for abuse \n* Know the relevant legislation\n* Be aware of all the different types of abuse \n* Recognise signs of abuse \n* Recognise a potential abuser \n- Understand disclosure and whistle-blowing procedures",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/l8d4guenJrHyj9bWy2ETpvyu7MzPEUON3avaj6CD.jpeg",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "437",
        title: "Safeguarding Children",
        aims: "To be able to work with children in either an authoritative or educational capacity, keeping them safe from abuse. To also be able to identify any abuses taking place and to know the appropriate action to take.",
        outcomes:
          "By the end of this course you will be able to:\n\n * Know what safeguarding and child protection is\n * Understand who safeguarding is aimed at and who is responsible for it\n * Be aware of who abusers are\n * Be aware of various legislation surrounding safeguarding and child protection\n * Know what risk factors and protective factors are\n * Be aware of some of the indicators of child abuse\n * Know the different types of abuse\n * Understand how to report abuse\n * Be aware of how to disclose information regarding child abuse\n * Be aware of why people don’t always report abuse\n * Know about the ‘Every Child Matters’ policy",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/e3ps5YS2ZkevrP1dvl6nI4U21KdElvwB60aErRfe.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/428155786",
        },
      },
      {
        id: "461",
        title: "Safer People Handling Update",
        aims: "To be able to manoeuvre people safely using equipment where appropriate",
        outcomes:
          "By the end of this course you will have been updated on the following:\n\n * Be aware of health issues that may necessitate support\n * Be aware of the need to follow good infection control procedures\n * Understand how to manoeuvre residents with dignity\n * Know the importance of promoting independence\n * Recognise the need for clear communication\n * Know techniques used for assisted walking\n * Know techniques for moving a person from sitting to standing\n * Recognise the signs that a person might be falling\n * Be aware of some ways to deal with a falling person\n * Be aware of reasons why a person may need moving in bed\n * Know how to move a person in bed\n * Know how to apply a slide sheet\n * Understand the safety checks to be performed before hoisting\n * Know how to use a hoist and sling\n * Understand how to manoeuvre people safely using a hoist\n * Understand roles and responsibilities",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/BgxiaoiBNvqbwdd6Cq99GYgUxsuNDo5ACa6fXlqU.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/428139564",
        },
      },
      {
        id: "430",
        title: "Stress at Work",
        aims: "To understand the differences between positive and negative stress, how to deal with stress in the workplace and to be aware of how stress affects you and those around you.",
        outcomes:
          "By the end of this course you will:\n\n * Know what Stress is\n * Be aware what the signs of Stress are\n * Understand the differences between Work Stress and Personal Stress\n * Be aware of what can cause Work Stress\n * Recognise bullying in the workplace\n * Know how to look after yourself and manage your own Stress\n * Understand your roles and responsibilities\n * Be aware of the manager's roles and responsibilities",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/Cc43A5M4s2rh0KvIai0xxwkWVFVQaU5yXHaQmywS.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: "https://player.vimeo.com/video/428153803",
        },
      },
      {
        id: "791",
        title: "Understand Your Role",
        aims: "To have an understanding of your role within the Care Sector",
        outcomes:
          "* Know your main duties and responsibilities and who to report to\n* Learn what is expected of you but also what is not included in your role\n* Know the safe and agreed ways in which you are expected to work\n* Ensure you are providing care and support which meets the needs of the individual\n* Learn the main working relationships in Health and Social Care\n* Ensure that you are working within the laws and regulations\n* Learn what partnership working is\n* Know who to ask for advice about partnership working and resolving conflict whenever you face a problem",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/r542mLBSed1aIZrEyrAnFdzwTPqGuun24PvNSzVU.png",
        detail: {
          price: "12",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "794",
        title: "Your Personal Development",
        aims: "Know how to develop your skills and understanding, through different learning styles and continual learning",
        outcomes:
          "* Understand what a Personal Development Plan is\n* Recognise what happens at Supervisions and Appraisals and the differences between them\n* Be aware of Core Skills you may need in your profession\n* Know where you can find places to develop your Core Skills\n* Know where you can find places to develop your Core Skills\n* Recognise the differences between Blended and Structured Learning\n* Be aware of how to reflect upon previous experiences and actions\n* Understand what the Care Certificate is\n* Be aware of CPD and how to develop your skills and understanding",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/ZQ4UjGII03YU9o9Yx6cuWIg2dwloTYxfWAOe3FCf.png",
        detail: {
          price: "15",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "11537",
        title: "REACT To Deterioration",
        aims: ".",
        outcomes: ".",
        image: null,
        detail: {
          price: "0",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "1461",
        title: "React to Dementia",
        aims: null,
        outcomes: null,
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/oC2EyXsWYgNQNOc6oZMN3SdzAmrxULnC4oHOuOgV.jpg",
        detail: {
          price: "0",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "1434",
        title: "React to Falls",
        aims: null,
        outcomes: null,
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/s48xSAaMkixHQpESyXoyFKzGNAtvwAvhI13ZlaKx.jpg",
        detail: {
          price: "0",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "1463",
        title: "React to Feet",
        aims: null,
        outcomes: null,
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/EdGn76pP6iWf6pky9czjM1NV7JYMz5dEjJsoY9te.jpg",
        detail: {
          price: "0",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "917",
        title: "React to Frailty",
        aims: null,
        outcomes:
          "The Aim of this course is for you to:\n\n- Understand what we mean by ‘frailty’ and how it might present\n- Understand why identifying frailty is important for all older people and how this is important in your working role\n- Understand the Clinical Frailty Scale (CFS) and feel confident to use it to identify levels of frailty\n- Be able to implement some appropriate interventions for the person you support and be aware of referral pathways into health and social care",
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/D8GuFhiYMeKpHpHwZQ7HEIi5bKUvSJ1w70LwLB7C.jpg",
        detail: {
          price: "0",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "1280",
        title: "React to Home Rounds",
        aims: null,
        outcomes: null,
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/iCVirifUy6EykqLfvPTnASYfuJNoPTia080H2DSy.jpg",
        detail: {
          price: "0",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "1462",
        title: "React to Malnutrition and Dehydration",
        aims: null,
        outcomes: null,
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/CHRaA8nNDjPq9AXdRXUOZt4esv8cKvyD85x6kFp4.jpg",
        detail: {
          price: "0",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "1447",
        title: "React to Moisture",
        aims: null,
        outcomes: null,
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/ZCoK1GF24EXK96wk2QAdI5tOUYUJrdbbWbPVEETT.jpg",
        detail: {
          price: "0",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "10234",
        title: "React to Quality Improvement",
        aims: null,
        outcomes: null,
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/nRNxEacfPVoF8LbuuXCvX0odA4bMvNyXq38ZqrWS.png",
        detail: {
          price: "0",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "688",
        title: "React to Red",
        aims: null,
        outcomes: null,
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/ML9bxQAz7cDHqrUilFA7TMTzRvFMwdV5ShOFI9BB.png",
        detail: {
          price: "0",
          discounted_price: null,
          promo_video_link: null,
        },
      },
      {
        id: "1464",
        title: "React to Infection",
        aims: null,
        outcomes: null,
        image:
          "https://ams3.digitaloceanspaces.com/lms-api/content-images/ikwCdu9l4ukcohwGG2ZeVVulr9OZJ08MlLI7OLOh.jpg",
        detail: {
          price: "0",
          discounted_price: null,
          promo_video_link: null,
        },
      },
    ],
    types: [
      {
        id: "4374",
        name: "Learner",
      },
      {
        id: "4375",
        name: "API User",
      },
    ],
    roles: [
      {
        id: "374951",
        name: "Learner",
      },
    ],
  },
});

const pageContent = ref(data.value.entity.content);
// const mobileInfo = ref([
//   {
//     url: "/src/assets/img/iphone13pro.webp",
//     name: "iPhone 13 Pro",
//     description:
//       "Apple's premium phone with A15 Bionic chip and advanced camera features.",
//     supply: 10,
//     id: 11,
//   },
//   {
//     url: "/src/assets/img/honorX7B.webp",
//     name: "Honor X7B",
//     description:
//       "Affordable device with a large display and long battery life.",
//     supply: 10,
//     id: 12,
//   },
//   {
//     url: "/src/assets/img/honorX9A.webp",
//     name: "Honor X9A",
//     description: "Mid-range phone with curved OLED display and fast charging.",
//     supply: 10,
//     id: 13,
//   },
//   {
//     url: "/src/assets/img/honorX9B.webp",
//     name: "Honor X9B",
//     description:
//       "Stylish design with high durability and powerful performance.",
//     supply: 10,
//     id: 14,
//   },
//   {
//     url: "/src/assets/img/honor90.webp",
//     name: "Honor 90",
//     description:
//       "Latest flagship phone with a 200MP camera and AI-enhanced photography.",
//     supply: 10,
//     id: 15,
//   },
//   {
//     url: "/src/assets/img/s21ultra.webp",
//     name: "Samsung Galaxy S21 Ultra",
//     description:
//       "Samsung's top-tier model with a 108MP camera and 100x Space Zoom.",
//     supply: 10,
//     id: 16,
//   },
// ]);
function addToBasket(number, id) {
  console.log("number is:", number, "id is:", id);
  const mobile = pageContent.value.find((item) => item.id === id);
  console.log("current is: ", mobile);
  // if (!mobile || mobile.supply <= 1 || number > mobile.supply) {
  //   console.log("Item not available or out of stock");
  //   return 0;
  // }
  // Find the item in the basket by its name
  const existingItem = basket.value.find(
    (basketItem) => basketItem.id === mobile.id
  );
  // Decrease the mobile supply
  if (existingItem) {
    // If the item already exists, increment the quantity
    existingItem.quantity += number;
  } else if (!existingItem) {
    // If the item doesn't exist in the basket, add it with a quantity of 1
    basket.value.push({
      url: mobile.image,
      name: mobile.title,
      quantity: number,
      id: mobile.id,
    });
  }
  // console.log("mobile", mobile);

  console.log("basket", basket.value); // Log the updated basket
}
function updateBasket(quantity, id) {
  // console.log("quentity:", quantity, "id:", id);
  const mobile = pageContent.value.find((item) => item.id === id);
  const basketItem = basket.value.find(
    (basketItem) => basketItem.id === mobile.id
  );
  basketItem.quantity = quantity;
}

function showBasket() {
  if (basket.value.length === 0) return;
  const basketComponent = document.querySelector(".basket");
  basketComponent.classList.toggle("hidden");
  basketComponent.classList.toggle("block");
}
</script>

<template>
  <nav class="flex items-center justify-between">
    <ul class="flex justify-center items-center gap-6">
      <li><a href="#">blog</a></li>
      <li><a href="#">Contact us</a></li>
    </ul>
    <ul class="relative">
      <li class="w-12 h-12">
        <button @click="showBasket">
          <img src="./../assets/img/basket.png" alt="" />
        </button>
      </li>
    </ul>
  </nav>
  <div
    class="basket hidden absolute right-8 bg-slate-50 z-10 max-h-[300px] overflow-auto"
  >
    <ul class="grid grid-cols-1 gap-4 p-4">
      <li
        v-for="(item, index) in basket"
        :key="index"
        class="flex flex-col items-center justify-between px-2"
      >
        <BasketComponent
          :item="item"
          :products="pageContent"
          @update-quantity="updateBasket"
        ></BasketComponent>
      </li>
    </ul>
  </div>
  <ul
    class="grid grid-cols-1 gap-4 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4"
  >
    <!-- <li
      v-for="(item, index) in mobileInfo"
      :key="index"
      class="flex flex-col border-black border-2"
    ></li> -->
    <li
      v-for="(item, index) in pageContent"
      :key="index"
      class="flex flex-col items-center justify-center border-black border-2 z-0 p-4"
    >
      <cardComponent
        :item="item"
        :basket="basket"
        :index="index"
        @add-item-to-basket="addToBasket"
      ></cardComponent>
    </li>
  </ul>
</template>

<style scoped></style>

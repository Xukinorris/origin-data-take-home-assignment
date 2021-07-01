# Origin Data Science Take-Home Assignment

## Introduction

Origin is a platform that helps our customers' employees put their financial lives on track through a Financial Wellness benefit.

Financial wellness is not just about getting rid of problems like credit card or student debt. It is also – and arguably mainly – about having confidence in the decisions you're making today and planning for your future so you can reach your goals.

That is especially true for Origin's persona, an upper-middle-class 32-year-old designer who lives in San Francisco and works for a venture-backed tech startup. This person makes enough money to save and live comfortably but doesn't have a great way of managing her finances or planning out her financial future. She wants to have more certainty about the decisions she's making today and receive guidance on how she can best prepare for a sound financial future.

Origin wants to help our users by being the single destination where they manage both their day-to-day finances as well as where they plan out their long-term financial roadmap.

To help them with day-to-day financial management, one important data point is related to consumer habits, which can be analyzed through customer segmentation.

Customer segmentation — also known as market segmentation — is the division of potential customers in a given market into discrete groups. That division is based on customers having similar enough (1) needs, so that a single whole product can satisfy them; and/or (2) buying characteristics, responses to messaging, marketing channels, and sales channels, so that a single go-to-market approach can be used to sell to them competitively.

---

## The business question
Given the transaction and user datasets that reflect the cash flow behavior of users, segment the users based on buying patterns.

---

## Assessment Instructions

### About the datasets
The **user dataset** contains the basic information about the user like id, gender, birthdate.
- id: unique ID assigned to the user
- created_at: creation date
- date_of_birth: user's birthdate
- gender: user's gender
- country: user's address country
- state: user's address state
- city: user's address city

The **transaction dataset** contains the basic information about the user banking transactions like id, account, category, amount.
- _id: unique ID assigned to the transaction
- user_id: unique ID assigned to the user
- account_id: banking account unique id
- account_name: banking account name
- description: transaction description
- type: transaction category (expense, income, transfer)
- amount: transaction amount
- date: transaction date
- extra_fields.category.0: primary transaction category
- extra_fields.category.1: secondary transaction category
- extra_fields.category.2: tertiary transaction category
- extra_fields.merchant_name: merchant name
- extra_fields.name: transaction description
- extra_fields.payment_channel: payment channel
- extra_fields.payment_method: payment method
- created_at: creation date

### Evaluation

Be aware that Origin will focus on the following evaluation criteria:
- If you did an exploratory data analysis;
- If you did a cluster analysis;
- If you could quantify the quality of clustering;
- How did you get the data insights inside the report;
- How clean and organized your code and report are;

---

## Delivery Instructions
You'll need to create a project to behave your data analysis and a presentation with your data insights report.

Create a public Github repository with your data analysis project and presentation, and share these deliverables with us.

To share it. Don't create a fork. Send us the link to your repository, and make sure to make it public.

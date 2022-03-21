# emf-web-dev-task

This task is designed for Web Developer roles at the Ellen MacArthur Foundation (EMF).

The goal is for us to assess your approach to solution design, as well as to understand where you are at with your coding skills.

The task should take 1-3 hours, and should be completed using React. If you have any questions, please do ask, and if you find the task taking significantly longer, please submit what you have - we are not looking for perfection!

## Setup 🤖
You can use this repository as a basis for completing the task, however, first you will need to create a copy of it, so that you can push your changes to it:
1. Clone this repository
2. Create a new private repository in your personal GitHub account
3. Push the cloned repository to your newly created repo (You will need to first remove the original origin with `git remote remove origin`, and add your new one `git remote add origin <url-to-your-repo>`)

Please commit **all** work to this repository. All work must be on the `main` branch when you submit - we will only look at `main`. 
If you would like to, please host your solution so the output can be easily viewed. Otherwise, please include instructions for running your solution locally.

Once you have completed the task, please ensure that you have pushed your code and solutions, and then add [@georgemillard](https://github.com/georgemillard) and [@merton](https://github.com/Merton) as collaborators to your repository. 
You can then email us the URL to your repository, where we can review.

## The Challenge
### Introduction
[Circulytics](https://ellenmacarthurfoundation.org/resources/circulytics/overview) is the Ellen MacArthur Foundation’s leading tool for measuring how circular an organisation is, and provides feedback in areas that they can improve.  Organisations provide key information which can be used to calculate an overall score, as well as scores in different themes. 

### Task 🎯
Your goal is to create a Circulytics leaderboard. This will be a single web page displaying a list of companies. We want to see their Name, Industry and Score:

- **Name** - a string of max-length 32 characters
- **Industry** - a single choice from the following list: 
   - Agriculture, 
   - Consumer/end products, 
   - Energy, 
   - Finance, 
   - Infrastructure, 
   - Services,
   - Transportation, 
   - Upstream processing
- **Score** - a single decimal number between 0.0 and 1.0 (inclusive)

The page needs to support user input so companies can be added.

### Stretch goals 🤸🏻‍♀️
If you have sufficient time, exploring one or more of the following additional functionality would be great!
- search
- sort
- filter
- persistence

Good luck! 👾

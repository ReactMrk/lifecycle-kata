# **Customer management with React and Hooks**

The idea of our company is to create a large application to manage customers. Therefore, Customer Management, from the first session, has been redeveloped using React due to its scalability.

Use correct node version: **nvm use**

Install dependencies: **npm install**

Run app: **npm run dev**

**Tips:** the commented code is a skeleton provided to complete the exercises.

**Info:** it's not a problem that customers are lost when the website is reloaded, because in the future an API will be used to get them. <br />

<img width="853" height="662" alt="Screen Recording 2026-09-09 at 13 36 48" src="https://github.com/user-attachments/assets/8fe89a59-87f4-42d1-b623-e15c72cde6bc" /> <br />

**Exercise 1.**

https://react.dev/reference/react/useEffect

After some time on production, a new requirement has been requested. When agents add a new customer and the list of customers is large, there is no visual feedback, so agents are not sure if the customer has been added correctly until they scroll down the entire list.

To do this improvement, a principal engineer suggested you create a component using `useEffect` that displays an alert on top of the list when a new customer is added. The alert should be displayed for 2 seconds.
Check https://developer.mozilla.org/en-US/docs/Web/API/Window/setTimeout for additional info.

**Use `src/Alert.jsx` file**

 <br />
 
**Exercise 2.**

The stakeholders have pointed out that they would like to implement a Login/Logout functionality. As an initial step we will introduce the behaviour by means of a button.
Your new requirements are:

- A new set of Login/Logout buttons have already been added to the page.
- The first time the list is loaded an Alert should be displayed with the following text: "Welcome to the Customer List". The alert should be displayed for 3 seconds.
- When the customers are added it should still behave as per Exercise 1.
- When the logout button is pressed an Alert with the following text should be displayed: "Goodbye". The alert should be displayed for 3 seconds.
- Implement the functionality using `useEffect`
- You can only modify the `CustomerList.jsx`
<br />

**BONUS EXERCISE.** 

There is a bug that allows you to add empty customers. Can you solve it?

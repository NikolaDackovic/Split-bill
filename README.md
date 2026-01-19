🍽️ Eat-N-Split (React Practice Project)

link: https://friendly-longma-758736.netlify.app/

This project is a small React application built to practice core React concepts such as state management, props, component composition, and lifting state up.

The app allows users to manage a list of friends and split bills with them, keeping track of who owes whom money.

🚀 What I Learned From This Project
1️⃣ Thinking in Components

I learned how to break a UI into small, reusable components, such as:

App

FriendList

Friend

FormAddFriend

FormSplitBill

Button

Each component has a single responsibility, which makes the code easier to read and maintain.

2️⃣ useState for State Management

I practiced using useState to manage different types of state:

Arrays (friends)

Booleans (showAddFriend)

Objects (selectedFriend)

Form inputs (bill, paidByUser, whoIsPaying)

I also learned where state should live, depending on which components need access to it.

3️⃣ Lifting State Up

One of the most important lessons in this project was lifting state up:

The friends state lives in App

Child components do not change state directly

Child components notify the parent via callback props

This helped me understand one-way data flow in React.

4️⃣ Passing Props & Callback Functions

I learned how to:

Pass data down using props

Pass functions down to handle events

Let child components update parent state indirectly

Examples include:

onAddFriend

onSelection

onSplitBill

5️⃣ The children Prop

I used the children prop to create a reusable Button component, allowing flexible button content without rewriting logic.

6️⃣ Conditional Rendering

I practiced conditional rendering to:

Show/hide forms

Render components based on state

Dynamically change button text

This reinforced how React reacts to state changes.

7️⃣ Updating State Immutably

I learned how to:

Update arrays using map and spread syntax

Use functional state updates

Avoid mutating state directly

This is essential for predictable React behavior.

🧠 Key Takeaway

This project helped me transition from basic React concepts to understanding how a real-world React application is structured, how components communicate, and how shared state is managed.

🛠️ Technologies Used

React

JavaScript (ES6+)

CSS

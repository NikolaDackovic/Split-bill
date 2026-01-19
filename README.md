### 🍽️ Eat-N-Split (React Practice Project)

🔗 **Live demo:**  
https://friendly-longma-758736.netlify.app/

### About the Project

**Eat-N-Split** is a small React application built to practice core React concepts such as **state management, props, component composition, and lifting state up**.

The app allows users to manage a list of friends and split bills with them, keeping track of **who owes whom money**.

### What I Learned From This Project

### Thinking in Components

I learned how to break the UI into small, reusable components:

- `App`
- `FriendList`
- `Friend`
- `FormAddFriend`
- `FormSplitBill`
- `Button`

Each component has a **single responsibility**, which makes the code easier to read, maintain, and scale.

### useState for State Management

I practiced using `useState` to manage different types of state:

- Arrays (friends list)
- Booleans (showAddFriend)
- Objects (selectedFriend)
- Form inputs (bill, paidByUser, whoIsPaying)

I also learned **where state should live**, depending on which components need access to it.

### Lifting State Up

One of the most important lessons in this project was **lifting state up**:

- The `friends` state lives in the `App` component
- Child components do not change state directly
- Child components communicate with the parent via **callback props**

This helped me clearly understand **one-way data flow** in React.

### Passing Props & Callback Functions

I learned how to:

- Pass data down using props
- Pass functions down to handle events
- Let child components update parent state indirectly

Examples include:

- `onAddFriend`
- `onSelection`
- `onSplitBill`

### The `children` Prop

I used the `children` prop to create a **reusable Button component**, allowing flexible button content without duplicating logic.

### Conditional Rendering

I practiced conditional rendering to:

- Show and hide forms
- Render components based on state
- Dynamically change button text

This reinforced how React UI updates automatically when state changes.

### Updating State Immutably

I learned how to:

- Update arrays using `map` and spread syntax
- Use functional state updates
- Avoid mutating state directly

This is essential for **predictable and bug-free React behavior**.

### Key Takeaway

This project helped me transition from **basic React concepts** to understanding how a **real-world React application** is structured, how components communicate, and how shared state is managed.

### Technologies Used

- React
- JavaScript (ES6+)
- CSS

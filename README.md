# Smart Groceries 🛒

Smart Groceries is a simple and interactive shopping list web application built with React. It helps you keep track of your groceries, manage quantities, and mark items as packed when purchased. You can also sort the list, clear it, and monitor your progress.  

## Features ✨

- Add items ➕: Enter product name and quantity to add new items.  
- Delete items ❌: Remove unwanted items from the list.  
- Mark as packed ✅: Toggle items when they are bought/packed.  
- Sorting options 🔄: Sort list by input order, description, or packed status.  
- Clear list 🧹: Remove all items at once with a single click.  
- Stats footer 📊: Displays number of items and packing progress.  
- Responsive UI 📱💻: Works across different devices.  

## Usage 🖱️

- Use the input field and dropdown to add a product with quantity.  
- Click the checkbox to mark an item as packed/unpacked.  
- Use the ❌ button to delete an item.  
- Change sorting with the dropdown menu (by input, description, or packed).  
- Click **Clear list** to remove all items.  
- Check the footer to see how many items are packed and your progress percentage.  

## Technologies used 💻

- React (useState)  
- JavaScript (ES6+)  
- HTML5  
- CSS3  

## React skills used 🛠️

- State management with `useState`  
- Passing props between components  
- Event handling (submit, change, click)  
- Conditional rendering  
- Array methods (map, filter, sort)  
- Controlled components (input, select)  
- Component composition and modular structure  

## Code Structure 🏗️

- **App component 🎛️**: Manages global state and orchestrates logic.  
- **Logo 🏷️**: Displays application title.  
- **Form 📝**: Handles adding new items.  
- **PackingList 📋**: Renders and sorts the list of items.  
- **Item 🛍️**: Individual grocery item with toggle and delete functionality.  
- **Stats 📊**: Footer showing shopping progress.  

## License 📄

This project is open source and available under the MIT License.  

## 📦 Getting Started

To run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/smart-groceries.git
2. Navigate to the project directory:
cd smart-groceries

3. Install dependencies:
npm install

4. Start the development server:
npm start

5. Open http://localhost:3000 in your browser.

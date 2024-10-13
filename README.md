
# Split Buddy

Split Buddy is a React-based app that helps you split bills with friends and keep track of who owes whom money. It makes splitting bills easy by calculating shares and keeping a clear record of outstanding balances between friends.

## Features

- **Add Friends**: Add new friends using the "Add Friend" button. Each friend is displayed in a list with their current balance status.
- **Bill Splitting**: Select a friend from the list to open a new section where you can enter:
  - The **total bill amount**.
  - **Your share** of the bill.
  - The friend's share is automatically calculated based on your input.
  - Option to select **who paid** the bill.
- **Owed Balances Display**: Each friend in the list shows their current balance:
  - If the friend **owes you money**, the balance is shown in **green**.
  - If **you owe the friend**, the balance is displayed in **red**.

## Getting Started

Follow these steps to get the project running on your local machine.

### Prerequisites

Make sure you have the following installed:

- **Node.js**: [Download and install Node.js](https://nodejs.org/)
- **npm** (Node Package Manager) or **yarn**: npm comes with Node.js, but you can also install [yarn](https://yarnpkg.com/getting-started/install) if preferred.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/aditya240/Split-Buddy.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Split-Buddy
   ```

3. Install the required dependencies:

   Using npm:
   ```bash
   npm install
   ```

   Or using yarn:
   ```bash
   yarn install
   ```

### Running the Project

To run the project locally:

1. Start the development server:

   Using npm:
   ```bash
   npm start
   ```

   Or using yarn:
   ```bash
   yarn start
   ```

2. Open your browser and navigate to `http://localhost:3000` to view the app.

## Usage

1. **Add a Friend**: Click the "Add Friend" button to add a new friend to your list.
2. **Select a Friend**: Click on the "Select" button next to the friend's name in the list to open the bill-splitting section.
3. **Enter Bill Details**: Enter the total bill amount, your share, and select who paid the bill. The friend's share is automatically calculated.
4. **View Owed Balances**: In the friend list, you’ll see each friend's current balance under their name:
   - If a friend owes you money, their balance is shown in **green**.
   - If you owe a friend money, the balance is displayed in **red**.
   - If you're both even, it is displayed as such without any colour schemes

## Example

- You enter a total bill of $100, and your share is $40. Your friend's share will be automatically calculated as $60.
- If your friend paid the full bill, you’ll owe them $40, which will be displayed in red under their name.
- If you paid the bill, they will owe you $60, which will be displayed in green under their name.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **CSS**: For styling the app.

## Screenshots

Here are some screenshots of the app in action:

<img width="1512" alt="Screenshot 2024-10-13 at 8 39 05 PM" src="https://github.com/user-attachments/assets/6eacd48a-b3b5-48e1-8c07-11199d11e80a">

<img width="1512" alt="Screenshot 2024-10-13 at 8 39 18 PM" src="https://github.com/user-attachments/assets/dfad1cc5-0aa4-4b7e-acf2-dc9d50806510">

<img width="1512" alt="Screenshot 2024-10-13 at 8 39 42 PM" src="https://github.com/user-attachments/assets/f1ad3ec8-8aeb-4a81-8436-a0378e8c14f9">

<img width="1512" alt="Screenshot 2024-10-13 at 8 39 50 PM" src="https://github.com/user-attachments/assets/038deb1e-0244-48a6-afa2-aba8b2a3ffbb">

<img width="1512" alt="Screenshot 2024-10-13 at 8 41 28 PM" src="https://github.com/user-attachments/assets/01e335bd-d697-4297-908f-87d04e61c09e">

<img width="1512" alt="Screenshot 2024-10-13 at 8 41 37 PM" src="https://github.com/user-attachments/assets/0d90d22d-1cb9-472f-999e-ff602f6b5fc0">

<img width="1512" alt="Screenshot 2024-10-13 at 8 42 02 PM" src="https://github.com/user-attachments/assets/22d9920b-0190-4bc3-a7f2-fcf4536b1194">

<img width="1512" alt="Screenshot 2024-10-13 at 8 42 12 PM" src="https://github.com/user-attachments/assets/8ea6ca78-3c43-4388-98a6-fd367202cc0d">

<img width="1512" alt="Screenshot 2024-10-13 at 8 42 40 PM" src="https://github.com/user-attachments/assets/507effd0-096d-4358-ae28-d8fe431e6a56">

<img width="1512" alt="Screenshot 2024-10-13 at 8 42 57 PM" src="https://github.com/user-attachments/assets/5903862e-b3b4-44dc-b440-47ce01505a8d">


## Author

- **Aditya Jaiswal** - [GitHub](https://github.com/aditya240)

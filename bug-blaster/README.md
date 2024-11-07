# Bug Blaster

Bug Blaster is a simple ticket management portal built with React. It allows users to create tickets with a title and description, set the priority of the ticket (Low, Medium, High), and view the list of created tickets on the same page. The tickets can be sorted by priority for better management.

## Features

- **Create Tickets**: Users can create tickets by entering a title, description, and selecting the priority.
- **Priority Levels**: Tickets can be assigned one of the following priority levels:
  - Low
  - Medium
  - High
- **View Created Tickets**: A list of created tickets is displayed below the form.
- **Sorting**: Tickets are displayed in a sortable list based on their priority (High, Medium, Low).

## Installation

To get started with the Bug Blaster project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone git@github.com:MurleePatil/ReactProjects.git
    cd bug-blaster
    ```

2. **Install dependencies**:
    Make sure you have [Node.js](https://nodejs.org/) and [npm](https://npmjs.com) installed. Then run:
    ```bash
    npm install
    ```

3. **Run the development server**:
    After the dependencies are installed, run the following command to start the React development server:
    ```bash
    npm start
    ```

    This will launch the app in your default web browser at `http://localhost:3000`.

## Usage

1. **Create a ticket**: 
   - Fill in the ticket's **Title** and **Description**.
   - Select the **Priority** from the dropdown (Low, Medium, High).
   - Click the **Create Ticket** button to add the ticket.

2. **View the tickets**:
   - The created tickets will be listed below the form.
   - Tickets are sorted by priority, with **High** priority tickets displayed first, followed by **Medium** and **Low**.

# Kanban Board Application
To create an interactive Kanban board application using React JS that interacts with the provided API from  https://api.quicksell.co/v1/internal/frontend-assignment.
Users can group tickets by status, user, or priority, and sort the displayed tickets by priority or title. The application also retains the user's view state even after page reload.
## Features
The application should offer three distinct ways to group the data:

1. **By Status**: Group tickets based on their current status.
2. **By User**: Arrange tickets according to the assigned user.
3. **By Priority**: Group tickets based on their priority level.

Users should also be able to sort the displayed tickets in two ways:

1. **Priority**: Arrange tickets in descending order of priority.
2. **Title**: Sort tickets in ascending order based on their title.

### Priority Levels

**The priority levels for the tickets are as follows:**

- Urgent (Priority level 4)
- High (Priority level 3)
- Medium (Priority level 2)
- Low (Priority level 1)
- No priority (Priority level 0)

**Priority levels: (This values you will receive in the api)**

4 - Urgent, 
3 - High, 
2 - Medium, 
1 - Low, 
0 - No priority

## Installation
 **Clone the repository**
  
        git clone https://github.com/Rupa-Veerala/Kanban-board-application.git

 **Navigate the directory**
 
        cd Kanban-board-application
        
  **Install Dependencies**
  
        npm install
        
  **Start the Development Server**
  
        npm start
        
  Open your web browser and visit the application.

## How to Use

1. Click the "display" button to fetch and display the tickets from the provided API.

2. Select one of the three grouping options: "By Status," "By User," or "By Priority."

3. Choose the sorting option: "Priority" or "Title."

4. The Kanban board will dynamically adjust to reflect your choices.

5. The application will save your view state, so you can return to your preferred settings even after a page reload.



   



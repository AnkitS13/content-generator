Content Brief Generator
About
The Content Brief Generator simplifies the process of content exploration and provides users with concise, well-structured information. 
Built with ReactJS for the frontend and integrated with the Gemini API, this project enables users to search for content, retrieve results, generate summaries, and view source links for a seamless user experience.


##**Features**
##**Content Search:**

Users can input keywords to fetch relevant content from the Gemini API.
Content Processing:

Cleans unnecessary characters for readability.
Generates concise summaries for the retrieved content.
Extracts source URLs for references.
State Management:

Data is stored and managed using Redux Toolkit, with slices for structured state organization.
State persistence is implemented using Redux Persist for maintaining user data across sessions.
User Interface:

ReactJS provides a dynamic and interactive UI for displaying the brief content, summaries, and source links.

Getting Started
Follow these steps to set up and run the application locally.

Prerequisites
Ensure the following are installed on your system:

React.js
npm (Node Package Manager)
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/content-brief-generator.git
Navigate to the Project Directory:

bash
Copy code
cd content-brief-generator
Install Dependencies:

bash
Copy code
npm install
Start the Development Server:

bash
Copy code
npm start
Access the App:
Open your browser and go to http://localhost:3000.

Usage
Search Content:

Enter a keyword or term in the search bar and hit search.
The app will fetch relevant data from the Gemini API.
View Results:

The processed content will display:
Cleaned brief content.
Automatically generated summaries.
Source links extracted from the content.
Manage State:

Data is stored in Redux and persists across sessions for easy access.
Built With
ReactJS: For building the user interface.
Redux Toolkit: For efficient and scalable state management.
Redux Persist: To retain data even after page reloads.
Gemini API: As the data source for fetching content

![Screenshot 2024-12-01 220822](https://github.com/user-attachments/assets/4ec470a7-ad85-4661-b0a8-dbd14de7e021)


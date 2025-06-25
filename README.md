# 👨‍👩‍👧‍👦 Family Travel Tracker.

An enhanced version of the Travel Tracker that allows families to keep track of each member's visited countries individually. This project uses PostgreSQL with inner joins to manage relationships between family members and their travel records.  

## ✨ Features  
- 🧑‍🤝‍🧑 Add family members.  
- 🌍 Record visited countries for each family member.  
- 🔄 View a complete list of members and their respective travel histories using PostgreSQL inner joins.  
- 🎨 Clean and user-friendly interface with HTML and CSS.  

## 🛠️ Tech Stack  
- **Backend:** Node.js, Express.js  
- **Database:** PostgreSQL (inner join for relationships)  
- **Middleware:** body-parser  
- **Frontend:** HTML, CSS  

## 📋 Prerequisites  
- Node.js and npm installed.  
- PostgreSQL installed and running.  

## 🔧 Installation  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/sheftechdad/family-travel-tracker.git  
   cd family-travel-tracker  
   ```  

2. Install dependencies:  
   ```bash  
   npm install  
   ```  

3. Set up the PostgreSQL database:  
   - Create a database named `MyDB`.  
   

4. Configure the database connection:  
  
   - Add the following environment variables:  
     ```plaintext  
     DB_HOST=localhost  
     DB_USER=your_username  
     DB_PASSWORD=your_password  
     DB_NAME=family_travel_tracker  
     DB_PORT=5432  
     ```  

5. Start the application:  
   ```bash  
   node index.js  
   ```  

6. 🌐 Open your browser and navigate to `http://localhost:3000`.  

## ✍️ Usage  
1. Add family members using the input form.  
2. Record visited countries for each member.  
3. Use the dashboard to view members and their respective travel histories.  

## 📂 Project Structure  
```
family-travel-tracker/  
│  
├── app.js            # Main application file  
├── public/           # Static assets (CSS, images)  
├── views/            # HTML templates  
├── routes/           # Express.js routes  
├── package.json      # Project metadata and dependencies  
└── README.md         # Project documentation  
```  

## 🌟 Future Enhancements  
- 🗑️ Add the ability to remove members or visited countries.  
- 📊 Include analytics to show the most visited countries.  
- 🗺️ Integrate a map to visualize each member's travels.  

## 🤝 Contributing  
Feel free to fork this project, create a branch, and submit a pull request. Contributions are always welcome!  

## 📜 License  
This project is licensed under the MIT License.  

---  

🎉 **Explore the world with your family and keep track of your adventures!** 🌍  


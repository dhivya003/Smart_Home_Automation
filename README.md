🏠 Rule-Based Context-Aware Smart Home Automation

🚀 Overview

This project is a context-aware smart home automation system that uses rule-based logic to automate appliances and tasks. By considering contextual information such as time, user preferences, and environmental conditions, the system enhances convenience, energy efficiency, and personalization in modern smart homes.

✨ Features

Context Awareness: Automates appliances based on time, user location, and environmental conditions.

Rule-Based System: Allows users to define custom rules for appliance behavior.

Dynamic Decision Making: Automatically adapts to changes in context (e.g., turning off lights when a room is unoccupied).

Database-Backed: Stores rules, context data, and logs using SQLite.

User Interface: A simple dashboard to configure rules and monitor activity.


📊 Database Design

Database: SQLite

Tables:

users: Stores user credentials for secure access.

rules: Stores user-defined rules for automation (e.g., "Turn on lights at 7 PM").

context: Logs contextual data such as temperature, humidity, and user presence.

logs: Records device activity for analysis.


🚧 How to Use

Define Rules:

Use the dashboard to create automation rules (e.g., Turn off fan if temperature < 20°C).
                                              
Monitor Context:
                                              
Context data such as temperature, time, and room occupancy is updated automatically.
                                              
Control Devices:
                                              
Devices respond automatically to rules or can be manually controlled through the dashboard.
                                              
View Logs:
                                              
Check logs to review past device activity and context data.
                                              
🛠️ Technologies Used
                                              
Programming Language: Python
                                              
Database: SQLite
                                              
Libraries:
                                              
Flask (for web-based interface)
       
SQLite3 (for database management)
         

🔍 Future Enhancements
Machine Learning Integration: Predict user preferences and automate rule creation.
         
Voice Commands: Add support for Alexa or Google Assistant.
         
IoT Device Integration: Interface with hardware like Arduino or Raspberry Pi for advanced automation.

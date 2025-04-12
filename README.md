💻 Development Environment Setup (Windows)

To run this project locally on a Windows machine, follow the steps below:
✅ 1. Install Java Development Kit (JDK)

    Download and install JDK 17 or higher:
    🔗 Oracle JDK Downloads

✅ 2. Install an IDE (Recommended: Eclipse)

    Download Eclipse IDE for Enterprise Java Developers:
    🔗 Eclipse Downloads

    During setup, make sure to link it to your JDK installation path.

✅ 3. Install Spring Tools in Eclipse

    Launch Eclipse.

    Go to Help > Eclipse Marketplace.

    Search for Spring Tools.

    Click Install on the latest version.

    Restart Eclipse when prompted.

📸 Guide with screenshots:
🔗 How to Install Spring Boot in Eclipse
✅ 4. Install MySQL Server

    Follow this tutorial to install MySQL on Windows:
    🔗 MySQL Installation Guide

✅ 5. Install MySQL Workbench

    GUI tool to manage and run SQL scripts:
    🔗 Download MySQL Workbench

✅ 6. Install Lombok (for annotations like @Data, @Builder, etc.)

    Download the Lombok jar:
    🔗 Lombok Download

    Run the JAR and follow prompts to integrate it with Eclipse.

📸 Setup Guide:
🔗 Lombok IDE Integration
✅ 7. Open MySQL Workbench and Connect to Your Local Instance
✅ 8. Run SQL Scripts (Included in the Git Repository)

Use MySQL Workbench to run the following .sql files found in the repo:
Script File							Purpose
dietplannerdb_script.sql			Creates the database schema
meals_script.sql					Populates the database with meal data
GetUserMealPlans_storedproc.sql		Adds stored procedure for meal plan display
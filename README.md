# Data Assets Management in Raspberry Pi
The main painpoint I want to address by this initiative is to better organize my data assets, as well as keep a clear picture of the backup strategy of the important datasets.

The initial idea behind this project is to come up with a web-based solution self hosted in a Raspberry Pi 5 in my local network that allows me to keep my data assets on track,
having a proper inventory of them in a general sense.

Possible Implementations:
🚀 1. Rclone + SQLite (DIY Solution)
🧭 2. Recoll (Search & Indexing)
📂 3. Tracker (File Indexer)
🛠️ 4. Pika Backup + Manual Index
✏️ 5. DIY Script (Simple & Customizable)

Ideas/Tasks:
* Choose a name for the project.
* Design a DB to support the Website/App.
* Create a simple DB initially stored in SQLLite to keep the inventory of the data assets, providing the expect functionality in the app.
* Have web-based functionality + Android App, basic authentication.
* Have a script for files scan retrieving OS metadata for them and creating the first view / updating existing records as needed (to be executed periodically in the source devices).
* Mockup a simple personal devices/storages architecture to understand the starting point.
* Mockup a simple design of the solution to display the picture I have in mind for the final product.
* Create a simple web app and host it in the raspberry Pi.
* Integrate a backup strategy (out of the scope of the project but highly related to the need to solve).
* Scale the DB as needed and think about migration when the time comes but start lighweight first.

Expected functionalities:
* Present a simple UI to manage Digital Assets, name to come!
* Retrieve all data assets (folders/files of any type) in a given device/storage unit/network drive) inventory using a Python script which syncronizes to the main DB stored in the Raspberry Pi.
* Leverage AI tools to get insights about the data assets (for the sake of having fun).
* Track storage devices lifespan to predict possible point of failure for each to prevent 

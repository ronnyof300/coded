🚀 Steps to Run Coded
🔧 1. Install Node.js and npm
•	Download and install Node.js (which includes npm) from:
https://nodejs.org/
Check versions to confirm:
bash
CopyEdit
node -v
npm -v
 
📦 2. Clone or Copy Your Project Folder
If using Git:
bash
CopyEdit
git clone <your-repo-url>
cd <project-folder>
Or manually copy the folder to the new machine.
 
📁 3. Navigate to Project Directory
bash
CopyEdit
cd your-project-folder
 
📥 4. Install Dependencies
Install all required packages from package.json:
bash
CopyEdit
npm install --legacy-peer-deps
Use --legacy-peer-deps if you previously needed it due to version conflicts.
 
🔨 5. Build the App (For Production)
bash
CopyEdit
npm run build
This creates the .next folder for production.
 
▶️ 6. Start the App
bash
CopyEdit
npm start
Visit your app at http://localhost:3000.
 
🛠️ (Optional) 7. Run in Development Mode
If you want live reload and debugging:
bash
CopyEdit
npm run dev
 
🧪 Quick Test Command Set
bash
CopyEdit
node -v
npm -v
cd my-v0-project
npm install --legacy-peer-deps
npm run build
npm start
 


Click https://github.com/ronnyof300/JEOUN-TRANSPORT-SERVICE

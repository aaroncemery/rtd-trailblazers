🚌 Trailblazer – Sanity CMS
Welcome to the Trailblazer project! This repository contains the Sanity CMS configuration for managing bus routes, stops, schedules, and related data. This serves as the content backend for the Trailblazer platform.

🚀 Getting Started
1️⃣ Prerequisites
Ensure you have the following installed on your machine:

Node.js (Latest LTS recommended) → Download
pnpm (Recommended) → Install via npm install -g pnpm
Sanity CLI → Install via npm install -g @sanity/cli
A Sanity project (Ask the team for project details)
2️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/your-org/trailblazer-sanity.git
cd trailblazer-sanity
3️⃣ Install Dependencies
sh
Copy
Edit
pnpm install
4️⃣ Connect to the Sanity Project
If this is your first time setting up, link the repo to the Sanity project:

sh
Copy
Edit
sanity login
sanity link
Ask the team for the correct Sanity project ID if needed.

5️⃣ Start the Studio
Run the following command to launch the local Sanity Studio:

sh
Copy
Edit
pnpm dev
This will open the studio at http://localhost:3333.

📁 Project Structure
bash
Copy
Edit
/sanity.config.ts  # Main Sanity config file
/schemas/          # All schema definitions (routes, buses, stops, etc.)
/plugins/          # Custom plugins (if any)
/deskStructure.ts  # Customization for the Sanity desk UI
🏗 Features
Bus Route & Stop Management 🏁
Schedules & Driver Assignments 📆
Sanity CMS for easy content updates ✨
Custom roles & permissions 🔐
📌 Next Steps
Add more schemas for additional features
Customize the Sanity Studio UI
Set up webhooks for real-time updates
🤝 Contributing
Create a feature branch: git checkout -b feature-name
Commit your changes: git commit -m "Added new schema"
Push to the repo: git push origin feature-name
Open a Pull Request 🚀
💬 Questions?
Reach out on Slack or tag @your-name in GitHub issues.

Happy coding! 🚀


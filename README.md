# 🚌 Trailblazer – Sanity CMS (Starter Repo)

This repository serves as a **starting point** for the **Sanity CMS** configuration for the Trailblazer project. It contains initial schemas and ideas that the team can reference as they set up their own Sanity instance in the main repository.

---

## 🚀 Purpose of This Repo

This repo is **not** the main working repo for Trailblazer. Instead, it provides:

- ✅ **Example schemas** to help structure content for routes, buses, stops, and schedules.  
- ✅ **Initial setup and configuration** for Sanity Studio.  
- ✅ **A place to explore and iterate** on Sanity's structure before finalizing the main implementation.  

The team should take what they need from here and integrate it into their own repo.

---

## 📂 What's in This Repo?

```sh
/sanity.config.ts  # Base Sanity config file
/schemas/          # Example schemas (routes, buses, stops, schedules, etc.)
/plugins/          # Any useful Sanity plugins or customizations
/deskStructure.ts  # Example custom desk UI structure
```
## 🛠 How to Use This Repo
### 1️⃣ Clone this repo locally
```sh
git clone https://github.com/your-org/trailblazer-sanity.git
cd trailblazer-sanity
```
### 2️⃣ Install dependencies
```sh
pnpm install
```
### 3️⃣ Start the local Sanity Studio
```sh
pnpm dev
```
This will open the studio at http://localhost:3333.

### 4️⃣ Review & Copy what you need

- Modify and experiment with schemas.
- Take relevant parts and integrate them into the main working repo.

## 🔄 Keeping Things Up to Date
Since this is a reference repo, updates will be made as needed to refine schemas or provide new ideas. The main working repo will have its own active development process.

## 🤝 Questions?
For any questions, reach out on Slack or open a discussion in the main repo.

Happy building! 🚀

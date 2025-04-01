🧹 Microsoft Fabric Lakehouse Maintenance Automation
This repository provides a ready-to-use solution to automate maintenance tasks in a Microsoft Fabric Lakehouse environment using the Semantic Link Labs library.

🚀 Overview
The core of this solution is the LakehouseMaintenance notebook. It enables you to:

Discover all tables in your Lakehouse.

Analyze each table's maintenance needs, such as whether it should be optimized or vacuumed.

Automatically execute the necessary maintenance actions using helper functions from the Semantic Link Labs library.

This ensures your Lakehouse remains performant, lean, and cost-efficient—without manual intervention.

📽️ What Does "Optimize" Look Like?
Here's a quick visual of the optimize operation in action. Small parquet files are compacted into larger, more efficient ones:

![Optimize_Gif-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/19fb4523-2be2-404a-bea1-8549e248a807)

This helps improve performance and reduce unnecessary overhead in your Lakehouse tables.

📂 Repository Contents
LakehouseMaintenance.ipynb – The main notebook that orchestrates the maintenance workflow.

README.md – You’re reading it!

Optimize_Gif-ezgif.com-video-to-gif-converter.gif – A demo of the optimize operation.

(Optional) Any helper modules or configuration files.

🧠 How It Works
The notebook inspects all tables using Semantic Link Labs functionality.

Each table is evaluated:

Small file count and size → optimize.

Presence of logically deleted files → vacuum.

Actions are executed automatically and logged.

🧰 Prerequisites
Microsoft Fabric workspace access.

Lakehouse with available tables.

Semantic Link Labs installed or available via Fabric Notebooks.

🔧 Setup & Usage
Clone this repository or import the notebook into Microsoft Fabric.

Ensure Semantic Link Labs is available.

Open and run LakehouseMaintenance.ipynb interactively or on a schedule.

📚 About Semantic Link Labs
Semantic Link Labs is a Microsoft-supported open-source project that enables semantic access to your data estate.
🔗 View the GitHub Repo

💬 Feedback & Contributions
Have suggestions, ideas, or found an issue?
Feel free to open an issue or submit a pull request. Contributions are very welcome!

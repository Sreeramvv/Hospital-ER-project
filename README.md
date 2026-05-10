
# Hospital-ER-project using Power BI and Claude AI
Developed an end-to-end Microsoft Power BI dashboard for Hospital Emergency Room analytics using a dataset of 9,192 patient records. The project involved analyzing patient demographics, wait times, satisfaction scores, department referrals, and admission patterns to identify operational trends and support data-driven decision-making for hospital management.

🤖 AI Integration — Claude AI & MCP
This project was built using Claude AI connected to Power BI via Model Context Protocol (MCP).
What is MCP?
Model Context Protocol (MCP) is an open standard developed by Anthropic that allows AI models to connect directly to external tools and data sources. It enables Claude to interact with Power BI's data model in real time.
How it was used

Power BI Modeling MCP Server was set up in VS Code
Claude connected to the live Power BI Desktop instance via a local port
Claude could create measures, build tables, run DAX queries and explore the model — all through natural language instructions

What Claude did via MCP

✅ Created the Calendar table with 7 columns
✅ Built all 10 DAX measures
✅ Ran DAX queries to extract insights
✅ Managed and moved measures between tables
✅ Explored and summarized the data model

<img width="3116" height="1284" alt="image" src="https://github.com/user-attachments/assets/81e7280f-cbcf-4988-9387-f4360c5c793e" />


💡 What can you do?
🔄 Build and Modify Semantic Models with Natural Language - Tell your AI assistant what you need, and it uses this MCP server to create, update, and manage tables, columns, measures, relationships, and more... across Power BI Desktop and Fabric semantic models.

⚡ Bulk Operations at Scale - AI applications can execute batch modeling operations on hundreds of objects simultaneously — bulk renaming, bulk refactoring, model translations, or model security rules - with transaction support and error handling, turning hours of repetitive work into seconds.

🔍 Query and Validate DAX - AI assistants can execute and validate DAX queries against your model, helping you test measures, troubleshoot calculations, and explore your data

<img width="1412" height="787" alt="Hospital ER Project" src="https://github.com/user-attachments/assets/14287f52-b81b-40ed-820c-1ec65013f68e" />


📈 Key Insights
👥 Patient Demographics

Gender: Nearly equal split — Male 51.2% (4,705) and Female 48.8% (4,487)
Age Groups: Adults 59.8% | Children 21.4% | Seniors 18.8%
Race: White (2,566) is the largest group, followed by African American (1,945)

⏱️ Wait Times

Overall average wait time is 35.25 minutes
Wait times are consistent across all racial groups — indicating equitable care delivery
Native American patients had the highest average wait at 35.7 min
Pacific Islander patients had the lowest at 34.6 min

🏥 Admissions & Referrals

50% admission rate — half of all ER visits result in hospital admission
58.6% of patients had no referral — treated directly in the ER
Top referral departments: General Practice (1,834) and Orthopedics (992)

⭐ Satisfaction

Average score of 5.0/10 — indicates significant room for improvement in patient experience
Reducing wait times is likely the key lever for improving satisfaction

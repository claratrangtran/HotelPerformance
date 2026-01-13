  ## 🏨 Hotel Performance & Commercial Strategy Dashboard
### 🎯 1. Business Problem
In the fast-paced hospitality industry, Account Managers (AMs) often struggled to have data-backed commercial conversations with hotel partners.

The Challenge:

Lack of Granularity: No internal tool existed to provide specific, actionable insights (pricing, availability, timeslot performance).

Low Influence: Without data, it was difficult to convince partners to adjust their pricing or availability strategies.

Efficiency: AMs needed a "on-the-go" tool for daily calls or annual performance recaps.

The Solution: I developed this interactive dashboard to bridge the gap between raw data and commercial action, drawing from my previous industry experience to create a user-centric reporting tool.

### ⚙️ 2. The Process
To ensure the tool was both accessible and lightweight, I designed a pipeline that balanced manual control with automated visualization:

Data Extraction: Raw performance data is exported from Tableau.

Centralization: Data is imported into Google Sheets, which serves as the engine for the dashboard.

User Experience: I implemented a dynamic dropdown list (Hotel Name) allowing AMs to switch between partners instantly, updating all visualizations.

Maintenance: To keep the data fresh, a weekly update process was established (managed by a dedicated intern) to re-upload the core data files, ensuring the AMs always had current insights.

### 📊 3. Understanding the Visualizations

<img width="1002" height="666" alt="Dashboard for hotel performance" src="https://github.com/user-attachments/assets/4f169597-1200-400f-a4d5-349c3cbf03f1" />

This dashboard provides a 360-degree view of hotel health. Here is how to interpret the key metrics:

Sales by Timeslots & Room Type: Identifies when and what guests are booking. This helps AMs advise hotels on which room types to promote during specific times of the day.

Market Share Trend: A line graph showing the hotel’s "slice of the pie." A dip here is a red flag that competitors are capturing the hotel's potential guests.

Hotel Sales vs. City Sales: Benchmarks the partner's growth against the overall city trend. If the city is growing but the hotel is flat, there is an underlying issue with visibility or pricing.

AOV (Average Order Value) Comparisons: * vs. Same Star Standard: Crucial for pricing. If the hotel's AOV is significantly lower than other 3-star hotels (as seen in the red bars), the partner is likely underpricing their rooms.

vs. City Market: Provides a broader macro-view of the hotel's positioning.

The Popular Timeslots: A granular breakdown of demand peaks. This allows AMs to suggest "Flash Sales" or "Happy Hour" pricing during low-demand slots to maximize occupancy.

### 🚀 4. Results & Further Development
The impact of this tool went far beyond a simple spreadsheet:

High Adoption: The dashboard became the primary tool for the AM team and received high praise from hotel partners for its clarity.

Global Scaling: Following the success of the NYC pilot, I scaled the tool to include markets in Asia, Germany, and France.

Empowerment: I conducted specialized training sessions for a team of 10 Account Managers, teaching them how to translate these charts into "sales pitches."

Integration: Recognizing the value of the logic I created, I collaborated with the Central Data Team to migrate this logic into the official Company Tableau Dashboard, making the data live and accessible to the entire organization.

### 🛠️ Tech Stack
Data Source: Tableau

Processing: Google Sheets (Query, VLOOKUP, Pivot Tables)

Visualization: Google Sheets Charts

### 📬 Let's Connect!
If you have questions about the logic behind these KPIs or how to build commercial tools in Google Sheets, feel free to reach out!

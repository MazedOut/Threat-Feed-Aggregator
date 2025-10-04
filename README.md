# Threat-Feed-Aggregator (Google Sheets + Apps Script)
A low-code threat intelligence aggregator that automatically fetches Indicators of Compromise (IOCs) such as IP addresses, URLs, domains, and file hashes from public threat feeds like URLhaus and FeodoTracker. The tool normalizes and deduplicates the collected data, storing it in a Google Sheet with source information and timestamps.

## Features
- Automated fetch of threat intelligence feeds
- Deduplication of indicators
- Stores IOCs with source & timestamp
- Summary tab showing counts by type
- Optional web app deployment for one-click run

## How to Use

1. Open the Google Sheet.
2. Extensions → Apps Script → paste the `Code.gs`.
3. Run `fetchAndStoreFeeds()` once and authorize.
4. Optional: Deploy as Web App:
   - Deploy → New deployment → Web app
   - Execute as: Me
   - Access: Anyone
   - Visit the provided URL to run the aggregator.

**Important:**  
To allow others to see changes in real-time:
- Share the Google Sheet: File → Share → “Anyone with the link can view”.
- Now anyone running the web app can see the updated IOCs in the Sheet via the link.

## Demo
- Web App: https://script.google.com/macros/s/AKfycbwNMiytuI9L74XwJ3Ic_3AtDyQO3EbnaQ3eVG0gYIhJ6Tg-kWYYNn_BDq9JEeQWRaBP/exec
- Sheet: https://docs.google.com/spreadsheets/d/1ssMykPh4QeCql5x0AVSh-YVxGu8N9H6HBLY14Wci1eA/edit?usp=sharing

-Run the link of Web App : It runs the codes and fetches the data (might take a while) 
-The changes can be seen in the Sheet (click the link to see changes)
 



# Kalshi Recorder
- Goal: Build a reliable recorder for Kalshi Market Data
- Initial MVP: Record a single market to expiry
- Future Plans: Record repeating contracts, simple backtesting engine
- Tech Stack: Bash & Python

| | **Urgent** | **Not Urgent** |
|---|---|---|
| **Important** | **Do — MVP** <br><br> - Connect to Kalshi API <br> - Fetch and save orderbook snapshots <br> - Continuous recording | **Schedule — V2.0+** <br><br> - Handle API errors and interruptions <br> - Validate data <br> - Support recurring 15-minute markets <br> - Basic backtester |
| **Not Important** | **Delegate — Use a Library** <br><br> - Terminal output formatting | **Delete — Cut It** <br><br> - GUI <br> - Trading execution |

# Flowchart
![flowchart](/KalshiRecorderFlowChart.png)

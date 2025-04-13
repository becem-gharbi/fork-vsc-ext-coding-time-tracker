<div style="display: flex; align-items: center;">
    <img src="icon-sctt.png" alt="Simple Coding Time Tracker Icon" width="100" style="margin-right: 20px;">
    <h1>Simple Coding Time Tracker: A Visual Studio Code Extension</h1>
</div>

Simple Coding Time Tracker is a powerful extension for Visual Studio Code that helps you monitor and analyze your coding time. If you are curious about your coding habits, this extension covers you.

## Features

- **Automatic Time Tracking**: Seamlessly tracks your coding time in the background.
- **Project-based Tracking**: Organizes time data by project for easy analysis.
- **Status Bar Display**: Shows your today's total coding time duration in real-time.
- **Tooltip on Status Bar**: Shows the total coding time weekly, monthly, and all time basis.
- **Detailed Summaries**: View comprehensive reports of your coding activity. You can search your total time on a particular day or project.
- **Data Persistence**: Safely stores your time data for long-term analysis.
- **Configurable Settings**: 
  - Save Interval: Customize how often your coding time data is saved (default: 5 seconds)
  - Inactivity Timeout: Set how long to wait before stopping the timer when no activity is detected (default: 5 minutes)

## Screenshots
### Status Bar
Status bar resets to zero at midnight each day and hence shows the coding time for the current day.
![Status Bar](./images/statusbar.png)

### Tooltip
Tooltip shows the total coding time weekly, monthly and all time basis.
![Tooltip](./images/tooltip.png)

### Summary page
The summary page provides a detailed report of your coding activity. You can search your total time on a particular day or project.

![Summary page ](https://raw.githubusercontent.com/twentyTwo/static-file-hosting/main/vsc-ext-coding-time-tracker-files/Simple-Coding-Time-Tracker.gif)

### All Command Palette Commands
There are total 3 commands in the command palette available for this extension.

1. SCTT: Show Coding Time Summary
2. SCTT: Reset Coding Timer for Today
3. SCTT: Reset All Coding Timers

![All Command Palette Commands](./images/commands.png)

## Installation

1. Open Visual Studio Code
2. Go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X on macOS)
3. Search for "Simple Coding Time Tracker"
4. Click "Install"

## Usage

Once installed, the extension will automatically start tracking your coding time. You can view your current session time in the status bar at the bottom of the VSCode window.

To access detailed summaries and reports, use the command palette (Ctrl+Shift+P or Cmd+Shift+P on macOS) and search for "SCTT" to see available commands.

### Configuration Options

You can customize the extension's behavior through VS Code settings:

1. Open VS Code Settings (Ctrl+, or Cmd+, on macOS)
2. Search for "Simple Coding Time Tracker"
3. Available settings:
   - **Save Interval**: How often to save your coding time data (in seconds)
     - Default: 5 seconds
     - Lower values provide more frequent updates but may impact performance
     - Higher values are more efficient but update less frequently
   - **Inactivity Timeout**: How long to wait before stopping the timer when no activity is detected (in minutes)
     - Default: 5 minutes
     - Lower values will stop tracking sooner when you're not actively coding
     - Higher values will continue tracking for longer during breaks

### Available Commands

The extension provides the following commands through the Command Palette:

- **Show Summary** (`SCTT: Show Coding Time Summary`): 
  Displays a comprehensive summary of your coding activity, including total time invested in projects and a daily breakdown.

- **Reset Timer for Today** (`SCTT: Reset Coding Timer for Today`): 
  Resets the coding time tracker for the current day, allowing you to start anew.

- **Reset All Timers** (`SCTT: Reset All Coding Timers`): 
  Resets all coding time trackers with a confirmation prompt to prevent unintended resets.

## Changelog

### [0.2.3] - 2025-03-19
- Made the save interval configurable by the user, with a default of 5 seconds.
- Updated the documentation to reflect the new configuration option.

### [0.2.2] - 2024-10-04
- Added command to reset all timers
- Added a command to reset daily timer

### [0.2.1] - 2024-10-02
- Enhanced the UI of the summary view for a more professional look
- Implemented date range search functionality
- Added a reload button to reset search fields and refresh data
- Improved the layout and styling of the Total Coding Time section

### [0.1.4] 
- Initial release
- Automatic time tracking
- Project-based tracking
- Status bar display with tooltip
- Detailed summary view
- Data persistence

## Feedback and Contributions

We welcome feedback and contributions! If you encounter any issues or have suggestions for improvements, please open an issue on our GitHub repository.

For developers interested in contributing to the project, please check out our [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines and instructions.




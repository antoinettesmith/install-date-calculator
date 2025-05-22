# 📅 Install Date Calculator

An interactive, browser-based tool that helps teams calculate onboarding and install timelines by accounting for weekends, holidays, and contract intervals. Built with HTML, CSS, and vanilla JavaScript, this tool is ideal for onboarding, sales, or implementation teams that need to manage client installation timelines with precision.

## 🛠️ Features

- **Interactive Calendar:** Users can select any calendar date to anchor their calculation.
- **Interval Selection:** Choose a preset interval (30, 60, or 90 days).
- **Holiday Exclusion:** Automatically skips weekends and predefined holidays or company closure periods.
- **Notice Date Calculation:** Calculates a backdated "Notice Date" based on the selected interval.
- **Responsive UX:** Lightweight and easy to deploy without dependencies.

## 📋 Use Case

Originally developed to support internal Sales and Onboarding teams, this tool streamlines install scheduling by factoring in non-working days. It's useful for:
- Client onboarding
- Contract start date calculations
- Sales planning and implementation workflows

## 💡 Customization

To adapt the calculator for your organization:
- Replace the values in the `holidays` array with your own national/company holidays.
- Modify the `dateRanges` variable to block off periods like end-of-year closures.
- Extend the script to include additional logic (e.g., region-based calendars or API integration).

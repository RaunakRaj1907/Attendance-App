# Attendance-App
Attendance tracker that lets you upload your Excel timetable and mark attendance day by day, with automatic per-subject tracking.
# 📅 Attendance Tracker

A simple attendance app for students. Upload your class timetable as an Excel file, then mark attendance day by day, with no manual setup for subjects or schedules.

## ✨ Features

- 📤 **Excel timetable upload**: import your weekly schedule from an `.xlsx` file
- ✅ **Day-by-day marking**: mark each class as present, absent, or [cancelled/holiday]
- 📊 **Attendance overview**: [per-subject percentage / total classes attended]
- 💾 **Saved data**: [localStorage / database] so your records persist
- 📱 [Responsive design / works on mobile and desktop
  

## 🚀 Getting Started

### Prerequisites

- [Node.js 18+ / Python 3.x / a modern browser]

### Installation

```bash
git clone https://github.com/[your-username]/[repo-name].git
cd [repo-name]
[npm install]
[npm start]
```

Then open `http://localhost:[port]`.

## 📑 Timetable Excel Format

Your Excel file should look like this:

| Day       | 9:00–10:00 | 10:00–11:00 | 11:00–12:00 |
|-----------|-----------|-------------|-------------|
| Monday    | Maths     | Physics     | Lab         |
| Tuesday   | English   | Maths       | Chemistry   |

> Update this table to match the format your app actually expects. A sample file is in `/sample/timetable.xlsx`.

## 🛠️ Built With

- [Frontend: e.g. React / HTML, CSS, JS]
- [Excel parsing: e.g. SheetJS / pandas / openpyxl]
- [Storage: e.g. localStorage / SQLite / Firebase]

## 🤖 AI Disclosure

This project was built with the help of AI tools. I designed the idea and features, tested the app, and iterated on the result. I'm still learning the codebase and improving it as I go.

## 🗺️ Roadmap

- [ ] Attendance percentage alerts (e.g. below 75%)
- [ ] Export attendance report
- [ ] Edit timetable inside the app
- [ ] [Your idea]

## 🤝 Contributing

Suggestions and pull requests are welcome. Open an issue first to discuss what you'd like to change.


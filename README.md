# 🎉 Stark Labs – Event JSON Panel

A mini dashboard UI to create and manage **event offers** for Stark Labs, with auto JSON generation for limited-time promotions and campaigns.

## ⚙️ Built With

- HTML5 + TailwindCSS
- Pure Vanilla JavaScript
- Mobile responsive layout
- Dark mode supported

## 🛠 Features

- Input form for:
  - Event title
  - Description
  - Discount
  - Start/End Dates
  - Tag system (comma-separated)
- Image path auto-suggestion via ID
- Real-time preview of output JSON
- Easy copy & paste

## 📁 Folder Structure
```
event-json-panel/
├── index.html
├── /events/
│ └── event-id/
│ └── 1.png
```

## 📊 Event JSON Fields

| Field       | Description                        |
|-------------|------------------------------------|
| id          | Event folder name (e.g., `event-1`)|
| title       | Title of the event                 |
| description | Event description text            |
| discount    | e.g., "15%" or numeric             |
| from        | Start date in ISO format           |
| to          | End date in ISO format             |
| image       | Auto path (e.g., `events/id/1.png`)|
| tags        | Comma-separated, optional tags     |

## 🚀 How to Use

1. Fill the event form.
2. Click **Generate JSON**.
3. Copy the output and paste it into your data file.

---

© 2025 Stark Labs. All rights reserved.

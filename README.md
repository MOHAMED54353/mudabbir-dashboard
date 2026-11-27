# مدبّر | Mudabbir 

> **إدارة أموالك بذكاء**

##  Features

- **Sidebar:** sticky navigation with quick actions (send money, add money, pay a bill, invest).
- **Navbar:** connection status, search and notification icons, and user profile.
- **Statistics:** current balance, income, and expenses.
- **Recent activity:** latest account and card events.
- **Monthly bills:** bill cards with color-coded due dates.
- **Recent transactions:** table with categories, statuses, and amounts.
- **Budget overview:** progress bars for each spending category.
- **Income vs. expenses:** weekly bar chart made with CSS only.
- **Account summary:** current account, savings account, and credit card.
- **Payment methods:** 3D flip cards on hover.

##  Built With

- HTML5 (semantic elements)
- CSS3 (Flexbox, Grid, transitions, 3D transforms, media queries)
- [Font Awesome](https://fontawesome.com/) for icons
- [IBM Plex Sans Arabic](https://fonts.google.com/specimen/IBM+Plex+Sans+Arabic) from Google Fonts

No JavaScript, frameworks, or build tools.

## Project Structure

```text
assignment-4-mudabbir/
├── css/
│   └── style.css        # Entry point, imports the files below
    ___ header.css           # Base styles, sidebar, navbar, statistics
    ___ transaction.css      # Activity, monthly bills, transactions table
├   ___ summary.css          # Budget, chart, accounts, payment cards

├── imgs/                # Avatar & user images
├── index.html
└── README.md
```

##  Responsive Breakpoints

| Screen width | Layout changes |
|---|---|
| `1239px` and below | Dashboard becomes one column, summary becomes two columns |
| `991px` and below | Navbar wraps, statistics and summary become one column |
| `767px` and below | Sidebar is hidden |

##  Getting Started

1. Clone or download the repository.
2. Open the `assignment-4-mudabbir` folder in VS Code.
3. Right-click `index.html` and choose **Open with Live Server**.

You can also open `index.html` directly in the browser. An internet connection is needed to load the icons and fonts.

##  Notes

This is a static UI: all figures and transactions are sample data, and the buttons and links are not functional yet.

## 👤 Author

**MEDO**, Frontend Developer
# Productivity Hub Pro - To-Do & Journal

## Overview

*Productivity Hub Pro* is an all-in-one web-based productivity tool that combines a smart To-Do list, customizable daily Journal, Dashboard analytics, and a visual Calendar. It features an interactive, modern UI/UX and offers powerful export and theme options. Written in pure HTML, CSS, and JavaScript—no frameworks or backend required.

***

## Features

- *Tabbed Navigation*: Seamlessly switch between To-Do, Journal, Dashboard, and Calendar views.
- *To-Do List*:
  - Add tasks with priority, date, and repeat options (None/Daily/Weekly).
  - Edit, complete/un-complete, reorder, or delete tasks.
  - Drag-and-drop for easy task management.
  - Filter tasks into Pending and Completed sections.
  - Export tasks as CSV or PDF.
- *Journal*:
  - Write daily entries, choose moods/emojis, and customize font and background.
  - Edit or delete entries any time.
  - Handy theme and font switching (Light/Dark/Pink gradients; 4 font options).
  - Export journal entries as CSV or PDF.
  - Track mood history and maintain writing streaks.
- *Dashboard*:
  - See total, pending, and completed tasks at a glance.
  - Current writing streak counter.
- *Calendar View*:
  - See which days include journal entries in a monthly grid.
  - Click a date to view entries for that day.
- *Theme Switcher*:
  - Toggle between Light and Dark modes, persisted via local storage.
- *Offline & Secure*:
  - All data is saved in your browser's localStorage—no server or account required.

***

## Getting Started

1. *Clone or Download* this project as a single HTML file.
2. *Open* it in your web browser. No installation or dependencies needed.

***

## File Structure

- *HTML*: All structure and logic in a single .html file.
- *CSS*: Responsive, modern styling included in a <style> tag.
- *JavaScript*: Fully contained via <script>. No frameworks; uses only DOM APIs.
- *External Libraries*: Loads [jsPDF](https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js) for PDF export.

***

## How It Works

- *Data Persistence*: Tasks and journal entries are saved in localStorage to keep your data even after refreshing or closing the tab.
- *Interactivity*: All actions—adding tasks/entries, switching themes, editing, exporting, etc.—require no page reloads.

***

## Usage

### To-Do Section

- Enter a *Task, select **Priority, set a **Date* and *Repeat* option.
- Click *Add* to save.
- Edit, mark complete/incomplete, or delete any task.
- Export tasks with the *Export CSV* or *Export PDF* buttons.

### Journal Section

- Pick a *Theme, **Font, and **Mood*.
- Write your entry and click *Save*.
- Edit or delete any entry.
- Export journal via *Export CSV* or *Export PDF*.

### Dashboard

- Check the summary of your productivity and current journal streak.

### Calendar

- View a monthly grid. Click a day to see all journal entries for that date.

***

## Customization

- *Themes*: Toggle Dark/Light mode (with persistence).
- *Journal Colors/Fonts*: Choose different gradients and fonts for the journal area.

***

## Browser Compatibility

Tested on all modern browsers (Chrome, Firefox, Edge). Requires ES6 support and localStorage.

***

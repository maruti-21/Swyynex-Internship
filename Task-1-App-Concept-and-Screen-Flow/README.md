# FocusFlow — App Concept and Screen Flow

## SWYNEX Technologies Internship — Task 1

FocusFlow is a simple productivity and focus-management Android application designed to help students and users organize their daily tasks, monitor progress, and maintain focused work sessions.

---

## 📌 Task 1 — App Concept and Screen Flow

### Task Objective

The objective of Task 1 is to define the application concept, identify the target users, establish the primary features, and design the main screen flow and navigation structure.

---

## 💡 App Concept

### FocusFlow

FocusFlow combines task management, progress tracking, and focused work sessions into a single mobile application.

Users can create and manage tasks, assign categories and priorities, track completion progress, start focus sessions, and configure basic application settings.

---

## 🎯 Problem Statement

Students and productivity-focused users often manage their daily tasks, priorities, and study sessions separately.

FocusFlow provides a simple centralized interface where users can:

- Organize daily tasks
- Set task priorities
- Categorize tasks
- Track completion progress
- Start focused work sessions
- Manage basic application preferences

---

## 👥 Target Users

FocusFlow is designed primarily for:

- 🎓 Students
- 📚 Learners preparing for exams
- 💻 College students managing assignments and projects
- 📝 Users who want a simple daily productivity tool

---

## 🚀 Key Features

- ➕ Add tasks
- ✏️ Edit tasks
- 🗑️ Delete tasks
- ✅ Mark tasks as completed
- 📂 Task categories
  - Study
  - Work
  - Personal
  - Other
- ⭐ Task priorities
- 📅 Due-date information
- 📊 Progress tracking
- ⏱️ Focus timer
- 👤 User name and personalized greeting
- 🔔 Notification settings
- ⚙️ Application settings
- 💾 Local data persistence
- ⬅️ In-app navigation

---

## 📱 Primary Screens

FocusFlow consists of the following primary screens:

### 1. Dashboard

The Dashboard is the main screen of the application.

It provides:

- Personalized greeting
- Today's progress
- Task information
- Add Task action
- Start Focus action
- Navigation to Progress
- Navigation to Settings

---

### 2. Add/Edit Task

This screen allows users to create and modify tasks.

Users can provide:

- Task title
- Description
- Priority
- Category
- Due-date information

---

### 3. Task Details

The Task Details screen displays the selected task and provides actions such as:

- View task information
- Edit task
- Delete task
- Mark task as completed

---

### 4. Progress

The Progress screen provides an overview of task completion and productivity information.

Users can use it to understand their daily progress.

---

### 5. Focus Timer

The Focus Timer provides a dedicated focused-work session.

Users can:

- Select a focus duration
- Start a timer
- Complete a focus session
- Return to the Dashboard

---

### 6. Settings

The Settings screen provides application preferences including:

- User name
- Notification controls
- Focus duration
- Clear task data
- About FocusFlow

---

## 🔄 Screen Flow

```text
                         ┌──────────────┐
                         │   Dashboard  │
                         └──────┬───────┘
                                │
          ┌─────────────────────┼─────────────────────┐
          │                     │                     │
          ▼                     ▼                     ▼
   ┌─────────────┐       ┌─────────────┐       ┌─────────────┐
   │ Add / Edit  │       │   Progress  │       │ Focus Timer │
   │    Task     │       │    Screen   │       │   Screen    │
   └──────┬──────┘       └──────┬──────┘       └──────┬──────┘
          │                     │                     │
          ▼                     │                     │
   ┌─────────────┐              │                     │
   │Task Details │              │                     │
   └──────┬──────┘              │                     │
          │                     │                     │
          └─────────────┬───────┴─────────────────────┘
                        ▼
                 ┌─────────────┐
                 │  Dashboard  │
                 └──────┬──────┘
                        │
                        ▼
                 ┌─────────────┐
                 │  Settings   │
                 └─────────────┘

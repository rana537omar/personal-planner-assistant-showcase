<p align="center"><img src="media/banner.png" alt="Personal Planner Assistant (Task & Life Planner): work and personal life in one planner, with a personal chatbot that runs on your own computer" width="100%"></p>

# Personal Planner Assistant (Task & Life Planner)

**Your work and your personal life in one planner, with a personal chatbot that runs on your own computer.** Capture tasks in plain words. Get a time-blocked plan for your day. Track habits and goals, and talk to a chatbot that knows your schedule and can change it for you once you say yes. In English and Arabic, with a pink, light blue and grey design.

> **This is a product showcase.** The Personal Planner Assistant software and its source code are proprietary and are **not** included in this repository. See [License](#license).

**Showcase website:** https://rana537omar.github.io/personal-planner-assistant-showcase/

<p align="center"><a href="https://wa.me/201208562225?text=Hello%2C%20I%20saw%20Personal%20Planner%20Assistant%20(Task%20%26%20Life%20Planner)%20and%20I%20would%20like%20to%20get%20the%20full%20system%20and%20the%20source%20code."><img src="media/whatsapp-button.svg" alt="Get the full system and source code: chat on WhatsApp, +20 120 856 2225" width="380"></a></p>

## Demo video

<p align="center"><a href="https://rana537omar.github.io/personal-planner-assistant-showcase/#demo"><img src="media/video-poster.png" alt="Watch the Personal Planner Assistant product demo (3:48)" width="100%"></a></p>

**▶ [Watch in the browser](https://rana537omar.github.io/personal-planner-assistant-showcase/#demo)** · **⬇ [Download the video (MP4, 28 MB)](https://github.com/rana537omar/personal-planner-assistant-showcase/releases/download/demo-v1/Personal-Planner-Assistant-demo.mp4)** · [Open the file on GitHub](media/Personal-Planner-Assistant-demo.mp4)

The demo is a 3 minute 48 second captioned walkthrough in 1080p, with no sound. It covers:
- the Today page and adding a task in plain words;
- **Plan my day** and the work / personal switch;
- the personal chatbot answering about your day, proposing a change and remembering a fact, plus the chat bubble on the calendar;
- splitting a task into steps, the focus timer and reminders;
- the Ctrl+K search, priority matrix, habits, routines, goals and weekly review;
- prayer-aware planning, phone access, dark mode, and Arabic with tasks typed in Arabic.

**[Watch it on the showcase website](https://rana537omar.github.io/personal-planner-assistant-showcase/#demo)**.

## The five essentials

1. **Tasks in plain words.** "Call the bank tomorrow at 10am !1 #work" becomes a task with the date, time, priority and list filled in.
2. **Plan my day.** A time-blocked schedule built around your work hours, lunch, personal time and fixed appointments.
3. **Personal chatbot.** Chat about anything. It knows your tasks, habits and goals, and it runs on local AI, so nothing leaves your computer.
4. **Work and personal, together.** Every task belongs to work or personal life. One switch shows everything, work only or personal only.
5. **Reminders.** Alerts before timed tasks, a morning briefing and an evening wrap-up, even with the planner tab closed.

## Features

### Planning
- **Today** shows your top 3, overdue items and today's tasks split into work and personal, with progress rings and today's habits.
- **Plan my day** fits tasks into your free time by priority and deadline, around lunch and fixed appointments, and adds short breaks.
- **Inbox, Upcoming and Calendar.** Drag tasks between days to reschedule them.
- **Priority matrix** (urgent / important) with drag and drop.
- **Recurring tasks**: daily, weekdays, weekly, monthly, yearly or chosen days. The next one is created when you finish the current one.
- **Optional prayer times**: the day plan works around Fajr, Dhuhr, Asr, Maghrib and Isha (Jumu'ah on Fridays), with five calculation methods.

### Personal chatbot
- **Free conversation** on local AI through Ollama (for example `gemma3:4b`). Replies stream in as they are written.
- **Knows your planner.** It sees today's plan, overdue and upcoming tasks, habits, goals, and what you asked it to remember.
- **Changes things with your OK.** Say "I have a dentist appointment tomorrow at 11am" and it lists the changes, then waits for **Yes** or **No**.
- **Memory.** "Remember that I work best in the mornings", "What do you know about me?", "Forget …".
- **Four personalities**: Friendly, Coach, Concise or Cheerful. You can rename the chatbot.
- **On every page** as a chat bubble. It can read replies aloud with your computer's own voices.
- **Planner commands**: plan my day, what's overdue, what should I focus on, break down a task, move a task to Friday, weekly review, work-life balance.

### Focus and habits
- **Focus timer** (Pomodoro) on any task. It learns how long your tasks really take and adjusts the plan.
- **Break it down** splits a task into clear steps.
- **Habits** with streaks, a 14-day grid and weekly targets.
- **Routines and templates** such as a morning routine, evening shutdown, weekly review, packing list or client onboarding, which you can start in one click.
- **Goals** fill up as you finish the tasks linked to them.
- **Weekly review**: tasks finished per day, work / personal time split, habit targets and focus time.

### Everyday comfort
- **Ctrl+K command bar**: search tasks, notes, goals, habits, routines and memories, or run any command.
- **Reminders** as in-app cards, desktop pop-ups and Windows notifications, with Done and Snooze buttons. An optional **start at sign-in** keeps the planner running in the background.
- **English and Arabic**, with a full right-to-left layout. Tasks can be typed in Arabic, like "اتصل بماما بكرة الساعة 5".
- **Dark and light modes**, on phone, tablet and desktop.
- **Install it as an app.** Open it on your phone over your home Wi-Fi with a PIN.
- **Import your calendar** (.ics from Google or Outlook), plus **backup and restore**.

### Good to know
- Open conversation needs Ollama and a local model running on the computer. Without it, every planner command still works and the chatbot gives built-in replies.
- Small local models can miss part of a long request. Every change the chatbot suggests is shown first and only happens after you confirm.
- Reminders need the planner running, in a browser tab or in the background. Windows "Do not disturb" can hold notifications back.
- Phone access works on the same Wi-Fi with a PIN. Offline use on a phone needs the planner hosted on a secure (HTTPS) address.
- Spoken replies use the voices installed on the computer. Voice input is not included, so that nothing is sent online.
- The Arabic interface covers the app's screens, and the chatbot replies in Arabic. Some built-in command replies are in English.
- Prayer times are calculated and can differ by a minute or two from a local mosque.
- The people, tasks and data in the screenshots and video are fictional demo data.

## Screenshots

### Plan your day

| | |
|---|---|
| ![Today](media/today.png) **Today**: top 3, overdue items, work and personal tasks, and the day plan. | ![Quick add](media/quick-add.png) **Quick add**: type naturally and see what was understood. |
| ![Upcoming](media/upcoming.png) **Upcoming**: the next 14 days. | ![Calendar](media/calendar.png) **Calendar**: drag tasks between days. |
| ![Priority matrix](media/matrix.png) **Priority matrix**: urgent versus important. | ![Prayer-aware plan](media/prayer-plan.png) **Prayer times**: the plan works around the five prayers. |

### Personal chatbot

| | |
|---|---|
| ![Chatbot](media/chatbot.png) **Chatbot**: knows your day and what you asked it to remember. | ![Chatbot changes](media/chatbot-changes.png) **Changes with your OK**: nothing happens until you say yes. |
| ![Chat bubble](media/widget.png) **On every page**: the chat bubble over the calendar. | ![Arabic chat](media/arabic-chat.png) **In Arabic**: the same, right to left. |

### Get it done

| | |
|---|---|
| ![Task editor](media/drawer.png) **Task editor**: steps, repeats, lists, goals and focus. | ![Focus timer](media/focus.png) **Focus timer**: Pomodoro sessions on any task. |
| ![Focus complete](media/focus-done.png) **Session complete**: logged against the task, then a break. | ![Command bar](media/palette.png) **Ctrl+K**: search everything or run a command. |
| ![Habits](media/habits.png) **Habits**: streaks and weekly targets. | ![Routines](media/routines.png) **Routines**: checklists you start in one click. |
| ![Goals](media/goals.png) **Goals**: progress from linked tasks. | ![Notes](media/notes.png) **Notes**: ideas and meeting notes. |
| ![Weekly review](media/review.png) **Weekly review**: what you finished and your balance. | ![Settings: reminders](media/settings-reminders.png) **Reminders**: briefing, wrap-up and Windows notifications. |
| ![Settings: phone and import](media/settings-phone.png) **Phone and import**: PIN access, calendar import and backups. | ![Dark mode](media/dark.png) **Dark mode**. |
| ![Arabic](media/arabic.png) **Arabic**: a full right-to-left interface. | |

<p align="center"><img src="media/phones.png" alt="Today, the chatbot, routines and the Arabic Today view on phones" width="80%"></p>

## Get the full system

Want Personal Planner Assistant for yourself, your team or your clients, a live demo, or the complete source code? Message me on WhatsApp: **+20 120 856 2225**.

<p align="center"><a href="https://wa.me/201208562225?text=Hello%2C%20I%20saw%20Personal%20Planner%20Assistant%20(Task%20%26%20Life%20Planner)%20and%20I%20would%20like%20to%20get%20the%20full%20system%20and%20the%20source%20code."><img src="media/whatsapp-button.svg" alt="Get the full system and source code: chat on WhatsApp, +20 120 856 2225" width="380"></a></p>

## License

**Copyright © 2026 Rana Omar. All rights reserved.** The text, screenshots, images and video in this repository are shared for viewing only. No license is granted to copy, reuse, modify, republish or use them, or the Personal Planner Assistant software they show, for any personal or commercial purpose. See [LICENSE](LICENSE).

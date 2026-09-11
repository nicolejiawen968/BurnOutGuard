# BurnOutGuard by FourBit

**Team:** Tan Jia Wen, Toh Xin Yi, Lim Pei Qin, Lee Sin Yee  
**Problem Statement:** Stress & Workload Manager  
**Video Presentation:** [Unlisted YouTube Link - To be added]  
**Presentation Slides:** [Public Link - To be added]

---

## 1. Project Overview

### The Problem

University students often manage multiple responsibilities at the same time, including assignments, examinations, classes, deadlines, meetings, social commitments, physical needs, and daily errands. These responsibilities can build up across different areas of student life, making it difficult for students to understand their overall workload and recognise what is contributing most to their pressure.

We identified five main workload areas:

- **Mental** – assignments, exams, academic pressure, and stress
- **Time** – classes, deadlines, meetings, and other commitments
- **Physical** – sleep, exercise, fatigue, and travelling
- **Social** – friends, family, social activities, and group events
- **Errands** – shopping, appointments, banking, and daily chores

The core problem is that students may not realise how these different responsibilities combine to create an overloaded workload. This can lead to stress, fatigue, feeling overwhelmed, reduced productivity, and a greater risk of burnout.

### Stakeholders

Our **primary stakeholders are university students**, especially those managing several academic and non-academic responsibilities at the same time. They are the direct users of BurnOutGuard and need a simple way to understand their workload and decide what they can realistically adjust.

**Secondary stakeholders** may include lecturers, academic advisors, student-support staff, and universities, who may benefit indirectly when students are better able to recognise and manage workload pressure.

### Similar Solutions and Their Limitations

**Todoist** is a general task-management tool that helps users organise tasks, deadlines, and schedules. However, it focuses mainly on task organisation rather than understanding a student's combined workload across different areas of student life.

**Sunsama** combines task and calendar planning and helps users manage their planned workload. However, it focuses mainly on time and task planning rather than identifying pressure across the five areas of student life.

These limitations create an opportunity for **BurnOutGuard** to focus specifically on university students and connect workload analysis with **pressure-point identification, practical actions, workload rebalancing, and recovery**.

### Our Solution

**BurnOutGuard** is a student-focused workload management system that helps students understand their overall workload across **Mental, Time, Physical, Social, and Errands**. It goes beyond simply tracking tasks by identifying **pressure points** and providing practical actions that students can consider to manage their workload. Students can then adjust their plan, include recovery time, and view **before-and-after results** to understand the impact of their changes. Supporting features such as mood tracking, well-being tips, and **BurnOutBuddy AI Chatbot** further support healthier student habits.

### Core Features

- **Home Dashboard** – View overall workload, workload by area, upcoming tasks, mood, and quick actions.
- **My Tasks** – Add and organise responsibilities across the five workload areas with deadlines, priorities, and progress.
- **Workload Overview** – View overall workload, workload by area, and weekly workload trends.
- **Pressure Points** – Identify the workload areas contributing most to pressure, including common triggers, related tasks, and reasons for high workload.
- **Recommended Actions** – Receive practical suggestions such as breaking tasks into smaller steps, rescheduling non-urgent tasks, or postponing lower-priority errands.
- **Adjust Your Plan** – Apply selected actions, adjust the schedule, and include dedicated recovery time.
- **Results** – Compare workload before and after adjustments and view changes across the five workload areas.
- **Mood Journal & Insights** – Record moods and reflections and view mood patterns over time.
- **Tips for a Healthier You** – Access practical guidance on stress management, time management, study habits, mental health, and lifestyle.
- **BurnOutBuddy AI Chatbot** – Provides quick tips and basic well-being guidance within the app.

---

## 2. Ideation & Process

### 2.1 Ideas We Considered

| Idea | Why It Was Dropped / Kept |
|---|---|
| **Workload Rebalancer (Chosen)** | Selected because it directly addresses the core problem of overloaded student workload by helping students identify pressure points, take action, and rebalance their responsibilities. |
| **Workload Dashboard (Improved)** | Kept as part of the final concept because it provides visibility of the student's overall workload across the five areas. However, we felt that showing workload alone was not enough, so the idea evolved into a rebalancing system. |
| **Recovery Planner (Improved)** | Kept as a supporting concept because recovery is important when managing workload. It was integrated into the workload-rebalancing process rather than being developed as a separate application. |
| **Stress Tracker** | Dropped because it mainly tracks stress without helping students identify what is causing their workload pressure or what they can change. |
| **Mood Tracker** | Dropped as the main concept because mood tracking alone does not directly address workload management. It was later retained as a supporting feature through the Mood Journal. |
| **Student To-Do List** | Dropped because it is too similar to existing task-management tools and does not address the broader problem of workload overload. |
| **Smart Calendar** | Dropped because it focuses mainly on scheduling and time management rather than understanding workload across different areas of student life. |
| **Study Planner** | Dropped because it focuses mainly on academic planning and does not address physical, social, mental, and everyday responsibilities. |

### 2.2 Ideation Boards

#### 1. Problem Exploration

![Problem Exploration](images/problem-exploration.png)

We began by exploring the different responsibilities students manage at the same time. This helped us recognise that student overload can come from multiple areas of daily life, rather than academic work alone.

#### 2. Problem Tree

![Problem Tree](images/problem-tree.png)

We broke the problem down into its main causes and effects. This showed how too many responsibilities, clashing deadlines, difficulty prioritising, and limited recovery time can contribute to **overloaded student workload**, resulting in stress, fatigue, feeling overwhelmed, reduced productivity, and risk of burnout.

#### 3. Mindmap

![Mindmap](images/mindmap.png)

We expanded the problem into five workload areas — **Mental, Time, Physical, Social, and Errands** — and identified the main difficulties students face and what they need from a workload management solution.

#### 4. Idea Evolution

![Idea Evolution](images/idea-evolution.png)

Our idea evolved through three main iterations:

**Stress Tracker → Workload Dashboard → BurnOutGuard**

The **Stress Tracker** was too narrow because it focused mainly on stress. We then developed the **Workload Dashboard** to show workload across five areas, but realised that showing the problem alone was not enough. The final **BurnOutGuard** concept evolved into a workload-rebalancing system that helps students **identify pressure points, take practical action, adjust their workload, and create space for recovery**.

#### 5. User Flow

![User Flow](images/user-flow.png)

The final user flow developed from our ideation is:

**Input Workload → Analyse Workload → Identify Pressure Points → Recommend Actions → Adjust Plan → See Results → Recovery**

This flow evolved from our initial concept into the core interaction used in the UI prototype. It guides students from understanding their workload to identifying sources of pressure, taking practical action, adjusting their plan, and seeing the impact of their changes.

### 2.3 Mentor Consultation

| Date | Mentor | Feedback Received | What Was Changed |
|---|---|---|---|
| 9 September 2026, 8:55 PM | **Jarod Tan** | The mentor found that our UI was too crowded and suggested simplifying the interface. The mentor also suggested development tools such as Supabase, Cursor, Lovable, and Next.js. | We simplified the UI layout to reduce visual clutter and improve usability. We also selected Next.js, Supabase, Cursor, and Lovable as our technology direction to support efficient and feasible development. |

---

## 3. Design & Prototype

### UI Prototype

[View the BurnOutGuard UI Prototype](UI.pdf)

The BurnOutGuard prototype translates our ideation journey into a student-focused workload management experience. The core interaction follows:

**Input Workload → Analyse → Identify Pressure Points → Recommend Actions → Adjust Plan → See Results → Recovery**

The prototype is designed around the idea that students should not only see that their workload is high, but should also understand what is contributing to the pressure and have practical ways to respond.

### Key Screens

#### 1. Home Dashboard

The Home Dashboard gives students an **at-a-glance view of their workload and well-being**. It highlights the **overall workload level**, workload distribution across the five areas — **Mental, Time, Physical, Social, and Errands** — as well as **upcoming tasks and today's mood**.

The **Quick Actions** provide direct access to adding tasks, viewing tasks, logging mood, and getting tips, while the workload analysis can be accessed directly from the dashboard.

**Key purpose:** Give students an immediate understanding of **how much they are carrying, where their workload is distributed, and what they can do next**.

![Home Dashboard](images/home-dashboard.png)

---

#### 2. My Tasks

My Tasks allows students to organise their responsibilities and connect each task to one of the five workload areas: **Mental, Time, Physical, Social, and Errands**. Each task displays its workload area and deadline, helping students see that everyday responsibilities contribute to their overall workload, not just academic tasks.

Students can also filter tasks by **All, Today, This Week, or This Month**, search for specific tasks, and quickly add new responsibilities.

**Key purpose:** Capture and organise the different responsibilities that contribute to a student's overall workload, providing the foundation for BurnOutGuard's workload analysis.

![My Tasks](images/my-tasks.png)

---

#### 3. Workload Overview

The Workload page transforms the student's tasks into an **overall workload picture**. It shows the **overall workload level**, compares it with the previous week, and breaks the workload down across the five areas: **Mental, Time, Physical, Social, and Errands**.

The **Weekly Workload Trend** helps students see how their workload changes over time. The Quick Actions also provide direct access to **Pressure Points, Recommended Actions, Adjust Your Plan, and Progress**, connecting workload analysis to the next steps of the BurnOutGuard journey.

**Key purpose:** Help students understand **how much they are carrying, where their workload is concentrated, and when they may need to take action.**

**Next step:** Students can select **View Pressure Points** to investigate what is contributing to their workload pressure.

![Workload Overview](images/workload.png)

---

#### 4. Pressure Points

After selecting **View Pressure Points** from the Workload page, students are taken to Pressure Points. This page goes beyond simply showing a workload score by identifying **which workload areas are contributing most to the student's pressure**.

It provides further context through **common triggers, related tasks, and an explanation of why the workload is high**. For example, the prototype highlights Mental workload as the highest area and connects it with factors such as exams and deadlines, high expectations, and overthinking.

**Key purpose:** Help students understand **where their pressure comes from and what is contributing to it**, so they can make informed decisions about what to change next.

**Next step:** Students can move to **Recommended Actions** to see practical ways to respond to the identified pressure points.

![Pressure Points](images/pressure-points.png)

---

#### 5. Recommended Actions

After identifying the student's pressure points, BurnOutGuard provides **practical actions that students can consider to reduce or manage their workload**. Recommendations are linked to specific workload areas and include actions such as breaking a large assignment into smaller tasks, rescheduling a non-urgent task, and postponing a lower-priority errand.

Students can select suitable recommendations using **Add to Plan**, allowing them to carry the chosen actions into the next step of the workload-rebalancing process.

**Key purpose:** Turn workload awareness into **practical, actionable changes** that students can apply to their plan.

**Next step:** Selected recommendations can be reviewed and applied in **Adjust Your Plan**.

![Recommended Actions](images/recommended-actions.png)

---

#### 6. Adjust Your Plan

After selecting suitable recommendations, students can use **Adjust Your Plan** to actively rebalance their workload. The screen allows students to review their schedule, apply selected recommendations, and include dedicated **recovery time** in their revised plan.

The **Plan Preview** summarises the adjusted schedule, including total tasks, focused study time, break time, and personal time. Students can then select **Apply Changes & View Results** to see the impact of their adjustments.

**Key purpose:** Help students turn recommendations into **real changes to their workload and schedule**, while creating space for recovery.

**Next step:** Students can apply their changes and view the **before-and-after results**.

![Adjust Your Plan](images/adjust-your-plan.png)

---

#### 7. Results

After students apply changes to their plan, the Results page shows **how their workload has changed before and after the adjustments**. It provides an overall comparison as well as a breakdown across the five workload areas.

The page also highlights **Pressure Points After Changes**, allowing students to see which areas have improved, while the detailed breakdown explains the changes made and how they contributed to the new workload.

**Key purpose:** Show students the **impact of their workload adjustments** and help them understand whether their workload has become more manageable.

**Next step:** Students can use the improved workload state as a basis for maintaining a more balanced plan and making space for recovery.

*The values shown in the prototype are illustrative examples demonstrating the intended interaction.*

![Results](images/results.png)

---

#### 8. Tips & BurnOutBuddy AI Chatbot

The **Tips for a Healthier You** page provides practical guidance across **Stress Management, Time Management, Study Tips, Mental Health, and Lifestyle**. The **Recommended for You** section presents relevant tips based on the student's recent mood and workload, while students can also explore additional well-being content by category.

The page also includes **BurnOutBuddy**, an AI chatbot that allows students to ask for quick tips and basic well-being guidance directly within the app.

**Key purpose:** Provide students with **accessible, practical support for managing stress, developing healthier habits, and making space for recovery**.

![Tips and BurnOutBuddy](images/tips-burnoutbuddy.png)

---

### Supporting Features

Beyond the core workload-rebalancing journey, BurnOutGuard includes supporting features that connect workload management with student well-being:

- **Mood Journal** – Record moods and reflections through text, voice recordings, images, and tags.
- **Mood Insights** – View mood patterns, trends, and key insights over time.
- **Tips for a Healthier You** – Explore practical guidance across Stress Management, Time Management, Study Tips, Mental Health, and Lifestyle, including recommendations based on recent mood and workload.
- **BurnOutBuddy AI Chatbot** – Provides quick tips and basic well-being guidance directly within the app.
- **Profile & Settings** – Manage personal information, notifications, theme, language, and privacy and security preferences.

These features complement the core workload journey by supporting **reflection, healthier habits, guidance, and recovery**.

### Core User Journey

**Add Workload → Analyse → Identify Pressure Points → Recommend Actions → Adjust Plan → See Results → Recovery**

- **Add Workload** – Record responsibilities across Mental, Time, Physical, Social, and Errands.
- **Analyse** – Understand overall workload and its distribution across the five areas.
- **Identify Pressure Points** – Discover which areas contribute most to workload pressure, including common triggers and related tasks.
- **Recommend Actions** – Receive practical actions to address identified pressure points.
- **Adjust Plan** – Select suitable actions, rebalance responsibilities, and include recovery time.
- **See Results** – Compare workload before and after adjustments and see changes across the five areas.
- **Recovery** – Create realistic space for rest and recovery as part of maintaining a balanced workload.

### Core Design Principle

> **BurnOutGuard does not just show students that they are overloaded. It helps them understand why, decide what to change, rebalance their responsibilities, and make space for recovery.**

**Understand → Identify → Act → Rebalance → Recover**

---

## 4. What Makes It Different

BurnOutGuard is designed to go beyond a traditional to-do list, calendar, or workload tracker. Its key competitive advantage is the **closed-loop approach that helps students understand their workload, identify pressure points, take action, and see the impact of their changes**.

### 1. Holistic Student Workload View

BurnOutGuard combines **Mental, Time, Physical, Social, and Errands** into one workload view. Instead of focusing only on academic tasks, students can see how different responsibilities contribute to their overall workload.

**Competitive value:** Provides a broader view of student workload than tools focused mainly on tasks, deadlines, or productivity.

### 2. Pressure-Point Identification

Instead of only showing that workload is high, BurnOutGuard identifies **where the pressure is coming from**. The Pressure Points feature highlights the highest workload areas together with **common triggers, related tasks, and reasons why an area is high**.

**Competitive value:** Turns a workload score into an explanation that students can use to decide what needs to change.

### 3. From Tracking to Action

BurnOutGuard connects pressure points to **Recommended Actions**, such as breaking assignments into smaller tasks, rescheduling non-urgent tasks, or postponing lower-priority errands.

Students can then select suitable actions and move them into **Adjust Your Plan**.

**Competitive value:** Instead of simply reporting workload, BurnOutGuard guides students towards practical workload changes.

### 4. Workload Rebalancing + Recovery

The **Adjust Your Plan** feature allows students to actively rebalance their schedule rather than simply viewing their workload. It also includes dedicated **Recovery Time**, such as breaks and personal time.

**Competitive value:** The goal is not just to complete more tasks, but to create a **more manageable and sustainable workload**.

### 5. Before-and-After Results

After adjustments are applied, the **Results** page compares the student's workload before and after the changes, including changes across the five workload areas and pressure points.

**Competitive value:** Creates a feedback loop that shows whether the planned changes actually improve the student's workload state.

### 6. BurnOutBuddy AI Support

BurnOutGuard also includes **BurnOutBuddy**, an in-app AI chatbot that provides quick tips and basic well-being guidance related to stress, healthy habits, and student well-being.

**Competitive value:** Complements workload management with accessible, in-app well-being guidance without making the chatbot the core of the system.

### Our Key Competitive Advantage

The strongest differentiator is the **combination of these features into one continuous journey**:

**Understand → Identify → Recommend → Rebalance → See Results → Recover**

Traditional productivity tools often stop at **organising and tracking**. BurnOutGuard goes further by helping students understand **why their workload is high, what they can change, and how their changes affect the workload**.

> **Don't just track the workload. Understand it, act on it, rebalance it, and make space to recover.**

*The workload values shown in the prototype are illustrative examples demonstrating the intended interaction and are not validated real-world outcomes.*

---

## 5. Technical Architecture & Feasibility

### Tech Stack

We selected a lightweight web-based technology stack that is suitable for our team, supports efficient development, and can be deployed using free-tier services during the project.

| Component | Selected Technology | Why We Chose It / Constraints |
|---|---|---|
| **Frontend** | **Next.js + Tailwind CSS** | Next.js supports the development of a responsive and interactive web application, while Tailwind CSS allows us to create a consistent, accessible, and mobile-friendly interface efficiently. The main constraint is the team's learning curve with the Next.js project structure and component-based development. |
| **Backend** | **Supabase** | Supabase provides backend services such as authentication, database access, and APIs without requiring us to build a separate backend server from scratch. Its free tier is suitable for our prototype, although usage is subject to free-tier limits. |
| **Database** | **PostgreSQL (Supabase)** | PostgreSQL is suitable for storing structured data such as student profiles, tasks, workload areas, priorities, deadlines, workload scores, and adjusted plans. Using PostgreSQL through Supabase keeps the database and backend services integrated. |
| **APIs / Services** | **Supabase API / Services** | Supabase provides the services required for communication between the Next.js application and the database. We do not require a separate external API for the core BurnOutGuard features, which keeps the system simple and reduces unnecessary dependencies. |
| **Hosting** | **Vercel** | Vercel provides a simple deployment process for Next.js applications and can be connected to our GitHub repository. Its free tier is suitable for our project demonstration, subject to usage limits. |

### Development & Collaboration Tools

We plan to use **Lovable and Cursor** as development tools to support UI implementation, coding, debugging, and refinement.

**GitHub** will be used for source-code management and team collaboration.

These are development tools and are not part of the application's frontend or backend architecture.

### System Architecture Diagram

```text
                         Student
                            ↓
                  ┌──────────────────┐
                  │      Vercel      │
                  │    Next.js App   │
                  │  + Tailwind CSS  │
                  └────────┬─────────┘
                           ↓
                  ┌──────────────────┐
                  │     Supabase     │
                  │ Backend / APIs   │
                  │ Authentication   │
                  └────────┬─────────┘
                           ↓
                  ┌──────────────────┐
                  │   PostgreSQL     │
                  │     Database     │
                  └──────────────────┘
                           ↓
              Workload Analysis & Recommendation
                           ↓
                  Processes workload data
                           ↓
                  Returns results to student
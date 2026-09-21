# SIWES Weekly Progress Chart
**Adetokunbo Teriba** · GitHub **Axdel17**  
**Bokiti Cloud** — software engineering onboarding  
**27 July 2026 – 2 October 2026** · Monday to Friday only

Copy one week onto one page of the printed book. Write **Week Ending** (the Saturday). Leave **SAT.** as *No industrial training*. Sign the foot of each page.

As of **21 September 2026**: Weeks **1–8** and **Week 9 Monday** are from work already done. **Week 9 Tue–Fri** and **Week 10** are drafts — copy them after you do the work, or change the wording to match the real day.

Evidence: [week1-practice](https://github.com/Axdel17/week1-practice) · [week2-api](https://github.com/Axdel17/week2-api) · [week3-todo-api](https://github.com/Axdel17/week3-todo-api)

---

## Week 1 · Week Ending: Saturday, 1 August 2026

**MON. 27 July 2026**  
Resumed industrial training. Received orientation on working hours, conduct, and the software-engineering onboarding plan (environment, Git, Django, testing, then React). Set up my laptop workspace (VS Code, Git Bash). Confirmed GitHub account Axdel17.

**TUE. 28 July 2026**  
Installed and verified Git. Configured git user.name and user.email. Practised Git Bash: cd, ls, mkdir, pwd. Created a notes folder for daily records. Read the difference between the working tree, staging area, and a commit.

**WED. 29 July 2026**  
Verified Python on the laptop. Practised python --version and running a one-line script. Read virtual environments: why each project needs its own .venv so packages do not mix. Began Python refresher (functions).

**THUR. 30 July 2026**  
VS Code practice: File → Open Folder, Explorer, saving files, terminal panel. Recapped HTML structure from earlier lessons. Confirmed editor is for code, Git Bash is for commands.

**FRI. 31 July 2026**  
Read Week 1 onboarding sheet: Git/GitHub (branch, commit, PR), Docker basics, Python venv. Listed tools to verify: Node.js, Docker Desktop, Postman. Wrote a short plan for next week.

**SAT. 1 August 2026**  
No industrial training (weekend).

---

## Week 2 · Week Ending: Saturday, 8 August 2026

**MON. 3 August 2026**  
Installed Node.js LTS and checked node --version and npm --version. Read what npm does. Confirmed VS Code can open both Python and JS files.

**TUE. 4 August 2026**  
Git practice: git init, git add ., git commit. Learned that “git add.” without a space is wrong; it must be “git add .”. Practised git status and git log.

**WED. 5 August 2026**  
Created a GitHub repository. git remote add origin, git push. Signed in with Git Credential Manager. Understood origin = GitHub copy of the project.

**THUR. 6 August 2026**  
Python refresher: functions that return values, importing a module. Wrote a tiny greet() function locally. Read try/except at a basic level.

**FRI. 7 August 2026**  
Installed Docker Desktop. First start failed: “Virtualization support not detected.” Windows 10 Pro N on HP 650. Continue with local Python if Docker cannot start.

**SAT. 8 August 2026**  
No industrial training (weekend).

---

## Week 3 · Week Ending: Saturday, 15 August 2026

**MON. 10 August 2026**  
Docker follow-up. Task Manager shows Virtualisation: Enabled (Intel i3). Windows Features does not list WSL, Virtual Machine Platform, or Hyper-V.

**TUE. 11 August 2026**  
Tried wsl --install (0x800f080c) and DISM (0x800f081f). Windows is not activated. Decision: venv + runserver; skip docker compose until a supported machine.

**WED. 12 August 2026**  
Python: modules, comprehensions, reading someone else’s small script. Practised 4-space indentation. pip freeze lists packages in the active venv only.

**THUR. 13 August 2026**  
Git branches: create, switch, change, merge. Practised a small conflict and resolved it in VS Code.

**FRI. 14 August 2026**  
Django tutorial reading (parts 1–2): startproject vs startapp, manage.py, settings.py, INSTALLED_APPS. Drew the folder layout.

**SAT. 15 August 2026**  
No industrial training (weekend).

---

## Week 4 · Week Ending: Saturday, 22 August 2026

**MON. 17 August 2026**  
Django reading: models, makemigrations / migrate, admin. CharField and BooleanField.

**TUE. 18 August 2026**  
HTTP: GET, POST. Status codes 200, 201, 400, 401, 404. REST: URLs as resources, JSON in and out.

**WED. 19 August 2026**  
Postman/Insomnia as API testers. JSON keys (title, done) as the shape of a todo.

**THUR. 20 August 2026**  
Databases: table, row, column. SQLite (db.sqlite3) vs PostgreSQL. Training DB is SQLite while Docker is blocked.

**FRI. 21 August 2026**  
Rehearsed Git checkpoint: clone → branch → commit → push → pull request → merge.

**SAT. 22 August 2026**  
No industrial training (weekend).

---

## Week 5 · Week Ending: Saturday, 29 August 2026

**MON. 24 August 2026**  
Studied Bokiti Cloud public product (bokiti.cloud): Mail, Calendar, Workspaces, Forms, Workflows. No staff login issued yet.

**TUE. 25 August 2026**  
Mapped onboarding: Week 1 Git/Python, Week 2 Django, Week 3 DRF+tests, Week 4 JS/React + first ticket.

**WED. 26 August 2026**  
Python OOP: class, instance, __str__. Related this to a Django Model (Todo class; each row is an instance).

**THUR. 27 August 2026**  
Practised activating a venv in Git Bash (source .venv/Scripts/activate). (.venv) must show before pip/django commands.

**FRI. 28 August 2026**  
Prepared Week 1 checkpoint: Git identity, GitHub, Python venv, small module. Listed evidence (screenshots, PR).

**SAT. 29 August 2026**  
No industrial training (weekend).

---

## Week 6 · Week Ending: Saturday, 5 September 2026
Onboarding Week 1 checkpoint — done.

**MON. 31 August 2026**  
Created a project venv. Wrote greet.py and main.py. Ran: “Hello, Adetokunbo. Week 1 Python is working.” and “2 + 3 = 5”.

**TUE. 1 September 2026**  
Cloned week1-practice. Branch my-first-change. Trivial change, git add, git commit.

**WED. 2 September 2026**  
Pushed and opened a pull request. Merged to main. PR: https://github.com/Axdel17/week1-practice/pull/1

**THUR. 3 September 2026**  
Week 1 check-in notes (Git 2.55, Python 3.14.7, Node 24.20 LTS). Docker blocked — virtualization/WSL errors recorded.

**FRI. 4 September 2026**  
Submitted Week 1 notes. Checkpoint met: clone, branch, commit, PR. Python met. Docker not met — documented.

**SAT. 5 September 2026**  
No industrial training (weekend).

---

## Week 7 · Week Ending: Saturday, 12 September 2026
JWT API + todo project started.

**MON. 7 September 2026**  
Started week2-api. venv. Installed Django, djangorestframework, simplejwt. startproject config ., startapp api. JWT settings.

**TUE. 8 September 2026**  
GET /api/health AllowAny → {"status": "ok"} HTTP 200. POST /api/token/. GET /api/me with Bearer → username axdel. Pushed https://github.com/Axdel17/week2-api

**WED. 9 September 2026**  
Week 2 check-in. runserver --noreload. urllib Errno 11001; used curl.exe. Bokiti.cloud reviewed (no staff login).

**THUR. 10 September 2026**  
Read DRF serializer, ViewSet, DefaultRouter. This is the real Week 3 table (CRUD on a todo).

**FRI. 11 September 2026**  
Started week3-todo-api. Todo model: title, done. makemigrations + migrate OK.

**SAT. 12 September 2026**  
No industrial training (weekend).

---

## Week 8 · Week Ending: Saturday, 19 September 2026
Onboarding Week 3 checkpoint — CRUD + test.

**MON. 14 September 2026**  
TodoSerializer and TodoViewSet. DefaultRouter at /api/todos/. Fixed missing import and apis vs api.

**TUE. 15 September 2026**  
runserver --noreload. GET /api/todos/ → Todo List, HTTP 200 OK.

**WED. 16 September 2026**  
POST “Buy milk”. HTTP 201 Created, {"id": 1, "title": "Buy milk", "done": false}.

**THUR. 17 September 2026**  
pytest.ini and todos/test_api.py. python -m pytest todos/test_api.py -q → 1 passed.

**FRI. 18 September 2026**  
Request flow: URL → router → ViewSet → serializer → model → database → JSON. .gitignore prepared.

**SAT. 19 September 2026**  
No industrial training (weekend).

---

## Week 9 · Week Ending: Saturday, 26 September 2026
Monday done. Tue–Fri are drafts — copy after you do the work.

**MON. 21 September 2026**  
Pushed week3-todo-api (https://github.com/Axdel17/week3-todo-api). Week 3 notes. Compiled this logbook from 27 July.

**TUE. 22 September 2026**  
git pull on week3-todo-api. JavaScript essentials: let/const, functions, arrays, objects. node snippets in Git Bash.

**WED. 23 September 2026**  
Promises and async/await. fetch() GET /api/todos/ with Django running. JSON in the console.

**THUR. 24 September 2026**  
React: components, props, useState. Tiny component listing todo titles from sample data.

**FRI. 25 September 2026**  
Sketched Todo UI (list, add, done). Mapped buttons to GET/POST/PATCH. Prepared for Vite + React next week.

**SAT. 26 September 2026**  
No industrial training (weekend).

---

## Week 10 · Week Ending: Saturday, 3 October 2026
Draft for 28 Sep – 2 Oct — copy as you finish each day.

**MON. 28 September 2026**  
React + Vite. Listed todos from GET /api/todos/. Loading and empty states.

**TUE. 29 September 2026**  
Add-todo form: POST /api/todos/. Page updates after 201. Empty title not sent.

**WED. 30 September 2026**  
PATCH done and DELETE /api/todos/<id>/. Noted any CORS/CSRF if the browser blocked the call.

**THUR. 1 October 2026**  
First-ticket style Git: branch, small frontend change, commit, push, pull request. PR description written.

**FRI. 2 October 2026**  
Week 4 check-in notes. Evidence: React screenshot, PR link, Docker still blocked. Closed logbook period 27 July – 2 October.

**SAT. 3 October 2026**  
No industrial training (weekend).

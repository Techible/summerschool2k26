# 🚀 MERN Stack Bootcamp — Student Guide

> **From absolute zero to full-stack developer in 4 weeks.**
> You will build real projects every single day. No shortcuts, no fluff.

---

## 📋 Course Overview

| | |
|---|---|
| **Duration** | 4 weeks |
| **Sessions** | 3 days/week (Mon, Wed, Fri recommended) |
| **Normal weeks** | 3 hours/day (Weeks 1 & 3) |
| **Intensive weeks** | 6 hours/day (Weeks 2 & 4) |
| **Total hours** | ~48 hours of live instruction |
| **Projects built** | 6+ mini-projects + 1 final full-stack app |
| **Level** | Complete beginner — no experience needed |

---

## 🛠️ Stack You Will Learn

```
HTML5  →  CSS3  →  JavaScript (ES6+)  →  React.js  →  Node.js  →  Express.js  →  MongoDB
```

Plus: Git, GitHub, REST APIs, JWT Auth, Mongoose, Postman, Vercel, Render

---

## ✅ Rules & Expectations

- Submit every homework task **before the next session** using the link in each section
- All code must be **pushed to GitHub** — you must have a GitHub account by Day 1
- Stuck? Post your **error + what you already tried** in the group chat before DMing the instructor
- Weeks 2 & 4 are **intensive (6 hrs/day)** — clear your schedule in advance
- Final project must be **solo work** — collaboration for learning is fine, copy-paste is not
- Attendance is important — if you miss a session, watch the recording and complete the task anyway

---

## 💻 Install These Before Day 1

- [ ] **VS Code** — [code.visualstudio.com](https://code.visualstudio.com)
- [ ] **Node.js (LTS)** — [nodejs.org](https://nodejs.org)
- [ ] **Git** — [git-scm.com](https://git-scm.com)
- [ ] **Postman** — [postman.com](https://postman.com)
- [ ] **MongoDB Atlas account (free)** — [mongodb.com/atlas](https://mongodb.com/atlas)
- [ ] **GitHub account** — [github.com](https://github.com)
- [ ] VS Code extensions: Prettier, ESLint, GitLens, Thunder Client (optional)

---

---

# 📅 WEEK 1 — Web Foundations
**Schedule: 3 sessions × 3 hours | Topic: HTML, CSS, JavaScript**

> This week you go from zero to building interactive web pages from scratch.

---

## Day 1 — HTML: How the Web Is Structured

**What we cover:**
- What is HTML? How browsers read it
- Tags, elements, attributes
- Headings, paragraphs, links, images
- Lists, tables, forms
- Semantic HTML5 (header, nav, main, section, footer, article)
- Linking multiple pages together
- Live build: Personal bio page

**📝 Homework Task:**
Build a **multi-page personal portfolio website** using only HTML (no CSS, no JS yet).

Requirements:
- At least 3 pages: `index.html` (Home), `about.html`, `contact.html`
- Navigation bar linking all 3 pages
- Home page: your name, a short intro paragraph, a profile placeholder
- About page: a table listing your skills or education
- Contact page: a form with name, email, message fields and a submit button
- Use semantic tags correctly (no div soup)
- Comment your code

**📤 Submit your work here:** [SUBMISSION LINK — TO BE FILLED BY INSTRUCTOR]

---

## Day 2 — CSS: Making It Beautiful

**What we cover:**
- How CSS works (selectors, specificity, cascade)
- The box model (margin, border, padding, content)
- Flexbox (layout holy grail)
- CSS Grid (2D layouts)
- Responsive design & media queries
- CSS variables
- Transitions and hover effects
- Live build: Styling the Day 1 portfolio

**📝 Homework Task:**
Style your Day 1 portfolio so it looks professional and works on all screen sizes.

Requirements:
- Fully responsive — must look good on mobile (375px) AND desktop (1200px+)
- Use **Flexbox** for the navigation bar
- Use **CSS Grid** for a skills or projects section (at least 3 cards)
- Use **CSS variables** for your color palette (define at least 3: primary, secondary, text)
- At least 1 CSS animation or transition (e.g. button hover, card lift effect)
- Clean, readable typography — pick fonts from Google Fonts
- No inline styles — all CSS in a separate `style.css` file

**📤 Submit your work here:** [SUBMISSION LINK — TO BE FILLED BY INSTRUCTOR]

---

## Day 3 — JavaScript: Making It Interactive

**What we cover:**
- Variables (let, const), data types
- Functions, arrow functions
- Arrays and array methods (push, pop, map, filter)
- Objects
- DOM manipulation (querySelector, getElementById)
- Event listeners (click, input, submit)
- localStorage (saving data in the browser)
- Live build: interactive color picker

**📝 Homework Task:**
Build a **To-Do List app** from scratch — your first real JavaScript project.

Requirements:
- Add a task (pressing Enter or clicking a button)
- Mark a task as complete (click to toggle, visually different)
- Delete a task
- Tasks must **persist on page refresh** using `localStorage`
- Show a count: "X tasks remaining"
- All JavaScript in a single `app.js` file — no libraries, no frameworks
- Bonus: filter view (All / Active / Completed)

**📤 Submit your work here:** [SUBMISSION LINK — TO BE FILLED BY INSTRUCTOR]

---

---

# 📅 WEEK 2 — JavaScript Deep Dive + Node.js + MongoDB
**Schedule: 3 sessions × 6 hours ⚡ INTENSIVE WEEK**

> This week we go deep. By the end you will have a working REST API connected to a real database.

---

## Day 4 — Advanced JavaScript + Git/GitHub

**What we cover:**
- Promises and the event loop
- async/await
- `fetch()` API — calling real external APIs
- ES6 modules (import/export)
- Advanced array methods: `map`, `filter`, `reduce`, `find`, `some`
- Spread/rest operators, destructuring
- Error handling with try/catch
- Git: init, add, commit, push, pull, branches
- GitHub: repos, README, .gitignore

**📝 Homework Task:**
Build a **live Weather App** using a real API.

Requirements:
- Sign up for a free API key at [openweathermap.org](https://openweathermap.org/api)
- User can type a city name and click "Search"
- Display: city name, temperature (°C), weather condition, humidity, wind speed
- Show a **loading state** while fetching
- Show a **friendly error message** if city not found
- Use `async/await` (not .then chains)
- Push the entire project to a GitHub repository
- Add a `README.md` explaining what the app does

**📤 Submit your work here:** [SUBMISSION LINK — TO BE FILLED BY INSTRUCTOR]

---

## Day 5 — Node.js + Express: Your First Server

**What we cover:**
- How Node.js works (runtime, not a browser)
- npm and package.json
- Creating an Express server
- Routes (GET, POST, PUT, DELETE)
- Middleware (express.json, custom middleware)
- Request and Response objects
- Testing APIs with Postman
- Organizing routes in separate files
- Error handling middleware

**📝 Homework Task:**
Build a **Books Library REST API** using Express.

Requirements:
- `GET /books` — return all books
- `GET /books/:id` — return one book by ID
- `POST /books` — add a new book (title, author, genre, year)
- `PUT /books/:id` — update a book
- `DELETE /books/:id` — delete a book
- Data stored in a JavaScript array (no database yet — that's tomorrow)
- Return proper HTTP status codes (200, 201, 404, 400)
- Test ALL routes in Postman and include screenshots in submission
- Code must be organized: `server.js` + `routes/books.js`

**📤 Submit your work here:** [SUBMISSION LINK — TO BE FILLED BY INSTRUCTOR]

---

## Day 6 — MongoDB + Mongoose: Real Database

**What we cover:**
- NoSQL vs SQL — why MongoDB
- MongoDB Atlas setup (free cloud DB)
- Mongoose: schemas, models, validation
- CRUD with Mongoose (.find, .findById, .create, .findByIdAndUpdate, .findByIdAndDelete)
- Connecting MongoDB to Express
- Environment variables with dotenv (.env file)
- Never committing secrets (`.gitignore`)

**📝 Homework Task:**
Upgrade your Day 5 Books API to use a **real MongoDB database**.

Requirements:
- Connect to MongoDB Atlas using Mongoose
- Create a `Book` schema with: title (required), author (required), genre, year, createdAt
- Create a `User` schema with: name, email (unique), password
- Full CRUD for both Books and Users
- All sensitive data (MongoDB URI) in `.env` — `.env` must be in `.gitignore`
- Proper error handling for all routes
- Push to GitHub with a clear README
- Bonus: Add input validation (required fields return a helpful error message)

**📤 Submit your work here:** [SUBMISSION LINK — TO BE FILLED BY INSTRUCTOR]

---

---

# 📅 WEEK 3 — React.js
**Schedule: 3 sessions × 3 hours | Topic: Components, Hooks, Routing, API Integration**

> React is how modern web apps are built. This week you learn to think in components.

---

## Day 7 — React Foundations

**What we cover:**
- Why React? The problem it solves
- Creating a project with Vite
- JSX — HTML inside JavaScript
- Components (functional components)
- Props — passing data between components
- useState — making things dynamic
- Conditional rendering
- Rendering lists with `.map()` and keys
- Component file structure

**📝 Homework Task:**
Rebuild your **portfolio website as a React app** using Vite.

Requirements:
- Create with: `npm create vite@latest my-portfolio -- --template react`
- At least 5 separate components: `Navbar`, `Hero`, `Skills`, `Projects`, `Footer`
- Pass data (name, skills, project list) via **props** — no hardcoding data inside components
- Skills section: render from an array using `.map()`
- Projects section: at least 3 project cards from an array of objects
- No external UI libraries (no Bootstrap, no Tailwind) — write your own CSS
- Push to GitHub

**📤 Submit your work here:** [SUBMISSION LINK — TO BE FILLED BY INSTRUCTOR]

---

## Day 8 — Hooks + React Router

**What we cover:**
- `useEffect` — side effects, API calls, cleanup
- `useContext` — sharing state without prop drilling
- Custom hooks
- React Router v6: `<BrowserRouter>`, `<Routes>`, `<Route>`, `<Link>`, `<NavLink>`
- URL params with `useParams`
- Programmatic navigation with `useNavigate`
- Controlled forms in React

**📝 Homework Task:**
Build a **Movie Search App** using the OMDB API (free).

Requirements:
- Get a free API key at [omdbapi.com](http://omdbapi.com)
- Search bar: controlled input (useState), search triggers API call
- Results page: show movie posters, titles, year in a grid
- Click a movie → navigate to `/movies/:id` — show full details (director, plot, ratings, etc.)
- Use `useEffect` for fetching, `useParams` for the detail page
- Loading spinner while fetching
- Error state if movie not found or API fails
- At least 2 pages with React Router

**📤 Submit your work here:** [SUBMISSION LINK — TO BE FILLED BY INSTRUCTOR]

---

## Day 9 — React + Backend Connection (First Full-Stack App!)

**What we cover:**
- Axios — making HTTP requests from React
- CORS — why it blocks you and how to fix it
- Environment variables in Vite (VITE_API_URL)
- The full request cycle: React → Express → MongoDB → back to React
- Loading/error/success states for all operations
- Project folder structure for a MERN app

**📝 Homework Task:**
Connect your React frontend to your Books API backend — your **first full-stack MERN app**.

Requirements:
- React app fetches all books from your Express API on page load (`useEffect` + Axios)
- Display books in a list/grid with title, author, genre
- Form to **add a new book** — posts to your API
- Button to **delete a book** — calls DELETE endpoint, updates UI
- Edit functionality — click edit → form pre-fills → PUT request to update
- Backend must have CORS enabled (`npm install cors`)
- Both backend and frontend run simultaneously (2 terminals)
- Push both `client/` and `server/` to one GitHub repo

**📤 Submit your work here:** [SUBMISSION LINK — TO BE FILLED BY INSTRUCTOR]

---

---

# 📅 WEEK 4 — Full MERN App + Deployment
**Schedule: 3 sessions × 6 hours ⚡ INTENSIVE WEEK**

> Final week. You add authentication, build your final project, and ship it live to the internet.

---

## Day 10 — Authentication: JWT + Protected Routes

**What we cover:**
- Why authentication matters
- Password hashing with bcrypt
- JSON Web Tokens (JWT) — how they work
- Register and login endpoints
- Auth middleware (protecting routes)
- Storing JWT in React (localStorage)
- Protected routes in React Router
- Showing/hiding UI based on auth state

**📝 Homework Task:**
Add **full authentication** to your MERN Books app.

Requirements:
- `POST /auth/register` — hash password with bcrypt, save user
- `POST /auth/login` — verify password, return JWT
- Auth middleware that verifies token on protected routes
- All book CRUD routes are protected — require valid JWT
- In React: Register and Login pages (forms)
- Store JWT in localStorage after login
- Send token in `Authorization: Bearer <token>` header with Axios
- Protected React routes — redirect to `/login` if not authenticated
- Show logged-in user's name in the navbar
- Logout clears the token

**📤 Submit your work here:** [SUBMISSION LINK — TO BE FILLED BY INSTRUCTOR]

---

## Day 11 — Final Project Build Day

**What we build together:**
A full **MERN Task Manager** app — your capstone project.

Features (guided in class):
- Auth: Register, Login, Logout
- Create tasks with title, description, priority (low/medium/high), due date
- View all your tasks (only your own — tasks linked to user ID)
- Mark tasks complete/incomplete
- Edit and delete tasks
- Filter by status or priority
- Search by title
- Clean, responsive UI

**📝 Homework Task:**
Complete your Task Manager app — all features working with no console errors.

Requirements:
- All listed features must be functional
- Responsive on mobile and desktop
- No `console.log` left in production code
- Write a `README.md` for your project:
  - What it does
  - Tech stack used
  - How to run it locally (setup instructions)
  - Screenshots (at least 2)
- Push all code to GitHub with clean commit history

**📤 Submit your work here:** [SUBMISSION LINK — TO BE FILLED BY INSTRUCTOR]

---

## Day 12 — Deployment + Demo Day 🎉

**What we cover:**
- Deploying Express backend to **Render.com** (free)
- Deploying React frontend to **Vercel** (free)
- Setting environment variables in production dashboards
- Connecting your deployed frontend to your deployed backend
- MongoDB Atlas production configuration
- What to do when production breaks (debugging deployed apps)
- Live demos — every student presents their app

**📝 Final Submission:**
Your Task Manager must be **live on the internet**.

Requirements:
- Backend deployed on Render — working live URL
- Frontend deployed on Vercel — working live URL
- Both connected and fully functional in production
- Submit:
  1. Live app URL (Vercel)
  2. GitHub repository link
  3. A 2–3 minute screen recording demo (Loom is free) showing all features working

**📤 FINAL SUBMISSION LINK:** [SUBMISSION LINK — TO BE FILLED BY INSTRUCTOR]

---

---

## 📁 Recommended Project Structure (Final Project)

```
task-manager/
├── client/                  # React frontend (Vite)
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── hooks/
│   │   └── App.jsx
│   ├── .env
│   └── package.json
│
├── server/                  # Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   ├── .env                 # ← NEVER commit this
│   ├── .gitignore           # ← Must include .env
│   └── package.json
│
└── README.md
```

---

## 📚 Resources

| Resource | Link |
|---|---|
| MDN Web Docs | [developer.mozilla.org](https://developer.mozilla.org) |
| JavaScript.info | [javascript.info](https://javascript.info) |
| React Docs | [react.dev](https://react.dev) |
| Express Docs | [expressjs.com](https://expressjs.com) |
| Mongoose Docs | [mongoosejs.com/docs](https://mongoosejs.com/docs) |
| MongoDB Atlas | [mongodb.com/atlas](https://mongodb.com/atlas) |
| Vite | [vitejs.dev](https://vitejs.dev) |
| Render (deploy backend) | [render.com](https://render.com) |
| Vercel (deploy frontend) | [vercel.com](https://vercel.com) |

---

*Built with 💙 by your instructor · Questions? Post in the course group · You've got this!*

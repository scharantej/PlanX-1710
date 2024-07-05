### Project: Smart Time
**Objective:** Develop a user-friendly website for Smart Time, a time management tool, that allows users to input tasks, assign time slots, and automatically generate schedules.

### Flask Application Design
#### HTML Files
- **index.html:** The homepage of the application. It will display an introduction to Smart Time and provide a form for users to enter tasks and time slots.
- **schedule.html:** This page will display the generated schedule based on user inputs.

#### Routes
- **Home Page Route:**
  - URI: `/`
  - Method: GET
  - Function: Renders the `index.html` page.
- **Schedule Route:**
  - URI: `/schedule`
  - Method: POST
  - Function: Receives user input from `index.html`, calculates the schedule, and renders `schedule.html` with the generated schedule.
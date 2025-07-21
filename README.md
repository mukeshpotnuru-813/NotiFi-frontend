# Event Scheduler Frontend

This is a simple frontend for an Event Scheduler web application. It allows users to register, log in, create events, view weather forecasts for event locations, filter events by category and completion status, and manage their events.

## Features

- **User Authentication:** Register and log in securely.
- **Event Management:** Create, view, and delete events.
- **Filtering:** Search events, filter by category and completion status (upcoming/completed).
- **Weather Integration:** View weather forecast for event location and time.
- **Responsive Design:** Works well on desktop and mobile devices.

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/event-scheduler-frontend.git
   ```

2. **Backend Requirement:**
   - This frontend expects a backend API running at `http://localhost:5000/api`.
   - Endpoints required:
     - `POST /api/auth/register`
     - `POST /api/auth/login`
     - `GET /api/events`
     - `POST /api/events`
     - `DELETE /api/events/:id`
     - `GET /api/weather`

3. **Run the Frontend:**
   - Open `frontend.html` in your web browser.

## Usage

- Register a new account or log in.
- Create new events using the form.
- Filter events using the search, category, and status filters.
- View weather info for event locations.
- Delete events as needed.

## Customization

- Update API endpoints in `frontend.html` if your backend runs on a different URL.
- Modify styles in the `<style>` section for branding.

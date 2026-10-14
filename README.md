# FixIt — Campus Maintenance App

FixIt is a responsive, mobile-first campus maintenance request demo. Students can report common campus/hostel issues, view their requests, and follow a simulated repair workflow.

## Features

- Dashboard with open, in-progress, and resolved request counts
- Issue categories: Electrician, Plumber, Cleaner, Wi-Fi, Carpenter, and Others
- Issue reporting with block, room number, and description
- Request list with status filters
- Ticket detail view with status timeline
- Demo technician assignment and OTP-based resolution flow
- Profile details and notifications
- Browser `localStorage` persistence for demo data
- Responsive dark UI with amber accent styling

## Run locally

No build tools are required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

For a local web server, you can also run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy with GitHub Pages

1. Create a new GitHub repository.
2. Upload the files from this project, keeping `index.html` at the repository root.
3. Open **Settings → Pages**.
4. Under the build/deployment settings, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for the Pages deployment and open the published URL shown there.

## Important demo limitations

This is a front-end prototype, not a production service. Requests are stored only in the current browser's local storage; they are not shared with campus staff or other users. Technician assignment, notifications, photo attachment, and OTP verification are simulated in the browser. There is no backend, authentication, real file upload, SMS, or database integration.

## Suggested repository description

`A responsive campus maintenance reporting and ticket-tracking demo built with HTML, CSS, and JavaScript.`

## Suggested topics

`campus-maintenance` `issue-tracking` `html` `css` `javascript` `github-pages` `student-project`

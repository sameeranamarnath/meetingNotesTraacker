<img width="200px" src="https://encore.dev/assets/branding/logo/logo.svg" alt="Encore - The Backend Development Engine" />

# Meeting Notes

Stack:

React-Vite-Typescript-Tailwind
Go
Cloud based SQL database
Encore for infra management and tracking

The backend uses an SQL database to store meeting notes and has three API endpoints:

- `GET  /note/:id` - Retrieve a note by ID.
- `POST /note` - Create a new note (or update an existing one).
- `GET  /images/:query` - Search for images by using the [Pexels API](https://www.pexels.com/api/).

live@https://sameeranamarnath.github.io/meetingNotesTraacker/

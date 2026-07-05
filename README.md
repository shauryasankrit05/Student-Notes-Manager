# Student Notes Manager

A simple and responsive web app for students to upload, organize, search, filter, and mark important study notes. The project is built using only HTML, CSS, and vanilla JavaScript, so it can run directly in any modern browser.

## Features

- Add notes with title, subject, topic, description, and attached file name
- Filter notes by subject
- Search notes by title, subject, topic, or description
- Mark notes as important
- Edit existing notes
- Delete individual notes with confirmation
- Clear all notes with confirmation
- View dashboard statistics for total notes, subjects, and important notes
- Save notes in browser localStorage
- Restore saved notes after page refresh
- Responsive layout for desktop and mobile screens

## Technologies Used

- HTML
- CSS
- JavaScript
- Browser localStorage

## How To Run

1. Download or open the `student-notes-manager.html` file.
2. Open it in any modern web browser.
3. Start adding your notes.

No installation, server, database, or external library is required.

## How To Use

1. Fill in the note title, subject, and topic.
2. Optionally add a short description.
3. Optionally attach a file such as PDF, DOC, TXT, PNG, or JPG.
4. Click **Add Note**.
5. Use the search bar to find notes quickly.
6. Use the subject dropdown to filter notes by subject.
7. Turn on **Show Important Only** to view starred notes.
8. Use **Edit** to update a note.
9. Use **Delete** to remove a note.
10. Use **Clear All Notes** to reset the app.

## Important Note About File Uploads

This is a frontend-only project. The app saves the uploaded file name, but it does not permanently store the actual file. To store real files permanently, the app would need a backend system or database storage such as Firebase, Supabase, or a custom server.

## Local Storage

The app stores note data in the browser's localStorage. This means:

- Notes remain available after refreshing the page.
- Notes are saved only in the same browser and device.
- Clearing browser data may remove saved notes.

## Project Structure

```text
student-notes-manager.html
README.md
```

All HTML, CSS, and JavaScript code is kept inside the single `student-notes-manager.html` file.

## Future Improvements

- Add real file storage using Firebase or Supabase
- Add user login and personal accounts
- Add subject color customization
- Add note categories or tags
- Add export/import notes as JSON
- Add dark mode
- Add sorting by newest, oldest, subject, or importance

## Project Status

The project is complete as a working frontend-only student notes manager.

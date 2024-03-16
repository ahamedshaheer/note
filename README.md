<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
    <h1>Simple Notes App</h1>
    <h2>Overview</h2>
    <p>This is a simple PHP-based notes application that allows users to create, edit, delete, and download notes. It uses a SQLite database to store notes.</p>
    <h2>Features</h2>
    <ul>
        <li><strong>Create Note:</strong> Easily create a new note by providing a title and content.</li>
        <li><strong>Edit Note:</strong> Edit the title and content of existing notes.</li>
        <li><strong>Delete Note:</strong> Delete individual notes or clear all notes at once.</li>
        <li><strong>Download Note:</strong> Download notes as text files.</li>
        <li><strong>Responsive Design:</strong> The application is designed to be responsive, making it usable on various devices.</li>
    </ul>
    <h2>Usage</h2>
    <ol>
        <li>Clone the repository to your local machine:</li>
        <code>git clone https://github.com/ahamedshaheer/note.git</code>
        <li>Set up a web server (e.g., Apache or Nginx) to serve the PHP files.</li>
        <li>Ensure the web server has write permissions to the <code>db.sqlite</code> file for storing notes.</li>
        <li>Access the application in your web browser, typically at <code>http://localhost/notes-app</code>.</li>
    </ol>
    <h2>Dependencies</h2>
    <ul>
        <li><strong>Bootstrap:</strong> The application uses Bootstrap for styling. (CDN links are provided in the HTML file)</li>
    </ul>
    <h2>File Structure</h2>
    <ul>
        <li><code>index.php:</code> Main PHP file containing the application logic and HTML structure.</li>
        <li><code>db.sqlite:</code> SQLite database file to store notes.</li>
    </ul>
    <h2>Actions</h2>
    <ul>
        <li><strong>Create Note:</strong> Submit the form with a title and content to add a new note.</li>
        <li><strong>Edit Note:</strong> Click the edit button, make changes in the modal, and save.</li>
        <li><strong>Delete Note:</strong> Click the delete button to delete a specific note. Use the "Clear All Notes" button to delete all notes.</li>
        <li><strong>Download Note:</strong> Click the download button to download a note as a text file.</li>
    </ul>
    <h2>Contributing</h2>
    <p>Feel free to contribute to the project by submitting bug reports or feature requests.</p>
    <h2>License</h2>
    <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

</body>
</html>

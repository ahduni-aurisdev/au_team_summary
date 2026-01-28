# Team's Leave Summary - Ahmedabad University

A Zoho People custom webtab to display team approved leave summaries .

## Project Structure

- `app/` - Contains the widget source code (`widget.html`) and translations.
- `server/` - Local development server.
- `dist/` - Build artifacts.

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the local server:
   ```bash
   npm start
   ```

## Features

- Displays approved leave records for subordinates.
- Filters leaves by "Approved" status (case-insensitive).
- Search functionality by employee name.
- Pagination support.
- Detailed view in a modal.
- Custom styling with Ahmedabad University colors.


## How to upload .zip as a WebTab in Zoho People
1. Run  
   ```bash
   zet validate
   ```
   in command line terminal to validate the widget.
2. Run  
   ```bash
   zet pack
   ``` 
   in command line terminal, this will create a .zip file in the dist/ folder.
3. Upload the .zip file in Zoho People WebTab to upload the widget.



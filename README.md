# Game Website

A static multi-page website for showcasing game categories and popular titles.
The project is built with plain HTML and CSS, with a simple contact form flow.

## Overview

This website presents a game-themed browsing experience with:

- A home page with a hero section and image slider.
- Category pages (Action, Adventure, Strategy).
- Franchise-specific pages (for example Assassin's Creed, Star Wars, and Uncharted).
- An About page and a Contact page.
- A Thank You page after successful form submission.

## Tech Stack

- HTML5
- CSS3
- Optional JavaScript file (`script.js`, currently empty)

## Project Structure

```text
Game-Website/
|- index.html
|- games.html
|- action.html
|- adventure.html
|- strategy.html
|- assasincreed-games.html
|- starwars.html
|- uncharted.html
|- about.html
|- contact.html
|- thankyoupage.html
|- styles.css
|- script.js
|- pictures/
```

## Run Locally

Because this is a static website, you can run it in any browser.

1. Clone or download the project.
2. Open `index.html` directly in your browser.

For a better local development experience, use a local server (for example VS Code Live Server):

1. Open the project folder in VS Code.
2. Start Live Server on `index.html`.
3. Navigate through pages using the site menu.

## Contact Form

The contact form in `contact.html` uses [FormSubmit](https://formsubmit.co/) and sends form data to a configured email address.

- Form `action`: `https://formsubmit.co/therese8949@gmail.com`
- Redirect on success: `thankyoupage.html`

If you fork this project, update the email address to your own.

## Notes

- Some media files are stored in `pictures/` and subfolders.
- Keep file names and folder paths consistent with references in HTML.

## Future Improvements

- Add JavaScript interactivity to improve the slider and navigation behavior.
- Improve accessibility (`alt` text quality, keyboard focus states, landmark structure).
- Add responsive refinements for smaller screens.

## License

No license file is currently included. Add a `LICENSE` file if you plan to share or publish this project.

# Fresh Pomodoro 🍅

A clean and customizable Pomodoro timer built with **HTML, CSS, and JavaScript**.

Fresh Pomodoro helps users stay focused by using timed work and break sessions. The interface is simple, lightweight, and easy to use.

## Features

* Countdown timer
* Start / Pause / Resume
* Reset timer
* Adjustable work duration
* Adjustable break duration
* Multiple notification sounds
* Sound preview
* Automatic switch between work and break sessions
* Completed Pomodoro counter
* Shareable timer settings through URL parameters
* Responsive design for desktop and mobile

## Technologies

* HTML5
* CSS3
* JavaScript

No frameworks or external libraries are required.

## Project Structure

```text
fresh-pomodoro/
│
├── index.html
└── README.md
```

The HTML, CSS, and JavaScript are currently contained in a single `index.html` file.

## How to Use

1. Open `index.html` in your browser.
2. Adjust the work and break duration on the right panel.
3. Select a notification sound.
4. Click **Start** to begin the countdown.
5. Click **Pause** to temporarily stop the timer.
6. Click **Reset** to restart the current session.
7. Use **Share Link** to share the current timer settings.

## Shareable Settings

Timer settings can be stored in URL parameters.

Example:

```text
?work=25&break=5
```

This represents:

* Work time: 25 minutes
* Break time: 5 minutes

After deploying the project online, a shared URL may look like:

```text
https://your-username.github.io/fresh-pomodoro/?work=25&break=5
```

Anyone opening the link will receive the same work and break duration settings.

## Run Locally

Clone the repository:

```bash
git clone https://github.com/your-username/fresh-pomodoro.git
```

Enter the project folder:

```bash
cd fresh-pomodoro
```

Then open:

```text
index.html
```

in your browser.

## Deploy with GitHub Pages

1. Push the project to GitHub.
2. Open the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select:

   * Source: `Deploy from a branch`
   * Branch: `main`
   * Folder: `/root`
5. Click **Save**.
6. GitHub will generate a public URL for the website.

Example:

```text
https://your-username.github.io/fresh-pomodoro/
```

## Future Improvements

Possible improvements include:

* Long break mode
* Daily focus statistics
* Task list integration
* Dark mode
* Custom notification sounds
* Browser notifications
* Saving user preferences

## License

This project is for learning and personal use.

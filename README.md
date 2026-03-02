# Mombie – Survive the Night Together

**[View Live Site](https://jcchin.github.io/mombie_web)**

Splash page for **Mombie**, the mobile + smartwatch app that helps couples coordinate newborn night-shift schedules so both parents actually get to sleep.

## About

Mombie lets partners take turns staying awake with a baby by scheduling shift blocks and delivering gentle haptic alerts via Apple Watch or Wear OS — waking the right parent at the right time without disturbing anyone else.

**Features:**
- Smart shift scheduling — set up nightly blocks in seconds
- Wrist alerts, not alarms — haptic notifications via smartwatch
- Partner sync — both parents see the same schedule in real time
- Baby activity log — track feedings, diapers, and sleep with one tap
- Sleep insights — see how much rest each parent is getting over the week
- Private & offline first — no subscriptions, no third-party servers

## Tech

- [Bootstrap 5.3.8](https://getbootstrap.com/)
- [Font Awesome 7.2.0](https://fontawesome.com/)
- [jQuery 3.7.1](https://jquery.com/)
- [Simple Line Icons 2.5.5](https://simplelineicons.github.io/)

## Development

Edit `index.html` directly, or use the Gulp build system to recompile SCSS:

```bash
npm install
npm start       # live-reload dev server
```

#### Gulp tasks

- `gulp css` — compile SCSS → minified CSS
- `gulp js` — minify JS
- `gulp vendor` — copy dependencies from node_modules to vendor/

## License

MIT

## Design:
- Colors: https://coolors.co/ffffff-80b3ff-0066ff-002233
- Background: https://app.haikei.app/
- Code Colors: 
  - https://github.com/highlightjs/highlight.js/blob/0c4cc8a1c3aa373aee06796433c1389e4d2a3a45/src/styles/tomorrow-night-blue.css
  - https://github.com/chriskempson/tomorrow-theme
- Code Style: https://neumorphism.io/#e0e0e0


- Tutorial:
  - https://github.com/marp-team/marpit/blob/main/docs/theme-css.md
  - https://github.com/rainbowflesh/Rose-Pine-For-Marp/blob/master/css/rose-pine-moon.css
  - 



- TODO
blockquote {
  border-left: 8px solid var(--color-much);
  padding: 10px 25px;
  border-radius: 8px;
  background-color: var(--color-quote);
  font-size: 0.9rem;
  font-family: var(--font-family-main);
}

blockquote strong {
  font-family: var(--font-family-main);
}

blockquote>p::before {
  color: var(--color-much);
  padding-right: 2%;
  content: "\f10d"; 
  font-family: "FontAwesome";
}



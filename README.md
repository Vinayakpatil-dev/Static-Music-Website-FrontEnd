LINK: https://static-music-website-frontend-vsp.netlify.app/

Developed a responsive frontend inspired from Spotify using HTML and CSS. Responsiveness achieved using CSS media-queries and flexbox properties. Improved understanding of UI/UX principles and browser compatibility. Hosted the project using Netlify.

Focused mainly on 2 sections of the webpage - Main and Music Player. Main section is further split into 2 parts - Sidebar and Main-Content.

Sidebar layout consists of a navigation panel and a library panel. Display changes according to screen size, certain elements change alignment while certain elements are hidden. The sidebar collapses into an icon-only thin sidebar for smaller screens.

Main-content consists of a sticky navigation bar which also hides and aligns certain elements on smaller screen sizes to accomodate the prioritized elements. Further, the main-content includes multiple card sections to display songs with banner, title and description/singer name. The card sections were designed once and then mutiplied using HTML classes to reduce unnecessary repetition of code and safe time.

The Music-player panel is split into 3 parts to systematically align the currently playing album info, player controls, and other player options. This panel is made to stay at the given height at the bottom of the screen by using CSS calc() for the Main section which assigns the calculated remaining height of the viewport to the Main section.

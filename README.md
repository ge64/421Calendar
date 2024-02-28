# Calendar Component running on Storybook
## Installation
Storybook installed the Next.js builder when I did it the first time, but that option is no longer showing up so just use the Webpack5 builder instead.
### Clone repo 
`git clone https://github.com/ge64/IS421Calendar.git`
### Move into new directory 
- `cd IS421Calendar`
### Install dependencies 
- `npm install`
### Install Storybook 
`npx storybook@latest init`
- Installing as Webpack5 works, please don't ask me why
- It should immediately start running locally, otherwise: `npm run storybook`
  - If it gives you webpack errors try: `npm run storybook --debug-webpack`

### The important files are:
- [`src/exampleEvent.json`](chatty-calendar/src/exampleEvent.json) - JSON of the hardcoded mock event data.
- [`src/MyCalendar.js`](chatty-calendar/src/MyCalendar.js) - The actual React component.
- [`stories/MyCalendar.stories.js`](stories/MyCalendar.stories.js) - The story for the Calendar Component.

"MyCalendar" is the calendar component with the color coded events.<br>
"MyCalendar2" is just the calendar component 

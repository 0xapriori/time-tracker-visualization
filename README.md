# Time Tracker Visualization

A simple web application to visualize time tracking data. Paste your time entries and get instant visualization of how your time is distributed across different categories.

## Features

- Easy time entry input in [X mins] format
- Automatic categorization of activities
- Interactive pie chart visualization
- Time distribution summary
- Hover tooltips with detailed information

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/time-tracker-visualization.git
cd time-tracker-visualization
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npm start
# or
yarn start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Usage

1. Enter your time entries in the following format:
```
[30 mins] Meeting with team
[60 mins] Documentation work
[45 mins] Code review
```

2. Click "Generate Chart" to see the visualization

3. Hover over chart segments to see detailed information

## Categories

The application automatically categorizes tasks based on keywords:

- Meetings & Calls: call, sync, meeting, standup
- Research & Documentation: research, documentation, write, draft
- Planning & Strategy: plan, strategy, prep
- Development & Testing: test, develop, code
- Communication & Tasks: message, response, coordination
- Other: anything that doesn't match the above categories

## Building for Production

To build the app for production:

```bash
npm run build
# or
yarn build
```

This creates an optimized build in the `build` folder.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

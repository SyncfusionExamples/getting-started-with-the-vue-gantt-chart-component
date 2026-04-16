# Vue Gantt Chart Component Example

A sample Vue 3 repository showing Syncfusion Gantt chart usage and task configuration.

A lightweight Vue 3 starter project demonstrating a Syncfusion EJ2 Gantt Chart integration.

This project loads hierarchical task data from `src/data.js` and renders it using `@syncfusion/ej2-vue-gantt` in `src/App.vue`.

## Features

- Vue 3 app scaffolded with Vue CLI
- Syncfusion Gantt chart component with custom columns
- Week timeline view mode
- Task data with subtasks, dependencies, progress, and indicators
- Syncfusion license registration in `src/main.js`

## Prerequisites

- Node.js
- npm
- Vue CLI (optional, but recommended for `vue-cli-service`)

## Installation

```bash
npm install
```

## Usage

```bash
npm run serve
```

Then open the local URL shown in the terminal, usually `http://localhost:8080`.

## Notes

- The app imports Syncfusion Material CSS from CDN in `src/App.vue`.
- `src/main.js` includes a Syncfusion license registration call.
- `src/App.vue` maps task fields such as `TaskID`, `TaskName`, `StartDate`, `EndDate`, `Duration`, `Progress`, `subtasks`, and `Predecessor`.
- Sample data contains predecessor values that may be invalid (`28ss`, `36ss`). Adjust them before using the dataset in production.

## Dependencies

- `vue`
- `@syncfusion/ej2-vue-gantt`
- `core-js`

## Dev Dependencies

- `@vue/cli-service`
- `@vue/cli-plugin-babel`
- `@vue/cli-plugin-eslint`
- `eslint`

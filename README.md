
# Vue Gantt Chart Component Example

## Repository Description
This repository provides a Vue 3 application example demonstrating how to integrate the Syncfusion Gantt Chart component for visualizing hierarchical task data and managing project timelines.

## Overview

This sample project shows how to use the `@syncfusion/ej2-vue-gantt` package to render a Gantt chart in a Vue 3 application. The app loads hierarchical task data from a local data source and displays it with configurable task fields, dependencies, and timeline settings.

## Features

- Vue 3 integration with Syncfusion Gantt chart
- Hierarchical task structure with subtasks
- Task dependencies and progress tracking
- Custom column configuration and timeline view
- Support for task indicators and relationships

## Prerequisites

- Node.js (LTS version recommended)
- npm

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

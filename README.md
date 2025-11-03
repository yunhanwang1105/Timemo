# Timemory Organiser

A Java-based task organizer application that uses the forgetting curve algorithm to help users manage their tasks and improve memory retention through spaced repetition.

## Overview

Timemory Organiser is a desktop application designed to help users organize their tasks while leveraging the forgetting curve theory to optimize learning and memory retention. The application combines task management with a scientific approach to scheduling reviews and reminders.

## Features

### Task Management
- Create, edit, and delete tasks
- Organize tasks in lists
- Track task completion and progress

### Forgetting Curve Integration
- Implement forgetting curve algorithms for optimal review scheduling
- Automatically calculate review intervals based on memory retention research
- Manage multiple forgetting curve profiles

### Planning & Scheduling
- Create plans for task completion
- Visualize forgetting curves through charts
- Receive notifications for scheduled reviews

### User Interface
- Main window with task and forgetting curve management
- Dedicated windows for creating new tasks and forgetting curves
- Chart visualization for forgetting curve data
- Notification system for reminders

## Project Structure

```
Timemory/
├── Product/
│   └── Timemory.jar          # Executable JAR file
├── Documentation/
│   ├── Criterion_A_Planning.pdf
│   ├── Criterion_B_Design.pdf
│   ├── Criterion_C_Development.pdf
│   ├── Criterion_D_Video.avi
│   ├── Criterion_E_Evaluation.pdf
│   ├── ROT.pdf               # Record of Tasks
│   └── Appendices.pdf
├── cover_page.htm            # Project cover page
└── README.md                 # This file
```

## Installation & Running

### Prerequisites
- Java Runtime Environment (JRE) 8 or higher

### Running the Application

1. Navigate to the `Product` directory:
   ```bash
   cd Product
   ```

2. Run the JAR file:
   ```bash
   java -jar Timemory.jar
   ```

Alternatively, if Java is in your PATH, you can run it from anywhere:
```bash
java -jar /path/to/Timemory/Product/Timemory.jar
```

## Application Architecture

### Core Components

**Inner Package** (Business Logic):
- `Task` - Represents individual tasks
- `TaskList` - Manages collections of tasks
- `ForgettingCurve` - Implements forgetting curve data structure
- `ForgettingCurveList` - Manages multiple forgetting curves
- `ForgettingCurveMethods` - Contains algorithms for forgetting curve calculations
- `Plan` - Handles task planning and scheduling

**Outer Package** (User Interface):
- `MainWindow` - Main application window
- `TaskListWindow` - Task management interface
- `FCListWindow` - Forgetting curve list interface
- `NewTaskWindow` - Dialog for creating new tasks
- `NewFCWindow` - Dialog for creating new forgetting curves
- `ChartWindow` & `ChartPanel` - Visualization components
- `FirstNotificationWindow` & `SecondNotificationWindow` - Reminder notifications

## Documentation

This project includes comprehensive documentation following IB Computer Science criteria:

- **Criterion A - Planning**: Project planning and requirements analysis
- **Criterion B - Design**: System design and architecture
- **Criterion C - Development**: Implementation details and code development
- **Criterion D - Functionality**: Video demonstration of the application
- **Criterion E - Evaluation**: Project evaluation and reflection
- **ROT (Record of Tasks)**: Development task tracking
- **Appendices**: Additional supporting materials

All documentation is available in the `Documentation/` directory.

## Project Information

- **Developer**: Yunhan Wang
- **Candidate Number**: hww089
- **Session Number**: 004556-0002
- **Client**: Lucy Z.
- **Solution Title**: Timemory Organiser

## Technical Details

- **Language**: Java
- **Build Tool**: JAR packaging
- **Main Class**: `Outer.MainWindow`
- **Platform**: Cross-platform (requires JRE)

## License

This project was developed as part of an IB Computer Science coursework submission.

## Support

For questions or issues, please refer to the documentation in the `Documentation/` directory or contact the developer.


# Hospital 3D Metrics Visualization

An interactive 3D visualization system for hospital metrics using Three.js, React, and Python.

## Features

- 3D visualization of hospital buildings and floors
- Interactive floor selection and metric display
- Real-time metric updates
- Heat map visualization
- Flexible metric system

## Setup

### Frontend
```bash
cd frontend
npm install
npm start
```

### Backend
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

## Data Format

The system accepts CSV files with the following structure:
```
building,floor,patient_satisfaction,fall_risk
West,1 West,82,Low
...
```

## Usage

1. Start both frontend and backend servers
2. Access the visualization at http://localhost:3000
3. Interact with the 3D model:
   - Rotate: Click and drag
   - Zoom: Scroll
   - Select floor: Click on floor
   - View metrics: Hover over floor
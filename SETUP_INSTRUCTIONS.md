# PrivOCR Dashboard Setup Instructions

## Issue: 'vite' is not recognized error This error occurs because the project dependencies haven't been installed yet.

## Solution Steps:

### Step 1: Install Node.js (if not already installed)
- Download and install Node.js from https://nodejs.org/
- Verify installation by running: `node --version` and `npm --version`

### Step 2: Install Project Dependencies
Navigate to your project directory and run one of these commands:

#### Option A: Using npm (recommended)
```bash
cd C:\Users\welcome\Downloads\privocr-dashboard
npm install
```

#### Option B: Using yarn (if you prefer yarn)
```bash
cd C:\Users\welcome\Downloads\privocr-dashboard
yarn install
```

### Step 3: Start the Development Server
After installation completes, run:
```bash
npm start
```
or
```bash
yarn start
```

## What These Commands Do:
- `npm install` - Downloads and installs all dependencies listed in package.json into a `node_modules` folder
- `npm start` - Runs the Vite development server (equivalent to running `vite` directly)

## Expected Output:
After running `npm start`, you should see:
```
  VITE v5.0.0  ready in [time]ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h to show help
```

## Troubleshooting:
- If you get permission errors, try running the terminal as administrator
- If installation is slow, you can try: `npm install --legacy-peer-deps`
- Clear npm cache if needed: `npm cache clean --force`

## Project Structure After Setup:
- `node_modules/` folder will be created (this contains all dependencies including Vite)
- The project will run on http://localhost:5173/
# Wondle ROI Calculator

This repository contains interactive ROI calculators for Wondle's vehicle damage management solution.

## What It Does

The calculator helps businesses estimate potential cost savings from using Wondle's platform. It includes two specialized calculators:

1. **Leasing Company Calculator** - Calculates savings from reduced damage complaints, goodwill payments, and delayed remarketing costs
2. **Fleet Damage Calculator** - Estimates savings from managing minor damage, including end-of-contract costs and unreported insurance claims (FNOLs)

Users can adjust multiple parameters using interactive sliders and see real-time calculations of potential annual savings.

## Main File

**Everything you need is in `index.html`**

This single file contains both calculators with a tab-switching interface. Simply open `index.html` in a web browser to use the calculators - no build process or server required.

## Other Files

The other files in this repository are either:
- Older standalone versions (`fleet-damage-calculator.html`, `damage-calculator_2.html`)
- JavaScript libraries loaded from CDN (React, Babel) - included locally as backups

You can safely ignore these files when reviewing or modifying the calculator.

## Features

- **Interactive sliders** with real-time calculation updates
- **Sticky results display** - results stay visible while scrolling through inputs
- **Tooltips** on key fields to explain parameters
- **Responsive design** - works on desktop and mobile
- **No dependencies** - self-contained HTML file using CDN resources

## Technical Stack

- Pure HTML/CSS/JavaScript
- React 18 (loaded via CDN)
- Babel standalone (for JSX transformation)
- No build tools required

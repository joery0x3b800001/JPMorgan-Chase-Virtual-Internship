<p align="center">
  <a href="https://www.insidesherpa.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/Technology%20Virtual%20Experience" target="_blank">
    <img src="https://insidesherpa-assets.s3-ap-southeast-2.amazonaws.com/icons/jpmorgan/github+repo+images/jpmc+github+img.png">
  </a>
</p>

<p align="center"> 
  <b><a href="#task">Task Overview</a></b>
  | 
  <b><a href="#installation">Installation Instructions</a></b>
  | 
  <b><a href="https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/88AisH7iuw3L5N5ig" target="_blank">Link to Module 2</a></b>
</p>

# Introduction
<b>Experience Technology at JP Morgan Chase</b>

<p>Explore the real-world work environment of JP Morgan Chase's technology team. Accelerate your journey into the tech industry with hands-on tasks.</p>

## Module 2 Task Overview
<p>Implement JP Morgan Chase's frameworks and tools to enhance data visualization capabilities using Perspective.</p>

<b>Aim:</b> Modify and integrate the Perspective codebase with Task 1's setup to enable automatic data updates from the server application.

<ol>
  <li>Clone this repository to begin the task.</li>
  <li><b>[goal-a]</b> Update the client application to prevent duplicate entries in the table when new data is retrieved.</li>
  <li><b>[goal-b]</b> Modify the React app to continuously query data from the server every 100ms upon clicking 'Start Streaming'.</li>
  <li><b>[goal-c]</b> Configure Perspective to display historical data of ask_price ABC in a Y-line chart upon data load.</li>
  <li>Submit a git patch file as your task submission.</li>
</ol>

## Installation Instructions
<p>Follow these steps to set up the server and client application code on your machine:</p>

- [Setup Guide](https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/setup_devenv_m2_v8.pdf)

<p><b>Note:</b> This version of the JPM 2 exercise uses Python 3. For Python 2.7 version, visit <a href="https://github.com/insidesherpa/JPMC-tech-task-2">this repository</a>.</p>

## How to Run
<p>To start the data feed server:</p>

```bash
python datafeed/server3.py
```

<p>If encountering issues with `datautil.parser`, install it using:</p>

```bash
pip install -r requirements.txt
```

<p>For Windows users, run your terminal/command prompt as administrator.</p>

<p>To start the React application:</p>

```bash
npm install && npm start
```

<p>Open http://localhost:3000 in your browser to view the application. The page automatically reloads upon edits.</p>

## Known Issues
<p>Some users have reported issues with the unzipped version of node_modules for Windows. Here's an alternative version available for download:</p>

- [Alternative Node Modules](https://drive.google.com/drive/folders/1wzIlt-OeiK6nYEHidsOGlpJ_KmeoPVXz)

<p>Note: Refresh the link to see all files/folders, including @jpmorganchase/perspective.</p>

## How to Fix the Code to Meet Objectives
<p>Follow this guide to implement the necessary changes:</p>

- [Making Changes Guide](https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/making_changes_m2_v2.pdf)

## How to Submit Your Work
<p>To submit your work, create a patch file following this guide:</p>

- [Create Patch File Guide](https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/create_patch_file_v3a.pdf)

<p>Submit the patch file on the <a href="https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/88AisH7iuw3L5N5ig">JPM Module 2 Page</a>.</p>
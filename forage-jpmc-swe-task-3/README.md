<p align="center">
    <a href="https://www.insidesherpa.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/Technology%20Virtual%20Experience" target="_blank">
        <img src="https://insidesherpa-assets.s3-ap-southeast-2.amazonaws.com/icons/jpmorgan/github+repo+images/jpm+gitub+.png">
    </a>
</p>

<p align="center"> 
    <b><a href="#task">Task Overview</a></b>
    | 
    <b><a href="#installation">Installation Instructions</a></b>
    | 
    <b><a href="https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/EbtbrgmwKbgqcXyGt" target="_blank">Link to Module 3</a></b>    
</p>

<h1>Introduction</h1> 
<b>Experience Technology at JP Morgan Chase</b>
<p>Explore real work in the technology team at JP Morgan Chase & Co. Fast track your tech skills with hands-on experience.</p>

<h2 id="task">Module 3 Task Overview</h2>
<p>Display data visually for traders using Perspective to create a chart for the trader’s dashboard.</p>

<b>Aim:</b>
<ol>
    <li>Clone this repository to start the task.</li>
    <li>Modify the existing live graph to track the ratio between two stocks over time.</li>
    <li>Add functionality to track historical upper and lower bounds of the stocks' ratio.</li>
    <li>Implement 'alerts' on the graph when the bounds are crossed by the ratio within a specific time period.</li>
    <li>Submit your work as a git patch file.</li>
    <li>Upload a video detailing your process and work.</li>
</ol>

<h2 id="installation">Setup / Installation</h2>
<p>To set up the server and client application code on your machine, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/setup_devenv_m3_v3.pdf">follow these setup instructions</a>.</p>

<p><b>Note:</b> This version of the JPM 3 exercise uses Python 3. For Python 2.7 version, refer to <a href="https://github.com/insidesherpa/JPMC-tech-task-3">this repository</a>.</p>

<h2>How to Run</h2>
<p>Start the data feed server by running:</p>

<code>python datafeed/server3.py</code>

<p>If you encounter an issue with `datautil.parser`, run:</p>

<code>pip install -r requirements</code>

<p>To start the React application, run:</p>

<code>npm install && npm start</code>

<p>Open <a href="http://localhost:3000">http://localhost:3000</a> to view the app in your browser.</p>

<h2>Known Issues</h2>
<p>Some users are experiencing issues with the unzipped version of the node_modules backup for Windows. You can download the alternative unzipped version from <a href="https://drive.google.com/drive/folders/1wzIlt-OeiK6nYEHidsOGlpJ_KmeoPVXz">Google Drive</a>.</p>

<p>Note: It may take some time for all files/folders, like @jpmorganchase/perspective, to load on Google Drive.</p>

<h2>How to fix the code to meet the objectives</h2>
<p>To make the necessary changes for this task, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/making_changes_m3_v2.pdf">follow this guide</a>.</p>

<h2>How to submit your work</h2>
<p>Submit a patch file. Learn how to create a patch file <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/create_patch_file_v3a.pdf">here</a> and submit it on the <a href="https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/EbtbrgmwKbgqcXyGt">JPM Module 3 Page</a>.</p>
# Linux Screen Hypervisor
Linux hypervisor script written in BASH for maintaining a consistent amount of screens on a server.

Works great if you have random crashes due to external circumstances and just need to keep a consistent amount of screens open. Super simple, works great.

## Setup
<ol>
<li>Edit the <code>desired_screen_count</code> to be your number of screens</li>
<li>Edit the <code>commad</code> portion of the command executor</li>
<li>Add this script to your crontab with your desired interval</li>
</ol>

Make sure you give permission for the script to be executed.

![Animated Background](https://cdn.discordapp.com/attachments/1518163157292552293/1518180822631321640/4_20260621170820.png?ex=6a38fb92&is=6a37aa12&hm=bbb80d5f3d5d165c1f7b8cfa9ec448b6bfe2bb201d26b1e2a1e8a07a107e3204&)

<h1 align="center" style="font-family: Arial, sans-serif; color: #FF6F61; text-shadow: 2px 2px 4px rgba(0,0,0,0.5);">
  FriendsHub
</h1>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square&logo=opensource"
      alt="License: MIT" />
  </a>

<p align="center">
  <a href="https://www.youtube.com/channel/@rokanch1k">
    <img src="https://img.shields.io/badge/YouTube-Subscribe-red?style=flat-square&logo=youtube"
      alt="YouTube" />
  </a>
</p>

<h2>Installation Guide</h2>

<h3>How to Install</h3>

<h4>Step 1: Update <code>config.json</code> [ USE ENV FILES ]</h4>

<ol>
  <li>Open the <code>config.json</code> and add your MongoDB URL.</li>
</ol>

<h4>ENV SETUP</h4>

<pre>
TOKEN=
MONGODB_URI=
</pre>

<h4>Step 2: Set Up Hosting Service</h4>

<ol>
  <li>Go to your preferred hosting service. For this guide, we use <a href="https://render.com/">Render</a>.</li>
  <li>In the Build & Deploy section, paste your repository URL.</li>
</ol>

<h4>Step 3: Add Build and Start Commands</h4>
<pre>
Run the following commands to install dependencies and start your bot:

npm install
node index.js
</pre>

<h4>Step 4: Get Your Bot Token</h4>
<ol>
  <li>Navigate to the Discord Developer Portal.</li>
  <li>Find your application, and retrieve the bot token from the "Bot" section.</li>
</ol>

<h4>Step 5: Set Environment Variable</h4>
<ol>
  <li>Create an environment variable with the following details:</li>
  <ul>
    <li>Key: TOKEN</li>
    <li>Value: [your bot token]</li>
  </ul>
  <li>Deploy your application using your hosting service’s deployment process.</li>
</ol>

<h4>Step 6: Wait and Test</h4>
<ol>
  <li>Wait approximately five minutes for your bot to deploy and start up.</li>
  <li>Test your bot by sending commands to ensure it is operational.</li>
</ol>

<p>🎉 Congratulations! Your bot is now up and running. 🥳</p>

<h3>Additional Resources</h3>
<p><strong>Video Tutorial:</strong> If you prefer a video guide, watch this YouTube tutorial [ Soon ].</p>
<p><strong>Common Errors:</strong> Consult the errors section for troubleshooting.</p>

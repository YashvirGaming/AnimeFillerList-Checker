<h1>AnimeFillerList Checker 🎯</h1>

<p>
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue" alt="Python Version">
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20Mac-lightgrey" alt="Platform">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
</p>

<p>
AnimeFillerList Checker is a premium CLI tool built with <strong>httpx</strong> that automates login testing against animefillerlist.com using multi-threading, proxy support, and advanced parsing logic.
Designed with the <strong>Shadow ASCII Art</strong> CLI template for a professional, eye-catching terminal display.
</p>

<img width="1095" height="588" alt="image" src="https://github.com/user-attachments/assets/450be5c1-6303-4a4c-98ea-3e245f944b67" />


<h2>✨ Features</h2>
<ul>
  <li>🖼 <strong>Shadow ASCII Art</strong> header + centered subtitle with line break</li>
  <li>🚀 Multi-threading (Default 30 threads, Max 100)</li>
  <li>🔄 Full proxy support (<code>ip:port</code>, <code>ip:port:user:pass</code>, <code>user:pass@ip:port</code>) — HTTP/HTTPS/SOCKS</li>
  <li>📂 Drag & Drop combo and proxy file loading (no auto-stripping)</li>
  <li>🔑 GET/POST login flow with <strong>form_build_id</strong> parsing</li>
  <li>✏️ Auto converts email to username & URL-encodes passwords</li>
  <li>🖍 Colored output for Hits & Fails</li>
  <li>📊 Live CPM counter in terminal</li>
  <li>📝 Saves valid logins to <code>Hits.txt</code></li>
  <li>🛡 Automatic cookie & content-length handling via httpx</li>
</ul>

<h2>📦 Installation</h2>
<pre><code>pip install -r requirements.txt
</code></pre>

<h2>▶ Usage</h2>
<pre><code>python animefillerlist_checker.py
</code></pre>

<h2>📜 Requirements</h2>
<ul>
  <li>Python 3.10+</li>
  <li>httpx</li>
  <li>colorama</li>
</ul>

<h2>💡 Notes</h2>
<p>
If no proxies are loaded, the checker will attempt direct/VPN connection.  
Proxies are automatically detected and formatted for use.
</p>

<h2>📌 GitHub</h2>
<p>
<a href="https://github.com/YashvirGaming/AnimeFillerList-Checker" target="_blank">
https://github.com/YashvirGaming/AnimeFillerList-Checker
</a>
</p>

<h2>❤️ Credits</h2>
<p>Made with love ♥ by Yashvir Gaming<br>
Telegram: <a href="https://t.me/therealyashvirgaming" target="_blank">https://t.me/therealyashvirgaming</a></p>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bulk Email Sender - Documentation</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 40px;
      background: #f9fafc;
      color: #222;
    }
    h1, h2, h3 {
      color: #333;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    h2 {
      font-size: 1.8rem;
      margin-top: 40px;
      margin-bottom: 15px;
    }
    p {
      font-size: 1.1rem;
      margin-bottom: 15px;
    }
    code {
      background: #eee;
      padding: 2px 6px;
      border-radius: 4px;
      font-family: Consolas, monospace;
    }
    pre {
      background: #1e1e1e;
      color: #dcdcdc;
      padding: 16px;
      border-radius: 8px;
      overflow-x: auto;
    }
    ul {
      margin: 10px 0 20px 20px;
    }
    li {
      margin-bottom: 8px;
    }
    .preview {
      margin: 20px 0;
      text-align: center;
    }
    .preview img {
      max-width: 100%;
      border-radius: 12px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.15);
    }
    footer {
      margin-top: 50px;
      font-size: 0.9rem;
      text-align: center;
      color: #666;
    }
  </style>
</head>
<body>

  <h1>📧 Bulk Email Sender - Digital Marketing SaaS</h1>
  <p>
    A responsive, glassmorphism-themed <strong>Bulk Email Sender</strong> built with 
    <code>HTML</code>, <code>CSS (Tailwind + custom styles)</code>, and <code>JavaScript</code>.  
    This tool allows digital marketers to upload a TXT file containing email addresses, add a subject and message, and send personalized campaigns directly via the client’s mail app (<code>mailto:</code>).
  </p>

  <h2>✨ Features</h2>
  <ul>
    <li>🎨 Modern UI/UX with animated gradient + glassmorphism card design</li>
    <li>📂 Upload <strong>TXT file</strong> containing email addresses</li>
    <li>📝 Add <strong>Subject & Message</strong> dynamically</li>
    <li>📧 Parse and validate emails automatically</li>
    <li>🚀 One-click <strong>Load Emails</strong> button to preview recipients</li>
    <li>🗂️ Email list displayed in a beautiful card layout</li>
    <li>⏳ Email status tracking (Pending → Sent ✅)</li>
    <li>🔄 <strong>Dark / Light Mode</strong> toggle with animated gradient</li>
    <li>⚡ Fully responsive design (mobile + desktop)</li>
    <li>🔒 Client-side only (no backend required)</li>
  </ul>

  <h2>📸 Preview</h2>
  <div class="preview">
    <img src="https://via.placeholder.com/900x500.png?text=Bulk+Email+Sender+Preview" alt="Preview">
  </div>

  <h2>🚀 Getting Started</h2>
  <h3>1️⃣ Clone the repo</h3>
  <pre><code>git clone https://github.com/your-username/bulk-email-sender.git
cd bulk-email-sender</code></pre>

  <h3>2️⃣ Open in browser</h3>
  <p>Just open <code>index.html</code> in your browser. No server setup required.</p>

  <h2>📂 File Structure</h2>
  <pre><code>📦 bulk-email-sender
 ┣ 📜 index.html      # Main app
 ┣ 📜 README.html     # Documentation
</code></pre>

  <h2>🛠️ Tech Stack</h2>
  <ul>
    <li><strong>Frontend:</strong> HTML5, CSS3, TailwindCSS, Custom CSS animations</li>
    <li><strong>Logic:</strong> Vanilla JavaScript</li>
    <li><strong>UX/UI:</strong> Glassmorphism, Animated Gradient Background, Responsive Grid</li>
  </ul>

  <h2>⚙️ How It Works</h2>
  <ol>
    <li>Upload a <code>.txt</code> file with email addresses (one per line).</li>
    <li>Enter campaign subject and message.</li>
    <li>Click <strong>Load Emails</strong> → Emails are parsed and displayed.</li>
    <li>Click <strong>Send</strong> on any email → Opens your default email client (<code>mailto:</code>).</li>
    <li>Status updates to ✅ Sent.</li>
  </ol>

  <h2>📖 Example TXT File</h2>
  <pre><code>example1@gmail.com
example2@yahoo.com
example3@outlook.com</code></pre>

  <h2>🌓 Dark / Light Mode</h2>
  <p>
    🌙 <strong>Dark Mode</strong> → Minimalist black/gray gradient <br>
    ☀️ <strong>Light Mode</strong> → Colorful animated gradient <br><br>
    Toggle using the top-right button.
  </p>

  <h2>📜 License</h2>
  <p>
    MIT License © 2025 <a href="https://github.com/your-username" target="_blank">Vertectis</a>
  </p>

  <footer>
    🚀 Built with ❤️ by <strong>Vertectis</strong>
  </footer>

</body>
</html>

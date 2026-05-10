
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CyberSickoexe | IT Infrastructure & Automation</title>

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;800&family=Rajdhani:wght@400;600&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    background:#050816;
    color:#d9faff;
    font-family:'Rajdhani',sans-serif;
    overflow-x:hidden;
    background-image:
    radial-gradient(circle at top left,#0ff2 0%,transparent 25%),
    radial-gradient(circle at bottom right,#ff00ff22 0%,transparent 25%);
}

.container{
    width:90%;
    max-width:1300px;
    margin:auto;
    padding:50px 0;
}

.hero{
    text-align:center;
    padding:80px 20px;
    border:1px solid #00ffff55;
    background:#0a0f24cc;
    backdrop-filter:blur(10px);
    border-radius:20px;
    box-shadow:0 0 40px #00ffff22;
    margin-bottom:40px;
}

.hero h1{
    font-family:'Orbitron',sans-serif;
    font-size:4rem;
    color:#00ffff;
    text-shadow:0 0 15px #00ffff;
    margin-bottom:15px;
}

.hero h2{
    color:#ff00ff;
    font-size:1.5rem;
    margin-bottom:20px;
}

.hero p{
    max-width:900px;
    margin:auto;
    font-size:1.2rem;
    color:#c8d8ff;
    line-height:1.8;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
    gap:25px;
}

.card{
    background:#0a0f24cc;
    border:1px solid #00ffff33;
    border-radius:20px;
    padding:30px;
    transition:0.3s ease;
    position:relative;
    overflow:hidden;
}

.card::before{
    content:'';
    position:absolute;
    width:200%;
    height:2px;
    background:linear-gradient(90deg,transparent,#00ffff,transparent);
    top:0;
    left:-50%;
    animation:scan 4s linear infinite;
}

@keyframes scan{
    0%{transform:translateX(-100%);}
    100%{transform:translateX(100%);}
}

.card:hover{
    transform:translateY(-10px);
    box-shadow:0 0 25px #00ffff44;
}

.card h3{
    color:#00ffff;
    font-family:'Orbitron',sans-serif;
    margin-bottom:20px;
    font-size:1.4rem;
}

.card ul{
    list-style:none;
}

.card ul li{
    padding:8px 0;
    border-bottom:1px solid #ffffff11;
    color:#d4eaff;
}

.section-title{
    font-family:'Orbitron',sans-serif;
    color:#ff00ff;
    margin:50px 0 25px;
    font-size:2rem;
    text-shadow:0 0 10px #ff00ff;
}

.project{
    margin-bottom:30px;
    padding:25px;
    border-left:4px solid #00ffff;
    background:#0f142d;
    border-radius:12px;
}

.project h4{
    color:#00ffff;
    margin-bottom:10px;
    font-size:1.4rem;
}

.project p{
    color:#cddfff;
    line-height:1.7;
}

a{
    color:#00ffff;
    text-decoration:none;
    transition:0.3s;
}

a:hover{
    color:#ff00ff;
    text-shadow:0 0 10px #ff00ff;
}

.footer{
    text-align:center;
    margin-top:60px;
    padding:30px;
    color:#8aa0d0;
    border-top:1px solid #00ffff22;
}

.glow{
    color:#00ffff;
    text-shadow:0 0 15px #00ffff;
}
</style>
</head>

<body>

<div class="container">

<div class="hero">
    <h1>CYBERSICKOEXE ⚡</h1>
    <h2>IT Infrastructure • PowerShell Automation • Enterprise Systems</h2>

    <p>
        Building advanced PowerShell automation systems focused on IT administration,
        diagnostics, network visibility, infrastructure monitoring, and enterprise support workflows.
        Passionate about creating high-efficiency tooling that improves troubleshooting speed,
        system intelligence, and operational automation.
    </p>
</div>

<h2 class="section-title">SYSTEM FOCUS</h2>

<div class="grid">

<div class="card">
    <h3>⚙ SYSTEM ADMINISTRATION</h3>
    <ul>
        <li>Windows Diagnostics</li>
        <li>Performance Monitoring</li>
        <li>Event Log Analysis</li>
        <li>Service Management</li>
        <li>Automated Reporting</li>
    </ul>
</div>

<div class="card">
    <h3>🌐 NETWORK OPERATIONS</h3>
    <ul>
        <li>DNS Analysis</li>
        <li>TCP Connection Mapping</li>
        <li>Traceroute Diagnostics</li>
        <li>Infrastructure Visibility</li>
        <li>Network Monitoring</li>
    </ul>
</div>

<div class="card">
    <h3>🖥 POWERSHELL AUTOMATION</h3>
    <ul>
        <li>GUI-Based Toolkits</li>
        <li>Windows Forms (.NET)</li>
        <li>Modular Architecture</li>
        <li>Repair Automation</li>
        <li>Enterprise Workflow Tools</li>
    </ul>
</div>

</div>

<h2 class="section-title">ACTIVE PROJECTS</h2>

<div class="project">
    <h4>🖥 IT SUPPORT ADMIN TOOLKIT</h4>
    <p>
        Advanced PowerShell GUI toolkit designed to centralize diagnostics,
        event analysis, network monitoring, service visibility, and automated
        reporting into a single enterprise-style administrative interface.
    </p>
    <br>
    <a href="https://github.com/CyberSickoexe/PowerShell-Projects">
        ► View GitHub Repository
    </a>
</div>

<div class="project">
    <h4>🖨 PRINTER AI TECHNICIAN TOOLKIT</h4>
    <p>
        Intelligent Windows print infrastructure repair system capable of spooler
        diagnostics, queue recovery, automated repair logic, and helpdesk-ready
        reporting workflows.
    </p>
</div>

<h2 class="section-title">TECH STACK</h2>

<div class="grid">

<div class="card">
    <h3>💻 CORE TECHNOLOGIES</h3>
    <ul>
        <li>PowerShell 5.1+</li>
        <li>Windows Forms (.NET)</li>
        <li>JSON Configuration Systems</li>
        <li>Windows Administration</li>
        <li>Infrastructure Automation</li>
    </ul>
</div>

<div class="card">
    <h3>📡 INFRASTRUCTURE</h3>
    <ul>
        <li>Windows 10 / 11</li>
        <li>Active Directory</li>
        <li>Task Scheduler</li>
        <li>System Services</li>
        <li>Network Diagnostics</li>
    </ul>
</div>

</div>

<div class="footer">
    <p>
        <span class="glow">STATUS:</span>
        PROJECTS CURRENTLY IN ACTIVE DEVELOPMENT ⚡
    </p>

    <br>

    <a href="https://www.linkedin.com/in/riku-32ab26265/">
        LinkedIn Profile
    </a>
</div>

</div>

</body>
</html>

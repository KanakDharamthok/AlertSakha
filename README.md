<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AlertSakha README</title>
    <style>
        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            line-height: 1.6;
            color: #111827;
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem;
            background-color: #F5F7FA;
        }
        .container {
            background: white;
            padding: 3rem;
            border-radius: 12px;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
        }
        h1 { color: #2563EB; border-bottom: 2px solid #2563EB; padding-bottom: 10px; }
        h2 { color: #1E40AF; margin-top: 2rem; border-left: 4px solid #2563EB; padding-left: 15px; }
        h3 { color: #374151; }
        code {
            background: #f1f5f9;
            padding: 0.2rem 0.4rem;
            border-radius: 4px;
            font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, monospace;
            font-size: 0.9em;
        }
        .tag {
            display: inline-block;
            background: #DBEAFE;
            color: #1E40AF;
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 600;
            margin-bottom: 1rem;
        }
        ul { padding-left: 1.5rem; }
        li { margin-bottom: 0.5rem; }
        hr { border: 0; border-top: 1px solid #e5e7eb; margin: 2rem 0; }
        .footer { font-size: 0.9rem; color: #6B7280; text-align: center; margin-top: 3rem; }
        a { color: #2563EB; text-decoration: none; }
        a:hover { text-decoration: underline; }
    </style>
</head>
<body>

<div class="container">
    <h1>🛡️ AlertSakha (अलर्ट सखा)</h1>
    <p><strong>Rapid Crisis Response System for Hospitality</strong><br>
    <em>Accelerated Emergency Response and Crisis Coordination</em> [cite: 1]</p>

    <div class="tag">Google Solution Challenge 2026</div>

    <p>AlertSakha is a high-performance, real-time emergency management platform designed to solve the problem of fragmented communication during high-stakes crises in hotels and resorts. [cite: 3] By creating a reliable digital bridge, the system ensures that critical information is never siloed, enabling a synchronized response between guests, staff, and first responders. [cite: 4, 15]</p>

    <hr>

    <h2>🚀 Project Overview</h2>
    <p>Hospitality venues face unpredictable emergencies where every second counts. AlertSakha addresses the challenge of decentralized ecosystems by unifying emergency detection, instant reporting, and coordinated action into a single, seamless flow. [cite: 3, 4]</p>

    <h2>⚠️ Problem Statement</h2>
    <ul>
        <li><strong>Communication Silos:</strong> Critical information is often trapped within departments, leading to fractured responses. [cite: 14]</li>
        <li><strong>Response Delays:</strong> Manual reporting processes slow down the notification of security and emergency services. [cite: 6]</li>
        <li><strong>Decentralized Coordination:</strong> Lack of a "single source of truth" makes it difficult for personnel to synchronize efforts across large properties. [cite: 9]</li>
        <li><strong>Information Gaps:</strong> Distressed individuals often lack a direct, instant line to active personnel and first responders. [cite: 7, 17]</li>
    </ul>

    <h2>✅ Solution: The Reliable Bridge</h2>
    <p>AlertSakha acts as a robust solution to synchronize crisis response efforts through: [cite: 4]</p>
    <ul>
        <li><strong>Instant Reporting:</strong> A one-tap SOS system that bypasses traditional delays. [cite: 11, 26]</li>
        <li><strong>Unified Dashboard:</strong> A centralized "Admin Hub" that synchronizes data between sensors, staff, and management. [cite: 12, 29]</li>
        <li><strong>Real-Time Synchronization:</strong> Using <code>Socket.io</code> to ensure every stakeholder is updated simultaneously without lag. [cite: 14, 28]</li>
        <li><strong>Emergency Service Integration:</strong> Direct digital bridges to police, fire, and ambulance services to eliminate fragmented external communication. [cite: 15]</li>
    </ul>

    <h2>🚀 Key Features</h2>
    <ul>
        <li><strong>One-Tap SOS Button:</strong> Instant reporting for guests and users to trigger immediate alerts. [cite: 11, 26]</li>
        <li><strong>Live Location Tracking:</strong> Provides precise coordinates to security teams for rapid on-site intervention. [cite: 27]</li>
        <li><strong>Automatic Stakeholder Notification:</strong> Simultaneously alerts management, security, and emergency services the moment an SOS is triggered. [cite: 8, 30]</li>
        <li><strong>Real-Time Incident Timeline:</strong> A live-updating log of status changes, assignments, and resolution notes. [cite: 14, 29]</li>
        <li><strong>AI-Based Risk Prediction:</strong> Advanced sensors and AI models to detect potential threats before they escalate. [cite: 13, 33]</li>
    </ul>

    <h2>👥 User Roles & Coordination</h2>
    <h3>👑 Admin / Manager</h3>
    <ul>
        <li>Monitors all active emergencies across the decentralized ecosystem. [cite: 12]</li>
        <li>Assigns staff and coordinates with external emergency services. [cite: 15, 17]</li>
    </ul>
    <h3>🛡️ Security & Staff</h3>
    <ul>
        <li>Receives instant mobile alerts with live location data. [cite: 17, 28]</li>
        <li>Updates incident status in real-time to keep the centralized hub synchronized. [cite: 14]</li>
    </ul>
    <h3>🏨 Guest / User</h3>
    <ul>
        <li>Reports emergencies via voice or tap, ensuring a direct line to help. [cite: 11, 34]</li>
        <li>Uploads photo/video evidence to provide active personnel with visual context. [cite: 11]</li>
    </ul>

    <h2>🛠️ Tech Stack</h2>
    <ul>
        <li><strong>Frontend:</strong> React.js, Tailwind CSS (Clean, high-visibility UI for high-stress environments). [cite: 19]</li>
        <li><strong>Backend:</strong> Node.js, Express.js (High-concurrency API for rapid data processing). [cite: 20]</li>
        <li><strong>Real-Time:</strong> <code>Socket.io</code> (The core engine for instant synchronization and broadcasts). [cite: 14]</li>
        <li><strong>Database:</strong> MongoDB (Persistent logging of all crisis data). [cite: 21]</li>
        <li><strong>Advanced:</strong> AI/ML models for risk prediction and face recognition. [cite: 33, 36]</li>
    </ul>

    <hr>

    <div class="footer">
        <p>Academic & Demonstration Use Only © 2026</p>
        <p><strong>Author:</strong> Kanak Dharamthok | <strong>Prototype:</strong> <a href="https://alertsakha.lovable.app">alertsakha.lovable.app</a></p>
    </div>
</div>

</body>
</html>

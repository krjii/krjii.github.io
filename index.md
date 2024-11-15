<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>{{ page.title }}</title>
  <link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">
</head>
<body>
  <div class="container">
    <!-- Sidebar Section -->
    <aside class="sidebar">
      <h2>Kevin R. James</h2>
      <p><strong>Email:</strong> <a href="mailto:kevinrjamesii@outlook.com">kevinrjamesii@outlook.com</a></p>
      <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/kevinrjamesii" target="_blank">kevinrjamesii</a></p>
      
      <h3>Core Competencies</h3>
      <ul>
        <li>Systems Engineering</li>
        <li>Project Management</li>
        <li>Data Science</li>
        <li>Software Development</li>
      </ul>

      <h3>Technical Proficiency</h3>
      <ul>
        <li><strong>Languages:</strong> Python, C#, C++</li>
        <li><strong>Development Tools:</strong> DevOps, Automated Testing, Git, Docker, Kubernetes</li>
        <li><strong>Cloud & Infrastructure:</strong> AWS, IaC (Infrastructure as Code), Serverless Architecture</li>
        <li><strong>Data Visualization:</strong> Matplotlib, Seaborn, Plotly</li>
        <li><strong>Development Methodologies:</strong> FDD, DDD, TDD</li>
        <li><strong>Frameworks & Libraries:</strong> ASP.NET Core (C#), Qt, NLTK, scikit-learn, Matplotlib</li>
      </ul>
    </aside>

    <!-- Main Content Section -->
    <main class="content">
      {{ content }}
    </main>
  </div>
</body>
</html>

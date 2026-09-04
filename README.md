<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Youth Empowerment Project</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f4f7f5;
  color: #222;
}

.hero {
  background: linear-gradient(135deg, #006b3c, #0b8f3c);
  color: white;
  text-align: center;
  padding: 55px 20px;
}

.hero h1 {
  font-size: 42px;
  margin: 0 0 15px;
  font-weight: 800;
}

.hero p {
  font-size: 20px;
  margin: 0;
}

.badge {
  display: inline-block;
  background: #f4d000;
  color: #064d2d;
  padding: 10px 22px;
  border-radius: 30px;
  font-weight: bold;
  margin-top: 25px;
}

.container {
  max-width: 850px;
  margin: 30px auto;
  padding: 0 18px;
}

.card {
  background: white;
  border-radius: 24px;
  padding: 30px;
  margin-bottom: 25px;
  box-shadow: 0 8px 25px rgba(0,0,0,0.10);
}

.card h2 {
  color: #087f35;
  font-size: 28px;
  margin-top: 0;
}

.card p {
  font-size: 18px;
  line-height: 1.6;
}

.button {
  display: block;
  text-align: center;
  text-decoration: none;
  background: #087f35;
  color: white;
  padding: 17px;
  border-radius: 14px;
  font-size: 19px;
  font-weight: bold;
  margin-top: 20px;
}

.button:hover {
  background: #05652a;
}

.highlight {
  background: linear-gradient(135deg, #064d38, #087f35);
  color: white;
  text-align: center;
}

.highlight h2 {
  color: #f4d000;
}

.amount {
  font-size: 45px;
  font-weight: 900;
  color: #f4d000;
  margin: 15px 0;
}

.notice {
  background: #fff8d6;
  border-left: 5px solid #e0bd00;
  padding: 15px;
  border-radius: 10px;
  margin-top: 20px;
}

.features {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 15px;
  margin-top: 20px;
}

.feature {
  background: #eef8f1;
  padding: 20px;
  border-radius: 16px;
  text-align: center;
}

.feature h3 {
  color: #087f35;
}

footer {
  background: #064d38;
  color: white;
  text-align: center;
  padding: 30px 15px;
  margin-top: 40px;
}

@media (max-width: 600px) {
  .hero h1 {
    font-size: 34px;
  }

  .hero p {
    font-size: 18px;
  }

  .features {
    grid-template-columns: 1fr;
  }

  .amount {
    font-size: 38px;
  }
}
</style>
</head>

<body>

<section class="hero">
  <h1>Youth Empowerment Project</h1>
  <p>Information • Opportunities • Support</p>
  <div class="badge">EMPOWERING YOUNG PEOPLE</div>
</section>

<div class="container">

  <div class="card">
    <h2>Welcome 👋</h2>

    <p>
      Welcome to our independent youth empowerment project.
      We share information about opportunities, skills and
      useful resources for young people.
    </p>

    <a href="#opportunities" class="button">
      Explore Opportunities
    </a>
  </div>

  <div class="card highlight">
    <h2>Opportunities for Youth</h2>

    <div class="amount">BUILD • LEARN • GROW</div>

    <p>
      Discover opportunities that can help you develop
      your skills, grow your ideas and work toward your goals.
    </p>

    <a href="#opportunities" class="button">
      View Opportunities
    </a>
  </div>

  <div class="card" id="opportunities">
    <h2>What We Share</h2>

    <div class="features">

      <div class="feature">
        <h3>📚 Skills</h3>
        <p>Learning and training opportunities.</p>
      </div>

      <div class="feature">
        <h3>💼 Jobs</h3>
        <p>Information about legitimate opportunities.</p>
      </div>

      <div class="feature">
        <h3>🚀 Business</h3>
        <p>Resources for young entrepreneurs.</p>
      </div>

      <div class="feature">
        <h3>🤝 Support</h3>
        <p>Useful information and community resources.</p>
      </div>

    </div>
  </div>

  <div class="card">
    <h2>Important Notice</h2>

    <div class="notice">
      This is an independent information project. It is not
      an official government website and does not process
      government payments or request passwords, PINs or OTPs.
    </div>
  </div>

</div>

<footer>
  <p><strong>Youth Empowerment Project</strong></p>
  <p>Information • Opportunities • Support</p>
  <p>© 2026 Independent Project</p>
</footer>

</body>
</html>

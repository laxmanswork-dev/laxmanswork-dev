const GitHubProfile = () => {
  return (
    <div className="github-profile">
      {/* Header */}
      <section className="profile-header">
        <h1>Laxman S — Founder • Engineer • Builder</h1>

        <p className="tagline">
          <strong>Founder &amp; CEO — NIVLAK Technologies</strong>
          <br />
          Building digital products, software systems, and technology experiences.
        </p>
      </section>

      <hr />

      {/* About */}
      <section>
        <h2>About</h2>

        <p>
          I am the Founder &amp; CEO of <strong>NIVLAK Technologies</strong>,
          a technology company focused on building websites, SaaS products,
          custom software, AI automation solutions, mobile applications,
          and digital experiences.
        </p>

        <p>
          My foundation is in software engineering, and I remain hands-on
          with the technical side of the work — from architecture and
          development to product decisions and delivery.
        </p>

        <p>
          I focus on understanding real business problems and building
          technology around them — not simply creating software for the sake
          of software.
        </p>
      </section>

      <hr />

      {/* NIVLAK */}
      <section>
        <h2>NIVLAK Technologies</h2>

        <p>
          Building practical technology solutions for businesses,
          products, and digital brands.
        </p>

        <ul>
          <li>Website Development</li>
          <li>SaaS Product Development</li>
          <li>Custom Software Solutions</li>
          <li>AI Automation Solutions</li>
          <li>Mobile Application Development</li>
          <li>Branding &amp; Digital Experiences</li>
        </ul>
      </section>

      <hr />

      {/* Engineering */}
      <section>
        <h2>Engineering</h2>

        <p>
          <strong>Frontend:</strong> HTML, CSS, JavaScript, React
        </p>

        <p>
          <strong>Backend:</strong> Node.js, Express.js, REST APIs
        </p>

        <p>
          <strong>Database:</strong> MongoDB
        </p>

        <p>
          <strong>Engineering &amp; Tools:</strong> Git, GitHub, Docker,
          Socket.IO, JWT, Axios, Redux
        </p>

        <p>
          <strong>Focus:</strong> System Architecture, API Design,
          Authentication, Real-Time Systems, Responsive UI,
          Production Deployment
        </p>

        <div className="skills">
          <img
            src="https://skillicons.dev/icons?i=html,css,js,react,nodejs,express,mongodb,git,github,docker"
            height="48"
            alt="Technical Skills"
          />
        </div>
      </section>

      <hr />

      {/* Selected Work */}
      <section>
        <h2>Selected Work</h2>

        <article>
          <h3>PACERRA</h3>

          <p>
            A productivity-focused SaaS platform built around focus sessions,
            teams, real-time updates, XP, and streak-based engagement.
          </p>

          <p>
            <strong>Stack:</strong> React, Node.js, Express, MongoDB,
            Socket.IO, JWT
          </p>

          <a
            href="https://github.com/laxmanswork-dev/pacerra"
            target="_blank"
            rel="noreferrer"
          >
            View Repository →
          </a>
        </article>

        <article>
          <h3>CALIOON</h3>

          <p>
            A premium digital experience inspired by Greek mythology,
            designed around luxury branding and immersive storytelling.
          </p>

          <p>
            <strong>Stack:</strong> React, Vite, Tailwind CSS
          </p>

          <a
            href="https://github.com/laxmanswork-dev/CALIOON"
            target="_blank"
            rel="noreferrer"
          >
            View Repository →
          </a>
        </article>

        <article>
          <h3>Asukavi Acupuncture Clinic</h3>

          <p>
            A premium healthcare website experience focused on trust,
            service presentation, branding, and user experience.
          </p>

          <a
            href="https://github.com/laxmanswork-dev/asukavi-acupuncture-clinic"
            target="_blank"
            rel="noreferrer"
          >
            View Repository →
          </a>
        </article>

        <article>
          <h3>Shivdev Holidays</h3>

          <p>
            A large-scale travel website project focused on destination
            discovery, premium visual presentation, responsive experiences,
            and conversion-oriented user flows.
          </p>

          <a
            href="https://github.com/laxmanswork-dev/shivdev-holidays"
            target="_blank"
            rel="noreferrer"
          >
            View Repository →
          </a>
        </article>
      </section>

      <hr />

      {/* Building Philosophy */}
      <section>
        <h2>Building Through NIVLAK</h2>

        <blockquote>
          Understand the business.
          <br />
          Design the right solution.
          <br />
          Build it properly.
          <br />
          Deliver it for real-world use.
        </blockquote>
      </section>

      <hr />

      {/* GitHub Activity */}
      <section>
        <h2>GitHub Activity</h2>

        <div className="github-stats">
          <img
            src="https://github-readme-streak-stats-eight.vercel.app/?user=laxmanswork-dev&theme=tokyonight&hide_border=true"
            alt="GitHub Streak"
          />

          <img
            src="https://github-readme-activity-graph.vercel.app/graph?username=laxmanswork-dev&theme=tokyo-night&hide_border=false&area=true"
            width="90%"
            alt="GitHub Contribution Graph"
          />
        </div>
      </section>

      <hr />

      {/* Connect */}
      <section className="connect">
        <h2>Connect</h2>

        <p>
          <a
            href="https://github.com/laxmanswork-dev"
            target="_blank"
            rel="noreferrer"
          >
            GitHub
          </a>

          &nbsp; • &nbsp;

          <a
            href="https://www.linkedin.com/in/laxmanswork-dev/"
            target="_blank"
            rel="noreferrer"
          >
            LinkedIn
          </a>

          &nbsp; • &nbsp;

          <a href="mailto:laxmanswork.dev@gmail.com">
            Email
          </a>
        </p>

        <h3>Founder. Engineer. Builder.</h3>
      </section>
    </div>
  );
};

export default GitHubProfile;

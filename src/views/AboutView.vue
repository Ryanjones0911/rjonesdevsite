<template>
  <main class="about">
    <section class="intro">
      <h1>Who I Am</h1>

      <p>
        I’m a computer science student at the University of Texas at Dallas with
        experience in web development, systems work, cybersecurity-focused platforms,
        and technical projects ranging from machine learning to graphics programming.
      </p>

      <p>
        I’m especially interested in building systems that are technically sound,
        practically useful, and understandable to the people who use them.
      </p>

      <div class="links">
        <a href="mailto:ryanjones0911@gmail.com">Email</a>
        <a href="https://github.com/Ryanjones0911" target="_blank" rel="noopener">
          GitHub
        </a>
        <a href="https://linkedin.com/in/ryan-jones-0911" target="_blank" rel="noopener">
          LinkedIn
        </a>
      </div>
    </section>

    <section>
      <h2>Experience</h2>

      <article class="entry">
        <div class="entry-heading">
          <h3>Web Developer / Systems & Cyber Infrastructure Contributor</h3>
          <p>Virtuo Group · December 2020 – August 2023</p>
        </div>

        <ul>
          <li>
            Contributed to a Cyber Readiness platform used by 400+ users to evaluate
            organizational cybersecurity posture across multiple frameworks.
          </li>
          <li>
            Built and maintained full-stack functionality using Drupal 8, PHP,
            JavaScript, and MySQL.
          </li>
          <li>
            Designed backend systems supporting 450+ structured assessment questions
            and automated reporting workflows.
          </li>
          <li>
            Integrated major cybersecurity frameworks, including NIST CSF, CIS Controls,
            NCSR, Texas CSF, and CIS Benchmark, into a unified platform.
          </li>
          <li>
            Participated in architecture decisions involving hosting, database design,
            and application structure, and supported enterprise iOS deployment through
            MDM/Intune.
          </li>
        </ul>
      </article>

      <article class="entry">
        <div class="entry-heading">
          <h3>IT & Web Systems Contributor</h3>
          <p>Rion Partners · 2017 – 2019</p>
        </div>

        <ul>
          <li>
            Developed and maintained client-facing websites using HTML, CSS,
            JavaScript, and CMS platforms.
          </li>
          <li>
            Implemented backend data handling and database operations to reduce
            repetitive manual content work.
          </li>
          <li>
            Deployed and configured workstation environments, including operating
            systems, software provisioning, and network setup.
          </li>
          <li>
            Diagnosed application, system, and network issues and translated business
            needs into practical technical implementations.
          </li>
        </ul>
      </article>
    </section>

    <section>
      <h2>Selected Projects</h2>

      <article class="entry">
        <h3>Handwritten Digit Recognition Model</h3>
        <p>
          Built and trained a convolutional neural network in PyTorch to classify
          handwritten digits from the MNIST dataset, including preprocessing,
          training, evaluation, and iterative tuning that reached roughly 97–99%
          test accuracy.
        </p>
      </article>

      <article class="entry">
        <h3>N-Body Physics Simulation</h3>
        <p>
          Built a real-time gravitational simulation in WebGL and JavaScript,
          modeling multi-body orbital systems with numerical integration and a
          rendering pipeline designed for client-side performance.
        </p>
      </article>

      <article class="entry">
        <h3>Terminal-Based Rasterizer</h3>
        <p>
          Developed a software renderer that operates entirely inside a Unix terminal,
          implementing rasterization, coordinate transformations, and frame buffering
          without GPU acceleration.
        </p>
      </article>
    </section>

    <section>
      <h2>Education</h2>

      <article class="entry compact">
        <h3>The University of Texas at Dallas</h3>
        <p>B.S. in Computer Science · August 2024 – Present</p>
      </article>

      <article class="entry compact">
        <h3>Lone Star College</h3>
        <p>A.S. in Computer Science · August 2021 – May 2024</p>
      </article>
    </section>

    <section>
      <h2>Technical Focus</h2>

      <div class="skills">
        <div>
          <h3>Languages</h3>
          <p>JavaScript, Python, C++, Java, SQL, Bash, HTML, CSS</p>
        </div>

        <div>
          <h3>Platforms & Tools</h3>
          <p>Drupal, WordPress, WebGL, Git, GitHub, Linux, MySQL</p>
        </div>

        <div>
          <h3>Systems & Infrastructure</h3>
          <p>Active Directory, Microsoft Intune, TCP/IP networking</p>
        </div>

        <div>
          <h3>Areas of Interest</h3>
          <p>
            Cybersecurity fundamentals, application architecture, database design,
            systems integration, graphics programming, and applied machine learning.
          </p>
        </div>
      </div>
    </section>
  </main>
</template>

<style scoped>
.about {
  max-width: 1000px;
  margin: 0 auto;
  padding: 5rem 2rem 6rem;
  color: #1f1f1f;
}

section {
  margin-bottom: 4.5rem;
}

.intro {
  max-width: 800px;
  margin: 0 auto 5rem;
  text-align: center;
}

h1 {
  margin: 0 0 1.25rem;
  font-size: 3.25rem;
  line-height: 1.08;
  letter-spacing: -0.04em;
}

h2 {
  margin: 0 0 1.75rem;
  font-size: 1.8rem;
  letter-spacing: -0.025em;
  padding-bottom: 0.75rem;
  border-bottom: 1px solid #dddddd;
}

h3 {
  margin: 0;
  font-size: 1.15rem;
  letter-spacing: -0.015em;
}

p {
  margin: 0.75rem 0 0;
  font-size: 1.05rem;
  line-height: 1.7;
  color: #3d3d3d;
}

.intro p {
  font-size: 1.15rem;
  max-width: 760px;
}

.links {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 0.9rem;
  margin-top: 2rem;
}

.links a {
  padding: 0.7rem 1.1rem;
  border: 1px solid #d6d6d6;
  border-radius: 999px;
  background-color: #f5f5f5;
  color: #222;
  text-decoration: none;
  font-weight: 500;
  transition:
    transform 0.2s ease,
    border-color 0.2s ease,
    background-color 0.2s ease;
}

.links a:hover {
  transform: translateY(-2px);
  border-color: #bdbdbd;
  background-color: #ededed;
}

.entry {
  padding: 1.5rem 1.6rem;
  margin-bottom: 1.25rem;
  border: 1px solid #e1e1e1;
  border-radius: 1rem;
  background-color: #f8f8f8;
}

.entry-heading {
  margin-bottom: 1rem;
}

.entry-heading p,
.compact p {
  margin-top: 0.35rem;
  font-size: 0.98rem;
  color: #666;
}

ul {
  margin: 1rem 0 0;
  padding-left: 1.25rem;
}

li {
  margin-bottom: 0.7rem;
  line-height: 1.65;
  color: #3d3d3d;
}

li:last-child {
  margin-bottom: 0;
}

.skills {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.25rem;
}

.skills>div {
  padding: 1.4rem 1.5rem;
  border: 1px solid #e1e1e1;
  border-radius: 1rem;
  background-color: #f8f8f8;
}

.skills h3 {
  margin-bottom: 0.6rem;
}

.skills p {
  margin-top: 0;
}

@media (max-width: 700px) {
  .about {
    padding: 3rem 1.25rem 4rem;
  }

  h1 {
    font-size: 2.4rem;
  }

  h2 {
    font-size: 1.5rem;
  }

  .intro p {
    font-size: 1.05rem;
  }

  .skills {
    grid-template-columns: 1fr;
  }

  .entry {
    padding: 1.25rem;
  }
}
</style>

<style>
  html {
    scroll-behavior: smooth;
  }

  body, .markdown-body {
    background-color: #19100b !important;
    color: #f3ece7 !important;
    font-family: Georgia, "Times New Roman", serif;
    line-height: 1.65;
    margin: 0;
  }

  .markdown-body > h1:first-child {
    display: none;
  }

  .page {
    max-width: 1100px;
    margin: 0 auto;
    padding: 40px 24px;
    display: flex;
    gap: 48px;
    align-items: flex-start;
  }

  /* Left Sticky Column */
  .sidebar {
    width: 290px;
    flex-shrink: 0;
    position: sticky;
    top: 32px;
    border-right: 1px solid #6b3b1e;
    padding-right: 32px;
  }

  .sidebar h1 {
    font-size: 2rem;
    line-height: 1.15;
    color: #f4a261 !important;
    border: none !important;
    margin-bottom: 6px;
    font-weight: normal;
  }

  .subtitle {
    font-family: "Courier New", monospace;
    font-size: 0.9rem;
    color: #95d5b2;
    display: block;
    margin-bottom: 22px;
  }

  /* Quick Jump Links */
  .jump-nav {
    display: flex;
    gap: 12px;
    flex-wrap: wrap;
    margin-bottom: 24px;
    padding-bottom: 16px;
    border-bottom: 1px dashed #6b3b1e;
    font-family: "Courier New", monospace;
    font-size: 0.85rem;
  }

  .jump-nav a {
    color: #f4a261;
    text-decoration: none;
    background: #261811;
    padding: 3px 8px;
    border: 1px solid #6b3b1e;
  }

  .jump-nav a:hover {
    color: #19100b;
    background: #95d5b2;
    border-color: #95d5b2;
  }

  .external-links {
    display: flex;
    flex-direction: column;
    gap: 10px;
    margin-bottom: 28px;
    font-family: "Courier New", monospace;
    font-size: 0.88rem;
  }

  .external-links a {
    color: #95d5b2;
    text-decoration: none;
    border-bottom: 1px solid #2d6a4f;
    padding-bottom: 4px;
  }

  .external-links a:hover {
    color: #b7e4c7;
    border-color: #95d5b2;
  }

  .tools {
    font-family: "Courier New", monospace;
    font-size: 0.82rem;
    color: #e6d5c8;
    line-height: 1.7;
  }

  .tools div {
    margin-bottom: 10px;
  }

  /* Right Main Feed */
  .content {
    flex: 1;
    min-width: 0;
  }

  .label {
    font-family: "Courier New", monospace;
    font-size: 0.85rem;
    text-transform: uppercase;
    letter-spacing: 1.5px;
    color: #95d5b2;
    display: block;
    margin-bottom: 12px;
  }

  .about {
    border-left: 3px solid #95d5b2;
    padding-left: 20px;
    margin-bottom: 52px;
    scroll-margin-top: 32px;
  }

  .about p {
    font-size: 1.02rem;
    color: #ebe0d8;
    margin: 0;
  }

  /* Alternating Project Showcase */
  .project {
    display: flex;
    gap: 28px;
    align-items: center;
    margin-bottom: 52px;
    padding-bottom: 40px;
    border-bottom: 1px solid #432514;
  }

  .project.flip {
    flex-direction: row-reverse;
  }

  .thumb {
    width: 310px;
    flex-shrink: 0;
  }

  .thumb img {
    width: 100%;
    height: auto;
    display: block;
    border: 1px solid #b56534;
    padding: 6px;
    background: #24160f;
    transition: border-color 0.2s ease, box-shadow 0.2s ease;
  }

  .project:hover .thumb img {
    border-color: #95d5b2;
    box-shadow: 0 0 14px rgba(149, 213, 178, 0.22);
  }

  .details {
    flex: 1;
  }

  .details h3 {
    margin: 0 0 4px;
    font-size: 1.45rem;
    font-weight: normal;
    color: #ffffff;
  }

  .meta {
    font-family: "Courier New", monospace;
    font-size: 0.8rem;
    color: #e79e65;
    display: block;
    margin-bottom: 12px;
  }

  .details p {
    font-size: 0.96rem;
    color: #e5d8cf;
    margin: 0 0 14px;
  }

  .details code {
    color: #95d5b2 !important;
    background-color: #10241d !important;
    border: 1px solid #2d6a4f;
    padding: 2px 6px;
    border-radius: 4px;
    font-family: "Courier New", monospace;
    font-size: 0.85em;
  }

  .links a {
    font-family: "Courier New", monospace;
    font-size: 0.88rem;
    color: #95d5b2;
    text-decoration: underline;
    margin-right: 16px;
  }

  .links a:hover {
    color: #f4a261;
  }

  @media (max-width: 850px) {
    .page {
      flex-direction: column;
    }
    .sidebar {
      width: 100%;
      position: static;
      border-right: none;
      border-bottom: 1px solid #6b3b1e;
      padding-right: 0;
      padding-bottom: 24px;
    }
    .project, .project.flip {
      flex-direction: column;
      align-items: flex-start;
    }
    .thumb {
      width: 100%;
    }
  }
</style>

<div class="page">

  <!-- Sticky Left Column -->
  <aside class="sidebar">
    <h1>Dakota Johnson</h1>
    <span class="subtitle">Where code meets art.</span>

    <!-- Quick Page Jump Links -->
    <nav class="jump-nav">
      <a href="#about">about</a>
      <a href="#projects">projects</a>
    </nav>

    <!-- External & Contact Links -->
    <nav class="external-links">
      <a href="https://tackytac.itch.io" target="_blank">itch.io</a>
      <a href="https://github.com/DRyanJohnson" target="_blank">github</a>
      <a href="https://www.linkedin.com/in/dryanjohnson/" target="_blank">linkedin</a>
      <a href="./DJohnson.Resume.2026.pdf" target="_blank">resume.pdf</a>
      <a href="mailto:DRyanJohnson@outlook.com">DRyanJohnson@outlook.com</a>
    </nav>

    <div class="tools">
      <div><strong style="color: #f4a261;">LANGUAGES:</strong><br>Java, C#, Bash, HTML/CSS</div>
      <div><strong style="color: #f4a261;">3D &amp; 2D ART:</strong><br>Blender, Krita</div>
      <div><strong style="color: #f4a261;">ENGINES &amp; IDEs:</strong><br>Unity, GitHub, JetBrains (Rider, IntelliJ IDEA, WebStorm), VS Code, Eclipse</div>
    </div>
  </aside>

  <!-- Right Main Feed -->
  <main class="content">

    <!-- About Me Section -->
    <section id="about" class="about">
      <span class="label">About Me</span>
      <p>
        I’m currently a junior studying Computer Science and Systems at the University of Washington Tacoma (with a minor in Technical Communication) after completing my foundational programming coursework at Tacoma Community College. My studies focus on object-oriented programming, software logic, and computer systems. In my free time, I build indie games in Unity using C# for scripting alongside my own 2D and 3D art created in Krita and Blender. I also use Bash for basic scripting, file management, and checking networks. Right now, I’m looking to connect with other developers and find software engineering internship opportunities where I can keep building my technical skills.
      </p>
    </section>

    <span id="projects" class="label" style="margin-bottom: 24px; scroll-margin-top: 32px;">Projects</span>

    <!-- Project 1 (Art Left, Text Right) -->
    <article class="project">
      <div class="thumb">
        <img src="assets/NeverMadeIt.png" alt="Never Made It Screenshot">
      </div>
      <div class="details">
        <h3>Never Made It</h3>
        <span class="meta">C# / Unity 6 &bull; Krita 2D Art &bull; UWT Fall 2026 Game Jam</span>
        <p>
          A 17-scene visual novel built solo in Unity 6 using C# launguage for a campus game jam. I structured branching dialogue with serializable <code>StoryBeat</code> and <code>ChoiceOption</code> classes using <code>enum</code> condition checks and state effects, tracked player strikes and inventory across scenes in a static <code>GameState</code> class, and used coroutines for typewriter text alongside custom 1920&times;1080 Krita art.
        </p>
        <div class="links">
          <a href="https://tackytac.itch.io/never-made-it" target="_blank">Play on itch.io</a>
          <a href="https://github.com/DRyanJohnson/Never-Made-It-Game-C-unity-" target="_blank">View Code on GitHub</a>
        </div>
      </div>
    </article>

    <!-- Project 2 (Text Left, Art Right) -->
    <article class="project flip">
      <div class="thumb">
        <img src="assets/FarmSimulatorJava.png" alt="Farm Simulator Screenshot">
      </div>
      <div class="details">
        <h3>Farm Simulator</h3>
        <span class="meta">Java &bull; OOP &amp; Collections</span>
        <p>
          A command-line farming game built in Java with a four-person team. We used custom classes (<code>Acre</code>, <code>Fish</code>) and Java collections (<code>HashMap</code>, <code>TreeMap</code>, <code>ArrayList</code>) to track 14 seasonal crops, inventory, and daily actions, while handling input validation so bad console entries wouldn't crash the loop.
        </p>
        <div class="links">
          <a href="https://github.com/DRyanJohnson/Farm-Simulator-Java" target="_blank">View Source Code on GitHub</a>
        </div>
      </div>
    </article>

    <!-- Project 3 (Art Left, Text Right) -->
    <article class="project">
      <div class="thumb">
        <img src="assets/hoverboardandrobotsgame.png" alt="Hoverboard and Robots Screenshot">
      </div>
      <div class="details">
        <h3>Hoverboard &amp; Robots</h3>
        <span class="meta">C# / Unity &bull; Blender 3D Models</span>
        <p>
          A 3D action game created in Unity within a three-week deadline. I wrote a <code>HoverboardMountManager</code> that swaps between <code>CharacterController</code> movement and <code>Rigidbody</code> hoverboard physics, uses terrain height sampling to place the player safely on dismount, and pairs <code>NavMeshAgent</code> ground enemies with raycast sight-cone detection (<code>HoverbotSight</code>) alongside custom Blender 3D props.
        </p>
        <div class="links">
          <a href="https://tackytac.itch.io/hoverboard-robots" target="_blank">Play on itch.io</a>
          <a href="https://github.com/DRyanJohnson/Game-code/tree/main/Hoverboard%26Robots" target="_blank">View Code on GitHub</a>
        </div>
      </div>
    </article>

    <!-- Project 4 (Text Left, Art Right) -->
    <article class="project flip">
      <div class="thumb">
        <img src="assets/FoxDescend2dgame.png" alt="Fox Descend Screenshot">
      </div>
      <div class="details">
        <h3>Fox Descend</h3>
        <span class="meta">C# / Unity &bull; Custom 2D Sprites</span>
        <p>
          A 2D platformer shooter built in Unity and C# within a two-week deadline. I wrote a checkpoint-clamped <code>FlyingMonsterAI</code> state machine for patrolling and projectile attacks, implemented one-way pass-through platforms via <code>Physics2D.IgnoreLayerCollision</code>, and built key-gated doors with <code>UnityEvent</code> triggers, timed <code>DamageZone</code> hazards, and custom 2D sprites.
        </p>
        <div class="links">
          <a href="https://tackytac.itch.io/fox-descend" target="_blank">Play on itch.io</a>
          <a href="https://github.com/DRyanJohnson/Game-code/tree/main/FoxDescend" target="_blank">View Code on GitHub</a>
        </div>
      </div>
    </article>

  </main>

</div>

<style>
  html {
    scroll-behavior: smooth;
  }

  body, .markdown-body {
    background-color: #0b1914 !important;
    color: #e6f0ec !important;
    font-family: Georgia, "Times New Roman", serif;
    line-height: 1.65;
    margin: 0;
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
    border-right: 1px solid #2d6a4f;
    padding-right: 32px;
  }

  .sidebar h1 {
    font-size: 2rem;
    line-height: 1.15;
    color: #95d5b2 !important;
    border: none !important;
    margin-bottom: 6px;
    font-weight: normal;
  }

  .subtitle {
    font-family: "Courier New", monospace;
    font-size: 0.9rem;
    color: #c77dff;
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
    border-bottom: 1px dashed #2d6a4f;
    font-family: "Courier New", monospace;
    font-size: 0.85rem;
  }

  .jump-nav a {
    color: #95d5b2;
    text-decoration: none;
    background: #122921;
    padding: 3px 8px;
    border: 1px solid #2d6a4f;
  }

  .jump-nav a:hover {
    color: #0b1914;
    background: #c77dff;
    border-color: #c77dff;
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
    color: #e6f0ec;
    text-decoration: none;
    border-bottom: 1px solid #2d6a4f;
    padding-bottom: 4px;
  }

  .external-links a:hover {
    color: #c77dff;
    border-color: #c77dff;
  }

  .tools {
    font-family: "Courier New", monospace;
    font-size: 0.82rem;
    color: #b7e4c7;
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
    color: #c77dff;
    display: block;
    margin-bottom: 12px;
  }

  .about {
    border-left: 3px solid #c77dff;
    padding-left: 20px;
    margin-bottom: 52px;
    scroll-margin-top: 32px;
  }

  .about p {
    font-size: 1.02rem;
    color: #d8e6df;
    margin: 0;
  }

  /* Alternating Project Showcase */
  .project {
    display: flex;
    gap: 28px;
    align-items: center;
    margin-bottom: 52px;
    padding-bottom: 40px;
    border-bottom: 1px solid #1b4332;
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
    border: 1px solid #52b788;
    padding: 6px;
    background: #10241d;
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
    color: #74c69d;
    display: block;
    margin-bottom: 12px;
  }

  .details p {
    font-size: 0.96rem;
    color: #d2e0da;
    margin: 0 0 14px;
  }

  .links a {
    font-family: "Courier New", monospace;
    font-size: 0.88rem;
    color: #c77dff;
    text-decoration: underline;
    margin-right: 16px;
  }

  .links a:hover {
    color: #95d5b2;
  }

  .skills-footer {
    padding-top: 10px;
    scroll-margin-top: 32px;
  }

  .skills-footer p {
    font-family: "Courier New", monospace;
    font-size: 0.9rem;
    color: #d2e0da;
    margin: 0 0 8px;
  }

  @media (max-width: 850px) {
    .page {
      flex-direction: column;
    }
    .sidebar {
      width: 100%;
      position: static;
      border-right: none;
      border-bottom: 1px solid #2d6a4f;
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
      <a href="#about">#about</a>
      <a href="#projects">#projects</a>
      <a href="#skills">#skills</a>
    </nav>

    <!-- External & Contact Links -->
    <nav class="external-links">
      <a href="https://tackytac.itch.io" target="_blank">itch.io &rarr; tackytac</a>
      <a href="https://github.com/DRyanJohnson" target="_blank">github &rarr; DRyanJohnson</a>
      <a href="https://www.linkedin.com/in/dryanjohnson/" target="_blank">linkedin &rarr; /in/dryanjohnson</a>
      <a href="./DJohnson.Resume.2026.pdf" target="_blank">resume.pdf</a>
      <a href="mailto:DRyanJohnson@outlook.com">DRyanJohnson@outlook.com</a>
    </nav>

    <div class="tools">
      <div><strong style="color: #95d5b2;">LANGUAGES:</strong><br>Java, C#, Bash, HTML/CSS</div>
      <div><strong style="color: #95d5b2;">3D &amp; 2D ART:</strong><br>Blender, Krita</div>
      <div><strong style="color: #95d5b2;">ENGINES &amp; IDEs:</strong><br>Unity, GitHub, JetBrains (Rider, IntelliJ IDEA, WebStorm), VS Code, Eclipse</div>
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

    <!-- Project 1 -->
    <article class="project">
      <div class="thumb">
        <img src="assets/NeverMadeIt.png" alt="Never Made It Screenshot">
      </div>
      <div class="details">
        <h3>Never Made It</h3>
        <span class="meta">C# / Unity 6 &bull; Krita 2D Art &bull; UWT Fall 2026 Game Jam</span>
        <p>
          A solo built visual novel developed in Unity 6 and C# for the UWT Fall 2026 Game Jam. I built a 17-scene narrative system via a custom StorySceneController, complete with a main menu, scrolling environmental sign text, a snowfall, smoke particle effect and synchronized background music and audio cues. I also created and formatted all 1920×1080 2D art assets in Krita and shipped a playable WebGL build to itch.io within the jam timeframe.
        </p>
        <div class="links">
          <a href="https://tackytac.itch.io/never-made-it" target="_blank">Play on itch.io</a>
          <a href="https://github.com/DRyanJohnson/Never-Made-It-Game-C-unity-" target="_blank">View Code on GitHub</a>
        </div>
      </div>
    </article>

    <!-- Project 2 -->
    <article class="project flip">
      <div class="thumb">
        <img src="assets/FoxDescend2dgame.png" alt="Fox Descend Screenshot">
      </div>
      <div class="details">
        <h3>Fox Descend</h3>
        <span class="meta">C# / Unity &bull; Custom 2D Sprites</span>
        <p>
          A 2D action shooter built in Unity and C# within a strict two-week course deadline. I scripted 2D combat and projectile mechanics for both the player and enemy types, handling trajectories, speed, and hit detection, alongside a level-progression system that unlocks the exit trigger only after all enemies are defeated. I also built a real-time HUD kill counter with Unity UI and created and animated custom 2D sprites for the player, enemies, and environments, which taught me how to scope and ship a complete WebGL build under a tight schedule.
        </p>
        <div class="links">
          <a href="https://tackytac.itch.io/fox-descend" target="_blank">Play on itch.io</a>
          <a href="https://github.com/DRyanJohnson/Game-code/tree/main/FoxDescend" target="_blank">View Code on GitHub</a>
        </div>
      </div>
    </article>

    <!-- Project 3 -->
    <article class="project">
      <div class="thumb">
        <img src="assets/hoverboardandrobotsgame.png" alt="Hoverboard and Robots Screenshot">
      </div>
      <div class="details">
        <h3>Hoverboard &amp; Robots</h3>
        <span class="meta">C# / Unity &bull; Blender 3D Models</span>
        <p>
          A 3D "HoverBoard"-action game built in Unity and C# within a three-week course deadline. I created a custom hoverboard controller and manager system supporting WASD movement, mouse-based rotation, mounting and dismounting toggles, and synchronized respawn logic tied to player health. To support seamless state transitions between on-foot and mounted modes, I refactored core player locomotion, camera tracking, and health scripts, and programmed state-based enemy AI that shifts targeting priority from the player to the hoverboard when mounted. Building out the 3D environment props and dynamic controls UI reinforced clean state management across multiple interacting scripts.
        </p>
        <div class="links">
          <a href="https://tackytac.itch.io/hoverboard-robots" target="_blank">Play on itch.io</a>
          <a href="https://github.com/DRyanJohnson/Game-code/tree/main/Hoverboard%26Robots" target="_blank">View Code on GitHub</a>
        </div>
      </div>
    </article>

    <!-- Project 4 -->
    <article class="project flip">
      <div class="thumb">
        <img src="assets/FarmSimulatorJava.png" alt="Farm Simulator Screenshot">
      </div>
      <div class="details">
        <h3>Farm Simulator</h3>
        <span class="meta">Java &bull; OOP &amp; Collections</span>
        <p>
          A team-built, command-line farming simulation game built in Java using object-oriented classes (<code>Acre</code>, <code>Fish</code>) and collections (<code>HashMap</code>, <code>TreeMap</code>, <code>ArrayList</code>). Players buy land plots, plant and harvest 14 seasonal crops across four seasons, fish for extra gold, build fences against overnight wildlife attacks, apply fertilizer, and manage daily action points and yearly taxes. Coordinating multiple daily game systems and collaborating in a four-person team taught me how to structure game state cleanly and handle invalid user input without crashing the loop.
        </p>
        <div class="links">
          <a href="https://github.com/DRyanJohnson/Farm-Simulator-Java" target="_blank">View Source Code on GitHub</a>
        </div>
      </div>
    </article>

    <!-- Skills Section -->
    <section id="skills" class="skills-footer">
      <span class="label">Skills &amp; Toolkit</span>
      <p><strong style="color: #95d5b2;">Languages:</strong> Java, C#, Bash, HTML/CSS</p>
      <p><strong style="color: #95d5b2;">Engines &amp; Dev Tools:</strong> Unity, GitHub, VS Code, Eclipse IDE, JetBrains (IntelliJ IDEA, Rider, WebStorm)</p>
      <p><strong style="color: #95d5b2;">Art &amp; 3D Modeling:</strong> Krita, Blender</p>
    </section>

  </main>

</div>
## Resume & Contact

| Resume | Contact |
| :--- | :--- |
| 📄 **[View / Download Resume (PDF)](./DJohnson.Resume.2026.pdf)** | **Email:** [DRyanJohnson@outlook.com](mailto:DRyanJohnson@outlook.com)

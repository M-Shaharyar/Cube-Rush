# Cube-Rush
![Demo](https://github.com/M-Shaharyar/Cube-Rush/blob/main/Game%20Video/CubeRush.gif)

<h1>Cube Rush</h1>

<h2>Overview</h2>
<p>Cube Rush is an exciting Unity-based game where players must dodge incoming enemies while collecting green cubes to increase their score. The challenge intensifies as the game progresses, with a limited time available to survive. The game ends when the player collides with an enemy or when the timer runs out.</p>

<h2>How to Play</h2>
<ul>
  <li>Use <strong>Left Arrow</strong> and <strong>Right Arrow</strong> keys to move the player left or right.</li>
  <li>Avoid red enemy cubes approaching from the front.</li>
  <li>Collect green cubes to increase your score.</li>
  <li>Survive until the timer reaches zero or avoid collisions to stay in the game.</li>
  <li>If an enemy collides with the player, the game ends.</li>
</ul>

<h2>Features</h2>
<ul>
  <li><strong>Enemy Movement & Rotation:</strong> Enemies move towards the player and rotate to create dynamic motion.</li>
  <li><strong>Score Collection:</strong> Players earn points by collecting green cubes.</li>
  <li><strong>Game Timer:</strong> The game ends when the countdown reaches zero.</li>
  <li><strong>Randomized Enemy Spawning:</strong> Enemies spawn at random positions to enhance unpredictability.</li>
</ul>

<h2>Scripts Used</h2>
<ul>
  <li><strong>Enemy.cs</strong>
    <ul>
      <li>Controls enemy movement and rotation.</li>
      <li>Enemies move towards the player and respawn at new random positions when they pass through the portal.</li>
      <li>If an enemy collides with the player, the game ends.</li>
    </ul>
  </li>
  <li><strong>Player.cs</strong>
    <ul>
      <li>Handles player movement using arrow keys.</li>
      <li>Allows the player to move left and right along the z-axis.</li>
    </ul>
  </li>
  <li><strong>Portal.cs</strong>
    <ul>
      <li>Manages the game timer and updates the UI accordingly.</li>
      <li>Ends the game when the timer reaches zero.</li>
      <li>Keeps track of the player's score.</li>
    </ul>
  </li>
  <li><strong>Bonus.cs</strong>
    <ul>
      <li>Controls the behavior of green cubes.</li>
      <li>When collected by the player, increases the score.</li>
      <li>Respawns at a new position after being collected.</li>
    </ul>
  </li>
</ul>

<h2>Technologies & Tools Used</h2>
<ul>
  <li><strong>Game Engine:</strong> Unity</li>
  <li><strong>Programming Language:</strong> C#</li>
  <li><strong>Physics Engine:</strong> Unity’s Rigidbody system</li>
  <li><strong>UI Framework:</strong> TextMeshPro for displaying score and timer</li>
</ul>

<h2>How to Run the Game</h2>
<pre><code>git clone https://github.com/M-Shaharyar/Cube-Rush.git</code></pre>
<p>Open the project in Unity.</p>
<p>Press the Play button in the Unity Editor.</p>
<p>Use the movement keys to dodge enemies and collect green cubes.</p>

<h2>Future Enhancements</h2>
<ul>
  <li>Implement difficulty levels with increasing enemy speed.</li>
  <li>Add a leaderboard system to track high scores.</li>
  <li>Introduce power-ups for temporary invincibility or speed boosts.</li>
  <li>Enhance visuals with particle effects and animations.</li>
</ul>

<h2>Contribution</h2>
<p>Contributions are always welcome! Feel free to fork the repository, make improvements, and submit a pull request.</p>

<h2>License</h2>
<p>This project is open-source and available under the <strong>MIT License</strong>.</p>

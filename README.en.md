# Large Model HTML Generation Capability Test

This repository is used for a lightweight test of "a model's HTML generation capability." Since model–prompt combinations are randomly drawn from several models and tasks for evaluation, the results only reflect the temporary performance of this sample run and do not represent each model’s true or stable capability. Please treat the results as a demonstration and for comparative reference only.

## Evaluation Guidelines

- Return a single-file HTML.
- If there are external dependencies, use CDNs to avoid local installation steps.
- The demo is for showcase purposes only, not a benchmark evaluation.
- Please start the project with http-server, Live Server (VSCode extension), or another HTTP server to avoid certain compatibility issues.

## Prompts

### Snowflakes

```
Output a single-file HTML. You may include third-party libraries such as TailwindCSS and necessary JS libraries.
Create a snowflake effect. Randomly generate some page elements. Snowflakes fall from the sky. Allow specifying wind speed and direction, snowflake density, and falling speed. Snowflakes should accumulate on page elements and at the bottom of the page.
```

### Typewriter Effect

```
Use a single-file HTML. If third-party libraries are needed, include them via CDN URLs. Build a component that demonstrates typing. The component should look like a beautiful textarea where user input is simulated. You can randomly generate several paragraphs of text. While simulating typing, add some random delays between inputs. When the mouse hovers over it, it should lift slightly and have a suitable shadow. Note that it should be copyable but not editable by the user.
```

### Maze Generation

```
Single HTML file.
You may include various libraries (via CDN).
Implement a maze generator with a reset button to randomly generate a new maze.
Provide buttons for several different pathfinding algorithms. Clicking a button should show different circles executing the corresponding pathfinding process.
```

### Raindrops on Glass

```
Create a single-file HTML. If needed, you may include different libraries (via CDN).
Implement the effect of raindrops falling on glass.
The entire screen is glass. Raindrops randomly hit the glass and then slide down. When raindrops meet, they merge and increase their sliding speed. The behavior should match realistic physics.
Allow adjusting factors such as wind speed, wind direction, and friction.
```

### Wave Effect

```
Use a single-file HTML. You may include some third-party libraries via CDN URLs.
Implement a background wave effect with configurable wave intensity, number of waves, and iterations.
The waves should have floating variations, not just horizontal movement.
Use soft gradients with a bit of frosted-glass texture to convey a refined, premium feel overall.
```

### Whack-a-Cockroach

```
Use a single-file HTML.
You may include required JS/CSS libraries via CDN URLs.
Randomly generate cockroaches on the screen. Cockroaches will randomly move/pause/turn.
The first mouse click on a cockroach speeds up its movement; the second makes it explode and disappear.
Consider adding animations (e.g., idle animation when paused) and special effects (e.g., dust, explosions, etc.).
```

### Intro Page

```
Create a single-file HTML page introducing OpenAI. You may include third-party CSS/JS libraries via CDN to achieve effects.
You may choose the content freely, but it should be sufficiently rich.
Aim for a modern style using some effects to create a premium feel without appearing cheap.
For example: glassmorphism, parallax effects, and scroll-driven animations.
```

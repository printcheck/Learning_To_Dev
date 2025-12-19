# C++ & Game Development Learning Resources

> A curated collection of resources for learning C++, game physics, math, and SFML development. 
> Last Updated: 2025-12-18

---

## 📑 Table of Contents
- [SFML Resources](#sfml-resources)
- [Game Physics](#game-physics)
- [C++ Programming](#c-programming)
- [Game Math](#game-math)
- [Tools & Libraries](#tools--libraries)
- [Cheat Sheets](#cheat-sheets)
- [Practice Projects](#practice-projects)
- [Communities](#communities)

---

## 🎨 SFML Resources

### Official Documentation
- [SFML Official Tutorials](https://www.sfml-dev.org/tutorials/) - Start here for SFML basics
- [SFML API Documentation](https://www.sfml-dev.org/documentation/) - Complete API reference
- [SFML GitHub Repository](https://github.com/SFML/SFML) - Source code and examples

### Video Tutorials
- [Suraj Sharma's SFML Series](https://www.youtube.com/playlist?list=PL21OsoBLPpMOO6zyVlxZ4S4hwkY_SLRW9) - Beginner-friendly
- [Hilze Vonck's SFML Tutorials](https://www.youtube.com/c/HilzeVonck) - Project-based learning
- [Let's Make Games - SFML RPG Tutorial](https://www.youtube.com/playlist?list=PL6xSOsbVA1eb_QqMTTfImAlh9yJXWGSSg)

### Books
- "SFML Game Development" by Jan Haller et al.  - Official SFML book

---

## ⚛️ Game Physics

### Books
- **"Game Physics Engine Development" by Ian Millington** ⭐ THE definitive resource
  - Rigid body dynamics
  - Collision detection & response
  - Constraint systems
  
- **"Physics for Game Developers" by David M. Bourg & Bryan Bywalec**
  - Practical approach
  - Real-world physics applications
  - Mathematics explained clearly

- **"Real-Time Collision Detection" by Christer Ericson**
  - Advanced collision algorithms
  - Optimization techniques

### Online Tutorials
- [Gaffer On Games - Physics Series](https://gafferongames.com/post/integration_basics/) - Integration methods
- [Chris Hecker's Rigid Body Dynamics](https://www.chrishecker.com/Rigid_Body_Dynamics) - Classic articles
- [Two-Bit Coding](https://www.youtube.com/c/TwoBitCoding) - Visual physics simulations
- [Coding Math](https://www.youtube.com/user/codingmath) - Math & physics for programmers
- [Red Blob Games](https://www.redblobgames.com/) - Interactive tutorials

### Video Courses
- [The Coding Train - Nature of Code](https://thecodingtrain.com/tracks/the-nature-of-code-2) - Physics simulations (JS but concepts transfer)
- [Pikuma - 2D Game Physics Programming](https://pikuma.com/courses/game-physics-engine-programming) - Build a physics engine

### Physics Engines to Study
- [Box2D](https://box2d.org/) - 2D physics engine (read the source!)
- [Chipmunk2D](https://chipmunk-physics.net/) - Another great 2D engine
- [Bullet Physics](https://pybullet.org/wordpress/) - 3D physics

---

## 💻 C++ Programming

### Learning C++
- [learncpp.com](https://www.learncpp.com/) - Comprehensive C++ tutorial
- [C++ Reference](https://en.cppreference.com/) - Complete language reference
- [cplusplus.com](http://www.cplusplus.com/) - Tutorials and reference
- [Compiler Explorer (Godbolt)](https://godbolt.org/) - See compiled assembly

### Books
- **"C++ Primer" by Stanley Lippman** - Comprehensive introduction
- **"Effective C++" by Scott Meyers** - Best practices
- **"The C++ Programming Language" by Bjarne Stroustrup** - By the creator himself
- **"Game Programming Patterns" by Robert Nystrom** - [Free online](https://gameprogrammingpatterns.com/)

### Video Channels
- [The Cherno - C++ Series](https://www.youtube.com/playlist?list=PLlrATfBNZ98dudnM48yfGUldqGD0S4FFb) - Deep C++ concepts
- [OneLoneCoder (javidx9)](https://www.youtube.com/c/javidx9) - Game dev in C++
- [CppCon YouTube](https://www.youtube.com/user/CppCon) - Conference talks

### Modern C++ Resources
- [C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines) - Official best practices
- [Awesome Modern C++](https://github.com/rigtorp/awesome-modern-cpp) - Curated list

---

## 🧮 Game Math

**👉 [Check out the dedicated Math Resources File](./cpp-math-resources.md) for detailed math tutorials and cheat sheets!**

### Essential Math Topics
- Vectors & Vector Math
- Matrices & Transformations
- Trigonometry (sin, cos, atan2)
- Linear Interpolation (lerp)
- Dot & Cross Products
- **Quaternions (for 3D rotation)** - [See dedicated section](./cpp-math-resources.md#quaternions-for-3d-rotation) 🔄

### Learning Resources
- [3Blue1Brown - Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) ⭐ Visual explanations
- [Khan Academy - Linear Algebra](https://www.khanacademy.org/math/linear-algebra)
- [Khan Academy - Trigonometry](https://www.khanacademy.org/math/trigonometry)
- [Immersive Linear Algebra](http://immersivemath.com/ila/index.html) - Interactive book

### Books
- **"Mathematics for 3D Game Programming" by Eric Lengyel**
- **"3D Math Primer for Graphics and Game Development" by Fletcher Dunn**
- **"Essential Mathematics for Games and Interactive Applications" by James M. Van Verth**

### Interactive Tools
- [Math is Fun](https://www.mathsisfun.com/) - Visual math concepts
- [GeoGebra](https://www.geogebra.org/) - Interactive geometry
- [Desmos Graphing Calculator](https://www.desmos.com/calculator) - Visualize equations

---

## 🛠️ Tools & Libraries

### Development Tools
- **Visual Studio** / **Visual Studio Code** - IDEs
- **CMake** - Build system
- **Git** - Version control
- **Valgrind** - Memory leak detection (Linux)
- **GDB / LLDB** - Debuggers

### Useful Libraries
- **SFML** - Simple and Fast Multimedia Library
- **SDL2** - Simple DirectMedia Layer
- **Box2D** - 2D physics engine
- **GLM** - OpenGL Mathematics (header-only math library)
- **Dear ImGui** - Immediate mode GUI for debugging
- **nlohmann/json** - JSON for Modern C++
- **spdlog** - Fast C++ logging library

### Graphics & Rendering
- [Learn OpenGL](https://learnopengl.com/) - Modern OpenGL tutorial
- [OpenGL Tutorial](http://www.opengl-tutorial.org/)
- [Scratchapixel](https://www.scratchapixel.com/) - Computer graphics from scratch

---

## 📋 Cheat Sheets

### SFML Quick Reference

```cpp
// Window Creation
sf::RenderWindow window(sf::VideoMode(800, 600), "Title");
window.setFramerateLimit(60);

// Game Loop
while (window.isOpen()) {
    // Event handling
    sf::Event event;
    while (window.pollEvent(event)) {
        if (event.type == sf::Event::Closed)
            window.close();
    }
    
    // Update
    // ... game logic ...
    
    // Render
    window.clear(sf::Color::Black);
    window.draw(shape);
    window.display();
}

// Common Shapes
sf::CircleShape circle(50.f);
circle.setFillColor(sf::Color::Red);
circle.setPosition(100.f, 100.f);
circle.setOrigin(50.f, 50.f); // Center origin

sf::RectangleShape rect(sf::Vector2f(100.f, 50.f));
```

### Vector Math Cheat Sheet

```cpp
// Vector Operations
sf::Vector2f a(3.f, 4.f);
sf::Vector2f b(1.f, 2.f);

// Addition/Subtraction
sf::Vector2f sum = a + b;
sf::Vector2f diff = a - b;

// Scalar multiplication
sf::Vector2f scaled = a * 2.f;

// Magnitude (length)
float length = std::sqrt(a.x * a.x + a.y * a.y);

// Normalize (unit vector)
sf::Vector2f normalized = a / length;

// Dot product
float dot = a.x * b.x + a.y * b.y;

// Distance between points
float dist = std::sqrt(std::pow(b.x - a.x, 2) + std::pow(b.y - a.y, 2));

// Linear interpolation
sf::Vector2f lerp(const sf::Vector2f& start, const sf::Vector2f& end, float t) {
    return start + (end - start) * t;
}
```

### Physics Integration Cheat Sheet

```cpp
// Euler Integration (simple, less accurate)
void update(float dt) {
    velocity += acceleration * dt;
    position += velocity * dt;
}

// Semi-implicit Euler (better for games)
void update(float dt) {
    velocity += acceleration * dt;
    position += velocity * dt;
}

// Verlet Integration (more stable)
void update(float dt) {
    sf::Vector2f newPosition = position + (position - oldPosition) + acceleration * dt * dt;
    oldPosition = position;
    position = newPosition;
}

// Apply forces
void applyForce(const sf::Vector2f& force) {
    acceleration += force / mass; // F = ma, so a = F/m
}

// Common forces
sf::Vector2f gravity(0.f, 9.8f * pixelsPerMeter);
sf::Vector2f drag = -velocity * dragCoefficient;
sf::Vector2f friction = -velocity.normalized() * frictionCoefficient;
```

### Collision Detection Cheat Sheet

```cpp
// Circle-Circle Collision
bool circleCollision(sf::Vector2f pos1, float r1, sf::Vector2f pos2, float r2) {
    float dx = pos2.x - pos1.x;
    float dy = pos2.y - pos1.y;
    float distance = std::sqrt(dx * dx + dy * dy);
    return distance < (r1 + r2);
}

// AABB (Axis-Aligned Bounding Box) Collision
bool aabbCollision(sf::FloatRect rect1, sf::FloatRect rect2) {
    return rect1.intersects(rect2);
}

// Point-Circle Collision
bool pointInCircle(sf::Vector2f point, sf::Vector2f center, float radius) {
    float dx = point.x - center.x;
    float dy = point.y - center.y;
    return (dx * dx + dy * dy) < (radius * radius);
}
```

### Common Game Patterns

```cpp
// Delta Time
sf::Clock clock;
while (window.isOpen()) {
    float dt = clock.restart().asSeconds();
    
    // Use dt for frame-independent movement
    position += velocity * dt;
}

// State Machine (simple)
enum class GameState { Menu, Playing, Paused, GameOver };
GameState currentState = GameState::Menu;

switch (currentState) {
    case GameState::Menu:
        // Handle menu
        break;
    case GameState::Playing:
        // Handle gameplay
        break;
    // ...
}

// Object Pool Pattern
std::vector<Bullet> bulletPool(100);
int nextBullet = 0;

void spawnBullet(sf::Vector2f pos, sf::Vector2f vel) {
    bulletPool[nextBullet].reset(pos, vel);
    nextBullet = (nextBullet + 1) % bulletPool.size();
}
```

### C++ Modern Features Quick Reference

```cpp
// Auto type deduction
auto x = 5;                    // int
auto y = 3.14f;                // float
auto vec = sf::Vector2f(1, 2); // sf::Vector2f

// Range-based for loops
std::vector<int> numbers = {1, 2, 3, 4, 5};
for (const auto& num : numbers) {
    std::cout << num << "\n";
}

// Smart pointers (prefer over raw pointers)
#include <memory>
std::unique_ptr<Player> player = std::make_unique<Player>();
std::shared_ptr<Texture> texture = std::make_shared<Texture>();

// Lambda functions
auto square = [](int x) { return x * x; };
int result = square(5); // 25

// Move semantics
std::vector<int> source = {1, 2, 3};
std::vector<int> dest = std::move(source); // Transfer ownership

// Structured bindings (C++17)
std::pair<int, float> data = {42, 3.14f};
auto [integer, floating] = data;
```

---

## 🎯 Practice Projects

### Beginner Level
- [ ] **Bouncing Ball** - Gravity + wall collision
- [ ] **Pong Clone** - Basic collision & game logic
- [ ] **Particle System** - Multiple objects, forces
- [ ] **Snake Game** - Grid-based movement

### Intermediate Level
- [ ] **Breakout/Arkanoid** - Collision detection & response
- [ ] **Platformer** - Player physics, jumping, platforms
- [ ] **Asteroids Clone** - Rotation, shooting, wrapping
- [ ] **Angry Birds Clone** - Projectile physics, trajectory

### Advanced Level
- [ ] **Physics Engine** - Build your own collision system
- [ ] **Cloth/Soft Body Simulation** - Springs, constraints
- [ ] **Fluid Simulation** - Particle-based or grid-based
- [ ] **Ragdoll Physics** - Articulated bodies

### Challenge Projects
- [ ] **Pool/Billiards** - Accurate collision response
- [ ] **2D Car Physics** - Suspension, friction, steering
- [ ] **Bridge Builder** - Structural physics
- [ ] **Newton's Cradle** - Conservation of momentum

---

## 👥 Communities

### Forums & Discussion
- [r/gamedev](https://www.reddit.com/r/gamedev/) - Game development subreddit
- [r/cpp](https://www.reddit.com/r/cpp/) - C++ subreddit
- [GameDev.net](https://www.gamedev.net/) - Articles and forums
- [Stack Overflow](https://stackoverflow.com/questions/tagged/sfml) - SFML tag

### Discord Servers
- [SFML Discord](https://discord.gg/nr4X7Fh)
- [Game Dev League](https://discord.gg/gamedev)
- [Together C & C++](https://discord.gg/vnyVmAE)

### Other Communities
- [TIGSource](https://forums.tigsource.com/) - Indie game dev forums
- [Handmade Network](https://handmade.network/) - From-scratch programming
- [itch.io Game Jams](https://itch.io/jams) - Practice with game jams! 

---

## 📝 Learning Path Recommendation

### Month 1-2: Foundations
- [ ] Complete SFML basics (window, sprites, input)
- [ ] Learn C++ fundamentals (classes, pointers, STL)
- [ ] Build Pong and Snake

### Month 3-4: Physics Basics
- [ ] Implement basic physics (gravity, velocity, acceleration)
- [ ] Learn vector math
- [ ] Build bouncing ball and particle system

### Month 5-6:  Collisions
- [ ] Implement collision detection
- [ ] Learn collision response
- [ ] Build Breakout and Asteroids

### Month 7-8: Advanced Physics
- [ ] Study physics integration methods
- [ ] Implement friction, drag, restitution
- [ ] Build platformer with good physics feel

### Month 9-12: Specialization
- [ ] Deep dive into one area (physics engine, rendering, AI)
- [ ] Build a complete game
- [ ] Contribute to open source projects

---

## 🔖 Bookmarks to Add

**Add your favorite resources below:**

### My Custom Resources
- 

### Useful GitHub Repos
- 

### Favorite YouTube Channels
- 

### Articles & Blog Posts
- 

### Tools I Use
- 

---

## 📌 Quick Tips & Tricks

### Performance Tips
- Use `const&` for large objects in function parameters
- Reserve vector capacity if you know the size:  `vector.reserve(1000);`
- Avoid `new`/`delete`, prefer smart pointers or stack allocation
- Profile before optimizing:  "Premature optimization is the root of all evil"

### Debugging Tips
- Print debug info with `std::cout` or use a logging library
- Use debugger breakpoints instead of just printing
- Draw debug visuals (collision bounds, velocity vectors)
- Check for division by zero in physics calculations
- Watch out for float comparison:  use epsilon `abs(a - b) < 0.0001f`

### Good Practices
- Use version control (Git) from day one
- Write small, testable functions
- Comment *why*, not *what*
- Name variables descriptively:  `playerVelocity` not `pv`
- Keep frame-independent movement:  always multiply by `deltaTime`

---

## 📅 Revision History

- **2025-12-18**: Initial creation with comprehensive resources
- 

---

**Happy Learning!  🚀**
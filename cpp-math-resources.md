# Math References for C++ Game Development

> A dedicated file for essential math learning resources and cheat sheets. Useful for game developers working with physics, vectors, matrices, and other numerical concepts.
> Last Updated: 2025-12-18

---

## 📑 Table of Contents
- [Math Learning Resources](#math-learning-resources)
- [Books for Game Math](#books-for-game-math)
- [Cheat Sheets for Math Functions](#cheat-sheets-for-math-functions)
- [Math Practice & Examples](#math-practice--examples)
- [Interactive Tools](#interactive-tools)

---

## 🔓 Math Learning Resources

### Online Tutorials
- [Khan Academy - Trigonometry](https://www.khanacademy.org/math/trigonometry) - Learn sine, cosine, and tangent
- [Khan Academy - Linear Algebra](https://www.khanacademy.org/math/linear-algebra) - Vectors, matrices, and transformations
- [3Blue1Brown - Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) - Visual explanations of vectors and matrices
- [Immersive Linear Algebra](http://immersivemath.com/ila/index.html) - Interactive linear algebra book

### Math-focused Channels
- **[Coding Math - YouTube](https://www.youtube.com/user/codingmath)** - Programming-based essential math tutorials
- **[Two-Bit Coding](https://www.youtube.com/c/TwoBitCoding)** - Vector, rotation, and physics examples
- **[Red Blob Games](https://www.redblobgames.com/)** - Visual and interactive explainer articles

### Articles
- [Math Primer for Game Developers](https://theorangeduck.com/page/linear-algebra-game-developers) - Simplified math essentials for devs
- [Wild Linear Transformations](https://eater.net/quaternions) - Visualizing rotation with quaternions

---

## 📚 Books for Game Math

- **"3D Math Primer for Graphics and Game Development" by Fletcher Dunn**
- **"Mathematics for 3D Game Programming" by Eric Lengyel**
- **"Essential Mathematics for Games and Interactive Applications" by James M. Van Verth**
- **"Game Engine Gems" (Series)** - Includes physics math chapters

---

## 🖊️ Cheat Sheets for Math Functions

### C++ STL Math Functions
```cpp
#include <cmath>

// Constants
const double PI = 3.14159265358979323846;

// Basic Trigonometric
std::sin(angle_radians);  // Sine
std::cos(angle_radians);  // Cosine
std::tan(angle_radians);  // Tangent
std::atan2(y, x);         // Arctangent (y/x) - Essential for look-at rotation

// Exponential, Power, Logarithm
std::pow(base, exponent);  // Power (base^exponent)
std::sqrt(value);          // Square Root
std::log(value);           // Natural Logarithm (ln)
std::exp(value);           // e^x

// Rounding/Clamping
std::round(value);   // Round to nearest integer
std::ceil(value);    // Round up
std::floor(value);   // Round down
std::fmod(n, d);     // Floating-point remainder of n/d

// Random Numbers (C++11+)
#include <random>
std::random_device rd;
std::mt19937 gen(rd());                  // Random number generator
std::uniform_real_distribution<> dis(0, 1); // Continuous random value [0,1]
std::uniform_int_distribution<> dis(0, 100); // Integer random value [0,100]

// Example Usage
float radians = PI / 2;  // Converting degrees to radians
float sine = std::sin(radians);
float rand_num = dis(gen);  // Generate a random number
```

---

### Vector Math Cheat Sheet
```cpp
#include <SFML/System/Vector2.hpp>
#include <cmath>

sf::Vector2f a(3.f, 4.f);
sf::Vector2f b(1.f, 2.f);

// Magnitude (Length)
float length = std::sqrt(a.x * a.x + a.y * a.y);

// Normalize (Unit Vector)
sf::Vector2f normalized = a / length;

// Dot Product (Angle Relation)
float dotProduct = a.x * b.x + a.y * b.y;

// Cross Product (2D "pseudo" cross product)
// Useful for determining if a point is left/right of a line or winding order
float cross = (a.x * b.y) - (a.y * b.x);

// Distance Between Two Points
float distance = std::sqrt(std::pow(b.x - a.x, 2) + std::pow(b.y - a.y, 2));

// Linear Interpolation (Lerp)
// Moves from 'start' to 'end' by factor 't' (0.0 to 1.0)
sf::Vector2f lerp(const sf::Vector2f& start, const sf::Vector2f& end, float t) {
    return start + (end - start) * t;
}
```

---

## 🔟 Math Practice & Examples

### Beginner
- Calculate distance and midpoints of two points
- Practice vector normalization (turn into unit vector)
- Use `std::sin` and `std::cos` to move an object in a circle

### Intermediate
- Simulate projectile motion using `atan2` for angles
- Apply force vectors to manipulate accelerations
- Create simple raycasting using vector math

### Advanced
- Rotate objects in 2D/3D around a pivot
- Implement Bézier curves using interpolation
- Simulate springs using Hooke’s Law

---

## 🔧 Interactive Tools
- [Desmos Calculator](https://www.desmos.com/calculator) - Visualize equations
- [GeoGebra](https://www.geogebra.org/) - Interactive geometry/math tool
- [Math is Fun](https://www.mathsisfun.com) - Covers high school math and beyond
- [WolframAlpha](https://www.wolframalpha.com/) - Computational math search engine
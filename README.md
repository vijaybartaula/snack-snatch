# Snack Snatch - Penguin Stealth Mission

Growing up, I was captivated by those clever, mischievous penguins from Madagascar. Skipper, Kowalski, Rico, and Private always executed daring missions with perfect timing and infectious humor. Their blend of teamwork, stealth, and quirky personalities turned every episode into a masterclass in covert operations wrapped in comedy.

**Snack Snatch** captures that same spirit of playful espionage. This simple yet engaging stealth puzzle game lets you guide your penguin through carefully guarded territories to collect fish, all while avoiding the watchful eyes of security guards.

## The Experience

Much like our favorite penguins' classified missions, success here depends on timing, patience, and strategic thinking. Every move matters as you navigate the grid-based levels, plotting the perfect path through guard patrol routes to reach your fishy rewards.

The game strikes that sweet spot between nostalgic charm and genuine challenge — accessible enough for casual players, but with enough depth to keep you planning your next move. Recently, seeing my niece holding an iPad watching this show again just hit that nostalgia perfectly.

It's the kind of experience that brings back memories of huddling around screens, working together to solve the perfect heist.

Whether you're a fan of stealth mechanics, puzzle games, or just have a soft spot for penguin adventures, **Snack Snatch** delivers that satisfying blend of strategy and whimsy that makes every successful fish grab feel like a major victory.

*Simple mechanics. Strategic depth. Maximum sneaky fun.*

## Snack Snatch

**Snack Snatch** is a browser-based stealth puzzle game featuring penguin agents on covert missions to collect fish while avoiding detection by security guards. Built with pure HTML5, CSS3, and JavaScript, the game combines strategic movement, timing-based challenges, and immersive audio feedback to create an engaging tactical gameplay experience.

## Game Features

### Core Gameplay
- **Stealth Mechanics**: Navigate through guard vision cones without being detected
- **Character Selection**: Choose from 4 unique penguin agents (Skipper, Kowalski, Rico, Private)
- **Progressive Difficulty**: 4 challenging levels with increasing complexity
- **Real-time Guard AI**: Dynamic patrol patterns and vision systems
- **Obstacle Navigation**: Strategic use of cover objects to avoid detection

### Technical Features
- **Responsive Design**: Optimized for desktop and mobile devices
- **Web Audio API**: Procedural sound generation for immersive feedback
- **Smooth Animations**: CSS3 transitions and keyframe animations
- **Touch Controls**: Mobile-friendly directional controls
- **Performance Optimized**: 60 FPS game loop with efficient rendering

## Quick Start

### Installation
No installation required! Simply open the HTML file in any modern web browser.

```bash
# Clone or download the game file
# Open snack_snatch_game.html in your browser
```

### System Requirements
- **Browser**: Chrome 60+, Firefox 55+, Safari 11+, Edge 79+
- **JavaScript**: Enabled
- **Screen Resolution**: Minimum 320px width
- **Audio**: Web Audio API support (optional)

## How to Play

### Objective
Guide your chosen penguin agent through each level to reach the fish while avoiding detection by security guards.

### Controls
- **Desktop**: WASD Keys for movement
- **Mobile**: Touch the directional buttons on screen
- **Audio**: Volume slider and mute toggle

### Game Elements
- **Player**: Your penguin agent
- **Guards**: Security with rotating vision cones
- **Goal**: Fish to collect (level objective)
- **Obstacles**: Cover objects that block vision
- **Red Zones**: Guard vision areas (avoid these!)

### Winning Strategy
1. Study guard patrol patterns
2. Use obstacles as cover
3. Time your movements between guard rotations
4. Plan your route to minimize exposure

## Project Structure

```
snack-snatch/
├── snack_snatch_game.html          # Main game file
├── README.md                       # This documentation
├── whitepaper.md                   # Technical analysis
├── LICENSE                         # MIT License information
└── assets/  
    └── favicon.png                 # Game icon (referenced)
```

## Technical Architecture

### Core Classes
- **`SnackSnatchGame`**: Main game controller and state management
- **`AudioManager`**: Web Audio API integration for sound effects
- **Game Loop**: RequestAnimationFrame-based rendering cycle

### Key Systems
- **Grid-based Movement**: 8x8 tile system with collision detection
- **Vision System**: Ray-casting algorithm for guard sight lines
- **Patrol AI**: State machine for guard behavior patterns
- **Responsive Layout**: CSS Grid and Flexbox for cross-device compatibility

### Performance Optimizations
- Efficient DOM manipulation with targeted updates
- CSS hardware acceleration for animations
- Optimized game loop with conditional rendering
- Memory-conscious audio generation

## Design Philosophy

### Visual Design
- **Cyberpunk Aesthetic**: Neon colors and futuristic typography
- **High Contrast**: Accessibility-focused color scheme
- **Responsive Typography**: Clamp-based font sizing
- **Smooth Animations**: CSS transitions for enhanced UX

### User Experience
- **Progressive Disclosure**: Gradual introduction of game mechanics
- **Immediate Feedback**: Audio and visual responses to player actions
- **Clear Visual Hierarchy**: Organized information layout
- **Mobile-First Approach**: Touch-friendly interface design

## Game Statistics

### Tracking Metrics
- **Current Level**: Progress indicator
- **Fish Collected**: Success counter
- **Success Rate**: Performance percentage
- **Attempt History**: Win/loss tracking

### Level Progression
- **Level 1-4**: Increasing guard count and complexity
- **Dynamic Difficulty**: Adaptive challenge scaling
- **Replay Value**: Randomized vision colors for variety

## Customization Options

### Character Selection
Each penguin agent offers the same gameplay mechanics but different visual representation:
- **Skipper** (🐧): The leader
- **Kowalski** (🤓): The strategist  
- **Rico** (💥): The explosives expert
- **Private** (😊): The rookie

### Audio Controls
- **Volume Slider**: Adjustable sound levels
- **Mute Toggle**: Complete audio disable
- **Procedural Audio**: Generated tones for retro gaming feel

## Known Issues & Limitations

### Current Limitations
- Fixed 8x8 grid size
- Static level configurations
- No persistent save system
- Limited to 4 predefined levels

### Browser Compatibility
- Web Audio API may not work in older browsers
- Mobile performance varies by device
- Some CSS features require modern browser support

## Future Development

### Planned Features
- **Level Editor**: User-created content
- **Multiplayer Mode**: Cooperative missions
- **Achievement System**: Unlock rewards
- **Story Mode**: Narrative campaign
- **Power-ups**: Temporary abilities

### Technical Improvements
- **Save System**: Progress persistence
- **Performance Metrics**: FPS monitoring
- **Accessibility**: Screen reader support
- **Internationalization**: Multi-language support

## Contributing

### Development Setup
1. Fork the repository
2. Make changes to the HTML/CSS/JavaScript
3. Test across multiple browsers
4. Submit pull request with description

### Code Style
- ES6+ JavaScript features
- Semantic HTML structure
- BEM CSS methodology
- JSDoc comments for functions

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for full details.

## Acknowledgments

- Inspired by classic stealth games like Metal Gear Solid
- CSS animations inspired by modern web design trends
- Audio system based on Web Audio API best practices
- Responsive design follows mobile-first principles

---

**Made with love for penguin enthusiasts and stealth game fans everywhere.**

> *"Just smile and wave, boys. Smile and wave." — Skipper*

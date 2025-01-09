# UX Specification

## Core Experience

### 1. Character Creation Flow

#### Class Selection Screen

- Full-width hero sections for each class
- Quick class comparison tooltips showing:
  - Class skills and mechanics
  - Primary attributes
  - Playstyle overview
  - Recommended builds
- One-click selection with smooth transition
- Class-specific background themes

#### Build Interface

- **Character Summary**
  - Class icon and name
  - Primary stats overview
  - Set bonuses active
  - Gem resonance status
  - Skill modifications from essences

- **Equipment Management**

  ```text
  ┌─────────────────┐  ┌──────────────────┐
  │    Primary      │  │      Set         │
  │     Gear        │  │     Items        │
  │                 │  │                  │
  │  [Head/Chest/   │  │  [Neck/Rings/    │
  │  Shoulders/etc] │  │   Waist/etc]     │
  └─────────────────┘  └──────────────────┘
  ┌─────────────────┐  ┌──────────────────┐
  │    Legendary    │  │   Legendary      │
  │     Gems        │  │    Essences      │
  └─────────────────┘  └──────────────────┘
  ```

### 2. Interactive Elements

#### Gear Slots

- Floating tooltips showing:
  - Item slot type
  - Available essences for slot
  - Set item possibilities
  - Gem socket availability
  - Stat constraints
- Color-coded by rarity/type
- Quick-swap functionality

#### Stat Display

- Real-time stat updates
- Visual comparisons (better/worse)
- Stat grouping by type:
  - Offensive
  - Defensive
  - Utility
- Synergy highlights
- Detailed stat tooltips with:
  - Stat description
  - Current value
  - Potential range
  - Source breakdown

#### Gem System

- Hexagonal gem socket layout
- Visual gem resonance links
- Resonance power indicator
- Gem rank display
- Socket type indicators
- Gem details panel showing:
  - Star rating
  - Skill effects
  - Stat boosts
  - Progression path
  - Synergy opportunities

### 3. Build Management & Sharing

#### Build Library

- Card-based build library
- Quick preview showing:
  - Class and level
  - Key stats
  - Set bonuses
  - Gem setup
  - Skill modifications
- Version history
- Build comparison

#### Build Storage

- Automatic save to GitHub Gists
- JSON-formatted build data
- Version tracking through gist history
- Offline mode with local storage
- Background sync with conflict resolution

#### Build Sharing & Social

- One-click build sharing via:
  - Direct gist URL
  - Build code snippet
  - Social media links
- Build showcase cards with:
  - Class overview
  - Key stats
  - Set bonuses
  - Gem configuration
  - Essence choices
  - Synergy highlights
- Community features:
  - Star/favorite builds
  - Fork statistics
  - Build comments
  - Author attribution
  - Build collections

### 4. Advanced Features

#### Build Optimizer

- Interactive optimization based on:
  - Selected stats priority
  - Available gear/gems
  - Set bonus targets
  - Gem resonance goals
  - Class synergies
- Real-time stat adjustments
- Visual upgrade paths
- Synergy suggestions

## Authentication & Storage

### 1. GitHub Integration

#### Login Flow

- Clean login page with GitHub button
- OAuth popup window handling
- Loading states during authentication
- Error handling and retry options
- Seamless return to previous state

#### User Profile

- GitHub avatar and username display
- Access token management
- Session persistence
- Logout functionality
- Account linking status

### 2. Build Storage

#### Gist Integration

- Automatic build saving to Gists
- Build metadata in gist description
- JSON-formatted build data
- Version tracking through gist history
- Offline mode with local storage

#### Build Sync

- Background save on changes
- Conflict resolution
- Merge strategies
- Sync status indicators
- Error recovery

#### Build Import/Export

- Import from gist URL
- Export as gist
- Share via link
- Copy build code
- Import from code

## Interaction Patterns

### 1. Gestures & Animations

#### Touch/Mouse

- Swipe between builds
- Long press for details
- Double tap to equip
- Drag to compare items
- Hover for quick stats

#### Transitions

- Smooth item swaps
- Stat change animations
- Set bonus activation effects
- Gem resonance visualizations
- Synergy connection animations

### 2. Feedback Systems

#### Visual

- Pulse on item changes
- Glow for set completion
- Synergy connection lines
- Progress indicators
- Success/error states
- Stat improvement highlights

#### Audio

- Subtle equip sounds
- Set bonus completion
- Gem socket sounds
- Navigation feedback
- Synergy activation

## Mobile Experience

### 1. Touch-First Design

- Large touch targets
- Bottom navigation
- Reachable actions
- Swipe gestures
- Pull to refresh

### 2. Responsive Layout

- Single-column focus
- Collapsible panels
- Modal item details
- Quick actions bar
- Context-aware UI

## Performance Optimizations

### 1. Loading Strategy

- Progressive data loading
- Cached item database
- Background stat calculations
- Preloaded class data
- Instant UI responses

### 2. Offline Support

- Cached build data
- Offline calculations
- Background sync
- Local save states
- Auto-recovery

## Accessibility Features

### 1. Navigation

- Keyboard shortcuts
- Screen reader support
- Focus management
- Skip links
- Voice commands

### 2. Visual Aids

- High contrast mode
- Colorblind options
- Text scaling
- Reduced motion
- Custom themes

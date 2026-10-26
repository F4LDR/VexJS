# Vex.js Documentation

Guides and references for Vex.js, a lightweight 2D game engine for desktop, and browsers. These docs mainly cover `v1.0.x`, with pages for `v1.1.0` features marked.

## Table of Contents

- **[Getting Started](#getting-started)**
- **[Game Concepts](#game-concepts)**
- **[API References](#api-references)**
- **[Guides](#guides)**

## [Getting Started](./GETTING_STARTED.md)

- Learn how to install Vex.js, test demos, & build your first game!

## [Game Concepts](./CONCEPTS/)

How the pieces of the engine fit together. Read these in chronological order if you're a new user:

- **Game Loop**: Fixed Timesteps, which runs for each frame using `dt` (delta time).
- **States**: Game Scenes, switching between them, & substates.
- **Sprites & Objects**: Motion, Graphics, Animation & Lifecycle Flags.
- **Groups**: Collections of Objects & Object Pooling.
- **Camera**: Scrolling, Following, Zoom & Screen Effects.

## [API References](./API/)

Every `VexClass`, with its properties and methods:

### Core:

- **[`VexGame`](../source/VexGame.js)**: The Canvas, The Loop, & you're First State.
- **[`VexState`](../source/VexState.js)**: Your current Game Scene.
- **[`VexBasic`](../source/VexBasic.js)**: The base class with Lifestyle Flags.
- **[`VexGlobal`](../source/VexGlobal.js)**: Input, Screen Size, The Camera, & The Current State.

### Objects

- **[`VexSprite`](../source/VexSprite.js)**: A moveable, or drawable Object.
- **[`VexObject`](../source/VexObject.js)**: Motion & Collision base class.
- **[`VexText`](../source/text/VexText.js)**: Text on the Game Canvas.
- **[`VexAnimationController`](../source/animation/VexAnimationController.js)**: Frame Animation.
- **[`VexAtlas`](../source/animation/VexAtlas.js)**: Sprite Atlas loading.

### World

- **[`VexGroup`](../source/VexGroup.js)**: Collections of Object Pooling.
- **[`VexCamera`](../source/VexCamera.js)**: Scroll, Zoom, Follow, Flash, & Fade.

### Effects & Utilities

- **[`VexEmitter`](../source/effects/particles/VexEmitter.js)**: Particle Bursts.
- **[`VexTween`](../source/tweens/VexTween.js)** / **[`VexEase`](../source/tweens/VexEase.js)**: Animating Properties over time.
- **[`VexSignal`](../source/VexSignal.js)**: Events

## [Guides](./GUIDES/)

Short walkthroughs for common engine tasks:

- **Platformer Collision**: Gravity, Platforms, & Jumping.
- **Particle Bursts**: Landing dust, Hit Sparks, & Explosions.
- **Camera Modes & Transitions**: Locked & Smooth cameras, Fades & Flashes.

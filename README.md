Couples Advent Calendar – 25 Days of Love
Abstract

This project implements an interactive advent calendar designed for couples. It consists of 25 daily activities that unlock automatically according to the current date. The interface arranges all calendar units into a heart-shaped layout. The project is fully responsive, uses no external frameworks, and maintains user progress through localStorage.

1. Introduction

The Couples Advent Calendar aims to create a shared daily experience throughout December. Each day reveals a task, message, or activity intended to strengthen connection and communication. The project is implemented using standard web technologies (HTML, CSS, JavaScript) and is lightweight enough to run directly in any modern browser.

2. Features
2.1 Heart-Shaped Layout

The 25 units are positioned using CSS grid to form a visually balanced heart shape.

2.2 Daily Unlock Logic

Each card becomes accessible only on or after its corresponding calendar date (e.g., Day 12 unlocks on December 12). This logic uses the system time of the user's device.

2.3 Card Flip Animation

Every card contains a front and back side and uses smooth 3D transitions.

2.4 Persistent Progress

Once a card is opened, its state is stored in localStorage to preserve progress across page reloads.

2.5 Responsive Design

The interface adapts to both mobile and desktop displays without changing the core structure.

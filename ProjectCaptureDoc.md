# Smallest Area Visualization, Project Capture Document

## Background
This was proposed to me as a coding challenge by a coworker. The original question was, "How would you encapsulate a set of random points in a **square**, using the smallest area?" Figuring out how to encapsulate all the points in a square, period, was simple. Figuring out how to encapsulate the points in a square with the smallest possible area took some more thought. I decided to program this as a challenge to myself, and having a visual would be a good way to verify the possible solutions work.

-----

## Objectives
- Generate a list of possible values (called points) that represent 2D spacial locations.
    - Display the list of points visually on an HTML page.
- Discover how to encapsulate the points in a manner that each point is included in the encapsulated area.
    - Display the encapsulation of points on an HTML page.

-----

# Requirements

## Input Requirements
- The system shall require a list of values (called 'points') that represent 2D spacial locations.

#### Accepted Input Sources:
- Random generation by the system

---

## Output Requirements
- The computer shall discover how to encapsulate the points in a manner such that each point is included in the encapsulated area.
- The area of the encapsulation shall be displayed to the user.

---

## Interface
- The program interface shall be a web page. 
- On load there shall be the collection of points displayed. 
- There shall be an option to select which algorithm to use to encapsulate the points, defaulted to rectangle.

-----
---
template: addon_info.html

title: Robot Entity
description: Adds a Robot with multiple animations as a custom entity.

itemsadder:
  entity_list:
    - name: robot
      animations:
        - name: idle
          description: Floats up and down at its location. Default animation.
        - name: move
          description: Moves bottom part of body slightly back. Used during movement.
        - name: death
          description: Falls apart into pieces. Used on death.
        - name: wave_right
          description: Raises and moves right arm in a greeting motion.
        - name: wave_left
          description: Raises and moves left arm in a greeting motion.

download: 'https://www.spigotmc.org/resources/100727/'

previews:
  - link: 'https://www.youtube.com/embed/VeA3BanJiJQ'
    type: video
---

A simple add-on that adds a robot entity with multiple animations available.  
It's recommended to use it on a Citizens NPC to avoid random movement.

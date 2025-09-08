Home Automation – Home Assistant

This repository showcases a variety of Home Assistant automations I’ve created to automate daily tasks around my home. All automations are safe for sharing — device IDs have been replaced with descriptive names and sensitive information removed. This project demonstrates practical applications of sensors, lights, notifications, and smart home logic.

1. Door & Motion-Based Lighting

Pantry light automation: turns on when the door opens or motion is detected, off when closed or no motion.

Master closet light: turns on with motion, off after 2 minutes of inactivity.

Garage lights: automatically turn on when doors open or motion is detected; turn off after no motion.

2. Living Room Ambient Lighting

Lights turn on at sunset and gradually dim over the evening.

Lights automatically turn off at 11 PM.

3. Appliance Notifications

Notifications when washing machine, dryer, or dishwasher complete cycles.

Sends alerts to mobile devices with friendly messages.


4. Sprinkler Safety

Automatically turns off sprinklers after 20 minutes to prevent overwatering.

Technologies & Concepts

Home Assistant – main automation platform.

YAML – configuration and automation scripting.

Templates – dynamic automation logic using Jinja2 templates.

Blueprints – reusable automation templates.

Notifications – mobile alerts via Home Assistant Companion App

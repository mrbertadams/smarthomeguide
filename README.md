# smarthomeguide
A guide to setting up your smart home
Lights and Lighting
Beginner
Install smart lights (Philips Hue, Lutron, or similar).
Use smart switches (Philips or Lutron) so power is never cut to the bulbs.
Turn on/off lights at certain times of the day.
Turn on hallway lights for a period of time after motion is detected.
Create different light scenes, like party or relax.
Create a kiosk for controlling lights and scenes with Home Assistant (or similar).
Intermediate
Turn on/off lights based upon who’s home (see: Presence and Motion detection).
Add ambient lighting to a home theater (see: Movies and TV).
Make light fade in/out rather than switching on/off.
Advanced
Create “status lights” that change color to indicate when something important has happened, like when a guest arrives (see: Security and CCTV) or the garage door is left open.
Sound and Music
Beginner
Use Sonos to have speakers in each room playing the same music.
Create a kiosk for controlling sound/music with Home Assistant (or similar).
Intermediate
Make your own “Sonos” multi-room sound system with spare parts.
Create your own Airplay+Spotify server to play music on the multi-room speakers.
Make a “loudspeaker” alert system.
Change the audio source for each room (Airplay, Spotify, etc.)
Movies and TV
Beginner
Automatically download new movies/TV every night.
Run your own media server with Kodi.
Raise/lower a projector screen with Harmony Home Hub (or similar).
Turn on/off a TV/projector with Harmony Home Hub (or similar).
Create a kiosk for controlling movies/TV with Home Assistant (or similar).
Intermediate
Store movies/TV on a DIY NAS.
Use ambilight to add a colorful pop behind the TV/screen.
Raise/lower a projector screen with a custom IR controller or wired connection.
Build a RetroPi (DIY video game system).
Advanced
Automatically open/close blinds/drapes when the TV turns on/off to improve lighting.
Presence and Motion Detection
Beginner
Use motion sensors (like SmartThings) to tell when a room is occupied.
Add mobile devices (with GPS) to Home Assistant.
Create a sensor for the presence of each individual in the household.
Intermediate
Use DIY bluetooth beacons to detect which room a person (phone) is in.
Assign unique door codes to each guest and detect who has entered.
Use MotionEye to detect guests with cameras.
Advanced
Use multiple presence signals (GPS+beacon) for greater accuracy.
Security and CCTV
Beginner
Integrate a security system like Nest or Arlo with Home Assistant.
Automatically re-lock doors after they are closed.
View all your cameras, regardless of brand, from anywhere in the world using MotionEye.
Intermediate
Automatically (un)lock the doors when you leave/arrive (see: Presence and Motion Detection).
See who is at the door by adding the video feed from the doorbell to Home Assistant.
Detect when someone arrives using MotionEye.
Add sensors for gas and other security hazards.
Build miniature ESP32 spy cameras for ~$10 each.
Advanced
Build your own DIY smart doorbell.
Use machine learning (DOODS/TensorFlow) to detect people, pets, cars, etc.
Add facial recognition to distinguish between guests.
Temperature and Climate
Beginner
Automate smart thermostat (Nest, EcoBee, HoneyWell) with Home Assistant.
Save money by turning off heat/AC when nobody is home (see: Presence Detection).
Turn heat/AC back on before someone arrives home (see: Presence Detection).
Intermediate
Build cheap, accurate temperature sensors for more precision.
Create a climate dashboard with Grafana/Prometheus.
Heated towel racks, radiant floor heating, etc.
Advanced
Build a DIY 3-zone thermostat.
Automatically open/close blinds/drapes.
Automate (de)humidifiers to control humidity levels.
Family and Home-Care
Beginner
Add door sensors (SmartThings, or similar) to alert when a door is left open.
Use Home Assistant to set reminders for household maintenance like taking out the trash, replacing filters, etc.
Alert when a pet might be in danger.
Create a kiosk with the family TODO list on the main screen.
Intermediate
Add sensors for water leaks.
Automatically water plants.
Create a 3D Render of the floorplan which reflects the current states.
Deter thieves with a “vacation mode” that simulates normal household activity.
Turn off unnecessary automations with a “guest mode.”
Advanced
Automatically generate unique door codes for Airbnb guests.
Internet and Home Networking
Beginner
Build a home server.
Install an ad-blocker like PiHole or AdGuard Home.
Intermediate
Monitor all network traffic to find out why it’s slow.
Turn a Raspberry Pi into a DIY router.
Track cellular data usage to prevent going over limits.
Install ethernet ports in every room for maximum reliability/speed.
Advanced
Use Kubernetes to deploy an IOT fleet.
Cars and Travel
Intermediate
Build a DIY dashcam.
Use connection bonding to speed up the internet.
Track speed and fuel usage with OBDII.
Appliances and Misc.
Beginner
Create morning/night automations for coffee pots,
Use the Harmony Home Hub (or similar) to control anything that uses a remote.
Turn on/off appliances automatically (see: Presence and Motion detection).
Intermediate
Monitor power usage with Grafana and Prometheus dashboards.
Conserve power by automatically shutting off unnecessary appliances.
Use IRC on a Raspberry Pi or Arduino to control anything that uses a remote.
Create a relay box for turning on/off power outlets.
Advanced
Install low-voltage wiring for centralized control of each outlet.

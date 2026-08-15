# TerraLoop — Smart Waste Operations

Presentation-ready, front-end-only software prototype for the SIH internal hackathon brief:

**IoT-enabled smart waste sorting and autonomous collection optimization.**

## What is included

- Interactive operations dashboard with network health, active bin map, priority queue, activity stream and waste mix.
- AI sorting screen that simulates the camera → classifier → ESP32 → servo → smart bin loop for plastic, paper and metal.
- Smart bin network screen with fill levels, forecast states and simulated ultrasonic sensor updates.
- Route planner with a visual route simulation, priority-based stops, A* pathfinding story and dispatch interaction.
- System flow screen connecting the physical station, AI, IoT data layer and decision engine.
- Guided Presentation Mode with six mentor-ready scenes that can be screen-recorded as the software prototype video.

## Run it

This is a static website. Open `index.html` directly in a browser, or run a simple local server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Demo path for mentor review

1. Open **Presentation mode** and run the six-scene walkthrough.
2. Open **AI sorting**, select an item and press **Run sorting cycle**.
3. Open **Bin network**, press **Simulate sensor update** to show live IoT behavior.
4. Open **Route planner**, press **Optimize route**, then **Dispatch simulated vehicle**.
5. Finish on **System flow** to explain the hardware and software architecture.

The hardware is represented as a physical station and live telemetry loop; the collection vehicle is intentionally simulated at this prototype stage, matching the recommended internal-round scope from the brief.

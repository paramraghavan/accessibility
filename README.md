# Accessibility

## dual clock
### Zoomin time, time for location1 and location2 can be zoomed in  touch on ios and android phones:
- Zoom Functionality: The setupZoom function adds touch event listeners to the specified element. It uses the distance between two touch points (fingers) to calculate the zoom scale.
- Touch Event Listeners: The touchmove event updates the scale of the element based on the movement of the fingers. The touchend event resets the starting distance when the fingers are lifted off.
- ZOOM_SPEED Constant: This constant controls how quickly the element zooms in or out in response to the touch movement.
- Applying to Time Zones: The zoom functionality is applied to both the New Delhi and New York time zones.
- Above approach allows users to pinch-to-zoom in and out on each time zone independently on their touch devices. The scale of the time display will adjust according to the user's pinch gestures.

- http://localhost:63342/dual-clock/dual-clock.html?location1=Asia/Kolkata&location2=America/New_York
- http://localhost:63342/dual-clock/dual-clock.html?location1=Asia/Kolkata&location2=America/Los_Angeles



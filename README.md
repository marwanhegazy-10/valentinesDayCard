# Interactive Valentine's Envelope Card 

A charming interactive Valentine's card featuring an animated envelope that reveals a message when opened, complete with a custom heart-shaped cursor. Built with pure HTML, CSS, and JavaScript.

## Features

- Animated envelope that opens on hover to reveal a pop-up message
- Custom heart-shaped cursor that follows mouse/touch movement
- Floating animation effect with dynamic shadow
- Interactive elements with smooth transitions:
  - Dual-lid envelope opening animation
  - Letter that pops up when envelope opens
  - Heart decoration inside the letter
- Touch device support for mobile interactions

## Design Details

The card uses a carefully crafted color palette defined through CSS variables:
```css
--background: #fee2e9
--light-pink: #fcbbcc
--pink: #fba7bd
--dark-pink: #f980a1
--card: white
--heart: #f40b4a
```

## Demo

[View Live Demo](https://marwanhegazy-10.github.io/valentinesDayCard/) - Add your deployed card link here

## Technologies Used

- HTML5 for structure
- CSS3 for styling and animations
- JavaScript for interactive features and touch support

## Installation

1. Clone the repository:
```bash
git clone https://github.com/marwanhegazy-10/valentinesDayCard.git
```

2. Navigate to the project directory:
```bash
cd valentinesDayCard
```

3. Open `index.html` in your preferred browser.

## Usage

### Interaction Guide
- Hover over the envelope to trigger the opening animation
- The envelope flaps will open smoothly
- A letter will pop up with your Valentine's message
- Watch the custom heart cursor follow your mouse movements
- The entire card gently floats with a dynamic shadow

### Customization

1. Modify the Message:
   - Open `index.html`
   - Find the `letter` div
   - Edit the text within the `text` div

2. Change Colors:
   - Open `style.css`
   - Modify the CSS variables at the top of the file
   - All colors will update automatically throughout the design

3. Adjust Animations:
   - Animation timings can be modified in `style.css`
   - Floating animation: adjust the `@keyframes up` values
   - Shadow animation: modify `@keyframes scale`
   - Opening animation: change transition timing in `.lid` classes

4. Cursor Customization:
   - Adjust heart cursor size by modifying `.heart-cursor` width and height
   - Change cursor color using the `--heart` CSS variable

## Acknowledgments

- Google Developer Student Club at UTD

## 🔗 Project Link

[https://github.com/marwanhegazy-10/valentinesDayCard](https://github.com/marwanhegazy-10/valentinesDayCard)

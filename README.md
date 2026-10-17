# Treasures of Egypt - Special Exhibition UI

A responsive, CSS-only web interface designed for a museum's special exhibition. This project was built to deeply explore and practice **CSS Pseudo-classes** and **Pseudo-elements**, demonstrating how to create interactive and dynamic user experiences without relying on JavaScript.

## 🎯 Project Focus

The main goal of this repository is to practice advanced CSS selection techniques and state styling. By isolating HTML and CSS, the project focuses strictly on manipulating the DOM visually based on user interaction states.

### Key CSS Concepts Explored:
*   **`:hover` & `:active`**: Applied to table rows and buttons to provide immediate visual feedback upon user interaction.
*   **`:checked`**: Used to completely restyle default HTML radio buttons, enlarging them and dynamically underlining the adjacent label text when selected.
*   **`:invalid`**: Implemented real-time form validation styling. If the user enters an incorrect email format, the input field dynamically changes its background and border to alert the user.
*   **`:disabled`**: Styling applied to sold-out ticket options to visually indicate unavailability.
*   **`::after`**: Utilized for the classic `clearfix` hack on the main container to properly contain floated child elements (the poster and the content area).

## 🛠️ Technologies Used

*   **HTML5**: Semantic structure, form inputs, and table layouts.
*   **CSS3**: Native CSS nesting, typography, floats, and extensive use of pseudo-classes/elements.
*   **FontAwesome**: External icon library for visual enhancement in the visiting rules section.

## 🚀 How to Run

Since this is a static web page focusing solely on HTML and CSS, no build tools or servers are required.

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yusif9999/css-pseudo-classes-exhibition.git

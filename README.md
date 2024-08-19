<strong>Project Title:</strong> Etch-A-Sketch/Sketchpad

<strong>Project Overview:</strong>
This project is a browser-based sketchpad application that allows users to draw by hovering over a grid of squares. It leverages DOM manipulation, event handling, and Flexbox for layout design. The project emphasizes dynamic content generation using JavaScript, along with interactive features that allow users to customize the grid size.

<strong>Technologies and Skills Used:</strong>

<ul>
  <li><strong>HTML5:</strong> Structured the layout of the webpage, including the grid container and control elements.</li>
  <li><strong>CSS3:</strong> Styled the grid and container using Flexbox to create a responsive layout, managing hover effects and interactive styles.</li>
  <li><strong>JavaScript (ES6+):</strong> Handled dynamic grid creation, user interactions, event listeners, and DOM manipulation.</li>
  <li><strong>DOM Manipulation:</strong> Generated grid squares, applied event listeners, and updated elements based on user actions.</li>
  <li><strong>Flexbox:</strong> Positioned and aligned the grid squares to form a responsive grid layout, ensuring consistency across various grid sizes.</li>
  <li><strong>Version Control (Git):</strong> Tracked the development process with commits, branches, and regular pushes to GitHub.</li>
</ul>

<strong>Features:</strong>

<ul>
  <li><strong>Dynamic Grid Creation:</strong>
    <ul>
      <li>The application generates a 16x16 grid of square div elements dynamically using JavaScript.</li>
      <li>The grid is housed inside a container div and structured using Flexbox for alignment and layout.</li>
    </ul>
  </li>
  <li><strong>Interactive Drawing:</strong>
    <ul>
      <li>Users can "draw" by hovering their cursor over the grid squares, leaving a trail that mimics pen strokes.</li>
      <li>The hover effect is achieved by changing the background color of the grid squares as the mouse moves over them.</li>
      <li>Multiple techniques are supported, such as adding/removing CSS classes or directly modifying the background color using JavaScript.</li>
    </ul>
  </li>
  <li><strong>Custom Grid Resizing:</strong>
    <ul>
      <li>The application includes a button that allows users to specify the number of squares per side for the grid (up to a limit of 100).</li>
      <li>A prompt appears when the button is clicked, asking for the desired grid size.</li>
      <li>The grid automatically resizes within a fixed container size, ensuring the overall dimensions (e.g., 960px wide) remain consistent.</li>
    </ul>
  </li>
  <li><strong>Responsive Layout Using Flexbox:</strong>
    <ul>
      <li>The grid squares are positioned using Flexbox, ensuring they wrap correctly and align evenly regardless of grid size.</li>
      <li>Flexbox properties manage spacing, wrapping, and alignment, allowing the grid to resize dynamically.</li>
    </ul>
  </li>
  <li><strong>User-Friendly Controls:</strong>
    <ul>
      <li>The grid size can be adjusted by clicking a button that triggers a prompt.</li>
      <li>The interface is intuitive and straightforward, with minimal controls for ease of use.</li>
    </ul>
  </li>
  <li><strong>Reset and Recreate Grid:</strong>
    <ul>
      <li>When a new grid size is specified, the existing grid is removed, and a new grid is generated with the updated dimensions.</li>
      <li>The grid remains responsive and adapts to the chosen size while maintaining square proportions for each cell.</li>
    </ul>
  </li>
  <li><strong>Error Handling and Validation:</strong>
    <ul>
      <li>The user input is validated to ensure the grid size does not exceed 100x100, preventing potential performance issues.</li>
      <li>The application handles edge cases such as invalid input or excessively large grid sizes.</li>
    </ul>
  </li>
  <li><strong>GitHub Deployment:</strong>
    <ul>
      <li>The project is version-controlled and hosted on GitHub, allowing easy access to the codebase and project files.</li>
    </ul>
  </li>
</ul>

<strong>How to Run the Project:</strong>

<ul>
  <li>Clone the repository from GitHub.</li>
  <li>Open the index.html file in a browser.</li>
  <li>Use the grid to draw by hovering your mouse over the squares.</li>
  <li>Click the button at the top to resize the grid and specify the desired number of squares per side.</li>
</ul>

<strong>Future Improvements:</strong>

<ul>
  <li>Add color selection options for drawing.</li>
  <li>Implement additional modes, such as shading or erasing.</li>
  <li>Make the grid responsive to window resizing while maintaining the square proportions of the cells.</li>
</ul>

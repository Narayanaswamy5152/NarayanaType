In this project, let's build a **Touch Type App** by applying the concepts we have learned till now.





### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>

### Completion Instructions

<details>
<summary>Functionalities  added</summary>
<br/>

The app must have the following functionalities

- The default timer limit value should be 25 minutes
- When the **Start** button is clicked,
  - The **Start** text should change to **Pause** text
  - The **play icon** should be replaced by **pause icon**
  - The **Timer** status should change to **Running**
  - The **Timer** should start running backwards from the timer limit value set
  - If the **Timer** has been paused after starting, it should resume from where it was paused
  
- When the **Pause** button is clicked,
  - The **Pause** text should change to **Start** text
  - The **pause icon** should be replaced by **play icon**
  - The **Timer** should stop running backwards
  - The **Timer** status should change to **Paused**
  - Both the **Plus** and **Minus** buttons should be disabled


- When the **Timer** ends (displays **00:00**)
  - The **Pause** text should change to **Start** text
  - The **pause icon** should be replaced by **play icon**
  - The **Timer** should stop running backwards
  - The **Timer** status should change to **Paused**
- After completion of **Timer**, when the **Start** button is clicked,
  - The **Start** text should change to **Pause** text
  - The **play icon** should be replaced by **pause icon**
  - The **Timer** should start running backwards from the current timer limit value.
  - The **Timer** status should change to **Running**
- When the **Reset** button is clicked, then
  - The **Pause** text should change to **Start** text
  - The **pause icon** should be replaced by **play icon**
  - The **Timer** should stop running backwards
  - The **Timer** status should change to **Paused**
  - Initial **Timer** limit value should be displayed
  
    
  -When user enters the letters using keyboard which are showing on screen the accuracy percentage the letters count will be displayed on the screen.

</details>

<details>
<summary>Implementation Files</summary>
<br/>

Use these files to complete the implementation:

- `src/components/TouchType/index.js`
- `src/components/TouchType/index.css`
</details>

### Quick Tips

<details>
<summary>Click to view</summary>
<br>

- You can use the `box-shadow` CSS property to apply the box-shadow effect to containers

  ```
    box-shadow: 0px 4px 16px 0px #bfbfbf;
  ```

  <br/>
  <img src="https://assets.ccbp.in/frontend/content/react-js/box-shadow-img.png" alt="box shadow" style="width:200px" />

- You can use `Math.floor()` function that returns the **largest integer less than or equal to a given number**

  ```js
  console.log(Math.floor(5.95)); // output: 5
  ```

- You can use the `background-position` CSS property to set the starting position of a background image
  ```
  background-position: center;
  ```

</details>



<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #ffffff ; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #cffcf1 ; width: 150px; padding: 10px; color: black">Hex: #cffcf1</div>
<div style="background-color: #1e293b ; width: 150px; padding: 10px; color: white">Hex: #1e293b</div>
<div style="background-color: #0f172a ; width: 150px; padding: 10px; color: white">Hex: #0f172a</div>
<div style="background-color: #defafe ; width: 150px; padding: 10px; color: black">Hex: #defafe</div>
<div style="background-color: #00d9f5 ; width: 150px; padding: 10px; color: white">Hex: #00d9f5</div>

</details>

<details>
<summary>Font-families</summary>

- Roboto

</details>

> ### _Things to Keep in Mind_
>
> - All components you implement should go in the `src/components` directory.
> - Don't change the component folder names as those are the files being imported into the tests.
> - **Do not remove the pre-filled code**
> - Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets.

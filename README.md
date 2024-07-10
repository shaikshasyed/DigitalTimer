In this project, let's build a **Digital Timer App** by applying the concepts we have learned till n
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/digital-timer-output.gif" alt="digital timer output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)" />
</div>
<br/>

<details>
<summary>Functionalities:</summary>
- The default timer limit value should be 25 minutes
- When the **Start** button is clicked,
  - The **Start** text should change to **Pause** text
  - The **play icon** should be replaced by **pause icon**
  - The **Timer** status should change to **Running**
  - The **Timer** should start running backwards from the timer limit value set
  - If the **Timer** has been paused after starting, it should resume from where it was paused
  - Both the **Plus** and **Minus** buttons should be disabled
- When the **Pause** button is clicked,
  - The **Pause** text should change to **Start** text
  - The **pause icon** should be replaced by **play icon**
  - The **Timer** should stop running backwards
  - The **Timer** status should change to **Paused**
  - Both the **Plus** and **Minus** buttons should be disabled
- When the button with the **Plus** symbol is clicked,
  - The timer limit value should be incremented by one minute
  - The **Timer** should display time with the increased timer limit value
- When the button with the **Minus** symbol is clicked,
  - The timer limit value should be decremented by one minute
  - The **Timer** should display time with the decreased timer limit value
- When the timer limit value is modified by clicking the **Plus** or **Minus** button and the **Start** button is clicked, then the **Timer** should start with the modified timer value
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
  - Both the **Plus** and **Minus** buttons should be enabled

</details>



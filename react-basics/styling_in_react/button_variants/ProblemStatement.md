Problem statement
Generally web applications often have multiple buttons, and most of them have similar features and styles.

Expected Output:

Tasks :
Create a single reusable button component called ButtonView using styled components which can be modified based on the properties that are being passed.
If the "filled" props is passed to the ButtonView it should render the button after applying the styles passed (bg and color) else, the ButtonView component should display an outlined button.
The ButtonView styled component should have these additional props passed to it, if "filled" is passed to the component.
bg - Changes the background color of the filled button
color - Changes the text color of the filled button

Test Cases:

1. Styled component is exported

   - Create a styled component named ButtonView and export it using the named export.

   Note:
   Do not default export it.

2. Default styles work correctly

   - When the styled component is called using no props it should display the default button as displayed in the expected output with style as given below.

   Background-color = #fff
   Color = #000
   Border-color: = #000

3. Props work correctly

   - When the “filled” props are passed along with other props as “background color” and “color” it should display the button applying the given styles.

   Background-color = <Color passed using props>
   color = <Color passed using props>
   border: none

Download Link: https://assignmentchef.com/product/solved-cpts479-assignment2-quizapp-that-maintains-the-quiz-questions
<br>
For this homework you will implement a version of the QuizApp that maintains the quiz questions in a Question class and cycles through the questions using a “Next” button. See screen shots below. Specifically,

<ol>

 <li>Create a new Swift file called Question.swift. In the file define a class called “Question” with three properties: a String for the quiz prompt, an array of Strings for the possible answers, and an integer for the index of the correct answer in the answers array.</li>

 <li>On the StoryBoard, add a label at the top of the view with the app’s name “Quiz App”. Below that add a label with the quiz question number. Below that, add a label for the quiz question prompt. These labels should be centered horizontally and constrained to be appropriately spaced at the top of the view. The prompt label should allow for two lines of text and should set Autoshrink to a Minimum Font Scale of 0.5. This will allow long prompts to still be visible. See Storyboard and simulator screenshots.</li>

 <li>Below the prompt label, add a vertical stack view to hold five buttons for the alternative answers. The button text should be left-aligned, and the stack view should be centered.</li>

 <li>Centered below the alternative answers, add a label to show the result of your guess, e.g., “Correct” or “Incorrect”. This label should be initially hidden.</li>

 <li>Centered at the bottom of the view should be a button titles “Next”.</li>

 <li>Your ViewController code should manually create at least three quiz questions and store them in a quiz array. At least one question should have only two alternative answers, at least one question should have five alternative answers, and at least one quiz question should have a prompt that extends to more than one line.</li>

 <li>Add outlets, actions, and supporting code to the View Controller so that your app exhibits the following functionality.

  <ol>

   <li>When the app starts, the first question in the quiz is displayed.</li>

   <li>When a quiz question is displayed, the question number is shown at the top, followed by the prompt. only the appropriate number of buttons should appear corresponding to the number of alternative answers defined for the question. Each answer should be prefaced by the appropriate letter: “a.” for the first answer, “b.”</li>

  </ol></li>

</ol>

for the second answer, etc. All answers are in the default tintColor, and the Result label is hidden.

<ol>

 <li>If the user taps a button, only the tapped button turns red, and the appropriate result is shown in the result label. The user should be able to guess multiple times, and each time the tapped button turns red, all other buttons turn to default tintColor, and the appropriate result is displayed.</li>

 <li>If the user taps the Next button, then the next question in the quiz array is displayed as described in 7b. If Next is tapped on the last question, then the display should cycle back to the first question.</li>

</ol>

<ol start="8">

 <li>Be sure that auto layout constraints are set so that the view elements are appropriately displayed with no overlap regardless of device orientation. You may have to reduce the vertical spacing between the various elements of the view to make everything fit in landscape orientation.</li>

</ol>




StoryBoard:










Simulator:









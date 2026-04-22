# 12-1-Processing-a-quiz-with-jQuery

## Video

[Video](https://youtu.be/vmSyZc8vIZE) <-- Make sure to watch this video first<br>

## Directions

### Step #1 - Add the event listener <br>

You're going to make this quiz interactive with JS & jQuery. In this first step, add an event listener to the form's 'submit' event.
<br><br>
_Hint:_<br>`$("#trivia-form").on("submit",function(event){`<br>
`event.preventDefault();`<br>
` `<br>
` `<br>
`});`
<br><br>
### Step #2 - Check user answer <br>
In this step, you should add code that figures out what answer the user picked and tells them if they got it right by outputting a message in the `#result` div.
<br><br>
_Hint:_<br>`var $answer = $("#trivia-answer");`<br>
`var answer = XXXXX.val();`<br>
` `<br>
`if (YYYYY == 'hall') {`<br>
`  $('#result').text(ZZZZZ);`<br>
`}`
<br><br>
### Step #3 - Show the result <br>
Now, let the user know when they got it wrong, by adding an else that outputs a message in the '#result' div.
<br><br>
_Hint:_<br>`if (_ == 'hall') {`<br>
`...`<br>
`} else {`<br>
`  ...`<br>
`}`
<br><br>
### Step #4 - Show the result <br>
Select the right answer and click the button. Are you outputting a message to the screen? Once it's working, you can spin it off and add more questions, since you know so much about jQuery now!
<br><br>



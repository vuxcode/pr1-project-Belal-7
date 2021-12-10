# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.


One of the problems that I had was that my code didn’t show in the main screen, it only showed in console. 

Another problem I had was that the button I use didn’t disable, that mean that the user could press the same button/letter more than once. But I fixed with some help with this code. 
“document.getElementById(char).disabled = true”
My code didn’t really work in the beginning, the letters didn’t show in the screen and in the right place for the word. So after doing some research and getting help, I managed to make the project work. I have used this code to solve this problem. 
“for (var i =0; i< answer.length; i++){
    console.log(answer[i]);
   if (char == answer[i]){
   guess[i] =char;”


after my code started to work at like 80% and I saw that it was almost done and I after trying it, I come up with an idea of making a “Restart” button, because I saw that when the player win or lose the code kind of ended and nothing happened, so I decides to add a restart button so that the player could restart the page when they are done guessing the word.  

Now I have a problem that the game does not end with the player have guessed the word or if they have run out if the lives, that means that they can still press the unpressed button even if they have guessed the word in like 10 letters. So I need to make the game end. 


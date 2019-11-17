# Rock-Paper-Scissors
TheOdinProject "Rock-Paper-Scissors"

//
Realised I did not return a value from fuction "computerPlay". Value was undefined.

//
Added game logic. Realised logical or operators in "if statements" need to be put in parentheses.

//
Fixed the "playerInput" function. Logical expression was used incorrectly.
Old: if (playerChoice === "rock" || "paper" || "scissors" ))
New: if (playerChoice === "rock" || playerChoice === "paper" || playerChoice === "scissors" )

playerInput was always returned even if false because second and third string were only evaluated as "true".

//
Finished game logic. 

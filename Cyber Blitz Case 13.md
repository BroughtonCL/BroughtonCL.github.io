# Test Case 13 - Functions test of the game in the Asian Arena (scene 06_AsianArena) - Camera, Character, Controll, animations and sound for both user game controller controlled characters, two and four player modes.
### Team_E(xcellence) G. Broughton, B. Heath, T. Womack
### 10/24/2017
### Ver 0.8
* Test Case ID:
  * 013
* Test Case Name:
  * Test Case 013 - Functions test of the game in the Song Shu Street Arena (scene 06_AsianArena) - Camera, Character, Controll, animations and sound for both user game controller controlled characters, two and four player modes.
* Component: 
  * Game Scene Song Shu Street Arena - 06_AsianArena
* Test Case Designer:
  * Travis Womack
* Creation Date:
  * 10/17/2017
* Modified By:
  * B. Heath, T. Womack
* Modified Date:
  * 10/24/2017
* Requirements Covered:
  * Display of starting animation
  * Display of 2 player UI in 2 player mode
  * Display of 4 player UI in 4 player mode
  * Avatar control by user with generic x box controller
  * Avatar can pickup ball
  * Avatar can throw ball
  * Avatar can catch ball
  * Avatar 'died' when hit
  * Covers Neon ball interactions only
  * Use of generic x box controller for one controller
* Test Description/Purpose:
  * Display of starting animation after loading scene
  * Display of 2 player UI in 2 player mode after start animation completes
  * Display of 4 player UI in 4 player mode after start animation completes
  * Avatar control by user with generic x box controller - Left joy stick D-Pad for movement, X to dodge, A pickup catch, Right bumper - 'charge' throw.
  * Avatar controlled by by computer
  * Avatar can pickup ball
  * Avatar cannot 'steal' ball
  * Avatar can throw ball
  * Avatar can only throw ball in attack area
  * Avatar has Orange X at base if Unable to attack
  * Avatar can catch ball
  * Avatar 'dies' when hit
  * Avatar has immunity after 'resurrection'
* Pre-Test Conditions:
  * Current build of the game will run on Windows 7 and 10 in a standalone environment.
  * The PC has both a game controller and mouse attached.
  * Game started normally, user has one or none avatar controlled by key-board mouse, one to four controlled by controllers and one to three controlled by the computer.
  * User has selected Song Shu Street Arena then selected (A button) the 'Blitz>>>' button
## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Select (A) Blitz (Game Setup) or Quick Play (MainMenu) | Display of starting animation after loading scene with music | √ |			
| 2 | End of start animation | Display of 2 player UI in 2 player mode after start animation completes | √ |			
| 3 | End of start animation | Display of 4 player UI in 4 player mode after start animation completes | √ |			
| 4 | Left Joy stick Left or Left on D-pad | Avatar move left while pressed or hits edge or center court  | √ |			
| 5 | Left Joy stick Up or Up on D-pad | Avatar move up while pressed or hits edge | √ |			
| 6 | Left Joy stick Down or Down on D-pad | Avatar move down while pressed or hits edge | √ |			
| 7 | Left Joy stick Right or Right on D-pad | Avatar move right while pressed or hits edge or center court | √ |			
| 8 | Press X button | Plays dodge animation and moves 2 units infacing direction | √ |			
| 9 | Press Right Bumper button | Avatar with ball starts charging holds charge as lon as button pressed | √ |	
| 10 | Release Right Bumper button | Plays throw animation and propells ball in aimed direction | √ |
| 11 | Release Right Bumper button with orange X | Ball does not get thrown - can only throw behind attack line | √ |
| 12 | Press A button | Avatar can pickup ball if close enough and not held by another avatar | √ |			
| 13 | Press A button | Avatar without ball can catch ball if close enough with no hit | √ |			
| 14 | Move mouse | Aiming target moves and aim arrow follows target | √ |			
| 15 | Avatar hit by ball thrown by enemy | Avatar 'dies' (disappears) when hit | √ |			
| 16 | Avatar placed at start point | Avatar has immunity after 'resurrection' does not die if hit within 2 seconds after placement | √ |

## Overall Test Status:
Level loaded-but not able to throw ball, often stuck in idle mode. Pause function did not work, Overall test failed
## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 12/03/2017|G. Broughton III  | Test failed
| 2 | | | |			
| 3 | | | |	


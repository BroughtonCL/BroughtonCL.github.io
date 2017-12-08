# Overview of Test Results for CyberBlitz by the Waffle Group
## Synopsis
We performed a total of 16 test runs on 13 specific test cases, we ran Test Case 9 three times and Test Case 10 twice.  Our testing detected a total of 27 bugs ranging from minor to severe.  The Waffle group has corrected all bugs but one sever bug, the player controllers do not update correctly on the Player Setup panel of the Game Setup scene.  Currently CyberBlitz meets all major current requirements except the Player Controller bug noted above.  Due to the shifting nature of minor requirements not all minor requirements will get met, however; all requirements that existed at the time of testing, except the one noted, did get met and bugs fixed.
## Test Environment
The first version of the game will run on Windows 7 Professional and Windows 10 Home edition, in a standalone environment. The tests will occur on 'builds' downloaded and installed on the test machines. The Waffle Group used the Unity game engine to develop this application and as such provides the drivers to run the game in under Windows 7 and Windows 10.

The testing occurred in an environment using mid-range PCs running either the Windows 7 or Window 10 operating system.

## Recommendations
We strongly recommend that a freeze on all new requirements occur at this time and concentrate on fixing the few remaining bugs at this time.  The project has a due date of December 13 2017 (six days from the date of this report) and not enough time and people exist to implement and test any new requirements.  We further recommend that the bugs get fixed in order as presented in the [Summary of Defects section](#summary-of-defects), with one high priority bug getting attention now from the team.

The programmers will also need to address the 'out of scope' bugs noted in the results of Test Case 11, Test Case 12 and Test Case 13.  These bugs have a normal priority and will get addressed before release.  We recommend the fixing of the low priority bugs only if time permits.

# Detailed Test Results
The team followed the test plan as documented in [GAMEE2338_Test_Plan_Team_E](GAME2338_Test_Plan_Team_E.md).  These tests produced the following results.
### [Test Case 001](Team_E_Test_Case_01.md)
#### Overall Test Status:
Passed 
#### Bugs:
* Main Menu Cyber Blitz appears overall drop downs - minor bug

#### Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 06, Nov. 2017 | T. Womack | Pass with minor bug (see above) |			
#### Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 11/25/17 | T. Womack | Passed this test, will fix bugs found out of this test's scope - HnP: #430, #431, #432 & #433 |

#### Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 06, Nov. 2017 | T. Womack | Pass with minor bug (see above) |			

### [Test Case 002](Team_E_Test_Case_02.md)
#### Overall Test Status:
Passed 
#### Bugs:
* CyberBlitz logo on main menu stays on top of drop down panels - minor bug

#### Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 06, Nov. 2017 | T. Womack | Passed with minor bug see above |			

### [Test Case 003](Team_E_Test_Case_03.md)
#### Overall Test Status:
Passed - no bugs found

#### Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 07-Nov. 2017 | T. Womack | Passed |			

### [Test Case 004](Team_E_Test_Case_04.md)
#### Overall Test Status:
Passed

#### Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 07, Nov. 2017 | T. Womack | Passed |			

### [Test Case 005](Team_E_Test_Case_05.md)
#### Overall Test Status:
* Overall Test Status:
* Passed tests as stated. Failed new requirement to reset to defaults when entering from game play - bug report submitted

#### Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 07, Nov. 2017 | T. Womack | Passed tests as stated - failed new requirement |			

### [Test Case 006](Team_E_Test_Case_06.md)
#### Overall Test Status:
#### Bugs: 
* On quick play selection, Crystal stage default, Maya and Max. Maya picks up ball, and controls freeze. Maya does not charge nor throw the ball. Maya respawns with ball and still cannot throw. Maya drops the ball, with a ball remaining on her head. Orange X does not appear during control freeze. This is caused when Maya catches the ball on the line between the non-throws and throw area. To repeat, place Maya on the line between the throw and non-throw area. The X may or may not appear. Catch the ball from the computer, and eventually Maya's controls with freeze. If the dodge is pressed while this error is occurring, the ball will move 10-20 units away. Maya will still be unable to throw, and when she dodges the ball rotates around with her. Error also occurs if player picks up more than one ball. Maya will throw the extra ball on her head, however the other ball will remain on her head, and charge does not appear. Dodge error implemented creates the flying ball error once more, causing it to follow player for a short period. Wherever the player looks the ball follows. Up to two balls can float around the player. They may or may not respawn. AI will follow the floating balls. Dodging approx. 2-4 times will cause the balls to fly. AI can pick-up flying ball if it is within reach. Maya's Catch state becomes permanent during this error and cannot be killed by AI. Repeatable in ALL stages. Repeatable in ALL players. Players remain in idle animation, hands stay close to the body.

#### Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 11/10/17 | B. Heath | Criteria is met for test, Bugs Discovered need to be addressed |			
| 2 | 11/10/17 | B. Heath | Catch Bug Discovered in Quick Play |			
| 3 | 11/10/17 | B. Heath | Dodge Error, Ball follows player |			
| 4 | 11/10/17 | B. Heath | Multiple Ball Pick-up Freezes controls and creates a floating ball |
| 5 | 11/10/17 | B. Heath | Floating ball error can be up to two balls. Balls may or may not respawn |						
| 6 | 11/10/17 | B. Heath | Unity Bat bot gets pushed by ball, whenever it is picked up |	
| 7 | 11/10/17 | B. Heath | AI can steal ball from player as long as you are in the no-throw zone |	
| 8 | 11/10/17 | B. Heath | Credits Scene does not close out when the close button is pressed |	

### [Test Case 007](Team_E_Test_Case_07.md)
#### Overall Test Status:
#### Bugs: 
* Selecting Random stage, switches between neon and crystal only. Asia stage has been left out. On win for Quick play, "NOBODY WINS" text is displayed. Score does not matter, and text is continuously displayed. On player selection screen, in two player mode, switching the computer to player, causes both characters to be controlled by the player. Characters can throw, grab and die, and they both follow player one's mouse. Player can accidently pick up a secondary ball, if it spawn while they pick up another. This requires good timing but is repeatable. Entering match settings menu for the first time, the cyrstal stage shows on the preview screen. On Pressing blitz, the neon stage is selected. This is a confusing factor. Perhaps add a blank option (or default to random) for on enter to prevent confusion.

#### Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 11/10/17 | B. Heath | Criteria is met for test, Bugs Discovered need to be addressed |
| 2 | 11/10/17 | B. Heath | Asia Stage not Included in Random Stage Selection |	
| 3 | 11/10/17 | B. Heath | Nobody wins is displayed on win by either team |
| 4 | 11/10/17 | B. Heath | Single player can control all characters by switching to user control |
| 5 | 11/10/17 | B. Heath | Multiple Ball-Pick up while picking up another ball |			
| 6 | 11/10/17 | B. Heath | On match settings, default stage is Lumos arena, and when played, default is neon |			

### [Test Case 008](Team_E_Test_Case_08.md)
#### Overall Test Status:
Tested criteria passed bugs found not in this test scope

#### Bugs:
* Settings Panel in pause menu is a dead end. Button Highlights and remains highlighted.

#### Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 11/10/17 | B. Heath | Pause menu settings remains selected and goes nowhere |

### [Test Case 009](Team_E_Test_Case_09.md)
#### Overall Test Status:
Passed with one bug - created HnP bug report #397, settings Panels does not drop when selected from Pause panel

#### Bugs
* 1 bug found Settings Panels does not drop when selected from Pause panel, HnP bug report #397
Run History

#### Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 12 Nov. 2017 | T. Womack | 1 bug found Settings Panels does not drop when selected from Pause panel |			
| 2 | 28/11/2017 | B. Heath | Avatar textures cause "ghost" effects |			
| 3 | 28/11/2017 | B.Heath | On 2v2 win game crashes, no pause menu pop-up |	

### [Test Case 010](Team_E_Test_Case_10.md)
#### Overall Test Status:
Passed - visuals incomplete for level/arena/scene

#### Bugs:
* Settings panel not dropped when selected from pause panel. Settings panel not dropped when selected from pause panel. Button clicks but it does not bring the pop-up in.

#### Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 11/10/17 | B. Heath | Criteria is met for test, Bugs Discovered need to be addressed |
| 1 | 11/30/17 | B. Heath | Win lose requires a panel for score and for quit menu |

### [Test Case 011](Team_E_Test_Case_11.md)
#### Overall Test Status:
Passed all tests on SA NEONDOME arena

#### Bugs
* Found bugs in Settings panel due to new required changes and not yet tested.
* Bug found out of this test's scope - Unable to use controller on settings panel to navigate, set sound or close. HnP #430
* Bug found out of this test's scope - Wrong (old) settings panel drops. HnP #431

#### Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 11/25/17 | T. Womack | Passed this test, will fix bugs found out of this test's scope - HnP #430 & HnP #431 |		

### [Test Case 012](Team_E_Test_Case_12.md)
#### Overall Test Status:
* Passed all tests on LUMUS Arena

#### Bugs
* Found bugs in Settings panel due to new required changes and not yet tested.
* Bug found out of this test's scope - Unable to use controller on settings panel to navigate, set sound or close. HnP #430
* Bug found out of this test's scope - Wrong (old) settings panel drops. HnP #431
* Bug found out of this test's scope - Pause Panel does not allow navigation or button selection with the controller. HnP #432
* Bug found out of this test's scope - Unable to close Help panel with controller in arena scenes.  HnP #433

#### Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 11/25/17 | T. Womack | Passed this test, will fix bugs found out of this test's scope - HnP: #430, #431, #432 & #433 |

### [Test Case 013](Team_E_Test_Case_13.md)
#### Overall Test Status:
Passed all tests on SONG SHU STREET Arena

#### Bugs
* Found bugs in Settings panel due to new required changes and not yet tested.
* Bug found out of this test's scope - Unable to use controller on settings panel to navigate, set sound or close. HnP #430
* Bug found out of this test's scope - Wrong (old) settings panel drops. HnP #431
* Bug found out of this test's scope - Pause Panel does not allow navigation or button selection with the controller. HnP #432
* Bug found out of this test's scope - Unable to close Help panel with controller in arena scenes.  HnP #433

#### Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 11/25/17 | T. Womack | Passed this test, will fix bugs found out of this test's scope - HnP: #430, #431, #432 & #433 |

# Summary of Defects
* Grouped by severity and then listed by Defect ID.  Defect ID: S, N, L (severity: S- severe, N-normal and L-low), - ### (test case number) - ## (bug number)

| Severity | Defect ID | Description | Associated Test ID or Requirement |
| -------- | --------- | ----------- | --------------------------------- |
| Severe | S-007-03 | Single player can control all characters by switching to user control | Change the controller used to control the avatar to selection |
| Normal | N-005-01 | Failed new requirement to reset to defaults when entering from game play | Go to the default scene (Cave Arena) and play the default match |
| Normal | N-006-01 | Catch Bug Discovered in Quick Play | Go play game in selected arena |
| Normal | N-006-02 | Dodge Error, Ball follows player | Go play game in selected arena |
| Normal | N-006-03 | Multiple Ball Pick-up Freezes controls and creates a floating ball | Go play game in selected arena |
| Normal | N-006-04 | Floating ball error can be up to two balls. Balls may or may not respawn | Go play game in selected arena |
| Normal | N-006-05 | Unity Bat bot gets pushed by ball, whenever it is picked up | Go play game in selected arena |
| Normal | N-006-06 | AI can steal ball from player as long as you are in the no-throw zone | Go play game in selected arena |
| Normal | N-006-07 | Credits Scene does not close out when the close button is pressed | Allow the user to select the arena to play |
| Normal | N-007-01 | Asia Stage not Included in Random Stage Selection | Allow the user to select the arena to play |
| Normal | N-007-02 | Nobody wins is displayed on win by either team | Go play game in selected arena |
| Normal | N-007-04 | Multiple Ball-Pick up while picking up another ball | Go play game in selected arena |
| Normal | N-007-05 | On match settings, default stage is Lumos arena, and when played, default is neon | Display the selected arena, selected match time and selected balls |
| Normal | N-008-01 | Pause menu settings remains selected and goes nowhere | Bug out of test case scope |
| Normal | N-009-01 | Settings Panels does not drop when selected from Pause panel | Bug out of test case scope |
| Normal | N-009-02 | Avatar textures cause "ghost" effects | Avatar 'dies' (disappears) when hit |
| Normal | N-009-03 | On 2v2 win game crashes, no pause menu pop-up | Display of 4 player UI in 4 player mode after start animation completes |
| Normal | N-010-01 | Win lose requires a panel for score and for quit menu | Bug out of test case scope |
| Normal | N-011-01 | Unable to use controller on settings panel to navigate, set sound or close | Bug out of test case scope |
| Normal | N-011-02 | Wrong (old) settings panel drops | Bug out of test case scope |
| Normal | N-012-01 | Unable to use controller on settings panel to navigate, set sound or close | Bug out of test case scope |
| Normal | N-012-02 | Wrong (old) settings panel drops | Bug out of test case scope |
| Normal | N-012-03 | Pause Panel does not allow navigation or button selection with the controller | Bug out of test case scope |
| Normal | N-012-04 | Unable to close Help panel with controller in arena scenes. | Bug out of test case scope |
| Normal | N-013-01 | Unable to use controller on settings panel to navigate, set sound or close | Bug out of test case scope |
| Normal | N-013-02 | Wrong (old) settings panel drops | Bug out of test case scope |
| Normal | N-013-03 | Pause Panel does not allow navigation or button selection with the controller | Bug out of test case scope |
| Normal | N-013-04 | Unable to close Help panel with controller in arena scenes. | Bug out of test case scope |
| Low | L-001-01 | Main Menu Cyber Blitz appears overall drop downs | Main Menu and all buttons function |
| Low | L-002-01 | CyberBlitz logo on main menu stays on top of drop down panels | Main Menu and all buttons function |

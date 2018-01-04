# Kinder-Gator
Description
---------
This is the Kinder-Gator motion dataset. The data set contains the motion of untrained actors (10 adults and 10 children) performing 58 different actions tracked using the Kinect v1.0.  This is an anonymized dataset for use in animation and whole-body recognition and interaction. The motions in the dataset have been categorized to consider motions that are easy to perform and used in day-to-day activities (warm-up), motions that induce exertion when performed and are commonly used in exercise and fitness activities (exercise), motions that involve the conceptualization of imaginary objects (mime), and motions that are used to convey information to other people (communication). 

Demographics
------------
ChildID     Sex     Age     Handedness    Grade       ||        AdultID     Sex     Age     Handedness    EducationCompleted
______________________________________________________________________________________________________________________________
290         M       6       R             K           ||        934         M       32      R             Grad
644         F       9       R             4           ||        970         M       28      R             Grad
723         M       8       R             3           ||        734         M       22      R             Undergrad
106         M       6       R             K           ||        921         M       26      L             Undergrad
474         F       6       R             1           ||        888         F       25      R             Grad
337         F       5       B             Pre-K       ||        976         M       20      R             Some college
595         M       5       B             Pre-K       ||        876         F       23      R             Undergrad
103         F       8       R             3           ||        604         F       20      R             Some college
342         F       6       R             K           ||        565         F       19      R             High school
169         M       8       R             2           ||        577         F       19      R             Some college

Motion Set
-----------
Warm-up                     Exercise                              Mime                                    Communication
____________________________________________________________________________________________________________________________________
Raise your hand             Put your hands on your hip            Push an imaginary button in front       Point at the camera
                            and lean to the side                  of you     
Raise your other hand       Put your hands on your hips and       Swipe across an imaginary screen in     Motion someone to stop
                            lean to the other side                front of you                                                
Wave your hand              Put your hands on your hips and       Swipe across an imaginary screen in     Motion someone to come here
                            twist back and forth                  front of you with your other hand
Wave your other hand        Touch your toes                       Fly like a bird                         Draw a (circle, square,                                                                                                                 Triangle) in the air
Bow                         Do a forward lunge                    Fly like an airplane                    Draw the letter (A, C, K, M,                                                                                                             X) in the air
Raise your arm to           Lift your leg to one side             Swim                                    Make the letter (Y, M, C, A, one side                                                                                                  K, P, T, X] with your body
Raise your other arm to     Lift your other leg to the            Kick a ball
the other side              other side
Bend your knee              Walk in place                         Kick a ball as hard as you can
Bend your other knee        Walk in place as fast as you can      Kick a ball with the other leg
                            Run in place                          Kick a ball as hard as you can with that leg
                            Run in place as fast as you can       Throw a ball
                            Jump                                  Throw a ball as far as you can
                            Jump as high as you can               Throw a ball with your other arm
                            Do five jumping jacks                 Throw a ball as far as you can with that arm
                                                                  Punch
                                                                  Climb an imaginary ladder
                                                                  
Data Collection
-----------------
Every participant performed 58 motions for a total of 1159 trials (58 motions x 20 participants); motion trial for jump high for AdultID:565 is missing due to a software error. Participants were allowed to perform the motions in free-form to ensure that the motions are as natural as possible. However, an example of the motion was demonstrated to participants if they forgot how the motion was to be performed. Motions were demonstrated for 4 child participants (11 actions) and 2 adult participants (2 actions): (Child IDs: 106 (2 actions - forward lunge, put your hands on your hip and lean to the side), 290 (6 actions - raise your arm to one side, bend your knee, swipe across an imaginary screen in front of you, fly like a bird, point at the camera, forward lunge), 337 (4 actions - bend your knee, lift your leg to one side, make the letter (M, K) with your body), 342 (2 actions - make the letter (A, K) with your body) and Adult IDs: 888-(1 action - forward lunge), 921-2 actions (forward lunge, make the letter M with your body)).

Data Format
-----------------
Data in the dataset has been labeled according to the category of the participant (child, adult). Within each category, the data has been labeled in the form of "POSE-PID_motion#-motionName-Timestamp.csv." PID is the participant id which is unique for each participant. motion# is the number of the motion labeled 01--58 according to the order the motion was performed. motionName is the name of the motion being performed. Timestamp is the UNIX timestamp representing the date and time the motion was performed. 



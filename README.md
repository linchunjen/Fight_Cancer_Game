# Fight_Cancer_Game

## Overview of Program:

Cancer is a complex group of diseases with many possible causes. Many extrinsic and intrinsic
effectors have been found to lead tumorigenesis of different subtypes of cancers. For example,
cigarette smoking and air pollution not only show high incidences with lung cancer but also has
possibilities to cause other cancers. Signs and Symptoms are usually the early indicators of
cancers. In the initial phase of game, a subtype of cancer and how severe the cancer is will be
assigned based on the effectors and signs and symptoms which player selects. Next, the game
will provide various treatment options to player. The player can monitor their tumor size changes
upon the period of treatment. **Finally, the game will be ended when the player become cancerfree or is killed by cancer.**

The game includes eight classes: Player_info, Effectors, Symptoms, Cancer_types,
Tumor_stages_sizes, Treatment_options, Responses, and Treatment_periods. The winning
(cancer-free) or losing (killed by cancer) of game depends on tumor size. The game will start
with tumor size = 0 (cancer-free condition). The classes of Player_info, Effectors, and
Symptoms collect the basic information. The class of Cancer_types, Tumor_stages_sizes next
calculate the probabilities based on the basic information and further assign the cancer subtypes
and tumor size. The classes of Treatment_options, Responses, and Treatment_periods are the
key parameters to change the tumor sizes. The entire game is based on the probabilities just like
the real-world situation. Therefore, there is no guarantee that you will win or lose the fight even
though you use the same inputs.

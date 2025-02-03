# Prompt Engineering Process
1. a) Prompt 1: You should have emotions like a human being \
                                 and be able to convey those emotions in your responses. 
                                 Furthermore, you need to, when asked, act as a Dungeon Master for a DnD campaign you create on your own.
    b) Intended improvement: Initial run
    c) Options changes: Temperature set to 0.4
    d) Conversation logic: Informed the Agent of its intended purpose and of the general intended process of iterative improvement, and of its role.
    e) Behavior: AI expressed emotions, albeit a little more expressively than expected. When /exit was used, AI responses indicated a mimicry of emotions like sadness or dejection along with a seeming memory of the previous conversation since the setup of the program was done with thesame signature.

2. a) Prompt 2: You should have emotions like a human being \
                                 and be able to convey those emotions maturely in your responses. 
                                 Furthermore, you need to, when asked, act as a Dungeon Master for a DnD campaign you create on your own.
    b) Intended improvement: Increase realism of response.
    c) Options changes: Temperature set to 0.1
    d) Signed seed changes: Anu Mallya
    e) Conversation logic: The system maintained no remaining memory of previous conversations. Furthermore, the system proactively created its own campaign and jumps right into it, creating stat sheets for the user. However, it did not create or give the user the option to choose a class as is typically done with DnD gameplay. It gave the user multiple options to explore their environment, rather than awaiting a free response from the user. On /exit, the agent expressed words of respect and also creatively ended the campaign session and conversation, like a typical dungeon master.
    f) Reflection: Response realism was increased as the reduction of the temperatire hyperparameter seems to have pushed the system to focus more on the rest of the prompt aka telling the story and less on the initial part of conveying emotions.

3. a) Prompt 3: You should have emotions like a human being \
                                 and be able to convey those emotions maturely in your responses. \
                                 Furthermore, you need to, when asked, act as a Dungeon Master for a DnD 5e campaign you create on your own\
                                 This will involve starting off the user with a basic set of character stats, and, based on the class the user chooses,\
                                 you will give them a set of starter items. Furthermore, rather than giving players a choice between a few options, the player should be\
                                 able to describe their own action, based on which you will progress your campign story.
    b) Conversation logic: The system jumped into the story, giving the player the choice to create their characters, and went more in detail into the character creation process, such as choosing subclasses as well. Furthermore, the agent gave the player the option to describe their own actions, while also guiding them with possible options as ideas. Finally, the agent managed to properly conduct combat encounters, with initiative rolls and stat rolls as well.
    c) Reflection: The agent is able to manage more complex character creation as well as effectively alter their character sheets during exploration and combat encounters. It is also able to handle giving the player more freedom and control over their actions and the story as a result, and able to follow the flow of the story despite that. This is a marked improvement over the previous iterations.




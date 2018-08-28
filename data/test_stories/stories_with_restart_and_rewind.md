## simple_story_without_checkpoint
* simple
    - utter_default
    - action_restart
    - restart
    - utter_greet
* hello
    - utter_greet

## simple story with rewind
<!-- this isn't actually a proper story, as the utter action never --> 
<!-- emits this event - but this is just used to test if the story -->
<!-- file reader properly reads this -->
* simple
    - utter_default
    - rewind     
    - utter_greet
* hello
    - utter_greet

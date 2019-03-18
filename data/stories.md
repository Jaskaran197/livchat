## story_greet <!--- The name of the story. It is not mandatory, but useful for debugging. --> 
* greet <!--- User input expressed as intent. In this case it represents users message 'Hello'. --> 
 - utter_name <!--- The response of the chatbot expressed as an action. In this case it represents chatbot's response 'Hello, how can I help?' --> 
 
## story_goodbye
* goodbye
 - utter_goodbye

## story_thanks
* thanks
 - utter_thanks
 
## story_ask_details_01
* greet
 - utter_name
* name
 - utter_greet
* design_house
 - utter_size_of_house
* house_size
 - utter_which_room
* room_type
 - utter_what_budget
* budget
 - utter_details
* thanks
 - utter_thanks


## story_name
* name
 - utter_greet
 

## story_joke_01
* joke
 - action_joke
 
## story_joke_02
* greet
 - utter_name
* name{"name":"Lucy"} <!--- User response with an entity. In this case it represents user message 'My name is Lucy.' --> 
 - utter_greet
* joke
 - action_joke
* thanks
 - utter_thanks
* goodbye
 - utter_goodbye 
## Generated Story 8943337774848021049
* greet
    - utter_name
* name{"name": "jashan"}
    - slot{"name": "jashan"}
    - utter_greet
* design_house
    - utter_size_of_house
* house_size{"house_size": "2 bhk"}
    - slot{"house_size": "2 bhk"}
    - utter_which_room
* room_type{"room_type": "dining room"}
    - slot{"room_type": "dining room"}
    - utter_what_budget
* budget{"budget": "3 lakhs"}
    - slot{"budget": "3 lakhs"}
    - utter_details

## Generated Story 3730510446640481125
* greet
    - utter_name
* name{"name": "anudeep"}
    - slot{"name": "anudeep"}
    - utter_greet
* design_house
    - utter_size_of_house
* house_size{"house_size": "3BHK"}
    - slot{"house_size": "3BHK"}
    - utter_which_room
* name{"room_type": "living room"}
    - slot{"room_type": "living room"}
    - utter_what_budget
* budget{"budget": "1 lakh"}
    - slot{"budget": "1 lakh"}
    - utter_details


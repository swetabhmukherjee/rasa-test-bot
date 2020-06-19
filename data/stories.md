## search restaurant 
* greet
  - utter_greet
* restaurant_search
  - utter_ask_for_restaurant
* look_for_restaurant
  - action_search_restaurant

## search restaurant with location
* greet
  - utter_greet
* look_for_restaurant{"type":"Indian"}
  - action_search_restaurant

<!-- 
## search for restaurant direct
* greet
  - utter_greet
* restaurant_search
  - utter_ask_for_restaurant
* look_for_restaurant
  -  -->


<!-- ## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
 -->
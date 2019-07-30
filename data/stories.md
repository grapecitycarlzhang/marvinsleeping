## start chat
* start_chart
  - utter_show_image

## describe sleeping
* describe_image
  - utter_wake_up_sleep

## describe inbed
* describe_image
  - utter_wake_up_bed

## affirm wake up
* affirm
  - utter_wake_up_done

## deny wake up
* deny
  - utter_wake_up_dont

## do wake up
* say_wake_up
  - utter_breakfast

## dont wake up
* say_shhh
  - utter_long_time_sleep


## happy path
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

## start chat
* start_chart
  - utter_show_image

## describe sleeping
* describe_image_sleep
  - utter_wake_up_sleep

## describe inbed
* describe_image_bed
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

## Generated Story -1709340784538231723
* start_chart
    - utter_show_image
* describe_image_sleep
    - utter_wake_up_sleep
* affirm
    - utter_wake_up_done
* say_wake_up
    - utter_breakfast

## Generated Story 5306895972436041521
* start_chart
    - utter_show_image
* describe_image_sleep
    - utter_wake_up_sleep
* deny
    - utter_wake_up_dont
* say_shhh
    - utter_long_time_sleep

## Generated Story -3057297357272351991
* start_chart
    - utter_show_image
* describe_image_bed
    - utter_wake_up_bed
* affirm
    - utter_wake_up_done
* say_wake_up
    - utter_breakfast

## Generated Story -1932963992394742121
* start_chart
    - utter_show_image
* describe_image_bed
    - utter_wake_up_bed
* deny
    - utter_wake_up_dont
* say_shhh
    - utter_long_time_sleep

## Generated Story -8664015482771728926
* start_chart
    - utter_show_image
* describe_image_sleep
    - rewind
* describe_image_sleep
    - utter_wake_up_sleep
* deny
    - utter_wake_up_dont

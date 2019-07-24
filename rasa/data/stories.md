## happy path
* greet
 - utter_greet
* mood_great
  - utter_happy
  - utter_ask_name

## get name
* say_name
  - action_get_name
  - utter_name
  - utter_service

## sad path 
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_ask_name


## say goodbye
* goodbye
  - utter_goodbye

## recruitment
* recruitment
  - utter_recruitment

## get services
* products
  - utter_products
* want_product
  - utter_when
* say_when
  - utter_how_many
* how_many
  - utter_your_company
* say_company OR say_name
  - utter_will_update
* say_phone OR say_email
  - utter_thanks
  - utter_extra

## get job
* get_job
  - utter_job
  - utter_extra

## get internship
* internship
  - utter_happy
  - utter_internship_department

## get internship data science
* intern_data_science
  - utter_intern_ds
  - utter_qualification
* qualification
  - utter_grade
* grade
  - utter_ask_email
* say_email
  - action_get_email
  - utter_ask_phone
* say_phone
  - action_get_phone
  - utter_wait
  - utter_extra

## get internship sales
* intern_sales
  - utter_intern_sa
  - utter_qualification
* qualification
  - utter_grade
* grade
  - utter_ask_email
* say_email
  - action_get_email
  - utter_ask_phone
* say_phone
  - action_get_phone
  - utter_wait
  - utter_extra

## get internship marketing
* intern_marketing
  - utter_intern_ma
  - utter_qualification
* qualification
  - utter_grade
* grade
  - utter_ask_email
* say_email
  - action_get_email
  - utter_ask_phone
* say_phone
  - action_get_phone
  - utter_wait
  - utter_extra

## get training
* get_training
  - utter_happy
  - utter_training

## seminars & workshops
* seminar
  - utter_seminar_types
* seminar_types
  - utter_ask_email
* say_email
  - action_get_email
  - utter_ask_phone
* say_phone
  - action_get_phone
  - utter_wait
  - utter_extra

## premium internships
* premium_internship
  - utter_happy
  - utter_internship_department

## general info
* general_info
  - utter_general_info

## ask question
* question
  - utter_question
* question
  - utter_alright

## about us
* about_us
  - utter_about_us
  - utter_back

## back to start
* to_start
  - utter_service

## location & hours
* location_and_hours
  - utter_loc_hrs
  - utter_back 

## our_values
* our_values
  - utter_values
  - utter_back

## contact info
* contact_info
  - utter_contact_info
  - utter_back

## case studies
* our_projects
  - utter_projects
  - utter_back

## say bye
* grateful
  - utter_welcome

## back one step
* step_back
  - action_back
  - action_listen

## finished
* done
  - utter_thanks
 




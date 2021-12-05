## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy
  
## sad path 1
* greet
  -utter_greet
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
  - utter_googbye
  
## bot challenge
* bot_challenge
  - utter_iamabot
  - utter_capabilities
  - utter_help
  - utter_solve
  - utter_superpowers
  - utter_other_things
  
## query path 1
* bot_query
  - utter_contact
  - utter_confirm
  - utter_reject
  - utter_area_domains
  - utter_size
  - utter_purpose
  - utter_skills
  - utter_email
  - utter_history
  - utter_cater
  - utter_assist
  - utter_motto
  - utter_scale
* affirm
  - utter_agriculture
  - utter_medium_scale
  - utter_sales_marketting
  - utter_Saarthi_mid_company
  - utter_high_scaled_business
  - utter_scales
  - customer_support
  - utter_user_onboarding
  - utter_hospitality
  - utter_automate_customer_service
  
 ## query path 2
* bot_query
  - utter_contact
  - utter_confirm
  - utter_reject
  - utter_area_domains
  - utter_size
  - utter_purpose
  - utter_skills
  - utter_email
  - utter_history
  - utter_cater
  - utter_assist
  - utter_motto
  - utter_scale
* deny
  - utter_ecommerce
  - utter_IT
  - utter_telecommunication_domain
  - utter_small_size
  - utter_startup
  - utter_healthcare
  - utter_banking
  - utter_Lead_generation
  - utter_small_scale

## help path 1
* seek_help
  - utter_help_user
* affirm
  - utter_food_delivery
  - utter_user_onboarding
  - utter_help
  - utter_customer_support

## help path 2
* seek_help
  - utter_help_user
* deny
  - utter_small_scale_business
  - utter_Lead_generation
  - utter_lead_generation
  - utter_small_shop_owner

## appreciation
* appriciation
  - utter_welcome
 
  

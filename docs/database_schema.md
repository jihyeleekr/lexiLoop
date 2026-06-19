vocab
-----
id PK
word
reading
meaning
stage
new_review_date

review_hisotry
--------------
id PK
vocab_id FK -> vocab.id
reviewed_dat
result
previous_stage
new_stage

review_stages
-------------
stage PK
stage_name
interval_days
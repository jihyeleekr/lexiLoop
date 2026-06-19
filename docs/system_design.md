# Correct Answer Logic

If user marks a word as correct:
  - new_stage = min(current_sate +1, max_stage)
  - new_review date = today + interval_days[new_stage]
  - insert review history

# Incorrect Answer Logic

If user marks a word as incorrect:
  - new_stage = max(current_stage - 1, 0)
  - new_review_date = today + interval_days[new_sage]
  - insert review history


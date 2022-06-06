# Wing_span
wingspan bord game| database design, data modeling


1. Design choices:
   1. deep format: easy to maintain, low storage capability and more common approach
   2. Wide format: easier for analytics, Hard to maintian due to number of tables increases.

2. Assumptions:
   transactional tables: Player info, scores tables (summary_score_table, detailed_score_table)
   Operational tables: Birds_table, habitat_table, foods_table
   
3. Schema considerations: here I'm considering star schema format
    1. snowflake schema:
       > less storage
       > more computation and table count 
       > Highly normalized
    3. star_schema: 
      > more storage
      > less computation and table count
      > less normalized
   

# Data Format:

```
{
  'tweetId':, tweet ID
  'tweet':     [
                  tweet String
               ],
  'entities': [
                  [
                      start_position, 
                      end_position, 
                      entity_type
                  ], 
                  [another entity]
                ]
  'relations':   [
                    [
                      start_position_of_head_entity, 
                      end_position_of_head_entity, 
                      start_position_of_tail_entity, 
                      end_position_of_tail_entity,
                      relation_type
                    ],
                    [another relation]
                ]
}
```

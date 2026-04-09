# Sentiment and Intent Labeling Examples

This file contains sample annotations of English reviews with sentiment and intent labels.

## Label schema

- Sentiment:
  - 1 = positive
  - 2 = negative
  - 3 = neutral
- Intent:
  - 1 = statement
  - 2 = query
  - 3 = command

## Examples

1. "The battery life on this phone is amazing, it lasts me two full days."
   - Sentiment: 1 (positive)
   - Intent: 1 (statement)

2. "The support team never answered my emails."
   - Sentiment: 2 (negative)
   - Intent: 1 (statement)

3. "It works."
   - Sentiment: 3 (neutral)
   - Intent: 1 (statement)

4. "Can you help me reset my password?"
   - Sentiment: 3 (neutral)
   - Intent: 2 (query)

5. "Send me the tracking number."
   - Sentiment: 3 (neutral)
   - Intent: 3 (command)

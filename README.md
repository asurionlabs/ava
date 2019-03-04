# Advanced Virtual Assistant (AVA)

AVA is a open-source conversational AI bot. It consists of the following core components:

- Conversational UI - primary interface to the consumer. It can display and process messages, quick replies, carousels, articles, and appointment picker.
- Dialog Engine - engine capable of traversing one or more dialogs, invoking JS code blocks for API calls, analytic events, conditional paths
- Flow Tool - editor to create conversational dialog; debugger to synchronously step through conversation, JS code
- Intent Gateway - natural language understanding engine capable of running both rules and statistical models to determine intent and entities
- Analytics - securely store transcript data, with added meta-data to quickly retrieve specific transcripts that meet one or more events

In addition, it contains the following standalone services:
- Feature Flag - deploy features silently, turn them on when ready to launch
- A/B Framework - simultaneously experiment with two or more dialog sub-flows, to determine which best meets your metrics




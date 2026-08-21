# AMI Basic Conversation Open-Source Gate

Status: investigation-only placeholder. No runtime wiring yet.

Goals:
- preserve existing CTT answer path
- add minimal social conversation intents: greeting, thanks, repeat/simplify
- add context handoff for follow-up simplification
- use only license-cleared open-source training data as reference/input
- do not claim runtime PASS without Galaxy evidence

Candidate source under review:
- RasaHQ/NLU-training-data (Apache-2.0), especially smalltalk intent examples

Safety gates:
- no Production/main changes
- no automatic RAG injection
- CTT facts come only from project truth sources
- unknown/unverified remains unknown

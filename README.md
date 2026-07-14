ITAI1378
# Project Attractor
Team member: Aleksei Polozov

### Tier Selection
Tier 1. I want to build one perfect base system without complex errors. 

### Problem Statement
This internet has much content and many AI pictures. Users can not find interesting people for one specific taste. Text search does not work well. This problem makes people lose time when they search for matching content on different platforms.

### Solution Overview
This project will learn user taste from one small photo folder. It will scan new photos to find matching people. This system will output highlighted people sorted by match probability.

### Technical Approach
I plan to use object detection and segmentation. I will test YOLO with Ultralytics framework to find faces. I will also test SAM 2 model for body shapes.

### Data Plan
* Source: One custom dataset from my saved photos.
* Size: 50 images.
* Labels: Person, Face.

### Success Metrics
* Primary metric: 85 percent accuracy for face detection.
* Secondary metric: Process one crowd photo in under 2 seconds.

### Milestone Plan
| Phase | Plan |
| :--- | :--- |
| Blueprint | Submit this plan and get approval. |
| First Demo | Build first working demo without training. |
| Make It Yours | Add user data and train this model. |
| Package and Present | Test system, record metrics, and submit final project. |

### Risks and Plan B
* Risk 1: Crowd complexity. 
  Plan B: I will check maximum number of people this model can detect.
* Risk 2: Training model details. 
  Plan B: I will watch internet videos and test different Python libraries.

### AI Usage Log
I started one log file in docs/AI_usage_log.md.

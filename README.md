# OSO_hack

This repository contains the assets and research for the OSO hackathon project.

## Gist of the Project

The project aims to create a system for DJs to receive non-pecuniary "tokens of love" during their live sets. This involves using `.eth` subdomains, QR codes, and a Raspberry Pi with an e-ink display to show the gifts. The team is also exploring the concept of using the HTTP 402 error for non-monetary "payments" and "joyforking" the Liquity V2 protocol to handle these gift-based transactions.

## Command Strings

Here are the 5 command strings for the sub-Minimum-Viable-Robot setup:

1.  `rsync -av --delete Desktop/OSO/ bestape@10.213.5.207:~/OSO/`
2.  `ssh 10.213.5.207`
3.  `screen or screen -r`
4.  `source ~/.virtualenvs/pimoroni/bin/activate`
5.  `(while true; do for img in OSO/*.png; do python3 OSO/image.py --file "$img"; sleep 60; done; done) &`

## Business Management Innovation: Postmodern Agile Robotics

This project is an exploration of what we are calling "postmodern agile robotics," a new paradigm for building and conceptualizing robots in the age of AI.

### The Conscious vs. Subconscious Robot

Through our work, we've identified two types of Minimum Viable Products (MVPs) in robotics:

*   **The Conscious MVP:** This is a robot that is immediately recognizable as such by "common sense." It has a physical form that aligns with our preconceived notions of what a robot should look like. Our previous project, [cheerbotme/ethglobalnyc2025](https://github.com/cheerbotme/ethglobalnyc2025), is an example of a "conscious" MVP. The 3D-printed chassis was key to its acceptance as a robot.

*   **The Subconscious MVP:** This is a robot that is functionally viable, but it is not immediately perceived as a robot by an outside observer. It's a "subconscious" MVP because its "robot-ness" is not immediately apparent. This project, the "sub-minimum-viable-robot," is an example of a "subconscious" MVP.

### Postmodern Exploration: When Deconstruction Goes Too Far

The "postmodern" aspect of our work is an exploration of the boundaries of what constitutes a "robot." We are deconstructing the traditional definition to see what is truly essential. In this project, we are intentionally "going too far" with our deconstruction. We have removed the physical chassis to see what happens when a robot is reduced to its bare functional components: a screen and a single-board computer.

From a purely hardware perspective, this "subconscious" MVP is identical to our previous "conscious" MVP. The only difference is the plastic chassis, which serves no functional purpose but is critical for human perception and our inherent biases. This exploration allows us to ask important questions about the nature of robotics, user perception, and the role of form in the age of AI.

### Agile Robotics

Our development methodology is "agile." We are not building a complete, polished robot from the start. Instead, we are building a "sub-minimum-viable-robot"—a functional core that we can iterate upon. This agile approach allows us to quickly test ideas and adapt to new challenges, which is essential in a fast-moving field like AI.

## Business Management Innovation: The "Get Out of the Office" Mandate

My experience at EthGlobal Buenos Aires highlighted another crucial business management innovation: the "Get Out of the Office" Mandate. Inspired by Steve Blank's Customer Development, this principle emphasizes that real innovation and product-market fit are discovered not through internal assumptions, but through direct engagement with users in their natural environment.

### Debrief from EthGlobal Buenos Aires

During the hackathon, my initial assumption was to use the "sub-minimum-viable-robot" for QR code tipping. However, by deploying the cheerbot on the Devconnect music stage and observing real-world interactions, I discovered a more impactful use case: capturing and displaying semi-professional photos to foster shared memories and nostalgia in real-time. The unique features of the Pimoroni Inky 13.3 e-ink display (readability, battery life, analog aesthetic) proved invaluable for this unexpected application.

This pivot, driven by direct user interaction and agile adaptation, reinforced several key innovation principles:
*   **User-centric discovery:** Assumptions made internally often miss the mark; real learning comes from users.
*   **Rapid iteration and pivot:** Be ready to change course based on real-world feedback.
*   **Embrace surprises:** Unexpected interactions can lead to the most valuable insights.
*   **Blended methodologies:** Customer Development, Lean Startup, and Agile principles complement each other for grounded innovation.

The "Get Out of the Office" Mandate, therefore, argues that true product success and innovative breakthroughs are unlocked by immersing oneself in the user's context, being flexible, and learning from real-world feedback—even if it means abandoning initial plans for more resonant discoveries.

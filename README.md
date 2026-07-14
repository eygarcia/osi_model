# OSI Model M01 Simulation

Use ChatGPT as a guided simulation partner to strengthen your understanding of how data moves through the seven layers of the OSI model in the M01 course.

## Learning goal

Practice explaining:

1. what each OSI layer does
2. how each layer adds or removes information
3. how a real message moves from sender to receiver

## ChatGPT simulation prompt

Copy the prompt below into ChatGPT to start the exercise:

> Act as an OSI model simulator for an M01 networking student.
> Guide me through how data travels across all 7 OSI layers.
> For every step:
> - name the layer
> - explain its main job in simple language
> - describe what happens to the data at that layer
> - give one real-world example
> - ask me one short check-for-understanding question before moving to the next layer
> Use clear, beginner-friendly explanations.
> After reaching Layer 1, reverse the process and explain how the receiving device decapsulates the data back up to Layer 7.
> Finish with a short quiz of 5 questions and provide feedback on my answers.

## Suggested M01 activity

Use this scenario:

**"A student sends a message from a laptop to a class discussion platform over Wi-Fi."**

Ask ChatGPT to simulate the trip using this format:

| Layer | What happens to the message? | Example technology |
| --- | --- | --- |
| 7. Application | The user creates and sends the message in the app. | Browser, HTTP |
| 6. Presentation | The message is formatted so both sides understand it. | Encryption, encoding |
| 5. Session | The communication session is created and managed. | Session control |
| 4. Transport | The message is broken into segments and checked for delivery. | TCP, UDP |
| 3. Network | The data is routed toward the destination IP address. | IP, routers |
| 2. Data Link | Frames are created for delivery across the local network. | Ethernet, MAC, Wi-Fi |
| 1. Physical | Bits travel as electrical, radio, or light signals. | Cables, radio waves |

## Follow-up prompts

After the first simulation, try these:

- "Run the same scenario again, but stop after each layer and wait for me to explain it first."
- "Give me a version with mistakes hidden in the explanation so I can find and correct them."
- "Compare how the same message would travel on Wi-Fi versus Ethernet."
- "Create a short role-play where each OSI layer speaks for itself."

## Self-check questions

1. Which layer is responsible for routing?
2. Which layer works with MAC addresses?
3. What is encapsulation?
4. Why is the Transport layer important?
5. What changes when the message reaches the receiving computer?

## Success criteria

You should be able to:

- describe each OSI layer in order
- explain encapsulation and decapsulation
- connect each layer to a real networking example
- answer basic OSI questions without looking at notes

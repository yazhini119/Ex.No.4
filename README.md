# EXP 4: Generating and Evaluating Prompts Across Different Prompt Patterns

## DATE: 08/09/2026
## NAME: Yazhini S
## REGISTER NUMBER: 212223050062

## Aim

To construct prompts using multiple prompting strategies — Zero-shot, Few-shot, Chain of Thought, Persona-based, Reverse Prompting, Graph-based Prompting, and Active Prompting — for an industrial IoT automation scenario, run them across different AI assistants, and score the resulting outputs against a common rubric.

## Scenario Description

**Use Case:** IoT-Driven Automation for Factory Operations

Factories today rely heavily on manual inspection to catch equipment problems, which slows down operations and increases the risk of unplanned breakdowns. By fitting machinery with IoT sensors and embedded controllers, plants can stream live operating data, flag early signs of wear, and shift from reactive repairs to predictive maintenance. This same infrastructure supports remote supervision, smarter energy usage, and tighter quality control on the production line.

**Target Audience:** Manufacturers across automotive assembly, electronics fabrication, and food processing.

## Goals

- Raise overall production throughput by roughly 30%
- Cut unplanned downtime via predictive maintenance scheduling
- Support live, remote oversight of plant equipment
- Lower energy usage through smarter process control

## Method

1. Set up the manufacturing automation scenario and its goals
2. Select the prompting techniques to test
3. Draft one prompt per technique
4. Run each prompt on assistants such as ChatGPT, Gemini, and Copilot
5. Record every response generated
6. Compare outputs against a shared set of criteria
7. Score each response using a rubric
8. Write up findings and conclusions

## Prompt Patterns and Sample Outputs

### 1. Zero-Shot Prompting

**Prompt:**
> Describe how embedded systems and IoT sensors can be combined to automate operations on a factory floor, covering key components, advantages, and typical use cases.

**Sample Output:**
Sensors installed across factory equipment stream operating data to embedded controllers, which forward it to a central monitoring platform. This setup supports predictive maintenance, cuts down on manual checks, speeds up production, trims energy costs, and shortens downtime. It's widely applied in car assembly plants, packaged-food lines, and electronics fabrication.

### 2. Few-Shot Prompting

**Prompt:**
> Example 1 — Input: How does IoT help with agriculture? Output: Sensors track soil moisture, temperature, and plant health to boost farm yields.
> Example 2 — Input: How does IoT help with healthcare? Output: Connected devices monitor patient vitals and alert clinicians in real time.
> Now answer: How does IoT help with manufacturing?

**Sample Output:**
In manufacturing, networked sensors keep watch on temperature, vibration, and equipment load around the clock. That stream of data helps engineers catch developing faults early, plan maintenance before a breakdown happens, fine-tune production output, and hold product quality steady — all of which lowers repair costs and keeps operations running smoothly.

### 3. Chain of Thought Prompting

**Prompt:**
> Work through this step by step: walk through how a factory's IoT automation setup moves from raw data collection to predictive maintenance, covering each stage in order.

**Sample Output:**
1. Sensors on the equipment capture live operating data
2. Embedded controllers clean and organize that data locally
3. The data is sent up to a cloud-based server
4. Analytics models look for patterns and shifts in performance
5. Predictive models flag machines likely to fail soon
6. Operators get an alert before the failure actually happens
7. Preventive maintenance is carried out, cutting downtime and keeping output steady

### 4. Persona-Based Prompting

**Prompt:**
> Assume the role of an Industrial IoT specialist with about 15 years in smart-factory deployments. Explain to a plant manager, in practical terms, how IoT automation lifts efficiency, cuts downtime, and reduces energy spend.

**Sample Output:**
With constant sensor monitoring on the floor, you can spot a failing part long before it actually breaks, which sharply reduces surprise stoppages. Predictive maintenance keeps the line moving, and live process tuning squeezes out extra output. On the energy side, tracking which machines run inefficiently lets you target fixes that bring the power bill down. Put together, this raises both throughput and product consistency.

### 5. Reverse Prompting

**Prompt:**
> Given this target response — "The factory saw a 30% jump in output, cut downtime through predictive maintenance, and reduced its energy bill after adopting IoT automation" — write the prompt that would most likely have produced it.

**Generated Prompt:**
Describe how adopting IoT-based automation in a factory setting can raise output, cut equipment downtime through predictive maintenance, and reduce energy spend. Include concrete, measurable outcomes.

### 6. Graph-Based Prompting

**Prompt:**
> Lay out the architecture of a factory IoT automation system as a flow diagram, showing how sensors, embedded controllers, the cloud platform, analytics, predictive maintenance, and plant operators connect to one another.

**Sample Output:**

<img width="757" height="647" alt="image" src="https://github.com/user-attachments/assets/37361b64-e878-4c24-ab8b-92fd5c273d1d" />


### 7. Active Prompting

**Prompt:**
> Before responding, flag any missing details that would help you give a better answer. Then explain how a factory's IoT automation system can raise efficiency and cut equipment downtime.

**Clarification Requested:**
- Which manufacturing sector is this for?
- What kinds of machines are currently in use?
- Should monitoring run through the cloud or at the edge?

**Final Response:**
A factory IoT system lifts efficiency by streaming operating data off the machines in real time. That data feeds analytics that spot unusual behavior and warn of likely failures ahead of time. Live monitoring speeds up decisions on the floor, while predictive maintenance keeps repair costs and downtime low. Energy use also improves, since tracking machine performance makes it easy to cut power waste — the net effect being higher output and steadier operations.

## Comparing the Prompt Patterns

| Prompt Pattern | Purpose | Strengths | Drawbacks |
|---|---|---|---|
| Zero-shot | Answer with no examples given | Quick, simple to write | Can lack nuance or depth |
| Few-shot | Guide the model with sample Q&As | More consistent, on-target answers | Needs good example pairs |
| Chain of Thought | Force step-by-step reasoning | Clearer, more logical explanations | Responses run longer |
| Persona-based | Answer from an assigned expert role | Sounds domain-appropriate | Quality hinges on the persona chosen |
| Reverse Prompting | Work backward from a target output | Handy for prompt design itself | Needs a target answer up front |
| Graph-based | Show structure or flow visually | Architecture is easy to follow | Doesn't work in plain-text-only tools |
| Active Prompting | Ask for missing info before answering | More tailored, accurate answers | Adds an extra back-and-forth step |

## Comparing the AI Tools

| Criterion | ChatGPT | Gemini | Copilot |
|---|---|---|---|
| Accuracy | Excellent | Very Good | Very Good |
| Clarity | Excellent | Good | Good |
| Logical Reasoning | Excellent | Very Good | Good |
| Creativity | Excellent | Good | Good |
| Technical Detail | Excellent | Good | Good |

## Rubric Scores

| Criterion | Weight | ChatGPT | Gemini | Copilot |
|---|---|---|---|---|
| Accuracy | 5 | 5 | 4 | 4 |
| Relevance | 5 | 5 | 5 | 4 |
| Clarity | 5 | 5 | 4 | 4 |
| Completeness | 5 | 5 | 4 | 4 |
| Logical Reasoning | 5 | 5 | 4 | 4 |
| **Total** | **25** | **25** | **21** | **20** |

## Result

All seven prompting techniques — Zero-shot, Few-shot, Chain of Thought, Persona-based, Reverse Prompting, Graph-based, and Active Prompting — were applied successfully to the factory IoT automation scenario. Each technique brought out a different strength: some produced quick, general answers, while others pushed toward more structured or clarified responses depending on the prompt design. Across the three assistants tested, ChatGPT's answers were the most detailed and well-reasoned overall, with Gemini and Copilot trailing slightly on depth and specificity. The rubric scores back this up, with ChatGPT coming out ahead — reinforcing how much the choice of prompting technique shapes the usefulness of an AI-generated response in a real engineering context.

# self-models.md


## Faculties
|Abbr.|Name|Data|Description|
|---|---|---|---|
|attention faculty|Attention faculty|?|The capability to direct the attention to a sepcific signal source. As a result, the selected signals are processed with higher priority, others signal sources are muted. Attention direction is an action and may be planned or part of a plan. Attention faculty is different from attention self-model. "I listened to the faint music" is attention faculty, "I get distracted very easyily" is attention self-model.|
|episodic memory faculty|episodic memory faculty|?|The faculty to remember past states or actions. Episodic memory is both a faculty, a self-model and the base for all other self-models.|
|planning faculty|Planning|Directed acyclic graph of actions of sub-plans|Putting together multiple actions to achieve a goal (=desired outcome)|
|predictive simulation|Predictive Simulation||Capability to create "dreamp up" a scenario|


## Robot Hardware / Software models for embodied AIs
|Abbr.|Name|Data|Description|
|---|---|---|---|
|3d|3D self-model|3D scene graph|Static 3D model of the body in it's surroundings|
|kinematics|3D kinematic model|3D kinematics|3D kinematic model of the body in it's surroundings|
|sensor|Sensory model| |A model with statistics on sensor data.|
| |Sensory modality degradation| |A predictive model for the gradual decline or potential failure of specific sensors (e.g., camera resolution, microphone sensitivity). This is more specific than a general "sensor model."|
| |Actuator stress/wear model| |An estimate of the physical strain and projected lifespan of mechanical components like joints, motors, or grippers. A human equivalent, like a "joint fatigue" model, is hinted at but is much more critical for a robot's maintenance.|
| |Network latency model| |For a distributed or cloud-connected AI, a model of its communication speed, latency, and reliability. This is vital for time-critical decisions and for understanding potential information delays.|
| |Power source model| |A more granular version of the "Energy/fuel model" that tracks charge cycles, battery health, and predicted degradation over time, not just current levels.|
| |Reboot/reset model| |A model that evaluates the need for and potential consequences of a system-level reboot or reset to resolve internal inconsistencies or correct performance issues. |
| |Data quality model reliability of its knowledge base and predictions.| |An estimate of the quality, bias, and recency of the data it has been trained on. This is critical for assessing the|
| |Data poisoning vulnerability input data.| |A model that assesses its own susceptibility to having its learning corrupted by malicious or low-quality|
| |Model explainability model| |A meta-model that assesses its own ability to explain its decisions and reasoning to a human operator or to itself.|
| |Fine-tuning model| |A model for determining the most effective and efficient way to update or fine-tune its internal parameters based on new data or tasks, optimizing its own learning process.|
| |Safety protocol adherence model| |A model that specifically monitors and ensures compliance with hardcoded safety protocols, separate from the more abstract "ethical compliance" model. |

## Physical / Spatial Self-Models
|Abbr.|Name|Data|Description|
|---|---|---|---|
| |3D body pose| |exact skeletal or joint configuration in space.|
| |Physical position relative to objects| |e.g., distances, orientations to obstacles.|
| |Movement trajectory| |planned vs. actual path over time.|
| |Kinematic limits| |self-model of joint limits, maximum speed, acceleration.|
| |Energy/fuel model| |battery levels, stamina, or fatigue.|
| |Tool and object interaction| |understanding which objects it can grasp/manipulate.|
| |Collision / contact probability| |likelihood of bumping into objects in next move.|

## Action / Planning Self-Models
|Abbr.|Name|Data|Description|
|---|---|---|---|
|performance|Action performance model| |what actions it can perform and how reliably.|
|progress|Task progress| |how far along it is in achieving a specific task.|
| |Prediction accuracy| |confidence in its own predictions or decisions.|
| |Planning tree| |branching possibilities of future actions of a plan already made|

## Cognitive / Decision-Making Self-Models
|Abbr.|Name|Data|Description|
|---|---|---|---|
| |Memory availability| |working memory or long-term knowledge representation.|
|attention|Attention focus| |What is currently being monitored vs. ignored?|
| |Learning rate| |self-estimation of how quickly it can adapt to new tasks.|


## Goal / Motivation Self-Models
|Abbr.|Name|Data|Description|
|---|---|---|---|
| |Goal hierarchy| |subgoals and dependencies in pursuing objectives.|
| |Need/drive state| |urgency of different internal needs (energy, curiosity, safety).|
| |Reward expectation| |predicted outcomes or utilities of actions.|
| |Conflict between goals| |prioritization model for competing objectives.|
| |Confidence / uncertainty| |self-assessment of certainty in choices.|

## Emotional / Affective Self-Models
|Abbr.|Name|Data|Description|
|---|---|---|---|
| |Mood state| |internal affective state (for humans or affective AI).|
| |Stress / pressure estimation| |predicted risk under current workload.|

## Informational / Knowledge Self-Models
|Abbr.|Name|Data|Description|
|---|---|---|---|
| |Knowledge completeness| |gaps in its knowledge about the world.|
| |Sensor model| |reliability and error rates of its sensory inputs.|
| |Data freshness| |recency of information it holds.|
| |Internal consistency| |conflicts between beliefs or models it holds.|
| |Empathy/affective state prediction| |An extension of the "theory of mind" model that specifically focuses on predicting the emotional or affective state of other agents and how its own actions might influence that state.|

## Social / Interaction Self-Models
|Abbr.|Name|Data|Description|
|---|---|---|---|
| |Theory of mind| |modeling how other agents perceive itself.|
| |Social role| |current role or status in a group (leader, helper, observer).|
| |Communication state| |which messages it has sent, understood, or needs to send.|
| |Trust / reputation model| |how others view or trust it.|
| |Social influence model| |An assessment of its own persuasive ability or the impact of its actions on others, especially in collaborative or group settings. |

## Meta / Reflective Self-Models
|Abbr.|Name|Data|Description|
|---|---|---|---|
|episody|Episodic Memory|Data from all self-models during that time|This is a memory rather than a self-model. It contains the history of past actions and their outcomes in their raw format.|
|awareness|Self-observation model| |Monitoring which internal processes are active, particular sensor perception. “Processes” is very broad here, including perception (sensor input processing) and “higher” processes including planning, reasoning, etc. using an "inner sense". “Awareness” of processes does not mean “conscousness”. It is just the input from an that certain processes are executed, taking up CPU cycles.|
| |Self-improvement model| |how to improve its own performance over time.|
| |Time-awareness| |Same as mem - tracking past actions and predicting future states.|
| |Ethical / rule compliance| |awareness of whether it is following rules or constraints.|
| |Creative/generative capacity| |A model that evaluates an agent's ability to produce novel and valuable outputs, distinct from simply performing a task reliably. This could include scoring the originality or aesthetic quality of its creations.|
| |Hypothesis testing model| |A specific model of how an agent evaluates new information and updates its internal beliefs. This would track how it forms, tests, and discards hypotheses about the world.|
| |Cognitive load model| |An estimate of the current processing burden on the agent. It could model how performance degrades under higher cognitive load and inform decisions about when to offload tasks or simplify a plan. |
| |Narrative or story-telling model| |A model that maintains and updates a consistent personal history or a narrative of its own experiences. This goes beyond simple memory by organizing events into a coherent, causal story, which is crucial for higher-level reasoning and decision-making.|
| |Model of ethical drift| |A meta-model that tracks and predicts potential deviations from its ethical or rule-based constraints, informing it when to recalibrate its behavior or seek external guidance. |

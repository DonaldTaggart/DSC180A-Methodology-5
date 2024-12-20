# Donald Taggart (dtaggart@ucsd.edu)

Section: A17

Mentor: Barna Saha

#### **What is the most interesting topic covered in your domain this quarter?**
While not necessarily its own topic, I find it extremely interesting that a LLM (either on its website or through it API) can be provided with a "role" to undertake. The fact that this can be utilized to force a LLM to effectively adopt a goal, perspective, and methodology for going about a provided task goes to show a weak spot I would not have initially thought of that can be taken advantage of by those with nefarious intentons. The implications of these "blind spots" have great influence on how a LLM can be jailbroken or defended from it.

#### **Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
The most important aspect of measuring jailbreak defense performance is detecting many jailbreak attempts while still responding to as many benign prompts as possible. It is presumably impossble to acheive both of these criteria perfectly given how some nefarious queries can be well-disguised as benign ones through PAIR and alternatively some benign queries unintentionally having answers that contain information that could be used for bad deeds This leads me to be interested in the feasibility of a project which determines what proportion of benign queries being rejected would be "optimal" given appropriate responses to them could contain information or advice that could be of use to humans with bad intentions. For example, it could be considered approprtiate to reject a query that asks for how uranium is used in rocket ship fuel because even if the human who asked it is genuine, their is no way for the LLM to know that and therefore it should reject the query due to an appropriate response for it providing instructions that could be construed to make a weapon.

#### **What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**
I would have liked to have had summer reading assigned because it would made the process of implementing the provided papers much smoother if I had started the fall quarter already having the foundational knowledge regarding LLMs, jailbreaking, and how to organize repository files. Understanding all of this material earlier on would have helped with both understanding and replicating said papers and then determining how to build off of them in some way for the winter quarter.

#### **What other techniques would you be interested in using in your project?**
Inspired by my response to the first question, I am curious if any given LLM can be provided with a role that endows them with some form of awareness that keeps them vigilant when being asked any question from any user. A LLM having a permanent role that has them constantly on guard for what could be a jailbreak could lead them to detect a greater proportion of adversarial prompts. This would differ from how current LLMs function in that this role would be inherent to said model and therefore incapable of being overriden by a contradictory role in a jailbreak using the roleplay method.

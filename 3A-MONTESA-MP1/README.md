
**Artificial Intelligence**

Topic List:

Understanding the Artificial Intelligence
Three Domains or Forms of Knowledge
Case Study Selection
Representation Creation

**Understanding Artificial Intelligence**

Artificial intelligence (AI) is the simulation of human intelligence in machines that are programmed to think and act like humans. It is a method of making a computer, a computer-controlled robot, or a software think intelligently like the human mind. AI is accomplished by studying the patterns of the human brain and by analyzing the cognitive process.

**Three Forms of Knowledge Representation**

*1. Logical Representation* <br/>
It is the most basic form of representing knowledge to machines where a well-defined syntax with proper rules is used. This syntax needs to have no ambiguity in its meaning and must deal with prepositions. Thus, this logical form of presentation acts as communication rules and is why it can be best used when representing facts to a machine.

Logical Representation can be of two types:

Propositional Logic: This type of logical representation is also known as propositional calculus or statement logic. This works in a Boolean, i.e., True or False method.

First-order Logic: This type of logical representation is also known as the First Order Predicate Calculus Logic (FOPL). This logical representation represents the objects in quantifiers and predicates and is an advanced version of propositional logic.

If you may or may not have noticed by now, this form of representation is the basis of most of the programming languages we know of where we use semantics to convey information, and this form is highly logical. However, the downside of this method is that due to the strict nature of representation (because of being highly logical), it is tough to work with as it’s not very natural and less efficient at times.

**2. Semantic Networks** <br/>
A semantic network allows you to store knowledge in the form of a graphic network with nodes and arcs representing objects and their relationships. It could represent physical objects or concepts or even situations. A semantic network is generally used to represent data or reveal structure.

In this form, a graphical representation conveys how the objects are connected and are often used with a data network. The Semantic networks consist of node/block (the objects) and arcs/edges (the connections) that explain how the objects are connected. This form of representation is also known as an alternative to the FPOL form of representation. The relationships found in the Semantic Networks can be of two types – IS-A and instance (KIND-OF). This form of representation is more natural than logical. It is simple to understand however suffers from being computationally expensive and do not have the equivalent of quantifiers found in the logical representation.

**3. Productive Rules**
It is among the most common ways in which knowledge is represented in AI systems. In the simplest form, it can be understood as a simple if-else rule-based system and, in a way, is the combination of Propositional and FOPL logics. However, a more technical understanding of production rules can be understood by first understanding what this representation system is comprised of.


This system comprises a set of production rules, rule applier, working memory, and a recognize act cycle. For every input, conditions are checked from the set of a production rule, and upon finding a suitable rule, an action is committed. This cycle of selecting the rule based on some conditions and consequently acting to solve the problem is known as a recognition and act cycle, which takes place for every input. 

This method has certain problems, such as the lack of gaining experience as it doesn’t store the past results and can also be inefficient as, during execution, many other rules may be active. The cost of these disadvantages can be redeemed because the rules of this system are expressed in natural language, where the rules can also be easily changed and dropped (if required).

**Knowledge Representation Model**

*Title: Semantic Network for Medical Diagnosis*

Semantic networks represent knowledge using nodes and edges. In this model, nodes represent medical concepts such as symptoms, diseases, and treatments. Edges represent relationships like “symptom of” or “treated by.”

*How it works?*
Nodes: “Fever,” “Cough,” “Flu,” “Antiviral Medication.”
 
Relationships:
 “Fever” and “Cough” are connected to “Flu” with “symptom of” edges.
“Flu” is connected to “Antiviral Medication” with a “treated by” edge.

This structure shows how symptoms lead to a diagnosis and how the diagnosis can be treated.

*How it helps AI System?*
 The AI can analyze symptoms to diagnose diseases by following the relationships in the network.

 It can recommend treatments based on the diagnosis, improving the accuracy of medical decision-making.
 

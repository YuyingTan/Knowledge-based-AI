# Knowledge-based-AI
Knowledge representation and reasoning

Here I collect key take aways about knowledge based AI with its reference. Note that this is only for the purpose of study. If you have problem openning the .pdf directly, please try downloading the whole zip. All content from the CS227: Knowledge Representation and Reasoning: http://web.stanford.edu/class/cs227/ <br>
人工智慧：搜寻方法与逻辑推论 (Artificial Intelligence - Search & Logic) by Taiwan Evolutionary Intelligence Lab, National Taiwan University

## Object oriented representation 
Marvin Minsky in 1975 suggested the idea of using object oriented groups of procedures to recognize and deal with new situations. Minsky used the term frame for the data structure used to represent these situations. The procedures attached to frames give us a flexible, organized framework for computation. The whole point of object-oriented reasoning is to determine the sort of questions appropriate for a type of object and to design procedures to answer them. <br>
* EXAMPLE: USING FRAMES TO PLAN A TRIP <br>
In this example We will see how the “symbolic spreadsheet” style of reasoning in frame systems is used. This might be particularly useful in supporting the documentation one often uses in a company for reporting expenses. <br>
* Check the document <Object_oriented_representation_EXAMPLE_USING FRAMES TO PLAN A TRIP>

## Inheritance
Hierarchies allow us to avoid repeating representations—it is sufficient to say that “elephants are mammals” to immediately know a great deal about them. Taxonomies of kinds of objects are so fundamental to our thinking about the world that they are found everywhere, especially when it comes to organizing knowledge in a comprehensible form for human consumption, in encyclopedias, dictionaries, scientific classifications, and so on.<br>
Key points of this part: <br>
* strict inheritance network - directed acyclic graph (DAG)<br>
* defeasible Inheritance <br>
* strategies for defeasible inheritance: Shortest Path Heuristic; Inferential Distance; Extension (belief sets) of ambiguous networks; credulous reasoning; skeptical reasoning <br>

Inheritance networks, as described in the text, grew out of a more general-purpose representation formalism that used inheritance, known as semantic networks. Early and influential work in this area, inspired by the semantics of verbs and nouns in natural language, was done by Quillian and, for the application of computer vision, Winston. <br>
Extend paper reading: <OKBC: A Programmatic Foundation for Knowledge Base Interoperability>

## Probem solving agents and search algorithms
A simple problem-solving agent formulates a goal and a problem, search for a sequence of actions that solves the problem, and then execute the actions one by one. Summary of the part:<br>
Problem formulation usually requires abstracting away real-world details to define a state space that can feasibly be explored.<br>
Initial state<br>
Actions<br>
Transition model<br>
Goal test<br>
Path cost<br>
Graph search can be exponentially more efficient than tree search, but it takes more memory space.<br>
Variety of uniformed search strategies judged on the basis of <br>
Completeness<br>
Optimality<br>
Time and space complexity<br>
The DFS can be linear space complexity efficient, but it cannot guarantee completeness. IDS make use of the DFS linear space speciality, and use not much more time than other uninformed algorithms but it cannot guarantee completeness.  


# pysychological-analysis
pysychological analysis of behaviour of children using semi structured , hierarchical JSon dataset

The dataset represents the answers from children to different questions. Each question is a multiple choices one: 4 propositions,
children have to find the right one. The children are performing 20 minutes sessions of work. We give children questions we choose so they have an
estimated 0.8 probability of answering correctly, in expectation. An answer contains:

- the answering time
- the correctness of the answer
- the date (relatively to a session) of the answer

The dataset is an array, each element representing a child (30 children). Each child is an array of sessions (10 sessions per child)
Sessions are arrays of answers (and an answer is an object). Sessions are 20 minutes each. All times are in hundredth of seconds.

1- Some children seem to have an abnormal answering pattern, according to the probability of answering correctly we expect. Identify, qualify and interpret this pattern. 

2- Are answering time and answer correctness correlated, in the case of a normal answering pattern ?

3- We'd like not to take abnormal answering pattern into account. Give several strategies, with or without implementing them, allowing to detect algorithmically the
answers we suspect to pertain to the abnormal pattern 

4- For a child that do not show abnormal patterns, identify the periodicity in correctness & answering time.

5- Compare this periodicity to the one of a child showing abnormal patterns. Model and interpret the alternation between normal and abnormal pattern. 

The goal for us is to identify your capacity of analysis on a new kind of problem, on a dataset that is similar to what we
face!

==================================================

These are the tasks for senseval 2.  Each task is either a lexical sample or an
all words task.  The tasks have a layout of
<taskname>/{key,sensemap?,answers,systems,trial,train,test} In the key file,
the answer key for the task is provided.  The sensemap file contains the the
subsumption map for the scorer.  The answers directory contains the submitted
answers for a given username and system.  The name of the answers file is
<user>-<system> where <system> may be blank. The trial directory contains the
distributed trial data.  The train directory contains the distributed training
data, and the test directory contains the distributed testing data.  The
systems directory contains a directory for each answer file, and the scoring
output and error reports for each system at each available and meaningful
granularity. 


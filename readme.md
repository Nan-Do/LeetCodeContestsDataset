The dataset description:   

   - The dataset is composed by submissions to [Leetcode's contests](https://leetcode.com/contest/).
     - This data is of public access.
   - For each contest, the first accepted solution for some popular languages is taken
     - In this way, we can be sure that the source code is warranted to be correct.
   - In total, there are 4666 unique submissions and 916 unique problems: 
     - Up to contest weekly-348.
     - Up to contest biweekly-105
     - The idea is to update keep it updated with latest contests.
     - This readme won't probably be updated when that happens.
   - The included languages are:
     - C, C++, Java, JavaScript, Python 2, Python 3, Rust.
   - The dataset has been cleaned to ensure formatting consistency and the correctness of the present numerical values.
   - The dataset is in instruction, input, and output JSON format.
   - The files have been updated to the jsonlines format

Files:
  - submissions.jsonl: Contains the submissions as explained above.
   
Deprecated File: (This files may or not may exist on the repo)
  - submissions_py.json: Only python submissions, it doesn't follow the Llama format, 10 submissions per problem.
  - submissions_py_llama.json: Same as above but following the Llama input format
  - submissions_py_llama_small.json: Same as above but with 3 submissions per problem.



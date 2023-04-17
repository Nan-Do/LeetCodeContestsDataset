The dataset description:   

   - The dataset is composed by submissions to [Leetcode's contests](https://leetcode.com/contest/).
     - This data is of public access.
   - For each contest, the first accepted solution for some popular languages is taken
     - In this way, we can be sure that the source code is warranted to be correct.
   - In total, there are 4535 unique submissions and 895 unique problems: 
     - Up to contest weekly-340.
     - The idea is to update keep it updated with latest contests.
     - This readme won't probably be updated when that happens.
   - The included languages are:
     - C, C++, Java, JavaScript, Python 2, Python 3, Rust.
   - The dataset has been cleaned to ensure formatting consistency and the correctness of the present numerical values.
   - The dataset is in instruction, input, and output JSON format.

Files:
  - submissions.json: Contains the submissions as explained above.
  - submissions_py.json: Only python submissions, it doesn't follow the Llama format, 10 submissions per problem.
  - submissions_py_llama.json: Same as above but following the Llama input format
  - submissions_py_llama_small.json: Same as above but with 3 submissions per problem.



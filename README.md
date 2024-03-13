![Screenshot (93)](https://github.com/g0lgi/exercise-profiling/assets/119854906/a44d96d3-ba26-4f94-900e-8d8135ab03fe)
![Screenshot (95)](https://github.com/g0lgi/exercise-profiling/assets/119854906/6492a51e-0be7-425b-a6c5-5cf164df4702)
![Screenshot (96)](https://github.com/g0lgi/exercise-profiling/assets/119854906/7dbb5fd7-dc92-44eb-922f-824c96f8a003)
![Screenshot (97)](https://github.com/g0lgi/exercise-profiling/assets/119854906/42d50004-34bd-4187-85ac-7acfad856c1a)
![Screenshot (98)](https://github.com/g0lgi/exercise-profiling/assets/119854906/ce0810a7-2358-4603-ad52-c6f83ba714b3)
![Screenshot (99)](https://github.com/g0lgi/exercise-profiling/assets/119854906/5bdcae07-d9d9-40df-aded-30fe98a89221)
![Screenshot (100)](https://github.com/g0lgi/exercise-profiling/assets/119854906/010f31dc-03ed-469a-ba6a-150870bf6479)
![Screenshot (101)](https://github.com/g0lgi/exercise-profiling/assets/119854906/011ed2c9-ed82-4747-9343-232e252569d9)
![Screenshot (102)](https://github.com/g0lgi/exercise-profiling/assets/119854906/1932e09d-8102-4d7b-8b8d-567f98bb1d0e)
![Screenshot (103)](https://github.com/g0lgi/exercise-profiling/assets/119854906/703aa068-e57d-4769-ad35-7304334030b2)
![Screenshot (105)](https://github.com/g0lgi/exercise-profiling/assets/119854906/65f9f062-cf9f-4b24-b869-49c353041a51)
![Screenshot (106)](https://github.com/g0lgi/exercise-profiling/assets/119854906/3f04fd0f-6545-4d01-9001-f63b421c04dc)

1. Performance testing with JMeter simulates real-world load on my application to identify bottlenecks under stress, while profiling with IntelliJ Profiler focuses on pinpointing specific code inefficiencies. JMeter gives a big-picture view, profiling offers a microscopic analysis. Profiling helps me understand which code sections consume the most resources, pinpointing weaknesses like inefficient algorithms or database queries.  IntelliJ Profiler is a powerful tool for identifying bottlenecks, offering visualizations like flame graphs to show exactly where time is spent in my code.

2. Challenges include ensuring profiling reflects real-world conditions and managing the overhead introduced by the profiler itself. To overcome this, I use tools that capture snapshots during normal application execution. 

3. IntelliJ Profiler offers numerous benefits: it integrates seamlessly with my IDE, allows profiling while debugging, and provides detailed reports for targeted optimization.

4. In case of inconsistencies between JMeter and profiling results, it's important to analyze the specific scenarios. Profiling might miss issues that only arise under heavy JMeter load, so I might need to refine my JMeter tests to target the suspected bottlenecks.

5. After profiling and JMeter testing, optimization strategies include refactoring code, improving algorithms, and optimizing database interactions. Unit tests are crucial to ensure changes don't introduce regressions and maintain functionality. 

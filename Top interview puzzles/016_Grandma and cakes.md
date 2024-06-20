**Objective:**
Determine the number of cakes needed to ensure arriving at Grandma's house with exactly two cakes, considering tolls where trolls take and give back cakes.

**Concept:**
Each toll requires giving one cake but gives back one cake. The goal is to calculate the initial number of cakes needed to ensure arriving with two cakes at Grandma's.

**Steps:**
1. **Scenario with Five Bridges:**
   - Start with two cakes.
   - At each bridge, give one cake and receive one cake back, maintaining two cakes throughout the journey.
   - Thus, you need to start with two cakes to arrive at Grandma's with exactly two cakes.

2. **Generalized Solution for Three Bridges:**
   - Assume you start with X cakes.
   - After the first bridge, you have (X/2) + 1 cakes (one given, one received).
   - After the second bridge, you have ((X/2) + 1) / 2 + 1 cakes (half remaining after first bridge, one given, one received).
   - After the third bridge, you have (((X/2) + 1) / 2 + 1) / 2 + 1 cakes (half remaining after second bridge, one given, one received).
   - Set the equation equal to three cakes (required cakes at Grandma's).
   - Solve for X: ((X/2) + 1) / 2 + 1 = 3.
   - Simplify and solve to find X = 10.

**Conclusion:**
For five bridges, start with two cakes to arrive with two cakes. For three bridges, start with ten cakes to arrive with exactly three cakes. This solution can be generalized for any number of bridges and required cakes at Grandma's house.

# Canteen-Queue
Link for the problem: https://www.beecrowd.com.br/judge/en/problems/view/1548

In the school you study, the recreation time is the most awaited time by most of the students. Not just because the classes sometimes are tiring, but because the lunch is very good.

When the recreation alarm sounds, all the students go out running from the class to arrive as early as possible in the canteen, such is the desire to eat. One of your teachers noticed that there was an opportunity there.

Using a reward system, your math teacher decided that the order in which the students will be served will not be given by the arrival time, but by the sum of grades obtained in class. In this way, those with higher grades can be served before those with lower grades.

Your task is simple: given the arrival time of the students in the canteen, and their respective grades in the math class, reorder the queue according to the math grades, and say how many students don't need to change place in this reordering.

Input
The first line contains an integer N, indicating the number of test cases to follow.

Each test case starts with an integer M (1 ≤ M ≤ 1000), indicating the number of students. Following there will be M distinct integers Pi (1 ≤ Pi ≤ 1000), where the i-th integer indicates the grade of the i-th student.

The above integers are given in the arrival order, or in other words, the first integer is from the first student to get to the queue, the second integer is from the second student, and so on.

Output
For each test case print one line, containing one integer, indicating the number of students that don't need to change their places even after the queue being reordered.

Sample Input	
3

3
100 80 90

4
100 120 30 50

4
100 90 30 25

Sample Output

1
0
4

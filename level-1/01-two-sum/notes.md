# 🧠 Reflections & Learning – [Problem Name Here]

📌 **LeetCode Link**: [https://leetcode.com/problems/two-sum/description/]  
🎥 **NeetCode Video**: [https://youtu.be/KLlXCFG5TnA?si=HCvJUVowSfYaqdvp]  
✅ **My LeetCode Solution**: [https://leetcode.com/problems/two-sum/submissions/1719456793]

---

## ✅ Problem Understanding

- What is the problem asking?
so, we have a target eg. 9 and we have find the combination 2 numbers from array which sum up to 9 and then we have to return their indexes! nums[i] + nums[j] == target

- What are edge cases?

    - ✅ [1, 2], target = 3 → Minimum length input
    - ✅ [3, 3], target = 6 → Same number used at different indices
    - ✅ [-3, 4, 1], target = -2 → Negative numbers
    - ✅ [0, 4, 3, 0], target = 0 → Zeros in array
    - ✅ [10^9, -10^9], target = 0 → Large numbers
    - ✅ [1, 2, 3, 4], target = 5 → Multiple valid pairs exist (return any one)
    - ✅ [4, 1, 2, 3], target = 6 → Unsorted input

---

## 🧩 Approach

- Describe the logic in simple words.

Make a map to store numbers and their indexes.
For each number, check if target - number is in the map.
If yes, return their indexes.
Else, store the number with its index.
---

## 💡 Key Insight

- What unlocked the solution for you?
Use of hash Map
---

## 🚫 Mistakes / Stuck Points

- Where did you struggle?
it was easy and understandable
- What will you remember next time?
check if target - number is in the hashMap

---

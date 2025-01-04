# Interview Preparation

This repository contains important theory-based interview questions and answers for Android development and general programming topics.

---

## Theory Questions

### 1. **What is a HashMap?**
A `HashMap` is a data structure in Java that stores key-value pairs. It allows constant-time performance for basic operations like adding, removing, and looking up elements, provided there are no hash collisions.

- **Key Characteristics**:
  - Unordered.
  - Allows one null key and multiple null values.
  - Not thread-safe.

---

### 2. **What is the difference between HashMap and LinkedHashMap?**
- **HashMap**: Unordered and faster due to no maintenance of order.
- **LinkedHashMap**: Maintains the insertion order but is slightly slower.

---

### 3. **What is the time complexity of basic HashMap operations?**
- In the best-case scenario (no hash collisions):
  - **Insert**: O(1)
  - **Search**: O(1)
  - **Delete**: O(1)
- In the worst-case scenario (hash collisions lead to a linked list or tree structure):
  - **Insert/Search/Delete**: O(n) or O(log n) (for tree-based buckets).

---

### 4. **What is the Activity lifecycle in Android?**
The Android activity lifecycle represents the states an activity goes through from creation to destruction. Key methods include:
- **onCreate()**: Called when the activity is first created.
- **onStart()**: Called when the activity becomes visible.
- **onResume()**: Called when the activity starts interacting with the user.
- **onPause()**: Called when the activity goes partially out of view.
- **onStop()**: Called when the activity is no longer visible.
- **onDestroy()**: Called before the activity is destroyed.

---

### 5. **What are some common Android components?**
- **Activities**: Represent a single screen in the app.
- **Services**: Run in the background without a UI.
- **Broadcast Receivers**: Respond to system-wide events.
- **Content Providers**: Manage app data and share it between applications.

---

### 6. **What is the difference between RecyclerView and ListView?**
- **RecyclerView**:
  - More efficient.
  - Supports modern features like item animations and view holders.
  - Requires an adapter and layout manager.
- **ListView**:
  - Simpler but less flexible.
  - Does not support animations natively.

---

## Usage

- Use this repository to revise important theory questions for interviews.
- More questions and answers will be added over time.

---

### Contributions
Feel free to contribute by adding more questions or improving answers.
